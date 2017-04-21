# SFY05-14 Entries Aggregates Age Bands

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfy05-14-entries-aggregates-age-bands) |
| Metadata | [Link](https://data.ct.gov/api/views/fnfg-dct4) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/fnfg-dct4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/fnfg-dct4/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | fnfg-dct4 |
| Name | SFY05-14 Entries Aggregates Age Bands |
| Attribution | Department of Children and Families, Office for Research and Evaluation |
| Category | Health and Human Services |
| Tags | dcf, department of children and families, children, placement, age, age group, trend, foster care, congregate care |
| Created | 2015-08-11T12:48:27Z |
| Publication Date | 2015-08-12T12:39:15Z |

## Description

This dataset contains aggregate data concerning the number of children that entered DCF placement during a given SFY (July 1 ? June 30).  These figures are broken out by the DCF Region and Office responsible for the child's care, the child's Age Group (based on age on entry date), and by the categorical Placement Type into which the child was initially placed.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | ============== | ======================= | ======================= | ============= | ============= |
| Yes      | time           | data_as_of              | DATA_AS_OF              | calendar_date | calendar_date |
| Yes      | numeric metric | sfy_entry               | SFY_ENTRY               | number        | number        |
| Yes      | series tag     | region                  | REGION                  | text          | text          |
| Yes      | series tag     | office                  | OFFICE                  | text          | text          |
| Yes      | series tag     | demographic             | DEMOGRAPHIC             | text          | text          |
| Yes      | numeric metric | total_entries           | TOTAL_ENTRIES           | number        | number        |
| Yes      | numeric metric | foster_care             | FOSTER_CARE             | number        | number        |
| Yes      | numeric metric | relative_care           | RELATIVE_CARE           | number        | number        |
| Yes      | numeric metric | special_study           | SPECIAL_STUDY           | number        | number        |
| Yes      | numeric metric | therapeutic_foster_care | THERAPEUTIC_FOSTER_CARE | number        | number        |
| Yes      | numeric metric | pdc_safe_home           | PDC_SAFE_HOME           | number        | number        |
| Yes      | numeric metric | shelter                 | SHELTER                 | number        | number        |
| Yes      | numeric metric | group_home              | GROUP_HOME              | number        | number        |
| Yes      | numeric metric | residential             | RESIDENTIAL             | number        | number        |
| Yes      | numeric metric | dcf_highmeadows         | DCF_HIGHMEADOWS         | number        | number        |
| Yes      | numeric metric | dcf_solnit              | DCF_SOLNIT              | number        | number        |
| Yes      | numeric metric | hospital                | HOSPITAL                | number        | number        |
| Yes      | numeric metric | dcf_cjts                | DCF_CJTS                | number        | number        |
| Yes      | numeric metric | independent_living      | INDEPENDENT_LIVING      | number        | number        |
```

## Time Field

```ls
Value = data_as_of
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fnfg-dct4 d:2015-08-06T00:00:00.000Z t:region=Other t:office=Other t:demographic="Age 0-3" m:independent_living=0 m:dcf_solnit=0 m:dcf_highmeadows=0 m:residential=0 m:sfy_entry=2005 m:special_study=0 m:dcf_cjts=0 m:group_home=0 m:relative_care=2 m:shelter=0 m:pdc_safe_home=2 m:foster_care=6 m:therapeutic_foster_care=0 m:hospital=0 m:total_entries=10

series e:fnfg-dct4 d:2015-08-06T00:00:00.000Z t:region=Other t:office=Other t:demographic="Age 13-17" m:independent_living=0 m:dcf_solnit=4 m:dcf_highmeadows=0 m:residential=147 m:sfy_entry=2005 m:special_study=0 m:dcf_cjts=51 m:group_home=7 m:relative_care=1 m:shelter=0 m:pdc_safe_home=0 m:foster_care=1 m:therapeutic_foster_care=0 m:hospital=0 m:total_entries=211

series e:fnfg-dct4 d:2015-08-06T00:00:00.000Z t:region=Other t:office=Other t:demographic="Age 4-6" m:independent_living=0 m:dcf_solnit=0 m:dcf_highmeadows=0 m:residential=0 m:sfy_entry=2005 m:special_study=0 m:dcf_cjts=0 m:group_home=0 m:relative_care=1 m:shelter=0 m:pdc_safe_home=1 m:foster_care=2 m:therapeutic_foster_care=0 m:hospital=0 m:total_entries=4
```

## Meta Commands

```ls
metric m:sfy_entry p:integer l:SFY_ENTRY t:dataTypeName=number

metric m:total_entries p:integer l:TOTAL_ENTRIES t:dataTypeName=number

metric m:foster_care p:integer l:FOSTER_CARE t:dataTypeName=number

metric m:relative_care p:integer l:RELATIVE_CARE t:dataTypeName=number

metric m:special_study p:integer l:SPECIAL_STUDY t:dataTypeName=number

metric m:therapeutic_foster_care p:integer l:THERAPEUTIC_FOSTER_CARE t:dataTypeName=number

metric m:pdc_safe_home p:integer l:PDC_SAFE_HOME t:dataTypeName=number

metric m:shelter p:integer l:SHELTER t:dataTypeName=number

metric m:group_home p:integer l:GROUP_HOME t:dataTypeName=number

metric m:residential p:integer l:RESIDENTIAL t:dataTypeName=number

metric m:dcf_highmeadows p:integer l:DCF_HIGHMEADOWS t:dataTypeName=number

metric m:dcf_solnit p:integer l:DCF_SOLNIT t:dataTypeName=number

metric m:hospital p:integer l:HOSPITAL t:dataTypeName=number

metric m:dcf_cjts p:integer l:DCF_CJTS t:dataTypeName=number

metric m:independent_living p:integer l:INDEPENDENT_LIVING t:dataTypeName=number

entity e:fnfg-dct4 l:"SFY05-14 Entries Aggregates Age Bands" t:attribution="Department of Children and Families, Office for Research and Evaluation" t:url=https://data.ct.gov/api/views/fnfg-dct4

property e:fnfg-dct4 t:meta.view v:id=fnfg-dct4 v:category="Health and Human Services" v:averageRating=0 v:name="SFY05-14 Entries Aggregates Age Bands" v:attribution="Department of Children and Families, Office for Research and Evaluation"

property e:fnfg-dct4 t:meta.view.license v:name="Public Domain"

property e:fnfg-dct4 t:meta.view.owner v:id=hd87-ziyn v:screenName="Fred North" v:displayName="Fred North"

property e:fnfg-dct4 t:meta.view.tableauthor v:id=hd87-ziyn v:screenName="Fred North" v:roleName=editor v:displayName="Fred North"
```

## Top Records

```ls
| data_as_of          | sfy_entry | region   | office            | demographic | total_entries | foster_care | relative_care | special_study | therapeutic_foster_care | pdc_safe_home | shelter | group_home | residential | dcf_highmeadows | dcf_solnit | hospital | dcf_cjts | independent_living | 
| =================== | ========= | ======== | ================= | =========== | ============= | =========== | ============= | ============= | ======================= | ============= | ======= | ========== | =========== | =============== | ========== | ======== | ======== | ================== | 
| 2015-08-06T00:00:00 | 2005      | Other    | Other             | Age 0-3     | 10            | 6           | 2             | 0             | 0                       | 2             | 0       | 0          | 0           | 0               | 0          | 0        | 0        | 0                  | 
| 2015-08-06T00:00:00 | 2005      | Other    | Other             | Age 13-17   | 211           | 1           | 1             | 0             | 0                       | 0             | 0       | 7          | 147         | 0               | 4          | 0        | 51       | 0                  | 
| 2015-08-06T00:00:00 | 2005      | Other    | Other             | Age 4-6     | 4             | 2           | 1             | 0             | 0                       | 1             | 0       | 0          | 0           | 0               | 0          | 0        | 0        | 0                  | 
| 2015-08-06T00:00:00 | 2005      | Other    | Other             | Age 7-12    | 6             | 2           | 3             | 0             | 0                       | 1             | 0       | 0          | 0           | 0               | 0          | 0        | 0        | 0                  | 
| 2015-08-06T00:00:00 | 2005      | Region 1 | Bridgeport Office | Age >=18    | 2             | 0           | 0             | 0             | 0                       | 0             | 0       | 0          | 1           | 0               | 0          | 0        | 0        | 1                  | 
| 2015-08-06T00:00:00 | 2005      | Region 1 | Bridgeport Office | Age 0-3     | 88            | 57          | 11            | 1             | 4                       | 12            | 1       | 1          | 0           | 0               | 0          | 1        | 0        | 0                  | 
| 2015-08-06T00:00:00 | 2005      | Region 1 | Bridgeport Office | Age 13-17   | 96            | 39          | 8             | 1             | 1                       | 2             | 14      | 4          | 21          | 2               | 1          | 0        | 3        | 0                  | 
| 2015-08-06T00:00:00 | 2005      | Region 1 | Bridgeport Office | Age 4-6     | 38            | 20          | 7             | 0             | 1                       | 10            | 0       | 0          | 0           | 0               | 0          | 0        | 0        | 0                  | 
| 2015-08-06T00:00:00 | 2005      | Region 1 | Bridgeport Office | Age 7-12    | 72            | 30          | 10            | 1             | 0                       | 25            | 2       | 0          | 3           | 0               | 1          | 0        | 0        | 0                  | 
| 2015-08-06T00:00:00 | 2005      | Region 1 | Norwalk Office    | Age >=18    | 1             | 1           | 0             | 0             | 0                       | 0             | 0       | 0          | 0           | 0               | 0          | 0        | 0        | 0                  | 
```