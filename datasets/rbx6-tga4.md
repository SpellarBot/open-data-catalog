# DOB NOW: Build ? Approved Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-now-build-approved-permits) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rbx6-tga4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rbx6-tga4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rbx6-tga4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rbx6-tga4 |
| Name | DOB NOW: Build ? Approved Permits |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | dob, buildings, permits |
| Created | 2016-05-26T13:36:30Z |
| Publication Date | 2017-03-23T14:35:05Z |

## Description

List of all approved permits in DOB NOW

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================== | ============= | ============= |
| Yes      | series tag     | job_filing_number                    | Job Filing Number                    | text          | text          |
| Yes      | series tag     | filing_reason                        | Filing Reason                        | text          | text          |
| Yes      | series tag     | house_no                             | House No                             | text          | text          |
| Yes      | series tag     | street_name                          | Street Name                          | text          | text          |
| Yes      | series tag     | borough                              | Borough                              | text          | text          |
| Yes      | series tag     | lot                                  | LOT                                  | text          | text          |
| Yes      | numeric metric | bin                                  | Bin                                  | number        | text          |
| Yes      | series tag     | block                                | Block                                | text          | text          |
| Yes      | series tag     | c_b_no                               | C B NO                               | text          | text          |
| Yes      | series tag     | apt_condo_no_s                       | Apt/Condo No(s)                      | text          | text          |
| Yes      | series tag     | work_on_floor                        | Work on Floor                        | text          | text          |
| Yes      | series tag     | work_type                            | Work Type                            | text          | text          |
| Yes      | series tag     | permittee_s_license_type             | Permittee's License Type             | text          | text          |
| Yes      | series tag     | applicant_license                    | Applicant License #                  | text          | text          |
| Yes      | series tag     | applicant_first_name                 | Applicant First Name                 | text          | text          |
| Yes      | series tag     | applicant_middle_name                | Applicant Middle Name                | text          | text          |
| Yes      | series tag     | applicant_last_name                  | Applicant Last Name                  | text          | text          |
| Yes      | series tag     | applicant_business_name              | Applicant Business Name              | text          | text          |
| No       |                | applicant_business_address           | Applicant Business Address           | text          | text          |
| Yes      | series tag     | filing_representative_first_name     | Filing Representative First Name     | text          | text          |
| Yes      | series tag     | filing_representative_middle_initial | Filing Representative Middle Initial | text          | text          |
| Yes      | series tag     | filing_representative_last_name      | Filing Representative Last Name      | text          | text          |
| Yes      | series tag     | filing_representative_business_name  | Filing Representative Business Name  | text          | text          |
| Yes      | series tag     | work_permit                          | Work Permit                          | text          | text          |
| Yes      | time           | approved_date                        | Approved Date                        | calendar_date | calendar_date |
| No       |                | issued_date                          | Issued Date                          | calendar_date | calendar_date |
| No       |                | expired_date                         | Expired Date                         | calendar_date | calendar_date |
| Yes      | series tag     | job_description                      | Job Description                      | text          | text          |
| Yes      | numeric metric | estimated_job_costs                  | Estimated Job Costs                  | number        | text          |
| Yes      | series tag     | owner_business_name                  | Owner Business Name                  | text          | text          |
| Yes      | series tag     | owner_name                           | Owner Name                           | text          | text          |
| Yes      | series tag     | owner_street_address                 | Owner Street Address                 | text          | text          |
| Yes      | series tag     | owner_city                           | Owner City                           | text          | text          |
| Yes      | series tag     | owner_state                          | Owner State                          | text          | text          |
| Yes      | series tag     | owner_zip_code                       | Owner Zip Code                       | text          | text          |
```

## Time Field

```ls
Value = approved_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = applicant_business_address,issued_date,expired_date
```

## Data Commands

```ls
series e:rbx6-tga4 d:2017-02-03T19:00:00.000Z t:owner_business_name=PR t:applicant_last_name=DEMARINIS t:owner_name="CHRIS CHIN" t:applicant_license=001549 t:owner_street_address="139 CENTRE ST" t:job_filing_number=M00000200-I1 t:filing_representative_last_name=FRANCIS t:street_name="CANAL STREET" t:work_type=Plumbing t:owner_zip_code=10013 t:block=231 t:borough=MANHATTAN t:owner_city="NEW YORK" t:work_on_floor=CEL,001-003 t:filing_reason="Initial Permit" t:applicant_business_name={CDEEE3D5-1DB0-E611-8111-005056B627E6} t:applicant_first_name=ALESSANDRO t:permittee_s_license_type=P t:owner_state=NY t:house_no=303 t:filing_representative_first_name=BERDEENA t:lot=2 t:work_permit=M00000200-I1-PL t:c_b_no=102 t:job_description="RELOCATION OF EXISTING GAS METER, REPLACEMENT OF GAS PIPING THROUGHOUT BUILDING, INSTALLATION OF NEW GAS HEATERS AND HOT WATER HEATER; NO CHANGE TO USE, OCCUPANCY OR EGRESS." m:bin=1003006 m:estimated_job_costs=11500

