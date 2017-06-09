# DEPRECATED : King County Ballot Drop Boxes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/deprecated-king-county-ballot-drop-boxes-ea2c9) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/2dce-kiyy) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/2dce-kiyy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/2dce-kiyy/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 2dce-kiyy |
| Name | DEPRECATED : King County Ballot Drop Boxes |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | elections, king county, voting |
| Created | 2012-06-19T20:38:58Z |
| Publication Date | 2013-10-25T20:37:50Z |

## Description

GO HERE (08/2013): https://electionsdata.kingcounty.gov/dataset/Master-KC-Ballot-Drop-Box-Dataset/k59d-q4u8

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | ballot_drop_box        | Ballot drop box        | text      | text        |
| Yes      | series tag  | in_use                 | In use                 | checkbox  | checkbox    |
| Yes      | series tag  | box_city               | Box city               | text      | text        |
| No       |             | bdb_address            | Address                | text      | text        |
| Yes      | series tag  | box_zip_code           | Box Zip Code           | text      | text        |
| Yes      | series tag  | description            | Description            | text      | text        |
| Yes      | series tag  | photo2                 | Photo                  | photo     | photo       |
| Yes      | series tag  | dates_open             | Dates Open             | text      | text        |
| Yes      | series tag  | hours                  | Hours                  | text      | text        |
| Yes      | series tag  | election_day_hours     | Election Day Hours     | text      | text        |
| Yes      | series tag  | chinese                | Chinese                | text      | text        |
| Yes      | series tag  | chinese_description    | Chinese description    | text      | text        |
| Yes      | series tag  | vietnamese             | Vietnamese             | text      | text        |
| Yes      | series tag  | vietnamese_description | Vietnamese description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = bdb_address
```

## Data Commands

```ls
series e:2dce-kiyy d:2013-10-25T10:06:51.000Z t:box_city=Burien t:election_day_hours="Close at 8 pm" t:ballot_drop_box="Burien City Hall" t:box_zip_code=98166 t:hours="24 hours" t:in_use=true t:vietnamese="Hội Trường Thành Phố Burien" t:photo2=EqLUSLZASNzMiwp4OUmu-ftPzpdbDS4RXXXvpT9-_Fs t:dates_open="Oct 17-Nov 5" t:chinese=布萊恩市政廳 m:row_number.2dce-kiyy=1

series e:2dce-kiyy d:2013-10-25T10:14:21.000Z t:box_city="Maple Valley" t:election_day_hours="Close at 8 pm" t:ballot_drop_box="Van: Tahoma School District  Building" t:box_zip_code=98038 t:hours="10 a.m. to 5 p.m." t:in_use=true t:vietnamese="Trường Học Khu Vực Tahoma" t:photo2=gm70_AWlmwWjTDPliJ1Ue5OgjN76P9LklA2jyXyenTQ t:dates_open="Nov 2, 4, 5" t:chinese=塔何瑪（Tahoma）校區辦公室 m:row_number.2dce-kiyy=2

series e:2dce-kiyy d:2013-10-25T10:14:42.000Z t:box_city=Seattle t:election_day_hours="10 a.m. to 8 p.m." t:ballot_drop_box="Van: University of Washington Campus" t:box_zip_code=98105 t:description="Red Square; no parking or vehicle access available" t:hours="10 a.m. to 5 p.m." t:in_use=true t:vietnamese="Khu Trường Học Đại Học Washington" t:photo2=HYkBnnUKNm4ZkyvVMW4r_209ssAIFrSMJyPGau_Nfgs t:dates_open="Nov 2, 4, 5" t:chinese=華盛頓大學校園 m:row_number.2dce-kiyy=3
```

## Meta Commands

```ls
metric m:row_number.2dce-kiyy p:long l:"Row Number"

entity e:2dce-kiyy l:"DEPRECATED : King County Ballot Drop Boxes" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/2dce-kiyy

property e:2dce-kiyy t:meta.view d:2017-06-09T13:53:56.015Z v:id=2dce-kiyy v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="DEPRECATED : King County Ballot Drop Boxes" v:attribution="King County Elections"

property e:2dce-kiyy t:meta.view.license d:2017-06-09T13:53:56.015Z v:name="Public Domain"

