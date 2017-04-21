# Zoning Rating (1986 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/zoning-rating-1986-present) |
| Metadata | [Link](https://data.nola.gov/api/views/prjn-nrpj) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/prjn-nrpj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/prjn-nrpj/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | prjn-nrpj |
| Name | Zoning Rating (1986 - Present) |
| Attribution | The University of New Orleans Survey Research Center's Quality of Life Survey |
| Category | Housing, Land Use, and Blight |
| Created | 2015-03-19T18:58:14Z |
| Publication Date | 2015-11-05T21:01:21Z |

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
series e:prjn-nrpj d:1986-01-01T00:00:00.000Z t:row_id=Orleans1986 t:parish=Orleans m:total_verygood_good_fair=63 m:poor=20 m:good=20 m:fair=41 m:very_good=2

series e:prjn-nrpj d:1986-01-01T00:00:00.000Z t:row_id=Jefferson1986 t:parish=Jefferson m:total_verygood_good_fair=58 m:poor=31 m:good=25 m:fair=32 m:very_good=1

series e:prjn-nrpj d:1988-01-01T00:00:00.000Z t:row_id=Orleans1988 t:parish=Orleans m:total_verygood_good_fair=65 m:poor=19 m:good=18 m:fair=46 m:very_good=1
```

## Meta Commands

```ls
metric m:very_good p:integer l:Very_good t:dataTypeName=number

metric m:good p:integer l:Good t:dataTypeName=number

metric m:fair p:integer l:Fair t:dataTypeName=number

metric m:poor p:integer l:Poor t:dataTypeName=number

metric m:very_poor p:integer l:Very_poor t:dataTypeName=number

metric m:total_verygood_good_fair p:integer l:Total_VeryGood_Good_Fair t:dataTypeName=number

entity e:prjn-nrpj l:"Zoning Rating (1986 - Present)" t:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey" t:url=https://data.nola.gov/api/views/prjn-nrpj

property e:prjn-nrpj t:meta.view v:id=prjn-nrpj v:category="Housing, Land Use, and Blight" v:attributionLink=http://www.uno.edu/cola/political-science/survey-research-center-studies.aspx v:averageRating=0 v:name="Zoning Rating (1986 - Present)" v:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey"

property e:prjn-nrpj t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:prjn-nrpj t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:prjn-nrpj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| row_id        | year | date                | parish    | very_good | good | fair | poor | very_poor | total_verygood_good_fair | 
| ============= | ==== | =================== | ========= | ========= | ==== | ==== | ==== | ========= | ======================== | 
| Orleans1986   | 1986 | 1986-01-01T00:00:00 | Orleans   | 2         | 20   | 41   | 20   |           | 63                       | 
| Jefferson1986 | 1986 | 1986-01-01T00:00:00 | Jefferson | 1         | 25   | 32   | 31   |           | 58                       | 
| Orleans1988   | 1988 | 1988-01-01T00:00:00 | Orleans   | 1         | 18   | 46   | 19   |           | 65                       | 
| Jefferson1988 | 1988 | 1988-01-01T00:00:00 | Jefferson | 2         | 23   | 39   | 25   |           | 64                       | 
| Orleans1990   | 1990 | 1990-01-01T00:00:00 | Orleans   | 2         | 18   | 37   | 21   |           | 57                       | 
| Jefferson1990 | 1990 | 1990-01-01T00:00:00 | Jefferson | 1         | 28   | 35   | 24   |           | 64                       | 
| Orleans1992   | 1992 | 1992-01-01T00:00:00 | Orleans   | 1         | 13   | 41   | 26   |           | 55                       | 
| Jefferson1992 | 1992 | 1992-01-01T00:00:00 | Jefferson | 1         | 29   | 40   | 16   |           | 70                       | 
| Orleans1994   | 1994 | 1994-01-01T00:00:00 | Orleans   | 1         | 17   | 34   | 32   |           | 52                       | 
| Jefferson1994 | 1994 | 1994-01-01T00:00:00 | Jefferson | 1         | 28   | 35   | 20   |           | 64                       | 
```