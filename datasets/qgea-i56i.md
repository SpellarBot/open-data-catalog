# NYPD Complaint Data Historic

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nypd-complaint-data-historic) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qgea-i56i) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qgea-i56i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qgea-i56i/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qgea-i56i |
| Name | NYPD Complaint Data Historic |
| Attribution | Police Department (NYPD) |
| Category | Public Safety |
| Tags | nypd, incident, crime, nycopendata |
| Created | 2016-11-02T16:06:26Z |
| Publication Date | 2016-11-15T18:52:34Z |

## Description

This dataset includes all valid felony, misdemeanor, and violation crimes reported to the New York City Police Department (NYPD) from 2006 to the end of last year (2015). For additional details, please see the attached data dictionary in the ?About? section.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | cmplnt_num        | CMPLNT_NUM        | text          | number        |
| No       |                | cmplnt_fr_dt      | CMPLNT_FR_DT      | calendar_date | calendar_date |
| Yes      | series tag     | cmplnt_fr_tm      | CMPLNT_FR_TM      | text          | text          |
| No       |                | cmplnt_to_dt      | CMPLNT_TO_DT      | calendar_date | calendar_date |
| Yes      | series tag     | cmplnt_to_tm      | CMPLNT_TO_TM      | text          | text          |
| Yes      | time           | rpt_dt            | RPT_DT            | calendar_date | calendar_date |
| Yes      | numeric metric | ky_cd             | KY_CD             | number        | number        |
| Yes      | series tag     | ofns_desc         | OFNS_DESC         | text          | text          |
| Yes      | numeric metric | pd_cd             | PD_CD             | number        | number        |
| Yes      | series tag     | pd_desc           | PD_DESC           | text          | text          |
| Yes      | series tag     | crm_atpt_cptd_cd  | CRM_ATPT_CPTD_CD  | text          | text          |
| Yes      | series tag     | law_cat_cd        | LAW_CAT_CD        | text          | text          |
| Yes      | series tag     | juris_desc        | JURIS_DESC        | text          | text          |
| Yes      | series tag     | boro_nm           | BORO_NM           | text          | text          |
| Yes      | numeric metric | addr_pct_cd       | ADDR_PCT_CD       | number        | number        |
| Yes      | series tag     | loc_of_occur_desc | LOC_OF_OCCUR_DESC | text          | text          |
| Yes      | series tag     | prem_typ_desc     | PREM_TYP_DESC     | text          | text          |
| Yes      | series tag     | parks_nm          | PARKS_NM          | text          | text          |
| Yes      | series tag     | hadevelopt        | HADEVELOPT        | text          | text          |
| Yes      | numeric metric | x_coord_cd        | X_COORD_CD        | number        | number        |
| Yes      | numeric metric | y_coord_cd        | Y_COORD_CD        | number        | number        |
| No       |                | latitude          | Latitude          | number        | number        |
| No       |                | longitude         | Longitude         | number        | number        |
```

## Time Field

```ls
Value = rpt_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = cmplnt_to_dt,cmplnt_fr_dt,latitude,longitude
```

## Data Commands

```ls
series e:qgea-i56i d:2015-12-31T00:00:00.000Z t:boro_nm=BRONX t:juris_desc="N.Y. POLICE DEPT" t:ofns_desc=FORGERY t:cmplnt_fr_tm=23:45:00 t:pd_desc=FORGERY,ETC.,UNCLASSIFIED-FELO t:cmplnt_num=101109527 t:crm_atpt_cptd_cd=COMPLETED t:law_cat_cd=FELONY t:prem_typ_desc="BAR/NIGHT CLUB" t:loc_of_occur_desc=INSIDE m:x_coord_cd=1007314 m:ky_cd=113 m:pd_cd=729 m:y_coord_cd=241257 m:addr_pct_cd=44

