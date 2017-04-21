# SSMMA Available Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-available-buildings-9a7b2) |
| Metadata | [Link](https://data.illinois.gov/api/views/ittj-asww) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ittj-asww/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ittj-asww/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ittj-asww |
| Name | SSMMA Available Buildings |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | planning, economic development, chicago southland, industrial, retail, commercial, office |
| Created | 2012-11-27T18:11:30Z |
| Publication Date | 2012-11-27T19:03:31Z |

## Description

This dataset includes Available Buildings for Sale or Lease in the Chicago Southland region. This list is a aggregation of data from Wm C Groebe & Co, Lee & Associates, Newmark, Knight, and Frank, Simborg, and Rofo data.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | size        | Size       | text      | text        |
| Yes      | series tag     | price       | Price      | text      | text        |
| Yes      | series tag     | contact     | Contact    | text      | text        |
| Yes      | series tag     | contact_nu  | Contact_Nu | text      | text        |
| Yes      | series tag     | source      | Source     | text      | text        |
| Yes      | series tag     | type        | Type       | text      | text        |
| Yes      | series tag     | website     | Website    | text      | text        |
| Yes      | series tag     | lois_link   | LOIS_Link  | text      | text        |
| Yes      | series tag     | editor      | Editor     | text      | text        |
| Yes      | numeric metric | propreitar  | Propreitar | number    | number      |
| Yes      | series tag     | universali  | UniversalI | text      | text        |
| Yes      | numeric metric | shape_leng  | Shape_Leng | number    | number      |
| Yes      | numeric metric | shape_area  | Shape_Area | number    | number      |
| No       |                | location_1  | Location 1 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = location_1
```

## Data Commands

```ls
series e:ittj-asww d:2012-11-27T10:11:31.000Z t:editor=MJR t:price=$1,275,000 t:contact_nu=(312)-337-1571 t:source=Loopnet t:website="http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=17182098&SRID=2450125369&StepID=101&jli=y" t:objectid=1 t:universali=UR0 t:type=Office t:contact="Steve Aaronson-CTK Chicago" t:size=60406 m:shape_area=18232.4858788 m:shape_leng=607.350857987 m:propreitar=0

series e:ittj-asww d:2012-11-27T10:11:31.000Z t:editor=MJR t:price=$450,000 t:contact_nu=(630)-699-2211 t:source=Loopnet t:website="http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=16671132&SRID=2450133693&StepID=101" t:objectid=2 t:universali=UR1 t:type=Retail t:contact="Kris Maranda-Koenig and Strey GMAC" t:size=60406 m:shape_area=4462.1448271 m:shape_leng=352.630940412 m:propreitar=1

series e:ittj-asww d:2012-11-27T10:11:31.000Z t:editor=MJR t:price=$18/SF/Year t:contact_nu=(312)-456-7107 t:source=Loopnet t:website="http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=16046135&SRID=2450138378&StepID=101" t:objectid=3 t:universali=UR2 t:type=Office-Lease t:contact="Yolanda Valle-WS Equities" t:size=11400 m:shape_area=31241.5362207 m:shape_leng=764.434921363 m:propreitar=2
```

## Meta Commands

```ls
metric m:propreitar p:integer l:Propreitar t:dataTypeName=number

metric m:shape_leng p:double l:Shape_Leng t:dataTypeName=number

metric m:shape_area p:double l:Shape_Area t:dataTypeName=number

entity e:ittj-asww l:"SSMMA Available Buildings" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/ittj-asww

property e:ittj-asww t:meta.view v:id=ittj-asww v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA Available Buildings" v:attribution="South Suburban Mayors and Managers Association"

property e:ittj-asww t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ittj-asww t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:ittj-asww t:meta.view.tableauthor v:id=74c3-ka9x v:profileImageUrlMedium=/api/users/74c3-ka9x/profile_images/THUMB v:profileImageUrlLarge=/api/users/74c3-ka9x/profile_images/LARGE v:screenName="Rey de Castro" v:profileImageUrlSmall=/api/users/74c3-ka9x/profile_images/TINY v:roleName=publisher v:displayName="Rey de Castro"
```

## Top Records

```ls
| :updated_at | objectid | size  | price          | contact                            | contact_nu     | source  | type             | website                                                                                                                  | lois_link | editor | propreitar | universali | shape_leng    | shape_area    | location_1                                                                             | 
| =========== | ======== | ===== | ============== | ================================== | ============== | ======= | ================ | ======================================================================================================================== | ========= | ====== | ========== | ========== | ============= | ============= | ====================================================================================== | 
| 1354011091  | 1        | 60406 | $1,275,000     | Steve Aaronson-CTK Chicago         | (312)-337-1571 | Loopnet | Office           | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=17182098&SRID=2450125369&StepID=101&jli=y          |           | MJR    | 0          | UR0        | 607.350857987 | 18232.4858788 | 12757 S. Western Avenue Blue Island, Illinois (41.6609484606923, -87.68002680475657)   | 
| 1354011091  | 2        | 60406 | $450,000       | Kris Maranda-Koenig and Strey GMAC | (630)-699-2211 | Loopnet | Retail           | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=16671132&SRID=2450133693&StepID=101                |           | MJR    | 1          | UR1        | 352.630940412 | 4462.1448271  | 13000 S. Western Avenue Blue Island, Illinois (41.65715812665316, -87.68013759071722)  | 
| 1354011091  | 3        | 11400 | $18/SF/Year    | Yolanda Valle-WS Equities          | (312)-456-7107 | Loopnet | Office-Lease     | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=16046135&SRID=2450138378&StepID=101                |           | MJR    | 2          | UR2        | 764.434921363 | 31241.5362207 | 12015 S. Western Avenue Blue Island, Illinois (41.674861267209614, -87.6805559882707)  | 
| 1354011091  | 4        | 1600  | $24.00/SF/Year |                                    |                | Loopnet | Retail-Lease     | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=17240011&SRID=2450143899&StepID=101&LinkCode=20280 |           | MJR    | 3          | UR3        | 470.964469911 | 13492.505748  | 12434 S. Western Avenue Blue Island, Illinois (41.667265321424246, -87.6804697892168)  | 
| 1354011091  | 5        | 4948  | $24/SF/Year    |                                    |                | Loopnet | Retail-Lease     | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=17355760&SRID=2450170020&StepID=101&LinkCode=20280 |           | MJR    | 4          | UR4        | 337.968368632 | 4931.00013984 | 12606 S. Western Avenue Blue Island, Illinois (41.66440556045153, -87.68033951764228)  | 
| 1354011091  | 6        | 5313  | $20/SF/Year    |                                    |                | Loopnet | Retail-Lease     | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=15656143&SRID=2450176684&StepID=101&LinkCode=20280 |           | MJR    | 5          | UR5        | 809.54810582  | 37404.6503953 | 12601 S. Western Avenue Blue Island, Illinois (41.6645243168861, -87.68020479454434)   | 
| 1354011091  | 7        | 12000 | $8/SF/Year     |                                    |                | Loopnet | Retail-Lease     | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=15916634&SRID=2450179859&StepID=101&LinkCode=20280 |           | MJR    | 6          | UR6        | 527.709634928 | 17079.9659738 | 13102 S. Western Avenue Blue Island, Illinois (41.65532202583206, -87.68013758896011)  | 
| 1354011091  | 8        | 10960 | $3.50/SF/Year  |                                    |                | Loopnet | Industrial-Lease | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=16417881&SRID=2450184119&StepID=101&LinkCode=20280 |           | MJR    | 7          | UR7        | 4026.6787118  | 1004243.08875 | 13636 S. Western Avenue Blue Island, Illinois (41.64423120987925, -87.68011791271745)  | 
| 1354011091  | 9        | 3400  | Negotiable     |                                    |                | Loopnet | Retail           | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=17355763&SRID=2450195515&StepID=101&LinkCode=20280 |           | MJR    | 8          | UR8        | 332.982740034 | 5165.99838794 | 13328 S. Olde Western Blue Island, Illinois (41.65522000020303, -87.68005999956915)    | 
| 1354011091  | 10       | 5000  | $7.92/SF/Year  | Bob Hennessy-Simborg               | (708)-799-4900 | Loopnet | Industrial-Lease | http://www.loopnet.com/xNet/MainSite/Listing/Profile/Profile.aspx?LID=17504923&SRID=2450200289&StepID=101                |           | MJR    | 9          | UR9        | 471.402329446 | 13529.2025312 | 13830 S. Harrison Street Blue Island, Illinois (41.64199113312474, -87.68807694297202) | 
```