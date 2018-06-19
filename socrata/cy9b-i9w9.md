# Metropolitan Transportation Authority (MTA) Performance Indicators per Agency: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/metropolitan-transportation-authority-mta-performance-indicators-per-agency-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/cy9b-i9w9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cy9b-i9w9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cy9b-i9w9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cy9b-i9w9 |
| Name | Metropolitan Transportation Authority (MTA) Performance Indicators per Agency: Beginning 2008 |
| Attribution | MTA Headquarters, New York City Transit, Long Island Rail Road, Metro-North Railroad, MTA Bus and MTA Bridges and Tunnels |
| Category | Transportation |
| Tags | performance indicator, year-to-date target, year-to-date actual |
| Created | 2013-04-26T17:04:19Z |
| Publication Date | 2017-03-28T22:22:02Z |

## Description

This information comes from the MTA?s Performance Dashboard and is used to increase transparency at the MTA. The Key Performance Indicators (KPI) are used to track performance is areas such as On Time Performance.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | numeric metric | indicator_sequence | Indicator Sequence | number    | number      |
| Yes      | numeric metric | parent_sequence    | Parent Sequence    | number    | number      |
| Yes      | series tag     | agency_name        | Agency Name        | text      | text        |
| Yes      | series tag     | indicator_name     | Indicator Name     | text      | text        |
| Yes      | series tag     | description        | Description        | text      | text        |
| Yes      | series tag     | category           | Category           | text      | text        |
| Yes      | series tag     | frequency          | Frequency          | text      | text        |
| Yes      | series tag     | desired_change     | Desired Change     | text      | text        |
| Yes      | series tag     | indicator_unit     | Indicator Unit     | text      | text        |
| Yes      | numeric metric | decimal_places     | Decimal Places     | number    | number      |
| Yes      | time           | period_year        | Period Year        | text      | number      |
| Yes      | numeric metric | period_month       | Period Month       | number    | number      |
| Yes      | numeric metric | ytd_target         | YTD Target         | number    | number      |
| Yes      | numeric metric | ytd_actual         | YTD Actual         | number    | number      |
| Yes      | numeric metric | monthly_target     | Monthly Target     | number    | number      |
| Yes      | numeric metric | monthly_actual     | Monthly Actual     | number    | number      |
| Yes      | series tag     | period             | Period             | text      | text        |
```

## Time Field

```ls
Value = period_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:cy9b-i9w9 d:2008-01-01T00:00:00.000Z t:category="Safety Indicators" t:indicator_name="Collisions with Injury Rate" t:description="All customer collisions with injuries on B&T property.  The rate is collisions with injuries per million vehicles." t:indicator_unit=- t:frequency=M t:period=2008-01 t:agency_name="Bridges and Tunnels" t:desired_change=D m:ytd_actual=0.54 m:monthly_actual=0.54 m:ytd_target=0.75 m:parent_sequence=0 m:decimal_places=2 m:indicator_sequence=74039 m:period_month=1 m:monthly_target=0.75

series e:cy9b-i9w9 d:2008-01-01T00:00:00.000Z t:category="Safety Indicators" t:indicator_name="Collisions with Injury Rate" t:description="All customer collisions with injuries on B&T property.  The rate is collisions with injuries per million vehicles." t:indicator_unit=- t:frequency=M t:period=2008-02 t:agency_name="Bridges and Tunnels" t:desired_change=D m:ytd_actual=0.75 m:monthly_actual=0.98 m:ytd_target=0.89 m:parent_sequence=0 m:decimal_places=2 m:indicator_sequence=74039 m:period_month=2 m:monthly_target=1.02

