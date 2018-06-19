# Ward Offices (Deprecated May 2015)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ward-offices-deprecated-may-2015) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/6mw6-krd4) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/6mw6-krd4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/6mw6-krd4/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 6mw6-krd4 |
| Name | Ward Offices (Deprecated May 2015) |
| Attribution | City of Chicago |
| Category | Facilities & Geographic Boundaries |
| Tags | ward, gis, facilities, city council, deprecated |
| Created | 2015-07-10T18:20:43Z |
| Publication Date | 2015-07-10T18:21:28Z |

## Description

OUTDATED. See the current data at https://data.cityofchicago.org/d/htai-wnw4 -- List of alderman, office address, phone number, and website for all 50 Chicago wards.  This version of the data was posted 7/2/2013 and stayed live until 7/16/2015, when it was replaced with the list of aldermen inaugurated 5/18/2015, after allowing time for most office space arrangements to be finalized.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | numeric metric | ward              | WARD              | number    | text        |
| Yes      | series tag     | alderman          | ALDERMAN          | text      | text        |
| No       |                | address           | ADDRESS           | text      | text        |
| Yes      | series tag     | city              | CITY              | text      | text        |
| Yes      | series tag     | state             | STATE             | text      | text        |
| Yes      | series tag     | zipcode           | ZIPCODE           | text      | text        |
| Yes      | series tag     | ward_phone        | WARD PHONE        | phone     | phone       |
| Yes      | series tag     | website           | WEBSITE           | url       | url         |
| Yes      | series tag     | email             | EMAIL             | email     | email       |
| No       |                | city_hall_address | CITY HALL ADDRESS | text      | text        |
| Yes      | series tag     | city_hall_city    | CITY HALL CITY    | text      | text        |
| Yes      | series tag     | city_hall_state   | CITY HALL STATE   | text      | text        |
| Yes      | series tag     | city_hall_zipcode | CITY HALL ZIPCODE | text      | number      |
| Yes      | series tag     | city_hall_phone   | CITY HALL PHONE   | phone     | phone       |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address,city_hall_address
```

## Data Commands

```ls
series e:6mw6-krd4 d:2015-01-01T00:00:00.000Z t:alderman="JOE MORENO" t:phone_number=312-744-3063 t:email=ward01@cityofchicago.org t:website=http://www.cityofchicago.org/city/en/about/wards/01.html t:zipcode=60647 t:state=IL t:city_hall_zipcode=60602 t:city_hall_state=IL t:city_hall_city=CHICAGO t:city=CHICAGO m:ward=1

series e:6mw6-krd4 d:2015-01-01T00:00:00.000Z t:alderman="ROBERT FIORETTI" t:phone_number=312-744-6836 t:email=ward02@cityofchicago.org t:website=http://www.cityofchicago.org/city/en/about/wards/02.html t:zipcode=60605 t:state=IL t:city_hall_zipcode=60602 t:city_hall_state=IL t:city_hall_city=CHICAGO t:city=CHICAGO m:ward=2

series e:6mw6-krd4 d:2015-01-01T00:00:00.000Z t:alderman="PAT DOWELL" t:phone_number=312-744-8734 t:email=ward03@cityofchicago.org t:website=http://www.cityofchicago.org/city/en/about/wards/03.html t:zipcode=60609 t:state=IL t:city_hall_zipcode=60602 t:city_hall_state=IL t:city_hall_city=CHICAGO t:city=CHICAGO m:ward=3
```

## Meta Commands

```ls
metric m:ward p:integer l:WARD t:dataTypeName=number

entity e:6mw6-krd4 l:"Ward Offices (Deprecated May 2015)" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/6mw6-krd4

property e:6mw6-krd4 t:meta.view v:id=6mw6-krd4 v:category="Facilities & Geographic Boundaries" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Ward Offices (Deprecated May 2015)" v:attribution="City of Chicago"

