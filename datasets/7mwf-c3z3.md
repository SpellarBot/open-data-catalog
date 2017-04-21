# Abandoned Vehicles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/abandoned-vehicles) |
| Metadata | [Link](https://data.honolulu.gov/api/views/7mwf-c3z3) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/7mwf-c3z3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/7mwf-c3z3/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | 7mwf-c3z3 |
| Name | Abandoned Vehicles |
| Category | Transportation |
| Created | 2015-03-17T20:05:44Z |
| Publication Date | 2015-03-17T20:08:20Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | streetnumber | StreetNumber | text          | text          |
| Yes      | series tag  | streetname   | StreetName   | text          | text          |
| Yes      | series tag  | vehiclemake  | VehicleMake  | text          | text          |
| Yes      | series tag  | vehicletype  | VehicleType  | text          | text          |
| Yes      | time        | entrydate    | EntryDate    | calendar_date | calendar_date |
| No       |             | closedate    | CloseDate    | calendar_date | calendar_date |
| Yes      | series tag  | status       | Status       | text          | text          |
| Yes      | series tag  | closereason  | CloseReason  | text          | text          |
```

## Time Field

```ls
Value = entrydate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = closedate
```

## Data Commands

```ls
series e:7mwf-c3z3 d:2017-04-19T00:00:00.000Z t:vehiclemake=HONDA t:status=CLOSE t:streetnumber=1*** t:closereason=CANCEL/DUPLICATE t:vehicletype=4DSD t:streetname="KOMO MAI DR" m:row_number.7mwf-c3z3=1

series e:7mwf-c3z3 d:2017-04-19T00:00:00.000Z t:vehiclemake=CHEVROLET t:status=CLOSE t:streetnumber=2*** t:closereason=CANCEL t:vehicletype=PKUP t:streetname="KILIHAU ST" m:row_number.7mwf-c3z3=2

series e:7mwf-c3z3 d:2017-04-18T00:00:00.000Z t:vehiclemake=HONDA t:status=CLOSE t:streetnumber=1*** t:closereason="NOT ON LOCATION" t:vehicletype=4DSD t:streetname="MAGAZINE ST" m:row_number.7mwf-c3z3=3
```

## Meta Commands

```ls
metric m:row_number.7mwf-c3z3 p:long l:"Row Number"

entity e:7mwf-c3z3 l:"Abandoned Vehicles" t:url=https://data.honolulu.gov/api/views/7mwf-c3z3

property e:7mwf-c3z3 t:meta.view v:id=7mwf-c3z3 v:category=Transportation v:averageRating=0 v:name="Abandoned Vehicles"

property e:7mwf-c3z3 t:meta.view.owner v:id=sr3i-nqxd v:screenName="Open Data" v:displayName="Open Data"

property e:7mwf-c3z3 t:meta.view.tableauthor v:id=sr3i-nqxd v:screenName="Open Data" v:roleName=administrator v:displayName="Open Data"
```

## Top Records

```ls
| streetnumber | streetname       | vehiclemake | vehicletype | entrydate           | closedate           | status | closereason      | 
| ============ | ================ | =========== | =========== | =================== | =================== | ====== | ================ | 
| 1***         | KOMO MAI DR      | HONDA       | 4DSD        | 2017-04-19T00:00:00 | 2017-04-19T00:00:00 | CLOSE  | CANCEL/DUPLICATE | 
| 2***         | KILIHAU ST       | CHEVROLET   | PKUP        | 2017-04-19T00:00:00 | 2017-04-19T00:00:00 | CLOSE  | CANCEL           | 
| 1***         | MAGAZINE ST      | HONDA       | 4DSD        | 2017-04-18T00:00:00 | 2017-04-19T00:00:00 | CLOSE  | NOT ON LOCATION  | 
| ***          | CAPTAIN COOK AVE | GMC         | PKUP        | 2017-04-18T00:00:00 | 2017-04-19T00:00:00 | CLOSE  | NOT ON LOCATION  | 
| ***          | ANAKUA ST        | CHEVROLET   | VAN         | 2017-04-18T00:00:00 | 2017-04-19T00:00:00 | CLOSE  | NOT ON LOCATION  | 
| 1***         | PALAMA ST        | LEXUS       | 4DSD        | 2017-04-18T00:00:00 | 2017-04-18T00:00:00 | CLOSE  | CANCEL/DUPLICATE | 
| 9***         | LEONUI ST        | NISSAN      | MPVH        | 2017-04-18T00:00:00 | 2017-04-19T00:00:00 | CLOSE  | CANCEL/DUPLICATE | 
| ***          | ALA NAPUAA PL    | HONDA       | 4DSD        | 2017-04-18T00:00:00 | 2017-04-19T00:00:00 | CLOSE  | CANCEL/DUPLICATE | 
| 5***         | KUKUNA RD        | CHEVROLET   | OTHER       | 2017-04-18T00:00:00 | 2017-04-19T00:00:00 | CLOSE  | NOT ON LOCATION  | 
| 6***         | KUPAHU ST        | ISUZU       | MPVH        | 2017-04-18T00:00:00 | 2017-04-18T00:00:00 | CLOSE  | CANCEL/DUPLICATE | 
```