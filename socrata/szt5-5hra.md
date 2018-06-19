# IHPA - CLG Grants 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-clg-grants-2012-af21a) |
| Metadata | [Link](https://data.illinois.gov/api/views/szt5-5hra) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/szt5-5hra/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/szt5-5hra/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | szt5-5hra |
| Name | IHPA - CLG Grants 2012 |
| Attribution | IHPA |
| Category | Reference |
| Tags | grants, il grants, grant reporting |
| Created | 2014-07-21T20:03:36Z |
| Publication Date | 2014-07-21T20:06:04Z |

## Description

Dataset listing grants to certified local governments.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | grantee_name_clg       | Grantee Name (CLG)     | text          | text          |
| Yes      | series tag     | zip_code               | Zip Code               | text          | text          |
| Yes      | series tag     | discription_of_project | Discription of Project | text          | text          |
| Yes      | numeric metric | amount_of_award        | Amount of Award        | money         | money         |
| Yes      | time           | date_of_award          | Date of Award          | calendar_date | calendar_date |
| Yes      | series tag     | duration               | Duration               | text          | text          |
```

## Time Field

```ls
Value = date_of_award
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:szt5-5hra d:2012-01-13T00:00:00.000Z t:grantee_name_clg="Charleston, IL" t:duration="2 Years" t:discription_of_project="Create a website for Historic Preservation Commission" t:zip_code=61920 m:amount_of_award=25022
```

## Meta Commands

```ls
metric m:amount_of_award p:double l:"Amount of Award" t:dataTypeName=money

entity e:szt5-5hra l:"IHPA - CLG Grants 2012" t:attribution=IHPA t:url=https://data.illinois.gov/api/views/szt5-5hra

property e:szt5-5hra t:meta.view v:id=szt5-5hra v:category=Reference v:averageRating=0 v:name="IHPA - CLG Grants 2012" v:attribution=IHPA

property e:szt5-5hra t:meta.view.license v:name="Public Domain"

property e:szt5-5hra t:meta.view.owner v:id=5iir-ecwn v:screenName=jtedrow v:displayName=jtedrow

property e:szt5-5hra t:meta.view.tableauthor v:id=5iir-ecwn v:screenName=jtedrow v:roleName=publisher v:displayName=jtedrow
```

## Top Records

```ls
| grantee_name_clg | zip_code | discription_of_project                                | amount_of_award | date_of_award       | duration | 
| ================ | ======== | ===================================================== | =============== | =================== | ======== | 
| Charleston, IL   | 61920    | Create a website for Historic Preservation Commission | 25022.00        | 2012-01-13T00:00:00 | 2 Years  | 
```