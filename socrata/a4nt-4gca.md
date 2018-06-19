# Library Branches

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/library-branches-ab001) |
| Metadata | [Link](https://data.lacity.org/api/views/a4nt-4gca) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/a4nt-4gca/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/a4nt-4gca/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | a4nt-4gca |
| Name | Library Branches |
| Category | A Livable and Sustainable City |
| Tags | library branches, contact information |
| Created | 2014-05-27T19:21:14Z |
| Publication Date | 2014-05-28T20:30:34Z |

## Description

Name, Location, Council District, Phone Number and Email Address for all 72 library branches. Static data.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | branch_name      | Branch Name      | text      | text        |
| Yes      | series tag  | phone_number     | Phone Number     | text      | text        |
| Yes      | series tag  | email            | Email            | text      | text        |
| Yes      | series tag  | council_district | Council District | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a4nt-4gca d:2014-05-27T12:21:21.000Z t:phone_number="(310) 534-9520" t:email=harbor@lapl.org t:council_district=15 t:branch_name="Harbor City - Harbor Gateway" m:row_number.a4nt-4gca=1

series e:a4nt-4gca d:2014-05-27T12:21:21.000Z t:phone_number="(310) 548-7779" t:email=spedro@lapl.org t:council_district=15 t:branch_name="San Pedro Regional" m:row_number.a4nt-4gca=2

series e:a4nt-4gca d:2014-05-27T12:21:21.000Z t:phone_number="(323) 789-2850" t:email=wattsl@lapl.org t:council_district=15 t:branch_name="Alma Reaves Woods - Watts" m:row_number.a4nt-4gca=3
```

## Meta Commands

```ls
metric m:row_number.a4nt-4gca p:long l:"Row Number"

entity e:a4nt-4gca l:"Library Branches" t:url=https://data.lacity.org/api/views/a4nt-4gca

property e:a4nt-4gca t:meta.view v:id=a4nt-4gca v:category="A Livable and Sustainable City" v:attributionLink=http://www.lapl.org v:averageRating=0 v:name="Library Branches"

property e:a4nt-4gca t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:a4nt-4gca t:meta.view.owner v:id=ysts-hp3n v:profileImageUrlMedium=/api/users/ysts-hp3n/profile_images/THUMB v:profileImageUrlLarge=/api/users/ysts-hp3n/profile_images/LARGE v:screenName="Library OpenData" v:profileImageUrlSmall=/api/users/ysts-hp3n/profile_images/TINY v:displayName="Library OpenData"

property e:a4nt-4gca t:meta.view.tableauthor v:id=ysts-hp3n v:profileImageUrlMedium=/api/users/ysts-hp3n/profile_images/THUMB v:profileImageUrlLarge=/api/users/ysts-hp3n/profile_images/LARGE v:screenName="Library OpenData" v:profileImageUrlSmall=/api/users/ysts-hp3n/profile_images/TINY v:roleName=publisher v:displayName="Library OpenData"
```

## Top Records

```ls
| :updated_at | branch_name                  | phone_number   | email           | council_district | 
| =========== | ============================ | ============== | =============== | ================ | 
| 1401193281  | Harbor City - Harbor Gateway | (310) 534-9520 | harbor@lapl.org | 15               | 
| 1401193281  | San Pedro Regional           | (310) 548-7779 | spedro@lapl.org | 15               | 
| 1401193281  | Alma Reaves Woods - Watts    | (323) 789-2850 | wattsl@lapl.org | 15               | 
| 1401193281  | Wilmington                   | (310) 834-1082 | wmngtn@lapl.org | 15               | 
| 1401193281  | John C. Fremont              | (323) 962-3521 | jcfrmt@lapl.org | 4                | 
| 1401193281  | Angeles Mesa                 | (323) 292-4328 | angmsa@lapl.org | 8                | 
| 1401193281  | Arroyo Seco Regional         | (323) 255-0537 | ayosco@lapl.org | 1                | 
| 1401193281  | Ascot                        | (323) 759-4817 | ascott@lapl.org | 9                | 
| 1401193281  | Atwater Village              | (323) 664-1353 | atwatr@lapl.org | 13               | 
| 1401193281  | Baldwin Hills                | (323) 733-1196 | bldhls@lapl.org | 10               | 
```