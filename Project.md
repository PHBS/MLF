# Course Project

## Suggestions on project topics:
### Hoberg-Phillips similarity
* [Hoberg-Phillips](https://hobergphillips.tuck.dartmouth.edu/) provide firms' product cosine similarity.
* It can be used as the kernel function between firms.
* Use HP similarity as a proxy for stock correlation and calculate portfolio weight
* Consider a proper y variable (?) for Kernel SVM or (Kernel PCA + ML methods)
* Improve HP similarity with `doc2vec` method? (quite a big project)
### Sentiment analysis on central bank statement
* Train the FOMC (or PBoC's) [statements or minute](https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm) with `doc2vec` (or `word2vec`) algorithm to  to create vector representation
* Fit ML models with the policy rate change or market reaction as y variable
* Identify the most important vector (and corresponding word/phrase) with feature selection/extraction

## Team List (Presentation Order)

Group | Date | Title
--- | -- | ---


## Team Formation (__10. 24 Sun__)
* Form a group (up to 3 students) and select data set
* Designate a repository `GITHUB_ID/PHBS_MLF_2021` of one team member for the team project.
* Let TA know the repository to be used for th eproject
* Put team members' student # and github ID in `README.md` (for the syntax of `.md` file, see [markdown cheetsheet](https://guides.github.com/features/mastering-markdown/)) 
* `README.md` will be eventually the report of your course project.

## Data Selection (__10. 28 Thurs__)
* No restriction on data set. However, business(fin/ma/econ) related data is welcome (extra credit for creative data selection and pre-processing)
* Put the data under `GITHUB_ID/PHBS_MLF_2021/data` folder (if too big, put some samples)
* Put a brief description of your data and the goal of the project in `README.md` (refer to [markdown cheetsheet](https://guides.github.com/features/mastering-markdown/))

## Project Guidline
* Report should be consist of the summary in `README.md` and the execution in python notebooks `.ipynb`.  ( `.pdf`, `.ppt`, `.doc` __NOT__ accepted.)
* In the `README.md` summary, 
  * You may update your proposal file.
  * briefly describe your motivation, goal, data source, result and conclusion.
  * A few figure or table for summary is recommended.
  * Use links to data or `.ipynb` files (see past year examples below)
* In the `.ipynb` execution, 
  * Put command cell and edit cell (comments) in a balanced way. (Do not only put code!)
  * Put a brief table of contents with links (example: __PML__)
  * You may breakdown code into several `.ipynb` files by function (e.g., data cleaning, learning, result analysis). In that case, make sure to __save__ intermediate result into file so that I can run the later steps (result analysis) without running previous steps (data cleaning, learning).
  * The use of `.py` file should be strictly restricted to function or class only. (Do not put any learning procedure in `.py`)
  * I should be able to reproduce the result from your code. Your code should run with no error. Code with error will be severely deduct your score. Make sure to run your code in a new session.
* Other considerations:
  * Make sure the workload within team is balanced. (Add your team members to collaborators, each team members commit codes, etc)
  * There should be no secret component (e.g., stock trading strategy)
  * Creative (out-of-textbook) ideas are recommended for better result or result analysis
* Deadline for updating report is __11.21 Sunday Midnight (11:59 PM)__
