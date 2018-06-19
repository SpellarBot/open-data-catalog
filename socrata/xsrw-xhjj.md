# Missouri Show Caves

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-show-caves-73310) |
| Metadata | [Link](https://data.mo.gov/api/views/xsrw-xhjj) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/xsrw-xhjj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/xsrw-xhjj/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | xsrw-xhjj |
| Name | Missouri Show Caves |
| Created | 2013-11-01T14:49:20Z |
| Publication Date | 2017-02-15T15:06:54Z |

## Columns

```ls
| Included | Schema Type | Field Name                                 | Name                                         | Data Type | Render Type |
| ======== | =========== | ========================================== | ============================================ | ========= | =========== |
| No       | time        | :updated_at                                | updated_at                                   | meta_data | meta_data   |
| Yes      | series tag  | name_of_cave                               | Name of Cave                                 | text      | text        |
| Yes      | series tag  | park_company                               | Park/Company                                 | text      | text        |
| No       |             | mailing_address_if_different_from_physical | Mailing Address (if different from Physical) | text      | text        |
| No       |             | physical_address                           | Physical Address                             | text      | text        |
| Yes      | series tag  | zip_code                                   | Zip Code                                     | text      | text        |
| Yes      | series tag  | county                                     | County                                       | text      | text        |
| Yes      | series tag  | phone_number                               | Phone Number                                 | text      | text        |
| Yes      | series tag  | alt_phone_number                           | Alt Phone Number                             | text      | text        |
| Yes      | series tag  | website                                    | Website                                      | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailing_address_if_different_from_physical,physical_address
```

## Data Commands

```ls
series e:xsrw-xhjj d:2017-02-15T15:06:07.000Z t:name_of_cave="Bridal Cave & Bear Cave" t:phone_number=573-346-2676 t:zip_code=65020 t:website=http://www.bridalcave.com t:county=Camden t:park_company="Thunder Mountain Park" m:row_number.xsrw-xhjj=1

series e:xsrw-xhjj d:2017-02-15T15:06:07.000Z t:name_of_cave="Bluff Dwellers Cavern" t:phone_number=417-475-3666 t:zip_code=64854 t:website=http://www.bluffdwellerscavern.com t:county=McDonald m:row_number.xsrw-xhjj=2

series e:xsrw-xhjj d:2017-02-15T15:06:07.000Z t:name_of_cave="Bonne Terre Mine" t:phone_number=314-209-7200 t:zip_code=63044 t:website=http://www.westenddiving.com t:county="Saint Francois" t:alt_phone_number=1-888-843-3483 t:park_company="West-End Driving - Bonne Terre, Inc." m:row_number.xsrw-xhjj=3
```

## Meta Commands

```ls
metric m:row_number.xsrw-xhjj p:long l:"Row Number"

entity e:xsrw-xhjj l:"Missouri Show Caves" t:url=https://data.mo.gov/api/views/xsrw-xhjj

property e:xsrw-xhjj t:meta.view v:id=xsrw-xhjj v:averageRating=0 v:name="Missouri Show Caves"

property e:xsrw-xhjj t:meta.view.owner v:id=eb88-upz2 v:screenName=DOLIR v:displayName=DOLIR

property e:xsrw-xhjj t:meta.view.tableauthor v:id=eb88-upz2 v:screenName=DOLIR v:roleName=editor v:displayName=DOLIR
```

## Top Records

```ls
| :updated_at | name_of_cave             | park_company                         | mailing_address_if_different_from_physical | physical_address        | zip_code | county         | phone_number | alt_phone_number        | website                                                                          | 
| =========== | ======================== | ==================================== | ========================================== | ======================= | ======== | ============== | ============ | ======================= | ================================================================================ | 
| 1487171167  | Bridal Cave & Bear Cave  | Thunder Mountain Park                |                                            | 526 Bridal Cave Rd.     | 65020    | Camden         | 573-346-2676 |                         | [http://www.bridalcave.com, null]                                                | 
| 1487171167  | Bluff Dwellers Cavern    |                                      | 945 Cliff Side Dr.                         | 954 Highway 59 South    | 64854    | McDonald       | 417-475-3666 |                         | [http://www.bluffdwellerscavern.com, null]                                       | 
| 1487171167  | Bonne Terre Mine         | West-End Driving - Bonne Terre, Inc. | 12464 Natural Bridge Rd.                   | Hwy 7 & Allen St.       | 63044    | Saint Francois | 314-209-7200 | 1-888-843-3483          | [http://www.westenddiving.com, null]                                             | 
| 1487171167  | Cameron Cave             | Mark Twain Cave, Inc.                |                                            | 300 Cave Hollow Road    | 63401    | Marion         | 573-221-1656 |                         | [http://www.marktwaincave.com/mtc_cameroncave.html, null]                        | 
| 1487171167  | Cathedral Cave           | Onondaga Cave State Park             |                                            | 7556 Hwy. H             | 65535    | Crawford       | 573-245-6576 | 573-245-6600 Cave Tours | [http://www.silverdollarcity.com/theme-park/Attractions/Rides/Marvel-Cave, null] | 
| 1487171167  | Cave Vineyard            |                                      |                                            | 21124 Cave Road         | 63670    | Ste. Genevieve | 573-543-5284 |                         | [http://www.cavevineyard.com, null]                                              | 
| 1487171167  | Crystal City Underground |                                      |                                            | 700 Crystal Avenue      | 63019    | Jefferson      | 636-931-2888 |                         | [http://www.crystalcityunderground.com, null]                                    | 
| 1487171167  | Current River Cavern     | Cave Spring Park                     | P.O. Box 1138                              | HC 1 Box 89             | 63965    | Carter         | 573-323-9943 |                         | [http://www.cavespringpark.com, null]                                            | 
| 1487171167  | Fantastic Caverns        |                                      |                                            | 4872 North Farm Rd. 125 | 65803    | Greene         | 417-833-2010 |                         | [http://www.fantasticcaverns.com, null]                                          | 
| 1487171167  | Fisher Cave              | Meramac State Park                   |                                            | 115 Meramec Park Dr.    | 63080    | Franklin       | 573-468-6072 | 1-800-334-6946          | [http://www.mostateparks.com/park/meramec-state-park, null]                      | 
```