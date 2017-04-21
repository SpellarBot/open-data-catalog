# IDOL 2013 Amusement Ride Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2013-amusement-ride-inspections-2cbc6) |
| Metadata | [Link](https://data.illinois.gov/api/views/au3k-b3pd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/au3k-b3pd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/au3k-b3pd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | au3k-b3pd |
| Name | IDOL 2013 Amusement Ride Inspections |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | amusement ride, permit, labor, 430 ilcs 85 |
| Created | 2014-03-19T21:45:22Z |
| Publication Date | 2014-04-01T17:14:28Z |

## Description

The following is a list of amusement rides and attractions inspected in 2013.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type     | Render Type   |
| ======== | ============== | =========== | ========== | ============= | ============= |
| Yes      | series tag     | company     | COMPANY    | text          | text          |
| Yes      | series tag     | ridename    | RIDENAME   | text          | text          |
| Yes      | numeric metric | inspector   | INSPECTOR  | number        | text          |
| Yes      | time           | inspected   | INSPECTED  | calendar_date | calendar_date |
| Yes      | numeric metric | permit      | PERMIT     | number        | text          |
| No       |                | stoporder_1 | STOPORDER  | calendar_date | calendar_date |
| Yes      | numeric metric | stoporder_2 | STOPORDER# | number        | number        |
| Yes      | series tag     | comments    | COMMENTS   | text          | text          |
```

## Time Field

```ls
Value = inspected
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = stoporder_1
```

## Data Commands

```ls
series e:au3k-b3pd d:2013-09-24T00:00:00.000Z t:ridename="HAUNTED HOUSE" t:company="217 TERROR HAUNTED HOUSE" t:comments="RIDE IS ACCEPTABLE AT TIME OF INSPECTION." m:inspector=8 m:permit=11308

series e:au3k-b3pd d:2013-07-10T00:00:00.000Z t:ridename="ROCK WALL" t:company="25/8 XTREME" t:comments="RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY:[1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES." m:inspector=8 m:permit=11109

series e:au3k-b3pd d:2013-11-05T00:00:00.000Z t:ridename="ROCK WALL" t:company="25/8 XTREME" t:comments="RIDE IS ACCEPTABLE AT TIME OF INSPECTION." m:inspector=9 m:permit=11109
```

## Meta Commands

```ls
metric m:inspector p:integer l:INSPECTOR t:dataTypeName=number

metric m:permit p:integer l:PERMIT t:dataTypeName=number

metric m:stoporder_2 p:integer l:STOPORDER# t:dataTypeName=number

entity e:au3k-b3pd l:"IDOL 2013 Amusement Ride Inspections" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/au3k-b3pd

property e:au3k-b3pd t:meta.view v:id=au3k-b3pd v:category=Labor v:attributionLink=http://labor.illinois.gov/ v:averageRating=0 v:name="IDOL 2013 Amusement Ride Inspections" v:attribution="Illinois Department of Labor"

property e:au3k-b3pd t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:au3k-b3pd t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| company                  | ridename                       | inspector | inspected           | permit | stoporder_1 | stoporder_2 | comments                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 
| ======================== | ============================== | ========= | =================== | ====== | =========== | =========== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================ | 
| 217 TERROR HAUNTED HOUSE | HAUNTED HOUSE                  | 8         | 2013-09-24T00:00:00 | 11308  |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 25/8 XTREME              | ROCK WALL                      | 8         | 2013-07-10T00:00:00 | 11109  |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY:[1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. | 
| 25/8 XTREME              | ROCK WALL                      | 9         | 2013-11-05T00:00:00 | 11109  |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 62 SPORTS GROUP, INC.    | INFLATABLE, 2 LANE BUNGEE      | 8         | 2013-06-05T00:00:00 | 9608   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY:[1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. | 
| 62 SPORTS GROUP, INC.    | INFLATABLE, BALLOON BOUNCE     | 8         | 2013-06-05T00:00:00 | 9603   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 62 SPORTS GROUP, INC.    | INFLATABLE, BOUNCE - COW       | 8         | 2013-06-05T00:00:00 | 9610   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 62 SPORTS GROUP, INC.    | INFLATABLE, BOUNCE FOOTBALL    | 8         | 2013-06-05T00:00:00 | 9615   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 62 SPORTS GROUP, INC.    | INFLATABLE, BOUNCE-SKID LOADER | 8         | 2013-06-05T00:00:00 | 9614   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 62 SPORTS GROUP, INC.    | INFLATABLE, COMBO SAFARI BUS   | 8         | 2013-06-05T00:00:00 | 9604   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 62 SPORTS GROUP, INC.    | INFLATABLE, DALMATION COMBO    | 8         | 2013-06-05T00:00:00 | 9601   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY:[1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. | 
```