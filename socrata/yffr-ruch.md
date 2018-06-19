# 4- H Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/4-h-expenditures-4eafa) |
| Metadata | [Link](https://data.illinois.gov/api/views/yffr-ruch) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/yffr-ruch/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/yffr-ruch/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | yffr-ruch |
| Name | 4- H Expenditures |
| Created | 2014-06-27T20:33:26Z |
| Publication Date | 2014-06-27T20:33:57Z |

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| Yes      | series tag     | grantor_agency                  | Grantor Agency                  | text      | text        |
| Yes      | series tag     | grantee                         | Grantee                         | text      | text        |
| Yes      | series tag     | description_of_purpose_of_award | Description of Purpose of Award | text      | text        |
| Yes      | numeric metric | grant_amount                    | Grant Amount                    | number    | text        |
| Yes      | time           | start_date                      | Start Date                      | text      | text        |
| No       |                | completion_date                 | Completion Date                 | text      | text        |
| Yes      | numeric metric | duration_in_days                | Duration (in days)              | number    | text        |
| Yes      | series tag     | grantee_zip_code                | Grantee Zip Code                | text      | text        |
```

## Time Field

```ls
Value = start_date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = completion_date
```

## Data Commands

```ls
series e:yffr-ruch d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=623015807 t:description_of_purpose_of_award="4- H premium reimbursement  statute 30ILCS  120/14" t:grantee="UNIVERSITY OF ILLINOIS" m:grant_amount=786382.23 m:duration_in_days=365
```

## Meta Commands

```ls
metric m:grant_amount p:double l:"Grant Amount" t:dataTypeName=number

metric m:duration_in_days p:integer l:"Duration (in days)" t:dataTypeName=number

entity e:yffr-ruch l:"4- H Expenditures" t:url=https://data.illinois.gov/api/views/yffr-ruch

property e:yffr-ruch t:meta.view v:id=yffr-ruch v:averageRating=0 v:name="4- H Expenditures"

property e:yffr-ruch t:meta.view.owner v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"

property e:yffr-ruch t:meta.view.tableauthor v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"
```

## Top Records

```ls
| grantor_agency         | grantee                 | description_of_purpose_of_award                  | grant_amount | start_date | completion_date | duration_in_days | grantee_zip_code | 
| ====================== | ======================= | ================================================ | ============ | ========== | =============== | ================ | ================ | 
| IL Dept of Agriculture |  UNIVERSITY OF ILLINOIS | 4- H premium reimbursement statute 30ILCS 120/14 | 786,382.23   | 7/1/12     | 6/30/13         | 365              |  623015807       | 
```