# Citizens feeling safe in neighborhood (2009 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/citizens-reporting-confidence-in-nopd-and-feeling-safe-in-their-neighborhood-2009-present) |
| Metadata | [Link](https://data.nola.gov/api/views/vmfi-gxr8) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/vmfi-gxr8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/vmfi-gxr8/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | vmfi-gxr8 |
| Name | Citizens feeling safe in neighborhood (2009 - Present) |
| Attribution | New Orleans Crime Coalition's Citizen Satisfaction Survey |
| Category | Public Safety and Preparedness |
| Tags | resultsnola |
| Created | 2015-04-23T21:44:55Z |
| Publication Date | 2015-11-05T16:56:19Z |

## Description

This data comes from a survey conducted by the New Orleans Crime Coalition's Citizen Satisfaction Survey. The survey sample includes 600 New Orleans residents, 75 from each police distract. The data has a margin of error of plus or minus 4% and has a 95% confidence interval. The results of the survey represent citizen perceptions and opinions, not objective measures of performance or safety.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | series tag     | indicator      | IndicatorName  | text          | text          |
| No       |                | indicatorlabel | IndicatorLabel | text          | text          |
| Yes      | time           | year           | Date           | calendar_date | calendar_date |
| Yes      | series tag     | datelabel      | DateLabel      | text          | text          |
| No       |                | month          | Month          | text          | text          |
| No       |                | year2          | Year           | number        | number        |
| Yes      | numeric metric | percent        | IndicatorValue | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = indicatorlabel,year2,month
```

## Data Commands

```ls
series e:vmfi-gxr8 d:2009-08-01T00:00:00.000Z t:indicator="Percent of citizens reporting feeling safe in their neighborhood" t:datelabel="Aug, 2009" t:rowid="Percent of citizens reporting feeling safe in their neighborhoodAugust2009" m:percent=69

series e:vmfi-gxr8 d:2010-08-01T00:00:00.000Z t:indicator="Percent of citizens reporting feeling safe in their neighborhood" t:datelabel="Aug, 2010" t:rowid="Percent of citizens reporting feeling safe in their neighborhoodAugust2010" m:percent=76

series e:vmfi-gxr8 d:2011-02-01T00:00:00.000Z t:indicator="Percent of citizens reporting feeling safe in their neighborhood" t:datelabel="Feb, 2011" t:rowid="Percent of citizens reporting feeling safe in their neighborhoodFebruary2011" m:percent=74
```

## Meta Commands

```ls
metric m:percent p:integer l:IndicatorValue t:dataTypeName=number

entity e:vmfi-gxr8 l:"Citizens feeling safe in neighborhood (2009 - Present)" t:attribution="New Orleans Crime Coalition's Citizen Satisfaction Survey" t:url=https://data.nola.gov/api/views/vmfi-gxr8

property e:vmfi-gxr8 t:meta.view v:id=vmfi-gxr8 v:category="Public Safety and Preparedness" v:attributionLink=http://crimecoalitionnola.com/ v:averageRating=0 v:name="Citizens feeling safe in neighborhood (2009 - Present)" v:attribution="New Orleans Crime Coalition's Citizen Satisfaction Survey"

property e:vmfi-gxr8 t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:vmfi-gxr8 t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:vmfi-gxr8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                                        | indicator                                                        | indicatorlabel | year                | datelabel | month    | year2 | percent | 
| ============================================================================ | ================================================================ | ============== | =================== | ========= | ======== | ===== | ======= | 
| Percent of citizens reporting feeling safe in their neighborhoodAugust2009   | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2009-08-01T00:00:00 | Aug, 2009 | August   | 2009  | 69      | 
| Percent of citizens reporting feeling safe in their neighborhoodAugust2010   | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2010-08-01T00:00:00 | Aug, 2010 | August   | 2010  | 76      | 
| Percent of citizens reporting feeling safe in their neighborhoodFebruary2011 | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2011-02-01T00:00:00 | Feb, 2011 | February | 2011  | 74      | 
| Percent of citizens reporting feeling safe in their neighborhoodAugust2011   | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2011-08-01T00:00:00 | Aug, 2011 | August   | 2011  | 77      | 
| Percent of citizens reporting feeling safe in their neighborhoodFebruary2012 | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2012-02-01T00:00:00 | Feb, 2012 | February | 2012  | 81      | 
| Percent of citizens reporting feeling safe in their neighborhoodAugust2012   | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2012-08-01T00:00:00 | Aug, 2012 | August   | 2012  | 79      | 
| Percent of citizens reporting feeling safe in their neighborhoodMarch2013    | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2013-03-01T00:00:00 | Mar, 2013 | March    | 2013  | 79      | 
| Percent of citizens reporting feeling safe in their neighborhoodAugust2013   | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2013-08-01T00:00:00 | Aug, 2013 | August   | 2013  | 85      | 
| Percent of citizens reporting feeling safe in their neighborhoodMarch2014    | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2014-03-01T00:00:00 | Mar, 2014 | March    | 2014  | 81      | 
| Percent of citizens reporting feeling safe in their neighborhoodFebruary2015 | Percent of citizens reporting feeling safe in their neighborhood | Safe           | 2015-02-01T00:00:00 | Feb, 2015 | February | 2015  | 77      | 
```