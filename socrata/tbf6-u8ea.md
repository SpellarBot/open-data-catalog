# HRA Domestic Violence Partners

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hra-domestic-violence-partners-ed33a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/tbf6-u8ea) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/tbf6-u8ea/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/tbf6-u8ea/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | tbf6-u8ea |
| Name | HRA Domestic Violence Partners |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | hra domestic violence partners, jobs and economic mobility |
| Created | 2013-03-26T16:48:11Z |
| Publication Date | 2013-03-26T16:55:05Z |

## Description

Listing of domestic violence non-residential services. Phone numbers and the borough where service is provided is included.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | provider    | Provider   | text      | text        |
| Yes      | series tag  | hotline     | Hotline #  | text      | text        |
| Yes      | series tag  | borough     | Borough    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tbf6-u8ea d:2013-03-26T09:48:12.000Z t:hotline=212-533-4358 t:borough=All t:provider="Barrier Free Living" m:row_number.tbf6-u8ea=1

series e:tbf6-u8ea d:2013-03-26T09:48:12.000Z t:hotline=718-922-7980 t:borough=Brooklyn t:provider="HELP R.O.A.D.S" m:row_number.tbf6-u8ea=2

series e:tbf6-u8ea d:2013-03-26T09:48:12.000Z t:hotline=718-367-0605 t:borough=Bronx t:provider="JBFCS Bronx DV Programs" m:row_number.tbf6-u8ea=3
```

## Meta Commands

```ls
metric m:row_number.tbf6-u8ea p:long l:"Row Number"

entity e:tbf6-u8ea l:"HRA Domestic Violence Partners" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/tbf6-u8ea

property e:tbf6-u8ea t:meta.view v:id=tbf6-u8ea v:category="Social Services" v:averageRating=0 v:name="HRA Domestic Violence Partners" v:attribution="Human Resources Administration (HRA)"

property e:tbf6-u8ea t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:tbf6-u8ea t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | provider                                   | hotline                    | borough           | 
| =========== | ========================================== | ========================== | ================= | 
| 1364291292  | Barrier Free Living                        | 212-533-4358               | All               | 
| 1364291292  | HELP R.O.A.D.S                             | 718-922-7980               | Brooklyn          | 
| 1364291292  | JBFCS Bronx DV Programs                    | 718-367-0605               | Bronx             | 
| 1364291292  | New York Asian Women's Center              | 212- 732-5230 888-888-7702 | Queens & Brooklyn | 
| 1364291292  | FEGS Center for Women & Families           | 888-242-5838               | Manhanttan        | 
| 1364291292  | NYC Gay & Lesbian Anti-Violence Project    | 212-714-1141               | All               | 
| 1364291292  | Queens Legal Services Corporatino          | 718-657-0424               | Queens            | 
| 1364291292  | Safe Horizon                               | 718-889-1233               | Queens            | 
| 1364291292  | Sanctuary for Families                     | 718-993-5990               | Bronx             | 
| 1364291292  | Seamen's Society for Children and Families | 888-837-6687 ext.4792      | Staten Island     | 
```