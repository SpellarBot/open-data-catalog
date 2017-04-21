# 2015 Annual Performance Report Key Indicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-annual-performance-report-key-indicators) |
| Metadata | [Link](https://data.austintexas.gov/api/views/dgbw-ce4x) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/dgbw-ce4x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/dgbw-ce4x/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | dgbw-ce4x |
| Name | 2015 Annual Performance Report Key Indicators |
| Category | Government |
| Tags | indicator, measure, annual performance report |
| Created | 2016-04-22T21:59:47Z |
| Publication Date | 2016-05-18T14:20:08Z |

## Description

Dataset for the 2015 Annual Performance Report

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | department_name           | Department Name           | text          | text          |
| Yes      | series tag     | measure_id                | Measure ID                | text          | number        |
| Yes      | series tag     | measure_name              | Measure Name              | text          | text          |
| Yes      | series tag     | frequency                 | Frequency                 | text          | text          |
| No       |                | fiscal_year               | Fiscal Year               | number        | number        |
| Yes      | numeric metric | actual_value              | Result                    | number        | number        |
| Yes      | numeric metric | amended_value             | Goal                      | number        | number        |
| Yes      | numeric metric | long_term_goal            | Long Term Goal            | number        | number        |
| Yes      | time           | data_as_of_date           | Data as of Date           | calendar_date | calendar_date |
| Yes      | series tag     | frequency_of_goal         | Frequency of Goal         | text          | text          |
| Yes      | numeric metric | supports_goal_value       | Supports Goal Value       | number        | number        |
| Yes      | series tag     | supports_goal             | Supports Goal             | text          | text          |
| Yes      | numeric metric | dashboard_indicator_value | Dashboard Indicator Value | number        | number        |
| Yes      | series tag     | dashboard_indicator       | Dashboard Indicator       | text          | text          |
| Yes      | series tag     | legend                    | Legend                    | text          | text          |
```

## Time Field

```ls
Value = data_as_of_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:dgbw-ce4x d:2010-09-30T00:00:00.000Z t:measure_id=1838 t:frequency_of_goal=Annual t:frequency=Annual t:department_name="Animal Services" t:dashboard_indicator=No t:measure_name="Number of animals sterilized in the community" t:supports_goal=No m:supports_goal_value=0 m:actual_value=6718 m:amended_value=3500 m:dashboard_indicator_value=0

series e:dgbw-ce4x d:2011-09-30T00:00:00.000Z t:measure_id=1838 t:frequency_of_goal=Annual t:frequency=Annual t:department_name="Animal Services" t:dashboard_indicator=No t:measure_name="Number of animals sterilized in the community" t:supports_goal=No m:supports_goal_value=0 m:actual_value=5019 m:amended_value=6100 m:dashboard_indicator_value=0

series e:dgbw-ce4x d:2012-09-30T00:00:00.000Z t:measure_id=1838 t:frequency_of_goal=Annual t:frequency=Annual t:department_name="Animal Services" t:dashboard_indicator=No t:measure_name="Number of animals sterilized in the community" t:supports_goal=No m:supports_goal_value=0 m:actual_value=6692 m:amended_value=5000 m:dashboard_indicator_value=0
```

## Meta Commands

```ls
metric m:actual_value p:integer l:Result t:dataTypeName=number

metric m:amended_value p:integer l:Goal t:dataTypeName=number

metric m:long_term_goal p:integer l:"Long Term Goal" t:dataTypeName=number

metric m:supports_goal_value p:integer l:"Supports Goal Value" t:dataTypeName=number

metric m:dashboard_indicator_value p:integer l:"Dashboard Indicator Value" t:dataTypeName=number

entity e:dgbw-ce4x l:"2015 Annual Performance Report Key Indicators" t:url=https://data.austintexas.gov/api/views/dgbw-ce4x

property e:dgbw-ce4x t:meta.view v:id=dgbw-ce4x v:category=Government v:averageRating=0 v:name="2015 Annual Performance Report Key Indicators"

property e:dgbw-ce4x t:meta.view.owner v:id=gzfz-ijhr v:screenName="Peter Feighner" v:lastNotificationSeenAt=1492183538 v:displayName="Peter Feighner"

property e:dgbw-ce4x t:meta.view.tableauthor v:id=gzfz-ijhr v:screenName="Peter Feighner" v:roleName=administrator v:lastNotificationSeenAt=1492183538 v:displayName="Peter Feighner"
```

## Top Records

```ls
| department_name | measure_id | measure_name                                          | frequency | fiscal_year | actual_value | amended_value | long_term_goal | data_as_of_date     | frequency_of_goal | supports_goal_value | supports_goal | dashboard_indicator_value | dashboard_indicator | legend | 
| =============== | ========== | ===================================================== | ========= | =========== | ============ | ============= | ============== | =================== | ================= | =================== | ============= | ========================= | =================== | ====== | 
| Animal Services | 1838       | Number of animals sterilized in the community         | Annual    | 2010        | 6718         | 3500          |                | 2010-09-30T00:00:00 | Annual            | 0                   | No            | 0                         | No                  |        | 
| Animal Services | 1838       | Number of animals sterilized in the community         | Annual    | 2011        | 5019         | 6100          |                | 2011-09-30T00:00:00 | Annual            | 0                   | No            | 0                         | No                  |        | 
| Animal Services | 1838       | Number of animals sterilized in the community         | Annual    | 2012        | 6692         | 5000          |                | 2012-09-30T00:00:00 | Annual            | 0                   | No            | 0                         | No                  |        | 
| Animal Services | 1838       | Number of animals sterilized in the community         | Annual    | 2013        | 6625         | 6200          |                | 2013-09-30T00:00:00 | Annual            | 1                   | Yes           | 0                         | No                  |        | 
| Animal Services | 1838       | Number of animals sterilized in the community         | Annual    | 2014        | 7636         | 7500          |                | 2014-09-30T00:00:00 | Annual            | 1                   | Yes           | 0                         | No                  |        | 
| Animal Services | 1838       | Number of animals sterilized in the community         | Annual    | 2015        | 10182        | 7500          |                | 2015-09-30T00:00:00 | Annual            | 1                   | Yes           | 0                         | No                  |        | 
| Animal Services | 1850       | Number of spay/neuters performed at the Animal Center | Annual    | 2010        | 3364         | 4000          |                | 2010-09-30T00:00:00 | Annual            | 0                   | No            | 0                         | No                  |        | 
| Animal Services | 1850       | Number of spay/neuters performed at the Animal Center | Annual    | 2011        | 6036         | 4000          |                | 2011-09-30T00:00:00 | Annual            | 0                   | No            | 0                         | No                  |        | 
| Animal Services | 1850       | Number of spay/neuters performed at the Animal Center | Annual    | 2012        | 6091         | 6000          |                | 2012-09-30T00:00:00 | Annual            | 0                   | No            | 0                         | No                  |        | 
| Animal Services | 1850       | Number of spay/neuters performed at the Animal Center | Annual    | 2013        | 6492         | 6500          |                | 2013-09-30T00:00:00 | Annual            | 0                   | No            | 0                         | No                  |        | 
```