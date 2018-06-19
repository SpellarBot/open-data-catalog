# Food Establishment Inspection Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-establishment-inspection-data-d4465) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/f29f-zza5) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/f29f-zza5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/f29f-zza5/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | f29f-zza5 |
| Name | Food Establishment Inspection Data |
| Attribution | Public Health - Seattle & King County |
| Category | Health |
| Tags | government, health, restaurant inspections, violations, closures, food safety |
| Created | 2010-10-04T14:40:02Z |
| Publication Date | 2017-04-20T14:18:18Z |

## Description

Health Department inspection results for food service establishments in King County, 2006 to the present. This data is organized by Business / Inspection Date / Violation. Each row in this dataset is an inspection, and if an inspection at a particular buiness results in multiple violations there will be multiple rows for that business with the same Inspection_Serial_Num. This dataset was last updated on 04/19/2017 and is current from 1/1/2006 to 04/14/2017.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | name                       | Name                       | text          | text          |
| Yes      | series tag     | program_identifier         | Program Identifier         | text          | text          |
| Yes      | time           | inspection_date            | Inspection Date            | calendar_date | calendar_date |
| Yes      | series tag     | description                | Description                | text          | text          |
| No       |                | address                    | Address                    | text          | text          |
| Yes      | series tag     | city                       | City                       | text          | text          |
| Yes      | series tag     | zip_code                   | Zip Code                   | text          | text          |
| Yes      | series tag     | phone                      | Phone                      | text          | text          |
| Yes      | numeric metric | longitude                  | Longitude                  | number        | number        |
| Yes      | numeric metric | latitude                   | Latitude                   | number        | number        |
| Yes      | series tag     | inspection_business_name   | Inspection Business Name   | text          | text          |
| Yes      | series tag     | inspection_type            | Inspection Type            | text          | text          |
| Yes      | numeric metric | inspection_score           | Inspection Score           | number        | number        |
| Yes      | series tag     | inspection_result          | Inspection Result          | text          | text          |
| Yes      | series tag     | inspection_closed_business | Inspection Closed Business | checkbox      | checkbox      |
| Yes      | series tag     | violation_type             | Violation Type             | flag          | flag          |
| Yes      | series tag     | violation_description      | Violation Description      | text          | text          |
| Yes      | numeric metric | violation_points           | Violation Points           | number        | number        |
| Yes      | series tag     | business_id                | Business_ID                | text          | text          |
| Yes      | series tag     | inspection_serial_num      | Inspection_Serial_Num      | text          | text          |
| Yes      | series tag     | violation_record_id        | Violation_Record_ID        | text          | text          |
| Yes      | series tag     | grade                      | Grade                      | text          | text          |
```

## Time Field

```ls
Value = inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:f29f-zza5 d:2017-04-20T14:15:56.000Z t:phone="(206) 938-5665" t:zip_code=98126 t:description="Seating 0-12 - Risk Category I" t:name="@ THE SHACK, LLC" t:business_id=PR0048053 t:program_identifier="SHACK COFFEE" t:city=Seattle m:longitude=-122.3709134945 m:latitude=47.5704253956 m:violation_points=0

series e:f29f-zza5 d:2017-01-24T00:00:00.000Z t:inspection_business_name="10 MERCER RESTAURANT" t:inspection_result=Unsatisfactory t:zip_code=98109 t:inspection_type="Routine Inspection/Field Review" t:violation_description="4300 - Non-food contact surfaces maintained and clean" t:city=Seattle t:inspection_closed_business=false t:violation_record_id=IV43WZVLN t:violation_type=blue t:inspection_serial_num=DAHSIBSJT t:description="Seating 13-50 - Risk Category III" t:name="10 MERCER RESTAURANT" t:business_id=PR0049572 t:grade=2 t:program_identifier="10 MERCER RESTAURANT" m:inspection_score=10 m:longitude=-122.3561914741 m:latitude=47.6250635431 m:violation_points=3

