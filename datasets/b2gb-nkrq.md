# Citizen Emergency Response Team (CERT)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/citizen-emergency-response-team-cert-b938e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/b2gb-nkrq) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/b2gb-nkrq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/b2gb-nkrq/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | b2gb-nkrq |
| Name | Citizen Emergency Response Team (CERT) |
| Attribution | Office of Emergency Management (OEM) |
| Category | Public Safety |
| Tags | citizen emergency response team (cert), oem, emergency management, citizen |
| Created | 2014-06-02T16:19:32Z |
| Publication Date | 2016-01-25T16:17:20Z |

## Description

List of Citizen Emergency Response Teams (CERT)

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | series tag     | team_name   | TEAM_NAME   | text          | text          |
| Yes      | series tag     | label_cd    | CD_Name     | text          | text          |
| Yes      | series tag     | borocd      | CD_Number   | text          | text          |
| Yes      | numeric metric | team_total  | Team_Total  | number        | number        |
| Yes      | series tag     | cert_status | CERT_STATUS | text          | text          |
| Yes      | time           | updated     | UPDATED     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = updated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:b2gb-nkrq d:2010-05-19T00:00:00.000Z t:cert_status="Active CERT team" t:borocd=101 t:team_name="Manhattan 1" t:label_cd="Manhattan CD 1" m:team_total=1

series e:b2gb-nkrq d:2011-09-21T00:00:00.000Z t:cert_status="Active CERT team" t:borocd=102 t:team_name="Manhattan 2" t:label_cd="Manhattan CD 2" m:team_total=1

series e:b2gb-nkrq d:2010-05-19T00:00:00.000Z t:cert_status="Active CERT team" t:borocd=103 t:team_name="Manhattan 3" t:label_cd="Manhattan CD 3" m:team_total=1
```

## Meta Commands

```ls
metric m:team_total p:integer l:Team_Total t:dataTypeName=number

entity e:b2gb-nkrq l:"Citizen Emergency Response Team (CERT)" t:attribution="Office of Emergency Management (OEM)" t:url=https://data.cityofnewyork.us/api/views/b2gb-nkrq

property e:b2gb-nkrq t:meta.view v:id=b2gb-nkrq v:category="Public Safety" v:averageRating=0 v:name="Citizen Emergency Response Team (CERT)" v:attribution="Office of Emergency Management (OEM)"

property e:b2gb-nkrq t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:b2gb-nkrq t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| team_name     | label_cd           | borocd  | team_total | cert_status      | updated             | 
| ============= | ================== | ======= | ========== | ================ | =================== | 
| Manhattan 1   | Manhattan CD 1     | 101     | 1          | Active CERT team | 2010-05-19T00:00:00 | 
| Manhattan 2   | Manhattan CD 2     | 102     | 1          | Active CERT team | 2011-09-21T00:00:00 | 
| Manhattan 3   | Manhattan CD 3     | 103     | 1          | Active CERT team | 2010-05-19T00:00:00 | 
| Manhattan 4/5 | Manhattan CD 4 & 5 | 104/105 | 1          | Active CERT team | 2010-05-19T00:00:00 | 
| Manhattan 6   | Manhattan CD 6     | 106     | 1          | Active CERT team | 2010-05-19T00:00:00 | 
| Manhattan 7   | Manhattan CD 7     | 107     | 1          | Active CERT team | 2010-05-19T00:00:00 | 
| Manhattan 8   | Manhattan CD8      | 108     | 3          | Active CERT team | 2016-01-11T00:00:00 | 
| Manhattan 9   | Manhattan CD 9     | 109     | 1          | Active CERT team | 2010-07-28T00:00:00 | 
| Manhattan 10  | Manhattan CD 10    | 110     | 2          | Active CERT team | 2016-01-11T00:00:00 | 
| Manhattan 11  | Manhattan CD 11    | 111     | 1          | Active CERT team | 2010-05-19T00:00:00 | 
```