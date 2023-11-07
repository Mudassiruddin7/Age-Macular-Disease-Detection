![Hello](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExOHU5YnRwZ3J5aDY3a242aWRwZXRzdG5pbnRuOGJ2dTF1eHM4djZnbiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/fRMjhlutjykSs/giphy.gif)

# _**Age Related Macular Disease Detection Using CNN**_
Age Related Macular Degeneration is a type of eye disease which normally affects the central vision of a person. This Disease might sometimes lead to permanent vision loss in some persons and mostly this might affect the people who are aged above 50. This disease doesn’t lead to permanent vision loss but it will definitely impact the peripheral vision. So, basically there are 2 different types of ARMD i.e., Dry and Wet, Dry ARMD will generate a tiny amount of protein deposits called drusen, whereas Wet ARMD occurs whenever any abnormal blood vessel is developed under the retina, so sometimes this blood vessels might leak blood fluid, this type of ARMD is very severe and can even lead to severe permanent central vision loss.

# _**Base Paper**_
+ https://www.researchgate.net/publication/325435611_Age-related_Macular_Degeneration_detection_using_deep_convolutional_neural_network

# _**Algorithm Description**_
So, we have used **Convolutional neural networks** to identify whether a person has brain tumour or not, as we all know, how sophisticated CNNs are and how they can learn almost anything like a brain does, this can help us save a lot of time and also giving almost accurate predictions for the disease. As we discussed convolutional neural networks are very sophisticated and more advanced version of neural networks, these are very superior to other neural networks which works better with images and audio/speech input signal. A CNN network comprises of 3 important layers such as a convolutional layer, pooling layer and fully connected layer. we can have as many layers as possible depending on the domain and project we are working on.

**Reference:**

+ https://www.researchgate.net/figure/Neural-Network-architecture-Reference-http-cs231ngithubio-neural-networks-1_fig11_325359390

+ https://www.ibm.com/cloud/learn/convolutional-neural-networks

# _**How to Execute?**_
So, before execution we have some pre-requisites that we need to download or install i.e., anaconda environment, python and a code editor.

**Anaconda**: Anaconda is like a package of libraries and offers a great deal of information which allows a data engineer to create multiple environments and install required libraries easy and neat.

**Download link:**

![Anaconda](https://1.bp.blogspot.com/-UJ1Ws2zZ9V4/TtMbG2ynJiI/AAAAAAAABbM/m6t2kuEhKdY/s1600/The-biggest-anaconda-snake-3.jpg)

https://www.anaconda.com/

**Python**: Python is a most popular interpreter programming language, which is used in almost every field. Its syntax is very similar to English language and even children and learning it nowadays, due to its readability and easy syntax and large community of users to help you whenever you face any issues.

**Download link:**

![Python](https://i0.wp.com/reptileworldfacts.com/wp-content/uploads/2019/05/male-blonde-super-tiger-reticulated-python.jpg?resize=351%2C351&ssl=1)

+ https://www.python.org/downloads/

**Code editor**: Code editor is like a notepad for a programming language which allows user to write, run and execute program which we have written. Along with these some code editors also allows us to debug, which usually allows users to execute the code line by line and allows them to see where and how to solve the errors. But I personally feel visual code is very good to work with any programming language and makes a great deal of attachment with user.

**Download links:**

![Vs code](https://schwabencode.com/contents/logos/VS2019-Badge.png) ![Pycharm](https://i0.wp.com/scracked.com/wp-content/uploads/2020/01/PyCharm-2019.3.4-Crack.png?fit=200%2C200&ssl=1)

+ https://code.visualstudio.com/Download, 
+ https://www.jetbrains.com/pycharm/download/#section=windows

# _**Steps to execute**_
**Note:** Make sure you have added path while installing the software’s.
1. Install the prerequisites mentioned above.
2. open anaconda prompt and create a new environment.
  - conda create -n "env_name"
  - conda activate "env_name"
3. Install necessary libraries from requirements.txt file provided.
4. Run pip install -r requirements.txt or conda install requirements.txt (Requirements.txt is a text file consisting of all the necessary libraries required for executing this python file. If it gives any error while installing libraries, you might need to install them individually.)
5. Run python main.py in your terminal, or run main_gui.ipynb. You can even try running main_eye.ipynb to get a feel of model creation and preprocess.ipynb to get a feel of pre-processing steps taken.
(The .py files should be executed on your terminal and .ipynb files should be executed directly in the code editor)

# _**Data Description**_
So, the dataset in the project was collected from a private repository and consist of two classes of images each class consists of 50 images each, Dry and Wet. Along with these two classes, we have also used No ARMD/Normal people eye dataset combined with other two classes. Below are some sample images of 3 classes.

**DRY**

![Dry ARMD](https://static.wixstatic.com/media/5810c8_7065f62283454270905888fec8f5a96f~mv2.png/v1/fill/w_199,h_160,al_c,usm_0.66_1.00_0.01/Dry%20AMD%20photo%20insert_PNG.png)

**WET**

![Wet_ARMD](https://d1l9wtg77iuzz5.cloudfront.net/assets/5625/229995/original.png?1525299390)

**NORMAL**

![Normal](https://i0.wp.com/post.healthline.com/wp-content/uploads/2019/03/Human_Eye_Closeup_1296x728-header-1024x575.jpg?w=1155&h=1528)

# Issues Faced.
1. Data Augmentation can be performed more accurately.
2. Preprocessing of the images should be done properly because, Having larger image might result in high computational cost.
3. We might face an issue while installing specific libraries.
4. Make sure you have the latest version of python, since sometimes it might cause version mismatch.
5. Adding path to environment variables in order to run python files and anaconda environment in code editor, specifically in visual studio code.
6. Make sure to change the path in the code where your dataset is saved.

### _**Let’s Connect**_
https://www.linkedin.com/in/mudassiruddin21

![Connect](https://media2.giphy.com/media/l1O6zvqu7O317887HF/source.gif)

# _**Yes, you now have more knowledge than yesterday, Keep Going.**_

![Happy](https://winkgo.com/wp-content/uploads/2019/11/congratulations-memes-44.gif)
  
