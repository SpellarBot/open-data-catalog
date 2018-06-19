# School Allocation Memorandum (SAM)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/school-allocation-memorandum-sam-fy-2015) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/d6ee-k2sh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/d6ee-k2sh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/d6ee-k2sh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | d6ee-k2sh |
| Name | School Allocation Memorandum (SAM) |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | doe, sam |
| Created | 2016-07-12T16:50:53Z |
| Publication Date | 2017-02-03T17:29:10Z |

## Description

This data represents funding allocated to New York City public schools in the school year.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | numeric metric | sam         | SAM #       | number    | number      |
| Yes      | series tag     | sam_link    | SAM_LINK    | text      | text        |
| Yes      | series tag     | subcategory | Subcategory | text      | text        |
| Yes      | numeric metric | total       | Total       | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:d6ee-k2sh d:2016-07-12T09:50:56.000Z t:subcategory="Fair Student Funding FY15" t:sam_link="SAM 01: Fair Student Funding (FSF)" m:total=5101044441 m:sam=1

series e:d6ee-k2sh d:2016-07-12T09:50:56.000Z t:subcategory="Children First Funding Network FY15" t:sam_link="SAM 02: Children First Funding Network Support" m:total=79000000 m:sam=2

series e:d6ee-k2sh d:2016-07-12T09:50:56.000Z t:subcategory="Internally Restricted Funds FY15" t:sam_link="SAM 03: Network Support for Schools" m:total=58040157 m:sam=3
```

## Meta Commands

```ls
metric m:sam p:integer l:"SAM #" d:"The number of the school allocation memorandum" t:dataTypeName=number

metric m:total p:long l:Total d:"Aggregate amount of funding given to all schools" t:dataTypeName=number

entity e:d6ee-k2sh l:"School Allocation Memorandum (SAM)" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/d6ee-k2sh

property e:d6ee-k2sh t:meta.view v:id=d6ee-k2sh v:category=Education v:averageRating=0 v:name="School Allocation Memorandum (SAM)" v:attribution="Department of Education (DOE)"

property e:d6ee-k2sh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:d6ee-k2sh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | sam | sam_link                                                                  | subcategory                           | total         | 
| =========== | === | ========================================================================= | ===================================== | ============= | 
| 1468317056  | 1   | SAM 01: Fair Student Funding (FSF)                                        | Fair Student Funding FY15             | 5101044441.00 | 
| 1468317056  | 2   | SAM 02: Children First Funding Network Support                            | Children First Funding Network FY15   | 79000000.00   | 
| 1468317056  | 3   | SAM 03: Network Support for Schools                                       | Internally Restricted Funds FY15      | 58040157.00   | 
| 1468317056  | 4   | SAM 04: Fair Student Funding Legacy Teacher Supplement                    | Fair Student Funding FY15             | 15521352.00   | 
| 1468317056  | 5   | SAM 05: Contract for Excellence                                           | Externally Restricted Funds FY15      | 198181072.00  | 
| 1468317056  | 6   | SAM 06: Deferred Program Planning Initiative (DPPI)                       | Budget and Technical Adjustments FY15 | 43987777.00   | 
| 1468317056  | 7   | SAM 07: Summer School Program                                             | Internally Restricted Funds FY15      | 23632680.00   | 
| 1468317056  | 8   | SAM 08: Title I School Allocations                                        | Externally Restricted Funds FY15      | 551060908.00  | 
| 1468317056  | 9   | SAM 09: Parent Coordinator Allocation                                     | Internally Restricted Funds FY15      | 67228415.00   | 
| 1468317056  | 10  | SAM 10:New York State Textbook, Library, Software and Hardware Allocation | Externally Restricted Funds FY15      | 40906413.00   | 
```