# 2016 Registered Foreclosure Properties

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-registered-foreclosure-properties) |
| Metadata | [Link](https://data.lacity.org/api/views/4sbs-dcfn) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/4sbs-dcfn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/4sbs-dcfn/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 4sbs-dcfn |
| Name | 2016 Registered Foreclosure Properties |
| Attribution | LOS ANGELES HOUSING AND COMMUNITY INVESTMENT DEPARTMENT |
| Category | A Well Run City |
| Tags | foreclosure, 2016, hcidla, foreclosures, foreclosed |
| Created | 2016-04-22T21:08:40Z |
| Publication Date | 2016-04-25T16:42:28Z |

## Description

2016 Foreclosure Properties registered with HCIDLA between January 1, 2016 and December 31, 2016

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | numeric metric | apn                       | APN                       | number        | number        |
| Yes      | time           | registereddate            | RegisteredDate            | calendar_date | calendar_date |
| Yes      | series tag     | propertytype              | PropertyType              | text          | text          |
| Yes      | series tag     | propertycity              | PropertyCity              | text          | text          |
| Yes      | series tag     | propertystate             | PropertyState             | text          | text          |
| Yes      | series tag     | propertyzip               | PropertyZip               | text          | text          |
| Yes      | series tag     | councildistrict           | CouncilDistrict           | text          | number        |
| Yes      | series tag     | lender                    | Lender                    | text          | text          |
| Yes      | series tag     | lendercontact             | LenderContact             | text          | text          |
| Yes      | series tag     | lendercontactphone        | LenderContactPhone        | text          | text          |
| Yes      | series tag     | propertymanagement        | PropertyManagement        | text          | text          |
| Yes      | series tag     | propertymanagementcontact | PropertyManagementContact | text          | text          |
| No       |                | propertymanagementaddress | PropertyManagementAddress | text          | text          |
| Yes      | series tag     | propertymgmtcontactphone  | PropertyMgmtContactPhone  | text          | text          |
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
series e:4sbs-dcfn d:2016-03-18T00:00:00.000Z t:lendercontact="Siamak Kohanoff" t:propertymanagementcontact=NULL t:propertystate=CA t:propertymgmtcontactphone=NULL t:councildistrict=2 t:propertymanagement=NULL t:propertyzip=91352 t:lendercontactphone=818-986-2274 t:lender="Siamak Kohanoff" t:propertycity="LOS ANGELES" t:propertytype="Single Family" m:apn=2403013010

series e:4sbs-dcfn d:2016-01-14T00:00:00.000Z t:lendercontact="Jennifer Hathaway" t:propertymanagementcontact=NULL t:propertystate=CA t:propertymgmtcontactphone=NULL t:councildistrict=3 t:propertymanagement=NULL t:propertyzip=91335 t:lendercontactphone=972-894-2950 t:lender="Champion Mortgage" t:propertycity="LOS ANGELES" t:propertytype="Single Family" m:apn=2124021015

series e:4sbs-dcfn d:2016-05-12T00:00:00.000Z t:lendercontact="Karen Larson" t:propertymanagementcontact=NULL t:propertystate=CA t:propertymgmtcontactphone=NULL t:councildistrict=11 t:propertymanagement=NULL t:propertyzip=90049 t:lendercontactphone=818-222-5222 t:lender="Platinum Loan Servicing" t:propertycity="LOS ANGELES" t:propertytype="Single Family" m:apn=4365016012
```

## Meta Commands

```ls
metric m:apn p:long l:APN d:"Assessor Parcel Number (APN) is a unique number assigned to each plot of land by a county tax assessor. The APN is based on formatting codes depending on the home's location. The local government uses APNs to identify and keep track of land ownership for property tax purposes." t:dataTypeName=number

entity e:4sbs-dcfn l:"2016 Registered Foreclosure Properties" t:attribution="LOS ANGELES HOUSING AND COMMUNITY INVESTMENT DEPARTMENT" t:url=https://data.lacity.org/api/views/4sbs-dcfn

property e:4sbs-dcfn t:meta.view v:id=4sbs-dcfn v:category="A Well Run City" v:attributionLink=http://www.hcidla.org v:averageRating=0 v:name="2016 Registered Foreclosure Properties" v:attribution="LOS ANGELES HOUSING AND COMMUNITY INVESTMENT DEPARTMENT"

property e:4sbs-dcfn t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:4sbs-dcfn t:meta.view.owner v:id=tdkf-rwnq v:profileImageUrlMedium=/api/users/tdkf-rwnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdkf-rwnq/profile_images/LARGE v:screenName="HCIDLA OpenData" v:profileImageUrlSmall=/api/users/tdkf-rwnq/profile_images/TINY v:lastNotificationSeenAt=1492106425 v:displayName="HCIDLA OpenData"

property e:4sbs-dcfn t:meta.view.tableauthor v:id=ey4n-c8js v:screenName="Maria Gonzalez" v:roleName=editor v:displayName="Maria Gonzalez"
```

## Top Records

```ls
| apn        | registereddate      | propertytype  | propertycity | propertystate | propertyzip | councildistrict | lender                                  | lendercontact      | lendercontactphone | propertymanagement   | propertymanagementcontact | propertymanagementaddress                    | propertymgmtcontactphone | 
| ========== | =================== | ============= | ============ | ============= | =========== | =============== | ======================================= | ================== | ================== | ==================== | ========================= | ============================================ | ======================== | 
| 2403013010 | 2016-03-18T00:00:00 | Single Family | LOS ANGELES  | CA            | 91352       | 2               | Siamak Kohanoff                         | Siamak Kohanoff    | 818-986-2274       | NULL                 | NULL                      |                                              | NULL                     | 
| 2124021015 | 2016-01-14T00:00:00 | Single Family | LOS ANGELES  | CA            | 91335       | 3               | Champion Mortgage                       | Jennifer Hathaway  | 972-894-2950       | NULL                 | NULL                      |                                              | NULL                     | 
| 4365016012 | 2016-05-12T00:00:00 | Single Family | LOS ANGELES  | CA            | 90049       | 11              | Platinum Loan Servicing                 | Karen Larson       | 818-222-5222       | NULL                 | NULL                      |                                              | NULL                     | 
| 2274024029 | 2016-04-06T00:00:00 | Single Family | LOS ANGELES  | CA            | 91423       | 4               | Wells Fargo Bank N.A.                   | Jonathon Holt      | 877-617-5274       | LPS                  | Jonathon Holt             | 1003 E Brier DR San Bernardino CA 92408      | 281-404-7816             | 
| 5094025058 | 2016-06-24T00:00:00 | Single Family | LOS ANGELES  | CA            | 90006       | 10              | PMA Finance of America Mortgage, LLC    | MARTHA ANAYA       | 909-539-6746       | NULL                 | NULL                      |                                              | NULL                     | 
| 5067020044 | 2016-03-14T00:00:00 | Single Family | LOS ANGELES  | CA            | 90019       | 10              | HSBC CONSUMER LENDING MORTGAGE SERVICES | Christina Berdecia | 813-571-8620       | SAFEGUARD            | Edward Zubia              | 3540 WILSHIRE BLVD 1109 LOS ANGELES CA 90010 | 213-383-2097             | 
| 5303007026 | 2016-01-29T00:00:00 | Multi-Family  | LOS ANGELES  | CA            | 90031       | 1               | Flagstar                                | Lori Richard       | 904-473-0504       | Bron Inc             | Eric Moore                | 41951 Remington AVE 150 Temecula CA 92590    | 951-970-3899             | 
| 2628011011 | 2016-01-19T00:00:00 | Single Family | LOS ANGELES  | CA            | 91331       | 6               | Nationstar Mortgage LLC                 | NSTAR CLIENT       | 469-549-2178       | Safeguard Properties | Safeguard Properties      | 7887 Safeguard Cir Valley View OH 44125      | 800-852-8306             | 
| 2331011156 | 2016-01-07T00:00:00 | Single Family | LOS ANGELES  | CA            | 91606       | 2               | BVS LP-Barbra Petie-Pally Trust         | brian ostrow       | 916-769-0664       | NULL                 | NULL                      |                                              | NULL                     | 
| 5028011010 | 2016-01-26T00:00:00 | Single Family | LOS ANGELES  | CA            | 90008       | 8               | Wells Fargo Bank N.A.                   | Jonathon Holt      | 877-617-5274       | EDWARD ZUBIA         | EDWARD ZUBIA              | 3540 WILSHIRE BLVD 1109 LOS ANGELES CA 90010 | 818-406-3611             | 
```