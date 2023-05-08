📌📌 Industrial-Automation-Technique-Using-Deep-Learning

✅✅ Pen parts detection

Dataseet -> https://app.roboflow.com/spectacle/pen_parts_detection/browse?queryText=&pageSize=50&startingIndex=0&browseQuery=true

PT File -> https://drive.google.com/drive/folders/1a7baey55y07oU-1_5EgLgHFrUzr5A18B

🗄️ ABSTRACT
YOLO stands for 'You only look once', is an object detection algorithm that divides images into a grid system. Each cell in the grid is responsible for detecting objects within itself.

Deep learning has revolutionized some fields of technology in the past few years and is going to touch many others in the near future. One of these could be industrial automation, though traditionally a reluctant environment to adopt new technologies. We propose a novel and robust colour object detection and localization algorithm. Without a priori information about the number of objects, our method can detect all the objects with similar colour features in the template. An SIFT and key points matching algorithm is used to find the object candidate regions. The weighted histogram intersection is used to verify the presence of objects. With the colour feature in the template, our method can detect and locate the objects accurately, get the number of objects, estimate their scales and orientations. Our experimental results on outdoor images obtained under different environments verify the effectiveness of our algorithm

🗄️ Introduction
A few years ago, the creation of the software and hardware image processing systems was mainly limited to the development of the user interface, which most of the programmers of each firm were engaged in. The situation has been significantly changed with the advent of the Windows operating system when the majority of the developers switched to solving the problems of image processing itself. However, this has not yet led to the cardinal progress in solving typical tasks of recognizing faces, car numbers, road signs, analyzing remote and medical images, etc. Each of these "eternal" problems is solved by trial and error by the efforts of numerous groups of engineers and scientists. As modern technical solutions turn out to be excessively expensive, the task of automating the creation of the software tools for solving intellectual problems is formulated and intensively solved abroad. In the field of image processing, the required tool kit should support the analysis and recognition of images of previously unknown content and ensure the effective development of applications by ordinary programmers. Just as the Windows toolkit supports the creation of interfaces for solving various applied problems. Industrial Automation Technique project is based on deep learning, this project included two parts Hardware and Software and based on image detection technique. This automation technique detects the image and as well as gathers the information and data for unique identification of object. This technique usually used in production factory like logistic supply chain companies ,FMCG, Packaging companies etc. This technique is very useful and saves a lot of time and human.

🗄️ MOTIVATION

Initially during the early stage of our project, we thought about what should be the best outcome of deep learning. So, we as a team came up with many project models, then we selected “INDUSTRIAL AUTOMATION USING DEEP LEARNING” . The main motive to select Industrial automation is that this technique will bring a huge revolution in the supply chain industry. This small change in the supply chain industry will help in factories productivity and will save a lot of time This simple technique will omit human errors in the production line . The factory efficiency is also increased as compared to a semiautomated or manually operated factory. The future is technology and we need to adapt to new technology to keep in pace with this fast moving world. This innovation will help factories to keep them updated and help in running efficiently. Companies can go forward with new innovation on their research and development of their product.

🗄️ BACKGROUND

In this project we are working on an Industrial Automation model. In this model we are taking an example of a PEN production industry where different colours of pens are being manufactured in a pen factory. There are four colours that we will consider in our project i.e Red, Yellow, Blue and Black.

After production the pens and its different components come onto the conveyor line. Here the product will come on the conveyor belt. A camera will be fitted at a suitable angle in such a way that the camera will scan each and

every product that passes on the conveyor belt. The camera will detect each and every object and will match it with the image present in its database. First of all we created the database by taking pictures of the four different colours of pen and feeding the system with the required data. The picture was taken from all possible angles. This process is known as annotation. This process is easily explained in the data flow diagram. After this process we came to the second stage where the object identification will take place. We have used the coding platform google colab and the code was done in python. Here the system is coded in such a way that the camera lens will capture the image of a particular pen passing through the conveyor line and will check with the predefined database present in its system. For Example - If a black pen body passes the conveyor line the lens will detect the black pen and match with its database , it will detect the black colour pen body and count that one black pen body is produced at that particular time and store this data in another database. In this way all different parts of the pens are detected i.e pen cap, pen body, pen refill cover and pen refill and the parts are separated from each other with its unique colour. In this way we can collect the total number of pens manufactured in a particular period of time.

🗄️ SUMMARY OF PRESENT WORK

Industrial Automation Technique is a computer vision task that refers to the process of locating and identifying multiple objects in an image. Deep learning algorithms like YOLO V5, SSD and R-CNN detect objects on an image using deep convolutional neural networks, a kind of artificial neural network inspired by the visual cortex.

image

