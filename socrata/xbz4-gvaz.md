# Outpatient Procedures ? Volume

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/outpatient-procedures-volume-e39ba) |
| Metadata | [Link](https://data.medicare.gov/api/views/xbz4-gvaz) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/xbz4-gvaz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/xbz4-gvaz/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | xbz4-gvaz |
| Name | Outpatient Procedures ? Volume |
| Category | Hospital Compare |
| Tags | hospital compare, number of medicare patients |
| Created | 2014-05-09T14:35:42Z |
| Publication Date | 2016-12-19T02:12:55Z |

## Description

The aggregate count of selected outpatient procedures performed within the outpatient department from all-payer data.

## Columns

```ls
| Included | Schema Type | Field Name       | Name               | Data Type     | Render Type   |
| ======== | =========== | ================ | ================== | ============= | ============= |
| Yes      | series tag  | provider_id      | Provider ID        | text          | text          |
| Yes      | series tag  | hospital_name    | Hospital Name      | text          | text          |
| Yes      | series tag  | measure_id       | Measure ID         | text          | text          |
| Yes      | series tag  | gastrointestinal | Gastrointestinal   | text          | text          |
| Yes      | series tag  | eye              | Eye                | text          | text          |
| Yes      | series tag  | nervous_system   | Nervous System     | text          | text          |
| Yes      | series tag  | musculoskeletal  | Musculoskeletal    | text          | text          |
| Yes      | series tag  | skin             | Skin               | text          | text          |
| Yes      | series tag  | genitourinary    | Genitourinary      | text          | text          |
| Yes      | series tag  | cardiovascular   | Cardiovascular     | text          | text          |
| Yes      | series tag  | respiratory      | Respiratory        | text          | text          |
| Yes      | series tag  | other            | Other              | text          | text          |
| No       |             | footnote         | Footnote           | number        | text          |
| Yes      | time        | start_date       | Measure Start Date | calendar_date | calendar_date |
| No       |             | end_date         | Measure End Date   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = footnote,end_date
```

## Data Commands

```ls
series e:xbz4-gvaz d:2015-01-01T00:00:00.000Z t:hospital_name="SOUTHEAST ALABAMA MEDICAL CENTER" t:nervous_system=429 t:musculoskeletal=1202 t:respiratory=9 t:other=3965 t:measure_id=OP-26 t:provider_id=010001 t:genitourinary=1704 t:cardiovascular=9 t:gastrointestinal=683 t:skin=96 t:eye=313 m:row_number.xbz4-gvaz=1

series e:xbz4-gvaz d:2015-01-01T00:00:00.000Z t:hospital_name="MARSHALL MEDICAL CENTERS" t:nervous_system=829 t:musculoskeletal=319 t:respiratory=36 t:other=30 t:measure_id=OP-26 t:provider_id=010005 t:genitourinary=286 t:cardiovascular=201 t:gastrointestinal=4161 t:skin=482 t:eye=69 m:row_number.xbz4-gvaz=2

series e:xbz4-gvaz d:2015-01-01T00:00:00.000Z t:hospital_name="ELIZA COFFEE MEMORIAL HOSPITAL" t:nervous_system=70 t:musculoskeletal=159 t:respiratory=61 t:other=13 t:measure_id=OP-26 t:provider_id=010006 t:genitourinary=318 t:cardiovascular=807 t:gastrointestinal=5587 t:skin=260 t:eye=0 m:row_number.xbz4-gvaz=3
```

## Meta Commands

```ls
metric m:row_number.xbz4-gvaz p:long l:"Row Number"

entity e:xbz4-gvaz l:"Outpatient Procedures ? Volume" t:url=https://data.medicare.gov/api/views/xbz4-gvaz

property e:xbz4-gvaz t:meta.view v:id=xbz4-gvaz v:category="Hospital Compare" v:averageRating=0 v:name="Outpatient Procedures ? Volume"

property e:xbz4-gvaz t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:xbz4-gvaz t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:xbz4-gvaz t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HospitalCompare@hsag.com v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| provider_id | hospital_name                    | measure_id | gastrointestinal | eye  | nervous_system | musculoskeletal | skin | genitourinary | cardiovascular | respiratory | other | footnote | start_date          | end_date            | 
| =========== | ================================ | ========== | ================ | ==== | ============== | =============== | ==== | ============= | ============== | =========== | ===== | ======== | =================== | =================== | 
| 010001      | SOUTHEAST ALABAMA MEDICAL CENTER | OP-26      | 683              | 313  | 429            | 1202            | 96   | 1704          | 9              | 9           | 3965  |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010005      | MARSHALL MEDICAL CENTERS         | OP-26      | 4161             | 69   | 829            | 319             | 482  | 286           | 201            | 36          | 30    |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010006      | ELIZA COFFEE MEMORIAL HOSPITAL   | OP-26      | 5587             | 0    | 70             | 159             | 260  | 318           | 807            | 61          | 13    |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010007      | MIZELL MEMORIAL HOSPITAL         | OP-26      | 547              | 150  | 10             | 75              | 45   | 71            | 8              | 0           | 30    |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010008      | CRENSHAW COMMUNITY HOSPITAL      | OP-26      | 194              | 0    | 0              | 0               | 25   | 42            | 0              | 0           | 0     |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010011      | ST. VINCENT'S EAST               | OP-26      | 1602             | 0    | 351            | 196             | 113  | 375           | 2038           | 60          | 33    |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010012      | DEKALB REGIONAL MEDICAL CENTER   | OP-26      | 2935             | 56   | 15             | 80              | 155  | 185           | 185            | 0           | 18    |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010016      | SHELBY BAPTIST MEDICAL CENTER    | OP-26      | 2057             | 0    | 10             | 1067            | 1773 | 500           | 289            | 39          | 292   |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010018      | CALLAHAN EYE HOSPITAL            | OP-26      | 0                | 6423 | 0              | 0               | 272  | 0             | 0              | 0           | 0     |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| 010019      | HELEN KELLER HOSPITAL            | OP-26      | 4427             | 514  | 103            | 105             | 33   | 640           | 102            | 1           | 11    |          | 2015-01-01T00:00:00 | 2015-12-31T00:00:00 | 
```