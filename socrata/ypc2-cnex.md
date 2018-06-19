# Hawaii String Configurations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-string-configurations) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ypc2-cnex) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ypc2-cnex/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ypc2-cnex/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ypc2-cnex |
| Name | Hawaii String Configurations |
| Created | 2015-02-02T17:15:37Z |
| Publication Date | 2015-02-02T17:16:10Z |

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
series e:ypc2-cnex d:2015-02-02T09:15:40.000Z t:description="Your organization's name. Shouldn't be longer than a couple of words." t:name=customer_name t:value="State of Hawaii" m:row_number.ypc2-cnex=1

series e:ypc2-cnex d:2015-02-02T09:15:40.000Z t:description="Your jurisdiction type. For example: state or commonwealth or county or city." t:name=customer_type t:value=State m:row_number.ypc2-cnex=2

series e:ypc2-cnex d:2015-02-02T09:15:40.000Z t:description="The title of the site to use on the homepage." t:name=site_title t:value="Welcome to the State of Hawaii Budget" m:row_number.ypc2-cnex=3
```

## Meta Commands

```ls
metric m:row_number.ypc2-cnex p:long l:"Row Number"

entity e:ypc2-cnex l:"Hawaii String Configurations" t:url=https://data.hawaii.gov/api/views/ypc2-cnex

property e:ypc2-cnex t:meta.view v:id=ypc2-cnex v:averageRating=0 v:name="Hawaii String Configurations"

property e:ypc2-cnex t:meta.view.owner v:id=n97x-2qif v:screenName="Tim Wang" v:displayName="Tim Wang"

property e:ypc2-cnex t:meta.view.tableauthor v:id=n97x-2qif v:screenName="Tim Wang" v:displayName="Tim Wang"
```

## Top Records

```ls
| :updated_at | name                | description                                                                                   | value                                 | 
| =========== | =================== | ============================================================================================= | ===================================== | 
| 1422868540  | customer_name       | Your organization's name. Shouldn't be longer than a couple of words.                         | State of Hawaii                       | 
| 1422868540  | customer_type       | Your jurisdiction type. For example: state or commonwealth or county or city.                 | State                                 | 
| 1422868540  | site_title          | The title of the site to use on the homepage.                                                 | Welcome to the State of Hawaii Budget | 
| 1422868540  | browser_title       | The title of the site to use in the browser window.                                           | Budget | State of Hawaii              | 
| 1422868540  | header_link         | Where clicking the logo at the top of the page should direct to.                              | http://data.hawaii.gov                | 
| 1422868540  | recommending_entity | The entity that creates the recommended budget                                                | Budget Office                         | 
| 1422868540  | region_name         | The title of the regions that each capital project is allocated to. Commonly called district. | County                                | 
```