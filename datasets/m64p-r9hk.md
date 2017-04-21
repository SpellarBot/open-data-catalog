# Certified Asbestos Investigator

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/certified-asbestos-investigator-b153e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/m64p-r9hk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/m64p-r9hk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/m64p-r9hk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | m64p-r9hk |
| Name | Certified Asbestos Investigator |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Tags | dep, department of environmental protection, environment, certified, asbestos, investigators, cai, certified asbestos investigators (cai), healthy living |
| Created | 2013-01-31T04:41:16Z |
| Publication Date | 2017-03-22T21:13:07Z |

## Description

List of Certified Asbestos Investigators (CAI)

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag  | last_name            | Last Name            | text      | text        |
| Yes      | series tag  | first_name           | First Name           | text      | text        |
| Yes      | series tag  | certification_number | Certification Number | text      | number      |
| Yes      | time        | expiration_date      | Expiration Date      | text      | text        |
| Yes      | series tag  | telephone            | Telephone            | text      | text        |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:m64p-r9hk d:2017-08-22T00:00:00.000Z t:certification_number=119921 t:first_name=SAJJAD t:last_name=AKBAR t:telephone="(718) 928-5909" m:row_number.m64p-r9hk=1

series e:m64p-r9hk d:2018-12-20T00:00:00.000Z t:certification_number=116983 t:first_name=SOHAIL t:last_name=AKHTAR t:telephone="(646) 385-3063" m:row_number.m64p-r9hk=2

series e:m64p-r9hk d:2018-08-01T00:00:00.000Z t:certification_number=133598 t:first_name="MD. SHAMIM" t:last_name=AKOND t:telephone="(347) 828-1309" m:row_number.m64p-r9hk=3
```

## Meta Commands

```ls
metric m:row_number.m64p-r9hk p:long l:"Row Number"

entity e:m64p-r9hk l:"Certified Asbestos Investigator" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/m64p-r9hk

property e:m64p-r9hk t:meta.view v:id=m64p-r9hk v:category=Environment v:attributionLink=https://a826-web01.nyc.gov/cai/ v:averageRating=0 v:name="Certified Asbestos Investigator" v:attribution="Department of Environmental Protection (DEP)"

property e:m64p-r9hk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:m64p-r9hk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| last_name | first_name | certification_number | expiration_date | telephone      | 
| ========= | ========== | ==================== | =============== | ============== | 
| AKBAR     | SAJJAD     | 119921               | 8/22/17         | (718) 928-5909 | 
| AKHTAR    | SOHAIL     | 116983               | 12/20/18        | (646) 385-3063 | 
| AKOND     | MD. SHAMIM | 133598               | 8/1/18          | (347) 828-1309 | 
| AMBROSE   | MARTIN     | 116635               | 12/3/17         | (718) 342-7686 | 
| ANDREOU   | ANDREAS    | 120413               | 12/5/18         | (718) 383-2626 | 
| ANDREWS   | GREGORY    | 146396               | 2/28/19         | (716) 206-5100 | 
| ARRIGO    | ALEXANDER  | 140047               | 4/9/18          | (212) 290-6323 | 
| ASHMAN    | THOMAS     | 141219               | 11/6/17         | (607) 624-9548 | 
| ATHINEOS  | PAUL       | 113453               | 2/28/19         | (212) 226-0096 | 
| AYORINDE  | AKINTAYO   | 145489               | 6/8/19          | (917) 337-4166 | 
```