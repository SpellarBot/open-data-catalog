# BHO SUD Engagement in Care: 2010-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bho-sud-engagement-in-care-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/y8rt-xmjq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/y8rt-xmjq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/y8rt-xmjq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | y8rt-xmjq |
| Name | BHO SUD Engagement in Care: 2010-2014 |
| Attribution | The New York State Office Of Mental Health |
| Category | Human Services |
| Tags | acute care discharges, follow-up treatments, detoxification & rehabilitation |
| Created | 2014-05-16T20:59:12Z |
| Publication Date | 2015-08-05T22:06:44Z |

## Description

The Behavioral Health Organization (BHO) initiative oversees the transition to managed care for Medicaid recipients who receive mental health (MH) and substance use disorder (SUD) services in New York State. The metrics emphasize improving rates of timely follow-up treatment post discharge, timely filling of appropriate medication prescriptions post discharge, and reducing rates of readmission.The BHO SUD Engagement in Care dataset is designed to assess the frequency with which individuals discharged from inpatient detoxification or chemical dependence inpatient rehabilitation engage in lower level substance use disorder treatment services within 14 and 30 days of discharge. Engagement is defined as receiving two or more such services within 14 days of discharge and three or more lower level services within 30 days of discharge.
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
series e:y8rt-xmjq d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge" t:metric_id=28 t:indicator_domain_group="SUD Engagement in Care" m:year_to_date_numerator=989 m:rate=31.3 m:year_to_date_rate=34.2 m:year_to_date_denominator=2896 m:numerator=190 m:denominator=608

series e:y8rt-xmjq d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge" t:metric_id=28 t:indicator_domain_group="SUD Engagement in Care" m:year_to_date_numerator=533 m:rate=34.899999999999 m:year_to_date_rate=33.6 m:year_to_date_denominator=1584 m:numerator=251 m:denominator=719

series e:y8rt-xmjq d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge" t:metric_id=28 t:indicator_domain_group="SUD Engagement in Care" m:year_to_date_numerator=790 m:rate=37.7 m:year_to_date_rate=34.899999999999 m:year_to_date_denominator=2265 m:numerator=257 m:denominator=681
```

## Meta Commands

```ls
metric m:numerator p:float l:Numerator d:"Value of the ""top"" of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Quarter that is being examined. For more detail, see the ?Detailed Metric Descriptions? table in the data dictionary attached to this dataset." t:dataTypeName=number

metric m:denominator p:float l:Denominator d:"Value of the ""bottom"" of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Quarter that is being examined. For more detail, see the ?Detailed Metric Descriptions? table in the data dictionary attached to this dataset." t:dataTypeName=number

metric m:rate p:float l:Rate d:"For the Age Group, OMH Region, Performance Metric and Quarter being examined, this is the rate of the metric as calculated by dividing the Numerator by the Denominator." t:dataTypeName=number

metric m:year_to_date_numerator p:float l:"Year to Date Numerator" d:"Value of the ""top"" of the ""Rate"" calculation for the year to date as of the Quarter that is being examined." t:dataTypeName=number

metric m:year_to_date_denominator p:float l:"Year to Date Denominator" d:"Value of the bottom of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Year to Date being examined." t:dataTypeName=number

metric m:year_to_date_rate p:float l:"Year to Date Rate" d:"For the Performance Metric and the Quarter being examined, this is the rate of the metric as calculated by dividing the Year to Date Numerator by the Year to Date Denominator." t:dataTypeName=number

entity e:y8rt-xmjq l:"BHO SUD Engagement in Care: 2010-2014" t:attribution="The New York State Office Of Mental Health" t:url=https://data.ny.gov/api/views/y8rt-xmjq

property e:y8rt-xmjq t:meta.view v:id=y8rt-xmjq v:category="Human Services" v:attributionLink=http://omh.ny.gov/omhweb/statistics/index.htm v:averageRating=0 v:name="BHO SUD Engagement in Care: 2010-2014" v:attribution="The New York State Office Of Mental Health"

property e:y8rt-xmjq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:y8rt-xmjq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:y8rt-xmjq t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| row_created_date_time | metric_id | description_of_metric                                                                                                             | indicator_domain_group | omh_region    | age_group | numerator       | denominator     | rate            | year | quarter | year_to_date_numerator | year_to_date_denominator | year_to_date_rate | 
| ===================== | ========= | ================================================================================================================================= | ====================== | ============= | ========= | =============== | =============== | =============== | ==== | ======= | ====================== | ======================== | ================= | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 190.00000000000 | 608.00000000000 | 31.300000000000 | 2012 | Q4      | 989.00000000000        | 2896.0000000000          | 34.200000000000   | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 251.00000000000 | 719.00000000000 | 34.899999999999 | 2012 | Q2      | 533.00000000000        | 1584.0000000000          | 33.600000000000   | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 257.00000000000 | 681.00000000000 | 37.700000000000 | 2012 | Q3      | 790.00000000000        | 2265.0000000000          | 34.899999999999   | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 274.00000000000 | 852.00000000000 | 32.200000000000 | 2012 | Q1      | 274.00000000000        | 852.00000000000          | 32.200000000000   | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 284.00000000000 | 875.00000000000 | 32.500000000000 | 2011 | Q4      | 1294.0000000000        | 3885.0000000000          | 33.300000000000   | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 314.00000000000 | 973.00000000000 | 32.300000000000 | 2011 | Q3      | 1010.0000000000        | 3010.0000000000          | 33.600000000000   | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 324.00000000000 | 954.00000000000 | 34.000000000000 | 2010 | Q4      | 1348.0000000000        | 4206.0000000000          | 32.000000000000   | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 347.00000000000 | 1011.0000000000 | 34.300000000000 | 2011 | Q2      | 696.00000000000        | 2037.0000000000          | 34.200000000000   | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 349.00000000000 | 1026.0000000000 | 34.000000000000 | 2011 | Q1      | 349.00000000000        | 1026.0000000000          | 34.000000000000   | 
| 2015-07-17T08:58:25   | 28        | Percentage of SUD Detox or Rehabilitation Discharges Followed by Two or More Lower Level SUD Services within 14 Days of Discharge | SUD Engagement in Care | 01-Western NY | Adult     | 412.00000000000 | 1243.0000000000 | 33.100000000000 | 2013 | Q3Q4    | 863.00000000000        | 2464.0000000000          | 35.000000000000   | 
```