# Physician Compare National Downloadable File

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/physician-compare-national-downloadable-file) |
| Metadata | [Link](https://data.medicare.gov/api/views/mj5m-pzi6) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/mj5m-pzi6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/mj5m-pzi6/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | mj5m-pzi6 |
| Name | Physician Compare National Downloadable File |
| Category | Physician Compare |
| Tags | physician compare, healthcare professional, eligible professional, physicians, doctors |
| Created | 2016-06-24T20:40:39Z |
| Publication Date | 2017-04-13T16:38:19Z |

## Description

The Physician Compare National Downloadable File  is organized at the individual eligible professional level; each line is unique at the professional/enrollment record/Group Practice/address level. Professionals with multiple Medicare enrollment records and/or single enrollments linking to multiple practice location addresses are listed on multiple lines.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name                                                               | Data Type | Render Type |
| ======== | ============== | ============== | ================================================================== | ========= | =========== |
| No       | time           | :updated_at    | updated_at                                                         | meta_data | meta_data   |
| Yes      | numeric metric | npi            | NPI                                                                | number    | text        |
| Yes      | series tag     | ind_pac_id     | PAC ID                                                             | text      | text        |
| Yes      | series tag     | ind_enrl_id    | Professional Enrollment ID                                         | text      | text        |
| Yes      | series tag     | lst_nm         | Last Name                                                          | text      | text        |
| Yes      | series tag     | frst_nm        | First Name                                                         | text      | text        |
| Yes      | series tag     | mid_nm         | Middle Name                                                        | text      | text        |
| Yes      | series tag     | suff           | Suffix                                                             | text      | text        |
| Yes      | series tag     | gndr           | Gender                                                             | text      | text        |
| Yes      | series tag     | cred           | Credential                                                         | text      | text        |
| Yes      | series tag     | med_sch        | Medical school name                                                | text      | text        |
| Yes      | numeric metric | grd_yr         | Graduation year                                                    | number    | number      |
| Yes      | series tag     | pri_spec       | Primary specialty                                                  | text      | text        |
| Yes      | series tag     | sec_spec_1     | Secondary specialty 1                                              | text      | text        |
| Yes      | series tag     | sec_spec_2     | Secondary specialty 2                                              | text      | text        |
| Yes      | series tag     | sec_spec_3     | Secondary specialty 3                                              | text      | text        |
| Yes      | series tag     | sec_spec_4     | Secondary specialty 4                                              | text      | text        |
| Yes      | series tag     | sec_spec_all   | All secondary specialties                                          | text      | text        |
| Yes      | series tag     | org_lgl_nm     | Organization legal name                                            | text      | text        |
| Yes      | series tag     | org_pac_id     | Group Practice PAC ID                                              | text      | text        |
| Yes      | numeric metric | num_org_mem    | Number of Group Practice members                                   | number    | number      |
| Yes      | series tag     | adr_ln_1       | Line 1 Street Address                                              | text      | text        |
| Yes      | series tag     | adr_ln_2       | Line 2 Street Address                                              | text      | text        |
| No       |                | ln_2_sprs      | Marker of address line 2 suppression                               | text      | text        |
| Yes      | series tag     | cty            | City                                                               | text      | text        |
| No       |                | st             | State                                                              | text      | text        |
| Yes      | series tag     | zip            | Zip Code                                                           | text      | text        |
| Yes      | series tag     | phn_numbr      | Phone Number                                                       | text      | text        |
| Yes      | series tag     | hosp_afl_1     | Hospital affiliation CCN 1                                         | text      | text        |
| Yes      | series tag     | hosp_afl_lbn_1 | Hospital affiliation LBN 1                                         | text      | text        |
| Yes      | series tag     | hosp_afl_2     | Hospital affiliation CCN 2                                         | text      | text        |
| Yes      | series tag     | hosp_afl_lbn_2 | Hospital affiliation LBN 2                                         | text      | text        |
| Yes      | series tag     | hosp_afl_3     | Hospital affiliation CCN 3                                         | text      | text        |
| Yes      | series tag     | hosp_afl_lbn_3 | Hospital affiliation LBN 3                                         | text      | text        |
| Yes      | series tag     | hosp_afl_4     | Hospital affiliation CCN 4                                         | text      | text        |
| Yes      | series tag     | hosp_afl_lbn_4 | Hospital affiliation LBN 4                                         | text      | text        |
| Yes      | series tag     | hosp_afl_5     | Hospital affiliation CCN 5                                         | text      | text        |
| Yes      | series tag     | hosp_afl_lbn_5 | Hospital affiliation LBN 5                                         | text      | text        |
| Yes      | series tag     | assgn          | Professional accepts Medicare Assignment                           | text      | text        |
| Yes      | series tag     | pqrs           | Reported Quality Measures                                          | text      | text        |
| Yes      | series tag     | ehr            | Used electronic health records                                     | text      | text        |
| Yes      | series tag     | moc            | Participated in the Medicare Maintenance of Certification Program. | text      | text        |
| Yes      | series tag     | mhi            | Committed to heart health through the Million Hearts? initiative.  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = ln_2_sprs,st
```

## Data Commands

```ls
series e:mj5m-pzi6 d:2016-06-27T07:35:36.000Z t:zip=956673933 t:assgn=Y t:ind_enrl_id=I20120726000331 t:gndr=F t:phn_numbr=5306228041 t:frst_nm=ESTHER t:lst_nm=HALL t:pri_spec=CHIROPRACTIC t:cty=PLACERVILLE t:adr_ln_1="183 PLACERVILLE DR" t:ind_pac_id=4880850486 t:adr_ln_2="SUITE A" t:mid_nm=S t:med_sch="LIFE CHIROPRACTIC COLLEGE - WEST" m:npi=1487927612 m:grd_yr=2010

series e:mj5m-pzi6 d:2016-06-27T07:35:36.000Z t:zip=076312530 t:lst_nm=WHITE t:assgn=Y t:pri_spec="CLINICAL SOCIAL WORKER" t:cty=ENGLEWOOD t:ind_enrl_id=I20040406000367 t:adr_ln_1="163 ENGLE ST" t:ind_pac_id=2365435336 t:cred=CSW t:mid_nm=L t:phn_numbr=2014102812 t:gndr=F t:med_sch=OTHER t:frst_nm=BARBARA m:npi=1235146762 m:grd_yr=1992

series e:mj5m-pzi6 d:2016-06-27T07:35:36.000Z t:org_pac_id=1951388073 t:zip=956283541 t:assgn=M t:ind_enrl_id=I20040707000479 t:cred=DC t:gndr=M t:phn_numbr=9169677436 t:frst_nm=MARK t:org_lgl_nm="CASHA-CROSS CHIROPRACTIC, INC" t:lst_nm=CASHA t:pri_spec=CHIROPRACTIC t:cty="FAIR OAKS" t:adr_ln_1="5330 PRIMROSE DR" t:ind_pac_id=5799762829 t:mid_nm=S t:med_sch=OTHER m:num_org_mem=2 m:npi=1285727842 m:grd_yr=1981
```

## Meta Commands

```ls
metric m:npi p:integer l:NPI d:"Unique professional ID assigned by NPPES" t:dataTypeName=number

metric m:grd_yr p:integer l:"Graduation year" d:"Individual professional's medical school graduation year" t:dataTypeName=number

metric m:num_org_mem p:integer l:"Number of Group Practice members" d:"Total number of individual professionals affiliated with the Group Practice based on Group Practice PAC ID" t:dataTypeName=number

entity e:mj5m-pzi6 l:"Physician Compare National Downloadable File" t:url=https://data.medicare.gov/api/views/mj5m-pzi6

property e:mj5m-pzi6 t:meta.view v:id=mj5m-pzi6 v:category="Physician Compare" v:averageRating=0 v:name="Physician Compare National Downloadable File"

property e:mj5m-pzi6 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:mj5m-pzi6 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:mj5m-pzi6 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=PhysicianCompare@westat.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | npi        | ind_pac_id | ind_enrl_id     | lst_nm   | frst_nm | mid_nm | suff | gndr | cred | med_sch                                   | grd_yr | pri_spec               | sec_spec_1 | sec_spec_2 | sec_spec_3 | sec_spec_4 | sec_spec_all | org_lgl_nm                               | org_pac_id | num_org_mem | adr_ln_1            | adr_ln_2  | ln_2_sprs | cty         | st | zip       | phn_numbr  | hosp_afl_1 | hosp_afl_lbn_1 | hosp_afl_2 | hosp_afl_lbn_2 | hosp_afl_3 | hosp_afl_lbn_3 | hosp_afl_4 | hosp_afl_lbn_4 | hosp_afl_5 | hosp_afl_lbn_5 | assgn | pqrs | ehr | moc | mhi | 
| =========== | ========== | ========== | =============== | ======== | ======= | ====== | ==== | ==== | ==== | ========================================= | ====== | ====================== | ========== | ========== | ========== | ========== | ============ | ======================================== | ========== | =========== | =================== | ========= | ========= | =========== | == | ========= | ========== | ========== | ============== | ========== | ============== | ========== | ============== | ========== | ============== | ========== | ============== | ===== | ==== | === | === | === | 
| 1467012936  | 1487927612 | 4880850486 | I20120726000331 | HALL     | ESTHER  | S      |      | F    |      | LIFE CHIROPRACTIC COLLEGE - WEST          | 2010   | CHIROPRACTIC           |            |            |            |            |              |                                          |            |             | 183 PLACERVILLE DR  | SUITE A   |           | PLACERVILLE | CA | 956673933 | 5306228041 |            |                |            |                |            |                |            |                |            |                | Y     |      |     |     |     | 
| 1467012936  | 1235146762 | 2365435336 | I20040406000367 | WHITE    | BARBARA | L      |      | F    | CSW  | OTHER                                     | 1992   | CLINICAL SOCIAL WORKER |            |            |            |            |              |                                          |            |             | 163 ENGLE ST        |           |           | ENGLEWOOD   | NJ | 076312530 | 2014102812 |            |                |            |                |            |                |            |                |            |                | Y     |      |     |     |     | 
| 1467012936  | 1285727842 | 5799762829 | I20040707000479 | CASHA    | MARK    | S      |      | M    | DC   | OTHER                                     | 1981   | CHIROPRACTIC           |            |            |            |            |              | CASHA-CROSS CHIROPRACTIC, INC            | 1951388073 | 2           | 5330 PRIMROSE DR    |           |           | FAIR OAKS   | CA | 956283541 | 9169677436 |            |                |            |                |            |                |            |                |            |                | M     |      |     |     |     | 
| 1467012936  | 1295821098 | 0840459889 | I20120309000459 | MORANZ   | JANICE  | F      |      | F    |      | OHIO STATE UNIVERSITY COLLEGE OF MEDICINE | 1984   | DERMATOLOGY            |            |            |            |            |              | SOUTHWEST INTEGRATIVE HEALTH CENTER, LLC | 6800954819 | 6           | 5310 HOMESTEAD NERD | SUITE 400 |           | ALBUQUERQUE | NM | 871101437 | 5052563648 |            |                |            |                |            |                |            |                |            |                | Y     |      |     |     |     | 
| 1467012936  | 1063514289 | 1951391671 | I20040514000778 | MCGREGOR | VICTOR  |        |      | M    | NP   | OTHER                                     | 1997   | NURSE PRACTITIONER     |            |            |            |            |              |                                          |            |             | 10 ANN ST           |           |           | SAUGERTIES  | NY | 124771804 | 8455322493 |            |                |            |                |            |                |            |                |            |                | Y     |      |     |     |     | 
| 1467012936  | 1346282258 | 5395768527 | I20060113000139 | DAVIDSON | JOHN    | A      |      | M    | CSW  | OTHER                                     | 1999   | CLINICAL SOCIAL WORKER |            |            |            |            |              |                                          |            |             | 9 KATTELVILLE RD    |           |           | BINGHAMTON  | NY | 139015821 | 6072456259 |            |                |            |                |            |                |            |                |            |                | Y     |      |     |     |     | 
| 1467012936  | 1932283124 | 5193762862 | I20050415000143 | CAGEN    | STEVEN  | F      |      | M    | DC   | SHERMAN COLLEGE OF STRAIGHT CHIROPRACTIC  | 1997   | CHIROPRACTIC           |            |            |            |            |              | CAGEN FAMILY CHIROPRACTIC PLLC           | 7012954787 | 2           | 1486 ASHEVILLE HWY  |           |           | BREVARD     | NC | 287129524 | 8288857100 |            |                |            |                |            |                |            |                |            |                | Y     |      |     |     |     | 
| 1467012936  | 1902950462 | 7416123666 | I20120110000522 | ESPY     | LEISHA  | H      |      | F    |      | LIFE CHIROPRACTIC COLLEGE                 | 1985   | CHIROPRACTIC           |            |            |            |            |              |                                          |            |             | 100 E GORDON AVE    |           |           | ROSSVILLE   | GA | 307411348 | 7068667557 |            |                |            |                |            |                |            |                |            |                | M     |      |     |     |     | 
| 1467012936  | 1518981026 | 7719166586 | I20110125001223 | PETROSKY | DAN     | M      |      | M    |      | OTHER                                     | 1976   | CHIROPRACTIC           |            |            |            |            |              |                                          |            |             | 125 N 6TH ST        |           |           | ALPINE      | TX | 798304607 | 4328371800 |            |                |            |                |            |                |            |                |            |                | M     |      |     |     |     | 
| 1467012936  | 1972698736 | 5294726436 | I20040518001235 | JANAS    | INNA    |        |      | F    | MD   | OTHER                                     | 1990   | INTERNAL MEDICINE      |            |            |            |            |              | NANDI JANAS MEDICAL, P.C.                | 7315961356 | 2           | 3501 202ND ST       |           |           | BAYSIDE     | NY | 113611117 | 7182247194 |            |                |            |                |            |                |            |                |            |                | Y     |      |     |     |     | 
```