series e:f29f-zza5 d:2017-01-24T00:00:00.000Z t:inspection_business_name="10 MERCER RESTAURANT" t:inspection_result=Unsatisfactory t:zip_code=98109 t:inspection_type="Routine Inspection/Field Review" t:violation_description="4800 - Physical facilities properly installed,..." t:city=Seattle t:inspection_closed_business=false t:violation_record_id=IVCQ1ZIV0 t:violation_type=blue t:inspection_serial_num=DAHSIBSJT t:description="Seating 13-50 - Risk Category III" t:name="10 MERCER RESTAURANT" t:business_id=PR0049572 t:grade=2 t:program_identifier="10 MERCER RESTAURANT" m:inspection_score=10 m:longitude=-122.3561914741 m:latitude=47.6250635431 m:violation_points=2
```

## Meta Commands

```ls
metric m:longitude p:long l:Longitude t:dataTypeName=number

metric m:latitude p:long l:Latitude t:dataTypeName=number

metric m:inspection_score p:long l:"Inspection Score" t:dataTypeName=number

metric m:violation_points p:long l:"Violation Points" t:dataTypeName=number

entity e:f29f-zza5 l:"Food Establishment Inspection Data" t:attribution="Public Health - Seattle & King County" t:url=https://data.kingcounty.gov/api/views/f29f-zza5

property e:f29f-zza5 t:meta.view v:id=f29f-zza5 v:category=Health v:attributionLink=http://www.kingcounty.gov/healthservices/health/ehs/foodsafety/inspections.aspx v:averageRating=0 v:name="Food Establishment Inspection Data" v:attribution="Public Health - Seattle & King County"

property e:f29f-zza5 t:meta.view.license v:name="Public Domain"

property e:f29f-zza5 t:meta.view.owner v:id=e663-xk3s v:screenName=drakec v:displayName=drakec

