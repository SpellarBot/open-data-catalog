# Premiums

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/premiums-e38ad) |
| Metadata | [Link](https://data.illinois.gov/api/views/pbnq-tdta) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/pbnq-tdta/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/pbnq-tdta/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | pbnq-tdta |
| Name | Premiums |
| Created | 2014-06-27T20:30:40Z |
| Publication Date | 2014-06-27T20:31:27Z |

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
series e:pbnq-tdta d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=614800212 t:description_of_purpose_of_award="Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9" t:grantee="HENDERSON COUNTY FAIR" m:grant_amount=13683.56 m:duration_in_days=365

series e:pbnq-tdta d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=610129670 t:description_of_purpose_of_award="Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9" t:grantee="BOONE COUNTY FAIR ASSOCIATION" m:grant_amount=55719.84 m:duration_in_days=365

series e:pbnq-tdta d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=604440097 t:description_of_purpose_of_award="Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9" t:grantee="GRUNDY COUNTY ARGIC DIST FAIR" m:grant_amount=36786.57 m:duration_in_days=365
```

## Meta Commands

```ls
metric m:grant_amount p:float l:"Grant Amount" t:dataTypeName=number

metric m:duration_in_days p:integer l:"Duration (in days)" t:dataTypeName=number

entity e:pbnq-tdta l:Premiums t:url=https://data.illinois.gov/api/views/pbnq-tdta

property e:pbnq-tdta t:meta.view v:id=pbnq-tdta v:averageRating=0 v:name=Premiums

property e:pbnq-tdta t:meta.view.owner v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"

property e:pbnq-tdta t:meta.view.tableauthor v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"
```

## Top Records

```ls
| grantor_agency         | grantee                        | description_of_purpose_of_award                                                           | grant_amount | start_date          | completion_date     | duration_in_days | grantee_zip_code | 
| ====================== | ============================== | ========================================================================================= | ============ | =================== | =================== | ================ | ================ | 
| IL Dept of Agriculture |  HENDERSON COUNTY FAIR         | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 13683.56     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 614800212        | 
| IL Dept of Agriculture |  BOONE COUNTY FAIR ASSOCIATION | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 55719.84     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 610129670        | 
| IL Dept of Agriculture |  GRUNDY COUNTY ARGIC DIST FAIR | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 36786.57     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 604440097        | 
| IL Dept of Agriculture |  ADAMS COUNTY FAIR ASSOC       | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 25799.35     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 623242811        | 
| IL Dept of Agriculture |  MARION CO FAIR                | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 24733.49     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 628019528        | 
| IL Dept of Agriculture |  TRI COUNTY FAIR ASSOC INC     | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 8594.21      | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 613420142        | 
| IL Dept of Agriculture |  HENRY COUNTY FAIR ASSOCIATION | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 19975.60     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 612549999        | 
| IL Dept of Agriculture |  SANDWICH FAIR ASSOCIATION INC | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 63053.87     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 605482196        | 
| IL Dept of Agriculture |  STEPHENSON COUNTY FAIR ASSOC  | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 46917.98     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 610489658        | 
| IL Dept of Agriculture |  UNION AGRICULTURAL SOCIETY    | Reimbursement for premiums awarded to participants at county fairs. Statute 30 ILCS 120/9 | 14304.35     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 610879417        | 
```