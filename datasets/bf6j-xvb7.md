# BOEE Practitioners, Licenses, & Endorsements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boee-practitioners-licenses-endorsements) |
| Metadata | [Link](https://data.iowa.gov/api/views/bf6j-xvb7) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/bf6j-xvb7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/bf6j-xvb7/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | bf6j-xvb7 |
| Name | BOEE Practitioners, Licenses, & Endorsements |
| Attribution | Iowa BOEE |
| Category | Education |
| Tags | teacher, principal, superintendent, coach, educator, license, endorsement |
| Created | 2016-10-04T19:43:23Z |
| Publication Date | 2017-04-04T13:02:41Z |

## Description

A list of Teachers, Administrators, Coaches, & Other Education Certification Holders combined with license and endorsement information.

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | =========== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag  | folder_number               | Folder Number               | text          | number        |
| Yes      | series tag  | first_name                  | First Name                  | text          | text          |
| Yes      | series tag  | last_name                   | Last Name                   | text          | text          |
| Yes      | series tag  | practitioner_status_type_id | Practitioner Status Type ID | text          | number        |
| Yes      | series tag  | practitioner_status         | Practitioner Status         | text          | text          |
| Yes      | series tag  | license_type_id             | License Type ID             | text          | number        |
| Yes      | series tag  | license_type                | License Type                | text          | text          |
| Yes      | time        | license_original_issue_date | License Original Issue Date | calendar_date | calendar_date |
| No       |             | license_issue_date          | License Issue Date          | calendar_date | calendar_date |
| No       |             | license_expiration_date     | License Expiration Date     | calendar_date | calendar_date |
| Yes      | series tag  | endorsement_type_id         | Endorsement Type ID         | text          | number        |
| Yes      | series tag  | endorsement_type            | Endorsement Type            | text          | text          |
| No       |             | endorsement_issue_date      | Endorsement Issue Date      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = license_original_issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = license_issue_date,license_expiration_date,endorsement_issue_date
```

## Data Commands

```ls
series e:bf6j-xvb7 d:1957-07-01T00:00:00.000Z t:practitioner_status_type_id=1 t:license_type_id=1 t:first_name=DOUGLAS t:license_type="Permanent Professional License" t:endorsement_type="Superintendent (K-12)" t:last_name=DUNSMOOR t:practitioner_status=Active t:endorsement_type_id=60 t:folder_number=9 m:row_number.bf6j-xvb7=1

series e:bf6j-xvb7 d:1957-07-01T00:00:00.000Z t:practitioner_status_type_id=1 t:license_type_id=1 t:first_name=DOUGLAS t:license_type="Permanent Professional License" t:endorsement_type="5-12 Principal" t:last_name=DUNSMOOR t:practitioner_status=Active t:endorsement_type_id=170 t:folder_number=9 m:row_number.bf6j-xvb7=2

series e:bf6j-xvb7 d:1956-07-02T00:00:00.000Z t:practitioner_status_type_id=1 t:license_type_id=5 t:first_name=DOUGLAS t:license_type="Temporary License" t:endorsement_type="5-12 Principal" t:last_name=DUNSMOOR t:practitioner_status=Active t:endorsement_type_id=170 t:folder_number=9 m:row_number.bf6j-xvb7=3
```

## Meta Commands

```ls
metric m:row_number.bf6j-xvb7 p:long l:"Row Number"

entity e:bf6j-xvb7 l:"BOEE Practitioners, Licenses, & Endorsements" t:attribution="Iowa BOEE" t:url=https://data.iowa.gov/api/views/bf6j-xvb7

property e:bf6j-xvb7 t:meta.view v:id=bf6j-xvb7 v:category=Education v:attributionLink=http://www.boee.iowa.gov/ v:averageRating=0 v:name="BOEE Practitioners, Licenses, & Endorsements" v:attribution="Iowa BOEE"

property e:bf6j-xvb7 t:meta.view.owner v:id=djpv-fh9y v:profileImageUrlMedium=/api/users/djpv-fh9y/profile_images/THUMB v:profileImageUrlLarge=/api/users/djpv-fh9y/profile_images/LARGE v:screenName="Iowa Board of Educational Examiners" v:profileImageUrlSmall=/api/users/djpv-fh9y/profile_images/TINY v:displayName="Iowa Board of Educational Examiners"

property e:bf6j-xvb7 t:meta.view.tableauthor v:id=djpv-fh9y v:profileImageUrlMedium=/api/users/djpv-fh9y/profile_images/THUMB v:profileImageUrlLarge=/api/users/djpv-fh9y/profile_images/LARGE v:screenName="Iowa Board of Educational Examiners" v:profileImageUrlSmall=/api/users/djpv-fh9y/profile_images/TINY v:roleName=editor v:displayName="Iowa Board of Educational Examiners"
```

## Top Records

```ls
| folder_number | first_name | last_name   | practitioner_status_type_id | practitioner_status | license_type_id | license_type                   | license_original_issue_date | license_issue_date  | license_expiration_date | endorsement_type_id | endorsement_type                 | endorsement_issue_date | 
| ============= | ========== | =========== | =========================== | =================== | =============== | ============================== | =========================== | =================== | ======================= | =================== | ================================ | ====================== | 
| 9             | DOUGLAS    | DUNSMOOR    | 1                           | Active              | 1               | Permanent Professional License | 1957-07-01T00:00:00         | 1957-07-01T00:00:00 |                         | 60                  | Superintendent (K-12)            | 1957-07-01T00:00:00    | 
| 9             | DOUGLAS    | DUNSMOOR    | 1                           | Active              | 1               | Permanent Professional License | 1957-07-01T00:00:00         | 1957-07-01T00:00:00 |                         | 170                 | 5-12 Principal                   | 1957-07-01T00:00:00    | 
| 9             | DOUGLAS    | DUNSMOOR    | 1                           | Active              | 5               | Temporary License              | 1956-07-02T00:00:00         | 1956-07-02T00:00:00 | 1957-08-30T00:00:00     | 170                 | 5-12 Principal                   | 1956-07-02T00:00:00    | 
| 10            | JOHN       | PENCE       | 1                           | Active              | 15              | Standard License               | 1952-02-27T00:00:00         | 1952-02-27T00:00:00 | 1962-08-30T00:00:00     | 81                  | Standard Secondary               | 1952-02-27T00:00:00    | 
| 12            | IVA        | ITZEN       | 1                           | Active              | 3               | Pre-Professional License       | 1954-07-01T00:00:00         | 1954-07-01T00:00:00 | 1960-08-30T00:00:00     | 102                 | K-6 Teacher Elementary Classroom | 1954-07-01T00:00:00    | 
| 17            | TRESSA     | BAUMANN     | 1                           | Active              | 3               | Pre-Professional License       | 1964-07-01T00:00:00         | 1964-07-01T00:00:00 | 1970-08-30T00:00:00     | 102                 | K-6 Teacher Elementary Classroom | 1964-07-01T00:00:00    | 
| 18            | VIOLA      | BINNS       | 1                           | Active              | 3               | Pre-Professional License       | 1968-07-01T00:00:00         | 1968-07-01T00:00:00 | 1974-08-30T00:00:00     | 102                 | K-6 Teacher Elementary Classroom | 1968-07-01T00:00:00    | 
| 19            | EDNA       | BOERSMA     | 1                           | Active              | 3               | Pre-Professional License       | 1959-08-31T00:00:00         | 1959-08-31T00:00:00 | 1965-08-30T00:00:00     | 102                 | K-6 Teacher Elementary Classroom | 1959-08-31T00:00:00    | 
| 20            | LEONE      | BROOKHOUSER | 1                           | Active              | 3               | Pre-Professional License       | 1958-07-01T00:00:00         | 1958-07-01T00:00:00 | 1964-08-30T00:00:00     | 102                 | K-6 Teacher Elementary Classroom | 1958-07-01T00:00:00    | 
| 20            | LEONE      | BROOKHOUSER | 1                           | Active              | 5               | Temporary License              | 1966-07-01T00:00:00         | 1966-07-01T00:00:00 | 1967-08-30T00:00:00     | 102                 | K-6 Teacher Elementary Classroom | 1966-07-01T00:00:00    | 
```