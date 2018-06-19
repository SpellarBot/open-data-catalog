# Registered Motor Vehicle Service Contract Companies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-motor-vehicle-service-contract-companies) |
| Metadata | [Link](https://data.iowa.gov/api/views/j78q-bdp3) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/j78q-bdp3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/j78q-bdp3/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | j78q-bdp3 |
| Name | Registered Motor Vehicle Service Contract Companies |
| Attribution | Iowa Insurance Division |
| Category | Economy |
| Tags | motor vehicle, service contract |
| Created | 2015-07-02T20:10:35Z |
| Publication Date | 2016-12-07T16:43:23Z |

## Description

This dataset contains a listing of the companies registered to offer motor vehicle service contracts in Iowa.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | numeric metric | tracking         | TRACKING         | number    | number      |
| Yes      | series tag     | company_name     | COMPANY NAME     | text      | text        |
| No       |                | mailing_address1 | MAILING ADDRESS1 | text      | text        |
| No       |                | mailing_address2 | MAILING ADDRESS2 | text      | text        |
| No       |                | mailing_address3 | MAILING ADDRESS3 | text      | text        |
| Yes      | series tag     | mailing_city     | MAILING CITY     | text      | text        |
| Yes      | series tag     | mailing_state    | MAILING STATE    | text      | text        |
| Yes      | series tag     | mailing_zip      | MAILING ZIP      | text      | number      |
| Yes      | series tag     | business_phone   | BUSINESS PHONE   | phone     | phone       |
| Yes      | series tag     | business_email   | BUSINESS EMAIL   | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailing_address1,mailing_address2,mailing_address3
```

## Data Commands

```ls
series e:j78q-bdp3 d:2015-07-03T04:32:05.000Z t:phone_number=800-747-4400 t:mailing_zip=66201 t:company_name="MPP COMPANY, INC." t:business_email=glamb@vtaig.com t:mailing_state=KS t:mailing_city=MERRIAM m:tracking=127886

series e:j78q-bdp3 d:2015-07-03T04:32:05.000Z t:phone_number=870-425-8330 t:mailing_zip=72653 t:company_name="AUTO SERVICES COMPANY, INC." t:business_email=debbie.smith@ascwarranty.com t:mailing_state=AR t:mailing_city="MOUNTAIN HOME" m:tracking=127838

series e:j78q-bdp3 d:2015-07-03T04:32:05.000Z t:phone_number=678-258-8084 t:mailing_zip=76021 t:company_name="AMT Warranty Corp." t:business_email=kristen.sampson@amtrustgroup.com t:mailing_state=TX t:mailing_city=BEDFORD m:tracking=127818
```

## Meta Commands

```ls
metric m:tracking p:integer l:TRACKING t:dataTypeName=number

entity e:j78q-bdp3 l:"Registered Motor Vehicle Service Contract Companies" t:attribution="Iowa Insurance Division" t:url=https://data.iowa.gov/api/views/j78q-bdp3

property e:j78q-bdp3 t:meta.view v:id=j78q-bdp3 v:category=Economy v:averageRating=0 v:name="Registered Motor Vehicle Service Contract Companies" v:attribution="Iowa Insurance Division"

property e:j78q-bdp3 t:meta.view.license v:name="Public Domain"

property e:j78q-bdp3 t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:j78q-bdp3 t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| :updated_at | tracking | company_name                              | mailing_address1                  | mailing_address2 | mailing_address3 | mailing_city      | mailing_state | mailing_zip | business_phone       | business_email                    | 
| =========== | ======== | ========================================= | ================================= | ================ | ================ | ================= | ============= | =========== | ==================== | ================================= | 
| 1435897925  | 127886   | MPP COMPANY, INC.                         | P.O. Box 634                      |                  |                  | MERRIAM           | KS            | 66201       | [800-747-4400, null] | glamb@vtaig.com                   | 
| 1435897925  | 127838   | AUTO SERVICES COMPANY, INC.               | PO BOX 72654                      |                  |                  | MOUNTAIN HOME     | AR            | 72653       | [870-425-8330, null] | debbie.smith@ascwarranty.com      | 
| 1435897925  | 127818   | AMT Warranty Corp.                        | 2200 HIGHWAY 121 SUITE 100        |                  |                  | BEDFORD           | TX            | 76021       | [678-258-8084, null] | kristen.sampson@amtrustgroup.com  | 
| 1435897925  | 130182   | AMERICAN AUTO GUARDIAN INC                | PO BOX 925                        |                  |                  | ARLINGTON HEIGHTS | IL            | 60006       | [888-442-2886, null] | compliance@aagi.com               | 
| 1435897925  | 127918   | American Heritage Insurance Services      | 1776 American Heritage Life Drive |                  |                  | Jacksonville      | FL            | 32224       | [904-992-3106, null] | ofeliali.brevaldo@allstate.com    | 
| 1435897925  | 127798   | American Auto Shield, LLC                 | 5695 YUKON STREET                 |                  |                  | ARVADA            | CO            | 80002       | [303-420-7488, null] | r.garfield@americanautoshield.com | 
| 1435897925  | 130307   | Advantage Plus, Inc.                      | 3401 West 41st Street             |                  |                  | Sioux Falls       | SD            | 57105       | [713-580-3169, null] | gsfslegal@gsfsgroup.com           | 
| 1435897925  | 127875   | AMERICAN GUARDIAN WARRANTY SERVICES, INC. | 4450 WEAVER PARKWAY               | SUITE 200        |                  | WARRENVILLE       | IL            | 60555       | [630-534-4114, null] | SPolanco@agwarranty.com           | 
| 1435897926  | 127871   | A.U.L. CORPORATION                        | 1250 Main Street                  | STE. 300         |                  | NAPA              | CA            | 94559       | [800-826-3207, null] | geagerton@aulcorp.com             | 
| 1435897926  | 127811   | 3M COMPANY INC                            | 3M CENTER, BLDG 223-6N-01         |                  |                  | ST. PAUL          | MN            | 55144       | [651-737-9574, null] | jphanbury@mmm.com                 | 
```