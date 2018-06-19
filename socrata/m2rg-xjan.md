# Prison Admissions: Beginning 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/prison-admissions-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/m2rg-xjan) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/m2rg-xjan/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/m2rg-xjan/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | m2rg-xjan |
| Name | Prison Admissions: Beginning 2008 |
| Attribution | NYS Department of Corrections and Community Supervision |
| Category | Public Safety |
| Tags | admission type, county, prison admissions, gender, age, crime |
| Created | 2014-01-09T15:51:48Z |
| Publication Date | 2015-11-30T16:20:04Z |

## Description

Represents inmate admissions to the NYS Department of Corrections and Community Supervision for a new offense or for a parole violation by month of admission.  Includes data about admission type, county, gender, age, and crime.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | admission_year              | Admission Year              | number    | number      |
| Yes      | series tag     | admission_month             | Admission Month             | text      | text        |
| Yes      | series tag     | month_code                  | Month Code                  | text      | number      |
| Yes      | series tag     | latest_admission_type       | Admission Type              | text      | text        |
| Yes      | series tag     | county_of_commitment        | County of Commitment        | text      | text        |
| Yes      | series tag     | last_known_residence_county | Last Known Residence County | text      | text        |
| Yes      | series tag     | gender                      | Gender                      | text      | text        |
| Yes      | numeric metric | age_at_admission            | Age at Admission            | number    | number      |
| Yes      | series tag     | most_serious_crime          | Most Serious Crime          | text      | text        |
```

## Time Field

```ls
Value = admission_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m2rg-xjan d:2012-01-01T00:00:00.000Z t:latest_admission_type="NEW COURT COMMITMENT" t:admission_month=JANUARY t:gender=FEMALE t:county_of_commitment=ALBANY t:month_code=1 t:most_serious_crime="BURGLARY 3RD" m:age_at_admission=17

series e:m2rg-xjan d:2012-01-01T00:00:00.000Z t:latest_admission_type="NEW COURT COMMITMENT" t:admission_month=JANUARY t:gender=FEMALE t:county_of_commitment=ALBANY t:month_code=1 t:most_serious_crime="CRIM SALE CONTROLLED SUB 3RD" m:age_at_admission=24

series e:m2rg-xjan d:2012-01-01T00:00:00.000Z t:latest_admission_type="NEW COURT COMMITMENT" t:admission_month=JANUARY t:gender=FEMALE t:county_of_commitment=ALBANY t:month_code=1 t:most_serious_crime="CRIM POSS CONTROLLED SUB 4TH" m:age_at_admission=27
```

## Meta Commands

```ls
metric m:age_at_admission p:integer l:"Age at Admission" d:"Age of offender at admission to NYSDOCCS" t:dataTypeName=number

entity e:m2rg-xjan l:"Prison Admissions: Beginning 2008" t:attribution="NYS Department of Corrections and Community Supervision" t:url=https://data.ny.gov/api/views/m2rg-xjan

property e:m2rg-xjan t:meta.view d:2017-09-25T07:25:08.675Z v:averageRating=0 v:name="Prison Admissions: Beginning 2008" v:attribution="NYS Department of Corrections and Community Supervision" v:attributionLink=http://www.doccs.ny.gov v:id=m2rg-xjan v:category="Public Safety"

property e:m2rg-xjan t:meta.view.owner d:2017-09-25T07:25:08.675Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:m2rg-xjan t:meta.view.tableauthor d:2017-09-25T07:25:08.675Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:m2rg-xjan t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:25:08.675Z v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY" v:Publisher="State of New York"
```

## Top Records

```ls
| admission_year | admission_month | month_code | latest_admission_type | county_of_commitment | last_known_residence_county | gender | age_at_admission | most_serious_crime           | 
| ============== | =============== | ========== | ===================== | ==================== | =========================== | ====== | ================ | ============================ | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | FEMALE | 17               | BURGLARY 3RD                 | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | FEMALE | 24               | CRIM SALE CONTROLLED SUB 3RD | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | FEMALE | 27               | CRIM POSS CONTROLLED SUB 4TH | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | FEMALE | 41               | CRIM SALE CONTROLLED SUB 3RD | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | FEMALE | 50               | POS FORGE INS 2ND            | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | MALE   | 19               | ROBBERY 2ND                  | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | MALE   | 19               | ROBBERY 2ND                  | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | MALE   | 19               | ROBBERY 2ND                  | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | MALE   | 20               | C POS WEAPON 2ND             | 
| 2012           | JANUARY         | 1          | NEW COURT COMMITMENT  | ALBANY               |                             | MALE   | 21               | CRIM POSS CONTROLLED SUB 3RD | 
```