# Economic Development Compliance: Texas Enterprise Zone Nominations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/economic-development-compliance-texas-enterprise-zone-nominations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/tv4x-8thz) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/tv4x-8thz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/tv4x-8thz/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | tv4x-8thz |
| Name | Economic Development Compliance: Texas Enterprise Zone Nominations |
| Created | 2014-02-10T22:29:51Z |
| Publication Date | 2017-03-01T14:48:54Z |

## Description

This table lists firms who have been nominated by the City of Austin for the Texas Enterprise Zone Program.The Texas Enterprise Zone Program is a State of Texas incentive program and does not require a cash incentive from the City.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag     | firm                    | Firm                    | text          | text          |
| Yes      | time           | application_date        | Application Date        | calendar_date | calendar_date |
| Yes      | numeric metric | total_investment        | Total Investment        | money         | money         |
| Yes      | numeric metric | total_announced_jobs    | Total Announced Jobs    | number        | number        |
| Yes      | numeric metric | jobs_retained           | Total Jobs Retained     | number        | number        |
| Yes      | series tag     | state_status            | State Status            | text          | text          |
| Yes      | series tag     | chapter_380_agreement   | Chapter 380 Agreement   | text          | text          |
| Yes      | series tag     | city_council_resolution | City Council Resolution | url           | url           |
| Yes      | series tag     | rca                     | RCA                     | url           | url           |
```

## Time Field

```ls
Value = application_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:tv4x-8thz d:2010-09-01T00:00:00.000Z t:chapter_380_agreement=Active t:firm="Samsung Austin Semiconductor, LLC" t:state_status=Approved t:city_council_resolution="http://www.ci.austin.tx.us/edims/document.cfm?id=141756" t:rca="http://www.austintexas.gov/edims/document.cfm?id=141485" m:total_investment=3599000000 m:jobs_retained=1035 m:total_announced_jobs=500

series e:tv4x-8thz d:2014-06-02T00:00:00.000Z t:chapter_380_agreement=None t:firm="Flextronics America LLC" t:state_status=Approved t:city_council_resolution="http://www.austintexas.gov/edims/document.cfm?id=210780" t:rca="http://www.austintexas.gov/edims/document.cfm?id=210477" m:total_investment=15000000 m:jobs_retained=200 m:total_announced_jobs=300

series e:tv4x-8thz d:2007-12-03T00:00:00.000Z t:chapter_380_agreement=None t:firm="Spansion LLC" t:state_status=Approved t:city_council_resolution="http://www.austintexas.gov/edims/document.cfm?id=109946" t:rca="http://www.austintexas.gov/edims/document.cfm?id=109767" m:total_investment=280000000 m:jobs_retained=1271 m:total_announced_jobs=0
```

## Meta Commands

```ls
metric m:total_investment p:long l:"Total Investment" t:dataTypeName=money

metric m:total_announced_jobs p:integer l:"Total Announced Jobs" d:"Includes new jobs created; does not include retained jobs" t:dataTypeName=number

metric m:jobs_retained p:integer l:"Total Jobs Retained" t:dataTypeName=number

entity e:tv4x-8thz l:"Economic Development Compliance: Texas Enterprise Zone Nominations" t:url=https://data.austintexas.gov/api/views/tv4x-8thz

property e:tv4x-8thz t:meta.view v:id=tv4x-8thz v:averageRating=0 v:name="Economic Development Compliance: Texas Enterprise Zone Nominations"

property e:tv4x-8thz t:meta.view.owner v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:displayName="Melissa Alvarado"

property e:tv4x-8thz t:meta.view.tableauthor v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:roleName=editor v:displayName="Melissa Alvarado"
```

## Top Records

```ls
| firm                                          | application_date    | total_investment | total_announced_jobs | jobs_retained | state_status | chapter_380_agreement                          | city_council_resolution                                                                | rca                                                                                                | 
| ============================================= | =================== | ================ | ==================== | ============= | ============ | ============================================== | ====================================================================================== | ================================================================================================== | 
| Samsung Austin Semiconductor, LLC             | 2010-09-01T00:00:00 | 3599000000       | 500                  | 1035          | Approved     | Active                                         | [http://www.ci.austin.tx.us/edims/document.cfm?id=141756, Resolution No. 20100826-016] | [http://www.austintexas.gov/edims/document.cfm?id=141485, Samsung Enterprise Zone RCA]             | 
| Flextronics America LLC                       | 2014-06-02T00:00:00 | 15000000         | 300                  | 200           | Approved     | None                                           | [http://www.austintexas.gov/edims/document.cfm?id=210780, Resolution No. 20140522-006] | [http://www.austintexas.gov/edims/document.cfm?id=210477, Flextronics America LLC Project Summary] | 
| Spansion LLC                                  | 2007-12-03T00:00:00 | 280000000        | 0                    | 1271          | Approved     | None                                           | [http://www.austintexas.gov/edims/document.cfm?id=109946, Resolution No. 20071101-004] | [http://www.austintexas.gov/edims/document.cfm?id=109767, Spansion Enterprise Zone RCA]            | 
| Spansion LLC                                  | 2014-06-02T00:00:00 | 230500000        | 0                    | 500           | Approved     | None                                           | [http://www.austintexas.gov/edims/document.cfm?id=210779, Resolution No. 20140522-005] | [http://www.austintexas.gov/edims/document.cfm?id=210474, Spansion LLC Project Summary]            | 
| Bazaarvoice, Inc.                             | 2010-06-01T00:00:00 | 6050000          | 513                  | 208           | Denied       | None                                           | [http://www.austintexas.gov/edims/document.cfm?id=137720, Resolution No. 20100527-027] | [http://www.austintexas.gov/edims/document.cfm?id=137721, Bazaarvoice Enterprise Zone RCA]         | 
| St. David?s Healthcare Partnership, L.P., LLP | 2010-06-01T00:00:00 | 71775000         | 0                    | 654           | Denied       | None                                           | [http://www.austintexas.gov/edims/document.cfm?id=137723, Resolution No. 20100527-026] | [http://www.austintexas.gov/edims/document.cfm?id=137724, St. David's Enterprise Zone RCA]         | 
| Gila LLC                                      | 2011-09-01T00:00:00 | 5500000          | 150                  | 303           | Denied       | None                                           | [http://www.austintexas.gov/edims/document.cfm?id=155792, Resolution No. 20110804-006] | [http://www.austintexas.gov/edims/document.cfm?id=155574, Gila Enterprise Zone RCA]                | 
| US Farathane Corporation                      | 2012-03-01T00:00:00 | 26877000         | 228                  | 0             | Denied       | Company Retained in Austin, Agreement Inactive | [http://www.austintexas.gov/edims/document.cfm?id=164508, Resolution No. 20120301-007] | [http://www.austintexas.gov/edims/document.cfm?id=164347, US Farathane Enterprise Zone RCA]        | 
| eBay, Inc.                                    | 2013-12-02T00:00:00 | 8486323          | 400                  | 651           | Approved     | Company Retained in Austin, Agreement Inactive | [http://www.austintexas.gov/edims/document.cfm?id=201497, Resolution No. 20131121-107] | [http://www.austintexas.gov/edims/document.cfm?id=201390, eBay Enterprise Zone RCA]                | 
| Otis Spunkmeyer, Inc.                         | 2007-09-04T00:00:00 | 17800000         | 60                   | 123           | Approved     | None                                           | [http://www.ci.austin.tx.us/edims/document.cfm?id=210780, Resolution No. 20140522-006] | [http://www.austintexas.gov/edims/document.cfm?id=109519, Otis Spunkmeyer Enterprise Zone RCA]     | 
```