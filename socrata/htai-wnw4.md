# Ward Offices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ward-offices-642e4) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/htai-wnw4) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/htai-wnw4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/htai-wnw4/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | htai-wnw4 |
| Name | Ward Offices |
| Attribution | City of Chicago |
| Category | Facilities & Geographic Boundaries |
| Tags | ward, gis, facilities |
| Created | 2010-12-22T00:50:52Z |
| Publication Date | 2015-07-16T18:35:12Z |

## Description

List of alderman, office address, phone number, and website for all 50 Chicago wards.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | ward              | WARD              | text      | number      |
| Yes      | series tag  | alderman          | ALDERMAN          | text      | text        |
| No       |             | address           | ADDRESS           | text      | text        |
| Yes      | series tag  | city              | CITY              | text      | text        |
| Yes      | series tag  | state             | STATE             | text      | text        |
| Yes      | series tag  | zipcode           | ZIPCODE           | text      | text        |
| Yes      | series tag  | ward_phone        | WARD PHONE        | phone     | phone       |
| Yes      | series tag  | ward_fax          | WARD FAX          | phone     | phone       |
| Yes      | series tag  | email             | EMAIL             | email     | email       |
| Yes      | series tag  | website           | WEBSITE           | url       | url         |
| No       |             | city_hall_address | CITY HALL ADDRESS | text      | text        |
| Yes      | series tag  | city_hall_city    | CITY HALL CITY    | text      | text        |
| Yes      | series tag  | city_hall_state   | CITY HALL STATE   | text      | text        |
| Yes      | series tag  | city_hall_zipcode | CITY HALL ZIPCODE | text      | number      |
| Yes      | series tag  | city_hall_phone   | CITY HALL PHONE   | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,city_hall_address
```

## Data Commands

```ls
series e:htai-wnw4 d:2015-07-16T11:27:37.000Z t:alderman="Proco ""Joe"" Moreno" t:phone_number="(312) 744-3063" t:ward=1 t:email=ward01@cityofchicago.org t:website=http://www.ward1.org t:zipcode=60647 t:state=IL t:city_hall_zipcode=60602 t:city_hall_state=IL t:city_hall_city=Chicago t:city=Chicago m:row_number.htai-wnw4=1

series e:htai-wnw4 d:2015-07-16T11:27:37.000Z t:alderman="Brian Hopkins" t:phone_number="(312) 744-6834" t:ward=2 t:email=Ward02@cityofchicago.org t:website=http://www.brianhopkinsforchicago.com/ t:zipcode=60622 t:state=IL t:city_hall_zipcode=60602 t:city_hall_state=IL t:city_hall_city=Chicago t:city=Chicago m:row_number.htai-wnw4=2

series e:htai-wnw4 d:2015-07-16T11:27:37.000Z t:alderman="Pat Dowell" t:phone_number="(312) 744-8734" t:ward=3 t:email=Pat.Dowell@cityofchicago.org t:website=http://www.dowellfor3rdward.com/ t:zipcode=60609 t:state=IL t:city_hall_zipcode=60602 t:city_hall_state=IL t:city_hall_city=Chicago t:city=Chicago m:row_number.htai-wnw4=3
```

## Meta Commands

```ls
metric m:row_number.htai-wnw4 p:long l:"Row Number"

entity e:htai-wnw4 l:"Ward Offices" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/htai-wnw4

property e:htai-wnw4 t:meta.view v:id=htai-wnw4 v:category="Facilities & Geographic Boundaries" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Ward Offices" v:attribution="City of Chicago"

