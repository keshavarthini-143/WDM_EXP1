### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 27.07.2026
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
<img width="1236" height="740" alt="626647553-40f51f31-f7aa-48be-baac-996344c65b12" src="https://github.com/user-attachments/assets/e3c5fdc9-8d45-429e-8755-bb6151c3b8f3" />

<img width="593" height="392" alt="626648157-749bb836-853c-4477-9908-b3699cbcb1db" src="https://github.com/user-attachments/assets/e0aa4ea7-a4ca-40f1-b4d0-a350f92f8a73" />

### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1227" height="733" alt="626647803-27971982-ebbe-4f58-b436-67bd07ebfa41" src="https://github.com/user-attachments/assets/04ef04a0-b84b-459e-af4c-010d4b837b80" />

<img width="705" height="421" alt="626648488-3a2fa519-5b65-4a6e-bf24-ed439e2941f4" src="https://github.com/user-attachments/assets/e514a0f0-bc01-40ba-9319-8a4bc25a6fe2" />

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

<img width="1227" height="735" alt="626647877-d539704a-bda0-44b1-9e55-5d1ef56e56c7" src="https://github.com/user-attachments/assets/4f9cd029-498b-4e23-9ecc-9a4110d0f4bc" />

<img width="686" height="457" alt="626648605-e4ac7d21-920f-438b-98ab-49e30fb9764a" src="https://github.com/user-attachments/assets/c40cb8cd-700a-45ef-876a-a4c648823502" />

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
<img width="816" height="701" alt="626648081-7ed8c63f-ff5b-4290-a9b8-b8932b761428" src="https://github.com/user-attachments/assets/7b013d10-0a96-46a1-b7cc-f39008084fad" />

<img width="773" height="627" alt="626648654-95b9465b-40db-4239-bb43-482fc04f749f" src="https://github.com/user-attachments/assets/f0596f12-fde2-41aa-8735-34ffef2584d5" />

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
