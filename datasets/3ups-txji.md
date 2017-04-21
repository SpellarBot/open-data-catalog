# Small Purchase Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/small-purchase-report) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/3ups-txji) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/3ups-txji/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/3ups-txji/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 3ups-txji |
| Name | Small Purchase Report |
| Attribution | Office of the mayor (OTM) |
| Category | City Government |
| Tags | small purchase report |
| Created | 2016-04-22T17:18:45Z |
| Publication Date | 2016-04-22T21:12:28Z |

## Description

On or before September thirtieth, two thousand and three, and on or before the last day of every quarter thereafter, the mayor or his or her designee shall submit to the council and the comptroller a report detailing each small purchase award made pursuant to this section during the quarter that ended three months before such report is due and for which information is required to be contained in the computerized data base maintained pursuant to subdivision a of section 6-116.2 of the administrative code.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | acronym     | Acronym     | text      | text        |
| Yes      | series tag     | vendorname  | VendorName  | text      | text        |
| Yes      | series tag     | contractid  | ContractID  | text      | text        |
| Yes      | series tag     | description | Description | text      | text        |
| No       |                | date        | Date        | text      | text        |
| Yes      | numeric metric | amount      | Amount      | money     | money       |
| Yes      | series tag     | cttyp_nm    | CTTYP_NM    | text      | text        |
| Yes      | series tag     | awd_meth_nm | AWD_METH_NM | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:3ups-txji d:2016-04-22T10:18:49.000Z t:awd_meth_nm="SMALL PURCH - IT- 25 K TO 100K" t:vendorname="XEROX CORPORATION" t:acronym=ACS t:description="XEROX DOCUSHARE LICENSE RENEWAL" t:contractid=CT106820161408178 t:cttyp_nm=WORK/LABOR m:amount=32000

series e:3ups-txji d:2016-04-22T10:18:49.000Z t:awd_meth_nm="SM PURCH GOODS SERVICES 100K" t:vendorname="RIVERDALE PAINTING CORP" t:acronym=ACS t:description="Blanket PO for on-call Painting Work
@Juveline Detention C" t:contractid=CT106820161406301 t:cttyp_nm=WORK/LABOR m:amount=80000

series e:3ups-txji d:2016-04-22T10:18:49.000Z t:awd_meth_nm="SM PURCH GOODS SERVICES 100K" t:vendorname="Alimade LLC" t:acronym=ACS t:description="FOOD CATERING SERVICES FOR THE CHILDRENS CENTER" t:contractid=CT106820161410297 t:cttyp_nm=WORK/LABOR m:amount=100000
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

entity e:3ups-txji l:"Small Purchase Report" t:attribution="Office of the mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/3ups-txji

property e:3ups-txji t:meta.view v:id=3ups-txji v:category="City Government" v:averageRating=0 v:name="Small Purchase Report" v:attribution="Office of the mayor (OTM)"

property e:3ups-txji t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:3ups-txji t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | acronym | vendorname                                 | contractid        | description                                                  | date      | amount | cttyp_nm   | awd_meth_nm                    | 
| =========== | ======= | ========================================== | ================= | ============================================================ | ========= | ====== | ========== | ============================== | 
| 1461320329  | ACS     | XEROX CORPORATION                          | CT106820161408178 | XEROX DOCUSHARE LICENSE RENEWAL                              | 05-Nov-15 | 32000  | WORK/LABOR | SMALL PURCH - IT- 25 K TO 100K | 
| 1461320329  | ACS     | RIVERDALE PAINTING CORP                    | CT106820161406301 | Blanket PO for on-call Painting Work @Juveline Detention C   | 14-Oct-15 | 80000  | WORK/LABOR | SM PURCH GOODS SERVICES 100K   | 
| 1461320329  | ACS     | Alimade LLC                                | CT106820161410297 | FOOD CATERING SERVICES FOR THE CHILDRENS CENTER              | 14-Dec-15 | 100000 | WORK/LABOR | SM PURCH GOODS SERVICES 100K   | 
| 1461320329  | ACS     | AMIGO CONSTRUCTION INC                     | CT106820161406201 | Repair/Replacement of Doors,frame Finish Hardware @ elcs     | 05-Oct-15 | 100000 | WORK/LABOR | SM PURCH GOODS SERVICES 100K   | 
| 1461320329  | ACS     | ALPHA ENVIRONMENTAL SERVICES INC           | CT106820161405747 | Repair Environmental Testing @ Various ELCS in NYC           | 05-Oct-15 | 80000  | WORK/LABOR | SM PURCH GOODS SERVICES 100K   | 
| 1461320329  | ACS     | PGA Mechanical Contractors Inc             | CT106820161406168 | On-call Repair of Refrigerators, Freezers @ ELCS in NY       | 03-Dec-15 | 80000  | WORK/LABOR | SM PURCH GOODS SERVICES 100K   | 
| 1461320329  | ACS     | DIVERSITY SERVICES                         | CT106820161411926 | Temporary Cooks svcs @ various juvenile detentions in NYC    | 16-Dec-15 | 99000  | WORK/LABOR | SM PURCH GOODS SERVICES 100K   | 
| 1461320329  | ACS     | Heather Henderson                          | CT106820161409211 | CONSULTANT SERVICES                                          | 10-Nov-15 | 100000 | CONSULTANT | SM PURCH GOODS SERVICES 100K   | 
| 1461320329  | ACS     | LOMAX SECURITY SYSTEMS INC                 | CT106820161406017 | on-call repair and replacement of electronic security system | 05-Nov-15 | 90000  | WORK/LABOR | SM PURCH GOODS SERVICES 100K   | 
| 1461320329  | ACS     | EXECUTIVE SAFETY & HEALTH CONSULTANTS INC. | CT106820161403782 | RTW/VDT/WPV TRAINING                                         | 20-Oct-15 | 97650  | WORK/LABOR | SM PURCH GOODS SERVICES 100K   | 
```