# EX-02 Generating Association Rules for Employee dataset using Apriori Algorithm 
<br>

### Aim: 
To generate associate rules for the employee dataset using Apriori Algorithm. &emsp;**DATE: 00.00.2024**

### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:

### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.<br>
<br>
<table align=center>
<tr>
<td>
  
**Buying Data:**
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
  </td>
</tr>
</table>

<br>
3) After that the file is saved with .arff file format.<br>
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.<br>
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.<br>
6) In that dialog box there are four modes, click on explorer.<br>
7) Explorer shows many options. In that click on ‘open file’ and select the arff file.<br>
8) Click on edit button which shows buying table on weka.<br>
<br>

### Ouptut:
<img height=24% width=30% src="https://github.com/user-attachments/assets/8122097f-9ca5-4253-8087-3ae8b6b784f1">


### Procedure for Association Rules:
1) Start -> Programs -> Weka-3-4 -> Explorer -> Open File -> buying.arff.
2) Select Associate option on the top of the Menu bar.
3) Select Choose button and then click on Apriori Algorithm.
4) Click on Start button and output will be displayed on the right side of the window.

### Output:
<img height=50% width=90% src="https://github.com/user-attachments/assets/3a779e17-fa8c-484c-ae3e-40bcb31fb96d">


### Result: 
Thus, generation of association rules using apriori algorithm is executed succesfully.
<br>
<br>
###### Developed by: Deepika S
###### RegisterNumber: 212222230028
