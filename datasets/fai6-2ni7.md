# Street Condition Rating (1986 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/street-condition-rating-1986-present) |
| Metadata | [Link](https://data.nola.gov/api/views/fai6-2ni7) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/fai6-2ni7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/fai6-2ni7/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | fai6-2ni7 |
| Name | Street Condition Rating (1986 - Present) |
| Attribution | The University of New Orleans Survey Research Center's Quality of Life Survey |
| Category | Transportation and Infrastructure |
| Created | 2015-03-19T18:45:11Z |
| Publication Date | 2015-11-05T20:46:31Z |

## Description

This data comes from the Quality of Life Survey conducted by the University of New Orleans Survey Research Center. The Center began its Quality of Life series in 1986. Since then the quality of life and government services in Jefferson and Orleans parishes have been assessed roughly every other year. The results of the Quality of Life surveys represent the perceptions and opinions of the registered voters of the two parishes. The results are not objective measures of the quality of services.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | row_id                   | Row ID                   | text          | text          |
| No       |                | year                     | Year                     | number        | number        |
| Yes      | time           | date                     | Date                     | calendar_date | calendar_date |
| Yes      | series tag     | parish                   | Parish                   | text          | text          |
| Yes      | numeric metric | very_good                | Very Good                | number        | number        |
| Yes      | numeric metric | good                     | Good                     | number        | number        |
| Yes      | numeric metric | fair                     | Fair                     | number        | number        |
| Yes      | numeric metric | poor                     | Poor                     | number        | number        |
| Yes      | numeric metric | very_poor                | Very Poor                | number        | number        |
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
series e:fai6-2ni7 d:1986-01-01T00:00:00.000Z t:row_id=Orleans1986 t:parish=Orleans m:total_verygood_good_fair=57 m:poor=40 m:good=16 m:fair=37 m:very_good=4

series e:fai6-2ni7 d:1986-01-01T00:00:00.000Z t:row_id=Jefferson1986 t:parish=Jefferson m:total_verygood_good_fair=83 m:poor=16 m:good=40 m:fair=37 m:very_good=6

series e:fai6-2ni7 d:1988-01-01T00:00:00.000Z t:row_id=Orleans1988 t:parish=Orleans m:total_verygood_good_fair=48 m:poor=51 m:good=17 m:fair=29 m:very_good=2
```

## Meta Commands

```ls
metric m:very_good p:integer l:"Very Good" t:dataTypeName=number

metric m:good p:integer l:Good t:dataTypeName=number

metric m:fair p:integer l:Fair t:dataTypeName=number

metric m:poor p:integer l:Poor t:dataTypeName=number

metric m:very_poor p:integer l:"Very Poor" t:dataTypeName=number

metric m:total_verygood_good_fair p:integer l:Total_VeryGood_Good_Fair t:dataTypeName=number

entity e:fai6-2ni7 l:"Street Condition Rating (1986 - Present)" t:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey" t:url=https://data.nola.gov/api/views/fai6-2ni7

property e:fai6-2ni7 t:meta.view v:id=fai6-2ni7 v:category="Transportation and Infrastructure" v:attributionLink=http://www.uno.edu/cola/political-science/survey-research-center-studies.aspx v:averageRating=0 v:name="Street Condition Rating (1986 - Present)" v:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey"

property e:fai6-2ni7 t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:fai6-2ni7 t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:fai6-2ni7 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| row_id        | year | date                | parish    | very_good | good | fair | poor | very_poor | total_verygood_good_fair | 
| ============= | ==== | =================== | ========= | ========= | ==== | ==== | ==== | ========= | ======================== | 
| Orleans1986   | 1986 | 1986-01-01T00:00:00 | Orleans   | 4         | 16   | 37   | 40   |           | 57                       | 
| Jefferson1986 | 1986 | 1986-01-01T00:00:00 | Jefferson | 6         | 40   | 37   | 16   |           | 83                       | 
| Orleans1988   | 1988 | 1988-01-01T00:00:00 | Orleans   | 2         | 17   | 29   | 51   |           | 48                       | 
| Jefferson1988 | 1988 | 1988-01-01T00:00:00 | Jefferson | 2         | 40   | 40   | 18   |           | 82                       | 
| Orleans1990   | 1990 | 1990-01-01T00:00:00 | Orleans   | 1         | 12   | 30   | 56   |           | 43                       | 
| Jefferson1990 | 1990 | 1990-01-01T00:00:00 | Jefferson | 4         | 37   | 37   | 22   |           | 78                       | 
| Orleans1992   | 1992 | 1992-01-01T00:00:00 | Orleans   | 1         | 9    | 29   | 60   |           | 39                       | 
| Jefferson1992 | 1992 | 1992-01-01T00:00:00 | Jefferson | 4         | 34   | 36   | 26   |           | 74                       | 
| Orleans1994   | 1994 | 1994-01-01T00:00:00 | Orleans   | 1         | 10   | 26   | 63   |           | 37                       | 
| Jefferson1994 | 1994 | 1994-01-01T00:00:00 | Jefferson | 2         | 36   | 39   | 22   |           | 77                       | 
```