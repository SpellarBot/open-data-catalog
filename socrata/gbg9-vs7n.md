# Youth Source Centers Location And Contact Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/youth-source-centers-location-and-contact-info-d4671) |
| Metadata | [Link](https://data.lacity.org/api/views/gbg9-vs7n) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/gbg9-vs7n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/gbg9-vs7n/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | gbg9-vs7n |
| Name | Youth Source Centers Location And Contact Info |
| Attribution | EWDD |
| Tags | ewdd, youthsource, agency, contact |
| Created | 2014-05-30T15:34:01Z |
| Publication Date | 2014-05-30T15:36:19Z |

## Description

Identifies EWDD YouthSource Centers along with related agency, location, and contact information.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | agency_name    | Agency Name    | text      | text        |
| Yes      | series tag  | street_address | Street Address | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | zip            | Zip            | text      | text        |
| Yes      | series tag  | ysc_phone      | YSC Phone      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gbg9-vs7n d:2014-05-30T08:34:15.000Z t:zip=90021 t:ysc_phone="(213) 623-8446" t:street_address="838 E 6th St." t:agency_name="Para Los Ninos (East)" t:city="Los Angeles" m:row_number.gbg9-vs7n=1

series e:gbg9-vs7n d:2014-05-30T08:34:15.000Z t:zip=90043 t:ysc_phone="(323) 545-1130" t:street_address="5414 S Crenshaw Bl." t:agency_name="Brotherhood Crusade (South)" t:city="Los Angeles" m:row_number.gbg9-vs7n=2

series e:gbg9-vs7n d:2014-05-30T08:34:15.000Z t:zip=90010 t:ysc_phone="(213) 736-5456" t:street_address="3250 Wilshire Blvd., Ste. 1010" t:agency_name="AYE/Catholic Charities Wilshire Office (Central)" t:city="Los Angeles" m:row_number.gbg9-vs7n=3
```

## Meta Commands

```ls
metric m:row_number.gbg9-vs7n p:long l:"Row Number"

entity e:gbg9-vs7n l:"Youth Source Centers Location And Contact Info" t:attribution=EWDD t:url=https://data.lacity.org/api/views/gbg9-vs7n

property e:gbg9-vs7n t:meta.view v:id=gbg9-vs7n v:averageRating=0 v:name="Youth Source Centers Location And Contact Info" v:attribution=EWDD

property e:gbg9-vs7n t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:gbg9-vs7n t:meta.view.owner v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:displayName="Economic and Workforce Dev OpenData"

property e:gbg9-vs7n t:meta.view.tableauthor v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:roleName=publisher v:displayName="Economic and Workforce Dev OpenData"
```

## Top Records

```ls
| :updated_at | agency_name                                      | street_address                 | city         | zip   | ysc_phone      | 
| =========== | ================================================ | ============================== | ============ | ===== | ============== | 
| 1401438855  | Para Los Ninos (East)                            | 838 E 6th St.                  | Los Angeles  | 90021 | (213) 623-8446 | 
| 1401438855  | Brotherhood Crusade (South)                      | 5414 S Crenshaw Bl.            | Los Angeles  | 90043 | (323) 545-1130 | 
| 1401438855  | AYE/Catholic Charities Wilshire Office (Central) | 3250 Wilshire Blvd., Ste. 1010 | Los Angeles  | 90010 | (213) 736-5456 | 
| 1401438855  | Youth Policy Institute (North Valley)            | 11844 Glenoaks Bl.             | San Fernando | 91340 | (818) 361-7108 | 
| 1401438855  | Youth Opportunity Movement (Watts)               | 1501 E 103rd St.               | Los Angeles  | 90002 | (323) 971-7640 | 
| 1401438855  | Watts Labor Community Action Center (South)      | 958 E 108th St.                | Los Angeles  | 90059 | (323) 563-5634 | 
| 1401438855  | El Proyecto Del Barrio (South Valley)            | 20800 Sherman Way              | Los Angeles  | 91306 | (818) 710-5239 | 
| 1401438855  | UCLA (Central)                                   | 501 South Bixel Ave.           | Los Angeles  | 90017 | (213) 202-5327 | 
| 1401438855  | AYE / Catholic Charities (South)                 | 3965 S Vermont Ave.            | Los Angeles  | 90037 | (323) 730-7900 | 
| 1401438855  | El Proyecto Del Barrio (North Valley)            | 9030 Laurel Canyon Blvd.       | Sun Valley   | 91352 | (818) 771-0184 | 
```