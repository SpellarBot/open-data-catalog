# Airport (SFO) Monthly Utility Usage And Revenue

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/airport-sfo-monthly-utility-usage-and-revenue) |
| Metadata | [Link](https://data.sfgov.org/api/views/jzyy-jx2t) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/jzyy-jx2t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/jzyy-jx2t/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | jzyy-jx2t |
| Name | Airport (SFO) Monthly Utility Usage And Revenue |
| Attribution | San Francisco International Airport |
| Category | Transportation |
| Tags | airport, sfo, utility consumption, utility usage |
| Created | 2016-05-12T19:24:39Z |
| Publication Date | 2016-06-09T21:42:23Z |

## Description

San Francisco International Airport Report on Monthly utility usage and revenues by utility type and meter number

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | time           | readperiod              | READPERIOD              | calendar_date | calendar_date |
| Yes      | series tag     | utilitytypeabbrev       | UTILITYTYPEABBREV       | text          | text          |
| Yes      | series tag     | utilitydescription      | UTILITYDESCRIPTION      | text          | text          |
| Yes      | series tag     | meterreadingid          | METERREADINGID          | text          | number        |
| Yes      | series tag     | meterid                 | METERID                 | text          | number        |
| Yes      | series tag     | meternumber             | METERNUMBER             | text          | text          |
| Yes      | series tag     | meterserialnumber       | METERSERIALNUMBER       | text          | text          |
| Yes      | series tag     | servicelocation         | SERVICELOCATION         | text          | text          |
| Yes      | series tag     | meterlocation           | METERLOCATION           | text          | text          |
| Yes      | series tag     | agrmtid                 | AGRMTID                 | text          | number        |
| Yes      | series tag     | agrmtnumber             | AGRMTNUMBER             | text          | text          |
| Yes      | series tag     | agreementtitle          | AGREEMENTTITLE          | text          | text          |
| Yes      | series tag     | provid                  | PROVID                  | text          | number        |
| No       |                | provassnstart           | PROVASSNSTART           | calendar_date | calendar_date |
| No       |                | provassnend             | PROVASSNEND             | calendar_date | calendar_date |
| Yes      | numeric metric | previousreading         | PREVIOUSREADING         | number        | number        |
| Yes      | numeric metric | meterreading            | METERREADING            | number        | number        |
| Yes      | numeric metric | baseusage               | BASEUSAGE               | number        | number        |
| Yes      | numeric metric | multifactor             | MULTIFACTOR             | number        | number        |
| Yes      | numeric metric | totalusage              | TOTALUSAGE              | number        | number        |
| Yes      | numeric metric | adjustment              | ADJUSTMENT              | number        | number        |
| Yes      | numeric metric | netusage                | NETUSAGE                | number        | number        |
| Yes      | numeric metric | previoususage           | PREVIOUSUSAGE           | number        | number        |
| Yes      | numeric metric | usagepctchange          | USAGEPCTCHANGE          | percent       | percent       |
| Yes      | numeric metric | totaldemand             | TOTALDEMAND             | number        | number        |
| Yes      | numeric metric | previousdemand          | PREVIOUSDEMAND          | number        | number        |
| Yes      | numeric metric | demandpctchange         | DEMANDPCTCHANGE         | number        | number        |
| Yes      | numeric metric | percentuse              | PERCENTUSE              | percent       | percent       |
| Yes      | numeric metric | pctbaseamount           | PCTBASEAMOUNT           | number        | number        |
| Yes      | numeric metric | pctfueladjustmentamount | PCTFUELADJUSTMENTAMOUNT | number        | number        |
| Yes      | numeric metric | pctsalestaxamount       | PCTSALESTAXAMOUNT       | number        | number        |
| Yes      | numeric metric | pcttotalamount          | PCTTOTALAMOUNT          | number        | number        |
```

## Time Field

```ls
Value = readperiod
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = provassnstart,provassnend
```

## Data Commands

```ls
series e:jzyy-jx2t d:200801-01-01T00:00:00.000Z t:agrmtid=1958 t:agrmtnumber=L82-0111 t:meterid=1176 t:meterlocation="E LC 89" t:utilitydescription="Electric A" t:utilitytypeabbrev=EA t:meterreadingid=119 t:servicelocation="American Airlines Motor Generator for Plane Power" t:meternumber=70-251-407 t:provid=12263 t:agreementtitle="American Airlines Lease And Use Agreement in Terminal 3" m:netusage=46400 m:totaldemand=224 m:pctsalestaxamount=0 m:percentuse=100 m:demandpctchange=0 m:pctbaseamount=4077.65 m:previousdemand=0 m:baseusage=58 m:previoususage=0 m:adjustment=0 m:pctfueladjustmentamount=0 m:previousreading=6586 m:totalusage=46400 m:usagepctchange=0 m:multifactor=800 m:meterreading=6644 m:pcttotalamount=4077.65

series e:jzyy-jx2t d:200801-01-01T00:00:00.000Z t:agrmtid=2453 t:agrmtnumber=L99-0292E t:meterid=490 t:meterlocation="meter room" t:utilitydescription=Water t:utilitytypeabbrev=WA t:meterreadingid=171 t:servicelocation="Emporio Rulli 2 IT, North Food Court, CN30E" t:meternumber=47998343 t:provid=15851 t:agreementtitle="Emporio Rulli IT FB Lease Agreement" m:netusage=9 m:totaldemand=0 m:pctsalestaxamount=0 m:percentuse=100 m:demandpctchange=0 m:pctbaseamount=0 m:previousdemand=0 m:baseusage=9 m:previoususage=0 m:adjustment=0 m:pctfueladjustmentamount=0 m:previousreading=643 m:totalusage=9 m:usagepctchange=0 m:multifactor=1 m:meterreading=652 m:pcttotalamount=0

series e:jzyy-jx2t d:200801-01-01T00:00:00.000Z t:agrmtid=3063 t:agrmtnumber=L03-0180 t:meterid=499 t:meterlocation="in office up high" t:utilitydescription=Water t:utilitytypeabbrev=WA t:meterreadingid=180 t:servicelocation="Sankaku, Inc. T3" t:meternumber=47998356 t:provid=22336 t:agreementtitle="Sankaku Domestic Terminal FB Lease" m:netusage=43 m:totaldemand=0 m:pctsalestaxamount=0 m:percentuse=100 m:demandpctchange=0 m:pctbaseamount=0 m:previousdemand=0 m:baseusage=43 m:previoususage=0 m:adjustment=0 m:pctfueladjustmentamount=0 m:previousreading=1146 m:totalusage=43 m:usagepctchange=0 m:multifactor=1 m:meterreading=1189 m:pcttotalamount=0
```

## Meta Commands

```ls
metric m:previousreading p:double l:PREVIOUSREADING t:dataTypeName=number

metric m:meterreading p:integer l:METERREADING t:dataTypeName=number

metric m:baseusage p:integer l:BASEUSAGE t:dataTypeName=number

metric m:multifactor p:integer l:MULTIFACTOR t:dataTypeName=number

metric m:totalusage p:integer l:TOTALUSAGE t:dataTypeName=number

metric m:adjustment p:float l:ADJUSTMENT t:dataTypeName=number

metric m:netusage p:integer l:NETUSAGE t:dataTypeName=number

metric m:previoususage p:integer l:PREVIOUSUSAGE t:dataTypeName=number

metric m:usagepctchange p:double l:USAGEPCTCHANGE t:dataTypeName=percent

metric m:totaldemand p:integer l:TOTALDEMAND t:dataTypeName=number

metric m:previousdemand p:double l:PREVIOUSDEMAND t:dataTypeName=number

metric m:demandpctchange p:double l:DEMANDPCTCHANGE t:dataTypeName=number

metric m:percentuse p:double l:PERCENTUSE t:dataTypeName=percent

metric m:pctbaseamount p:double l:PCTBASEAMOUNT t:dataTypeName=number

metric m:pctfueladjustmentamount p:integer l:PCTFUELADJUSTMENTAMOUNT t:dataTypeName=number

metric m:pctsalestaxamount p:float l:PCTSALESTAXAMOUNT t:dataTypeName=number

metric m:pcttotalamount p:double l:PCTTOTALAMOUNT t:dataTypeName=number

entity e:jzyy-jx2t l:"Airport (SFO) Monthly Utility Usage And Revenue" t:attribution="San Francisco International Airport" t:url=https://data.sfgov.org/api/views/jzyy-jx2t

property e:jzyy-jx2t t:meta.view v:id=jzyy-jx2t v:category=Transportation v:averageRating=0 v:name="Airport (SFO) Monthly Utility Usage And Revenue" v:attribution="San Francisco International Airport"

property e:jzyy-jx2t t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:jzyy-jx2t t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:jzyy-jx2t t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| readperiod            | utilitytypeabbrev | utilitydescription | meterreadingid | meterid | meternumber | meterserialnumber | servicelocation                                   | meterlocation                                      | agrmtid | agrmtnumber | agreementtitle                                                    | provid | provassnstart         | provassnend           | previousreading | meterreading | baseusage | multifactor | totalusage | adjustment | netusage | previoususage | usagepctchange | totaldemand | previousdemand | demandpctchange | percentuse | pctbaseamount | pctfueladjustmentamount | pctsalestaxamount | pcttotalamount | 
| ===================== | ================= | ================== | ============== | ======= | =========== | ================= | ================================================= | ================================================== | ======= | =========== | ================================================================= | ====== | ===================== | ===================== | =============== | ============ | ========= | =========== | ========== | ========== | ======== | ============= | ============== | =========== | ============== | =============== | ========== | ============= | ======================= | ================= | ============== | 
| 200801-01-01T00:00:00 | EA                | Electric A         | 119            | 1176    | 70-251-407  |                   | American Airlines Motor Generator for Plane Power | E LC 89                                            | 1958    | L82-0111    | American Airlines Lease And Use Agreement in Terminal 3           | 12263  | 200801-01-01T00:00:00 | 201106-01-01T00:00:00 | 6586            | 6644         | 58        | 800         | 46400      | 0          | 46400    | 0             | 0              | 224         | 0              | 0               | 100        | 4077.65       | 0                       | 0                 | 4077.65        | 
| 200801-01-01T00:00:00 | WA                | Water              | 171            | 490     | 47998343    |                   | Emporio Rulli 2 IT, North Food Court, CN30E       | meter room                                         | 2453    | L99-0292E   | Emporio Rulli IT FB Lease Agreement                               | 15851  | 200801-01-01T00:00:00 | 205012-01-01T00:00:00 | 643             | 652          | 9         | 1           | 9          | 0          | 9        | 0             | 0              | 0           | 0              | 0               | 100        | 0             | 0                       | 0                 | 0              | 
| 200801-01-01T00:00:00 | WA                | Water              | 180            | 499     | 47998356    |                   | Sankaku, Inc. T3                                  | in office up high                                  | 3063    | L03-0180    | Sankaku Domestic Terminal FB Lease                                | 22336  | 200801-01-01T00:00:00 | 205012-01-01T00:00:00 | 1146            | 1189         | 43        | 1           | 43         | 0          | 43       | 0             | 0              | 0           | 0              | 0               | 100        | 0             | 0                       | 0                 | 0              | 
| 200801-01-01T00:00:00 | WA                | Water              | 185            | 504     | 47998366    |                   | Bay Area Rest dba Max's Eatz Tu B/A B             | Lower level below restaurant near Gate 24 ctr of Y | 2625    | L03-0184    | BARG Max's (2 locations) Domestic FB Program Lease                | 17494  | 200801-01-01T00:00:00 | 205012-01-01T00:00:00 | 1038            | 1070         | 32        | 1           | 32         | 0          | 32       | 0             | 0              | 0           | 0              | 0               | 100        | 0             | 0                       | 0                 | 0              | 
| 200801-01-01T00:00:00 | WA                | Water              | 190            | 509     | 47998391    |                   | Meyers Hldg dba Firewood Cafe T1, Near C Checkpt  | in rear above fridge                               | 3116    | L03-0181    | Meyers Holdings, LLC dba Firewood Cafe Domestic Terminal FB Lease | 23102  | 200801-01-01T00:00:00 | 207512-01-01T00:00:00 | 284             | 291          | 7         | 1           | 7          | 0          | 7        | 0             | 0              | 0           | 0              | 0               | 100        | 0             | 0                       | 0                 | 0              | 
| 200801-01-01T00:00:00 | WA                | Water              | 195            | 514     | 47998405    |                   | Lori's Diner T1, Food Court                       | in kitchen remote                                  | 0       |             |                                                                   | 0      |                       |                       | 463             | 480          | 17        | 1           | 17         | 0          | 17       | 0             | 0              | 0           | 0              | 0               | 0          | 0             | 0                       | 0                 | 0              | 
| 200801-01-01T00:00:00 | WA                | Water              | 199            | 518     | 48000408    |                   | Willow Street New IT                              | meter room                                         | 3021    | L99-0292P   | Bayport Concessions dba Willow Street Woodfired Pizza IT FB Lease | 21719  | 200801-01-01T00:00:00 | 205012-01-01T00:00:00 | 1737            | 1749         | 12        | 1           | 12         | 0          | 12       | 0             | 0              | 0           | 0              | 0               | 100        | 0             | 0                       | 0                 | 0              | 
| 200801-01-01T00:00:00 | WA                | Water              | 201            | 520     | 48000411    |                   | Harbor Village New IT, North Food Court           | meter room                                         | 2643    | L99-0292I   | Harbor Airport LLC dba Harbor Village IT FB Lease                 | 17735  | 200801-01-01T00:00:00 | 205012-01-01T00:00:00 | 9174            | 9338         | 164       | 1           | 164        | 0          | 164      | 0             | 0              | 0           | 0              | 0               | 100        | 0             | 0                       | 0                 | 0              | 
| 200801-01-01T00:00:00 | NG                | Natural Gas        | 24             | 875     | 1014396     | 1014396           | IT North Fung Lum                                 | Courtyard 3 in Gas meter room                      | 2797    | L99-0292G   | Fung Lum Corporation IT FB Lease                                  | 19101  | 200801-01-01T00:00:00 | 205012-01-01T00:00:00 | 111695          | 113027       | 1332      | 1           | 1332       | 0          | 1332     | 0             | 0              | 0           | 0              | 0               | 100        | 0             | 0                       | 0                 | 0              | 
| 200801-01-01T00:00:00 | NG                | Natural Gas        | 39             | 890     | ?           | ?                 | T1-L9 Firewood Caf?                               | Near cart road at "C"                              | 3116    | L03-0181    | Meyers Holdings, LLC dba Firewood Cafe Domestic Terminal FB Lease | 23103  | 200801-01-01T00:00:00 | 205012-01-01T00:00:00 | 12061           | 12508        | 447       | 1           | 447        | 0          | 447      | 0             | 0              | 0           | 0              | 0               | 100        | 0             | 0                       | 0                 | 0              | 
```