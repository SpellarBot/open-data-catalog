# LymeDisease_9211_county

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lymedisease-9211-county) |
| Metadata | [Link](https://data.cdc.gov/api/views/smai-7mz9) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/smai-7mz9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/smai-7mz9/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | smai-7mz9 |
| Name | LymeDisease_9211_county |
| Attribution | CDC |
| Tags | lyme |
| Created | 2015-03-05T00:18:34Z |
| Publication Date | 2015-03-05T00:22:12Z |

## Description

To facilitate the public health and research community's access to NNDSS data on Lyme disease, CDC has developed a public use dataset. Based on reports submitted to CDC, this dataset provides the number of confirmed cases by county for the years 1992???2011, in four 5???year intervals. County tabulation is by American National Standard Institute (ANSI) [formerly Federal Information Processing Standard (FIPS)] codes. County codes of "0" represent "unknown" county of residence within each state. More recent county-level case counts are not publicly available at this time.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag     | statecode                | StateCode                | text      | number      |
| Yes      | series tag     | countycode               | CountyCode               | text      | number      |
| Yes      | series tag     | statename                | StateName                | text      | text        |
| Yes      | series tag     | countyname               | CountyName               | text      | text        |
| Yes      | numeric metric | confirmedcount_1992_1996 | ConfirmedCount_1992_1996 | number    | number      |
| Yes      | numeric metric | confirmedcount_1997_2001 | ConfirmedCount_1997_2001 | number    | number      |
| Yes      | numeric metric | confirmedcount_2002_2006 | ConfirmedCount_2002_2006 | number    | number      |
| Yes      | numeric metric | confirmedcount_2007_2011 | ConfirmedCount_2007_2011 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:smai-7mz9 d:2015-03-04T16:19:02.000Z t:statecode=1 t:countyname=Alabama t:statename=Alabama t:countycode=0 m:confirmedcount_2007_2011=1

series e:smai-7mz9 d:2015-03-04T16:19:02.000Z t:statecode=1 t:countyname="Autauga County" t:statename=Alabama t:countycode=1 m:confirmedcount_1997_2001=2

series e:smai-7mz9 d:2015-03-04T16:19:02.000Z t:statecode=1 t:countyname="Baldwin County" t:statename=Alabama t:countycode=3 m:confirmedcount_1997_2001=4 m:confirmedcount_2002_2006=1 m:confirmedcount_1992_1996=4 m:confirmedcount_2007_2011=1
```

## Meta Commands

```ls
metric m:confirmedcount_1992_1996 p:integer l:ConfirmedCount_1992_1996 t:dataTypeName=number

metric m:confirmedcount_1997_2001 p:integer l:ConfirmedCount_1997_2001 t:dataTypeName=number

metric m:confirmedcount_2002_2006 p:integer l:ConfirmedCount_2002_2006 t:dataTypeName=number

metric m:confirmedcount_2007_2011 p:integer l:ConfirmedCount_2007_2011 t:dataTypeName=number

entity e:smai-7mz9 l:LymeDisease_9211_county t:attribution=CDC t:url=https://data.cdc.gov/api/views/smai-7mz9

property e:smai-7mz9 t:meta.view v:id=smai-7mz9 v:attributionLink=http://www.cdc.gov/lyme/stats/index.html v:averageRating=0 v:name=LymeDisease_9211_county v:attribution=CDC

property e:smai-7mz9 t:meta.view.license v:name="Public Domain"

property e:smai-7mz9 t:meta.view.owner v:id=8r4c-f7kd v:screenName="Kiersten Kugeler" v:displayName="Kiersten Kugeler"

property e:smai-7mz9 t:meta.view.tableauthor v:id=8r4c-f7kd v:screenName="Kiersten Kugeler" v:roleName=publisher v:displayName="Kiersten Kugeler"

property e:smai-7mz9 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| :updated_at | statecode | countycode | statename | countyname      | confirmedcount_1992_1996 | confirmedcount_1997_2001 | confirmedcount_2002_2006 | confirmedcount_2007_2011 | 
| =========== | ========= | ========== | ========= | =============== | ======================== | ======================== | ======================== | ======================== | 
| 1425485942  | 1         | 0          | Alabama   | Alabama         |                          |                          |                          | 1                        | 
| 1425485942  | 1         | 1          | Alabama   | Autauga County  |                          | 2                        |                          |                          | 
| 1425485942  | 1         | 3          | Alabama   | Baldwin County  | 4                        | 4                        | 1                        | 1                        | 
| 1425485942  | 1         | 5          | Alabama   | Barbour County  |                          |                          |                          |                          | 
| 1425485942  | 1         | 7          | Alabama   | Bibb County     | 1                        |                          |                          |                          | 
| 1425485942  | 1         | 9          | Alabama   | Blount County   |                          |                          |                          |                          | 
| 1425485942  | 1         | 11         | Alabama   | Bullock County  |                          |                          |                          |                          | 
| 1425485942  | 1         | 13         | Alabama   | Butler County   |                          |                          |                          |                          | 
| 1425485942  | 1         | 15         | Alabama   | Calhoun County  | 1                        | 3                        |                          | 2                        | 
| 1425485942  | 1         | 17         | Alabama   | Chambers County |                          |                          |                          | 2                        | 
```