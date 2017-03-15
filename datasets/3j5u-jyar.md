# City Court Warrants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-court-warrants) |
| Metadata | [Link](https://data.brla.gov/api/views/3j5u-jyar) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/3j5u-jyar/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/3j5u-jyar/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | 3j5u-jyar |
| Name | City Court Warrants |
| Attribution | Baton Rouge City Court |
| Category | Public Safety |
| Tags | warrants, court |
| Created | 2014-12-17T16:22:27Z |
| Publication Date | 2015-07-14T15:32:39Z |
| Rows Updated | 2017-03-13T07:00:36Z |

## Description

Listing of active warrants for Baton Rouge City Court.

Warrants are posted to the site daily, however it may take up to 7-10 days for information processed in court to be reflected on the site.  If you have questions please contact the Criminal Traffic Division via email at traffic@brgov.com or call (225) 389-5278.

This lookup is not confirmation of an active warrant.  All City Court warrants should be confirmed by the official court file.  Please contact the City Constable's Office at 389-3889 or 389-3004 for confirmation.

## Columns

```ls
| Included | Schema Type    | Field Name | Name        | Data Type     | Render Type   |
| ======== | ============== | ========== | =========== | ============= | ============= |
| Yes      | series tag     | name       | NAME        | text          | text          |
| Yes      | series tag     | add3       | CITY        | text          | text          |
| Yes      | series tag     | state      | STATE       | text          | text          |
| Yes      | series tag     | zip        | ZIPCODE     | text          | text          |
| Yes      | series tag     | race       | RACE        | text          | text          |
| Yes      | series tag     | sex        | SEX         | text          | text          |
| Yes      | numeric metric | dob        | YOB         | number        | text          |
| Yes      | time           | doa        | DOA         | calendar_date | calendar_date |
| Yes      | series tag     | fileno     | FILE NUMBER | text          | text          |
| Yes      | series tag     | div        | DIV         | text          | text          |
| Yes      | series tag     | type       | CASE TYPE   | text          | text          |
```

## Time Field

```ls
Value = doa
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3j5u-jyar d:2015-08-10T00:00:00.000Z t:zip=70714 t:sex=M t:fileno=PP00010364 t:name="GRADNEY, TORY" t:div=D t:state=LA t:type=PP t:race=B t:add3=BAKER m:dob=1976

series e:3j5u-jyar d:2016-11-14T00:00:00.000Z t:zip=70807 t:sex=M t:fileno=BR02196968 t:name="CHAPMAN, ARTHUR  D" t:div=D t:state=LA t:type=CCTRAF t:race=B t:add3="BATON ROUGE" m:dob=1994

series e:3j5u-jyar d:2016-07-11T00:00:00.000Z t:zip=70810 t:sex=F t:fileno=BR02165956 t:name="BARROW, STEPHANIE  C" t:div=A t:state=LA t:type=CCTRAF t:race=B t:add3="BATON ROUGE" m:dob=1996
```

## Meta Commands

```ls
metric m:dob p:integer l:YOB d:"Defendant's year of birth" t:dataTypeName=number

entity e:3j5u-jyar l:"City Court Warrants" t:attribution="Baton Rouge City Court" t:url=https://data.brla.gov/api/views/3j5u-jyar

property e:3j5u-jyar t:meta.view v:id=3j5u-jyar v:category="Public Safety" v:attributionLink=http://brgov.com/dept/citycourt v:averageRating=0 v:name="City Court Warrants" v:attribution="Baton Rouge City Court"

property e:3j5u-jyar t:meta.view.license v:name="Public Domain"

property e:3j5u-jyar t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"

property e:3j5u-jyar t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```