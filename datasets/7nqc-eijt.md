# Landmarks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/landmarks-43b38) |
| Metadata | [Link](https://data.seattle.gov/api/views/7nqc-eijt) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/7nqc-eijt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/7nqc-eijt/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 7nqc-eijt |
| Name | Landmarks |
| Attribution | Seattle Department of Neighborhoods |
| Category | Community |
| Tags | historic register, historic, landmarks, preservation, historic preservation |
| Created | 2011-12-20T18:57:32Z |
| Publication Date | 2011-12-21T19:27:24Z |

## Description

Seattle designated individual sites, buildings, vehicles, vessels, and street clocks as landmarks subject to protection by city ordinance.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | objectid   | OBJECTID   | text      | number      |
| Yes      | series tag     | name       | NAME       | text      | text        |
| No       |                | address    | ADDRESS    | text      | text        |
| Yes      | series tag     | orig_addre | ORIG_ADDRE | text      | text        |
| Yes      | series tag     | pin        | PIN        | text      | text        |
| Yes      | numeric metric | landno     | LANDNO     | number    | number      |
| Yes      | numeric metric | ordinance  | ORDINANCE  | number    | number      |
| Yes      | time           | eff_date   | EFF_DATE   | date      | date        |
| Yes      | series tag     | photo      | PHOTO      | text      | text        |
```

## Time Field

```ls
Value = eff_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:7nqc-eijt d:1988-05-31T00:00:00.000Z t:pin=1976200160 t:orig_addre="84 Union St" t:name="84 Union Building/U.S. Immigration Building" t:objectid=1 t:photo=USImmigrationBldg1DON.jpg m:ordinance=113990 m:landno=129

series e:7nqc-eijt d:1987-05-11T00:00:00.000Z t:pin=7666202480 t:orig_addre="1203-7 Western Ave" t:name="Olympic Warehouse and Cold Storage Building" t:objectid=2 t:photo=OlympicWarehouse1DON.jpg m:ordinance=113429 m:landno=134

series e:7nqc-eijt d:1978-07-17T00:00:00.000Z t:pin=0939000515 t:orig_addre="107 Spring St" t:name="Holyoke Building" t:objectid=3 t:photo=HolyokeBldg3DON.jpg m:ordinance=107521 m:landno=138
```

## Meta Commands

```ls
metric m:landno p:integer l:LANDNO d:LANDNO t:dataTypeName=number

metric m:ordinance p:integer l:ORDINANCE d:ORDINANCE t:dataTypeName=number

entity e:7nqc-eijt l:Landmarks t:attribution="Seattle Department of Neighborhoods" t:url=https://data.seattle.gov/api/views/7nqc-eijt

property e:7nqc-eijt t:meta.view v:id=7nqc-eijt v:category=Community v:attributionLink=http://seattle.gov/neighborhoods/preservation/landmarks.htm v:averageRating=0 v:name=Landmarks v:attribution="Seattle Department of Neighborhoods"

property e:7nqc-eijt t:meta.view.license v:name="Public Domain"

property e:7nqc-eijt t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:7nqc-eijt t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| objectid | name                                        | address          | orig_addre         | pin        | landno | ordinance | eff_date  | photo                       | 
| ======== | =========================================== | ================ | ================== | ========== | ====== | ========= | ========= | =========================== | 
| 1        | 84 Union Building/U.S. Immigration Building | 84 Union St      | 84 Union St        | 1976200160 | 129    | 113990    | 581040000 | USImmigrationBldg1DON.jpg   | 
| 2        | Olympic Warehouse and Cold Storage Building | 1205 Western Ave | 1203-7 Western Ave | 7666202480 | 134    | 113429    | 547689600 | OlympicWarehouse1DON.jpg    | 
| 3        | Holyoke Building                            | 107 Spring St    | 107 Spring St      | 0939000515 | 138    | 107521    | 269481600 | HolyokeBldg3DON.jpg         | 
| 4        | Exchange Building                           | 821 2nd Ave      | 821 2nd Ave        | 0939000335 | 148    | 115038    | 640224000 | Exchange1DON.jpg            | 
| 5        | Puget Sound Bank (Bank of California)       | 815 2nd Ave      | 815 2nd Ave        | 0939000345 | 149    | 113602    | 558057600 | BankofCABldg2DON.jpg        | 
| 6        | Colman Building                             | 810 1st Ave      | 801-821 1st Ave    | 8591400005 | 152    | 114993    | 637804800 | Colman3DON.jpg              | 
| 7        | St Nicholas Russian Orthodox Cathedral      | 1714 13th Ave    | 1714 13th Ave      | 6003000910 | 89     | 106098    | 219888000 | StNicholasCathedral2DON.jpg | 
| 8        | 1st African Methodist Episcopal Church      | 1522 14th Ave    | 1522 14th Ave      | 0222000010 | 94     | 111928    | 464832000 | FirstAfricanChurch6DON.jpg  | 
| 9        | Summit School/Northwest School              | 1415 Summit Ave  | 1415 Summit Ave    | 8804901000 | 96     | 114994    | 637804800 | SummitNWSchool1DON.jpg      | 
| 10       | Stimson/Green House                         | 1204 Minor Ave   | 1204 Minor Ave     | 1978200805 | 109    | 106068    | 251510400 | StimsonGreenMansion2DON.jpg | 
```