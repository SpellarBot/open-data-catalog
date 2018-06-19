# Leased State Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/leased-state-buildings) |
| Metadata | [Link](https://data.ct.gov/api/views/khxa-vid2) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/khxa-vid2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/khxa-vid2/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | khxa-vid2 |
| Name | Leased State Buildings |
| Attribution | Office of Policy and Management |
| Category | Government |
| Tags | lease, state buildings, opm |
| Created | 2014-03-22T18:46:15Z |
| Publication Date | 2014-03-22T18:48:00Z |

## Description

Buildings leased by the State of Connecticut

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | leaseid         | LEASEID         | text          | text          |
| Yes      | series tag     | municipality    | MUNICIPALITY    | text          | text          |
| Yes      | series tag     | tenant_agency   | TENANT_AGENCY   | text          | text          |
| Yes      | series tag     | type_of_space   | TYPE_OF_SPACE   | text          | text          |
| Yes      | series tag     | lessor_name     | LESSOR_NAME     | text          | text          |
| Yes      | numeric metric | usable_area     | USABLE_AREA     | number        | number        |
| Yes      | numeric metric | annual_rent     | ANNUAL_RENT     | money         | money         |
| Yes      | time           | expiration_date | EXPIRATION_DATE | calendar_date | calendar_date |
| Yes      | numeric metric | no_pkg_spaces   | NO_PKG_SPACES   | number        | number        |
| Yes      | series tag     | purchase_option | PURCHASE_OPTION | text          | text          |
| Yes      | numeric metric | tax_escalation  | TAX_ESCALATION  | percent       | percent       |
| No       |                | he              | HE              | text          | text          |
| Yes      | series tag     | he2             | HE2             | text          | text          |
| No       |                | el              | EL              | text          | text          |
| Yes      | series tag     | el2             | EL2             | text          | text          |
| No       |                | hw              | HW              | text          | text          |
| Yes      | series tag     | hw2             | HW2             | text          | text          |
| No       |                | ac              | AC              | text          | text          |
| Yes      | series tag     | ac2             | AC2             | text          | text          |
| Yes      | series tag     | jales           | JALes           | text          | text          |
| Yes      | series tag     | jacom           | JACom           | text          | text          |
| Yes      | series tag     | bmles           | BMLes           | text          | text          |
| Yes      | series tag     | bmcom           | BMCom           | text          | text          |
| Yes      | series tag     | rrles           | RRLes           | text          | text          |
| Yes      | series tag     | rrcom           | RRCom           | text          | text          |
| No       |                | ev              | EV              | text          | text          |
| No       |                | li              | LI              | text          | text          |
| No       |                | sn              | SN              | text          | text          |
| No       |                | pa              | PA              | text          | text          |
| No       |                | se              | SE              | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = he,el,hw,ac,ev,li,sn,pa,se
```

## Data Commands

```ls
series e:khxa-vid2 d:2017-04-30T00:00:00.000Z t:hw2=Y t:jales=N t:el2=Y t:he2=Y t:leaseid=104-01 t:municipality=NORWICH t:rrcom=Y t:tenant_agency=DOC t:lessor_name="LORD FAMILY NOMINEE TRUST" t:bmcom=Y t:ac2=Y t:purchase_option=N t:rrles=N t:jacom=Y t:type_of_space=Building t:bmles=Y m:usable_area=3735 m:no_pkg_spaces=12 m:annual_rent=53223.72 m:tax_escalation=7.75

series e:khxa-vid2 d:2017-11-13T00:00:00.000Z t:hw2=N t:jales=N t:el2=N t:he2=N t:leaseid=015-16 t:municipality=BRIDGEPORT t:rrcom=N t:tenant_agency=JUD t:lessor_name="FAIRFIELD AVE. PARKING  CORP." t:bmcom=N t:ac2=N t:purchase_option=N t:rrles=N t:jacom=N t:type_of_space=Parking t:bmles=N m:usable_area=0 m:no_pkg_spaces=90 m:annual_rent=99999.96 m:tax_escalation=0

series e:khxa-vid2 d:2014-02-09T00:00:00.000Z t:hw2=Y t:jales=N t:el2=Y t:he2=Y t:leaseid=077-01 t:municipality=MANCHESTER t:rrcom=Y t:tenant_agency=DCF t:lessor_name="L & J MANCHESTER II, LLC" t:bmcom=Y t:ac2=Y t:purchase_option=N t:rrles=N t:jacom=Y t:type_of_space=Building t:bmles=Y m:usable_area=40198 m:no_pkg_spaces=193 m:annual_rent=582871 m:tax_escalation=0
```

## Meta Commands

```ls
metric m:usable_area p:integer l:USABLE_AREA t:dataTypeName=number

metric m:annual_rent p:double l:ANNUAL_RENT t:dataTypeName=money

metric m:no_pkg_spaces p:integer l:NO_PKG_SPACES t:dataTypeName=number

metric m:tax_escalation p:float l:TAX_ESCALATION t:dataTypeName=percent

entity e:khxa-vid2 l:"Leased State Buildings" t:attribution="Office of Policy and Management" t:url=https://data.ct.gov/api/views/khxa-vid2

property e:khxa-vid2 t:meta.view v:id=khxa-vid2 v:category=Government v:averageRating=0 v:name="Leased State Buildings" v:attribution="Office of Policy and Management"

property e:khxa-vid2 t:meta.view.license v:name="Public Domain"

property e:khxa-vid2 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:khxa-vid2 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| leaseid | municipality  | tenant_agency | type_of_space | lessor_name                                     | usable_area | annual_rent | expiration_date     | no_pkg_spaces | purchase_option | tax_escalation | he | he2 | el | el2 | hw | hw2 | ac | ac2 | jales | jacom | bmles | bmcom | rrles | rrcom | ev | li | sn | pa | se | 
| ======= | ============= | ============= | ============= | =============================================== | =========== | =========== | =================== | ============= | =============== | ============== | == | === | == | === | == | === | == | === | ===== | ===== | ===== | ===== | ===== | ===== | == | == | == | == | == | 
| 104-01  | NORWICH       | DOC           | Building      | LORD FAMILY NOMINEE TRUST                       | 3735        | 53223.72    | 2017-04-30T00:00:00 | 12            | N               | 7.75           | N  | Y   | N  | Y   | N  | Y   | N  | Y   | N     | Y     | Y     | Y     | N     | Y     | Y  | Y  | Y  | Y  | N  | 
| 015-16  | BRIDGEPORT    | JUD           | Parking       | FAIRFIELD AVE. PARKING CORP.                    | 0           | 99999.96    | 2017-11-13T00:00:00 | 90            | N               | 0.00           | N  | N   | N  | N   | N  | N   | N  | N   | N     | N     | N     | N     | N     | N     | N  | N  | N  | N  | N  | 
| 077-01  | MANCHESTER    | DCF           | Building      | L & J MANCHESTER II, LLC                        | 40198       | 582871.00   | 2014-02-09T00:00:00 | 193           | N               | 0.00           | N  | Y   | N  | Y   | N  | Y   | N  | Y   | N     | Y     | Y     | Y     | N     | Y     | Y  | Y  | Y  | Y  | N  | 
| 093-11  | NEW HAVEN     | JUD           | Building      | MORGAN REED CHAPEL, LLC                         | 15718       | 200404.50   | 2013-11-06T00:00:00 | 85            | N               | 21.60          | N  | Y   | N  | Y   | N  | Y   | N  | Y   | N     | Y     | Y     | Y     | N     | Y     | Y  | Y  | Y  | Y  | N  | 
| 104-05  | NORWICH       | DCF           | Building      | NASSI CT.REALTY LLC                             | 36022       | 608553.48   | 2016-07-12T00:00:00 | 284           | N               | 0.00           | Y  | Y   | N  | Y   | Y  | Y   | N  | Y   | N     | Y     | N     | N     | N     | N     | Y  | N  | Y  | N  | N  | 
| 163-05  | WINDHAM       | CSL           | Building      | ALEXANDER TYLER CORP                            | 10067       | 112876.22   | 2015-12-31T00:00:00 | 50            | N               | 20.00          | N  | Y   | N  | Y   | N  | Y   | N  | Y   | N     | Y     | Y     | Y     | N     | Y     | Y  | N  | Y  | Y  | N  | 
| 043-04  | EAST HARTFORD | DDS           | Building      | FREMONT 155, LLC                                | 32628       | 459999.96   | 2014-11-30T00:00:00 | 230           | N               | 67.65          | N  | Y   | N  | Y   | N  | Y   | N  | Y   | Y     | Y     | Y     | Y     | Y     | Y     | Y  | Y  | Y  | Y  | N  | 
| 094-01  | NEWINGTON     | DSS           | Building      | RENO PROPERTIES II, LLC                         | 28325       | 573581.25   | 2019-01-14T00:00:00 | 155           | N               | 100.00         | N  | Y   | N  | Y   | N  | Y   | N  | Y   | N     | N     | Y     | Y     | N     | Y     | Y  | N  | Y  | Y  | N  | 
| 015-11  | BRIDGEPORT    | DSS           | Building      | EST. OF F.FRANCIS D'ADDARIO & LM BRIDGEPORT LLC | 57430       | 781648.92   | 2013-12-31T00:00:00 | 200           | N               | 100.00         | Y  | Y   | Y  | Y   | Y  | Y   | Y  | Y   | N     | Y     | Y     | Y     | Y     | Y     | Y  | Y  | Y  | Y  | N  | 
| 155-02  | WEST HARTFORD | DCJ           | Building      | BK SOUTH LLC                                    | 7496        | 62516.63    | 2013-06-15T00:00:00 | 15            | N               | 0.00           | N  | Y   | N  | Y   | N  | Y   | N  | Y   | N     | Y     | Y     | Y     | N     | Y     | N  | Y  | Y  | Y  | N  | 
```