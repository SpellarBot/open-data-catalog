# DOB NOW: Safety ? Facades Compliance Filings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-now-safety-facades-compliance-filings) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xubg-57si) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xubg-57si/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xubg-57si/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xubg-57si |
| Name | DOB NOW: Safety ? Facades Compliance Filings |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | dob, buildings, now, facades, compliance, filings |
| Created | 2016-09-09T15:34:48Z |
| Publication Date | 2017-04-20T19:34:51Z |

## Description

List of all Facades compliance filings submitted in DOB NOW.

## Columns

```ls
| Included | Schema Type | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | =========== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag  | tr6_no                          | TR6_NO                          | text          | text          |
| Yes      | series tag  | control_no                      | CONTROL_NO                      | text          | text          |
| Yes      | series tag  | filing_type                     | FILING_TYPE                     | text          | text          |
| Yes      | series tag  | cycle                           | CYCLE                           | text          | text          |
| Yes      | series tag  | bin                             | BIN                             | text          | text          |
| Yes      | series tag  | house_no                        | HOUSE_NO                        | text          | text          |
| Yes      | series tag  | street_name                     | STREET_NAME                     | text          | text          |
| Yes      | series tag  | borough                         | BOROUGH                         | text          | text          |
| Yes      | series tag  | block                           | BLOCK                           | text          | text          |
| Yes      | series tag  | lot                             | LOT                             | text          | text          |
| Yes      | series tag  | sequence_no                     | SEQUENCE_NO                     | text          | text          |
| Yes      | series tag  | submitted_on                    | SUBMITTED_ON                    | text          | text          |
| Yes      | series tag  | current_status                  | CURRENT_STATUS                  | text          | text          |
| Yes      | series tag  | qewi_name                       | QEWI_NAME                       | text          | text          |
| Yes      | series tag  | qewi_bus_name                   | QEWI_BUS_NAME                   | text          | text          |
| Yes      | series tag  | qewi_bus_street_name            | QEWI_BUS_STREET_NAME            | text          | text          |
| Yes      | series tag  | qewi_city                       | QEWI_CITY                       | text          | text          |
| Yes      | series tag  | qewi_state                      | QEWI_STATE                      | text          | text          |
| Yes      | series tag  | qewi_zip                        | QEWI_ZIP                        | text          | text          |
| Yes      | series tag  | qewi_nys_lic_no                 | QEWI_NYS_LIC_NO                 | text          | text          |
| Yes      | series tag  | owner_name                      | OWNER_NAME                      | text          | text          |
| Yes      | series tag  | owner_bus_name                  | OWNER_BUS_NAME                  | text          | text          |
| Yes      | series tag  | owner_bus_street_name           | OWNER_BUS_STREET_NAME           | text          | text          |
| Yes      | series tag  | owner_city                      | OWNER_CITY                      | text          | text          |
| Yes      | series tag  | owner_zip                       | OWNER_ZIP                       | text          | text          |
| Yes      | series tag  | owner_state                     | OWNER_STATE                     | text          | text          |
| Yes      | time        | filing_date                     | FILING_DATE                     | calendar_date | calendar_date |
| Yes      | series tag  | filing_status                   | FILING_STATUS                   | text          | text          |
| No       |             | prior_cycle_filing_date         | PRIOR_CYCLE_FILING_DATE         | calendar_date | calendar_date |
| Yes      | series tag  | prior_status                    | PRIOR_STATUS                    | text          | text          |
| No       |             | field_inspection_completed_date | FIELD_INSPECTION_COMPLETED_DATE | calendar_date | calendar_date |
| No       |             | qewi_signed_date                | QEWI_SIGNED_DATE                | calendar_date | calendar_date |
| Yes      | series tag  | late_filing_amt                 | LATE_FILING_AMT                 | text          | text          |
| Yes      | series tag  | failure_to_file_amt             | FAILURE_TO_FILE_AMT             | text          | text          |
| Yes      | series tag  | failure_to_collect_amt          | FAILURE_TO_COLLECT_AMT          | text          | text          |
| Yes      | series tag  | comments                        | COMMENTS                        | text          | text          |
```

## Time Field

```ls
Value = filing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = prior_cycle_filing_date,field_inspection_completed_date,qewi_signed_date
```

