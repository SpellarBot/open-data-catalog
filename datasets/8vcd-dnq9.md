# Express Lane Eligibility for Medicaid and CHIP Coverage

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/express-lane-eligibility-for-medicaid-and-chip-coverage) |
| Metadata | [Link](https://data.medicaid.gov/api/views/8vcd-dnq9) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/8vcd-dnq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/8vcd-dnq9/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | 8vcd-dnq9 |
| Name | Express Lane Eligibility for Medicaid and CHIP Coverage |
| Attribution | Centers for Medicare & Medicaid Services |
| Category | Eligibility |
| Tags | enrollment strategies |
| Created | 2016-07-13T19:57:47Z |
| Publication Date | 2016-11-29T01:37:57Z |

## Description

States may rely on eligibility information from "Express Lane" agency programs to streamline and simplify enrollment and renewal in Medicaid and CHIP. Express Lane agencies may include Supplemental Nutrition Assistance Program (SNAP), School Lunch programs, Temporary Assistance for Needy Families, Head Start, and the Women, infant, and children's program (WIC) , among others. States can also use state income tax data to determine Medicaid and CHIP eligibility for children.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag  | state                 | State                 | text          | text          |
| Yes      | series tag  | medicaid_chip         | Medicaid/CHIP         | text          | text          |
| Yes      | time        | approved              | Approved              | calendar_date | calendar_date |
| No       |             | effective             | Effective             | calendar_date | calendar_date |
| Yes      | series tag  | agency                | Agency                | text          | text          |
| Yes      | series tag  | initial_determination | Initial Determination | checkbox      | checkbox      |
| Yes      | series tag  | redetermination       | Redetermination       | checkbox      | checkbox      |
| Yes      | series tag  | ele_findings          | ELE Findings          | text          | text          |
| Yes      | series tag  | enrollment_process    | Enrollment Process    | text          | text          |
```

## Time Field

```ls
Value = approved
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = effective
```

## Data Commands

```ls
series e:8vcd-dnq9 d:2010-06-14T00:00:00.000Z t:ele_findings="All except alien/citizen status" t:initial_determination=true t:medicaid_chip="Medicaid & CHIP" t:state=Iowa t:agency=SNAP t:enrollment_process="While Iowa's Medicaid program uses SNAP as the ELA, no children are enrolled in CHIP based on SNAP findings. Instead, when a child is denied Medicaid based on being over-income, the Medicaid findings and methodologies are accepted by CHIP for automatic enrollment." m:row_number.8vcd-dnq9=1

series e:8vcd-dnq9 d:2010-01-22T00:00:00.000Z t:ele_findings="SNAP - Income, SSN, age, residency, identity. NSLP-Income, age, residency, identity" t:initial_determination=true t:redetermination=true t:medicaid_chip=Medicaid t:state=Louisiana t:agency="SNAP & NSLP (School Lunch)" t:enrollment_process="Regular CHIP screen/enroll. The state auto-enrolls children based on information available." m:row_number.8vcd-dnq9=2

series e:8vcd-dnq9 d:2009-06-23T00:00:00.000Z t:ele_findings="Income, Budget unit, insurance, identity" t:initial_determination=true t:redetermination=true t:medicaid_chip="Medicaid & CHIP" t:state="New Jersey" t:agency="Div. Taxation & NSLP" t:enrollment_process="Screen/Enroll-30% points. State finds out from NSLP whether kids receive Free Lunch or reduced Lunch. If free lunch (under 130%FPL), kids are put on Medicaid. If reduced lunch, they are temporarily put on CHIP until more income information can be gathered." m:row_number.8vcd-dnq9=3
```

## Meta Commands

```ls
metric m:row_number.8vcd-dnq9 p:long l:"Row Number"

entity e:8vcd-dnq9 l:"Express Lane Eligibility for Medicaid and CHIP Coverage" t:attribution="Centers for Medicare & Medicaid Services" t:url=https://data.medicaid.gov/api/views/8vcd-dnq9

property e:8vcd-dnq9 t:meta.view v:id=8vcd-dnq9 v:category=Eligibility v:attributionLink=http://www.medicaid.gov v:averageRating=0 v:name="Express Lane Eligibility for Medicaid and CHIP Coverage" v:attribution="Centers for Medicare & Medicaid Services"

property e:8vcd-dnq9 t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:8vcd-dnq9 t:meta.view.owner v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:8vcd-dnq9 t:meta.view.tableauthor v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491332351 v:displayName="Jeff Chamblee"

property e:8vcd-dnq9 t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```

## Top Records

```ls
| state          | medicaid_chip   | approved            | effective           | agency                     | initial_determination | redetermination | ele_findings                                                                        | enrollment_process                                                                                                                                                                                                                                                                                                         | 
| ============== | =============== | =================== | =================== | ========================== | ===================== | =============== | =================================================================================== | ========================================================================================================================================================================================================================================================================================================================== | 
| Iowa           | Medicaid & CHIP | 2010-06-14T00:00:00 | 2010-06-01T00:00:00 | SNAP                       | true                  |                 | All except alien/citizen status                                                     | While Iowa's Medicaid program uses SNAP as the ELA, no children are enrolled in CHIP based on SNAP findings. Instead, when a child is denied Medicaid based on being over-income, the Medicaid findings and methodologies are accepted by CHIP for automatic enrollment.                                                   | 
| Louisiana      | Medicaid        | 2010-01-22T00:00:00 | 2009-10-10T00:00:00 | SNAP & NSLP (School Lunch) | true                  | true            | SNAP - Income, SSN, age, residency, identity. NSLP-Income, age, residency, identity | Regular CHIP screen/enroll. The state auto-enrolls children based on information available.                                                                                                                                                                                                                                | 
| New Jersey     | Medicaid & CHIP | 2009-06-23T00:00:00 | 2009-05-01T00:00:00 | Div. Taxation & NSLP       | true                  | true            | Income, Budget unit, insurance, identity                                            | Screen/Enroll-30% points. State finds out from NSLP whether kids receive Free Lunch or reduced Lunch. If free lunch (under 130%FPL), kids are put on Medicaid. If reduced lunch, they are temporarily put on CHIP until more income information can be gathered.                                                           | 
| Maryland       | Medicaid        | 2010-09-28T00:00:00 | 2010-04-01T00:00:00 | Office of the Comptroller  | true                  |                 | State residency                                                                     | Regular CHIP screen/enroll- Families indicate on their tax return that they are uninsured and the Comptroller sends list of all those under 300%FPL to the State agency, which sends out applications. State is in discussion with us now about how to move forward using income findings from the state tax data as well. | 
| Oregon         | Medicaid & CHIP | 2010-10-11T00:00:00 | 2010-08-01T00:00:00 | SNAP & NSLP                | true                  |                 | SNAP: Income, group size, SSN, residency. NSLP: Income, household comp, residency   | Screen/enroll- 30% points. SNAP recipients are sent a shortened Healthy Kids enrollment form one month after being found eligible for SNAP. School districts send lists of free lunch kids to OHA and OHA sends shortened Health Kids enrollment form                                                                      | 
| South Carolina | Medicaid        | 2011-06-29T00:00:00 | 2011-04-01T00:00:00 | SNAP & TANF                |                       | true            | Income                                                                              | South Carolina is using income findings from the SNAP/TANF agency only at redetermination, for Medicaid enrollees who are also enrolled in SNAP or TANF. SC estimates this will greatly reduce churning off and on the program for children.                                                                               | 
| Colorado       | Medicaid & CHIP | 2012-03-27T00:00:00 | 2011-10-14T00:00:00 | NSLP                       | true                  |                 | Income                                                                              | Colorado is using the National School Lunch income findings and using a 30% point screen and enroll option; at approval, 24 school districts were participating                                                                                                                                                            | 
| Massachusetts  | Medicaid & CHIP | 2012-08-08T00:00:00 | 2012-01-23T00:00:00 | SNAP                       |                       | true            | Income, household size                                                              | Using SNAP income to keep families on at renewal if income is up to 150%FPL- using 30 Screen and Enroll to keep families on Medicaid, State will be able to use the same process for adults under their waiver authority                                                                                                   | 
| Utah           | CHIP            | 2012-07-13T00:00:00 | 2012-04-01T00:00:00 | Dept of Taxation           |                       | true            | income                                                                              | At renewal, clients are mailed a consent form at renewal explaining their option to give consent to access their most current AGI from the Utah State Tax Commission instead of providing verification of each source of countable income for their family.                                                                | 
| New York       | Medicaid        | 2012-09-18T00:00:00 | 2012-05-01T00:00:00 | CHIP                       | true                  |                 | Income, household size, residency                                                   | New York's ELE process relies on the use of findings from the CHIP agency at CHIP renewal to seamlessly enroll applicant children into Medicaid. This process alleviates the administrative burden associated with the two separate applications and verification processes in place for Medicaid and CHIP.                | 
```