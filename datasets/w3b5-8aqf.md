# Utility Company Customer Service Response Index (CSRI): Beginning 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/utility-company-customer-service-response-index-csri-beginning-2005) |
| Metadata | [Link](https://data.ny.gov/api/views/w3b5-8aqf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/w3b5-8aqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/w3b5-8aqf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | w3b5-8aqf |
| Name | Utility Company Customer Service Response Index (CSRI): Beginning 2005 |
| Attribution | New York State Department of Public Service |
| Category | Energy & Environment |
| Tags | utility, complaint, electric, gas, telecommunications |
| Created | 2014-02-04T15:30:36Z |
| Publication Date | 2017-04-13T15:45:48Z |

## Description

The Customer Service Response Index tracks utility performance and identifies the current level of customer service and responsiveness delivered by each utility service provider under the Commission?s jurisdiction with respect to consumer complaints filed with the Commission.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                              | Data Type | Render Type |
| ======== | ============== | ========================= | ================================= | ========= | =========== |
| No       |                | month                     | Month                             | number    | number      |
| No       |                | year                      | Year                              | number    | number      |
| Yes      | series tag     | service_provider          | Service Provider                  | text      | text        |
| Yes      | numeric metric | initial_complaints        | Initial Complaints                | number    | number      |
| Yes      | numeric metric | escalated_complaints      | Escalated Complaints              | number    | number      |
| Yes      | numeric metric | csm_index                 | CSM Index                         | number    | number      |
| No       |                | complaint_response_time   | Complaint Response Time           | number    | number      |
| Yes      | numeric metric | crm_index                 | CRM Index                         | number    | number      |
| No       |                | e_complaint_response_time | Escalated Complaint Response Time | number    | number      |
| Yes      | numeric metric | erm_index                 | ERM Index                         | number    | number      |
| Yes      | numeric metric | avg_age_of_cases_pending  | Avg Age of Cases Pending          | number    | number      |
| Yes      | numeric metric | pcm_index                 | PCM Index                         | number    | number      |
| Yes      | numeric metric | csri                      | CSRI                              | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = complaint_response_time,e_complaint_response_time,year,month
```

## Data Commands

```ls
series e:w3b5-8aqf d:2005-01-01T00:00:00.000Z t:service_provider=MCI m:csri=6 m:crm_index=2 m:escalated_complaints=32 m:avg_age_of_cases_pending=30.1 m:pcm_index=0.6 m:erm_index=1.3 m:csm_index=2.1 m:initial_complaints=112

series e:w3b5-8aqf d:2005-01-01T00:00:00.000Z t:service_provider="Sprint Communications" m:csri=0 m:crm_index=2 m:escalated_complaints=3 m:avg_age_of_cases_pending=93.2 m:pcm_index=-9 m:erm_index=2 m:csm_index=4.2 m:initial_complaints=36

series e:w3b5-8aqf d:2005-01-01T00:00:00.000Z t:service_provider="Talk America, Inc." m:csri=2.3 m:crm_index=0 m:escalated_complaints=3 m:avg_age_of_cases_pending=63.8 m:pcm_index=0 m:erm_index=0 m:csm_index=2.3 m:initial_complaints=11
```

## Meta Commands

```ls
metric m:initial_complaints p:integer l:"Initial Complaints" d:"The number of initial complaints DPS receives and forwards to the utility company for resolution directly with the customer." t:dataTypeName=number

metric m:escalated_complaints p:integer l:"Escalated Complaints" d:"The number of complaints that DPS escalated for further handling and investigation because the customer informed DPS that the utility failed to satisfy their initial complaint." t:dataTypeName=number

metric m:csm_index p:float l:"CSM Index" d:"The Consumer Satisfaction (CSM) Index scores the ratio of the number of initial complaints to the number of escalated complaints in the reporting month. A score of 5 points are awarded when a service provider receives no escalated complaints during the reporting month. There is no score awarded if a service provider satisfies less than 50% of the customers that the PSC refers to them." t:dataTypeName=number

metric m:crm_index p:float l:"CRM Index" d:"The Complaint Response Time (CRM) Index scores the service providers responsiveness to initial complaints closed in the reporting month. A score of 2 points is awarded when a provider's average response time for initial complaints is 14 days or less. No points are earned if the average response time for initial complaints is more than 28 days (twice the acceptable reply standard)." t:dataTypeName=number

metric m:erm_index p:float l:"ERM Index" d:"The Escalated Complaint Response Time (ERM) Index scores the service providers responsiveness to escalated complaints closed in the reporting month. A score of 2 points is awarded when a provider's average response time for escalated complaints is 10 days or less. No points are earned if the average response time for escalated complaints is more than 25 days (two weeks past due)." t:dataTypeName=number

metric m:avg_age_of_cases_pending p:float l:"Avg Age of Cases Pending" d:"This is the average age, in days, of all the cases awaiting a response from the service provider." t:dataTypeName=number

metric m:pcm_index p:float l:"PCM Index" d:"The Pending Case (PCM) Index scores the average age of all cases awaiting response by the service provider. A score of 1 point is awarded when a service providers' average age of all cases is 14 days or less. No points are earned if the average age of all cases exceeds 70 days (two months delinquent). A negative score is applied if the average age of all cases is over 70 days." t:dataTypeName=number

metric m:csri p:float l:CSRI d:"The Customer Service Response Index (CSRI) is the overall score received by the service provider. It is the sum of the four indices; CSM, CRM, ERM and PCM." t:dataTypeName=number

entity e:w3b5-8aqf l:"Utility Company Customer Service Response Index (CSRI): Beginning 2005" t:attribution="New York State Department of Public Service" t:url=https://data.ny.gov/api/views/w3b5-8aqf

property e:w3b5-8aqf t:meta.view v:id=w3b5-8aqf v:category="Energy & Environment" v:attributionLink=http://www3.dps.ny.gov/W/PSCWeb.nsf/ArticlesByTitle/448C499468E952C085257687006F3A82?OpenDocument v:averageRating=0 v:name="Utility Company Customer Service Response Index (CSRI): Beginning 2005" v:attribution="New York State Department of Public Service"

property e:w3b5-8aqf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:w3b5-8aqf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:w3b5-8aqf t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| month | year | service_provider              | initial_complaints | escalated_complaints | csm_index | complaint_response_time | crm_index | e_complaint_response_time | erm_index | avg_age_of_cases_pending | pcm_index | csri | 
| ===== | ==== | ============================= | ================== | ==================== | ========= | ======================= | ========= | ========================= | ========= | ======================== | ========= | ==== | 
| 1     | 2005 | MCI                           | 112                | 32                   | 2.1       | 11.5                    | 2.0       | 17.6                      | 1.3       | 30.1                     | 0.6       | 6.0  | 
| 1     | 2005 | Sprint Communications         | 36                 | 3                    | 4.2       | 10.3                    | 2.0       | 7.3                       | 2.0       | 93.2                     | -9.0      | 0.0  | 
| 1     | 2005 | Talk America, Inc.            | 11                 | 3                    | 2.3       | 36.2                    | 0.0       | 31.1                      | 0.0       | 63.8                     | 0.0       | 2.3  | 
| 1     | 2005 | Cordia Communications Company | 21                 | 5                    | 2.6       | 12.8                    | 2.0       | 32.9                      | 0.0       | 49.3                     | 0.3       | 4.9  | 
| 1     | 2005 | AT&T of New York              | 251                | 62                   | 2.5       | 10.3                    | 2.0       | 51.0                      | 0.0       | 29.6                     | 0.7       | 5.2  | 
| 1     | 2005 | KeySpan of Long Island        | 26                 | 7                    | 2.3       | 6.8                     | 2.0       | 34.8                      | 0.0       | 1.0                      | 1.0       | 5.3  | 
| 1     | 2005 | Con Edison of New York        | 300                | 59                   | 3.0       | 17.2                    | 1.6       | 54.0                      | 0.0       | 25.2                     | 0.7       | 5.3  | 
| 1     | 2005 | Econnergy                     | 27                 | 5                    | 3.1       | 66.4                    | 0.0       | 0.1                       | 2.0       | 44.7                     | 0.4       | 5.5  | 
| 1     | 2005 | IDT America Corp.             | 51                 | 13                   | 2.5       | 8.0                     | 2.0       | 73.9                      | 0.0       | 10.5                     | 1.0       | 5.5  | 
| 1     | 2005 | KeySpan of New York           | 68                 | 15                   | 2.8       | 6.6                     | 2.0       | 50.5                      | 0.0       | 19.9                     | 0.9       | 5.7  | 
```