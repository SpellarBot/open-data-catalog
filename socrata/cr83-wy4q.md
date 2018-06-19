# Wireless Usage at Austin Public Library

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wireless-usage-at-austin-public-library) |
| Metadata | [Link](https://data.austintexas.gov/api/views/cr83-wy4q) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/cr83-wy4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/cr83-wy4q/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | cr83-wy4q |
| Name | Wireless Usage at Austin Public Library |
| Attribution | Austin Public Library |
| Category | Neighborhood |
| Tags | wifi, usage, library |
| Created | 2015-07-08T16:38:33Z |
| Publication Date | 2017-04-03T19:49:16Z |

## Description

The Library offers WiFi access at all locations. As of 10/2016 we are pulling the usage from Meraki, and it is the number of distinct clients using our WiFi. Prior to 10/2016, we pulled number of sessions/connections for each location from Google Analytics monthly.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| No       |                | date                       | Date                       | text      | text        |
| Yes      | numeric metric | faulk_central_library      | Faulk Central Library      | number    | number      |
| Yes      | numeric metric | carver_branch              | Carver Branch              | number    | number      |
| Yes      | numeric metric | cepeda_branch              | Cepeda Branch              | number    | number      |
| Yes      | numeric metric | hampton_branch_at_oak_hill | Hampton Branch at Oak Hill | number    | number      |
| Yes      | numeric metric | howson_branch              | Howson Branch              | number    | number      |
| Yes      | numeric metric | little_walnut_creek_branch | Little Walnut Creek Branch | number    | number      |
| Yes      | numeric metric | milwood_branch             | Milwood Branch             | number    | number      |
| Yes      | numeric metric | manchaca_road_branch       | Manchaca Road Branch       | number    | number      |
| Yes      | numeric metric | north_village_branch       | North Village Branch       | number    | number      |
| Yes      | numeric metric | old_quarry_branch          | Old Quarry Branch          | number    | number      |
| Yes      | numeric metric | pleasant_hill_branch       | Pleasant Hill Branch       | number    | number      |
| Yes      | numeric metric | recycled_reads_bookstore   | Recycled Reads Bookstore   | number    | number      |
| Yes      | numeric metric | ruiz_branch                | Ruiz Branch                | number    | number      |
| Yes      | numeric metric | southeast_branch           | Southeast Branch           | number    | number      |
| Yes      | numeric metric | st_john_branch             | St. John Branch            | number    | number      |
| Yes      | numeric metric | spicewood_springs_branch   | Spicewood Springs Branch   | number    | number      |
| Yes      | numeric metric | terrazas_branch            | Terrazas Branch            | number    | number      |
| Yes      | numeric metric | twin_oaks_branch           | Twin Oaks Branch           | number    | number      |
| Yes      | numeric metric | university_hills_branch    | University Hills Branch    | number    | number      |
| Yes      | numeric metric | willie_mae_kirk_branch     | Willie Mae Kirk Branch     | number    | number      |
| Yes      | numeric metric | windsor_park_branch        | Windsor Park Branch        | number    | number      |
| Yes      | numeric metric | yarborough_branch          | Yarborough Branch          | number    | number      |
| Yes      | series tag     | notes                      | Notes                      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:cr83-wy4q d:2017-04-03T19:41:02.000Z m:recycled_reads_bookstore=1018 m:spicewood_springs_branch=1526 m:windsor_park_branch=921 m:old_quarry_branch=1053 m:yarborough_branch=1087 m:howson_branch=510 m:hampton_branch_at_oak_hill=680 m:st_john_branch=1020 m:ruiz_branch=2277 m:twin_oaks_branch=1436 m:little_walnut_creek_branch=1695 m:willie_mae_kirk_branch=415 m:north_village_branch=1362 m:faulk_central_library=6455 m:milwood_branch=956 m:carver_branch=1135 m:cepeda_branch=841 m:terrazas_branch=757 m:pleasant_hill_branch=848 m:southeast_branch=831 m:university_hills_branch=991 m:manchaca_road_branch=1974

series e:cr83-wy4q d:2017-04-03T19:41:02.000Z m:recycled_reads_bookstore=1389 m:spicewood_springs_branch=1335 m:windsor_park_branch=893 m:old_quarry_branch=928 m:yarborough_branch=936 m:howson_branch=427 m:hampton_branch_at_oak_hill=536 m:st_john_branch=1059 m:ruiz_branch=2609 m:twin_oaks_branch=1468 m:little_walnut_creek_branch=2016 m:willie_mae_kirk_branch=449 m:north_village_branch=1607 m:faulk_central_library=7009 m:milwood_branch=804 m:carver_branch=1274 m:cepeda_branch=965 m:terrazas_branch=719 m:pleasant_hill_branch=1031 m:southeast_branch=902 m:university_hills_branch=940 m:manchaca_road_branch=2271

series e:cr83-wy4q d:2017-04-03T19:41:02.000Z m:recycled_reads_bookstore=1152 m:spicewood_springs_branch=1223 m:windsor_park_branch=869 m:old_quarry_branch=742 m:yarborough_branch=818 m:howson_branch=279 m:hampton_branch_at_oak_hill=463 m:st_john_branch=923 m:ruiz_branch=1997 m:twin_oaks_branch=1186 m:little_walnut_creek_branch=1751 m:willie_mae_kirk_branch=338 m:north_village_branch=1203 m:faulk_central_library=6010 m:milwood_branch=662 m:carver_branch=915 m:cepeda_branch=764 m:terrazas_branch=616 m:pleasant_hill_branch=829 m:southeast_branch=792 m:university_hills_branch=756 m:manchaca_road_branch=1780
```

## Meta Commands

```ls
metric m:faulk_central_library p:integer l:"Faulk Central Library" t:dataTypeName=number

metric m:carver_branch p:integer l:"Carver Branch" t:dataTypeName=number

metric m:cepeda_branch p:integer l:"Cepeda Branch" t:dataTypeName=number

metric m:hampton_branch_at_oak_hill p:integer l:"Hampton Branch at Oak Hill" t:dataTypeName=number

metric m:howson_branch p:integer l:"Howson Branch" t:dataTypeName=number

metric m:little_walnut_creek_branch p:integer l:"Little Walnut Creek Branch" t:dataTypeName=number

metric m:milwood_branch p:integer l:"Milwood Branch" t:dataTypeName=number

metric m:manchaca_road_branch p:integer l:"Manchaca Road Branch" t:dataTypeName=number

metric m:north_village_branch p:integer l:"North Village Branch" t:dataTypeName=number

metric m:old_quarry_branch p:integer l:"Old Quarry Branch" t:dataTypeName=number

metric m:pleasant_hill_branch p:integer l:"Pleasant Hill Branch" t:dataTypeName=number

metric m:recycled_reads_bookstore p:integer l:"Recycled Reads Bookstore" t:dataTypeName=number

metric m:ruiz_branch p:integer l:"Ruiz Branch" t:dataTypeName=number

metric m:southeast_branch p:integer l:"Southeast Branch" t:dataTypeName=number

metric m:st_john_branch p:integer l:"St. John Branch" t:dataTypeName=number

metric m:spicewood_springs_branch p:integer l:"Spicewood Springs Branch" t:dataTypeName=number

metric m:terrazas_branch p:integer l:"Terrazas Branch" t:dataTypeName=number

metric m:twin_oaks_branch p:integer l:"Twin Oaks Branch" t:dataTypeName=number

metric m:university_hills_branch p:integer l:"University Hills Branch" t:dataTypeName=number

metric m:willie_mae_kirk_branch p:integer l:"Willie Mae Kirk Branch" t:dataTypeName=number

metric m:windsor_park_branch p:integer l:"Windsor Park Branch" t:dataTypeName=number

metric m:yarborough_branch p:integer l:"Yarborough Branch" t:dataTypeName=number

entity e:cr83-wy4q l:"Wireless Usage at Austin Public Library" t:attribution="Austin Public Library" t:url=https://data.austintexas.gov/api/views/cr83-wy4q

property e:cr83-wy4q t:meta.view v:id=cr83-wy4q v:category=Neighborhood v:averageRating=0 v:name="Wireless Usage at Austin Public Library" v:attribution="Austin Public Library"

property e:cr83-wy4q t:meta.view.license v:name="Public Domain"

property e:cr83-wy4q t:meta.view.owner v:id=knx5-5zd7 v:screenName=Sarah v:displayName=Sarah

property e:cr83-wy4q t:meta.view.tableauthor v:id=knx5-5zd7 v:screenName=Sarah v:roleName=editor_stories v:displayName=Sarah
```

## Top Records

```ls
| :updated_at | date   | faulk_central_library | carver_branch | cepeda_branch | hampton_branch_at_oak_hill | howson_branch | little_walnut_creek_branch | milwood_branch | manchaca_road_branch | north_village_branch | old_quarry_branch | pleasant_hill_branch | recycled_reads_bookstore | ruiz_branch | southeast_branch | st_john_branch | spicewood_springs_branch | terrazas_branch | twin_oaks_branch | university_hills_branch | willie_mae_kirk_branch | windsor_park_branch | yarborough_branch | notes | 
| =========== | ====== | ===================== | ============= | ============= | ========================== | ============= | ========================== | ============== | ==================== | ==================== | ================= | ==================== | ======================== | =========== | ================ | ============== | ======================== | =============== | ================ | ======================= | ====================== | =================== | ================= | ===== | 
| 1491248462  | Oct-14 | 6455                  | 1135          | 841           | 680                        | 510           | 1695                       | 956            | 1974                 | 1362                 | 1053              | 848                  | 1018                     | 2277        | 831              | 1020           | 1526                     | 757             | 1436             | 991                     | 415                    | 921                 | 1087              |       | 
| 1491248462  | Nov-14 | 7009                  | 1274          | 965           | 536                        | 427           | 2016                       | 804            | 2271                 | 1607                 | 928               | 1031                 | 1389                     | 2609        | 902              | 1059           | 1335                     | 719             | 1468             | 940                     | 449                    | 893                 | 936               |       | 
| 1491248462  | Dec-14 | 6010                  | 915           | 764           | 463                        | 279           | 1751                       | 662            | 1780                 | 1203                 | 742               | 829                  | 1152                     | 1997        | 792              | 923            | 1223                     | 616             | 1186             | 756                     | 338                    | 869                 | 818               |       | 
| 1491248462  | Jan-15 | 3949                  | 616           | 508           | 358                        | 196           | 1255                       | 348            | 1143                 | 706                  | 337               | 659                  | 773                      | 1521        | 478              | 580            | 808                      | 747             | 519              | 445                     | 265                    | 580                 | 553               |       | 
| 1491248462  | Feb-15 | 3735                  | 773           | 527           | 349                        | 351           | 1034                       | 42             | 1110                 | 873                  | 487               | 598                  | 743                      | 1378        | 548              | 581            | 1003                     | 399             | 997              | 352                     | 271                    | 508                 | 641               |       | 
| 1491248462  | Mar-15 | 4795                  | 736           | 481           | 391                        | 348           | 1226                       | 24             | 1224                 | 939                  | 495               | 734                  | 748                      | 1759        | 567              | 707            | 1101                     | 618             | 1039             | 472                     | 247                    | 654                 | 630               |       | 
| 1491248462  | Apr-15 | 4739                  | 714           | 479           | 386                        | 291           | 1076                       | 26             | 1208                 | 823                  | 578               | 770                  | 726                      | 1604        | 604              | 609            | 954                      | 532             | 959              | 490                     | 301                    | 552                 | 660               |       | 
| 1491248462  | May-15 | 4823                  | 676           | 471           | 314                        | 164           | 1013                       | 35             | 1158                 | 866                  | 554               | 692                  | 630                      | 1480        | 642              | 619            | 941                      | 617             | 914              | 467                     | 381                    | 541                 | 676               |       | 
| 1491248462  | Jun-15 | 4363                  | 628           | 521           | 307                        | 277           | 1126                       | 36             | 1151                 | 890                  | 635               | 570                  | 617                      | 1499        | 592              | 582            | 1119                     | 621             | 790              | 458                     | 441                    | 538                 | 678               |       | 
| 1491248462  | Jul-15 | 5303                  | 788           | 481           | 388                        | 256           | 1282                       | 33             | 1278                 | 998                  | 722               | 627                  | 277                      | 1741        | 597              | 734            | 1416                     | 590             | 1054             | 572                     | 439                    | 748                 | 796               |       | 
```