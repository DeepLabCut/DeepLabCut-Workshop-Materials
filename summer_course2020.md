## Got Behavior? Get Poses ...  <img src="https://images.squarespace-cdn.com/content/v1/57f6d51c9f74566f55ecf271/1572296495650-Y4ZTJ2XP2Z9XF1AD74VW/ke17ZwdGBToddI8pDm48kMulEJPOrz9Y8HeI7oJuXxR7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QPOohDIaIeljMHgDF5CVlOqpeNLcJ80NK65_fV7S1UZiU3J6AN9rgO1lHw9nGbkYQrCLTag1XBHRgOrY8YAdXW07ycm2Trb21kYhaLJjddA/DLC_logo_blk-01.png?format=1000w" width="350" title="DLC-live" alt="DLC LIVE!" align="right" vspace = "50">

This document is an outline of resources for an informal "spring/summer course" for those wanting to learn to use DeepLabCut while responsibly isolating due to COVID-19. We expect it to take *roughly* 1-2 weeks to get through alone, or you can join the course and it will be spread out over 3 weeks.


**UPDATE:** We will also be organzing a "structured" version with a kick-off webinar (**JUNE 5TH!**), then a weekly meeting (for 3 weeks) to have Q & A style discussions with the core development team! 

(emails have been sent out)


:purple_heart: Anyone (i.e. webinar participants or not): we would also be very excited if you contributed to the newly launched DeepLabCut Model Zoo while you learn! Namely, you can learn to use DeepLabCut on data that can be used to build better community tools!! Please contact us in this form if you are interested: https://forms.gle/KRtdKKYB57ZkaBwH7 :purple_heart:

www.deeplabcut.org 

