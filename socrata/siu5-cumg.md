# IDOL 2012 Amusement Ride Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2012-amusement-ride-inspections-c7803) |
| Metadata | [Link](https://data.illinois.gov/api/views/siu5-cumg) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/siu5-cumg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/siu5-cumg/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | siu5-cumg |
| Name | IDOL 2012 Amusement Ride Inspections |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | amusement ride, permit, labor, 430 ilcs 85 |
| Created | 2014-04-01T21:53:06Z |
| Publication Date | 2014-04-01T21:59:43Z |

## Description

The following is a list of amusement rides and attractions inspected in 2012.

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
series e:siu5-cumg d:2012-01-11T00:00:00.000Z t:ridename="INFLATABLE, 5 IN 1 OBSTACLE PLAYLAND" t:company="123 JUMP" t:comments="RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. [1] 19) THE ATTENDENT MUST BE AN EMPLOYEE OF THE OWNER." m:inspector=7 m:permit=6289

series e:siu5-cumg d:2012-01-11T00:00:00.000Z t:ridename="INFLATABLE, 5 IN 1 SPORTS ARENA" t:company="123 JUMP" t:comments="RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. [1] 19) THE ATTENDENT MUST BE AN EMPLOYEE OF THE OWNER." m:inspector=7 m:permit=6290

series e:siu5-cumg d:2012-01-11T00:00:00.000Z t:ridename="INFLATABLE, BOUNCE HOUSE" t:company="123 JUMP" t:comments="RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. [1] 19) THE ATTENDENT MUST BE AN EMPLOYEE OF THE OWNER." m:inspector=7 m:permit=6291
```

## Meta Commands

```ls
metric m:inspector p:integer l:INSPECTOR t:dataTypeName=number

metric m:permit p:integer l:PERMIT t:dataTypeName=number

metric m:stoporder_2 p:integer l:STOPORDER# t:dataTypeName=number

entity e:siu5-cumg l:"IDOL 2012 Amusement Ride Inspections" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/siu5-cumg

property e:siu5-cumg t:meta.view v:id=siu5-cumg v:category=Labor v:attributionLink=http://labor.illinois.gov v:averageRating=0 v:name="IDOL 2012 Amusement Ride Inspections" v:attribution="Illinois Department of Labor"

property e:siu5-cumg t:meta.view.license v:name="Public Domain"

property e:siu5-cumg t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:siu5-cumg t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| company                  | ridename                             | inspector | inspected           | permit | stoporder_1 | stoporder_2 | comments                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| ======================== | ==================================== | ========= | =================== | ====== | =========== | =========== | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | 
| 123 JUMP                 | INFLATABLE, 5 IN 1 OBSTACLE PLAYLAND | 7         | 2012-01-11T00:00:00 | 6289   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. [1] 19) THE ATTENDENT MUST BE AN EMPLOYEE OF THE OWNER. | 
| 123 JUMP                 | INFLATABLE, 5 IN 1 SPORTS ARENA      | 7         | 2012-01-11T00:00:00 | 6290   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. [1] 19) THE ATTENDENT MUST BE AN EMPLOYEE OF THE OWNER. | 
| 123 JUMP                 | INFLATABLE, BOUNCE HOUSE             | 7         | 2012-01-11T00:00:00 | 6291   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. [1] 19) THE ATTENDENT MUST BE AN EMPLOYEE OF THE OWNER. | 
| 123 JUMP                 | INFLATABLE, SLIDE FRONT LOAD DOUBLE  | 7         | 2012-01-11T00:00:00 | 6292   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. [1] 19) THE ATTENDENT MUST BE AN EMPLOYEE OF THE OWNER. | 
| 123 JUMP                 | INFLATABLE, WACKY WORLD              | 7         | 2012-01-11T00:00:00 | 6293   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES. [1] 19) THE ATTENDENT MUST BE AN EMPLOYEE OF THE OWNER. | 
| 217 TERROR HAUNTED HOUSE | HAUNTED HOUSE                        | 8         | 2012-09-26T00:00:00 | 7775   |             |             | REPAIR/REPOSITION SOCKET IN BEDROOM #1 ADD ADDTL FIRE EXTINGUISHERS INSTALL EXIT SIGNS AT 3 EXITS ADD HANDY BOX TO SPLICED WIRING IN MAZE ADD ADDTL SMOKE DETECTOR AND FIRE EXT. IN VORTEX AREA BY MOTOR ALL TO BE DONE PRIOR TO OPENING                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 25/8 XTREME              | ROCK WALL                            | 9         | 2012-07-27T00:00:00 | 6938   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| 4 YOUR AMUSEMENT, LLC    | EURO BUNGY                           | 7         | 2012-06-01T00:00:00 | 7199   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. REPLACE 2 HARNESSES. [1] 1) SAFETY BELTS, BARS, LOCKS AND OTHER PASSENGER RESTRAINTS. [1] 20) OTHER (DESCRIBED IN INSPECTOR COMMENTS)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 4 YOUR AMUSEMENT, LLC    | INFLATABLE, 5-1 COMBO                | 7         | 2012-06-01T00:00:00 | 7400   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES.                                                         | 
| 4 YOUR AMUSEMENT, LLC    | INFLATABLE, BOUNCE HOUSE             | 7         | 2012-06-01T00:00:00 | 7401   |             |             | RIDE IS ACCEPTABLE AT TIME OF INSPECTION. AT THE TIME OF INSPECTION, THE OWNER WAS ADVISED THAT IN THE ABSENCE OF MANUFACTURERS' REQUIREMENTS TO THE CONTRARY, THE FOLLOWING MINUMUM SAFETY REQUIREMENTS APPLY: [1] 14) ALL ANCHOR TABS MUST BE USED EACH TIME THE ATTRACTION IS INFLATED. [1] EACH TAB, ATTACHMENT AND ANCHOR MUST BE IN GOOD CONDITION AND RESIST A PULL OF AT LEAST 75 LB. FOR INFLATABLE BOUNCES AND 500 LBS. FOR INFLATABLE SLIDES UNLESS THE MANUFACTURER'S SPECIFICATION IS MORE.THE USE OF COTTON ROPE, TARP STRAPS, BUNGEE CORDS OR ELASTIC STRAPS IS PROHIBITED. [1] 16) MOTOR VEHICLES MAY NOT BE USED AT ANCHORS. [1] 17) THE ATTRACTION MUST NEVER BE INFLATED OR OPERATED IN WINDS OVER 25 MPH. [1] 18) A TRAINED ATTENDANT MUST BE AT THE ATTRACTION AT ALL TIMES.                                                         | 
```