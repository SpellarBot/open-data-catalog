# SSMMA Vacant Property Registry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-vacant-property-registry-0b494) |
| Metadata | [Link](https://data.illinois.gov/api/views/c2f2-z5eb) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/c2f2-z5eb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/c2f2-z5eb/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | c2f2-z5eb |
| Name | SSMMA Vacant Property Registry |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | housing, planning, economic development |
| Created | 2012-11-27T20:57:55Z |
| Publication Date | 2012-11-27T20:58:55Z |

## Description

This dataset details communities in the Chicago Southland which have passed a vacant property registry.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | objectid   | OBJECTID   | text          | number        |
| Yes      | series tag     | municipali | Municipali | text          | text          |
| Yes      | series tag     | adopted    | Adopted    | text          | text          |
| Yes      | time           | date_of_ad | Date_Of_Ad | calendar_date | calendar_date |
| Yes      | series tag     | county     | County     | text          | text          |
| Yes      | series tag     | source     | Source     | text          | text          |
| Yes      | numeric metric | shape_leng | SHAPE_Leng | number        | number        |
| Yes      | numeric metric | shape_area | SHAPE_Area | number        | number        |
| Yes      | series tag     | status     | Status     | text          | text          |
| Yes      | series tag     | registrati | Registrati | text          | text          |
| Yes      | numeric metric | fee        | Fee        | money         | text          |
| Yes      | series tag     | contact_na | Contact_Na | text          | text          |
| Yes      | series tag     | contact_in | Contact_In | text          | text          |
| Yes      | series tag     | editor     | Editor     | text          | text          |
| Yes      | numeric metric | propreitar | Propreitar | number        | number        |
| Yes      | series tag     | universal  | Universal_ | text          | text          |
| Yes      | series tag     | ordinance  | Ordinance_ | text          | text          |
| Yes      | series tag     | form_link  | Form_Link  | text          | text          |
```

## Time Field

```ls
Value = date_of_ad
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:c2f2-z5eb d:2008-10-06T00:00:00.000Z t:contact_na="Michael Spongberg-Building" t:ordinance=http://library.municode.com/HTML/14055/level3/COOR_CH6BUBURE_ARTXVIIIVABU.html#COOR_CH6BUBURE_ARTXVIIIVABU_S6-602OBREVABU t:editor=MJR t:adopted=Yes t:county=Cook t:status=Enacted t:contact_in=mspongberg@villageofalsip.org t:registrati="30 days following vacancy" t:universal=UR5 t:objectid=5 t:municipali=Alsip m:fee=200 m:shape_area=177684807.401 m:shape_leng=78660.5849903 m:propreitar=5

series e:c2f2-z5eb d:2012-11-27T12:57:58.000Z t:contact_na="David Mindeman-Building" t:form_link=http://www.blueisland.org/wp-content/uploads/government/city-council/city-council-agenda-minutes/Agenda-and-Council-Materials-082311.pdf t:editor=MJR t:adopted="In Process" t:county=Cook t:status=Proposed t:contact_in=building@cityofblueisland.org t:universal=UR6 t:objectid=6 t:municipali="Blue Island" m:shape_area=115009607.02 m:shape_leng=74811.6522735 m:propreitar=6

series e:c2f2-z5eb d:2008-12-17T00:00:00.000Z t:contact_na="Jim Gigliotti-Community Development" t:ordinance="https://docs.google.com/a/cshcdc.org/viewer?a=v&pid=explorer&chrome=true&srcid=0B0zIlzp6v4g1Nzc1MWNjMDctM2ViNi00ZmU1LWEwNGYtYjQwNTdiMGI2YmZh" t:editor=MJR t:adopted=Yes t:county=Cook t:status=Enacted t:contact_in=jgigliotti@calumetcity.org t:universal=UR7 t:objectid=7 t:municipali="Calumet City" m:shape_area=204892281.96 m:shape_leng=104445.610712 m:propreitar=7
```

## Meta Commands

```ls
metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

metric m:shape_area p:double l:SHAPE_Area t:dataTypeName=number

metric m:fee p:long l:Fee t:dataTypeName=money

metric m:propreitar p:integer l:Propreitar t:dataTypeName=number

entity e:c2f2-z5eb l:"SSMMA Vacant Property Registry" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/c2f2-z5eb

property e:c2f2-z5eb t:meta.view v:id=c2f2-z5eb v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Vacant Property Registry" v:attribution="South Suburban Mayors and Managers Association"

property e:c2f2-z5eb t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:c2f2-z5eb t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:c2f2-z5eb t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| objectid | municipali   | adopted    | date_of_ad          | county | source | shape_leng    | shape_area    | status   | registrati                | fee               | contact_na                          | contact_in                         | editor | propreitar | universal | ordinance                                                                                                                                    | form_link                                                                                                                                | 
| ======== | ============ | ========== | =================== | ====== | ====== | ============= | ============= | ======== | ========================= | ================= | =================================== | ================================== | ====== | ========== | ========= | ============================================================================================================================================ | ======================================================================================================================================== | 
| 5        | Alsip        | Yes        | 2008-10-06T00:00:00 | Cook   |        | 78660.5849903 | 177684807.401 | Enacted  | 30 days following vacancy | $200.00           | Michael Spongberg-Building          | mspongberg@villageofalsip.org      | MJR    | 5          | UR5       | http://library.municode.com/HTML/14055/level3/COOR_CH6BUBURE_ARTXVIIIVABU.html#COOR_CH6BUBURE_ARTXVIIIVABU_S6-602OBREVABU                    |                                                                                                                                          | 
| 6        | Blue Island  | In Process |                     | Cook   |        | 74811.6522735 | 115009607.02  | Proposed |                           |                   | David Mindeman-Building             | building@cityofblueisland.org      | MJR    | 6          | UR6       |                                                                                                                                              | http://www.blueisland.org/wp-content/uploads/government/city-council/city-council-agenda-minutes/Agenda-and-Council-Materials-082311.pdf | 
| 7        | Calumet City | Yes        | 2008-12-17T00:00:00 | Cook   |        | 104445.610712 | 204892281.96  | Enacted  |                           |                   | Jim Gigliotti-Community Development | jgigliotti@calumetcity.org         | MJR    | 7          | UR7       | https://docs.google.com/a/cshcdc.org/viewer?a=v&pid=explorer&chrome=true&srcid=0B0zIlzp6v4g1Nzc1MWNjMDctM2ViNi00ZmU1LWEwNGYtYjQwNTdiMGI2YmZh |                                                                                                                                          | 
| 8        | Countryside  | Yes        | 2008-08-14T00:00:00 | Cook   |        | 60783.9399691 | 78488924.8128 | Enacted  | 15 days following vacancy | $135 for 120 days | Ms. Sharon Peterson                 | building@countryside-il.org        | MJR    | 8          | UR8       | http://www.sterlingcodifiers.com/codebook/getBookData.php?id=&chapter_id=45171&keywords                                                      | http://www.countryside-il.org/sites/default/files/forms_permits/Vacant%20Property%20Form_0.pdf                                           | 
| 9        | Harvey       | Yes        |                     | Cook   |        | 84016.4213909 | 171353181.523 | Enacted  |                           | $200              | Ms. Latonya Rufus-Planning          | lrufus@cityofharvey.org            | MJR    | 9          | UR9       |                                                                                                                                              | http://www.safeguardproperties.com/pub/pdf/_0406145830_001.pdf                                                                           | 
| 10       | Lansing      | Yes        | 2010-09-21T00:00:00 | Cook   |        | 97442.4919202 | 190333148.98  | Enacted  | 60 days following vacancy | $200.00 annually  | Ms. Kristi Delaurentiis-Planning    | kdelaurentiis@villageoflansing.org | MJR    | 10         | UR10      | https://docs.google.com/a/cshcdc.org/viewer?a=v&pid=explorer&chrome=true&srcid=0B0zIlzp6v4g1ZTlhNjcxMmYtYzIwOS00OTgwLThkNWItNTg1ZDc0OTUyN2Mx | http://www.villageoflansing.com/media/vacant.pdf                                                                                         | 
| 11       | Lemont       | Yes        | 2010-08-23T00:00:00 | Cook   |        | 203603.001849 | 157085837.428 | Enacted  | 15 days following vacancy | $75.00            | Mr. Ed Buettner-Building            | ebuettner@lemont.il.us             | MJR    | 11         | UR11      | http://www.lemont.il.us/DocumentView.aspx?DID=288                                                                                            | http://www.lemont.il.us/DocumentView.aspx?DID=287                                                                                        | 
| 12       | Lyons        | Yes        | 2008-10-21T00:00:00 | Cook   |        | 43644.6124393 | 61136572.5398 | Enacted  | 15 days following vacancy | $200 annually     | John Pierce-Building                | (708)-442-4500                     | MJR    | 12         | UR12      | http://www.sterlingcodifiers.com/codebook/getBookData.php?id=?ion_id=541722&keywords=                                                        |                                                                                                                                          | 
| 13       | Mokena       | Yes        | 2010-01-11T00:00:00 | Will   |        | 218668.670717 | 168561627.146 | Enacted  | 30 days                   | $100 annually     | Richard Massey-Building             | rmassey@mokena.org                 | MJR    | 13         | UR13      | http://www2.safeguardproperties.com/vpr/docs/Mokena_IL_ordinance.pdf                                                                         | http://www.mokena.org/DocumentView.aspx?DID=732                                                                                          | 
| 14       | New Lenox    | Yes        | 2010-02-23T00:00:00 | Will   |        | 264540.07385  | 244040391.044 | Enacted  | 30 days following vacancy | $50.00 annually   | Building Department Staff           | (815)-462-6490                     | MJR    | 14         | UR14      | http://library.municode.com/HTML/14158/level3/VICO_CH18BUBURE_ARTXVIIVABU.html#VICO_CH18BUBURE_ARTXVIIVABU_S18-373OBREVABU                   | http://www.newlenox.net/permit_pdfs/vacant%20prop%20reg%20form.pdf#                                                                      | 
```