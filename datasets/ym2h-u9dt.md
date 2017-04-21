# Brooklyn Public Library Catalog

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/brooklyn-public-library-catalog-f85b8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ym2h-u9dt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ym2h-u9dt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ym2h-u9dt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ym2h-u9dt |
| Name | Brooklyn Public Library Catalog |
| Attribution | Brooklyn Public Library (BPL) |
| Category | Recreation |
| Tags | library, catalog, catalogue, brooklyn, book, author, title, edition, publisher |
| Created | 2011-10-04T21:42:50Z |
| Publication Date | 2013-06-21T20:11:31Z |

## Description

Brooklyn Public Library Catalog, with Call #, Author, Title, Edition, Pub Info, Standard #. Data delimiter is ?|?.

## Columns

```ls
| Included | Schema Type | Field Name   | Name           | Data Type | Render Type |
| ======== | =========== | ============ | ============== | ========= | =========== |
| No       | time        | :updated_at  | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | call_biblio_ | CALL #(BIBLIO) | text      | text        |
| Yes      | series tag  | author       | AUTHOR         | text      | text        |
| Yes      | series tag  | title        | TITLE          | text      | text        |
| Yes      | series tag  | edition      | EDITION        | text      | text        |
| Yes      | series tag  | pub_info     | PUB INFO       | text      | text        |
| Yes      | series tag  | standard_    | STANDARD #     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ym2h-u9dt d:2011-10-04T14:42:59.000Z t:title="09/11, 8:48 AM : documenting America's greatest tragedy / edited by BlueEar.com: Global Writing Worth Reading with the faculty and students of the New York University Department of Journalism   foreward by Jay Rosen   introduction by Ethan Casey." t:standard_="1591090113 (pbk.) : $22.00" t:pub_info="[Charleston, SC] : BookSurge.com, 2001." t:call_biblio_="974.71 N" m:row_number.ym2h-u9dt=1

series e:ym2h-u9dt d:2011-10-04T14:42:59.000Z t:title="1812-1814 : sekretna?i?a perepiska generala P.I. Bagrationa, lichnye pis?ma generala N.N. Raevskogo, zapiski generala M.S. Voron?t?sova, dnevniki ofi?t?serov russko?i armii : iz sobrani?i?a Gosudarstvennogo Istoricheskogo muze?i?a / [sostaviteli, avtory vstupitel?nykh state?i i kommentariev A.K. Afanas?ev ... et al.]." t:standard_=5852551538 t:pub_info="Moskva :  Terra , c1992." t:call_biblio_="RUS q947.072 E" m:row_number.ym2h-u9dt=2

series e:ym2h-u9dt d:2011-10-04T14:42:59.000Z t:title="1799-1837 : Pushkin i ego vrem?i?a / [redaktory S.G. Blinov, M.D. Filin]." t:standard_=5300002216 t:pub_info="Moskva :  TERRA , 1997." t:call_biblio_="RUS qB PUSHKIN T" m:row_number.ym2h-u9dt=3
```

## Meta Commands

```ls
metric m:row_number.ym2h-u9dt p:long l:"Row Number"

entity e:ym2h-u9dt l:"Brooklyn Public Library Catalog" t:attribution="Brooklyn Public Library (BPL)" t:url=https://data.cityofnewyork.us/api/views/ym2h-u9dt

property e:ym2h-u9dt t:meta.view v:id=ym2h-u9dt v:category=Recreation v:averageRating=0 v:name="Brooklyn Public Library Catalog" v:attribution="Brooklyn Public Library (BPL)"

property e:ym2h-u9dt t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ym2h-u9dt t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | call_biblio_          | author | title                                                                                                                                                                                                                                                                                                                           | edition   | pub_info                                                                     | standard_                       | 
| =========== | ===================== | ====== | =============================================================================================================================================================================================================================================================================================================================== | ========= | ============================================================================ | =============================== | 
| 1317739379  | 974.71 N              |        | 09/11, 8:48 AM : documenting America's greatest tragedy / edited by BlueEar.com: Global Writing Worth Reading with the faculty and students of the New York University Department of Journalism foreward by Jay Rosen introduction by Ethan Casey.                                                                              |           | [Charleston, SC] : BookSurge.com, 2001.                                      | 1591090113 (pbk.) : $22.00      | 
| 1317739379  | RUS q947.072 E        |        | 1812-1814 : sekretna?i?a perepiska generala P.I. Bagrationa, lichnye pis?ma generala N.N. Raevskogo, zapiski generala M.S. Voron?t?sova, dnevniki ofi?t?serov russko?i armii : iz sobrani?i?a Gosudarstvennogo Istoricheskogo muze?i?a / [sostaviteli, avtory vstupitel?nykh state?i i kommentariev A.K. Afanas?ev ... et al.]. |           | Moskva : Terra , c1992.                                                      | 5852551538                      | 
| 1317739379  | RUS qB PUSHKIN T      |        | 1799-1837 : Pushkin i ego vrem?i?a / [redaktory S.G. Blinov, M.D. Filin].                                                                                                                                                                                                                                                       |           | Moskva : TERRA , 1997.                                                       | 5300002216                      | 
| 1317739379  | NEIG 0149";"NEIG 2713 |        | 177-179 Columbia Heights [picture]                                                                                                                                                                                                                                                                                              |           | 1920.                                                                        |                                 | 
| 1317739379  | NEIG 0150             |        | 132-134 Columbia Heights [picture]                                                                                                                                                                                                                                                                                              |           | 1921.                                                                        |                                 | 
| 1317739379  | VIDEO 618.92 F        |        | The 15-18 month old [videorecording]                                                                                                                                                                                                                                                                                            |           | Salt Lake City, Utah : Humancare, Inc. : Medical Media [distributor], c1994. | $26.00                          | 
| 1317739379  | NEIG 0185             |        | 111-117 Montague St. [picture]                                                                                                                                                                                                                                                                                                  |           | 1926.                                                                        |                                 | 
| 1317739379  | CHI J-E               |        | 1 2 3 / [fan i Huang Ch?ing-y?n].                                                                                                                                                                                                                                                                                               | Ch?u pan. | Hsiang-kang : Hsin ya wen hua shih yeh yu hsien kung ssu, 1994.              | 9620823397 : $6.00              | 
| 1317739379  | VIDEO J 791.433 O     |        | 1, 2, 3 count with me [videorecording] / Children's Television Workshop producer, Karin Young Shiel director, Emily Squires writers, Sara Compton and Joey Mazzarino.                                                                                                                                                           |           | New York : Sony Wonder, c1997.                                               | 1573305677 : $8.65";"7464499193 | 
| 1317739379  | 227.9406 F            |        | 1, 2 & 3 John / Bruce B. Barton ... [et al.] Grant Osborne, general editor.                                                                                                                                                                                                                                                     |           | Wheaton, Ill. : Tyndale House, c1998.                                        | 0842328572 (pbk.) : $14.99      | 
```