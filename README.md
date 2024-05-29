# Welcome to 3050571 Pracical Clinical Data Science
This is the repository for the learning materials from the **3050571: Pracical Clinical Data Science** course taught by our group at the Faculty of Medicine, Chulalongkorn University in Bangkok, Thailand in Spring 2024.

Lectures were taught in Thai but the slides and assignments are in English.

## Announcements
* **Location**: Classes will be held in the conference room at **Bhumisiri Building, 8th Floor, Zone C** (look for Stem Cell Center)
* **Time**: See the [schedule](https://github.com/cmb-chula/clini-data-science-3050571/blob/main/3050571_syllabus_schedule.pdf) for more details
  * Lecture and recitation on Tuesday and Thursday 1-2pm (except the first class on Jan 30 which will be 1-3pm)
  * Python workshop on Friday 1-3pm (**bring your computer**, except on March 8 which will be a recitation) + Wednesday March 6
* **Contact**:
  * Post your questions / comments in the [Discussion](https://github.com/cmb-chula/clini-data-science-3050571/discussions)
  * Emails and phone numbers for myself and TAs will be given in the first class

## What can you find here?
1. Lecture and recitation slides
2. Assigned online video and readings
3. Python notebooks and data files for the practical sessions

## Course structure
This is a 6-week course that mixes independent study of online contents with in-class recitation and Python workshop. The total assigned videos range from 1-3 hours for each session. Assignments include [Kaggle Python modules](https://www.kaggle.com/learn) and analysis of public clinical datasets. Half of the course involve an active intership with the Data Team at King Chulalongkorn Memorial Hospital where students are expected to participate in drafting solutions for real-world use cases.

### Key topics
1. Computational thinking
2. Python programming for data science
3. Machine learning
4. AI in healthcare and hospital management

### Recommended prerequisites
* [MIT 6.0001 Introduction to Python programming](https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/)
* Some familiarity with the syntax of a programming language

### Recommended extra resources
* [MIT 6.S191 Deep Learning & AI](https://www.youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI) provides deeper knowledge of deep learning and artificial intelligence beyond this course.
* [University of Tubingen Intro to ML](https://www.youtube.com/playlist?list=PL05umP7R6ij35ShKLDqccJSDntugY4FQT) provides more rigorous understanding of machine learning.
* [MIT 6.0002 Computational Thinking](https://www.youtube.com/playlist?list=PLUl4u3cNGP619EG1wp0kT-7rDE_Az5TNd) dedicates more time to problem-solving and computational thinking practice with Python.
* [MIT 6.S897 ML for Healthcare](https://ocw.mit.edu/courses/6-s897-machine-learning-for-healthcare-spring-2019/) covers more real-world applications of AI in healthcare.
* [StatQuest YouTube channel](https://www.youtube.com/@statquest) presents bite-size visual explanation of computational techniques.

## Timeline for internship with hospital data team
* Pick a problem they want to tackle by **Week 2**
* Submit a draft proposal on how to solve the problem by **Week 3** and a refined proposal by **Week 4**
* Work with the data team to test the proposed solution
* Present the findings and progress at the end of the course on **Week 6**

## Week 1 - Computational Thinking
### Key learning points
* What is computational thinking and how do you apply it to solve problem?
* How to systematically approach a problem?

### Assigned study
* Computational Thinking [video](https://www.youtube.com/watch?v=qbnTZCj0ugI) and [reading](https://www.americanscientist.org/article/computational-thinking-in-science)
* A perspective on programming vs coding [first 3 min](https://www.youtube.com/watch?v=rkZzg7Vowao)
*	[Three (3) things to do when starting out in Data Science](https://www.youtube.com/watch?v=ilUbD7EoQnk)
*	Optimization problem from MIT 6.0002 [Lecture 1](https://www.youtube.com/watch?v=C1lhuz6pZC0) and [Lecture 2](https://www.youtube.com/watch?v=uK5yvoXnkSk)

### Assigned practice
*	[Python code editors](https://www.youtube.com/watch?v=5pf0_bpNbkw)
*	Kaggle [Intro to programming](https://www.kaggle.com/learn/intro-to-programming) and [Python](https://www.kaggle.com/learn/python) lessons

## Week 2 - Data Exploration and Storytelling
### Key learning points
* What can (and can't) the data tell us?
* What are the right statistical & analytical techniques for your hypothesis?
* How to pick the right graphs to tell your story?

### Assigned study
#### Statistics and probability
* MIT 6.0002 [Stochastic Thinking](https://www.youtube.com/watch?v=-1BnXEwHUok) and [Sampling](https://www.youtube.com/watch?v=soZv_KKax3E)
* StatQuest [Hypothesis Testing](https://www.youtube.com/watch?v=0oc49DyA3hU), [P-value](https://www.youtube.com/watch?v=vemZtEM63GY), and [Maximum Likelihood](https://www.youtube.com/watch?v=XepXtl9YKwc) clips
* **Extra**: MIT 18.05 summary notes on [Probability](https://ocw.mit.edu/courses/18-05-introduction-to-probability-and-statistics-spring-2022/resources/mit18_05_s22_probability_pdf/) and [Statistics](https://ocw.mit.edu/courses/18-05-introduction-to-probability-and-statistics-spring-2022/resources/mit18_05_s22_statistics_pdf/). You are not expected to understand everything in this class, but you should understand everything for your future career.

#### Data handling and visualization
* [Exploratory data analysis with Python](https://www.youtube.com/watch?v=xi0vhXFPegw)
* [Basic visualization with Python](https://www.youtube.com/watch?v=UO98lJQ3QGI)
* [Story telling with graphs design](https://www.youtube.com/watch?v=Hfx1X9WSGYQ)

### Assigned homework
*	Kaggle [Data Handling](https://www.kaggle.com/learn/pandas) (for tabular data) and [Visualization](https://www.kaggle.com/learn/data-visualization) lessons
* Kaggle [Titanic Dataset](https://www.kaggle.com/competitions/titanic)
  * Explore the data. Develop and test some hypotheses regarding the passengers of the Titanic.
  * Visualize the patterns to tell something interesting
  * For example, what were the demographics of the passengers? Who were the survivors? Which factors did you think are predictive of survival? Did the data agree or disagree?

## Week 3 - Unsupervised Learning
### Key learning points
* How can we learn from unlabeled data (such as clinical data without diagnosis result)?
* How do dimensionality reduction and clustering techniques work? What are the pros and cons? How to interpret?

### Assigned study
#### Dimensionality reduction
* The first 24 minutes of Andrew Ng's [Dimensionality Reduction](https://www.youtube.com/watch?v=pAwjiGkafbM) lecture
* StatQuest Principal Component Analysis (PCA)'s [Concept](https://www.youtube.com/watch?v=FgakZw6K1QQ) and [Practical Points](https://www.youtube.com/watch?v=oRvgq966yZg)
* **Extra**: PCA explanations from [Steve Brunton](https://www.youtube.com/watch?v=Oi4SJqJIL2E) and [University of Tubingen](https://www.youtube.com/watch?v=xBf_LZ5ZgY4)
* The first 33 minutes of University of Tubingen's [Manifold and t-SNE](https://www.youtube.com/watch?v=MnRskV3NY1k) lecture
* StatQuest [t-distributed Stochastic Neighbor Embedding](https://www.youtube.com/watch?v=NEaUSP4YerM)

#### Clustering
* MIT 6.0002 introduction to [Clustering](https://www.youtube.com/watch?v=esmzYhuFnds)
* StatQuest [k-Mean](https://www.youtube.com/watch?v=4b5d3muPQmA), [Hierarchical Clustering](https://www.youtube.com/watch?v=7xHsRkOdVwo), and [DBSCAN](https://www.youtube.com/watch?v=RDZUdRSDOok) explanation
* More technical explanation on k-mean from the first 23 minutes of [University of Tubingen](https://www.youtube.com/watch?v=mU3GZaOoVDA)
* **Extra**: Introduction to network-based clustering from [Stanford University](https://www.youtube.com/playlist?list=PLLssT5z_DsK9JDLcT8T62VtzwyW9LNepV) [Lecture 24, 28, and 29]

### Assigned homework
*	Kaggle [Data Cleaning](https://www.kaggle.com/learn/data-cleaning) lesson
*	Python for Health Data Science's exercises on [Emergency Department](https://www.pythonhealthdatascience.com/content/02_stat_prog/03_exercises/01_data_wrangling_matplotlib.html), [Stroke](https://www.pythonhealthdatascience.com/content/02_stat_prog/03_exercises/02_stroke_data_wrangling.html), and [Readmission](https://www.pythonhealthdatascience.com/content/02_stat_prog/03_exercises/03_visualise_ts.html) datasets
* [Operating Room Utilization](https://www.kaggle.com/datasets/drjfalk/operating-room-utilization) by a Kaggle User
  * Summarize and visualize the activity of operating room at this hospital.
  * Extract knowledge. For example, which type of operations occupy the room the longest? Did booked time match well with actual usage?
* **Extra**: [Colorectal Cancer Molecular Subtyping](https://www.nature.com/articles/nm.3967)
  * Get the [clinical](https://www.synapse.org/#!Synapse:syn2325330) and [gene expression](https://www.synapse.org/#!Synapse:syn2325328) data (n = 604, Synapse registration required)
  * Use unsupervised learning technique on gene expressiondata to identify patient subgroups
  * Test your subgroups with clinical data

## Week 4 - Supervised Learning
### Key learning points
* How does the computer learn to make prediction?
* What are the key parameters describing each model? How can we optimize them using our data?

### Assigned study
#### Principles of machine learning
* MIT 6.0002 [Machine Learning](https://www.youtube.com/watch?v=h0e2HAPTGF4) and [Classification](https://www.youtube.com/watch?v=eg8DJYwdMyg)
* StatQuest [Ridge Regression](https://www.youtube.com/watch?v=Q81RR3yKn30), [LASSO Regression](https://www.youtube.com/watch?v=NGf0voTMlcs), [Logistic Regression Part 1](https://www.youtube.com/watch?v=vN5cNN2-HWE), [Logistic Regression Part 2](https://www.youtube.com/watch?v=BfKanl1aSG0), and [Support Vector Machine](https://www.youtube.com/watch?v=efR1C6CvhmE)
* StatQuest [Bias vs Variance Tradeoff](https://www.youtube.com/watch?v=EuBBz3bI-aA) principle

#### Tree models
* StatQuest [Decision Tree](https://www.youtube.com/watch?v=_L39rN6gz7Y), [Random Forest](https://www.youtube.com/watch?v=J4Wdy0Wc_xQ), and [Adaptive Boosting](https://www.youtube.com/watch?v=LsK-xG1cLYA)
* StatQuest [XGBoost library in Python](https://www.youtube.com/watch?v=GrJP9FLV3FE)

### Assigned homework
* Kaggle [Intro to ML](https://www.kaggle.com/learn/intro-to-machine-learning) and [Intermediate ML](https://www.kaggle.com/learn/intermediate-machine-learning) lessons
* Predicting hospital admission using Emergency Department dataset from [Hong, W.S. *et al*. PLOS ONE 2018](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0201016) 

## Week 5 - Introduction to Deep Learning and AI
### Key learning points
* What are deep learning and artificial neural network?
* How did modern AI emerge? Why is AI so powerful today?

### Assigned study
#### Artificial intelligence
* An introduction by [COMPSCI188](https://www.youtube.com/watch?v=16Dir4QqCUg) at UC Berkeley
* Stanford webminar on [How can AI improve healthcare?](https://www.youtube.com/watch?v=7rs79MUDId0)
* TEDx talk by [A Doctor Who Code](https://www.youtube.com/watch?v=Et5HC8SR0BA)

#### Deep learning
* MIT 6.S191 [Introduction to Deep Learning](https://www.youtube.com/watch?v=QDX-1M5Nj7s) and [Convolutional Neural Network](https://www.youtube.com/watch?v=NmLK_WQBxB4)
* **Extra**: MIT 6.S191 [Recurrent Neural Network, Transformer, and Attention](https://www.youtube.com/watch?v=ySEx_Bqxvvo) and [Reinforcement Learning](https://www.youtube.com/watch?v=AhyznRSDjw8)

### Assigned homework
* Kaggle [Deep Learning](https://www.kaggle.com/learn/intro-to-deep-learning) and [Computer Vision](https://www.kaggle.com/learn/computer-vision) lessons
* Kaggle [Digit MNIST Dataset](https://www.kaggle.com/competitions/digit-recognizer)
  * Use unsupervised learning technique to visualize the data
  * Develop linear, tree, and artificial neural network models
* **Extra**: [Chula's COVID-19 Home Isolation Dataset](https://github.com/cmb-chula/cu-covid19-isolation/tree/main)
  * Predict whether a particular patient will develop pneumonia and be admitted to a hospital within 3 days

## Week 6 - AI Explainability and Pitfall
### Key learning points
* How can we understand decisions made by the model?
* What should we be concerned about when developing a medical AI?

### Assigned study
#### Explainability
* Stanford webminar on [Motivation](https://www.youtube.com/watch?v=_DYQdP_F-LA), [Explainability Techniques (first 30 min)](https://www.youtube.com/watch?v=_6n8r523QP8), and [How to Evaluate (first 40 min)](https://www.youtube.com/watch?v=htjpbbvHJQo)
* MIT 6.S191 [Robustness and Trustworthiness](https://www.youtube.com/watch?v=kIiO4VSrivU)

#### AI project design
* Stanford symposium on [Responsible Implementation of AI in Healthcare](https://www.youtube.com/watch?v=RCIleZj3rp8)
* TensorFlow tech talk on [Building AI Models for Healthcare](https://www.youtube.com/watch?v=UZEstizNxkg) and [Best Practices for ML Product Decisions](https://www.youtube.com/watch?v=2aWh3-Wnb-A)

### Assigned homework
* Kaggle [Explainability](https://www.kaggle.com/learn/machine-learning-explainability) lesson
* A CVPR 2021 [CXR tutorial on Explainability](https://alistairewj.github.io/talk/2021-cvpr-cxr-tutorial/) by Dr. Alistair Johnson with both video and Google Colab notebook
