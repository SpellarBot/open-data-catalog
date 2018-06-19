# Building Permits - Waived Fees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-permits-waived-fees-e4efe) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/rfav-vmja) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/rfav-vmja/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/rfav-vmja/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | rfav-vmja |
| Name | Building Permits - Waived Fees |
| Attribution | City of Chicago |
| Category | Buildings |
| Tags | permits |
| Created | 2012-06-01T20:08:29Z |
| Publication Date | 2012-06-04T16:31:35Z |

## Description

Fees waived since January 1, 2012 by building permit.  If you believe that any information in the published public data sets concerning your organization or business contains confidential information or has been published in error, please contact dataportal@cityofchicago.org so that we may address your concerns. Data Owner: Buildings. Time Period: January 1, 2012 to present. Update Frequency: Data is updated as needed.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | permit_no            | PERMIT#              | text          | number        |
| Yes      | series tag     | permit_type          | PERMIT_TYPE          | text          | text          |
| Yes      | time           | issued_date          | ISSUED_DATE          | calendar_date | calendar_date |
| No       |                | address              | ADDRESS              | text          | text          |
| Yes      | series tag     | work_description     | WORK_DESCRIPTION     | text          | text          |
| Yes      | numeric metric | amount_waived        | AMOUNT_WAIVED        | money         | money         |
| Yes      | series tag     | amount_paid          | AMOUNT_PAID          | text          | money         |
| Yes      | series tag     | contact_name         | CONTACT_NAME         | text          | text          |
| Yes      | series tag     | contact_organization | CONTACT_ORGANIZATION | text          | text          |
```

## Time Field

```ls
Value = issued_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:rfav-vmja d:2012-05-30T00:00:00.000Z t:amount_paid=0.00 t:permit_type="PERMIT - RENOVATION/ALTERATION" t:contact_name="CHGO PUBLIC SCHOOLS" t:permit_no=100442998 t:contact_organization="CHGO PUBLIC SCHOOLS" t:work_description="CAMERON SCHOOL: Three Story Kindergarten thru Eight Grade Elementary School. Masonry Repairs, New Elevator, Accessibility Upgrades, Re-Roof, Limited Renovation of Finishes, Site Improvements, Parking Lot Replacement." m:amount_waived=46931.25

series e:rfav-vmja d:2012-05-30T00:00:00.000Z t:amount_paid=0.00 t:permit_type="PERMIT - ELECTRIC WIRING" t:permit_no=100441230 t:work_description="MAINTENANCE PERMIT" m:amount_waived=300

series e:rfav-vmja d:2012-05-30T00:00:00.000Z t:amount_paid=0.00 t:permit_type="PERMIT - RENOVATION/ALTERATION" t:permit_no=100442695 t:work_description="RENOVATION OF ONE UNIT, 2 STORY, SINGLE-FAMILY. CONSTRUCT WOODEN DECK, STAIRS, AND HANDRAILS. RUN ELECTIRC TO POWER LIFT. NO CHANGE TO PARKING." m:amount_waived=200
```

## Meta Commands

```ls
metric m:amount_waived p:double l:AMOUNT_WAIVED t:dataTypeName=money

entity e:rfav-vmja l:"Building Permits - Waived Fees" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/rfav-vmja

property e:rfav-vmja t:meta.view v:id=rfav-vmja v:category=Buildings v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Building Permits - Waived Fees" v:attribution="City of Chicago"

