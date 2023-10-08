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
| Q4 | Family highest educaitonal background | Categorical (ordinal) |	{diploma, degree, masters, PhD, high school, high school dropout, no education} |
| Q5 | Extra tutorial given? | Categorical (ordinal) | {Yes, No} |
| Q6 | Grade 10 GPA | Categorical (ordinal) | {2–2.5, 2.5–3, 3–3.5, 3.5–4} |
| Q7 | Parent occupation | Categorical (nominal) |	{Civil servant, Artisan, Trading/merchant, Military} |
| Q8 | Does the student think education is good for future growth?	| Categorical (nominal)	| {Yes, No} |

If you are using this dataset, please cite our paper:

Yekun, Ephrem Admasu, and Abrahaley Teklay Haile. "Student performance prediction with optimum multilabel ensemble model." Journal of Intelligent Systems 30.1 (2021): 511-523.
```
@article{yekun2021student,
  title={Student performance prediction with optimum multilabel ensemble model},
  author={Yekun, Ephrem Admasu and Haile, Abrahaley Teklay},
  journal={Journal of Intelligent Systems},
  volume={30},
  number={1},
  pages={511--523},
  year={2021},
  publisher={De Gruyter}
}
```