property e:2dce-kiyy t:meta.view.owner d:2017-06-09T13:53:56.015Z v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:2dce-kiyy t:meta.view.tableauthor d:2017-06-09T13:53:56.015Z v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| :updated_at | ballot_drop_box                      | in_use | box_city         | bdb_address                            | box_zip_code | description                                        | photo2                                      | dates_open   | hours             | election_day_hours | chinese                   | chinese_description | vietnamese                            | vietnamese_description | 
| =========== | ==================================== | ====== | ================ | ====================================== | ============ | ================================================== | =========================================== | ============ | ================= | ================== | ========================= | =================== | ===================================== | ====================== | 
| 1382695611  | Burien City Hall                     | true   | Burien           | 400 SW 152nd Street                    | 98166        |                                                    | EqLUSLZASNzMiwp4OUmu-ftPzpdbDS4RXXXvpT9-_Fs | Oct 17-Nov 5 | 24 hours          | Close at 8 pm      | 布萊恩市政廳                    |                     | Hội Trường Thành Phố Burien           |                        | 
| 1382696061  | Van: Tahoma School District Building | true   | Maple Valley     | 25720 Maple Valley-Black Diamond Rd SE | 98038        |                                                    | gm70_AWlmwWjTDPliJ1Ue5OgjN76P9LklA2jyXyenTQ | Nov 2, 4, 5  | 10 a.m. to 5 p.m. | Close at 8 pm      | 塔何瑪（Tahoma）校區辦公室          |                     | Trường Học Khu Vực Tahoma             |                        | 
| 1382696082  | Van: University of Washington Campus | true   | Seattle          | 4000 15th Ave NE                       | 98105        | Red Square; no parking or vehicle access available | HYkBnnUKNm4ZkyvVMW4r_209ssAIFrSMJyPGau_Nfgs | Nov 2, 4, 5  | 10 a.m. to 5 p.m. | 10 a.m. to 8 p.m.  | 華盛頓大學校園                   |                     | Khu Trường Học Đại Học Washington     |                        | 
| 1382695584  | Ballard Branch Library               | true   | Seattle          | 5614 22nd Ave NW                       | 98107        |                                                    | FQfTFom6I0RhMyo888DkGX5sPeoi30KzLmZvf2vcmnw | Oct 17-Nov 5 | 24 hours          | Close at 8 pm      | 巴雷（Ballard）分區圖書館          |                     | Thư Viện Chi Nhánh Ballard            |                        | 
| 1382695635  | Crossroads Shopping Center           | true   | Bellevue         | 15600 NE 8th Street                    | 98008        | South entrance                                     | Qw_1ehgWu5UBRY36lY0d5CdPz9TZovk_6ERxei7obVw | Oct 17-Nov 5 | 24 hours          | Close at 8 pm      | Crossroads購物中心            | 南面入口                | Trung tâm mua sắm Crossroads          | Lối vào hướng Nam      | 
| 1382695652  | Federal Way City Hall                | true   | Federal Way      | 33325 8th Avenue South                 | 98003        |                                                    | HQ67QntEsBHKJ5R_NIuNFF8t3fqDTea5ugLlA96omFU | Oct 17-Nov 5 | 24 hours          | Close at 8 pm      | 費多威（Federal Way）市政廳       |                     | Hội trường thành phố Federal Way      |                        | 
| 1382695670  | Issaquah City Hall                   | true   | Issaquah         | 130 East Sunset Way                    | 98027        |                                                    | g_HtytZlJotaLHe4zGpMTnSiVYaWPd_ikuYIgE4d9Bg | Oct 17-Nov 5 | 24 hours          | Close at 8 pm      | 伊薩夸（Issaquah）市政廳          |                     | Hội trường thành phố Issaquah         |                        | 
| 1382695713  | King County Elections                | true   | Renton           | 919 SW Grady Way                       | 98057        |                                                    | hsbd3KdcaWGNzn31HZW9vujA7yIITP1JwoODN8D5jqc | Oct 17-Nov 5 | 24 hours          | Close at 8 pm      | 金郡選舉部                     |                     | Hội đồng bầu cử quận King             |                        | 
| 1382695761  | Lake Forest Park City Hall           | true   | Lake Forest Park | 17425 Ballinger Way NE                 | 98155        |                                                    | 03xg14KR9GuoQ2-bcViVXlPVMdxwp8qkjALQKQ6LpDY | Oct 17-Nov 5 | 24 hours          | Close at 8 pm      | 湖林公園（Lake Forest Park）市政廳 |                     | Hội Trường Thành Phố Lake Forest Park |                        | 
| 1382695782  | Redmond City Hall                    | true   | Redmond          | 15670 NE 85th Street                   | 98052        |                                                    | -NqWo41KHWvguQSLi2IrSRX3kzX5tqa4gMxFrRosrmk | Oct 17-Nov 5 | 24 hours          | Close at 8 pm      | 雷德蒙（Redmond）市政廳           |                     | Hội Trường Thành Phố Redmond          |                        | 
```