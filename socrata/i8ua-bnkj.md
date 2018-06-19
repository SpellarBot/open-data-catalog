# Monthly Performance Management Reports (includes Corruption Lectures and Customer Service indicators)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monthly-performance-management-reports-includes-corruption-lectures-and-customer-service-i) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/i8ua-bnkj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/i8ua-bnkj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/i8ua-bnkj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | i8ua-bnkj |
| Name | Monthly Performance Management Reports (includes Corruption Lectures and Customer Service indicators) |
| Attribution | Department of Investigation (DOI) |
| Category | City Government |
| Tags | performance, management, doi, investigation |
| Created | 2016-10-24T14:36:31Z |
| Publication Date | 2016-10-24T14:38:09Z |

## Description

This dataset contains select monthly performance statistics that DOI regularly reports to the Mayor's Office of Operations for 2010 - 2015.  This dataset includes several indicators that are cummulated for the Mayor's Management Reports, such as the including numbers of complaints received by the Agency and the numbers of arrests made.  This dataset also includes monthly statistics on the Agency's outreach efforts (anticorrupion and whistleblower lectures) as well customer service indicators (such as the number of emails received by the Agency).

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | indicator_name | Indicator Name | text      | text        |
| Yes      | series tag  | month          | Month          | text      | text        |
| Yes      | series tag  | report_month   | Report Month   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:i8ua-bnkj d:2016-10-24T14:36:33.000Z t:indicator_name="Arrests resulting from DOI investigations" t:report_month=25 t:month="2010 / 01" m:row_number.i8ua-bnkj=1

series e:i8ua-bnkj d:2016-10-24T14:36:33.000Z t:indicator_name="Arrests resulting from DOI investigations" t:report_month=41 t:month="2010 / 02" m:row_number.i8ua-bnkj=2

series e:i8ua-bnkj d:2016-10-24T14:36:33.000Z t:indicator_name="Arrests resulting from DOI investigations" t:report_month=92 t:month="2010 / 03" m:row_number.i8ua-bnkj=3
```

## Meta Commands

```ls
metric m:row_number.i8ua-bnkj p:long l:"Row Number"

entity e:i8ua-bnkj l:"Monthly Performance Management Reports (includes Corruption Lectures and Customer Service indicators)" t:attribution="Department of Investigation (DOI)" t:url=https://data.cityofnewyork.us/api/views/i8ua-bnkj

property e:i8ua-bnkj t:meta.view v:id=i8ua-bnkj v:category="City Government" v:averageRating=0 v:name="Monthly Performance Management Reports (includes Corruption Lectures and Customer Service indicators)" v:attribution="Department of Investigation (DOI)"

property e:i8ua-bnkj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:i8ua-bnkj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | indicator_name                            | month     | report_month | 
| =========== | ========================================= | ========= | ============ | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 01 | 25           | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 02 | 41           | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 03 | 92           | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 04 | 36           | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 05 | 35           | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 06 | 102          | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 07 | 63           | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 08 | 48           | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 09 | 67           | 
| 1477319793  | Arrests resulting from DOI investigations | 2010 / 10 | 166          | 
```