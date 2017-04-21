# Final Harvest - ESA Compliance All -- 10252016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/final-harvest-esa-compliance-all-11182014) |
| Metadata | [Link](https://data.wa.gov/api/views/7iwq-4tne) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/7iwq-4tne/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/7iwq-4tne/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 7iwq-4tne |
| Name | Final Harvest - ESA Compliance All -- 10252016 |
| Tags | state-of-the-salmon |
| Created | 2014-11-06T20:37:25Z |
| Publication Date | 2016-11-28T15:06:58Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | esu                      | ESU                      | text      | text        |
| Yes      | series tag     | category                 | Category                 | text      | text        |
| Yes      | numeric metric | of_years                 | Percent of Years         | number    | text        |
| Yes      | series tag     | number_of_years_assessed | Number of Years Assessed | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7iwq-4tne d:2016-10-25T18:11:21.000Z t:category="Years Within ESA Limit" t:esu="Puget Sound Central and South Chinook" t:number_of_years_assessed="7.1 of 10 years (2005 - 2014)" m:of_years=71

series e:7iwq-4tne d:2016-10-25T18:11:21.000Z t:category="Years Outside ESA Limit" t:esu="Puget Sound Central and South Chinook" t:number_of_years_assessed="2.9 of 10 years (2005 - 2014)" m:of_years=29

series e:7iwq-4tne d:2016-10-25T18:11:21.000Z t:category="Years Within ESA Limit" t:esu="Puget Sound Hood Canal Chinook" t:number_of_years_assessed="8.0 of 10 years (2005 - 2014)" m:of_years=80
```

## Meta Commands

```ls
metric m:of_years p:integer l:"Percent of Years" t:dataTypeName=number

entity e:7iwq-4tne l:"Final Harvest - ESA Compliance All -- 10252016" t:url=https://data.wa.gov/api/views/7iwq-4tne

property e:7iwq-4tne t:meta.view v:id=7iwq-4tne v:averageRating=0 v:name="Final Harvest - ESA Compliance All -- 10252016"

property e:7iwq-4tne t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:7iwq-4tne t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| :updated_at | esu                                | category                | of_years | number_of_years_assessed | 
| =========== | ================================== | ======================= | ======== | ======================== | 
| 1477419081  | Lower Columbia All Chinook         | Years Within ESA Limit  |          |                          | 
| 1477419081  | Lower Columbia All Chinook         | Years Outside ESA Limit |          |                          | 
| 1477419081  | Lower Columbia Fall Bright Chinook | Years Within ESA Limit  |          |                          | 
| 1477419081  | Lower Columbia Fall Bright Chinook | Years Outside ESA Limit |          |                          | 
| 1477419081  | Lower Columbia Fall Tule Chinook   | Years Within ESA Limit  |          |                          | 
| 1477419081  | Lower Columbia Fall Tule Chinook   | Years Outside ESA Limit |          |                          | 
| 1477419081  | Lower Columbia Spring Chinook      | Years Within ESA Limit  |          |                          | 
| 1477419081  | Lower Columbia Spring Chinook      | Years Outside ESA Limit |          |                          | 
| 1477419081  | Lower Columbia Coho                | Years Within ESA Limit  |          |                          | 
| 1477419081  | Lower Columbia Coho                | Years Outside ESA Limit |          |                          | 
```