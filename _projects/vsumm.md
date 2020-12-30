---
name: Video Summarization Using REINFORCE
img: ../imgs/flockas.png
img_size: 300px
links:
 - name: Report
   value: ../pdfs/FLOCKAS.pdf
   last: true
ordering: 1
---
With inspiration from [Deep Reinforcement Learning for Unsupervised Video Summarization with Diversity-Representativeness Reward, Kaiyang Zhou et al.](https://arxiv.org/abs/1801.00054), we built a paired unsupervised and supervised pipeline to train a network to select key frames of interest from videos using deep reinforcement learning. Also, we added two custom reward functions:  (1) a time-delta reward that yields high reward for clustering frames in a video summary, and (2) an object-ness reward based on the YoloV3 that encourages the policy to choose frames that may contain an abundance of objects. Our network, coined FLOCKAS, was tested on the SumMe and TVSum video summarization datasets and achieved an F-Score of 45.5% and 58.9% respectively, beating the 
previous benchmark by 4.1% and 1.3% respectively.    

(Code is not released as we are currently still performing further research in this domain)