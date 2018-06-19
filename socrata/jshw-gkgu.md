# Assembled Workers' Compensation Claims: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/assembled-workers-compensation-claims-beginning-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/jshw-gkgu) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jshw-gkgu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jshw-gkgu/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jshw-gkgu |
| Name | Assembled Workers' Compensation Claims: Beginning 2000 |
| Attribution | New York State Workers' Compensation Board |
| Category | Government & Finance |
| Tags | wcb, compensation claims, assembled claims |
| Created | 2014-12-04T16:36:47Z |
| Publication Date | 2016-12-16T01:35:24Z |

## Description

The Workers? Compensation Board (WCB) administers and regulates workers? compensation benefits, disability benefits, volunteer firefighters? benefits, volunteer ambulance workers? benefits, and volunteer civil defense workers? benefits. The WCB processes and adjudicates claims for benefits; ensures employer compliance with the requirement to maintain appropriate insurance coverage; and regulates the various system stakeholders, including self-insured employers, medical providers, third party administrators, insurance carriers and legal representatives.  Claim assembly occurs when the WCB learns of a workplace injury and assigns the claim a WCB claim number. The WCB ?assembles? a claim in which an injured worker has lost more than one week of work, has a serious injury that may result in a permanent disability, is disputed by the carrier or employer, or receives a claim form from the injured worker (Form C-3).  A reopened claim is one that has been reactivated to resolve new issues following a finding that no further action was necessary

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                               | Data Type     | Render Type   |
| ======== | ============== | ============================== | ================================== | ============= | ============= |
| Yes      | series tag     | claim_identifier               | Claim Identifier                   | text          | number        |
| Yes      | series tag     | claim_type                     | Claim Type                         | text          | text          |
| Yes      | series tag     | district_name                  | District Name                      | text          | text          |
| Yes      | numeric metric | average_weekly_wage            | Average Weekly Wage                | money         | money         |
| Yes      | series tag     | current_claim_status           | Current Claim Status               | text          | text          |
| Yes      | series tag     | claim_injury_type              | Claim Injury Type                  | text          | text          |
| Yes      | numeric metric | age_at_injury                  | Age at Injury                      | number        | number        |
| Yes      | time           | assembly_date                  | Assembly Date                      | calendar_date | calendar_date |
| No       |                | accident_date                  | Accident Date                      | calendar_date | calendar_date |
| No       |                | ancr_date                      | ANCR Date                          | calendar_date | calendar_date |
| No       |                | controverted_date              | Controverted Date                  | calendar_date | calendar_date |
| No       |                | section_32_date                | Section 32 Date                    | calendar_date | calendar_date |
| No       |                | ppd_scheduled_loss_date        | PPD Scheduled Loss Date            | calendar_date | calendar_date |
| No       |                | ppd_non_scheduled_loss_date    | PPD Non-Scheduled Loss Date        | calendar_date | calendar_date |
| No       |                | ptd_date                       | PTD Date                           | text          | text          |
| No       |                | first_appeal_date              | First Appeal Date                  | calendar_date | calendar_date |
| Yes      | series tag     | wcio_pob_code                  | WCIO Part Of Body Code             | text          | text          |
| Yes      | series tag     | wcio_pob_desc                  | WCIO Part Of Body Description      | text          | text          |
| Yes      | series tag     | wcio_nature_of_injury_code     | WCIO Nature of Injury Code         | text          | text          |
| Yes      | series tag     | wcio_nature_of_injury_desc     | WCIO Nature of Injury Description  | text          | text          |
| Yes      | series tag     | wcio_cause_of_injury_code      | WCIO Cause of Injury Code          | text          | text          |
| Yes      | series tag     | wcio_cause_of_injury_desc      | WCIO Cause of Injury Description   | text          | text          |
| Yes      | series tag     | oiics_pob_code                 | OIICS Part Of Body Code            | text          | text          |
| Yes      | series tag     | oiics_pob_desc                 | OIICS Part Of Body Description     | text          | text          |
| Yes      | series tag     | oiics_nature_injury_code       | OIICS Nature of Injury Code        | text          | text          |
| Yes      | series tag     | oiics_nature_injury_desc       | OIICS Nature of Injury Description | text          | text          |
| Yes      | series tag     | oiics_injury_source_code       | OIICS Injury Source Code           | text          | text          |
| Yes      | series tag     | oiics_injury_source_desc       | OIICS Injury Source Description    | text          | text          |
| Yes      | series tag     | oiics_event_exposure_code      | OIICS Event Exposure Code          | text          | text          |
| Yes      | series tag     | oiics_event_exposure_desc      | OIICS Event Exposure Description   | text          | text          |
| Yes      | series tag     | oiics_secondary_source_code    | OIICS Secondary Source Code        | text          | text          |
| Yes      | series tag     | oiics_secondary_source_desc    | OIICS Secondary Source Description | text          | text          |
| Yes      | series tag     | alternative_dispute_resolution | Alternative Dispute Resolution     | text          | text          |
| Yes      | series tag     | gender                         | Gender                             | text          | text          |
| Yes      | numeric metric | birth_year                     | Birth Year                         | number        | number        |
| Yes      | series tag     | zip_code                       | Zip Code                           | text          | text          |
| Yes      | series tag     | medical_fee_region             | Medical Fee Region                 | text          | text          |
| No       |                | c2_date                        | C-2 Date                           | calendar_date | calendar_date |
| No       |                | c3_date                        | C-3 Date                           | calendar_date | calendar_date |
| No       |                | first_hearing_date             | First Hearing Date                 | calendar_date | calendar_date |
| Yes      | series tag     | highest_process                | Highest Process                    | text          | text          |
| Yes      | numeric metric | hearing_count                  | Hearing Count                      | number        | number        |
| Yes      | numeric metric | closed_count                   | Closed Count                       | number        | number        |
| Yes      | series tag     | atty_rep_ind                   | Attorney/Representative            | text          | text          |
| Yes      | series tag     | carrier_name                   | Carrier Name                       | text          | text          |
| Yes      | series tag     | carrier_type                   | Carrier Type                       | text          | text          |
| Yes      | numeric metric | ime4_count                     | IME-4 Count                        | number        | number        |
| Yes      | numeric metric | interval_assembled_to_ancr     | Interval Assembled to ANCR         | number        | number        |
| Yes      | series tag     | accident_ind                   | Accident                           | text          | text          |
| Yes      | series tag     | occupational_disease_ind       | Occupational Disease               | text          | text          |
| Yes      | series tag     | injured_in_county_name         | County of Injury                   | text          | text          |
```

## Time Field

```ls
Value = assembly_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = accident_date,ancr_date,controverted_date,section_32_date,ppd_scheduled_loss_date,ppd_non_scheduled_loss_date,first_appeal_date,c2_date,c3_date,first_hearing_date,ptd_date
```

## Data Commands

```ls
series e:jshw-gkgu d:2013-04-01T00:00:00.000Z t:current_claim_status="ADMINISTRATIVELY CLOSED" t:occupational_disease_ind=N t:wcio_pob_desc=UNKNOWN t:wcio_pob_code=UK t:zip_code=11423 t:claim_identifier=2069421 t:atty_rep_ind=N t:accident_ind=Y t:claim_injury_type=NON-COMP t:wcio_cause_of_injury_code=UK t:wcio_nature_of_injury_desc=UNKNOWN t:highest_process="No Resolutions" t:claim_type="Workers Compensation" t:district_name=NYC t:medical_fee_region=IV t:gender=M t:wcio_cause_of_injury_desc=UNKNOWN t:wcio_nature_of_injury_code=UK t:carrier_type="2A. SIF" t:carrier_name="STATE INSURANCE FUND" t:injured_in_county_name=QUEENS t:alternative_dispute_resolution=N m:age_at_injury=0 m:average_weekly_wage=0 m:closed_count=1 m:hearing_count=0 m:birth_year=0

