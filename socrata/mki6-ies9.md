# BHO SUD Readmission: 2010-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bho-sud-readmission-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/mki6-ies9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mki6-ies9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mki6-ies9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mki6-ies9 |
| Name | BHO SUD Readmission: 2010-2014 |
| Attribution | The New York State Office Of Mental Health |
| Category | Human Services |
| Tags | acute care discharges, follow-up treatments, detoxification & rehabilitation |
| Created | 2014-05-16T21:12:59Z |
| Publication Date | 2015-08-05T22:08:31Z |

## Description

The Behavioral Health Organization (BHO) initiative oversees the transition to managed care for Medicaid recipients who receive mental health (MH) and substance use disorder (SUD) services in New York State. The metrics emphasize improving rates of timely follow-up treatment post discharge, timely filling of appropriate medication prescriptions post discharge, and reducing rates of readmission.The BHO SUD Readmission dataset describes the rate of readmission for substance use disorder inpatient detoxification or chemical dependence inpatient rehabilitation within either 30 or 45 days of the last inpatient substance use disorder discharge for all discharges identified from paid fee-for-service Medicaid claims.
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
series e:mki6-ies9 d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region)" t:metric_id=30 t:indicator_domain_group="SUD Readmission" m:year_to_date_numerator=74 m:rate=3.6 m:year_to_date_rate=4.8 m:year_to_date_denominator=1536 m:numerator=25 m:denominator=697

series e:mki6-ies9 d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region)" t:metric_id=30 t:indicator_domain_group="SUD Readmission" m:year_to_date_numerator=106 m:rate=4.7 m:year_to_date_rate=4.8 m:year_to_date_denominator=2217 m:numerator=32 m:denominator=681

series e:mki6-ies9 d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region)" t:metric_id=30 t:indicator_domain_group="SUD Readmission" m:year_to_date_numerator=146 m:rate=6.7 m:year_to_date_rate=5.2 m:year_to_date_denominator=2814 m:numerator=40 m:denominator=597
```

## Meta Commands

```ls
metric m:numerator p:float l:Numerator d:"Value of the ""top"" of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Quarter that is being examined. More detail on the Numerator for each metric is provided in the ?Detailed Metric Descriptions? table in the data dictionary attached to this dataset." t:dataTypeName=number

metric m:denominator p:float l:Denominator d:"The denominator includes discharges from inpatient detoxification or chemical dependence inpatient rehabilitation identified from paid fee-for-service Medicaid claims. An inpatient detoxification service followed by an inpatient rehabilitation service within 14 days is counted as one inpatient stay in the denominator. Individuals who meet any of the following criteria are excluded: Ineligible for Medicaid in any of the 90 days post discharge; Medicare-eligible." t:dataTypeName=number

metric m:rate p:double l:Rate d:"For the Age Group, OMH Region, Performance Metric and Quarter being examined, this is the rate of the metric as calculated by dividing the Numerator by the Denominator. For example, for Adults in OMH Region ""01 - Western NY"" and the Performance Metric "" 30 Day SUD Readmission (Any Region)"" during Q4 of 2010, 146 out of 2814 patients that were discharged from inpatient detoxification or chemical dependence inpatient rehabilitation (identified from paid fee-for-service Medicaid claims)" t:dataTypeName=number

metric m:year_to_date_numerator p:float l:"Year to Date Numerator" d:"Value of the ""top"" of the ""Rate"" calculation for the year to date as of the Quarter that is being examined. For example, for the metric ""30 Day SUD Readmission (Any Region) "" in Q4 of 2012, the Numerator is the number of discharges in the denominator having a readmission for substance use disorder inpatient detoxification or chemical dependence inpatient rehabilitation within 30 days of the last inpatient substance use disorder discharge during Quarters 1, 2, 3 and 4 of 2012." t:dataTypeName=number

metric m:year_to_date_denominator p:float l:"Year to Date Denominator" d:"Value of the bottom of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Year to Date being examined. For example, for the metric ""30 Day SUD Readmission (Any Region)"" in Q4 of 2012, this is the number of all patients discharged from inpatient detoxification or chemical dependence inpatient rehabilitation identified from paid fee-for-service Medicaid claims Quarters 1,2, 3 and 4 of that year." t:dataTypeName=number

metric m:year_to_date_rate p:double l:"Year to Date Rate" d:"For the Performance Metric and the Quarter being examined, this is the rate of the metric as calculated by dividing the Year to Date Numerator by the Year to Date Denominator." t:dataTypeName=number

entity e:mki6-ies9 l:"BHO SUD Readmission: 2010-2014" t:attribution="The New York State Office Of Mental Health" t:url=https://data.ny.gov/api/views/mki6-ies9

property e:mki6-ies9 t:meta.view v:id=mki6-ies9 v:category="Human Services" v:attributionLink=http://omh.ny.gov/omhweb/statistics/index.htm v:averageRating=0 v:name="BHO SUD Readmission: 2010-2014" v:attribution="The New York State Office Of Mental Health"

property e:mki6-ies9 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mki6-ies9 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:mki6-ies9 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| row_created_date_time | metric_id | description_of_metric                                                                                    | indicator_domain_group | omh_region    | age_group | numerator       | denominator     | rate            | year | quarter | year_to_date_numerator | year_to_date_denominator | year_to_date_rate | 
| ===================== | ========= | ======================================================================================================== | ====================== | ============= | ========= | =============== | =============== | =============== | ==== | ======= | ====================== | ======================== | ================= | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 25.000000000000 | 697.00000000000 | 3.6000000000000 | 2012 | Q2      | 74.000000000000        | 1536.0000000000          | 4.8000000000000   | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 32.000000000000 | 681.00000000000 | 4.7000000000000 | 2012 | Q3      | 106.00000000000        | 2217.0000000000          | 4.8000000000000   | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 40.000000000000 | 597.00000000000 | 6.7000000000000 | 2012 | Q4      | 146.00000000000        | 2814.0000000000          | 5.2000000000000   | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 51.000000000000 | 871.00000000000 | 5.8999999999999 | 2012 | Q1      | 51.000000000000        | 871.00000000000          | 5.8999999999999   | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 53.000000000000 | 1204.0000000000 | 4.3999999999999 | 2014 | Q1Q2    | 53.000000000000        | 1204.0000000000          | 4.3999999999999   | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 57.000000000000 | 896.00000000000 | 6.4000000000000 | 2011 | Q4      | 296.00000000000        | 3969.0000000000          | 7.5000000000000   | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 59.000000000000 | 1288.0000000000 | 4.6000000000000 | 2014 | Q3Q4    | 114.00000000000        | 2506.0000000000          | 4.5000000000000   | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 61.000000000000 | 1169.0000000000 | 5.2000000000000 | 2013 | Q1Q2    | 61.000000000000        | 1169.0000000000          | 5.2000000000000   | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 62.000000000000 | 1233.0000000000 | 5.0000000000000 | 2013 | Q3Q4    | 124.00000000000        | 2451.0000000000          | 5.1000000000000   | 
| 2015-07-17T08:58:25   | 30        | Rate of Readmission to SUD Detox or Rehabilitation within 30 Days (Readmission in Any Geographic Region) | SUD Readmission        | 01-Western NY | Adult     | 69.000000000000 | 916.00000000000 | 7.5000000000000 | 2010 | Q4      | 353.00000000000        | 3987.0000000000          | 8.9000000000000   | 
```