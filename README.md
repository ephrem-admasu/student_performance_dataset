## Dataset Description

This is a dataset used for student performance prediction of three public high schools in Mekelle City, Ethiopia.
The dataset is represented as a multilabel prediction task where 21 features are used as input and 5 target values as output. The summary of the input features is given as follows:

| Feature Symbol | Description | Type | Possible Values |
| -------------- | ----------- | ---- | --------------- |
| Sex            | Gender of student | Categorical (nominal) | Female or Male |
| Age            | Age of student | Numerical | [1, 100] |
| Eng1, Eng2, Math1, Math2, etc. | Score obtained by a student in semester 1 or 2) |	Numerical | [0, 100] |
| Q1 | Quality of education | Categorical (nominal) | {Excellent, Very good, Good, Satisfactory, Bad, Very bad} |
| Q2 | Legal guardians | Categorical (nominal) | {mother and father, father only, mother only, siblings, other, live alone} |
| Q3 | Family income | Categorical (ordinal) | {<5000, 5000–10000, 10000–20000, >20000} |


