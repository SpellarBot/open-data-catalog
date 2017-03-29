# VO-AG Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vo-ag-expenditures-9b3cf) |
| Metadata | [Link](https://data.illinois.gov/api/views/c3bk-jwwq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/c3bk-jwwq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/c3bk-jwwq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | c3bk-jwwq |
| Name | VO-AG Expenditures |
| Created | 2014-06-27T20:26:05Z |
| Publication Date | 2014-06-27T20:27:23Z |

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag     | grantor_agency                  | Grantor Agency                  | text          | text          |
| Yes      | series tag     | grantee                         | Grantee                         | text          | text          |
| Yes      | series tag     | description_of_purpose_of_award | Description of Purpose of Award | text          | text          |
| Yes      | numeric metric | grant_amount                    | Grant Amount                    | number        | number        |
| Yes      | time           | start_date                      | Start Date                      | calendar_date | calendar_date |
| No       |                | completion_date                 | Completion Date                 | calendar_date | calendar_date |
| Yes      | numeric metric | duration_in_days                | Duration (in days)              | number        | number        |
| Yes      | series tag     | grantee_zip_code                | Grantee Zip Code                | text          | number        |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = completion_date
```

## Data Commands

```ls
series e:c3bk-jwwq d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=612312513 t:description_of_purpose_of_award="Vocational Agricultural grants for educational purposes statute 30ILCS  120/16" t:grantee="MERCER COUNTY SCHOOL DISTRICT" m:grant_amount=2153.65 m:duration_in_days=365

series e:c3bk-jwwq d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=613269697 t:description_of_purpose_of_award="Vocational Agricultural grants for educational purposes statute 30ILCS  120/16" t:grantee="PUTNAM COUNTY COMMUNITY UNIT" m:grant_amount=1154.35 m:duration_in_days=365

series e:c3bk-jwwq d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=605523136 t:description_of_purpose_of_award="Vocational Agricultural grants for educational purposes statute 30ILCS  120/16" t:grantee="SOMONAUK COMMUNITY UNIT SCHOOL" m:grant_amount=1296.1 m:duration_in_days=365
```

## Meta Commands

```ls
metric m:grant_amount p:float l:"Grant Amount" t:dataTypeName=number

metric m:duration_in_days p:integer l:"Duration (in days)" t:dataTypeName=number

entity e:c3bk-jwwq l:"VO-AG Expenditures" t:url=https://data.illinois.gov/api/views/c3bk-jwwq

property e:c3bk-jwwq t:meta.view v:id=c3bk-jwwq v:averageRating=0 v:name="VO-AG Expenditures"

property e:c3bk-jwwq t:meta.view.owner v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"

property e:c3bk-jwwq t:meta.view.tableauthor v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"
```

## Top Records

```ls
| grantor_agency         | grantee                         | description_of_purpose_of_award                                               | grant_amount | start_date          | completion_date     | duration_in_days | grantee_zip_code | 
| ====================== | =============================== | ============================================================================= | ============ | =================== | =================== | ================ | ================ | 
| IL Dept of Agriculture |  MERCER COUNTY SCHOOL DISTRICT  | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 2153.65      | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 612312513        | 
| IL Dept of Agriculture |  PUTNAM COUNTY COMMUNITY UNIT   | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 1154.35      | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 613269697        | 
| IL Dept of Agriculture |  SOMONAUK COMMUNITY UNIT SCHOOL | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 1296.10      | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 605523136        | 
| IL Dept of Agriculture |  COMMUNITY UNIT SCHOOL DIST 2   | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 1011.16      | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 605490107        | 
| IL Dept of Agriculture |  STARK COUNTY COMMUNITY UNIT    | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 359.6        | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 614830659        | 
| IL Dept of Agriculture |  BUREAU VALLEY COMMUITY UNIT    | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 1030.82      | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 613380329        | 
| IL Dept of Agriculture |  COUNTY OF GRUNDY SCHL DIST 111 | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 535.41       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 604479466        | 
| IL Dept of Agriculture |  ORION COMMUNITY UNIT SCHOOL    | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 1236.89      | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 612739611        | 
| IL Dept of Agriculture |  GALVA COMMUNITY UNIT           | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 1557.64      | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 614341090        | 
| IL Dept of Agriculture |  ALWOOD COMMUNITY UNIT SCHOOL   | Vocational Agricultural grants for educational purposes statute 30ILCS 120/16 | 1356.83      | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 614909684        | 
```