# Use Of Force

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/use-of-force) |
| Metadata | [Link](https://data.seattle.gov/api/views/ppi5-g2bj) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ppi5-g2bj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ppi5-g2bj/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ppi5-g2bj |
| Name | Use Of Force |
| Attribution | Seattle Police Department |
| Category | Public Safety |
| Created | 2017-01-28T19:55:05Z |
| Publication Date | 2017-01-31T02:31:54Z |

## Description

Records representing Use of Force (UOF) by sworn law enforcement officers of the Seattle Police Department.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | uniqueid          | ID                | text          | text          |
| Yes      | numeric metric | incident_num      | Incident_Num      | number        | text          |
| Yes      | series tag     | incident_type     | Incident_Type     | text          | text          |
| Yes      | time           | occured_date_time | Occured_date_time | calendar_date | calendar_date |
| Yes      | series tag     | precinct          | Precinct          | text          | text          |
| Yes      | series tag     | sector            | Sector            | text          | text          |
| Yes      | series tag     | beat              | Beat              | text          | text          |
| Yes      | series tag     | officer_id        | Officer_ID        | text          | text          |
| Yes      | series tag     | subject_id        | Subject_ID        | text          | text          |
| Yes      | series tag     | subject_race      | Subject_Race      | text          | text          |
| Yes      | series tag     | subject_gender    | Subject_Gender    | text          | text          |
```

## Time Field

```ls
Value = occured_date_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ppi5-g2bj d:2016-07-26T10:30:00.000Z t:sector=O t:precinct=S t:incident_type="Level 1 - Use of Force" t:officer_id=1668 t:uniqueid=11969-1668-9129 t:subject_gender=Male t:beat=O3 t:subject_id=9129 t:subject_race=White m:incident_num=11969

series e:ppi5-g2bj d:2016-07-26T13:40:00.000Z t:sector=J t:precinct=N t:incident_type="Level 1 - Use of Force" t:officer_id=863 t:uniqueid=11970-863-9130 t:subject_gender=Male t:beat=J2 t:subject_id=9130 t:subject_race="Black or African American" m:incident_num=11970

series e:ppi5-g2bj d:2016-07-26T17:00:00.000Z t:sector=J t:precinct=N t:incident_type="Level 2 - Use of Force" t:officer_id=1615 t:uniqueid=11971-1615-9133 t:subject_gender=Male t:beat=J1 t:subject_id=9133 t:subject_race=White m:incident_num=11971
```

## Meta Commands

```ls
metric m:incident_num p:integer l:Incident_Num d:"Key identifying a force incident." t:dataTypeName=number

entity e:ppi5-g2bj l:"Use Of Force" t:attribution="Seattle Police Department" t:url=https://data.seattle.gov/api/views/ppi5-g2bj

property e:ppi5-g2bj t:meta.view v:id=ppi5-g2bj v:category="Public Safety" v:averageRating=0 v:name="Use Of Force" v:attribution="Seattle Police Department"

property e:ppi5-g2bj t:meta.view.license v:name="Public Domain"

property e:ppi5-g2bj t:meta.view.owner v:id=6bay-fiph v:screenName="6506 Baden, Toby" v:displayName="6506 Baden, Toby"

property e:ppi5-g2bj t:meta.view.tableauthor v:id=6bay-fiph v:screenName="6506 Baden, Toby" v:roleName=publisher v:displayName="6506 Baden, Toby"
```

## Top Records

```ls
| uniqueid        | incident_num | incident_type          | occured_date_time   | precinct | sector | beat | officer_id | subject_id | subject_race              | subject_gender | 
| =============== | ============ | ====================== | =================== | ======== | ====== | ==== | ========== | ========== | ========================= | ============== | 
| 11969-1668-9129 | 11969        | Level 1 - Use of Force | 2016-07-26T10:30:00 | S        | O      | O3   | 1668       | 9129       | White                     | Male           | 
| 11970-863-9130  | 11970        | Level 1 - Use of Force | 2016-07-26T13:40:00 | N        | J      | J2   | 863        | 9130       | Black or African American | Male           | 
| 11971-1615-9133 | 11971        | Level 2 - Use of Force | 2016-07-26T17:00:00 | N        | J      | J1   | 1615       | 9133       | White                     | Male           | 
| 11972-762-9133  | 11972        | Level 1 - Use of Force | 2016-07-26T17:10:00 | N        | J      | J1   | 762        | 9133       | White                     | Male           | 
| 11985-1610-9133 | 11985        | Level 2 - Use of Force | 2016-07-26T17:07:00 | N        | J      | J1   | 1610       | 9133       | White                     | Male           | 
| 11974-2189-9134 | 11974        | Level 1 - Use of Force | 2016-07-26T21:54:00 | N        | B      | B2   | 2189       | 9134       | White                     | Male           | 
| 11975-1719-9135 | 11975        | Level 1 - Use of Force | 2016-07-27T06:09:00 | W        | D      | D2   | 1719       | 9135       | White                     | Male           | 
| 11976-1683-9135 | 11976        | Level 1 - Use of Force | 2016-07-27T06:15:00 | W        | D      | D2   | 1683       | 9135       | White                     | Male           | 
| 12032-854-9181  | 12032        | Level 1 - Use of Force | 2016-07-30T22:30:00 | W        | M      | M3   | 854        | 9181       | Not Specified             | Female         | 
| 12040-1849-9185 | 12040        | Level 1 - Use of Force | 2016-07-31T23:02:00 | N        | B      | B1   | 1849       | 9185       | Not Specified             | Male           | 
```