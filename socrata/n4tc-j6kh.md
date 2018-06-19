# Inspections Requested

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inspections-requested) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/n4tc-j6kh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/n4tc-j6kh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/n4tc-j6kh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | n4tc-j6kh |
| Name | Inspections Requested |
| Attribution | School Construction Authority (SCA) |
| Category | Education |
| Created | 2015-08-12T13:45:30Z |
| Publication Date | 2017-04-03T21:24:48Z |

## Description

List of Inspections requested for construction projects

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | =========== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag  | school_code                | School Code                | text          | text          |
| Yes      | series tag  | borough_name               | Borough Name               | text          | text          |
| Yes      | series tag  | dob                        | DOB#                       | text          | text          |
| Yes      | series tag  | inspection_category        | Inspection Category        | text          | text          |
| Yes      | time        | inspection_date            | Inspection Date            | calendar_date | calendar_date |
| No       |             | date_requested             | Date Requested             | calendar_date | calendar_date |
| Yes      | series tag  | request_status_description | Request Status Description | text          | text          |
```

## Time Field

```ls
Value = inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_requested
```

## Data Commands

```ls
series e:n4tc-j6kh d:2017-03-27T15:30:00.000Z t:inspection_category=PLUMBING t:request_status_description=COMPLETED t:dob=500871746 t:borough_name="STATEN ISLAND" t:school_code=HS047R m:row_number.n4tc-j6kh=1

series e:n4tc-j6kh d:2017-03-03T15:00:00.000Z t:inspection_category=MASONRY t:request_status_description=COMPLETED t:dob=402899333 t:borough_name=QUEENS t:school_code=HS265Q m:row_number.n4tc-j6kh=2

series e:n4tc-j6kh d:2017-03-16T15:00:00.000Z t:inspection_category=MASONRY t:request_status_description=COMPLETED t:dob=402899333 t:borough_name=QUEENS t:school_code=HS265Q m:row_number.n4tc-j6kh=3
```

## Meta Commands

```ls
metric m:row_number.n4tc-j6kh p:long l:"Row Number"

entity e:n4tc-j6kh l:"Inspections Requested" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/n4tc-j6kh

property e:n4tc-j6kh t:meta.view v:id=n4tc-j6kh v:category=Education v:averageRating=0 v:name="Inspections Requested" v:attribution="School Construction Authority (SCA)"

property e:n4tc-j6kh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:n4tc-j6kh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| school_code | borough_name  | dob       | inspection_category | inspection_date     | date_requested      | request_status_description | 
| =========== | ============= | ========= | =================== | =================== | =================== | ========================== | 
| HS047R      | STATEN ISLAND | 500871746 | PLUMBING            | 2017-03-27T15:30:00 | 2017-03-24T09:40:12 | COMPLETED                  | 
| HS265Q      | QUEENS        | 402899333 | MASONRY             | 2017-03-03T15:00:00 | 2017-02-24T13:25:41 | COMPLETED                  | 
| HS265Q      | QUEENS        | 402899333 | MASONRY             | 2017-03-16T15:00:00 | 2017-02-24T13:30:26 | COMPLETED                  | 
| HS265Q      | QUEENS        | 402899333 | MASONRY             | 2017-03-30T15:00:00 | 2017-02-24T13:32:39 | COMPLETED                  | 
| HS268X      | BRONX         | 201196188 | ARCHITECTURAL       | 2017-03-22T11:00:00 | 2017-02-23T14:14:37 | COMPLETED                  | 
| HS268X      | BRONX         | 201196188 | POWERANDLIGHTING    | 2017-03-06T09:00:00 | 2017-02-23T14:16:17 | COMPLETED                  | 
| HS282Q      | QUEENS        | 402887569 | PLUMBING            | 2017-03-30T10:00:00 | 2017-03-22T12:56:45 | COMPLETED                  | 
| HS288M      | MANHATTAN     | 103644521 | LOWVOLTAGE          | 2017-03-01T18:00:00 | 2017-02-21T07:39:00 | COMPLETED                  | 
| HS288M      | MANHATTAN     | 103645511 | ARCHITECTURAL       | 2017-03-03T14:00:00 | 2017-02-14T10:44:48 | COMPLETED                  | 
| HS288M      | MANHATTAN     | 103645511 | ARCHITECTURAL       | 2017-03-10T14:00:00 | 2017-02-14T10:45:32 | COMPLETED                  | 
```