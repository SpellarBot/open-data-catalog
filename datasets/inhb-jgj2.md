# BHO MH Readmission: 2010-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bho-mh-readmission-beginning-2010) |
| Metadata | [Link](https://data.ny.gov/api/views/inhb-jgj2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/inhb-jgj2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/inhb-jgj2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | inhb-jgj2 |
| Name | BHO MH Readmission: 2010-2014 |
| Attribution | The New York State Office Of Mental Health |
| Category | Human Services |
| Tags | acute care discharges, follow-up treatments, detoxification & rehabilitation |
| Created | 2014-05-16T20:10:05Z |
| Publication Date | 2015-08-05T22:11:54Z |

## Description

The Behavioral Health Organization (BHO) initiative oversees the transition to managed care for Medicaid recipients who receive mental health (MH) and substance use disorder (SUD) services in New York State. The metrics emphasize improving rates of timely follow-up treatment post discharge, timely filling of appropriate medication prescriptions post discharge, and reducing rates of readmission.The BHO MH Readmissions dataset is designed to assess the frequency with which individuals are admitted for another mental health hospitalization in any region within 30 or 90 days of discharge from a prior mental health inpatient stay, and the frequency with which individuals are admitted for another mental health hospitalization in the same region within 30 days of discharge from a prior mental health inpatient stay.
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
series e:inhb-jgj2 d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region)" t:metric_id=5 t:indicator_domain_group="MH Readmission" m:year_to_date_numerator=655 m:rate=16.199999999999 m:year_to_date_rate=17 m:year_to_date_denominator=3845 m:numerator=135 m:denominator=831

series e:inhb-jgj2 d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region)" t:metric_id=5 t:indicator_domain_group="MH Readmission" m:year_to_date_numerator=334 m:rate=15.199999999999 m:year_to_date_rate=16.8 m:year_to_date_denominator=1986 m:numerator=148 m:denominator=974

series e:inhb-jgj2 d:2015-07-17T08:58:25.000Z t:omh_region="01-Western NY" t:age_group=Adult t:description_of_metric="Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region)" t:metric_id=5 t:indicator_domain_group="MH Readmission" m:year_to_date_numerator=776 m:rate=16.6 m:year_to_date_rate=17.299999999999 m:year_to_date_denominator=4497 m:numerator=165 m:denominator=992
```

## Meta Commands

```ls
metric m:numerator p:float l:Numerator d:"Value of the ""top"" of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Quarter that is being examined. For more detailed descriptions of the Numerators for the MH Readmission dataset, see the ?Detailed Metric Descriptions? table in the data dictionary attached to this dataset." t:dataTypeName=number

metric m:denominator p:float l:Denominator d:"Value of ""bottom"" of the calculation for the Age Group, OMH Region, Performance Metric and Quarter that is being examined. For the MH Readmissions dataset, the Denominator includes discharges from inpatient psychiatric units at general hospitals (Article 28), private psychiatric hospitals (Article 31), and state operated psychiatric hospitals (SPCs) that are identified from paid fee-for-service Medicaid claims. Individuals who meet any of the following criteria are excluded: Ineligible for Medicaid in any of the 90 days post discharge; Medicare-eligible." t:dataTypeName=number

metric m:rate p:float l:Rate d:"For the Age Group, OMH Region, Performance Metric and Quarter being examined, this is the rate of the metric as calculated by dividing the Numerator by the Denominator." t:dataTypeName=number

metric m:year_to_date_numerator p:float l:"Year to Date Numerator" d:"Value of the ""top"" of the ""Rate"" calculation for the year to date as of the Quarter that is being examined. For example, for a given metric in Q4 of 2012, the Numerator is the number of Readmissions within the specified time frame and region of the metric (30 or 90 days after discharge, ?same? or ?any? region) during Quarters 1, 2, 3 and 4 of 2012." t:dataTypeName=number

metric m:year_to_date_denominator p:float l:"Year to Date Denominator" d:"Value of the bottom of the ""Rate"" calculation for the Age Group, OMH Region, Performance Metric and Year to Date being examined. For example, for a given metric in Q4 of 2012, the Denominator is the number of Discharges from inpatient psychiatric units at general hospitals (Article 28), private psychiatric hospitals (Article 31), and state operated psychiatric hospitals (SPCs) within the specified time frame and region of the metric (30 or 90 days after discharge, ?same? or ?any? region) during Quarters 1, 2, 3 and 4 of 2012." t:dataTypeName=number

metric m:year_to_date_rate p:double l:"Year to Date Rate" d:"For the Performance Metric and the Quarter being examined, this is the rate of the metric as calculated by dividing the Year to Date Numerator by the Year to Date Denominator." t:dataTypeName=number

entity e:inhb-jgj2 l:"BHO MH Readmission: 2010-2014" t:attribution="The New York State Office Of Mental Health" t:url=https://data.ny.gov/api/views/inhb-jgj2

property e:inhb-jgj2 t:meta.view v:id=inhb-jgj2 v:category="Human Services" v:attributionLink=http://omh.ny.gov/omhweb/statistics/index.htm v:averageRating=0 v:name="BHO MH Readmission: 2010-2014" v:attribution="The New York State Office Of Mental Health"

property e:inhb-jgj2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:inhb-jgj2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:inhb-jgj2 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| row_created_date_time | metric_id | description_of_metric                                                                               | indicator_domain_group | omh_region    | age_group | numerator       | denominator     | rate            | year | quarter | year_to_date_numerator | year_to_date_denominator | year_to_date_rate | 
| ===================== | ========= | =================================================================================================== | ====================== | ============= | ========= | =============== | =============== | =============== | ==== | ======= | ====================== | ======================== | ================= | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 135.00000000000 | 831.00000000000 | 16.199999999999 | 2012 | Q4      | 655.00000000000        | 3845.0000000000          | 17.000000000000   | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 148.00000000000 | 974.00000000000 | 15.199999999999 | 2012 | Q2      | 334.00000000000        | 1986.0000000000          | 16.800000000000   | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 165.00000000000 | 992.00000000000 | 16.600000000000 | 2011 | Q4      | 776.00000000000        | 4497.0000000000          | 17.299999999999   | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 184.00000000000 | 1037.0000000000 | 17.699999999999 | 2012 | Q1      | 184.00000000000        | 1037.0000000000          | 17.699999999999   | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 186.00000000000 | 1028.0000000000 | 18.099999999999 | 2012 | Q3      | 520.00000000000        | 3014.0000000000          | 17.299999999999   | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 189.00000000000 | 1045.0000000000 | 18.099999999999 | 2010 | Q4      | 724.00000000000        | 4333.0000000000          | 16.699999999999   | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 196.00000000000 | 1180.0000000000 | 16.600000000000 | 2011 | Q3      | 611.00000000000        | 3505.0000000000          | 17.399999999999   | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 206.00000000000 | 1156.0000000000 | 17.800000000000 | 2011 | Q2      | 415.00000000000        | 2325.0000000000          | 17.800000000000   | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 209.00000000000 | 1169.0000000000 | 17.899999999999 | 2011 | Q1      | 209.00000000000        | 1169.0000000000          | 17.899999999999   | 
| 2015-07-17T08:58:25   | 5         | Rate of Readmission to Inpatient MH Treatment within 30 Days (Readmission in Any Geographic Region) | MH Readmission         | 01-Western NY | Adult     | 230.00000000000 | 1556.0000000000 | 14.799999999999 | 2013 | Q3Q4    | 485.00000000000        | 3298.0000000000          | 14.699999999999   | 
```