# Choose Maryland: Compare Metros - Quality of Life

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-metros-quality-of-life) |
| Metadata | [Link](https://data.maryland.gov/api/views/yjpu-x8hr) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/yjpu-x8hr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/yjpu-x8hr/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | yjpu-x8hr |
| Name | Choose Maryland: Compare Metros - Quality of Life |
| Attribution | Maryland Department of Commerce |
| Category | Housing |
| Tags | maryland, baltimore, metro, compare, housing, home, price |
| Created | 2013-08-22T15:40:00Z |
| Publication Date | 2017-03-31T16:07:11Z |

## Description

Key quality of life indicators - housing costs, arts.

## Columns

```ls
| Included | Schema Type    | Field Name                                              | Name                                                      | Data Type | Render Type |
| ======== | ============== | ======================================================= | ========================================================= | ========= | =========== |
| No       | time           | :updated_at                                             | updated_at                                                | meta_data | meta_data   |
| Yes      | series tag     | metro                                                   | Metro                                                     | text      | text        |
| Yes      | numeric metric | med_selling_price_existing_homes                        | Median Selling Price, Existing Homes ($ Dollars)          | money     | money       |
| Yes      | numeric metric | arts_entertainment_sports_and_media_employment_per_1000 | Arts, Entertainment, Sports and Media Employment per 1000 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yjpu-x8hr d:2017-03-31T16:06:59.000Z t:metro="Atlanta metro" m:arts_entertainment_sports_and_media_employment_per_1000=14.28 m:med_selling_price_existing_homes=173600

series e:yjpu-x8hr d:2017-03-31T16:06:59.000Z t:metro="Austin, TX metro" m:arts_entertainment_sports_and_media_employment_per_1000=16.96 m:med_selling_price_existing_homes=263300

series e:yjpu-x8hr d:2017-03-31T16:06:59.000Z t:metro="Baltimore metro" m:arts_entertainment_sports_and_media_employment_per_1000=11.22 m:med_selling_price_existing_homes=242800
```

## Meta Commands

```ls
metric m:med_selling_price_existing_homes p:integer l:"Median Selling Price, Existing Homes ($ Dollars)" t:dataTypeName=money

metric m:arts_entertainment_sports_and_media_employment_per_1000 p:float l:"Arts, Entertainment, Sports and Media Employment per 1000" t:dataTypeName=number

entity e:yjpu-x8hr l:"Choose Maryland:  Compare Metros - Quality of Life" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/yjpu-x8hr

property e:yjpu-x8hr t:meta.view v:id=yjpu-x8hr v:category=Housing v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare Metros - Quality of Life" v:attribution="Maryland Department of Commerce"

property e:yjpu-x8hr t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:yjpu-x8hr t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | metro               | med_selling_price_existing_homes | arts_entertainment_sports_and_media_employment_per_1000 | 
| =========== | =================== | ================================ | ======================================================= | 
| 1490976419  | Atlanta metro       | 173600                           | 14.28                                                   | 
| 1490976419  | Austin, TX metro    | 263300                           | 16.96                                                   | 
| 1490976419  | Baltimore metro     | 242800                           | 11.22                                                   | 
| 1490976419  | Birmingham metro    | 178500                           | 11.82                                                   | 
| 1490976419  | Boston metro        | 403900                           | 15.41                                                   | 
| 1490976419  | Buffalo metro       | 129800                           | 10.15                                                   | 
| 1490976419  | Charlotte metro     | 194000                           | 11.81                                                   | 
| 1490976419  | Chicago metro       | 218900                           | 12.49                                                   | 
| 1490976419  | Cincinnati metro    | 145400                           | 11.68                                                   | 
| 1490976419  | Cleveland, OH metro | 125100                           | 12.13                                                   | 
```