series e:rbx6-tga4 d:2016-12-07T05:00:00.000Z t:applicant_last_name=POLADIAN t:owner_name="JACOB MAYER" t:applicant_license=002025 t:job_filing_number=Q00000149-I1 t:owner_street_address="277 LODI STREET" t:street_name="FLUSHING AVENUE" t:work_type=Plumbing t:owner_zip_code=07601 t:block=3412 t:borough=QUEENS t:owner_city=HACKENSACK t:work_on_floor="001, 002" t:filing_reason="Initial Permit" t:applicant_business_name={776FF439-6EB7-E611-8110-005056B627E4} t:applicant_first_name=DUANE t:permittee_s_license_type=P t:owner_state=NJ t:house_no=1710 t:lot=47 t:work_permit=Q00000149-I1-PL t:c_b_no=405 t:job_description="INSTALLATION OF NEW GAS METER AND GAS PIPE TO DISTRIBUTED EXISTING GAS FURNACE." m:bin=4443075 m:estimated_job_costs=12000

series e:rbx6-tga4 d:2016-06-23T04:00:00.000Z t:owner_business_name="Lincoln Center for the Performing" t:applicant_last_name=MITCHELL t:owner_name="PETER FLAMM" t:applicant_license=000422 t:job_filing_number=M00000044-I1 t:owner_street_address="146 WEST 65 STREET" t:street_name="west 65 street" t:work_type=Sprinkler t:owner_zip_code=NY t:block=1137 t:borough=MANHATTAN t:owner_city="NEW YORK" t:work_on_floor=22 t:filing_reason="Initial Permit" t:applicant_business_name={E47D7D34-7D38-E611-810E-005056B627E6} t:applicant_first_name=THOMAS t:permittee_s_license_type=F t:owner_state=NY t:house_no=165 t:lot=7501 t:work_permit=M00000044-I1-EW-SP t:c_b_no=107 t:job_description="HEREWITH FILING SPRINKLER APPLICATION FOR REMOVAL, RELOCATION AND INSTALLATION OF NEW SPRINKLER HEADS ON 22ND FLOOR AS PER PLANS ATTACHED. NO CHANGE TO USE, EGRESS OR OCCUPANCY." m:bin=1077844 m:estimated_job_costs=14000
```

## Meta Commands

```ls
metric m:bin p:integer l:Bin t:dataTypeName=number

metric m:estimated_job_costs p:integer l:"Estimated Job Costs" t:dataTypeName=number

entity e:rbx6-tga4 l:"DOB NOW: Build ? Approved Permits" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/rbx6-tga4

property e:rbx6-tga4 t:meta.view v:id=rbx6-tga4 v:category="Housing & Development" v:averageRating=0 v:name="DOB NOW: Build ? Approved Permits" v:attribution="Department of Buildings (DOB)"

