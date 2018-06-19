# IHPA - CLG Grants 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-clg-grants-2010-fc376) |
| Metadata | [Link](https://data.illinois.gov/api/views/cvrw-tygd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/cvrw-tygd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/cvrw-tygd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | cvrw-tygd |
| Name | IHPA - CLG Grants 2010 |
| Attribution | IHPA |
| Category | Reference |
| Tags | grants, il grants, grant reporting |
| Created | 2014-07-21T19:54:39Z |
| Publication Date | 2014-07-21T19:57:30Z |

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
series e:cvrw-tygd d:2010-02-18T00:00:00.000Z t:grantee_name_clg="Berwyn, IL" t:duration="2 Years" t:discription_of_project="Architectural and historical survey of the 1.3 mile Cermak Road corridor through Berwyn, including the development of design guidelines for restoration and future development." t:zip_code=60402 m:amount_of_award=14541.8

series e:cvrw-tygd d:2010-02-18T00:00:00.000Z t:grantee_name_clg="Blue Island, IL" t:duration="2 Years" t:discription_of_project="Catalog and evaluate preservation records; assess & enhance administrative policies & procedures; update historic preservation ordinance; integrate preservation principles with current community" t:zip_code=60406 m:amount_of_award=11648

series e:cvrw-tygd d:2010-02-18T00:00:00.000Z t:grantee_name_clg="Evanston, IL" t:duration="2 Years" t:discription_of_project="Perform a survey on Lakeshore Historic District (Phase 1)" t:zip_code=60201 m:amount_of_award=12000
```

## Meta Commands

```ls
metric m:amount_of_award p:double l:"Amount of Award" t:dataTypeName=money

entity e:cvrw-tygd l:"IHPA - CLG Grants 2010" t:attribution=IHPA t:url=https://data.illinois.gov/api/views/cvrw-tygd

property e:cvrw-tygd t:meta.view v:id=cvrw-tygd v:category=Reference v:averageRating=0 v:name="IHPA - CLG Grants 2010" v:attribution=IHPA

property e:cvrw-tygd t:meta.view.license v:name="Public Domain"

property e:cvrw-tygd t:meta.view.owner v:id=5iir-ecwn v:screenName=jtedrow v:displayName=jtedrow

property e:cvrw-tygd t:meta.view.tableauthor v:id=5iir-ecwn v:screenName=jtedrow v:roleName=publisher v:displayName=jtedrow
```

## Top Records

```ls
| grantee_name_clg | zip_code | discription_of_project                                                                                                                                                                             | amount_of_award | date_of_award       | duration | 
| ================ | ======== | ================================================================================================================================================================================================== | =============== | =================== | ======== | 
| Berwyn, IL       | 60402    | Architectural and historical survey of the 1.3 mile Cermak Road corridor through Berwyn, including the development of design guidelines for restoration and future development.                    | 14541.80        | 2010-02-18T00:00:00 | 2 Years  | 
| Blue Island, IL  | 60406    | Catalog and evaluate preservation records; assess & enhance administrative policies & procedures; update historic preservation ordinance; integrate preservation principles with current community | 11648.00        | 2010-02-18T00:00:00 | 2 Years  | 
| Evanston, IL     | 60201    | Perform a survey on Lakeshore Historic District (Phase 1)                                                                                                                                          | 12000.00        | 2010-02-18T00:00:00 | 2 Years  | 
| Jacksonville, IL | 62650    | Perform a survey on Jacksonville Historic District and Update Main Street Survey.                                                                                                                  | 10000.00        | 2010-02-18T00:00:00 | 2 Years  | 
| Lake Forest, IL  | 60045    | Update Lake Forest Historic District Resource Survey.                                                                                                                                              | 25585.50        | 2010-02-18T00:00:00 | 2 Years  | 
| Macomb, IL       | 61455    | Conduct an intensive sturctural survey report of each building 50 years old in the downtown historic district.                                                                                     | 15787.18        | 2010-02-18T00:00:00 | 2 Years  | 
| Ottawa, IL       | 61350    | Conduct a survey of Ottawa's East Side                                                                                                                                                             | 15200.00        | 2010-02-18T00:00:00 | 2 Years  | 
| Quincy, IL       | 62301    | Improve Local Landmark & Historic Districts Driving Tour Brochure.                                                                                                                                 | 3000.00         | 2010-02-18T00:00:00 | 2 Years  | 
```