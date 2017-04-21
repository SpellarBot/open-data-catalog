# FDNY Vital Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-vital-statistics-db36e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qg7h-jiy8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qg7h-jiy8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qg7h-jiy8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qg7h-jiy8 |
| Name | FDNY Vital Statistics |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, safety, fire safety, fdny vital statistics |
| Created | 2013-01-31T20:38:54Z |
| Publication Date | 2013-02-04T19:29:18Z |

## Description

FDNY Vital Statistics

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | year                          | Year                          | number    | text        |
| Yes      | series tag     | vital_statistic_name          | Vital Statistic Name          | text      | text        |
| Yes      | numeric metric | vtail_statistic_value         | Vtail Statistic Value         | money     | text        |
| Yes      | series tag     | vital_statist_unit_of_measure | Vital Statist Unit of Measure | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qg7h-jiy8 d:2012-01-01T00:00:00.000Z t:vital_statist_unit_of_measure="sq. miles" t:vital_statistic_name="NYC Land Area:" m:vtail_statistic_value=322

series e:qg7h-jiy8 d:2012-01-01T00:00:00.000Z t:vital_statist_unit_of_measure=Count t:vital_statistic_name=Population: m:vtail_statistic_value=8175133

series e:qg7h-jiy8 d:2012-01-01T00:00:00.000Z t:vital_statist_unit_of_measure=Count t:vital_statistic_name="Fire Houses:" m:vtail_statistic_value=218
```

## Meta Commands

```ls
metric m:vtail_statistic_value p:long l:"Vtail Statistic Value" t:dataTypeName=money

entity e:qg7h-jiy8 l:"FDNY Vital Statistics" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/qg7h-jiy8

property e:qg7h-jiy8 t:meta.view v:id=qg7h-jiy8 v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/fdny/pdf/vital_stats_2012.pdf v:averageRating=0 v:name="FDNY Vital Statistics" v:attribution="Fire Department of New York City (FDNY)"

property e:qg7h-jiy8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qg7h-jiy8 t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| year | vital_statistic_name                                               | vtail_statistic_value | vital_statist_unit_of_measure | 
| ==== | ================================================================== | ===================== | ============================= | 
| 2012 | NYC Land Area:                                                     | 322                   | sq. miles                     | 
| 2012 | Population:                                                        | 8,175,133             | Count                         | 
| 2012 | Fire Houses:                                                       | 218                   | Count                         | 
| 2012 | Personnel--Uniformed Fire:                                         | 10,227                | Count                         | 
| 2012 | EMS Stations:                                                      | 33                    | Count                         | 
| 2012 | Personnel--Uniformed EMS:                                          | 3,492                 | Count                         | 
| 2012 | Personnel-- Civilian:                                              | 1,649                 | Count                         | 
| 2012 | Average Citywide Response Times Structural Fires                   | 4:01                  | Minutes:Seconds               | 
| 2012 | Average Citywide Response Times Medical Emergencies (Fire)         | 4:11                  | Minutes:Seconds               | 
| 2012 | Average Citywide Response Times Cardiac Arrest /Choke (Fire & EMS) | 4:02                  | Minutes:Seconds               | 
```