# Directory Of Land Use Application Fees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-land-use-application-fees-49ed2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fdx7-6jsr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fdx7-6jsr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fdx7-6jsr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fdx7-6jsr |
| Name | Directory Of Land Use Application Fees |
| Attribution | Department of City Planning (DCP) |
| Category | Housing & Development |
| Tags | dcp, city, planning, land use, fees |
| Created | 2013-02-19T22:12:35Z |
| Publication Date | 2013-06-21T20:51:23Z |

## Description

Details about various fees associated with Land Use

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | application_type | Application Type | text      | text        |
| Yes      | series tag     | land_use_detail  | Land Use Detail  | text      | text        |
| Yes      | numeric metric | amount           | Amount           | money     | money       |
| Yes      | series tag     | comments         | Comments         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fdx7-6jsr d:2013-02-19T14:12:37.000Z t:land_use_detail="Less than 10,000 square feet" t:application_type="Special Permit" t:comments="The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement" m:amount=2040

series e:fdx7-6jsr d:2013-02-19T14:12:37.000Z t:land_use_detail="10,000 to 19,999 square feet" t:application_type="Special Permit" t:comments="The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement" m:amount=3100

series e:fdx7-6jsr d:2013-02-19T14:12:37.000Z t:land_use_detail="20,000 to 39,999 square feet" t:application_type="Special Permit" t:comments="The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement" m:amount=4080
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:fdx7-6jsr l:"Directory Of Land Use Application Fees" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/fdx7-6jsr

property e:fdx7-6jsr t:meta.view v:id=fdx7-6jsr v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dcp/html/luproc/ulurpfee.shtml v:averageRating=0 v:name="Directory Of Land Use Application Fees" v:attribution="Department of City Planning (DCP)"

property e:fdx7-6jsr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fdx7-6jsr t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | application_type     | land_use_detail                | amount | comments                                                                                                         | 
| =========== | ==================== | ============================== | ====== | ================================================================================================================ | 
| 1361283157  | Special Permit       | Less than 10,000 square feet   | 2040   | The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement | 
| 1361283157  | Special Permit       | 10,000 to 19,999 square feet   | 3100   | The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement | 
| 1361283157  | Special Permit       | 20,000 to 39,999 square feet   | 4080   | The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement | 
| 1361283157  | Special Permit       | 40,000 to 69,999 square feet   | 5215   | The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement | 
| 1361283157  | Special Permit       | 70,000 to 99,999 square feet   | 6125   | The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement | 
| 1361283157  | Special Permit       | 100,000 to 239,999 square feet | 6805   | The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement | 
| 1361283157  | Special Permit       | 240,000 to 500,000 square feet | 17765  | The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement | 
| 1361283157  | Special Permit       | over 500,000 square feet       | 29485  | The amount of floor area shall be calculated based upon the floor area for the entire development or enlargement | 
| 1361283157  | Zoning Map Amendment | Less than 10,000 square feet   | 2190   | The area of all zoning lots in the area to be rezoned                                                            | 
| 1361283157  | Zoning Map Amendment | 10,000 to 19,999 square feet   | 3250   | The area of all zoning lots in the area to be rezoned                                                            | 
```