# msds-692-moore
MS Data Science Practicum <br>
Eugene Moore moore938@regis.edu

# Title of Project
Malware Image Classification with CNN

## Description
Since 2011[1] malware analysis is beginning to see progress with novel ways through the help of computer vision. Traditionally, security research on malware is a lengthy process resulting in error prone signature detection. In the paper “Malware image classification using one-shot learning with Siamese networks.” An attempt to classify malware similarity with limited samples is presented that might solve two problems. The first of limited sample data and second a way to spot malware “strains”, for lack of a better word. 
I will use this paper as a guide to first reproduce the setup. This will provide a foundation to build on in future work. Given the time frame for this course work I believe a successful project would result in the setting up similar data processing and training networks to what is presented in the paper. Another paper, “Deep multi-task learning for malware image classification.” Presents a more advanced approach that uses multiple data points or tasks to classify malware. The use of color imaging through a custom technique, not presented, could offer better results for the one-shot approach. Time permitting, I will attempt to experiment with this option. Finally, the latest paper researched for this project presents a transfer learning approach. All techniques used to replicate these experiments have been taught and in my course work here at Regis. My main goal of this project is to leverage and demonstrate these techniques. I anticipate challenges at every phase from data selection and collection, data engineering, CNN setup, and transfer learning. I will attempt to follow the basic data science workflow taught at Regis and will no doubt have to curtail some experimentation to complete final analysis of results.

### Research Option 1
In the paper MSIC: Malware Spectrogram Image Classification, published in 2020, the authors experiment with classiifing malware samples transformed into spectorgram images. This is a differnet approach to transforming malware into grey scale images. There is an option to explore classification between grey scale images with compared to spectrogram images.

### Research Option 2
Due to limited malware data sets a research option is might be to explore the ability for a CNN to recognize file types. This might be to distinquish between binary vs text, etc.

## Data Science Task Type
This is an image classification (Computer Vision) task using supervised learning. This project will require data engineering for binary files, transfer learning, and analysis of results.

## Data
Due to the choice of lab I’m attempting to replicate, I do not expect to need a large amount of data since the point of the approach for the scenario is that of limited sample data. Additionally, since the focus of the experiment is on malware, I will first use benign binaries from my local system to establish a data pipeline. Once I have a successful end to end data prep, train, and analysis established, I may use live malware as a final proof of concept. <br> 
Using live malware can be problematic since it will most likely require dedicated hardware in a controlled and disconnected lab which I have access to but may not have time to set up given the course duration.

## Analysis
In the research I’m using as a guide I will be experimenting with CNN networks and transfer learning to perform image classification for binary file samples. 

## Anticipated Difficulties
I think the main difficulty will be obtaining and cautiously working with live malware. This sometimes requires gaining access to samples through a vetting process by private organizations. The next issue will be containing malware which can drive some isolated lab setup which can be time consuming task that are not directly related to the experimentation. Another challenge will be attempting color imaging for binary sample. The idea for this comes from more advanced research in this area, however, the technique for color is not disclosed. From what I can tell it may be a special way of coloring different parts of the original binary that corresponds to areas of malware targets. So, my attempt to coloration, time permitting, will be purely my own experimentation which might prove rewarding.

## Project Timeline
Wk1	Project research, write-up, schedule, and program acceptance <br>
Wk2	Initial data collection, EDA, and data engineering<br>
Wk3	Continued data engineering.<br>
Wk4	CNN setup and initial classification experimentation<br>
Wk5	Continued CNN experimentation, and deep learning approach.<br> 
Wk6	Results analysis.<br>
Wk7	Document practicum <br>
Wk8	Finalize presentation and presentation.<br>

## Reference
1 Hsiao, S.-C., Kao, D.-Y., Liu, Z.-Y., & Tso, R. (2019). Malware image classification using one-shot learning with Siamese networks. Procedia Computer Science, 159, 1863–1871. https://doi.org/10.1016/j.procs.2019.09.358

2 Bensaoud, A., & Kalita, J. (2022). Deep multi-task learning for malware image classification. Journal of Information Security and Applications, 64(103057), 103057. https://doi.org/10.1016/j.jisa.2021.103057

3 Kumar, S., Janet, B., & Neelakantan, S. (2024). IMCNN:Intelligent Malware Classification using Deep Convolution Neural Networks as Transfer learning and ensemble learning in honeypot enabled organizational network. Computer Communications, 216, 16–33. https://doi.org/10.1016/j.comcom.2023.12.036

4 AHMAD AZAB , (Member, IEEE), AND MAHMOUD KHASAWNEH , (Member, IEEE). (2020, June 1). MSIC: Malware Spectrogram Image Classification. Ieee.Org. https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9104999

5 MSIC-Paper: MSIC: Malware Spectrogram Image Classification. (n.d.). Retrieved January 27, 2024, from https://github.com/AhmadAzab/MSIC-Paper

6 Hashemi, M. (2019). Enlarging smaller images before inputting into convolutional neural network: zero-padding vs. interpolation. Journal of Big Data, 6(1). https://doi.org/10.1186/s40537-019-0263-7

7 Pillow in Python won’t let me open image (“exceeds limit”). (n.d.). Stack Overflow. Retrieved January 27, 2024, from https://stackoverflow.com/questions/51152059/pillow-in-python-wont-let-me-open-image-exceeds-limit

8 Ramalingam, A. (2021, June 23). How to Pick the Optimal Image Size for Training Convolution Neural Network? Analytics Vidhya. https://medium.com/analytics-vidhya/how-to-pick-the-optimal-image-size-for-training-convolution-neural-network-65702b880f05


9 Brownlee, J. (2019, January 1). Impact of Dataset Size on Deep Learning Model Skill And Performance Estimates. MachineLearningMastery.Com. https://machinelearningmastery.com/impact-of-dataset-size-on-deep-learning-model-skill-and-performance-estimates/





