# msds-692-moore
MS Data Science Practicum <br>
Eugene Moore moore938@regis.edu
# Title of Project
TBD
## Description
Since 2011[1] malware analysis is beginning to see progress with novel ways through the help of computer vision. Traditionally, security research on malware is a lengthy process resulting in error prone signature detection. In the paper “Malware image classification using one-shot learning with Siamese networks.” An attempt to classify malware similarity with limited samples is presented that might solve two problems. The first of limited sample data and second a way to spot malware “strains”, for lack of a better word. 
I will use this paper as a guide to first reproduce the setup. This will provide a foundation to build on in future work. Given the time frame for this course work I believe a successful project would result in the setting up similar data processing and training networks to what is presented in the paper. Another paper, “Deep multi-task learning for malware image classification.” Presents a more advanced approach that uses multiple data points or tasks to classify malware. The use of color imaging through a custom technique, not presented, could offer better results for the one-shot approach. Time permitting I will attempt to experiment with this option.
## Data Science Task Type
This is an image classification (Computer Vision) task using supervised learning.
## Data
Due to the choice of lab I’m attempting to replicate, I do not expect to need a large amount of data since the point of the approach for the scenario is that of limited sample data. Additionally, since the focus of the experiment is on malware, I will first use benign binaries from my local system to establish a data pipeline. Once I have a successful end to end data prep, train, and analysis established, I may use live malware as a final proof of concept. <br> 
Using live malware can be problematic since it will most likely require dedicated hardware in a controlled and disconnected lab which I have access to but may not have time to set up given the course duration.
## Analysis
In the research I’m using as a guide I will be setting a Siamese network configuration for two CNN networks. 
## Anticipated Difficulties
I think the main difficulty will be obtaining and cautiously working with live malware. This sometimes requires gaining access to samples through a vetting process by private organizations. The next issue will be containing malware which can drive some isolated lab setup which can be time consuming task that are not directly related to the experimentation. Another challenge will be attempting color imaging for binary sample. The idea for this comes from more advanced research in this area, however, the technique for color is not disclosed. From what I can tell it may be a special way of coloring different parts of the original binary that corresponds to areas of malware targets. So, my attempt to coloration, time permitting, will be purely my own experimentation which might prove rewarding.
## Project Timeline
TBD
## Reference
1 Hsiao, S.-C., Kao, D.-Y., Liu, Z.-Y., & Tso, R. (2019). Malware image classification using one-shot learning with Siamese networks. Procedia Computer Science, 159, 1863–1871. https://doi.org/10.1016/j.procs.2019.09.358

2 Bensaoud, A., & Kalita, J. (2022). Deep multi-task learning for malware image classification. Journal of Information Security and Applications, 64(103057), 103057. https://doi.org/10.1016/j.jisa.2021.103057




