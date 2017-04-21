# Timber Harvest Data 1942-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/timber-harvest-data-1942-2015-81bed) |
| Metadata | [Link](https://data.oregon.gov/api/views/v7yh-3r7a) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/v7yh-3r7a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/v7yh-3r7a/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | v7yh-3r7a |
| Name | Timber Harvest Data 1942-2015 |
| Attribution | Oregon Department of Forestry |
| Category | Natural Resources |
| Tags | forestry, natural resources, forest economics, timber harvest |
| Created | 2016-08-08T22:08:06Z |
| Publication Date | 2016-08-08T22:14:22Z |

## Description

This is all timber harvest data for Oregon. The 25 year report is available as a .pdf in the "About" tab to the right.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | county               | County               | text      | text        |
| Yes      | time           | year                 | Year                 | number    | text        |
| Yes      | numeric metric | blm                  | BLM                  | number    | number      |
| Yes      | numeric metric | usfs                 | USFS                 | number    | number      |
| Yes      | numeric metric | state                | State                | number    | number      |
| Yes      | numeric metric | county_and_municipal | County and Municipal | number    | number      |
| Yes      | numeric metric | native_american      | Native American      | number    | number      |
| Yes      | numeric metric | industry             | Industry             | number    | number      |
| Yes      | numeric metric | nip                  | NIP                  | number    | number      |
| Yes      | numeric metric | total_of_volume      | Total Of Volume      | number    | number      |
| Yes      | numeric metric | total_private        | Total Private        | number    | number      |
| Yes      | numeric metric | total_public         | Total Public         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v7yh-3r7a d:1962-01-01T00:00:00.000Z t:county=BAKER m:native_american=0 m:county_and_municipal=0 m:state=0 m:total_public=64758 m:blm=5858 m:nip=6540 m:industry=0 m:usfs=58900 m:total_of_volume=71298 m:total_private=6540

series e:v7yh-3r7a d:1963-01-01T00:00:00.000Z t:county=BAKER m:native_american=0 m:state=0 m:total_public=61967 m:blm=767 m:nip=2729 m:industry=256 m:usfs=61200 m:total_of_volume=64952 m:total_private=2985

series e:v7yh-3r7a d:1964-01-01T00:00:00.000Z t:county=BAKER m:native_american=0 m:state=11 m:total_public=104383 m:blm=272 m:nip=6252 m:industry=0 m:usfs=104100 m:total_of_volume=110635 m:total_private=6252
```

## Meta Commands

```ls
metric m:blm p:float l:BLM t:dataTypeName=number

metric m:usfs p:float l:USFS t:dataTypeName=number

metric m:state p:float l:State t:dataTypeName=number

metric m:county_and_municipal p:float l:"County and Municipal" t:dataTypeName=number

metric m:native_american p:float l:"Native American" t:dataTypeName=number

metric m:industry p:float l:Industry t:dataTypeName=number

metric m:nip p:float l:NIP t:dataTypeName=number

metric m:total_of_volume p:float l:"Total Of Volume" t:dataTypeName=number

metric m:total_private p:float l:"Total Private" t:dataTypeName=number

metric m:total_public p:float l:"Total Public" t:dataTypeName=number

entity e:v7yh-3r7a l:"Timber Harvest Data 1942-2015" t:attribution="Oregon Department of Forestry" t:url=https://data.oregon.gov/api/views/v7yh-3r7a

property e:v7yh-3r7a t:meta.view v:id=v7yh-3r7a v:category="Natural Resources" v:averageRating=0 v:name="Timber Harvest Data 1942-2015" v:attribution="Oregon Department of Forestry"

property e:v7yh-3r7a t:meta.view.license v:name="Public Domain"

property e:v7yh-3r7a t:meta.view.owner v:id=s5qg-kz93 v:screenName="Brandon Kaetzel" v:displayName="Brandon Kaetzel"

property e:v7yh-3r7a t:meta.view.tableauthor v:id=s5qg-kz93 v:screenName="Brandon Kaetzel" v:roleName=editor v:displayName="Brandon Kaetzel"
```

## Top Records

```ls
| county | year | blm     | usfs      | state | county_and_municipal | native_american | industry | nip      | total_of_volume | total_private | total_public | 
| ====== | ==== | ======= | ========= | ===== | ==================== | =============== | ======== | ======== | =============== | ============= | ============ | 
| BAKER  | 1962 | 5858.00 | 58900.00  | 0.0   | 0.0                  | 0.0             | 0.0      | 6540.00  | 71298.00        | 6540.00       | 64758.00     | 
| BAKER  | 1963 | 767.00  | 61200.00  | 0.0   |                      | 0.0             | 256.00   | 2729.00  | 64952.00        | 2985.00       | 61967.00     | 
| BAKER  | 1964 | 272.00  | 104100.00 | 11.00 |                      | 0.0             | 0.0      | 6252.00  | 110635.00       | 6252.00       | 104383.00    | 
| BAKER  | 1965 | 68.00   | 107800.00 | 0.0   | 0.0                  | 0.0             | 0.0      | 1151.00  | 109019.00       | 1151.00       | 107868.00    | 
| BAKER  | 1966 | 17.00   | 114900.00 | 0.0   | 0.0                  | 0.0             | 0.0      | 350.00   | 115267.00       | 350.00        | 114917.00    | 
| BAKER  | 1967 | 439.00  | 93000.00  | 0.0   | 0.0                  | 0.0             | 0.0      | 2747.00  | 96186.00        | 2747.00       | 93439.00     | 
| BAKER  | 1968 | 2916.00 | 103047.00 | 0.0   | 0.0                  | 0.0             | 4675.00  | 0.0      | 110638.00       | 4675.00       | 105963.00    | 
| BAKER  | 1969 | 802.00  | 91004.00  | 0.0   | 0.0                  | 0.0             | 0.0      | 10766.00 | 102572.00       | 10766.00      | 91806.00     | 
| BAKER  | 1970 | 1109.00 | 61379.00  | 0.0   | 0.0                  | 0.0             | 0.0      | 4007.00  | 66495.00        | 4007.00       | 62488.00     | 
| BAKER  | 1971 | 35.00   | 83208.00  | 0.0   | 0.0                  | 0.0             | 567.00   | 53142.00 | 136952.00       | 53709.00      | 83243.00     | 
```