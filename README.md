# Machine Learning for Finance (FN 570) 2019-20 Module 3 (Spring 2020)

## Announcements
* Email is the preferred method of communication. Class mailing list will be created as PHBS.MLF@allmail.net. But, the announcements will be made in DingTalk group chat.
<!--
* [Midterm exam solution](files/MLF2018_Midterm.pdf) is uploaded
* Midterm exam on Friday will be in __Rm 321__ 
* Python Crash Course will be on 9.12 (Wed) **1:30 PM**. Class mailing list created.
-->

## Lectures:
* __01__ (2.18 Tue): Course overview ([Syllabus](#syllabus)), Python, Github, Etc.
* __02__ (2.21 Fri): __HSBC Guest Lecture [1/4]__ Model management cycle in banking industry, Tool setup (GCP/Ali Cloud).
* __03__ (2.25 Tue): Python crash course ([Basic](py/PythonCrashCourse_Derek_Banas.ipynb) | [Numpy](py/PythonCrashCourse_Numpy.ipynb)) | 
Intro ([Slides](files/MLF_Intro.pdf), Reading: __PML__ Ch. 1)
* __04__ (2.28 Fri): Regression ([Slides](files/MLF_Regression.pdf))
* __05__ (3.03 Tue): __PML__ Ch. 2 (Perceptron, Adaline, Gradient descent, SGD), Regression weight update ([Slides](files/MLF_Regression.pdf))
* __06__ (3.06 Fri): Logistic Regression ([Slides](files/MLF_Regression.pdf), Reading: __PML__ Ch. 3) 
* __07__ (3.10 Tue): SVM/KNN/Decision Tree ([Slides](files/MLF_SVM_KNN_Tree.pdf), Reading: __PML__ Ch. 3) 
* __08__ (3.13 Fri):
* __09__ (3.17 Tue):
* __10__ (3.20 Fri): __HSBC Guest Lecture [2/4]__ Data mining, profiling, visualization, and conclusion. 
* __11__ (3.24 Tue):
* __12__ (3.27 Fri): __HSBC Guest Lecture [3/4]__ Model sharings.
* __13__ (3.31 Tue):
* __14__ (4.03 Fri): __HSBC Guest Lecture [4/4]__ Practical issues of applying ML to the real world.
* __15__ (4.07 Tue): __Midterm Exam__
* __16__ (4.10 Fri):
* __17__ (4.14 Tue): Course Project Presentation (Tentative)
* __18__ (4.17 Fri): Course Project Presentation
<!--
* __18__ (11.09 Fri) 
* __17__ (11.06 Tues): Tensorflow / Keras ([XOR](py/TF_Keras_XOR.ipynb), [Iris](py/Keras_Iris.ipynb) based on [here](https://machinelearningmastery.com/multi-class-classification-tutorial-keras-deep-learning-library/))
* __16__ (11.02 Fri): Neural Network ([Slides](files/MLF_Neural_Network.pdf)), ML-related research presentation (LOOLSM)
* __15__ (10.30 Tues): Use of sklearn in __PML__ Ch. 10, Neural Network ([Slides](files/MLF_Neural_Network.pdf))
* __14__ (10.26 Fri): Use of sklearn in __PML__ Ch. 5/6/7
* __13__ (10.23 Tues): [Course Project Proposal](Project.md)
* __12__ (10.19 Fri): Midterm exam (Rm 321) ([Solution](files/MLF2018_Midterm.pdf))
* __NO CLASS__ on __10.16 Tues__
* __11__ (10.12 Fri): Confusion matrix, ROC curve, LOOCV ([Slides](files/MLF_Bias_Variance_Metric.pdf))
* __10__ (10.09 Tues): SVD/PCA/LDA ([Slides](files/MLF_SVD_PCA_LDA.pdf)) __PML__ Ch. 5, Hyperparameters ([Slides](files/MLF_Bias_Variance_Metric.pdf)) __PML__ Ch. 6
* __09__ (09.28 Fri): Data Preprocessing __PML__ Ch. 4, SVD/PCA/LDA ([Slides](files/MLF_SVD_PCA_LDA.pdf)) __PML__ Ch. 5
* __08__ (09.25 Tues): Kernel SVM/Bagging/RF ([Slides](files/MLF_SVM_KNN_Tree.pdf)) __PML__ Ch. 3
* __07__ (09.21 Fri): 
* __06__ (09.18 Tues): 
* __05__ (09.14 Fri): 
* __04__ (__09.12 Wed__ instead of __10.16 Tues__): More [cheatsheets](https://ehmatthes.github.io/pcc/cheatsheets/README.html) also available in [MLF CMS](http://cms.phbs.pku.edu.cn/claroline/document/document.php?cidReset=true&cidReq=FN570).
* __03__ (09.11 Tues): 
* __02__ (09.07 Fri): 
* __01__ (09.04 Tues): 
-->

## Course Resources
* Course slides: [Intro](files/MLF_Intro.pdf) | [Regression](files/MLF_Regression.pdf) | [SVM/KNN/Tree](files/MLF_SVM_KNN_Tree.pdf) | [SVD/PCA/LDA](files/MLF_SVD_PCA_LDA.pdf) | [Hyperparameter](files/MLF_Bias_Variance_Metric.pdf) | [Neural Network](files/MLF_Neural_Network.pdf) | [Graphical Model](files/MLF_Graphical_Model.pdf)
* Past Exam: [2017](files/MLF2017_Midterm.pdf) | [2018](files/MLF2018_Midterm.pdf)
* [Exams from Tom Michell's ML course](http://www.cs.cmu.edu/~tom/10701_sp11/prev.shtml) (Carnegie Mellon University)

## Homeworks:
* ### __Set 0: [Required Software]__ [Due by 2.22 Sat]
  * Register on [Github.com](https://github.com/) and let TA know your ID (by DingTalk). Make sure to user your __full real name__ in your profile. Accept invitation to the [PHBS organization](https://github.com/orgs/PHBS/people) from TA. 
    * Create a designated repository `GITHUB_ID/PHBS_MLF_2019` for your HW and project. Tick `Initialize this repository with a README` and select `python` under `.gitignore`
    * Fork [PML repository](https://github.com/PHBS/python-machine-learning-book-2nd-edition) to your repository.
  * Install [Github Desktop](https://desktop.github.com/) (available on [CMS](http://cms.phbs.pku.edu.cn/claroline/course/index.php?cid=FN570)). Then __clone__ the two repositories to your local storage.
  * Install [Anaconda](https://www.anaconda.com/download/) Python distribution (__3.X version__, not 2.X version). Anaconda distribution is core Python + useful scientific computation libraries (e.g., numpy, scipy, pandas) + package management system (pip or conda)
  * Install [PyCharm](https://www.jetbrains.com/pycharm/) Community version. (Or Professional version after applying for [free student license](https://www.jetbrains.com/student/))
  * Save the screenshot of (1) Github Desktop (showing 2 repositories) (2) Jupyter Notebook (Anaconda) (3) PyCharm (See my [example](https://github.com/jaehyukchoi/PHBS_MLF_2019/tree/master/HW0)) and make sure to press __`Push Origin`__ to sync with the online repository in github.com.

## Course Project
* Previous Years: [2018](past-years/2018.M1/Project.md)
<!--
* ### Data Proposal [__10.23 Tues__ class]
* ### Presentation [__11.09 Fri__ class]
-->

***
# Syllabus

## Classes:
* Lectures: Tuesday & Friday 1:30 – 3:20 PM
* Venue: Online/DingTalk ~~PHBS Building, Room 229~~

## Instructor: [Jaehyuk Choi](http://www.jaehyukchoi.net/phbs_en)
* Office: PHBS Building, Room 755
* Phone: 86-755-2603-0568
* Email: jaehyuk@phbs.pku.edu.cn
* Office Hour: Online/DingTalk (TBA)

## Teaching Assistance: Shiqi Zhang (张诗琪)
* Email: 1701213153@sz.pku.edu.cn
* TA Office Hour: Online/DingTalk ~~(Room 213/214)~~

## Course overview
With the advent of computation power and big data, machine learning (ML) recently became one of the most spotlighted research field in industry and academia. This course provides a broad introduction to ML in theoretical and practical perspectives. Through this course, students will learn the intuition and implementation behind the popular ML methods and gain hands-on experience of using ML software packages such as SK-learn and Tensorflow. This course will also explore the possibility of applying ML to finance and business. Each student is required to complete a final course project. 
__This year, the compliance analytics team in HSBC bank will give 4 guest lectures thrroughout the course to demonstrate how ML is developed and shared in banking industry. In the guest lectures, students will also learn how to use cloud computing (Google Cloud Platform/Ali Cloud)__

## Prerequisites
This course assumes prior knowkedge in probability/statistics and experience in Python. This course is ideally recommended for those who have taken introductory ML/AI courses from undergraduate program.

##  Textbooks and Reading Materials
### Primary textbook
* __PML__ (primary textbook): [Python Machine Learning](https://github.com/PHBS/python-machine-learning-book-2nd-edition) by Sebastian Raschka
### ML
* __ISLR__: [An Introduction to Statistical Learning (with Applications in R)](http://faculty.marshall.usc.edu/gareth-james/ISL/) by James, Witten, Hastie, and Tibshirani
* __Bishop__: Pattern Recognition and Machine Learning by Bishop (Microsoft)
* __ESL__:  [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/) by Hastie, Tibshirani, and Friedman
* __CML__: [Coursera Machine Learning](https://www.coursera.org/learn/machine-learning) by Andrew Ng
* __DL__: [Deep Learning](http://www.deeplearningbook.org/) by Goodfellow, Bengio, and Courville
### ML in Finance
* __AFML__: [Advances in financial machine learning](https://www.amazon.com/Advances-Financial-Machine-Learning-Marcos/dp/1119482089) by López de Prado
<!--
* __JPM-AI__: [Big Data and AI Strategies](http://valuesimplex.com/articles/JPM.pdf) by J.P. Morgan
-->

## Useful Github Repositories
* __PML__: [PHBS/python-machine-learning-book-2nd-edition](https://github.com/PHBS/python-machine-learning-book-2nd-edition) (forked)
* __ISLR-Python__: [PHBS/ISLR-python](https://github.com/PHBS/ISLR-python) (forked) __ISRL__ implemented in Python

## Assessment / Grading Details
* Attendance 20%, Mid-term exam 30%, Assignments 20%, Course Project 30%
* Attendance: TBA ~~Randomly checked. The score is calculated as __`20 – 2x(#of absence)`__. Leave request should be made 24 hours before with supporting documents, except for emergency. Job interview/internship cannot be a valid reason for leave~~
* __Mid-term exam__: __4.7 Tues__. In-class open-book without computer/phone/calculator
* __Course project__: Data Proposal and Presentation. Group of up to ?? people.
* __Attendance__: checked randomly. The score is calculated as 20 – 2`x`(#of absence). Leave request should be made 24 hours before with supporting documents, except for emergency. Job interview/internship cannot be a valid reason for leave
* __Grade__ in letters (e.g., A+, A-, ... ,D+, D, F). __A- or above < 30% and B- or below > 10%__.
