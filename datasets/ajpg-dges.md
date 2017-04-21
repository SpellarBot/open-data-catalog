# King County Health Reform Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-health-reform-indicators-9eaac) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ajpg-dges) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ajpg-dges/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ajpg-dges/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ajpg-dges |
| Name | King County Health Reform Indicators |
| Attribution | Public Health - Seattle & King County |
| Category | Health |
| Tags | health, community health, health reform, aca, zip, hra |
| Created | 2014-03-06T23:17:51Z |
| Publication Date | 2014-12-17T00:09:12Z |

## Description

Health reporting area (HRA) and zip code-level indicators for monitoring the impact of the Affordable Care Act in King County, WA. Topic areas range from access to care to population health. Imported to Socrata to allow data to be pulled as JSON from SODA to feed into Leaflet.js-based maps on an external site.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | geo         | geo         | text      | text        |
| Yes      | numeric metric | vid         | vid         | number    | number      |
| Yes      | numeric metric | estimate    | estimate    | number    | number      |
| Yes      | numeric metric | estlb       | estlb       | number    | number      |
| Yes      | numeric metric | estub       | estub       | number    | number      |
| Yes      | numeric metric | estse       | estse       | number    | number      |
| Yes      | numeric metric | estrse      | estrse      | number    | number      |
| Yes      | numeric metric | pop         | pop         | number    | number      |
| Yes      | numeric metric | number      | number      | number    | number      |
| Yes      | numeric metric | numlb       | numlb       | number    | number      |
| Yes      | numeric metric | numub       | numub       | number    | number      |
| Yes      | numeric metric | numerator   | numerator   | number    | number      |
| Yes      | numeric metric | denominator | denominator | number    | number      |
| Yes      | series tag     | indicator   | indicator   | text      | text        |
| Yes      | time           | year        | year        | number    | text        |
| Yes      | series tag     | datatype    | datatype    | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ajpg-dges d:2012-01-01T00:00:00.000Z t:indicator=medcost t:geo=Auburn-North t:datatype=survey m:estlb=8 m:estrse=25.958491 m:estse=3.72228446 m:numlb=3200 m:estub=23 m:numerator=28 m:number=5500 m:pop=38061 m:denominator=295 m:numub=8900 m:estimate=14 m:vid=1000

series e:ajpg-dges d:2012-01-01T00:00:00.000Z t:indicator=medcost t:geo=Auburn-South t:datatype=survey m:estlb=13 m:estrse=25.215083 m:estse=5.36896827 m:numlb=3200 m:estub=34 m:numerator=29 m:number=5400 m:pop=25274 m:denominator=180 m:numub=8500 m:estimate=21 m:vid=1100

series e:ajpg-dges d:2012-01-01T00:00:00.000Z t:indicator=medcost t:geo=Ballard t:datatype=survey m:estlb=5 m:estrse=28.332279999999997 m:estse=2.47033825 m:numlb=2500 m:estub=15 m:numerator=40 m:number=4500 m:pop=51489 m:denominator=570 m:numub=7700 m:estimate=9 m:vid=2000
```

## Meta Commands

```ls
metric m:vid p:integer l:vid t:dataTypeName=number

metric m:estimate p:double l:estimate t:dataTypeName=number

metric m:estlb p:double l:estlb t:dataTypeName=number

metric m:estub p:float l:estub t:dataTypeName=number

metric m:estse p:float l:estse t:dataTypeName=number

metric m:estrse p:double l:estrse t:dataTypeName=number

metric m:pop p:integer l:pop t:dataTypeName=number

metric m:number p:integer l:number t:dataTypeName=number

metric m:numlb p:integer l:numlb t:dataTypeName=number

metric m:numub p:integer l:numub t:dataTypeName=number

metric m:numerator p:integer l:numerator t:dataTypeName=number

metric m:denominator p:integer l:denominator t:dataTypeName=number

