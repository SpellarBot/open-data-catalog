# Employee Travel Data (Non-Local)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-travel-data-non-local) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/kf2b-wnaq) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/kf2b-wnaq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/kf2b-wnaq/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | kf2b-wnaq |
| Name | Employee Travel Data (Non-Local) |
| Category | Government |
| Tags | county, employee travel, non local, approved cost, etravel |
| Created | 2015-10-13T21:30:42Z |
| Publication Date | 2016-02-10T16:09:34Z |

## Description

?This dataset provides information regarding the total approved actual expenses incurred by Montgomery County government employees traveling non-locally (over 75 miles from the County?s Executive Office Building at 101 Monroe St. Rockville, MD) for official business, beginning on or after August 12, 2015. The dataset includes the name of traveling employee; the employee?s home department; travel start and end dates; destination; purpose of travel; and actual total expenses funded by the County.  Update Frequency: Monthly

## Columns

```ls
| Included | Schema Type    | Field Name     | Name                  | Data Type | Render Type |
| ======== | ============== | ============== | ===================== | ========= | =========== |
| No       | time           | :updated_at    | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | department     | Department            | text      | text        |
| Yes      | series tag     | traveler_name  | Employee              | text      | text        |
| No       |                | departure_date | Travel Start Date     | text      | text        |
| No       |                | return_date    | Travel End Date       | text      | text        |
| Yes      | series tag     | destinations   | Destination(s)        | text      | text        |
| Yes      | series tag     | purpose        | Purpose Of Travel     | text      | text        |
| Yes      | numeric metric | total_cost     | Actual Total Expenses | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = departure_date,return_date
```

## Data Commands

```ls
series e:kf2b-wnaq d:2016-08-22T16:10:24.000Z t:destinations="Monroeville, PA" t:department=Police t:purpose=Other t:traveler_name="George Stephens" m:total_cost=491

series e:kf2b-wnaq d:2016-09-15T21:10:16.000Z t:destinations="West Hampton, NJ" t:department=Police t:purpose=Other t:traveler_name="Demond Johnson" m:total_cost=398

series e:kf2b-wnaq d:2016-09-15T21:10:16.000Z t:destinations="Salt Lake City, UT" t:department=Police t:purpose="Conference / Seminar attendee" t:traveler_name="Lea Ann Gross" m:total_cost=2171.26
```

## Meta Commands

```ls
metric m:total_cost p:float l:"Actual Total Expenses" d:"Total business travel cost funded by County" t:dataTypeName=number

entity e:kf2b-wnaq l:"Employee Travel Data (Non-Local)" t:url=https://data.montgomerycountymd.gov/api/views/kf2b-wnaq

property e:kf2b-wnaq t:meta.view v:id=kf2b-wnaq v:category=Government v:averageRating=0 v:name="Employee Travel Data (Non-Local)"

property e:kf2b-wnaq t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:kf2b-wnaq t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| :updated_at | department              | traveler_name   | departure_date | return_date | destinations        | purpose                              | total_cost | 
| =========== | ======================= | =============== | ============== | =========== | =================== | ==================================== | ========== | 
| 1471882224  | Police                  | George Stephens | 2016-03-08     | 2016-03-09  | Monroeville, PA     | Other                                | 491        | 
| 1473973816  | Police                  | Demond Johnson  | 2016-08-02     | 2016-08-03  | West Hampton, NJ    | Other                                | 398        | 
| 1473973816  | Police                  | Lea Ann Gross   | 2016-07-13     | 2016-07-17  | Salt Lake City, UT  | Conference / Seminar attendee        | 2171.26    | 
| 1482351012  | Police                  | Officer 007553  | 2016-01-01     | 2016-01-01  | City, ST            | Conference / Seminar attendee        | 1827.04    | 
| 1486669354  | Police                  | Holly Ryan      | 2016-07-25     | 2016-07-28  | Kansas City, MO     | Conference / Seminar attendee        | 982.82     | 
| 1486669354  | Police                  | Michael Parker  | 2016-07-25     | 2016-07-28  | Kansas City, MO     | Conference / Seminar attendee        | 1126.82    | 
| 1486669354  | Police                  | DAVID GILLESPIE | 2016-11-29     | 2016-12-01  | UNCASVILLE, CT      | Other                                | 1360.6     | 
| 1486669354  | Police                  | HEATHER MULLOY  | 2016-11-29     | 2016-12-01  | UNCASVILLE, CT      | Other                                | 1325.6     | 
| 1486669354  | Police                  | Officer 013645  | 2016-01-01     | 2016-01-01  | City, ST            | Other                                | 540.25     | 
| 1486669354  | Fire and Rescue Service | BENTLEY, JOHN   | 2016-12-05     | 2016-12-08  | VIRGINIA BEACH, VA. | Training / Licensing / Certification | 0          | 
```