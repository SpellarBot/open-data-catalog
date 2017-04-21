# Table 2: Ambient Levels of Airborne Particulates (PM) in Honolulu

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-2-ambient-levels-of-airborne-particulates-pm-in-honolulu-7c51c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fn9b-s9c4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fn9b-s9c4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fn9b-s9c4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fn9b-s9c4 |
| Name | Table 2: Ambient Levels of Airborne Particulates (PM) in Honolulu |
| Attribution | DOH |
| Category | Health |
| Tags | ambient, levels, airborne, particulates |
| Created | 2012-07-31T23:20:29Z |
| Publication Date | 2012-07-31T23:22:24Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | year                    | Year                    | number    | text        |
| Yes      | numeric metric | honolulu_annual_average | Honolulu Annual Average | number    | number      |
| Yes      | numeric metric | national_standard       | National Standard       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fn9b-s9c4 d:2005-01-01T00:00:00.000Z m:honolulu_annual_average=4 m:national_standard=15

series e:fn9b-s9c4 d:2006-01-01T00:00:00.000Z m:honolulu_annual_average=3 m:national_standard=15

series e:fn9b-s9c4 d:2007-01-01T00:00:00.000Z m:honolulu_annual_average=3.9 m:national_standard=15
```

## Meta Commands

```ls
metric m:honolulu_annual_average p:float l:"Honolulu Annual Average" t:dataTypeName=number

metric m:national_standard p:integer l:"National Standard" t:dataTypeName=number

entity e:fn9b-s9c4 l:"Table 2: Ambient Levels of Airborne Particulates (PM) in Honolulu" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/fn9b-s9c4

property e:fn9b-s9c4 t:meta.view v:id=fn9b-s9c4 v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 2: Ambient Levels of Airborne Particulates (PM) in Honolulu" v:attribution=DOH

property e:fn9b-s9c4 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:fn9b-s9c4 t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:fn9b-s9c4 t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| year | honolulu_annual_average | national_standard | 
| ==== | ======================= | ================= | 
| 2005 | 4.0                     | 15                | 
| 2006 | 3.0                     | 15                | 
| 2007 | 3.9                     | 15                | 
| 2008 | 4.7                     | 15                | 
| 2009 | 4.8                     | 15                | 
| 2010 | 4.8                     | 15                | 
| 2011 | 4.8                     | 15                | 
```