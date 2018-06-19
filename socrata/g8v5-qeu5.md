# CCRB: Age of Docket Measured from the Date of Incident 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-age-of-docket-measured-from-the-date-of-incident-2005-2009-35719) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/g8v5-qeu5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/g8v5-qeu5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/g8v5-qeu5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | g8v5-qeu5 |
| Name | CCRB: Age of Docket Measured from the Date of Incident 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, crime, year, age, demographics 2005, 2006, 2007, 2008, 2009, docket, incident |
| Created | 2011-09-12T18:15:21Z |
| Publication Date | 2011-09-12T18:15:21Z |

## Description

A statistical breakdown of the age of Civilian Complaint Review Board (CCRB)dockets, by year, measured from the date of the incidents in the years 2205 through 2009.The age of the docket is measured by the number of open cases at the end of each reporting period.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | age_of_case_in_months  | Age of Case in Months  | text      | text        |
| Yes      | numeric metric | 2005_number_of_cases   | 2005 Number of Cases   | number    | number      |
| Yes      | numeric metric | 2005_percent_of_docket | 2005 Percent of Docket | percent   | percent     |
| Yes      | numeric metric | 2006_number_of_cases   | 2006 Number of Cases   | number    | number      |
| Yes      | numeric metric | 2006_percent_of_docket | 2006 Percent of Docket | percent   | percent     |
| Yes      | numeric metric | 2007_number_of_cases   | 2007 Number of Cases   | number    | number      |
| Yes      | numeric metric | 2007_percent_of_docket | 2007 Percent of Docket | percent   | percent     |
| Yes      | numeric metric | 2008_number_of_cases   | 2008 Number of Cases   | number    | number      |
| Yes      | numeric metric | 2008_percent_of_docket | 2008 Percent of Docket | percent   | percent     |
| Yes      | numeric metric | 2009_number_of_cases   | 2009 Number of Cases   | number    | number      |
| Yes      | numeric metric | 2009_percent_of_docket | 2009 Percent of Docket | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:g8v5-qeu5 d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="0 - 4 months" m:2005_number_of_cases=2225 m:2008_percent_of_docket=57 m:2007_number_of_cases=2068 m:2006_number_of_cases=2370 m:2006_percent_of_docket=63.4 m:2009_percent_of_docket=60 m:2009_number_of_cases=2014 m:2005_percent_of_docket=64.2 m:2008_number_of_cases=2113 m:2007_percent_of_docket=61.6

series e:g8v5-qeu5 d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="5 - 7 months" m:2005_number_of_cases=623 m:2008_percent_of_docket=17.2 m:2007_number_of_cases=567 m:2006_number_of_cases=610 m:2006_percent_of_docket=16.3 m:2009_percent_of_docket=14.8 m:2009_number_of_cases=497 m:2005_percent_of_docket=18 m:2008_number_of_cases=638 m:2007_percent_of_docket=16.9

series e:g8v5-qeu5 d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="8 months" m:2005_number_of_cases=140 m:2008_percent_of_docket=4.2 m:2007_number_of_cases=135 m:2006_number_of_cases=167 m:2006_percent_of_docket=4.5 m:2009_percent_of_docket=4.4 m:2009_number_of_cases=147 m:2005_percent_of_docket=4 m:2008_number_of_cases=155 m:2007_percent_of_docket=4
```

## Meta Commands

```ls
metric m:2005_number_of_cases p:integer l:"2005 Number of Cases" t:dataTypeName=number

metric m:2005_percent_of_docket p:float l:"2005 Percent of Docket" t:dataTypeName=percent

metric m:2006_number_of_cases p:integer l:"2006 Number of Cases" t:dataTypeName=number

metric m:2006_percent_of_docket p:float l:"2006 Percent of Docket" t:dataTypeName=percent

metric m:2007_number_of_cases p:integer l:"2007 Number of Cases" t:dataTypeName=number

metric m:2007_percent_of_docket p:float l:"2007 Percent of Docket" t:dataTypeName=percent

metric m:2008_number_of_cases p:integer l:"2008 Number of Cases" t:dataTypeName=number

metric m:2008_percent_of_docket p:float l:"2008 Percent of Docket" t:dataTypeName=percent

metric m:2009_number_of_cases p:integer l:"2009 Number of Cases" t:dataTypeName=number

metric m:2009_percent_of_docket p:float l:"2009 Percent of Docket" t:dataTypeName=percent

entity e:g8v5-qeu5 l:"CCRB: Age of Docket Measured from the Date of Incident 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/g8v5-qeu5

property e:g8v5-qeu5 t:meta.view v:id=g8v5-qeu5 v:category="Public Safety" v:averageRating=0 v:name="CCRB: Age of Docket Measured from the Date of Incident 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:g8v5-qeu5 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:g8v5-qeu5 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| age_of_case_in_months | 2005_number_of_cases | 2005_percent_of_docket | 2006_number_of_cases | 2006_percent_of_docket | 2007_number_of_cases | 2007_percent_of_docket | 2008_number_of_cases | 2008_percent_of_docket | 2009_number_of_cases | 2009_percent_of_docket | 
| ===================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | 
| 0 - 4 months          | 2225                 | 64.20                  | 2370                 | 63.40                  | 2068                 | 61.60                  | 2113                 | 57.00                  | 2014                 | 60.00                  | 
| 5 - 7 months          | 623                  | 18.00                  | 610                  | 16.30                  | 567                  | 16.90                  | 638                  | 17.20                  | 497                  | 14.80                  | 
| 8 months              | 140                  | 4.00                   | 167                  | 4.50                   | 135                  | 4.00                   | 155                  | 4.20                   | 147                  | 4.40                   | 
| 9 months              | 98                   | 2.80                   | 131                  | 3.50                   | 129                  | 3.80                   | 145                  | 3.90                   | 154                  | 4.60                   | 
| 10 months             | 84                   | 2.40                   | 89                   | 2.40                   | 102                  | 3.00                   | 122                  | 3.30                   | 162                  | 4.80                   | 
| 11 months             | 73                   | 2.10                   | 97                   | 2.60                   | 77                   | 2.30                   | 134                  | 3.60                   | 86                   | 2.60                   | 
| 12 months             | 51                   | 1.50                   | 71                   | 1.90                   | 60                   | 1.80                   | 81                   | 2.20                   | 63                   | 1.90                   | 
| 13 months             | 27                   | 0.80                   | 52                   | 1.40                   | 52                   | 1.50                   | 73                   | 2.00                   | 60                   | 1.80                   | 
| 14 months             | 28                   | 0.80                   | 31                   | 0.80                   | 37                   | 1.10                   | 54                   | 1.50                   | 60                   | 1.80                   | 
| 15 months             | 31                   | 0.90                   | 38                   | 1.00                   | 34                   | 1.00                   | 53                   | 1.40                   | 31                   | 0.90                   | 
```