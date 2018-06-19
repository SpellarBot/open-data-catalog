# Oregon Consumer Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-consumer-complaints-7f511) |
| Metadata | [Link](https://data.oregon.gov/api/views/2ix7-8hwk) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/2ix7-8hwk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/2ix7-8hwk/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 2ix7-8hwk |
| Name | Oregon Consumer Complaints |
| Attribution | Oregon Department of Justice |
| Category | Public Safety |
| Tags | consumer, complaint, consumer protection, department of justice, doj, attorney general, ag |
| Created | 2011-03-02T17:00:30Z |
| Publication Date | 2017-04-03T14:05:12Z |

## Description

Consumer complaints registered with the Oregon Dept. of Justice.  The database of consumer complaints is derived from consumer contacts for the past 3 years and is for information only. This database may not offer a completely accurate or comprehensive account of every incident. Several factors, including a company?s size and volume of transactions, may affect the likelihood of a consumer complaint being filed. The number of complaints about a business may not be a reliable measure as to whether it is appropriately conducting business.

The information in this database is updated as soon as possible. However, recently submitted complaints may not be immediately available.

The statements in this database do not necessarily reflect the opinion of the DOJ.

For more information, see http://www.doj.state.or.us/finfraud/index.shtml

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag  | reference_no_         | Reference No.         | html          | html          |
| Yes      | series tag  | status                | Status                | text          | text          |
| Yes      | time        | date_open             | Date Open             | calendar_date | calendar_date |
| No       |             | date_closed           | Date Closed           | calendar_date | calendar_date |
| Yes      | series tag  | respondent            | Respondent            | text          | text          |
| No       |             | address_1             | Address 1             | text          | text          |
| No       |             | address_2             | Address 2             | text          | text          |
| Yes      | series tag  | city                  | City                  | text          | text          |
| Yes      | series tag  | state                 | State                 | text          | text          |
| Yes      | series tag  | zip                   | Zip                   | text          | text          |
| Yes      | series tag  | business_type         | Business Type         | text          | text          |
| Yes      | series tag  | complaint_description | Complaint Description | text          | text          |
| Yes      | series tag  | closing_description   | Closing Description   | text          | text          |
```

## Time Field

```ls
Value = date_open
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_closed,address_1,address_2
```

## Data Commands

```ls
series e:2ix7-8hwk d:2014-08-18T00:00:00.000Z t:respondent="CREDIT BUREAUS" t:complaint_description="Disclosed debtor's credit record in violation of law" t:status=Closed t:closing_description="Suggested consumer contact CFPB" t:reference_no_=FF5027-14 t:business_type="Credit/Lending: Credit Bureaus" m:row_number.2ix7-8hwk=1

series e:2ix7-8hwk d:2014-08-06T00:00:00.000Z t:respondent="COOS CURRY ELECTRIC COOPERATIVE" t:complaint_description="Inaccurately calculated a bill or debt, a portion of which the complainant does owe" t:zip=97465 t:status=Closed t:closing_description="DOJ has No Jurisdiction" t:state=OR t:reference_no_=FF4755-14 t:business_type="Electric Service Providor: Power Distribution" t:city="Port Orford" m:row_number.2ix7-8hwk=2

series e:2ix7-8hwk d:2014-11-03T00:00:00.000Z t:respondent="COOS CURRY ELECTRIC COOPERATIVE" t:complaint_description="Failure to pay rebate" t:zip=97465 t:status=Closed t:closing_description="DOJ has No Jurisdiction" t:state=OR t:reference_no_=FF6783-14 t:business_type="Electric Service Providor: Power Distribution" t:city="Port Orford" m:row_number.2ix7-8hwk=3
```

## Meta Commands

```ls
metric m:row_number.2ix7-8hwk p:long l:"Row Number"

entity e:2ix7-8hwk l:"Oregon Consumer Complaints" t:attribution="Oregon Department of Justice" t:url=https://data.oregon.gov/api/views/2ix7-8hwk

property e:2ix7-8hwk t:meta.view v:id=2ix7-8hwk v:category="Public Safety" v:attributionLink=http://www.doj.state.or.us/ v:averageRating=0 v:name="Oregon Consumer Complaints" v:attribution="Oregon Department of Justice"

property e:2ix7-8hwk t:meta.view.owner v:id=e4uc-pqeh v:profileImageUrlMedium=/api/users/e4uc-pqeh/profile_images/THUMB v:profileImageUrlLarge=/api/users/e4uc-pqeh/profile_images/LARGE v:screenName="Mike Greiner" v:profileImageUrlSmall=/api/users/e4uc-pqeh/profile_images/TINY v:displayName="Mike Greiner"

property e:2ix7-8hwk t:meta.view.tableauthor v:id=e4uc-pqeh v:profileImageUrlMedium=/api/users/e4uc-pqeh/profile_images/THUMB v:profileImageUrlLarge=/api/users/e4uc-pqeh/profile_images/LARGE v:screenName="Mike Greiner" v:profileImageUrlSmall=/api/users/e4uc-pqeh/profile_images/TINY v:roleName=editor v:displayName="Mike Greiner"
```

## Top Records

```ls
| reference_no_ | status | date_open           | date_closed         | respondent                        | address_1               | address_2                             | city        | state | zip       | business_type                                        | complaint_description                                                                   | closing_description              | 
| ============= | ====== | =================== | =================== | ================================= | ======================= | ===================================== | =========== | ===== | ========= | ==================================================== | ======================================================================================= | ================================ | 
| FF5027-14     | Closed | 2014-08-18T00:00:00 | 2014-08-18T00:00:00 | CREDIT BUREAUS                    |                         |                                       |             |       |           | Credit/Lending: Credit Bureaus                       | Disclosed debtor's credit record in violation of law                                    | Suggested consumer contact CFPB  | 
| FF4755-14     | Closed | 2014-08-06T00:00:00 | 2014-08-06T00:00:00 | COOS CURRY ELECTRIC COOPERATIVE   | P.O. Box 1268           | 43050 Hwy. 101                        | Port Orford | OR    | 97465     | Electric Service Providor: Power Distribution        | Inaccurately calculated a bill or debt, a portion of which the complainant does owe     | DOJ has No Jurisdiction          | 
| FF6783-14     | Closed | 2014-11-03T00:00:00 | 2014-11-03T00:00:00 | COOS CURRY ELECTRIC COOPERATIVE   | P.O. Box 1268           | 43050 Hwy. 101                        | Port Orford | OR    | 97465     | Electric Service Providor: Power Distribution        | Failure to pay rebate                                                                   | DOJ has No Jurisdiction          | 
| FF2788-15     | Closed | 2015-05-07T00:00:00 | 2015-11-03T00:00:00 | COOS BAY POLICE DEPARTMENT        | 500 Central Ave.        |                                       | Coos Bay    | OR    | 974201895 | Justice, Public Order & Safety Activities            | Service quality lower than what the complainant ordered or expected                     | DOJ has No Jurisdiction          | 
| FF2641-15     | Closed | 2015-04-29T00:00:00 | 2015-04-29T00:00:00 | CLUB TAN CENTERS OF OREGON, INC.* | PMB 428                 | 14845 S.W. MURRAY SCHOLLS DR, STE 110 | BEAVERTON   | OR    | 970079237 | Recreation: Health club facilities, physical fitness | General allegation of unlawful conduct                                                  | Referred Complainant Elsewhere   | 
| FF2912-14     | Closed | 2014-05-09T00:00:00 | 2014-05-22T00:00:00 | CITY OF MEDFORD                   |                         |                                       |             |       |           | General Government                                   | Discriminated against complainant on basis of race, national origin, religion, handicap | Referred Complainant Elsewhere   | 
| FF1162-17     | Closed | 2017-02-21T00:00:00 | 2017-02-21T00:00:00 | CITIBANK (SOUTH DAKOTA) N.A.*     | OFFICE OF THE PRESIDENT | PO BOX 6000                           | SIOUX FALLS | SD    | 57117     | Credit/Lending: Credit Card Protection services      | Inaccurately calculated a bill or debt, a portion of which the complainant does owe     | Consumer Pursuing Own Resolution | 
| FF2000-17     | Closed | 2017-03-23T00:00:00 | 2017-03-23T00:00:00 | CITIBANK (SOUTH DAKOTA) N.A.*     | OFFICE OF THE PRESIDENT | PO BOX 6000                           | SIOUX FALLS | SD    | 57117     | Credit/Lending: Credit Card Issuing                  | Inaccurately calculated a bill or debt, a portion of which the complainant does owe     | Referred Complainant Elsewhere   | 
| FF0491-17     | Closed | 2017-01-26T00:00:00 | 2017-01-26T00:00:00 | CITIBANK (SOUTH DAKOTA) N.A.*     | OFFICE OF THE PRESIDENT | PO BOX 6000                           | SIOUX FALLS | SD    | 57117     | Credit/Lending: Credit Card Issuing                  | Inaccurately calculated a bill or debt, a portion of which the complainant does owe     | Referred Complainant Elsewhere   | 
| FF0621-17     | Closed | 2017-01-31T00:00:00 | 2017-01-31T00:00:00 | CITIBANK (SOUTH DAKOTA) N.A.*     | OFFICE OF THE PRESIDENT | PO BOX 6000                           | SIOUX FALLS | SD    | 57117     | Credit/Lending: Credit Card Issuing                  | Service quality lower than what the complainant ordered or expected                     | Referred Complainant Elsewhere   | 
```