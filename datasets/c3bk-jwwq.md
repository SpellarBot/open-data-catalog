# VO-AG Expenditures

## Dataset

* [Dataset URL](https://data.illinois.gov/api/views/c3bk-jwwq/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/vo-ag-expenditures-9b3cf)
* Id = c3bk-jwwq
* Name = VO-AG Expenditures
* Created = 2014-06-27T20:26:05Z
* Publication Date = 2014-06-27T20:27:23Z
* Rows Updated = 2014-06-27T20:26:18Z

## Description



## Columns

```ls
| Name                            | Field Name                      | Data Type     | Render Type   | Schema Type    | Included | 
| =============================== | =============================== | ============= | ============= | ============== | ======== | 
| Grantor Agency                  | grantor_agency                  | text          | text          | series tag     | Yes      | 
| Grantee                         | grantee                         | text          | text          | series tag     | Yes      | 
| Description of Purpose of Award | description_of_purpose_of_award | text          | text          | series tag     | Yes      | 
| Grant Amount                    | grant_amount                    | number        | number        | numeric metric | Yes      | 
| Start Date                      | start_date                      | calendar_date | calendar_date | time           | Yes      | 
| Completion Date                 | completion_date                 | calendar_date | calendar_date |                | No       | 
| Duration (in days)              | duration_in_days                | number        | number        | numeric metric | Yes      | 
| Grantee Zip Code                | grantee_zip_code                | text          | number        | series tag     | Yes      | 
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = completion_date
Annotation Fields = 
```

## Data Commands

```ls
series e:c3bk-jwwq d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=612312513 t:description_of_purpose_of_award="Vocational Agricultural grants for educational purposes statute 30ILCS  120/16" t:grantee="?MERCER COUNTY SCHOOL DISTRICT" m:grant_amount=2153.65 m:duration_in_days=365

series e:c3bk-jwwq d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=613269697 t:description_of_purpose_of_award="Vocational Agricultural grants for educational purposes statute 30ILCS  120/16" t:grantee="?PUTNAM COUNTY COMMUNITY UNIT" m:grant_amount=1154.35 m:duration_in_days=365

series e:c3bk-jwwq d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=605523136 t:description_of_purpose_of_award="Vocational Agricultural grants for educational purposes statute 30ILCS  120/16" t:grantee="?SOMONAUK COMMUNITY UNIT SCHOOL" m:grant_amount=1296.1 m:duration_in_days=365
```

## Meta Commands

```ls
metric m:grant_amount l:"Grant Amount" t:dataTypeName=number

metric m:duration_in_days p:integer l:"Duration (in days)" t:dataTypeName=number

entity e:c3bk-jwwq l:"VO-AG Expenditures" t:url=https://data.illinois.gov/api/views/c3bk-jwwq

property e:c3bk-jwwq t:meta.view d:2017-03-03T14:29:31.948Z v:id=c3bk-jwwq v:averageRating=0 v:name="VO-AG Expenditures"

property e:c3bk-jwwq t:meta.view.owner d:2017-03-03T14:29:31.948Z v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:roleName=publisher v:displayName="Rhonda Jachino"

property e:c3bk-jwwq t:meta.view.tableauthor d:2017-03-03T14:29:31.948Z v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:roleName=publisher v:displayName="Rhonda Jachino"
```