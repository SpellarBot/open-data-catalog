# DBEDT Hawaii Annual Electricity Cost And Consumption 2006-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-annual-electricity-cost-and-consumption-2006-2010-3d9bd) |
| Metadata | [Link](https://data.hawaii.gov/api/views/dnwk-g44q) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/dnwk-g44q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/dnwk-g44q/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | dnwk-g44q |
| Name | DBEDT Hawaii Annual Electricity Cost And Consumption 2006-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | electricity, energy |
| Created | 2012-08-28T19:40:44Z |
| Publication Date | 2012-08-29T01:27:11Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                      | Data Type | Render Type |
| ======== | ============== | =========================== | ========================= | ========= | =========== |
| Yes      | numeric metric | x_values                    | X Values                  | number    | number      |
| Yes      | numeric metric | city_amp_county_of_honolulu | City & County of Honolulu | number    | number      |
| Yes      | numeric metric | maui_county                 | Maui County               | number    | number      |
| Yes      | numeric metric | hawaii_county               | Hawaii County             | number    | number      |
| Yes      | numeric metric | kauai_county                | Kauai County              | number    | number      |
| Yes      | numeric metric | state_cost                  | State Cost                | number    | number      |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dnwk-g44q d:2006-01-01T00:00:00.000Z m:state_cost=2190152387 m:hawaii_county=1148760827 m:city_amp_county_of_honolulu=7700604915 m:maui_county=1266466780 m:x_values=2006 m:kauai_county=452079711

series e:dnwk-g44q d:2006-01-01T00:00:00.000Z m:state_cost=2253431463 m:hawaii_county=1162683764 m:city_amp_county_of_honolulu=7675354990 m:maui_county=1280102549 m:x_values=2007 m:kauai_county=466895789

series e:dnwk-g44q d:2006-01-01T00:00:00.000Z m:state_cost=3033950142 m:hawaii_county=1141029607 m:city_amp_county_of_honolulu=7555961805 m:maui_county=1239228345 m:x_values=2008 m:kauai_county=453790517
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:city_amp_county_of_honolulu p:long l:"City &amp; County of Honolulu" t:dataTypeName=number

metric m:maui_county p:integer l:"Maui County" t:dataTypeName=number

metric m:hawaii_county p:integer l:"Hawaii County" t:dataTypeName=number

metric m:kauai_county p:integer l:"Kauai County" t:dataTypeName=number

metric m:state_cost p:long l:"State Cost" t:dataTypeName=number

entity e:dnwk-g44q l:"DBEDT Hawaii Annual Electricity Cost And Consumption 2006-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/dnwk-g44q

property e:dnwk-g44q t:meta.view v:id=dnwk-g44q v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii Annual Electricity Cost And Consumption 2006-2010" v:attribution="Department of Economic Development and Tourism"

property e:dnwk-g44q t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:dnwk-g44q t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:dnwk-g44q t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values | city_amp_county_of_honolulu | maui_county | hawaii_county | kauai_county | state_cost | 
| ======== | =========================== | =========== | ============= | ============ | ========== | 
| 2006     | 7700604915                  | 1266466780  | 1148760827    | 452079711    | 2190152387 | 
| 2007     | 7675354990                  | 1280102549  | 1162683764    | 466895789    | 2253431463 | 
| 2008     | 7555961805                  | 1239228345  | 1141029607    | 453790517    | 3033950142 | 
| 2009     | 7377537123                  | 1192243436  | 1119881301    | 436273236    | 2148123027 | 
| 2010     | 7277228851                  | 1191558936  | 1109782654    | 434533319    | 2515731291 | 
```