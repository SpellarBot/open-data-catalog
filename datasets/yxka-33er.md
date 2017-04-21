# DEA_MovieTheater

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dea-movietheater-384e4) |
| Metadata | [Link](https://data.seattle.gov/api/views/yxka-33er) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/yxka-33er/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/yxka-33er/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | yxka-33er |
| Name | DEA_MovieTheater |
| Attribution | Seattle Public Utilities GIS Program |
| Category | Community |
| Tags | movie, theater |
| Created | 2011-12-20T18:54:08Z |
| Publication Date | 2011-12-21T19:29:00Z |

## Description

Movie theaters in Seattle

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag  | objectid                  | OBJECTID                  | text      | number      |
| Yes      | series tag  | buslic_id                 | BUSLIC_ID                 | text      | number      |
| Yes      | series tag  | buslic_location_id        | BUSLIC_LOCATION_ID        | text      | number      |
| Yes      | series tag  | buslic_year_num           | BUSLIC_YEAR_NUM           | text      | number      |
| Yes      | time        | buslic_expiration_date    | BUSLIC_EXPIRATION_DATE    | date      | date        |
| Yes      | series tag  | buslic_legal_name         | BUSLIC_LEGAL_NAME         | text      | text        |
| Yes      | series tag  | buslic_trade_name         | BUSLIC_TRADE_NAME         | text      | text        |
| Yes      | series tag  | buslic_location_type      | BUSLIC_LOCATION_TYPE      | text      | text        |
| Yes      | series tag  | buslic_status_type        | BUSLIC_STATUS_TYPE        | text      | text        |
| Yes      | series tag  | buslic_contact_name       | BUSLIC_CONTACT_NAME       | text      | text        |
| Yes      | series tag  | buslic_phone_num          | BUSLIC_PHONE_NUM          | text      | text        |
| Yes      | series tag  | buslic_sic_code           | BUSLIC_SIC_CODE           | text      | number      |
| Yes      | series tag  | buslic_sic_desc           | BUSLIC_SIC_DESC           | text      | text        |
| Yes      | series tag  | buslic_naics_code         | BUSLIC_NAICS_CODE         | text      | text        |
| Yes      | series tag  | buslic_naics_desc         | BUSLIC_NAICS_DESC         | text      | text        |
| Yes      | series tag  | buslic_location_adrs_text | BUSLIC_LOCATION_ADRS_TEXT | text      | text        |
| Yes      | series tag  | buslic_dap_id             | BUSLIC_DAP_ID             | text      | number      |
| Yes      | series tag  | buslic_maf_id             | BUSLIC_MAF_ID             | text      | number      |
| Yes      | series tag  | buslic_cpn_id             | BUSLIC_CPN_ID             | text      | number      |
| Yes      | series tag  | buslic_snd_id             | BUSLIC_SND_ID             | text      | number      |
| Yes      | series tag  | buslic_mail_adrs_text     | BUSLIC_MAIL_ADRS_TEXT     | text      | text        |
| Yes      | series tag  | buslic_mailing_dap_id     | BUSLIC_MAILING_DAP_ID     | text      | number      |
| Yes      | series tag  | buslic_mailing_maf_id     | BUSLIC_MAILING_MAF_ID     | text      | number      |
| Yes      | series tag  | buslic_mailing_cpn_id     | BUSLIC_MAILING_CPN_ID     | text      | number      |
| Yes      | series tag  | buslic_mailing_snd_id     | BUSLIC_MAILING_SND_ID     | text      | number      |
| Yes      | series tag  | buslic_symbol_num         | BUSLIC_SYMBOL_NUM         | text      | number      |
| Yes      | series tag  | buslic_prkstall_num       | BUSLIC_PRKSTALL_NUM       | text      | number      |
| Yes      | series tag  | buslic_pubprk_flag        | BUSLIC_PUBPRK_FLAG        | text      | text        |
| No       |             | buslic_opendate           | BUSLIC_OPENDATE           | text      | text        |
```

## Time Field

```ls
Value = buslic_expiration_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = buslic_opendate
```

## Data Commands

```ls
series e:yxka-33er d:2017-12-31T00:00:00.000Z t:buslic_mail_adrs_text="11500 ASH ST, LEAWOOD, KS 66211-7804" t:buslic_id=482162 t:buslic_sic_code=7832 t:buslic_status_type=ACTIVE t:buslic_phone_num=9132132406 t:buslic_cpn_id=0 t:buslic_symbol_num=70 t:buslic_prkstall_num=0 t:buslic_naics_desc="MOTION PICTURE THEATERS (EXCEPT DRIVE-INS)" t:buslic_sic_desc="MOTION PICTURE THEATERS, EXCEPT DRIVE-IN" t:buslic_legal_name="AMERICAN MULTI CINEMA INC" t:buslic_location_type="HEADER QUARTER" t:buslic_year_num=2017 t:buslic_location_id=557559 t:buslic_maf_id=135055 t:buslic_naics_code=512131 t:buslic_contact_name="PHILLIP SINGLETON" t:buslic_location_adrs_text="600 PINE ST #400, SEATTLE, WA 98101" t:buslic_trade_name="AMC THEATRES PACIFIC PLACE II" t:buslic_pubprk_flag=N t:buslic_dap_id=140643 t:objectid=1 t:buslic_snd_id=25770 m:row_number.yxka-33er=1

series e:yxka-33er d:2017-12-31T00:00:00.000Z t:buslic_mail_adrs_text="220   2ND AVE S # STE 102, SEATTLE, WA 98104-2222" t:buslic_id=634043 t:buslic_sic_code=7832 t:buslic_status_type=ACTIVE t:buslic_phone_num=2069051026 t:buslic_symbol_num=70 t:buslic_prkstall_num=0 t:buslic_naics_desc="MOTION PICTURE THEATERS (EXCEPT DRIVE-INS)" t:buslic_sic_desc="MOTION PICTURE THEATERS, EXCEPT DRIVE-IN" t:buslic_legal_name="SEATTLE ASIAN AMERICAN FILM FESTIVAL" t:buslic_location_type="HEADER QUARTER" t:buslic_year_num=2017 t:buslic_location_id=667279 t:buslic_maf_id=144018 t:buslic_naics_code=512131 t:buslic_contact_name="KEVIN BANG" t:buslic_location_adrs_text="220   2ND AVE S # STE 102, SEATTLE, WA 98104-2222" t:buslic_trade_name="SEATTLE ASIAN AMERICAN FILM FESTIVAL" t:buslic_pubprk_flag=N t:buslic_dap_id=148879 t:objectid=2 t:buslic_snd_id=46838 m:row_number.yxka-33er=2

series e:yxka-33er d:2017-12-31T00:00:00.000Z t:buslic_mail_adrs_text="4739 UNIVERSITY WAY NE #1330, SEATTLE, WA 98105" t:buslic_id=510176 t:buslic_sic_code=7832 t:buslic_status_type=ACTIVE t:buslic_phone_num=2065259685 t:buslic_cpn_id=0 t:buslic_symbol_num=70 t:buslic_prkstall_num=0 t:buslic_naics_desc="MOTION PICTURE THEATERS (EXCEPT DRIVE-INS)" t:buslic_sic_desc="MOTION PICTURE THEATERS, EXCEPT DRIVE-IN" t:buslic_legal_name="THE GRAND ILLUSION CINEMA" t:buslic_location_type="HEADER QUARTER" t:buslic_year_num=2017 t:buslic_location_id=577097 t:buslic_maf_id=85587 t:buslic_naics_code=512131 t:buslic_contact_name="KATE BARR" t:buslic_location_adrs_text="1403 NE 50TH ST, SEATTLE, WA 98105" t:buslic_trade_name="THE GRAND ILLUSION CINEMA" t:buslic_pubprk_flag=N t:buslic_dap_id=93249 t:objectid=3 t:buslic_snd_id=13361 m:row_number.yxka-33er=3
```

## Meta Commands

```ls
metric m:row_number.yxka-33er p:long l:"Row Number"

entity e:yxka-33er l:DEA_MovieTheater t:attribution="Seattle Public Utilities GIS Program" t:url=https://data.seattle.gov/api/views/yxka-33er

property e:yxka-33er t:meta.view v:id=yxka-33er v:category=Community v:averageRating=0 v:name=DEA_MovieTheater v:attribution="Seattle Public Utilities GIS Program"

property e:yxka-33er t:meta.view.license v:name="Public Domain"

property e:yxka-33er t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:yxka-33er t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid | buslic_id | buslic_location_id | buslic_year_num | buslic_expiration_date | buslic_legal_name                    | buslic_trade_name                    | buslic_location_type | buslic_status_type | buslic_contact_name | buslic_phone_num | buslic_sic_code | buslic_sic_desc                          | buslic_naics_code | buslic_naics_desc                          | buslic_location_adrs_text                       | buslic_dap_id | buslic_maf_id | buslic_cpn_id | buslic_snd_id | buslic_mail_adrs_text                           | buslic_mailing_dap_id | buslic_mailing_maf_id | buslic_mailing_cpn_id | buslic_mailing_snd_id | buslic_symbol_num | buslic_prkstall_num | buslic_pubprk_flag | buslic_opendate | 
| ======== | ========= | ================== | =============== | ====================== | ==================================== | ==================================== | ==================== | ================== | =================== | ================ | =============== | ======================================== | ================= | ========================================== | =============================================== | ============= | ============= | ============= | ============= | =============================================== | ===================== | ===================== | ===================== | ===================== | ================= | =================== | ================== | =============== | 
| 1        | 482162    | 557559             | 2017            | 1514678400             | AMERICAN MULTI CINEMA INC            | AMC THEATRES PACIFIC PLACE II        | HEADER QUARTER       | ACTIVE             | PHILLIP SINGLETON   | 9132132406       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 600 PINE ST #400, SEATTLE, WA 98101             | 140643        | 135055        | 0             | 25770         | 11500 ASH ST, LEAWOOD, KS 66211-7804            |                       |                       |                       |                       | 70                | 0                   | N                  | 04/01/2002      | 
| 2        | 634043    | 667279             | 2017            | 1514678400             | SEATTLE ASIAN AMERICAN FILM FESTIVAL | SEATTLE ASIAN AMERICAN FILM FESTIVAL | HEADER QUARTER       | ACTIVE             | KEVIN BANG          | 2069051026       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 220 2ND AVE S # STE 102, SEATTLE, WA 98104-2222 | 148879        | 144018        |               | 46838         | 220 2ND AVE S # STE 102, SEATTLE, WA 98104-2222 |                       |                       |                       |                       | 70                | 0                   | N                  | 01/01/2013      | 
| 3        | 510176    | 577097             | 2017            | 1514678400             | THE GRAND ILLUSION CINEMA            | THE GRAND ILLUSION CINEMA            | HEADER QUARTER       | ACTIVE             | KATE BARR           | 2065259685       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 1403 NE 50TH ST, SEATTLE, WA 98105              | 93249         | 85587         | 0             | 13361         | 4739 UNIVERSITY WAY NE #1330, SEATTLE, WA 98105 |                       |                       |                       |                       | 70                | 0                   | N                  | 04/01/2004      | 
| 4        | 482162    | 557559             | 2017            | 1514678400             | AMERICAN MULTI CINEMA INC            | AMC THEATRES PACIFIC PLACE II        | HEADER QUARTER       | ACTIVE             | PHILLIP SINGLETON   | 9132132000       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 600 PINE ST #400, SEATTLE, WA 98101             | 140643        | 135055        | 0             | 25770         | 11500 ASH ST, LEAWOOD, KS 66211-7804            |                       |                       |                       |                       | 70                | 0                   | N                  | 04/01/2002      | 
| 5        | 549362    | 606566             | 2017            | 1514678400             | AMERICAN MULTI CINEMA INC            | AMC THEATRES OAK TREE 6              | BRANCH               | ACTIVE             | PHILLIP SINGLETON   | 9132132000       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 10006 AURORA AVE N, SEATTLE, WA 98133           | 49653         | 438753        | 0             | 4908          | 11500 ASH ST, LEAWOOD, KS 66211-7804            |                       |                       |                       |                       | 70                | 0                   | N                  | 05/31/2007      | 
| 6        | 576192    | 626134             | 2017            | 1514678400             | REGAL CINEMAS INC                    | REGAL THORNTON PLACE STADIUM 14      | BRANCH               | ACTIVE             | PETER BRANDOW       | 2065179943       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 301 NE 103RD ST, SEATTLE, WA 98125              | 605811        | 42654         |               | 47957         | 7132 REGAL LN, KNOXVILLE, TN 37918-5803         |                       |                       |                       |                       | 70                | 0                   | N                  | 05/22/2009      | 
| 7        | 539805    | 599177             | 2017            | 1514678400             | REGAL CINEMAS INC                    | MERIDIAN 16                          | HEADER QUARTER       | ACTIVE             | PETER BRANDOW       | 8659259630       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 1501 7TH AVE, SEATTLE, WA 98101                 | 140669        | 238774        | 0             | 25799         | 7132 REGAL LN, KNOXVILLE, TN 37918-5803         |                       |                       |                       |                       | 70                | 0                   | N                  | 09/20/2006      | 
| 8        | 619751    | 657138             | 2017            | 1514678400             | SUNDANCE CINEMAS LLC                 | SUNDANCE CINEMAS SEATTLE             | HEADER QUARTER       | ACTIVE             | PAUL RICHARDSON     | 9132132000       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 4500 9TH AVE NE # 100, SEATTLE, WA 98105-4762   | 93429         | 85815         |               | 13574         | 11500 ASH ST, LEAWOOD, KS 66211-7804            |                       |                       |                       |                       | 70                | 0                   | N                  | 05/15/2012      | 
| 9        | 549362    | 606566             | 2017            | 1514678400             | AMERICAN MULTI CINEMA INC            | AMC THEATRES OAK TREE 6              | BRANCH               | ACTIVE             | PHILLIP SINGLETON   | 9132132406       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 10006 AURORA AVE N, SEATTLE, WA 98133           | 49653         | 438753        | 0             | 4908          | 11500 ASH ST, LEAWOOD, KS 66211-7804            |                       |                       |                       |                       | 70                | 0                   | N                  | 05/31/2007      | 
| 10       | 470486    | 549335             | 2017            | 1514678400             | SILVER CINEMAS ACQUISITION CO        | GUILD 45TH                           | HEADER QUARTER       | ACTIVE             | PAUL RICHARDSON     | 9725039851       | 7832            | MOTION PICTURE THEATERS, EXCEPT DRIVE-IN | 512131            | MOTION PICTURE THEATERS (EXCEPT DRIVE-INS) | 2115 N 45TH ST, SEATTLE, WA 98103               | 99452         | 91824         |               | 10621         | 2222 S BARRINGTON AVE, LOS ANGELES, CA 90064    |                       |                       |                       |                       | 70                | 0                   | N                  | 06/01/2001      | 
```