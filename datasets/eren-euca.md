# Vehicle Repairs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vehicle-repairs) |
| Metadata | [Link](https://data.ct.gov/api/views/eren-euca) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/eren-euca/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/eren-euca/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | eren-euca |
| Name | Vehicle Repairs |
| Attribution | City of Stamford |
| Category | Government |
| Tags | vehicle maintenance |
| Created | 2015-07-14T18:18:50Z |
| Publication Date | 2015-07-14T21:24:31Z |

## Description

Vehicle Maintenance Charge Back to departments

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type     | Render Type   |
| ======== | ============== | ========== | ========= | ============= | ============= |
| Yes      | numeric metric | dept       | Dept      | number        | number        |
| Yes      | time           | jobdate    | JobDate   | calendar_date | calendar_date |
| Yes      | numeric metric | jobno      | jobno     | number        | number        |
| Yes      | series tag     | vehicleid  | Vehicleid | text          | text          |
| Yes      | numeric metric | unitno     | UnitNo    | number        | number        |
| Yes      | series tag     | reason     | Reason    | text          | text          |
| Yes      | series tag     | notes      | Notes     | text          | text          |
| Yes      | numeric metric | costparts  | CostParts | number        | number        |
| Yes      | numeric metric | costlabor  | CostLabor | number        | number        |
| Yes      | numeric metric | costtotal  | CostTotal | number        | number        |
```

## Time Field

```ls
Value = jobdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:eren-euca d:2015-01-06T00:00:00.000Z t:vehicleid=118743 t:reason="04    DRIVER'S REPORT" t:notes="PM SERVICE, CHECK TURN SIGNAL, CLUNKING NOISE WHEN DRIVING" m:costlabor=0 m:unitno=14 m:jobno=14073 m:costtotal=493.85 m:dept=1020 m:costparts=493.85

series e:eren-euca d:2015-01-14T00:00:00.000Z t:vehicleid=230973 t:reason="08    PM SERVICE              ***" t:notes=SERVICEROB,EXT,5604 m:costlabor=0 m:unitno=13 m:jobno=14232 m:costtotal=38.87 m:dept=1020 m:costparts=38.87

series e:eren-euca d:2015-01-02T00:00:00.000Z t:vehicleid=1243 t:reason="04    DRIVER'S REPORT" t:notes="NEED 4 PLOW PINS" m:costlabor=0 m:unitno=116 m:jobno=14006 m:costtotal=45 m:dept=2111 m:costparts=45
```

## Meta Commands

```ls
metric m:dept p:integer l:Dept t:dataTypeName=number

metric m:jobno p:integer l:jobno t:dataTypeName=number

metric m:unitno p:integer l:UnitNo t:dataTypeName=number

metric m:costparts p:float l:CostParts t:dataTypeName=number

metric m:costlabor p:integer l:CostLabor t:dataTypeName=number

metric m:costtotal p:float l:CostTotal t:dataTypeName=number

entity e:eren-euca l:"Vehicle Repairs" t:attribution="City of Stamford" t:url=https://data.ct.gov/api/views/eren-euca

property e:eren-euca t:meta.view v:id=eren-euca v:category=Government v:averageRating=0 v:name="Vehicle Repairs" v:attribution="City of Stamford"

property e:eren-euca t:meta.view.owner v:id=d2jw-b5qp v:screenName="City of Stamford" v:displayName="City of Stamford"

property e:eren-euca t:meta.view.tableauthor v:id=d2jw-b5qp v:screenName="City of Stamford" v:roleName=publisher v:displayName="City of Stamford"
```

## Top Records

```ls
| dept | jobdate             | jobno | vehicleid | unitno | reason             | notes                                                      | costparts          | costlabor | costtotal          | 
| ==== | =================== | ===== | ========= | ====== | ================== | ========================================================== | ================== | ========= | ================== | 
| 1020 | 2015-01-06T00:00:00 | 14073 | 118743    | 14     | 04 DRIVER'S REPORT | PM SERVICE, CHECK TURN SIGNAL, CLUNKING NOISE WHEN DRIVING | 493.85             | 0         | 493.85             | 
| 1020 | 2015-01-14T00:00:00 | 14232 | 230973    | 13     | 08 PM SERVICE ***  | SERVICEROB,EXT,5604                                        | 38.869999999999997 | 0         | 38.869999999999997 | 
| 2111 | 2015-01-02T00:00:00 | 14006 | 1243      | 116    | 04 DRIVER'S REPORT | NEED 4 PLOW PINS                                           | 45                 | 0         | 45                 | 
| 2111 | 2015-01-02T00:00:00 | 14140 | B39109    | 178    | 04 DRIVER'S REPORT | INSTALL SPINNER ASSY                                       | 0                  | 0         | 0                  | 
| 2111 | 2015-01-03T00:00:00 | 14163 | 574950    | 215    | 13 SNOW BREAKDOWN  | DONT START                                                 | 0                  | 0         | 0                  | 
| 2111 | 2015-01-05T00:00:00 | 14169 | A00413    | 283    | 04 DRIVER'S REPORT | DOG BONE PIN BROKEN                                        | 20                 | 0         | 20                 | 
| 2111 | 2015-01-06T00:00:00 | 14000 | 766153    | 248    | 08 PM SERVICE ***  | NEED SERVICE, CHECK BRAKES                                 | 387.17             | 0         | 387.17             | 
| 2111 | 2015-01-06T00:00:00 | 14155 | 525670    | 232    | 04 DRIVER'S REPORT | HYD CAP CHECK ENGINE LIGHT ON                              | 12.95              | 0         | 12.95              | 
| 2111 | 2015-01-06T00:00:00 | 14157 | 621909    | 213    | 40 NEGLIGENCE      | TARP VALVE STICKINGRIGHT SIDE MIRROR BRACKET BROKEN        | 50.02              | 0         | 50.02              | 
| 2111 | 2015-01-06T00:00:00 | 14164 | 1226      | 117    | 13 SNOW BREAKDOWN  | HANDLES IN CAB LOOSE                                       | 0                  | 0         | 0                  | 
```