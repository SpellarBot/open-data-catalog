# Citizen Satisfaction With NOPD (2009 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/citizen-satisfaction-with-nopd-2009-present) |
| Metadata | [Link](https://data.nola.gov/api/views/vnht-dg7x) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/vnht-dg7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/vnht-dg7x/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | vnht-dg7x |
| Name | Citizen Satisfaction With NOPD (2009 - Present) |
| Attribution | New Orleans Crime Coalition's Citizen Satisfaction Survey |
| Category | Public Safety and Preparedness |
| Tags | resultsnola |
| Created | 2015-11-05T16:40:05Z |
| Publication Date | 2015-11-05T16:42:03Z |
| Rows Updated | 2015-11-05T16:40:17Z |

## Description

This data comes from a survey conducted by the New Orleans Crime Coalition's Citizen Satisfaction Survey. The survey sample includes 600 New Orleans residents, 75 from each police distract. The data has a margin of error of plus or minus 4% and has a 95% confidence interval. The results of the survey represent citizen perceptions and opinions, not objective measures of performance or safety.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | series tag     | indicatorname  | IndicatorName  | text          | text          |
| Yes      | series tag     | indicatorlabel | IndicatorLabel | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | datelabel      | DateLabel      | text          | text          |
| No       |                | month          | Month          | text          | text          |
| No       |                | year           | Year           | number        | number        |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = datelabel,year,month
```

## Data Commands

```ls
series e:vnht-dg7x d:2009-08-01T00:00:00.000Z t:indicatorlabel=Satisfied t:rowid="Percent of citizens reporting being satisfied with the New Orleans Police DepartmentAugust2009" t:indicatorname="Percent of citizens reporting being satisfied with the New Orleans Police Department" m:indicatorvalue=33

series e:vnht-dg7x d:2010-08-01T00:00:00.000Z t:indicatorlabel=Satisfied t:rowid="Percent of citizens reporting being satisfied with the New Orleans Police DepartmentAugust2010" t:indicatorname="Percent of citizens reporting being satisfied with the New Orleans Police Department" m:indicatorvalue=50

series e:vnht-dg7x d:2011-02-01T00:00:00.000Z t:indicatorlabel=Satisfied t:rowid="Percent of citizens reporting being satisfied with the New Orleans Police DepartmentFebruary2011" t:indicatorname="Percent of citizens reporting being satisfied with the New Orleans Police Department" m:indicatorvalue=60
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:vnht-dg7x l:"Citizen Satisfaction With NOPD (2009 - Present)" t:attribution="New Orleans Crime Coalition's Citizen Satisfaction Survey" t:url=https://data.nola.gov/api/views/vnht-dg7x

property e:vnht-dg7x t:meta.view v:id=vnht-dg7x v:category="Public Safety and Preparedness" v:attributionLink=http://crimecoalitionnola.com/ v:averageRating=0 v:name="Citizen Satisfaction With NOPD (2009 - Present)" v:attribution="New Orleans Crime Coalition's Citizen Satisfaction Survey"

property e:vnht-dg7x t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:vnht-dg7x t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:vnht-dg7x t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```