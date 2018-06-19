# Registered Motor Vehicle Service Contract Providers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-motor-vehicle-service-contract-providers) |
| Metadata | [Link](https://data.iowa.gov/api/views/hbfc-v9c2) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/hbfc-v9c2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/hbfc-v9c2/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | hbfc-v9c2 |
| Name | Registered Motor Vehicle Service Contract Providers |
| Attribution | Iowa Insurance Division |
| Category | Economy |
| Tags | licensed, motor vehicle, service contract |
| Created | 2015-07-02T19:54:25Z |
| Publication Date | 2015-08-06T14:42:46Z |

## Description

This dataset contains a listing of providers registered to sell motor vehicle service contracts in Iowa.

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
series e:hbfc-v9c2 d:2015-07-03T04:31:49.000Z t:phone_number=641-932-5172 t:mailing_zip=52531 t:company_name="DUEA MOTOR COMPANY" t:business_email=ANNFRAN24@HOTMAIL.COM t:mailing_state=IA t:mailing_city=ALBIA m:tracking=127177

series e:hbfc-v9c2 d:2015-07-03T04:31:39.000Z t:phone_number=563-547-2401 t:mailing_zip=52136 t:company_name="H & S MOTORS LLC" t:business_email=bryan@hsmotors.com t:mailing_state=IA t:mailing_city=CRESCO m:tracking=127186

series e:hbfc-v9c2 d:2015-07-03T04:31:39.000Z t:phone_number=515-962-8130 t:mailing_zip=50208 t:company_name="NOBLE AUTOMOTIVE" t:business_email=joanhembry@hotmail.com t:mailing_state=IA t:mailing_city=NEWTON m:tracking=127404
```

## Meta Commands

```ls
metric m:tracking p:integer l:TRACKING t:dataTypeName=number

entity e:hbfc-v9c2 l:"Registered Motor Vehicle Service Contract Providers" t:attribution="Iowa Insurance Division" t:url=https://data.iowa.gov/api/views/hbfc-v9c2

property e:hbfc-v9c2 t:meta.view v:id=hbfc-v9c2 v:category=Economy v:averageRating=0 v:name="Registered Motor Vehicle Service Contract Providers" v:attribution="Iowa Insurance Division"

property e:hbfc-v9c2 t:meta.view.license v:name="Public Domain"

property e:hbfc-v9c2 t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:hbfc-v9c2 t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| :updated_at | tracking | company_name                 | mailing_address1      | mailing_address2 | mailing_address3 | mailing_city | mailing_state | mailing_zip | business_phone       | business_email         | 
| =========== | ======== | ============================ | ===================== | ================ | ================ | ============ | ============= | =========== | ==================== | ====================== | 
| 1435897909  | 127177   | DUEA MOTOR COMPANY           | PO BOX 278            |                  |                  | ALBIA        | IA            | 52531       | [641-932-5172, null] | ANNFRAN24@HOTMAIL.COM  | 
| 1435897899  | 127186   | H & S MOTORS LLC             | P.O. BOX 449          |                  |                  | CRESCO       | IA            | 52136       | [563-547-2401, null] | bryan@hsmotors.com     | 
| 1435897899  | 127404   | NOBLE AUTOMOTIVE             | P.O. Box 248          |                  |                  | NEWTON       | IA            | 50208       | [515-962-8130, null] | joanhembry@hotmail.com | 
| 1435897898  | 127289   | VANNOY CHEVROLET CO.         | PO BOX 310            |                  |                  | MONTEZUMA    | IA            | 50171       | [641-623-2177, null] | blazer11@zumatel.net   | 
| 1435897899  | 127585   | ALLIANT CREDIT UNION         | 1200 ASSOCIATES DRIVE | SUITE 102        |                  | DUBUQUE      | IA            | 52002       | [563-585-3737, null] | cdecker@alliantcu.com  | 
| 1435897899  | 127200   | ASHER MOTOR COMPANY          | 228 11TH ST SE        |                  |                  | SPENCER      | IA            | 51301       | [712-262-5730, null] | ashers@smunet.net      | 
| 1435897899  | 127261   | SHORE MOTOR CO.              | P.O. BOX 473          |                  |                  | CLARINDA     | IA            | 51632       | [712-542-6581, null] | larrys7777@yahoo.com   | 
| 1435897899  | 127613   | KEN WISE CHRYSLER DODGE JEEP | P.O. BOX 1553         |                  |                  | MARSHALLTOWN | IA            | 50158       | [641-752-3636, null] | tomwise@kenwise.com    | 
| 1435897898  | 127676   | Euro Car LLC                 | 1200 BOYSON RD        |                  |                  | HIAWATHA     | IA            | 52233       | [319-294-4635, null] | ryanbuns@vwofcr.com    | 
| 1435897898  | 127443   | BSB AUTO                     | 1413 PLAZA DRIVE      |                  |                  | CARROLL      | IA            | 51401       | [712-792-2551, null] | runner@westianet.net   | 
```