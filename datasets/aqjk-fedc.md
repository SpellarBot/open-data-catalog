# String Config

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/string-config-1c28c) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/aqjk-fedc) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/aqjk-fedc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/aqjk-fedc/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | aqjk-fedc |
| Name | String Config |
| Category | Financial |
| Tags | string, text, config |
| Created | 2014-09-17T18:10:03Z |
| Publication Date | 2014-09-17T18:12:04Z |

## Description

Dataset created for budgetMontgomery purposes

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
series e:aqjk-fedc d:2014-09-17T11:10:05.000Z t:description="Your organization's name. Shouldn't be longer than a couple of words." t:name=customer_name t:value="Montgomery County" m:row_number.aqjk-fedc=1

series e:aqjk-fedc d:2014-09-17T11:10:05.000Z t:description="Your jurisdiction type. For example: state or commonwealth or county or city." t:name=customer_type t:value=County m:row_number.aqjk-fedc=2

series e:aqjk-fedc d:2014-09-17T11:10:05.000Z t:description="The title of the site to use on the homepage." t:name=site_title t:value="Welcome to budgetMontgomery" m:row_number.aqjk-fedc=3
```

## Meta Commands

```ls
metric m:row_number.aqjk-fedc p:long l:"Row Number"

entity e:aqjk-fedc l:"String Config" t:url=https://data.montgomerycountymd.gov/api/views/aqjk-fedc

property e:aqjk-fedc t:meta.view v:id=aqjk-fedc v:category=Financial v:averageRating=0 v:name="String Config"

property e:aqjk-fedc t:meta.view.owner v:id=qzhb-tftn v:screenName="Kathy Luh" v:displayName="Kathy Luh"

property e:aqjk-fedc t:meta.view.tableauthor v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```

## Top Records

```ls
| :updated_at | name                | description                                                                   | value                             | 
| =========== | =================== | ============================================================================= | ================================= | 
| 1410952205  | customer_name       | Your organization's name. Shouldn't be longer than a couple of words.         | Montgomery County                 | 
| 1410952205  | customer_type       | Your jurisdiction type. For example: state or commonwealth or county or city. | County                            | 
| 1410952205  | site_title          | The title of the site to use on the homepage.                                 | Welcome to budgetMontgomery       | 
| 1410952205  | browser_title       | The title of the site to use in the browser window.                           | budgetMontgomery                  | 
| 1410952205  | header_link         | Where clicking the logo at the top of the page should direct to.              | http://www.montgomerycountymd.gov | 
| 1410952205  | recommending_entity | The entity that creates the recommended budget                                | County Executive                  | 
| 1410952205  | region_name         | What to call each geographic area; eg county or neighborhood or district      | Council District                  | 
```