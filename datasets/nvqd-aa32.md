# Social Indicators Report Data By Community District

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/social-indicators-report-data-by-community-district) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nvqd-aa32) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nvqd-aa32/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nvqd-aa32/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nvqd-aa32 |
| Name | Social Indicators Report Data By Community District |
| Attribution | Mayor's Office of Operations (OPS) |
| Category | Social Services |
| Tags | ceo, moo, indicators, social conditions |
| Created | 2016-04-13T15:20:51Z |
| Publication Date | 2016-04-25T21:24:38Z |

## Description

Select metrics by Community District/Neighborhood Tabulation Districts  where available. To see the full set of indicators (including those without CD/NTD level data), please refer to ?Social Indicators Report Data ? Citywide? at https://data.cityofnewyork.us/Social-Services/Social-Indicators-Report-Data-Citywide/gysw-j2f3.

The Social Indicators Report is an analysis of social conditions across New York City, including geographic and demographic breakdowns, changes over time, and the Mayor's plan for responding to problems highlighted in the report. The report can be found at http://www1.nyc.gov/assets/operations/downloads/pdf/Social-Indicators-Report-April-2016.pdf

*data not available; # data are suppressed due to imprecise and unreliable estimates

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | domain      | Domain     | text      | text        |
| Yes      | series tag     | indicator   | Indicator  | text      | text        |
| No       |                | cd          | CD         | text      | text        |
| Yes      | series tag     | 2005        | 2005       | text      | text        |
| Yes      | series tag     | 2006        | 2006       | text      | text        |
| Yes      | numeric metric | 2007        | 2007       | number    | text        |
| Yes      | series tag     | 2008        | 2008       | text      | text        |
| Yes      | series tag     | 2009        | 2009       | text      | text        |
| Yes      | numeric metric | 2010        | 2010       | number    | text        |
| Yes      | numeric metric | 2011        | 2011       | number    | text        |
| Yes      | numeric metric | 2012        | 2012       | number    | text        |
| Yes      | numeric metric | 2013        | 2013       | number    | text        |
| Yes      | numeric metric | 2014        | 2014       | number    | text        |
| Yes      | numeric metric | 2015        | 2015       | number    | text        |
| Yes      | series tag     | definition  | Definition | text      | text        |
| Yes      | series tag     | source      | Source     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = cd
```

## Data Commands

```ls
series e:nvqd-aa32 d:2016-04-25T14:23:03.000Z t:2008=* t:indicator="Premature Mortality Rate" t:2009=* t:2006=* t:2007=* t:source="NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf" t:definition="Age-adjusted rate of deaths under the age of 65 years per 100,000 population." t:2014=* t:2005=* t:2015=* t:domain=Health t:2010=* m:2013=2.9 m:2012=2.9 m:2011=3.4

series e:nvqd-aa32 d:2016-04-25T14:23:03.000Z t:2008=* t:indicator="Premature Mortality Rate" t:2009=* t:2006=* t:2007=* t:source="NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf" t:definition="Age-adjusted rate of deaths under the age of 65 years per 100,000 population." t:2014=* t:2005=* t:2015=* t:domain=Health t:2010=* m:2013=2.4 m:2012=2.7 m:2011=2.6

series e:nvqd-aa32 d:2016-04-25T14:23:03.000Z t:2008=* t:indicator="Premature Mortality Rate" t:2009=* t:2006=* t:2007=* t:source="NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf" t:definition="Age-adjusted rate of deaths under the age of 65 years per 100,000 population." t:2014=* t:2005=* t:2015=* t:domain=Health t:2010=* m:2013=3.6 m:2012=3.1 m:2011=3.6
```

## Meta Commands

```ls
metric m:2013 p:float l:2013 t:dataTypeName=number

entity e:nvqd-aa32 l:"Social Indicators Report Data By Community District" t:attribution="Mayor's Office of Operations (OPS)" t:url=https://data.cityofnewyork.us/api/views/nvqd-aa32

property e:nvqd-aa32 t:meta.view v:id=nvqd-aa32 v:category="Social Services" v:averageRating=0 v:name="Social Indicators Report Data By Community District" v:attribution="Mayor's Office of Operations (OPS)"

property e:nvqd-aa32 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nvqd-aa32 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | domain | indicator                | cd          | 2005 | 2006 | 2007 | 2008 | 2009 | 2010 | 2011 | 2012 | 2013 | 2014 | 2015 | definition                                                                    | source                                                                                                             | 
| =========== | ====== | ======================== | =========== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ============================================================================= | ================================================================================================================== | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 1  | *    | *    | *    | *    | *    | *    | 3.4  | 2.9  | 2.9  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 2  | *    | *    | *    | *    | *    | *    | 2.6  | 2.7  | 2.4  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 3  | *    | *    | *    | *    | *    | *    | 3.6  | 3.1  | 3.6  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 4  | *    | *    | *    | *    | *    | *    | 2.5  | 2.6  | 2.4  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 5  | *    | *    | *    | *    | *    | *    | 2.7  | 2.4  | 2.4  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 6  | *    | *    | *    | *    | *    | *    | 2.9  | 2.9  | 3.2  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 7  | *    | *    | *    | *    | *    | *    | 2.3  | 2.1  | 2.2  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 8  | *    | *    | *    | *    | *    | *    | 1.8  | 1.7  | 1.3  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 9  | *    | *    | *    | *    | *    | *    | 2.4  | 2.2  | 2.0  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
| 1461594183  | Health | Premature Mortality Rate | Bronx CD 10 | *    | *    | *    | *    | *    | *    | 1.9  | 2.1  | 1.7  | *    | *    | Age-adjusted rate of deaths under the age of 65 years per 100,000 population. | NYC Department of Health and Mental Hygiene; http://www.nyc.gov/html/doh/downloads/pdf/vs/mortality-report2013.pdf | 
```