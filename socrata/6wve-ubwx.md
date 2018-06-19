# Hi- Caps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hi-caps-559a9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/6wve-ubwx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/6wve-ubwx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/6wve-ubwx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 6wve-ubwx |
| Name | Hi- Caps |
| Attribution | Department of Information Technology & Telecommunications (DoITT) |
| Category | City Government |
| Tags | hi- caps, doitt, telecommunications, department of information technology & telecommunications (doitt) |
| Created | 2014-03-06T05:56:11Z |
| Publication Date | 2014-03-06T05:57:23Z |

## Description

Data on DoITT's high-capacity/telecommunications services franchise agreements

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | metric            | Metric            | text      | text        |
| Yes      | numeric metric | cablevision       | Cablevision       | percent   | percent     |
| No       |                | time_warner_cable | Time Warner Cable | percent   | percent     |
| Yes      | numeric metric | verizon_fios      | Verizon FIOS      | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = time_warner_cable
```

## Data Commands

```ls
series e:6wve-ubwx d:2014-03-05T21:56:14.000Z t:metric="Pctg of calls answered by voice response units (""VRU"")" m:verizon_fios=99.96 m:cablevision=99.8

series e:6wve-ubwx d:2014-03-05T21:56:14.000Z t:metric="Pctg of Calls abandoned by VRU" m:verizon_fios=4.8 m:cablevision=4.5

series e:6wve-ubwx d:2014-03-05T21:56:14.000Z t:metric="Percntage of busy Calls by VRU" m:verizon_fios=0.04 m:cablevision=0.2
```

## Meta Commands

```ls
metric m:cablevision p:float l:Cablevision t:dataTypeName=percent

metric m:verizon_fios p:float l:"Verizon FIOS" t:dataTypeName=percent

entity e:6wve-ubwx l:"Hi- Caps" t:attribution="Department of Information Technology & Telecommunications (DoITT)" t:url=https://data.cityofnewyork.us/api/views/6wve-ubwx

property e:6wve-ubwx t:meta.view v:id=6wve-ubwx v:category="City Government" v:averageRating=0 v:name="Hi- Caps" v:attribution="Department of Information Technology & Telecommunications (DoITT)"

property e:6wve-ubwx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:6wve-ubwx t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | metric                                                  | cablevision | time_warner_cable | verizon_fios | 
| =========== | ======================================================= | =========== | ================= | ============ | 
| 1394056574  |  Pctg of calls answered by voice response units ("VRU") | 99.80       | 98.90             | 99.96        | 
| 1394056574  |  Pctg of Calls abandoned by VRU                         | 4.50        | 12.60             | 4.80         | 
| 1394056574  | Percntage of busy Calls by VRU                          | 0.20        | 1.10              | 0.04         | 
```