🗄️ The whole process is as follows: • We are going to detect a particular object in this project. We have taken a PEN as an object. • Here we have divided the pen into four different parts namely PEN BODY, PEN CAP, PEN REFILL COVER AND PEN REFILL. • There will be four different colours of pen i.e. RED, YELLOW, BLUE & BLACK. • At first we trained our system by feeding the data of 1500 images of different parts of the pen at various angles. • In our working model there is a conveyor belt that will carry the pen and its parts. • A camera will be fitted at a suitable angle that it can check each and every object. • The camera system will detect the object and will identify each and every specific object. • After detecting the data will be collected and stored in our database.

🗄️ HARDWARE AND SOFTWARE

Software

❖ Python 

❖ Google Colab 

❖ CVAT 

❖ YOLO V5 

❖ Strong SORT 

❖ HTML, CSS, JS, PHP 

❖ PhpMyAdmin

Hardware

❖ Johnson Motor 

❖ 12 Volt adapter 

❖ Rack & Pinion

🗄️ ER Diagram

![image](https://user-images.githubusercontent.com/85603537/236640669-59c6fdfb-761e-49a0-ada8-681956b1465d.png)

🗄️ FLOWCHART

Dataset Flowchart

![image](https://user-images.githubusercontent.com/85603537/236640682-941e0de4-977c-448a-b32a-307948a85a2a.png)


Main Flowchart

![image](https://user-images.githubusercontent.com/85603537/236640695-c3ee7eb1-18cd-427a-ae8e-16256b10c77f.png)


🗄️ AIM OF THE PROJECT

✔ This project is mainly based on Industrial automation technique

✔ In this project we have used a production line of PENs for our reference.

✔ After manufacturing of the pens all pens come in the same conveyor belt unseparated.

✔ Before further process of packaging, the camera fitted over the conveyor belt will detect each and every object and store the data

✔ For example – It will detect a red pen body ,black cap , yellow refill cover and refill .

✔ After that it will keep a count of each and every object in the database for further process.

✔ This will help in accurate output of pens from the factory.

✔ It will remove human errors and improve efficiency of the factory.

🗄️ FUTURE SCOPE The evolution of Industrial Automation has led to the future scope of manufacturing to become autonomous. Moreover, there have been tremendous changes and applications in adopting new technologies, network architectures, and innovations in the devices and systems. Above all, industrial automation and its applications have helped determine the scope and future of many technologies and companies. Hence, here are the top latest trends in Industrial Automation that will shape its future. During this pandemic, manufacturing industries have been hit the most. Hence, they are in dire need of new technologies in the operation processes. That is to say, industrial automation provides advances in digitalization that lead to new processes in automation. Moreover, it digitally transforms manufacturing processes with IT/OT. Hence, manufacturers have an opportunity to convert from “automation” to “autonomous” processes.

🗄️ CONCLUSION In conclusion, industrial automation has led us to develop comprehensive strategies for Industry 4.0. Although, manufacturers would soon have to prepare for the next generation, Industry 5.0. It is a further advanced trend that will focus on personalization and immediate customer service. As a result, it will integrate people with “cobots” or collaborative robots.

🗄️ REFERENCES

https://github.com/ultralytics/yolov5

https://github.com/mikel-brostrom/Yolov5_StrongSORT_OSNet

https://www.makesense.ai/

https://www.tutorialspoint.com/python_deep_learning/index.htm

https://www.udemy.com/course/deeplearning_x/

https://www.mathworks.com/discovery/deep-learning.html

https://wisdomplexus.com/blogs/industrial-automation/

https://www.engpaper.com/deep-learning-ieee-paper.html

https://www.autodesk.com/products/fusion-360/blog/the-role-of-machine-learning-in-industrial-automation/#:~:text=Industrial%20automation%20and%20machine%20learning,handling%20tedious%20time%2Dconsuming%20tasks.

📌📌 Project Pictures & Output:

![image](https://user-images.githubusercontent.com/85603537/236862971-40d5ab3d-46dc-481b-b268-2631e043ad70.png)
![image](https://user-images.githubusercontent.com/85603537/236863061-1e11c098-71f0-4a0a-9536-eebe50e7cd26.png)
![image](https://user-images.githubusercontent.com/85603537/236863280-9538f3f4-ea6a-45df-8af2-52843b7fab8f.png)
![image](https://user-images.githubusercontent.com/85603537/236863141-b37e84a5-876b-4a94-9a99-ede1ab992d39.png)
![image](https://user-images.githubusercontent.com/85603537/236863346-29bca067-cec7-410e-bd95-1d7a6c3812f6.png)
![image](https://user-images.githubusercontent.com/85603537/236863389-42497b47-e3f0-427d-8af4-1a0023bf7a8d.png)
![image](https://user-images.githubusercontent.com/85603537/236863509-69706b51-a6f1-4334-8f97-945d3b056f3d.png)
![image](https://user-images.githubusercontent.com/85603537/236863577-aa7c62bb-a5c1-422a-b748-b07ca8790ac1.png)



