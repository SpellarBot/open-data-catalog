# Permit Application Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/permit-application-information) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nj5b-z2hw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nj5b-z2hw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nj5b-z2hw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nj5b-z2hw |
| Name | Permit Application Information |
| Attribution | Landmarks Preservation Commission (LPC) |
| Category | City Government |
| Created | 2016-07-01T19:52:24Z |
| Publication Date | 2016-07-05T17:49:04Z |

## Description

Contains information pertaining to permit applications for work to landmark sites submitted to and processed by LPC.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | numeric metric | docket              | docket              | number    | text        |
| No       |                | received_date       | received_date       | text      | text        |
| No       |                | address             | address             | text      | text        |
| Yes      | series tag     | borough             | Borough             | text      | text        |
| Yes      | series tag     | block               | block               | text      | number      |
| Yes      | series tag     | lot                 | lot                 | text      | number      |
| Yes      | series tag     | historic_district   | historic_district   | text      | text        |
| Yes      | series tag     | applicant_name      | applicant_name      | text      | text        |
| Yes      | series tag     | applicant_co        | applicant_co        | text      | text        |
| No       |                | applicant_address_1 | applicant_address_1 | text      | text        |
| No       |                | applicant_address_2 | applicant_address_2 | text      | text        |
| Yes      | series tag     | applicant_zip       | applicant_zip       | text      | text        |
| Yes      | series tag     | applicant_city      | applicant_city      | text      | text        |
| Yes      | series tag     | applicant_state     | applicant_state     | text      | text        |
| Yes      | series tag     | owner_name          | owner_name          | text      | text        |
| Yes      | series tag     | owner_co            | owner_co            | text      | text        |
| No       |                | owner_address_1     | owner_address_1     | text      | text        |
| No       |                | owner_address_2     | owner_address_2     | text      | text        |
| Yes      | series tag     | owner_zip           | owner_zip           | text      | text        |
| Yes      | series tag     | owner_city          | owner_city          | text      | text        |
| Yes      | series tag     | owner_state         | owner_state         | text      | text        |
| Yes      | series tag     | work_type           | work_type           | text      | text        |
| Yes      | series tag     | regulation_type     | regulation_type     | text      | text        |
| No       |                | issue_date          | issue_date          | text      | text        |
| Yes      | series tag     | permit_no           | permit_no           | text      | text        |
| No       |                | expiration_date     | expiration_date     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = received_date,address,applicant_address_1,applicant_address_2,owner_address_1,owner_address_2,issue_date,expiration_date
```

## Data Commands

```ls
series e:nj5b-z2hw d:2016-07-05T10:21:08.000Z t:owner_name="Laura Ray, Asst. Sec." t:owner_zip=10017 t:applicant_zip=10018 t:applicant_state=NY t:work_type="INTERIOR ALTERATIONS" t:applicant_co=Novation t:block=1501 t:borough=Manhattan t:applicant_name="David Trachtenberg" t:owner_city="New York" t:applicant_city="New York" t:historic_district="CARNEGIE HILL" t:regulation_type="CERTIFICATE OF NO EFFECT" t:owner_co="Madison - 90th Street Corporation" t:owner_state=NY t:lot=56 t:permit_no="CNE 41-40" m:docket=3771

series e:nj5b-z2hw d:2016-07-05T10:21:08.000Z t:owner_name="Edward Honig" t:owner_zip=11516 t:applicant_zip=11231 t:applicant_state=NY t:work_type="RESTORATIVE WORK" t:applicant_co="Benjamin R. M. Ellis Architect" t:block=285 t:borough=Brooklyn t:applicant_name="Benjamin R. M. Ellis" t:owner_city=Cedarhurst t:applicant_city=Brooklyn t:historic_district="COBBLE HILL" t:regulation_type="NOTICE OF COMPLIANCE" t:owner_co="Keren Realty LLc" t:owner_state=NY t:lot=4 t:permit_no="NOC 39-13" m:docket=3789

