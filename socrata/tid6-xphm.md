# Quitline ? Quitline Names and Phone Numbers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quitline-a-quitline-names-and-phone-numbers-42790) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/tid6-xphm) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/tid6-xphm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/tid6-xphm/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | tid6-xphm |
| Name | Quitline ? Quitline Names and Phone Numbers |
| Category | Quitline |
| Tags | osh, office on smoking and health, nqdw, state system, national quitline data warehouse, quitline, quit, callers, services, cessation, intervention, quit-now |
| Created | 2014-11-06T12:21:54Z |
| Publication Date | 2017-04-13T15:23:43Z |

## Description

2010-2016.  National Quitline Data Warehouse (NQDW). State Tobacco Activities Tracking and Evaluation (STATE) System.  NQDW Data.  National Quitline Data Warehouse (NQDW) assists in evaluating quitline activities and serves as a national resource for data on the use, success, and services of state quitlines.  States report data on quitline callers, quitting success, as well as the services provided by their quitlines. The NQDW consolidates this information for evaluating programs and improving quitline services.  The jurisdictions participating in this data collection effort include the 50 states, the District of Columbia, Guam and Puerto Rico.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | locationabbr    | LocationAbbr    | text      | text        |
| Yes      | series tag  | locationdesc    | LocationDesc    | text      | text        |
| Yes      | series tag  | quitline_name   | Quitline_Name   | text      | text        |
| Yes      | series tag  | quitline_phone1 | QuitLine_Phone1 | text      | text        |
| Yes      | series tag  | quitline_phone2 | Quitline_Phone2 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tid6-xphm d:2017-04-06T14:13:24.000Z t:locationdesc=Alaska t:locationabbr=AK t:quitline_phone1="1-800-QUIT-NOW (1-800-784-8669)" t:quitline_name="Alaska's Tobacco Quitline" m:row_number.tid6-xphm=1

series e:tid6-xphm d:2017-04-06T14:13:24.000Z t:locationdesc=Alabama t:locationabbr=AL t:quitline_phone1="1-800-QUIT-NOW (1-800-784-8669)" t:quitline_name="Quit Now Alabama" m:row_number.tid6-xphm=2

series e:tid6-xphm d:2017-04-06T14:13:24.000Z t:locationdesc=Arkansas t:locationabbr=AR t:quitline_phone2="1-866-NOW-QUIT (1-866-669-7848)" t:quitline_phone1="1-800-QUIT-NOW (1-800-784-8669)" t:quitline_name="Arkansas Tobacco Quitline" m:row_number.tid6-xphm=3
```

## Meta Commands

```ls
metric m:row_number.tid6-xphm p:long l:"Row Number"

entity e:tid6-xphm l:"Quitline ? Quitline Names and Phone Numbers" t:url=https://chronicdata.cdc.gov/api/views/tid6-xphm

property e:tid6-xphm t:meta.view v:id=tid6-xphm v:category=Quitline v:attributionLink=http://www.cdc.gov/tobacco/quit_smoking/cessation/nqdw/index.htm v:averageRating=0 v:name="Quitline ? Quitline Names and Phone Numbers"

property e:tid6-xphm t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:tid6-xphm t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:tid6-xphm t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| :updated_at | locationabbr | locationdesc         | quitline_name                 | quitline_phone1                  | quitline_phone2                  | 
| =========== | ============ | ==================== | ============================= | ================================ | ================================ | 
| 1491488004  | AK           | Alaska               | Alaska's Tobacco Quitline     | 1-800-QUIT-NOW (1-800-784-8669)  |                                  | 
| 1491488004  | AL           | Alabama              | Quit Now Alabama              | 1-800-QUIT-NOW (1-800-784-8669)  |                                  | 
| 1491488004  | AR           | Arkansas             | Arkansas Tobacco Quitline     | 1-800-QUIT-NOW (1-800-784-8669)  | 1-866-NOW-QUIT (1-866-669-7848)  | 
| 1491488004  | AZ           | Arizona              | Arizona Smokers' Helpline     | 1-800-556-6222                   |                                  | 
| 1491488004  | CA           | California           | California Smokers' Helpline  | 1-800-NO-BUTTS (1-800-662-8887)  | 1-800-456-6386                   | 
| 1491488004  | CO           | Colorado             | Colorado QuitLine             | 1-800-QUIT-NOW (1-800-784-8669)  | 1-855-D?JELO-YA (1-855-335-3569) | 
| 1491488004  | CT           | Connecticut          | Connecticut Quitline          | 1-800-QUIT-NOW (1-800-784-8669)  | 1-855-D?JELO-YA (1-855-335-3569) | 
| 1491488004  | DC           | District of Columbia | District of Columbia Quitline | 1-800-QUIT-NOW (1-800-784-8669)  |                                  | 
| 1491488004  | DE           | Delaware             | Delaware Quitline             | 1-866-409-1858                   | 1-788-709-5783                   | 
| 1491488004  | FL           | Florida              | Florida Quitline              | 1-877-U-CAN-NOW (1-877-822-6669) |                                  | 
```