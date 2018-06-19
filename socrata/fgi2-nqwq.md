# Fairs and Expositions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fairs-and-expositions-ffb71) |
| Metadata | [Link](https://data.illinois.gov/api/views/fgi2-nqwq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/fgi2-nqwq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/fgi2-nqwq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | fgi2-nqwq |
| Name | Fairs and Expositions |
| Created | 2014-06-27T20:32:09Z |
| Publication Date | 2014-06-27T20:32:46Z |

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
series e:fgi2-nqwq d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=601740521 t:description_of_purpose_of_award="FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17" t:grantee="KANE COUNTY FAIR" m:grant_amount=83256 m:duration_in_days=365

series e:fgi2-nqwq d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=601872401 t:description_of_purpose_of_award="FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17" t:grantee="DUPAGE COUNTY FAIR" m:grant_amount=204989.3 m:duration_in_days=365

series e:fgi2-nqwq d:2012-07-01T00:00:00.000Z t:grantor_agency="IL Dept of Agriculture" t:grantee_zip_code=612440387 t:description_of_purpose_of_award="FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17" t:grantee="ROCK ISLAND CNTY AGRICULTURAL" m:grant_amount=39169.18 m:duration_in_days=365
```

## Meta Commands

```ls
metric m:grant_amount p:float l:"Grant Amount" t:dataTypeName=number

metric m:duration_in_days p:integer l:"Duration (in days)" t:dataTypeName=number

entity e:fgi2-nqwq l:"Fairs and Expositions" t:url=https://data.illinois.gov/api/views/fgi2-nqwq

property e:fgi2-nqwq t:meta.view v:id=fgi2-nqwq v:averageRating=0 v:name="Fairs and Expositions"

property e:fgi2-nqwq t:meta.view.owner v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"

property e:fgi2-nqwq t:meta.view.tableauthor v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"
```

## Top Records

```ls
| grantor_agency         | grantee                         | description_of_purpose_of_award                         | grant_amount | start_date          | completion_date     | duration_in_days | grantee_zip_code | 
| ====================== | =============================== | ======================================================= | ============ | =================== | =================== | ================ | ================ | 
| IL Dept of Agriculture |  KANE COUNTY FAIR               | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 83256.00     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 601740521        | 
| IL Dept of Agriculture |  DUPAGE COUNTY FAIR             | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 204989.30    | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 601872401        | 
| IL Dept of Agriculture |  ROCK ISLAND CNTY AGRICULTURAL  | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 39169.18     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 612440387        | 
| IL Dept of Agriculture |  WILL COUNTY FAIR ASSOCIATION   | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 93704.09     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 609501054        | 
| IL Dept of Agriculture |  LAKE COUNTY FAIR ASSOCIATION   | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 135428.90    | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 600300216        | 
| IL Dept of Agriculture |  MCHENRY COUNTY FAIR ASSOC      | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 49985.70     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 600980375        | 
| IL Dept of Agriculture |  WINNEBAGO COUNTY FAIR ASSOC    | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 66382.84     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 610888769        | 
| IL Dept of Agriculture |  SANGAMON COUNTY FAIR AND       | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 46781.02     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 626700147        | 
| IL Dept of Agriculture |  EXPOSITION GARDENS INC         | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 47945.66     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 616143436        | 
| IL Dept of Agriculture |  MCLEAN COUNTY FAIR ASSOCIATION | FAIR AND EXPOSITION REIMBURSEMENT STATUTE 30ILCS 120/17 | 32860.68     | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 365              | 617045147        | 
```