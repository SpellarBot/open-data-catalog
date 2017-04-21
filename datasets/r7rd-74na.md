# Table 1.09 DE FACTO POPULATION, BY COUNTY 1990 TO 2014 (as of July 1)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-1-09-de-facto-population-by-county-1990-to-2013-as-of-july-1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/r7rd-74na) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/r7rd-74na/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/r7rd-74na/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | r7rd-74na |
| Name | Table 1.09 DE FACTO POPULATION, BY COUNTY 1990 TO 2014 (as of July 1) |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | population |
| Created | 2012-08-27T20:01:04Z |
| Publication Date | 2015-10-27T00:28:24Z |

## Description

* Includes all persons physically present in an area, regardless of military status or usual place of residence.  					
* Includes visitors present but excludes residents temporarily absent, both calculated as an average daily census.					
* Maui County includes Kalawao County.  The 2014 de facto population of Kalawao County, which is the Kalaupapa Settlement on Molokai, was 89. 					
     Source:  DBEDT calculations based on Hawaii tourism data and population data by the U.S. Census Bureau					
Please go to the DBEDT Databook site, http://hawaii.gov/dbedt/info/economic/databook,  for the complete data source.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | year                        | Year                        | number    | text        |
| Yes      | numeric metric | state_total                 | State total                 | number    | number      |
| Yes      | numeric metric | city_and_county_of_honolulu | City and County of Honolulu | number    | number      |
| Yes      | numeric metric | hawaii_county               | Hawaii County               | number    | number      |
| Yes      | numeric metric | kauai_county                | Kauai County                | number    | number      |
| Yes      | numeric metric | maui_county                 | Maui County                 | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:r7rd-74na d:1990-01-01T00:00:00.000Z m:state_total=1257319 m:hawaii_county=137103 m:city_and_county_of_honolulu=913268 m:maui_county=138390 m:kauai_county=68558

series e:r7rd-74na d:1991-01-01T00:00:00.000Z m:state_total=1252265 m:hawaii_county=141240 m:city_and_county_of_honolulu=901717 m:maui_county=139703 m:kauai_county=69605

series e:r7rd-74na d:1992-01-01T00:00:00.000Z m:state_total=1271662 m:hawaii_county=146421 m:city_and_county_of_honolulu=912514 m:maui_county=146651 m:kauai_county=66076
```

## Meta Commands

```ls
metric m:state_total p:integer l:"State total" t:dataTypeName=number

metric m:city_and_county_of_honolulu p:integer l:"City and County of Honolulu" t:dataTypeName=number

metric m:hawaii_county p:integer l:"Hawaii County" t:dataTypeName=number

metric m:kauai_county p:integer l:"Kauai County" t:dataTypeName=number

metric m:maui_county p:integer l:"Maui County" t:dataTypeName=number

entity e:r7rd-74na l:"Table 1.09 DE FACTO POPULATION, BY COUNTY  1990 TO 2014 (as of July 1)" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/r7rd-74na

property e:r7rd-74na t:meta.view v:id=r7rd-74na v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/databook v:averageRating=0 v:name="Table 1.09 DE FACTO POPULATION, BY COUNTY  1990 TO 2014 (as of July 1)" v:attribution="Department of Economic Development and Tourism"

property e:r7rd-74na t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:r7rd-74na t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:r7rd-74na t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | state_total | city_and_county_of_honolulu | hawaii_county | kauai_county | maui_county | 
| ==== | =========== | =========================== | ============= | ============ | =========== | 
| 1990 | 1257319     | 913268                      | 137103        | 68558        | 138390      | 
| 1991 | 1252265     | 901717                      | 141240        | 69605        | 139703      | 
| 1992 | 1271662     | 912514                      | 146421        | 66076        | 146651      | 
| 1993 | 1267849     | 909506                      | 148014        | 61262        | 149067      | 
| 1994 | 1289804     | 919898                      | 150311        | 67161        | 152434      | 
| 1995 | 1298096     | 921626                      | 152482        | 68844        | 155144      | 
| 1996 | 1303915     | 921609                      | 154364        | 70474        | 157468      | 
| 1997 | 1327930     | 932931                      | 161225        | 71763        | 162011      | 
| 1998 | 1334125     | 931439                      | 165205        | 73920        | 163562      | 
| 1999 | 1332442     | 927689                      | 164570        | 74441        | 165743      | 
```