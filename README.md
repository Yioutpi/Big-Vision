# Large-scale-Vision

- SAM: Segment Anything [[`Paper`]](https://arxiv.org/abs/2304.02643) [[`Dataset`]](https://segment-anything.com/dataset/index.html)
  - SA-1B Dataset:
  Total number of images: 11M
  Total number of masks: 1.1B
  Average masks per image: 100
  Average image resolution: 1500×2250 pixels
- ImageNet: A Large-Scale Hierarchical Image Database [[`Paper`]](https://ieeexplore.ieee.org/abstract/document/5206848) [[`Dataset`]](https://www.image-net.org/download.php)
  - This dataset spans 1000 object classes and contains 1,281,167 training images, 50,000 validation images and 100,000 test images. 
- MVImgNet: A Large-scale Dataset of Multi-view Images [[`Paper`]](https://arxiv.org/abs/2303.06042) [[`Dataset`]](https://gaplab.cuhk.edu.cn/projects/MVImgNet/)
  -  It contains 6.5 million frames from 219,188 videos crossing objects from 238 classes, with rich annotations of object masks, camera parameters, and point clouds. 
- Large Scale Visual Food Recognition [[`Paper`]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10019590) [[`Dataset`]](http://123.57.42.89/FoodProject.html)
  - A new large-scale high-quality food recognition benchmark Food2K, which is the largest food image dataset with 2,000 categories and 1,036,564 images
- LogoDet-3K: A Large-scale Image Dataset for Logo Detection [[`Paper`]](https://dl.acm.org/doi/pdf/10.1145/3466780) [[`Dataset`]](https://github.com/Wangjing1551/LogoDet-3K-Dataset)
  -  A new large-scale logo dataset LogoDet-3K1 with 3,000 classes, 194,261 objects and 158,652 images, which is the largest logo classes with full annotation.
- Objects365: A Large-scale, High-quality Dataset for Object Detection [[`Paper`]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Shao_Objects365_A_Large-Scale_High-Quality_Dataset_for_Object_Detection_ICCV_2019_paper.pdf) [[`Dataset`]](http://www.objects365.org/overview.html)
  - Objects365 is a brand new dataset, designed to spur object detection research with a focus on diverse objects in the Wild.
    365 categories
    2 million images
    30 million bounding boxes
- TrackingNet: A Large-Scale Dataset and Benchmark for Object Tracking in the Wild [[`Paper`]](https://openaccess.thecvf.com/content_ECCV_2018/papers/Matthias_Muller_TrackingNet_A_Large-Scale_ECCV_2018_paper.pdf) [[`Dataset`]](https://tracking-net.org/)
  - A Large-Scale Dataset and Benchmark for Object Tracking in the Wild.Large Scale Dataset > 30K Video Sequences, Object Tracking > 14M Bounding Boxes
- YouTube-VOS: A Large-Scale Video Object Segmentation Benchmark [[`Paper`]](https://arxiv.org/pdf/1809.03327.pdf) [[`Dataset`]](https://youtube-vos.org/)
  -   It also has the following features.
    5000+ high-resolution YouTube videos
    90+ semantic categories
    7800+ unique objects
    190k+ high-quality manual annotations
    340+ minutes duration
- DINOv2: Learning Robust Visual Features without Supervision [[`Paper`]](https://arxiv.org/abs/2304.07193) 
  - LVD-142M Dataset: A curated dataset containing 142M images
- JFT-300M: Revisiting Unreasonable Effectiveness of Data in Deep Learning Era [[`Paper`]](https://arxiv.org/abs/1707.02968)
  - An internal Google dataset, containing over one billion labels for the 300M images. Of the billion image labels, approximately 375M are selected via an algorithm that aims to maximize label precision of selected images.
  - V-MoE adopts JFT-300M as its pretraining dataset
  - ViT-22B extends JFT to around 4B images as its pretraining dataset
- YFCC100M: The New Data in Multimedia Research[[`Paper`]](https://arxiv.org/pdf/1503.01817v2.pdf) [[`Dataset`]](https://bit.ly/yfcc100md)
  - The largest publicly and freely useable multimedia collection, containing  the metadata of around 99.2 million photos and 0.8 million videos from Flickr
- Open Images V7: From colouring-in to pointillism: revisiting semantic segmentation supervision[[`Paper`]](https://arxiv.org/pdf/2210.14142v2.pdf) [[`Dataset`]](https://g.co/dataset/open-images)
  - Open Images is a dataset of ~9M images annotated with image-level labels, object bounding boxes, object segmentation masks, visual relationships, and localized narratives. It has 15,851,536 boxes on 600 classes, 2,785,498 instance segmentations on 350 classes, 3,284,280 relationship annotations on 1,466 relationships, 675,155 localized narratives, 66,391,027 point-level annotations on 5,827 classes ,61,404,966 image-level labels on 20,638 classes
---
## Multimodal
- LAION-400M: Open Dataset of CLIP-Filtered 400 Million Image-Text Pairs [[`Paper`]](https://arxiv.org/abs/2111.02114) [[`Dataset`]](https://laion.ai/blog/laion-400-open-dataset/)
  - Number of unique samples 413M
  Number with height or width >= 1024 26M
  Number with height and width >= 1024 9.6M
  Number with height or width >= 512 112M
  Number with height and width >= 512 67M
  Number with height or width >= 256 268M
  Number with height and width >= 256 211M


- Redcaps: Web-curated imagetext data created by the people, for the people  [[`Paper`]](https://arxiv.org/abs/2111.11431) [[`Dataset`]](https://redcaps.xyz/)
  -  12M image-text pairs

- Wukong: A 100 Million Large-scale Chinese Cross-modal Pre-training Benchmark [[`Paper`]](https://arxiv.org/abs/2202.06767) [[`Dataset`]](https://wukong-dataset.github.io/wukong-dataset/)
  - A large-scale Chinese VLP dataset with 100 million image-text pairs, covering a wide range of concepts.

- Conceptual 12M: Pushing Web-Scale Image-Text Pre-Training To Recognize Long-Tail Visual Concepts [[`Paper`]](https://arxiv.org/pdf/2102.08981v2.pdf) [[`Dataset`]](https://github.com/google-research-datasets/conceptual-12m)
  - A dataset with ~12 million image-text pairs meant to be used for vision-and-language pre-trainin