# Means of Transportation to Work (2007 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/commuters-means-of-transportation-to-work-2005-present) |
| Metadata | [Link](https://data.nola.gov/api/views/r2sy-8afw) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/r2sy-8afw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/r2sy-8afw/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | r2sy-8afw |
| Name | Means of Transportation to Work (2007 - Present) |
| Attribution | U.S. Census Bureau |
| Category | Transportation and Infrastructure |
| Tags | resultsnola, commuters, public transportation, travel time, carpooling, biking, walking |
| Created | 2015-09-08T21:06:17Z |
| Publication Date | 2015-09-08T21:47:39Z |

## Description

This data on means of transportation for commuters traveling to work comes from the U.S. Census Bureau's American Community Survey (ACS) one-year estimates, which are published on an annual basis.  It includes data for the following cities: Tampa, Florida; Memphis, Tennessee; Louisville, Kentucky; Nashville, Tennessee; Raleigh, North Carolina; Atlanta, Georgia; Baton Rouge, Louisiana; New Orleans, Louisiana. This data covers the time period of 2007 to present.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | rowid           | RowID           | text          | text          |
| Yes      | time           | date            | Date            | calendar_date | calendar_date |
| No       |                | year            | Year            | number        | number        |
| Yes      | series tag     | location        | Location        | text          | text          |
| Yes      | series tag     | indicatorname   | IndicatorName   | text          | text          |
| Yes      | numeric metric | indicatorvalue  | IndicatorValue  | number        | number        |
| Yes      | series tag     | indicatorid     | IndicatorID     | text          | text          |
| Yes      | series tag     | indicatorid_old | IndicatorID_old | text          | text          |
| Yes      | series tag     | indicatortable  | IndicatorTable  | text          | text          |
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
series e:r2sy-8afw d:2007-01-01T00:00:00.000Z t:indicatorid_old=HD01_calculation t:location="Miami, FL" t:indicatorid="Calculation: (B08301_001E - B08301_003E - B08301_021E) / (B08301_001E -B08301_021E)" t:indicatortable="B08301: Means of transportation to work" t:rowid="Miami, FL_Calculation: (B08301_001E - B08301_003E - B08301_021E) / (B08301_001E -B08301_021E)_2007" t:indicatorname="Percent of workers commuting to work by means other than driving alone, including carpooling, public transportation, biking, and walking" m:indicatorvalue=29.79048231

series e:r2sy-8afw d:2007-01-01T00:00:00.000Z t:indicatorid_old=HD01_VD17 t:location="Miami, FL" t:indicatorid=B08301_017E t:indicatortable="B08301: Means of transportation to work" t:rowid="Miami, FL_B08301_017E_2007" t:indicatorname="Workers commuting to work by motorcycle" m:indicatorvalue=491

series e:r2sy-8afw d:2007-01-01T00:00:00.000Z t:indicatorid_old=HD01_VD01 t:location="Miami, FL" t:indicatorid=B08301_001E t:indicatortable="B08301: Means of transportation to work" t:rowid="Miami, FL_B08301_001E_2007" t:indicatorname="Total workers 16 years and older" m:indicatorvalue=152887
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:r2sy-8afw l:"Means of Transportation to Work (2007 - Present)" t:attribution="U.S. Census Bureau" t:url=https://data.nola.gov/api/views/r2sy-8afw

property e:r2sy-8afw t:meta.view v:id=r2sy-8afw v:category="Transportation and Infrastructure" v:attributionLink=http://www.census.gov/ v:averageRating=0 v:name="Means of Transportation to Work (2007 - Present)" v:attribution="U.S. Census Bureau"

property e:r2sy-8afw t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:r2sy-8afw t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:r2sy-8afw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov v:Public_Access_Level=public
```

## Top Records

```ls
| rowid                                                                                              | date                | year | location  | indicatorname                                                                                                                            | indicatorvalue | indicatorid                                                                         | indicatorid_old  | indicatortable                          | 
| ================================================================================================== | =================== | ==== | ========= | ======================================================================================================================================== | ============== | =================================================================================== | ================ | ======================================= | 
| Miami, FL_Calculation: (B08301_001E - B08301_003E - B08301_021E) / (B08301_001E -B08301_021E)_2007 | 2007-01-01T00:00:00 | 2007 | Miami, FL | Percent of workers commuting to work by means other than driving alone, including carpooling, public transportation, biking, and walking | 29.79048231    | Calculation: (B08301_001E - B08301_003E - B08301_021E) / (B08301_001E -B08301_021E) | HD01_calculation | B08301: Means of transportation to work | 
| Miami, FL_B08301_017E_2007                                                                         | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers commuting to work by motorcycle                                                                                                  | 491            | B08301_017E                                                                         | HD01_VD17        | B08301: Means of transportation to work | 
| Miami, FL_B08301_001E_2007                                                                         | 2007-01-01T00:00:00 | 2007 | Miami, FL | Total workers 16 years and older                                                                                                         | 152887         | B08301_001E                                                                         | HD01_VD01        | B08301: Means of transportation to work | 
| Miami, FL_B08301_004E_2007                                                                         | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers commuting to work by carpool (car, truck, or van)                                                                                | 14508          | B08301_004E                                                                         | HD01_VD04        | B08301: Means of transportation to work | 
| Miami, FL_B08301_010E_2007                                                                         | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers commuting to work by public transportation (excluding taxicab)                                                                   | 19391          | B08301_010E                                                                         | HD01_VD10        | B08301: Means of transportation to work | 
| Miami, FL_B08301_016E_2007                                                                         | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers commuting to work by taxicab                                                                                                     | 389            | B08301_016E                                                                         | HD01_VD16        | B08301: Means of transportation to work | 
| Miami, FL_B08301_018E_2007                                                                         | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers commuting to work by bicycle                                                                                                     | 187            | B08301_018E                                                                         | HD01_VD18        | B08301: Means of transportation to work | 
| Miami, FL_B08301_021E_2007                                                                         | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers working at home                                                                                                                  | 3544           | B08301_021E                                                                         | HD01_VD21        | B08301: Means of transportation to work | 
| Miami, FL_B08301_003E_2007                                                                         | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers commuting to work by driving alone (car, truck, or van)                                                                          | 104853         | B08301_003E                                                                         | HD01_VD03        | B08301: Means of transportation to work | 
| Miami, FL_B08301_019E_2007                                                                         | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers commuting to work by walking                                                                                                     | 6269           | B08301_019E                                                                         | HD01_VD19        | B08301: Means of transportation to work | 
```