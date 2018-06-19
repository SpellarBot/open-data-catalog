# Water And Electric Res 2005-2013 By Zip

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-and-electric-res-2005-2013-by-zip) |
| Metadata | [Link](https://data.lacity.org/api/views/c72k-f6bb) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/c72k-f6bb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/c72k-f6bb/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | c72k-f6bb |
| Name | Water And Electric Res 2005-2013 By Zip |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Created | 2014-05-30T19:54:54Z |
| Publication Date | 2015-12-04T21:27:45Z |

## Description

Combined Data of Electric and Water Use (water is HCF and Power kWh).

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| No       |                | text_date  | Text Date  | text      | text        |
| No       |                | value_date | Value Date | text      | text        |
| Yes      | series tag     | zip_code   | Zip Code   | text      | text        |
| Yes      | numeric metric | water_use  | Water Use  | number    | number      |
| Yes      | numeric metric | power_use  | Power Use  | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = text_date,value_date
```

## Data Commands

```ls
series e:c72k-f6bb d:2005-01-01T00:00:00.000Z t:zip_code=90001 m:water_use=21.52 m:power_use=329

series e:c72k-f6bb d:2005-01-01T00:00:00.000Z t:zip_code=90001 m:water_use=22.42 m:power_use=340

series e:c72k-f6bb d:2005-01-01T00:00:00.000Z t:zip_code=90001 m:water_use=21.66 m:power_use=312
```

## Meta Commands

```ls
metric m:water_use p:float l:"Water Use" t:dataTypeName=number

metric m:power_use p:integer l:"Power Use" t:dataTypeName=number

entity e:c72k-f6bb l:"Water And Electric Res 2005-2013 By Zip" t:attribution=LADWP t:url=https://data.lacity.org/api/views/c72k-f6bb

property e:c72k-f6bb t:meta.view v:id=c72k-f6bb v:category="A Livable and Sustainable City" v:averageRating=0 v:name="Water And Electric Res 2005-2013 By Zip" v:attribution=LADWP

property e:c72k-f6bb t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:c72k-f6bb t:meta.view.owner v:id=7q7s-tyf3 v:screenName="Steve Baule" v:displayName="Steve Baule"

property e:c72k-f6bb t:meta.view.tableauthor v:id=7q7s-tyf3 v:screenName="Steve Baule" v:roleName=publisher v:displayName="Steve Baule"
```

## Top Records

```ls
| text_date | value_date | zip_code | water_use | power_use | 
| ========= | ========== | ======== | ========= | ========= | 
| Jul_2005  | Jul-05     | 90001    | 21.52     | 329       | 
| Aug_2005  | Aug-05     | 90001    | 22.42     | 340       | 
| Sep_2005  | Sep-05     | 90001    | 21.66     | 312       | 
| Oct_2005  | Oct-05     | 90001    | 19.63     | 316       | 
| Nov_2005  | Nov-05     | 90001    | 18.03     | 343       | 
| Dec_2005  | Dec-05     | 90001    | 18.70     | 367       | 
| Jan_2006  | Jan-06     | 90001    | 19.61     | 362       | 
| Feb_2006  | Feb-06     | 90001    | 17.17     | 325       | 
| Mar_2006  | Mar-06     | 90001    | 18.82     | 344       | 
| Apr_2006  | Apr-06     | 90001    | 18.25     | 322       | 
```