# Picnic Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/picnic-sites) |
| Metadata | [Link](https://data.seattle.gov/api/views/tik2-ywhq) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/tik2-ywhq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/tik2-ywhq/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | tik2-ywhq |
| Name | Picnic Sites |
| Attribution | Seattle Parks and Recreation |
| Category | Parks and Recreation |
| Tags | picnic, reservation, table, site, reserve |
| Created | 2016-04-19T23:39:24Z |
| Publication Date | 2017-01-23T18:21:32Z |

## Description

Seattle Parks and Recreation Reservable Picnic Sites

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | shelter_name       | Shelter Name       | text      | text        |
| Yes      | numeric metric | fee                | Fee                | money     | money       |
| Yes      | numeric metric | capacity           | Capacity           | number    | number      |
| Yes      | numeric metric | unsheltered_tables | Unsheltered Tables | number    | number      |
| Yes      | numeric metric | sheltered_tables   | Sheltered Tables   | number    | number      |
| Yes      | series tag     | ada                | ADA                | text      | text        |
| Yes      | series tag     | photo_1            | Photo 1            | url       | url         |
| Yes      | series tag     | photo_caption_1    | Photo Caption 1    | text      | text        |
| Yes      | series tag     | photo_2            | Photo 2            | url       | url         |
| Yes      | series tag     | photo_caption_2    | Photo Caption 2    | text      | text        |
| Yes      | series tag     | photo_3            | Photo 3            | url       | url         |
| Yes      | series tag     | photo_caption_3    | Photo Caption 3    | text      | text        |
| Yes      | series tag     | photo_4            | Photo 4            | url       | url         |
| Yes      | series tag     | photo_caption_4    | Photo Caption 4    | text      | text        |
| Yes      | series tag     | map_link           | Map Link           | url       | url         |
| Yes      | series tag     | features           | Features           | html      | html        |
| Yes      | series tag     | park_xid           | Park xID           | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tik2-ywhq d:2016-08-17T14:13:13.000Z t:park_xid=63744 t:photo_caption_1="Beer Sheeva Park tables" t:photo_1=http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/BeerShevaTables1-2.jpg t:map_link=http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/BeerSheva.pdf t:shelter_name="Beer Sheva Park Picnic Area Tables Only" m:fee=0 m:unsheltered_tables=2 m:capacity=30

series e:tik2-ywhq d:2016-08-22T19:32:15.000Z t:park_xid=63777 t:photo_2=http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/MeKwaMooksTables1-2.jpg t:photo_1=http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/MeKwaMooksTables.jpg t:map_link=http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/Me-Kwa-Mooks.pdf t:shelter_name="Me-Kwa-Mooks Park Picnic Area Tables Only" m:fee=0 m:unsheltered_tables=2 m:capacity=30

series e:tik2-ywhq d:2016-09-26T18:37:38.000Z t:park_xid=63685 t:photo_caption_1="Don Armeni Picnic Tables 1 and 2" t:photo_caption_3="Don Aremni Picnic Table 1" t:photo_caption_2="Don Armeni Picnic Tables 1 and 2" t:photo_3=http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/DonArmeniTable1.jpg t:photo_2=http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/DonArmeniTable1and2.jpg t:photo_1=http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/DonArmeniPicnicArea.jpg t:map_link=http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/DonArmeni.pdf t:shelter_name="Don Armeni Boat Ramp Picnic Area Tables Only" m:fee=0 m:unsheltered_tables=2 m:capacity=30
```

## Meta Commands

```ls
metric m:fee p:double l:Fee t:dataTypeName=money

metric m:capacity p:integer l:Capacity t:dataTypeName=number

metric m:unsheltered_tables p:integer l:"Unsheltered Tables" t:dataTypeName=number

metric m:sheltered_tables p:integer l:"Sheltered Tables" t:dataTypeName=number

entity e:tik2-ywhq l:"Picnic Sites" t:attribution="Seattle Parks and Recreation" t:url=https://data.seattle.gov/api/views/tik2-ywhq

property e:tik2-ywhq t:meta.view v:id=tik2-ywhq v:category="Parks and Recreation" v:averageRating=0 v:name="Picnic Sites" v:attribution="Seattle Parks and Recreation"

property e:tik2-ywhq t:meta.view.license v:name="Public Domain"

property e:tik2-ywhq t:meta.view.owner v:id=rtg9-vvu6 v:screenName="Somerfield, Beth" v:displayName="Somerfield, Beth"

property e:tik2-ywhq t:meta.view.tableauthor v:id=rtg9-vvu6 v:screenName="Somerfield, Beth" v:roleName=publisher v:displayName="Somerfield, Beth"
```

## Top Records

```ls
| :updated_at | shelter_name                                       | fee  | capacity | unsheltered_tables | sheltered_tables | ada     | photo_1                                                                                                                                                       | photo_caption_1                                           | photo_2                                                                                                                    | photo_caption_2                                                              | photo_3                                                                                                              | photo_caption_3                                                                                                        | photo_4                                                                                                                | photo_caption_4                                 | map_link                                                                                                 | features                  | park_xid | 
| =========== | ================================================== | ==== | ======== | ================== | ================ | ======= | ============================================================================================================================================================= | ========================================================= | ========================================================================================================================== | ============================================================================ | ==================================================================================================================== | ====================================================================================================================== | ====================================================================================================================== | =============================================== | ======================================================================================================== | ========================= | ======== | 
| 1471443193  | Beer Sheva Park Picnic Area Tables Only            | 0.00 | 30       | 2                  |                  |         | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/BeerShevaTables1-2.jpg, null]                                                    | Beer Sheeva Park tables                                   | [null, null]                                                                                                               |                                                                              | [null, null]                                                                                                         |                                                                                                                        | [null, null]                                                                                                           |                                                 | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/BeerSheva.pdf, null]    |                           | 63744    | 
| 1471894335  | Me-Kwa-Mooks Park Picnic Area Tables Only          | 0.00 | 30       | 2                  |                  |         | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/MeKwaMooksTables.jpg, null]                                                      |                                                           | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/MeKwaMooksTables1-2.jpg, null]                |                                                                              | [null, null]                                                                                                         |                                                                                                                        | [null, null]                                                                                                           |                                                 | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/Me-Kwa-Mooks.pdf, null] |                           | 63777    | 
| 1474915058  | Don Armeni Boat Ramp Picnic Area Tables Only       | 0.00 | 30       | 2                  |                  |         | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/DonArmeniPicnicArea.jpg, null]                                                   | Don Armeni Picnic Tables 1 and 2                          | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/DonArmeniTable1and2.jpg, null]                | Don Armeni Picnic Tables 1 and 2                                             | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/DonArmeniTable1.jpg, null]              | Don Aremni Picnic Table 1                                                                                              | [null, null]                                                                                                           |                                                 | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/DonArmeni.pdf, null]    |                           | 63685    | 
| 1475505823  | Northacres Park Picnic Area Tables Only            | 0.00 | 50       | 4                  |                  |         | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/NorthacresTable2.jpg, null]                                                      | Northacres Table 2                                        | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/NorthacresParkTable2withPlayground.jpg, null] | Northacres Park Table 2 with Playground Behind Hill                          | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/NorthacresParkTables1and2.jpg, null]    | Northacres Park Table 1 & 2                                                                                            | [null, null]                                                                                                           |                                                 | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/Northacres.pdf, null]   |                           | 63712    | 
| 1480548234  | Carkeek Park Piper's Creek Picnic Area Tables Only | 0.00 | 100      | 12                 |                  |         | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/CarkeekParkTable37_38_39.jpg, Carkeek Park Table 37, 38 with 39 in the distance] | Carkeek Park Table 37, 38 with 39 in the distance         | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/CarkeekParkPipersCreekTable34.jpg, null]      | Carkeek Park Piper?s Creek Table 34 With First Come First Serve Table Behind | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/CarkeekParkPipersCreek373839.jpg, null] | Carkeek Park Piper?s Creek Table 37, 38 and 39                                                                         | [null, null]                                                                                                           |                                                 | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/Carkeek.pdf, null]      |                           | 63773    | 
| 1481757397  | Alki Beach Park Shelter #1                         | 120  | 130      | 14                 |                  | Partial | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/AlkiShelterwithgrill.jpg, null]                                                  | Picnic Shelter at Alki Beach Park With Two Serving Tables | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/AlkiTable12.jpg, null]                        | Alki Beach Tables 1, 2                                                       | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/AlkiTable8.jpg, null]                   | Alki Beach Table 8, 10 and Alki Shelter #1                                                                             | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/AlkiwithTables510.jpg, null]              | Alki Beach Tables 5-10                          | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/AlkiBeach.pdf, null]    | 2 grills
2 serving tables | 63856    | 
| 1481757402  | Benefit Playground Shelter #1                      | 150  | 35       |                    | 2                |         | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/BenefitShelter.JPG, null]                                                        |                                                           | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/BenefitPicnicShelter.JPG, null]               |                                                                              | [null, null]                                                                                                         |                                                                                                                        | [null, null]                                                                                                           |                                                 | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/Benefit.pdf, null]      |                           | 63751    | 
| 1481757507  | Lincoln Park Shelter #2                            | 140  | 250      | 21                 | 1                |         | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/Lincoln2-1.jpg, null]                                                            |                                                           | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/Lincoln2-2.jpg, null]                         |                                                                              | [null, null]                                                                                                         |                                                                                                                        | [null, null]                                                                                                           |                                                 | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/Lincoln1-4.pdf, null]   |                           | 63806    | 
| 1481757416  | Carkeek Park Shelter #2                            | 180  | 190      | 14                 | 3                |         | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/CarkeekParkPlaygroundGrassyAreaShelter2.jpg, null]                               | Carkeek Park Shelter 2 Picnic Area From Grassy Area       | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/CarkeekParkShelter2withGrill.jpg, null]       | Carkeek Park Shelter 2 With Large Grill                                      | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/CarkeekTables810TwoFirstCome.jpg, null] | Vantage from Carkeek Park Shelter 2 Picnic Area with Views of Picnic Tables 8-10 and Two First Come First Serve Tables | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/CarkeekParkShelter2ViewTable11.jpg, null] | Carkeek Park Shelter 2 Looking Up From Table 11 | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/Carkeek.pdf, null]      |                           | 63773    | 
| 1481757420  | Dr. Jose Rizal Park Shelter #1                     | 190  | 75       |                    | 4                | Partial | [http://www.seattle.gov/images/Departments/ParksAndRecreation/Reserve/Picnic/JoseRizalShelter.jpg, null]                                                      |                                                           | [null, null]                                                                                                               |                                                                              | [null, null]                                                                                                         |                                                                                                                        | [null, null]                                                                                                           |                                                 | [http://www.seattle.gov//Documents/Departments/ParksAndRecreation/Reserve/Picnic/Rizal.pdf, null]        |                           | 63692    | 
```