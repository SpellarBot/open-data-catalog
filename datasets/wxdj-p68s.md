# Grant Information Collection Act - 1 3rd Quarter 10-8-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grant-information-collection-act-1-3rd-quarter-10-8-2014-6b8fc) |
| Metadata | [Link](https://data.illinois.gov/api/views/wxdj-p68s) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/wxdj-p68s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/wxdj-p68s/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | wxdj-p68s |
| Name | Grant Information Collection Act - 1 3rd Quarter 10-8-2014 |
| Attribution | Illinois Arts Council Agency |
| Tags | illinois, arts, council, agency, grants, third, quarter |
| Created | 2014-10-14T17:24:44Z |
| Publication Date | 2014-10-14T17:29:30Z |

## Description

Grants vouchered from 7/1/14 through 9/30/14

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type     | Render Type   |
| ======== | ============== | ========== | ====== | ============= | ============= |
| No       |                | fy         | FY     | number        | number        |
| Yes      | series tag     | flname     | FLName | text          | text          |
| Yes      | series tag     | title      | Title  | text          | text          |
| Yes      | numeric metric | grant      | Grant  | money         | money         |
| Yes      | time           | dvo        | Dvo    | calendar_date | calendar_date |
| No       |                | beg        | Beg    | calendar_date | calendar_date |
| No       |                | end        | End    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dvo
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fy,beg,end
```

## Data Commands

```ls
series e:wxdj-p68s d:2014-07-24T00:00:00.000Z t:title="for an IAS Artist Project grant" t:flname="Jeffrey Glassman" m:grant=3000

series e:wxdj-p68s d:2014-07-15T00:00:00.000Z t:title="for a performance by Corky Siegel's Chamber Blues" t:flname="The Next Picture Show" m:grant=4800

series e:wxdj-p68s d:2014-07-01T00:00:00.000Z t:title="for a Youth Employment in the Arts project" t:flname="Carbondale Community Arts" m:grant=6000
```

## Meta Commands

```ls
metric m:grant p:integer l:Grant t:dataTypeName=money

entity e:wxdj-p68s l:"Grant Information Collection Act - 1  3rd Quarter 10-8-2014" t:attribution="Illinois Arts Council Agency" t:url=https://data.illinois.gov/api/views/wxdj-p68s

property e:wxdj-p68s t:meta.view v:id=wxdj-p68s v:attributionLink=http://www.arts.illinois.gov/ v:averageRating=0 v:name="Grant Information Collection Act - 1  3rd Quarter 10-8-2014" v:attribution="Illinois Arts Council Agency"

property e:wxdj-p68s t:meta.view.owner v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"

property e:wxdj-p68s t:meta.view.tableauthor v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"
```

## Top Records

```ls
| fy | flname                              | title                                             | grant | dvo                 | beg                 | end                 | 
| == | =================================== | ================================================= | ===== | =================== | =================== | =================== | 
| 14 | Jeffrey Glassman                    | for an IAS Artist Project grant                   | 3000  | 2014-07-24T00:00:00 | 2014-04-01T00:00:00 | 2014-06-30T00:00:00 | 
| 14 | The Next Picture Show               | for a performance by Corky Siegel's Chamber Blues | 4800  | 2014-07-15T00:00:00 | 2014-06-15T00:00:00 | 2014-09-30T00:00:00 | 
| 14 | Carbondale Community Arts           | for a Youth Employment in the Arts project        | 6000  | 2014-07-01T00:00:00 | 2014-06-10T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Heritage Ensemble                   | for a Youth Employment in the Arts project        | 1460  | 2014-07-01T00:00:00 | 2014-06-10T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Korean Amer Resource/Cultural Ctr   | for a Youth Employment in the Arts project        | 3200  | 2014-07-01T00:00:00 | 2014-06-10T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | National Vietnam Vets Art Museum    | for a Youth Employment in the Arts project        | 4365  | 2014-07-01T00:00:00 | 2014-06-10T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Oak Park Area Arts Council          | for a Youth Employment in the Arts project        | 900   | 2014-07-01T00:00:00 | 2014-06-10T00:00:00 | 2014-09-30T00:00:00 | 
| 14 | Rockford Area Arts Council          | for a Youth Employment in the Arts project        | 4945  | 2014-07-03T00:00:00 | 2014-06-10T00:00:00 | 2014-08-31T00:00:00 | 
| 14 | Jeffrey J Harms                     | for an IAS Artist Project grant                   | 3000  | 2014-07-01T00:00:00 | 2014-06-15T00:00:00 | 2014-11-30T00:00:00 | 
| 14 | Discovery Center Museum of Rockford | for a performance by Jim Gill, musician           | 475   | 2014-07-01T00:00:00 | 2014-06-15T00:00:00 | 2014-06-30T00:00:00 | 
```