# Population and population growth (2010 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/population-and-population-growth-2010-present) |
| Metadata | [Link](https://data.nola.gov/api/views/uyf9-d7tt) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/uyf9-d7tt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/uyf9-d7tt/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | uyf9-d7tt |
| Name | Population and population growth (2010 - Present) |
| Attribution | U.S. Census Bureau |
| Category | Economy and Workforce |
| Tags | resultsnola |
| Created | 2015-10-05T18:32:09Z |
| Publication Date | 2015-10-05T18:35:56Z |

## Description

This population data comes from the U.S. Census Bureau's Population Estimates Program, which are published on an annual basis. It includes data for the following counties:  Orleans Parish, LA (New Orleans); Oklahoma County, OK (Oklahoma City); Hillsborough County, FL (Tampa); Wake County, NC (Raleigh); Fulton County, GA (Atlanta); Miami-Dade County, FL (Miami); Davidson County, TN (Nashville); Shelby County, TN (Memphis); and Jefferson County, KY (Louisville). This data covers the time period of 2010 to present.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | rowid          | RowID          | text          | text          |
| Yes      | time           | date           | Date           | calendar_date | calendar_date |
| No       |                | year           | Year           | number        | number        |
| Yes      | series tag     | location       | Location       | text          | text          |
| Yes      | series tag     | indicatorname  | IndicatorName  | text          | text          |
| Yes      | numeric metric | indicatorvalue | IndicatorValue | number        | number        |
| Yes      | series tag     | indicatorid    | IndicatorID    | text          | text          |
| Yes      | series tag     | indicatortable | IndicatorTable | text          | text          |
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
series e:uyf9-d7tt d:2012-01-01T00:00:00.000Z t:location="Tampa. FL" t:indicatorid=respop72012 t:indicatortable="Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014" t:rowid="Tampa. FL_respop72012_2012" t:indicatorname=Population m:indicatorvalue=1282032

series e:uyf9-d7tt d:2012-01-01T00:00:00.000Z t:location="Tampa. FL" t:indicatorid=Calculation t:indicatortable="Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014" t:rowid="Tampa. FL_Calculation_2012" t:indicatorname="Population growth" m:indicatorvalue=0.810870317365458

series e:uyf9-d7tt d:2014-01-01T00:00:00.000Z t:location="Tampa. FL" t:indicatorid=respop72014 t:indicatortable="Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014" t:rowid="Tampa. FL_respop72014_2014" t:indicatorname=Population m:indicatorvalue=1316298
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:uyf9-d7tt l:"Population and population growth (2010 - Present)" t:attribution="U.S. Census Bureau" t:url=https://data.nola.gov/api/views/uyf9-d7tt

property e:uyf9-d7tt t:meta.view v:id=uyf9-d7tt v:category="Economy and Workforce" v:attributionLink=http://www.census.gov/ v:averageRating=0 v:name="Population and population growth (2010 - Present)" v:attribution="U.S. Census Bureau"

property e:uyf9-d7tt t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:uyf9-d7tt t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:uyf9-d7tt t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                      | date                | year | location  | indicatorname     | indicatorvalue    | indicatorid | indicatortable                                                             | 
| ========================== | =================== | ==== | ========= | ================= | ================= | =========== | ========================================================================== | 
| Tampa. FL_respop72012_2012 | 2012-01-01T00:00:00 | 2012 | Tampa. FL | Population        | 1282032           | respop72012 | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
| Tampa. FL_Calculation_2012 | 2012-01-01T00:00:00 | 2012 | Tampa. FL | Population growth | 0.810870317365458 | Calculation | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
| Tampa. FL_respop72014_2014 | 2014-01-01T00:00:00 | 2014 | Tampa. FL | Population        | 1316298           | respop72014 | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
| Tampa. FL_Calculation_2014 | 2014-01-01T00:00:00 | 2014 | Tampa. FL | Population growth | 1.71178654632982  | Calculation | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
| Tampa. FL_respop72011_2011 | 2011-01-01T00:00:00 | 2011 | Tampa. FL | Population        | 1271720           | respop72011 | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
| Tampa. FL_Calculation_2013 | 2013-01-01T00:00:00 | 2013 | Tampa. FL | Population growth | 0.944828210216282 | Calculation | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
| Tampa. FL_respop72013_2013 | 2013-01-01T00:00:00 | 2013 | Tampa. FL | Population        | 1294145           | respop72013 | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
| Tampa. FL_respop72010_2010 | 2010-01-01T00:00:00 | 2010 | Tampa. FL | Population        | 1234145           | respop72010 | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
| Tampa. FL_Calculation_2011 | 2011-01-01T00:00:00 | 2011 | Tampa. FL | Population growth | 3.04461793387325  | Calculation | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
| Miami, FL_respop72012_2012 | 2012-01-01T00:00:00 | 2012 | Miami, FL | Population        | 2610960           | respop72012 | Annual Estimates of the Resident Population: April 1, 2010 to July 1, 2014 | 
```