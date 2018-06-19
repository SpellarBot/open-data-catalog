# IHPA - CLG Grants 2014 (YTD)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihpa-clg-grants-2014-ytd-3db5f) |
| Metadata | [Link](https://data.illinois.gov/api/views/qycd-888m) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qycd-888m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qycd-888m/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qycd-888m |
| Name | IHPA - CLG Grants 2014 (YTD) |
| Attribution | IHPA |
| Category | Reference |
| Tags | grants, il grants, grant reporting |
| Created | 2014-07-21T20:09:32Z |
| Publication Date | 2014-07-21T20:11:06Z |

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
series e:qycd-888m d:2014-02-21T00:00:00.000Z t:grantee_name_clg="Belleville, IL" t:duration="2 Years" t:discription_of_project="Reassessment of Downtown Historic District with potential to enlarge NW quadrant." t:zip_code=62220 m:amount_of_award=14000

series e:qycd-888m d:2014-02-21T00:00:00.000Z t:grantee_name_clg="Berwyn, IL" t:duration="2 Years" t:discription_of_project="To complete survey and research for National Register Nomination for Bungalow residential district, conduct public meetings and attend IHSAC hearing." t:zip_code=60402 m:amount_of_award=17500

series e:qycd-888m d:2014-02-21T00:00:00.000Z t:grantee_name_clg="Highland Park, IL" t:duration="2 Years" t:discription_of_project="Series of tours, lectures and educational events and projects to promote community awareness of the rich architectural heritage of Robert Seyfarth designed buildings." t:zip_code=60035 m:amount_of_award=5250
```

## Meta Commands

```ls
metric m:amount_of_award p:double l:"Amount of Award" t:dataTypeName=money

entity e:qycd-888m l:"IHPA - CLG Grants 2014 (YTD)" t:attribution=IHPA t:url=https://data.illinois.gov/api/views/qycd-888m

property e:qycd-888m t:meta.view v:id=qycd-888m v:category=Reference v:averageRating=0 v:name="IHPA - CLG Grants 2014 (YTD)" v:attribution=IHPA

property e:qycd-888m t:meta.view.license v:name="Public Domain"

property e:qycd-888m t:meta.view.owner v:id=5iir-ecwn v:screenName=jtedrow v:displayName=jtedrow

property e:qycd-888m t:meta.view.tableauthor v:id=5iir-ecwn v:screenName=jtedrow v:roleName=publisher v:displayName=jtedrow
```

## Top Records

```ls
| grantee_name_clg    | zip_code | discription_of_project                                                                                                                                                                                              | amount_of_award | date_of_award       | duration | 
| =================== | ======== | =================================================================================================================================================================================================================== | =============== | =================== | ======== | 
| Belleville, IL      | 62220    | Reassessment of Downtown Historic District with potential to enlarge NW quadrant.                                                                                                                                   | 14000.00        | 2014-02-21T00:00:00 | 2 Years  | 
| Berwyn, IL          | 60402    | To complete survey and research for National Register Nomination for Bungalow residential district, conduct public meetings and attend IHSAC hearing.                                                               | 17500.00        | 2014-02-21T00:00:00 | 2 Years  | 
| Highland Park, IL   | 60035    | Series of tours, lectures and educational events and projects to promote community awareness of the rich architectural heritage of Robert Seyfarth designed buildings.                                              | 5250.00         | 2014-02-21T00:00:00 | 2 Years  | 
| McHenry County, IL. | 60098    | To continue work on an intensive level survey of rural structures, under the direction of University of Illinois professional staff.                                                                                | 15400.00        | 2014-02-21T00:00:00 | 2 Years  | 
| Will County, IL     | 60432    | Intensive level historic cultural resource survey in the Peotone Township region, for purposes of planning future development.                                                                                      | 26250.00        | 2014-02-21T00:00:00 | 2 Years  | 
| Evanston, IL        | 60201    | Research and document property identificaioin number and legal descriptions of porpertied designatred as local landmarks and in historic districts.                                                                 | 37240.00        | 2014-03-19T00:00:00 | 2 Years  | 
| Centralia, IL       | 62801    | Evaluation and Inventory of historic resources and develop a plan to attract investment and assess the feasibility of a financial incentive program to provide capital support for improvement on these properites. | 7000.00         | 2014-03-25T00:00:00 | 2 Years  | 
```