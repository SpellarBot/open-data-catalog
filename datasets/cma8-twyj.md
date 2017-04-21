# City Public Parking Stalls

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-public-parking-stalls) |
| Metadata | [Link](https://data.honolulu.gov/api/views/cma8-twyj) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/cma8-twyj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/cma8-twyj/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | cma8-twyj |
| Name | City Public Parking Stalls |
| Category | Transportation |
| Created | 2015-05-23T01:56:23Z |
| Publication Date | 2015-05-23T01:58:14Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | location      | LOCATION      | text      | text        |
| Yes      | numeric metric | quantity      | Quantity      | number    | number      |
| Yes      | series tag     | meter_numbers | METER NUMBERS | text      | text        |
| Yes      | numeric metric | rate_hr       | RATE/HR       | money     | money       |
| Yes      | series tag     | timelimit     | TIMELIMIT     | text      | text        |
| Yes      | series tag     | type          | TYPE          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cma8-twyj d:2015-05-22T18:56:26.000Z t:location="Aala Place" t:timelimit="2 HRS" t:meter_numbers=1175-1185 t:type=On-street m:quantity=12 m:rate_hr=0.75

series e:cma8-twyj d:2015-05-22T18:56:26.000Z t:location="Aala St." t:timelimit="2 HRS" t:meter_numbers=1101-1173 t:type=On-street m:quantity=73 m:rate_hr=0.75

series e:cma8-twyj d:2015-05-22T18:56:26.000Z t:location="Alakea St." t:timelimit="1 HR" t:meter_numbers=401-404 t:type=On-street m:quantity=4 m:rate_hr=1.5
```

## Meta Commands

```ls
metric m:quantity p:integer l:Quantity t:dataTypeName=number

metric m:rate_hr p:double l:RATE/HR t:dataTypeName=money

entity e:cma8-twyj l:"City Public Parking Stalls" t:url=https://data.honolulu.gov/api/views/cma8-twyj

property e:cma8-twyj t:meta.view v:id=cma8-twyj v:category=Transportation v:averageRating=0 v:name="City Public Parking Stalls"

property e:cma8-twyj t:meta.view.owner v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:displayName="Karl Sueyoshi"

property e:cma8-twyj t:meta.view.tableauthor v:id=b4zr-4dtj v:screenName="Karl Sueyoshi" v:roleName=administrator v:displayName="Karl Sueyoshi"
```

## Top Records

```ls
| :updated_at | location    | quantity | meter_numbers | rate_hr | timelimit | type      | 
| =========== | =========== | ======== | ============= | ======= | ========= | ========= | 
| 1432320986  | Aala Place  | 12       | 1175-1185     | 0.75    | 2 HRS     | On-street | 
| 1432320986  | Aala St.    | 73       | 1101-1173     | 0.75    | 2 HRS     | On-street | 
| 1432320986  | Alakea St.  | 4        | 401-404       | 1.50    | 1 HR      | On-street | 
| 1432320986  | Alapai St.  | 16       | 2127-2142     | 0.75    | 2 HRS     | On-street | 
| 1432320986  | Aloha Drive | 19       | 4601-4620     | 1.50    | 2 HRS     | On-street | 
| 1432320986  | Auahi St.   | 45       | 3600-3644     | 1.50    | 2 HRS     | On-street | 
| 1432320986  | Beachwalk   | 6        | 4461-4468     | 1.50    | 2 HRS     | On-street | 
| 1432320986  | Bethel St.  | 19       | 1670-1688     | 1.50    | 1 HR      | On-street | 
| 1432320986  | Bishop St.  | 14       | 1631-1644     | 1.50    | 1 HR      | On-street | 
| 1432320986  | Fort St.    | 18       | 1600-1617     | 1.50    | 1 HR      | On-street | 
```