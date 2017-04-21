# .nyc Domain Registrations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-domain-registrations) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9cw8-7heb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9cw8-7heb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9cw8-7heb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9cw8-7heb |
| Name | .nyc Domain Registrations |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | Business |
| Tags | .nyc, domain, internet, web, site, website, webpage, page, registration |
| Created | 2015-07-13T18:48:56Z |
| Publication Date | 2017-04-20T21:11:25Z |

## Description

A list of all .nyc domains registered along with the registration date and registrant type. This list is updated daily.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag  | domain_name              | Domain Name              | text          | text          |
| Yes      | time        | domain_registration_date | Domain Registration Date | calendar_date | calendar_date |
| Yes      | series tag  | nexus_category           | Nexus Category           | text          | text          |
```

## Time Field

```ls
Value = domain_registration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:9cw8-7heb d:2016-12-27T05:01:47.000Z t:nexus_category=ORG t:domain_name=000.nyc m:row_number.9cw8-7heb=1

series e:9cw8-7heb d:2015-12-23T17:41:17.000Z t:nexus_category=INDIV t:domain_name=001.nyc m:row_number.9cw8-7heb=2

series e:9cw8-7heb d:2014-10-08T15:48:29.000Z t:nexus_category=INDIV t:domain_name=007names.nyc m:row_number.9cw8-7heb=3
```

## Meta Commands

```ls
metric m:row_number.9cw8-7heb p:long l:"Row Number"

entity e:9cw8-7heb l:".nyc Domain Registrations" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/9cw8-7heb

property e:9cw8-7heb t:meta.view v:id=9cw8-7heb v:category=Business v:averageRating=0 v:name=".nyc Domain Registrations" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:9cw8-7heb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9cw8-7heb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| domain_name  | domain_registration_date | nexus_category | 
| ============ | ======================== | ============== | 
| 000.nyc      | 2016-12-27T05:01:47      | ORG            | 
| 001.nyc      | 2015-12-23T17:41:17      | INDIV          | 
| 007names.nyc | 2014-10-08T15:48:29      | INDIV          | 
| 007.nyc      | 2016-04-11T01:49:54      | INDIV          | 
| 013.nyc      | 2014-10-21T18:27:57      | INDIV          | 
| 020.nyc      | 2015-08-16T16:37:49      | INDIV          | 
| 06880.nyc    | 2015-06-19T04:39:45      | ORG            | 
| 0ne.nyc      | 2016-03-18T04:58:52      | ORG            | 
| 0pen.nyc     | 2016-03-18T04:58:49      | ORG            | 
| 0xcc.nyc     | 2016-02-24T15:36:36      | INDIV          | 
```