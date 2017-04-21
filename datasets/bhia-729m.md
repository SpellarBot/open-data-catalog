# Electronic Waste Recycling Facilities List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electronic-waste-recycling-facilities-list) |
| Metadata | [Link](https://data.ny.gov/api/views/bhia-729m) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/bhia-729m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/bhia-729m/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | bhia-729m |
| Name | Electronic Waste Recycling Facilities List |
| Attribution | Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | electronic waste, recycling |
| Created | 2016-11-04T21:37:09Z |
| Publication Date | 2016-12-29T19:58:20Z |

## Description

A current listing of NYS Registered Electronic Waste Recycling Facilities. Electronic waste types accepted vary from facility to facility.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | facility_name       | Facility Name       | text      | text        |
| Yes      | series tag     | registration_number | Registration Number | text      | text        |
| Yes      | series tag     | county              | County              | text      | text        |
| Yes      | series tag     | street_address      | Street Address      | text      | text        |
| Yes      | series tag     | city                | City                | text      | text        |
| Yes      | series tag     | state               | State               | text      | text        |
| Yes      | series tag     | zip_code            | Zip Code            | text      | text        |
| Yes      | series tag     | contact_name        | Contact Name        | text      | text        |
| Yes      | series tag     | contact_email       | Contact Email       | email     | email       |
| Yes      | series tag     | phone_number        | Phone Number        | text      | text        |
| Yes      | numeric metric | extension           | Extension           | number    | number      |
| Yes      | series tag     | website             | Website             | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bhia-729m d:2016-11-18T18:37:58.000Z t:phone_number=585-458-2460 t:facility_name="Maven Technologies, LLC" t:zip_code=14606 t:contact_email=kjohnson@maventech.com t:county=Monroe t:website=http://www.maventech.com t:contact_name="Ken Johnson" t:state=NY t:street_address="1450 Lyell Avenue" t:registration_number=00123 t:city=Rochester m:extension=225

series e:bhia-729m d:2016-11-18T18:37:58.000Z t:phone_number=518-649-9500 t:facility_name="Electronics Recycling & Scrapping, Inc." t:zip_code=12204 t:contact_email=todd@ersirecycling.com t:county=Albany t:website=http://ersirecycling.com t:contact_name="Todd D'Alleva" t:state=NY t:street_address="279 Broadway" t:registration_number=00563 t:city=Menands m:extension=3

series e:bhia-729m d:2016-11-18T17:22:07.000Z t:phone_number=518-672-4451 t:facility_name="Coarc ecycle" t:zip_code=12534 t:contact_email=johnm@coarc.org t:county=Columbia t:website=http://coarcecycle.com t:contact_name="John Menegio" t:state=NY t:street_address="1 Industrial Tract" t:registration_number=01146 t:city=Hudson m:extension=2423
```

## Meta Commands

```ls
metric m:extension p:integer l:Extension d:"Phone number extension of facility contact; blank if no extension was provided." t:dataTypeName=number

entity e:bhia-729m l:"Electronic Waste Recycling Facilities List" t:attribution="Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/bhia-729m

property e:bhia-729m t:meta.view v:id=bhia-729m v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/65583.html v:averageRating=0 v:name="Electronic Waste Recycling Facilities List" v:attribution="Department of Environmental Conservation"

property e:bhia-729m t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:bhia-729m t:meta.view.tableauthor v:id=28jg-4c4u v:screenName="Diane L. Boyd" v:roleName=administrator v:displayName="Diane L. Boyd"
```

## Top Records

```ls
| :updated_at | facility_name                                  | registration_number | county       | street_address                    | city        | state | zip_code | contact_name                    | contact_email                           | phone_number | extension | website                                     | 
| =========== | ============================================== | =================== | ============ | ================================= | =========== | ===== | ======== | =============================== | ======================================= | ============ | ========= | =========================================== | 
| 1479489727  | ecoComp                                        | 00880               | Monroe       | 785 Spencerport Rd                | Rochester   | NY    | 14606    | Evan Snow                       |                                         | 585-633-3886 |           | [null, null]                                | 
| 1479494278  | Edison Electronics, Inc.                       | 00402               | Otsego       | 5375 New York 7                   | Oneonta     | NY    | 13820    | Ahren Edison                    | edisoncomputers@gmail.com               | 607-432-9311 |           | [null, null]                                | 
| 1479494278  | Compass E-Tech, Inc.                           | 01040               | Suffolk      | 100 Knickerbocker Avenue, Suite B | Bohemia     | NY    | 11716    | Customer Service Representative | sales@compassetech.com                  | 631-750-5556 |           | [http://www.compassetech.com, null]         | 
| 1479494278  | Electronic Recycling Solutions                 | 01056               | Rensselaer   | 295 1st Street                    | Troy        | NY    | 12180    | VItaly Sandul                   | scottybro1@aol.com                      | 518-598-6965 |           | [null, null]                                | 
| 1479494278  | Advanced Recovery Inc                          | 00028               | Orange       | 41 Mechanic Street                | Port Jervis | NY    | 12771    | Mark Rea                        | bzaccari@advancedrecovery.com           | 845-858-8809 |           | [http://advancedrecovery.com, null]         | 
| 1479494278  | Advanced Technology Recycling                  | 01060               | Erie         | 200 Fire Tower Drive              | Tonawanda   | NY    | 14150    | Barb Ehresman                   | Barb@atrecycle.com                      | 716-693-7779 |           | [http://www.atrecycle.com, null]            | 
| 1479494278  | Buffalo Computer Recycling, LLC                | 00927               | Erie         | 934 Clinton Street                | Buffalo     | NY    | 14210    | Steve Chumsky                   | purchasing@buffalocomputerrecycling.com | 716-868-8640 |           | [http://buffalocomputerrecycling.com, null] | 
| 1479494278  | First Class Aire, LLC dba First Class Services | 00873               | St. Lawrence | 495 West Parishville Road         | Potsdam     | NY    | 13676    | Lisa Clothier                   | Lisa@FirstClassNNY.com                  | 315-265-1003 |           | [http://www.firstclassnny.com, null]        | 
| 1479494278  | Garys Auto Parts, Inc                          | 01022               | Madison      | 651 Fitch Street                  | Oneida      | NY    | 13421    | Jim Clark                       | jimclark63@frontiernet.net              | 315-363-2240 |           | [null, null]                                | 
| 1479494278  | Maryhaven Center of Hope                       | 00777               | Suffolk      | 445 County Road 101               | Yaphank     | NY    | 11980    | John Mahoney                    | john.mahoney@chsli.org                  | 631-924-5900 |           | [http://www.maryhaven.chsli.org, null]      | 
```