series e:jshw-gkgu d:2013-11-20T00:00:00.000Z t:current_claim_status="ADMINISTRATIVELY CLOSED" t:occupational_disease_ind=N t:wcio_pob_desc=UNKNOWN t:wcio_pob_code=UK t:zip_code=11691 t:claim_identifier=2174033 t:atty_rep_ind=N t:accident_ind=Y t:claim_injury_type=NON-COMP t:wcio_cause_of_injury_code=UK t:wcio_nature_of_injury_desc=UNKNOWN t:highest_process="No Resolutions" t:claim_type="Workers Compensation" t:district_name=NYC t:medical_fee_region=IV t:gender=F t:wcio_cause_of_injury_desc=UNKNOWN t:wcio_nature_of_injury_code=UK t:carrier_type="2A. SIF" t:carrier_name="STATE INSURANCE FUND" t:injured_in_county_name=QUEENS t:alternative_dispute_resolution=N m:age_at_injury=0 m:average_weekly_wage=0 m:closed_count=1 m:hearing_count=0 m:birth_year=0

series e:jshw-gkgu d:2013-09-24T00:00:00.000Z t:current_claim_status="ADMINISTRATIVELY CLOSED" t:occupational_disease_ind=N t:wcio_pob_desc=UNKNOWN t:wcio_pob_code=UK t:zip_code=11435 t:claim_identifier=2126673 t:atty_rep_ind=N t:accident_ind=Y t:claim_injury_type=NON-COMP t:wcio_cause_of_injury_code=UK t:wcio_nature_of_injury_desc=UNKNOWN t:highest_process="No Resolutions" t:claim_type="Workers Compensation" t:district_name=NYC t:medical_fee_region=IV t:gender=M t:wcio_cause_of_injury_desc=UNKNOWN t:wcio_nature_of_injury_code=UK t:carrier_type="2A. SIF" t:carrier_name="STATE INSURANCE FUND" t:injured_in_county_name=QUEENS t:alternative_dispute_resolution=N m:age_at_injury=0 m:average_weekly_wage=0 m:closed_count=1 m:hearing_count=0 m:birth_year=0
```

## Meta Commands

```ls
metric m:average_weekly_wage p:double l:"Average Weekly Wage" d:"Wage used to calculate total disability benefit rates for most claimants defined as 1/52nd of the Injured Worker's average annual earnings, based on the prior year's payroll data. Blank means data was not provided." t:dataTypeName=money

