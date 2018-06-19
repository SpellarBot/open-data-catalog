# String Config

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/string-config-c9c5c) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/w7si-gcgk) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/w7si-gcgk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/w7si-gcgk/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | w7si-gcgk |
| Name | String Config |
| Category | Financial |
| Created | 2014-12-11T18:48:02Z |
| Publication Date | 2014-12-11T18:49:31Z |

## Description

Supporting dataset necessary to launch spendingMontgomery

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | name        | Name        | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
| Yes      | series tag  | value       | Value       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:w7si-gcgk d:2014-12-11T10:48:07.000Z t:description="Your organization's name. Shouldn't be longer than a couple of words." t:name=customer_name t:value="Montgomery County" m:row_number.w7si-gcgk=1

series e:w7si-gcgk d:2014-12-11T10:48:07.000Z t:description="Your jurisdiction type. For example: state or commonwealth or county or city." t:name=customer_type t:value=county m:row_number.w7si-gcgk=2

series e:w7si-gcgk d:2014-12-11T10:48:07.000Z t:description="The title of the site to use on the homepage." t:name=site_title t:value="Welcome to spendingMontgomery" m:row_number.w7si-gcgk=3
```

## Meta Commands

```ls
metric m:row_number.w7si-gcgk p:long l:"Row Number"

entity e:w7si-gcgk l:"String Config" t:url=https://data.montgomerycountymd.gov/api/views/w7si-gcgk

property e:w7si-gcgk t:meta.view v:id=w7si-gcgk v:category=Financial v:averageRating=0 v:name="String Config"

property e:w7si-gcgk t:meta.view.owner v:id=fnci-gphj v:screenName="MC Open Data" v:displayName="MC Open Data"

property e:w7si-gcgk t:meta.view.tableauthor v:id=fnci-gphj v:screenName="MC Open Data" v:roleName=administrator v:displayName="MC Open Data"
```

## Top Records

```ls
| :updated_at | name          | description                                                                   | value                                | 
| =========== | ============= | ============================================================================= | ==================================== | 
| 1418294887  | customer_name | Your organization's name. Shouldn't be longer than a couple of words.         | Montgomery County                    | 
| 1418294887  | customer_type | Your jurisdiction type. For example: state or commonwealth or county or city. | county                               | 
| 1418294887  | site_title    | The title of the site to use on the homepage.                                 | Welcome to spendingMontgomery        | 
| 1418294887  | browser_title | The title of the site to use in the browser window.                           | Spending | Montgomery County         | 
| 1418294887  | header_link   | Where clicking the logo at the top of the page should direct to.              | https://data.montgomerycountymd.gov/ | 
```