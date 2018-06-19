# Choose Maryland: Compare States - Quality Of Life

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/choose-maryland-compare-states-quality-of-life) |
| Metadata | [Link](https://data.maryland.gov/api/views/cz6x-aq2i) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/cz6x-aq2i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/cz6x-aq2i/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | cz6x-aq2i |
| Name | Choose Maryland: Compare States - Quality Of Life |
| Attribution | Maryland Department of Commerce |
| Category | Health and Human Services |
| Tags | maryland, state, compare |
| Created | 2013-08-20T17:28:03Z |
| Publication Date | 2017-03-31T16:05:41Z |

## Description

Key quality of life indicators.

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========================================================== | ========================================================== | ========= | =========== |
| No       | time           | :updated_at                                                | updated_at                                                 | meta_data | meta_data   |
| Yes      | series tag     | state                                                      | State                                                      | text      | text        |
| Yes      | numeric metric | number_of_america_s_byways                                 | Number of America's Byways                                 | number    | number      |
| Yes      | numeric metric | number_of_national_parks                                   | Number of National Parks                                   | number    | number      |
| Yes      | numeric metric | number_of_national_historic_landmarks                      | Number of National Historic Landmarks                      | number    | number      |
| Yes      | numeric metric | national_register_of_historic_places_listings              | National Register of Historic Places Listings              | number    | number      |
| Yes      | numeric metric | state_arts_agency_appropriations_per_capita                | State Arts Agency Appropriations Per Capita                | money     | money       |
| Yes      | numeric metric | broadband_internet                                         | Percent of Households with Broadband Internet              | percent   | percent     |
| Yes      | numeric metric | arts_entertainment_sports_and_media_employment_per_1000    | Arts, Entertainment, Sports and Media Employment per 1000  | number    | number      |
| Yes      | numeric metric | well_being_index                                           | Well-Being Index                                           | number    | number      |
| Yes      | numeric metric | total_professionally_active_physicians_per_1000_population | Total Professionally Active Physicians per 1000 Population | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cz6x-aq2i d:2017-03-31T16:05:27.000Z t:state=Alabama m:broadband_internet=68.3 m:number_of_america_s_byways=4 m:national_register_of_historic_places_listings=1280 m:arts_entertainment_sports_and_media_employment_per_1000=9.08 m:number_of_national_historic_landmarks=38 m:well_being_index=61 m:number_of_national_parks=7 m:total_professionally_active_physicians_per_1000_population=2.33 m:state_arts_agency_appropriations_per_capita=0.97

series e:cz6x-aq2i d:2017-03-31T16:05:27.000Z t:state=Alaska m:broadband_internet=81.7 m:number_of_america_s_byways=5 m:national_register_of_historic_places_listings=423 m:arts_entertainment_sports_and_media_employment_per_1000=10.32 m:number_of_national_historic_landmarks=50 m:well_being_index=64 m:number_of_national_parks=24 m:total_professionally_active_physicians_per_1000_population=2.36 m:state_arts_agency_appropriations_per_capita=0.95

series e:cz6x-aq2i d:2017-03-31T16:05:27.000Z t:state=Arizona m:broadband_internet=78.1 m:number_of_america_s_byways=5 m:national_register_of_historic_places_listings=1423 m:arts_entertainment_sports_and_media_employment_per_1000=11.56 m:number_of_national_historic_landmarks=46 m:well_being_index=63.4 m:number_of_national_parks=22 m:total_professionally_active_physicians_per_1000_population=2.43 m:state_arts_agency_appropriations_per_capita=0.22
```

## Meta Commands

```ls
metric m:number_of_america_s_byways p:integer l:"Number of America's Byways" d:"Number of America's Byways" t:dataTypeName=number

metric m:number_of_national_parks p:integer l:"Number of National Parks" d:"Number of National Parks" t:dataTypeName=number

metric m:number_of_national_historic_landmarks p:integer l:"Number of National Historic Landmarks" d:"Number of National Historic Landmarks" t:dataTypeName=number

metric m:national_register_of_historic_places_listings p:integer l:"National Register of Historic Places Listings" d:"National Register of Historic Places Listings" t:dataTypeName=number

metric m:state_arts_agency_appropriations_per_capita p:double l:"State Arts Agency Appropriations Per Capita" d:"State Arts Agency Appropriations Per Capita" t:dataTypeName=money

metric m:broadband_internet p:float l:"Percent of Households with Broadband Internet" d:"Percent of Households with Broadband Internet" t:dataTypeName=percent

metric m:arts_entertainment_sports_and_media_employment_per_1000 p:float l:"Arts, Entertainment, Sports and Media Employment per 1000" d:"Arts, Entertainment, Sports and Media Employment per 1000" t:dataTypeName=number

metric m:well_being_index p:float l:"Well-Being Index" d:"Well-Being Index" t:dataTypeName=number

metric m:total_professionally_active_physicians_per_1000_population p:float l:"Total Professionally Active Physicians per 1000 Population" d:"Total Professionally Active Physicians per 1000 Population" t:dataTypeName=number

entity e:cz6x-aq2i l:"Choose Maryland:  Compare States - Quality Of Life" t:attribution="Maryland Department of Commerce" t:url=https://data.maryland.gov/api/views/cz6x-aq2i

property e:cz6x-aq2i t:meta.view v:id=cz6x-aq2i v:category="Health and Human Services" v:attributionLink=http://commerce.maryland.gov v:averageRating=0 v:name="Choose Maryland:  Compare States - Quality Of Life" v:attribution="Maryland Department of Commerce"

property e:cz6x-aq2i t:meta.view.owner v:id=m2gt-bxeg v:screenName="Mike Grandel" v:displayName="Mike Grandel"

property e:cz6x-aq2i t:meta.view.tableauthor v:id=m2gt-bxeg v:screenName="Mike Grandel" v:roleName=editor v:displayName="Mike Grandel"
```

## Top Records

```ls
| :updated_at | state       | number_of_america_s_byways | number_of_national_parks | number_of_national_historic_landmarks | national_register_of_historic_places_listings | state_arts_agency_appropriations_per_capita | broadband_internet | arts_entertainment_sports_and_media_employment_per_1000 | well_being_index | total_professionally_active_physicians_per_1000_population | 
| =========== | =========== | ========================== | ======================== | ===================================== | ============================================= | =========================================== | ================== | ======================================================= | ================ | ========================================================== | 
| 1490976327  | Alabama     | 4                          | 7                        | 38                                    | 1280                                          | 0.97                                        | 68.3               | 9.08                                                    | 61.0             | 2.33                                                       | 
| 1490976327  | Alaska      | 5                          | 24                       | 50                                    | 423                                           | 0.95                                        | 81.7               | 10.32                                                   | 64.0             | 2.36                                                       | 
| 1490976327  | Arizona     | 5                          | 22                       | 46                                    | 1423                                          | 0.22                                        | 78.1               | 11.56                                                   | 63.4             | 2.43                                                       | 
| 1490976327  | Arkansas    | 3                          | 7                        | 16                                    | 2587                                          | 0.54                                        | 64.2               | 6.86                                                    | 60.8             | 2.21                                                       | 
| 1490976327  | California  | 7                          | 28                       | 148                                   | 2653                                          | 0.39                                        | 81.3               | 19.84                                                   | 63.0             | 2.63                                                       | 
| 1490976327  | Colorado    | 11                         | 13                       | 25                                    | 1477                                          | 0.37                                        | 83.0               | 15.58                                                   | 63.5             | 2.49                                                       | 
| 1490976327  | Connecticut | 2                          | 2                        | 63                                    | 1594                                          | 1.54                                        | 82.0               | 14.86                                                   | 61.7             | 4.03                                                       | 
| 1490976327  | Delaware    | 1                          | 1                        | 14                                    | 692                                           | 3.50                                        | 77.4               | 8.63                                                    | 61.4             | 3.03                                                       | 
| 1490976327  | Florida     | 6                          | 11                       | 46                                    | 1702                                          | 2.15                                        | 77.5               | 11.81                                                   | 63.1             | 2.53                                                       | 
| 1490976327  | Georgia     | 1                          | 11                       | 49                                    | 2086                                          | 0.10                                        | 74.8               | 12.08                                                   | 62.3             | 2.27                                                       | 
```