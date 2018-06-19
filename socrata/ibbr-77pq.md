# Building Permits - January 1, 2005 thru December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-permits-january-1-2005-thru-december-31-2016) |
| Metadata | [Link](https://data.honolulu.gov/api/views/ibbr-77pq) |
| Data: JSON | [100 Rows](https://data.honolulu.gov/api/views/ibbr-77pq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.honolulu.gov/api/views/ibbr-77pq/rows.csv?max_rows=100) |
| Host | data.honolulu.gov |
| Id | ibbr-77pq |
| Name | Building Permits - January 1, 2005 thru December 31, 2016 |
| Category | Business |
| Created | 2017-01-06T23:14:07Z |
| Publication Date | 2017-01-09T21:22:46Z |

## Description

This file is a static view of Building Permit data.  This snapshot of data is an extract from the source database as of the moment of the snapshot's creation.  A snapshot does not reflect changes that occur in the live data source.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | numeric metric | jobid                      | jobid                      | number        | number        |
| Yes      | numeric metric | acceptedvalue              | acceptedvalue              | money         | money         |
| Yes      | series tag     | addition                   | addition                   | text          | text          |
| Yes      | series tag     | alteration                 | alteration                 | text          | text          |
| Yes      | numeric metric | buildingpermitno           | buildingpermitno           | number        | number        |
| Yes      | series tag     | buildingpermittype         | buildingpermittype         | text          | text          |
| Yes      | series tag     | contractor                 | contractor                 | text          | text          |
| Yes      | series tag     | contractorelectrical       | contractorelectrical       | text          | text          |
| Yes      | series tag     | contractorplumbing         | contractorplumbing         | text          | text          |
| Yes      | series tag     | curbingtypes               | curbingtypes               | text          | text          |
| Yes      | series tag     | demolition                 | demolition                 | text          | text          |
| Yes      | series tag     | electricalwork             | electricalwork             | text          | text          |
| Yes      | numeric metric | estimatedvalueofwork       | estimatedvalueofwork       | money         | money         |
| Yes      | series tag     | externalfilenum            | externalfilenum            | text          | text          |
| Yes      | series tag     | fence                      | fence                      | text          | text          |
| Yes      | numeric metric | finalstories               | finalstories               | number        | number        |
| Yes      | series tag     | floodhazardcomplied        | floodhazardcomplied        | text          | text          |
| Yes      | series tag     | floodhazardexempt          | floodhazardexempt          | text          | text          |
| Yes      | series tag     | foundationonly             | foundationonly             | text          | text          |
| Yes      | time           | issuedate                  | issuedate                  | calendar_date | calendar_date |
| Yes      | series tag     | newbuilding                | newbuilding                | text          | text          |
| Yes      | numeric metric | numroomsadd                | numroomsadd                | number        | number        |
| Yes      | numeric metric | numroomsdel                | numroomsdel                | number        | number        |
| Yes      | series tag     | occupancygroupassessed     | occupancygroupassessed     | text          | text          |
| Yes      | series tag     | occupancygroupcategory     | occupancygroupcategory     | text          | text          |
| Yes      | series tag     | occupancygroupresidential  | occupancygroupresidential  | text          | text          |
| Yes      | series tag     | otherwork                  | otherwork                  | text          | text          |
| Yes      | series tag     | planmaker                  | planmaker                  | text          | text          |
| Yes      | series tag     | plumbingwork               | plumbingwork               | text          | text          |
| Yes      | series tag     | pool                       | pool                       | text          | text          |
| Yes      | series tag     | proposeduse                | proposeduse                | text          | text          |
| Yes      | series tag     | repair                     | repair                     | text          | text          |
| Yes      | series tag     | retainingwall              | retainingwall              | text          | text          |
| Yes      | series tag     | shellonly                  | shellonly                  | text          | text          |
| Yes      | series tag     | sidewalktypes              | sidewalktypes              | text          | text          |
| Yes      | series tag     | statusdescription          | statusdescription          | text          | text          |
| Yes      | series tag     | tmk                        | tmk                        | text          | text          |
| Yes      | series tag     | electrical_vehicle_charger | electrical vehicle charger | text          | text          |
| Yes      | numeric metric | totalfloorarea             | totalfloorarea             | number        | number        |
| Yes      | series tag     | typesofconstructionactual  | typesofconstructionactual  | text          | text          |
| Yes      | series tag     | typesofconstructionmin     | typesofconstructionmin     | text          | text          |
| Yes      | numeric metric | bpfeescollected            | bpfeescollected            | money         | money         |
| Yes      | series tag     | ownershipassessed          | ownershipassessed          | text          | text          |
| Yes      | series tag     | structurecode              | structurecode              | text          | text          |
| No       |                | createddate                | createddate                | calendar_date | calendar_date |
| No       |                | completeddate              | completeddate              | text          | text          |
| Yes      | series tag     | commercialresidential      | commercialresidential      | text          | text          |
| Yes      | series tag     | electricalmeteronly        | electricalmeteronly        | text          | text          |
| Yes      | series tag     | ohana                      | ohana                      | text          | text          |
| Yes      | series tag     | solar                      | solar                      | text          | text          |
| Yes      | series tag     | solarvpinstallation        | solarvpinstallation        | text          | text          |
| Yes      | series tag     | accessorydwellingunitadu   | accessorydwellingunitadu   | text          | text          |
```

## Time Field

```ls
Value = issuedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = createddate,completeddate
```

## Data Commands

```ls
series e:ibbr-77pq d:2012-12-21T00:00:00.000Z t:solarvpinstallation=Y t:electrical_vehicle_charger=N t:alteration=N t:demolition=N t:ohana=N t:plumbingwork=N t:typesofconstructionactual=VN t:contractorplumbing=NONE t:floodhazardcomplied=N t:commercialresidential=Residential t:electricalmeteronly=N t:ownershipassessed="01 - Private" t:proposeduse="Single Family Dwelling" t:pool=N t:planmaker=NONE t:statusdescription="Permit application closed" t:foundationonly=N t:repair=N t:electricalwork=Y t:tmk=37012020 t:retainingwall=N t:shellonly=N t:accessorydwellingunitadu=N t:contractor="TEE'S ELECTRICAL AND MAINTENANCE LLC  
1419 ALEXANDER STREET  / State Lic: CT30385 / ID: 33427274 / PH: (808) 479-3333" t:occupancygroupassessed="01 - Single Family" t:structurecode="51 - SINGLE FAMILY" t:occupancygroupresidential=N t:newbuilding=N t:solar=N t:addition=N t:floodhazardexempt=N t:typesofconstructionmin=VN t:fence=N t:otherwork=Photovoltaic t:contractorelectrical="TEE'S ELECTRICAL AND MAINTENANCE LLC" t:externalfilenum=A2012-12-2439 t:occupancygroupcategory="R-3 Dwelling" m:bpfeescollected=0 m:acceptedvalue=30000 m:estimatedvalueofwork=30000 m:buildingpermitno=712890 m:jobid=48041598

series e:ibbr-77pq d:2015-04-08T00:00:00.000Z t:solarvpinstallation=Y t:electrical_vehicle_charger=N t:alteration=N t:demolition=N t:ohana=N t:plumbingwork=N t:typesofconstructionactual=VN t:contractorplumbing=NONE t:floodhazardcomplied=N t:commercialresidential=Residential t:electricalmeteronly=N t:ownershipassessed="01 - Private" t:proposeduse="Single Family Dwelling" t:pool=N t:planmaker=NONE t:statusdescription="Inspection(s) in Progress" t:foundationonly=N t:repair=N t:electricalwork=Y t:tmk=44035015 t:retainingwall=N t:shellonly=N t:accessorydwellingunitadu=N t:contractor="PACIFIC POWER & LIGHT LLC  
 PO BOX 5215  / State Lic: CT27588 / ID: 25742907 / PH: (800) 975-5112, (866) 424-0953, (808) 721-0264, (808) 927-3868" t:occupancygroupassessed="01 - Single Family" t:structurecode="51 - SINGLE FAMILY" t:occupancygroupresidential=N t:newbuilding=N t:solar=N t:addition=N t:floodhazardexempt=N t:typesofconstructionmin=VN t:fence=N t:otherwork=Photovoltaic t:contractorelectrical="PACIFIC POWER & LIGHT LLC" t:externalfilenum=A2015-04-0500 t:occupancygroupcategory="R-3 Dwelling" m:bpfeescollected=655 m:acceptedvalue=35000 m:estimatedvalueofwork=35000 m:buildingpermitno=764082 m:jobid=54789907

series e:ibbr-77pq d:2012-10-08T00:00:00.000Z t:solarvpinstallation=Y t:electrical_vehicle_charger=N t:alteration=N t:demolition=N t:ohana=N t:plumbingwork=N t:typesofconstructionactual=VN t:contractorplumbing=NONE t:floodhazardcomplied=N t:commercialresidential=Residential t:electricalmeteronly=N t:ownershipassessed="01 - Private" t:proposeduse="Single Family Dwelling" t:pool=N t:planmaker=NONE t:statusdescription="Permit application closed" t:foundationonly=N t:repair=N t:electricalwork=Y t:tmk=75020013 t:retainingwall=N t:shellonly=N t:accessorydwellingunitadu=N t:contractor="Hawaiian Island Solar  
416 Lokelau Place  / State Lic: CT24030 / ID: 17041093 / PH: (808) 371-8907, (808) 261-9740, (808) 256-5111, (808) 255-6585, (808) 394-5263, (808) 676-4270" t:occupancygroupassessed="01 - Single Family" t:structurecode="51 - SINGLE FAMILY" t:occupancygroupresidential=N t:newbuilding=N t:solar=N t:addition=N t:floodhazardexempt=N t:typesofconstructionmin=VN t:fence=N t:otherwork=Photovoltaic t:contractorelectrical="EYC ELECTRIC" t:externalfilenum=A2012-10-1090 t:occupancygroupcategory="R-3 Dwelling" m:bpfeescollected=0 m:acceptedvalue=54000 m:estimatedvalueofwork=54000 m:buildingpermitno=704814 m:jobid=47226112
```

## Meta Commands

```ls
metric m:jobid p:integer l:jobid t:dataTypeName=number

metric m:acceptedvalue p:double l:acceptedvalue t:dataTypeName=money

metric m:buildingpermitno p:integer l:buildingpermitno t:dataTypeName=number

metric m:estimatedvalueofwork p:double l:estimatedvalueofwork t:dataTypeName=money

metric m:finalstories p:integer l:finalstories t:dataTypeName=number

metric m:numroomsadd p:integer l:numroomsadd t:dataTypeName=number

metric m:numroomsdel p:integer l:numroomsdel t:dataTypeName=number

metric m:totalfloorarea p:double l:totalfloorarea t:dataTypeName=number

metric m:bpfeescollected p:integer l:bpfeescollected t:dataTypeName=money

entity e:ibbr-77pq l:"Building Permits - January 1, 2005 thru December 31, 2016" t:url=https://data.honolulu.gov/api/views/ibbr-77pq

property e:ibbr-77pq t:meta.view v:id=ibbr-77pq v:category=Business v:averageRating=0 v:name="Building Permits - January 1, 2005 thru December 31, 2016"

property e:ibbr-77pq t:meta.view.owner v:id=sr3i-nqxd v:screenName="Open Data" v:displayName="Open Data"

property e:ibbr-77pq t:meta.view.tableauthor v:id=sr3i-nqxd v:screenName="Open Data" v:roleName=administrator v:displayName="Open Data"
```

## Top Records

```ls
| jobid    | acceptedvalue | addition | alteration | buildingpermitno | buildingpermittype | contractor                                                                                                                                                                                                                                              | contractorelectrical                 | contractorplumbing | curbingtypes | demolition | electricalwork | estimatedvalueofwork | externalfilenum | fence | finalstories | floodhazardcomplied | floodhazardexempt | foundationonly | issuedate           | newbuilding | numroomsadd | numroomsdel | occupancygroupassessed | occupancygroupcategory | occupancygroupresidential | otherwork    | planmaker | plumbingwork | pool | proposeduse            | repair | retainingwall | shellonly | sidewalktypes | statusdescription         | tmk      | electrical_vehicle_charger | totalfloorarea | typesofconstructionactual | typesofconstructionmin | bpfeescollected | ownershipassessed | structurecode      | createddate         | completeddate | commercialresidential | electricalmeteronly | ohana | solar | solarvpinstallation | accessorydwellingunitadu | 
| ======== | ============= | ======== | ========== | ================ | ================== | ======================================================================================================================================================================================================================================================= | ==================================== | ================== | ============ | ========== | ============== | ==================== | =============== | ===== | ============ | =================== | ================= | ============== | =================== | =========== | =========== | =========== | ====================== | ====================== | ========================= | ============ | ========= | ============ | ==== | ====================== | ====== | ============= | ========= | ============= | ========================= | ======== | ========================== | ============== | ========================= | ====================== | =============== | ================= | ================== | =================== | ============= | ===================== | =================== | ===== | ===== | =================== | ======================== | 
| 48041598 | 30000         | N        | N          | 712890           |                    | TEE'S ELECTRICAL AND MAINTENANCE LLC 1419 ALEXANDER STREET / State Lic: CT30385 / ID: 33427274 / PH: (808) 479-3333                                                                                                                                     | TEE'S ELECTRICAL AND MAINTENANCE LLC | NONE               |              | N          | Y              | 30000                | A2012-12-2439   | N     |              | N                   | N                 | N              | 2012-12-21T00:00:00 | N           |             |             | 01 - Single Family     | R-3 Dwelling           | N                         | Photovoltaic | NONE      | N            | N    | Single Family Dwelling | N      | N             | N         |               | Permit application closed | 37012020 | N                          |                | VN                        | VN                     | 0               | 01 - Private      | 51 - SINGLE FAMILY | 2012-12-21T22:47:00 | 3/14/13 7:45  | Residential           | N                   | N     | N     | Y                   | N                        | 
| 54789907 | 35000         | N        | N          | 764082           |                    | PACIFIC POWER & LIGHT LLC PO BOX 5215 / State Lic: CT27588 / ID: 25742907 / PH: (800) 975-5112, (866) 424-0953, (808) 721-0264, (808) 927-3868                                                                                                          | PACIFIC POWER & LIGHT LLC            | NONE               |              | N          | Y              | 35000                | A2015-04-0500   | N     |              | N                   | N                 | N              | 2015-04-08T00:00:00 | N           |             |             | 01 - Single Family     | R-3 Dwelling           | N                         | Photovoltaic | NONE      | N            | N    | Single Family Dwelling | N      | N             | N         |               | Inspection(s) in Progress | 44035015 | N                          |                | VN                        | VN                     | 655             | 01 - Private      | 51 - SINGLE FAMILY | 2015-04-08T17:43:00 |               | Residential           | N                   | N     | N     | Y                   | N                        | 
| 47226112 | 54000         | N        | N          | 704814           |                    | Hawaiian Island Solar 416 Lokelau Place / State Lic: CT24030 / ID: 17041093 / PH: (808) 371-8907, (808) 261-9740, (808) 256-5111, (808) 255-6585, (808) 394-5263, (808) 676-4270                                                                        | EYC ELECTRIC                         | NONE               |              | N          | Y              | 54000                | A2012-10-1090   | N     |              | N                   | N                 | N              | 2012-10-08T00:00:00 | N           |             |             | 01 - Single Family     | R-3 Dwelling           | N                         | Photovoltaic | NONE      | N            | N    | Single Family Dwelling | N      | N             | N         |               | Permit application closed | 75020013 | N                          |                | VN                        | VN                     | 0               | 01 - Private      | 51 - SINGLE FAMILY | 2012-10-08T13:20:00 | 3/1/13 6:38   | Residential           | N                   | N     | N     | Y                   | N                        | 
| 47788244 | 22551         | N        | N          | 710206           |                    | Adon Construction 45-781-A Kam Hwy / State Lic: CT16511 / ID: 7185836 / PH: (808) 236-1110, (808) 236-1700, (808) 554-3244, (808) 845-3361, (808) 236-1110                                                                                              | Husky Electrical Services, Inc.      | NONE               |              | N          | Y              | 22551                | A2012-11-2959   | N     |              | N                   | N                 | N              | 2012-11-28T00:00:00 | N           |             |             | 01 - Single Family     | R-3 Dwelling           | N                         | Photovoltaic | NONE      | N            | N    | Single Family Dwelling | N      | N             | N         |               | Permit application closed | 39076113 | N                          |                | VN                        | VN                     | 0               | 01 - Private      | 51 - SINGLE FAMILY | 2012-11-28T08:59:00 | 3/12/13 6:40  | Residential           | N                   | N     | N     | Y                   | N                        | 
| 57908669 | 5747          | N        | N          | 788290           |                    | SUNRUN INSTALLATION SVS INC 94-1388 MOANIANI STREET, SUITE 215-216 / State Lic: CT28011 / ID: 26488664 / PH: (808) 202-0219                                                                                                                             | SUNRUN INSTALLATION SVS INC          | NONE               |              | N          | Y              | 5747                 | A2016-06-1067   | N     |              | N                   | N                 | N              | 2016-06-17T00:00:00 | N           |             |             | 01 - Single Family     | R-3 Dwelling           | N                         | Photovoltaic | NONE      | N            | N    | Single Family Dwelling | N      | N             | N         |               | Inspection(s) in Progress | *168476  | N                          |                | VN                        | VN                     | 127             | 01 - Private      | 51 - SINGLE FAMILY | 2016-06-17T15:00:00 |               | Residential           | N                   | N     | N     | Y                   | N                        | 
| 58914997 | 10000         | N        | N          | 795772           |                    | Hawaii Energy Connection, LLC 99-1350 Koaha Pl / State Lic: CT31046 / ID: 41043291 / PH: (808) 626-4486, (808) 954-6811, (808) 954-6825, (808) 954-6833, (808) 954-6818, (808) 623-4379, (808) 954-6815, (808) 954-6820, (808) 954-6825, (808) 524-7336 | Hawaii Energy Connection, LLC        | NONE               |              | N          | Y              | 10000                | A2016-11-1187   | N     |              | N                   | N                 | N              | 2016-11-23T00:00:00 | N           |             |             | 01 - Single Family     | R-3 Dwelling           | N                         | Photovoltaic | NONE      | N            | N    | Single Family Dwelling | N      | N             | N         |               | Inspection(s) in Progress | 41022070 | N                          |                | VN                        | VN                     | 211             | 01 - Private      | 51 - SINGLE FAMILY | 2016-11-23T09:54:00 |               | Residential           | N                   | N     | N     | Y                   | N                        | 
| 47226559 | 53000         | N        | N          | 704820           |                    | Hawaiian Island Solar 416 Lokelau Place / State Lic: CT24030 / ID: 17041093 / PH: (808) 371-8907, (808) 261-9740, (808) 256-5111, (808) 255-6585, (808) 394-5263, (808) 676-4270                                                                        | EYC ELECTRIC                         | NONE               |              | N          | Y              | 53000                | A2012-10-1096   | N     |              | N                   | N                 | N              | 2012-10-08T00:00:00 | N           |             |             | 01 - Single Family     | R-3 Dwelling           | N                         | Photovoltaic | NONE      | N            | N    | Single Family Dwelling | N      | N             | N         |               | Permit application closed | 32012056 | N                          |                | VN                        | VN                     | 0               | 01 - Private      | 51 - SINGLE FAMILY | 2012-10-08T13:52:00 | 3/5/13 7:39   | Residential           | N                   | N     | N     | Y                   | N                        | 
| 28063159 | 6200          | N        | N          | 626082           |                    | GIANT SOLAR 94-1147 HINA ST / State Lic: CT26914 / ID: 24510233 / PH: (808) 479-7999, (808) 721-3722, (808) 778-0160, (808) 677-1729, (808) 375-6544, (808) 479-7999, (808) 478-7998                                                                    | ANGEL ELECTRIC LLC                   | ALLENS PLUMBING    |              | N          | Y              | 6200                 | A2008-04-0595   | N     |              | N                   | N                 | N              | 2008-04-28T00:00:00 | N           |             |             | 01 - Single Family     | R-3 dwelling           | N                         |              | NONE      | Y            | N    | sfd                    | N      | N             | N         |               | Inspection(s) in Progress | 91016076 | N                          |                | VN                        | VN                     | 135             | 01 - Private      | 51 - SINGLE FAMILY | 2008-04-14T10:54:00 |               | Residential           | N                   | N     | Y     | N                   | N                        | 
| 56945908 | 1500          | N        | N          | 782934           |                    | NONE / State Lic: / ID: 11320462 / PH:                                                                                                                                                                                                                  | PAUMALU ELECTRIC INC                 | NONE               |              | N          | Y              | 1500                 | A2016-03-0043   | N     |              | N                   | N                 | N              | 2016-03-01T00:00:00 | N           |             |             | 01 - Single Family     | R-3 Dwelling           | N                         |              | NONE      | N            | N    | sfd                    | N      | N             | N         |               | Inspection(s) in Progress | 59019054 | N                          |                |                           |                        | 41              | 01 - Private      | 96 - ELECTRICAL    | 2016-03-01T11:47:00 |               | Residential           | Y                   | N     | N     | N                   | N                        | 
| 47699450 | 61000         | N        | N          | 709262           |                    | Alternate Energy, Inc. 803 Ahua St / State Lic: CT26041 / ID: 7002080 / PH: (808) 842-5853                                                                                                                                                              | Force Electric, Inc.                 | NONE               |              | N          | Y              | 61000                | A2012-11-1912   | N     |              | N                   | N                 | N              | 2012-11-18T00:00:00 | N           |             |             | 01 - Single Family     | R-3 Dwelling           | N                         | Photovoltaic | NONE      | N            | N    | Single Family Dwelling | N      | N             | N         |               | Permit application closed | 43059080 | N                          |                | VN                        | VN                     | 0               | 01 - Private      | 51 - SINGLE FAMILY | 2012-11-18T22:13:00 | 2/28/13 8:43  | Residential           | N                   | N     | N     | Y                   | N                        | 
```