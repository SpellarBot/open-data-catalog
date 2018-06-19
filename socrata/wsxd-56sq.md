# Statement of Economic Interests Database (SEI) (Form 700) - Non-Filers - April 10, 2015 Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statement-of-economic-interests-database-sei-form-700-non-filers-169f1) |
| Metadata | [Link](https://data.sfgov.org/api/views/wsxd-56sq) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wsxd-56sq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wsxd-56sq/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wsxd-56sq |
| Name | Statement of Economic Interests Database (SEI) (Form 700) - Non-Filers - April 10, 2015 Report |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | statement of economic interests, sei, form 700, ethics, conflict of interest, non-filer |
| Created | 2014-06-27T22:14:26Z |
| Publication Date | 2015-05-19T18:13:52Z |

## Description

The filers listed in the table linked below did not file the required Statement of Economic Interests (Form 700) as of April 10, 2015. The annual statements are due on April 1st of each year.

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
series e:wsxd-56sq d:2015-04-01T00:00:00.000Z t:name="Alloy, Jonathan" t:agency="Citizens General Obligation Bond Oversight Committee" t:type_of_filing="Annual Form 700" m:row_number.wsxd-56sq=1

series e:wsxd-56sq d:2015-04-01T00:00:00.000Z t:name="Buell, Mark" t:agency="Recreation & Parks Commission" t:type_of_filing="Annual Form 700" m:row_number.wsxd-56sq=2

series e:wsxd-56sq d:2015-04-01T00:00:00.000Z t:name="Buscovich, Patrick" t:agency="Board of Examiners" t:type_of_filing="Annual Form 700" m:row_number.wsxd-56sq=3
```

## Meta Commands

```ls
metric m:row_number.wsxd-56sq p:long l:"Row Number"

entity e:wsxd-56sq l:"Statement of Economic Interests Database (SEI) (Form 700) - Non-Filers - April 10, 2015 Report" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/wsxd-56sq

property e:wsxd-56sq t:meta.view v:id=wsxd-56sq v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Statement of Economic Interests Database (SEI) (Form 700) - Non-Filers - April 10, 2015 Report" v:attribution="San Francisco Ethics Commission"

property e:wsxd-56sq t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wsxd-56sq t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:wsxd-56sq t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| name               | agency                                               | type_of_filing  | due_date            | notes | 
| ================== | ==================================================== | =============== | =================== | ===== | 
| Alloy, Jonathan    | Citizens General Obligation Bond Oversight Committee | Annual Form 700 | 2015-04-01T00:00:00 |       | 
| Buell, Mark        | Recreation & Parks Commission                        | Annual Form 700 | 2015-04-01T00:00:00 |       | 
| Buscovich, Patrick | Board of Examiners                                   | Annual Form 700 | 2015-04-01T00:00:00 |       | 
| Caracciolo, Dan    | Board of Examiners                                   | Annual Form 700 | 2015-04-01T00:00:00 |       | 
| Chrisco, Aaron     | Workforce Investment Board                           | Annual Form 700 | 2015-04-01T00:00:00 |       | 
| Clinch, Kevin      | Building Inspection Commission                       | Annual Form 700 | 2015-04-01T00:00:00 |       | 
| Coulter, Penny     | Fine Arts Museums                                    | Annual Form 700 | 2015-04-01T00:00:00 |       | 
| Davis, Sheryl      | Human Rights Commission                              | Annual Form 700 | 2015-04-01T00:00:00 |       | 
| Durgy, Michelle    | Office of the Treasurer/Tax Collector                | Annual Form 700 | 2015-04-01T00:00:00 |       | 
| Fong, Jacalyn      | Housing Authority Commission                         | Annual Form 700 | 2015-04-01T00:00:00 |       | 
```