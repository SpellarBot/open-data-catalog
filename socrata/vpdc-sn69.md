# 2012 Primary - Election Results (final daily)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-august-2012-primary-results-king-county-ab890) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/vpdc-sn69) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/vpdc-sn69/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/vpdc-sn69/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | vpdc-sn69 |
| Name | 2012 Primary - Election Results (final daily) |
| Attribution | King County Elections |
| Category | Election results |
| Tags | 2012, 2012 primary, primary, elections, results |
| Created | 2012-08-08T05:25:56Z |
| Publication Date | 2012-08-28T21:09:46Z |

## Description

August 2012 primary election; final daily results report.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | contest      | Contest      | text      | text        |
| Yes      | series tag     | nameonballot | NameOnBallot | text      | text        |
| Yes      | series tag     | party        | Party        | text      | text        |
| Yes      | numeric metric | votes        | Votes        | number    | number      |
| Yes      | numeric metric | percent      | Percent      | percent   | percent     |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vpdc-sn69 d:2012-01-01T00:00:00.000Z t:nameonballot=Approved t:contest="King County Proposition No. 1" m:percent=55.42 m:votes=226544

series e:vpdc-sn69 d:2012-01-01T00:00:00.000Z t:nameonballot=Rejected t:contest="King County Proposition No. 1" m:percent=44.57 m:votes=182205

series e:vpdc-sn69 d:2012-01-01T00:00:00.000Z t:nameonballot="Michael Baumgartner" t:contest="U.S. Senator  partisan office" t:party="(Prefers Republican Party)" m:percent=22.53 m:votes=95062
```

## Meta Commands

```ls
metric m:votes p:integer l:Votes t:dataTypeName=number

metric m:percent p:float l:Percent t:dataTypeName=percent

entity e:vpdc-sn69 l:"2012 Primary - Election Results (final daily)" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/vpdc-sn69

property e:vpdc-sn69 t:meta.view v:id=vpdc-sn69 v:category="Election results" v:attributionLink=http://kingcounty.gov/elections/ v:averageRating=0 v:name="2012 Primary - Election Results (final daily)" v:attribution="King County Elections"

property e:vpdc-sn69 t:meta.view.license v:name="Public Domain"

property e:vpdc-sn69 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:vpdc-sn69 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| contest                       | nameonballot               | party                      | votes  | percent | 
| ============================= | ========================== | ========================== | ====== | ======= | 
| King County Proposition No. 1 | Approved                   |                            | 226544 | 55.42   | 
| King County Proposition No. 1 | Rejected                   |                            | 182205 | 44.57   | 
| U.S. Senator partisan office  | Michael Baumgartner        | (Prefers Republican Party) | 95062  | 22.53   | 
| U.S. Senator partisan office  | Will Baker                 | (Prefers Reform Party)     | 2156   | 0.51    | 
| U.S. Senator partisan office  | Chuck Jackson              | (Prefers Republican Party) | 4230   | 1       | 
| U.S. Senator partisan office  | Timmy (Doc) Wilson         | (Prefers Democratic Party) | 7415   | 1.75    | 
| U.S. Senator partisan office  | Art Coday                  | (Prefers Republican Party) | 20543  | 4.87    | 
| U.S. Senator partisan office  | Maria Cantwell             | (Prefers Democratic Party) | 284999 | 67.56   | 
| U.S. Senator partisan office  | Glen (Stocky) R. Stockwell | (Prefers Republican Party) | 3802   | 0.9     | 
| U.S. Senator partisan office  | Mike the Mover             | (Prefers Republican Party) | 3176   | 0.75    | 
```