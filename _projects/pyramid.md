---
name: Rendering Physically-Based Lens Flares
img: ../imgs/pyramid.png
img_size: 200px
links:
 - name: Code
   value: https://github.com/aatifjiwani/lens-flare
 - name: Website
   value: https://aatifjiwani.github.io/lens-flare/
   last: true
ordering: 0
---
Current methods for producing lens flare distortions are scene-independent, in the sense that they render a flare distortion without regard to the camera viewpoint or position of the sun, and synthetically overlay the distortion onto a scene that had been previously rendered or captured. In this project, we modified a ray-tracing engine to capture infinite light sources in a scene (like the sun), and render the physics-based lens flare distortion that would appear as if the image was taken by a camera. Half of this implementation is based on a Fourier method, and the other half is based on heuristics of light. Unlike some approaches, a rendered lens flare in our approach completely depends on the viewpoint and the location of the light source. 