# Alcoholic Beverage License Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/alcoholic-beverage-license-violations) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/4tja-rkhg) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/4tja-rkhg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/4tja-rkhg/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 4tja-rkhg |
| Name | Alcoholic Beverage License Violations |
| Category | Business |
| Tags | liquor, alcohol, license, violations, fines |
| Created | 2013-12-04T11:35:40Z |
| Publication Date | 2017-01-26T16:39:46Z |

## Description

The dataset includes alcohol violations as a result of sale to minor compliance checks, routine inspections and enforcement efforts. Update Frequency: Monthly

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type     | Render Type   |
| ======== | =========== | =============== | =============== | ============= | ============= |
| Yes      | series tag  | facilityname    | FacilityName    | text          | text          |
| No       |             | address         | FacilityAddress | text          | text          |
| Yes      | time        | violationdate   | ViolationDate   | calendar_date | calendar_date |
| Yes      | series tag  | violation       | Violation       | text          | text          |
| Yes      | series tag  | disposition     | Disposition     | text          | text          |
| No       |             | dispositiondate | DispositionDate | calendar_date | calendar_date |
```

## Time Field

```ls
Value = violationdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,dispositiondate
```

## Data Commands

```ls
series e:4tja-rkhg d:2016-01-01T00:00:00.000Z t:violation="DISORDERLY HOUSE" t:facilityname="OGEI'S CHICKEN & SUBS" t:disposition="HEARING; LICENSE REVOKED; STAY PENDING APPEAL" m:row_number.4tja-rkhg=1

series e:4tja-rkhg d:2016-05-18T00:00:00.000Z t:violation="DISORDERLY HOUSE" t:facilityname="AZUL BAR & GRILL" t:disposition="HEARING; $4,000 FINE" m:row_number.4tja-rkhg=2

series e:4tja-rkhg d:2016-03-26T00:00:00.000Z t:violation="NOISE/DISTURBANCE OF THE NEIGHBORHOOD" t:facilityname="OGEI'S CHICKEN & SUBS" t:disposition="HEARING; LICENSE REVOKED; STAY PENDING APPEAL" m:row_number.4tja-rkhg=3
```

## Meta Commands

```ls
metric m:row_number.4tja-rkhg p:long l:"Row Number"

entity e:4tja-rkhg l:"Alcoholic Beverage License Violations" t:url=https://data.montgomerycountymd.gov/api/views/4tja-rkhg

property e:4tja-rkhg t:meta.view v:id=4tja-rkhg v:category=Business v:averageRating=0 v:name="Alcoholic Beverage License Violations"

property e:4tja-rkhg t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:4tja-rkhg t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| facilityname          | address                                              | violationdate       | violation                             | disposition                                   | dispositiondate     | 
| ===================== | ==================================================== | =================== | ===================================== | ============================================= | =================== | 
| OGEI'S CHICKEN & SUBS | 293 MUDDY BRANCH ROAD , GAITHERSBURG, MD 20878       | 2016-01-01T00:00:00 | DISORDERLY HOUSE                      | HEARING; LICENSE REVOKED; STAY PENDING APPEAL | 2016-05-31T00:00:00 | 
| AZUL BAR & GRILL      | 18749 N. FREDERICK ROAD , GAITHERSBURG, MD 20879     | 2016-05-18T00:00:00 | DISORDERLY HOUSE                      | HEARING; $4,000 FINE                          | 2016-09-15T00:00:00 | 
| OGEI'S CHICKEN & SUBS | 293 MUDDY BRANCH ROAD , GAITHERSBURG, MD 20878       | 2016-03-26T00:00:00 | NOISE/DISTURBANCE OF THE NEIGHBORHOOD | HEARING; LICENSE REVOKED; STAY PENDING APPEAL | 2016-05-31T00:00:00 | 
| FUSION BAR & GRILL    | 15535 NEW HAMPSHIRE AVENUE , SILVER SPRING, MD 20905 | 2016-03-27T00:00:00 | DISORDERLY HOUSE                      | HEARING; LICENSE REVOKED                      | 2016-10-05T00:00:00 | 
| FUSION BAR & GRILL    | 15535 NEW HAMPSHIRE AVENUE , SILVER SPRING, MD 20905 | 2016-03-27T00:00:00 | INSPECTIONS GENERALLY                 | HEARING; LICENSE REVOKED                      | 2016-10-05T00:00:00 | 
| TEXAS PARRILLADA      | 9631 LOST KNIFE ROAD , GAITHERSBURG, MD 20879        | 2016-05-22T00:00:00 | DISORDERLY HOUSE                      | HEARING; NOT GUILTY                           | 2016-08-04T00:00:00 | 
| FUSION BAR & GRILL    | 15535 NEW HAMPSHIRE AVENUE , SILVER SPRING, MD 20905 | 2016-03-27T00:00:00 | ACTS CONTRARY TO LAW                  | HEARING; LICENSE REVOKED                      | 2016-10-05T00:00:00 | 
| FUSION BAR & GRILL    | 15535 NEW HAMPSHIRE AVENUE , SILVER SPRING, MD 20905 | 2016-03-27T00:00:00 | NOISE/DISTURBANCE OF THE NEIGHBORHOOD | HEARING; LICENSE REVOKED                      | 2016-10-05T00:00:00 | 
| BRIGHTON BEER & WINE  | 225 MUDDY BRANCH ROAD , GAITHERSBURG, MD 20878       | 2016-12-01T00:00:00 | WINDOW TINTING                        | SETTLED; $500.00 + ALERT                      | 2016-12-27T00:00:00 | 
| TALBOTT BEER & WINE   | 1071 ROCKVILLE PIKE , ROCKVILLE, MD 20852            | 2016-12-30T00:00:00 | SALE TO MINOR                         | SETTLED; $1000.00 + ALERT                     | 2017-01-30T00:00:00 | 
```