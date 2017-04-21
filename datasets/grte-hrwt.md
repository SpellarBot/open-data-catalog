# Green Jobs By Industry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/green-jobs-by-industry-143bb) |
| Metadata | [Link](https://data.hawaii.gov/api/views/grte-hrwt) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/grte-hrwt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/grte-hrwt/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | grte-hrwt |
| Name | Green Jobs By Industry |
| Created | 2012-11-21T17:37:15Z |
| Publication Date | 2012-11-21T17:37:57Z |

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | green_jobs_by_industry | Green Jobs by Industry | text      | text        |
| No       |             | _1                     | 2010                   | number    | number      |
| No       |             | _2                     | 2012                   | number    | number      |
| No       |             | _3                     | 2014                   | number    | number      |
| No       |             | _4                     | 2016                   | number    | number      |
| No       |             | _5                     | 2018                   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2,_3,_4,_5
```

## Data Commands

```ls
series e:grte-hrwt d:2012-11-21T09:37:17.000Z t:green_jobs_by_industry="Agriculture, Forestry, Fishing, & Hunting" m:row_number.grte-hrwt=1

series e:grte-hrwt d:2012-11-21T09:37:17.000Z t:green_jobs_by_industry="Construction and Mining" m:row_number.grte-hrwt=2

series e:grte-hrwt d:2012-11-21T09:37:17.000Z t:green_jobs_by_industry=Manufacturing m:row_number.grte-hrwt=3
```

## Meta Commands

```ls
metric m:row_number.grte-hrwt p:long l:"Row Number"

entity e:grte-hrwt l:"Green Jobs By Industry" t:url=https://data.hawaii.gov/api/views/grte-hrwt

property e:grte-hrwt t:meta.view v:id=grte-hrwt v:averageRating=0 v:name="Green Jobs By Industry"

property e:grte-hrwt t:meta.view.owner v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:displayName="Jerome Koehler"

property e:grte-hrwt t:meta.view.tableauthor v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```

## Top Records

```ls
| :updated_at | green_jobs_by_industry                     | _1      | _2      | _3      | _4      | _5      | 
| =========== | ========================================== | ======= | ======= | ======= | ======= | ======= | 
| 1353490637  | Agriculture, Forestry, Fishing, & Hunting  | 278.0   | 413.0   | 544.5   | 676.5   | 807.0   | 
| 1353490637  | Construction and Mining                    | 3330.0  | 4373.0  | 5849.5  | 6789.0  | 7494.0  | 
| 1353490637  | Manufacturing                              | 347.0   | 382.0   | 410.5   | 437.5   | 463.5   | 
| 1353490637  | Transportation, Warehousing, & Utilities   | 389.0   | 406.5   | 431.0   | 444.0   | 450.0   | 
| 1353490637  | Retail and Wholesale Trade                 | 1494.0  | 1611.0  | 1735.5  | 1857.5  | 1973.5  | 
| 1353490637  | Finance, Insurance, and Real Estate        | 98.0    | 5.0     | 5.0     | 5.0     | 5.0     | 
| 1353490637  | Health Care and Social Assistance Services | 183.0   | 197.0   | 240.0   | 232.5   | 249.0   | 
| 1353490637  | Accomodations and Food Services            | 174.0   | 240.0   | 310.0   | 381.5   | 455.0   | 
| 1353490637  | Other Services                             | 4854.0  | 5494.0  | 6148.5  | 6778.0  | 7353.0  | 
| 1353490637  | Total                                      | 11147.0 | 13122.0 | 15675.0 | 17602.0 | 19250.0 | 
```