# Neighborhood Boards

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/neighborhood-boards-0ffcb) |
| Metadata | [Link](https://data.honolulu.gov/api/views/3dxw-z8rr) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/3dxw-z8rr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/3dxw-z8rr/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | 3dxw-z8rr |
| Name | Neighborhood Boards |
| Category | Location |
| Created | 2012-06-23T02:34:25Z |
| Publication Date | 2012-06-23T02:34:46Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | numeric metric | number        | Number        | number    | number      |
| Yes      | series tag     | board         | Board         | text      | text        |
| Yes      | series tag     | dayofthemonth | DayOfTheMonth | text      | text        |
| Yes      | series tag     | locationname  | LocationName  | text      | text        |
| Yes      | series tag     | time          | Time          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3dxw-z8rr d:2012-06-22T19:34:30.000Z t:time="7:00 PM" t:dayofthemonth="2nd Thursday" t:locationname="Ala Wai Clubhouse, 2nd Floor" t:board="Diamond Head/Kapahulu/St. Louis Hts." m:number=5

series e:3dxw-z8rr d:2012-06-22T19:34:30.000Z t:time="7:00 PM" t:dayofthemonth="2nd Monday" t:locationname="Ma'ema'e Elementary School Cafeteria" t:board=Liliha/Kapalama m:number=14

series e:3dxw-z8rr d:2012-06-22T19:34:30.000Z t:time="7:00 PM" t:dayofthemonth="2nd Wednesday" t:locationname="KEY Project" t:board=Kahalu'u m:number=29
```

## Meta Commands

```ls
metric m:number p:integer l:Number t:dataTypeName=number

entity e:3dxw-z8rr l:"Neighborhood Boards" t:url=https://data.honolulu.gov/api/views/3dxw-z8rr

property e:3dxw-z8rr t:meta.view v:id=3dxw-z8rr v:category=Location v:averageRating=0 v:name="Neighborhood Boards"

property e:3dxw-z8rr t:meta.view.owner v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"

property e:3dxw-z8rr t:meta.view.tableauthor v:id=gcjf-354x v:screenName="Mick Thompson" v:displayName="Mick Thompson"
```

## Top Records

```ls
| :updated_at | number | board                                | dayofthemonth | locationname                         | time    | 
| =========== | ====== | ==================================== | ============= | ==================================== | ======= | 
| 1340393670  | 5      | Diamond Head/Kapahulu/St. Louis Hts. | 2nd Thursday  | Ala Wai Clubhouse, 2nd Floor         | 7:00 PM | 
| 1340393670  | 14     | Liliha/Kapalama                      | 2nd Monday    | Ma'ema'e Elementary School Cafeteria | 7:00 PM | 
| 1340393670  | 29     | Kahalu'u                             | 2nd Wednesday | KEY Project                          | 7:00 PM | 
| 1340393670  | 23     | Ewa                                  | 2nd Thursday  | Ewa Beach Public Library             | 7:00 PM | 
| 1340393670  | 21     | Pearl City                           | 4th Tuesday   | Waiau District Park                  | 7:00 PM | 
| 1340393670  | 9      | Waikiki                              | 2nd Tuesday   | Waikiki Community Center             | 7:00 PM | 
| 1340393670  | 35     | Mililani Mauka/Launani Valley        | 3rd Tuesday   | Mililani Mauka Elem. School          | 7:00 PM | 
| 1340393670  | 1      | Hawaii Kai                           | Last Tuesday  | Hahaione Elem. School                | 7:00 PM | 
| 1340393670  | 6      | Palolo                               | 2nd Wednesday | Palolo Elem School Cafeteria         | 7:00 PM | 
| 1340393670  | 15     | Kalihi-Palama                        | 3rd Wednesday | Kalihi Union Church                  | 7:00 PM | 
```