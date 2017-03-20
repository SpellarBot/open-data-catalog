# Election Maps - Statewide

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-maps-statewide) |
| Metadata | [Link](https://data.hawaii.gov/api/views/qjpr-gyut) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/qjpr-gyut/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/qjpr-gyut/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | qjpr-gyut |
| Name | Election Maps - Statewide |
| Created | 2015-02-27T20:54:58Z |
| Publication Date | 2016-01-25T20:27:26Z |
| Rows Updated | 2016-01-25T20:25:43Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | map_name    | MAP NAME    | html      | html        |
| Yes      | series tag  | description | DESCRIPTION | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qjpr-gyut d:2016-01-25T12:25:37.000Z t:description="Hawaii Island" t:map_name="<a target=""_blank"" href=""http://files.hawaii.gov/elections/files/maps/electionmaps/ISLAND_OF_HAWAII.pdf""> Hawaii Map: Island view</a>" m:row_number.qjpr-gyut=1

series e:qjpr-gyut d:2016-01-25T12:25:37.000Z t:description="Waipio - Kohala Mountain" t:map_name="<a target=""_blank"" href=""http://files.hawaii.gov/elections/files/maps/electionmaps/HAWAII1.pdf""> Hawaii #1: Waipio - Kohala Mountain</a>" m:row_number.qjpr-gyut=2

series e:qjpr-gyut d:2016-01-25T12:25:37.000Z t:description=Hilo t:map_name="<a target=""_blank"" href=""http://files.hawaii.gov/elections/files/maps/electionmaps/HAWAII2.pdf""> Hawaii #2: Hilo</a>" m:row_number.qjpr-gyut=3
```

## Meta Commands

```ls
metric m:row_number.qjpr-gyut p:long l:"Row Number"

entity e:qjpr-gyut l:"Election Maps - Statewide" t:url=https://data.hawaii.gov/api/views/qjpr-gyut

property e:qjpr-gyut t:meta.view v:id=qjpr-gyut v:averageRating=0 v:name="Election Maps - Statewide"

property e:qjpr-gyut t:meta.view.owner v:id=a7h7-u2zq v:screenName="Office of Elections" v:roleName=publisher v:displayName="Office of Elections"

property e:qjpr-gyut t:meta.view.tableauthor v:id=a7h7-u2zq v:screenName="Office of Elections" v:roleName=publisher v:displayName="Office of Elections"
```