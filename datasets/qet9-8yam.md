# Missouri Weekly Report of Initial Unemployment Claims

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-weekly-report-of-initial-unemployment-claims-2c10b) |
| Metadata | [Link](https://data.mo.gov/api/views/qet9-8yam) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/qet9-8yam/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/qet9-8yam/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | qet9-8yam |
| Name | Missouri Weekly Report of Initial Unemployment Claims |
| Attribution | Missouri Department of Labor and Industrial Relations |
| Category | Labor |
| Tags | unemployment, labor, employment |
| Created | 2012-08-10T15:26:58Z |
| Publication Date | 2017-04-17T12:01:03Z |

## Description

The number of people filing for initial unemployment benefits by county and week.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | time           | weekending | weekEnding | calendar_date | calendar_date |
| Yes      | series tag     | county     | county     | text          | text          |
| Yes      | numeric metric | claims     | claims     | number        | number        |
```

## Time Field

```ls
Value = weekending
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:qet9-8yam d:2010-05-15T00:00:00.000Z t:county=ADAIR m:claims=85

series e:qet9-8yam d:2010-05-15T00:00:00.000Z t:county=ANDREW m:claims=29

series e:qet9-8yam d:2010-05-15T00:00:00.000Z t:county=ATCHISON m:claims=2
```

## Meta Commands

```ls
metric m:claims p:integer l:claims t:dataTypeName=number

entity e:qet9-8yam l:"Missouri Weekly Report of Initial Unemployment Claims" t:attribution="Missouri Department of Labor and Industrial Relations" t:url=https://data.mo.gov/api/views/qet9-8yam

property e:qet9-8yam t:meta.view v:id=qet9-8yam v:category=Labor v:attributionLink=http://labor.mo.gov/DES/Claims/ v:averageRating=0 v:name="Missouri Weekly Report of Initial Unemployment Claims" v:attribution="Missouri Department of Labor and Industrial Relations"

property e:qet9-8yam t:meta.view.owner v:id=eb88-upz2 v:screenName=DOLIR v:displayName=DOLIR

property e:qet9-8yam t:meta.view.tableauthor v:id=eb88-upz2 v:screenName=DOLIR v:roleName=editor v:displayName=DOLIR
```

## Top Records

```ls
| weekending          | county    | claims | 
| =================== | ========= | ====== | 
| 2010-05-15T00:00:00 | ADAIR     | 85     | 
| 2010-05-15T00:00:00 | ANDREW    | 29     | 
| 2010-05-15T00:00:00 | ATCHISON  | 2      | 
| 2010-05-15T00:00:00 | AUDRAIN   | 27     | 
| 2010-05-15T00:00:00 | BARRY     | 28     | 
| 2010-05-15T00:00:00 | BARTON    | 9      | 
| 2010-05-15T00:00:00 | BATES     | 28     | 
| 2010-05-15T00:00:00 | BENTON    | 32     | 
| 2010-05-15T00:00:00 | BOLLINGER | 11     | 
| 2010-05-15T00:00:00 | BOONE     | 144    | 
```