# BHO Medication Fill Data: 2010-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bho-medication-fill-data-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/cc9j-4ujx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cc9j-4ujx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cc9j-4ujx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cc9j-4ujx |
| Name | BHO Medication Fill Data: 2010-2014 |
| Attribution | The New York State Office Of Mental Health |
| Category | Human Services |
| Tags | acute care discharges, follow-up treatments, detoxification & rehabilitation |
| Created | 2014-05-16T16:07:06Z |
| Publication Date | 2015-08-05T22:17:28Z |

## Description

The Behavioral Health Organization (BHO) initiative oversees the transition to managed care for Medicaid recipients who receive mental health (MH) and substance use disorder (SUD) services in New York State. The metrics emphasize improving rates of timely follow-up treatment post discharge, timely filling of appropriate medication prescriptions post discharge, and reducing rates of readmission.The BHO Medication Fill dataset is designed to assess the frequency with which individuals receiving Mental Health or SUD treatment fill an initial prescription for a mood stabilizer, anti-psychotic, psychotropic, or anti-addition medication within 30 days of discharge from a mental health inpatient hospitalization or SUD inpatient stay and refill those prescriptions within 100 days of discharge.
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
series e:cc9j-4ujx d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days" t:metric_id=10 t:indicator_domain_group="Medication Fill" m:year_to_date_numerator=2585 m:rate=73 m:year_to_date_rate=73.4 m:year_to_date_denominator=3520 m:numerator=563 m:denominator=771

series e:cc9j-4ujx d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days" t:metric_id=10 t:indicator_domain_group="Medication Fill" m:year_to_date_numerator=1974 m:rate=69.899999999999 m:year_to_date_rate=72.799999999999 m:year_to_date_denominator=2712 m:numerator=631 m:denominator=903

series e:cc9j-4ujx d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days" t:metric_id=10 t:indicator_domain_group="Medication Fill" m:year_to_date_numerator=1343 m:rate=73.4 m:year_to_date_rate=74.2 m:year_to_date_denominator=1809 m:numerator=655 m:denominator=892
```

## Meta Commands

```ls
metric m:numerator p:float l:Numerator d:"Value of the ""top"" of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Quarter that is being examined. For Detailed Descriptions of the Numerator for each metric, see the ?Detailed Metric Definitions? in the data dictionary attached to this dataset." t:dataTypeName=number

metric m:denominator p:float l:Denominator d:"Value of ""bottom"" of the calculation for the Age Group, OMH Region, Performance Metric and Quarter that is being examined. For Detailed Descriptions of the Denominator for each metric, see the ?Detailed Metric Definitions? table in the data dictionary attached to this dataset." t:dataTypeName=number

metric m:rate p:float l:Rate d:"For the Age Group, OMH Region, Performance Metric and Quarter being examined, this is the rate of the metric as calculated by dividing the Numerator by the Denominator." t:dataTypeName=number

metric m:year_to_date_numerator p:float l:"Year to Date Numerator" d:"Value of the top of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Year to Date being examined." t:dataTypeName=number

metric m:year_to_date_denominator p:float l:"Year to Date Denominator" d:"Value of the bottom of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Year to Date being examined." t:dataTypeName=number

metric m:year_to_date_rate p:float l:"Year to Date Rate" d:"For the Performance Metric and the Quarter being examined, this is the rate of the metric as calculated by dividing the Year to Date Numerator by the Year to Date Denominator." t:dataTypeName=number

entity e:cc9j-4ujx l:"BHO Medication Fill Data: 2010-2014" t:attribution="The New York State Office Of Mental Health" t:url=https://data.ny.gov/api/views/cc9j-4ujx

property e:cc9j-4ujx t:meta.view v:id=cc9j-4ujx v:category="Human Services" v:attributionLink=http://omh.ny.gov/omhweb/statistics/index.htm v:averageRating=0 v:name="BHO Medication Fill Data: 2010-2014" v:attribution="The New York State Office Of Mental Health"

property e:cc9j-4ujx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cc9j-4ujx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cc9j-4ujx t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| row_created_date_time | metric_id | description_of_metric                                                                                    | indicator_domain_group | omh_region    | age_group | numerator       | denominator     | rate            | year | quarter | year_to_date_numerator | year_to_date_denominator | year_to_date_rate | 
| ===================== | ========= | ======================================================================================================== | ====================== | ============= | ========= | =============== | =============== | =============== | ==== | ======= | ====================== | ======================== | ================= | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 563.00000000000 | 771.00000000000 | 73.000000000000 | 2012 | Q4      | 2585.0000000000        | 3520.0000000000          | 73.400000000000   | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 631.00000000000 | 903.00000000000 | 69.899999999999 | 2012 | Q3      | 1974.0000000000        | 2712.0000000000          | 72.799999999999   | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 655.00000000000 | 892.00000000000 | 73.400000000000 | 2012 | Q2      | 1343.0000000000        | 1809.0000000000          | 74.200000000000   | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 656.00000000000 | 877.00000000000 | 74.799999999999 | 2011 | Q4      | 2869.0000000000        | 3885.0000000000          | 73.799999999999   | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 677.00000000000 | 912.00000000000 | 74.200000000000 | 2012 | Q1      | 677.00000000000        | 912.00000000000          | 74.200000000000   | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 701.00000000000 | 946.00000000000 | 74.099999999999 | 2010 | Q4      | 2867.0000000000        | 3915.0000000000          | 73.200000000000   | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 730.00000000000 | 1003.0000000000 | 72.799999999999 | 2011 | Q2      | 1488.0000000000        | 2021.0000000000          | 73.599999999999   | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 746.00000000000 | 1007.0000000000 | 74.099999999999 | 2011 | Q3      | 2234.0000000000        | 3028.0000000000          | 73.799999999999   | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 758.00000000000 | 1018.0000000000 | 74.500000000000 | 2011 | Q1      | 758.00000000000        | 1018.0000000000          | 74.500000000000   | 
| 2015-07-17T08:58:25   | 10        | Percentage of MH Discharges where a Prescription for a Psychotropic Medication was Filled within 30 Days | Medication Fill        | 01-Western NY | Adult     | 996.00000000000 | 1379.0000000000 | 72.200000000000 | 2013 | Q3Q4    | 2063.0000000000        | 2893.0000000000          | 71.299999999999   | 
```