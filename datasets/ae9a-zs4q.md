# Advantage After School Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/advantage-after-school-program) |
| Metadata | [Link](https://data.ny.gov/api/views/ae9a-zs4q) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ae9a-zs4q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ae9a-zs4q/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ae9a-zs4q |
| Name | Advantage After School Program |
| Attribution | NYS Office of Children and Family Services |
| Category | Human Services |
| Tags | after school, advantage after school, afterschool |
| Created | 2013-04-16T15:29:15Z |
| Publication Date | 2016-02-18T14:55:28Z |

## Description

Included in the data set are data elements that will help the public learn about the agencies currently contracting with New York State to provide Advantage After School Program services. The data elements are as follows:Contract Start Date, Contract End Date, Round Number, Contract Number, Contract Amount, School Levels Served (Elementary, Middle School, High School), Average Daily Attendance (MADA), Agency, Site Name, Street Address, Primary City, Zip Code.Also, the asterisks (*) indicate that the contract agency operates the program at two sites.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | contract_start_date | Contract Start Date | calendar_date | calendar_date |
| No       |                | contract_end_date   | Contract End Date   | calendar_date | calendar_date |
| Yes      | series tag     | round_number        | Round Number        | text          | text          |
| Yes      | series tag     | contract            | Contract Number     | text          | text          |
| Yes      | numeric metric | contract_amount     | Contract Amount     | money         | money         |
| Yes      | series tag     | elementary          | Elementary          | text          | text          |
| Yes      | series tag     | middle_school       | Middle School       | text          | text          |
| Yes      | series tag     | high_school         | High School         | text          | text          |
| Yes      | numeric metric | mada_for_site       | MADA for Site       | number        | number        |
| Yes      | series tag     | agency              | Agency              | text          | text          |
| Yes      | series tag     | site_name           | Site Name           | text          | text          |
| Yes      | series tag     | street_address      | Street Address      | text          | text          |
| Yes      | series tag     | primary_city        | Primary City        | text          | text          |
| Yes      | series tag     | zip_code            | ZIP Code            | text          | number        |
```

## Time Field

```ls
Value = contract_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = contract_end_date
```

## Data Commands

```ls
series e:ae9a-zs4q d:2014-10-01T00:00:00.000Z t:zip_code=14516 t:contract=C027297 t:agency="Wayne County Action Program" t:street_address="10456 Salter-Colvin Rd" t:site_name="North Rose/Wolcott Elementary" t:primary_city="North Rose" t:elementary=x t:round_number=9 m:mada_for_site=100 m:contract_amount=126041

series e:ae9a-zs4q d:2014-10-01T00:00:00.000Z t:zip_code=14305 t:contract=C027331 t:high_school=x t:agency="People and Possibilities" t:street_address="4455 Porter Rd" t:site_name="Niagara Falls High School" t:primary_city="Niagara Falls" t:round_number=9 m:mada_for_site=80

series e:ae9a-zs4q d:2014-10-01T00:00:00.000Z t:zip_code=12180 t:contract=C027330 t:agency="Catholic Charities of the Diocese of Albany" t:street_address="110 East Sunnyside Way" t:site_name="Sunnyside Center" t:primary_city=Troy t:elementary=x t:round_number=9 m:mada_for_site=80 m:contract_amount=110000
```

## Meta Commands

```ls
metric m:contract_amount p:integer l:"Contract Amount" d:"Dollar amount of Contract" t:dataTypeName=money

metric m:mada_for_site p:integer l:"MADA for Site" d:"Identifies the Maximum average daily attendance program is contracted to serve" t:dataTypeName=number

entity e:ae9a-zs4q l:"Advantage After School Program" t:attribution="NYS Office of Children and Family Services" t:url=https://data.ny.gov/api/views/ae9a-zs4q

property e:ae9a-zs4q t:meta.view d:2017-06-09T13:56:25.654Z v:id=ae9a-zs4q v:category="Human Services" v:attributionLink=http://www.ocfs.state.ny.us/main/bcm/tanf/aas/contractlistAAS.pdf v:averageRating=0 v:name="Advantage After School Program" v:attribution="NYS Office of Children and Family Services"

property e:ae9a-zs4q t:meta.view.owner d:2017-06-09T13:56:25.654Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ae9a-zs4q t:meta.view.tableauthor d:2017-06-09T13:56:25.654Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ae9a-zs4q t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:56:25.654Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| contract_start_date | contract_end_date   | round_number | contract | contract_amount | elementary | middle_school | high_school | mada_for_site | agency                                        | site_name                       | street_address                  | primary_city   | zip_code | 
| =================== | =================== | ============ | ======== | =============== | ========== | ============= | =========== | ============= | ============================================= | =============================== | =============================== | ============== | ======== | 
| 2014-10-01T00:00:00 | 2019-08-31T00:00:00 | 9            | C027297  | 126041          | x          |               |             | 100           | Wayne County Action Program                   | North Rose/Wolcott Elementary   | 10456 Salter-Colvin Rd          | North Rose     | 14516    | 
| 2014-10-01T00:00:00 | 2019-08-31T00:00:00 | 9            | C027331  |                 |            |               | x           | 80            | People and Possibilities                      | Niagara Falls High School       | 4455 Porter Rd                  | Niagara Falls  | 14305    | 
| 2014-10-01T00:00:00 | 2019-08-31T00:00:00 | 9            | C027330  | 110000          | x          |               |             | 80            | Catholic Charities of the Diocese of Albany   | Sunnyside Center                | 110 East Sunnyside Way          | Troy           | 12180    | 
| 2014-09-01T00:00:00 | 2019-08-31T00:00:00 | 9            | C027310  | 220000          | x          |               |             | 188           | NIA Community Services Network                | PS 330Q                         | 10-08 Northern Boulevard        | Corona         | 11368    | 
| 2014-09-01T00:00:00 | 2019-08-31T00:00:00 | 9            | C027277  | 216435          |            | x             |             | 180           | Economic Opportunity Council of Suffolk, Inc. | William Paca Middle School      | 338 Beacon Drive                | Mastic Beach   | 11951    | 
| 2014-09-01T00:00:00 | 2019-08-31T00:00:00 | 9            | C027336  | 165000          |            | x             | x           | 120           | The Children's Village                        | Greenburgh Eleven MS/HS         | One Echo Hills                  | Dobbs Ferry    | 10522    | 
| 2014-09-01T00:00:00 | 2019-08-31T00:00:00 | 9            | C027302  | 137500          | x          | x             |             | 100           | Maspeth Town Hall, Inc.                       | PS/IS 49                        | 63-6080th Street                | Middle Village | 11379    | 
| 2013-03-01T00:00:00 | 2017-11-14T00:00:00 | 8            | C026716  |                 | X          | X             | X           | 40            | Boys & Girls Clubs of Schenectady, Inc        | Yates Village Boys & Girls Club | 2400 Van Ranken Avenue, Apt E-3 | Schenectady    | 12308    | 
| 2013-03-01T00:00:00 | 2017-11-14T00:00:00 | 8            | C027079* | 220000          |            | X             |             | 100           | Boys & Girls Club of Newburgh, Inc.           | South Middle School             | 33-63 Monument Street           | Newburgh       | 12550    | 
| 2012-11-15T00:00:00 | 2017-11-14T00:00:00 | 8            | C026722  | 110000          |            | X             |             | 80            | Harlem Center for Education, Inc              | IS 171 Patrick Henry School     | 19 East 103rd Street            | New York       | 10029    | 
```