series e:qgea-i56i d:2015-12-31T00:00:00.000Z t:boro_nm=QUEENS t:juris_desc="N.Y. POLICE DEPT" t:ofns_desc="MURDER & NON-NEGL. MANSLAUGHTER" t:cmplnt_fr_tm=23:36:00 t:cmplnt_num=153401121 t:crm_atpt_cptd_cd=COMPLETED t:law_cat_cd=FELONY t:loc_of_occur_desc=OUTSIDE m:x_coord_cd=1043991 m:ky_cd=101 m:y_coord_cd=193406 m:addr_pct_cd=103

series e:qgea-i56i d:2015-12-31T00:00:00.000Z t:boro_nm=MANHATTAN t:juris_desc="N.Y. POLICE DEPT" t:ofns_desc="DANGEROUS DRUGS" t:cmplnt_fr_tm=23:30:00 t:pd_desc="CONTROLLED SUBSTANCE,INTENT TO" t:cmplnt_num=569369778 t:crm_atpt_cptd_cd=COMPLETED t:law_cat_cd=FELONY t:prem_typ_desc=OTHER m:x_coord_cd=999463 m:ky_cd=117 m:pd_cd=503 m:y_coord_cd=231690 m:addr_pct_cd=28
```

## Meta Commands

```ls
metric m:ky_cd p:integer l:KY_CD t:dataTypeName=number

metric m:pd_cd p:float l:PD_CD t:dataTypeName=number

metric m:addr_pct_cd p:double l:ADDR_PCT_CD t:dataTypeName=number

metric m:x_coord_cd p:float l:X_COORD_CD t:dataTypeName=number

metric m:y_coord_cd p:float l:Y_COORD_CD t:dataTypeName=number

entity e:qgea-i56i l:"NYPD Complaint Data Historic" t:attribution="Police Department (NYPD)" t:url=https://data.cityofnewyork.us/api/views/qgea-i56i

property e:qgea-i56i t:meta.view v:id=qgea-i56i v:category="Public Safety" v:averageRating=0 v:name="NYPD Complaint Data Historic" v:attribution="Police Department (NYPD)"