## Data Commands

```ls
series e:xubg-57si d:2011-12-12T05:00:00.000Z t:owner_bus_street_name="308 WEST 103 STREET, APT 8D" t:cycle=7 t:sequence_no=1 t:qewi_bus_street_name="1397 SECOND AVENUE. #117" t:control_no=706599 t:failure_to_file_amt=0 t:qewi_city="NEW YORK" t:street_name="WEST 103 STREET" t:failure_to_collect_amt=0 t:block=1890 t:borough=MANHATTAN t:qewi_name="LAWRENCE  TOBE" t:filing_type=Initial t:tr6_no=TR6-706599-7B-I1 t:qewi_bus_name="ANCHORETTE, INC" t:current_status=SWARMP t:owner_bus_name="CO-OP PRESIDENT" t:qewi_state=NY t:owner_city="NEW YORK" t:late_filing_amt=0 t:prior_status=SWARMP t:filing_status=SWARMP t:house_no=308 t:lot=28 t:submitted_on="2011-12-12 05:00:00" t:bin=1057183 m:row_number.xubg-57si=1

series e:xubg-57si d:2011-05-18T04:00:00.000Z t:owner_bus_street_name="155 RIVERSIDE DRIVE" t:cycle=7 t:sequence_no=1 t:qewi_bus_street_name="728 WESTWOOD AVENUE" t:control_no=706600 t:failure_to_file_amt=0 t:qewi_city="STATEN ISLAND" t:street_name="RIVERSIDE DRIVE" t:failure_to_collect_amt=0 t:block=1890 t:borough=MANHATTAN t:qewi_name="IRV L CHESNER" t:filing_type=Initial t:tr6_no=TR6-706600-7B-I1 t:qewi_bus_name="CHESNER IRV" t:current_status=SAFE t:owner_bus_name="305 RIVERSIDE CORP" t:qewi_state=NY t:owner_city="NEW YORK" t:late_filing_amt=0 t:prior_status=SAFE t:filing_status=SAFE t:house_no=305 t:lot=36 t:submitted_on="2011-05-18 04:00:00" t:bin=1057187 m:row_number.xubg-57si=2

series e:xubg-57si d:2012-06-28T04:00:00.000Z t:owner_bus_street_name="310 RIVERSIDE DRIVE" t:cycle=7 t:sequence_no=1 t:qewi_bus_street_name="1133 BROADWAY, SUITE 314" t:control_no=706601 t:failure_to_file_amt=0 t:qewi_city="NEW YORK" t:street_name="RIVERSIDE DRIVE" t:failure_to_collect_amt=0 t:block=1890 t:borough=MANHATTAN t:qewi_name="NICHOLAS M MELONE" t:filing_type=Initial t:tr6_no=TR6-706601-7B-I1 t:qewi_bus_name="ELONE ARCHITECTS" t:current_status=SAFE t:owner_bus_name="MASTER APTS, INC" t:qewi_state=NY t:owner_city="NEW YORK" t:late_filing_amt=0 t:prior_status=SAFE t:filing_status=SAFE t:house_no=310 t:lot=40 t:submitted_on="2012-06-28 04:00:00" t:bin=1057188 m:row_number.xubg-57si=3
```

## Meta Commands

