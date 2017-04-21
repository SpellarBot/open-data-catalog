# Oregon Populated Places

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-populated-places-5b4c5) |
| Metadata | [Link](https://data.oregon.gov/api/views/c6z4-hjsu) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/c6z4-hjsu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/c6z4-hjsu/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | c6z4-hjsu |
| Name | Oregon Populated Places |
| Attribution | USGS, Geographic Names Information System (GNIS) |
| Tags | oregon, places, populated, locations, towns, cities, villages |
| Created | 2010-11-12T22:13:22Z |
| Publication Date | 2013-03-01T18:12:24Z |

## Description

This point theme shows the location of populated places in the state of Oregon as derived from the 1:24,000 GNIS theme. 

    This dataset was created from the USGS GNIS database. Several SSCGIS staff members have worked on this theme over the years. 

Procedures_Used: The orppl theme was delineted from the 1990 GNIS theme. To get an idea how this coverage was created download the GNIS metadata. The orppl point theme was generated as the orcov theme. It was built for point topology after the theme was generated. it was than copied to oregnis. Arcedit was used to populate the coverage by selecting ppl from the desig item. The theme was again built for point topology. the theme was imported in 1991 and copied to the gniscov name. External was used 5 times to populate the database. the theme was then exported as gniscov. The gniscov was edited and built for point topology. Reselect was used twice. ArcEdit was used 6 times to edit the theme and than renamed to orppl. The theme was than built for point topology. The theme was than copied twice. One of these copies ws overlayed with house90 using the identity using the point .1 fuzzy tolerance and join options to join the two themes together. The theme was than copied to another directory. In the new directory the theme was edited 7 times and build for point topology. The theme was than renamed orppl and copied two more times. The theme was exported twice and built once between 1993 and 1995. The Projectcopy command was used to copy the projection info from the citylimits theme to the orppl. The theme was than exported twice and imported back in to be projected into the Oregon State transfer standard. The theme was built for point topology and imported back in so that metadata could be created for it.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name          | Data Type | Render Type |
| ======== | ============== | =========== | ============= | ========= | =========== |
| No       | time           | :updated_at | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | name        | NAME          | text      | text        |
| Yes      | series tag     | county      | COUNTY        | text      | text        |
| Yes      | series tag     | mapname     | USGS Map Name | text      | text        |
| Yes      | numeric metric | house       | HOUSE         | number    | number      |
| Yes      | numeric metric | senate      | SENATE        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:c6z4-hjsu d:2010-11-12T14:19:27.000Z t:mapname=Knappa t:county=Clatsop t:name=Brownsmead m:house=1 m:senate=1

series e:c6z4-hjsu d:2010-11-12T14:19:27.000Z t:mapname=Warrenton t:county=Clatsop t:name="Fort Stevens" m:house=2 m:senate=1

series e:c6z4-hjsu d:2010-11-12T14:19:27.000Z t:mapname=Cathlamet t:county=Clatsop t:name=Clifton m:house=1 m:senate=1
```

## Meta Commands

```ls
metric m:house p:float l:HOUSE t:dataTypeName=number

metric m:senate p:float l:SENATE t:dataTypeName=number

entity e:c6z4-hjsu l:"Oregon Populated Places" t:attribution="USGS, Geographic Names Information System (GNIS)" t:url=https://data.oregon.gov/api/views/c6z4-hjsu

property e:c6z4-hjsu t:meta.view v:id=c6z4-hjsu v:attributionLink=http://gis.oregon.gov/DAS/EISPD/GEO/sdlibrary.shtml v:averageRating=0 v:name="Oregon Populated Places" v:attribution="USGS, Geographic Names Information System (GNIS)"

property e:c6z4-hjsu t:meta.view.owner v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"

property e:c6z4-hjsu t:meta.view.tableauthor v:id=n7yg-3wp3 v:profileImageUrlMedium=/api/users/n7yg-3wp3/profile_images/THUMB v:profileImageUrlLarge=/api/users/n7yg-3wp3/profile_images/LARGE v:screenName="Erik Endrulat" v:profileImageUrlSmall=/api/users/n7yg-3wp3/profile_images/TINY v:displayName="Erik Endrulat"
```

## Top Records

```ls
| :updated_at | name                    | county  | mapname   | house | senate | 
| =========== | ======================= | ======= | ========= | ===== | ====== | 
| 1289571567  | Brownsmead              | Clatsop | Knappa    | 1.0   | 1.0    | 
| 1289571567  | Fort Stevens            | Clatsop | Warrenton | 2.0   | 1.0    | 
| 1289571567  | Clifton                 | Clatsop | Cathlamet | 1.0   | 1.0    | 
| 1289571567  | Tongue Point Village    | Clatsop | Astoria   | 1.0   | 1.0    | 
| 1289571567  | Tongue Point Naval Base | Clatsop | Astoria   | 1.0   | 1.0    | 
| 1289571567  | Navy Heights            | Clatsop | Astoria   | 1.0   | 1.0    | 
| 1289571567  | Astoria                 | Clatsop | Astoria   | 1.0   | 1.0    | 
| 1289571567  | Bradwood                | Clatsop | Cathlamet | 1.0   | 1.0    | 
| 1289571567  | Knappa                  | Clatsop | Knappa    | 1.0   | 1.0    | 
| 1289571567  | Warrenton               | Clatsop | Warrenton | 2.0   | 1.0    | 
```