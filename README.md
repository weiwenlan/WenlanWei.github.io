# Wei Wenlan
an  junior undergraduate student at [Wuhan University](https://en.whu.edu.cn/)
#### **wwl999@whu.edu.cn**
#### **+86 13693092812| weiwenlan1999@gmail.com**

![image](/IMG_4245_di.jpg)


# PERSONAL
-	**GPA**: 3.70/4.00 (rank top **5%**); 
-	TOFEL 104( Read:28, Listen:28, **Speak:23**, Write:25)14/7/2020                                             
- **GRE 322**(V:154 Q:168)                              9/20/2019
- Computer Skills:
    -	Programming : C/C++, **Python**, TensorFlow, **Pytorch**
    -	Software: **MATLAB**, Multisim 
    -	Documentation:**Latex**, MS Office
- Experiment Skill: PCB board welding, Fiber cleaving and welding
-	Course experience
    - Computer Vision **(4.0/4.0)**
    - Machine Learning **(4.0/4.0)**
    - Robotic Vision **(4.0/4.0)**
    - Data Structure and Algorithms **(4.0/4,0) (97/100)** 
    - Artificial Intelligence **(4.0/4,0)**
    - Communication Theory **(4.0/4,0) 97/100**
    - Linear algebra **(4.0/4,0) 95/100**


# EDUCATION
* **B.Eng. in Electronic Information Engineering** , [Electronic Information School, Wuhan University](http://eis.whu.edu.cn/index.shtml)
*Sept 2017 - present*
* **Assistant researcher** in [Digtal Signal Process Lab, Wuhan University](http://dsp.whu.edu.cn/)
*Nov 2017 - present*
* **Team Leader** in [Imperial College London](https://www.imperial.ac.uk/)
*Jul. 2019 – Aug. 2019*

# AWARDS
## PATENT
1. **A Method to Construct Natural Scene Data Set Suitable for Computer Vision**
2.	**A Method for Image Super-resolution Reconstruction based on Lightweight Network**

## PAPER
**Lightweight Image Super-Resolution with Mobile Share-Source Network in IEEE Access, vol. 8, pp. 60008-60018, 2020, doi: 10.1109/ACCESS.2020.2983079.** [[**PDF**](https://github.com/weiwenlan/weiwenlan.github.io/blob/master/access.pdf)][[**LINK**](https://ieeexplore.ieee.org/abstract/document/9045996)]

## PRIZE
* [**"Best over all Prize"**](https://github.com/weiwenlan/weiwenlan.github.io/blob/master/%E8%AF%81%E4%B9%A61.pdf) in Summer research in Imperial College London Sep.2019
* **the Second Prize of the 5th China Internet Innovation and Entrepreneurship Competition.** Oct.2019
* **"The Second Prize Scholarship of Students"** Oct.2018
* **"The Third Prize Scholarship of Students"** Oct.2018
* National Computer Test(Brand Two: Python Language Programming)
* **The LuoJia Outstanding Exchange Scholarship** Oct.2019

# WORK AND RESEARCH EXPERIENCE

## University of California San Diego,Electrical and Computer Engineering
Mar. 2020 – Jul.2020

Because of the COVID-19, I have applied for the remote summer research and thanks to the [Prof. Xie](https://sites.google.com/site/pengtaoxie2008/) who offers me this opportunity. Also, I want to thanks to [Dr. He](https://jkooy.github.io/) who works with me and render lots of assistances to me. In three months, I mainly put my efforts in two projects.

### DenseUNet 3D and COVID-19 Database
In this project, Prof. Xie asked me to apply DenseUnet 3D with open source COVID-19 database. This task is aim to use Neural network to distinguish tissues with **inflammation in lung**. I learned about how to deal with the **medical images** which contains depth information, including dicom, mhd and Nifti. It is also fresh knowledge that how to generate masks and labels them with Neural Network. Various kinds of method are used to enhance images, setting thresholds and cropping , I finally completed whole experiment with the standard IOU 0.63 and DICE Coeff 0.68 on the CUDA platform.
![image](/mask.png)
### Medical Visual Question Answering
After the implementation of DenseUnet, Prof. Xie let me work with Dr. He on the task of VQA network. This work is mainly aim to build up an open source database which contains assorted questions and answers for further training.  I have hone my ability in dealing with practical problems.
- I have wrote a **crawler** to grab both images and captions from open source website, textbooks and public database. **More than 20000** images and their captions are being collected. I use Beautiful Soup to generate a parser to access the urls and tags of the images on the website pages, both asynchronous loading and synchronous loading.
- For the captions, we need to generate appropriate questions to make them a question-answer pair.  We perform **language processing** of the captions using the Stanford CoreNLP toolkit, including sentence split, tokenization, part-of-speech (POS) tagging, constituent parsing, and dependency parsing.
- After data being collected, I put my efforts in the VQA network from which we want to check how some of state of art networks perform on the new dataset. I have researched a bunch of networks, including Pythia, Lxmert, OpenVQA, DFAF and so on. I choose **LXMERT** to perform all functions. As the LXMERT is a network with encoders and decoders, it requires all images and QA pairs are encoded to enhance the speed of training. So I first use Faster RCNN to extract features and bboxes on remote server. Then I modified all answers and numbered them in a proper and unique form. Once the data loader was adjusted, I finally applied LXMERT on the X-ray dataset( a relative smaller one we created) and got the **F1 0.6977.**
![image](/VQA.png)

**Due to the ban from the US government, our collaboration was forced to be eliminated.**

## Imperial College, Computer Department - Research on Robotic arm 
Jul. 2019 – Aug. 2019
**Leader** 
### GOAL
- For one month, students are trying to work out a program on the **hardware platform of a 3d camera and a robotic arm.**

### Trash Classify system: 
-	Our group is trying to build a system including: **the interface, the cloud server and the hardware** to classify waste. We finally finished a system which is able to *sort various kinds of daily waste* by using the camera sorting and providing location and the robotic arm grabbing and putting it in the right area. The disparate calculation and the object detection were used to help building up the whole system.
-	As the **leader** of the group, I mainly dealt with the **object detection** part which was closed to my past research experience. I was also in charge of the *whole team ‘s pace and allocated everyday’s work* to ensure we were on the right track to our goal and exerted the strength of my group members. At the final, I made a **video** to fully show our hardworking result and acted as the speaker of the group as well. 
-	We awarded the **Best Overall Prize** in the end, judgement made by the **Prof. Guangzhong Yang**, Deputy Chairman of the Institute of Global Health Innovation, Imperial College London, UK.

### [More Details with the code and Final Project.](https://github.com/weiwenlan/Trash-classification-robotic-arm)

![image](/ic.jpg)



## Wuhan University, Signal Processing Lab - Research on Bio-Image
Jul. 2019 – Oct.2019
**Assistant Researcher** 
* In this project, we are trying to build up a system to **identify the cervical artery plaques by using the computer vision technology** with the ultrasound machines. To accomplish the project, we cooperate with the ZhongNan Hospital.
* We won **the Second Prize of the 5th China Internet Innovation and Entrepreneurship Competition.** 

## Wuhan University, Signal Processing Lab - Research on Image project
Sep. 2018 – Present
**Assistant Researcher** 
-	Put efforts in computer vision including various fields: **Image Retrieval, Image Super-Resolution, Object Detection etc**.

### Image Retrieval System: 
**Member**
-	System is used to analyze the location of the object from several images.
-	I mainly took the responsibility of **image retrieval part** with training and network building. With the help of my teammates, we built a small database and trained an own retrieval network. During this program, I applied for **2 patents and a software copyright** for my network.

### Research on Super Resolution Reconstruction Technology for Mobile: 
**Leader**
-	We intend to design a new network which is suitable for the portable devices and also combined with an app that enables users could lunch the **super resolution** network.
-	This is a program financed by **the National Innovation and Entrepreneurship Training Program** in which I am the leader of the group. I am in charge of the whole team’s pace, **the speech and the essay writing**. I also did a lot of work to apply for the fund including the writing of the application and the speech to show the feasibility of our research.
-	Besides the management work, I am mainly in charge of the **network building**. We are trying to post a paper for this project.

![image](/%E5%9B%BE%E7%89%87%201.png)

# LEADERSHIP AND COMMUNITY ACTIVITIES
*Student Union of college*
Sep. 2017 – Sep. 2018
- Work in the **secretariat** which is mainly responsible for the organization and management of whole student union ‘s several departments as a whole.
-	**Organize events** such as meeting for all members of school union and supervise their daily activities.

