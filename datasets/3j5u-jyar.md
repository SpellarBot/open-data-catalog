# City Court Warrants

## Dataset

* [Dataset URL](https://data.brla.gov/api/views/3j5u-jyar/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/city-court-warrants)
* [Metadata URL](https://data.brla.gov/api/views/3j5u-jyar)
* Id = 3j5u-jyar
* Name = City Court Warrants
* Attribution = Baton Rouge City Court
* [Attribution Link](http://brgov.com/dept/citycourt)
* Category = Public Safety
* Tags = [warrants, court]
* Created = 2014-12-17T16:22:27Z
* Publication Date = 2015-07-14T15:32:39Z
* Rows Updated = 2017-03-05T08:01:09Z

## Description

Listing of active warrants for Baton Rouge City Court.

Warrants are posted to the site daily, however it may take up to 7-10 days for information processed in court to be reflected on the site.  If you have questions please contact the Criminal Traffic Division via email at traffic@brgov.com or call (225) 389-5278.

This lookup is not confirmation of an active warrant.  All City Court warrants should be confirmed by the official court file.  Please contact the City Constable's Office at 389-3889 or 389-3004 for confirmation.

## Columns

```ls
| Name        | Field Name | Data Type     | Render Type   | Schema Type    | Included | 
| =========== | ========== | ============= | ============= | ============== | ======== | 
| NAME        | name       | text          | text          | series tag     | Yes      | 
| CITY        | add3       | text          | text          | series tag     | Yes      | 
| STATE       | state      | text          | text          | series tag     | Yes      | 
| ZIPCODE     | zip        | text          | text          | series tag     | Yes      | 
| RACE        | race       | number        | text          | numeric metric | Yes      | 
| SEX         | sex        | number        | text          | numeric metric | Yes      | 
| YOB         | dob        | number        | text          | numeric metric | Yes      | 
| DOA         | doa        | calendar_date | calendar_date | time           | Yes      | 
| FILE NUMBER | fileno     | text          | text          | series tag     | Yes      | 
| DIV         | div        | text          | text          | series tag     | Yes      | 
| CASE TYPE   | type       | text          | text          | series tag     | Yes      | 
```

## Time Field

```ls
Value = doa
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

property e:3j5u-jyar t:meta.view d:2017-03-07T20:24:53.264Z v:id=3j5u-jyar v:category="Public Safety" v:attributionLink=http://brgov.com/dept/citycourt v:averageRating=0 v:name="City Court Warrants" v:attribution="Baton Rouge City Court"

property e:3j5u-jyar t:meta.view.license d:2017-03-07T20:24:53.264Z v:name="Public Domain"

property e:3j5u-jyar t:meta.view.owner d:2017-03-07T20:24:53.264Z v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"

property e:3j5u-jyar t:meta.view.tableauthor d:2017-03-07T20:24:53.264Z v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```