You can also chat with one another on Gitter or Twitter:
[![Gitter](https://badges.gitter.im/DeepLabCut/community.svg)](https://gitter.im/DeepLabCut/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Twitter Follow](https://img.shields.io/twitter/follow/DeepLabCut.svg?label=DeepLabCut&style=social)](https://twitter.com/DeepLabCut)



## Quick Start: (before the kick-off)

You need: Anaconda for python3 and DeepLabCut installed (CPU version)
- you should have a [CPU version of DeepLabCut installed on your laptop](https://github.com/AlexEMG/DeepLabCut/blob/master/conda-environments/README.md). We will assume you don't all have GPUs at home, so we will 
utilize cloud-computing resources for those steps. 

- **WATCH:** overview of conda:  [Python Tutorial: Anaconda - Installation and Using Conda](https://www.youtube.com/watch?v=YJC6ldI3hWk)

 - **ACTION:** [Install DeepLabCut](https://github.com/AlexEMG/DeepLabCut/blob/master/docs/installation.md)

## Outline:

### **The basics of computing in Python, terminal, and overview of DLC:**

- **Learning:** Using the program terminal / cmd on your computer: [Video Tutorial!](https://www.youtube.com/watch?v=5XgBd6rjuDQ)

- **Learning:** although minimal to no Python coding is required (i.e. you could use the DLC GUI to run the full program without it), here are some resources you may want to check out. [Software Carpentry: Programming with Python](https://swcarpentry.github.io/python-novice-inflammation/)

- **Learning:** learning and teaching signal processing, and overview from Prof. Demba Ba [talk at JupyterCon](https://www.youtube.com/watch?v=ywz-LLYwkQQ)

- **Learning:** Watch a talk from Alexander Mathis (a lead DeepLabCut developer) [talk about DeepLabCut!](https://www.youtube.com/watch?v=ZjWPHM0sL4E)

- **DEMO:** Can I DEMO DEEPLABCUT (DLC) quickly? 
    - Yes: [you can click through this DEMO notebook](https://colab.research.google.com/github/AlexEMG/DeepLabCut/blob/master/examples/COLAB_DEMO_mouse_openfield.ipynb)
    - AND follow along with me: [Video Tutorial!](https://www.youtube.com/watch?v=DRT-Cq2vdWs)
    

- **WATCH:** How do you know DLC is installed properly? (i.e. how to use our test script!) [Video Tutorial!](https://youtu.be/IOWtKn3l33s)


<img src="https://images.squarespace-cdn.com/content/v1/57f6d51c9f74566f55ecf271/1587608364285-A8R2F24K4DCP0KLAYI91/ke17ZwdGBToddI8pDm48kOhrDvKq54Xu9oStUCFZX0R7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z4YTzHvnKhyp6Da-NYroOW3ZGjoBKy3azqku80C789l0p4XabXLlNWpcJMv7FrN_NLe3GEN018us8vX03EdtIDHsW7dEh7nvL5CemxAxOy1gg/EKlIEXyXUAE0cy3.jpeg?format=1000w" width="350" title="DLC" alt="review!" align="right" vspace = "50">

- **REVIEW PAPER:** The state of animal pose estmiation w/ deep learning i.e. "Deep learning tools for the measurement of animal behavior in neuroscience" [arXiv](https://arxiv.org/abs/1909.13868) & [published version](https://www.sciencedirect.com/science/article/pii/S0959438819301151)


- **WATCH:** There are a lot of docs... where to begin: [Video Tutorial!](https://www.youtube.com/watch?v=A9qZidI7tL8) 

### **Module 1: getting started on data**

**What you need:** any videos where you can see the animals/objects, etc. 
You can use our demo videos, grab some from the internet, or use whatever older data you have. Any camera, color/monchrome, etc will work. Find diverse videos, and label what you want to track well :) 
- IF YOU ARE PART OF THE COURSE: you will be contributing to the DLC Model Zoo :smile:

:purple_heart: **NOTE:** if you want to contribute back to community-science, please get in touch with us as we have a LOT of data we want to label to be able to share back with everyone; So, if you want to help sign up here (labeling can be on data we provide or possibly yours): https://forms.gle/KRtdKKYB57ZkaBwH7 :purple_heart:
    
   - **Slides:** [Overview of starting new projects](https://github.com/DeepLabCut/DeepLabCut-Workshop-Materials/blob/master/part1-labeling.pdf)
   - **READ ME PLEASE:** [DeepLabCut, the science](https://rdcu.be/4Rep)
   - **READ ME PLEASE:** [DeepLabCut, the user guide](https://rdcu.be/bHpHN)
   - **WATCH:** Video tutorial 1: [using the Project Manager GUI](https://www.youtube.com/watch?v=KcXogR-p5Ak)
     - Please go from project creation (use >1 video!) to labeling your data, and then check the labels!
   - **WATCH:** Video tutorial 2: [using the Project Manager GUI for multi-animal pose estimation](https://www.youtube.com/watch?v=Kp-stcTm77g)
     - Please go from project creation (use >1 video!) to labeling your data, and then check the labels!
   - **WATCH:** Video tutorial 3: [using ipython/pythonw (more functions!)](https://www.youtube.com/watch?v=7xwOhUcIGio)
      - multi-animal DLC: [labeling](https://www.youtube.com/watch?v=Kp-stcTm77g)
      - Please go from project creation (use >1 video!) to labeling your data, and then check the labels!
      
   - **June 5th RECAP: AFTER LABELING (ACTION/WATCH):**
      - IF YOU LABELED FOR THE MODEL ZOO, [please upload your labeled data here!!](https://docs.google.com/forms/d/e/1FAIpQLSf0z6CWihGOxBUiALpN-ms4hr42xHNPAbvfeI3WxZRbEk9Reg/viewform)
      - Once you label on your laptop and you want to train on the cloud, please upload your project folder to google drive, and then use this [COLAB NOTEBOOK](https://github.com/DeepLabCut/DeepLabCut/blob/master/examples/COLAB_YOURDATA_TrainNetwork_VideoAnalysis.ipynb) for single animal projects/model zoo, etc; and this [COLAB NOTEBOOK](https://github.com/DeepLabCut/DeepLabCut/blob/master/examples/COLAB_maDLC_TrainNetwork_VideoAnalysis.ipynb) if you have a multi-animal project to create a training set, train, and start evaluating. 
      - [VIDEO on using COLAB with your data](https://www.youtube.com/watch?v=qJGs8nxx80A)
      

### **Module 2: Neural Networks**
 
   - **Slides:** [Overview of creating training and test data, and training networks](https://github.com/DeepLabCut/DeepLabCut-Workshop-Materials/blob/master/part2-network.pdf)
   - **READ ME PLEASE:** [What are convolutional neural networks?](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53) 
   
   - **READ ME PLEASE:** Here is a new paper from us describing challenges in robust pose estimation, why PRE-TRAINING really matters - which was our major scientific contribution to low-data input pose-estimation - and it describes new networks that are availble to you. [Pretraining boosts out-of-domain robustness for pose estimation](https://paperswithcode.com/paper/pretraining-boosts-out-of-domain-robustness)
   
       - **MORE DETAILS:** ImageNet: check out the original paper and dataset: http://www.image-net.org/ (link to [ppt from Dr. Fei-Fei Li](http://www.image-net.org/papers/ImageNet_2010.ppt))
   
  Before you create a training/test set, please read/watch:
   - **More information:** [Which types neural networks are available, and what should I use?](https://github.com/AlexEMG/DeepLabCut/wiki/What-neural-network-should-I-use%3F)
   - **WATCH:** Video tutorial 1: [How to test different networks in a controlled way](https://www.youtube.com/watch?v=WXCVr6xAcCA)
     - Now, decide what model(s) you want to test. 
        - IF you want to train on your CPU, then run the step `create_training_dataset`, in the GUI etc. on your own computer. 
        - IF you want to use GPUs on google colab, [**(1)** watch this FIRST/follow along here!](https://www.youtube.com/watch?v=qJGs8nxx80A) **(2)** move your whole project folder to Google Drive, and then [**use this notebook**](https://github.com/AlexEMG/DeepLabCut/blob/master/examples/COLAB_YOURDATA_TrainNetwork_VideoAnalysis.ipynb)
   

### **Module 3: Evalution of network performance**
 
   - **Slides** [Evalute your network](https://github.com/DeepLabCut/DeepLabCut-Workshop-Materials/blob/master/part3-analysis.pdf)
   - **WATCH:** [Evaluate the network in ipython](https://www.youtube.com/watch?v=bgfnz1wtlpo)
      - why evaluation matters; how to benchmark; analyzing an video and using scoremaps, conf. readouts, etc.
   
### **Module 4: Scaling your analysis to many new videos**
 
   - [Analyzing videos in batches, over many folders, setting up automated data processing](https://github.com/DeepLabCut/DLCutils/tree/master/SCALE_YOUR_ANALYSIS) 
  
  - How to automate your analysis in the lab: [datajoint.io](datajoint.io), Cron Jobs: [schedule your code runs](https://www.ostechnix.com/a-beginners-guide-to-cron-jobs/)
### **Module 5: Got Poses? Now what ...**
 
   - [Helper code and packages for use on DLC outputs](https://github.com/DeepLabCut/DLCutils)
   
   - Course subscribers, we will go into depth on several ways to analyze your data. Please sign up! :smile:
   


*compiled and edited by Mackenzie Mathis*