property e:qgea-i56i t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qgea-i56i t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| cmplnt_num | cmplnt_fr_dt        | cmplnt_fr_tm | cmplnt_to_dt        | cmplnt_to_tm | rpt_dt              | ky_cd | ofns_desc                       | pd_cd | pd_desc                        | crm_atpt_cptd_cd | law_cat_cd  | juris_desc       | boro_nm   | addr_pct_cd | loc_of_occur_desc | prem_typ_desc          | parks_nm | hadevelopt | x_coord_cd | y_coord_cd | latitude     | longitude     | 
| ========== | =================== | ============ | =================== | ============ | =================== | ===== | =============================== | ===== | ============================== | ================ | =========== | ================ | ========= | =========== | ================= | ====================== | ======== | ========== | ========== | ========== | ============ | ============= | 
| 101109527  | 2015-12-31T00:00:00 | 23:45:00     |                     |              | 2015-12-31T00:00:00 | 113   | FORGERY                         | 729.0 | FORGERY,ETC.,UNCLASSIFIED-FELO | COMPLETED        | FELONY      | N.Y. POLICE DEPT | BRONX     | 44          | INSIDE            | BAR/NIGHT CLUB         |          |            | 1007314.0  | 241257.0   | 40.828848333 | -73.916661142 | 
| 153401121  | 2015-12-31T00:00:00 | 23:36:00     |                     |              | 2015-12-31T00:00:00 | 101   | MURDER & NON-NEGL. MANSLAUGHTER |       |                                | COMPLETED        | FELONY      | N.Y. POLICE DEPT | QUEENS    | 103         | OUTSIDE           |                        |          |            | 1043991.0  | 193406.0   | 40.697338138 | -73.784556739 | 
| 569369778  | 2015-12-31T00:00:00 | 23:30:00     |                     |              | 2015-12-31T00:00:00 | 117   | DANGEROUS DRUGS                 | 503.0 | CONTROLLED SUBSTANCE,INTENT TO | COMPLETED        | FELONY      | N.Y. POLICE DEPT | MANHATTAN | 28          |                   | OTHER                  |          |            | 999463.0   | 231690.0   | 40.802606608 | -73.945051911 | 
| 968417082  | 2015-12-31T00:00:00 | 23:30:00     |                     |              | 2015-12-31T00:00:00 | 344   | ASSAULT 3 & RELATED OFFENSES    | 101.0 | ASSAULT 3                      | COMPLETED        | MISDEMEANOR | N.Y. POLICE DEPT | QUEENS    | 105         | INSIDE            | RESIDENCE-HOUSE        |          |            | 1060183.0  | 177862.0   | 40.654549444 | -73.726338791 | 
| 641637920  | 2015-12-31T00:00:00 | 23:25:00     | 2015-12-31T00:00:00 | 23:30:00     | 2015-12-31T00:00:00 | 344   | ASSAULT 3 & RELATED OFFENSES    | 101.0 | ASSAULT 3                      | COMPLETED        | MISDEMEANOR | N.Y. POLICE DEPT | MANHATTAN | 13          | FRONT OF          | OTHER                  |          |            | 987606.0   | 208148.0   | 40.7380024   | -73.98789129  | 
| 365661343  | 2015-12-31T00:00:00 | 23:18:00     | 2015-12-31T00:00:00 | 23:25:00     | 2015-12-31T00:00:00 | 106   | FELONY ASSAULT                  | 109.0 | ASSAULT 2,1,UNCLASSIFIED       | ATTEMPTED        | FELONY      | N.Y. POLICE DEPT | BROOKLYN  | 71          | FRONT OF          | DRUG STORE             |          |            | 996149.0   | 181562.0   | 40.665022689 | -73.957110763 | 
| 608231454  | 2015-12-31T00:00:00 | 23:15:00     |                     |              | 2015-12-31T00:00:00 | 235   | DANGEROUS DRUGS                 | 511.0 | CONTROLLED SUBSTANCE, POSSESSI | COMPLETED        | MISDEMEANOR | N.Y. POLICE DEPT | MANHATTAN | 7           | OPPOSITE OF       | STREET                 |          |            | 987373.0   | 201662.0   | 40.720199996 | -73.988735082 | 
| 265023856  | 2015-12-31T00:00:00 | 23:15:00     | 2015-12-31T00:00:00 | 23:15:00     | 2015-12-31T00:00:00 | 118   | DANGEROUS WEAPONS               | 792.0 | WEAPONS POSSESSION 1 & 2       | COMPLETED        | FELONY      | N.Y. POLICE DEPT | BRONX     | 46          | FRONT OF          | STREET                 |          |            | 1009041.0  | 247401.0   | 40.845707148 | -73.910398033 | 
| 989238731  | 2015-12-31T00:00:00 | 23:15:00     | 2015-12-31T00:00:00 | 23:30:00     | 2015-12-31T00:00:00 | 344   | ASSAULT 3 & RELATED OFFENSES    | 101.0 | ASSAULT 3                      | COMPLETED        | MISDEMEANOR | N.Y. POLICE DEPT | BRONX     | 48          | INSIDE            | RESIDENCE - APT. HOUSE |          |            | 1014154.0  | 251416.0   | 40.856711291 | -73.891899956 | 
| 415095955  | 2015-12-31T00:00:00 | 23:10:00     | 2015-12-31T00:00:00 | 23:10:00     | 2015-12-31T00:00:00 | 341   | PETIT LARCENY                   | 338.0 | LARCENY,PETIT FROM BUILDING,UN | COMPLETED        | MISDEMEANOR | N.Y. POLICE DEPT | MANHATTAN | 19          | INSIDE            | DRUG STORE             |          |            | 994327.0   | 218211.0   | 40.765617688 | -73.96362342  | 
```