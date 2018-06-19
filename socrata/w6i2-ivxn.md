# Table 23.33 VISITOR ACCOMMODATIONS, BY COUNTY 1965 TO 2014 (number Of Units)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-23-34-visitor-accommodations-by-county-1975-to-2013-number-of-units) |
| Metadata | [Link](https://data.hawaii.gov/api/views/w6i2-ivxn) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/w6i2-ivxn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/w6i2-ivxn/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | w6i2-ivxn |
| Name | Table 23.33 VISITOR ACCOMMODATIONS, BY COUNTY 1965 TO 2014 (number Of Units) |
| Attribution | Department of Economic Development and Tourism |
| Category | Culture and Recreation |
| Tags | visitor, unit, county |
| Created | 2012-08-28T22:11:52Z |
| Publication Date | 2015-10-13T01:47:12Z |

## Description

Source: Hawaii Tourism Authority, Visitor Plant Inventory (annual) Please go to the DBEDT Databook site, http://hawaii.gov/dbedt/info/economic/databook, for the complete data source.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                      | Data Type | Render Type |
| ======== | ============== | =========================== | ========================= | ========= | =========== |
| Yes      | time           | year                        | Year                      | number    | number      |
| Yes      | numeric metric | state_total                 | State total               | number    | number      |
| Yes      | numeric metric | city_amp_county_of_honolulu | City & County of Honolulu | number    | number      |
| Yes      | numeric metric | hawaii_county               | Hawaii County             | number    | number      |
| Yes      | numeric metric | kauai_county                | Kauai County              | number    | number      |
| Yes      | numeric metric | maui_county                 | Maui County               | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:w6i2-ivxn d:1975-01-01T00:00:00.000Z m:state_total=39632 m:hawaii_county=5348 m:city_amp_county_of_honolulu=25352 m:maui_county=5830 m:kauai_county=3102

series e:w6i2-ivxn d:1976-01-01T00:00:00.000Z m:state_total=42648 m:hawaii_county=6045 m:city_amp_county_of_honolulu=25851 m:maui_county=7232 m:kauai_county=3520

series e:w6i2-ivxn d:1977-01-01T00:00:00.000Z m:state_total=44986 m:hawaii_county=5929 m:city_amp_county_of_honolulu=27363 m:maui_county=8037 m:kauai_county=3657
```

## Meta Commands

```ls
metric m:state_total p:integer l:"State total" t:dataTypeName=number

metric m:city_amp_county_of_honolulu p:integer l:"City & County of Honolulu" t:dataTypeName=number

metric m:hawaii_county p:integer l:"Hawaii County" t:dataTypeName=number

metric m:kauai_county p:integer l:"Kauai County" t:dataTypeName=number

metric m:maui_county p:integer l:"Maui County" t:dataTypeName=number

entity e:w6i2-ivxn l:"Table 23.33 VISITOR ACCOMMODATIONS, BY COUNTY  1965 TO 2014 (number Of Units)" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/w6i2-ivxn

property e:w6i2-ivxn t:meta.view v:id=w6i2-ivxn v:category="Culture and Recreation" v:attributionLink=http://hawaii.gov/dbedt/info/economic/databook v:averageRating=0 v:name="Table 23.33 VISITOR ACCOMMODATIONS, BY COUNTY  1965 TO 2014 (number Of Units)" v:attribution="Department of Economic Development and Tourism"

property e:w6i2-ivxn t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:w6i2-ivxn t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:w6i2-ivxn t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | state_total | city_amp_county_of_honolulu | hawaii_county | kauai_county | maui_county | 
| ==== | =========== | =========================== | ============= | ============ | =========== | 
| 1975 | 39632       | 25352                       | 5348          | 3102         | 5830        | 
| 1976 | 42648       | 25851                       | 6045          | 3520         | 7232        | 
| 1977 | 44986       | 27363                       | 5929          | 3657         | 8037        | 
| 1978 | 47070       | 28546                       | 6002          | 3786         | 8736        | 
| 1979 | 49832       | 30065                       | 6093          | 4202         | 9472        | 
| 1980 | 54246       | 34334                       | 5889          | 4322         | 9701        | 
| 1981 | 56769       | 33967                       | 6705          | 4738         | 11359       | 
| 1982 | 57968       | 33492                       | 7167          | 5147         | 12162       | 
| 1983 | 58765       | 34354                       | 7469          | 4193         | 12749       | 
| 1984 | 62448       | 36848                       | 7149          | 5313         | 13138       | 
```