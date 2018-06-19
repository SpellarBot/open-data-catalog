# BHO SUD Continuity of Care: 2010-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bho-sud-continuity-of-care-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/58ew-qhce) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/58ew-qhce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/58ew-qhce/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 58ew-qhce |
| Name | BHO SUD Continuity of Care: 2010-2014 |
| Attribution | The New York State Office Of Mental Health |
| Category | Human Services |
| Tags | acute care discharges, follow-up treatments, detoxification & rehabilitation |
| Created | 2014-05-16T20:45:20Z |
| Publication Date | 2015-08-05T22:15:43Z |

## Description

The Behavioral Health Organization (BHO) initiative overseesthe transition to managed care for Medicaid recipients who receive mental health (MH) and substance use disorder (SUD) services in New York State. The metrics emphasize improving rates of timely follow-up treatment post discharge, timely filling of appropriate medication prescriptions post discharge, and reducing rates of readmission.The BHO SUD Continuity of Care dataset is designed to assess the frequency with which individuals receive a lower level, less intensive, substance use disorder or Mental Health Follow-Up service within 14 or 30 days following a discharge from inpatient detoxification, chemical dependence inpatient rehabilitation, inpatient detoxification or chemical dependence inpatient rehabilitation.
The year 2015 saw the conclusion of the first phase of the Behavioral Health Organization initiative
(BHO). A new Behavioral Health Managed Care Transition phase II is underway. The data contained in
the BHO metrics span 2010 to 2014, using the 2010 calendar year for a baseline. Earlier in the program
(2011?2012) the metrics were calculated quarterly and on a year?to?date basis, later in (2013?2014),
New York State Office of Mental Health opted for semi?annual and year?to?date aggregations.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | time           | row_created_date_time    | Row Created Date Time    | calendar_date | calendar_date |
| Yes      | series tag     | metric_id                | Metric ID                | text          | number        |
| Yes      | series tag     | description_of_metric    | Description of Metric    | text          | text          |
| Yes      | series tag     | indicator_domain_group   | Indicator Domain Group   | text          | text          |
| Yes      | series tag     | omh_region               | OMH Region               | text          | text          |
| Yes      | series tag     | age_group                | Age Group                | text          | text          |
| Yes      | numeric metric | numerator                | Numerator                | number        | number        |
| Yes      | numeric metric | denominator              | Denominator              | number        | number        |
| Yes      | numeric metric | rate                     | Rate                     | number        | number        |
| No       |                | year                     | Year                     | number        | number        |
| No       |                | quarter                  | Quarter                  | text          | text          |
| Yes      | numeric metric | year_to_date_numerator   | Year to Date Numerator   | number        | number        |
| Yes      | numeric metric | year_to_date_denominator | Year to Date Denominator | number        | number        |
| Yes      | numeric metric | year_to_date_rate        | Year to Date Rate        | number        | number        |
```

## Time Field

```ls
Value = row_created_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter,year
```

## Data Commands

```ls
series e:58ew-qhce d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days" t:metric_id=20 t:indicator_domain_group="SUD Continuity of Care" m:year_to_date_numerator=437 m:rate=56.299999999999 m:year_to_date_rate=56.699999999999 m:year_to_date_denominator=771 m:numerator=81 m:denominator=144

series e:58ew-qhce d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days" t:metric_id=20 t:indicator_domain_group="SUD Continuity of Care" m:year_to_date_numerator=350 m:rate=55.9 m:year_to_date_rate=56.599999999999 m:year_to_date_denominator=618 m:numerator=81 m:denominator=145

series e:58ew-qhce d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days" t:metric_id=20 t:indicator_domain_group="SUD Continuity of Care" m:year_to_date_numerator=269 m:rate=56.299999999999 m:year_to_date_rate=56.899999999999 m:year_to_date_denominator=473 m:numerator=116 m:denominator=206
```

## Meta Commands

```ls
metric m:numerator p:float l:Numerator d:"Value of the ""top"" of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Quarter that is being examined. The description of the Numerator is specific to the metric being evaluated. For more detail on the numerator for each metric, see the ?Detailed Metric Descriptions? table in the data dictionary attached to this dataset." t:dataTypeName=number

metric m:denominator p:float l:Denominator d:"The denominator includes discharges from chemical dependence inpatient rehabilitation identified from paid fee-for-service Medicaid claims. Individuals who meet any of the following criteria are excluded: Ineligible for Medicaid in any of the 30 days post discharge; Medicare-eligible." t:dataTypeName=number

