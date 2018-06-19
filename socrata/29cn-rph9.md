# Housing & Community Investment Service Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-community-investment-service-locations) |
| Metadata | [Link](https://data.lacity.org/api/views/29cn-rph9) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/29cn-rph9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/29cn-rph9/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 29cn-rph9 |
| Name | Housing & Community Investment Service Locations |
| Attribution | LOS ANGELES HOUSING AND COMMUNITY INVESTMENT DEPARTMENT |
| Category | A Livable and Sustainable City |
| Tags | family services, income tax assistance, financial planning assistance, educational counseling, family counseling, pre-employment counseling, esl, high school equivalency preparation, computer lite... |
| Created | 2014-05-21T18:36:47Z |
| Publication Date | 2015-12-07T19:59:16Z |

## Description

Locations of offices associated with the Los Angeles Housing and Community Investment Department which provide services to city residents.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                 | Data Type | Render Type |
| ======== | =========== | =================== | ==================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | location_type       | LOCATION TYPE        | text      | text        |
| Yes      | series tag  | facility_title      | FACILITY TITLE       | text      | text        |
| Yes      | series tag  | phone               | PHONE                | text      | text        |
| Yes      | series tag  | hours_open          | HOURS OPEN TO PUBLIC | text      | text        |
| Yes      | series tag  | hours_closed        | HOURS CLOSED         | text      | text        |
| Yes      | series tag  | service_description | SERVICE DESCRIPTION  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:29cn-rph9 d:2014-05-22T12:04:34.000Z t:phone="(213) 483-6335" t:location_type="NON-PROFIT FSC" t:facility_title="EL CENTRO DEL PUEBLO" t:hours_open="8AM-6PM MON-FRI" t:service_description="Family support services, including:  Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services." m:row_number.29cn-rph9=1

series e:29cn-rph9 d:2014-05-22T12:05:12.000Z t:phone="(323) 953-7356" t:location_type="NON-PROFIT FSC" t:facility_title="OAKWOOD FAMILY RESOURCE CENTER" t:hours_open="8:30AM-5PM MON, WED, THURS; 8:30AM-8PM TUES; 8:30AM-4:30PM FRI" t:service_description="Family support services, including:  Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services." m:row_number.29cn-rph9=2

series e:29cn-rph9 d:2014-05-22T12:09:01.000Z t:phone="(323) 692-0669" t:location_type="CITY OWNED/RUN FSC" t:facility_title="TOM BRADLEY FAMILYSOURCE CENTER" t:hours_open="9AM-9PM MON, THURS;  9AM-6PM TUES, WED, FRI; 4TH SAT OF THE MONTH 10AM-3PM" t:service_description="Family support services, including:  Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services." m:row_number.29cn-rph9=3
```

## Meta Commands

```ls
metric m:row_number.29cn-rph9 p:long l:"Row Number"

entity e:29cn-rph9 l:"Housing & Community Investment Service Locations" t:attribution="LOS ANGELES HOUSING AND COMMUNITY INVESTMENT DEPARTMENT" t:url=https://data.lacity.org/api/views/29cn-rph9

property e:29cn-rph9 t:meta.view v:id=29cn-rph9 v:category="A Livable and Sustainable City" v:attributionLink=http://www.hcidla.org v:averageRating=0 v:name="Housing & Community Investment Service Locations" v:attribution="LOS ANGELES HOUSING AND COMMUNITY INVESTMENT DEPARTMENT"

property e:29cn-rph9 t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:29cn-rph9 t:meta.view.owner v:id=tdkf-rwnq v:profileImageUrlMedium=/api/users/tdkf-rwnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdkf-rwnq/profile_images/LARGE v:screenName="HCIDLA OpenData" v:profileImageUrlSmall=/api/users/tdkf-rwnq/profile_images/TINY v:lastNotificationSeenAt=1492106425 v:displayName="HCIDLA OpenData"

property e:29cn-rph9 t:meta.view.tableauthor v:id=tdkf-rwnq v:profileImageUrlMedium=/api/users/tdkf-rwnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdkf-rwnq/profile_images/LARGE v:screenName="HCIDLA OpenData" v:profileImageUrlSmall=/api/users/tdkf-rwnq/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492106425 v:displayName="HCIDLA OpenData"
```

## Top Records

```ls
| :updated_at | location_type           | facility_title                           | phone          | hours_open                                                                | hours_closed    | service_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| =========== | ======================= | ======================================== | ============== | ========================================================================= | =============== | =================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1400760274  | NON-PROFIT FSC          | EL CENTRO DEL PUEBLO                     | (213) 483-6335 | 8AM-6PM MON-FRI                                                           |                 | Family support services, including: Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 1400760312  | NON-PROFIT FSC          | OAKWOOD FAMILY RESOURCE CENTER           | (323) 953-7356 | 8:30AM-5PM MON, WED, THURS; 8:30AM-8PM TUES; 8:30AM-4:30PM FRI            |                 | Family support services, including: Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 1400760541  | CITY OWNED/RUN FSC      | TOM BRADLEY FAMILYSOURCE CENTER          | (323) 692-0669 | 9AM-9PM MON, THURS; 9AM-6PM TUES, WED, FRI; 4TH SAT OF THE MONTH 10AM-3PM |                 | Family support services, including: Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 1400760551  | NON-PROFIT FSC          | 1736 FAMILY CRISIS CENTER                | (323) 737-3900 | 9AM-5PM MON-FRI                                                           |                 | Family support services, including: Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 1400760582  | NON-PROFIT FSC          | BARRIO ACTION YOUTH AND FAMILY CENTER    | (323) 221-0779 | 8AM-6PM MON&FRI; 8AM-8PM TUES,WED,THURS                                   |                 | Family support services, including: Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 1400769065  | HOUSING REGIONAL OFFICE | HCIDLA CENTRAL REGIONAL OFFICE           | (866) 557-7368 | 9AM-4PM MON-FRI                                                           |                 | The Central Regional Office administers the Rent Stabilization Program, Code Enforcement, Billing and Collections, the Rent Escrow Account Program (REAP), and the Utility Maintenance Program (UMP). Property owners may register rental properties, file applications, verify property registration and pay registration. Tenants may file complaints for Code and Rent Stabilization Ordinance (RSO) violations. Constituents may obtain a variety of information regarding HCIDLA programs, as well as referrals on related housing matters. SCEP:The Systematic Code Enforcement Program which provides systematic and complaint-based habitability inspections of the City's multifamily residential rental properties (two or more rental units) for conformance with the City's Housing Code. The program's objective is to protect the basic need of safe housing and neighborhoods for the City's rental population by preventing the development of substandard, slum and dilapidated buildings and unsafe and unsanitary living conditions. Billing:The Department issues bills, processes payments and reviews exemption requests for SCEP, Rent Registration and other HCIDLA bills including the Annual Bill issued in January. The Department also to issues rent registration certificates to rental properties that have paid their rent registration fees. Rent Escrow Account Program (REAP): REAP enforces compliance with the Housing code, and encourages property owners to maintain their properties by entitling tenants of units with unresolved violations to reduced rent rates, and providing them the option to deposit their reduced rents into a City-managed escrow account. These funds can be withdrawn for different purposes authorized by the Ordinance. UMP: UMP is an enforcement program that allows tenants to continue to receive essential utility services. Through UMP, the Department of Water and Power (DWP) and the Gas Company refer delinquent master-metered properties subject to rent stabilization to HCIDLA to establish escrow accounts for tenants to voluntarily deposit their rent. HCIDLA is then able to release these funds to maintain utility services for the affected tenants. | 
| 1400769101  | HOUSING REGIONAL OFFICE | HCIDLA NORTH REGIONAL OFFICE             | (866) 557-7368 | 9AM-4PM MON-FRI                                                           |                 | The North Regional Office administers the Rent Stabilization Program, Code Enforcement, Billing and Collections, the Rent Escrow Account Program (REAP), and the Utility Maintenance Program (UMP). Property owners may register rental properties, file applications, verify property registration and pay registration. Tenants may file complaints for Code and Rent Stabilization Ordinance (RSO) violations. Constituents may obtain a variety of information regarding HCIDLA programs, as well as referrals on related housing matters. SCEP:The Systematic Code Enforcement Program which provides systematic and complaint-based habitability inspections of the City's multifamily residential rental properties (two or more rental units) for conformance with the City's Housing Code. The program's objective is to protect the basic need of safe housing and neighborhoods for the City's rental population by preventing the development of substandard, slum and dilapidated buildings and unsafe and unsanitary living conditions. Billing:The Department issues bills, processes payments and reviews exemption requests for SCEP, Rent Registration and other HCIDLA bills including the Annual Bill issued in January. The Department also to issues rent registration certificates to rental properties that have paid their rent registration fees. Rent Escrow Account Program (REAP): REAP enforces compliance with the Housing code, and encourages property owners to maintain their properties by entitling tenants of units with unresolved violations to reduced rent rates, and providing them the option to deposit their reduced rents into a City-managed escrow account. These funds can be withdrawn for different purposes authorized by the Ordinance. UMP: UMP is an enforcement program that allows tenants to continue to receive essential utility services. Through UMP, the Department of Water and Power (DWP) and the Gas Company refer delinquent master-metered properties subject to rent stabilization to HCIDLA to establish escrow accounts for tenants to voluntarily deposit their rent. HCIDLA is then able to release these funds to maintain utility services for the affected tenants.   | 
| 1400759690  | NON-PROFIT FSC          | COALITION OF MENTAL HEALTH PROFESSIONALS | (323) 777-3120 | 8:30AM-7:30PM MON-FRI, 9AM-1PM SAT                                        |                 | Family support services, including: Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 1400759863  | NON-PROFIT FSC          | COMMUNITY BUILD                          | (323) 789-9950 | 9AM-5PM MON-FRI                                                           |                 | Family support services, including: Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 1400759874  | NON-PROFIT FSC          | WATTS LABOR COMMUNITY ACTION COMMITTEE   | (323) 249-7751 | 8AM-4:30PM MON-FRI                                                        | 12:30PM- 1:30PM | Family support services, including: Income tax & financial planning assistance, education and pre-employment counseling, and information and referral services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
```