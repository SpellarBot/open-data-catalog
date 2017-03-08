# Directory of NYCHA Community Facilities

## Dataset

* [Dataset URL](https://data.cityofnewyork.us/api/views/crns-fw6u/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/directory-of-nycha-community-facilities-f87c8)
* [Metadata URL](https://data.cityofnewyork.us/api/views/crns-fw6u)
* Id = crns-fw6u
* Name = Directory of NYCHA Community Facilities
* Attribution = New York City Housing Authority (NYCHA)
* [Attribution Link](http://www.nyc.gov/html/nycha/html/ccschtml/communitycenters.shtml)
* Category = Social Services
* Tags = [nycha, nyc housing, community center, community facility, senior center, lunch program, day care, head start, health clinic]
* Created = 2013-03-28T21:01:03Z
* Publication Date = 2013-03-29T13:19:07Z
* Rows Updated = 2013-03-29T13:17:49Z

## Description

Community Facilities (Centers) that are on NYCHA property with programs either sponsored by NYCHA or by a non-NYCHA entity. All programs are open to the public. The file contains development name, address, city, state, zipcode, telephone #, sponsoring organization and contact person. 

This file is updated on a need basis.

## Columns

```ls
| Name           | Field Name     | Data Type | Render Type | Schema Type | Included | 
| ============== | ============== | ========= | =========== | =========== | ======== | 
| TYPE           | type           | text      | text        | series tag  | Yes      | 
| FUNDING AGENCY | funding_agency | text      | text        | series tag  | Yes      | 
| BOROUGH        | borough        | text      | text        | series tag  | Yes      | 
| PROGRAM TYPE   | program_type   | text      | text        | series tag  | Yes      | 
| COUNT AS       | count_as       | text      | text        | series tag  | Yes      | 
| DEVELOPMENT    | development    | text      | text        | series tag  | Yes      | 
| ADDRESS        | address        | text      | text        |             | No       | 
| CITY           | city           | text      | text        | series tag  | Yes      | 
| STATE          | state          | text      | text        | series tag  | Yes      | 
| ZIP            | zip            | text      | text        | series tag  | Yes      | 
| TELEPHONE      | telephone      | text      | text        | series tag  | Yes      | 
| SPONSOR        | sponsor        | text      | text        | series tag  | Yes      | 
| DIRECTOR       | director       | text      | text        | series tag  | Yes      | 
| MONTH          | month          | text      | text        |             | No       | 
| YEAR           | year           | number    | text        |             | No       | 
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = address,month,year
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:crns-fw6u l:"Directory of NYCHA Community Facilities" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/crns-fw6u

property e:crns-fw6u t:meta.view d:2017-03-08T02:22:27.237Z v:id=crns-fw6u v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/nycha/html/ccschtml/communitycenters.shtml v:averageRating=0 v:name="Directory of NYCHA Community Facilities" v:attribution="New York City Housing Authority (NYCHA)"

property e:crns-fw6u t:meta.view.owner d:2017-03-08T02:22:27.237Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:crns-fw6u t:meta.view.tableauthor d:2017-03-08T02:22:27.237Z v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```