metric m:rate p:double l:Rate d:"For the Age Group, OMH Region, Performance Metric and Quarter being examined, this is the rate of the metric as calculated by dividing the Numerator by the Denominator." t:dataTypeName=number

metric m:year_to_date_numerator p:float l:"Year to Date Numerator" d:"Value of the ""top"" of the ""Rate"" calculation for the year to date as of the Quarter that is being examined. For example, for the metric ""14 Day SUD Detox (SUD Follow-Up)"" in Q4 of 2012, the Numerator is the number of discharges in the denominator where the individual had a substance use disorder non-crisis treatment service within 14 days post discharge from inpatient detoxification during Quarters 1, 2, 3 and 4 of 2012." t:dataTypeName=number

metric m:year_to_date_denominator p:float l:"Year to Date Denominator" d:"Value of the bottom of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Year to Date being examined. For example, for the metric ""14 Day SUD Detox (SUD Follow-Up)"" in Q4 of 2012, this is the number of all patients discharged from chemical dependence inpatient rehabilitation identified from paid fee-for-service Medicaid claims during Quarters 1,2, 3 and 4 of that year." t:dataTypeName=number

metric m:year_to_date_rate p:float l:"Year to Date Rate" d:"For the Performance Metric and the Quarter being examined, this is the rate of the metric as calculated by dividing the Year to Date Numerator by the Year to Date Denominator." t:dataTypeName=number

entity e:58ew-qhce l:"BHO SUD Continuity of Care: 2010-2014" t:attribution="The New York State Office Of Mental Health" t:url=https://data.ny.gov/api/views/58ew-qhce

property e:58ew-qhce t:meta.view v:id=58ew-qhce v:category="Human Services" v:attributionLink=http://omh.ny.gov/omhweb/statistics/index.htm v:averageRating=0 v:name="BHO SUD Continuity of Care: 2010-2014" v:attribution="The New York State Office Of Mental Health"

property e:58ew-qhce t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:58ew-qhce t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:58ew-qhce t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| row_created_date_time | metric_id | description_of_metric                                                                   | indicator_domain_group | omh_region    | age_group | numerator       | denominator     | rate            | year | quarter | year_to_date_numerator | year_to_date_denominator | year_to_date_rate | 
| ===================== | ========= | ======================================================================================= | ====================== | ============= | ========= | =============== | =============== | =============== | ==== | ======= | ====================== | ======================== | ================= | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 81.000000000000 | 144.00000000000 | 56.299999999999 | 2012 | Q4      | 437.00000000000        | 771.00000000000          | 56.699999999999   | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 81.000000000000 | 145.00000000000 | 55.900000000000 | 2012 | Q3      | 350.00000000000        | 618.00000000000          | 56.599999999999   | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 116.00000000000 | 206.00000000000 | 56.299999999999 | 2012 | Q2      | 269.00000000000        | 473.00000000000          | 56.899999999999   | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 145.00000000000 | 281.00000000000 | 51.600000000000 | 2014 | Q1Q2    | 145.00000000000        | 281.00000000000          | 51.600000000000   | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 147.00000000000 | 291.00000000000 | 50.500000000000 | 2011 | Q4      | 690.00000000000        | 1257.0000000000          | 54.900000000000   | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 149.00000000000 | 276.00000000000 | 54.000000000000 | 2013 | Q1Q2    | 149.00000000000        | 276.00000000000          | 54.000000000000   | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 151.00000000000 | 260.00000000000 | 58.099999999999 | 2012 | Q1      | 151.00000000000        | 260.00000000000          | 58.099999999999   | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 154.00000000000 | 305.00000000000 | 50.500000000000 | 2013 | Q3Q4    | 307.00000000000        | 594.00000000000          | 51.700000000000   | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 155.00000000000 | 304.00000000000 | 51.000000000000 | 2011 | Q3      | 548.00000000000        | 976.00000000000          | 56.100000000000   | 
| 2015-07-17T08:58:25   | 20        | Percentage of SUD Detox Discharges Followed by a Lower Level SUD Service within 14 Days | SUD Continuity of Care | 01-Western NY | Adult     | 174.00000000000 | 323.00000000000 | 53.900000000000 | 2014 | Q3Q4    | 319.00000000000        | 607.00000000000          | 52.600000000000   | 
```