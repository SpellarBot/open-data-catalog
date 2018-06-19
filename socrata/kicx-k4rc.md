# Violent Crimes by County: 2006 to 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/violent-crimes-by-county-2006-to-2013-00616) |
| Metadata | [Link](https://data.maryland.gov/api/views/kicx-k4rc) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/kicx-k4rc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/kicx-k4rc/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | kicx-k4rc |
| Name | Violent Crimes by County: 2006 to 2013 |
| Attribution | Maryland Statistical Analysis Center |
| Category | Public Safety |
| Tags | crime, violent crime, public safety, homicide, murder, rape, assault, aggravated assault, robbery, security |
| Created | 2014-09-25T15:42:21Z |
| Publication Date | 2014-10-10T15:38:46Z |

## Description

This dataset shows the total number of violent crimes by county and statewide, for CY2006 versus CY2013. Data are provided by the Maryland Statistical Analysis Center (MSAC) within the Governor's Office of Crime Control and Prevention (GOCCP).

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | county                    | County                    | text      | text        |
| Yes      | numeric metric | 2006_total_violent_crimes | 2006 Total Violent Crimes | number    | number      |
| Yes      | numeric metric | 2007_total_violent_crimes | 2007 Total Violent Crimes | number    | number      |
| Yes      | numeric metric | 2008_total_violent_crimes | 2008 Total Violent Crimes | number    | number      |
| Yes      | numeric metric | 2009_total_violent_crimes | 2009 Total Violent Crimes | number    | number      |
| Yes      | numeric metric | 2010_total_violent_crimes | 2010 Total Violent Crimes | number    | number      |
| Yes      | numeric metric | 2011_total_violent_crimes | 2011 Total Violent Crimes | number    | number      |
| Yes      | numeric metric | 2012_total_violent_crimes | 2012 Total Violent Crimes | number    | number      |
| Yes      | numeric metric | 2013_total_violent_crimes | 2013 Total Violent Crimes | number    | number      |
| Yes      | numeric metric | change_2006_to_2013       | Change: 2006 to 2013      | percent   | percent     |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kicx-k4rc d:2006-01-01T00:00:00.000Z t:county="ANNE ARUNDEL" m:2009_total_violent_crimes=2920 m:2010_total_violent_crimes=2929 m:2007_total_violent_crimes=3068 m:2006_total_violent_crimes=3167 m:change_2006_to_2013=-27 m:2011_total_violent_crimes=2675 m:2008_total_violent_crimes=2931 m:2012_total_violent_crimes=2281 m:2013_total_violent_crimes=2319

series e:kicx-k4rc d:2006-01-01T00:00:00.000Z t:county="BALTIMORE CITY" m:2009_total_violent_crimes=9701 m:2010_total_violent_crimes=9352 m:2007_total_violent_crimes=10229 m:2006_total_violent_crimes=10871 m:change_2006_to_2013=-19 m:2011_total_violent_crimes=8928 m:2008_total_violent_crimes=10132 m:2012_total_violent_crimes=8825 m:2013_total_violent_crimes=8757

series e:kicx-k4rc d:2006-01-01T00:00:00.000Z t:county="BALTIMORE COUNTY" m:2009_total_violent_crimes=4555 m:2010_total_violent_crimes=4349 m:2007_total_violent_crimes=5381 m:2006_total_violent_crimes=5713 m:change_2006_to_2013=-26 m:2011_total_violent_crimes=4288 m:2008_total_violent_crimes=4931 m:2012_total_violent_crimes=4181 m:2013_total_violent_crimes=4200
```

## Meta Commands

```ls
metric m:2006_total_violent_crimes p:integer l:"2006 Total Violent Crimes" t:dataTypeName=number

metric m:2007_total_violent_crimes p:integer l:"2007 Total Violent Crimes" t:dataTypeName=number

metric m:2008_total_violent_crimes p:integer l:"2008 Total Violent Crimes" t:dataTypeName=number

metric m:2009_total_violent_crimes p:integer l:"2009 Total Violent Crimes" t:dataTypeName=number

metric m:2010_total_violent_crimes p:integer l:"2010 Total Violent Crimes" t:dataTypeName=number

metric m:2011_total_violent_crimes p:integer l:"2011 Total Violent Crimes" t:dataTypeName=number

metric m:2012_total_violent_crimes p:integer l:"2012 Total Violent Crimes" t:dataTypeName=number

metric m:2013_total_violent_crimes p:integer l:"2013 Total Violent Crimes" t:dataTypeName=number

metric m:change_2006_to_2013 p:integer l:"Change: 2006 to 2013" t:dataTypeName=percent

entity e:kicx-k4rc l:"Violent Crimes by County: 2006 to 2013" t:attribution="Maryland Statistical Analysis Center" t:url=https://data.maryland.gov/api/views/kicx-k4rc

property e:kicx-k4rc t:meta.view v:id=kicx-k4rc v:category="Public Safety" v:attributionLink=http://www.goccp.maryland.gov/msac/crime-statistics.php v:averageRating=0 v:name="Violent Crimes by County: 2006 to 2013" v:attribution="Maryland Statistical Analysis Center"

property e:kicx-k4rc t:meta.view.license v:name="Public Domain"

property e:kicx-k4rc t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:kicx-k4rc t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| county           | 2006_total_violent_crimes | 2007_total_violent_crimes | 2008_total_violent_crimes | 2009_total_violent_crimes | 2010_total_violent_crimes | 2011_total_violent_crimes | 2012_total_violent_crimes | 2013_total_violent_crimes | change_2006_to_2013 | 
| ================ | ========================= | ========================= | ========================= | ========================= | ========================= | ========================= | ========================= | ========================= | =================== | 
| ANNE ARUNDEL     | 3167                      | 3068                      | 2931                      | 2920                      | 2929                      | 2675                      | 2281                      | 2319                      | -27                 | 
| BALTIMORE CITY   | 10871                     | 10229                     | 10132                     | 9701                      | 9352                      | 8928                      | 8825                      | 8757                      | -19                 | 
| BALTIMORE COUNTY | 5713                      | 5381                      | 4931                      | 4555                      | 4349                      | 4288                      | 4181                      | 4200                      | -26                 | 
| CALVERT          | 257                       | 279                       | 367                       | 271                       | 194                       | 142                       | 115                       | 107                       | -58                 | 
| CAROLINE         | 149                       | 123                       | 123                       | 126                       | 128                       | 112                       | 115                       | 94                        | -37                 | 
| CARROLL          | 374                       | 359                       | 360                       | 393                       | 349                       | 256                       | 306                       | 342                       | -9                  | 
| CECIL            | 490                       | 568                       | 540                       | 746                       | 673                       | 579                       | 549                       | 436                       | -11                 | 
| CHARLES          | 729                       | 846                       | 794                       | 701                       | 713                       | 588                       | 575                       | 588                       | -19                 | 
| DORCHESTER       | 181                       | 160                       | 187                       | 183                       | 188                       | 142                       | 165                       | 150                       | -17                 | 
| FREDERICK        | 752                       | 807                       | 793                       | 793                       | 728                       | 593                       | 620                       | 614                       | -18                 | 
```