# IDPH Home Services Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-home-services-directory-072b1) |
| Metadata | [Link](https://data.illinois.gov/api/views/swzv-788p) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/swzv-788p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/swzv-788p/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | swzv-788p |
| Name | IDPH Home Services Directory |
| Attribution | Division of Health Care Facilities and Programs |
| Category | Public Health |
| Tags | home, services |
| Created | 2012-01-30T20:08:42Z |
| Publication Date | 2017-01-09T17:22:46Z |

## Description

Current as of January 2017

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | home_service_agency     | Home Service Agency     | text      | text        |
| No       |                | address                 | Address                 | text      | text        |
| Yes      | series tag     | city                    | City                    | text      | text        |
| Yes      | series tag     | zip                     | Zip                     | text      | number      |
| Yes      | series tag     | county                  | County                  | text      | text        |
| Yes      | series tag     | phone                   | Phone                   | phone     | phone       |
| Yes      | numeric metric | license_                | License #               | number    | number      |
| Yes      | series tag     | license_expiration_date | License Expiration Date | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:swzv-788p d:2017-01-09T17:20:59.000Z t:zip=60615 t:license_expiration_date=07/31/17 t:phone_number="(773) 386-6607" t:county=Cook t:home_service_agency="@ Home Healthcare 1" t:city=Chicago m:license_=3000780

series e:swzv-788p d:2017-01-09T17:20:59.000Z t:zip=60076 t:license_expiration_date=05/31/17 t:phone_number="(847) 533-6467" t:county=Cook t:home_service_agency="@home Advantage" t:city=Skokie m:license_=3001228

series e:swzv-788p d:2017-01-09T17:20:59.000Z t:zip=60403 t:license_expiration_date=05/31/17 t:phone_number="(815) 582-3599" t:county=Will t:home_service_agency="1 and Only Home Care, Inc." t:city="Crest Hill" m:license_=3001301
```

## Meta Commands

```ls
metric m:license_ p:integer l:"License #" t:dataTypeName=number

entity e:swzv-788p l:"IDPH Home Services Directory" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/swzv-788p

property e:swzv-788p t:meta.view v:id=swzv-788p v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Home Services Directory" v:attribution="Division of Health Care Facilities and Programs"

property e:swzv-788p t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:swzv-788p t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```

## Top Records

```ls
| :updated_at | home_service_agency                 | address                       | city         | zip   | county  | phone                  | license_ | license_expiration_date | 
| =========== | =================================== | ============================= | ============ | ===== | ======= | ====================== | ======== | ======================= | 
| 1483982459  | @ Home Healthcare 1                 | 1715 E 55th St                | Chicago      | 60615 | Cook    | [(773) 386-6607, null] | 3000780  | 07/31/17                | 
| 1483982459  | @home Advantage                     | 3349 Main Street              | Skokie       | 60076 | Cook    | [(847) 533-6467, null] | 3001228  | 05/31/17                | 
| 1483982459  | 1 and Only Home Care, Inc.          | 21355 Prestwick Drive         | Crest Hill   | 60403 | Will    | [(815) 582-3599, null] | 3001301  | 05/31/17                | 
| 1483982459  | 1 Stop Homemaker Services, LLC      | 9933 Lawler Avenue, Suite 206 | Skokie       | 60077 | Cook    | [(847) 644-4336, null] | 3000709  | 01/31/18                | 
| 1483982459  | 1776 Home Care, LLC                 | 800 Roosevelt Road, E114      | Glen Ellyn   | 60137 | Du Page | [(630) 469-4515, null] | 3001239  | 03/31/17                | 
| 1483982459  | 1Care Home Services LLC             | 649 Hiawatha Drive            | Carol Stream | 60188 | Du Page | [(630) 346-5224, null] | 3001303  | 12/31/17                | 
| 1483982459  | 1st Choice Caregiver, Inc.          | 1371 Karen Drive              | West Dundee  | 60118 | Kane    | [(224) 381-0106, null] | 3001165  | 08/31/17                | 
| 1483982459  | 1st Choice Home Health Agency, Inc. | 7260 W Benton Drive           | Frankfort    | 60423 | Will    | [(815) 464-9980, null] | 3001178  | 11/30/17                | 
| 1483982459  | 1ST Choice Senior HomeCare, Inc.    | 4556 Oakton St.Room 201       | Skokie       | 60076 | Cook    | [(847) 329-5122, null] | 3000520  | 06/30/17                | 
| 1483982459  | 24/7 At Home Care Services, Inc.    | 2700 Patriot Blvd., Suite 250 | Glenview     | 60026 | Cook    | [(847) 510-5982, null] | 3001362  | 03/31/17                | 
```