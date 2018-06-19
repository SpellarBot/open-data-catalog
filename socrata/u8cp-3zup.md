# TPAs Active in Iowa

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tpas-active-in-iowa) |
| Metadata | [Link](https://data.iowa.gov/api/views/u8cp-3zup) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/u8cp-3zup/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/u8cp-3zup/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | u8cp-3zup |
| Name | TPAs Active in Iowa |
| Category | Economy |
| Tags | insurance, claims |
| Created | 2016-11-10T16:34:08Z |
| Publication Date | 2016-11-10T16:39:36Z |

## Description

A third-party administrator is an entity that performs insurance and claims related tasks for residents of the state of Iowa. See legal definition pursuant to Iowa Code section 510.11(2).

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | name           | Name           | text          | text          |
| No       |             | address_line_1 | Address_Line_1 | text          | text          |
| No       |             | address_line_2 | Address_Line_2 | text          | text          |
| No       |             | address_line_3 | Address_Line_3 | text          | text          |
| Yes      | series tag  | city           | City           | text          | text          |
| Yes      | series tag  | state          | State          | text          | text          |
| Yes      | series tag  | zip            | ZIP            | text          | text          |
| Yes      | series tag  | dba_trade_name | DBA/Trade_Name | text          | text          |
| Yes      | series tag  | license_number | License_Number | text          | number        |
| Yes      | time        | effective_date | Effective Date | calendar_date | calendar_date |
| No       |             | expiry_date    | Expiry Date    | calendar_date | calendar_date |
| Yes      | series tag  | business_phone | Business Phone | text          | text          |
| Yes      | series tag  | email          | Email          | text          | text          |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2,address_line_3,expiry_date
```

## Data Commands

```ls
series e:u8cp-3zup d:2016-03-02T00:00:00.000Z t:zip=66207-0470 t:business_phone="(800) 325-8166" t:email=insurance@aafp.org t:license_number=1002059878 t:name="AAFP INSURANCE SERVICES INC" t:state=KS t:city="SHAWNEE MISSION" m:row_number.u8cp-3zup=1

series e:u8cp-3zup d:2016-04-06T00:00:00.000Z t:zip=19482 t:business_phone="(800) 927-9800" t:email=blinsurance@cscglobal.com t:license_number=1002048767 t:name="A-G ADMINISTRATORS INC" t:state=PA t:city="VALLEY FORGE" m:row_number.u8cp-3zup=2

series e:u8cp-3zup d:2015-04-09T00:00:00.000Z t:zip=92112-0670 t:business_phone="(619) 238-1828" t:email=kaguilar@alliantinsurance.com t:license_number=1002102846 t:name="ALLIANT SERVICES HOUSTON INC" t:state=CA t:city="SAN DIEGO" m:row_number.u8cp-3zup=3
```

## Meta Commands

```ls
metric m:row_number.u8cp-3zup p:long l:"Row Number"

entity e:u8cp-3zup l:"TPAs Active in Iowa" t:url=https://data.iowa.gov/api/views/u8cp-3zup

property e:u8cp-3zup t:meta.view v:id=u8cp-3zup v:category=Economy v:averageRating=0 v:name="TPAs Active in Iowa"

property e:u8cp-3zup t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:u8cp-3zup t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| name                               | address_line_1 | address_line_2 | address_line_3 | city            | state | zip        | dba_trade_name | license_number | effective_date      | expiry_date         | business_phone | email                                | 
| ================================== | ============== | ============== | ============== | =============== | ===== | ========== | ============== | ============== | =================== | =================== | ============== | ==================================== | 
| AAFP INSURANCE SERVICES INC        | PO BOX 7470    |                |                | SHAWNEE MISSION | KS    | 66207-0470 |                | 1002059878     | 2016-03-02T00:00:00 | 2019-03-01T00:00:00 | (800) 325-8166 | insurance@aafp.org                   | 
| A-G ADMINISTRATORS INC             | PO BOX 979     |                |                | VALLEY FORGE    | PA    | 19482      |                | 1002048767     | 2016-04-06T00:00:00 | 2019-04-05T00:00:00 | (800) 927-9800 | blinsurance@cscglobal.com            | 
| ALLIANT SERVICES HOUSTON INC       | PO BOX 120670  |                |                | SAN DIEGO       | CA    | 92112-0670 |                | 1002102846     | 2015-04-09T00:00:00 | 2018-02-28T00:00:00 | (619) 238-1828 | kaguilar@alliantinsurance.com        | 
| ALLIED NATIONAL INC                | PO BOX 29189   |                |                | SHAWNEE MISSION | KS    | 66201-9189 |                | 1002050315     | 2016-05-22T00:00:00 | 2019-05-21T00:00:00 | (913) 945-4100 | dashley@alliednational.com           | 
| ALWAYSCARE BENEFITS INC            | PO BOX 98100   |                |                | BATON ROUGE     | LA    | 70898-9100 |                | 1002104466     | 2015-03-30T00:00:00 | 2018-03-26T00:00:00 | (225) 926-2888 | LICENSINGINFO@ALWAYSCAREBENEFITS.COM | 
| BAY BRIDGE ADMINISTRATORS LLC      | P O BOX 161690 |                |                | AUSTIN          | TX    | 78716      |                | 1002188267     | 2015-10-25T00:00:00 | 2018-10-24T00:00:00 | (512) 329-5069 | state_compliance@bbadmin.com         | 
| BENEFIT & RISK MANAGEMENT SERVICES | P.O. BOX 2140  |                |                | FOLSOM          | CA    | 95763      |                | 1002229959     | 2014-05-06T00:00:00 | 2017-05-06T00:00:00 | (916) 467-1400 | celine.neff@brmsonline.com           | 
| BENEFIT MANAGEMENT LLC             | PO BOX 1090    |                |                | GREAT BEND      | KS    | 67530      |                | 1002057042     | 2016-11-19T00:00:00 | 2019-11-18T00:00:00 | (620) 792-1779 | cremmert@bmikansas.com               | 
| BENEFITS INC                       | P O BOX 410    |                |                | DECORAH         | IA    | 52101      |                | 1002109386     | 2015-02-12T00:00:00 | 2018-04-05T00:00:00 | (563) 387-0789 | PHIL@BENEFITSOLUTIONS.US             | 
| BMI BENEFITS LLC                   | P O BOX 511    |                |                | MATAWAN         | NJ    | 7747       |                | 1002061667     | 2013-12-29T00:00:00 | 2016-12-29T00:00:00 | (732) 583-1181 | tomp@bobmccloskey.com                | 
```