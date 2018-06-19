# University Of Hawaii - Degrees Awarded By Major, CIP, And Hawaiian Legacy

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/university-of-hawaii-degrees-awarded-by-major-cip-and-hawaiian-legacy-6aeed) |
| Metadata | [Link](https://data.hawaii.gov/api/views/7bfs-svqv) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/7bfs-svqv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/7bfs-svqv/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 7bfs-svqv |
| Name | University Of Hawaii - Degrees Awarded By Major, CIP, And Hawaiian Legacy |
| Category | Formal Education |
| Tags | degrees, outcomes, higher education, college, university |
| Created | 2013-08-01T20:29:09Z |
| Publication Date | 2015-09-18T18:39:14Z |

## Description

Degrees awarded for Fiscal Years 2010, 2011, 2012, 2013, 2014

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year     | FISCAL_YEAR     | text      | text        |
| Yes      | series tag     | campus          | CAMPUS          | text      | text        |
| Yes      | series tag     | cip             | CIP             | text      | text        |
| Yes      | series tag     | cip_desc        | CIP_DESC        | text      | text        |
| Yes      | series tag     | group1          | GROUP1          | text      | text        |
| Yes      | series tag     | group2          | GROUP2          | text      | text        |
| Yes      | series tag     | group3          | GROUP3          | text      | text        |
| Yes      | series tag     | group4          | GROUP4          | text      | text        |
| Yes      | series tag     | group5          | GROUP5          | text      | text        |
| Yes      | series tag     | outcome         | OUTCOME         | text      | text        |
| Yes      | series tag     | hawaiian_legacy | HAWAIIAN_LEGACY | text      | text        |
| Yes      | numeric metric | awards          | AWARDS          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7bfs-svqv d:2015-09-18T11:38:22.000Z t:fiscal_year="Fiscal Year 2010" t:group3=Law t:group1="School of Law" t:group2="School of Law" t:outcome=Other t:cip_desc=Law t:cip=220101 t:campus="UH Manoa" m:awards=69

series e:7bfs-svqv d:2015-09-18T11:38:22.000Z t:fiscal_year="Fiscal Year 2010" t:group3="Liberal Arts" t:group1="General & Pre-Prof Ed" t:group2="Liberal Arts" t:outcome="Associate Degrees" t:cip_desc="Liberal Arts" t:cip=240101 t:campus="Kapi`olani CC" m:awards=322

series e:7bfs-svqv d:2015-09-18T11:38:22.000Z t:fiscal_year="Fiscal Year 2010" t:group3=Nursing t:group4=Nursing t:group1="Career & Tech Ed" t:group2="Health Services" t:outcome="Associate Degrees" t:cip_desc="Registered Nursing/Reg Nurse" t:cip=513801 t:campus="Maui CC" m:awards=43
```

## Meta Commands

```ls
metric m:awards p:integer l:AWARDS t:dataTypeName=number

entity e:7bfs-svqv l:"University Of Hawaii - Degrees Awarded By Major, CIP, And Hawaiian Legacy" t:url=https://data.hawaii.gov/api/views/7bfs-svqv

property e:7bfs-svqv t:meta.view v:id=7bfs-svqv v:category="Formal Education" v:averageRating=0 v:name="University Of Hawaii - Degrees Awarded By Major, CIP, And Hawaiian Legacy"

property e:7bfs-svqv t:meta.view.owner v:id=axmy-vcri v:screenName="Jared Takazawa" v:displayName="Jared Takazawa"

property e:7bfs-svqv t:meta.view.tableauthor v:id=axmy-vcri v:screenName="Jared Takazawa" v:roleName=editor v:displayName="Jared Takazawa"
```

## Top Records

```ls
| :updated_at | fiscal_year      | campus        | cip    | cip_desc                       | group1                        | group2                   | group3               | group4  | group5 | outcome            | hawaiian_legacy | awards | 
| =========== | ================ | ============= | ====== | ============================== | ============================= | ======================== | ==================== | ======= | ====== | ================== | =============== | ====== | 
| 1442576302  | Fiscal Year 2010 | UH Manoa      | 220101 | Law                            | School of Law                 | School of Law            | Law                  |         |        | Other              |                 | 69     | 
| 1442576302  | Fiscal Year 2010 | Kapi`olani CC | 240101 | Liberal Arts                   | General & Pre-Prof Ed         | Liberal Arts             | Liberal Arts         |         |        | Associate Degrees  |                 | 322    | 
| 1442576302  | Fiscal Year 2010 | Maui CC       | 513801 | Registered Nursing/Reg Nurse   | Career & Tech Ed              | Health Services          | Nursing              | Nursing |        | Associate Degrees  |                 | 43     | 
| 1442576302  | Fiscal Year 2010 | Honolulu CC   | 460201 | Carpentry                      | Career & Tech Ed              | Technology               | Carpentry Technology |         |        | Associate Degrees  |                 | 5      | 
| 1442576302  | Fiscal Year 2010 | Kaua`i CC     | 240101 | Liberal Arts                   | General & Pre-Prof Ed         | Liberal Arts             | Liberal Arts         |         |        | Associate Degrees  | HAWAIIAN        | 12     | 
| 1442576302  | Fiscal Year 2010 | UH West O`ahu | 520201 | Business Admin & Mgmt, General | Professional Studies Division | Business Administration  | Accounting           |         |        | Bachelor's Degrees | HAWAIIAN        | 7      | 
| 1442576302  | Fiscal Year 2010 | UH Manoa      | 521401 | Marketing                      | College of Business Admin     | Business Administration  | Marketing            |         |        | Bachelor's Degrees |                 | 95     | 
| 1442576302  | Fiscal Year 2010 | UH Manoa      | 500501 | Drama & Theatre                | College of Arts & Sciences    | Arts & Humanities        | Theater & Dance      | Theatre |        | Bachelor's Degrees |                 | 8      | 
| 1442576302  | Fiscal Year 2010 | Leeward CC    | 240101 | Liberal Arts                   | General & Pre-Prof Ed         | Liberal Arts             | Liberal Arts         |         |        | Associate Degrees  |                 | 280    | 
| 1442576302  | Fiscal Year 2010 | UH Manoa      | 513801 | Registered Nursing/Reg Nurse   | Schl of Nurs & Dental Hygiene | Nursing & Dental Hygiene | Professional Nursing | Nursing |        | Bachelor's Degrees |                 | 94     | 
```