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
| Rows Updated | 2015-11-25T23:02:59Z |

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
series e:m2rg-xjan d:2012-01-01T00:00:00.000Z t:county_of_commitment=ALBANY t:admission_month=JANUARY t:month_code=1 t:latest_admission_type="NEW COURT COMMITMENT" t:most_serious_crime="BURGLARY 3RD" t:gender=FEMALE m:age_at_admission=17

series e:m2rg-xjan d:2012-01-01T00:00:00.000Z t:county_of_commitment=ALBANY t:admission_month=JANUARY t:month_code=1 t:latest_admission_type="NEW COURT COMMITMENT" t:most_serious_crime="CRIM SALE CONTROLLED SUB 3RD" t:gender=FEMALE m:age_at_admission=24

series e:m2rg-xjan d:2012-01-01T00:00:00.000Z t:county_of_commitment=ALBANY t:admission_month=JANUARY t:month_code=1 t:latest_admission_type="NEW COURT COMMITMENT" t:most_serious_crime="CRIM POSS CONTROLLED SUB 4TH" t:gender=FEMALE m:age_at_admission=27
```

## Meta Commands

```ls
metric m:age_at_admission p:integer l:"Age at Admission" d:"Age of offender at admission to NYSDOCCS" t:dataTypeName=number

entity e:m2rg-xjan l:"Prison Admissions: Beginning 2008" t:attribution="NYS Department of Corrections and Community Supervision" t:url=https://data.ny.gov/api/views/m2rg-xjan

property e:m2rg-xjan t:meta.view v:id=m2rg-xjan v:category="Public Safety" v:attributionLink=http://www.doccs.ny.gov v:averageRating=0 v:name="Prison Admissions: Beginning 2008" v:attribution="NYS Department of Corrections and Community Supervision"

property e:m2rg-xjan t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:m2rg-xjan t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:m2rg-xjan t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```