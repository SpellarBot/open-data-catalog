# Call Center Incoming call Volume at DMV

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/call-center-incoming-call-volume-at-dmv) |
| Metadata | [Link](https://data.ct.gov/api/views/v6s7-qsw3) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/v6s7-qsw3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/v6s7-qsw3/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | v6s7-qsw3 |
| Name | Call Center Incoming call Volume at DMV |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv |
| Created | 2014-10-03T12:24:34Z |
| Publication Date | 2014-10-03T12:31:15Z |

## Description

Number of Incoming Calls at Call Center

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | year           | Year           | number    | number      |
| Yes      | series tag     | months_of_2014 | Months of 2014 | text      | text        |
| Yes      | numeric metric | incoming_calls | Incoming Calls | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:v6s7-qsw3 d:2014-01-01T00:00:00.000Z t:months_of_2014=JAN m:incoming_calls=33631

series e:v6s7-qsw3 d:2014-01-01T00:00:00.000Z t:months_of_2014=FEB m:incoming_calls=26364

series e:v6s7-qsw3 d:2014-01-01T00:00:00.000Z t:months_of_2014=MAR m:incoming_calls=33917
```

## Meta Commands

```ls
metric m:incoming_calls p:integer l:"Incoming Calls" t:dataTypeName=number

entity e:v6s7-qsw3 l:"Call Center Incoming call Volume at DMV" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/v6s7-qsw3

property e:v6s7-qsw3 t:meta.view v:id=v6s7-qsw3 v:category=Transportation v:attributionLink=http://www.ct.gov/dmv v:averageRating=0 v:name="Call Center Incoming call Volume at DMV" v:attribution="Department of Motor Vehicles"

property e:v6s7-qsw3 t:meta.view.owner v:id=fd5k-6njr v:screenName=APatel v:displayName=APatel

property e:v6s7-qsw3 t:meta.view.tableauthor v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```

## Top Records

```ls
| year | months_of_2014 | incoming_calls | 
| ==== | ============== | ============== | 
| 2014 | JAN            | 33631          | 
| 2014 | FEB            | 26364          | 
| 2014 | MAR            | 33917          | 
| 2014 | APR            | 35703          | 
| 2014 | MAY            | 33422          | 
| 2014 | JUN            | 38545          | 
| 2014 | JUL            | 45150          | 
| 2014 | AUG            | 39006          | 
```