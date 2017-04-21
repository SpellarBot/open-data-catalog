# Air Quality

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/air-quality-ef520) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/c3uy-2p5r) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/c3uy-2p5r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/c3uy-2p5r/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | c3uy-2p5r |
| Name | Air Quality |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Environment |
| Tags | air quality, surveillance, health, dohmh |
| Created | 2014-10-24T00:53:47Z |
| Publication Date | 2014-10-24T00:55:18Z |

## Description

Dataset contains information on New York City air quality surveillance data

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | indicator_data_id | indicator_data_id | text      | number      |
| Yes      | series tag     | indicator_id      | indicator_id      | text      | number      |
| Yes      | series tag     | name              | name              | text      | text        |
| Yes      | series tag     | measure           | Measure           | text      | text        |
| Yes      | series tag     | geo_type_name     | geo_type_name     | text      | text        |
| Yes      | series tag     | geo_entity_id     | geo_entity_id     | text      | number      |
| Yes      | series tag     | geo_entity_name   | geo_entity_name   | text      | text        |
| Yes      | series tag     | year_description  | year_description  | text      | text        |
| Yes      | numeric metric | data_valuemessage | data_valuemessage | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:c3uy-2p5r d:2014-10-23T17:53:50.000Z t:geo_entity_id=1 t:measure="Average Concentration" t:indicator_data_id=130728 t:geo_type_name=Borough t:name="Air Toxics Concentrations- Average Benzene Concentrations" t:indicator_id=646 t:year_description=2005 t:geo_entity_name=Bronx m:data_valuemessage=2.8

series e:c3uy-2p5r d:2014-10-23T17:53:50.000Z t:geo_entity_id=2 t:measure="Average Concentration" t:indicator_data_id=130729 t:geo_type_name=Borough t:name="Air Toxics Concentrations- Average Benzene Concentrations" t:indicator_id=646 t:year_description=2005 t:geo_entity_name=Brooklyn m:data_valuemessage=2.8

series e:c3uy-2p5r d:2014-10-23T17:53:50.000Z t:geo_entity_id=3 t:measure="Average Concentration" t:indicator_data_id=130730 t:geo_type_name=Borough t:name="Air Toxics Concentrations- Average Benzene Concentrations" t:indicator_id=646 t:year_description=2005 t:geo_entity_name=Manhattan m:data_valuemessage=4.7
```

## Meta Commands

```ls
metric m:data_valuemessage p:double l:data_valuemessage t:dataTypeName=number

entity e:c3uy-2p5r l:"Air Quality" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/c3uy-2p5r

property e:c3uy-2p5r t:meta.view v:id=c3uy-2p5r v:category=Environment v:averageRating=0 v:name="Air Quality" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:c3uy-2p5r t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:c3uy-2p5r t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | indicator_data_id | indicator_id | name                                                      | measure               | geo_type_name | geo_entity_id | geo_entity_name         | year_description | data_valuemessage | 
| =========== | ================= | ============ | ========================================================= | ===================== | ============= | ============= | ======================= | ================ | ================= | 
| 1414086830  | 130728            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | Borough       | 1             | Bronx                   | 2005             | 2.8               | 
| 1414086830  | 130729            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | Borough       | 2             | Brooklyn                | 2005             | 2.8               | 
| 1414086830  | 130730            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | Borough       | 3             | Manhattan               | 2005             | 4.7               | 
| 1414086830  | 130731            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | Borough       | 4             | Queens                  | 2005             | 1.9               | 
| 1414086830  | 130732            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | Borough       | 5             | Staten Island           | 2005             | 1.6               | 
| 1414086830  | 130727            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | Citywide      | 1             | New York City           | 2005             | 2.9               | 
| 1414086830  | 130685            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | UHF42         | 101           | Kingsbridge - Riverdale | 2005             | 2.9               | 
| 1414086830  | 130686            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | UHF42         | 102           | Northeast Bronx         | 2005             | 2.8               | 
| 1414086830  | 130687            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | UHF42         | 103           | Fordham - Bronx Pk      | 2005             | 2.7               | 
| 1414086830  | 130688            | 646          | Air Toxics Concentrations- Average Benzene Concentrations | Average Concentration | UHF42         | 104           | Pelham - Throgs Neck    | 2005             | 2.7               | 
```