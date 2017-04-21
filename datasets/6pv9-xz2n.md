# Health Services Rating (2006 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-services-rating-2006-present) |
| Metadata | [Link](https://data.nola.gov/api/views/6pv9-xz2n) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/6pv9-xz2n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/6pv9-xz2n/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 6pv9-xz2n |
| Name | Health Services Rating (2006 - Present) |
| Attribution | The University of New Orleans Survey Research Center's Quality of Life Survey |
| Category | Health, Education, and Social Services |
| Created | 2015-03-19T18:05:37Z |
| Publication Date | 2015-11-05T20:17:07Z |

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
series e:6pv9-xz2n d:2006-01-01T00:00:00.000Z t:row_id=Orleans2006 t:parish=Orleans m:very_poor=20 m:total_verygood_good_fair=45 m:poor=31 m:good=17 m:fair=24 m:very_good=4

series e:6pv9-xz2n d:2006-01-01T00:00:00.000Z t:row_id=Jefferson2006 t:parish=Jefferson m:very_poor=7 m:total_verygood_good_fair=76 m:poor=15 m:good=31 m:fair=27 m:very_good=18

series e:6pv9-xz2n d:2007-01-01T00:00:00.000Z t:row_id=Orleans2007 t:parish=Orleans m:very_poor=19 m:total_verygood_good_fair=36 m:poor=41 m:good=10 m:fair=24 m:very_good=2
```

## Meta Commands

```ls
metric m:very_good p:integer l:Very_good t:dataTypeName=number

metric m:good p:integer l:Good t:dataTypeName=number

metric m:fair p:integer l:Fair t:dataTypeName=number

metric m:poor p:integer l:Poor t:dataTypeName=number

metric m:very_poor p:integer l:Very_poor t:dataTypeName=number

metric m:total_verygood_good_fair p:integer l:Total_VeryGood_Good_Fair t:dataTypeName=number

entity e:6pv9-xz2n l:"Health Services Rating (2006 - Present)" t:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey" t:url=https://data.nola.gov/api/views/6pv9-xz2n

property e:6pv9-xz2n t:meta.view v:id=6pv9-xz2n v:category="Health, Education, and Social Services" v:attributionLink=http://www.uno.edu/cola/political-science/survey-research-center-studies.aspx v:averageRating=0 v:name="Health Services Rating (2006 - Present)" v:attribution="The University of New Orleans Survey Research Center's Quality of Life Survey"

property e:6pv9-xz2n t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:6pv9-xz2n t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:6pv9-xz2n t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| row_id        | year | date                | parish    | very_good | good | fair | poor | very_poor | total_verygood_good_fair | 
| ============= | ==== | =================== | ========= | ========= | ==== | ==== | ==== | ========= | ======================== | 
| Orleans2006   | 2006 | 2006-01-01T00:00:00 | Orleans   | 4         | 17   | 24   | 31   | 20        | 45                       | 
| Jefferson2006 | 2006 | 2006-01-01T00:00:00 | Jefferson | 18        | 31   | 27   | 15   | 7         | 76                       | 
| Orleans2007   | 2007 | 2007-01-01T00:00:00 | Orleans   | 2         | 10   | 24   | 41   | 19        | 36                       | 
| Jefferson2007 | 2007 | 2007-01-01T00:00:00 | Jefferson | 13        | 39   | 24   | 14   | 5         | 76                       | 
| Orleans2008   | 2008 | 2008-01-01T00:00:00 | Orleans   | 8         | 18   | 32   | 24   | 14        | 58                       | 
| Jefferson2008 | 2008 | 2008-01-01T00:00:00 | Jefferson | 24        | 42   | 21   | 9    | 1         | 87                       | 
| Orleans2012   | 2012 | 2012-01-01T00:00:00 | Orleans   | 3         | 24   | 32   | 27   | 10        | 59                       | 
| Jefferson2012 | 2012 | 2012-01-01T00:00:00 | Jefferson | 16        | 53   | 19   | 5    | 1         | 88                       | 
| Orleans2013   | 2013 | 2013-01-01T00:00:00 | Orleans   | 3         | 22   | 39   | 23   | 7         | 64                       | 
| Jefferson2013 | 2013 | 2013-01-01T00:00:00 | Jefferson | 12        | 49   | 20   | 11   | 2         | 81                       | 
```