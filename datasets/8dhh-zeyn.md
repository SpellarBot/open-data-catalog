# IHPA - CLG Grants 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-clg-grants-2013-ee0a3) |
| Metadata | [Link](https://data.illinois.gov/api/views/8dhh-zeyn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8dhh-zeyn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8dhh-zeyn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8dhh-zeyn |
| Name | IHPA - CLG Grants 2013 |
| Attribution | IHPA |
| Category | Reference |
| Tags | grants, il grants, grant reporting |
| Created | 2014-07-21T20:06:38Z |
| Publication Date | 2014-07-21T20:08:15Z |

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
series e:8dhh-zeyn d:2013-02-08T00:00:00.000Z t:grantee_name_clg="Belvidere, IL" t:duration="2 Years" t:discription_of_project="Conduct an intensive level survey of the Courthouse Square area of Belvidere." t:zip_code=61008 m:amount_of_award=7000

series e:8dhh-zeyn d:2013-02-08T00:00:00.000Z t:grantee_name_clg="Columbia, IL" t:duration="2 Years" t:discription_of_project="Develop a comprehensive preservation plan by identifying historic resources." t:zip_code=62236 m:amount_of_award=7000

series e:8dhh-zeyn d:2013-02-08T00:00:00.000Z t:grantee_name_clg="Downers Grove, Il" t:duration="2 Years" t:discription_of_project="Conduct an intensive level survey in the Village of Downers Grove to include; 1) Denburn Woods; 2) Shady Lane Estates; 3) E. H. Prince Subdivision; 4)Maple Avenue/Main St Corridors" t:zip_code=60515 m:amount_of_award=15000
```

## Meta Commands

```ls
metric m:amount_of_award p:double l:"Amount of Award" t:dataTypeName=money

entity e:8dhh-zeyn l:"IHPA - CLG Grants 2013" t:attribution=IHPA t:url=https://data.illinois.gov/api/views/8dhh-zeyn

property e:8dhh-zeyn t:meta.view v:id=8dhh-zeyn v:category=Reference v:averageRating=0 v:name="IHPA - CLG Grants 2013" v:attribution=IHPA

property e:8dhh-zeyn t:meta.view.license v:name="Public Domain"

property e:8dhh-zeyn t:meta.view.owner v:id=5iir-ecwn v:screenName=jtedrow v:displayName=jtedrow

property e:8dhh-zeyn t:meta.view.tableauthor v:id=5iir-ecwn v:screenName=jtedrow v:roleName=publisher v:displayName=jtedrow
```

## Top Records

```ls
| grantee_name_clg  | zip_code | discription_of_project                                                                                                                                                               | amount_of_award | date_of_award       | duration | 
| ================= | ======== | ==================================================================================================================================================================================== | =============== | =================== | ======== | 
| Belvidere, IL     | 61008    | Conduct an intensive level survey of the Courthouse Square area of Belvidere.                                                                                                        | 7000.00         | 2013-02-08T00:00:00 | 2 Years  | 
| Columbia, IL      | 62236    | Develop a comprehensive preservation plan by identifying historic resources.                                                                                                         | 7000.00         | 2013-02-08T00:00:00 | 2 Years  | 
| Downers Grove, Il | 60515    | Conduct an intensive level survey in the Village of Downers Grove to include; 1) Denburn Woods; 2) Shady Lane Estates; 3) E. H. Prince Subdivision; 4)Maple Avenue/Main St Corridors | 15000.00        | 2013-02-08T00:00:00 | 2 Years  | 
| Edwardsville, IL  | 62025    | Update of the Leclaire National Register Historic District nomination.                                                                                                               | 14164.00        | 2013-02-08T00:00:00 | 2 Years  | 
| Glen Ellyn, IL    | 60137    | Conduct an intensive level survey of the area roughly bounded by Union Pacific Railroad Line, Eastside of Village boundary, Turner Ave., and Main St and Park Ave.                   | 14000.00        | 2013-02-08T00:00:00 | 2 Years  | 
| Glenview, IL      | 60025    | Historic Kit Home Recognition Manual & Survey                                                                                                                                        | 3018.00         | 2013-02-08T00:00:00 | 2 Years  | 
| Jacksonville, IL  | 62650    | Update and Boundary Extension of existing Jacksonville Historic District                                                                                                             | 11050.00        | 2013-02-08T00:00:00 | 2 Years  | 
| Marshall, IL      | 62441    | Update and reprint walking/driving tour of Marshall                                                                                                                                  | 1820.00         | 2013-02-08T00:00:00 | 2 Years  | 
| Maywood, IL       | 60153    | Conduct a Feasibility Study of Masonic Temple                                                                                                                                        | 5000.00         | 2013-02-08T00:00:00 | 2 Years  | 
| Morrrsion, IL     | 61270    | National Register Nomination for Downtown Morrison.                                                                                                                                  | 14000.00        | 2013-02-08T00:00:00 | 2 Years  | 
```