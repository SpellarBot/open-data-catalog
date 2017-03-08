# Campaign Finance - Ballot Measure Committee Name Mapping - November 4 2014 Election

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/dt7v-mz6s/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/campaign-finance-ballot-measure-committee-name-mapping-november-4-2014-election-a9735)
* [Metadata URL](https://data.sfgov.org/api/views/dt7v-mz6s)
* Id = dt7v-mz6s
* Name = Campaign Finance - Ballot Measure Committee Name Mapping - November 4 2014 Election
* Attribution = San Francisco Ethics Commission
* [Attribution Link](http://www.sfethics.org)
* Category = City Management and Ethics
* Tags = [campaign ballot measure committee]
* Created = 2014-10-10T15:59:23Z
* Publication Date = 2014-10-14T17:36:01Z
* Rows Updated = 2014-10-14T17:35:56Z

## Description

Mapping of reported ballot measure names and ID numbers to the corresponding measures on the November 4, 2014 Election.  Built for use by SF Ethics Commission Ballot Measure Dashboards and SF Brigade projects.

## Columns

```ls
| Name               | Field Name         | Data Type | Render Type | Schema Type | Included | 
| ================== | ================== | ========= | =========== | =========== | ======== | 
| updated_at         | :updated_at        | meta_data | meta_data   | time        | No       | 
| FilerID            | filerid            | text      | text        | series tag  | Yes      | 
| Reportered FilerID | reportered_filerid | text      | text        | series tag  | Yes      | 
| Filer Naml         | filer_naml         | text      | text        | series tag  | Yes      | 
| Measure            | measure            | text      | text        | series tag  | Yes      | 
| Position           | position           | text      | text        | series tag  | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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





```

## Meta Commands

```ls
entity e:dt7v-mz6s l:"Campaign Finance - Ballot Measure Committee Name Mapping - November 4 2014 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/dt7v-mz6s

property e:dt7v-mz6s t:meta.view d:2017-03-07T16:44:25.860Z v:id=dt7v-mz6s v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Ballot Measure Committee Name Mapping - November 4 2014 Election" v:attribution="San Francisco Ethics Commission"

property e:dt7v-mz6s t:meta.view.license d:2017-03-07T16:44:25.860Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:dt7v-mz6s t:meta.view.owner d:2017-03-07T16:44:25.860Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"

property e:dt7v-mz6s t:meta.view.tableauthor d:2017-03-07T16:44:25.860Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```