property e:rfav-vmja t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:rfav-vmja t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| permit_no | permit_type                    | issued_date         | address                  | work_description                                                                                                                                                                                                         | amount_waived | amount_paid | contact_name              | contact_organization | 
| ========= | ============================== | =================== | ======================== | ======================================================================================================================================================================================================================== | ============= | =========== | ========================= | ==================== | 
| 100442998 | PERMIT - RENOVATION/ALTERATION | 2012-05-30T00:00:00 | 1234 N MONTICELLO AVE    | CAMERON SCHOOL: Three Story Kindergarten thru Eight Grade Elementary School. Masonry Repairs, New Elevator, Accessibility Upgrades, Re-Roof, Limited Renovation of Finishes, Site Improvements, Parking Lot Replacement. | 46931.25      | 0.00        | CHGO PUBLIC SCHOOLS       | CHGO PUBLIC SCHOOLS  | 
| 100441230 | PERMIT - ELECTRIC WIRING       | 2012-05-30T00:00:00 | 59 W NORTH BLVD          | MAINTENANCE PERMIT                                                                                                                                                                                                       | 300.00        | 0.00        |                           |                      | 
| 100442695 | PERMIT - RENOVATION/ALTERATION | 2012-05-30T00:00:00 | 9144 S MAY ST            | RENOVATION OF ONE UNIT, 2 STORY, SINGLE-FAMILY. CONSTRUCT WOODEN DECK, STAIRS, AND HANDRAILS. RUN ELECTIRC TO POWER LIFT. NO CHANGE TO PARKING.                                                                          | 200.00        | 0.00        |                           |                      | 
| 100442699 | PERMIT - RENOVATION/ALTERATION | 2012-05-30T00:00:00 | 3525 W DICKENS AVE       | RENOVATION TO THREE-UNIT, TWO-STORY, RESIDENTIAL BUILDING. CONSTRUCT NEW WOODEN STAIRS AND HANDRAILS. RUN ELECTRIC TO POWER LIFT. NO CHANGE TO PARKING.                                                                  | 175.00        | 0.00        |                           |                      | 
| 100424442 | PERMIT - EASY PERMIT PROCESS   | 2012-05-30T00:00:00 | 11318 S FORRESTVILLE AVE | REPAIR/RESTORE EXISTING PARAPET WALL (30' X 5' AREA) AT FRONT ELEVATION TO SINGLE FAMILY, SAME AS EXISTING **LANDMARK DISTRICT**                                                                                         | 175.00        | 0.00        |                           |                      | 
| 100442832 | PERMIT - ELECTRIC WIRING       | 2012-05-30T00:00:00 | 11847 S OAKLEY AVE       | RUN ELECTRIC TO POWER THE LIFT.                                                                                                                                                                                          | 100.00        | 0.00        |                           |                      | 
| 100442977 | PERMIT - ELEVATOR EQUIPMENT    | 2012-05-30T00:00:00 | 11847 S OAKLEY AVE       | installation of 1 vertical wheelchair lift. Pursuant to plans submitted. Installation to be made in compliance with City of Chicago Elevator code. Subject to field inspection by City of chicago Elevator Bureau.       | 100.00        | 0.00        |                           |                      | 
| 12787     | CARNIVAL EVENTS (RIDES)        | 2012-05-30T00:00:00 | 1751 W 47TH ST           |                                                                                                                                                                                                                          | 2700          |             | BACK OF THE YARDS NEIGH C |                      | 
| 100436457 | PERMIT - NEW CONSTRUCTION      | 2012-05-29T00:00:00 | 1835 W BERWYN AVE        | ERECT 2-STORY FRAME CONSTRUCTION SINGLE FAMILY HOME WITH BASEMENT AND REAR YARD PARKING PAD. GREEN PERMIT PROGRAM BENEFIT TIER II (EXCEPTIONAL GREEN HOMES AND WATER MANAGEMENT)                                         | 1000.00       | 75.00       | ALCO CONSTRUCTION         |                      | 
| 100442694 | PERMIT - EASY PERMIT PROCESS   | 2012-05-29T00:00:00 | 60 E BALBO AVE           | ALL ELEVATIONS, TUCKPOINT 350LF, REPAIR/REPLACE 250SF BRICK, REPAIR/INSTALL NEW ANCHORS AT FIRE ESCAPE LADDER ON WEST ELEVATION, WATERPROOF18000SF AND REMOVE/REPLACE 330 LF COPING.                                     | 325.00        | 0.00        | DEPAUL UNIVERSITY         |                      | 
```