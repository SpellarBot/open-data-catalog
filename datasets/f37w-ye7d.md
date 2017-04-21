# 2015 Registered Foreclosure Properties

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-registered-foreclosure-properties) |
| Metadata | [Link](https://data.lacity.org/api/views/f37w-ye7d) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/f37w-ye7d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/f37w-ye7d/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | f37w-ye7d |
| Name | 2015 Registered Foreclosure Properties |
| Attribution | HCIDLA |
| Category | A Well Run City |
| Tags | foreclosure, 2015, hcidla, foreclosures |
| Created | 2016-01-04T21:22:47Z |
| Publication Date | 2016-01-16T00:00:42Z |

## Description

2015 Foreclosure Properties registered with the HCIDLA from January 1, 2015 through December 31, 2015.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                        | Data Type     | Render Type   |
| ======== | ============== | ============================== | =========================== | ============= | ============= |
| Yes      | numeric metric | apn                            | APN                         | number        | number        |
| Yes      | time           | registereddate                 | Registered Date             | calendar_date | calendar_date |
| Yes      | series tag     | propertytype                   | Property Type               | text          | text          |
| Yes      | series tag     | propertycity                   | Property City               | text          | text          |
| Yes      | series tag     | propertystate                  | Property State              | text          | text          |
| Yes      | series tag     | propertyzip                    | Property Zip                | text          | number        |
| Yes      | series tag     | councildistrict                | Council District            | text          | number        |
| Yes      | series tag     | lender                         | Lender                      | text          | text          |
| Yes      | series tag     | lendercontact                  | Lender Contact              | text          | text          |
| Yes      | series tag     | lendercontactphone             | Lender Contact Phone        | text          | text          |
| Yes      | series tag     | propertymanagement             | Property Management         | text          | text          |
| Yes      | series tag     | propertymanagementcontact      | Property Management Contact | text          | text          |
| No       |                | propertymanagementaddress      | Property Management Address | text          | text          |
| Yes      | series tag     | propertymanagementcontactphone | Property Mgmt Contact Phone | text          | text          |
```

## Time Field

```ls
Value = registereddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = propertymanagementaddress
```

## Data Commands

```ls
series e:f37w-ye7d d:2015-04-10T00:00:00.000Z t:lendercontact="Tina McCluskey" t:propertymanagementcontact=NULL t:propertystate=CA t:councildistrict=12 t:propertymanagement=NULL t:propertymanagementcontactphone=NULL t:propertyzip=93063 t:lendercontactphone=800-468-1743 t:lender="Fay Servicing" t:propertycity="LOS ANGELES" t:propertytype="Single Family" m:apn=2004005034

series e:f37w-ye7d d:2015-01-05T00:00:00.000Z t:lendercontact="Amy Whitcomb" t:propertymanagementcontact="Jonathon Holt" t:propertystate=CA t:councildistrict=12 t:propertymanagement="Lender Processing Services" t:propertymanagementcontactphone=877-617-8274 t:propertyzip=93063 t:lendercontactphone=877-617-5274 t:lender="Wells Fargo Bank N.A." t:propertycity="LOS ANGELES" t:propertytype="Single Family" m:apn=2004010012

series e:f37w-ye7d d:2015-01-28T00:00:00.000Z t:lendercontact="Paula Acosta" t:propertymanagementcontact="MCS Advantage Conveyance" t:propertystate=CA t:councildistrict=12 t:propertymanagement=MCS/687 t:propertymanagementcontactphone=949-642-4801 t:propertyzip=93063 t:lendercontactphone=972-315-8837 t:lender=NationStar t:propertycity="LOS ANGELES" t:propertytype="Single Family" m:apn=2004011022
```

## Meta Commands

```ls
metric m:apn p:long l:APN t:dataTypeName=number

entity e:f37w-ye7d l:"2015 Registered Foreclosure Properties" t:attribution=HCIDLA t:url=https://data.lacity.org/api/views/f37w-ye7d

property e:f37w-ye7d t:meta.view v:id=f37w-ye7d v:category="A Well Run City" v:attributionLink=http://www.hcidla.org v:averageRating=0 v:name="2015 Registered Foreclosure Properties" v:attribution=HCIDLA

property e:f37w-ye7d t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:f37w-ye7d t:meta.view.owner v:id=tdkf-rwnq v:profileImageUrlMedium=/api/users/tdkf-rwnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdkf-rwnq/profile_images/LARGE v:screenName="HCIDLA OpenData" v:profileImageUrlSmall=/api/users/tdkf-rwnq/profile_images/TINY v:lastNotificationSeenAt=1492106425 v:displayName="HCIDLA OpenData"

property e:f37w-ye7d t:meta.view.tableauthor v:id=tdkf-rwnq v:profileImageUrlMedium=/api/users/tdkf-rwnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdkf-rwnq/profile_images/LARGE v:screenName="HCIDLA OpenData" v:profileImageUrlSmall=/api/users/tdkf-rwnq/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492106425 v:displayName="HCIDLA OpenData"
```

## Top Records

```ls
| apn        | registereddate      | propertytype  | propertycity | propertystate | propertyzip | councildistrict | lender                                | lendercontact    | lendercontactphone | propertymanagement              | propertymanagementcontact       | propertymanagementaddress                     | propertymanagementcontactphone | 
| ========== | =================== | ============= | ============ | ============= | =========== | =============== | ===================================== | ================ | ================== | =============================== | =============================== | ============================================= | ============================== | 
| 2004005034 | 2015-04-10T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | Fay Servicing                         | Tina McCluskey   | 800-468-1743       | NULL                            | NULL                            |                                               | NULL                           | 
| 2004010012 | 2015-01-05T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | Wells Fargo Bank N.A.                 | Amy Whitcomb     | 877-617-5274       | Lender Processing Services      | Jonathon Holt                   | 1003 E Brier DR San Bernardino CA 92408       | 877-617-8274                   | 
| 2004011022 | 2015-01-28T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | NationStar                            | Paula Acosta     | 972-315-8837       | MCS/687                         | MCS Advantage Conveyance        | 1906 Irvine AVE Newport Beach CA 92660        | 949-642-4801                   | 
| 2004012013 | 2015-07-24T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | Celink                                | Cory Daggett     | 866-654-0020       | Connie Renteria / Five Brothers | Connie Renteria                 | 5228 Halifax RD Temple City CA 91780          | 626-453-0397                   | 
| 2004019004 | 2015-04-13T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | Federal National Mortgage Association | N/A N/a          | 800-732-6643       | EDWARD ZUBIA                    | EDWARD ZUBIA                    | 3540 WILSHIRE BLVD 1109 LOS ANGELES CA 90010  | 213-804-7437                   | 
| 2004023015 | 2015-01-08T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | Wells Fargo Bank N.A.                 | Amy Whitcomb     | 877-617-5274       | LPS                             | Jonathon Holt                   | 1003 E Brier DR San Bernardino CA 92408       | 281-404-7816                   | 
| 2004024038 | 2015-01-30T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | JP Morgan Chase NA                    | Amy Lott         | 888-310-1506       | MCS                             | MCS Standard Field Services LLC | 4646 Natick AVE 201 Sherman Oaks CA 91403     | 323-363-4863                   | 
| 2005008006 | 2015-01-13T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | Ocwen Loan Servicing, LLC             | Ivonne Pettegrew | 770-612-7007       | PPS                             | Trevethan Aaron                 | 30011 Ivy Glenn DR 224 Laguna Niguel CA 92677 | 949-612-0342                   | 
| 2005009002 | 2015-11-19T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | Caliber Home Loans                    | Kandyce Hughes   | 214-874-4174       | EDWARD ZUBIA                    | EDWARD ZUBIA                    | 3540 WILSHIRE BLVD 1109 LOS ANGELES CA 90010  | 213-804-7437                   | 
| 2005012021 | 2015-08-18T00:00:00 | Single Family | LOS ANGELES  | CA            | 93063       | 12              | Solutionstar Field Services           | Paula Acosta     | 888-456-0714       | Cyprexx Services, LLC           | Property Registrations          | 525 Grand Regency BLVD Brandon FL 33510       | 877-339-8202                   | 
```