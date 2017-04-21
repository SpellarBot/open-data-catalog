# ACCD :: Event Listings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/accd-event-listings-current-calendar-year) |
| Metadata | [Link](https://data.austintexas.gov/api/views/p9ma-z6y9) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/p9ma-z6y9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/p9ma-z6y9/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | p9ma-z6y9 |
| Name | ACCD :: Event Listings |
| Attribution | Austin Convention Center Department |
| Category | Business |
| Tags | convention center, palmer, events, calendar |
| Created | 2015-07-20T13:00:01Z |
| Publication Date | 2017-03-02T19:10:59Z |

## Description

Listing of our events at Austin Convention Center and Palmer Events Center for the current calendar year. Included are show dates, event names, hosting facility, attendance, contact numbers and websites for events.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | time           | arrive_date  | Arrive Date  | calendar_date | calendar_date |
| No       |                | depart_date  | Depart Date  | calendar_date | calendar_date |
| Yes      | series tag     | location     | Location     | text          | text          |
| Yes      | series tag     | event_name   | Event Name   | text          | text          |
| Yes      | numeric metric | attendance   | Attendance   | number        | number        |
| Yes      | series tag     | phone_number | Phone Number | text          | text          |
| Yes      | series tag     | website      | Website      | text          | text          |
```

## Time Field

```ls
Value = arrive_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = depart_date
```

## Data Commands

```ls
series e:p9ma-z6y9 d:2017-01-01T00:00:00.000Z t:phone_number=512-479-8776 t:website=www.austinsportscenter.com t:location="Austin Convention Center" t:event_name="2017 Tour of Texas Warm Up" m:attendance=2500

series e:p9ma-z6y9 d:2017-01-08T00:00:00.000Z t:phone_number=312-423-7262 t:website=www.pcma.org t:location="Austin Convention Center" t:event_name="2017 Convening Leaders" m:attendance=4000

series e:p9ma-z6y9 d:2017-01-14T00:00:00.000Z t:website=www.austinweddings.com t:location="Palmer Events Center" t:event_name="2017 Bridal Extravaganza" m:attendance=4000
```

## Meta Commands

```ls
metric m:attendance p:integer l:Attendance t:dataTypeName=number

entity e:p9ma-z6y9 l:"ACCD :: Event Listings" t:attribution="Austin Convention Center Department" t:url=https://data.austintexas.gov/api/views/p9ma-z6y9

property e:p9ma-z6y9 t:meta.view v:id=p9ma-z6y9 v:category=Business v:averageRating=0 v:name="ACCD :: Event Listings" v:attribution="Austin Convention Center Department"

property e:p9ma-z6y9 t:meta.view.license v:name="Public Domain"

property e:p9ma-z6y9 t:meta.view.owner v:id=mepj-zp7g v:screenName="Chris G Hernandez" v:displayName="Chris G Hernandez"

property e:p9ma-z6y9 t:meta.view.tableauthor v:id=mepj-zp7g v:screenName="Chris G Hernandez" v:roleName=publisher v:displayName="Chris G Hernandez"
```

## Top Records

```ls
| arrive_date         | depart_date         | location                 | event_name                                 | attendance | phone_number | website                         | 
| =================== | =================== | ======================== | ========================================== | ========== | ============ | =============================== | 
| 2017-01-01T00:00:00 | 2017-01-01T00:00:00 | Austin Convention Center | 2017 Tour of Texas Warm Up                 | 2500       | 512-479-8776 | www.austinsportscenter.com      | 
| 2017-01-08T00:00:00 | 2017-01-11T00:00:00 | Austin Convention Center | 2017 Convening Leaders                     | 4000       | 312-423-7262 | www.pcma.org                    | 
| 2017-01-08T00:00:00 | 2017-01-08T00:00:00 | Palmer Events Center     | Private Event                              |            |              |                                 | 
| 2017-01-12T00:00:00 | 2017-01-12T00:00:00 | Palmer Events Center     | Private Event                              |            |              |                                 | 
| 2017-01-13T00:00:00 | 2017-01-13T00:00:00 | Palmer Events Center     | Private Event                              |            |              |                                 | 
| 2017-01-13T00:00:00 | 2017-01-15T00:00:00 | Austin Convention Center | 19th Annual Austin Home & Garden Show      |            | 210-408-0998 | www.austinhomeandgardenshow.com | 
| 2017-01-14T00:00:00 | 2017-01-14T00:00:00 | Austin Convention Center | Private Event                              |            |              |                                 | 
| 2017-01-14T00:00:00 | 2017-01-15T00:00:00 | Palmer Events Center     | 2017 Bridal Extravaganza                   | 4000       |              | www.austinweddings.com          | 
| 2017-01-18T00:00:00 | 2017-01-19T00:00:00 | Palmer Events Center     | 2017 Build Expo                            | 1500       | 512-249-5303 | www.constructionexpo.com        | 
| 2017-01-18T00:00:00 | 2017-01-18T00:00:00 | Austin Convention Center | CMTA Downtown Station Stakeholder Workshop | 35         | 512-684-3231 | www.capmetro.org                | 
```