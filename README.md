
### Data Science Course

This repo contains materials for a short introductory/intermediate 
Data Science course taught in the new (2015) 
[MSc in Business Analytics program](http://business.ceu.edu/msc-in-business-analytics) 
at the Central European University (CEU).

It is this much one can teach in limited time (1200 minutes/20 hours net) to
students with varying analytical background. As most data science topics except 
machine learning are covered somewhat in other courses in the program, 
I decided to spend 60-70% of time on machine learning. Yet, I'm still spending the 
rest on an overview of data science with topics such as exploratory data analysis, data visualization, reproducibility, tools for data analysis etc. 
(and emphasizing how all this comes together).

-------------------------------------------------------------

## Syllabus

#### CEU MSc in Business Analytics 

#### Course: Data Science for Business

- **Term:** Winter 2015
- **Credits:** 2 (4 ECTS) 
- **Department:** Department of Economics / CEU Business School
- **Instructor:** Szilard Pafka


#### Course description:

This course will provide a brief overview of Data Science, the field aimed at extracting business value from data. Despite the new name and the recent hype, Data Science is actually not new, it has solid foundations in *statistics* and *computing technology* that go back several decades. A Data Science project usually involves several iterations of the following steps: business understanding, data acquisition, exploratory data analysis, data cleaning, feature engineering, advanced statistical modeling, model validation, technical implementation and deployment and communication of results to decision makers. This course will discuss these steps along with the knowledge and the technology necessary to be able to perform them; some topics will be discussed in very details, while others will have pointers to other courses in the MSc in Business Analytics program for further coverage.

A large part of this current course will be dedicated to advanced statistical modeling / *machine learning* / predictive analytics. We will discuss methods for supervised learning such as neural networks, decision trees, naive Bayes, k-nearest neighbors, support vector machines, random forests or gradient boosted machines. We will discuss important issues regarding model evaluation and validation (bias and variance, overfitting, training and test error, regularization, cross-validation, data leakage etc.). We will also cover methods for unsupervised learning such as principal component analysis and clustering (k-means, hierarchical).

Other topics, equally important for Data Science will be just briefly discussed here with more details following in other courses. For example, students will get hands-on experience with *exploratory data analysis*, *data manipulation/preparation* and cleaning, *data visualization*, *programming* with data and tools that help *reproducibility* in the Tools for Analytics Lab (the R Track). Data storage, databases, data transformations (data pipelines/ETL) and SQL will be discussed in The Big Data Computing course (also providing a *systems* view). *Data visualization* (a very important component in exploratory data analysis and also in the communication of results to decision makers) will be discussed in further details in the Data Visualization elective course (highly recommended). Some of the more traditional *statistical modeling* topics (such as linear regression) have been already covered in the Data Analysis I and II courses.

#### Assessment:

- 10% class participation
- 50% final exam
- 40% data analysis project

#### Course schedule and reading for each session:

**1.** [DS] **The Data Science process**: business understanding, data acquisition, exploratory data analysis, data cleaning, feature engineering, advanced statistical modeling, model validation, technical implementation and deployment, communication of results to decision makers.

Foster Provost, Tom Fawcett: [Data Science for Business](http://www.amazon.com/Data-Science-Business-data-analytic-thinking/dp/1449361323), Ch. 2 (pp. 19-41)

**2.** [DS] Tools for Data Science (R/Python, databases). Exploratory data analysis. Data preparation/munging. Data visualization. Tools for workflow/reproducibility/productivity

Sean Kandel, Andreas Paepcke, Joseph M. Hellerstein, and Jeffrey Heer: 
[Enterprise Data Analysis and Visualization: An Interview Study](http://db.cs.berkeley.edu/papers/vast12-interview.pdf) (pp. 1-10)

Rexer Analytics: [2013 Data Miner Survey (Summary Report)](http://www.rexeranalytics.com/Data-Miner-Survey-Results-2013.html) (pp. 8, 9, 12, 16, 31, 35)

**3.** [ML] **Supervised learning**. Linear models vs k-nearest neighbors (bias, variance). An overview of supervised learning methods (with details in the following 3 sessions). Linear regression. Ridge regression and Lasso (regularization). Logistic regression

Trevor Hastie, Robert Tibshirani, Jerome Friedman: [The Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/printings/ESLII_print10.pdf), 2nd Edition, Ch. 2 (pp. 9-24, 28-30), Ch. 3 (pp. 43-45, 47, 51-52, 57, 62-65, 68-69, 71), Ch. 4 (pp. 119-120)

Leo Breiman: [Statistical Modeling: The Two Cultures](http://projecteuclid.org/euclid.ss/1009213726) (pp. 199, 202-205)

[Demo code](machine_learning/1-intro+linear)

**4.** [ML] Decision trees. Bagging. Random forests. GBM. Ensembles I.

Trevor Hastie, Robert Tibshirani, Jerome Friedman: [The Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/printings/ESLII_print10.pdf), 2nd Edition, Ch. 9 (pp. 295, 305-312), Ch. 8 (pp. 282-286), Ch. 15 (pp. 587-594), Ch. 10 (pp. 337-340)

[Demo code](machine_learning/2-trees+ensembles/)

**5.** [ML] **Model evaluation and validation**: bias and variance, overfitting, training and test error, regularization, cross-validation, ROC curve, data leakage. Comparison of various supervised learning methods (accuracy)

Trevor Hastie, Robert Tibshirani, Jerome Friedman: [The Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/printings/ESLII_print10.pdf), 2nd Edition, Ch. 7 (pp. 219-223, 241-242, 244)

Rich Caruana, Alexandru Niculescu-Mizil: [An Empirical Comparison of Supervised Learning Algorithms](https://www.cs.cornell.edu/~caruana/ctp/ct.papers/caruana.icml06.pdf) (pp. 1-8)

[Demo code](machine_learning/3-model_eval)

...




