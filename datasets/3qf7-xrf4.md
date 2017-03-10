# Cook County Clerk - Polling Place Locations - 2014 November 4 Gubernatorial Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-clerk-polling-place-locations-2014-november-4-gubernatorial-election-d302d) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/3qf7-xrf4) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3qf7-xrf4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3qf7-xrf4/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 3qf7-xrf4 |
| Name | Cook County Clerk - Polling Place Locations - 2014 November 4 Gubernatorial Election |
| Attribution | Cook County Clerk |
| Category | Finance & Administration |
| Tags | elections, voting, vote, polling locations |
| Created | 2014-10-17T16:18:17Z |
| Publication Date | 2014-10-27T19:46:26Z |
| Rows Updated | 2014-10-27T19:45:57Z |

## Description

Data Updated 10/27/2014. This dataset contains the Polling Place locations in suburban Cook County for the 2014 Gubernatorial Election on November 4. For more information on Polling Locations see http://www.cookcountyclerk.com/elections/pollinglocations/Pages/default.aspx

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | precinct                    | Precinct                    | text      | number      |
| Yes      | series tag  | polling_place_id            | Polling Place ID            | text      | number      |
| Yes      | series tag  | polling_place_location_name | Polling Place Location Name | text      | text        |
| Yes      | series tag  | accessible                  | Accessible                  | text      | text        |
| No       |             | address                     | Address                     | text      | text        |
| Yes      | series tag  | city                        | City                        | text      | text        |
| Yes      | series tag  | zip                         | Zip                         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:3qf7-xrf4 l:"Cook County Clerk - Polling Place Locations - 2014 November 4 Gubernatorial Election" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/3qf7-xrf4

property e:3qf7-xrf4 t:meta.view d:2017-03-10T16:08:13.908Z v:id=3qf7-xrf4 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyclerk.com/elections/pollinglocations/Pages/default.aspx v:averageRating=0 v:name="Cook County Clerk - Polling Place Locations - 2014 November 4 Gubernatorial Election" v:attribution="Cook County Clerk"

property e:3qf7-xrf4 t:meta.view.license d:2017-03-10T16:08:13.908Z v:name="Public Domain"

property e:3qf7-xrf4 t:meta.view.owner d:2017-03-10T16:08:13.908Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"

property e:3qf7-xrf4 t:meta.view.tableauthor d:2017-03-10T16:08:13.908Z v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:displayName="Cook County Open Data"
```