# Daily Arrests

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/daily-arrests) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/xhwt-7h2h) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/xhwt-7h2h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/xhwt-7h2h/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | xhwt-7h2h |
| Name | Daily Arrests |
| Attribution | Montgomery County, MD |
| Category | Public Safety |
| Tags | daily, arrest, arrestee |
| Created | 2016-03-09T12:49:30Z |
| Publication Date | 2016-05-11T15:14:52Z |

## Description

This dataset provides the public with arrest information from the Montgomery County Central Processing Unit (CPU) systems. The data presented is derived from every booking; criminal, civil and motor vehicle entered through CPU. The data is compiled by ?CRIMS?, a respected jail records-management system used by the Montgomery County Corrections and many other law enforcement agencies. To protect arrestee?s privacy, personal information is redacted. Residential addresses are rounded to the nearest hundred block. All data is refreshed on 2 hour basis to reflect any additions or changes. 
-Information that may include mechanical or human error 
-Arrest information [Note: all arrested persons are presumed innocent until proven guilty in a court of law
- Records will be removed after 30 days.
Update Frequency - every 2 hours

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | series tag     | last_name   | LAST NAME   | text          | text          |
| Yes      | series tag     | first_name  | FIRST NAME  | text          | text          |
| Yes      | series tag     | middle_name | MIDDLE NAME | text          | text          |
| Yes      | numeric metric | age         | AGE         | number        | number        |
| Yes      | series tag     | street      | STREET      | text          | text          |
| Yes      | series tag     | city        | CITY        | text          | text          |
| Yes      | series tag     | state       | STATE       | text          | text          |
| Yes      | time           | arrest_date | ARREST DATE | calendar_date | calendar_date |
| Yes      | series tag     | offense     | OFFENSE     | text          | text          |
```

## Time Field

```ls
Value = arrest_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:xhwt-7h2h d:2017-04-10T06:20:00.000Z t:first_name=JOSHUA t:middle_name=J t:street="11600 Block Of paramus dr" t:state=MD t:last_name=CASTILLO t:offense="POSSESS/ISSUE  FORGED CURRENCY" t:city="NORTH POTOMAC" m:age=20

series e:xhwt-7h2h d:2017-04-10T07:05:00.000Z t:first_name=XAVIER t:middle_name=TEOFILO t:street="3200 Block Of Waters LN" t:state=MD t:last_name=FUENTES-MEJIA t:offense="Urinating / Defecating in Public" t:city=Forestville m:age=25

series e:xhwt-7h2h d:2017-04-10T11:45:00.000Z t:first_name=DAVON t:street="700 Block Of  Strepper St" t:state=MD t:last_name=DATES t:offense=ROBBERY t:city=BALTIMORE m:age=21
```

## Meta Commands

```ls
metric m:age p:integer l:AGE d:"Age of the person arrested" t:dataTypeName=number

entity e:xhwt-7h2h l:"Daily Arrests" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/xhwt-7h2h

property e:xhwt-7h2h t:meta.view v:id=xhwt-7h2h v:category="Public Safety" v:averageRating=0 v:name="Daily Arrests" v:attribution="Montgomery County, MD"

property e:xhwt-7h2h t:meta.view.license v:name="Public Domain"

property e:xhwt-7h2h t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:xhwt-7h2h t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| last_name       | first_name | middle_name   | age | street                           | city          | state | arrest_date         | offense                             | 
| =============== | ========== | ============= | === | ================================ | ============= | ===== | =================== | =================================== | 
| CASTILLO        | JOSHUA     | J             | 20  | 11600 Block Of paramus dr        | NORTH POTOMAC | MD    | 2017-04-10T06:20:00 | POSSESS/ISSUE FORGED CURRENCY       | 
| FUENTES-MEJIA   | XAVIER     | TEOFILO       | 25  | 3200 Block Of Waters LN          | Forestville   | MD    | 2017-04-10T07:05:00 | Urinating / Defecating in Public    | 
| DATES           | DAVON      |               | 21  | 700 Block Of Strepper St         | BALTIMORE     | MD    | 2017-04-10T11:45:00 | ROBBERY                             | 
| PHANG           | MICHAEL    | WAYNE ANTHONY | 63  | 12200 Block Of Centerhill        | SILVER SPRING | MD    | 2017-04-10T13:30:00 | ASSAULT-FIRST DEGREE                | 
| OLIVERAS-MCLEAN | ABEL       | FRANCISCO     | 22  | 11500 Block Of LOCKWOOD DRIVE    | SILVER SPRING | MD    | 2017-04-10T11:59:00 | CDS:POSSESS-NOT MARIJUANA           | 
| TURNER          | DEVIN      | NATHAN        | 21  | 2400 Block Of Elvans Rd          | WASHINGTON    | DC    | 2017-04-10T10:04:00 | THEFT: $1,000 TO UNDER $10,000      | 
| STEPHENSON      | GEVAUGHN   | KENNETH       | 23  | 2100 Block Of harlequin terrance | SILVER SPRING | MD    | 2017-04-10T11:45:00 | CHILD ABUSE 1ST DEG:SEVERE PHYS INJ | 
| HOES            | KEVIN      | KENNETH       | 33  | NO FIXED ADDRESS                 | ROCKVILLE     | MD    | 2017-04-10T14:50:00 | TRESPASS: PRIVATE PROPERTY          | 
| BOWERS          | RAMECE     |               | 25  | 1400 Block Of elm grove cir      | SILVER SPRING | MD    | 2017-04-10T16:50:00 | TRESPASS: PRIVATE PROPERTY          | 
| SANDERS         | JOHN       | THOMAS        | 31  | 100 Block Of Joel Cir.           | HAGERSTOWN    | MD    | 2017-04-10T01:00:00 | THEFT LESS THAN $100.00             | 
```