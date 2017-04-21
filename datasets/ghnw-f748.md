# Housing Costs (2007 - Present)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-costs-renters-2007-present) |
| Metadata | [Link](https://data.nola.gov/api/views/ghnw-f748) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/ghnw-f748/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/ghnw-f748/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | ghnw-f748 |
| Name | Housing Costs (2007 - Present) |
| Attribution | U.S. Census Bureau |
| Category | Housing, Land Use, and Blight |
| Tags | resultsnola |
| Created | 2015-09-22T17:00:09Z |
| Publication Date | 2015-09-24T16:13:06Z |

## Description

This data on housing costs for renters and homeowners comes from the U.S. Census Bureau's American Community Survey (ACS) one-year estimates, which are published on an annual basis. It includes data for the following cities: Tampa, Florida; Memphis, Tennessee; Louisville, Kentucky; Nashville, Tennessee; Raleigh, North Carolina; Atlanta, Georgia; Baton Rouge, Louisiana; New Orleans, Louisiana. This data covers the time period of 2007 to present.

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
series e:ghnw-f748 d:2007-01-01T00:00:00.000Z t:indicatorid_old=HD01_VD02 t:location="Miami, FL" t:indicatorid=B25070_002E t:indicatortable="B25070. Gross rent as a percentage of household income in the past 12 months" t:rowid="Miami, FL_B25070_002E_2007" t:indicatorname="Renter households paying less than 10 percent of pre-tax income on housing" m:indicatorvalue=1653

series e:ghnw-f748 d:2007-01-01T00:00:00.000Z t:indicatorid_old=HD01_VD03 t:location="Miami, FL" t:indicatorid=B25070_003E t:indicatortable="B25070. Gross rent as a percentage of household income in the past 12 months" t:rowid="Miami, FL_B25070_003E_2007" t:indicatorname="Renter households paying 10 to 14.9 percent of pre-tax income on housing" m:indicatorvalue=3248

series e:ghnw-f748 d:2007-01-01T00:00:00.000Z t:indicatorid_old=HD01_VD07 t:location="Miami, FL" t:indicatorid=B25070_007E t:indicatortable="B25070. Gross rent as a percentage of household income in the past 12 months" t:rowid="Miami, FL_B25070_007E_2007" t:indicatorname="Renter households paying 30 to 34.9 percent of pre-tax income on housing" m:indicatorvalue=10402
```

## Meta Commands

```ls
metric m:indicatorvalue p:double l:IndicatorValue t:dataTypeName=number

entity e:ghnw-f748 l:"Housing Costs (2007 - Present)" t:attribution="U.S. Census Bureau" t:url=https://data.nola.gov/api/views/ghnw-f748

property e:ghnw-f748 t:meta.view v:id=ghnw-f748 v:category="Housing, Land Use, and Blight" v:attributionLink=http://www.census.gov/ v:averageRating=0 v:name="Housing Costs (2007 - Present)" v:attribution="U.S. Census Bureau"

property e:ghnw-f748 t:meta.view.owner v:id=ii98-542e v:screenName=mschigoda v:displayName=mschigoda

property e:ghnw-f748 t:meta.view.tableauthor v:id=ii98-542e v:screenName=mschigoda v:roleName=publisher v:displayName=mschigoda

property e:ghnw-f748 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| rowid                                                                                       | date                | year | location  | indicatorname                                                              | indicatorvalue   | indicatorid                                                                  | indicatorid_old                                                    | indicatortable                                                               | 
| =========================================================================================== | =================== | ==== | ========= | ========================================================================== | ================ | ============================================================================ | ================================================================== | ============================================================================ | 
| Miami, FL_B25070_002E_2007                                                                  | 2007-01-01T00:00:00 | 2007 | Miami, FL | Renter households paying less than 10 percent of pre-tax income on housing | 1653             | B25070_002E                                                                  | HD01_VD02                                                          | B25070. Gross rent as a percentage of household income in the past 12 months | 
| Miami, FL_B25070_003E_2007                                                                  | 2007-01-01T00:00:00 | 2007 | Miami, FL | Renter households paying 10 to 14.9 percent of pre-tax income on housing   | 3248             | B25070_003E                                                                  | HD01_VD03                                                          | B25070. Gross rent as a percentage of household income in the past 12 months | 
| Miami, FL_B25070_007E_2007                                                                  | 2007-01-01T00:00:00 | 2007 | Miami, FL | Renter households paying 30 to 34.9 percent of pre-tax income on housing   | 10402            | B25070_007E                                                                  | HD01_VD07                                                          | B25070. Gross rent as a percentage of household income in the past 12 months | 
| Miami, FL_B25070_005E_2007                                                                  | 2007-01-01T00:00:00 | 2007 | Miami, FL | Renter households paying 20 to 24.9 percent of pre-tax income on housing   | 7681             | B25070_005E                                                                  | HD01_VD05                                                          | B25070. Gross rent as a percentage of household income in the past 12 months | 
| Miami, FL_B25070_008E_2007                                                                  | 2007-01-01T00:00:00 | 2007 | Miami, FL | Renter households paying 35 to 39.9 percent of pre-tax income on housing   | 4289             | B25070_008E                                                                  | HD01_VD08                                                          | B25070. Gross rent as a percentage of household income in the past 12 months | 
| Miami, FL_B25070_011E_2007                                                                  | 2007-01-01T00:00:00 | 2007 | Miami, FL | Renter households not computed                                             | 3707             | B25070_011E                                                                  | HD01_VD11                                                          | B25070. Gross rent as a percentage of household income in the past 12 months | 
| Miami, FL_B25070_009E_2007                                                                  | 2007-01-01T00:00:00 | 2007 | Miami, FL | Renter households paying 40 to 49.9 percent of pre-tax income on housing   | 9079             | B25070_009E                                                                  | HD01_VD09                                                          | B25070. Gross rent as a percentage of household income in the past 12 months | 
| Miami, FL_B25070_010E_2007                                                                  | 2007-01-01T00:00:00 | 2007 | Miami, FL | Renter households paying more than 50 percent of pre-tax income on housing | 29143            | B25070_010E                                                                  | HD01_VD10                                                          | B25070. Gross rent as a percentage of household income in the past 12 months | 
| Miami, FL_Calculation: (B25070_008E+B25070_009E+B25070_010E)/(B25070_001E-B25070_011E)_2007 | 2007-01-01T00:00:00 | 2007 | Miami, FL | Percent of renter households paying unaffordable housing cost              | 52.1511378273937 | Calculation: (B25070_008E+B25070_009E+B25070_010E)/(B25070_001E-B25070_011E) | Calculation: (HD01_VD08+HD01_VD09+HD01_VD10)/(HD01_VD01-HD01_VD11) | B25070. Gross rent as a percentage of household income in the past 12 months | 
| Miami, FL_B25070_004E_2007                                                                  | 2007-01-01T00:00:00 | 2007 | Miami, FL | Renter households paying 15 to 19.9 percent of pre-tax income on housing   | 5815             | B25070_004E                                                                  | HD01_VD04                                                          | B25070. Gross rent as a percentage of household income in the past 12 months | 
```