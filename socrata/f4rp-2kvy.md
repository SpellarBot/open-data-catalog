# CATS Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cats-permits) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/f4rp-2kvy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/f4rp-2kvy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/f4rp-2kvy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | f4rp-2kvy |
| Name | CATS Permits |
| Attribution | Department of Environmental Protection (DEP) |
| Category | Environment |
| Created | 2015-07-07T22:05:30Z |
| Publication Date | 2017-04-21T00:38:19Z |

## Description

Contains information on current boiler and industrial operation permits in New York City registered with DEP.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | requestid      | RequestID      | text          | number        |
| Yes      | series tag     | applicationid  | ApplicationID  | text          | text          |
| Yes      | series tag     | requesttype    | RequestType    | text          | text          |
| Yes      | series tag     | house          | House          | text          | text          |
| Yes      | series tag     | street         | Street         | text          | text          |
| Yes      | series tag     | borough        | Borough        | text          | text          |
| Yes      | numeric metric | bin            | Bin            | number        | number        |
| Yes      | series tag     | block          | Block          | text          | text          |
| Yes      | series tag     | lot            | Lot            | text          | text          |
| Yes      | series tag     | ownername      | OwnerName      | text          | text          |
| Yes      | time           | expirationdate | ExpirationDate | calendar_date | calendar_date |
| Yes      | series tag     | make           | Make           | text          | text          |
| Yes      | series tag     | model          | Model          | text          | text          |
| Yes      | series tag     | burnermake     | BurnerMake     | text          | text          |
| Yes      | series tag     | burnermodel    | BurnerModel    | text          | text          |
| Yes      | series tag     | primaryfuel    | PrimaryFuel    | text          | text          |
| Yes      | series tag     | secondaryfuel  | SecondaryFuel  | text          | text          |
| Yes      | numeric metric | quantity       | Quantity       | number        | number        |
| No       |                | issuedate      | IssueDate      | calendar_date | calendar_date |
| Yes      | series tag     | status         | status         | text          | text          |
| Yes      | series tag     | premisename    | PremiseName    | text          | text          |
```

## Time Field

```ls
Value = expirationdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issuedate
```

## Data Commands

```ls
series e:f4rp-2kvy d:1995-01-23T00:00:00.000Z t:model="NATIONAL/U.S. 11-16B" t:burnermake="INTEGRAL ATMOSPHERIC" t:primaryfuel=NATURALGAS t:status=APPROVED t:street="EAST 81 STREET" t:secondaryfuel=NONE t:block=01544 t:borough=MANHATTAN t:house=337 t:applicationid=CA000689 t:ownername="M &AMP; M ASSO/MARFAM RLTY.CO" t:lot=0015 t:burnermodel="INTEGRAL ATMOSPHERIC" t:requestid=87221 t:make="NATIONAL/U.S. 11-16B" t:requesttype=REGISTRATION m:quantity=1 m:bin=49850

series e:f4rp-2kvy d:2009-01-14T00:00:00.000Z t:model="FULTON, FB-010-A" t:burnermake="FULTON, INTEGRAL" t:primaryfuel=NO2FUEL t:status=APPROVED t:street="GLENWOOD ROAD" t:secondaryfuel=NONE t:block=07724 t:borough=BROOKLYN t:house=4016A t:applicationid=CA000697 t:ownername="STAR DRY CLEANERS" t:lot=0140 t:burnermodel="FULTON, INTEGRAL" t:requestid=54798 t:make="FULTON, FB-010-A" t:requesttype=REGISTRATION m:quantity=1 m:bin=213335

series e:f4rp-2kvy d:1989-07-01T00:00:00.000Z t:model="HYDROTHERM  MO-770" t:burnermake="WAYNE  MH(RT-16 RATING)" t:primaryfuel=NO2FUEL t:status=APPROVED t:street="PARSON BOULEVARD" t:secondaryfuel=NONE t:block=01111 t:borough=QUEENS t:house=41-37 t:applicationid=CA000776 t:ownername="ABRAHAM NAYMARK" t:lot=01111 t:burnermodel="WAYNE  MH(RT-16 RATING)" t:requestid=87707 t:make="HYDROTHERM  MO-770" t:requesttype=REGISTRATION m:quantity=1
```

## Meta Commands

```ls
metric m:bin p:long l:Bin t:dataTypeName=number

metric m:quantity p:long l:Quantity t:dataTypeName=number

entity e:f4rp-2kvy l:"CATS Permits" t:attribution="Department of Environmental Protection (DEP)" t:url=https://data.cityofnewyork.us/api/views/f4rp-2kvy

property e:f4rp-2kvy t:meta.view v:id=f4rp-2kvy v:category=Environment v:averageRating=0 v:name="CATS Permits" v:attribution="Department of Environmental Protection (DEP)"

property e:f4rp-2kvy t:meta.view.license v:name="Public Domain"

