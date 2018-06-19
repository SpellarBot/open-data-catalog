# 2014 Registered Foreclosure Properties

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-registered-foreclosure-properties-93f96) |
| Metadata | [Link](https://data.lacity.org/api/views/fdwe-pgcu) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/fdwe-pgcu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/fdwe-pgcu/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | fdwe-pgcu |
| Name | 2014 Registered Foreclosure Properties |
| Category | A Well Run City |
| Tags | foreclosure, 2014, hcidla |
| Created | 2014-05-28T22:28:27Z |
| Publication Date | 2014-09-23T22:03:14Z |

## Description

The 2014 Foreclosure Properties registered at HCIDLA between 1/1/2014 and 12/31/2014.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                        | Data Type     | Render Type   |
| ======== | ============== | ==================== | =========================== | ============= | ============= |
| Yes      | numeric metric | apn                  | APN                         | number        | number        |
| Yes      | time           | registereddate       | Registered Date             | calendar_date | calendar_date |
| Yes      | series tag     | property_type        | Property Type               | text          | text          |
| Yes      | series tag     | zip_code             | Zip Code                    | text          | number        |
| No       |                | cd                   | Council District            | number        | number        |
| Yes      | series tag     | lender               | Lender                      | text          | text          |
| Yes      | series tag     | lendercontact        | Lender Contact              | text          | text          |
| Yes      | series tag     | lendercontactphone   | Lender Contact Phone        | text          | text          |
| Yes      | series tag     | propertymanagement   | Property Management         | text          | text          |
| Yes      | series tag     | propertymgmtcontact  | Property Management Contact | text          | text          |
| No       |                | propmgmt_address     | Property Management Address | text          | text          |
| Yes      | series tag     | propertycontactphone | Property Contact Phone      | text          | text          |
```

## Time Field

```ls
Value = registereddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = cd,propmgmt_address
```

## Data Commands

```ls
series e:fdwe-pgcu d:2014-03-18T00:00:00.000Z t:lendercontact="DANNY P" t:propertycontactphone=NULL t:property_type="Single Family" t:propertymgmtcontact=NULL t:zip_code=90044 t:propertymanagement=NULL t:lendercontactphone=818-291-5527 t:lender="CALIFORNIA CREDIT UNION" m:apn=6054024007

series e:fdwe-pgcu d:2014-10-01T00:00:00.000Z t:lendercontact="Amy Lott" t:propertycontactphone=213-804-7437 t:property_type="Single Family" t:propertymgmtcontact="EDWARD ZUBIA" t:zip_code=91406 t:propertymanagement="EDWARD ZUBIA" t:lendercontactphone=888-310-1506 t:lender="JP Morgan Chase NA" m:apn=2224027015

series e:fdwe-pgcu d:2014-02-12T00:00:00.000Z t:lendercontact="Reid Schermer" t:propertycontactphone=805-496-1084 t:property_type="Single Family" t:propertymgmtcontact="Mingham Brian" t:zip_code=90038 t:propertymanagement="National Real Estate Solutions" t:lendercontactphone=770-612-7007 t:lender="Ocwen Loan Servicing, LLC" m:apn=5534021019
```

## Meta Commands

```ls
metric m:apn p:long l:APN t:dataTypeName=number

entity e:fdwe-pgcu l:"2014 Registered Foreclosure Properties" t:url=https://data.lacity.org/api/views/fdwe-pgcu

property e:fdwe-pgcu t:meta.view v:id=fdwe-pgcu v:category="A Well Run City" v:averageRating=0 v:name="2014 Registered Foreclosure Properties"

property e:fdwe-pgcu t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:fdwe-pgcu t:meta.view.owner v:id=tdkf-rwnq v:profileImageUrlMedium=/api/users/tdkf-rwnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdkf-rwnq/profile_images/LARGE v:screenName="HCIDLA OpenData" v:profileImageUrlSmall=/api/users/tdkf-rwnq/profile_images/TINY v:lastNotificationSeenAt=1492106425 v:displayName="HCIDLA OpenData"

property e:fdwe-pgcu t:meta.view.tableauthor v:id=tdkf-rwnq v:profileImageUrlMedium=/api/users/tdkf-rwnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdkf-rwnq/profile_images/LARGE v:screenName="HCIDLA OpenData" v:profileImageUrlSmall=/api/users/tdkf-rwnq/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492106425 v:displayName="HCIDLA OpenData"
```

## Top Records

```ls
| apn        | registereddate      | property_type | zip_code | cd | lender                    | lendercontact   | lendercontactphone | propertymanagement                                         | propertymgmtcontact             | propmgmt_address                              | propertycontactphone | 
| ========== | =================== | ============= | ======== | == | ========================= | =============== | ================== | ========================================================== | =============================== | ============================================= | ==================== | 
| 6054024007 | 2014-03-18T00:00:00 | Single Family | 90044    | 8  | CALIFORNIA CREDIT UNION   | DANNY P         | 818-291-5527       | NULL                                                       | NULL                            |                                               | NULL                 | 
| 2224027015 | 2014-10-01T00:00:00 | Single Family | 91406    | 6  | JP Morgan Chase NA        | Amy Lott        | 888-310-1506       | EDWARD ZUBIA                                               | EDWARD ZUBIA                    | 3540 WILSHIRE BLVD 1109 LOS ANGELES CA 90010  | 213-804-7437         | 
| 5534021019 | 2014-02-12T00:00:00 | Single Family | 90038    | 13 | Ocwen Loan Servicing, LLC | Reid Schermer   | 770-612-7007       | National Real Estate Solutions                             | Mingham Brian                   | 299 W Hillcrest DR 117 Thousand Oaks CA 91360 | 805-496-1084         | 
| 2671012001 | 2014-12-16T00:00:00 | Single Family | 91343    | 12 | Ocwen Loan Servicing, LLC | Reid Schermer   | 770-612-7007       | PPS                                                        | Trevethan Aaron                 | 30011 Ivy Glenn DR 224 Laguna Niguel CA 92677 | 949-612-0342         | 
| 2303017044 | 2014-09-30T00:00:00 | Single Family | 91605    | 2  | JP Morgan Chase NA        | Amy Lott        | 888-310-1506       | MCS                                                        | MCS Standard Field Services LLC | 4646 Natick AVE 201 Sherman Oaks CA 91403     | 323-363-4863         | 
| 5594001003 | 2014-06-16T00:00:00 | Multi-Family  | 90039    | 13 | GREEN TREE SERVICING LLC  | James Patterson | 800-557-1602       | Assurant Field Asset Services c/o New Beginning Properties | Lourdes Chavez                  | 445 W 34 ST San Bernardino CA 92405           | 909-289-1453         | 
| 6119010023 | 2014-06-17T00:00:00 | Single Family | 90247    | 15 | Wells Fargo Bank N.A.     | Amy Whitcomb    | 877-617-5274       | Lender Processing Services                                 | Amy Whitcomb                    | 1003 E Brier DR San Bernardino CA 92408       | 877-617-8274         | 
| 2112001111 | 2014-12-01T00:00:00 | Single Family | 91304    | 3  | Wells Fargo Bank N.A.     | Amy Whitcomb    | 877-617-5274       | LPS                                                        | Amy Whitcomb                    | 1003 E Brier DR San Bernardino CA 92408       | 281-404-7816         | 
| 2033006006 | 2014-07-15T00:00:00 | Single Family | 91307    | 12 | Wells Fargo Bank N.A.     | Amy Whitcomb    | 877-617-5274       | Lender Processing Services                                 | Amy Whitcomb                    | 1003 E Brier DR San Bernardino CA 92408       | 877-617-8274         | 
| 7559017034 | 2014-11-11T00:00:00 | Single Family | 90732    | 15 | Nationstar Mortgage LLC   | NSTAR CLIENT    | 469-549-2178       | EDWARD ZUBIA                                               | EDWARD ZUBIA                    | 3540 WILSHIRE BLVD 1109 LOS ANGELES CA 90010  | 213-804-7437         | 
```