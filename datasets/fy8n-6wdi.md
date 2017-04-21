# IEPA No Further Remediation Sites

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iepa-no-further-remediation-sites) |
| Metadata | [Link](https://data.illinois.gov/api/views/fy8n-6wdi) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/fy8n-6wdi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/fy8n-6wdi/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | fy8n-6wdi |
| Name | IEPA No Further Remediation Sites |
| Attribution | Illinois Environmental Protection Agency |
| Category | Environment |
| Tags | sites, remediation, cleanup |
| Created | 2011-06-15T01:31:50Z |
| Publication Date | 2011-06-15T01:31:50Z |

## Description

Data extracted from the Bureau of Land's Site Remediation Program Database which identifies the terms and conditions of all "No Further Remediation " (NFR) Letters issued for all voluntary remediation projects administered through the Pre-Notice Site Cleanup Program (1989 to 1995) and the Site Remediation Program (1996 to the present).

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | lpc                    | LPC#                   | text      | text        |
| Yes      | series tag     | site_name              | Site Name              | text      | text        |
| Yes      | time           | nfr_letter_date        | NFR Letter Date        | date      | date        |
| No       |                | date_recorded          | Date Recorded          | date      | date        |
| Yes      | series tag     | remediation_standard   | Remediation Standard   | text      | text        |
| Yes      | series tag     | comprehensive_focused  | Comprehensive/Focused  | text      | text        |
| Yes      | series tag     | applicant_title        | Applicant Title        | text      | text        |
| Yes      | series tag     | applicant_first_name   | Applicant First Name   | text      | text        |
| Yes      | series tag     | applicant_last_name    | Applicant Last Name    | text      | text        |
| Yes      | series tag     | applicant_company      | Applicant Company      | text      | text        |
| Yes      | series tag     | institutional_controls | Institutional Controls | text      | text        |
| Yes      | series tag     | engineered_barriers    | Engineered Barriers    | text      | text        |
| Yes      | series tag     | worker_caution         | Worker Caution         | text      | text        |
| Yes      | numeric metric | acres                  | Acres                  | number    | number      |
```

## Time Field

```ls
Value = nfr_letter_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = date_recorded
```

## Data Commands

```ls
series e:fy8n-6wdi d:2003-10-03T07:00:00.000Z t:institutional_controls="Groundwater use restriction" t:applicant_first_name=William t:applicant_last_name=Hageman t:remediation_standard=Residential t:lpc='0010655254 t:applicant_title=Mr. t:worker_caution=False t:site_name="Hageman, William Sr." t:comprehensive_focused=Comprehensive t:applicant_company="Rose Construction" m:acres=0.63999999

series e:fy8n-6wdi d:2004-07-22T07:00:00.000Z t:applicant_first_name=Brian t:applicant_last_name=Davis t:remediation_standard=Industrial/Commercial t:lpc='0030055002 t:engineered_barriers="Asphalt barrier/Concrete barriers" t:applicant_title=Mr. t:worker_caution=False t:site_name="Aramark Service Master" t:comprehensive_focused=Focused t:applicant_company="Ecolab, Inc." m:acres=2.77

series e:fy8n-6wdi d:2000-12-28T08:00:00.000Z t:institutional_controls="Groundwater use restriction" t:applicant_first_name=Brian t:applicant_last_name=Martin t:remediation_standard=Industrial/Commercial t:lpc='0050050016 t:engineered_barriers="Clean soil barrier/Building foundation" t:applicant_title=Mr. t:worker_caution=True t:site_name="Illinois Power Town Gas Site" t:comprehensive_focused=Focused t:applicant_company="Illinois Power Company" m:acres=0.60000002
```

## Meta Commands

```ls
metric m:acres p:double l:Acres t:dataTypeName=number

entity e:fy8n-6wdi l:"IEPA No Further Remediation Sites" t:attribution="Illinois Environmental Protection Agency" t:url=https://data.illinois.gov/api/views/fy8n-6wdi

property e:fy8n-6wdi t:meta.view v:id=fy8n-6wdi v:category=Environment v:attributionLink=http://epadata.epa.state.il.us/land/srp/ v:averageRating=0 v:name="IEPA No Further Remediation Sites" v:attribution="Illinois Environmental Protection Agency"

property e:fy8n-6wdi t:meta.view.owner v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:displayName=wilcoxd

property e:fy8n-6wdi t:meta.view.tableauthor v:id=jkb2-496s v:profileImageUrlMedium=/api/users/jkb2-496s/profile_images/THUMB v:profileImageUrlLarge=/api/users/jkb2-496s/profile_images/LARGE v:screenName=wilcoxd v:profileImageUrlSmall=/api/users/jkb2-496s/profile_images/TINY v:roleName=publisher v:displayName=wilcoxd
```

## Top Records

```ls
| lpc         | site_name                    | nfr_letter_date | date_recorded | remediation_standard  | comprehensive_focused | applicant_title | applicant_first_name | applicant_last_name | applicant_company                            | institutional_controls      | engineered_barriers                    | worker_caution | acres      | 
| =========== | ============================ | =============== | ============= | ===================== | ===================== | =============== | ==================== | =================== | ============================================ | =========================== | ====================================== | ============== | ========== | 
| '0010655254 | Hageman, William Sr.         | 1065164400      | 1066201200    | Residential           | Comprehensive         | Mr.             | William              | Hageman             | Rose Construction                            | Groundwater use restriction |                                        | False          | 0.63999999 | 
| '0030055002 | Aramark Service Master       | 1090479600      | 1092812400    | Industrial/Commercial | Focused               | Mr.             | Brian                | Davis               | Ecolab, Inc.                                 |                             | Asphalt barrier/Concrete barriers      | False          | 2.77       | 
| '0050050016 | Illinois Power Town Gas Site | 977990400       | 980236800     | Industrial/Commercial | Focused               | Mr.             | Brian                | Martin              | Illinois Power Company                       | Groundwater use restriction | Clean soil barrier/Building foundation | True           | 0.60000002 | 
| '0050055044 | DeMoulin Brothers & Company  | 1068451200      | 1070870400    | Residential           | Focused               | Vice President  | Michael              | Coling              | DeMoulin Brothers & Company                  | Groundwater use restriction |                                        | False          | 2.5        | 
| '0050055052 | Schewe Property              | 905410800       | 905842800     | Residential           | Focused               | Mr.             | Maurice              | Schewe              |                                              |                             |                                        | False          | 0.1        | 
| '0110855003 | Harper-Wyman Company         | 1117695600      | 1121065200    | Industrial/Commercial | Comprehensive         | Mr.             | Douglas              | Wolf                | Corning, Incorporated                        | Groundwater use restriction | Concrete barrier/Building foundation   | True           | 22         | 
| '0110855098 | Austin L. Hade Trust         | 1083913200      | 1084863600    | Industrial/Commercial | Comprehensive         | Mr.             | Richard              | Hade                | Russell, English, Scoma & Beneke Law Offices | Groundwater use restriction |                                        | False          | 0.289      | 
| '0110855103 | Ag View FS                   | 1099900800      | 1106208000    | Industrial/Commercial | Focused               | Mr.             | Craig                | Wesner              | Ag View FS                                   | Groundwater use restriction |                                        | True           | 1.35       | 
| '0111005029 | Cheesman Olds Chevy          | 1100505600      | 1101801600    | Industrial/Commercial | Comprehensive         | Ms.             | Renee                | Waitkus             | Estate of Ronald Bukovic                     |                             |                                        | False          | 1          | 
| '0111005030 | Manning Farm Property        | 978681600       | 982224000     | Residential           | Focused               | Mr.             | Steven               | Karras              | Wal-Mart Stores, Inc.                        |                             |                                        | False          | 1.5        | 
```