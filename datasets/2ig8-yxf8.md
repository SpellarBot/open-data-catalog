# Current Active Clinical Trials - Roswell Park Cancer Institute

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-active-clinical-trials-roswell-park-cancer-institute) |
| Metadata | [Link](https://data.ny.gov/api/views/2ig8-yxf8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2ig8-yxf8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2ig8-yxf8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2ig8-yxf8 |
| Name | Current Active Clinical Trials - Roswell Park Cancer Institute |
| Attribution | Roswell Park Cancer Institute (RPCI) |
| Category | Health |
| Tags | nci, rpci, cancer study |
| Created | 2015-01-29T17:33:51Z |
| Publication Date | 2015-05-28T18:28:58Z |

## Description

List of active studies submitted by Roswell Park Cancer Institute (RPCI) to National Cancer Institute (NCI) annually as part of the Cancer Center Report Grant reporting. It includes the primary site, protocol, principal investigator, date opened, phase and study name.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | primary_site           | Primary Site           | text          | text          |
| Yes      | series tag  | protocol               | Protocol               | text          | text          |
| Yes      | series tag  | principal_investigator | Principal Investigator | text          | text          |
| Yes      | time        | date_opened            | Date Opened            | calendar_date | calendar_date |
| No       |             | date_closed            | Date Closed            | calendar_date | calendar_date |
| Yes      | series tag  | study_phase            | Study Phase            | text          | text          |
| Yes      | series tag  | title                  | Title                  | text          | text          |
```

## Time Field

```ls
Value = date_opened
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_closed
```

## Data Commands

```ls
series e:2ig8-yxf8 d:2010-11-18T00:00:00.000Z t:title="(COG AALL0932) Treatment of Patients with Newly Diagnosed Standard Risk B-Lymphoblastic Leukemia (B-ALL) or Localized B-Lineage Lymphoblastic Lymphoma (B-LLy)" t:protocol="COG AALL0932 / NCG 185010" t:principal_investigator="Bambach B" t:study_phase="Phase III" t:primary_site="Acute Lymphocytic Leukemia" m:row_number.2ig8-yxf8=1

series e:2ig8-yxf8 d:2007-01-05T00:00:00.000Z t:title="(COG AALL05B1/chob 2197) A Children's Oncology Group Protocol for Collecting and Banking Relapsed Acute Lymphoblastic Leukemia Research Specimens" t:protocol="COG AALL05B1 / NCG 95606" t:principal_investigator="Brecher M" t:study_phase="Not Applicable" t:primary_site="Acute Lymphocytic Leukemia" m:row_number.2ig8-yxf8=2

series e:2ig8-yxf8 d:2011-06-08T00:00:00.000Z t:title="(COG AALL0631) A Phase III Study of Risk Directed Therapy for Infants with Acute Lymphoblastic Leukemia (ALL):  Randomization of Highest Risk Infants to Intensive Chemotherapy +/- FLT3 Inhibition (CEP-701, Lestraurtinib; IND #76431; NSC #617807)" t:protocol="COG AALL0631 / NCG 196511" t:principal_investigator="Brecher M" t:study_phase="Phase III" t:primary_site="Acute Lymphocytic Leukemia" m:row_number.2ig8-yxf8=3
```

## Meta Commands

```ls
metric m:row_number.2ig8-yxf8 p:long l:"Row Number"

entity e:2ig8-yxf8 l:"Current Active Clinical Trials - Roswell Park Cancer Institute" t:attribution="Roswell Park Cancer Institute (RPCI)" t:url=https://data.ny.gov/api/views/2ig8-yxf8

property e:2ig8-yxf8 t:meta.view v:id=2ig8-yxf8 v:category=Health v:attributionLink=https://www.roswellpark.org/ v:averageRating=0 v:name="Current Active Clinical Trials - Roswell Park Cancer Institute" v:attribution="Roswell Park Cancer Institute (RPCI)"

property e:2ig8-yxf8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2ig8-yxf8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:2ig8-yxf8 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| primary_site               | protocol                  | principal_investigator | date_opened         | date_closed         | study_phase    | title                                                                                                                                                                                                                                                           | 
| ========================== | ========================= | ====================== | =================== | =================== | ============== | =============================================================================================================================================================================================================================================================== | 
| Acute Lymphocytic Leukemia | COG AALL0932 / NCG 185010 | Bambach B              | 2010-11-18T00:00:00 |                     | Phase III      | (COG AALL0932) Treatment of Patients with Newly Diagnosed Standard Risk B-Lymphoblastic Leukemia (B-ALL) or Localized B-Lineage Lymphoblastic Lymphoma (B-LLy)                                                                                                  | 
| Acute Lymphocytic Leukemia | COG AALL05B1 / NCG 95606  | Brecher M              | 2007-01-05T00:00:00 |                     | Not Applicable | (COG AALL05B1/chob 2197) A Children's Oncology Group Protocol for Collecting and Banking Relapsed Acute Lymphoblastic Leukemia Research Specimens                                                                                                               | 
| Acute Lymphocytic Leukemia | COG AALL0631 / NCG 196511 | Brecher M              | 2011-06-08T00:00:00 | 2014-06-30T00:00:00 | Phase III      | (COG AALL0631) A Phase III Study of Risk Directed Therapy for Infants with Acute Lymphoblastic Leukemia (ALL): Randomization of Highest Risk Infants to Intensive Chemotherapy +/- FLT3 Inhibition (CEP-701, Lestraurtinib; IND #76431; NSC #617807)            | 
| Acute Lymphocytic Leukemia | COG AALL1131 / NCG 206911 | Brecher M              | 2012-05-07T00:00:00 |                     | Phase III      | (COG AALL1131) A Phase III Randomized Trial for Newly Diagnosed High Risk B-Precursor Acute Lymphoblastic Leukemia (ALL) Testing Clofarabine (IND# 73789, NSC# 606869) in the Very High Risk Stratum                                                            | 
| Acute Lymphocytic Leukemia | PH 208211                 | Wang E                 | 2012-04-27T00:00:00 |                     | Phase III      | A Phase 3, Multicenter, Randomized Study to Evaluate the Substitution of MARQIBO? (Vincristine Sulfate Liposomes Injection, VSLI) for Standard Vincristine Sulfate Injection (VSI) in the Induction, Intensification, and Maintenance Phases of Combination Che | 
| Acute Lymphocytic Leukemia | CALGB 9862                | Wetzler M              | 1999-09-09T00:00:00 |                     | Not Applicable | Molecular Genetic Features of Acute Leukemia                                                                                                                                                                                                                    | 
| Acute Myelocytic Leukemia  | NCG 198911                | Bambach B              | 2011-08-04T00:00:00 | 2014-10-21T00:00:00 | Not Applicable | (PBMTC ONC 1001) The Role of Minimal Residual Disease Testing Before and After Hematopoietic Cell Transplantation for Pediatric Acute Myeloid Leukemia                                                                                                          | 
| Acute Myelocytic Leukemia  | COG AAML1031 / NCG 217112 | Beaupin L              | 2012-08-21T00:00:00 |                     | Phase III      | (COG AAML1031) A Phase III Randomized Trial for Patients with de novo AML Using Bortezomib and Sorafenib (IND#114480; NSC#681239, NSC#724772) for Patients with High Allelic Ratio FLT3/ITD                                                                     | 
| Acute Myelocytic Leukemia  | COG ACCL0933 / NCG 206811 | Brecher M              | 2012-03-30T00:00:00 |                     | Phase III      | (COG ACCL0933) A Randomized Open-Label Trial of Caspofungin Versus Fluconazole to Prevent Invasive Fungal Infections in Children Undergoing Chemotherapy for Acute Myeloid Leukemia (AML)                                                                       | 
| Acute Myelocytic Leukemia  | I 211411                  | Griffiths E            | 2012-03-13T00:00:00 |                     | Not Applicable | Clinical Relevance of T-Cell Phenotype in AML Patients Following Therapy                                                                                                                                                                                        | 
```