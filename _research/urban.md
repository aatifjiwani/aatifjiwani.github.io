---
title: A Semantic Segmentation Network for Urban-Scale Building Footprint Extraction Using RGB Satellite Imagery
authors: Shubhrakanti Ganguly, Chao Ding, Nan Zhou, David M. Chan
img: ../imgs/urban.jpg
cite: Preprint arXiv:2104.01263 (In Submission)
paper_link: https://arxiv.org/pdf/2104.01263
code_link: https://github.com/aatifjiwani/rgb-footprint-extract
img_size: 250px
ordering: 0
---
Urban areas consume over two-thirds of the world's energy and account for more than 70 percent of global CO2 emissions. As stated in IPCC's Global Warming of 1.5C report, achieving carbon neutrality by 2050 requires a scalable approach that can be applied in a global context. Conventional methods of collecting data on energy use and emissions of buildings are extremely expensive and require specialized geometry information that not all cities have readily available. High-quality building footprint generation from satellite images can accelerate this predictive process and empower municipal decision-making at scale. However, previous deep learning-based approaches use supplemental data such as point cloud data, building height information, and multi-band imagery - which has limited availability and is difficult to produce. In this paper, we propose a modified DeeplabV3+ module with a Dilated ResNet backbone to generate masks of building footprints from only three-channel RGB satellite imagery. Furthermore, we introduce an F-Beta measure in our objective function to help the model account for skewed class distributions. In addition to an F-Beta objective function, we incorporate an exponentially weighted boundary loss and use a cross-dataset training strategy to further increase the quality of predictions. As a result, we achieve state-of-the-art performance across three standard benchmarks and demonstrate that our RGB-only method is agnostic to the scale, resolution, and urban density of satellite imagery.