property e:f29f-zza5 t:meta.view.tableauthor v:id=e663-xk3s v:screenName=drakec v:roleName=publisher v:displayName=drakec
```

## Top Records

```ls
| name                 | program_identifier   | inspection_date     | description                       | address            | city    | zip_code | phone          | longitude       | latitude      | inspection_business_name | inspection_type                 | inspection_score | inspection_result | inspection_closed_business | violation_type | violation_description                                                                   | violation_points | business_id | inspection_serial_num | violation_record_id | grade | 
| ==================== | ==================== | =================== | ================================= | ================== | ======= | ======== | ============== | =============== | ============= | ======================== | =============================== | ================ | ================= | ========================== | ============== | ======================================================================================= | ================ | =========== | ===================== | =================== | ===== | 
| @ THE SHACK, LLC     | SHACK COFFEE         |                     | Seating 0-12 - Risk Category I    | 2920 SW AVALON WAY | Seattle | 98126    | (206) 938-5665 | -122.3709134945 | 47.5704253956 |                          |                                 |                  |                   |                            |                |                                                                                         | 0                | PR0048053   |                       |                     |       | 
| 10 MERCER RESTAURANT | 10 MERCER RESTAURANT | 2017-01-24T00:00:00 | Seating 13-50 - Risk Category III | 10 MERCER ST       | Seattle | 98109    |                | -122.3561914741 | 47.6250635431 | 10 MERCER RESTAURANT     | Routine Inspection/Field Review | 10               | Unsatisfactory    | false                      | blue           | 4300 - Non-food contact surfaces maintained and clean                                   | 3                | PR0049572   | DAHSIBSJT             | IV43WZVLN           | 2     | 
| 10 MERCER RESTAURANT | 10 MERCER RESTAURANT | 2017-01-24T00:00:00 | Seating 13-50 - Risk Category III | 10 MERCER ST       | Seattle | 98109    |                | -122.3561914741 | 47.6250635431 | 10 MERCER RESTAURANT     | Routine Inspection/Field Review | 10               | Unsatisfactory    | false                      | blue           | 4800 - Physical facilities properly installed,...                                       | 2                | PR0049572   | DAHSIBSJT             | IVCQ1ZIV0           | 2     | 
| 10 MERCER RESTAURANT | 10 MERCER RESTAURANT | 2017-01-24T00:00:00 | Seating 13-50 - Risk Category III | 10 MERCER ST       | Seattle | 98109    |                | -122.3561914741 | 47.6250635431 | 10 MERCER RESTAURANT     | Routine Inspection/Field Review | 10               | Unsatisfactory    | false                      | red            | 1200 - Proper shellstock ID; wild mushroom ID; parasite destruction procedures for fish | 5                | PR0049572   | DAHSIBSJT             | IVREK90PM           | 2     | 
| 10 MERCER RESTAURANT | 10 MERCER RESTAURANT | 2016-10-10T00:00:00 | Seating 13-50 - Risk Category III | 10 MERCER ST       | Seattle | 98109    |                | -122.3561914741 | 47.6250635431 | 10 MERCER RESTAURANT     | Routine Inspection/Field Review | 15               | Unsatisfactory    | false                      | blue           | 4100 - Warewashing facilities properly installed,...                                    | 5                | PR0049572   | DASXYDI0S             | IVWH1PRGO           | 2     | 
| 10 MERCER RESTAURANT | 10 MERCER RESTAURANT | 2016-10-10T00:00:00 | Seating 13-50 - Risk Category III | 10 MERCER ST       | Seattle | 98109    |                | -122.3561914741 | 47.6250635431 | 10 MERCER RESTAURANT     | Routine Inspection/Field Review | 15               | Unsatisfactory    | false                      | red            | 2120 - Proper cold holding temperatures ( 42 degrees F to 45 degrees F)                 | 5                | PR0049572   | DASXYDI0S             | IVX08XRIM           | 2     | 
| 10 MERCER RESTAURANT | 10 MERCER RESTAURANT | 2016-10-10T00:00:00 | Seating 13-50 - Risk Category III | 10 MERCER ST       | Seattle | 98109    |                | -122.3561914741 | 47.6250635431 | 10 MERCER RESTAURANT     | Routine Inspection/Field Review | 15               | Unsatisfactory    | false                      | red            | 1400 - Raw meats below and away from ready to eat food; species separated               | 5                | PR0049572   | DASXYDI0S             | IVD0AHSHT           | 2     | 
| 10 MERCER RESTAURANT | 10 MERCER RESTAURANT | 2016-07-07T00:00:00 | Seating 13-50 - Risk Category III | 10 MERCER ST       | Seattle | 98109    |                | -122.3561914741 | 47.6250635431 | 10 MERCER RESTAURANT     | Consultation/Education - Field  | 0                | Complete          | false                      |                |                                                                                         | 0                | PR0049572   | DAKPQMFUU             |                     | 2     | 
| 10 MERCER RESTAURANT | 10 MERCER RESTAURANT | 2016-02-24T00:00:00 | Seating 13-50 - Risk Category III | 10 MERCER ST       | Seattle | 98109    |                | -122.3561914741 | 47.6250635431 | 10 MERCER RESTAURANT     | Routine Inspection/Field Review | 15               | Unsatisfactory    | false                      | blue           | 4200 - Food-contact surfaces maintained, clean, sanitized                               | 5                | PR0049572   | DAHS37PNS             | IVSDCSC2L           | 2     | 
| 10 MERCER RESTAURANT | 10 MERCER RESTAURANT | 2016-02-24T00:00:00 | Seating 13-50 - Risk Category III | 10 MERCER ST       | Seattle | 98109    |                | -122.3561914741 | 47.6250635431 | 10 MERCER RESTAURANT     | Routine Inspection/Field Review | 15               | Unsatisfactory    | false                      | red            | 2500 - Toxic substances properly identified,...                                         | 10               | PR0049572   | DAHS37PNS             | IVLA9OQM1           | 2     | 
```