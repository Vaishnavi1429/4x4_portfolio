portfolio
4x4 training
Done by:
Varanasi Vaishnavi
21WU0101051
B. Tech - DS & AI
ABOUT
CEREBRATECH
"We’re thrilled to have you onboard as
part of our growing community.
Together, let’s innovate, learn, and build
solutions for tomorrow!"
"Cerebra Tech is a dynamic startup
specializing in developing end-to-end
projects using modern technologies.“
"Our mission is to deliver impactful
solutions while fostering a culture of
innovation and continuous learning."
Day - 1
The entire Python programming course was
covered in one intensive session. The
experience was engaging and insightful,
making it easy to grasp the concepts quickly.
Overview:
Assignments: Worked on 13 hands-on
assignments designed to cover all major
Python topics comprehensively.
Python Programming Bootcamp
Key Topics Covered:
Basics of Python: Variables, data types, and
operators.
Control Flow: If-else statements, loops, and
nested constructs.
Functions: Creating reusable code blocks andworking with parameters.
Data Structures: Lists, tuples, dictionaries,
and sets.
Object-Oriented Programming (OOP):
Classes, objects, inheritance, and
polymorphism.
Day - 2
mysql
Focused on understanding MySQL and its
usage for managing relational databases.
Overview:
Work done:
Learned MySQL Fundamentals: Covered
basic SQL operations such as SELECT,
INSERT, UPDATE, DELETE, and JOIN, as well
as understanding database schema,
normalization, and relationships between
tables.
Practice Questions: Completed 100 practice
interview questions to solidify the concepts
of MySQL. These questions helped in
mastering query writing, database
manipulation, and data retrieval techniques.
Solved 50 Challenging Questions: Tackled 50
questions from the training, applying
advanced SQL concepts like subqueries,
indexing, complex joins, and aggregate
functions. This hands-on practice improved
the ability to write efficient SQL queries and
troubleshoot database-related issues.
SELECT name, age FROM students WHERE age > 18;
Key Learning: Gained a deeper understanding
of how relational databases work, how to
manage large datasets, and how to optimize
queries for performance.
Hands-On Practice
Writing a query to retrieve data from a table:
Writing a query to retrieve data from a table:
INSERT INTO students (name, age, grade) VALUES ('John
Doe'
, 20,
'A');
Joining two tables to fetch data from both:
SELECT students.name, courses.course_name FROM students
INNER JOIN enrollments ON students.id =
enrollments.student_id INNER JOIN courses ON
enrollments.course_id = courses.id;
Using a subquery to get students who scored
above average:
SELECT name, score FROM students
WHERE score > (SELECT AVG(score) FROM students);
Day - 3
Learning NumPy, Pandas,
Matplotlib, and EDA
(Exploratory Data Analysis)
Numpy:
Focused on key data analysis libraries like
NumPy, Pandas, Matplotlib, and along with
performing Exploratory Data Analysis (EDA)
on datasets. Covered topics like detecting
outliers and addressing class imbalance.
Overview:
NumPy is a Python library for efficient
numerical computing, providing support for
multi-dimensional arrays and matrices. It
offers a wide range of mathematical
functions for operations on large datasets.
import numpy as np arr = np.array([1, 2, 3, 4])
print(np.mean(arr)) # Calculate mean
Pandas:
Pandas is a Python library for data
manipulation and analysis, providing flexible
data structures like DataFrames and Series.
It simplifies tasks like data cleaning,
transformation, and exploration with
intuitive indexing and powerful functions.
import pandas as pd
data = {'Name': ['Alice'
,
'Bob', 'Charlie'
, 'David'], 'Age':
[25, 30, np.nan, 22]}
df = pd.DataFrame(data)
df['Age'].fillna(df['Age'].mean(), inplace=True)
# Fill missing values with mean
Matplotlib:
Learned how to visualize data using
Matplotlib, creating different types of plots
like line charts, bar charts, and histograms.
import matplotlib.pyplot as plt
x = [1, 2, 3, 4]
y = [10, 20, 25, 30]
plt.plot(x, y)
plt.title('Line Plot')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
Exploratory Data Analysis
(EDA):
Performed EDA to understand the dataset's
structure, detect outliers, and handle class
imbalance.
Outliers: Identified outliers in the dataset
using statistical methods and visualizations.
Class Imbalance: Addressed class imbalance
by applying techniques like resampling and
using visualization methods to understand
the imbalance.
from imblearn.over_sampling import SMOTE
X_resampled, y_resampled = SMOTE().fit_resample(X,
y)
# Applying SMOTE for balancing classes
Key Learnings:
Data manipulation and visualization
techniques using NumPy, Pandas, and
Matplotlib.
Understood and applied key EDA
techniques for identifying outliers and
addressing class imbalance, which are
critical for preparing data before applying
machine learning algorithms.
Machine Learning:
Machine Learning is a branch of Artificial
Intelligence (AI) that focuses on building
systems capable of learning from data and
improving their performance over time
without explicit programming. ML
algorithms analyze large datasets to
identify patterns, make predictions, or take
decisions based on input data.
Types of Machine Learning:
Supervised Learning
unsupervised Learning
Reinforcement Learning
Real-World Applications:
Healthcare
Finance
Retail
Transportation
Typical ML Workflow:
Data Collection
Data Preprocessing
Model Selection
Training
Evaluation
Deployment
The goal of an email spam classifier is to
categorize emails as:
Spam (Unwanted emails, promotional
content, phishing emails) or
Ham (Legitimate, personal, or businessrelated emails).
This is a binary classification problem, and
Logistic Regression is well-suited for this
task because it predicts probabilities that
can be converted into binary labels.
Dataset
Features: Typically, the email content (text)
is used as the primary feature.
Target: Binary labels:
0 for Spam
1 for Ham
Common pre-processing steps include
removing duplicates, handling missing
values, and encoding categorical labels.
Machine Learning Project:
Email Spam Classifier
Day - 4
Key Topics Covered:
Introduction to Neural Networks
Activation Functions
Deep Learning:
Deep Learning Project:
Hand Digit Recognition:
Hand-written digit recognition aims to
identify digits (0-9) from images,
commonly using the MNIST dataset.
The process involves normalizing images,
building a neural network model with
layers like Flatten and Dense, and
training it with a loss function such as
Sparse Categorical Crossentropy.
After training, the model is evaluated for
accuracy and can be deployed for realtime recognition tasks using libraries like
TensorFlow and Keras.
