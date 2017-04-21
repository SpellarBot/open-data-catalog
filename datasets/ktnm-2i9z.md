# Parks and Recreation Rating (1986 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parks-and-recreation-rating-1986-present) |
| Metadata | [Link](https://data.nola.gov/api/views/ktnm-2i9z) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/ktnm-2i9z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/ktnm-2i9z/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | ktnm-2i9z |
| Name | Parks and Recreation Rating (1986 - Present) |
| Attribution | The University of New Orleans Survey Research Center's Quality of Life Survey |
| Category | Recreation and Culture |
| Created | 2015-03-19T18:16:51Z |
| Publication Date | 2015-11-05T20:22:10Z |

## Description

This data comes from the Quality of Life Survey conducted by the University of New Orleans Survey Research Center. The Center began its Quality of Life series in 1986. Since then the quality of life and government services in Jefferson and Orleans parishes have been assessed roughly every other year. The results of the Quality of Life surveys represent the perceptions and opinions of the registered voters of the two parishes. The results are not objective measures of the quality of services.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | row_id                   | Row_ID                   | text          | text          |
| No       |                | year                     | Year                     | number        | number        |
| Yes      | time           | date                     | Date                     | calendar_date | calendar_date |
| Yes      | series tag     | parish                   | Parish                   | text          | text          |
| Yes      | numeric metric | very_good                | Very_good                | number        | number        |
| Yes      | numeric metric | good                     | Good                     | number        | number        |
| Yes      | numeric metric | fair                     | Fair                     | number        | number        |
| Yes      | numeric metric | poor                     | Poor                     | number        | number        |
| Yes      | numeric metric | very_poor                | Very_poor                | number        | number        |
| Yes      | numeric metric | total_verygood_good_fair | Total_VeryGood_Good_Fair | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:ktnm-2i9z d:1986-01-01T00:00:00.000Z t:row_id=Orleans1986 t:parish=Orleans m:total_verygood_good_fair=73 m:poor=21 m:good=27 m:fair=39 m:very_good=7

series e:ktnm-2i9z d:1986-01-01T00:00:00.000Z t:row_id=Jefferson1986 t:parish=Jefferson m:total_verygood_good_fair=86 m:poor=9 m:good=42 m:fair=32 m:very_good=12

series e:ktnm-2i9z d:1988-01-01T00:00:00.000Z t:row_id=Orleans1988 t:parish=Orleans m:total_verygood_good_fair=70 m:poor=26 m:good=27 m:fair=35 m:very_good=8
```

## Meta Commands

```ls
metric m:very_good p:integer l:Very_good t:dataTypeName=number

metric m:good p:integer l:Good t:dataTypeName=number

metric m:fair p:integer l:Fair t:dataTypeName=number

metric m:poor p:integer l:Poor t:dataTypeName=number

metric m:very_poor p:integer l:Very_poor t:dataTypeName=number

metric m:total_verygood_good_fair p:integer l:Total_VeryGood_Good_Fair t:dataTypeName=number

entity e:ktnm-2i9z l:"Parks and Recreation Rating (1986 - Present)" t:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey" t:url=https://data.nola.gov/api/views/ktnm-2i9z

property e:ktnm-2i9z t:meta.view v:id=ktnm-2i9z v:category="Recreation and Culture" v:attributionLink=http://www.uno.edu/cola/political-science/survey-research-center-studies.aspx v:averageRating=0 v:name="Parks and Recreation Rating (1986 - Present)" v:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey"

property e:ktnm-2i9z t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:ktnm-2i9z t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:ktnm-2i9z t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| row_id        | year | date                | parish    | very_good | good | fair | poor | very_poor | total_verygood_good_fair | 
| ============= | ==== | =================== | ========= | ========= | ==== | ==== | ==== | ========= | ======================== | 
| Orleans1986   | 1986 | 1986-01-01T00:00:00 | Orleans   | 7         | 27   | 39   | 21   |           | 73                       | 
| Jefferson1986 | 1986 | 1986-01-01T00:00:00 | Jefferson | 12        | 42   | 32   | 9    |           | 86                       | 
| Orleans1988   | 1988 | 1988-01-01T00:00:00 | Orleans   | 8         | 27   | 35   | 26   |           | 70                       | 
| Jefferson1988 | 1988 | 1988-01-01T00:00:00 | Jefferson | 8         | 48   | 27   | 11   |           | 83                       | 
| Orleans1990   | 1990 | 1990-01-01T00:00:00 | Orleans   | 5         | 28   | 37   | 26   |           | 70                       | 
| Jefferson1990 | 1990 | 1990-01-01T00:00:00 | Jefferson | 11        | 49   | 25   | 13   |           | 85                       | 
| Orleans1992   | 1992 | 1992-01-01T00:00:00 | Orleans   | 3         | 26   | 33   | 33   |           | 62                       | 
| Jefferson1992 | 1992 | 1992-01-01T00:00:00 | Jefferson | 14        | 53   | 20   | 9    |           | 87                       | 
| Orleans1994   | 1994 | 1994-01-01T00:00:00 | Orleans   | 3         | 18   | 32   | 44   |           | 53                       | 
| Jefferson1994 | 1994 | 1994-01-01T00:00:00 | Jefferson | 11        | 50   | 24   | 9    |           | 85                       | 
```