series e:nj5b-z2hw d:2016-07-05T10:21:08.000Z t:owner_name="Robert Galpern" t:owner_zip=10007 t:applicant_zip=11205 t:applicant_state=NY t:block=592 t:applicant_co="IPB Associates Design and Planning" t:borough=Manhattan t:applicant_name="Ian Peter Barnes" t:owner_city="New York" t:applicant_city=Brooklyn t:historic_district="GREENWICH VILLAGE" t:regulation_type="NOTICE OF COMPLIANCE" t:owner_co="African American Realty" t:owner_state=NY t:lot=18 t:permit_no="NOC 75-92" m:docket=3802
```

## Meta Commands

```ls
metric m:docket p:integer l:docket t:dataTypeName=number

entity e:nj5b-z2hw l:"Permit Application Information" t:attribution="Landmarks Preservation Commission (LPC)" t:url=https://data.cityofnewyork.us/api/views/nj5b-z2hw

property e:nj5b-z2hw t:meta.view v:id=nj5b-z2hw v:category="City Government" v:averageRating=0 v:name="Permit Application Information" v:attribution="Landmarks Preservation Commission (LPC)"

property e:nj5b-z2hw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nj5b-z2hw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | docket | received_date | address               | borough   | block | lot  | historic_district   | applicant_name                | applicant_co                       | applicant_address_1                                | applicant_address_2         | applicant_zip | applicant_city | applicant_state | owner_name                    | owner_co                                           | owner_address_1                     | owner_address_2  | owner_zip | owner_city | owner_state | work_type            | regulation_type                    | issue_date | permit_no  | expiration_date | 
| =========== | ====== | ============= | ===================== | ========= | ===== | ==== | =================== | ============================= | ================================== | ================================================== | =========================== | ============= | ============== | =============== | ============================= | ================================================== | =================================== | ================ | ========= | ========== | =========== | ==================== | ================================== | ========== | ========== | =============== | 
| 1467714068  | 3771   | 03-Jan-00     | 14 EAST 90TH STREET   | Manhattan | 1501  | 56   | CARNEGIE HILL       | David Trachtenberg            | Novation                           | 545 8th Avenue - Suite 20N                         |                             | 10018         | New York       | NY              | Laura Ray, Asst. Sec.         | Madison - 90th Street Corporation                  | 675 3rd Avenue                      |                  | 10017     | New York   | NY          | INTERIOR ALTERATIONS | CERTIFICATE OF NO EFFECT           | 19-Jan-00  | CNE 41-40  | 19-Jan-04       | 
| 1467714068  | 3789   | 03-Jan-00     | 327 HENRY STREET      | Brooklyn  | 285   | 4    | COBBLE HILL         | Benjamin R. M. Ellis          | Benjamin R. M. Ellis Architect     | 460 Sackett Street                                 |                             | 11231         | Brooklyn       | NY              | Edward Honig                  | Keren Realty LLc                                   | 218 Rockaway Turnpike - Rm 726      |                  | 11516     | Cedarhurst | NY          | RESTORATIVE WORK     | NOTICE OF COMPLIANCE               | 06-Jan-00  | NOC 39-13  |                 | 
| 1467714068  | 3802   | 03-Jan-00     | 361 6TH AVENUE        | Manhattan | 592   | 18   | GREENWICH VILLAGE   | Ian Peter Barnes              | IPB Associates Design and Planning | Brooklyn Navy Yard, Cumberland St. & Flushing Ave. | Building No 275 - Suite 405 | 11205         | Brooklyn       | NY              | Robert Galpern                | African American Realty                            | 28 Vesey Street Ste. 21-22          |                  | 10007     | New York   | NY          |                      | NOTICE OF COMPLIANCE               | 19-Jun-00  | NOC 75-92  |                 | 
| 1467714068  | 3780   | 03-Jan-00     | 210 RIVERSIDE DRIVE   | Manhattan | 1252  | 34   | RIVERSIDE- WEST END | Hannibal Galin                | EFG Consulting                     | P.O.B. 264                                         |                             | 10044         | New York       | NY              | Eric Lash, Agent              | 210 Riverside Tenants Corporation                  | Alexander Wol Building Management   | 1 DuPont Street  | 11803     | Plainview  | NY          | INTERIOR ALTERATIONS | CERTIFICATE OF NO EFFECT           | 06-Jan-00  | CNE 39-37  | 06-Jan-04       | 
| 1467714068  | 3827   | 03-Jan-00     | 17 HOLLYWOOD AVENUE   | Queens    | 8038  | 58   | DOUGLASTON          | Cherico King, R.A.            |                                    | 29-39 138th Street                                 | Suite 1C                    | 11354         | Flushing       | NY              | Peter Kramer                  |                                                    | 17 Hollywood Avenue                 |                  | 11363     | Flushing   | NY          | ADDITIONS            | MISCELLANEOUS/AMENDMENTS           | 07-Jan-00  | MISC 39-48 | 07-Jan-04       | 
| 1467714068  | 3768   | 03-Jan-00     | 31 PERRY STREET       | Manhattan | 613   | 7501 | GREENWICH VILLAGE   | John R. Coogan                |                                    | 435 Hudson Street                                  |                             | 10014         | New York       | NY              | Andrea Soros                  |                                                    | 31 Perry Street                     |                  | 10014     | New York   | NY          | ROOFTOP ADDITION     | CERTIFICATE OF NO EFFECT           | 25-Jan-00  | CNE 42-58  |                 | 
| 1467714068  | 3767   | 03-Jan-00     | 147-153 WAVERLY PLACE | Manhattan | 593   | 31   | GREENWICH VILLAGE   | Felicita Lennon               | D.C. Turano                        | 9920 4th Avenue                                    |                             | 11209         | Brooklyn       | NY              | David Sturner, Agent          | c/o 147 Waverly Place LLC                          | Murray Hill Property Management LLC | 440 Ninth Avenue | 10001     | New York   | NY          | INTERIOR ALTERATIONS | CERTIFICATE OF NO EFFECT           | 14-Jan-00  | CNE 40-82  | 14-Jan-04       | 
| 1467714068  | 3766   | 03-Jan-00     | 124 COLUMBIA HEIGHTS  | Brooklyn  | 208   | 101  | BROOKLYN HEIGHTS    | George Longoria               | Watchtower Bible & Tract Society   | 25 Columbia Heights                                |                             | 11201         | Brooklyn       | NY              | M.H. Larson                   | Watchtower Bible & Tract Society                   | 25 Columbia Heights                 |                  | 11201     | Brooklyn   | NY          | WINDOWS              | PERMIT FOR MINOR WORK              | 12-Jan-00  | PMW 40-41  | 12-Jan-04       | 
| 1467714068  | 3779   | 03-Jan-00     | 583 BROADWAY          | Manhattan | 512   | 7501 | SOHO-CAST IRON      | R Leocadi/ B Gillen / R Isler | CODE Consultants                   | 40 Worth Street, suite 1221                        |                             | 10013         | New York       | NY              | Lawrence Burnstein, President | 583-587 Broadway Condominium c/o Andrews Bldg. Co. | 666 Broadway, 12th flr              |                  | 10012     | New York   | NY          | INTERIOR ALTERATIONS | EXPEDITED CERTIFICATE OF NO EFFECT | 04-Jan-00  | XCNE 38-43 | 05-Jan-04       | 
| 1467714068  | 3826   | 03-Jan-00     | 355 GREENWICH STREET  | Manhattan | 181   | 7501 | TRIBECA WEST        | John C. Hulme, Architect      | H & H Building Consultants, Inc.   | 51 Hudson Street                                   |                             | 10013         | New York       | NY              | Candice Vanstryker, President |                                                    | 355 Greenwich Street                |                  | 10013     | New York   | NY          | INTERIOR ALTERATIONS | MISCELLANEOUS/AMENDMENTS           | 10-Jan-00  | MISC 39-87 | 12-Jan-04       | 
```