# Data Center Details Extract

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/data-center-details-extract) |
| Metadata | [Link](https://data.seattle.gov/api/views/i9zm-ri3m) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/i9zm-ri3m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/i9zm-ri3m/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | i9zm-ri3m |
| Name | Data Center Details Extract |
| Category | City Business |
| Created | 2016-08-04T17:56:24Z |
| Publication Date | 2016-08-04T18:01:29Z |

## Description

Ticket data for IT Service Level Indicators (in reference to inter-department Service Level Agreements).

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | status             | Status             | text          | text          |
| Yes      | series tag     | serviceoffering    | ServiceOffering    | text          | text          |
| Yes      | time           | recvddate          | RecvdDate          | calendar_date | calendar_date |
| Yes      | series tag     | recvdtime          | RecvdTime          | text          | text          |
| No       |                | dateresolv         | DateResolv         | calendar_date | calendar_date |
| Yes      | series tag     | timeresolv         | TimeResolv         | text          | text          |
| Yes      | numeric metric | actualhrs          | ActualHrs          | number        | number        |
| Yes      | numeric metric | targethours        | TargetHours        | number        | number        |
| Yes      | series tag     | department         | Department         | text          | text          |
| Yes      | series tag     | ticketnumber       | TicketNumber       | text          | number        |
| Yes      | numeric metric | nogreentks         | NoGreenTks         | number        | number        |
| Yes      | numeric metric | noyellowtks        | NoYellowTks        | number        | number        |
| Yes      | numeric metric | noredtks           | NoRedTks           | number        | number        |
| Yes      | series tag     | htcodesat          | HTCodesAT          | text          | text          |
| Yes      | numeric metric | maxhrsgreen        | MaxHrsGreen        | number        | number        |
| Yes      | numeric metric | minhrsyellow       | MinHrsYellow       | number        | number        |
| Yes      | numeric metric | minhrsred          | MinHrsRed          | number        | number        |
| Yes      | series tag     | targetunit         | TargetUnit         | text          | text          |
| Yes      | numeric metric | servofferingcntmtd | ServOfferingCntMTD | number        | number        |
| Yes      | numeric metric | servofferingcntytd | ServOfferingCntYTD | number        | number        |
| Yes      | series tag     | requester          | Requester          | text          | text          |
| No       |                | endofmth           | EndOfMth           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = recvddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = dateresolv,endofmth
```

## Data Commands

```ls
series e:i9zm-ri3m d:2016-03-15T00:00:00.000Z t:requester=BATRESE t:timeresolv=11:09:51 t:htcodesat=DCNW_Consulting t:targetunit=Day t:status=Red t:department="Executive Departments" t:recvdtime=16:02:00 t:serviceoffering="Networking - Internal Network Consulting/Update" t:ticketnumber=1608595 m:actualhrs=317.13 m:servofferingcntmtd=1 m:minhrsred=120 m:noredtks=1 m:servofferingcntytd=1 m:maxhrsgreen=0 m:nogreentks=0 m:targethours=128 m:noyellowtks=0 m:minhrsyellow=0

series e:i9zm-ri3m d:2016-03-02T00:00:00.000Z t:requester=MIRANDW t:timeresolv=11:51:39 t:htcodesat=DCSD_NewVPN t:targetunit=Day t:status=Green t:department="Executive Administration Department" t:recvdtime=16:35:35 t:serviceoffering="Networking - VPN Access for CoS Employee" t:ticketnumber=1602975 m:actualhrs=5.27 m:servofferingcntmtd=1 m:minhrsred=0 m:noredtks=0 m:servofferingcntytd=1 m:maxhrsgreen=24 m:nogreentks=1 m:targethours=24 m:noyellowtks=0 m:minhrsyellow=0

series e:i9zm-ri3m d:2016-03-28T00:00:00.000Z t:requester=BRUSKLA t:timeresolv=18:08:48 t:htcodesat=DCVH_NewVMachin t:targetunit=Day t:status=Green t:department="City Light" t:recvdtime=17:25:00 t:serviceoffering="Virtual Hosting - New Virtual Server" t:ticketnumber=1614071 m:actualhrs=0.73 m:servofferingcntmtd=1 m:minhrsred=0 m:noredtks=0 m:servofferingcntytd=1 m:maxhrsgreen=40 m:nogreentks=1 m:targethours=40 m:noyellowtks=0 m:minhrsyellow=0
```

## Meta Commands

```ls
metric m:actualhrs p:float l:ActualHrs t:dataTypeName=number

metric m:targethours p:integer l:TargetHours t:dataTypeName=number

metric m:nogreentks p:integer l:NoGreenTks t:dataTypeName=number

metric m:noyellowtks p:integer l:NoYellowTks t:dataTypeName=number

metric m:noredtks p:integer l:NoRedTks t:dataTypeName=number

metric m:maxhrsgreen p:integer l:MaxHrsGreen t:dataTypeName=number

metric m:minhrsyellow p:integer l:MinHrsYellow t:dataTypeName=number

metric m:minhrsred p:integer l:MinHrsRed t:dataTypeName=number

metric m:servofferingcntmtd p:integer l:ServOfferingCntMTD t:dataTypeName=number

metric m:servofferingcntytd p:integer l:ServOfferingCntYTD t:dataTypeName=number

entity e:i9zm-ri3m l:"Data Center Details Extract" t:url=https://data.seattle.gov/api/views/i9zm-ri3m

property e:i9zm-ri3m t:meta.view v:id=i9zm-ri3m v:category="City Business" v:averageRating=0 v:name="Data Center Details Extract"

property e:i9zm-ri3m t:meta.view.license v:name="Public Domain"

property e:i9zm-ri3m t:meta.view.owner v:id=quc8-ejr2 v:screenName="Morris, Dylan" v:displayName="Morris, Dylan"

property e:i9zm-ri3m t:meta.view.tableauthor v:id=quc8-ejr2 v:screenName="Morris, Dylan" v:roleName=publisher v:displayName="Morris, Dylan"
```

## Top Records

```ls
| status | serviceoffering                                                      | recvddate           | recvdtime | dateresolv          | timeresolv | actualhrs | targethours | department                          | ticketnumber | nogreentks | noyellowtks | noredtks | htcodesat        | maxhrsgreen | minhrsyellow | minhrsred | targetunit | servofferingcntmtd | servofferingcntytd | requester | endofmth            | 
| ====== | ==================================================================== | =================== | ========= | =================== | ========== | ========= | =========== | =================================== | ============ | ========== | =========== | ======== | ================ | =========== | ============ | ========= | ========== | ================== | ================== | ========= | =================== | 
| Red    | Networking - Internal Network Consulting/Update                      | 2016-03-15T00:00:00 | 16:02:00  | 2016-05-10T00:00:00 | 11:09:51   | 317.13    | 128         | Executive Departments               | 1608595      | 0          | 0           | 1        | DCNW_Consulting  | 0           | 0            | 120       | Day        | 1                  | 1                  | BATRESE   | 2016-05-31T00:00:00 | 
| Green  | Networking - VPN Access for CoS Employee                             | 2016-03-02T00:00:00 | 16:35:35  | 2016-03-03T00:00:00 | 11:51:39   | 5.27      | 24          | Executive Administration Department | 1602975      | 1          | 0           | 0        | DCSD_NewVPN      | 24          | 0            | 0         | Day        | 1                  | 1                  | MIRANDW   | 2016-03-31T00:00:00 | 
| Green  | Virtual Hosting - New Virtual Server                                 | 2016-03-28T00:00:00 | 17:25:00  | 2016-03-28T00:00:00 | 18:08:48   | 0.73      | 40          | City Light                          | 1614071      | 1          | 0           | 0        | DCVH_NewVMachin  | 40          | 0            | 0         | Day        | 1                  | 1                  | BRUSKLA   | 2016-03-31T00:00:00 | 
| Green  | Networking - VPN Access for CoS Employee                             | 2016-04-18T00:00:00 | 23:41:00  | 2016-04-19T00:00:00 | 10:04:12   | 3.07      | 24          | City Employees Retirement Syst      | 1623570      | 1          | 0           | 0        | DCSD_NewVPN      | 24          | 0            | 0         | Day        | 2                  | 5                  | TOLENTJ   | 2016-04-30T00:00:00 | 
| Green  | Virtual Hosting and Support - Custom Sizing and Technical Consulting | 2016-04-08T00:00:00 | 13:54:00  | 2016-04-12T00:00:00 | 13:29:20   | 25.59     | 80          | Information Technology Department   | 1619450      | 1          | 0           | 0        | DCVHS_Consulting | 80          | 0            | 0         | Day        | 2                  | 2                  | BRADSHS   | 2016-04-30T00:00:00 | 
| Green  | Virtual Hosting and Support - Custom Sizing and Technical Consulting | 2016-04-08T00:00:00 | 14:17:00  | 2016-04-12T00:00:00 | 13:30:49   | 25.23     | 80          | Information Technology Department   | 1619473      | 1          | 0           | 0        | DCVHS_Consulting | 80          | 0            | 0         | Day        | 2                  | 2                  | BRADSHS   | 2016-04-30T00:00:00 | 
| Green  | Virtual Hosting and Support - New Virtual Server                     | 2016-04-14T00:00:00 | 15:10:00  | 2016-04-14T00:00:00 | 17:49:48   | 2.66      | 40          | Seattle Center                      | 1622259      | 1          | 0           | 0        | DCVHS_NewVMachin | 40          | 0            | 0         | Day        | 1                  | 1                  | BELLE     | 2016-04-30T00:00:00 | 
| Green  | Networking - VPN Access for CoS Employee                             | 2016-05-06T00:00:00 | 14:02:00  | 2016-05-09T00:00:00 | 15:32:56   | 11.52     | 24          | City Employees Retirement Syst      | 1631651      | 1          | 0           | 0        | DCSD_NewVPN      | 24          | 0            | 0         | Day        | 3                  | 5                  | NAKATSK   | 2016-05-31T00:00:00 | 
| Red    | Storage - New Storage                                                | 2016-05-10T00:00:00 | 16:14:00  | 2016-06-07T00:00:00 | 14:58:35   | 152.74    | 8           | Law Department                      | 1632989      | 0          | 0           | 1        | DCSTO_NewStorage | 0           | 0            | 12        | Day        | 1                  | 1                  | MOKSIVA   | 2016-06-30T00:00:00 | 
| Red    | Storage - New Storage                                                | 2016-05-26T00:00:00 | 10:33:00  | 2016-06-06T00:00:00 | 14:22:08   | 53.82     | 8           | Information Technology Department   | 1639680      | 0          | 0           | 1        | DCSTO_NewStorage | 0           | 0            | 12        | Day        | 3                  | 3                  | JOYCET    | 2016-06-30T00:00:00 | 
```