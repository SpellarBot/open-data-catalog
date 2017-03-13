# Directory of NYCHA Community Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-nycha-community-facilities-f87c8) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/crns-fw6u) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/crns-fw6u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/crns-fw6u/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | crns-fw6u |
| Name | Directory of NYCHA Community Facilities |
| Attribution | New York City Housing Authority (NYCHA) |
| Category | Social Services |
| Tags | nycha, nyc housing, community center, community facility, senior center, lunch program, day care, head start, health clinic |
| Created | 2013-03-28T21:01:03Z |
| Publication Date | 2013-03-29T13:19:07Z |
| Rows Updated | 2013-03-29T13:17:49Z |

## Description

Community Facilities (Centers) that are on NYCHA property with programs either sponsored by NYCHA or by a non-NYCHA entity. All programs are open to the public. The file contains development name, address, city, state, zipcode, telephone #, sponsoring organization and contact person. 

This file is updated on a need basis.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | type           | TYPE           | text      | text        |
| Yes      | series tag  | funding_agency | FUNDING AGENCY | text      | text        |
| Yes      | series tag  | borough        | BOROUGH        | text      | text        |
| Yes      | series tag  | program_type   | PROGRAM TYPE   | text      | text        |
| Yes      | series tag  | count_as       | COUNT AS       | text      | text        |
| Yes      | series tag  | development    | DEVELOPMENT    | text      | text        |
| No       |             | address        | ADDRESS        | text      | text        |
| Yes      | series tag  | city           | CITY           | text      | text        |
| Yes      | series tag  | state          | STATE          | text      | text        |
| Yes      | series tag  | zip            | ZIP            | text      | text        |
| Yes      | series tag  | telephone      | TELEPHONE      | text      | text        |
| Yes      | series tag  | sponsor        | SPONSOR        | text      | text        |
| Yes      | series tag  | director       | DIRECTOR       | text      | text        |
| No       |             | month          | MONTH          | text      | text        |
| No       |             | year           | YEAR           | number    | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = address,month,year
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:crns-fw6u l:"Directory of NYCHA Community Facilities" t:attribution="New York City Housing Authority (NYCHA)" t:url=https://data.cityofnewyork.us/api/views/crns-fw6u

property e:crns-fw6u t:meta.view v:id=crns-fw6u v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/nycha/html/ccschtml/communitycenters.shtml v:averageRating=0 v:name="Directory of NYCHA Community Facilities" v:attribution="New York City Housing Authority (NYCHA)"

property e:crns-fw6u t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:crns-fw6u t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```