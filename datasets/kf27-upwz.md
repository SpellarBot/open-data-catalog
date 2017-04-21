# Motor Fuel Licensee List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-fuel-licensee-list) |
| Metadata | [Link](https://data.mo.gov/api/views/kf27-upwz) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/kf27-upwz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/kf27-upwz/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | kf27-upwz |
| Name | Motor Fuel Licensee List |
| Attribution | Missouri Department of Revenue |
| Category | Revenue |
| Tags | motor fuel, licensees |
| Created | 2015-09-21T15:34:49Z |
| Publication Date | 2017-04-18T20:53:23Z |

## Description

List of Motor Fuel Licensees

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | dba_company_name    | DBA Company Name    | text      | text        |
| Yes      | series tag  | status              | Status              | text      | text        |
| Yes      | series tag  | license_number      | License Number      | text      | text        |
| Yes      | series tag  | activity_type_s     | Activity Type(s)    | text      | text        |
| Yes      | series tag  | eligible_purchaser  | Eligible Purchaser  | text      | text        |
| Yes      | series tag  | pool_bond           | Pool Bond           | text      | text        |
| Yes      | series tag  | permissive_supplier | Permissive Supplier | text      | text        |
| No       |             | mailing_address     | Mailing Address     | text      | text        |
| Yes      | series tag  | city                | City                | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | zip_code            | Zip Code            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:kf27-upwz d:2015-09-21T08:34:54.000Z t:pool_bond=NO t:zip_code=64628 t:status="ACTIVE 06/01/02" t:eligible_purchaser=NA t:license_number=C4668 t:state=MO t:permissive_supplier=NO t:dba_company_name="LLL TRANSPORT" t:activity_type_s=C t:city=BROOKFIELD m:row_number.kf27-upwz=1

series e:kf27-upwz d:2015-09-21T08:34:54.000Z t:pool_bond=NO t:zip_code=63857 t:status="CANCELLED 04/30/01" t:eligible_purchaser=NA t:license_number=D1312 t:state=MO t:permissive_supplier=NO t:dba_company_name="PRANCE OIL CO INC" t:activity_type_s=D t:city=KENNETT m:row_number.kf27-upwz=2

series e:kf27-upwz d:2015-09-21T08:34:53.000Z t:pool_bond=NO t:zip_code=74133 t:status="REVOKED 05/27/04" t:eligible_purchaser="REVOKED 05/21/04" t:license_number=D3082 t:state=OK t:permissive_supplier=NO t:dba_company_name="4 FRONT PETROLEUM INC" t:activity_type_s=D t:city=TULSA m:row_number.kf27-upwz=3
```

## Meta Commands

```ls
metric m:row_number.kf27-upwz p:long l:"Row Number"

entity e:kf27-upwz l:"Motor Fuel Licensee List" t:attribution="Missouri Department of Revenue" t:url=https://data.mo.gov/api/views/kf27-upwz

property e:kf27-upwz t:meta.view v:id=kf27-upwz v:category=Revenue v:averageRating=0 v:name="Motor Fuel Licensee List" v:attribution="Missouri Department of Revenue"

property e:kf27-upwz t:meta.view.owner v:id=8xqn-4t42 v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:screenName="Rodney Distler" v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:displayName="Rodney Distler"

property e:kf27-upwz t:meta.view.tableauthor v:id=8xqn-4t42 v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:screenName="Rodney Distler" v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:roleName=publisher v:displayName="Rodney Distler"
```

## Top Records

```ls
| :updated_at | dba_company_name                   | status             | license_number | activity_type_s | eligible_purchaser | pool_bond | permissive_supplier | mailing_address    | city       | state | zip_code   | 
| =========== | ================================== | ================== | ============== | =============== | ================== | ========= | =================== | ================== | ========== | ===== | ========== | 
| 1442824494  | LLL TRANSPORT                      | ACTIVE 06/01/02    | C4668          | C               | NA                 | NO        | NO                  | PO BOX 327         | BROOKFIELD | MO    | 64628      | 
| 1442824494  | PRANCE OIL CO INC                  | CANCELLED 04/30/01 | D1312          | D               | NA                 | NO        | NO                  | PO BOX 888         | KENNETT    | MO    | 63857      | 
| 1442824493  | 4 FRONT PETROLEUM INC              | REVOKED 05/27/04   | D3082          | D               | REVOKED 05/21/04   | NO        | NO                  | 8316 E 73RD ST     | TULSA      | OK    | 74133      | 
| 1442824493  | AACTION TRANSPORTATION SERVICE INC | CANCELLED 9/30/99  | C2839          | C               | NA                 | NO        | NO                  | BOX 527            | CUBA       | MO    | 65453      | 
| 1442824493  | ABEL OIL COMPANY INC               | ACTIVE 01/01/99    | D0285          | D               | ACTIVE 01/01/99    | NO        | NO                  | PO BOX 532         | LOUISIANA  | MO    | 63353      | 
| 1442824493  | ACE TRANSPORTATION SERVICES        | CANCELLED 11/30/02 | C3055          | C               | NA                 | NO        | NO                  | 5804 US HIGHWAY 61 | JACKSON    | MO    | 63755-7765 | 
| 1442824493  | ADAMS FS INC                       | CANCELLED 12/31/01 | D2882          | D               | NA                 | NO        | NO                  | PO BOX 73          | PALOMA     | IL    | 62359      | 
| 1442824493  | AG COOP SERVICES INC               | ACTIVE 01/01/99    | D0910          | D               | ACTIVE 01/01/99    | NO        | NO                  | 2420 CLINTON RD    | SEDALIA    | MO    | 65301      | 
| 1442824493  | AG DISTRIBUTORS                    | CANCELLED 12/31/00 | D3031          | D               | NA                 | NO        | NO                  | BOX 528            | KENNETT    | MO    | 63857      | 
| 1442824493  | AG PROCESSING INC                  | ACTIVE 11/07/07    | S5003          | S               | NA                 | NO        | NO                  | PO BOX 2047        | OMAHA      | NE    | 68103      | 
```