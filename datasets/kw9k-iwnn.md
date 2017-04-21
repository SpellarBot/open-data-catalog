# MO State Park Bison Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mo-state-park-bison-locations-91ced) |
| Metadata | [Link](https://data.mo.gov/api/views/kw9k-iwnn) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/kw9k-iwnn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/kw9k-iwnn/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | kw9k-iwnn |
| Name | MO State Park Bison Locations |
| Category | Conservation |
| Tags | bison, buffalo |
| Created | 2014-09-25T13:39:25Z |
| Publication Date | 2014-09-26T13:00:56Z |

## Description

This dataset is composed of the latitude and longitude coordinates for the three bison located at MO State Park.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | recordid          | RecordID          | text          | text          |
| Yes      | numeric metric | gpsfixunixtimecst | GPSFixUnixTimeCST | number        | text          |
| Yes      | numeric metric | esn               | ESN               | number        | text          |
| Yes      | series tag     | name              | Name              | text          | text          |
| Yes      | time           | gpsfixdatetime    | GPSFixDateTime    | calendar_date | calendar_date |
| Yes      | series tag     | moving            | Moving            | text          | text          |
```

## Time Field

```ls
Value = gpsfixdatetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:kw9k-iwnn d:2014-09-21T08:01:00.000Z t:moving=Y t:name="Miller Bison 1" t:recordid=921992-1411305776 m:gpsfixunixtimecst=1411304479 m:esn=921992

series e:kw9k-iwnn d:2014-09-21T11:00:00.000Z t:moving=Y t:name="Miller Bison 1" t:recordid=921992-1411316536 m:gpsfixunixtimecst=1411315239 m:esn=921992

series e:kw9k-iwnn d:2014-09-21T12:30:00.000Z t:moving=N t:name="Miller Bison 1" t:recordid=921992-1411320662 m:gpsfixunixtimecst=1411320640 m:esn=921992
```

## Meta Commands

```ls
metric m:gpsfixunixtimecst p:integer l:GPSFixUnixTimeCST d:"Time that the GPS fix was made as unix timestamp in CST tmezone" t:dataTypeName=number

metric m:esn p:integer l:ESN t:dataTypeName=number

entity e:kw9k-iwnn l:"MO State Park Bison Locations" t:url=https://data.mo.gov/api/views/kw9k-iwnn

property e:kw9k-iwnn t:meta.view v:id=kw9k-iwnn v:category=Conservation v:averageRating=0 v:name="MO State Park Bison Locations"

property e:kw9k-iwnn t:meta.view.owner v:id=xfqs-bcyn v:screenName=whitwo v:displayName=whitwo

property e:kw9k-iwnn t:meta.view.tableauthor v:id=xfqs-bcyn v:screenName=whitwo v:roleName=editor v:displayName=whitwo
```

## Top Records

```ls
| recordid          | gpsfixunixtimecst | esn    | name           | gpsfixdatetime      | moving | 
| ================= | ================= | ====== | ============== | =================== | ====== | 
| 921992-1411305776 | 1411304479        | 921992 | Miller Bison 1 | 2014-09-21T08:01:00 | Y      | 
| 921992-1411316536 | 1411315239        | 921992 | Miller Bison 1 | 2014-09-21T11:00:00 | Y      | 
| 921992-1411320662 | 1411320640        | 921992 | Miller Bison 1 | 2014-09-21T12:30:00 | N      | 
| 921816-1411320663 | 1411320641        | 921816 | Miller Bison 2 | 2014-09-21T12:30:00 | N      | 
| 921992-1411326565 | 1411326040        | 921992 | Miller Bison 1 | 2014-09-21T14:00:00 | Y      | 
| 921992-1411332737 | 1411331440        | 921992 | Miller Bison 1 | 2014-09-21T15:30:00 | Y      | 
| 921816-1411332259 | 1411331441        | 921816 | Miller Bison 2 | 2014-09-21T15:30:00 | Y      | 
| 921992-1411338136 | 1411336839        | 921992 | Miller Bison 1 | 2014-09-21T17:00:00 | N      | 
| 921816-1411337303 | 1411336841        | 921816 | Miller Bison 2 | 2014-09-21T17:00:00 | N      | 
| 921816-1411602257 | 1411601462        | 921816 | Miller Bison 2 | 2014-09-24T18:31:00 | N      | 
```