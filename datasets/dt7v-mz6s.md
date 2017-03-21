# Campaign Finance - Ballot Measure Committee Name Mapping - November 4 2014 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-ballot-measure-committee-name-mapping-november-4-2014-election-a9735) |
| Metadata | [Link](https://data.sfgov.org/api/views/dt7v-mz6s) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/dt7v-mz6s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/dt7v-mz6s/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | dt7v-mz6s |
| Name | Campaign Finance - Ballot Measure Committee Name Mapping - November 4 2014 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign ballot measure committee |
| Created | 2014-10-10T15:59:23Z |
| Publication Date | 2014-10-14T17:36:01Z |
| Rows Updated | 2014-10-14T17:35:56Z |

## Description

Mapping of reported ballot measure names and ID numbers to the corresponding measures on the November 4, 2014 Election.  Built for use by SF Ethics Commission Ballot Measure Dashboards and SF Brigade projects.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | filerid            | FilerID            | text      | text        |
| Yes      | series tag  | reportered_filerid | Reportered FilerID | text      | text        |
| Yes      | series tag  | filer_naml         | Filer Naml         | text      | text        |
| Yes      | series tag  | measure            | Measure            | text      | text        |
| Yes      | series tag  | position           | Position           | text      | text        |
```

## Time Field

```ls
Value = 
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dt7v-mz6s d:2014-01-01T00:00:00.000Z t:position=Support t:measure="Measure J - Minimum Wage" t:reportered_filerid=1367310 t:filerid=1367310 t:filer_naml="Campaign for a Fair Economy and Higher Wages, sponsored by community and labor organizations" m:row_number.dt7v-mz6s=1

series e:dt7v-mz6s d:2014-01-01T00:00:00.000Z t:position=Support t:measure="Measure J - Minimum Wage" t:reportered_filerid=1367310 t:filerid=1367310 t:filer_naml="Campaign for a Fair Economy and Higher Wages, sponsored by community and labor organizations, Yes on Proposition J" m:row_number.dt7v-mz6s=2

series e:dt7v-mz6s d:2014-01-01T00:00:00.000Z t:position=Support t:measure="Measure C - Children and Youth Fund" t:reportered_filerid=1367736 t:filerid=1367736 t:filer_naml="Children and Family First Committee" m:row_number.dt7v-mz6s=3
```

## Meta Commands

```ls
metric m:row_number.dt7v-mz6s p:long l:"Row Number"

entity e:dt7v-mz6s l:"Campaign Finance - Ballot Measure Committee Name Mapping - November 4 2014 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/dt7v-mz6s

property e:dt7v-mz6s t:meta.view v:id=dt7v-mz6s v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Ballot Measure Committee Name Mapping - November 4 2014 Election" v:attribution="San Francisco Ethics Commission"

property e:dt7v-mz6s t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:dt7v-mz6s t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:dt7v-mz6s t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```