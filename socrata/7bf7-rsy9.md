# 2011 Net Grand List by Town

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-net-grand-list-by-town) |
| Metadata | [Link](https://data.ct.gov/api/views/7bf7-rsy9) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/7bf7-rsy9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/7bf7-rsy9/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 7bf7-rsy9 |
| Name | 2011 Net Grand List by Town |
| Category | Government |
| Tags | opm, grand list, igp |
| Created | 2014-07-29T13:54:49Z |
| Publication Date | 2014-07-29T14:36:55Z |

## Description

The Grand List is the aggregate valuation of taxable property within a given town. The Total Net Grand Lists by Town Data includes a breakdown for taxable categories and exemptions under the following column headings:

Town Name, Residential, Commercial, Industrial, Public Utility, Vacant, Land Use, 10 Mill Forest, Apartments, Total Real, Real Exemptions, Total Net Real, Motor Vehicles, MV Exemptions, Total Net MV, Personal Property, Personal Property Exemptions, Total Net Personal Property, Total Net Grand List

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                        | Data Type | Render Type |
| ======== | ============== | ========================================= | =========================================== | ========= | =========== |
| Yes      | series tag     | code                                      | CODE                                        | text      | number      |
| Yes      | series tag     | town                                      | TOWN                                        | text      | text        |
| Yes      | numeric metric | 2011_gross_assessment_100_residential     | 2011 GROSS ASSESSMENT - 100-Residential     | number    | number      |
| Yes      | numeric metric | 2011_gross_assessment_200_commercial      | 2011 GROSS ASSESSMENT - 200-Commercial      | number    | number      |
| Yes      | numeric metric | 2011_gross_assessment_300_industrial      | 2011 GROSS ASSESSMENT - 300-Industrial      | number    | number      |
| Yes      | numeric metric | 2011_gross_assessment_400_public_utility  | 2011 GROSS ASSESSMENT - 400-Public Utility  | number    | number      |
| Yes      | numeric metric | 2011_gross_assessment_500_vacant          | 2011 GROSS ASSESSMENT - 500-Vacant          | number    | number      |
| Yes      | numeric metric | 2011_gross_assessment_600_land_use        | 2011 GROSS ASSESSMENT - 600-Land Use        | number    | number      |
| Yes      | numeric metric | 2011_gross_assessment_700_ten_mill_forest | 2011 GROSS ASSESSMENT - 700-Ten Mill Forest | number    | number      |
| Yes      | numeric metric | 2011_gross_assessment_800_apartments      | 2011 GROSS ASSESSMENT - 800-Apartments      | number    | number      |
| Yes      | numeric metric | 2011_gross_assessment_total_real          | 2011 GROSS ASSESSMENT - TOTAL REAL          | number    | number      |
| Yes      | numeric metric | 2011_all_real_exemptions                  | 2011 ALL REAL - EXEMPTIONS                  | number    | number      |
| Yes      | numeric metric | 2011_total_net_real                       | 2011 TOTAL NET REAL                         | number    | number      |
| Yes      | numeric metric | 2011_assessment_total_gross_mv            | 2011 ASSESSMENT TOTAL GROSS MV              | number    | number      |
| Yes      | numeric metric | 2011_all_mv_exemptions                    | 2011 ALL MV EXEMPTIONS                      | number    | number      |
| Yes      | numeric metric | 2011_assessment_total_net_mv              | 2011 ASSESSMENT TOTAL NET MV                | number    | number      |
| Yes      | numeric metric | 2011_assessment_gross_personal_prop       | 2011 ASSESSMENT GROSS PERSONAL PROP         | number    | number      |
| Yes      | numeric metric | 2011_all_pp_exemptions                    | 2011 ALL PP EXEMPTIONS                      | number    | number      |
| Yes      | numeric metric | 2011_pp_total_net_pp                      | 2011 PP TOTAL NET PP                        | number    | number      |
| Yes      | numeric metric | 2011_total_net_grand_list                 | 2011 TOTAL NET GRAND LIST                   | money     | money       |
| Yes      | numeric metric | none                                      | (none)                                      | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7bf7-rsy9 d:2011-01-01T00:00:00.000Z t:town=Andover t:code=1 m:2011_gross_assessment_total_real=229364108 m:2011_gross_assessment_400_public_utility=616800 m:2011_total_net_real=228351608 m:2011_total_net_grand_list=258506273 m:2011_assessment_gross_personal_prop=6260773 m:2011_pp_total_net_pp=5893779 m:2011_assessment_total_gross_mv=24721366 m:2011_all_pp_exemptions=366994 m:2011_gross_assessment_600_land_use=636120 m:2011_gross_assessment_800_apartments=1536000 m:2011_gross_assessment_500_vacant=6133800 m:2011_assessment_total_net_mv=24260886 m:2011_gross_assessment_300_industrial=1068300 m:2011_gross_assessment_100_residential=214676688 m:2011_all_mv_exemptions=460480 m:2011_all_real_exemptions=1012500 m:2011_gross_assessment_200_commercial=4696400

series e:7bf7-rsy9 d:2011-01-01T00:00:00.000Z t:town=Ansonia t:code=2 m:2011_gross_assessment_total_real=1050595395 m:2011_gross_assessment_400_public_utility=333600 m:2011_total_net_real=1043894459 m:2011_total_net_grand_list=1174493645 m:2011_assessment_gross_personal_prop=44521036 m:2011_pp_total_net_pp=40734206 m:2011_assessment_total_gross_mv=90916888 m:2011_all_pp_exemptions=3786830 m:2011_gross_assessment_600_land_use=3180 m:2011_gross_assessment_800_apartments=16936400 m:2011_gross_assessment_500_vacant=0 m:2011_assessment_total_net_mv=89864980 m:2011_gross_assessment_300_industrial=20006500 m:2011_gross_assessment_100_residential=909108600 m:2011_all_mv_exemptions=1051908 m:2011_all_real_exemptions=6700936 m:2011_gross_assessment_700_ten_mill_forest=121115 m:2011_gross_assessment_200_commercial=104086000

series e:7bf7-rsy9 d:2011-01-01T00:00:00.000Z t:town=Ashford t:code=3 m:2011_gross_assessment_total_real=259644550 m:2011_gross_assessment_400_public_utility=0 m:2011_total_net_real=259050525 m:2011_total_net_grand_list=294930180 m:2011_assessment_gross_personal_prop=7562877 m:2011_pp_total_net_pp=6976935 m:2011_assessment_total_gross_mv=29897442 m:2011_all_pp_exemptions=585942 m:2011_gross_assessment_600_land_use=3101150 m:2011_gross_assessment_800_apartments=9291200 m:2011_gross_assessment_500_vacant=10916400 m:2011_assessment_total_net_mv=28902720 m:2011_gross_assessment_300_industrial=0 m:2011_gross_assessment_100_residential=223581000 m:2011_all_mv_exemptions=994722 m:2011_all_real_exemptions=594025 m:2011_gross_assessment_700_ten_mill_forest=9700 m:2011_gross_assessment_200_commercial=12745100
```

## Meta Commands

```ls
metric m:2011_gross_assessment_100_residential p:long l:"2011 GROSS ASSESSMENT - 100-Residential" t:dataTypeName=number

metric m:2011_gross_assessment_200_commercial p:long l:"2011 GROSS ASSESSMENT - 200-Commercial" t:dataTypeName=number

metric m:2011_gross_assessment_300_industrial p:long l:"2011 GROSS ASSESSMENT - 300-Industrial" t:dataTypeName=number

metric m:2011_gross_assessment_400_public_utility p:integer l:"2011 GROSS ASSESSMENT - 400-Public Utility" t:dataTypeName=number

metric m:2011_gross_assessment_500_vacant p:long l:"2011 GROSS ASSESSMENT - 500-Vacant" t:dataTypeName=number

metric m:2011_gross_assessment_600_land_use p:integer l:"2011 GROSS ASSESSMENT - 600-Land Use" t:dataTypeName=number

metric m:2011_gross_assessment_700_ten_mill_forest p:integer l:"2011 GROSS ASSESSMENT - 700-Ten Mill Forest" t:dataTypeName=number

metric m:2011_gross_assessment_800_apartments p:long l:"2011 GROSS ASSESSMENT - 800-Apartments" t:dataTypeName=number

metric m:2011_gross_assessment_total_real p:long l:"2011 GROSS ASSESSMENT - TOTAL REAL" t:dataTypeName=number

metric m:2011_all_real_exemptions p:long l:"2011 ALL REAL - EXEMPTIONS" t:dataTypeName=number

metric m:2011_total_net_real p:long l:"2011 TOTAL NET REAL" t:dataTypeName=number

metric m:2011_assessment_total_gross_mv p:long l:"2011 ASSESSMENT TOTAL GROSS MV" t:dataTypeName=number

metric m:2011_all_mv_exemptions p:integer l:"2011 ALL MV EXEMPTIONS" t:dataTypeName=number

metric m:2011_assessment_total_net_mv p:long l:"2011 ASSESSMENT TOTAL NET MV" t:dataTypeName=number

metric m:2011_assessment_gross_personal_prop p:long l:"2011 ASSESSMENT GROSS PERSONAL PROP" t:dataTypeName=number

metric m:2011_all_pp_exemptions p:long l:"2011 ALL PP EXEMPTIONS" t:dataTypeName=number

metric m:2011_pp_total_net_pp p:long l:"2011 PP TOTAL NET PP" t:dataTypeName=number

metric m:2011_total_net_grand_list p:long l:"2011 TOTAL NET GRAND LIST" t:dataTypeName=money

metric m:none p:long l:(none) t:dataTypeName=number

entity e:7bf7-rsy9 l:"2011 Net Grand List by Town" t:url=https://data.ct.gov/api/views/7bf7-rsy9

property e:7bf7-rsy9 t:meta.view v:id=7bf7-rsy9 v:category=Government v:averageRating=0 v:name="2011 Net Grand List by Town"

property e:7bf7-rsy9 t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:displayName="Jamie Gamble"

property e:7bf7-rsy9 t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```

## Top Records

```ls
| code | town         | 2011_gross_assessment_100_residential | 2011_gross_assessment_200_commercial | 2011_gross_assessment_300_industrial | 2011_gross_assessment_400_public_utility | 2011_gross_assessment_500_vacant | 2011_gross_assessment_600_land_use | 2011_gross_assessment_700_ten_mill_forest | 2011_gross_assessment_800_apartments | 2011_gross_assessment_total_real | 2011_all_real_exemptions | 2011_total_net_real | 2011_assessment_total_gross_mv | 2011_all_mv_exemptions | 2011_assessment_total_net_mv | 2011_assessment_gross_personal_prop | 2011_all_pp_exemptions | 2011_pp_total_net_pp | 2011_total_net_grand_list | none | 
| ==== | ============ | ===================================== | ==================================== | ==================================== | ======================================== | ================================ | ================================== | ========================================= | ==================================== | ================================ | ======================== | =================== | ============================== | ====================== | ============================ | =================================== | ====================== | ==================== | ========================= | ==== | 
| 1    | Andover      | 214676688                             | 4696400                              | 1068300                              | 616800                                   | 6133800                          | 636120                             |                                           | 1536000                              | 229364108                        | 1012500                  | 228351608           | 24721366                       | 460480                 | 24260886                     | 6260773                             | 366994                 | 5893779              | 258506273                 |      | 
| 2    | Ansonia      | 909108600                             | 104086000                            | 20006500                             | 333600                                   | 0                                | 3180                               | 121115                                    | 16936400                             | 1050595395                       | 6700936                  | 1043894459          | 90916888                       | 1051908                | 89864980                     | 44521036                            | 3786830                | 40734206             | 1174493645                |      | 
| 3    | Ashford      | 223581000                             | 12745100                             | 0                                    | 0                                        | 10916400                         | 3101150                            | 9700                                      | 9291200                              | 259644550                        | 594025                   | 259050525           | 29897442                       | 994722                 | 28902720                     | 7562877                             | 585942                 | 6976935              | 294930180                 |      | 
| 4    | Avon         | 2103432480                            | 248700780                            | 28467040                             | 340090                                   | 5265470                          | 242710                             |                                           | 37355920                             | 2423804490                       | 4946860                  | 2418857630          | 174465250                      | 827060                 | 173638190                    | 90912010                            | 15301040               | 75610970             | 2668106790                |      | 
| 5    | Barkhamsted  | 278853500                             | 13118390                             | 4331720                              |                                          | 3339860                          | 32055170                           |                                           | 2132050                              | 333830690                        | 1068790                  | 332761900           | 30788799                       | 753250                 | 30035549                     | 14710187                            | 3365640                | 11344547             | 374141996                 |      | 
| 6    | Beacon Falls | 357409820                             | 14544290                             | 30697430                             | 313640                                   | 13442490                         | 178340                             |                                           |                                      | 416586010                        | 4047858                  | 412538152           | 41007660                       | 367110                 | 40640550                     | 20463570                            | 2129638                | 18333932             | 471512634                 |      | 
| 7    | Berlin       | 1534224240                            | 284808180                            | 138882600                            | 3468400                                  | 34178210                         | 11086560                           | 884280                                    |                                      | 2007532470                       | 11264068                 | 1996268402          | 191601270                      | 11923310               | 179677960                    | 232799460                           | 57119040               | 175680420            | 2351626782                |      | 
| 8    | Bethany      | 517012400                             | 14671490                             | 19591290                             |                                          | 7059290                          | 225700                             |                                           |                                      | 558560170                        | 4928990                  | 553631180           | 45999669                       | 327387                 | 45672282                     | 23652578                            | 3476390                | 20176188             | 619479650                 |      | 
| 9    | Bethel       | 1689288980                            | 225096590                            | 88050310                             |                                          | 51458370                         | 5667650                            |                                           | 20779840                             | 2080341740                       | 7139840                  | 2073201900          | 136693790                      | 435420                 | 136258370                    | 154949640                           | 23945240               | 131004400            | 2340464670                |      | 
| 10   | Bethlehem    | 330956800                             | 22356600                             | 3146000                              |                                          | 10931840                         | 1625660                            |                                           |                                      | 369016900                        | 2903140                  | 366113760           | 32836080                       | 155290                 | 32680790                     | 8231332                             | 1427737                | 6803595              | 405598145                 |      | 
```