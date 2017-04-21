# Travel time to work (2007 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/travel-time-to-work-2007-present) |
| Metadata | [Link](https://data.nola.gov/api/views/qwed-53qf) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/qwed-53qf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/qwed-53qf/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | qwed-53qf |
| Name | Travel time to work (2007 - Present) |
| Attribution | U.S. Census Bureau |
| Category | Transportation and Infrastructure |
| Tags | resultsnola, commuters, public transportation, travel time, carpooling, biking, walking |
| Created | 2015-09-16T16:37:42Z |
| Publication Date | 2015-09-16T21:05:30Z |

## Description

This data on travel time to work for commuters comes from the U.S. Census Bureau's American Community Survey (ACS) one-year estimates, which are published on an annual basis.  It includes data for the following cities: Tampa, Florida; Memphis, Tennessee; Louisville, Kentucky; Nashville, Tennessee; Raleigh, North Carolina; Atlanta, Georgia; Baton Rouge, Louisiana; New Orleans, Louisiana. This data covers the time period of 2007 to present.

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
series e:qwed-53qf d:2007-01-01T00:00:00.000Z t:indicatorid_old=HD01_VD02 t:location="Miami, FL" t:indicatorid=B08303_002E t:indicatortable="B08303: Travel time to work" t:rowid="Miami, FL_B08303_002E_2007" t:indicatorname="Workers traveling less than 5 minutes to work" m:indicatorvalue=2555

series e:qwed-53qf d:2007-01-01T00:00:00.000Z t:indicatorid_old=HD01_VD01 t:location="Miami, FL" t:indicatorid=B08303_001E t:indicatortable="B08303: Travel time to work" t:rowid="Miami, FL_B08303_001E_2007" t:indicatorname="Total workers 16 years and older" m:indicatorvalue=149343

series e:qwed-53qf d:2007-01-01T00:00:00.000Z t:indicatorid_old=Calculation:(HD01_VD02+HD01_VD03+HD01_VD04+HD01_VD05+HD01_VD06+HD01_VD07)/HD01_VD01 t:location="Miami, FL" t:indicatorid=Calculation:(B08303_002E+B08303_003E+B08303_004E+B08303_005E+B08303_006E+B08303_007E)/B08303_001E t:indicatortable="B08303: Travel time to work" t:rowid="Miami, FL_Calculation:(B08303_002E+B08303_003E+B08303_004E+B08303_005E+B08303_006E+B08303_007E)/B08303_001E_2007" t:indicatorname="Percent of workers traveling less than 30 minutes to work" m:indicatorvalue=56.4900932752121
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:qwed-53qf l:"Travel time to work (2007 - Present)" t:attribution="U.S. Census Bureau" t:url=https://data.nola.gov/api/views/qwed-53qf

property e:qwed-53qf t:meta.view v:id=qwed-53qf v:category="Transportation and Infrastructure" v:attributionLink=http://www.census.gov/ v:averageRating=0 v:name="Travel time to work (2007 - Present)" v:attribution="U.S. Census Bureau"

property e:qwed-53qf t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:qwed-53qf t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:qwed-53qf t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                                                                            | date                | year | location  | indicatorname                                             | indicatorvalue   | indicatorid                                                                                       | indicatorid_old                                                                     | indicatortable              | 
| ================================================================================================================ | =================== | ==== | ========= | ========================================================= | ================ | ================================================================================================= | =================================================================================== | =========================== | 
| Miami, FL_B08303_002E_2007                                                                                       | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers traveling less than 5 minutes to work             | 2555             | B08303_002E                                                                                       | HD01_VD02                                                                           | B08303: Travel time to work | 
| Miami, FL_B08303_001E_2007                                                                                       | 2007-01-01T00:00:00 | 2007 | Miami, FL | Total workers 16 years and older                          | 149343           | B08303_001E                                                                                       | HD01_VD01                                                                           | B08303: Travel time to work | 
| Miami, FL_Calculation:(B08303_002E+B08303_003E+B08303_004E+B08303_005E+B08303_006E+B08303_007E)/B08303_001E_2007 | 2007-01-01T00:00:00 | 2007 | Miami, FL | Percent of workers traveling less than 30 minutes to work | 56.4900932752121 | Calculation:(B08303_002E+B08303_003E+B08303_004E+B08303_005E+B08303_006E+B08303_007E)/B08303_001E | Calculation:(HD01_VD02+HD01_VD03+HD01_VD04+HD01_VD05+HD01_VD06+HD01_VD07)/HD01_VD01 | B08303: Travel time to work | 
| Miami, FL_B08303_004E_2007                                                                                       | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers traveling 10 to 14 minutes to work                | 15683            | B08303_004E                                                                                       | HD01_VD04                                                                           | B08303: Travel time to work | 
| Miami, FL_B08303_005E_2007                                                                                       | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers traveling 15 to 19 minutes to work                | 18558            | B08303_005E                                                                                       | HD01_VD05                                                                           | B08303: Travel time to work | 
| Miami, FL_B08303_009E_2007                                                                                       | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers traveling 35 to 39 minutes to work                | 5962             | B08303_009E                                                                                       | HD01_VD09                                                                           | B08303: Travel time to work | 
| Miami, FL_B08303_007E_2007                                                                                       | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers traveling 25 to 29 minutes to work                | 8845             | B08303_007E                                                                                       | HD01_VD07                                                                           | B08303: Travel time to work | 
| Miami, FL_B08303_008E_2007                                                                                       | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers traveling 30 to 34 minutes to work                | 23705            | B08303_008E                                                                                       | HD01_VD08                                                                           | B08303: Travel time to work | 
| Miami, FL_B08303_010E_2007                                                                                       | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers traveling 40 to 44 minutes to work                | 7541             | B08303_010E                                                                                       | HD01_VD10                                                                           | B08303: Travel time to work | 
| Miami, FL_B08303_012E_2007                                                                                       | 2007-01-01T00:00:00 | 2007 | Miami, FL | Workers traveling 60 to 89 minutes to work                | 10857            | B08303_012E                                                                                       | HD01_VD12                                                                           | B08303: Travel time to work | 
```