property e:f4rp-2kvy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:f4rp-2kvy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| requestid | applicationid | requesttype            | house | street           | borough   | bin    | block | lot   | ownername                              | expirationdate      | make                  | model                 | burnermake             | burnermodel            | primaryfuel | secondaryfuel | quantity | issuedate           | status   | premisename              | 
| ========= | ============= | ====================== | ===== | ================ | ========= | ====== | ===== | ===== | ====================================== | =================== | ===================== | ===================== | ====================== | ====================== | =========== | ============= | ======== | =================== | ======== | ======================== | 
| 87221     | CA000689      | REGISTRATION           | 337   | EAST 81 STREET   | MANHATTAN | 49850  | 01544 | 0015  | M & M ASSO/MARFAM RLTY.CO              | 1995-01-23T00:00:00 | NATIONAL/U.S. 11-16B  | NATIONAL/U.S. 11-16B  | INTEGRAL ATMOSPHERIC   | INTEGRAL ATMOSPHERIC   | NATURALGAS  | NONE          | 1        | 1989-01-03T00:00:00 | APPROVED |                          | 
| 54798     | CA000697      | REGISTRATION           | 4016A | GLENWOOD ROAD    | BROOKLYN  | 213335 | 07724 | 0140  | STAR DRY CLEANERS                      | 2009-01-14T00:00:00 | FULTON, FB-010-A      | FULTON, FB-010-A      | FULTON, INTEGRAL       | FULTON, INTEGRAL       | NO2FUEL     | NONE          | 1        | 1997-01-02T00:00:00 | APPROVED |                          | 
| 87707     | CA000776      | REGISTRATION           | 41-37 | PARSON BOULEVARD | QUEENS    |        | 01111 | 01111 | ABRAHAM NAYMARK                        | 1989-07-01T00:00:00 | HYDROTHERM MO-770     | HYDROTHERM MO-770     | WAYNE MH(RT-16 RATING) | WAYNE MH(RT-16 RATING) | NO2FUEL     | NONE          | 1        | 1989-04-03T00:00:00 | APPROVED |                          | 
| 114664    | CA000797      | CERTIFICATE TO OPERATE | 770   | GROTE STREET     | BRONX     | 98380  | 03100 | 0014  | NYC DEPT OF EDUCATION (DOE)            | 2000-09-17T00:00:00 | CLEAVER BROOKS FB 626 | CLEAVER BROOKS FB 626 | WEBSTER JB 2C-50-MH-UL | WEBSTER JB 2C-50-MH-UL | NATURALGAS  | NO2FUEL       | 2        | 1997-01-06T00:00:00 | APPROVED |                          | 
| 57715     | CA000892      | REGISTRATION           | 56-45 | 58 STREET        | QUEENS    | 59723  | 02664 | 0001  | PURO CORP.OF AMERICA                   | 1998-01-08T00:00:00 | PEERLESS JOT-TW-275   | PEERLESS JOT-TW-275   | BECKETT SF             | BECKETT SF             | NO2FUEL     | NONE          | 1        | 1992-01-01T00:00:00 | APPROVED |                          | 
| 93063     | CA000893      | REGISTRATION           | 315   | WEST 36 STREET   | MANHATTAN | 13595  | 00760 | 7501  | 36 LLC C/O WALTER & S                  | 2004-01-07T00:00:00 | FULTON FB-010A        | FULTON FB-010A        | FULTON INTEGRAL        | FULTON INTEGRAL        | NATURALGAS  | NONE          | 1        | 1993-01-04T00:00:00 | APPROVED |                          | 
| 61090     | CA000895      | REGISTRATION           | 1492  | PARK PLACE       | BROOKLYN  | 36599  | 01374 | 0011  | H.P.D./JOHN WARREN                     | 2001-01-10T00:00:00 | H.B. SMITH LO28A-S-8  | H.B. SMITH LO28A-S-8  | CARLIN 801-CRD         | CARLIN 801-CRD         | NO2FUEL     | NONE          | 1        | 1995-01-03T00:00:00 | APPROVED |                          | 
| 28200     | CA000897      | REGISTRATION           | 50    | ST MARK'S PLACE  | MANHATTAN | 6320   | 00449 | 0014  | ROMAN SOROBAY                          | 2018-01-14T00:00:00 | WEIL MCLAIN           | EGH-85-PI             | WEIL MCLAIN            | EGH-85-PI              | NATURALGAS  | NONE          | 1        | 2014-11-20T16:15:28 | APPROVED | ROMAN SOROBAY            | 
| 184828    | CA000486      | CERTIFICATE TO OPERATE | 24    | JORALEMON STREET | BROOKLYN  | 341552 | 00258 | 0017  | 24 JORALEMON                           | 2019-02-28T00:00:00 | FEDERAL               | FST-175               | ICI                    | DEG-84 (P)             | NATURALGAS  | NO2FUEL       | 2        | 2016-08-15T15:58:53 | APPROVED | JORALEMON REALTY NY LLC. | 
| 169110    | CA000488      | CERTIFICATE TO OPERATE | 241   | WEST 97 STREET   | MANHATTAN | 86955  | 01869 | 7503  | BROADWAY 98 CONDOMINIUM/COSMIN ARDKJAN | 2018-07-13T00:00:00 | FEDERAL               | FST 400               | HEV-E                  | DEG 175-P              | NO4FUEL     | NONE          | 2        | 2016-11-07T10:55:07 | APPROVED | WEINREB MANAGEMENT       | 
```