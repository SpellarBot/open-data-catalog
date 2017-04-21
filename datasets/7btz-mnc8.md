# NYC REACH Members

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nyc-reach-members-4584f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7btz-mnc8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7btz-mnc8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7btz-mnc8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7btz-mnc8 |
| Name | NYC REACH Members |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Health |
| Tags | ehr, electronic health record, doctor, location, record, health |
| Created | 2013-11-20T16:11:45Z |
| Publication Date | 2017-01-21T20:33:45Z |

## Description

The location and facility information for doctors who participate in NYC Regional Electronic Adoption Center for Health (REACH), which assists providers in adopting technology and methods for electronic health records.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | provider_first_name      | Provider First Name      | text      | text        |
| Yes      | series tag  | provider_last_name       | Provider Last Name       | text      | text        |
| Yes      | series tag  | practice_name            | Practice Name            | text      | text        |
| Yes      | series tag  | primary_speciality       | Primary Speciality       | text      | text        |
| Yes      | series tag  | site_name                | Site Name                | text      | text        |
| Yes      | series tag  | practice_borough         | Practice Borough         | text      | text        |
| No       |             | practice_mailing_address | Practice Mailing Address | text      | text        |
| Yes      | series tag  | practice_phone_number    | Practice Phone Number    | text      | text        |
| Yes      | series tag  | organization_type        | Organization Type        | text      | text        |
| Yes      | series tag  | practice_zip_code        | Practice Zip Code        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = practice_mailing_address
```

## Data Commands

```ls
series e:7btz-mnc8 d:2017-01-21T20:33:32.000Z t:provider_last_name=Santana t:provider_first_name=Domingo t:practice_phone_number="(718) 676-4177" t:primary_speciality="Internal Medicine" t:practice_borough=Bronx t:practice_zip_code=10468 t:organization_type="Small Practice" t:site_name="Bethel Medical Practice,P.C" t:practice_name="Bethel Medical Practice,P.C" m:row_number.7btz-mnc8=1

series e:7btz-mnc8 d:2017-01-21T20:33:32.000Z t:provider_last_name=Hegazi t:provider_first_name=Tarek t:practice_phone_number="(718) 721-6100" t:primary_speciality="Family Medicine" t:practice_borough=Queens t:practice_zip_code=11103 t:organization_type="Small Practice" t:site_name="Better Care Inc." t:practice_name="Better Care Inc." m:row_number.7btz-mnc8=2

series e:7btz-mnc8 d:2017-01-21T20:33:32.000Z t:provider_last_name=Mohammed t:provider_first_name=Magdy t:practice_phone_number="(718) 721-6100" t:primary_speciality=Pediatrics t:practice_borough=Queens t:practice_zip_code=11103 t:organization_type="Small Practice" t:site_name="Better Care Inc." t:practice_name="Better Care Inc." m:row_number.7btz-mnc8=3
```

## Meta Commands

```ls
metric m:row_number.7btz-mnc8 p:long l:"Row Number"

entity e:7btz-mnc8 l:"NYC REACH Members" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/7btz-mnc8

property e:7btz-mnc8 t:meta.view v:id=7btz-mnc8 v:category=Health v:averageRating=0 v:name="NYC REACH Members" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:7btz-mnc8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7btz-mnc8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | provider_first_name | provider_last_name | practice_name                | primary_speciality | site_name                         | practice_borough | practice_mailing_address     | practice_phone_number          | organization_type | practice_zip_code | 
| =========== | =================== | ================== | ============================ | ================== | ================================= | ================ | ============================ | ============================== | ================= | ================= | 
| 1485030812  | Domingo             | Santana            | Bethel Medical Practice,P.C  | Internal Medicine  | Bethel Medical Practice,P.C       | Bronx            | 2869 Grand concouese suite11 | (718) 676-4177                 | Small Practice    | 10468             | 
| 1485030812  | Tarek               | Hegazi             | Better Care Inc.             | Family Medicine    | Better Care Inc.                  | Queens           | 25-92 steinway street        | (718) 721-6100                 | Small Practice    | 11103             | 
| 1485030812  | Magdy               | Mohammed           | Better Care Inc.             | Pediatrics         | Better Care Inc.                  | Queens           | 25-92 steinway street        | (718) 721-6100                 | Small Practice    | 11103             | 
| 1485030812  | Beverly             | Hurd               | Beverly W. Hurd, MD PC       | Internal Medicine  | Beverly W, Hurd MD PC             | Manhattan        | 342 East 77 St               | (212) 734-6620                 | Small Practice    | 10075             | 
| 1485030812  | Bhavana             | Japi               | Bhavana R. Japi Physician PC | Internal Medicine  | Brooklyn                          | Brooklyn         | 34-40 Fulton Street          | (718) 235-1811 or 516-437-5356 | Small Practice    | 11208             | 
| 1485030812  | Altagracia          | Navarro            | Bienvenido Fajardo MD PC     | Internal Medicine  | Bienvenido Fajardo MD PC          | Manhattan        | 2-12 Sickles Street          | (212) 942-0808                 | Small Practice    | 10040             | 
| 1485030812  | Bienvenido          | Fajardo            | Bienvenido Fajardo MD PC     | Internal Medicine  | Bienvenido Fajardo MD PC          | Manhattan        | 2-12 Sickles Street          | (212) 942-0808                 | Small Practice    | 10040             | 
| 1485030812  | Billy               | Geris              | Billy Geris MD               | Internal Medicine  | Billy Geris MD - BG Medical       | Staten Island    | 4335 Hylan Blvd              | (917) 838-9245                 | Small Practice    | 10312             | 
| 1485030812  | Jean Pierre         | Barakat            | Billy Geris MD               | Internal Medicine  | Billy Geris MD - Grasmere Medical | Staten Island    | 4335 Hylan Blvd              | (917) 838-9245                 | Small Practice    | 10304             | 
| 1485030812  | PCP FTE             | Credit             | Billy Geris MD               |                    | Billy Geris MD - BG Medical       | Staten Island    | 4335 Hylan Blvd              | (917) 838-9245                 | Small Practice    | 10312             | 
```