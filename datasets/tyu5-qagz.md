# IEMA Licensed Medical Radiation Technologists

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iema-licensed-medical-radiation-technologists-7c045) |
| Metadata | [Link](https://data.illinois.gov/api/views/tyu5-qagz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/tyu5-qagz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/tyu5-qagz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | tyu5-qagz |
| Name | IEMA Licensed Medical Radiation Technologists |
| Category | Social/Healthcare |
| Tags | radiation technologists, radiation, technologists, radtech, tech |
| Created | 2011-09-29T14:54:07Z |
| Publication Date | 2011-10-21T21:10:06Z |

## Description

A list of Individuals who are licensed Radiation Technologists in the state of Illinois.

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type | Render Type |
| ======== | =========== | ========== | ========= | ========= | =========== |
| Yes      | series tag  | lastname   | LASTNAME  | text      | text        |
| Yes      | series tag  | firstname  | FIRSTNAME | text      | text        |
| Yes      | series tag  | category   | CATEGORY  | text      | text        |
| Yes      | time        | expdate    | EXPDATE   | date      | date        |
| Yes      | series tag  | county     | COUNTY    | text      | text        |
| Yes      | series tag  | email      | EMAIL     | text      | text        |
```

## Time Field

```ls
Value = expdate
Format & Zone = seconds
```

## Data Commands

```ls
series e:tyu5-qagz d:2012-07-31T07:00:00.000Z t:category=RADIOGRAPHY t:email=gvandeursen@hotmail.com t:county="Out Of State" t:lastname="Van Deursen" t:firstname=Gary m:row_number.tyu5-qagz=1

series e:tyu5-qagz d:2012-07-31T07:00:00.000Z t:category=RADIOGRAPHY t:email=hall_e87@hotmail.com t:county="Out Of State" t:lastname=Heisner t:firstname=Holly m:row_number.tyu5-qagz=2

series e:tyu5-qagz d:2011-11-30T08:00:00.000Z t:category=RADIOGRAPHY t:email=tuccillothomas@yahoo.com t:county="Out Of State" t:lastname=Tuccillo t:firstname=Thomas m:row_number.tyu5-qagz=3
```

## Meta Commands

```ls
metric m:row_number.tyu5-qagz p:long l:"Row Number"

entity e:tyu5-qagz l:"IEMA Licensed Medical Radiation Technologists" t:url=https://data.illinois.gov/api/views/tyu5-qagz

property e:tyu5-qagz t:meta.view v:id=tyu5-qagz v:category=Social/Healthcare v:averageRating=0 v:name="IEMA Licensed Medical Radiation Technologists"

property e:tyu5-qagz t:meta.view.owner v:id=fx6u-bzri v:screenName=Paul v:displayName=Paul

property e:tyu5-qagz t:meta.view.tableauthor v:id=fx6u-bzri v:screenName=Paul v:roleName=publisher v:displayName=Paul
```

## Top Records

```ls
| lastname    | firstname | category         | expdate    | county       | email                      | 
| =========== | ========= | ================ | ========== | ============ | ========================== | 
| Van Deursen | Gary      | RADIOGRAPHY      | 1343718000 | Out Of State | gvandeursen@hotmail.com    | 
| Heisner     | Holly     | RADIOGRAPHY      | 1343718000 | Out Of State | hall_e87@hotmail.com       | 
| Tuccillo    | Thomas    | RADIOGRAPHY      | 1322640000 | Out Of State | tuccillothomas@yahoo.com   | 
| Scorsone    | Joseph    | RADIOGRAPHY      | 1327996800 | Out Of State | scarsoneauto@sbcglobal.net | 
| Villarreal  | Leann     | RADIOGRAPHY      | 1343718000 | Out Of State | leann976@yahoo.com         | 
| Hooker      | Keith     | RADIOGRAPHY      | 1325318400 | Out Of State |                            | 
| Keller      | Gene      | NUCLEAR MEDICINE | 1333177200 | Out Of State | geksinger@yahoo.com        | 
| Sitowski    | Susan     | RADIOGRAPHY      | 1348988400 | Out Of State | ssitowski@yahoo.com        | 
| Anliker     | Mark      | NUCLEAR MEDICINE | 1317366000 | Out Of State | mark_anliker@yahoo.com     | 
| Anliker     | Cynthia   | NUCLEAR MEDICINE | 1351666800 | Out Of State |                            | 
```