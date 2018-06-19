# Current Class 1 - Class 4 Food Establishments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-class-1-class-4-food-establishments) |
| Metadata | [Link](https://data.hartford.gov/api/views/xkvv-76v8) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/xkvv-76v8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/xkvv-76v8/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | xkvv-76v8 |
| Name | Current Class 1 - Class 4 Food Establishments |
| Attribution | City of Hartford |
| Category | Public Health |
| Tags | food, health, restaurant, hartford |
| Created | 2014-06-13T00:39:36Z |
| Publication Date | 2015-04-27T09:16:16Z |

## Description

Class 1 - Class 4 Food Establishments. Updated nightly. For more information on the Food Establishment Class codes select the about tab and scroll down to the attachments and open the PDF document

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | blms_id         | blms_id         | text      | text        |
| Yes      | numeric metric | blms_parcel     | blms_parcel     | number    | text        |
| Yes      | series tag     | blms_loc_no     | blms_loc_no     | text      | number      |
| Yes      | series tag     | blms_loc_street | blms_loc_street | text      | text        |
| Yes      | series tag     | blms_dba        | blms_dba        | text      | text        |
| Yes      | series tag     | bldt_lic_text2  | bldt_lic_text2  | text      | text        |
| Yes      | series tag     | bldt_lic_text3  | bldt_lic_text3  | text      | text        |
| Yes      | series tag     | bldt_lic_text6  | bldt_lic_text6  | text      | text        |
| Yes      | series tag     | bldt_lic_text7  | bldt_lic_text7  | text      | text        |
| No       |                | xcoord          | xcoord          | number    | number      |
| No       |                | ycoord          | ycoord          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = xcoord,ycoord
```

## Data Commands

```ls
series e:xkvv-76v8 d:2015-11-30T07:58:08.000Z t:blms_loc_street="MAPLE AV" t:blms_dba="SAM'S FOOD STORE" t:blms_id=15533 t:blms_loc_no=611 t:bldt_lic_text2="FOOD - CLASS 2" m:blms_parcel=229656158

series e:xkvv-76v8 d:2015-11-30T07:58:08.000Z t:blms_loc_street="ASYLUM ST" t:bldt_lic_text7=LIQUOR t:blms_dba="MCKINNON'S CAFE" t:bldt_lic_text3=CAFE' t:bldt_lic_text6="SEATING CAPACITY 75" t:blms_id=10090 t:blms_loc_no=114 t:bldt_lic_text2="FOOD - CLASS 4" m:blms_parcel=245345121

series e:xkvv-76v8 d:2015-11-30T07:58:08.000Z t:blms_loc_street="WOODLAND ST" t:blms_dba="XPRESS GROCERY STORE LLC" t:bldt_lic_text3=GROCERY t:blms_id=15865 t:blms_loc_no=148 t:bldt_lic_text2="FOOD - CLASS 2" m:blms_parcel=177251005
```

## Meta Commands

```ls
metric m:blms_parcel p:integer l:blms_parcel t:dataTypeName=number

entity e:xkvv-76v8 l:"Current Class 1 - Class 4 Food Establishments" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/xkvv-76v8

property e:xkvv-76v8 t:meta.view v:id=xkvv-76v8 v:category="Public Health" v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Current Class 1 - Class 4 Food Establishments" v:attribution="City of Hartford"

property e:xkvv-76v8 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:xkvv-76v8 t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:xkvv-76v8 t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| :updated_at | blms_id | blms_parcel | blms_loc_no | blms_loc_street | blms_dba                 | bldt_lic_text2 | bldt_lic_text3 | bldt_lic_text6      | bldt_lic_text7 | xcoord  | ycoord | 
| =========== | ======= | =========== | =========== | =============== | ======================== | ============== | ============== | =================== | ============== | ======= | ====== | 
| 1448870288  | 15533   | 229656158   | 611         | MAPLE AV        | SAM'S FOOD STORE         | FOOD - CLASS 2 |                |                     |                | 1018408 | 831809 | 
| 1448870288  | 10090   | 245345121   | 114         | ASYLUM ST       | MCKINNON'S CAFE          | FOOD - CLASS 4 | CAFE'          | SEATING CAPACITY 75 | LIQUOR         | 1020361 | 840341 | 
| 1448870288  | 15865   | 177251005   | 148         | WOODLAND ST     | XPRESS GROCERY STORE LLC | FOOD - CLASS 2 | GROCERY        |                     |                | 1014117 | 843860 | 
| 1448870288  | 16881   | 175187036   | 1330        | ALBANY AV       | SAVE A DOLLAR            | FOOD - CLASS 1 |                |                     |                | 1014016 | 846138 | 
| 1448870288  | 15866   | 276688125   | 634         | WETHERSFIELD AV | EVERGREEN GULF LLC       | FOOD - CLASS 1 |                |                     |                | 1021530 | 829901 | 
| 1448870288  | 11059   | 223330032   | 177         | ALLYN ST        | N/V                      | FOOD - CLASS 2 |                |                     |                | 1019012 | 840760 | 
| 1448870288  | 13515   | 137481080   | 72          | NEW PARK AV     | NEW PARK PIZZA CT        | FOOD - CLASS 4 |                |                     |                | 1011707 | 835867 | 
| 1448870288  | 16333   | 239113072   | 205         | BARBOUR ST      | BLUE MINI MARKET         | FOOD - CLASS 2 |                |                     |                | 1019599 | 848967 | 
| 1448870288  | 11726   | 269077031   | 100         | COLUMBUS BLVD   | SEATTLE'S BEST           | FOOD - CLASS 3 | FOOD SERVICE   |                     |                | 1022035 | 838816 | 
| 1448870288  | 16002   | 284074077   | 3250        | MAIN ST         | NOBLE ENERGY INC         | FOOD - CLASS 1 |                |                     |                | 1023778 | 850691 | 
```