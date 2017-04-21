# Statement of Economic Interests Database (SEI) (Form 700) - Non-Filers - April 10, 2016 Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statement-of-economic-interests-database-sei-form-700-non-filers-april-10-2016-report) |
| Metadata | [Link](https://data.sfgov.org/api/views/vp5d-6nuw) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/vp5d-6nuw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/vp5d-6nuw/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | vp5d-6nuw |
| Name | Statement of Economic Interests Database (SEI) (Form 700) - Non-Filers - April 10, 2016 Report |
| Attribution | San Francisco Ethics Commission |
| Tags | statement of economic interests, sei, form 700, ethics, conflict of interest, non-filer |
| Created | 2016-04-27T20:43:58Z |
| Publication Date | 2016-04-27T21:52:00Z |

## Description

The filers listed in the table linked below did not file the required Statement of Economic Interests (Form 700) as of April 10, 2016. The annual statements are due on April 1st of each year.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | name           | Name           | text          | text          |
| Yes      | series tag  | agency         | Agency         | text          | text          |
| Yes      | series tag  | type_of_filing | Type of Filing | text          | text          |
| Yes      | time        | due_date       | Due Date       | calendar_date | calendar_date |
| Yes      | series tag  | notes          | Notes          | text          | text          |
```

## Time Field

```ls
Value = due_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:vp5d-6nuw d:2016-04-01T00:00:00.000Z t:name="Abe, Calvin" t:agency="Residential Rent Stabilization and Arbitration Board" t:type_of_filing="Annual Form 700" m:row_number.vp5d-6nuw=1

series e:vp5d-6nuw d:2016-04-01T00:00:00.000Z t:name="Bailey, Colin" t:agency="Fine Arts Museums" t:type_of_filing="Annual Form 700" m:row_number.vp5d-6nuw=2

series e:vp5d-6nuw d:2016-04-01T00:00:00.000Z t:name="Barnes, William" t:agency="Workforce Investment Board" t:type_of_filing="Annual Form 700" m:row_number.vp5d-6nuw=3
```

## Meta Commands

```ls
metric m:row_number.vp5d-6nuw p:long l:"Row Number"

entity e:vp5d-6nuw l:"Statement of Economic Interests Database (SEI) (Form 700) - Non-Filers - April 10, 2016 Report" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/vp5d-6nuw

property e:vp5d-6nuw t:meta.view v:id=vp5d-6nuw v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Statement of Economic Interests Database (SEI) (Form 700) - Non-Filers - April 10, 2016 Report" v:attribution="San Francisco Ethics Commission"

property e:vp5d-6nuw t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:vp5d-6nuw t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:vp5d-6nuw t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| name               | agency                                               | type_of_filing  | due_date            | notes | 
| ================== | ==================================================== | =============== | =================== | ===== | 
| Abe, Calvin        | Residential Rent Stabilization and Arbitration Board | Annual Form 700 | 2016-04-01T00:00:00 |       | 
| Bailey, Colin      | Fine Arts Museums                                    | Annual Form 700 | 2016-04-01T00:00:00 |       | 
| Barnes, William    | Workforce Investment Board                           | Annual Form 700 | 2016-04-01T00:00:00 |       | 
| Bashford, Wilkes   | War Memorial San Francisco                           | Annual Form 700 | 2016-04-01T00:00:00 |       | 
| Bressan, Thomas    | Residential Users Appeal Board                       | Annual Form 700 | 2016-04-01T00:00:00 |       | 
| Buscovich, Patrick | Board of Examiners                                   | Annual Form 700 | 2016-04-01T00:00:00 |       | 
| Calhoun, Jack      | Fine Arts Museums                                    | Annual Form 700 | 2016-04-01T00:00:00 |       | 
| Chopra, Rishi      | Sunshine Ordinance Task Force                        | Annual Form 700 | 2016-04-01T00:00:00 |       | 
| Coulter, Penny     | Fine Arts Museums                                    | Annual Form 700 | 2016-04-01T00:00:00 |       | 
| Covington, Francee | Fire Commission                                      | Annual Form 700 | 2016-04-01T00:00:00 |       | 
```