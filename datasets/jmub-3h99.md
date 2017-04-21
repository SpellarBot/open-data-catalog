# Medical Examiner - Unclaimed Persons

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-examiner-unclaimed-persons) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/jmub-3h99) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jmub-3h99/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/jmub-3h99/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | jmub-3h99 |
| Name | Medical Examiner - Unclaimed Persons |
| Attribution | Cook County Medical Examiner |
| Created | 2016-06-23T15:36:05Z |
| Publication Date | 2017-04-14T21:12:24Z |

## Description

This dataset contains our most up to date list of Unclaimed Persons found in Cook County.

If you feel you are the next of kin to any of the individuals listed, Please contact Rebeca Perrone, Indigent Coordinator, at 312-997-4403. During regular business hours: Monday through Friday, 8:30 a.m. to 4:30 p.m.

Statement of Public Notice: Unclaimed indigents will be cremated or buried at County expense within 90 days of admission to our facility as dictated by the Cook County Medical Examiner Ordinance

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | case            | Case            | text          | text          |
| Yes      | series tag     | name            | Name            | text          | text          |
| Yes      | numeric metric | age_sex_race    | Age             | number        | text          |
| Yes      | series tag     | gender          | Gender          | text          | text          |
| Yes      | series tag     | race            | Race            | text          | text          |
| Yes      | time           | date_of_arrival | Date of Arrival | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_of_arrival
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jmub-3h99 d:2017-04-05T00:00:00.000Z t:name="KARL ANDERSON" t:gender=Male t:case=ST2017-00098 t:race=Black m:age_sex_race=51

series e:jmub-3h99 d:2017-04-05T00:00:00.000Z t:name="ROBERT KANE" t:gender=Male t:case=ST2017-00096 t:race=White m:age_sex_race=67

series e:jmub-3h99 d:2017-04-04T00:00:00.000Z t:name="JOHN NEELY" t:gender=Male t:case=ST2017-00094 t:race=Black m:age_sex_race=86
```

## Meta Commands

```ls
metric m:age_sex_race p:integer l:Age t:dataTypeName=number

entity e:jmub-3h99 l:"Medical Examiner - Unclaimed Persons" t:attribution="Cook County Medical Examiner" t:url=https://datacatalog.cookcountyil.gov/api/views/jmub-3h99

property e:jmub-3h99 t:meta.view v:id=jmub-3h99 v:averageRating=0 v:name="Medical Examiner - Unclaimed Persons" v:attribution="Cook County Medical Examiner"

property e:jmub-3h99 t:meta.view.license v:name="Public Domain"

property e:jmub-3h99 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:jmub-3h99 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| case         | name               | age_sex_race | gender | race  | date_of_arrival     | 
| ============ | ================== | ============ | ====== | ===== | =================== | 
| ST2017-00098 | KARL ANDERSON      | 51           | Male   | Black | 2017-04-05T00:00:00 | 
| ST2017-00096 | ROBERT KANE        | 67           | Male   | White | 2017-04-05T00:00:00 | 
| ST2017-00094 | JOHN NEELY         | 86           | Male   | Black | 2017-04-04T00:00:00 | 
| ST2017-00093 | WILFRED RIPPLER    | 78           | Male   | White | 2017-04-04T00:00:00 | 
| ST2017-00090 | PRESTON BALLARD JR | 75           | Male   | Black | 2017-04-04T00:00:00 | 
| ME2017-01675 | KAREN WINTERS      | 59           | Female | Black | 2017-04-09T00:00:00 | 
| ME2017-01609 | FRANK LEPISH       | 85           | Male   | White | 2017-04-06T00:00:00 | 
| ME2017-01579 | ERICK GILBERT      | 72           | Male   | White | 2017-04-04T00:00:00 | 
| ME2017-01577 | STEVEN WASZNIEWICZ | 47           | Male   | White | 2017-04-04T00:00:00 | 
| ME2017-01565 | CASSANDRA HUMPHREY | 56           | Female | Black | 2017-04-04T00:00:00 | 
```