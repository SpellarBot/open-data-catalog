# Council Members

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/council-members) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/uvw5-9znb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/uvw5-9znb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/uvw5-9znb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | uvw5-9znb |
| Name | Council Members |
| Attribution | City Council (NYCC) |
| Category | City Government |
| Tags | council members, city council, districts |
| Created | 2015-02-17T18:05:20Z |
| Publication Date | 2015-02-17T18:12:32Z |

## Description

This list contains information on Council Members

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | NAME            | text      | text        |
| Yes      | series tag  | district        | DISTRICT        | text      | number      |
| Yes      | series tag  | borough         | BOROUGH         | text      | text        |
| Yes      | series tag  | political_party | POLITICAL PARTY | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uvw5-9znb d:2015-02-17T10:05:22.000Z t:political_party=Democrat t:name="Maria del Carmen Arroyo" t:borough=Bronx t:district=17 m:row_number.uvw5-9znb=1

series e:uvw5-9znb d:2015-02-17T10:05:22.000Z t:political_party=Democrat t:name="Inez Barron" t:borough=Brooklyn t:district=42 m:row_number.uvw5-9znb=2

series e:uvw5-9znb d:2015-02-17T10:05:22.000Z t:political_party=Democrat t:name="Fernando Cabrera" t:borough=Bronx t:district=14 m:row_number.uvw5-9znb=3
```

## Meta Commands

```ls
metric m:row_number.uvw5-9znb p:long l:"Row Number"

entity e:uvw5-9znb l:"Council Members" t:attribution="City Council (NYCC)" t:url=https://data.cityofnewyork.us/api/views/uvw5-9znb

property e:uvw5-9znb t:meta.view v:id=uvw5-9znb v:category="City Government" v:averageRating=0 v:name="Council Members" v:attribution="City Council (NYCC)"

property e:uvw5-9znb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:uvw5-9znb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | name                    | district | borough   | political_party | 
| =========== | ======================= | ======== | ========= | =============== | 
| 1424167522  | Maria del Carmen Arroyo | 17       | Bronx     | Democrat        | 
| 1424167522  | Inez Barron             | 42       | Brooklyn  | Democrat        | 
| 1424167522  | Fernando Cabrera        | 14       | Bronx     | Democrat        | 
| 1424167522  | Margaret Chin           | 1        | Manhattan | Democrat        | 
| 1424167522  | Andrew Cohen            | 11       | Bronx     | Democrat        | 
| 1424167522  | Robert Cornegy          | 36       | Brooklyn  | Democrat        | 
| 1424167522  | Costa Constantinides    | 22       | Queens    | Democrat        | 
| 1424167522  | Elizabeth Crowley       | 30       | Queens    | Democrat        | 
| 1424167522  | Laurie Cumbo            | 35       | Brooklyn  | Democrat        | 
| 1424167522  | Chaim M. Deutsch        | 48       | Brooklyn  | Democrat        | 
```