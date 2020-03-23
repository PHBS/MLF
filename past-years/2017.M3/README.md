# Topics in Quantitative Finance: Machine Learning for Finance (2017-18 Module 3)

## Announcements
* __[NEW 4.02]__ Group formation, Project proposal (__4.12 W7 Thur__), Presentation (__5.7 Mon 7PM__) ([Project List](Project_List.md))
* __[NEW 3.19]__ Mid-term exam will be on 4.9 (W7 Monday, __Rm 401__)
* [3.7] Class mailing list is created as PHBS.TQF@allmail.net. If you did not receive a test e-mail, let me know.
* [2.26] Email is the preferred method of communication. Mail list will be set up soon.

## Course Note

## Lectures:
* (05.07 Mon) [Project Presentation](Project_List.md)
* __18__ (04.26 Thur): ML-related thesis presentation by two students
* __17__ (04.23 Mon):  __PML__ Ch. 15 Convolutional Neural Network
* __16__ (04.19 Thur): __PML__ Ch. 13, 14 Back-propagation,  Tensorflow/Keras
* __15__ (04.16 Mon): __PML__ Ch. 11 Unsupervised learning, Ch. 12 Neural Networks
* __14__ (04.12 Thurs): Project proposal ([Project List](Project_List.md)), 
* __13__ (04.09 Mon): Mid-term exam (Rm 401) [Solution](files/TQF2017_Midterm.pdf)
* __12__ (04.04 Wed): __PML__ Ch. 7 Bagging/RF/AdaBoosting, Ch 8 Quick Glimpse
* __11__ (04.02 Mon): __PML__ Ch. 6 Confusion matrix, F1 score, ROC AUC, Ch 7
* __10__ (03.29 Thur): __PML__ Ch. 6 Bias-variance tradeoff, Cross validation
* __09__ (03.26 Mon): __PML__ Ch. 5 Feature extraction ([SVD/PCA](files/SVD_PCA.pdf) and LDA)
* __08__ (03.22 Thur): __PML__ Ch. 4 (Data preprocessing, Feature selection)
* __07__ (03.19 Mon): __PML__ Ch. 3 (Kernel SVM, KNN, Decision Tree), [Slides](files/TQF_Notes.pdf) (SVM, Tree)
* __06__ (03.15 Thur): __PML__ Ch. 3 (Logistic Regression, Regularization, SVM), [Slides](files/TQF_Notes.pdf) (SVM)
* __05__ (03.12 Mon): __PML__ Ch. 2 (Perceptron, Adaline, Gradient descent), [Slides](files/TQF_Notes.pdf) (Weight update)
* __04__ (03.08 Thur): [Slides](files/TQF_Notes.pdf) (Vector Matrix Notations, Linear/Logistic Regression), __ISLR-python__ Ch. 3
* __03__ (03.05 Mon): [Python Crash Course](py/Cheatsheet_Derek_Banas.ipynb) (continued), [Slides](files/TQF_Notes.pdf) (Intro)
* __02__ (03.01 Thur): Python Notebook, Github Desktop, [Python Crash Course](py/Cheatsheet_Derek_Banas.ipynb)
* __01__ (02.26 Mon): Course overview ([Syllabus](files/syllabus.pdf)), Python, Github, Etc.

## Homeworks:
* ### __Set 1__ [Due by 3.5]: 
  * Register on Github.com and let TA know your ID. Give your full name in your profile.
  * Accept invitation to `2017.TQF-ML` team from TA
  * Install Python Aanconda and Github Desktop. Clone [PHBS/python-machine-learning-book-2nd-edition](https://github.com/PHBS/python-machine-learning-book-2nd-edition) and run `code/ch01/ch01.ipynb`  Send screenshots to TA
* ### __Set 2__ [Due by 3.29]
  * Create your own GitHub repository for homework `GITHUB_ID/PHBS_TQFML` (make sure to make it __public__)
  * Bank Marketing Data Set: [UCI](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing), [Download](files/DataSet1)
  * Write a Jupyter notebook `GITHUB_ID/PHBS_TQFML/HW/bank_marketing.ipynb`:
    * load data (`bank.csv`, smaller sample), normalize, and devide training/test sets
    * randomly select 2 or 3 features
    * apply the methods covered in Ch. 3 with SK-learn (logistic regress, SVM, decision tree, etc)
    * check the accuracy and plot the outcome
    * repeat above to find better feature
    * commit the best result and don't foget to `sync` to the repository
* ### Project proposal [Due by the end of 4.11]
  * Email __repository name, team members, data set and brief plan__ to Professor and TA
  * Designate one repository `GITHUB_ID/PHBS_TQFML/Project` and create `README.md` file to have the information above
  
## Classes: 
* Lectures: Monday & Thursday 8:30 AM – 10:20 AM
* Venue: PHBS Building, Room 229

## Instructor: [Jaehyuk Choi](http://www.jaehyukchoi.net/phbs_en)
* Office: PHBS Building, Room 755
* Phone: 86-755-2603-0568
* Email: jaehyuk@phbs.pku.edu.cn
* Office Hour: Monday & Thursday 1:30 – 2:30 PM or by appointment

## Teaching Assistance: Chenru LIU (刘晨茹)
* Email: 1501213463@sz.pku.edu.cn
* TA Office Hour: Tuesday & Friday 1-2 PM (Room 213/214)

## Course overview

The purpose of Topics in Quantitative Finance is to introduce students to recent trends and advanced research topics in quantitative methods of business and finance. This year’s course is dedicated to machine learning (ML) for finance. ML has been one of the hottest technology in software engineering. This course will explore the possibility of applying ML to finance and business. The course will give students the basic ideas and intuition behind the popular ML methods and hands-on experience of using ML software package such as SK-learn and Tensorflow (Google). Each student is required to complete a final course project.

## Prerequisites

There is no formal prerequisites. However, undergraduate-level knowledge in probability/statistics and previous experience in programming language is highly recommended.

##  Textbooks and Reading Materials
* __PML__ (primary textbook): [Python Machine Learning](https://github.com/rasbt/python-machine-learning-book-2nd-edition) by Sebastian Raschka
* __ISLR__: [An Introduction to Statistical Learning (with Applications in R)](http://www-bcf.usc.edu/~gareth/ISL/) by James, Witten, Hastie, and Tibshirani
* __CML__: [Coursera Machine Learning](https://www.coursera.org/learn/machine-learning) taught by Andrew Ng
* __DL__: [Deep Learning](http://www.deeplearningbook.org/) by Goodfellow, Bengio, and Courville
* __JPM-AI__: [Big Data and AI Strategies](http://valuesimplex.com/articles/JPM.pdf) by J.P. Morgan

## Useful Github Repositories
* __PML__: [PHBS/python-machine-learning-book-2nd-edition](https://github.com/PHBS/python-machine-learning-book-2nd-edition) (forked)
* __ISLR-Python__: [PHBS/ISLR-python](https://github.com/PHBS/ISLR-python) (forked) __ISRL__ implemented in Python

## Assessment / Grading Details
* Attendance 20%, __Mid-term Exam 20% (New)__, Assignments 20%, Final Project 40%
* __Mid-term exam__: 4.9 (W7 Mon)
* __Project proposal__: 4.12 (W7 Thur)
* __Presentation (5.7 Mon 7PM)__
* Exams are open-book without computer/phone/calculator use
* You may form a group of up to 2 people for course project. Extra credit will be given to individual projects.
* Grade in letters (e.g., A+, A-, ... ,D+, D, F). __A- or above < 30% and B- or above < 90%__.
