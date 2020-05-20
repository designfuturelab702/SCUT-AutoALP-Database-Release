SCUT-AutoALP-Database-Release
===
A diverse benchmark database (Size =583MB) for layout generation tasks and parsing tasks of floor plan/urban plan is now released jointly by School of Electronic and Information Engineering and School of Architecture of South China University of Technology. The database can be downloaded through the following links :

* Download link1 (faster for people in China):

https://pan.baidu.com/s/14LWNqeri6t9a_IUEoavS6Q (password: 3uq4)

* Download link2 (faster for people in other places):

https://drive.google.com/open?id=1u8bM3wsMRbDItnlr_-VKZmUbb-9Umevv

1 Description
---
The dataset SCUT-AutoALP containing 602 samples and dense labels, which is flexible for multi-paradigm automatic architectural layout parsing with diverse tasks (prediction/geneartion), labels (layout/boundary/attribute) and applications (floor plan/urban plan).

2 Database Construction
--
SCUT-AutoALP Dataset contains totally 602 samples with dense labels (annotated by architectural designers), which can be divided into two subsets.![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/Fig.2.jpg)

Subset-I is for floor plan design, which contains 300 residential floor plan images.The original samples were collected from ”lianjia” website, and that with obvious drawing errors has been eliminated. All the cleaned samples were resized by 1: 100, and the final samples were placed on 20cm×20cm white background images. For layout parsing, we use different RGB color block to denote different regions for boundary label and layout label, as shown in Fig. 2a. Since all the drawing images were resized with the same scale, each of the region was labelled with the corresponding area for attribute prediction.

Subset-II is for urban plan design, which contains 302 urban plan images of primary school campus. The original samples were collected from internet, like websites of architectural design or government. All the cleaned samples were resized by 1: 1800, and the final samples were placed on 24cm×24cm white background images. For layout parsing, we use different RGB color block to denote different regions for boundary label and layout label, as shown in Fig. 2b. For attribute prediction, we annotate each the regions with building area, and estimate building density and floor area ratio for attribute prediction.

3 Applications
--
With different combination of samples and labels, SCUT-AutoALP is available for different applications. For example, boundary label and layout label allow interior plan generation![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/Fig.8.png); samples and layout labels allow image-to-image layout recognition![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/Fig.9.png). 

4 Benchmark Analysis
--
Fig. 3![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/Fig.3.png) shows labels of boundary and layout for different samples. We analyzed the statistical variances of samples and different labels in SCUT-AutoALP. The evaluation results are shown in the following.![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/Fig.4.png) ![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/Fig.5.png) ![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/Table2.png) Please refer to our paper for more details.

5 Layout Parsing of SCUT-AutoALP
--
We evaluated SCUT-AutoALP for different layout parsing tasks, including interior plan generation, or layout recognition/generation.Based on SCUT-AutoALP, different combination of sample or labels can be used for different layout parsing tasks. 

![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/Fig.8.png) ![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/1%20interior%20plan%20generation%20for%20FP.jpg) ![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/2.%20interior%20plan%20generation%20for%20UP.jpg) shows the results of interior plan generation for floor/urban plan, which takes layout label as output ground-truth, boundary label as input condition. ![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/Fig.9.png) ![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/3.%20layout%20generation.jpg) ![image](https://github.com/designfuturelab702/SCUT-AutoALP-Database-Release/blob/master/4.%20layout%20recognition.jpg) shows the results of layout recognition/generation for floor plan, which takes layout label/sample as output ground-truth, sample/layout label as input condition.

And the results (Size = 3.46MB) can be downloaded through the following link:

* Download link1 (faster for people in China):

https://pan.baidu.com/s/1Ww54e12uGnNocA35Wl2-GQ (password: nmwc)

* Download link2 (faster for people in other places):

https://drive.google.com/open?id=1CiObapGiDtBZyEQR-HMP-d0Ts0AN1UQI

6 Contact
--
We are grateful to Professor Yubo Liu（liuyubo@scut.edu.cn）, Associate Professor Qiaoming Deng（dengqm@scut.edu.cn） and Associate Professor Lingyu Liang（lianglysky@gmail.com） for their deep insights. They not only promoted interdisciplinary cooperation, but also provided general ideas and macro guidance for the research.

Yangting Lai (laiyangtinglynne@qq.com) led the overall design and planning of the database, while Jianyong Chen () provided major algorithm and technical support and patiently answered our questions. Wenqiang Lin (857813742@qq.com) provided helpful suggestions on database creation.We also thank the students from the School of Architecture and the School of Telecommunications for their hard work in this study. 

Note: The SCUT-AutoALP-Database-Release can be only used for non-commercial research purpose.

For any questions about this database please contact the authors by sending email to designfuturelab702@scut.edu.cn and lianglysky@gmail.com.

Desclaimer
--

The dataset is for academic research use only. We are not responsible for the objectivity and accuracy of the proposed dataset.
