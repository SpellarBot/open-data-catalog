# EMS - Customer Satisfaction By Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-customer-satisfaction-by-month) |
| Metadata | [Link](https://data.austintexas.gov/api/views/fszi-c96k) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/fszi-c96k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/fszi-c96k/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | fszi-c96k |
| Name | EMS - Customer Satisfaction By Month |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | ems, atcems, customer satisfaction, survey results |
| Created | 2017-02-02T22:34:17Z |
| Publication Date | 2017-02-07T15:54:40Z |

## Description

ATCEMS conducts phone surveys of all patients or their family members for whom the department has a valid phone number.  The survey is performed within 72 hours of department contact with the patient.  This table contains data describing patient satisfaction with ATCEMS services in response to a question posed in the survey.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                                   | Data Type     | Render Type   |
| ======== | ============== | ========================================== | ====================================================== | ============= | ============= |
| Yes      | numeric metric | month_key                                  | Month Key                                              | number        | number        |
| Yes      | time           | month_start_date                           | Month-Year                                             | calendar_date | calendar_date |
| Yes      | numeric metric | count_respondents                          | Count - Respondents                                    | number        | number        |
| Yes      | numeric metric | count_satisfied_or_very_satisfied          | Count ? Satisfied or Very Satisfied Responses          | number        | number        |
| Yes      | numeric metric | percent_satisfied_or_very_satisfied        | Percent ? Satisfied or Very Satisfied Responses        | percent       | percent       |
| Yes      | numeric metric | percent_satisfied_or_very_satisfied_target | Target ? Percent Satisfied or Very Satisfied Responses | percent       | percent       |
```

## Time Field

```ls
Value = month_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fszi-c96k d:2013-10-01T00:00:00.000Z m:count_respondents=119 m:count_satisfied_or_very_satisfied=115 m:percent_satisfied_or_very_satisfied_target=95 m:percent_satisfied_or_very_satisfied=96.63 m:month_key=201310

series e:fszi-c96k d:2013-11-01T00:00:00.000Z m:count_respondents=99 m:count_satisfied_or_very_satisfied=91 m:percent_satisfied_or_very_satisfied_target=95 m:percent_satisfied_or_very_satisfied=91.91 m:month_key=201311

series e:fszi-c96k d:2013-12-01T00:00:00.000Z m:count_respondents=54 m:count_satisfied_or_very_satisfied=53 m:percent_satisfied_or_very_satisfied_target=95 m:percent_satisfied_or_very_satisfied=98.14 m:month_key=201312
```

## Meta Commands

```ls
metric m:month_key p:integer l:"Month Key" d:"Year and month for record in <yyyymm> format (e.g. 201407). This format is useful for sorting records." t:dataTypeName=number

metric m:count_respondents p:integer l:"Count - Respondents" d:"Count of patients or family members who responded to a question asking them to rate their satisfaction with the service provided by ATCEMS personnel." t:dataTypeName=number

metric m:count_satisfied_or_very_satisfied p:integer l:"Count ? Satisfied or Very Satisfied Responses" d:"Count of patients or family members who described themselves as ?Satisfied? or ?Very Satisfied.?" t:dataTypeName=number

metric m:percent_satisfied_or_very_satisfied p:float l:"Percent ? Satisfied or Very Satisfied Responses" d:"Percent of patients or family members who described themselves as ?Satisfied? or ?Very Satisfied.?" t:dataTypeName=percent

metric m:percent_satisfied_or_very_satisfied_target p:integer l:"Target ? Percent Satisfied or Very Satisfied Responses" d:"Performance target for percent of patients or family members who described themselves as ?Satisfied? or ?Very Satisfied.?" t:dataTypeName=percent

entity e:fszi-c96k l:"EMS - Customer Satisfaction By Month" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/fszi-c96k

property e:fszi-c96k t:meta.view v:id=fszi-c96k v:category="Public Safety" v:averageRating=0 v:name="EMS - Customer Satisfaction By Month" v:attribution="Austin-Travis County EMS"

property e:fszi-c96k t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:fszi-c96k t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| month_key | month_start_date    | count_respondents | count_satisfied_or_very_satisfied | percent_satisfied_or_very_satisfied | percent_satisfied_or_very_satisfied_target | 
| ========= | =================== | ================= | ================================= | =================================== | ========================================== | 
| 201310    | 2013-10-01T00:00:00 | 119               | 115                               | 96.63                               | 95                                         | 
| 201311    | 2013-11-01T00:00:00 | 99                | 91                                | 91.91                               | 95                                         | 
| 201312    | 2013-12-01T00:00:00 | 54                | 53                                | 98.14                               | 95                                         | 
| 201401    | 2014-01-01T00:00:00 | 133               | 132                               | 99.24                               | 95                                         | 
| 201402    | 2014-02-01T00:00:00 | 133               | 125                               | 93.98                               | 95                                         | 
| 201403    | 2014-03-01T00:00:00 | 143               | 140                               | 97.90                               | 95                                         | 
| 201404    | 2014-04-01T00:00:00 | 140               | 139                               | 99.28                               | 95                                         | 
| 201405    | 2014-05-01T00:00:00 | 186               | 183                               | 98.38                               | 95                                         | 
| 201406    | 2014-06-01T00:00:00 | 115               | 113                               | 98.26                               | 95                                         | 
| 201407    | 2014-07-01T00:00:00 | 183               | 178                               | 97.26                               | 95                                         | 
```