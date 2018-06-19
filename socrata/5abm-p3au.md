# Table 5: Ambient Levels of Carbon Monoxide (CO) in Honolulu

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-5-ambient-levels-of-carbon-monoxide-co-in-honolulu-c44bb) |
| Metadata | [Link](https://data.hawaii.gov/api/views/5abm-p3au) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/5abm-p3au/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/5abm-p3au/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 5abm-p3au |
| Name | Table 5: Ambient Levels of Carbon Monoxide (CO) in Honolulu |
| Attribution | DOH |
| Category | Health |
| Tags | levels, carbon, monoxide |
| Created | 2012-07-31T23:29:08Z |
| Publication Date | 2012-07-31T23:30:23Z |

## Description

DOH Environmental Indicators

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                         | Data Type | Render Type |
| ======== | ============== | ========================== | ============================ | ========= | =========== |
| Yes      | time           | year                       | Year                         | number    | text        |
| Yes      | numeric metric | highest_1_hour_average_ppm | Highest 1-hour Average (ppm) | number    | number      |
| Yes      | numeric metric | national_standard_ppm      | National Standard (ppm)      | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5abm-p3au d:2005-01-01T00:00:00.000Z m:highest_1_hour_average_ppm=3.4 m:national_standard_ppm=35

series e:5abm-p3au d:2006-01-01T00:00:00.000Z m:highest_1_hour_average_ppm=2.5 m:national_standard_ppm=35

series e:5abm-p3au d:2007-01-01T00:00:00.000Z m:highest_1_hour_average_ppm=2 m:national_standard_ppm=35
```

## Meta Commands

```ls
metric m:highest_1_hour_average_ppm p:float l:"Highest 1-hour Average (ppm)" t:dataTypeName=number

metric m:national_standard_ppm p:integer l:"National Standard (ppm)" t:dataTypeName=number

entity e:5abm-p3au l:"Table 5: Ambient Levels of Carbon Monoxide (CO) in Honolulu" t:attribution=DOH t:url=https://data.hawaii.gov/api/views/5abm-p3au

property e:5abm-p3au t:meta.view v:id=5abm-p3au v:category=Health v:attributionLink=http://hawaii.gov/doh v:averageRating=0 v:name="Table 5: Ambient Levels of Carbon Monoxide (CO) in Honolulu" v:attribution=DOH

property e:5abm-p3au t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:5abm-p3au t:meta.view.owner v:id=8c9u-vteh v:screenName=lorrink v:displayName=lorrink

property e:5abm-p3au t:meta.view.tableauthor v:id=8c9u-vteh v:screenName=lorrink v:roleName=editor v:displayName=lorrink
```

## Top Records

```ls
| year | highest_1_hour_average_ppm | national_standard_ppm | 
| ==== | ========================== | ===================== | 
| 2005 | 3.4                        | 35                    | 
| 2006 | 2.5                        | 35                    | 
| 2007 | 2                          | 35                    | 
| 2008 | 2.1                        | 35                    | 
| 2009 | 1.6                        | 35                    | 
| 2010 | 1.6                        | 35                    | 
| 2011 | 1.6                        | 35                    | 
```