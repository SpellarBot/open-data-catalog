# Energy Efficiency Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-efficiency-projects-95319) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/h3qk-ybvt) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/h3qk-ybvt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/h3qk-ybvt/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | h3qk-ybvt |
| Name | Energy Efficiency Projects |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | Environment |
| Tags | department of citywide administrative services, energy efficiency projects, dcas, sustainability, planyc, retrofit, efficient, emission, ghg, energy management, energy |
| Created | 2012-02-14T17:38:58Z |
| Publication Date | 2013-06-21T19:42:26Z |

## Description

The City?s Long-Term Sustainability Plan, PlaNYC, calls for City government to reduce greenhouse gas emissions produced by municipal operations 30% by 2017. A large part of this effort is retrofitting municipal buildings to become more energy efficient. This dataset lists energy efficiency projects at City buildings that are complete or in progress. Projects are listed by address, building name, and agency, and the dataset includes the estimated reduction in tons of GHG emissions associated with the project.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type | Render Type |
| ======== | ============== | ================== | ==================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | primaryprojecttype | PrimaryProjectType   | text      | text        |
| Yes      | series tag     | subtype            | SubType              | text      | text        |
| Yes      | series tag     | projectstatus      | ProjectStatus        | text      | text        |
| Yes      | series tag     | startdateactual    | StartDateActual      | text      | text        |
| Yes      | series tag     | finishdateactual   | FinishDateActual     | text      | text        |
| Yes      | series tag     | projectsitename    | ProjectSiteName      | text      | text        |
| No       |                | projectsiteaddress | ProjectSiteAddress   | text      | text        |
| Yes      | series tag     | acronym            | Acronym              | text      | text        |
| Yes      | numeric metric | co2e_mt_calculated | CO2e (MT) Calculated | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = projectsiteaddress
```

## Data Commands

```ls
series e:h3qk-ybvt d:2012-10-22T09:27:34.000Z t:primaryprojecttype="Lighting System Upgrade" t:startdateactual=09-Apr-12 t:acronym=BPL t:projectsitename="Leonard Branch Library" t:subtype=Retrofit t:finishdateactual=28-Sep-12 t:projectstatus=Completed m:co2e_mt_calculated=15.1

series e:h3qk-ybvt d:2012-10-22T09:27:34.000Z t:primaryprojecttype="Lighting System Upgrade" t:startdateactual=14-May-12 t:acronym=BPL t:projectsitename="Washington Irving Branch Library" t:subtype=Retrofit t:finishdateactual=28-Sep-12 t:projectstatus=Install m:co2e_mt_calculated=11.9

series e:h3qk-ybvt d:2012-10-22T09:27:34.000Z t:primaryprojecttype=Comprehensive t:acronym=BPL t:projectsitename="Brooklyn Heights Branch Library" t:subtype=Retrofit t:projectstatus=Cancelled m:co2e_mt_calculated=117.07
```

## Meta Commands

```ls
metric m:co2e_mt_calculated p:float l:"CO2e (MT) Calculated" t:dataTypeName=number

entity e:h3qk-ybvt l:"Energy Efficiency Projects" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/h3qk-ybvt

property e:h3qk-ybvt t:meta.view v:id=h3qk-ybvt v:category=Environment v:averageRating=0 v:name="Energy Efficiency Projects" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:h3qk-ybvt t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:h3qk-ybvt t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | primaryprojecttype      | subtype             | projectstatus | startdateactual | finishdateactual | projectsitename                                        | projectsiteaddress    | acronym | co2e_mt_calculated | 
| =========== | ======================= | =================== | ============= | =============== | ================ | ====================================================== | ===================== | ======= | ================== | 
| 1350898054  | HVAC System Upgrade     |                     | Completed     |                 |                  |                                                        |                       | BPL     |                    | 
| 1350898054  | Lighting System Upgrade | Retrofit            | Completed     | 09-Apr-12       | 28-Sep-12        | Leonard Branch Library                                 | 81 Devoe Street       | BPL     | 15.10              | 
| 1350898054  | Lighting System Upgrade | Retrofit            | Install       | 14-May-12       | 28-Sep-12        | Washington Irving Branch Library                       | 360 Irving Avenue     | BPL     | 11.90              | 
| 1350898054  | Comprehensive           | Retrofit            | Cancelled     |                 |                  | Brooklyn Heights Branch Library                        | 280 Cadman Plaza West | BPL     | 117.07             | 
| 1350898054  | Energy Audit            | None                | Completed     | 16-Mar-10       | 23-Aug-10        | Brooklyn Heights Branch Library                        | 286 Fulton Street     | BPL     | 135.53             | 
| 1350898054  | Other                   | Retro-commissioning | Proposed      |                 |                  | Brooklyn Heights Branch Library                        | 280 Cadman Plaza West | BPL     |                    | 
| 1350898054  | Other                   | Retro-commissioning | Survey        |                 |                  | Brooklyn Heights Branch Library                        | 280 Cadman Plaza West | BPL     |                    | 
| 1350898054  | HVAC System Upgrade     | Retrofit            | Design        |                 |                  | Kingsborough Community College                         | 2001 Oriental Blvd    | CUNY    | 1632.56            | 
| 1350898054  | HVAC System Upgrade     | Retrofit            | Install       |                 |                  | Queensborough Community College, Medical Arts Building | 222-05 56th Avenue    | CUNY    | 273.65             | 
| 1350898054  | Comprehensive           | Retrofit            | Design        |                 |                  | Kingsborough Community College, T-2 Building           | 2065 Oriental Blvd    | CUNY    | 43.32              | 
```