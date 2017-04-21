# 2016 Early Voting Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-early-voting-centers) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/hr8w-judx) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/hr8w-judx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/hr8w-judx/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | hr8w-judx |
| Name | 2016 Early Voting Centers |
| Category | Elections |
| Tags | voting, early voting, polling, elections |
| Created | 2016-04-12T16:09:54Z |
| Publication Date | 2016-10-20T15:32:41Z |

## Description

2016 early voting locations in Montgomery County as selected April 12th, 2016, subject to approval by the Maryland State Board of Elections. For more information, see www.777vote.org.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| Yes      | series tag  | site          | Site          | text      | text        |
| Yes      | series tag  | building_name | Building Name | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hr8w-judx d:2016-01-01T00:00:00.000Z t:building_name="EXECUTIVE OFFICE BUILDING" t:site=EV-2 m:row_number.hr8w-judx=1

series e:hr8w-judx d:2016-01-01T00:00:00.000Z t:building_name="SILVER SPRING CIVIC BUILDING" t:site=EV-5 m:row_number.hr8w-judx=2

series e:hr8w-judx d:2016-01-01T00:00:00.000Z t:building_name="MARILYN J. PRAISNER COMMUNITY RECREATION CENTER" t:site=EV-4 m:row_number.hr8w-judx=3
```

## Meta Commands

```ls
metric m:row_number.hr8w-judx p:long l:"Row Number"

entity e:hr8w-judx l:"2016 Early Voting Centers" t:url=https://data.montgomerycountymd.gov/api/views/hr8w-judx

property e:hr8w-judx t:meta.view v:id=hr8w-judx v:category=Elections v:averageRating=0 v:name="2016 Early Voting Centers"

property e:hr8w-judx t:meta.view.owner v:id=6ide-p8eb v:screenName="Ted Bowser" v:displayName="Ted Bowser"

property e:hr8w-judx t:meta.view.tableauthor v:id=6ide-p8eb v:screenName="Ted Bowser" v:roleName=viewer v:displayName="Ted Bowser"
```

## Top Records

```ls
| site  | building_name                                   | 
| ===== | =============================================== | 
| EV-2  | EXECUTIVE OFFICE BUILDING                       | 
| EV-5  | SILVER SPRING CIVIC BUILDING                    | 
| EV-4  | MARILYN J. PRAISNER COMMUNITY RECREATION CENTER | 
| EV-9  | WHEATON VOLUNTEER RESCUE SQUAD                  | 
| EV-8  | JANE E. LAWTON COMMUNITY RECREATION CENTER      | 
| EV-6  | ACTIVITY CENTER AT BOHRER PARK                  | 
| EV-3  | GERMANTOWN COMMUNITY RECREATION CENTER          | 
| EV-1  | MID-COUNTY COMMUNITY RECREATION CENTER          | 
| EV-7  | DAMASCUS COMMUNITY RECREATION CENTER            | 
| EV-10 | POTOMAC COMMUNITY RECREATION CENTER             | 
```