# HWP - Transporter

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hwp-transporter) |
| Metadata | [Link](https://data.mo.gov/api/views/9y27-beyb) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/9y27-beyb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/9y27-beyb/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 9y27-beyb |
| Name | HWP - Transporter |
| Attribution | Department of Natural Resources |
| Category | Natural Resources |
| Created | 2015-07-10T15:05:34Z |
| Publication Date | 2017-04-06T20:37:13Z |

## Description

HWP - Transporter

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | epa_id      | EPA_ID     | text      | text        |
| Yes      | series tag  | company     | COMPANY    | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
| Yes      | series tag  | expires     | EXPIRES    | text      | text        |
| Yes      | series tag  | tran_id     | US DOT #   | text      | text        |
| Yes      | series tag  | services    | Services   | text      | text        |
| Yes      | series tag  | mailcity    | MailCity   | text      | text        |
| Yes      | series tag  | state       | STATE      | text      | text        |
| Yes      | series tag  | mailzip     | ZIP        | text      | text        |
| Yes      | series tag  | website     | WEBSITE    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9y27-beyb d:2017-02-21T20:03:38.000Z t:services="1, B" t:phone=815-797-103 t:mailcity=SOMONAUK t:expires=5/11/17 t:website=PTSWORLDWIDE.NET t:company="PTS WORLDWIDE INC." t:epa_id=ILR000191270 t:mailzip=60552 t:state=IL t:tran_id=1835664 m:row_number.9y27-beyb=1

series e:9y27-beyb d:2017-02-21T20:03:38.000Z t:services="4, B" t:phone=509-923-0508 t:mailcity=METHOW t:expires=5/6/17 t:website=NORDANG@AMERION.COM t:company="ART NORDANG TRUCKING INC." t:epa_id=WAD980834782 t:mailzip=98834 t:state=WA t:tran_id=38491 m:row_number.9y27-beyb=2

series e:9y27-beyb d:2017-02-21T20:03:38.000Z t:services=UO t:phone="785 230-1647" t:mailcity=Topeka t:expires=7/12/17 t:website=www.eeusedoil.com t:company="Environmental Energy Inc." t:epa_id=KSR000508879 t:mailzip=66675 t:state=KS t:tran_id=1917289 m:row_number.9y27-beyb=3
```

## Meta Commands

```ls
metric m:row_number.9y27-beyb p:long l:"Row Number"

entity e:9y27-beyb l:"HWP - Transporter" t:attribution="Department of Natural Resources" t:url=https://data.mo.gov/api/views/9y27-beyb

property e:9y27-beyb t:meta.view v:id=9y27-beyb v:category="Natural Resources" v:attributionLink=http://dnr.mo.gov/env/hwp/ v:averageRating=0 v:name="HWP - Transporter" v:attribution="Department of Natural Resources"

property e:9y27-beyb t:meta.view.owner v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:displayName="Renee Wright"

property e:9y27-beyb t:meta.view.tableauthor v:id=wwxh-sgxy v:profileImageUrlMedium=/api/users/wwxh-sgxy/profile_images/THUMB v:profileImageUrlLarge=/api/users/wwxh-sgxy/profile_images/LARGE v:screenName="Renee Wright" v:profileImageUrlSmall=/api/users/wwxh-sgxy/profile_images/TINY v:roleName=editor v:displayName="Renee Wright"
```

## Top Records

```ls
| :updated_at | epa_id       | company                       | phone        | expires  | tran_id | services                       | mailcity     | state | mailzip | website                   | 
| =========== | ============ | ============================= | ============ | ======== | ======= | ============================== | ============ | ===== | ======= | ========================= | 
| 1487707418  | ILR000191270 | PTS WORLDWIDE INC.            | 815-797-103  | 5/11/17  | 1835664 | 1, B                           | SOMONAUK     | IL    | 60552   | PTSWORLDWIDE.NET          | 
| 1487707418  | WAD980834782 | ART NORDANG TRUCKING INC.     | 509-923-0508 | 5/6/17   | 38491   | 4, B                           | METHOW       | WA    | 98834   | NORDANG@AMERION.COM       | 
| 1487707418  | KSR000508879 | Environmental Energy Inc.     | 785 230-1647 | 7/12/17  | 1917289 | UO                             | Topeka       | KS    | 66675   | www.eeusedoil.com         | 
| 1487707418  | KSR000508879 | Environmental Energy Inc.     | 785 230-1647 | 7/12/17  | 1917289 | UO                             | Topeka       | KS    | 66675   | www.eeusedoil.com         | 
| 1487707418  | MOD981728504 | ENVIRONMENTAL WORKS, INC.     | 417-890-9500 | 7/1/17   | 933327  |                                |              |       |         |                           | 
| 1487707418  | ARR000026518 | UNION GAS WELL SERVICES LLC   | 501 589-2202 | 8/31/17  | 2146831 | B, UO                          | ALMA         | AR    | 72921   | uniongaswellservices.com  | 
| 1487707418  | ARR000026070 | RAMCO ENVIRONMENTAL LLC       | 501 269-2478 | 9/26/17  | 2335338 | 3, 8, B                        | ATLANTA      | GA    | 30325   | RAMCOENVIRO.COM           | 
| 1487707418  | NED986382133 | SMITH SYSTEMS TRANSPORTATION  | 308 632-5148 | 11/22/17 | 472690  | 1, 2, 3, 4, 5, 6, 8, 9, B, IW  | SCCOTTSBLUFF | NE    | 69363   | smithsystemsus.weebly.com | 
| 1487707418  | TXD988057931 | FLUID TRANSPORTS INC.         | 325 573-5421 | 8/31/17  | 462785  | 1, 7, 8, B, PCB                | SWEETWATER   | TX    | 79556   |                           | 
| 1487707418  | OKR000032466 | STAGECOACH TRANSPORTATION LLC | 918 424-5100 | 10/14/17 | 2872078 | 2, 3, 4, 5, 6, 8, 9, B, IW, UO | JENKS        | OK    | 74037   |                           | 
```