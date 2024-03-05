# SkilHarvest-Data-Analysis
This is where I documented my first project while learning data analysis with SkilHarvest

## Data Source
Data was gotten from skilharvet instructor named SkilHarvest-stationary-supplies [Download Here](https://docs.google.com/spreadsheets/d/1kIvUpU3t4_vJs3SVGH7i9hhOciQ8FELTxFv4CDy7WVA/edit#gid=32712049) 

## Data Analysis
Tools used for this analysis are; 
- Google Query
- PowerBI
  
    Using google query to analyse the data at hand, 
  
#### 1. Sales of binder items and pencil in 2015
```
=QUERY(A1:H44, "SELECT C,H,F WHERE (C='Binder' OR C='Pencil')AND F=2015",1)
```
![](SSGREEN.png)

#### 2. Sales in Central and East region in 2014
```
=QUERY(A:H,"SELECT A,H,F WHERE (A='Central' OR A='East') AND F=2014",1)
```
![](Screenshotpurple.png)

#### 3. Sales in August and September 2014
```
=QUERY(A1:H44,"SELECT E,H,F WHERE (E='Aug' OR E='Sep')AND F=2014",1)
```
![](SSBLUE.png)

#### 4. Show sales of items that start with Pen, include their region, sales rep and year.

```
=QUERY(A:H,"SELECT A,B,C,H,F WHERE C LIKE 'Pen%'",1)
```

<div align="center">
<img src="SStealgreen.png"
</div>


#### 5. Sales of items that end with ‘sk’, include their region, sales rep and year
```
=QUERY(A:H,"SELECT C,A,B,F WHERE C LIKE '%sk'",1)
```

<div align="center">
<img src="screenshotone.png"
</div>

## Data Visualization
<div align="center">  
<img src="firstpowerbi.png"
</div>
  
## Data Analysis
The basic lines of codes used during analysis on SkilHarvest Stationary supply are thus;
```
=QUERY(A1:H44,"SELECT C,H,F WHERE (C='Binder' OR C='Pencil')AND F=2015",1)
=QUERY(A:H,"SELECT A,H,F WHERE (A='Central' OR A='East') AND F=2014",1)
=QUERY(A1:H44,"SELECT E,H,F WHERE (E='Aug' OR E='Sep')AND F=2014",1)
=QUERY(A:H,"SELECT A,B,C,H,F WHERE C LIKE 'Pen%'",1)
=QUERY(A:H,"SELECT C,A,B,F WHERE C LIKE '%sk'",1)
```
## Result/Findings
This is the insight gotten from the analysis made on this project.

<div align="center"> <img src="Screenshotpurple.png" </div>

![](Screenshotpurple.png)
