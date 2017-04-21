# Driver License, Permit, and Non-Driver Identification Cards Issued

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/driver-license-permit-and-non-driver-identification-cards-issued) |
| Metadata | [Link](https://data.ny.gov/api/views/a4s2-d9tt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/a4s2-d9tt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/a4s2-d9tt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | a4s2-d9tt |
| Name | Driver License, Permit, and Non-Driver Identification Cards Issued |
| Attribution | New York State Department of Motor Vehicles |
| Category | Transportation |
| Tags | driver, license, permit, identification |
| Created | 2013-05-09T16:50:25Z |
| Publication Date | 2016-11-30T22:42:38Z |

## Description

This data set includes general demographics for all persons who hold, or have recently held a: Driver License, Permit or Non-Driver Identification Card (a.k.a. credential) issued by the New York State Department of Motor Vehicles.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | numeric metric | year_of_birth      | Year of Birth      | number    | number      |
| Yes      | series tag     | sex                | Sex                | text      | text        |
| Yes      | series tag     | city               | City               | text      | text        |
| Yes      | series tag     | state              | State              | text      | text        |
| Yes      | series tag     | zip                | Zip                | text      | text        |
| Yes      | series tag     | residence_county   | Residence County   | text      | text        |
| Yes      | series tag     | license_class      | License Class      | text      | text        |
| Yes      | series tag     | status             | Status             | text      | text        |
| Yes      | series tag     | privilege          | Privilege          | text      | text        |
| Yes      | numeric metric | year_of_expiration | Year of Expiration | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a4s2-d9tt d:2013-05-09T11:26:49.000Z t:residence_county=ERIE t:zip=14221 t:sex=MALE t:license_class=D t:status=VALID t:privilege=FULL t:state=NY t:city=WILLIAMSVILLE m:year_of_birth=1953 m:year_of_expiration=2020

series e:a4s2-d9tt d:2013-05-09T11:26:49.000Z t:residence_county=ONONDAGA t:zip=13211 t:sex=FEMALE t:license_class=D t:status=VALID t:privilege=FULL t:state=NY t:city=SYRACUSE m:year_of_birth=1979 m:year_of_expiration=2016

series e:a4s2-d9tt d:2013-05-09T11:26:49.000Z t:residence_county=BRONX t:zip=10465 t:sex=MALE t:license_class=D t:status=VALID t:privilege=FULL t:state=NY t:city=BRONX m:year_of_birth=1966 m:year_of_expiration=2020
```

## Meta Commands

```ls
metric m:year_of_birth p:integer l:"Year of Birth" d:"This is personal demographic information that the license, permit or ID card applicant provides to DMV. See http://dmv.ny.gov/driver-license/prove-identity-age-permitlicense for more information on how NYS DMV collects and validates the identity of its applicants. Personal identifiers such as, name, driver license number & full date of birth are not available in public data sets." t:dataTypeName=number

metric m:year_of_expiration p:integer l:"Year of Expiration" d:"This is the expiration year of the driver license or permit. If the record has both a license and a permit, it is the expiration year of the driver license." t:dataTypeName=number

entity e:a4s2-d9tt l:"Driver License, Permit, and Non-Driver Identification Cards Issued" t:attribution="New York State Department of Motor Vehicles" t:url=https://data.ny.gov/api/views/a4s2-d9tt

property e:a4s2-d9tt t:meta.view v:id=a4s2-d9tt v:category=Transportation v:attributionLink=http://www.dmv.ny.gov/license.htm v:averageRating=0 v:name="Driver License, Permit, and Non-Driver Identification Cards Issued" v:attribution="New York State Department of Motor Vehicles"

property e:a4s2-d9tt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:a4s2-d9tt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| :updated_at | year_of_birth | sex    | city          | state | zip   | residence_county | license_class | status | privilege | year_of_expiration | 
| =========== | ============= | ====== | ============= | ===== | ===== | ================ | ============= | ====== | ========= | ================== | 
| 1368098809  | 1953          | MALE   | WILLIAMSVILLE | NY    | 14221 | ERIE             | D             | VALID  | FULL      | 2020               | 
| 1368098809  | 1979          | FEMALE | SYRACUSE      | NY    | 13211 | ONONDAGA         | D             | VALID  | FULL      | 2016               | 
| 1368098809  | 1966          | MALE   | BRONX         | NY    | 10465 | BRONX            | D             | VALID  | FULL      | 2020               | 
| 1368098809  | 1984          | MALE   | BROOKLYN      | NY    | 11222 | KINGS            | D             | VALID  | FULL      | 2016               | 
| 1368098809  | 1945          | MALE   | PLEASANTVILLE | NY    | 10570 | WESTCHESTER      | D             | VALID  | FULL      | 2020               | 
| 1368098809  | 1984          | MALE   | N TONAWANDA   | NY    | 14120 | NIAGARA          | D             | VALID  | FULL      | 2019               | 
| 1368098809  | 1987          | FEMALE | HUDSON FALLS  | NY    | 12839 | WASHINGTON       | D             | VALID  | FULL      | 2016               | 
| 1368098809  | 1957          | MALE   | KIRKVILLE     | NY    | 13082 | ONONDAGA         | D             | VALID  | FULL      | 2020               | 
| 1368098809  | 1956          | FEMALE | POUGHQUAG     | NY    | 12570 | DUTCHESS         | D             | VALID  | FULL      | 2019               | 
| 1368098809  | 1963          | FEMALE | BROOKLYN      | NY    | 11203 | KINGS            | D             | VALID  | FULL      | 2017               | 
```