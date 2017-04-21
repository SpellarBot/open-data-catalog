# Data Center Summary Extract Service Offering Disk

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/data-center-summary-extract-service-offering-disk) |
| Metadata | [Link](https://data.seattle.gov/api/views/3wdb-kmn9) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/3wdb-kmn9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/3wdb-kmn9/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 3wdb-kmn9 |
| Name | Data Center Summary Extract Service Offering Disk |
| Category | City Business |
| Created | 2016-08-04T18:00:14Z |
| Publication Date | 2016-08-04T18:01:05Z |

## Description

Ticket data for IT Service Level Indicators (in reference to inter-department Service Level Agreements).

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | serviceoffering    | ServiceOffering    | text          | text          |
| Yes      | time           | month              | Month              | calendar_date | calendar_date |
| Yes      | numeric metric | mtdticketcnt       | MTDTicketCnt       | number        | number        |
| Yes      | numeric metric | mtdunigreendept    | MTDUniGreenDept    | number        | number        |
| Yes      | numeric metric | mtdhourstotal      | MTDHoursTotal      | number        | number        |
| Yes      | numeric metric | mtdavghours        | MTDAvgHours        | number        | number        |
| Yes      | numeric metric | blank1             | BLANK1             | number        | number        |
| Yes      | numeric metric | nogreentks         | NoGreenTks         | number        | number        |
| Yes      | numeric metric | noyellowtks        | NoYellowTks        | number        | number        |
| Yes      | numeric metric | noredtks           | NoRedTks           | number        | number        |
| Yes      | numeric metric | mtdgreenpct        | MTDGreenPct        | number        | number        |
| Yes      | numeric metric | mtdyellowpct       | MTDYellowPct       | number        | number        |
| Yes      | numeric metric | mtdredpct          | MTDRedPct          | number        | number        |
| Yes      | numeric metric | ytdunigreendept    | YTDUniGreenDept    | number        | number        |
| Yes      | numeric metric | ytdhourstotal      | YTDHoursTotal      | number        | number        |
| Yes      | numeric metric | ytdavghours        | YTDAvgHours        | number        | number        |
| Yes      | numeric metric | blank2             | BLANK2             | number        | number        |
| Yes      | numeric metric | ytdticketcnt       | YTDTicketCnt       | number        | number        |
| Yes      | numeric metric | ytdgreen           | YTDGreen           | number        | number        |
| Yes      | numeric metric | ytdyellow          | YTDYellow          | number        | number        |
| Yes      | numeric metric | ytdred             | YTDRed             | number        | number        |
| Yes      | numeric metric | ytdgreenpct        | YTDGreenPct        | number        | number        |
| Yes      | numeric metric | ytdyellowpct       | YTDYellowPct       | number        | number        |
| Yes      | numeric metric | ytdredpct          | YTDRedPct          | number        | number        |
| Yes      | series tag     | targetunit         | TargetUnit         | text          | text          |
| Yes      | numeric metric | mtduniservoffering | MTDUniServOffering | number        | number        |
| Yes      | numeric metric | ytduniservoffering | YTDUniServOffering | number        | number        |
| No       |                | endofmonth         | EndOfMonth         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = month
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = endofmonth
```

## Data Commands

```ls
series e:3wdb-kmn9 d:2016-06-03T00:00:00.000Z t:targetunit=Hour t:serviceoffering="Physical Hosting and Support  - New Physical Server" m:mtdgreenpct=0 m:ytdticketcnt=1 m:ytdred=1 m:noredtks=1 m:ytdunigreendept=0 m:ytduniservoffering=1 m:ytdgreen=0 m:mtdticketcnt=1 m:mtdunigreendept=0 m:ytdgreenpct=0 m:mtdyellowpct=0 m:blank2=0 m:blank1=0 m:ytdavghours=272.5 m:ytdhourstotal=272.48 m:ytdredpct=100 m:ytdyellow=0 m:mtdredpct=100 m:mtdavghours=272.5 m:nogreentks=0 m:noyellowtks=0 m:mtduniservoffering=1 m:ytdyellowpct=0 m:mtdhourstotal=272.48

series e:3wdb-kmn9 d:2016-06-22T00:00:00.000Z t:targetunit=Day t:serviceoffering="Virtual Hosting and Support - New Virtual Server" m:mtdgreenpct=0 m:ytdticketcnt=17 m:ytdred=11 m:noredtks=5 m:ytdunigreendept=0 m:ytduniservoffering=1 m:ytdgreen=6 m:mtdticketcnt=5 m:mtdunigreendept=0 m:ytdgreenpct=35 m:mtdyellowpct=0 m:blank2=0 m:blank1=0 m:ytdavghours=160.7 m:ytdhourstotal=2731.72 m:ytdredpct=65 m:ytdyellow=0 m:mtdredpct=100 m:mtdavghours=195.8 m:nogreentks=0 m:noyellowtks=0 m:mtduniservoffering=1 m:ytdyellowpct=0 m:mtdhourstotal=978.92

series e:3wdb-kmn9 d:2016-06-27T00:00:00.000Z t:targetunit=Day t:serviceoffering="Networking - VPN Access for Vendor" m:mtdgreenpct=100 m:ytdticketcnt=24 m:ytdred=1 m:noredtks=0 m:ytdunigreendept=0 m:ytduniservoffering=1 m:ytdgreen=19 m:mtdticketcnt=2 m:mtdunigreendept=0 m:ytdgreenpct=79 m:mtdyellowpct=0 m:blank2=0 m:blank1=0 m:ytdavghours=29.6 m:ytdhourstotal=711.25 m:ytdredpct=4 m:ytdyellow=4 m:mtdredpct=0 m:mtdavghours=31.9 m:nogreentks=2 m:noyellowtks=0 m:mtduniservoffering=1 m:ytdyellowpct=17 m:mtdhourstotal=63.81
```

## Meta Commands

```ls
metric m:mtdticketcnt p:integer l:MTDTicketCnt t:dataTypeName=number

metric m:mtdunigreendept p:integer l:MTDUniGreenDept t:dataTypeName=number

metric m:mtdhourstotal p:float l:MTDHoursTotal t:dataTypeName=number

metric m:mtdavghours p:float l:MTDAvgHours t:dataTypeName=number

metric m:blank1 p:integer l:BLANK1 t:dataTypeName=number

metric m:nogreentks p:integer l:NoGreenTks t:dataTypeName=number

metric m:noyellowtks p:integer l:NoYellowTks t:dataTypeName=number

metric m:noredtks p:integer l:NoRedTks t:dataTypeName=number

metric m:mtdgreenpct p:integer l:MTDGreenPct t:dataTypeName=number

metric m:mtdyellowpct p:integer l:MTDYellowPct t:dataTypeName=number

metric m:mtdredpct p:integer l:MTDRedPct t:dataTypeName=number

metric m:ytdunigreendept p:integer l:YTDUniGreenDept t:dataTypeName=number

metric m:ytdhourstotal p:float l:YTDHoursTotal t:dataTypeName=number

metric m:ytdavghours p:float l:YTDAvgHours t:dataTypeName=number

metric m:blank2 p:integer l:BLANK2 t:dataTypeName=number

metric m:ytdticketcnt p:integer l:YTDTicketCnt t:dataTypeName=number

metric m:ytdgreen p:integer l:YTDGreen t:dataTypeName=number

metric m:ytdyellow p:integer l:YTDYellow t:dataTypeName=number

metric m:ytdred p:integer l:YTDRed t:dataTypeName=number

metric m:ytdgreenpct p:integer l:YTDGreenPct t:dataTypeName=number

metric m:ytdyellowpct p:integer l:YTDYellowPct t:dataTypeName=number

metric m:ytdredpct p:integer l:YTDRedPct t:dataTypeName=number

metric m:mtduniservoffering p:integer l:MTDUniServOffering t:dataTypeName=number

metric m:ytduniservoffering p:integer l:YTDUniServOffering t:dataTypeName=number

entity e:3wdb-kmn9 l:"Data Center Summary Extract Service Offering Disk" t:url=https://data.seattle.gov/api/views/3wdb-kmn9

property e:3wdb-kmn9 t:meta.view v:id=3wdb-kmn9 v:category="City Business" v:averageRating=0 v:name="Data Center Summary Extract Service Offering Disk"

property e:3wdb-kmn9 t:meta.view.license v:name="Public Domain"

property e:3wdb-kmn9 t:meta.view.owner v:id=quc8-ejr2 v:screenName="Morris, Dylan" v:displayName="Morris, Dylan"

property e:3wdb-kmn9 t:meta.view.tableauthor v:id=quc8-ejr2 v:screenName="Morris, Dylan" v:roleName=publisher v:displayName="Morris, Dylan"
```

## Top Records

```ls
| serviceoffering                                          | month               | mtdticketcnt | mtdunigreendept | mtdhourstotal | mtdavghours | blank1 | nogreentks | noyellowtks | noredtks | mtdgreenpct | mtdyellowpct | mtdredpct | ytdunigreendept | ytdhourstotal | ytdavghours | blank2 | ytdticketcnt | ytdgreen | ytdyellow | ytdred | ytdgreenpct | ytdyellowpct | ytdredpct | targetunit | mtduniservoffering | ytduniservoffering | endofmonth          | 
| ======================================================== | =================== | ============ | =============== | ============= | =========== | ====== | ========== | =========== | ======== | =========== | ============ | ========= | =============== | ============= | =========== | ====== | ============ | ======== | ========= | ====== | =========== | ============ | ========= | ========== | ================== | ================== | =================== | 
| Physical Hosting and Support - New Physical Server       | 2016-06-03T00:00:00 | 1            | 0               | 272.48        | 272.5       | 0      | 0          | 0           | 1        | 0           | 0            | 100       | 0               | 272.48        | 272.5       | 0      | 1            | 0        | 0         | 1      | 0           | 0            | 100       | Hour       | 1                  | 1                  | 2016-06-30T00:00:00 | 
| Virtual Hosting and Support - New Virtual Server         | 2016-06-22T00:00:00 | 5            | 0               | 978.92        | 195.8       | 0      | 0          | 0           | 5        | 0           | 0            | 100       | 0               | 2731.72       | 160.7       | 0      | 17           | 6        | 0         | 11     | 35          | 0            | 65        | Day        | 1                  | 1                  | 2016-06-30T00:00:00 | 
| Networking - VPN Access for Vendor                       | 2016-06-27T00:00:00 | 2            | 0               | 63.81         | 31.9        | 0      | 2          | 0           | 0        | 100         | 0            | 0         | 0               | 711.25        | 29.6        | 0      | 24           | 19       | 4         | 1      | 79          | 17           | 4         | Day        | 1                  | 1                  | 2016-06-30T00:00:00 | 
| Virtual Hosting and Support - New Virtual Server         | 2016-08-02T00:00:00 | 1            | 0               | 381           | 381         | 0      | 0          | 0           | 1        | 0           | 0            | 100       | 0               | 2731.72       | 160.7       | 0      | 17           | 6        | 0         | 11     | 35          | 0            | 65        | Day        | 1                  | 1                  | 2016-08-31T00:00:00 | 
| Facilities - Hardware Installation, Move or Decommission | 2016-05-17T00:00:00 | 1            | 0               | 1.24          | 1.2         | 0      | 1          | 0           | 0        | 100         | 0            | 0         | 0               | 1.24          | 1.2         | 0      | 1            | 1        | 0         | 0      | 100         | 0            | 0         | Day        | 1                  | 1                  | 2016-05-31T00:00:00 | 
| **NO MATCH**                                             | 2016-07-29T00:00:00 | 23           | 0               | 3483.04       | 151.4       | 0      | 0          | 0           | 0        | 0           | 0            | 0         | 0               | 3483.04       | 151.4       | 0      | 23           | 0        | 0         | 0      | 0           | 0            | 0         | **         | 1                  | 1                  | 2016-07-31T00:00:00 | 
| Virtual Hosting - Custom Sizing and Technical Consulting | 2016-04-05T00:00:00 | 1            | 0               | 186.24        | 186.2       | 0      | 0          | 0           | 1        | 0           | 0            | 100       | 0               | 4947.03       | 549.7       | 0      | 9            | 0        | 0         | 9      | 0           | 0            | 100       | Day        | 1                  | 1                  | 2016-04-30T00:00:00 | 
| Storage - New Storage                                    | 2016-06-06T00:00:00 | 4            | 0               | 314.09        | 78.5        | 0      | 0          | 0           | 4        | 0           | 0            | 100       | 0               | 314.09        | 78.5        | 0      | 4            | 0        | 0         | 4      | 0           | 0            | 100       | Day        | 1                  | 1                  | 2016-06-30T00:00:00 | 
| Networking - VPN Access for CoS Employee                 | 2016-03-31T00:00:00 | 44           | 1               | 547.26        | 12.4        | 0      | 37         | 3           | 4        | 84          | 7            | 9         | 1               | 3613.37       | 21.6        | 0      | 167          | 133      | 12        | 22     | 80          | 7            | 13        | Day        | 1                  | 1                  | 2016-03-31T00:00:00 | 
| Virtual Hosting and Support - New Virtual Server         | 2016-03-08T00:00:00 | 1            | 3               | 0.38          | 0.4         | 0      | 1          | 0           | 0        | 100         | 0            | 0         | 8               | 2731.72       | 160.7       | 0      | 17           | 6        | 0         | 11     | 35          | 0            | 65        | Day        | 1                  | 1                  | 2016-03-31T00:00:00 | 
```