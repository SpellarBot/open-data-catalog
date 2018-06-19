# Projected New Housing Starts - as Used in Enrollment Projection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/projected-new-housing-starts-as-used-in-enrollment-projection-dbc49) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pa5t-ktd3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pa5t-ktd3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pa5t-ktd3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pa5t-ktd3 |
| Name | Projected New Housing Starts - as Used in Enrollment Projection |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, housing, forecast |
| Created | 2013-07-02T19:03:30Z |
| Publication Date | 2013-11-18T15:16:33Z |

## Description

# of units from projected future housing growth in the City

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                                | Data Type | Render Type |
| ======== | ============== | ======================= | =================================== | ========= | =========== |
| No       | time           | :updated_at             | updated_at                          | meta_data | meta_data   |
| Yes      | series tag     | district                | District                            | text      | text        |
| Yes      | numeric metric | five_year_housing_units | Five Year (2012-2016) Housing Units | number    | number      |
| Yes      | numeric metric | ten_year_housing_units  | Ten Year (2012-2021) Housing Units  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pa5t-ktd3 d:2013-11-15T13:35:43.000Z t:district=1 m:ten_year_housing_units=1238 m:five_year_housing_units=863

series e:pa5t-ktd3 d:2013-11-15T13:35:43.000Z t:district=2 m:ten_year_housing_units=30249 m:five_year_housing_units=23215

series e:pa5t-ktd3 d:2013-11-15T13:35:43.000Z t:district=3 m:ten_year_housing_units=3874 m:five_year_housing_units=3084
```

## Meta Commands

```ls
metric m:five_year_housing_units p:integer l:"Five Year (2012-2016) Housing Units" d:"The amount of five year (2012-2016) housing units projected" t:dataTypeName=number

metric m:ten_year_housing_units p:integer l:"Ten Year (2012-2021) Housing Units" d:"The amount of ten year (2012-2021) housing units projected" t:dataTypeName=number

entity e:pa5t-ktd3 l:"Projected New Housing Starts - as Used in Enrollment Projection" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/pa5t-ktd3

property e:pa5t-ktd3 t:meta.view v:id=pa5t-ktd3 v:category="Housing & Development" v:attributionLink=http://www.nycsca.org/Community/CapitalPlanManagementReportsData/Housing/2009-2018HousingWebChart.pdf v:averageRating=0 v:name="Projected New Housing Starts - as Used in Enrollment Projection" v:attribution="School Construction Authority (SCA)"

property e:pa5t-ktd3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pa5t-ktd3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | district | five_year_housing_units | ten_year_housing_units | 
| =========== | ======== | ======================= | ====================== | 
| 1384522543  | 1        | 863                     | 1238                   | 
| 1384522543  | 2        | 23215                   | 30249                  | 
| 1384522543  | 3        | 3084                    | 3874                   | 
| 1384522543  | 4        | 1028                    | 1028                   | 
| 1384522543  | 5        | 3432                    | 3925                   | 
| 1384522543  | 6        | 536                     | 690                    | 
| 1384522543  | 7        | 4308                    | 5528                   | 
| 1384522543  | 8        | 1047                    | 1053                   | 
| 1384522543  | 9        | 1995                    | 2149                   | 
| 1384522543  | 10       | 1390                    | 2172                   | 
```