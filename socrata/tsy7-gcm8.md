# Court Liaison Contact Sheet

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/court-liaison-contact-sheet-96a23) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tsy7-gcm8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tsy7-gcm8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tsy7-gcm8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tsy7-gcm8 |
| Name | Court Liaison Contact Sheet |
| Attribution | Department of Education (DOE) |
| Category | Social Services |
| Tags | court liaison contact sheet, doe, education court, jobs and economic mobility |
| Created | 2013-03-19T20:34:30Z |
| Publication Date | 2013-03-19T20:37:10Z |

## Description

Listing of NYC courts and their liaisons.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | region      | Region     | text      | text        |
| No       |             | address     | Address    | text      | text        |
| Yes      | series tag  | city        | City       | text      | text        |
| Yes      | series tag  | state       | State      | text      | text        |
| Yes      | series tag  | zip_code    | Zip Code   | text      | number      |
| Yes      | series tag  | contact     | Contact    | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
| Yes      | series tag  | email       | Email      | text      | text        |
| Yes      | series tag  | notes       | Notes      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:tsy7-gcm8 d:2013-03-19T13:34:32.000Z t:region="Bronx Family Court" t:phone=718-681-5999 t:zip_code=10451 t:email=dricetarrant@schools.nyc.gov t:state="New York" t:notes=Room6B19 t:contact="Deborah Rice-Tarrant" t:city=Bronx m:row_number.tsy7-gcm8=1

series e:tsy7-gcm8 d:2013-03-19T13:34:32.000Z t:region="Brooklyn Criminal Court" t:phone=347-404-9561 t:zip_code=11201 t:email=kharty@schools.nyc.gov t:state="New York" t:notes="Room 811" t:contact="Kristen Murphy" t:city=Brooklyn m:row_number.tsy7-gcm8=2

series e:tsy7-gcm8 d:2013-03-19T13:34:32.000Z t:region="Brooklyn Family Court" t:phone=718-802-2622 t:zip_code=11201 t:email=spowell112@schools.nyc.gov t:state="New York" t:notes="11th floor, cubicle #55" t:contact="Shah Noralez" t:city=Brooklyn m:row_number.tsy7-gcm8=3
```

## Meta Commands

```ls
metric m:row_number.tsy7-gcm8 p:long l:"Row Number"

entity e:tsy7-gcm8 l:"Court Liaison Contact Sheet" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/tsy7-gcm8

property e:tsy7-gcm8 t:meta.view v:id=tsy7-gcm8 v:category="Social Services" v:averageRating=0 v:name="Court Liaison Contact Sheet" v:attribution="Department of Education (DOE)"

property e:tsy7-gcm8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tsy7-gcm8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | region                  | address                 | city        | state    | zip_code | contact              | phone        | email                        | notes                   | 
| =========== | ======================= | ======================= | =========== | ======== | ======== | ==================== | ============ | ============================ | ======================= | 
| 1363700072  | Bronx Family Court      | 900 Sheridan Avenue     | Bronx       | New York | 10451    | Deborah Rice-Tarrant | 718-681-5999 | dricetarrant@schools.nyc.gov | Room6B19                | 
| 1363700072  | Brooklyn Criminal Court | 120 Schermerhorn Street | Brooklyn    | New York | 11201    | Kristen Murphy       | 347-404-9561 | kharty@schools.nyc.gov       | Room 811                | 
| 1363700072  | Brooklyn Family Court   | 330 Jay Street          | Brooklyn    | New York | 11201    | Shah Noralez         | 718-802-2622 | spowell112@schools.nyc.gov   | 11th floor, cubicle #55 | 
| 1363700072  | Manhattan Family Court  | 60 Lafayette Street     | New York    | New York | 10013    | Michelle Augustine   | 212-442-8548 | aaugustine3@schools.nyc.gov  | Room 3C7                | 
| 1363700072  | Queens Family Court     | 151-20 Jamaica Avenue   | Queens      | New York | 11432    | Cathy Sevos          | 718-291-8613 | csevos@schools.nyc.gov       | Lower Level, Room B103  | 
| 1363700072  | Queens Supreme Court    | 125-01 Queens Blvd      | Kew Gardens | New York | 11415    | Pat Faraglia         | 718-298-1379 | PFaraglia@schools.nyc.gov    | Room 322.02 Annex       | 
```