# Title Insurance Premiums Written Annually in New York: Beginning 1998

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/title-insurance-premiums-written-annually-in-new-york-beginning-1998) |
| Metadata | [Link](https://data.ny.gov/api/views/ixxq-mken) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ixxq-mken/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ixxq-mken/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ixxq-mken |
| Name | Title Insurance Premiums Written Annually in New York: Beginning 1998 |
| Attribution | Insurance Division - Property Bureau |
| Category | Government & Finance |
| Tags | insurance, property, casualty, licensed, title |
| Created | 2013-04-16T21:16:09Z |
| Publication Date | 2016-11-29T21:43:27Z |

## Description

Total written premiums for insurers authorized to write Title insurance business in New York State.  These insurers are required under Article 64 of the New York Insurance Law to meet minimum financial security requirements.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | naic_no                | NAIC No                | text      | number      |
| Yes      | series tag     | company                | Company                | text      | text        |
| Yes      | time           | calendar_year          | Calendar Year          | number    | number      |
| Yes      | numeric metric | direct_premium_written | Direct Premium Written | money     | money       |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ixxq-mken d:2015-01-01T00:00:00.000Z t:naic_no=50028 t:company="Ace Capital Title Reins Co" m:direct_premium_written=0

series e:ixxq-mken d:2015-01-01T00:00:00.000Z t:naic_no=51411 t:company="American Guar Title Ins Co" m:direct_premium_written=0

series e:ixxq-mken d:2015-01-01T00:00:00.000Z t:naic_no=15269 t:company="Ameristract Title Ins Co Inc" m:direct_premium_written=0
```

## Meta Commands

```ls
metric m:direct_premium_written p:double l:"Direct Premium Written" d:"Total premium amounts calculated prior to consideration of reinsurance" t:dataTypeName=money

entity e:ixxq-mken l:"Title Insurance Premiums Written Annually in New York: Beginning 1998" t:attribution="Insurance Division - Property Bureau" t:url=https://data.ny.gov/api/views/ixxq-mken

property e:ixxq-mken t:meta.view v:id=ixxq-mken v:category="Government & Finance" v:attributionLink=http://www.dfs.ny.gov v:averageRating=0 v:name="Title Insurance Premiums Written Annually in New York: Beginning 1998" v:attribution="Insurance Division - Property Bureau"

property e:ixxq-mken t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ixxq-mken t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ixxq-mken t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| naic_no | company                        | calendar_year | direct_premium_written | 
| ======= | ============================== | ============= | ====================== | 
| 50028   | Ace Capital Title Reins Co     | 2015          | 0.00                   | 
| 51411   | American Guar Title Ins Co     | 2015          | 0.00                   | 
| 15269   | Ameristract Title Ins Co Inc   | 2015          | 0.00                   | 
| 51578   | AmTrust Title Ins Co           | 2015          | 4080075.00             | 
| 12600   | ARIS Title Ins Co              | 2015          | 567644.00              | 
| 50229   | Chicago Title Ins Co           | 2015          | 142531659.00           | 
| 50083   | Commonwealth Land Title Ins Co | 2015          | 54513849.00            | 
| 51209   | Conestoga Title Ins Co         | 2015          | 794201.00              | 
| 51632   | EnTitle Ins Co                 | 2015          | 4866646.00             | 
| 51586   | Fidelity Natl Title Ins Co     | 2015          | 149557499.00           | 
```