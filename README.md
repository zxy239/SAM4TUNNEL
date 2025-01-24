# SAM4Tun

**Oct 9, 2024**

This is a repo for paper of "SAM4Tun: No-Training Model for Tunnel Lining Point Cloud Component Segmentation" 

In this paper, we propose SAM4Tun, a zero-shot automated instance segmentation method for tunnel lining segments. It is based on a Large Vision Model (LVM), prompt-based Segment Anything Model (SAM), and various point cloud and image processing techniques, enabling accurate instance segmentation  without requiring any training. The precess starts by unfolding tunnel point clouds to generate 2D panoramic images, enabling SAM to be extend its capabilities to point cloud segmentation. To enhance performance, we propose: (i) a local point cloud density-variation method to filter out non-segment parts, and (ii) a geometry feature-guided multi-step point cloud up-sampling method to address uneven point cloud density during projection. Then, we focus on prompt engineering, using traditional image processing techniques to automatically generate template prompt, enabling SAM's zero-shot ability to achieve precise instance-level segmentation of tunnel linings. The results demonstrate that our no-training model achieved highly accurate instance segmentation, even surpassing supervised learning algorithms. The proposed method addresses the issue of data dependency and serves as the foundation for component-level damage localization and displacement monitoring in tunnel.

We have organized all the steps in the code using Jupyter Notebook, corresponding directly to the descriptions in the paper. The example uses a partial tunnel point cloud for demonstration (Link for point cloud: https://pan.baidu.com/s/1xKhXnGi5pvASqSuDlKj_dA?pwd=adhx key: adhx). Many functions in the code can be reused for research related to tunnels.

Welcome to have a chat with us if you have any question.

**Update on Nov 4, 2024**

Now we have preprint version:

Ye, Zehao and Lin, Wei and Faramarzi, Asaad and Xie, Xiongyao and Ninić, J., Sam4tun: No-Training Model for Tunnel Lining Point Cloud Component Segmentation. Available at SSRN: https://ssrn.com/abstract=5009016 or http://dx.doi.org/10.2139/ssrn.5009016 

**Update on Jan 24, 2025**

Now paper is online, and accepted by Tunnelling and Underground Space Technology
https://doi.org/10.1016/j.tust.2025.106401
