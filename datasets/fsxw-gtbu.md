# Projects Awarded

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/projects-awarded-a555d) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fsxw-gtbu) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fsxw-gtbu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fsxw-gtbu/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fsxw-gtbu |
| Name | Projects Awarded |
| Created | 2014-12-30T01:23:41Z |
| Publication Date | 2016-12-03T01:16:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | time           | award_date  | Award Date  | calendar_date | calendar_date |
| Yes      | series tag     | description | Description | text          | text          |
| Yes      | series tag     | dags_job_no | DAGS Job No | text          | text          |
| Yes      | series tag     | contractor  | Contractor  | text          | text          |
| Yes      | numeric metric | amount      | Amount      | money         | money         |
```

## Time Field

```ls
Value = award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fsxw-gtbu d:2016-11-29T00:00:00.000Z t:contractor="CLOSE CONSTRUCTION, INC." t:description="HAWAII FILM STUDIO - VARIOUS IMPROVEMENTS, PHASES 2 AND 3A" t:dags_job_no="1 2-26-7534" m:amount=3359535

series e:fsxw-gtbu d:2016-11-10T00:00:00.000Z t:contractor="ABHE & SVOBODA, INC." t:description="ALOHA STADIUM - HEALTH AND SAFETY IMPROVEMENTS, PHASE 4" t:dags_job_no="1 2-10-0797" m:amount=7616287

series e:fsxw-gtbu d:2016-10-07T00:00:00.000Z t:contractor="BRIAN'S CONTRACTING, INC" t:description="WASHINGTON PLACE - HEALTH, SAFETY, AND PRESERVATION IMPROVEMENTS" t:dags_job_no="1 2-10-0811" m:amount=2152000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:fsxw-gtbu l:"Projects Awarded" t:url=https://data.hawaii.gov/api/views/fsxw-gtbu

property e:fsxw-gtbu t:meta.view v:id=fsxw-gtbu v:averageRating=0 v:name="Projects Awarded"

property e:fsxw-gtbu t:meta.view.owner v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:displayName=sojiri

property e:fsxw-gtbu t:meta.view.tableauthor v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:roleName=publisher v:displayName=sojiri
```

## Top Records

```ls
| award_date          | description                                                                      | dags_job_no | contractor                | amount    | 
| =================== | ================================================================================ | =========== | ========================= | ========= | 
| 2016-11-29T00:00:00 | HAWAII FILM STUDIO - VARIOUS IMPROVEMENTS, PHASES 2 AND 3A                       | 1 2-26-7534 | CLOSE CONSTRUCTION, INC.  | 3359535   | 
| 2016-11-10T00:00:00 | ALOHA STADIUM - HEALTH AND SAFETY IMPROVEMENTS, PHASE 4                          | 1 2-10-0797 | ABHE & SVOBODA, INC.      | 7616287   | 
| 2016-10-07T00:00:00 | WASHINGTON PLACE - HEALTH, SAFETY, AND PRESERVATION IMPROVEMENTS                 | 1 2-10-0811 | BRIAN'S CONTRACTING, INC  | 2152000   | 
| 2016-09-23T00:00:00 | MAUI COMM CORR CENTER - UPPER CAMPUS, ROOFING REPAIRS AND IMPROVEMENTS           | 1 5-27-5667 | F & H CONSTRUCTION        | 1695107   | 
| 2016-09-15T00:00:00 | NO. 1 CAPITOL DISTRICT BUILDING - REROOF AND REPAIR EXTERIOR                     | 6 2-10-0742 | INOUYE, RALPH S. CO., LTD | 7083460   | 
| 2016-09-13T00:00:00 | KEKAULUOHI BUILDING - A/C SYSTEM IMPROVEMENTS AND EMERGENCY GENERATOR CONNECTION | 6 2-10-0744 | LTM CORPORATION           | 1378989   | 
| 2016-09-13T00:00:00 | HAWAII CONVENTION CENTER - VARIOUS REPAIRS AND IMPROVEMENTS, PHASE 1             | 4 2-26-7449 | DIEDE CONSTRUCTION, INC.  | 7797573.9 | 
| 2016-09-08T00:00:00 | KAIMUKI PUBLIC LIBRARY - REPLACE A/C CHILLERS & COOLING TOWER, & OTHER IMPROV.   | 6 2-36-6549 | LTM CORPORATION           | 1120745   | 
| 2016-09-07T00:00:00 | PARKING LOT V (VINEYARD GARAGE) - EXTERIOR REPAINTING AND RELATED WORK, PHASE 1  | 2 2-10-0802 | COLOR DYNAMICS,INC.       | 686550    | 
| 2016-09-07T00:00:00 | KEELIKOLANI BUILDING - REPLACE COOLING TOWERS AND REPAIR ENCLOSURE               | 6 2-10-0805 | LTM CORPORATION           | 1270210   | 
```