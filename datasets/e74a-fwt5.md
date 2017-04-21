# Police Protection Rating (1986 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-protection-rating-1986-present) |
| Metadata | [Link](https://data.nola.gov/api/views/e74a-fwt5) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/e74a-fwt5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/e74a-fwt5/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | e74a-fwt5 |
| Name | Police Protection Rating (1986 - Present) |
| Attribution | The University of New Orleans Survey Research Center's Quality of Life Survey |
| Category | Public Safety and Preparedness |
| Created | 2015-03-19T18:23:44Z |
| Publication Date | 2015-11-05T20:07:17Z |

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
series e:e74a-fwt5 d:1986-01-01T00:00:00.000Z t:row_id=Orleans1986 t:parish=Orleans m:total_verygood_good_fair=85 m:poor=11 m:good=41 m:fair=40 m:very_good=4

series e:e74a-fwt5 d:1986-01-01T00:00:00.000Z t:row_id=Jefferson1986 t:parish=Jefferson m:total_verygood_good_fair=91 m:poor=7 m:good=51 m:fair=31 m:very_good=9

series e:e74a-fwt5 d:1988-01-01T00:00:00.000Z t:row_id=Orleans1988 t:parish=Orleans m:total_verygood_good_fair=76 m:poor=22 m:good=27 m:fair=46 m:very_good=3
```

## Meta Commands

```ls
metric m:very_good p:integer l:Very_good t:dataTypeName=number

metric m:good p:integer l:Good t:dataTypeName=number

metric m:fair p:integer l:Fair t:dataTypeName=number

metric m:poor p:integer l:Poor t:dataTypeName=number

metric m:very_poor p:integer l:Very_poor t:dataTypeName=number

metric m:total_verygood_good_fair p:integer l:Total_VeryGood_Good_Fair t:dataTypeName=number

entity e:e74a-fwt5 l:"Police Protection Rating (1986 - Present)" t:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey" t:url=https://data.nola.gov/api/views/e74a-fwt5

property e:e74a-fwt5 t:meta.view v:id=e74a-fwt5 v:category="Public Safety and Preparedness" v:attributionLink=http://www.uno.edu/cola/political-science/survey-research-center-studies.aspx v:averageRating=0 v:name="Police Protection Rating (1986 - Present)" v:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey"

property e:e74a-fwt5 t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:e74a-fwt5 t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:e74a-fwt5 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| row_id        | year | date                | parish    | very_good | good | fair | poor | very_poor | total_verygood_good_fair | 
| ============= | ==== | =================== | ========= | ========= | ==== | ==== | ==== | ========= | ======================== | 
| Orleans1986   | 1986 | 1986-01-01T00:00:00 | Orleans   | 4         | 41   | 40   | 11   |           | 85                       | 
| Jefferson1986 | 1986 | 1986-01-01T00:00:00 | Jefferson | 9         | 51   | 31   | 7    |           | 91                       | 
| Orleans1988   | 1988 | 1988-01-01T00:00:00 | Orleans   | 3         | 27   | 46   | 22   |           | 76                       | 
| Jefferson1988 | 1988 | 1988-01-01T00:00:00 | Jefferson | 8         | 54   | 29   | 7    |           | 91                       | 
| Orleans1990   | 1990 | 1990-01-01T00:00:00 | Orleans   | 5         | 32   | 44   | 16   |           | 81                       | 
| Jefferson1990 | 1990 | 1990-01-01T00:00:00 | Jefferson | 15        | 50   | 29   | 6    |           | 94                       | 
| Orleans1992   | 1992 | 1992-01-01T00:00:00 | Orleans   | 2         | 30   | 42   | 24   |           | 74                       | 
| Jefferson1992 | 1992 | 1992-01-01T00:00:00 | Jefferson | 10        | 57   | 27   | 5    |           | 94                       | 
| Orleans1994   | 1994 | 1994-01-01T00:00:00 | Orleans   | 2         | 17   | 38   | 41   |           | 57                       | 
| Jefferson1994 | 1994 | 1994-01-01T00:00:00 | Jefferson | 15        | 53   | 24   | 6    |           | 92                       | 
```