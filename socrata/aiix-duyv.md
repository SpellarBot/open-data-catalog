# Port of Los Angeles - Emissions Reduction Percentage 2005 - 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pola-emissions-reduction-percentage-e7b51) |
| Metadata | [Link](https://data.lacity.org/api/views/aiix-duyv) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/aiix-duyv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/aiix-duyv/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | aiix-duyv |
| Name | Port of Los Angeles - Emissions Reduction Percentage 2005 - 2012 |
| Attribution | Port of Los Angeles |
| Created | 2014-05-30T22:22:53Z |
| Publication Date | 2014-05-30T22:24:09Z |

## Description

This table reports emissions from Port operations in oxides of nitrogen (NOx), Oxides of Sulfur (SOx), and Diesel Particulate Matter (DPM); emissions impact health and quality of life in the Port-adjacent communities. Source: POLA Annual emissions inventory (for Port reductions)
Published historical data.  Live data is published online via: https://caap.airsis.com/HistoricalDetail.aspx

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type | Render Type |
| ======== | ============== | ===================== | ======================= | ========= | =========== |
| No       |                | date_name             | Date Name               | text      | text        |
| Yes      | numeric metric | nox_change_since_2005 | NOx % Change since 2005 | percent   | percent     |
| Yes      | numeric metric | sox_change_since_2005 | SOx % Change since 2005 | percent   | percent     |
| Yes      | numeric metric | dpm_change_since_2005 | DPM % Change since 2005 | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:aiix-duyv d:2005-01-01T00:00:00.000Z m:nox_change_since_2005=13.2 m:sox_change_since_2005=7.6 m:dpm_change_since_2005=6.3

series e:aiix-duyv d:2005-01-01T00:00:00.000Z m:nox_change_since_2005=0.3 m:sox_change_since_2005=-36.2 m:dpm_change_since_2005=-29.6

series e:aiix-duyv d:2005-01-01T00:00:00.000Z m:nox_change_since_2005=-8 m:sox_change_since_2005=-28.4 m:dpm_change_since_2005=-22.1
```

## Meta Commands

```ls
metric m:nox_change_since_2005 p:float l:"NOx % Change since 2005" t:dataTypeName=percent

metric m:sox_change_since_2005 p:float l:"SOx % Change since 2005" t:dataTypeName=percent

metric m:dpm_change_since_2005 p:float l:"DPM % Change since 2005" t:dataTypeName=percent

entity e:aiix-duyv l:"Port of Los Angeles - Emissions Reduction Percentage 2005 - 2012" t:attribution="Port of Los Angeles" t:url=https://data.lacity.org/api/views/aiix-duyv

property e:aiix-duyv t:meta.view v:id=aiix-duyv v:attributionLink=https://caap.airsis.com/HistoricalDetail.aspx v:averageRating=0 v:name="Port of Los Angeles - Emissions Reduction Percentage 2005 - 2012" v:attribution="Port of Los Angeles"

property e:aiix-duyv t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:aiix-duyv t:meta.view.owner v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:displayName="Port of Los Angeles"

property e:aiix-duyv t:meta.view.tableauthor v:id=2ib6-ssvz v:profileImageUrlMedium=/api/users/2ib6-ssvz/profile_images/THUMB v:profileImageUrlLarge=/api/users/2ib6-ssvz/profile_images/LARGE v:screenName="Port of Los Angeles" v:profileImageUrlSmall=/api/users/2ib6-ssvz/profile_images/TINY v:roleName=publisher v:displayName="Port of Los Angeles"
```

## Top Records

```ls
| date_name | nox_change_since_2005 | sox_change_since_2005 | dpm_change_since_2005 | 
| ========= | ===================== | ===================== | ===================== | 
| 2005      |                       |                       |                       | 
| 2006      | 13.2                  | 7.6                   | 6.3                   | 
| 2007      | 0.3                   | -36.2                 | -29.6                 | 
| 2008      | -8                    | -28.4                 | -22.1                 | 
| 2009      | -33.7                 | -54.1                 | -49.7                 | 
| 2010      | -50.2                 | -75.1                 | -68.9                 | 
| 2011      | -51.6                 | -75.7                 | -70.9                 | 
| 2012      | -56.1                 | -88.1                 | -79.2                 | 
```