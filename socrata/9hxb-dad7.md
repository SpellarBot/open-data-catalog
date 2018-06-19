# DWP - Power Sourced From Coal Chart

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dwp-power-sourced-from-coal-chart-c278f) |
| Metadata | [Link](https://data.lacity.org/api/views/9hxb-dad7) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/9hxb-dad7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/9hxb-dad7/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 9hxb-dad7 |
| Name | DWP - Power Sourced From Coal Chart |
| Tags | dwp, coal, power, energy, renewable |
| Created | 2014-05-30T22:12:25Z |
| Publication Date | 2014-05-30T22:13:33Z |

## Description

In March 2013, the LADWP Board approved a contract that will enable LADWP to completely transition out of coal power. Through these actions, the City of Los Angeles became the first major city in the United States to commit to becoming coal free. More information: https://www.ladwp.com/ladwp/faces/ladwp/aboutus/a-power/a-p-renewableenergy?_adf.ctrl-state=1cnzdaglow_191&_afrLoop=46545720898498

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type     | Render Type   |
| ======== | ============== | ============================== | ================================ | ============= | ============= |
| No       |                | date_name                      | Date Name                        | text          | text          |
| Yes      | time           | date_value                     | Date Value                       | calendar_date | calendar_date |
| Yes      | numeric metric | of_dwp_power_sourced_from_coal | % of DWP power sourced from Coal | percent       | percent       |
```

## Time Field

```ls
Value = date_value
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:9hxb-dad7 d:2008-12-31T00:00:00.000Z m:of_dwp_power_sourced_from_coal=43

series e:9hxb-dad7 d:2009-12-31T00:00:00.000Z m:of_dwp_power_sourced_from_coal=41

series e:9hxb-dad7 d:2010-12-31T00:00:00.000Z m:of_dwp_power_sourced_from_coal=39
```

## Meta Commands

```ls
metric m:of_dwp_power_sourced_from_coal p:integer l:"% of DWP power sourced from Coal" t:dataTypeName=percent

entity e:9hxb-dad7 l:"DWP - Power Sourced From Coal Chart" t:url=https://data.lacity.org/api/views/9hxb-dad7

property e:9hxb-dad7 t:meta.view v:id=9hxb-dad7 v:averageRating=0 v:name="DWP - Power Sourced From Coal Chart"

property e:9hxb-dad7 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:9hxb-dad7 t:meta.view.owner v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:displayName="LA DWP OpenData"

property e:9hxb-dad7 t:meta.view.tableauthor v:id=hb8e-gdsp v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:screenName="LA DWP OpenData" v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:roleName=publisher v:displayName="LA DWP OpenData"
```

## Top Records

```ls
| date_name | date_value          | of_dwp_power_sourced_from_coal | 
| ========= | =================== | ============================== | 
| 2008      | 2008-12-31T00:00:00 | 43                             | 
| 2009      | 2009-12-31T00:00:00 | 41                             | 
| 2010      | 2010-12-31T00:00:00 | 39                             | 
| 2011      | 2011-12-31T00:00:00 | 41                             | 
| 2012      | 2012-12-31T00:00:00 | 33                             | 
```