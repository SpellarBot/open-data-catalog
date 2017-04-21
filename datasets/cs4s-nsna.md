# Workforce Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/workforce-centers-dd480) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cs4s-nsna) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cs4s-nsna/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cs4s-nsna/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cs4s-nsna |
| Name | Workforce Centers |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | workforce, facilities, gis, human services, family and support services |
| Created | 2010-12-22T22:28:23Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

City of Chicago's Workforce Center locations, hours of operation and contact information.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | site_name          | SITE NAME          | text      | text        |
| Yes      | series tag  | hours_of_operation | HOURS OF OPERATION | text      | text        |
| No       |             | address            | ADDRESS            | text      | text        |
| Yes      | series tag  | city               | CITY               | text      | text        |
| Yes      | series tag  | state              | STATE              | text      | text        |
| Yes      | series tag  | zip                | ZIP                | text      | text        |
| Yes      | series tag  | phone              | PHONE              | text      | text        |
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
series e:cs4s-nsna d:2010-12-22T14:29:49.000Z t:zip=60612 t:phone=773-722-3885 t:hours_of_operation="Mon - Fri 9:00 a.m. to 5:00 p.m." t:state=IL t:site_name="Garfield Workforce Center" t:city=Chicago m:row_number.cs4s-nsna=1

series e:cs4s-nsna d:2010-12-22T14:29:49.000Z t:zip=60608 t:phone=312-994-8300 t:hours_of_operation="Mon - Fri 8:30 a.m. to 4:30 p.m." t:state=IL t:site_name="Pilsen Workforce Center" t:city=Chicago m:row_number.cs4s-nsna=2

series e:cs4s-nsna d:2010-12-22T14:29:49.000Z t:zip=60652 t:phone=773-884-7000 t:hours_of_operation="Mon - Fri 8:30 a.m. to 5:00 p.m." t:state=IL t:site_name="Southwest Workforce Center" t:city=Chicago m:row_number.cs4s-nsna=3
```

## Meta Commands

```ls
metric m:row_number.cs4s-nsna p:long l:"Row Number"

entity e:cs4s-nsna l:"Workforce Centers" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/cs4s-nsna

property e:cs4s-nsna t:meta.view v:id=cs4s-nsna v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Workforce Centers" v:attribution="City of Chicago"

property e:cs4s-nsna t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:cs4s-nsna t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | site_name                  | hours_of_operation               | address                    | city    | state | zip   | phone        | 
| =========== | ========================== | ================================ | ========================== | ======= | ===== | ===== | ============ | 
| 1293028189  | Garfield Workforce Center  | Mon - Fri 9:00 a.m. to 5:00 p.m. | 10 S. Kedzie               | Chicago | IL    | 60612 | 773-722-3885 | 
| 1293028189  | Pilsen Workforce Center    | Mon - Fri 8:30 a.m. to 4:30 p.m. | 1700 W. 18th               | Chicago | IL    | 60608 | 312-994-8300 | 
| 1293028189  | Southwest Workforce Center | Mon - Fri 8:30 a.m. to 5:00 p.m. | 7500 S. Pulaski, Bldg 100  | Chicago | IL    | 60652 | 773-884-7000 | 
| 1293028189  | Northside Workforce Center | Mon - Fri 8:30 a.m. to 5:00 p.m. | 4740 N. Sheridan           | Chicago | IL    | 60640 | 773-334-4747 | 
| 1293028189  | Mid-South Workforce Center | Mon - Fri 8:30 a.m. to 5:00 p.m. | 4314 S. Cottage Grove Ave. | Chicago | IL    | 60653 | 773-538-5627 | 
```