property e:rbx6-tga4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rbx6-tga4 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| job_filing_number | filing_reason  | house_no | street_name     | borough   | lot  | bin     | block | c_b_no | apt_condo_no_s | work_on_floor | work_type | permittee_s_license_type | applicant_license | applicant_first_name | applicant_middle_name | applicant_last_name | applicant_business_name                | applicant_business_address | filing_representative_first_name | filing_representative_middle_initial | filing_representative_last_name | filing_representative_business_name | work_permit        | approved_date       | issued_date         | expired_date        | job_description                                                                                                                                                                                                                       | estimated_job_costs | owner_business_name               | owner_name           | owner_street_address | owner_city      | owner_state | owner_zip_code | 
| ================= | ============== | ======== | =============== | ========= | ==== | ======= | ===== | ====== | ============== | ============= | ========= | ======================== | ================= | ==================== | ===================== | =================== | ====================================== | ========================== | ================================ | ==================================== | =============================== | =================================== | ================== | =================== | =================== | =================== | ===================================================================================================================================================================================================================================== | =================== | ================================= | ==================== | ==================== | =============== | =========== | ============== | 
| M00000200-I1      | Initial Permit | 303      | CANAL STREET    | MANHATTAN | 2    | 1003006 | 231   | 102    |                | CEL,001-003   | Plumbing  | P                        | 001549            | ALESSANDRO           |                       | DEMARINIS           | {CDEEE3D5-1DB0-E611-8111-005056B627E6} |                            | BERDEENA                         |                                      | FRANCIS                         |                                     | M00000200-I1-PL    | 2017-02-03T19:00:00 | 2017-02-03T05:00:00 | 2017-06-01T04:00:00 | RELOCATION OF EXISTING GAS METER, REPLACEMENT OF GAS PIPING THROUGHOUT BUILDING, INSTALLATION OF NEW GAS HEATERS AND HOT WATER HEATER; NO CHANGE TO USE, OCCUPANCY OR EGRESS.                                                         | 11500               | PR                                | CHRIS CHIN           | 139 CENTRE ST        | NEW YORK        | NY          | 10013          | 
| Q00000149-I1      | Initial Permit | 1710     | FLUSHING AVENUE | QUEENS    | 47   | 4443075 | 3412  | 405    |                | 001, 002      | Plumbing  | P                        | 002025            | DUANE                |                       | POLADIAN            | {776FF439-6EB7-E611-8110-005056B627E4} |                            |                                  |                                      |                                 |                                     | Q00000149-I1-PL    | 2016-12-07T05:00:00 | 2016-12-07T05:00:00 | 2016-12-12T05:00:00 | INSTALLATION OF NEW GAS METER AND GAS PIPE TO DISTRIBUTED EXISTING GAS FURNACE.                                                                                                                                                       | 12000               |                                   | JACOB MAYER          | 277 LODI STREET      | HACKENSACK      | NJ          | 07601          | 
| M00000044-I1      | Initial Permit | 165      | west 65 street  | MANHATTAN | 7501 | 1077844 | 1137  | 107    |                | 22            | Sprinkler | F                        | 000422            | THOMAS               |                       | MITCHELL            | {E47D7D34-7D38-E611-810E-005056B627E6} |                            |                                  |                                      |                                 |                                     | M00000044-I1-EW-SP | 2016-06-23T04:00:00 | 2016-06-23T12:15:04 | 2017-01-24T05:00:00 | HEREWITH FILING SPRINKLER APPLICATION FOR REMOVAL, RELOCATION AND INSTALLATION OF NEW SPRINKLER HEADS ON 22ND FLOOR AS PER PLANS ATTACHED. NO CHANGE TO USE, EGRESS OR OCCUPANCY.                                                     | 14000               | Lincoln Center for the Performing | PETER FLAMM          | 146 WEST 65 STREET   | NEW YORK        | NY          | NY             | 
| Q00000194-I1      | Initial Permit | 67-01    | 215 STREET      | QUEENS    | 35   | 4163126 | 7627  | 411    |                | CEL           | Plumbing  | P                        | 002025            | DUANE                |                       | POLADIAN            | {776FF439-6EB7-E611-8110-005056B627E4} |                            |                                  |                                      |                                 |                                     | Q00000194-I1-PL    | 2017-01-20T05:00:00 | 2017-01-27T05:00:00 | 2017-12-12T05:00:00 | Proposed replacement of existing 1' gas pipe from gas meter to HWH and furnace. Also, to replace existing HWH and furnace with new equipment in cellar. No change in use, egress and occupancy.                                       | 4500                |                                   | BI CAI ZHENG         | 67-01 215TH ST       | OAKLAND GARDENS | NY          | 11364          | 
| B00000119-I1      | Initial Permit | 642      | DRIGGS AVENUE   | BROOKLYN  | 25   | 3321245 | 2352  | 301    |                | CEL           | Plumbing  | P                        | 001876            | YEONG                |                       | HEO                 | {3CFC0C4F-7E64-E611-810F-005056B627E4} |                            |                                  |                                      |                                 |                                     | B00000119-I1-PL    | 2016-12-07T13:23:00 | 2016-12-07T05:00:00 | 2017-11-08T05:00:00 | INSTALLATION OF HOT WATER HEATER, STORAGE TANK, SUMP PUMP AND GAS METER IN CELLAR. THIS APPLICATION IS IN CONJUNCTION WITH APPLICATION# 321153504. NO CHANGE IN USE, MEANS OF EGRESS OR OCCUPANCY IS INVOLVED UNDER THIS APPLICATION. | 16000               | CARDINAL PROPERTIES LLC           | DOBRIVOYE FILIPOVICH | 642 DRIGGS AVENUE    | BROOKLYN        | NY          | 11211          | 
| M00000111-I1      | Initial Permit | 31       | WALKER STREET   | MANHATTAN | 25   | 1079007 | 193   | 101    |                | 4th           | Sprinkler | F                        | 000653            | ALESSANDRO           |                       | DEMARINIS           | {CDEEE3D5-1DB0-E611-8111-005056B627E6} |                            | BERDEENA                         |                                      | FRANCIS                         |                                     | M00000111-I1-EW-SP | 2016-12-14T05:00:00 | 2016-12-14T05:00:00 | 2017-06-01T04:00:00 | MODIFICATION OF EXISTING SPRINKLER SYSTEM ON 4TH FLOOR TO ACCOMMODATE NEW PARTITION LAYOUT. NO CHANGE IN USE (U.G.), OCCUPANCY OR EGRESS.                                                                                             | 9000                | ONLY PROPERTIES LLC               | ROBERT MOSKOWITZ     | 70 LAFAYETTE STREET  | NEW YORK        | NY          | 10013          | 
| B00000139-I1      | Initial Permit | 48       | Cedar Street    | BROOKLYN  | 1    | 3387647 | 3232  | 304    |                | 7, 8          | Sprinkler | F                        | 000712            | THOMAS               |                       | SMITH               | {FAD60BD3-088B-E611-8110-005056B627E4} |                            |                                  |                                      |                                 |                                     | B00000139-I1-EW-SP | 2016-10-06T04:00:00 | 2016-10-06T04:00:00 | 2017-03-21T04:00:00 | Addition of a dry pipe sprinkler system for the 8th floor corridor only. No change in use, egress, or occupancy under this application.                                                                                               | 8000                | Buena Vida Care Center            | NEIL LEVITT          | 48 CEDAR STREET      | BROOKLYN        | NY          | 11221          | 
```