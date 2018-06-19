# CCRB: Age of Docket Measured from the Date of Report 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-age-of-docket-measured-from-the-date-of-report-2005-2009-d60c2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7atn-adw6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7atn-adw6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7atn-adw6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7atn-adw6 |
| Name | CCRB: Age of Docket Measured from the Date of Report 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, crime, year, age, demographics 2005, 2006, 2007, 2008, 2009, docket, incident, report |
| Created | 2011-09-12T18:22:22Z |
| Publication Date | 2011-09-12T18:22:22Z |

## Description

A statistical breakdown of the age of Civilian Complaint Review Board (CCRB) dockets, by year, measured from the date of the reports in the years 2205 through 2009. The age of the docket is measured by the number of open cases at the end of each reporting period.

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
series e:7atn-adw6 d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="0 - 4 months" m:2005_number_of_cases=2343 m:2008_percent_of_docket=60.6 m:2007_number_of_cases=2208 m:2006_number_of_cases=2516 m:2006_percent_of_docket=67.3 m:2009_percent_of_docket=62.6 m:2009_number_of_cases=2102 m:2005_percent_of_docket=67.6 m:2008_number_of_cases=2247 m:2007_percent_of_docket=65.8

series e:7atn-adw6 d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="5 - 7 months" m:2005_number_of_cases=578 m:2008_percent_of_docket=16.5 m:2007_number_of_cases=546 m:2006_number_of_cases=577 m:2006_percent_of_docket=15.4 m:2009_percent_of_docket=14.7 m:2009_number_of_cases=492 m:2005_percent_of_docket=16.7 m:2008_number_of_cases=612 m:2007_percent_of_docket=16.3

series e:7atn-adw6 d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="8 months" m:2005_number_of_cases=145 m:2008_percent_of_docket=4.4 m:2007_number_of_cases=126 m:2006_number_of_cases=153 m:2006_percent_of_docket=4.1 m:2009_percent_of_docket=4.3 m:2009_number_of_cases=145 m:2005_percent_of_docket=4.2 m:2008_number_of_cases=163 m:2007_percent_of_docket=3.8
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

entity e:7atn-adw6 l:"CCRB: Age of Docket Measured from the Date of Report 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/7atn-adw6

property e:7atn-adw6 t:meta.view v:id=7atn-adw6 v:category="Public Safety" v:averageRating=0 v:name="CCRB: Age of Docket Measured from the Date of Report 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:7atn-adw6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7atn-adw6 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| age_of_case_in_months | 2005_number_of_cases | 2005_percent_of_docket | 2006_number_of_cases | 2006_percent_of_docket | 2007_number_of_cases | 2007_percent_of_docket | 2008_number_of_cases | 2008_percent_of_docket | 2009_number_of_cases | 2009_percent_of_docket | 
| ===================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | 
| 0 - 4 months          | 2343                 | 67.60                  | 2516                 | 67.30                  | 2208                 | 65.80                  | 2247                 | 60.60                  | 2102                 | 62.60                  | 
| 5 - 7 months          | 578                  | 16.70                  | 577                  | 15.40                  | 546                  | 16.30                  | 612                  | 16.50                  | 492                  | 14.70                  | 
| 8 months              | 145                  | 4.20                   | 153                  | 4.10                   | 126                  | 3.80                   | 163                  | 4.40                   | 145                  | 4.30                   | 
| 9 months              | 78                   | 2.20                   | 135                  | 3.60                   | 119                  | 3.50                   | 132                  | 3.60                   | 159                  | 4.70                   | 
| 10 months             | 90                   | 2.60                   | 74                   | 2.00                   | 85                   | 2.50                   | 108                  | 2.90                   | 145                  | 4.30                   | 
| 11 months             | 58                   | 1.70                   | 85                   | 2.30                   | 74                   | 2.20                   | 122                  | 3.30                   | 68                   | 2.00                   | 
| 12 months             | 36                   | 1.00                   | 47                   | 1.30                   | 43                   | 1.30                   | 78                   | 2.10                   | 66                   | 2.00                   | 
| 13 months             | 34                   | 1.00                   | 50                   | 1.30                   | 37                   | 1.10                   | 76                   | 2.00                   | 57                   | 1.70                   | 
| 14 months             | 20                   | 0.60                   | 21                   | 0.60                   | 40                   | 1.20                   | 51                   | 1.40                   | 48                   | 1.40                   | 
| 15 months             | 32                   | 0.90                   | 39                   | 1.00                   | 23                   | 0.70                   | 33                   | 0.90                   | 26                   | 0.80                   | 
```