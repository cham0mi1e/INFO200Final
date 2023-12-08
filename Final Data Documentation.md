# Data Documentation

## Data Sources
Our original datasets both came from the Center for Disease Control (CDC); here
is the [2000 data](https://www.cdc.gov/nchs/nhis/1997-2018.htm) and here is the
[2020 data](https://www.cdc.gov/nchs/nhis/2020nhis.htm).

## Our Variables
1. year - This variable represents the year that the observation was collected.  
2. race - This variable represents the self-reported race of each observation.  
3. sex - This variable represents the sex of each observation.  
4. lowerBoundIncome - This variable represents the lower bound of the
observation's household income.  
5. upperBoundIncome - This variable represents the upper bound of the
observation's household income.  
6. whiteOrNot - This variable represents whether or not the observation
identified their race as white.  
7. diagnosisStatus - This variable represents if the observation has recieved an
ADHD diagnosis.  

## Summary Statistics
Number of Rows: 12514
Number of Columns: 7  

### Missing/Invalid Values  
Our only invalid values were in the originial dataset in the ADDEV column (we
renamed this column to diagnosisStatus). We removed all of the observations that
were never surveyed regarding their ADHD diagnosis - a value of 0 corresponding
to 'NIU' or 'not in universe'.