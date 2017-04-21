# LAW Public Service Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/law-public-service-program-11ba2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yk6f-pa7p) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yk6f-pa7p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yk6f-pa7p/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yk6f-pa7p |
| Name | LAW Public Service Program |
| Attribution | Law Department (LAW) |
| Category | City Government |
| Tags | law, justice, legislation, law public service program |
| Created | 2013-02-06T18:19:07Z |
| Publication Date | 2013-06-21T20:07:09Z |

## Description

Early in his tenure at the Law Department, Corporation Counsel Michael A. Cardozo initiated the Public Service Program - a private/public partnership with the City's prominent law firms, where firms either lend their attorneys to the Law Department for a finite period of time or agree to take on City cases in-house. The Program benefits both the City and the law firms. The City receives the assistance of an incredibly well-trained and talented group of attorneys while the attorneys receive the kind of hands-on, in-court litigation experience that is often hard to come by at the best private law firms. While participation in the Program will not lead to offers of permanent employment at the Law Department, it will enable the volunteers to keep their skills fresh while serving the public. 
Trial Attorney Volunteers: A number of firms lend mid-level litigation associates to the Law Department for a period of four to six months to work full-time in our Tort Division trial units. These attorneys conduct back-to-back civil trials, selecting juries, examining and cross-examining witnesses and presenting opening statements and closing arguments.
Law Firm Volunteers: Other firms have chosen to take entire matters in-house, giving their attorneys the chance to participate in court conferences, settlement negotiations, depositions, and, ultimately, trials.
Deposition Program: Firms also lend associates to the Law Department either to conduct a series of depositions in an individual case or to spend two to three weeks in our offices conducting back-to-back depositions in a variety of cases.

## Columns

```ls
| Included | Schema Type | Field Name                         | Name                               | Data Type | Render Type |
| ======== | =========== | ================================== | ================================== | ========= | =========== |
| No       | time        | :updated_at                        | updated_at                         | meta_data | meta_data   |
| Yes      | series tag  | firms_donating_services_since_2007 | Firms Donating Services Since 2007 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yk6f-pa7p d:2013-02-06T10:19:08.000Z t:firms_donating_services_since_2007="Allen & Overy LLP" m:row_number.yk6f-pa7p=1

series e:yk6f-pa7p d:2013-02-06T10:19:08.000Z t:firms_donating_services_since_2007="Baker & Hostetler LLP" m:row_number.yk6f-pa7p=2

series e:yk6f-pa7p d:2013-02-06T10:19:08.000Z t:firms_donating_services_since_2007="Bracewell & Giuliani LLP" m:row_number.yk6f-pa7p=3
```

## Meta Commands

```ls
metric m:row_number.yk6f-pa7p p:long l:"Row Number"

entity e:yk6f-pa7p l:"LAW Public Service Program" t:attribution="Law Department (LAW)" t:url=https://data.cityofnewyork.us/api/views/yk6f-pa7p

property e:yk6f-pa7p t:meta.view v:id=yk6f-pa7p v:category="City Government" v:attributionLink=http://www.nyc.gov/html/law/html/about/service_firms.shtml v:averageRating=0 v:name="LAW Public Service Program" v:attribution="Law Department (LAW)"

property e:yk6f-pa7p t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yk6f-pa7p t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | firms_donating_services_since_2007 | 
| =========== | ================================== | 
| 1360145948  | Allen & Overy LLP                  | 
| 1360145948  | Baker & Hostetler LLP              | 
| 1360145948  | Bracewell & Giuliani LLP           | 
| 1360145948  | Cadwalader, Wickersham & Taft LLP  | 
| 1360145948  | Chadbourne & Parke LLP             | 
| 1360145948  | Cohen Milstein Sellers & Toll PLLC | 
| 1360145948  | Covington & Burling LLP            | 
| 1360145948  | Cravath, Swaine & Moore LLP        | 
| 1360145948  | Debevoise & Plimpton LLP           | 
| 1360145948  | Dechert LLP                        | 
```