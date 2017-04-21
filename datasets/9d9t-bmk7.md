# Directory Of Job Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-job-centers-c22f5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9d9t-bmk7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9d9t-bmk7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9d9t-bmk7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9d9t-bmk7 |
| Name | Directory Of Job Centers |
| Attribution | Human Resources Administration (HRA) |
| Category | Business |
| Tags | hra, human resources, jobs, economic mobility, jobs and economic mobility |
| Created | 2013-03-25T17:37:15Z |
| Publication Date | 2013-06-21T19:31:30Z |

## Description

List of Job Centers that offer temporary financial assistance, food stamps and Medicaid to eligible individuals

## Columns

```ls
| Included | Schema Type | Field Name     | Name            | Data Type | Render Type |
| ======== | =========== | ============== | =============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | borough        | Borough         | text      | text        |
| Yes      | series tag  | facility_name  | Facility Name   | text      | text        |
| Yes      | series tag  | street_address | Street Address  | text      | text        |
| Yes      | series tag  | city           | City            | text      | text        |
| Yes      | series tag  | state          | State           | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code        | text      | text        |
| Yes      | series tag  | phone_number_s | Phone Number(s) | text      | text        |
| Yes      | series tag  | comments       | Comments        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9d9t-bmk7 d:2013-03-25T10:37:17.000Z t:phone_number_s=718-742-3811/718-742-3924 t:zip_code=10451 t:facility_name=Rider t:state=NY t:borough=Bronx t:street_address="305 Rider Avenue" t:comments="Applicants / participants must enter the building at 300 Canal Place." t:city=Bronx m:row_number.9d9t-bmk7=1

series e:9d9t-bmk7 d:2013-03-25T10:37:17.000Z t:phone_number_s=718-901-0201/718-901-5596 t:zip_code=10457 t:facility_name=Crotona t:state=NY t:borough=Bronx t:street_address="1910 Monterey Avenue" t:city=Bronx m:row_number.9d9t-bmk7=2

series e:9d9t-bmk7 d:2013-03-25T10:37:17.000Z t:phone_number_s=718-664-2143/718-664-1140 t:zip_code=10451 t:facility_name=Melrose t:state=NY t:borough=Bronx t:street_address="260 East 161st Street" t:city=Bronx m:row_number.9d9t-bmk7=3
```

## Meta Commands

```ls
metric m:row_number.9d9t-bmk7 p:long l:"Row Number"

entity e:9d9t-bmk7 l:"Directory Of Job Centers" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/9d9t-bmk7

property e:9d9t-bmk7 t:meta.view v:id=9d9t-bmk7 v:category=Business v:attributionLink=http://www.nyc.gov/html/hra/html/directory/job_centers.shtml v:averageRating=0 v:name="Directory Of Job Centers" v:attribution="Human Resources Administration (HRA)"

property e:9d9t-bmk7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9d9t-bmk7 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | borough  | facility_name               | street_address            | city     | state | zip_code | phone_number_s            | comments                                                                                                                                                                                 | 
| =========== | ======== | =========================== | ========================= | ======== | ===== | ======== | ========================= | ======================================================================================================================================================================================== | 
| 1364207837  | Bronx    | Rider                       | 305 Rider Avenue          | Bronx    | NY    | 10451    | 718-742-3811/718-742-3924 | Applicants / participants must enter the building at 300 Canal Place.                                                                                                                    | 
| 1364207837  | Bronx    | Crotona                     | 1910 Monterey Avenue      | Bronx    | NY    | 10457    | 718-901-0201/718-901-5596 |                                                                                                                                                                                          | 
| 1364207837  | Bronx    | Melrose                     | 260 East 161st Street     | Bronx    | NY    | 10451    | 718-664-2143/718-664-1140 |                                                                                                                                                                                          | 
| 1364207837  | Bronx    | Fordham                     | 2541-2549 Bainbridge Ave. | Bronx    | NY    | 10458    | 718-220-6622/718-220-7012 |                                                                                                                                                                                          | 
| 1364207837  | Bronx    | Family Services Call Center | 260 East 161st Street     | Bronx    | NY    | 10451    | 718-664-1056/718-883-8296 | Primarily handles face to face recertifications and emergency walk-in activities for the Family Call Center's active child only cases whose payees are not in receipt of cash assistance | 
| 1364207837  | Brooklyn | Veterans' Service Center    | 25 Chapel Street          | Brooklyn | NY    | 11201    | 718-473-8313/718-222-2430 | Primarily services cash assistance recipient cases in which at least one household member is a Veteran.                                                                                  | 
| 1364207837  | Brooklyn | Coney Island                | 3050 West 21st Street     | Brooklyn | NY    | 11224    | 718-333-3100/718-333-3014 | Telephone line is temporary out of order due to hurricane Sandy. At this time a temporary phone number has been establish for Coney Island (718) 637-2554.                               | 
| 1364207837  | Brooklyn | Dekalb                      | 500 Dekalb Avenue         | Brooklyn | NY    | 11205    | 718-636-2626/718-636-2495 |                                                                                                                                                                                          | 
| 1364207837  | Brooklyn | Bushwick                    | 30 Thornton Street        | Brooklyn | NY    | 11206    | 718-963-5120/718-963-5117 |                                                                                                                                                                                          | 
| 1364207837  | Brooklyn | Clinton Hill Center #67     | 495 Clermont Ave          | Brooklyn | NY    | 11238    | 929-221-0922/929-221-2809 |                                                                                                                                                                                          | 
```