```ls
metric m:row_number.xubg-57si p:long l:"Row Number"

entity e:xubg-57si l:"DOB NOW: Safety ? Facades Compliance Filings" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/xubg-57si

property e:xubg-57si t:meta.view v:id=xubg-57si v:category="Housing & Development" v:averageRating=0 v:name="DOB NOW: Safety ? Facades Compliance Filings" v:attribution="Department of Buildings (DOB)"

property e:xubg-57si t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xubg-57si t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| tr6_no           | control_no | filing_type | cycle | bin     | house_no | street_name     | borough   | block | lot  | sequence_no | submitted_on        | current_status | qewi_name          | qewi_bus_name                | qewi_bus_street_name           | qewi_city     | qewi_state | qewi_zip | qewi_nys_lic_no | owner_name | owner_bus_name              | owner_bus_street_name       | owner_city | owner_zip | owner_state | filing_date         | filing_status | prior_cycle_filing_date | prior_status | field_inspection_completed_date | qewi_signed_date    | late_filing_amt | failure_to_file_amt | failure_to_collect_amt | comments                                                                                             | 
| ================ | ========== | =========== | ===== | ======= | ======== | =============== | ========= | ===== | ==== | =========== | =================== | ============== | ================== | ============================ | ============================== | ============= | ========== | ======== | =============== | ========== | =========================== | =========================== | ========== | ========= | =========== | =================== | ============= | ======================= | ============ | =============================== | =================== | =============== | =================== | ====================== | ==================================================================================================== | 
| TR6-706599-7B-I1 | 706599     | Initial     | 7     | 1057183 | 308      | WEST 103 STREET | MANHATTAN | 1890  | 28   | 1           | 2011-12-12 05:00:00 | SWARMP         | LAWRENCE TOBE      | ANCHORETTE, INC              | 1397 SECOND AVENUE. #117       | NEW YORK      | NY         |          |                 |            | CO-OP PRESIDENT             | 308 WEST 103 STREET, APT 8D | NEW YORK   |           |             | 2011-12-12T05:00:00 | SWARMP        | 2006-03-27T05:00:00     | SWARMP       | 2011-10-14T04:00:00             | 2011-11-21T05:00:00 | 0               | 0                   | 0                      |                                                                                                      | 
| TR6-706600-7B-I1 | 706600     | Initial     | 7     | 1057187 | 305      | RIVERSIDE DRIVE | MANHATTAN | 1890  | 36   | 1           | 2011-05-18 04:00:00 | SAFE           | IRV L CHESNER      | CHESNER IRV                  | 728 WESTWOOD AVENUE            | STATEN ISLAND | NY         |          |                 |            | 305 RIVERSIDE CORP          | 155 RIVERSIDE DRIVE         | NEW YORK   |           |             | 2011-05-18T04:00:00 | SAFE          | 2006-12-15T05:00:00     | SAFE         | 2011-04-15T04:00:00             | 2011-05-06T04:00:00 | 0               | 0                   | 0                      |                                                                                                      | 
| TR6-706601-7B-I1 | 706601     | Initial     | 7     | 1057188 | 310      | RIVERSIDE DRIVE | MANHATTAN | 1890  | 40   | 1           | 2012-06-28 04:00:00 | SAFE           | NICHOLAS M MELONE  | ELONE ARCHITECTS             | 1133 BROADWAY, SUITE 314       | NEW YORK      | NY         |          |                 |            | MASTER APTS, INC            | 310 RIVERSIDE DRIVE         | NEW YORK   |           |             | 2012-06-28T04:00:00 | SAFE          | 2007-02-21T05:00:00     | SAFE         | 2012-06-06T04:00:00             | 2012-06-18T04:00:00 | 0               | 0                   | 0                      |                                                                                                      | 
| TR6-706602-7B-I1 | 706602     | Initial     | 7     | 1057197 | 885      | WEST END AVENUE | MANHATTAN | 1890  | 53   | 1           | 2012-08-20 04:00:00 | SAFE           | JAMES J BLUM       | JOSEPH K. BLUM CO. LLP       | 6 EAST 39TH STREET             | NEW YORK      | NY         |          |                 |            | 885 WEST END RESIDENTS CORP | 885 WEST END AVENUE         | NEW YORK   |           |             | 2012-08-20T04:00:00 | SAFE          | 2007-02-16T05:00:00     | SWARMP       | 2012-08-08T04:00:00             | 2013-04-23T04:00:00 | 0               | 0                   | 0                      | INTIAL FILING 08/20/2012 AND REJECTED 03/11/2013. RESUBMITTED 04/24/2013 AND ACCEPTED. FILED ON TIME | 
| TR6-706603-7B-I1 | 706603     | Initial     | 7     | 1057198 | 895      | WEST END AVENUE | MANHATTAN | 1890  | 61   | 1           | 2012-08-21 04:00:00 | SAFE           | JOHN P MURRAY      | CASEWORKS ARCHITECT, PLLC    | 80 5TH AVENUE,SUITE 1201       | NEW YORK      | NY         |          |                 |            | 895 WEST END AVENUE COOPERA | 333 7TH AVENUE, 5TH FLOOR   | NEW YORK   |           |             | 2012-08-21T04:00:00 | UNSAFE        | 2006-12-07T05:00:00     |              | 2012-08-16T04:00:00             | 2012-08-15T04:00:00 | 0               | 0                   | 0                      |                                                                                                      | 
| TR6-706604-7B-I1 | 706604     | Initial     | 7     | 1057200 | 306      | WEST 104 STREET | MANHATTAN | 1890  | 64   | 1           | 2012-01-04 05:00:00 | SAFE           | IRV CHESNER        | IRV CHESNER, PE, LLC         | 728 WESTWOOD AVENUE            | STATEN ISLAND | NY         |          |                 |            | 308 WEST 104 STREET LLC     | 244 WEST 54TH STREET        | NEW YORK   |           |             | 2012-01-04T05:00:00 | SAFE          | 2008-06-16T04:00:00     | SWARMP       | 2011-12-02T05:00:00             | 2011-12-22T05:00:00 | 2400            | 0                   | 0                      |                                                                                                      | 
| TR6-706605-7B-I1 | 706605     | Initial     | 7     | 1057207 | 315      | RIVERSIDE DRIVE | MANHATTAN | 1890  | 73   | 1           | 2012-07-17 04:00:00 | SWARMP         | JAMES R GAINFORT   | JRGAIA CONSULTING ARCHITECTS | 104 WEST 27TH ST 5TH FLOOR     | NEW YORK      | NY         |          |                 |            | 315 HOMES CORP              | 315 RIVERSIDE DRIVE         | NEW YORK   |           |             | 2012-07-17T04:00:00 | SWARMP        | 2007-02-21T05:00:00     | SAFE         | 2012-05-30T04:00:00             | 2013-01-29T05:00:00 | 0               | 0                   | 0                      | INITIAL FILING DATE 7/17/2012 REJECTED 12/28/12 RESUB 2/11/2013(CAW)                                 | 
| TR6-706606-7C-I1 | 706606     | Initial     | 7     | 1057209 | 320      | RIVERSIDE DRIVE | MANHATTAN | 1891  | 1    | 1           | 2013-02-15 05:00:00 | SWARMP         | HOWARD L ZIMMERMAN | HOWARD L ZIMMERMAN ARCH      | 11 WEST 30TH STREET .3RD FLOOR | NEW YORK      | NY         |          |                 |            | 320 RIVERSIDE APTS CORP     | 320 RIVERSIDE DRIVE         | NEW YORK   |           |             | 2013-02-15T05:00:00 | SWARMP        | 2007-02-16T05:00:00     | SWARMP       | 2013-02-04T05:00:00             | 2013-02-14T05:00:00 | 0               | 0                   | 0                      |                                                                                                      | 
| TR6-706608-7C-I1 | 706608     | Initial     | 7     | 1057215 | 905      | WEST END AVENUE | MANHATTAN | 1891  | 7502 | 1           | 2013-02-20 05:00:00 | SWARMP         | BRIAN M O'CONNOR   | BOND ENGINEERING PC          | 209 WEST 13 STREET             | NEW YORK      | NY         |          |                 |            | SAMSON MANAGEMENT CO        | 97 77 QUEENS BLVD           | REGO PARK  |           |             | 2013-02-20T05:00:00 | SWARMP        | 2005-10-28T04:00:00     | SAFE         | 2013-01-09T05:00:00             | 2013-02-05T05:00:00 | 0               | 0                   | 0                      | OLD LOT (17) NEW LOT 7502                                                                            | 
| TR6-706609-7C-I1 | 706609     | Initial     | 7     | 1057216 | 915      | WEST END AVENUE | MANHATTAN | 1891  | 26   | 1           | 2015-02-20 05:00:00 | UNSAFE         | DAVID SALAMON      | SALAMON ENGINEERING PLLC     | 55 WEST 39TH STREET, SUITE 303 | NEW YORK      | NY         |          |                 |            | LICHTER REAL ESTATE         | 35 WEST 36TH STREET         | NEW YORK   |           |             | 2015-02-20T05:00:00 | UNSAFE        | 2009-04-02T04:00:00     | UNSAFE       | 2015-02-16T05:00:00             | 2015-02-16T05:00:00 | 10000           | 1000                | 0                      |                                                                                                      | 
```