metric m:age_at_injury p:integer l:"Age at Injury" d:"Age of claimant when the injury occurred." t:dataTypeName=number

metric m:birth_year p:integer l:"Birth Year" d:"Claimant?s year of birth. Blank means data was not provided." t:dataTypeName=number

metric m:hearing_count p:integer l:"Hearing Count" d:"Number of WCB hearings held on the claim." t:dataTypeName=number

metric m:closed_count p:integer l:"Closed Count" d:"The number of times a claim was closed in its lifecycle with a ""No further action"" decision." t:dataTypeName=number

metric m:ime4_count p:integer l:"IME-4 Count" d:"IME-4 is the ?Independent Examiner's Report of Independent Medical Examination? form. Number of IME-4s received for the claim." t:dataTypeName=number

metric m:interval_assembled_to_ancr p:integer l:"Interval Assembled to ANCR" d:"The number of days taken from the WCB Claim Assembly date to the establishment of the claim. A claim is established when Accident Notice Causal Relationship (ANCR) or Occupational Disease Notice Causal Relationship (ODNCR) is found in the claim." t:dataTypeName=number

entity e:jshw-gkgu l:"Assembled Workers' Compensation Claims:  Beginning 2000" t:attribution="New York State Workers' Compensation Board" t:url=https://data.ny.gov/api/views/jshw-gkgu

