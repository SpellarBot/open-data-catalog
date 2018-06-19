# DBEDT Average Annual Regular Gasoline Price Hawaii Vs U. S. 2006-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-average-annual-regular-gasoline-price-hawaii-vs-u-s-2006-2010-ecafc) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fsqf-xf57) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fsqf-xf57/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fsqf-xf57/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fsqf-xf57 |
| Name | DBEDT Average Annual Regular Gasoline Price Hawaii Vs U. S. 2006-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | gasoline, energy |
| Created | 2012-08-28T19:17:53Z |
| Publication Date | 2012-08-29T01:16:08Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                      | Data Type | Render Type |
| ======== | ============== | =========================== | ========================= | ========= | =========== |
| Yes      | numeric metric | x_values                    | X Values                  | number    | number      |
| Yes      | numeric metric | maui_county                 | Maui County               | number    | number      |
| Yes      | numeric metric | hawaii_county               | Hawaii County             | number    | number      |
| Yes      | numeric metric | city_amp_county_of_honolulu | City & County of Honolulu | number    | number      |
| Yes      | numeric metric | u_s                         | U.S.                      | number    | number      |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fsqf-xf57 d:2006-01-01T00:00:00.000Z m:u_s=2.565 m:hawaii_county=3.183 m:city_amp_county_of_honolulu=2.983 m:maui_county=3.34 m:x_values=2006

series e:fsqf-xf57 d:2006-01-01T00:00:00.000Z m:u_s=2.788 m:hawaii_county=3.218 m:city_amp_county_of_honolulu=3.091 m:maui_county=3.508 m:x_values=2007

series e:fsqf-xf57 d:2006-01-01T00:00:00.000Z m:u_s=3.247 m:hawaii_county=3.785 m:city_amp_county_of_honolulu=3.655 m:maui_county=4.087 m:x_values=2008
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:maui_county p:float l:"Maui County" t:dataTypeName=number

metric m:hawaii_county p:float l:"Hawaii County" t:dataTypeName=number

metric m:city_amp_county_of_honolulu p:float l:"City &amp; County of Honolulu" t:dataTypeName=number

metric m:u_s p:float l:U.S. t:dataTypeName=number

entity e:fsqf-xf57 l:"DBEDT Average Annual Regular Gasoline Price Hawaii Vs U. S. 2006-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/fsqf-xf57

property e:fsqf-xf57 t:meta.view v:id=fsqf-xf57 v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Average Annual Regular Gasoline Price Hawaii Vs U. S. 2006-2010" v:attribution="Department of Economic Development and Tourism"

property e:fsqf-xf57 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:fsqf-xf57 t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:fsqf-xf57 t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| x_values | maui_county | hawaii_county | city_amp_county_of_honolulu | u_s   | 
| ======== | =========== | ============= | =========================== | ===== | 
| 2006     | 3.340       | 3.183         | 2.983                       | 2.565 | 
| 2007     | 3.508       | 3.218         | 3.091                       | 2.788 | 
| 2008     | 4.087       | 3.785         | 3.655                       | 3.247 | 
| 2009     | 3.199       | 2.960         | 2.825                       | 2.349 | 
| 2010     | 3.845       | 3.488         | 3.373                       | 2.782 | 
```