property e:htai-wnw4 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:htai-wnw4 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | ward | alderman              | address                          | city    | state | zipcode | ward_phone             | ward_fax               | email                             | website                                        | city_hall_address                  | city_hall_city | city_hall_state | city_hall_zipcode | city_hall_phone        | 
| =========== | ==== | ===================== | ================================ | ======= | ===== | ======= | ====================== | ====================== | ================================= | ============================================== | ================================== | ============== | =============== | ================= | ====================== | 
| 1437046057  | 1    | Proco "Joe" Moreno    | 2058 North Western Avenue        | Chicago | IL    | 60647   | [(773) 278-0101, null] | [(773) 278-2541, null] | ward01@cityofchicago.org          | [http://www.ward1.org, null]                   | 121 North LaSalle Street, Room 300 | Chicago        | IL              | 60602             | [(312) 744-3063, null] | 
| 1437046057  | 2    | Brian Hopkins         | 1400 North Ashland Avenue        | Chicago | IL    | 60622   | [(312)643-2299, null]  | [null, null]           | Ward02@cityofchicago.org          | [http://www.brianhopkinsforchicago.com/, null] | 121 North LaSalle Street, Room 200 | Chicago        | IL              | 60602             | [(312) 744-6834, null] | 
| 1437046057  | 3    | Pat Dowell            | 5046 South State Street          | Chicago | IL    | 60609   | [(773) 373-9273, null] | [(773) 373-6852, null] | Pat.Dowell@cityofchicago.org      | [http://www.dowellfor3rdward.com/, null]       | 121 North LaSalle Street, Room 200 | Chicago        | IL              | 60602             | [(312) 744-8734, null] | 
| 1437046057  | 4    | William D. Burns      | 435 East 35th Street, 1st Floor  | Chicago | IL    | 60616   | [(773) 536-8103, null] | [(773) 536-7296, null] | ward04@cityofchicago.org          | [http://www.aldwillburns.com, null]            | 121 North LaSalle Street, Room 200 | Chicago        | IL              | 60602             | [(312) 744-2690, null] | 
| 1437046057  | 5    | Leslie A. Hairston    | 2325 East 71st Street            | Chicago | IL    | 60649   | [(773) 324-5555, null] | [(773) 324-1585, null] | lhairston@cityofchicago.org       | [http://www.leslieahairston.com/, null]        | 121 North LaSalle Street, Room 300 | Chicago        | IL              | 60602             | [(312) 744-6832, null] | 
| 1437046057  | 6    | Roderick T. Sawyer    | 8001 S. Martin Luther King Drive | Chicago | IL    | 60619   | [(773) 635-0006, null] | [(773) 891-5679, null] | Roderick.Sawyer@cityofchicago.org | [http://www.6thwardchicago.com, null]          | 121 North LaSalle Street, Room 200 | Chicago        | IL              | 60602             | [(312) 744-0670, null] | 
| 1437046057  | 7    | Gregory I. Mitchell   | 2249 East 95th Street            | Chicago | IL    | 60617   | [(773) 731-7777, null] | [null, null]           | alderman@gregmitchell7thward.org  | [http://mitchellforalderman.com/, null]        | 121 North LaSalle Street, Room 200 | Chicago        | IL              | 60602             | [(312) 744-6833, null] | 
| 1437046057  | 8    | Michelle A. Harris    | 8539 South Cottage Grove Avenue  | Chicago | IL    | 60619   | [(773) 874-3300, null] | [(773) 224-2425, null] | mharris@cityofchicago.org         | [http://www.aldermanmichelleharris.net/, null] | 121 Noth LaSalle Street, Room 200  | Chicago        | IL              | 60602             | [(312) 744-3075, null] | 
| 1437046057  | 9    | Anthony A. Beale      | 34 East 112th Place              | Chicago | IL    | 60628   | [(773) 785-1100, null] | [(773) 785-2900, null] | ward09@cityofchicago.org          | [http://www.ward09.cityofchicago.org/, null]   | 121 North LaSalle Street, Room 300 | Chicago        | IL              | 60602             | [(312) 744-6838, null] | 
| 1437046057  | 10   | Susan Sadlowski Garza | 10500 South Ewing Avenue         | Chicago | IL    | 60617   | [(773) 768-8138, null] | [null, null]           | ward10@cityofchicago.org          | [null, null]                                   | 121 North LaSalle Street, Room 200 | Chicago        | IL              | 60602             | [(312) 744-3078, null] | 
```