property e:jshw-gkgu t:meta.view v:id=jshw-gkgu v:category="Government & Finance" v:attributionLink=http://www.wcb.ny.gov/ v:averageRating=0 v:name="Assembled Workers' Compensation Claims:  Beginning 2000" v:attribution="New York State Workers' Compensation Board"

property e:jshw-gkgu t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jshw-gkgu t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jshw-gkgu t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| claim_identifier | claim_type           | district_name | average_weekly_wage | current_claim_status    | claim_injury_type | age_at_injury | assembly_date       | accident_date       | ancr_date | controverted_date | section_32_date | ppd_scheduled_loss_date | ppd_non_scheduled_loss_date | ptd_date | first_appeal_date | wcio_pob_code | wcio_pob_desc | wcio_nature_of_injury_code | wcio_nature_of_injury_desc | wcio_cause_of_injury_code | wcio_cause_of_injury_desc | oiics_pob_code | oiics_pob_desc | oiics_nature_injury_code | oiics_nature_injury_desc | oiics_injury_source_code | oiics_injury_source_desc | oiics_event_exposure_code | oiics_event_exposure_desc | oiics_secondary_source_code | oiics_secondary_source_desc | alternative_dispute_resolution | gender | birth_year | zip_code | medical_fee_region | c2_date | c3_date | first_hearing_date | highest_process | hearing_count | closed_count | atty_rep_ind | carrier_name         | carrier_type | ime4_count | interval_assembled_to_ancr | accident_ind | occupational_disease_ind | injured_in_county_name | 
| ================ | ==================== | ============= | =================== | ======================= | ================= | ============= | =================== | =================== | ========= | ================= | =============== | ======================= | =========================== | ======== | ================= | ============= | ============= | ========================== | ========================== | ========================= | ========================= | ============== | ============== | ======================== | ======================== | ======================== | ======================== | ========================= | ========================= | =========================== | =========================== | ============================== | ====== | ========== | ======== | ================== | ======= | ======= | ================== | =============== | ============= | ============ | ============ | ==================== | ============ | ========== | ========================== | ============ | ======================== | ====================== | 
| 2069421          | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2013-04-01T00:00:00 | 2013-03-15T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | M      | 0          | 11423    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
| 2174033          | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2013-11-20T00:00:00 | 2013-10-11T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | F      | 0          | 11691    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
| 2126673          | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2013-09-24T00:00:00 | 2013-07-22T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | M      | 0          | 11435    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
| 2043816          | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2013-05-29T00:00:00 | 2013-04-12T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | F      | 0          | 11413    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
| 2045428          | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2013-02-11T00:00:00 | 2012-12-29T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | F      | 0          | 11223    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
| 2112310          | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2013-07-22T00:00:00 | 2013-02-12T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | F      | 0          | 11372    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
| 1592571          | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2012-02-08T00:00:00 | 2012-01-30T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | M      | 0          | 11694    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
| 989929           | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2012-02-02T00:00:00 | 2011-09-23T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | M      | 0          | 11369    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
| 1992483          | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2012-01-30T00:00:00 | 2012-01-14T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | F      | 0          | 11422    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
| 2101958          | Workers Compensation | NYC           | 0.00                | ADMINISTRATIVELY CLOSED | NON-COMP          | 0             | 2013-07-16T00:00:00 | 2013-06-21T00:00:00 |           |                   |                 |                         |                             |          |                   | UK            | UNKNOWN       | UK                         | UNKNOWN                    | UK                        | UNKNOWN                   |                |                |                          |                          |                          |                          |                           |                           |                             |                             | N                              | M      | 0          | 11367    | IV                 |         |         |                    | No Resolutions  | 0             | 1            | N            | STATE INSURANCE FUND | 2A. SIF      |            |                            | Y            | N                        | QUEENS                 | 
```