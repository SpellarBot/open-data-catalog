# Medford Limited Maintenance Plan

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medford-limited-maintenance-plan) |
| Metadata | [Link](https://data.oregon.gov/api/views/pjba-5k5q) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/pjba-5k5q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/pjba-5k5q/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | pjba-5k5q |
| Name | Medford Limited Maintenance Plan |
| Created | 2015-08-05T21:03:29Z |
| Publication Date | 2015-09-24T23:22:51Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email_address       | Email Address       | email     | email       |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | comment             | Comment             | html      | html        |
| Yes      | series tag  | additional_document | Additional Document | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pjba-5k5q d:2015-08-19T08:34:28.000Z t:first_name=Diane t:organization=350Deschutes t:state=OR t:last_name=Hodiak t:comment="I encourage stronger emission standards. Multnomah County, which includes Portland, has the 4th highest level of diesel soot of all US counties, and more than Los Angeles County, and the State of Oregon has the 6th highest levels among all 50 states. This is because environmental laws are so lax throughout the state. Old trucks, unacceptable in other states, are allowed to operate here. As vehicle traffic increases, this will only worse." t:email_address=dhodiak@comcast.net m:row_number.pjba-5k5q=1
```

## Meta Commands

```ls
metric m:row_number.pjba-5k5q p:long l:"Row Number"

entity e:pjba-5k5q l:"Medford Limited Maintenance Plan" t:url=https://data.oregon.gov/api/views/pjba-5k5q

property e:pjba-5k5q t:meta.view v:id=pjba-5k5q v:averageRating=0 v:name="Medford Limited Maintenance Plan"

property e:pjba-5k5q t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:pjba-5k5q t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| :updated_at | first_name | last_name | email_address       | organization | state | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                   | additional_document      | 
| =========== | ========== | ========= | =================== | ============ | ===== | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ======================== | 
| 1439973268  | Diane      | Hodiak    | dhodiak@comcast.net | 350Deschutes | OR    | I encourage stronger emission standards. Multnomah County, which includes Portland, has the 4th highest level of diesel soot of all US counties, and more than Los Angeles County, and the State of Oregon has the 6th highest levels among all 50 states. This is because environmental laws are so lax throughout the state. Old trucks, unacceptable in other states, are allowed to operate here. As vehicle traffic increases, this will only worse. | [null, null, null, null] | 
```