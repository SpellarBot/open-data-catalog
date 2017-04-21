# E-Government Service Portfolio - OSCIO

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ets-e-government-service-portfolio-2a966) |
| Metadata | [Link](https://data.oregon.gov/api/views/9g5a-r9zs) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/9g5a-r9zs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/9g5a-r9zs/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 9g5a-r9zs |
| Name | E-Government Service Portfolio - OSCIO |
| Category | Administrative |
| Tags | e-gov, egovernment, services, online, portfolio, applications, oregon, ecommerce, commerce, website, websites, apps |
| Created | 2013-09-06T20:58:20Z |
| Publication Date | 2017-04-05T19:58:56Z |

## Description

List of services provided by the Office of the State CIO, Oregon E-Government Program.

## Columns

```ls
| Included | Schema Type | Field Name   | Name            | Data Type      | Render Type    |
| ======== | =========== | ============ | =============== | ============== | ============== |
| Yes      | series tag  | service_name | Service Name    | text           | text           |
| Yes      | series tag  | service_type | Service Type    | drop_down_list | drop_down_list |
| Yes      | series tag  | agency       | Agency          | text           | dataset_link   |
| Yes      | series tag  | url          | Link to Website | url            | url            |
| Yes      | series tag  | funding_type | Funding Type    | drop_down_list | drop_down_list |
| Yes      | series tag  | licensing    | Licensing       | checkbox       | checkbox       |
| Yes      | time        | deployed     | Deployed        | calendar_date  | calendar_date  |
| Yes      | series tag  | transitioned | Transitioned?   | checkbox       | checkbox       |
| No       |             | redesigned   | Redesigned      | calendar_date  | calendar_date  |
```

## Time Field

```ls
Value = deployed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = redesigned
```

## Data Commands

```ls
series e:9g5a-r9zs d:2012-06-30T00:00:00.000Z t:transitioned=true t:service_type=veec-z8fg t:funding_type=wa8r-qtrq t:agency="Accountancy State Board" t:service_name="Board of Accountancy" t:url=http://www.oregon.gov/BOA/Pages/index.aspx m:row_number.9g5a-r9zs=1

series e:9g5a-r9zs d:2012-06-30T00:00:00.000Z t:transitioned=true t:service_type=veec-z8fg t:funding_type=wa8r-qtrq t:agency="Administrative Hearings, Office of" t:service_name="Office of Administrative Hearings" t:url=http://www.oregon.gov/OAH/Pages/index.aspx m:row_number.9g5a-r9zs=2

series e:9g5a-r9zs d:2017-04-05T19:15:32.000Z t:transitioned=true t:service_type=ssbw-6jdb t:funding_type=wa8r-qtrq t:agency="Administrative Services Department" t:service_name="Cooperative Procurement Program Payment Application" m:row_number.9g5a-r9zs=3
```

## Meta Commands

```ls
metric m:row_number.9g5a-r9zs p:long l:"Row Number"

entity e:9g5a-r9zs l:"E-Government Service Portfolio - OSCIO" t:url=https://data.oregon.gov/api/views/9g5a-r9zs

property e:9g5a-r9zs t:meta.view v:id=9g5a-r9zs v:category=Administrative v:attributionLink=http://www.oregon.gov/das/ets/egov v:averageRating=0 v:name="E-Government Service Portfolio - OSCIO"

property e:9g5a-r9zs t:meta.view.owner v:id=x7ch-rbs5 v:profileImageUrlMedium=/api/users/x7ch-rbs5/profile_images/THUMB v:profileImageUrlLarge=/api/users/x7ch-rbs5/profile_images/LARGE v:screenName="Wally Rogers" v:profileImageUrlSmall=/api/users/x7ch-rbs5/profile_images/TINY v:displayName="Wally Rogers"

property e:9g5a-r9zs t:meta.view.tableauthor v:id=x7ch-rbs5 v:profileImageUrlMedium=/api/users/x7ch-rbs5/profile_images/THUMB v:profileImageUrlLarge=/api/users/x7ch-rbs5/profile_images/LARGE v:screenName="Wally Rogers" v:profileImageUrlSmall=/api/users/x7ch-rbs5/profile_images/TINY v:roleName=administrator v:displayName="Wally Rogers"
```

## Top Records

```ls
| service_name                                        | service_type | agency                             | url                                                                                                 | funding_type | licensing | deployed            | transitioned | redesigned | 
| =================================================== | ============ | ================================== | =================================================================================================== | ============ | ========= | =================== | ============ | ========== | 
| Board of Accountancy                                | veec-z8fg    | Accountancy State Board            | [http://www.oregon.gov/BOA/Pages/index.aspx, Board of Accountancy]                                  | wa8r-qtrq    |           | 2012-06-30T00:00:00 | true         |            | 
| Office of Administrative Hearings                   | veec-z8fg    | Administrative Hearings, Office of | [http://www.oregon.gov/OAH/Pages/index.aspx, Office of Administrative Hearings]                     | wa8r-qtrq    |           | 2012-06-30T00:00:00 | true         |            | 
| Cooperative Procurement Program Payment Application | ssbw-6jdb    | Administrative Services Department | [null, Oregon ProgramCooperative Procurement Program]                                               | wa8r-qtrq    |           |                     | true         |            | 
| Office of the Chief Operating Officer               | veec-z8fg    | Administrative Services Department | [http://www.oregon.gov/DAS/Pages/COO.aspx, Office of the Chief Operating Officer]                   | wa8r-qtrq    |           | 2012-06-30T00:00:00 | true         |            | 
| PDF Content Delivery Service Application            | 6ej5-byia    | Administrative Services Department | [https://apps.oregon.gov/Application/cdn, PDF Content Delivery Service Application]                 | wa8r-qtrq    |           |                     |              |            | 
| Oregon.gov Form Builder Application                 | 6ej5-byia    | Administrative Services Department | [https://apps.oregon.gov/Application/OID/FormBuilder/Account/LogOn, Form Builder Application]       | wa8r-qtrq    |           | 2014-05-15T00:00:00 |              |            | 
| Department of Administrative Services               | veec-z8fg    | Administrative Services Department | [http://www.oregon.gov/DAS/Pages/index.aspx, Department of Administrative Services]                 | wa8r-qtrq    |           | 2016-03-15T00:00:00 |              |            | 
| Administrative Services Intranet                    | afas-9372    | Administrative Services Department | [https://intranet.oregon.gov/DAS, Intranet]                                                         | wa8r-qtrq    |           | 2012-08-13T00:00:00 | true         |            | 
| Oregon Job Opportunities                            | veec-z8fg    | Administrative Services Department | [http://www.oregon.gov/jobs/Pages/index.aspx, Oregon Job Opportunities]                             | wa8r-qtrq    |           | 2016-03-07T00:00:00 |              |            | 
| State Surplus Payments for Liquidity Services       | 8z4r-nijp    | Administrative Services Department | [http://www.oregon.gov/DAS/EAM/SURPLS/Pages/AuctionVendors1.aspx, State & Federal Surplus Property] | wa8r-qtrq    |           |                     | true         |            | 
```