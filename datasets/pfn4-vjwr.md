# Young Adult Borough Centers 2012-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/young-adult-borough-centers-2012-2013-e3cae) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pfn4-vjwr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pfn4-vjwr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pfn4-vjwr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pfn4-vjwr |
| Name | Young Adult Borough Centers 2012-2013 |
| Attribution | Department of Education (DOE) |
| Category | Social Services |
| Tags | young adult borough centers 2012-2013, doe, education, jobs and economic mobility |
| Created | 2013-03-19T19:23:41Z |
| Publication Date | 2013-03-19T19:26:20Z |

## Description

Citywide young adult borough centers

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | location           | Location           | text      | text        |
| Yes      | series tag  | borough            | Borough            | text      | text        |
| Yes      | series tag  | site_administrator | Site Administrator | text      | text        |
| Yes      | series tag  | phone_number       | Phone Number       | text      | text        |
| Yes      | series tag  | email              | Email              | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:pfn4-vjwr d:2012-01-01T00:00:00.000Z t:site_administrator="Gladys De la Cruz" t:phone_number="(718) 918-2700 x111" t:email=gdelacruz@schools.nyc.gov t:location="Adlai Stevenson Campus YABC" t:borough=Bronx m:row_number.pfn4-vjwr=1

series e:pfn4-vjwr d:2012-01-01T00:00:00.000Z t:site_administrator="Arleen Milton" t:phone_number="(718) 993-1840" t:email=amilton2@schools.nyc.gov t:location="Alfred E. Smith Campus YABC" t:borough=Bronx m:row_number.pfn4-vjwr=2

series e:pfn4-vjwr d:2012-01-01T00:00:00.000Z t:site_administrator="Ruth Colton" t:phone_number="(718) 944-3400 x3558" t:email=rcolton@schools.nyc.gov t:location="Christopher Columbus YABC" t:borough=Bronx m:row_number.pfn4-vjwr=3
```

## Meta Commands

```ls
metric m:row_number.pfn4-vjwr p:long l:"Row Number"

entity e:pfn4-vjwr l:"Young Adult Borough Centers 2012-2013" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/pfn4-vjwr

property e:pfn4-vjwr t:meta.view v:id=pfn4-vjwr v:category="Social Services" v:averageRating=0 v:name="Young Adult Borough Centers 2012-2013" v:attribution="Department of Education (DOE)"

property e:pfn4-vjwr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pfn4-vjwr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| location                             | borough  | site_administrator | phone_number            | email                     | 
| ==================================== | ======== | ================== | ======================= | ========================= | 
| Adlai Stevenson Campus YABC          | Bronx    | Gladys De la Cruz  | (718) 918-2700 x111     | gdelacruz@schools.nyc.gov | 
| Alfred E. Smith Campus YABC          | Bronx    | Arleen Milton      | (718) 993-1840          | amilton2@schools.nyc.gov  | 
| Christopher Columbus YABC            | Bronx    | Ruth Colton        | (718) 944-3400 x3558    | rcolton@schools.nyc.gov   | 
| Grace Dodge YABC                     | Bronx    | Veronica Jackson   | (718) 584-2700 ext.2131 | vjackso7@schools.nyc.gov  | 
| Herbert Lehman YABC                  | Bronx    | Martin Smallhorne  | (718) 904-4280          | msmallh@schools.nyc.gov   | 
| James Monroe Educational Campus YABC | Bronx    | Carmel Belizaire   | (718) 860-8284          | cbeliza@schools.nyc.gov   | 
| John F. Kennedy YABC                 | Bronx    | James Barron       | (718) 817-7470          | jbarron4@schools.nyc.gov  | 
| Walton Campus YABC                   | Bronx    | Thomas Lopez       | (718) 329-7380 X 3211   | tlopez3@schools.nyc.gov   | 
| Abraham Lincoln YABC                 | Brooklyn | Neal Reich         | (718) 333-7433          | nreich@schools.nyc.gov    | 
| Automotive YABC                      | Brooklyn | David Decamp       | (718) 218-9301 x1595    | ddecamp@schools.nyc.gov   | 
```