# Machine Learning for Finance (FN 570) 2023-24 Module 3 (Spring 2024)

## Announcements
* The WeChat group will be created by TA. (No 1-to-1 chat please.)
* Email is the preferred method of communication. The class mailing list will be created as PHBS.MLF@allmail.net.
<!--
* [Midterm exam solution](files/MLF2018_Midterm.pdf) is uploaded
* Midterm exam on Friday will be in __Rm 321__ 
* Python Crash Course will be on 9.12 (Wed) **1:30 PM**. Class mailing list created.
-->

## Course Resources
* Course slides: [Intro](files/MLF_Intro.pdf) | [Regression](files/MLF_Regression.pdf) | [SVM/KNN/Tree](files/MLF_SVM_KNN_Tree.pdf) | [SVD/PCA/LDA](files/MLF_SVD_PCA_LDA.pdf) | [Hyperparameter](files/MLF_Bias_Variance_Metric.pdf) | [Neural Network](files/MLF_Neural_Network.pdf) | [Graphical Model](files/MLF_Graphical_Model.pdf)
* Project: [Current](Project.md) | [2021](past-years/2021.M1/Project.md) | [2019](past-years/2019.M3/Project.md) | [2018](past-years/2018.M1/Project.md) | [2017](past-years/2017.M3/Project_List.md) | [2016](past-years/2016.M3/Project_List.md)
* Past years' exam: [2022](files/MLF2022_Midterm.pdf) | [2021](files/MLF2021_Midterm.pdf) | [2019](files/MLF2019_Midterm.pdf) (online take-home) | [2018](files/MLF2018_Midterm.pdf) | [2017](files/MLF2017_Midterm.pdf) | [Exams from Tom Michell's ML course](http://www.cs.cmu.edu/~tom/10701_sp11/prev.shtml) (Carnegie Mellon University)
 
<!--
* ### Data Proposal [__10.23 Tues__ class]
* ### Presentation [__11.09 Fri__ class]
-->

## Lectures:
No | Date | Contents
--- | :---: | ---
__01__ | 2.20 Tue | Course overview ([Syllabus](#syllabus)) \| Required software (Python, Github, PyCharm) \| Python crash course ([Basic](py/PythonCrashCourse_Derek_Banas.ipynb), [Numpy](py/PythonCrashCourse_Numpy.ipynb) (Notebook Shorcut Keys), [Pandas](py/Pandas-CrashCourse.ipynb). Also see [Datacamp](https://www.datacamp.com/community/blog/python-pandas-cheat-sheet), [CheatSheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf))
__02__ | 2.23 Fri | __PML__ Ch. 1: Intro ([Slides](files/MLF_Intro.pdf)) \| Notations, Regression, Weight update ([Slides](files/MLF_Regression.pdf))
__03__ | 2.27 Tue | __PML__ Ch. 2: Perceptron, Adaline, Gradient descent, Stochastic Gradient Descent
__04__ | 3.01 Fri | __PML__ Ch. 3: Logistic Regression (LR) ([Slides](files/MLF_Regression.pdf)) and Support Vector Machine (SVM) ([Slides](files/MLF_SVM_KNN_Tree.pdf))
__05__ | 3.05 Tue | __PML__ Ch. 3: KNN ([Slides](files/MLF_SVM_KNN_Tree.pdf), [Code](https://github.com/PHBS/python-machine-learning-book-3rd-edition/blob/master/ch03/ch03.ipynb)), Decision Tree ([Slides](files/MLF_SVM_KNN_Tree.pdf)).
__06__ | 3.08 Fri | __PML__ Ch. 4: Data Preprocessing, __PML__ Ch. 5: SVD/PCA ([Slides](MLF_SVD_PCA_LDA.pdf))
__07__ | 3.12 Tue | __PML__ Ch. 5: LDA ([Slides](MLF_SVD_PCA_LDA.pdf)), __PML__ Ch. 6: Bias-Variance, Cross-validation ([Slides](files/MLF_Bias_Variance_Metric.pdf))
__08__ | 3.15 Fri | __PML__ Ch. 6: Hyperparameter tuning, Evaluation Metric, Class imbalance ([Slides](files/MLF_Bias_Variance_Metric.pdf))
__09__ | 3.19 Tue | __PML__ Ch. 7: Ensenble Learning ([Slides](files/MLF_SVM_KNN_Tree.pdf)), Kernel Method ([Slides](files/MLF_Kernel_Method.pdf), __PML__ Ch 3, 5)
__10__ | 3.22 Fri | __PML__ Ch. 8: Sentiment Analysis ([Slides](files/MLF_Sentiment.pdf))
__11__  | 3.26 Tue | Topics in Finance ML: Recession prediction ([Slides](files/MLF_Topic_RecessionPrediction.pdf)), ML in Finance Research ([Slides](files/MLF_Finance_Research.pdf)), Collaborative Filtering ([Slides](files/MLF_Col_Filtering.pdf))
__12__ | 3.29 Fri | Neural Network, Deep Learning, CNN ([Slides](files/MLF_Neural_Network.pdf), __PML__ Ch. 12-15) 
__14__ | 4.02 Tue | __HSBC Guest Lecture [1/4]__
__13__ | 4.07 Sun | __Midterm Exam__ (Tentative)
__15__ | 4.09 Tue | __HSBC Guest Lecture [2/4]__
__16__ | 4.12 Fri | __HSBC Guest Lecture [3/4]__
__17__ | 4.16 Tue | __HSBC Guest Lecture [4/4]__
__18__ | 4.19 Fri | Course Project Presentation (may be scheduled later)

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

## Homeworks:
* ### __Set 0: [Required Software]__ [Due by Friday]
  * Register on [Github.com](https://github.com/) and let TA know your ID. Make sure to use your __full real name__ in your profile. Accept TA's invitation to the [PHBS organization](https://github.com/orgs/PHBS/people). 
    * Create a designated repository `GITHUB_ID/PHBS_MLF_2023` for your HW and project. Tick `Initialize this repository with a README` and select `python` under `.gitignore`
    * Fork [PML repository](https://github.com/PHBS/python-machine-learning-book-3rd-edition) to your repository.
  * Install [Github Desktop](https://desktop.github.com/). Then __clone__ the PML repository to your local storage.
  * Install [Anaconda](https://www.anaconda.com/download/) Python distribution (__3.X version__, not 2.X version). Anaconda distribution is core Python + useful scientific computation libraries (e.g., numpy, scipy, pandas) + package management system (pip or conda)
  * Install [PyCharm](https://www.jetbrains.com/pycharm/) Community version. (Or Professional version after applying for [free student license](https://www.jetbrains.com/student/))
  * Send to TA the screenshots of (1) Github Desktop (showing the PML repository) (2) Jupyter Notebook (Anaconda) (3) PyCharm (See my examples: [Github Desktop](https://github.com/PHBS/ASP/blob/master/files/Choi_Jaehyuk_Github.png), [Anaconda Spyder](https://github.com/PHBS/ASP/blob/master/files/Choi_Jaehyuk_Python.png)).
* ### __Set 1: [Classifiers]__ [Due by 3.19 Tues]
  * The goal of this HW is to be familiar with the basic classifiers __PML__ Ch 3. 
  * For this HW, we will use [Give Me Some Credit](https://www.kaggle.com/c/GiveMeSomeCredit) on Kaggle. You may download it from the Kaggle link or CMS.
  * Load `cs-training.csv` into a Pandas dataframe.
  * Fill-in the missing values (`nan`) with the column means. (Use `pd.fillna()` or See Ch 4 of `PML`)
  * Select the 2 most important features using LogisticRegression with L1 penalty. (Adjust C until you see 2 features)
  * Using the 2 selected features, apply LR / SVM / decision tree. Try your own hyperparameters (C, gamma, tree depth, etc) to maximize the prediction accuracy. (Just try several values. You don't need to show your answer is the maximum.)
  * Visualize your classifiers using the `plot_decision_regions` function from __PML__ Ch. 3
  * Put your result in `YOUR_GITHUB_ID/Give-Me-Some-Credit/code/Classifiers.ipynb`
* ### __Set 2: [PCA/Hyperparameter/CV]__ [Due by 3.29 Wed]
  * The goal of this HW is to be familiar with PCA (feature extraction), grid search, pipeline, k-fold CV. 
  * For this HW, we continue to use [Give Me Some Credit]([http://archive.ics.uci.edu/ml/datasets/Polish+companies+bankruptcy+data](https://www.kaggle.com/datasets/brycecf/give-me-some-credit-dataset)) on Kaggle. 
  * Extract a few (>2) features using PCA method.
  * Using the selected features from above, we are going to apply LR / SVM / decision tree (or any other algorithm). 
  * Implement the methods using pipeline. (__PML__ p185)
  * Use grid search for finding optimal hyperparameters. (__PML__ p199). In the search, apply 5-fold cross-validation.

***
# Syllabus

## Classes:
* Lectures: Tuesday & Friday 1:30 – 3:20 PM
* Venue: PHBS Building, Room 313

## Instructor: [Jaehyuk Choi](http://www.jaehyukchoi.net/phbs_en)
* Office: PHBS Building, Room 755
* Phone: 86-755-2603-0568
* Email: jaehyuk@phbs.pku.edu.cn
* Office Hour: Monday 7-9 PM

## Teaching Assistance: 苏南 (Nan SU)
* Email: sunan@stu.pku.edu.cn
* TA Office Hour (Room 213/214): TBA

## Course overview
With the advent of computation power and big data, machine learning (ML) recently became one of the most spotlighted research fields in industry and academia. This course provides a broad introduction to ML in theoretical and practical perspectives. Through this course, students will learn the intuition and implementation behind the popular ML methods and gain hands-on experience in using ML software packages such as SK-learn and Tensorflow. This course will also explore the possibility of applying ML to finance and business. Each student is required to complete a final course project. 
__This year, the compliance analytics team in HSBC bank (Gunagzhou) will give 4 guest lectures to demonstrate how ML is developed and shared in banking industry.__

## Prerequisites
This course assumes prior knowkedge in probability/statistics and experience in Python. This course is ideally recommended for those who have taken introductory ML/AI courses from an undergraduate program.

##  Textbooks and Reading Materials
### Primary textbook
* __PML__ (primary textbook): Python Machine Learning 3rd Ed. by Sebastian Raschka. 
  * [Github](https://github.com/PHBS/python-machine-learning-book-3rd-edition) (PHBS fork)
### Other books and online courses
* __ISLR__: [An Introduction to Statistical Learning (with Applications in R)](http://faculty.marshall.usc.edu/gareth-james/ISL/) by James, Witten, Hastie, and Tibshirani
  * Python Implementation: [PHBS/ISLR-python](https://github.com/PHBS/ISLR-python) (PHBS fork)  
* __Bishop__: Pattern Recognition and Machine Learning by Bishop (Microsoft)
* __ESL__:  [The Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/) by Hastie, Tibshirani, and Friedman
* __CML__: [Coursera Machine Learning](https://www.coursera.org/learn/machine-learning) by Andrew Ng
* __DL__: [Deep Learning](http://www.deeplearningbook.org/) by Goodfellow, Bengio, and Courville
* __AFML__: [Advances in financial machine learning](https://www.amazon.com/Advances-Financial-Machine-Learning-Marcos/dp/1119482089) by López de Prado
<!--
* __JPM-AI__: [Big Data and AI Strategies](http://valuesimplex.com/articles/JPM.pdf) by J.P. Morgan
-->

## Assessment / Grading Details
* Attendance 20%, Mid-term exam 30%, Assignments 20%, Course Project 30%
* Attendance: Randomly checked. The score is calculated as __`20 – 2x(#of absence)`__. Leave requests should be made 24 hours before with supporting documents, except for emergencies. Job interview/internship cannot be a valid reason for leave.
* __Mid-term exam__: __11.1 Mon__. In-class open-book without computer/phone/calculator
* __Course project__: Data Proposal and Presentation. Group of up to ?? people.
* __Grade__ in letters (e.g., A+, A-, ... ,D+, D, F). __A- or above < 30% and B- or below > 10%__.
