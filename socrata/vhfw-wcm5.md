# Rehabilitation Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rehabilitation-expenditures-37cfb) |
| Metadata | [Link](https://data.illinois.gov/api/views/vhfw-wcm5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vhfw-wcm5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vhfw-wcm5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vhfw-wcm5 |
| Name | Rehabilitation Expenditures |
| Created | 2014-06-27T20:29:16Z |
| Publication Date | 2014-06-27T20:38:55Z |

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
series e:vhfw-wcm5 d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=610129670 t:description_of_purpose_of_award="Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects  statute 30ILCS 120/13" t:grantee="BOONE COUNTY FAIR ASSOCIATION" m:grant_amount=13250 m:duration_in_days=365

series e:vhfw-wcm5 d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=604440097 t:description_of_purpose_of_award="Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects  statute 30ILCS 120/13" t:grantee="GRUNDY COUNTY ARGIC DIST FAIR" m:grant_amount=13250 m:duration_in_days=365

series e:vhfw-wcm5 d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=623242811 t:description_of_purpose_of_award="Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects  statute 30ILCS 120/13" t:grantee="ADAMS COUNTY FAIR ASSOC" m:grant_amount=13250 m:duration_in_days=365
```

## Meta Commands

```ls
metric m:grant_amount p:float l:"Grant Amount" t:dataTypeName=number

metric m:duration_in_days p:integer l:"Duration (in days)" t:dataTypeName=number

entity e:vhfw-wcm5 l:"Rehabilitation Expenditures" t:url=https://data.illinois.gov/api/views/vhfw-wcm5

property e:vhfw-wcm5 t:meta.view v:id=vhfw-wcm5 v:averageRating=0 v:name="Rehabilitation Expenditures"

property e:vhfw-wcm5 t:meta.view.owner v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"

property e:vhfw-wcm5 t:meta.view.tableauthor v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"
```

## Top Records

```ls
| grantor_agency         | grantee                         | description_of_purpose_of_award                                                                                                                           | grant_amount | start_date          | completion_date     | duration_in_days | grantee_zip_code | 
| ====================== | =============================== | ========================================================================================================================================================= | ============ | =================== | =================== | ================ | ================ | 
| IL Dept of Agriculture |  BOONE COUNTY FAIR ASSOCIATION  | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 610129670        | 
| IL Dept of Agriculture |  GRUNDY COUNTY ARGIC DIST FAIR  | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 604440097        | 
| IL Dept of Agriculture |  ADAMS COUNTY FAIR ASSOC        | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 623242811        | 
| IL Dept of Agriculture |  MARION CO FAIR                 | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 628019528        | 
| IL Dept of Agriculture |  TRI COUNTY FAIR ASSOC INC      | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 613420142        | 
| IL Dept of Agriculture |  HENRY COUNTY FAIR ASSOCIATION  | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 612549999        | 
| IL Dept of Agriculture |  SANDWICH FAIR ASSOCIATION INC  | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 605482196        | 
| IL Dept of Agriculture |  STEPHENSON COUNTY FAIR ASSOC   | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 610489658        | 
| IL Dept of Agriculture |  BUREAU CO FAIR BOARD           | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 613560238        | 
| IL Dept of Agriculture |  MERCER COUNTY FAIR ASSOCIATION | Rehabilitation reimbursement to county fairs for rehabilitation of fairgrounds, its buildings, facilities and construction projects statute 30ILCS 120/13 | 13250.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 612312314        | 
```