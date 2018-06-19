# Traffic Congestion Rating (1986 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-congestion-rating-1986-present) |
| Metadata | [Link](https://data.nola.gov/api/views/wras-isie) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/wras-isie/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/wras-isie/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | wras-isie |
| Name | Traffic Congestion Rating (1986 - Present) |
| Attribution | The University of New Orleans Survey Research Center's Quality of Life Survey |
| Category | Transportation and Infrastructure |
| Created | 2015-03-19T18:50:00Z |
| Publication Date | 2015-11-05T20:52:23Z |

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
series e:wras-isie d:1986-01-01T00:00:00.000Z t:row_id=Orleans1986 t:parish=Orleans m:total_verygood_good_fair=64 m:poor=29 m:good=23 m:fair=37 m:very_good=4

series e:wras-isie d:1986-01-01T00:00:00.000Z t:row_id=Jefferson1986 t:parish=Jefferson m:total_verygood_good_fair=57 m:poor=39 m:good=21 m:fair=34 m:very_good=2

series e:wras-isie d:1988-01-01T00:00:00.000Z t:row_id=Orleans1988 t:parish=Orleans m:total_verygood_good_fair=65 m:poor=31 m:good=21 m:fair=41 m:very_good=3
```

## Meta Commands

```ls
metric m:very_good p:integer l:Very_good t:dataTypeName=number

metric m:good p:integer l:Good t:dataTypeName=number

metric m:fair p:integer l:Fair t:dataTypeName=number

metric m:poor p:integer l:Poor t:dataTypeName=number

metric m:very_poor p:integer l:Very_poor t:dataTypeName=number

metric m:total_verygood_good_fair p:integer l:Total_VeryGood_Good_Fair t:dataTypeName=number

entity e:wras-isie l:"Traffic Congestion Rating (1986 - Present)" t:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey" t:url=https://data.nola.gov/api/views/wras-isie

property e:wras-isie t:meta.view v:id=wras-isie v:category="Transportation and Infrastructure" v:attributionLink=http://www.uno.edu/cola/political-science/survey-research-center-studies.aspx v:averageRating=0 v:name="Traffic Congestion Rating (1986 - Present)" v:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey"

property e:wras-isie t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:wras-isie t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:wras-isie t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| row_id        | year | date                | parish    | very_good | good | fair | poor | very_poor | total_verygood_good_fair | 
| ============= | ==== | =================== | ========= | ========= | ==== | ==== | ==== | ========= | ======================== | 
| Orleans1986   | 1986 | 1986-01-01T00:00:00 | Orleans   | 4         | 23   | 37   | 29   |           | 64                       | 
| Jefferson1986 | 1986 | 1986-01-01T00:00:00 | Jefferson | 2         | 21   | 34   | 39   |           | 57                       | 
| Orleans1988   | 1988 | 1988-01-01T00:00:00 | Orleans   | 3         | 21   | 41   | 31   |           | 65                       | 
| Jefferson1988 | 1988 | 1988-01-01T00:00:00 | Jefferson | 1         | 23   | 39   | 35   |           | 63                       | 
| Orleans1990   | 1990 | 1990-01-01T00:00:00 | Orleans   | 2         | 29   | 39   | 25   |           | 70                       | 
| Jefferson1990 | 1990 | 1990-01-01T00:00:00 | Jefferson | 2         | 27   | 40   | 29   |           | 69                       | 
| Orleans1992   | 1992 | 1992-01-01T00:00:00 | Orleans   | 0         | 23   | 41   | 31   |           | 64                       | 
| Jefferson1992 | 1992 | 1992-01-01T00:00:00 | Jefferson | 4         | 24   | 40   | 30   |           | 68                       | 
| Orleans1994   | 1994 | 1994-01-01T00:00:00 | Orleans   | 1         | 23   | 40   | 34   |           | 64                       | 
| Jefferson1994 | 1994 | 1994-01-01T00:00:00 | Jefferson | 1         | 35   | 35   | 28   |           | 71                       | 
```