# Public Transportation Rating (1986 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-transportation-rating-1986-present) |
| Metadata | [Link](https://data.nola.gov/api/views/htpd-y79d) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/htpd-y79d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/htpd-y79d/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | htpd-y79d |
| Name | Public Transportation Rating (1986 - Present) |
| Attribution | The University of New Orleans Survey Research Center's Quality of Life Survey |
| Category | Transportation and Infrastructure |
| Created | 2015-03-19T18:28:56Z |
| Publication Date | 2015-11-05T20:32:11Z |

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
series e:htpd-y79d d:1986-01-01T00:00:00.000Z t:row_id=Orleans1986 t:parish=Orleans m:total_verygood_good_fair=81 m:poor=6 m:good=45 m:fair=21 m:very_good=15

series e:htpd-y79d d:1986-01-01T00:00:00.000Z t:row_id=Jefferson1986 t:parish=Jefferson m:total_verygood_good_fair=49 m:poor=29 m:good=18 m:fair=28 m:very_good=3

series e:htpd-y79d d:1988-01-01T00:00:00.000Z t:row_id=Orleans1988 t:parish=Orleans m:total_verygood_good_fair=84 m:poor=8 m:good=47 m:fair=24 m:very_good=13
```

## Meta Commands

```ls
metric m:very_good p:integer l:Very_good t:dataTypeName=number

metric m:good p:integer l:Good t:dataTypeName=number

metric m:fair p:integer l:Fair t:dataTypeName=number

metric m:poor p:integer l:Poor t:dataTypeName=number

metric m:very_poor p:integer l:Very_poor t:dataTypeName=number

metric m:total_verygood_good_fair p:integer l:Total_VeryGood_Good_Fair t:dataTypeName=number

entity e:htpd-y79d l:"Public Transportation Rating (1986 - Present)" t:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey" t:url=https://data.nola.gov/api/views/htpd-y79d

property e:htpd-y79d t:meta.view v:id=htpd-y79d v:category="Transportation and Infrastructure" v:attributionLink=http://www.uno.edu/cola/political-science/survey-research-center-studies.aspx v:averageRating=0 v:name="Public Transportation Rating (1986 - Present)" v:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey"

property e:htpd-y79d t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:htpd-y79d t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:htpd-y79d t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| row_id        | year | date                | parish    | very_good | good | fair | poor | very_poor | total_verygood_good_fair | 
| ============= | ==== | =================== | ========= | ========= | ==== | ==== | ==== | ========= | ======================== | 
| Orleans1986   | 1986 | 1986-01-01T00:00:00 | Orleans   | 15        | 45   | 21   | 6    |           | 81                       | 
| Jefferson1986 | 1986 | 1986-01-01T00:00:00 | Jefferson | 3         | 18   | 28   | 29   |           | 49                       | 
| Orleans1988   | 1988 | 1988-01-01T00:00:00 | Orleans   | 13        | 47   | 24   | 8    |           | 84                       | 
| Jefferson1988 | 1988 | 1988-01-01T00:00:00 | Jefferson | 2         | 25   | 26   | 22   |           | 53                       | 
| Orleans1990   | 1990 | 1990-01-01T00:00:00 | Orleans   | 10        | 49   | 26   | 6    |           | 85                       | 
| Jefferson1990 | 1990 | 1990-01-01T00:00:00 | Jefferson | 5         | 24   | 27   | 25   |           | 56                       | 
| Orleans1992   | 1992 | 1992-01-01T00:00:00 | Orleans   | 4         | 37   | 29   | 17   |           | 70                       | 
| Jefferson1992 | 1992 | 1992-01-01T00:00:00 | Jefferson | 5         | 26   | 23   | 24   |           | 54                       | 
| Orleans1994   | 1994 | 1994-01-01T00:00:00 | Orleans   | 5         | 40   | 30   | 13   |           | 75                       | 
| Jefferson1994 | 1994 | 1994-01-01T00:00:00 | Jefferson | 3         | 30   | 23   | 24   |           | 56                       | 
```