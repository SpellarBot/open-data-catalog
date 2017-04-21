# WTI Barrel of Oil Future Prices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wti-barrel-of-oil-future-prices-3fbfd) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jzyk-q3tp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jzyk-q3tp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jzyk-q3tp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jzyk-q3tp |
| Name | WTI Barrel of Oil Future Prices |
| Attribution | http://hawaii.gov/dbedt |
| Category | Economic Development |
| Tags | seo |
| Created | 2012-07-11T20:33:39Z |
| Publication Date | 2012-07-11T20:51:25Z |

## Description

Daily WTI Contract 1 Future Prices

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | time           | dateofprice  | DateOfPrice  | calendar_date | calendar_date |
| Yes      | series tag     | fuel         | Fuel         | text          | text          |
| Yes      | numeric metric | price        | Price        | number        | number        |
| Yes      | series tag     | physicalunit | PhysicalUnit | text          | text          |
```

## Time Field

```ls
Value = dateofprice
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jzyk-q3tp d:2006-01-03T00:00:00.000Z t:fuel="WTI Future Contract 1" t:physicalunit=$/BBL m:price=63.14

series e:jzyk-q3tp d:2006-01-04T00:00:00.000Z t:fuel="WTI Future Contract 1" t:physicalunit=$/BBL m:price=63.42

series e:jzyk-q3tp d:2006-01-05T00:00:00.000Z t:fuel="WTI Future Contract 1" t:physicalunit=$/BBL m:price=62.79
```

## Meta Commands

```ls
metric m:price p:float l:Price t:dataTypeName=number

entity e:jzyk-q3tp l:"WTI Barrel of Oil Future Prices" t:attribution=http://hawaii.gov/dbedt t:url=https://data.hawaii.gov/api/views/jzyk-q3tp

property e:jzyk-q3tp t:meta.view v:id=jzyk-q3tp v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="WTI Barrel of Oil Future Prices" v:attribution=http://hawaii.gov/dbedt

property e:jzyk-q3tp t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:jzyk-q3tp t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:jzyk-q3tp t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| dateofprice         | fuel                  | price | physicalunit | 
| =================== | ===================== | ===== | ============ | 
| 2006-01-03T00:00:00 | WTI Future Contract 1 | 63.14 | $/BBL        | 
| 2006-01-04T00:00:00 | WTI Future Contract 1 | 63.42 | $/BBL        | 
| 2006-01-05T00:00:00 | WTI Future Contract 1 | 62.79 | $/BBL        | 
| 2006-01-06T00:00:00 | WTI Future Contract 1 | 64.21 | $/BBL        | 
| 2006-01-09T00:00:00 | WTI Future Contract 1 | 63.50 | $/BBL        | 
| 2006-01-10T00:00:00 | WTI Future Contract 1 | 63.37 | $/BBL        | 
| 2006-01-11T00:00:00 | WTI Future Contract 1 | 63.94 | $/BBL        | 
| 2006-01-12T00:00:00 | WTI Future Contract 1 | 63.94 | $/BBL        | 
| 2006-01-13T00:00:00 | WTI Future Contract 1 | 63.92 | $/BBL        | 
| 2006-01-17T00:00:00 | WTI Future Contract 1 | 66.31 | $/BBL        | 
```