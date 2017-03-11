# WA State Accessibility Coordinators

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/j2u5-4qpk/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/wa-state-accessibility-coordinators)
* Id = j2u5-4qpk
* Name = WA State Accessibility Coordinators
* Attribution = WA State Accessibility Champion
* Tags = [policy 188, accessibility, ada, section 508]
* Created = 2016-11-22T21:43:29Z
* Publication Date = 2017-01-20T19:55:21Z
* Rows Updated = 2017-01-20T19:55:08Z

## Description

WA State Office of the Chief Information Officer Accessibility Policy #188 requires agencies and other groups required to follow OCIO Policy to identify an Accessibility Coordinator and publish information about their Accessibility policy and process.

## Columns

```ls
| Name                             | Field Name                       | Data Type     | Render Type   | Schema Type    | Included | 
| ================================ | ================================ | ============= | ============= | ============== | ======== | 
| AGENCY NUMBER                    | agency_number                    | number        | number        | numeric metric | Yes      | 
| AGENCY TITLE                     | agency_title                     | text          | text          | series tag     | Yes      | 
| Abbreviation                     | abbreviation                     | text          | text          | series tag     | Yes      | 
| Agency Accessibility Coordinator | agency_accessibility_coordinator | text          | text          | series tag     | Yes      | 
| Agency Coordinator Email         | agency_coordinator_email         | email         | email         | series tag     | Yes      | 
| Last change date                 | last_change_date                 | calendar_date | calendar_date | time           | Yes      | 
| URL of Accessibility Info        | url_of_accessibility_info        | url           | url           | series tag     | Yes      | 
```

## Time Field

```ls
Value = last_change_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:j2u5-4qpk d:2017-03-03T14:25:46.140Z t:agency_title="State Revenue for Distribution (SRD)" t:abbreviation=SRD m:agency_number=10

series e:j2u5-4qpk d:2017-03-03T14:25:46.140Z t:agency_title="Federal Revenue for Distribution (FRD)" t:abbreviation=FRD m:agency_number=50

series e:j2u5-4qpk d:2017-03-03T14:25:46.140Z t:agency_title="Bond Retirement and Interest (BRI)" t:abbreviation=BRI m:agency_number=100
```

## Meta Commands

```ls
metric m:agency_number p:integer l:"AGENCY NUMBER" t:dataTypeName=number

entity e:j2u5-4qpk l:"WA State Accessibility Coordinators" t:attribution="WA State Accessibility Champion" t:url=https://data.wa.gov/api/views/j2u5-4qpk

property e:j2u5-4qpk t:meta.view d:2017-03-03T14:25:46.140Z v:id=j2u5-4qpk v:averageRating=0 v:name="WA State Accessibility Coordinators" v:attribution="WA State Accessibility Champion"

property e:j2u5-4qpk t:meta.view.owner d:2017-03-03T14:25:46.140Z v:id=2iur-ynm8 v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:screenName=ryan.leisinger v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:roleName=administrator v:displayName=ryan.leisinger

property e:j2u5-4qpk t:meta.view.tableauthor d:2017-03-03T14:25:46.140Z v:id=2iur-ynm8 v:profileImageUrlMedium=/api/users/2iur-ynm8/profile_images/THUMB v:profileImageUrlLarge=/api/users/2iur-ynm8/profile_images/LARGE v:screenName=ryan.leisinger v:profileImageUrlSmall=/api/users/2iur-ynm8/profile_images/TINY v:roleName=administrator v:displayName=ryan.leisinger
```