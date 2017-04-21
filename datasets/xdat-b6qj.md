# IDPH - Intermediate Care Facilities for Individuals with Intellectual Disabilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-intermediate-care-facilities-for-individuals-with-intellectual-disabilities-3614d) |
| Metadata | [Link](https://data.illinois.gov/api/views/xdat-b6qj) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/xdat-b6qj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/xdat-b6qj/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | xdat-b6qj |
| Name | IDPH - Intermediate Care Facilities for Individuals with Intellectual Disabilities |
| Attribution | Illinois Department of Public Health |
| Category | Public Health |
| Tags | intermediate care facilities, individuals with intellectual disabilities, residential and habilitation services |
| Created | 2013-07-02T15:03:25Z |
| Publication Date | 2013-07-02T15:15:21Z |

## Description

The Intermediate Care Facilities for Individuals with an Intellectual Disability or related conditions program provides residential and habilitation services to people with intellectual disabilities and/or a related condition.      

Facilities have been designated as such in this list by presence of Skilled Pediatrics (Under 22), ICF-DD (Intermediate Care Facilities for Intellectual Disabilities), or Community Living Beds.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag  | facility_name         | Facility Name         | text          | text          |
| Yes      | series tag  | licensee_id           | Licensee ID           | html          | html          |
| Yes      | series tag  | facility_id           | Facility ID           | html          | html          |
| Yes      | series tag  | certification_number  | Certification Number  | text          | text          |
| Yes      | series tag  | region                | Region                | text          | text          |
| Yes      | series tag  | county                | County                | text          | text          |
| Yes      | series tag  | telephone             | Telephone             | text          | text          |
| Yes      | series tag  | fax                   | Fax                   | text          | text          |
| Yes      | series tag  | ownership_desc        | Ownership Desc        | text          | text          |
| Yes      | series tag  | facility_status       | Facility Status       | text          | text          |
| Yes      | series tag  | license_status        | License Status        | text          | text          |
| No       |             | expiration_date       | Expiration Date       | calendar_date | calendar_date |
| Yes      | time        | last_survey_date      | Last Survey Date      | calendar_date | calendar_date |
| Yes      | series tag  | skilled_beds          | Skilled Beds          | html          | html          |
| Yes      | series tag  | under_22_beds         | Under 22 Beds         | html          | html          |
| Yes      | series tag  | intermediate_beds     | Intermediate Beds     | html          | html          |
| Yes      | series tag  | icf_dd_beds           | ICF-DD Beds           | html          | html          |
| Yes      | series tag  | sheltered_care_beds   | Sheltered Care Beds   | html          | html          |
| Yes      | series tag  | community_living_beds | Community Living Beds | html          | html          |
```

## Time Field

```ls
Value = last_survey_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_date
```

## Data Commands

```ls
series e:xdat-b6qj d:2013-04-03T00:00:00.000Z t:region="West Chicago" t:certification_number=14G028 t:intermediate_beds=000 t:license_status="Not Required" t:fax=847/249-0677 t:sheltered_care_beds=000 t:skilled_beds=000 t:under_22_beds=000 t:facility_id=6009781 t:facility_name="Ann M Kiley Dev Center" t:facility_status=Active t:county=Lake t:community_living_beds=000 t:ownership_desc=State t:licensee_id=8000911 t:telephone=847/249-0600 t:icf_dd_beds=480 m:row_number.xdat-b6qj=1

series e:xdat-b6qj d:2012-10-11T00:00:00.000Z t:region=Chicago t:certification_number=14G155 t:intermediate_beds=000 t:license_status=Unrestricted t:fax=773/973-5214 t:sheltered_care_beds=000 t:skilled_beds=000 t:under_22_beds=000 t:facility_id=6006209 t:facility_name="Miniat House" t:facility_status=Active t:county=Cook t:community_living_beds=000 t:ownership_desc="Non-Prof Corporation" t:licensee_id=0028498 t:telephone=773/973-6300 t:icf_dd_beds=012 m:row_number.xdat-b6qj=2

series e:xdat-b6qj d:2013-01-03T00:00:00.000Z t:region=Bellwood t:certification_number=14G096 t:intermediate_beds=000 t:license_status=Unrestricted t:fax=708/352-9728 t:sheltered_care_beds=000 t:skilled_beds=000 t:under_22_beds=000 t:facility_id=6004162 t:facility_name="Helping Hand Ic Facility" t:facility_status=Active t:county=Cook t:community_living_beds=000 t:ownership_desc="Non-Prof Corporation" t:licensee_id=0028324 t:telephone=708/352-3580 t:icf_dd_beds=016 m:row_number.xdat-b6qj=3
```

## Meta Commands

```ls
metric m:row_number.xdat-b6qj p:long l:"Row Number"

entity e:xdat-b6qj l:"IDPH - Intermediate Care Facilities for Individuals with Intellectual Disabilities" t:attribution="Illinois Department of Public Health" t:url=https://data.illinois.gov/api/views/xdat-b6qj

property e:xdat-b6qj t:meta.view v:id=xdat-b6qj v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/ v:averageRating=0 v:name="IDPH - Intermediate Care Facilities for Individuals with Intellectual Disabilities" v:attribution="Illinois Department of Public Health"

property e:xdat-b6qj t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:xdat-b6qj t:meta.view.tableauthor v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```

## Top Records

```ls
| facility_name            | licensee_id | facility_id | certification_number | region       | county   | telephone    | fax          | ownership_desc       | facility_status | license_status | expiration_date     | last_survey_date    | skilled_beds | under_22_beds | intermediate_beds | icf_dd_beds | sheltered_care_beds | community_living_beds | 
| ======================== | =========== | =========== | ==================== | ============ | ======== | ============ | ============ | ==================== | =============== | ============== | =================== | =================== | ============ | ============= | ================= | =========== | =================== | ===================== | 
| Ann M Kiley Dev Center   | 8000911     | 6009781     | 14G028               | West Chicago | Lake     | 847/249-0600 | 847/249-0677 | State                | Active          | Not Required   |                     | 2013-04-03T00:00:00 | 000          | 000           | 000               | 480         | 000                 | 000                   | 
| Miniat House             | 0028498     | 6006209     | 14G155               | Chicago      | Cook     | 773/973-6300 | 773/973-5214 | Non-Prof Corporation | Active          | Unrestricted   | 2013-09-06T00:00:00 | 2012-10-11T00:00:00 | 000          | 000           | 000               | 012         | 000                 | 000                   | 
| Helping Hand Ic Facility | 0028324     | 6004162     | 14G096               | Bellwood     | Cook     | 708/352-3580 | 708/352-9728 | Non-Prof Corporation | Active          | Unrestricted   | 2013-07-30T00:00:00 | 2013-01-03T00:00:00 | 000          | 000           | 000               | 016         | 000                 | 000                   | 
| Glen Brook               | 0037051     | 6012694     | 14G250               | Marion       | Johnson  | 618/658-2005 | 618/833-4993 | For-Prof Corporation | Active          | Unrestricted   | 2013-08-07T00:00:00 | 2012-11-16T00:00:00 | 000          | 000           | 000               | 016         | 000                 | 000                   | 
| Gaylord Tull House       | 0032672     | 6010334     | 14G161               | Champaign    | Coles    | 217/345-3552 | 217/345-7340 | For-Prof Corporation | Active          | Unrestricted   | 2013-09-27T00:00:00 | 2013-06-13T00:00:00 | 000          | 000           | 000               | 016         | 000                 | 000                   | 
| Matteson Court           | 0043281     | 6014393     | 14G353               | Bellwood     | Cook     | 708/720-4931 | 708/720-4934 | Non-Prof Corporation | Active          | Unrestricted   | 2014-06-30T00:00:00 | 2013-05-07T00:00:00 | 000          | 000           | 000               | 016         | 000                 | 000                   | 
| Vintage                  | 0040477     | 6013569     | 14G320               | West Chicago | Will     | 815/725-3409 | 815/723-1177 | Non-Prof Corporation | Active          | Unrestricted   | 2014-05-29T00:00:00 | 2013-05-22T00:00:00 | 000          | 000           | 000               | 004         | 000                 | 000                   | 
| Alden Springs            | 0047191     | 6016224     | 14G379               | West Chicago | Dupage   | 630/523-5783 | 630/523-5787 | For-Prof Corporation | Active          | Unrestricted   | 2014-09-24T00:00:00 | 2013-02-06T00:00:00 | 000          | 000           | 000               | 016         | 000                 | 000                   | 
| Park Lawn Home           | 0035527     | 6012264     | 14G284               | Bellwood     | Cook     | 708/385-1982 | 708/425-3530 | Non-Prof Corporation | Active          | Unrestricted   | 2015-05-01T00:00:00 | 2013-03-29T00:00:00 | 000          | 000           | 000               | 015         | 000                 | 000                   | 
| Adloff Place             | 0038463     | 6013445     | 14G295               | Edwardsville | Sangamon | 217/786-3109 | 217/786-3784 | Non-Prof Corporation | Active          | Unrestricted   | 2014-04-05T00:00:00 | 2013-04-29T00:00:00 | 000          | 000           | 000               | 016         | 000                 | 000                   | 
```