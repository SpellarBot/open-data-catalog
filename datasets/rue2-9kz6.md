# Data Center Summary Extract Department Disk

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/data-center-summary-extract-department-disk) |
| Metadata | [Link](https://data.seattle.gov/api/views/rue2-9kz6) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/rue2-9kz6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/rue2-9kz6/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | rue2-9kz6 |
| Name | Data Center Summary Extract Department Disk |
| Category | City Business |
| Created | 2016-08-04T17:58:51Z |
| Publication Date | 2016-08-05T16:31:18Z |

## Description

Ticket data for IT Service Level Indicators (in reference to inter-department Service Level Agreements).

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | department         | Department         | text          | text          |
| Yes      | time           | month              | Month              | calendar_date | calendar_date |
| Yes      | numeric metric | mtdticketcnt       | MTDTicketCnt       | number        | number        |
| Yes      | numeric metric | mtdunigreendept    | MTDUniGreenDept    | number        | number        |
| Yes      | numeric metric | mtdhourstotal      | MTDHoursTotal      | number        | number        |
| Yes      | numeric metric | mtdgreenperc       | MTDGreenPerc       | number        | number        |
| Yes      | numeric metric | mtdlosperc         | MTDLoSPerc         | number        | number        |
| Yes      | numeric metric | nogreentks         | NoGreenTks         | number        | number        |
| Yes      | numeric metric | noyellowtks        | NoYellowTks        | number        | number        |
| Yes      | numeric metric | noredtks           | NoRedTks           | number        | number        |
| Yes      | numeric metric | mtdgreenpct        | MTDGreenPct        | number        | number        |
| Yes      | numeric metric | mtdyellowpct       | MTDYellowPct       | number        | number        |
| Yes      | numeric metric | mtdredpct          | MTDRedPct          | number        | number        |
| Yes      | numeric metric | ytdunigreendept    | YTDUniGreenDept    | number        | number        |
| Yes      | numeric metric | ytdhourstotal      | YTDHoursTotal      | number        | number        |
| Yes      | numeric metric | ytdgreenperc       | YTDGreenPerc       | number        | number        |
| Yes      | numeric metric | ytdlosperc         | YTDLoSPerc         | number        | number        |
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
series e:rue2-9kz6 d:2016-06-29T00:00:00.000Z t:targetunit=Day t:department="Networking - VPN Access for CoS Employee" m:mtdgreenpct=92 m:ytdticketcnt=167 m:ytdred=22 m:noredtks=2 m:ytdunigreendept=1 m:ytduniservoffering=1 m:ytdgreen=133 m:mtdticketcnt=39 m:mtdunigreendept=1 m:ytdgreenpct=80 m:ytdgreenperc=21.6 m:mtdyellowpct=3 m:mtdlosperc=0 m:mtdgreenperc=16.6 m:ytdhourstotal=3613.37 m:ytdredpct=13 m:ytdyellow=12 m:mtdredpct=5 m:nogreentks=36 m:noyellowtks=1 m:ytdlosperc=0 m:mtduniservoffering=1 m:ytdyellowpct=7 m:mtdhourstotal=647.6

series e:rue2-9kz6 d:2016-04-28T00:00:00.000Z t:targetunit=Day t:department="Networking - VPN Access for Vendor" m:mtdgreenpct=20 m:ytdticketcnt=24 m:ytdred=1 m:noredtks=1 m:ytdunigreendept=2 m:ytduniservoffering=1 m:ytdgreen=19 m:mtdticketcnt=5 m:mtdunigreendept=1 m:ytdgreenpct=79 m:ytdgreenperc=29.6 m:mtdyellowpct=60 m:mtdlosperc=0 m:mtdgreenperc=59.7 m:ytdhourstotal=711.25 m:ytdredpct=4 m:ytdyellow=4 m:mtdredpct=20 m:nogreentks=1 m:noyellowtks=3 m:ytdlosperc=0 m:mtduniservoffering=1 m:ytdyellowpct=17 m:mtdhourstotal=298.6

series e:rue2-9kz6 d:2016-04-25T00:00:00.000Z t:targetunit=Hour t:department="Storage - Storage Expansion" m:mtdgreenpct=100 m:ytdticketcnt=5 m:ytdred=1 m:noredtks=0 m:ytdunigreendept=4 m:ytduniservoffering=1 m:ytdgreen=4 m:mtdticketcnt=2 m:mtdunigreendept=2 m:ytdgreenpct=80 m:ytdgreenperc=2.3 m:mtdyellowpct=0 m:mtdlosperc=0 m:mtdgreenperc=1.5 m:ytdhourstotal=11.54 m:ytdredpct=20 m:ytdyellow=0 m:mtdredpct=0 m:nogreentks=2 m:noyellowtks=0 m:ytdlosperc=0 m:mtduniservoffering=1 m:ytdyellowpct=0 m:mtdhourstotal=3.02
```

## Meta Commands

```ls
metric m:mtdticketcnt p:integer l:MTDTicketCnt t:dataTypeName=number

metric m:mtdunigreendept p:integer l:MTDUniGreenDept t:dataTypeName=number

metric m:mtdhourstotal p:float l:MTDHoursTotal t:dataTypeName=number

metric m:mtdgreenperc p:float l:MTDGreenPerc t:dataTypeName=number

metric m:mtdlosperc p:integer l:MTDLoSPerc t:dataTypeName=number

metric m:nogreentks p:integer l:NoGreenTks t:dataTypeName=number

metric m:noyellowtks p:integer l:NoYellowTks t:dataTypeName=number

metric m:noredtks p:integer l:NoRedTks t:dataTypeName=number

metric m:mtdgreenpct p:integer l:MTDGreenPct t:dataTypeName=number

metric m:mtdyellowpct p:integer l:MTDYellowPct t:dataTypeName=number

metric m:mtdredpct p:integer l:MTDRedPct t:dataTypeName=number

metric m:ytdunigreendept p:integer l:YTDUniGreenDept t:dataTypeName=number

metric m:ytdhourstotal p:float l:YTDHoursTotal t:dataTypeName=number

metric m:ytdgreenperc p:float l:YTDGreenPerc t:dataTypeName=number

metric m:ytdlosperc p:integer l:YTDLoSPerc t:dataTypeName=number

metric m:ytdticketcnt p:integer l:YTDTicketCnt t:dataTypeName=number

metric m:ytdgreen p:integer l:YTDGreen t:dataTypeName=number

metric m:ytdyellow p:integer l:YTDYellow t:dataTypeName=number

metric m:ytdred p:integer l:YTDRed t:dataTypeName=number

metric m:ytdgreenpct p:integer l:YTDGreenPct t:dataTypeName=number

metric m:ytdyellowpct p:integer l:YTDYellowPct t:dataTypeName=number

metric m:ytdredpct p:integer l:YTDRedPct t:dataTypeName=number

metric m:mtduniservoffering p:integer l:MTDUniServOffering t:dataTypeName=number

metric m:ytduniservoffering p:integer l:YTDUniServOffering t:dataTypeName=number

entity e:rue2-9kz6 l:"Data Center Summary Extract Department Disk" t:url=https://data.seattle.gov/api/views/rue2-9kz6

property e:rue2-9kz6 t:meta.view v:id=rue2-9kz6 v:category="City Business" v:averageRating=0 v:name="Data Center Summary Extract Department Disk"

property e:rue2-9kz6 t:meta.view.license v:name="Public Domain"

property e:rue2-9kz6 t:meta.view.owner v:id=quc8-ejr2 v:screenName="Morris, Dylan" v:displayName="Morris, Dylan"

property e:rue2-9kz6 t:meta.view.tableauthor v:id=quc8-ejr2 v:screenName="Morris, Dylan" v:roleName=publisher v:displayName="Morris, Dylan"
```

## Top Records

```ls
| department                                               | month               | mtdticketcnt | mtdunigreendept | mtdhourstotal | mtdgreenperc | mtdlosperc | nogreentks | noyellowtks | noredtks | mtdgreenpct | mtdyellowpct | mtdredpct | ytdunigreendept | ytdhourstotal | ytdgreenperc | ytdlosperc | ytdticketcnt | ytdgreen | ytdyellow | ytdred | ytdgreenpct | ytdyellowpct | ytdredpct | targetunit | mtduniservoffering | ytduniservoffering | endofmonth          | 
| ======================================================== | =================== | ============ | =============== | ============= | ============ | ========== | ========== | =========== | ======== | =========== | ============ | ========= | =============== | ============= | ============ | ========== | ============ | ======== | ========= | ====== | =========== | ============ | ========= | ========== | ================== | ================== | =================== | 
| Networking - VPN Access for CoS Employee                 | 2016-06-29T00:00:00 | 39           | 1               | 647.6         | 16.6         | 0          | 36         | 1           | 2        | 92          | 3            | 5         | 1               | 3613.37       | 21.6         | 0          | 167          | 133      | 12        | 22     | 80          | 7            | 13        | Day        | 1                  | 1                  | 2016-06-30T00:00:00 | 
| Networking - VPN Access for Vendor                       | 2016-04-28T00:00:00 | 5            | 1               | 298.6         | 59.7         | 0          | 1          | 3           | 1        | 20          | 60           | 20        | 2               | 711.25        | 29.6         | 0          | 24           | 19       | 4         | 1      | 79          | 17           | 4         | Day        | 1                  | 1                  | 2016-04-30T00:00:00 | 
| Storage - Storage Expansion                              | 2016-04-25T00:00:00 | 2            | 2               | 3.02          | 1.5          | 0          | 2          | 0           | 0        | 100         | 0            | 0         | 4               | 11.54         | 2.3          | 0          | 5            | 4        | 0         | 1      | 80          | 0            | 20        | Hour       | 1                  | 1                  | 2016-04-30T00:00:00 | 
| Storage - New Storage                                    | 2016-06-06T00:00:00 | 4            | 0               | 314.09        | 78.5         | 0          | 0          | 0           | 4        | 0           | 0            | 100       | 0               | 314.09        | 78.5         | 0          | 4            | 0        | 0         | 4      | 0           | 0            | 100       | Day        | 1                  | 1                  | 2016-06-30T00:00:00 | 
| Networking - VPN Access for CoS Employee                 | 2016-05-26T00:00:00 | 27           | 1               | 990.3         | 36.7         | 0          | 18         | 1           | 8        | 67          | 4            | 30        | 1               | 3613.37       | 21.6         | 0          | 167          | 133      | 12        | 22     | 80          | 7            | 13        | Day        | 1                  | 1                  | 2016-05-31T00:00:00 | 
| Virtual Hosting - Custom Sizing and Technical Consulting | 2016-07-12T00:00:00 | 8            | 0               | 4760.8        | 595.1        | 0          | 0          | 0           | 8        | 0           | 0            | 100       | 0               | 4947.03       | 549.7        | 0          | 9            | 0        | 0         | 9      | 0           | 0            | 100       | Day        | 1                  | 1                  | 2016-07-31T00:00:00 | 
| Networking - VPN Site-to-Site Definition                 | 2016-06-13T00:00:00 | 2            | 0               | 20.17         | 10.1         | 0          | 1          | 0           | 1        | 50          | 0            | 50        | 0               | 50.47         | 16.8         | 0          | 3            | 1        | 0         | 2      | 33          | 0            | 67        | Day        | 1                  | 1                  | 2016-06-30T00:00:00 | 
| Networking - VPN Access for CoS Employee                 | 2016-04-28T00:00:00 | 23           | 0               | 476.61        | 20.7         | 0          | 12         | 7           | 4        | 52          | 30           | 17        | 0               | 3613.37       | 21.6         | 0          | 167          | 133      | 12        | 22     | 80          | 7            | 13        | Day        | 1                  | 1                  | 2016-04-30T00:00:00 | 
| Virtual Hosting and Support - New Virtual Server         | 2016-07-13T00:00:00 | 2            | 0               | 995.5         | 497.8        | 0          | 0          | 0           | 2        | 0           | 0            | 100       | 0               | 2731.72       | 160.7        | 0          | 17           | 6        | 0         | 11     | 35          | 0            | 65        | Day        | 1                  | 1                  | 2016-07-31T00:00:00 | 
| Networking - VPN Access for Vendor                       | 2016-08-04T00:00:00 | 1            | 1               | 7.89          | 7.9          | 0          | 1          | 0           | 0        | 100         | 0            | 0         | 4               | 711.25        | 29.6         | 0          | 24           | 19       | 4         | 1      | 79          | 17           | 4         | Day        | 1                  | 1                  | 2016-08-31T00:00:00 | 
```