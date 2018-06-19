# DBEDT Hawaii Annual Electricity Consumption

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-annual-electricity-consumption-96efd) |
| Metadata | [Link](https://data.hawaii.gov/api/views/biet-37vh) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/biet-37vh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/biet-37vh/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | biet-37vh |
| Name | DBEDT Hawaii Annual Electricity Consumption |
| Created | 2012-11-21T20:36:34Z |
| Publication Date | 2013-11-21T02:32:59Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                                      | Name                                                              | Data Type | Render Type |
| ======== | ============== | =============================================================== | ================================================================= | ========= | =========== |
| Yes      | time           | year                                                            | Year                                                              | number    | number      |
| Yes      | numeric metric | city_and_county_of_honolulu_annual_electricity_consumption_gwhs | City and County of Honolulu Annual Electricity Consumption (GWhs) | number    | number      |
| Yes      | numeric metric | maui_county_annual_electricity_consumption_gwhs                 | Maui County Annual Electricity Consumption (GWhs)                 | number    | number      |
| Yes      | numeric metric | hawaii_county_annual_electricity_consumption_gwhs               | Hawaii County Annual Electricity Consumption (GWhs)               | number    | number      |
| Yes      | numeric metric | kauai_county_annual_electricity_consumption_gwhs                | Kauai County Annual Electricity Consumption (GWhs)                | number    | number      |
| Yes      | numeric metric | total                                                           | Total                                                             | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:biet-37vh d:2006-01-01T00:00:00.000Z m:total=10568 m:city_and_county_of_honolulu_annual_electricity_consumption_gwhs=7701 m:maui_county_annual_electricity_consumption_gwhs=1266 m:kauai_county_annual_electricity_consumption_gwhs=452 m:hawaii_county_annual_electricity_consumption_gwhs=1149

series e:biet-37vh d:2007-01-01T00:00:00.000Z m:total=10585 m:city_and_county_of_honolulu_annual_electricity_consumption_gwhs=7675 m:maui_county_annual_electricity_consumption_gwhs=1280 m:kauai_county_annual_electricity_consumption_gwhs=467 m:hawaii_county_annual_electricity_consumption_gwhs=1163

series e:biet-37vh d:2008-01-01T00:00:00.000Z m:total=10390 m:city_and_county_of_honolulu_annual_electricity_consumption_gwhs=7556 m:maui_county_annual_electricity_consumption_gwhs=1239 m:kauai_county_annual_electricity_consumption_gwhs=454 m:hawaii_county_annual_electricity_consumption_gwhs=1141
```

## Meta Commands

```ls
metric m:city_and_county_of_honolulu_annual_electricity_consumption_gwhs p:integer l:"City and County of Honolulu Annual Electricity Consumption (GWhs)" t:dataTypeName=number

metric m:maui_county_annual_electricity_consumption_gwhs p:integer l:"Maui County Annual Electricity Consumption (GWhs)" t:dataTypeName=number

metric m:hawaii_county_annual_electricity_consumption_gwhs p:integer l:"Hawaii County Annual Electricity Consumption (GWhs)" t:dataTypeName=number

metric m:kauai_county_annual_electricity_consumption_gwhs p:integer l:"Kauai County Annual Electricity Consumption (GWhs)" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:biet-37vh l:"DBEDT Hawaii Annual Electricity Consumption" t:url=https://data.hawaii.gov/api/views/biet-37vh

property e:biet-37vh t:meta.view v:id=biet-37vh v:averageRating=0 v:name="DBEDT Hawaii Annual Electricity Consumption"

property e:biet-37vh t:meta.view.owner v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:displayName="Jerome Koehler"

property e:biet-37vh t:meta.view.tableauthor v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```

## Top Records

```ls
| year | city_and_county_of_honolulu_annual_electricity_consumption_gwhs | maui_county_annual_electricity_consumption_gwhs | hawaii_county_annual_electricity_consumption_gwhs | kauai_county_annual_electricity_consumption_gwhs | total | 
| ==== | =============================================================== | =============================================== | ================================================= | ================================================ | ===== | 
| 2006 | 7701                                                            | 1266                                            | 1149                                              | 452                                              | 10568 | 
| 2007 | 7675                                                            | 1280                                            | 1163                                              | 467                                              | 10585 | 
| 2008 | 7556                                                            | 1239                                            | 1141                                              | 454                                              | 10390 | 
| 2009 | 7378                                                            | 1192                                            | 1120                                              | 436                                              | 10126 | 
| 2010 | 7277                                                            | 1192                                            | 1110                                              | 434                                              | 10013 | 
| 2011 | 7242                                                            | 1181                                            | 1104                                              | 435                                              | 9962  | 
```