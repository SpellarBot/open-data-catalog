# KSD Apprenticeship Utilization

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ksd-apprenticeship-utilization) |
| Metadata | [Link](https://data.wa.gov/api/views/n2b9-zkkj) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/n2b9-zkkj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/n2b9-zkkj/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | n2b9-zkkj |
| Name | KSD Apprenticeship Utilization |
| Category | Education |
| Created | 2016-06-03T20:16:59Z |
| Publication Date | 2017-04-19T16:22:41Z |

## Description

Apprenticeship Utilization data for Kennewick School District Projects.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | projno             | PROJNO             | text          | text          |
| Yes      | series tag     | projtitle          | PROJTITLE          | text          | text          |
| Yes      | series tag     | agencycode         | AGENCYCODE         | text          | text          |
| Yes      | series tag     | agencyname         | AGENCYNAME         | text          | text          |
| Yes      | series tag     | firm_name          | FIRM_NAME          | text          | text          |
| Yes      | numeric metric | proj_summ_total    | PROJ_SUMM_TOTAL    | number        | number        |
| Yes      | time           | actual_constntp_dt | ACTUAL_CONSTNTP_DT | calendar_date | calendar_date |
| Yes      | series tag     | worker_type        | WORKER_TYPE        | text          | text          |
| Yes      | series tag     | worker_name        | WORKER_NAME        | text          | text          |
| Yes      | series tag     | worker_reg_num     | WORKER_REG_NUM     | text          | number        |
| Yes      | series tag     | trade_code         | TRADE_CODE         | text          | text          |
| Yes      | series tag     | trade_desc         | Trade_desc         | text          | text          |
| Yes      | numeric metric | hrs                | HRS                | number        | number        |
| No       |                | report_period_date | REPORT_PERIOD_DATE | calendar_date | calendar_date |
```

## Time Field

```ls
Value = actual_constntp_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = report_period_date
```

## Data Commands

```ls
series e:n2b9-zkkj d:2013-06-17T00:00:00.000Z t:worker_name="Sprenger, Justin" t:worker_reg_num=171362 t:projno=44029 t:projtitle="Lincoln Elementary Rem. & Add" t:worker_type=APPRENTICE t:trade_code=C t:agencyname="Kennewick School District" t:agencycode=KSD t:firm_name="Acoustical Ceilings Inc." t:trade_desc=Carpenter m:hrs=121.5 m:proj_summ_total=9475106.2

series e:n2b9-zkkj d:2013-06-17T00:00:00.000Z t:worker_name="Smith, Matt" t:worker_reg_num=175207 t:projno=44029 t:projtitle="Lincoln Elementary Rem. & Add" t:worker_type=APPRENTICE t:trade_code=B t:agencyname="Kennewick School District" t:agencycode=KSD t:firm_name="Aden Masonry" t:trade_desc=Bricklayer m:hrs=16 m:proj_summ_total=9475106.2

series e:n2b9-zkkj d:2013-06-17T00:00:00.000Z t:worker_name="Trissel, Skyler" t:worker_reg_num=176478 t:projno=44029 t:projtitle="Lincoln Elementary Rem. & Add" t:worker_type=APPRENTICE t:trade_code=B t:agencyname="Kennewick School District" t:agencycode=KSD t:firm_name="Aden Masonry" t:trade_desc=Bricklayer m:hrs=6.5 m:proj_summ_total=9475106.2
```

## Meta Commands

```ls
metric m:proj_summ_total p:double l:PROJ_SUMM_TOTAL t:dataTypeName=number

metric m:hrs p:float l:HRS t:dataTypeName=number

entity e:n2b9-zkkj l:"KSD Apprenticeship Utilization" t:url=https://data.wa.gov/api/views/n2b9-zkkj

property e:n2b9-zkkj t:meta.view v:id=n2b9-zkkj v:category=Education v:averageRating=0 v:name="KSD Apprenticeship Utilization"

property e:n2b9-zkkj t:meta.view.owner v:id=myrq-cd3j v:profileImageUrlMedium=/api/users/myrq-cd3j/profile_images/THUMB v:profileImageUrlLarge=/api/users/myrq-cd3j/profile_images/LARGE v:screenName="Kennewick School District #17" v:profileImageUrlSmall=/api/users/myrq-cd3j/profile_images/TINY v:lastNotificationSeenAt=1492619021 v:displayName="Kennewick School District #17"

property e:n2b9-zkkj t:meta.view.tableauthor v:id=myrq-cd3j v:profileImageUrlMedium=/api/users/myrq-cd3j/profile_images/THUMB v:profileImageUrlLarge=/api/users/myrq-cd3j/profile_images/LARGE v:screenName="Kennewick School District #17" v:profileImageUrlSmall=/api/users/myrq-cd3j/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1492619021 v:displayName="Kennewick School District #17"
```

## Top Records

```ls
| projno | projtitle                     | agencycode | agencyname                | firm_name                | proj_summ_total    | actual_constntp_dt  | worker_type | worker_name      | worker_reg_num | trade_code | trade_desc  | hrs     | report_period_date  | 
| ====== | ============================= | ========== | ========================= | ======================== | ================== | =================== | =========== | ================ | ============== | ========== | =========== | ======= | =================== | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Acoustical Ceilings Inc. | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Sprenger, Justin | 171362         | C          | Carpenter   | 121.50  | 2014-07-31T00:00:00 | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Aden Masonry             | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Smith, Matt      | 175207         | B          | Bricklayer  | 16.00   | 2014-07-31T00:00:00 | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Aden Masonry             | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Trissel, Skyler  | 176478         | B          | Bricklayer  | 6.50    | 2014-07-31T00:00:00 | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Bouten Construction      | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Till, Porter     | 173394         | L          | Laborer     | 1282.00 | 2014-07-31T00:00:00 | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Bouten Construction      | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Stone, Joshawa   | 172895         | L          | Laborer     | 80.00   | 2014-07-31T00:00:00 | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Bouten Construction      | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Bender, Jason    | 160126         | L          | Laborer     | 72.00   | 2014-07-31T00:00:00 | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Craig-Co                 | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Cleghorn, Daniel |                | E          | Electrician | 64.00   | 2014-07-31T00:00:00 | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Craig-Co                 | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Garibaldo, Pedro |                | E          | Electrician | 1118.00 | 2014-07-31T00:00:00 | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Craig-Co                 | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Andring, Jacob   |                | E          | Electrician | 78.00   | 2014-07-31T00:00:00 | 
| 44029  | Lincoln Elementary Rem. & Add | KSD        | Kennewick School District | Craig-Co                 | 9475106.1999999993 | 2013-06-17T00:00:00 | APPRENTICE  | Mora, Armando    | 174282         | E          |             | 150.75  | 2014-07-31T00:00:00 | 
```