# IMDb-Face
A new large-scale noise-controlled face recognition dataset.

By Fei Wang, Liren Chen, Cheng Li, Shiyao Huang, Yanjie Chen, Chen Qian, Chen Change Loy

**IMDb-Face** is the new large-scale noise-controlled dataset for face recognition research. The dataset contains about 1.7 million faces, 59k identities, which is manually cleaned from 2.0 million raw images. All images obtained from IMDb website. The detailed introduction of IMDb-Face can be found in the paper.

We hope that the IMDb-Face dataset could shed lights on the influences of data noise to the face recognition task, and point to potential labelling strategies to mitigate some of the problems. It could serve as a relatively clean data to facilitate future studies of noises in large-scale face recognition.

### Contents
0. [Data Download](#data-download)
0. [Data Statistics](#data-statistics)
0. [Overlap with Face Recognition Benchmarks](#Overlap-with-Face-Recognition-Benchmarks)
0. [Notation](#Notation)
0. [Contact](#Contact)

### Data Download
The IMDb-Face dataset is annotated with face-level labels and bounding boxes. We also give the 3 points face landmarks and head pose information which is generated by our face alignment and head pose estimation algorithms. The detailed information is described below.
1. URL(IMDb-Face.csv)
The IMDb-Face.csv includes name, IMDb index, index of the image, image URLs.
2. Meta information(IMDb-Face_meta-information.csv)
The IMDb-Face_meta-information.csv includes names, index of the image, bounding box of the owner face, 3 points face landmark, head pose.

### Data Statistics
Overall
Total number of images: 1.7M
Total number of identities: 59k
1. Data distribution

2. Head pose distribution

3. Gender distribution

### Overlap with Face Recognition Benchmarks
We have removed the celebrity images which the identification appears in the LFW, Facescrub (MegaFace evaluation images) and YTF based on the name. You can evaluate the face recognition model (trained on IMDb-Face) on these benchmarks directly. 

### Notation
(1) IMDb-Face does not own the copyright of the images. IMDb-Face only provides URLs of images. The images in their original resolutions may be subject to copyright, so we cannot make them publicly available on our server. The dataset is released for non-commercial research and/or educational purposes. 

(2) If you are the celebrity included in the IMDb-Face and you do not want to be included in the dataset, please contact us and we will remove the data base on your request.

### Contact
[Fei Wang](wangfei@sensetime.com)

  Questions can also be left as issues in the repository. 