property e:6mw6-krd4 t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:6mw6-krd4 t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| ward | alderman        | address                  | city    | state | zipcode | ward_phone           | website                                                          | email                       | city_hall_address                   | city_hall_city | city_hall_state | city_hall_zipcode | city_hall_phone      | 
| ==== | =============== | ======================== | ======= | ===== | ======= | ==================== | ================================================================ | =========================== | =================================== | ============== | =============== | ================= | ==================== | 
| 1    | JOE MORENO      | 2058 N WESTERN AVE       | CHICAGO | IL    | 60647   | [773-278-0101, null] | [http://www.cityofchicago.org/city/en/about/wards/01.html, null] | ward01@cityofchicago.org    | 121 N. La Salle Room 300, Office 5  | CHICAGO        | IL              | 60602             | [312-744-3063, null] | 
| 2    | ROBERT FIORETTI | 1319 S STATE ST          | CHICAGO | IL    | 60605   | [312-263-9273, null] | [http://www.cityofchicago.org/city/en/about/wards/02.html, null] | ward02@cityofchicago.org    | 121 N. La Salle Room 300, Office 2  | CHICAGO        | IL              | 60602             | [312-744-6836, null] | 
| 3    | PAT DOWELL      | 5046 S STATE ST          | CHICAGO | IL    | 60609   | [773-373-9273, null] | [http://www.cityofchicago.org/city/en/about/wards/03.html, null] | ward03@cityofchicago.org    | 121 N. La Salle Room 300, Office 3  | CHICAGO        | IL              | 60602             | [312-744-8734, null] | 
| 4    | WILLIAM BURNS   | 435 E 35TH ST            | CHICAGO | IL    | 60616   | [773-536-8103, null] | [http://www.cityofchicago.org/city/en/about/wards/04.html, null] | ward04@cityofchicago.org    | 121 N. La Salle Room 200            | CHICAGO        | IL              | 60602             | [312-744-2690, null] | 
| 5    | LESLIE HAIRSTON | 2325 E 71ST ST           | CHICAGO | IL    | 60649   | [773-324-5555, null] | [http://www.cityofchicago.org/city/en/about/wards/05.html, null] | LHairston@cityofchicago.org | 121 N. La Salle Room 300            | CHICAGO        | IL              | 60602             | [312-744-6832, null] | 
| 6    | RODERICK SAWYER | 463 1/2 E 83RD ST        | CHICAGO | IL    | 60619   | [773-635-0006, null] | [http://www.cityofchicago.org/city/en/about/wards/06.html, null] | service@6thwardchicago.com  | 121 N. La Salle Room 200            | CHICAGO        | IL              | 60602             | [312-744-0670, null] | 
| 7    | SANDI JACKSON   | 7123 S EXCHANGE          | CHICAGO | IL    | 60649   | [773-375-9180, null] | [http://www.cityofchicago.org/city/en/about/wards/07.html, null] | ward07@cityofchicago.org    | 121 N. La Salle Room 207, Office 13 | CHICAGO        | IL              | 60602             | [312-744-6833, null] | 
| 8    | MICHELLE HARRIS | 8539 S COTTAGE GROVE AVE | CHICAGO | IL    | 60619   | [773-874-3300, null] | [http://www.cityofchicago.org/city/en/about/wards/08.html, null] | ward08@cityofchicago.org    | 121 N. La Salle Room 203            | CHICAGO        | IL              | 60602             | [312-744-3075, null] | 
| 9    | ANTHONY BEALE   | 34 E 112TH PL            | CHICAGO | IL    | 60628   | [773-785-1100, null] | [http://www.cityofchicago.org/city/en/about/wards/09.html, null] | ward09@cityofchicago.org    | 121 N. La Salle Room 209, Office 13 | CHICAGO        | IL              | 60602             | [312-744-6838, null] | 
| 10   | JOHN POPE       | 3522 E 106TH ST          | CHICAGO | IL    | 60617   | [773-721-1999, null] | [http://www.cityofchicago.org/city/en/about/wards/10.html, null] | ward10@cityofchicago.org    | 121 N. La Salle Room 300, Office 19 | CHICAGO        | IL              | 60602             | [312-744-3078, null] | 
```