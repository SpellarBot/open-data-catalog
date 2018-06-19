# Mobility Talks: Find Us

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mobility-talks-find-us) |
| Metadata | [Link](https://data.austintexas.gov/api/views/nha4-9fvx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/nha4-9fvx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/nha4-9fvx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | nha4-9fvx |
| Name | Mobility Talks: Find Us |
| Attribution | City of Austin |
| Category | Capital Planning |
| Tags | mobility, cpo, atd, pwd, transportation |
| Created | 2016-03-17T23:00:05Z |
| Publication Date | 2016-05-09T18:08:06Z |

## Description

As great as Austin is, we struggle with transportation and mobility. Whether you drive, walk, bike, or take transit, your City Council wants to know your priorities for improving Austin?s transportation network. Between March 21 and May 8, the City is asking for your feedback. Find us at any of the locations listed to be heard.
The information you provide during Mobility Talks will be presented to the Mobility Committee of the City Council on June 8, 2016. The meeting will be at 3 p.m. in Council Chambers at City Hall, 301 W. 2nd Street. Learn more about Mobility Talks here www.mobilitytalks.org.

## Columns

```ls
| Included | Schema Type | Field Name     | Name                         | Data Type     | Render Type   |
| ======== | =========== | ============== | ============================ | ============= | ============= |
| Yes      | time        | date1          | Date                         | calendar_date | calendar_date |
| Yes      | series tag  | time           | Mobile Engagement Team Times | text          | text          |
| Yes      | series tag  | activity_event | Event                        | text          | text          |
| Yes      | series tag  | location       | Name of Location             | text          | text          |
```

## Time Field

```ls
Value = date1
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:nha4-9fvx d:2016-04-08T00:00:00.000Z t:time="7:30 a.m. - 9:30 a.m." t:location="Mozart's Coffee Shop" t:activity_event="Pop Up" m:row_number.nha4-9fvx=1

series e:nha4-9fvx d:2016-04-11T00:00:00.000Z t:time="6:30 a.m. - 8:30 a.m." t:location="Pavilion Park and Ride" t:activity_event="Pop Up" m:row_number.nha4-9fvx=2

series e:nha4-9fvx d:2016-04-04T00:00:00.000Z t:time="5:45 p.m. - 7:00 p.m." t:location="Terrazas Branch Library" t:activity_event="NHCD Public Meeting" m:row_number.nha4-9fvx=3
```

## Meta Commands

```ls
metric m:row_number.nha4-9fvx p:long l:"Row Number"

entity e:nha4-9fvx l:"Mobility Talks: Find Us" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/nha4-9fvx

property e:nha4-9fvx t:meta.view v:id=nha4-9fvx v:category="Capital Planning" v:attributionLink=http://www.austintexas.gov/mobilitytalks v:averageRating=0 v:name="Mobility Talks: Find Us" v:attribution="City of Austin"

property e:nha4-9fvx t:meta.view.license v:name="Public Domain"

property e:nha4-9fvx t:meta.view.owner v:id=k6xj-wrjq v:screenName="Ashley Parsons" v:displayName="Ashley Parsons"

property e:nha4-9fvx t:meta.view.tableauthor v:id=k6xj-wrjq v:screenName="Ashley Parsons" v:roleName=editor v:displayName="Ashley Parsons"
```

## Top Records

```ls
| date1               | time                    | activity_event              | location                     | 
| =================== | ======================= | =========================== | ============================ | 
| 2016-04-08T00:00:00 | 7:30 a.m. - 9:30 a.m.   | Pop Up                      | Mozart's Coffee Shop         | 
| 2016-04-11T00:00:00 | 6:30 a.m. - 8:30 a.m.   | Pop Up                      | Pavilion Park and Ride       | 
| 2016-04-04T00:00:00 | 5:45 p.m. - 7:00 p.m.   | NHCD Public Meeting         | Terrazas Branch Library      | 
| 2016-04-04T00:00:00 | 6:30 a.m. - 8:30 a.m.   | Pop Up                      | Tech Ridge Park and Ride     | 
| 2016-03-23T00:00:00 | 6:15 p.m.- 8:15 p.m.    | PARD Workshop - Shipe Pool  | Griffin School               | 
| 2016-04-10T00:00:00 | 8:30 a.m. - 10:30 a.m.  | Statesman Cap 10k           | Statesman building           | 
| 2016-04-25T00:00:00 | 5:45 p.m. - 7:00 p.m.   | NHCD Public Meeting         | North Village Branch Library | 
| 2016-04-01T00:00:00 | 5:00 p.m. - 7:00 p.m.   | Austin Urban Music Festival | Auditorium Shores            | 
| 2016-04-09T00:00:00 | 10:00 a.m. - 12:00 p.m. | STEAM Festival              | Martin Middle School         | 
| 2016-04-02T00:00:00 | 11:00 a.m. - 1:00 p.m.  | Zilker Garden Festival      | Zilker Gardens               | 
```