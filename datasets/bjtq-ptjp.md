# Trash Control and Pickup Rating (2006 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/trash-control-and-pickup-rating-2006-present) |
| Metadata | [Link](https://data.nola.gov/api/views/bjtq-ptjp) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/bjtq-ptjp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/bjtq-ptjp/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | bjtq-ptjp |
| Name | Trash Control and Pickup Rating (2006 - Present) |
| Attribution | The University of New Orleans Survey Research Center's Quality of Life Survey |
| Category | Customer Service |
| Created | 2015-03-19T18:54:03Z |
| Publication Date | 2015-11-05T20:56:50Z |
| Rows Updated | 2015-11-05T20:56:07Z |

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
series e:bjtq-ptjp d:2006-01-01T00:00:00.000Z t:row_id=Orleans2006 t:parish=Orleans m:very_poor=28 m:total_verygood_good_fair=35 m:poor=37 m:good=14 m:fair=18 m:very_good=3

series e:bjtq-ptjp d:2006-01-01T00:00:00.000Z t:row_id=Jefferson2006 t:parish=Jefferson m:very_poor=6 m:total_verygood_good_fair=75 m:poor=19 m:good=35 m:fair=28 m:very_good=12

series e:bjtq-ptjp d:2007-01-01T00:00:00.000Z t:row_id=Orleans2007 t:parish=Orleans m:very_poor=10 m:total_verygood_good_fair=65 m:poor=25 m:good=25 m:fair=34 m:very_good=6
```

## Meta Commands

```ls
metric m:very_good p:integer l:Very_good t:dataTypeName=number

metric m:good p:integer l:Good t:dataTypeName=number

metric m:fair p:integer l:Fair t:dataTypeName=number

metric m:poor p:integer l:Poor t:dataTypeName=number

metric m:very_poor p:integer l:Very_poor t:dataTypeName=number

metric m:total_verygood_good_fair p:integer l:Total_VeryGood_Good_Fair t:dataTypeName=number

entity e:bjtq-ptjp l:"Trash Control and Pickup Rating (2006 - Present)" t:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey" t:url=https://data.nola.gov/api/views/bjtq-ptjp

property e:bjtq-ptjp t:meta.view v:id=bjtq-ptjp v:category="Customer Service" v:attributionLink=http://www.uno.edu/cola/political-science/survey-research-center-studies.aspx v:averageRating=0 v:name="Trash Control and Pickup Rating (2006 - Present)" v:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey"

property e:bjtq-ptjp t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:bjtq-ptjp t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:bjtq-ptjp t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```