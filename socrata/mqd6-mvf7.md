# Incident based distribution of ReadyNY guides

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/incident-based-distribution-of-readyny-guides-9f52e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mqd6-mvf7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mqd6-mvf7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mqd6-mvf7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mqd6-mvf7 |
| Name | Incident based distribution of ReadyNY guides |
| Attribution | Office of Emergency Management (OEM) |
| Category | Public Safety |
| Tags | incident based distribution of readyny guides, emergency, oem, awareness, pamphlet |
| Created | 2014-05-05T17:00:51Z |
| Publication Date | 2016-08-01T17:00:07Z |

## Description

Areas targeted for ReadyNY guide distribution following a nearby incident, such as a large fire or water main break

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | time           | date_of_occurrence | Date of Occurrence | calendar_date | calendar_date |
| Yes      | series tag     | incident_type      | Incident Type      | text          | text          |
| Yes      | series tag     | street             | Street             | text          | text          |
| Yes      | series tag     | city               | City               | text          | text          |
| Yes      | series tag     | zip_code           | Zip Code           | text          | number        |
| Yes      | series tag     | guide_type         | Guide Type         | text          | text          |
| Yes      | numeric metric | amount_sent        | Amount Sent        | number        | number        |
```

## Time Field

```ls
Value = date_of_occurrence
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mqd6-mvf7 d:2016-04-03T00:00:00.000Z t:incident_type="Fire - 5 Alarm" t:guide_type=IBD-FIRE t:zip_code=11101 t:street="38-68 13 St" t:city=Queens m:amount_sent=2934

series e:mqd6-mvf7 d:2016-04-04T00:00:00.000Z t:incident_type="Fire - 5 Alarm" t:guide_type=IBD-FIRE t:zip_code=11226 t:street="640 Parkside Avenue" t:city=Brooklyn m:amount_sent=4253

series e:mqd6-mvf7 d:2016-03-31T00:00:00.000Z t:incident_type="Fire - 3 Alarm" t:guide_type=IBD-FIRE t:street=NA t:city=NA m:amount_sent=4567
```

## Meta Commands

```ls
metric m:amount_sent p:integer l:"Amount Sent" t:dataTypeName=number

entity e:mqd6-mvf7 l:"Incident based distribution of ReadyNY guides" t:attribution="Office of Emergency Management (OEM)" t:url=https://data.cityofnewyork.us/api/views/mqd6-mvf7

property e:mqd6-mvf7 t:meta.view v:id=mqd6-mvf7 v:category="Public Safety" v:averageRating=0 v:name="Incident based distribution of ReadyNY guides" v:attribution="Office of Emergency Management (OEM)"

property e:mqd6-mvf7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mqd6-mvf7 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| date_of_occurrence  | incident_type  | street                                      | city          | zip_code | guide_type    | amount_sent | 
| =================== | ============== | =========================================== | ============= | ======== | ============= | =========== | 
| 2016-04-03T00:00:00 | Fire - 5 Alarm | 38-68 13 St                                 | Queens        | 11101    | IBD-FIRE      | 2934        | 
| 2016-04-04T00:00:00 | Fire - 5 Alarm | 640 Parkside Avenue                         | Brooklyn      | 11226    | IBD-FIRE      | 4253        | 
| 2016-03-31T00:00:00 | Fire - 3 Alarm | NA                                          | NA            |          | IBD-FIRE      | 4567        | 
| 2016-02-02T00:00:00 | Fire - 3 Alarm | 1053 Sinclair Avenue c/s Maguire Avenue     | Staten Island | 10309    | IBD-FIRE      | 1346        | 
| 2016-02-06T00:00:00 | Fire - 2 Alarm | 200 West 111 Street c/s Douglass Boulevard  | Manhattan     | 10026    | IBD-FIRE      | 1547        | 
| 2016-02-02T00:00:00 | Fire - 3 Alarm | 2642 Broadway c/s West 100 Street           | Manhattan     | 10025    | IBD-FIRE      | 1758        | 
| 2016-01-21T00:00:00 | Fire - 3 Alarm | 15 Paerdegat 14 Street c/s East 80th Street | Brooklyn      | 11236    | IBD-FIRE      | 1514        | 
| 2016-01-23T00:00:00 | Fire - 3 Alarm | 90-89 175 St c/s 91st Ave                   | Queens        | 11432    | IBD-FIRE      | 836         | 
| 2016-01-24T00:00:00 | Fire - 4 Alarm | 763 9th Avenue c/s West 51 Street           | Manharttan    | 10019    | IBD-FIRE      | 1923        | 
| 2015-11-09T00:00:00 | 2 Alarm Fire   | 491 Montauk Avenue                          | Brooklyn      | 11208    | IBD-POWER OUT | 2233        | 
```