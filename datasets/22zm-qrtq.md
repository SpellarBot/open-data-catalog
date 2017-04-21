# CCRB: Age of Substantiated Cases Measured from the Date of Report 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-age-of-substantiated-cases-measured-from-the-date-of-report-2005-2009-ad1f3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/22zm-qrtq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/22zm-qrtq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/22zm-qrtq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 22zm-qrtq |
| Name | CCRB: Age of Substantiated Cases Measured from the Date of Report 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, crime, year, age, demographics 2005, 2006, 2007, 2008, 2009, docket, incident, report, substantiation, substantiated |
| Created | 2011-09-12T18:40:01Z |
| Publication Date | 2011-09-12T18:40:01Z |

## Description

A statistical breakdown of the age of Civilian Complaint Review Board (CCRB) substantiated cases, by year, measured from the date of the reports in the years 2205 through 2009.The age of the docket is measured by the number of open cases at the end of each reporting period.

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
series e:22zm-qrtq d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="3 or younger" m:2005_number_of_cases=11 m:2008_percent_of_docket=0 m:2007_number_of_cases=2 m:2006_number_of_cases=16 m:2006_percent_of_docket=6.1 m:2009_percent_of_docket=0 m:2009_number_of_cases=0 m:2005_percent_of_docket=4.2 m:2008_number_of_cases=0 m:2007_percent_of_docket=0.9

series e:22zm-qrtq d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="4 months" m:2005_number_of_cases=12 m:2008_percent_of_docket=1.9 m:2007_number_of_cases=10 m:2006_number_of_cases=21 m:2006_percent_of_docket=8 m:2009_percent_of_docket=0.5 m:2009_number_of_cases=1 m:2005_percent_of_docket=4.6 m:2008_number_of_cases=3 m:2007_percent_of_docket=4.6

series e:22zm-qrtq d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="5 months" m:2005_number_of_cases=21 m:2008_percent_of_docket=4.3 m:2007_number_of_cases=30 m:2006_number_of_cases=27 m:2006_percent_of_docket=10.2 m:2009_percent_of_docket=1 m:2009_number_of_cases=2 m:2005_percent_of_docket=8.1 m:2008_number_of_cases=7 m:2007_percent_of_docket=13.9
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

entity e:22zm-qrtq l:"CCRB: Age of Substantiated Cases Measured from the Date of Report 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/22zm-qrtq

property e:22zm-qrtq t:meta.view v:id=22zm-qrtq v:category="Public Safety" v:averageRating=0 v:name="CCRB: Age of Substantiated Cases Measured from the Date of Report 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:22zm-qrtq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:22zm-qrtq t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| age_of_case_in_months | 2005_number_of_cases | 2005_percent_of_docket | 2006_number_of_cases | 2006_percent_of_docket | 2007_number_of_cases | 2007_percent_of_docket | 2008_number_of_cases | 2008_percent_of_docket | 2009_number_of_cases | 2009_percent_of_docket | 
| ===================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | 
| 3 or younger          | 11                   | 4.20                   | 16                   | 6.10                   | 2                    | 0.90                   | 0                    | 0.00                   | 0                    | 0.00                   | 
| 4 months              | 12                   | 4.60                   | 21                   | 8.00                   | 10                   | 4.60                   | 3                    | 1.90                   | 1                    | 0.50                   | 
| 5 months              | 21                   | 8.10                   | 27                   | 10.20                  | 30                   | 13.90                  | 7                    | 4.30                   | 2                    | 1.00                   | 
| 6 months              | 19                   | 7.30                   | 21                   | 8.00                   | 21                   | 9.70                   | 9                    | 5.60                   | 5                    | 2.50                   | 
| 7 months              | 23                   | 8.80                   | 23                   | 8.70                   | 16                   | 7.40                   | 16                   | 9.90                   | 10                   | 5.10                   | 
| 8 months              | 21                   | 8.10                   | 23                   | 8.70                   | 25                   | 11.60                  | 10                   | 6.20                   | 11                   | 5.60                   | 
| 9 months              | 17                   | 6.50                   | 22                   | 8.30                   | 17                   | 7.90                   | 16                   | 9.90                   | 9                    | 4.60                   | 
| 10 months             | 24                   | 9.20                   | 19                   | 7.20                   | 17                   | 7.90                   | 7                    | 4.30                   | 20                   | 10.20                  | 
| 11 months             | 12                   | 4.60                   | 22                   | 8.30                   | 9                    | 4.20                   | 18                   | 11.20                  | 21                   | 10.70                  | 
| 12 months             | 26                   | 10.00                  | 19                   | 7.20                   | 19                   | 8.80                   | 18                   | 11.20                  | 18                   | 9.10                   | 
```