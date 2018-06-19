# CCRB: Age of Substantiated Cases Measured from the Date of Incident 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-age-of-substantiated-cases-measured-from-the-date-of-incident-2005-2009-8bb8f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jgjk-h2bn) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jgjk-h2bn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jgjk-h2bn/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jgjk-h2bn |
| Name | CCRB: Age of Substantiated Cases Measured from the Date of Incident 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | 2009, docket, incident, report, substantiation, substantiated |
| Created | 2011-09-12T18:32:24Z |
| Publication Date | 2011-09-12T18:32:24Z |

## Description

A statistical breakdown of the age of Civilian Complaint Review Board (CCRB) substantiated cases, by year, measured from the date of the incidents in the years 2205 through 2009.The age of the docket is measured by the number of open cases at the end of each reporting period.

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
series e:jgjk-h2bn d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="3 or younger" m:2005_number_of_cases=8 m:2008_percent_of_docket=0 m:2007_number_of_cases=2 m:2006_number_of_cases=13 m:2006_percent_of_docket=4.9 m:2009_percent_of_docket=0 m:2009_number_of_cases=0 m:2005_percent_of_docket=3.1 m:2008_number_of_cases=0 m:2007_percent_of_docket=0.9

series e:jgjk-h2bn d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="4 months" m:2005_number_of_cases=14 m:2008_percent_of_docket=1.2 m:2007_number_of_cases=8 m:2006_number_of_cases=22 m:2006_percent_of_docket=8.3 m:2009_percent_of_docket=0.5 m:2009_number_of_cases=1 m:2005_percent_of_docket=5.4 m:2008_number_of_cases=2 m:2007_percent_of_docket=3.7

series e:jgjk-h2bn d:2005-01-01T00:00:00.000Z t:age_of_case_in_months="5 months" m:2005_number_of_cases=13 m:2008_percent_of_docket=3.7 m:2007_number_of_cases=27 m:2006_number_of_cases=24 m:2006_percent_of_docket=9.1 m:2009_percent_of_docket=1 m:2009_number_of_cases=2 m:2005_percent_of_docket=5 m:2008_number_of_cases=6 m:2007_percent_of_docket=12.5
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

entity e:jgjk-h2bn l:"CCRB: Age of Substantiated Cases Measured from the Date of Incident 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/jgjk-h2bn

property e:jgjk-h2bn t:meta.view v:id=jgjk-h2bn v:category="Public Safety" v:averageRating=0 v:name="CCRB: Age of Substantiated Cases Measured from the Date of Incident 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:jgjk-h2bn t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jgjk-h2bn t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| age_of_case_in_months | 2005_number_of_cases | 2005_percent_of_docket | 2006_number_of_cases | 2006_percent_of_docket | 2007_number_of_cases | 2007_percent_of_docket | 2008_number_of_cases | 2008_percent_of_docket | 2009_number_of_cases | 2009_percent_of_docket | 
| ===================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | ==================== | ====================== | 
| 3 or younger          | 8                    | 3.10                   | 13                   | 4.90                   | 2                    | 0.90                   | 0                    | 0.00                   | 0                    | 0.00                   | 
| 4 months              | 14                   | 5.40                   | 22                   | 8.30                   | 8                    | 3.70                   | 2                    | 1.20                   | 1                    | 0.50                   | 
| 5 months              | 13                   | 5.00                   | 24                   | 9.10                   | 27                   | 12.50                  | 6                    | 3.70                   | 2                    | 1.00                   | 
| 6 months              | 23                   | 8.80                   | 20                   | 7.60                   | 21                   | 9.70                   | 7                    | 4.30                   | 5                    | 2.50                   | 
| 7 months              | 21                   | 8.10                   | 18                   | 6.80                   | 15                   | 6.90                   | 18                   | 11.20                  | 10                   | 5.10                   | 
| 8 months              | 23                   | 8.80                   | 26                   | 9.80                   | 21                   | 9.70                   | 9                    | 5.60                   | 10                   | 5.10                   | 
| 9 months              | 19                   | 7.30                   | 24                   | 9.10                   | 19                   | 8.80                   | 17                   | 10.60                  | 8                    | 4.10                   | 
| 10 months             | 22                   | 8.50                   | 18                   | 6.80                   | 18                   | 8.30                   | 8                    | 5.00                   | 21                   | 10.70                  | 
| 11 months             | 14                   | 5.40                   | 22                   | 8.30                   | 10                   | 4.60                   | 13                   | 8.10                   | 20                   | 10.20                  | 
| 12 months             | 23                   | 8.80                   | 19                   | 7.20                   | 16                   | 7.40                   | 18                   | 11.20                  | 16                   | 8.10                   | 
```