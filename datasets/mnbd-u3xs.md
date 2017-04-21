# Inmates In Orleans Parish Prison, Daily Number (2011 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inmates-in-orleans-parish-prison-daily-number-2011-present-e83b2) |
| Metadata | [Link](https://data.nola.gov/api/views/mnbd-u3xs) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/mnbd-u3xs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/mnbd-u3xs/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | mnbd-u3xs |
| Name | Inmates In Orleans Parish Prison, Daily Number (2011 - Present) |
| Attribution | Orleans Parish Sheriff's Office |
| Category | Public Safety and Preparedness |
| Tags | resultsnola |
| Created | 2016-01-19T17:56:31Z |
| Publication Date | 2016-01-19T17:59:44Z |

## Description

This dataset shows the number of inmates in Orleans Parish Prison on a daily basis from 2011 to present.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | indicatorname  | IndicatorName  | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
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
series e:mnbd-u3xs d:2011-01-01T00:00:00.000Z t:rowid="Inmates in Orleans Parish Prison (daily)1-1-2011" t:indicatorname="Inmates in Orleans Parish Prison (daily)" m:indicatorvalue=2828

series e:mnbd-u3xs d:2011-01-02T00:00:00.000Z t:rowid="Inmates in Orleans Parish Prison (daily)1-2-2011" t:indicatorname="Inmates in Orleans Parish Prison (daily)" m:indicatorvalue=2839

series e:mnbd-u3xs d:2011-01-03T00:00:00.000Z t:rowid="Inmates in Orleans Parish Prison (daily)1-3-2011" t:indicatorname="Inmates in Orleans Parish Prison (daily)" m:indicatorvalue=2871
```

## Meta Commands

```ls
metric m:indicatorvalue p:integer l:IndicatorValue t:dataTypeName=number

entity e:mnbd-u3xs l:"Inmates In Orleans Parish Prison, Daily Number (2011 - Present)" t:attribution="Orleans Parish Sheriff's Office" t:url=https://data.nola.gov/api/views/mnbd-u3xs

property e:mnbd-u3xs t:meta.view v:id=mnbd-u3xs v:category="Public Safety and Preparedness" v:attributionLink=http://www.opcso.org/ v:averageRating=0 v:name="Inmates In Orleans Parish Prison, Daily Number (2011 - Present)" v:attribution="Orleans Parish Sheriff's Office"

property e:mnbd-u3xs t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:mnbd-u3xs t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:mnbd-u3xs t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov v:Public_Access_Level=public
```

## Top Records

```ls
| rowid                                             | date                | year | indicatorname                            | indicatorvalue | 
| ================================================= | =================== | ==== | ======================================== | ============== | 
| Inmates in Orleans Parish Prison (daily)1-1-2011  | 2011-01-01T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2828           | 
| Inmates in Orleans Parish Prison (daily)1-2-2011  | 2011-01-02T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2839           | 
| Inmates in Orleans Parish Prison (daily)1-3-2011  | 2011-01-03T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2871           | 
| Inmates in Orleans Parish Prison (daily)1-4-2011  | 2011-01-04T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2871           | 
| Inmates in Orleans Parish Prison (daily)1-5-2011  | 2011-01-05T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2812           | 
| Inmates in Orleans Parish Prison (daily)1-6-2011  | 2011-01-06T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2811           | 
| Inmates in Orleans Parish Prison (daily)1-7-2011  | 2011-01-07T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2827           | 
| Inmates in Orleans Parish Prison (daily)1-8-2011  | 2011-01-08T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2812           | 
| Inmates in Orleans Parish Prison (daily)1-9-2011  | 2011-01-09T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2817           | 
| Inmates in Orleans Parish Prison (daily)1-10-2011 | 2011-01-10T00:00:00 | 2011 | Inmates in Orleans Parish Prison (daily) | 2845           | 
```