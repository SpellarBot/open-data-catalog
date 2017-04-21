# Maryland Female Labor Force Projections: 1970-2040

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-female-labor-force-projections-1970-2040-b5f9f) |
| Metadata | [Link](https://data.maryland.gov/api/views/athe-5ucu) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/athe-5ucu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/athe-5ucu/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | athe-5ucu |
| Name | Maryland Female Labor Force Projections: 1970-2040 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | female, labor force, projections, planning, mdp |
| Created | 2014-09-02T19:34:57Z |
| Publication Date | 2014-09-02T19:36:46Z |

## Description

Historical and Projected Female Labor Force in Maryland and its Jurisdictions, 1970-2040. Projected numbers are rounded to the nearest 10. Prepared by the Maryland Department of Planning, July 2014.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | jurisdiction    | Jurisdiction     | text      | text        |
| Yes      | numeric metric | census_1970     | Census, 1970     | number    | number      |
| Yes      | numeric metric | census_1980     | Census, 1980     | number    | number      |
| Yes      | numeric metric | census_1990     | Census, 1990     | number    | number      |
| Yes      | numeric metric | census_2000     | Census, 2000     | number    | number      |
| Yes      | numeric metric | census_2010     | Census, 2010     | number    | number      |
| Yes      | numeric metric | acs_2008_12     | ACS, 2008-12     | number    | number      |
| Yes      | numeric metric | projection_2015 | Projection, 2015 | number    | number      |
| Yes      | numeric metric | projection_2020 | Projection, 2020 | number    | number      |
| Yes      | numeric metric | projection_2025 | Projection, 2025 | number    | number      |
| Yes      | numeric metric | projection_2030 | Projection, 2030 | number    | number      |
| Yes      | numeric metric | projection_2035 | Projection, 2035 | number    | number      |
| Yes      | numeric metric | projection_2040 | Projection, 2040 | number    | number      |
```

## Time Field

```ls
Value = 1970
Format & Zone = yyyy
```

## Data Commands

```ls
series e:athe-5ucu d:1970-01-01T00:00:00.000Z t:jurisdiction=MARYLAND m:acs_2008_12=1574360 m:projection_2020=1665920 m:projection_2035=1717830 m:census_1980=920020 m:census_2000=1351034 m:census_1990=1238003 m:census_2010=1573680 m:projection_2040=1744190 m:projection_2030=1702860 m:projection_2025=1688580 m:projection_2015=1625920 m:census_1970=619766

series e:athe-5ucu d:1970-01-01T00:00:00.000Z t:jurisdiction="Allegany County" m:acs_2008_12=16431 m:projection_2020=16100 m:projection_2035=16050 m:census_1980=13179 m:census_2000=15476 m:census_1990=14693 m:census_2010=16610 m:projection_2040=16120 m:projection_2030=16070 m:projection_2025=16060 m:projection_2015=16270 m:census_1970=10330

series e:athe-5ucu d:1970-01-01T00:00:00.000Z t:jurisdiction="Anne Arundel County" m:acs_2008_12=143877 m:projection_2020=150270 m:projection_2035=152590 m:census_1980=76605 m:census_2000=125267 m:census_1990=108626 m:census_2010=143870 m:projection_2040=154360 m:projection_2030=151730 m:projection_2025=151000 m:projection_2015=146980 m:census_1970=40725
```

## Meta Commands

```ls
metric m:census_1970 p:integer l:"Census, 1970" t:dataTypeName=number

metric m:census_1980 p:integer l:"Census, 1980" t:dataTypeName=number

metric m:census_1990 p:integer l:"Census, 1990" t:dataTypeName=number

metric m:census_2000 p:integer l:"Census, 2000" t:dataTypeName=number

metric m:census_2010 p:integer l:"Census, 2010" t:dataTypeName=number

metric m:acs_2008_12 p:integer l:"ACS, 2008-12" t:dataTypeName=number

metric m:projection_2015 p:integer l:"Projection, 2015" t:dataTypeName=number

metric m:projection_2020 p:integer l:"Projection, 2020" t:dataTypeName=number

metric m:projection_2025 p:integer l:"Projection, 2025" t:dataTypeName=number

metric m:projection_2030 p:integer l:"Projection, 2030" t:dataTypeName=number

metric m:projection_2035 p:integer l:"Projection, 2035" t:dataTypeName=number

metric m:projection_2040 p:integer l:"Projection, 2040" t:dataTypeName=number

entity e:athe-5ucu l:"Maryland Female Labor Force Projections: 1970-2040" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/athe-5ucu

property e:athe-5ucu t:meta.view v:id=athe-5ucu v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/S3_Projection.shtml v:averageRating=0 v:name="Maryland Female Labor Force Projections: 1970-2040" v:attribution="Maryland Department of Planning"

property e:athe-5ucu t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:athe-5ucu t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| jurisdiction        | census_1970 | census_1980 | census_1990 | census_2000 | census_2010 | acs_2008_12 | projection_2015 | projection_2020 | projection_2025 | projection_2030 | projection_2035 | projection_2040 | 
| =================== | =========== | =========== | =========== | =========== | =========== | =========== | =============== | =============== | =============== | =============== | =============== | =============== | 
| MARYLAND            | 619766      | 920020      | 1238003     | 1351034     | 1573680     | 1574360     | 1625920         | 1665920         | 1688580         | 1702860         | 1717830         | 1744190         | 
| Allegany County     | 10330       | 13179       | 14693       | 15476       | 16610       | 16431       | 16270           | 16100           | 16060           | 16070           | 16050           | 16120           | 
| Anne Arundel County | 40725       | 76605       | 108626      | 125267      | 143870      | 143877      | 146980          | 150270          | 151000          | 151730          | 152590          | 154360          | 
| Baltimore City      | 156129      | 159149      | 171855      | 151057      | 167310      | 166813      | 170100          | 171940          | 172860          | 174050          | 175870          | 179070          | 
| Baltimore County    | 97392       | 149147      | 178358      | 195131      | 220550      | 220693      | 225180          | 226800          | 225580          | 223760          | 223700          | 225930          | 
| Calvert County      | 2579        | 6258        | 12595       | 18521       | 23350       | 23333       | 24180           | 24900           | 24740           | 24220           | 23820           | 23860           | 
| Caroline County     | 2854        | 4525        | 6359        | 7118        | 8250        | 8263        | 8420            | 8950            | 9470            | 9930            | 10440           | 11070           | 
| Carroll County      | 10431       | 19526       | 30383       | 37628       | 43400       | 43351       | 43900           | 45610           | 45200           | 44430           | 44000           | 44820           | 
| Cecil County        | 7225        | 10429       | 16503       | 21026       | 24980       | 25026       | 25290           | 26130           | 27620           | 28610           | 29490           | 30570           | 
| Charles County      | 5835        | 13818       | 26202       | 31448       | 40750       | 41035       | 43390           | 47790           | 51370           | 53330           | 55000           | 56720           | 
```