entity e:ajpg-dges l:"King County Health Reform Indicators" t:attribution="Public Health - Seattle & King County" t:url=https://data.kingcounty.gov/api/views/ajpg-dges

property e:ajpg-dges t:meta.view v:id=ajpg-dges v:category=Health v:averageRating=0 v:name="King County Health Reform Indicators" v:attribution="Public Health - Seattle & King County"

property e:ajpg-dges t:meta.view.owner v:id=byna-c6yy v:profileImageUrlMedium=/api/users/byna-c6yy/profile_images/THUMB v:profileImageUrlLarge=/api/users/byna-c6yy/profile_images/LARGE v:screenName="Eli Kern" v:profileImageUrlSmall=/api/users/byna-c6yy/profile_images/TINY v:displayName="Eli Kern"

property e:ajpg-dges t:meta.view.tableauthor v:id=byna-c6yy v:profileImageUrlMedium=/api/users/byna-c6yy/profile_images/THUMB v:profileImageUrlLarge=/api/users/byna-c6yy/profile_images/LARGE v:screenName="Eli Kern" v:profileImageUrlSmall=/api/users/byna-c6yy/profile_images/TINY v:roleName=publisher v:displayName="Eli Kern"
```

## Top Records

```ls
| geo                              | vid  | estimate | estlb | estub | estse              | estrse             | pop   | number | numlb | numub | numerator | denominator | indicator | year | datatype | 
| ================================ | ==== | ======== | ===== | ===== | ================== | ================== | ===== | ====== | ===== | ===== | ========= | =========== | ========= | ==== | ======== | 
| Auburn-North                     | 1000 | 14       | 8     | 23    | 3.72228446         | 25.958490999999999 | 38061 | 5500   | 3200  | 8900  | 28        | 295         | medcost   | 2012 | survey   | 
| Auburn-South                     | 1100 | 21       | 13    | 34    | 5.3689682699999999 | 25.215083          | 25274 | 5400   | 3200  | 8500  | 29        | 180         | medcost   | 2012 | survey   | 
| Ballard                          | 2000 | 9        | 5     | 15    | 2.4703382500000002 | 28.332279999999997 | 51489 | 4500   | 2500  | 7700  | 40        | 570         | medcost   | 2012 | survey   | 
| Beacon/Gtown/S.Park              | 2100 | 15       | 9     | 24    | 3.8497745700000001 | 25.419076          | 39649 | 6000   | 3600  | 9600  | 31        | 288         | medcost   | 2012 | survey   | 
| Bear Creek/Carnation/Duvall      | 3000 | 9        | 5     | 14    | 2.1762330799999998 | 25.306381000000002 | 64508 | 5500   | 3300  | 9000  | 34        | 556         | medcost   | 2012 | survey   | 
| Bellevue-Central                 | 4000 | 15       | 9     | 23    | 3.4999492800000001 | 23.278199000000001 | 35568 | 5300   | 3300  | 8300  | 26        | 301         | medcost   | 2012 | survey   | 
| Bellevue-NE                      | 4100 | 9        | 5     | 17    | 2.8912345699999999 | 31.977533000000001 | 34899 | 3200   | 1700  | 5800  | 23        | 328         | medcost   | 2012 | survey   | 
| Bellevue-South                   | 4200 | 6        | 3     | 10    | 1.6804557499999999 | 28.146023999999997 | 31530 | 1900   | 1100  | 3200  | 18        | 280         | medcost   | 2012 | survey   | 
| Bellevue-West                    | 4300 | 9        | 5     | 14    | 2.2990006599999999 | 26.493882000000003 | 28371 | 2500   | 1400  | 4100  | 18        | 277         | medcost   | 2012 | survey   | 
| Black Diamond/Enumclaw/SE County | 5000 | 10       | 7     | 14    | 1.8968626900000001 | 19.106572999999997 | 45386 | 4500   | 3100  | 6500  | 38        | 420         | medcost   | 2012 | survey   | 
```