# Oregon Inmate Off Group

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-inmate-off-group-9b945) |
| Metadata | [Link](https://data.oregon.gov/api/views/38dq-3yhz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/38dq-3yhz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/38dq-3yhz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 38dq-3yhz |
| Name | Oregon Inmate Off Group |
| Attribution | Oregon Department of Corrections |
| Category | Public Safety |
| Tags | oregon, inmate, crime, offense |
| Created | 2010-11-18T16:39:55Z |
| Publication Date | 2011-10-21T21:46:56Z |

## Description

Oregon Inmates by offense group

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | time           | count_date    | count_date    | calendar_date | calendar_date |
| Yes      | series tag     | gender        | GENDER        | text          | text          |
| Yes      | series tag     | offense_group | OFFENSE_GROUP | text          | text          |
| Yes      | numeric metric | inmates       | inmates       | number        | number        |
```

## Time Field

```ls
Value = count_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:38dq-3yhz d:1994-01-01T00:00:00.000Z t:gender=FEMALE t:offense_group=ARSON m:inmates=4

series e:38dq-3yhz d:1994-01-01T00:00:00.000Z t:gender=FEMALE t:offense_group=ASSAULT m:inmates=28

series e:38dq-3yhz d:1994-01-01T00:00:00.000Z t:gender=FEMALE t:offense_group=BURGLARY m:inmates=24
```

## Meta Commands

```ls
metric m:inmates p:integer l:inmates t:dataTypeName=number

entity e:38dq-3yhz l:"Oregon Inmate Off Group" t:attribution="Oregon Department of Corrections" t:url=https://data.oregon.gov/api/views/38dq-3yhz

property e:38dq-3yhz t:meta.view v:id=38dq-3yhz v:category="Public Safety" v:attributionLink=http://www.oregon.gov/doc v:averageRating=0 v:name="Oregon Inmate Off Group" v:attribution="Oregon Department of Corrections"

property e:38dq-3yhz t:meta.view.owner v:id=4d25-jqaq v:screenName="Shawn  Miller" v:displayName="Shawn  Miller"

property e:38dq-3yhz t:meta.view.tableauthor v:id=4d25-jqaq v:screenName="Shawn  Miller" v:displayName="Shawn  Miller"
```

## Top Records

```ls
| count_date          | gender | offense_group    | inmates | 
| =================== | ====== | ================ | ======= | 
| 1994-01-01T00:00:00 | FEMALE | ARSON            | 4       | 
| 1994-01-01T00:00:00 | FEMALE | ASSAULT          | 28      | 
| 1994-01-01T00:00:00 | FEMALE | BURGLARY         | 24      | 
| 1994-01-01T00:00:00 | FEMALE | DRIVING OFFENSES | 3       | 
| 1994-01-01T00:00:00 | FEMALE | DRUGS            | 116     | 
| 1994-01-01T00:00:00 | FEMALE | ESCAPE           | 7       | 
| 1994-01-01T00:00:00 | FEMALE | FORGERY          | 12      | 
| 1994-01-01T00:00:00 | FEMALE | HOMICIDE         | 59      | 
| 1994-01-01T00:00:00 | FEMALE | KIDNAPPING       | 3       | 
| 1994-01-01T00:00:00 | FEMALE | OTHER            | 24      | 
```