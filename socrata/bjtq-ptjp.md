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
series e:bjtq-ptjp d:2006-01-01T00:00:00.000Z t:parish=Orleans t:row_id=Orleans2006 m:poor=37 m:very_poor=28 m:very_good=3 m:fair=18 m:good=14 m:total_verygood_good_fair=35

series e:bjtq-ptjp d:2006-01-01T00:00:00.000Z t:parish=Jefferson t:row_id=Jefferson2006 m:poor=19 m:very_poor=6 m:very_good=12 m:fair=28 m:good=35 m:total_verygood_good_fair=75

series e:bjtq-ptjp d:2007-01-01T00:00:00.000Z t:parish=Orleans t:row_id=Orleans2007 m:poor=25 m:very_poor=10 m:very_good=6 m:fair=34 m:good=25 m:total_verygood_good_fair=65
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

property e:bjtq-ptjp t:meta.view d:2017-09-25T07:30:13.677Z v:averageRating=0 v:name="Trash Control and Pickup Rating (2006 - Present)" v:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey" v:attributionLink=http://www.uno.edu/cola/political-science/survey-research-center-studies.aspx v:id=bjtq-ptjp v:category="Customer Service"

property e:bjtq-ptjp t:meta.view.owner d:2017-09-25T07:30:13.677Z v:displayName=mschigoda v:id=ii98-542e v:screenName=mschigoda

property e:bjtq-ptjp t:meta.view.tableauthor d:2017-09-25T07:30:13.677Z v:displayName=mschigoda v:roleName=publisher v:id=ii98-542e v:screenName=mschigoda

property e:bjtq-ptjp t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:30:13.677Z v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| row_id        | year | date                | parish    | very_good | good | fair | poor | very_poor | total_verygood_good_fair | 
| ============= | ==== | =================== | ========= | ========= | ==== | ==== | ==== | ========= | ======================== | 
| Orleans2006   | 2006 | 2006-01-01T00:00:00 | Orleans   | 3         | 14   | 18   | 37   | 28        | 35                       | 
| Jefferson2006 | 2006 | 2006-01-01T00:00:00 | Jefferson | 12        | 35   | 28   | 19   | 6         | 75                       | 
| Orleans2007   | 2007 | 2007-01-01T00:00:00 | Orleans   | 6         | 25   | 34   | 25   | 10        | 65                       | 
| Jefferson2007 | 2007 | 2007-01-01T00:00:00 | Jefferson | 13        | 41   | 26   | 14   | 4         | 80                       | 
| Orleans2008   | 2008 | 2008-01-01T00:00:00 | Orleans   | 8         | 27   | 22   | 22   | 18        | 57                       | 
| Jefferson2008 | 2008 | 2008-01-01T00:00:00 | Jefferson | 18        | 41   | 27   | 12   | 2         | 86                       | 
| Orleans2012   | 2012 | 2012-01-01T00:00:00 | Orleans   | 14        | 49   | 26   | 9    | 2         | 89                       | 
| Jefferson2012 | 2012 | 2012-01-01T00:00:00 | Jefferson | 24        | 62   | 11   | 2    | 0         | 97                       | 
| Orleans2013   | 2013 | 2013-01-01T00:00:00 | Orleans   | 11        | 62   | 18   | 7    | 2         | 91                       | 
| Jefferson2013 | 2013 | 2013-01-01T00:00:00 | Jefferson | 21        | 61   | 15   | 1    | 0         | 97                       | 
```