series e:cy9b-i9w9 d:2008-01-01T00:00:00.000Z t:category="Safety Indicators" t:indicator_name="Collisions with Injury Rate" t:description="All customer collisions with injuries on B&T property.  The rate is collisions with injuries per million vehicles." t:indicator_unit=- t:frequency=M t:period=2008-03 t:agency_name="Bridges and Tunnels" t:desired_change=D m:ytd_actual=0.77 m:monthly_actual=0.8 m:ytd_target=0.9 m:parent_sequence=0 m:decimal_places=2 m:indicator_sequence=74039 m:period_month=3 m:monthly_target=0.92
```

## Meta Commands

```ls
metric m:indicator_sequence p:integer l:"Indicator Sequence" d:"A unique identifying sequence number associated with a KPI." t:dataTypeName=number

metric m:parent_sequence p:integer l:"Parent Sequence" d:"This indicates that the KPI is a Sun-Indicator and contains the indicator sequence value of the Parent KPI." t:dataTypeName=number

metric m:decimal_places p:integer l:"Decimal Places" d:"The number of decimal places that should be printed or shown for the indicator value (to the right of the decimal point). E.g. (2)=two decimial places" t:dataTypeName=number

metric m:period_month p:integer l:"Period Month" d:"This is the month of the reported KPI value" t:dataTypeName=number

metric m:ytd_target p:double l:"YTD Target" d:"This is the expected YTD target value for each month." t:dataTypeName=number

metric m:ytd_actual p:double l:"YTD Actual" d:"This is the expected YTD actual value for each month." t:dataTypeName=number

metric m:monthly_target p:double l:"Monthly Target" d:"This is the expected MONTHLY target value for each month." t:dataTypeName=number

metric m:monthly_actual p:double l:"Monthly Actual" d:"This is the expected MONTHLY actual value for each month." t:dataTypeName=number

entity e:cy9b-i9w9 l:"Metropolitan Transportation Authority (MTA) Performance Indicators per Agency: Beginning 2008" t:attribution="MTA Headquarters, New York City Transit, Long Island Rail Road, Metro-North Railroad, MTA Bus and MTA Bridges and Tunnels" t:url=https://data.ny.gov/api/views/cy9b-i9w9

property e:cy9b-i9w9 t:meta.view v:id=cy9b-i9w9 v:category=Transportation v:attributionLink=http://www.mta.info/developers/download.html v:averageRating=0 v:name="Metropolitan Transportation Authority (MTA) Performance Indicators per Agency: Beginning 2008" v:attribution="MTA Headquarters, New York City Transit, Long Island Rail Road, Metro-North Railroad, MTA Bus and MTA Bridges and Tunnels"

property e:cy9b-i9w9 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cy9b-i9w9 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cy9b-i9w9 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| indicator_sequence | parent_sequence | agency_name         | indicator_name              | description                                                                                                       | category          | frequency | desired_change | indicator_unit | decimal_places | period_year | period_month | ytd_target | ytd_actual | monthly_target | monthly_actual | period  | 
| ================== | =============== | =================== | =========================== | ================================================================================================================= | ================= | ========= | ============== | ============== | ============== | =========== | ============ | ========== | ========== | ============== | ============== | ======= | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 1            | 0.75       | 0.54       | 0.75           | 0.54           | 2008-01 | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 2            | 0.89       | 0.75       | 1.02           | 0.98           | 2008-02 | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 3            | 0.90       | 0.77       | 0.92           | 0.80           | 2008-03 | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 4            | 0.97       | 0.79       | 1.20           | 0.84           | 2008-04 | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 5            | 0.99       | 0.94       | 1.08           | 1.49           | 2008-05 | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 6            | 1.03       | 0.94       | 1.18           | 0.97           | 2008-06 | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 7            | 1.07       | 0.98       | 1.35           | 1.19           | 2008-07 | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 8            | 1.09       | 0.97       | 1.20           | 0.91           | 2008-08 | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 9            | 1.09       | 0.97       | 1.15           | 1.02           | 2008-09 | 
| 74039              | 0               | Bridges and Tunnels | Collisions with Injury Rate | All customer collisions with injuries on B&T property. The rate is collisions with injuries per million vehicles. | Safety Indicators | M         | D              | -              | 2              | 2008        | 10           | 1.09       | 0.98       | 1.02           | 0.99           | 2008-10 | 
```