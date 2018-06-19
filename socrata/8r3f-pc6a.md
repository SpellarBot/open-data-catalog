# Colleges in San Francisco (2011)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/colleges-in-san-francisco-2011) |
| Metadata | [Link](https://data.sfgov.org/api/views/8r3f-pc6a) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/8r3f-pc6a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/8r3f-pc6a/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 8r3f-pc6a |
| Name | Colleges in San Francisco (2011) |
| Attribution | National Center for Education Statistics |
| Category | Economy and Community |
| Created | 2016-07-17T19:38:23Z |
| Publication Date | 2016-07-17T19:48:33Z |

## Description

Public and private colleges within San Francisco from National Center of Education Statistics data. As of 2011. You can get updated institutional characteristics data at https://nces.ed.gov/ipeds/datacenter/DataFiles.aspx

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       |             | id          | ID          | text      | number      |
| Yes      | series tag  | institution | Institution | text      | text        |
| Yes      | series tag  | campus      | Campus      | text      | text        |
| No       |             | address     | Address     | text      | text        |
| Yes      | series tag  | phone       | Phone       | phone     | phone       |
| Yes      | series tag  | web_address | Web Address | url       | url         |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id,address
```

## Data Commands

```ls
series e:8r3f-pc6a d:2011-01-01T00:00:00.000Z t:web_address=http://www.uchastings.edu t:phone_number=4155654600 t:institution="University of California Hastings College of Law" m:row_number.8r3f-pc6a=1

series e:8r3f-pc6a d:2011-01-01T00:00:00.000Z t:web_address=http://www.uchastings.edu t:phone_number=4155654600 t:institution="University of California Hastings College of Law" m:row_number.8r3f-pc6a=2

series e:8r3f-pc6a d:2011-01-01T00:00:00.000Z t:web_address=http://www.uchastings.edu t:phone_number=4155654600 t:institution="University of California Hastings College of Law" m:row_number.8r3f-pc6a=3
```

## Meta Commands

```ls
metric m:row_number.8r3f-pc6a p:long l:"Row Number"

entity e:8r3f-pc6a l:"Colleges in San Francisco (2011)" t:attribution="National Center for Education Statistics" t:url=https://data.sfgov.org/api/views/8r3f-pc6a

property e:8r3f-pc6a t:meta.view v:id=8r3f-pc6a v:category="Economy and Community" v:attributionLink=https://nces.ed.gov/ipeds/datacenter/DataFiles.aspx v:averageRating=0 v:name="Colleges in San Francisco (2011)" v:attribution="National Center for Education Statistics"

property e:8r3f-pc6a t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:8r3f-pc6a t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:8r3f-pc6a t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| id | institution                                      | campus | address            | phone              | web_address                       | 
| == | ================================================ | ====== | ================== | ================== | ================================= | 
| 22 | University of California Hastings College of Law |        | 100 McAllister St  | [4155654600, null] | [http://www.uchastings.edu, null] | 
| 23 | University of California Hastings College of Law |        | 198 McAllister St  | [4155654600, null] | [http://www.uchastings.edu, null] | 
| 24 | University of California Hastings College of Law |        | 376 Larkin St      | [4155654600, null] | [http://www.uchastings.edu, null] | 
| 25 | Academy of Art University                        |        | 2300 Stockton St   | [null, null]       | [null, null]                      | 
| 26 | Academy of Art University                        |        | 701 Chestnut St    | [null, null]       | [null, null]                      | 
| 27 | Academy of Art University                        |        | 1849 Washington St | [null, null]       | [null, null]                      | 
| 28 | Academy of Art University                        |        | 740 Taylor St      | [null, null]       | [null, null]                      | 
| 29 | Academy of Art University                        |        | 2151 Van Ness Ave  | [null, null]       | [null, null]                      | 
| 30 | Academy of Art University                        |        | 688 Sutter St      | [null, null]       | [null, null]                      | 
| 31 | Academy of Art University                        |        | 625 Sutter St      | [null, null]       | [null, null]                      | 
```