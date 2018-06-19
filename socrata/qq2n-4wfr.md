# Work Source Centers Location And Contact Info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/work-source-centers-location-and-contact-info-a3f22) |
| Metadata | [Link](https://data.lacity.org/api/views/qq2n-4wfr) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/qq2n-4wfr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/qq2n-4wfr/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | qq2n-4wfr |
| Name | Work Source Centers Location And Contact Info |
| Attribution | EWDD |
| Tags | ewdd, worksource, agency |
| Created | 2014-05-30T15:19:20Z |
| Publication Date | 2014-05-30T15:29:48Z |

## Description

Identifies EWDD WorkSource Centers along with related agency, location, and contact information.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | agency_name            | Agency Name            | text      | text        |
| Yes      | series tag  | worksource_wsc_name    | WorkSource (WSC) Name  | text      | text        |
| Yes      | series tag  | city                   | City                   | text      | text        |
| Yes      | series tag  | zip                    | Zip                    | text      | text        |
| Yes      | series tag  | wsc_phone              | WSC Phone              | text      | text        |
| Yes      | series tag  | program_director       | Program Director       | text      | text        |
| Yes      | series tag  | program_director_phone | Program Director Phone | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qq2n-4wfr d:2014-05-30T08:19:32.000Z t:zip=90292 t:wsc_phone="(310) 309-6000" t:program_director="Donald Perry" t:program_director_phone="(310) 309-6000" t:agency_name="Jewish Vocational Services" t:city="Marina Del Rey" t:worksource_wsc_name="Marina Del Rey-Mar Vista WSC" m:row_number.qq2n-4wfr=1

series e:qq2n-4wfr d:2014-05-30T08:19:32.000Z t:zip=90012 t:wsc_phone="(213) 808-1761" t:program_director="Angelica Martin" t:program_director_phone="(213) 808-1769" t:agency_name="Chinatown Service Center" t:city="Los Angeles" t:worksource_wsc_name="Chinatown WSC" m:row_number.qq2n-4wfr=2

series e:qq2n-4wfr d:2014-05-30T08:19:32.000Z t:zip=90031 t:wsc_phone="(323) 539-2000" t:program_director="Sergio Perez" t:program_director_phone="(323) 539-2048" t:agency_name="Goodwill Industries of Southern California" t:city="Los Angeles" t:worksource_wsc_name="Metro North LA WSC" m:row_number.qq2n-4wfr=3
```

## Meta Commands

```ls
metric m:row_number.qq2n-4wfr p:long l:"Row Number"

entity e:qq2n-4wfr l:"Work Source Centers Location And Contact Info" t:attribution=EWDD t:url=https://data.lacity.org/api/views/qq2n-4wfr

property e:qq2n-4wfr t:meta.view v:id=qq2n-4wfr v:averageRating=0 v:name="Work Source Centers Location And Contact Info" v:attribution=EWDD

property e:qq2n-4wfr t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:qq2n-4wfr t:meta.view.owner v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:displayName="Economic and Workforce Dev OpenData"

property e:qq2n-4wfr t:meta.view.tableauthor v:id=utpt-bj92 v:profileImageUrlMedium=/api/users/utpt-bj92/profile_images/THUMB v:profileImageUrlLarge=/api/users/utpt-bj92/profile_images/LARGE v:screenName="Economic and Workforce Dev OpenData" v:profileImageUrlSmall=/api/users/utpt-bj92/profile_images/TINY v:roleName=publisher v:displayName="Economic and Workforce Dev OpenData"
```

## Top Records

```ls
| :updated_at | agency_name                                                                                   | worksource_wsc_name          | city           | zip   | wsc_phone      | program_director  | program_director_phone | 
| =========== | ============================================================================================= | ============================ | ============== | ===== | ============== | ================= | ====================== | 
| 1401437972  | Jewish Vocational Services                                                                    | Marina Del Rey-Mar Vista WSC | Marina Del Rey | 90292 | (310) 309-6000 | Donald Perry      | (310) 309-6000         | 
| 1401437972  | Chinatown Service Center                                                                      | Chinatown WSC                | Los Angeles    | 90012 | (213) 808-1761 | Angelica Martin   | (213) 808-1769         | 
| 1401437972  | Goodwill Industries of Southern California                                                    | Metro North LA WSC           | Los Angeles    | 90031 | (323) 539-2000 | Sergio Perez      | (323) 539-2048         | 
| 1401437972  | Pacific Asian Consortium in Employment                                                        | Westlake WSC                 | Los Angeles    | 90017 | (213) 353-1677 | Johnson Ng        | (213) 207-1388         | 
| 1401437972  | Watts Labor Community Action Committee                                                        | Southeast LA-Watts WSC       | Los Angeles    | 90059 | (323) 563-4702 | Elton Blake       | (323) 563-5683         | 
| 1401437972  | Los Angeles Urban League                                                                      | West Adams-Baldwin Hills WSC | Los Angeles    | 90016 | (323) 525-3740 | Kuliema Blueford  | (323) 525-2255         | 
| 1401437972  | El Proyecto del Barrio, Inc.                                                                  | Sun Valley WSC               | Sun Valley     | 91352 | (818) 504-0334 | Magdalena Duran   | (818) 504-0334         | 
| 1401437972  | Managed Career Solutions, Inc.                                                                | Hollywood WSC                | Los Angeles    | 90029 | (323) 454-6100 | Margo Scoble      | (323) 454-6103         | 
| 1401437972  | City of Long Beach (as Administering Entity for Pacific Gateway Workforce Investment Network) | Harbor WSC                   | San Pedro      | 90731 | (800) 292-7200 | Cherie Gomez      | (562) 570-4715         | 
| 1401437972  | UAW - Labor Employment and Training Corporation                                               | Southeast LA-Crenshaw WSC    | Los Angeles    | 90037 | (323) 730-7900 | Henryetta Andrade | (323) 730-7900         | 
```