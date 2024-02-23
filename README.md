

### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 17.02.2024
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
#### Training Data Set -> Buying Table
<img width="272" alt="305595571-e7c05833-7194-4952-bbc1-943642366884" src="https://github.com/RuchithaReddy28/WDM_EXP2/assets/93427261/b32ec4f4-aebf-4695-b0dc-d6316e5c9345">

#### Training Data Set -> Banking Table
<img width="270" alt="305595573-647d9744-0e52-4215-8c9c-7cba912d7b04" src="https://github.com/RuchithaReddy28/WDM_EXP2/assets/93427261/f4ed433b-91b9-4d3b-845f-028e002341a9">

#### Training Data Set -> Employee Table
<img width="161" alt="305595601-eb091ca3-a3c8-4fc6-9574-0dd43b39372a" src="https://github.com/RuchithaReddy28/WDM_EXP2/assets/93427261/f3dbe541-6fb4-4fcc-8292-443869772861">


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
#### Buying Table
<img width="609" alt="305595623-cd517b4e-4661-491b-bf3a-43095c245873" src="https://github.com/RuchithaReddy28/WDM_EXP2/assets/93427261/5a056943-6066-4d7d-a67f-3d6d77bb3fde">

#### Banking Table
<img width="578" alt="305595661-7a9743c5-253d-4307-a38f-b710086af36c" src="https://github.com/RuchithaReddy28/WDM_EXP2/assets/93427261/039530c4-a97d-4a0e-9bf8-c61fedde25da">

#### Employee Table
<img width="539" alt="305595699-8d7e624f-e76a-438f-bbe5-d52646b21fd1" src="https://github.com/RuchithaReddy28/WDM_EXP2/assets/93427261/c5f78097-5815-4cec-9363-6fbbd6b43e10">

### RESULT: 
Thus this program has been successfully executed.
