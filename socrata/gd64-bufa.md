# Expenditures: ESD: Hight Desert: Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/expenditures-esd-hight-desert-fiscal-year-2013-73153) |
| Metadata | [Link](https://data.oregon.gov/api/views/gd64-bufa) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/gd64-bufa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/gd64-bufa/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | gd64-bufa |
| Name | Expenditures: ESD: Hight Desert: Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | expenditures, esd, high desert, fiscal year 2013 |
| Created | 2013-10-31T17:57:43Z |
| Publication Date | 2013-10-31T18:38:30Z |

## Description

Expenditures for High Desert ESD for Fiscal Year 2013

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | esd_number   | ESD Number   | text      | number      |
| Yes      | series tag     | esd_name     | ESD Name     | text      | text        |
| Yes      | numeric metric | fund         | Fund         | number    | number      |
| Yes      | series tag     | fund_name    | Fund Name    | text      | text        |
| Yes      | numeric metric | object       | Object       | number    | number      |
| Yes      | series tag     | object_name  | Object Name  | text      | text        |
| Yes      | series tag     | remitname    | RemitName    | text      | text        |
| Yes      | series tag     | remitstreet1 | RemitStreet1 | text      | text        |
| Yes      | series tag     | remitcity    | RemitCity    | text      | text        |
| Yes      | series tag     | remitstate   | RemitState   | text      | text        |
| Yes      | series tag     | remitzipcode | RemitZipCode | text      | text        |
| Yes      | numeric metric | totalcost    | TotalCost    | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gd64-bufa d:2013-01-01T00:00:00.000Z t:fund_name=ADMINISTRATION t:esd_name="High Desert ESD" t:esd_number=1975 t:remitstate=. t:remitcity=. t:object_name="IN LIEU OF INSURANCE CAP" t:remitzipcode=. t:remitstreet1="Electronic Insurance Payment" t:remitname="OEBB Insurance -  Non Negotiable" m:totalcost=1110 m:fund=100 m:object=241

series e:gd64-bufa d:2013-01-01T00:00:00.000Z t:fund_name=ADMINISTRATION t:esd_name="High Desert ESD" t:esd_number=1975 t:remitstate=. t:remitcity=. t:object_name="IN LIEU OF INSURANCE CAP" t:remitzipcode=. t:remitstreet1="Electronic Insurance Payment" t:remitname="OEBB Insurance -  Non Negotiable" m:totalcost=1110 m:fund=100 m:object=241

series e:gd64-bufa d:2013-01-01T00:00:00.000Z t:fund_name=ADMINISTRATION t:esd_name="High Desert ESD" t:esd_number=1975 t:remitstate=. t:remitcity=. t:object_name="IN LIEU OF INSURANCE CAP" t:remitzipcode=. t:remitstreet1="Electronic Insurance Payment" t:remitname="OEBB Insurance -  Non Negotiable" m:totalcost=717.08 m:fund=100 m:object=241
```

## Meta Commands

```ls
metric m:fund p:integer l:Fund t:dataTypeName=number

metric m:object p:integer l:Object t:dataTypeName=number

metric m:totalcost p:double l:TotalCost t:dataTypeName=number

entity e:gd64-bufa l:"Expenditures: ESD: Hight Desert: Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/gd64-bufa

property e:gd64-bufa t:meta.view v:id=gd64-bufa v:category="Revenue & Expense" v:averageRating=0 v:name="Expenditures: ESD: Hight Desert: Fiscal Year 2013"

property e:gd64-bufa t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:gd64-bufa t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| esd_number | esd_name        | fund | fund_name      | object | object_name              | remitname                       | remitstreet1                 | remitcity | remitstate | remitzipcode | totalcost | 
| ========== | =============== | ==== | ============== | ====== | ======================== | =============================== | ============================ | ========= | ========== | ============ | ========= | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | OEBB Insurance - Non Negotiable | Electronic Insurance Payment | .         | .          | .            | 1110      | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | OEBB Insurance - Non Negotiable | Electronic Insurance Payment | .         | .          | .            | 1110      | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | OEBB Insurance - Non Negotiable | Electronic Insurance Payment | .         | .          | .            | 717.08    | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | OEBB Insurance - Non Negotiable | Electronic Insurance Payment | .         | .          | .            | 717.08    | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | OEBB Insurance - Non Negotiable | Electronic Insurance Payment | .         | .          | .            | 539.36    | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | OEBB Insurance - Non Negotiable | Electronic Insurance Payment | .         | .          | .            | 657.84    | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | OEBB Insurance - Non Negotiable | Electronic Insurance Payment | .         | .          | .            | 657.84    | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | OEBB Insurance - Non Negotiable | Electronic Insurance Payment | .         | .          | .            | 1013.28   | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | OEBB Insurance - Non Negotiable | Electronic Insurance Payment | .         | .          | .            | 717.08    | 
| 1975       | High Desert ESD | 100  | ADMINISTRATION | 241    | IN LIEU OF INSURANCE CAP | PACIFIC SOURCE HEALTH PLANS     | PO BOX 4210                  | PORTLAND  | OR         | 97208-4210   | 1096      | 
```