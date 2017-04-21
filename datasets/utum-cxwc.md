# Incoming Calls for Driver Services Division at DMV

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/incoming-calls-for-driver-services-division-at-dmv) |
| Metadata | [Link](https://data.ct.gov/api/views/utum-cxwc) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/utum-cxwc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/utum-cxwc/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | utum-cxwc |
| Name | Incoming Calls for Driver Services Division at DMV |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv |
| Created | 2014-10-02T20:26:01Z |
| Publication Date | 2014-10-02T20:29:41Z |

## Description

Number of Incoming Calls for Driver Services from Jan to Aug 2014

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | month          | Month          | text      | text        |
| Yes      | numeric metric | incoming_calls | Incoming Calls | number    | number      |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Data Commands

```ls
series e:utum-cxwc d:2014-01-01T00:00:00.000Z m:incoming_calls=15842

series e:utum-cxwc d:2014-02-01T00:00:00.000Z m:incoming_calls=13095

series e:utum-cxwc d:2014-03-01T00:00:00.000Z m:incoming_calls=15813
```

## Meta Commands

```ls
metric m:incoming_calls p:integer l:"Incoming Calls" t:dataTypeName=number

entity e:utum-cxwc l:"Incoming Calls for Driver Services Division at DMV" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/utum-cxwc

property e:utum-cxwc t:meta.view v:id=utum-cxwc v:category=Transportation v:attributionLink=http://www.ct.gov/dmv v:averageRating=0 v:name="Incoming Calls for Driver Services Division at DMV" v:attribution="Department of Motor Vehicles"

property e:utum-cxwc t:meta.view.owner v:id=fd5k-6njr v:screenName=APatel v:displayName=APatel

property e:utum-cxwc t:meta.view.tableauthor v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```

## Top Records

```ls
| month  | incoming_calls | 
| ====== | ============== | 
| Jan-14 | 15842          | 
| Feb-14 | 13095          | 
| Mar-14 | 15813          | 
| Apr-14 | 13604          | 
| May-14 | 13260          | 
| Jun-14 | 13210          | 
| Jul-14 | 14553          | 
| Aug-14 | 13292          | 
```