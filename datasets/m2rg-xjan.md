# Prison Admissions: Beginning 2008

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/m2rg-xjan/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/prison-admissions-beginning-2008)
* [Metadata URL](https://data.ny.gov/api/views/m2rg-xjan)
* Id = m2rg-xjan
* Name = Prison Admissions: Beginning 2008
* Attribution = NYS Department of Corrections and Community Supervision
* [Attribution Link](http://www.doccs.ny.gov)
* Category = Public Safety
* Tags = [admission type, county, prison admissions, gender, age, crime]
* Created = 2014-01-09T15:51:48Z
* Publication Date = 2015-11-30T16:20:04Z
* Rows Updated = 2015-11-25T23:02:59Z

## Description

Represents inmate admissions to the NYS Department of Corrections and Community Supervision for a new offense or for a parole violation by month of admission.  Includes data about admission type, county, gender, age, and crime.

## Columns

```ls
| Name                        | Field Name                  | Data Type | Render Type | Schema Type    | Included | 
| =========================== | =========================== | ========= | =========== | ============== | ======== | 
| Admission Year              | admission_year              | number    | number      | time           | Yes      | 
| Admission Month             | admission_month             | text      | text        | series tag     | Yes      | 
| Month Code                  | month_code                  | text      | number      | series tag     | Yes      | 
| Admission Type              | latest_admission_type       | text      | text        | series tag     | Yes      | 
| County of Commitment        | county_of_commitment        | text      | text        | series tag     | Yes      | 
| Last Known Residence County | last_known_residence_county | text      | text        | series tag     | Yes      | 
| Gender                      | gender                      | text      | text        | series tag     | Yes      | 
| Age at Admission            | age_at_admission            | number    | number      | numeric metric | Yes      | 
| Most Serious Crime          | most_serious_crime          | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = admission_year
Format & Zone = yyyy
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
series e:m2rg-xjan d:2012-01-01T00:00:00.000Z t:county_of_commitment=ALBANY t:admission_month=JANUARY t:month_code=1 t:latest_admission_type="NEW COURT COMMITMENT" t:most_serious_crime="BURGLARY 3RD" t:gender=FEMALE m:age_at_admission=17

series e:m2rg-xjan d:2012-01-01T00:00:00.000Z t:county_of_commitment=ALBANY t:admission_month=JANUARY t:month_code=1 t:latest_admission_type="NEW COURT COMMITMENT" t:most_serious_crime="CRIM SALE CONTROLLED SUB 3RD" t:gender=FEMALE m:age_at_admission=24

series e:m2rg-xjan d:2012-01-01T00:00:00.000Z t:county_of_commitment=ALBANY t:admission_month=JANUARY t:month_code=1 t:latest_admission_type="NEW COURT COMMITMENT" t:most_serious_crime="CRIM POSS CONTROLLED SUB 4TH" t:gender=FEMALE m:age_at_admission=27
```

## Meta Commands

```ls
metric m:age_at_admission p:integer l:"Age at Admission" d:"Age of offender at admission to NYSDOCCS" t:dataTypeName=number

entity e:m2rg-xjan l:"Prison Admissions: Beginning 2008" t:attribution="NYS Department of Corrections and Community Supervision" t:url=https://data.ny.gov/api/views/m2rg-xjan

property e:m2rg-xjan t:meta.view d:2017-03-08T00:50:44.401Z v:id=m2rg-xjan v:category="Public Safety" v:attributionLink=http://www.doccs.ny.gov v:averageRating=0 v:name="Prison Admissions: Beginning 2008" v:attribution="NYS Department of Corrections and Community Supervision"

property e:m2rg-xjan t:meta.view.owner d:2017-03-08T00:50:44.401Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:m2rg-xjan t:meta.view.tableauthor d:2017-03-08T00:50:44.401Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:m2rg-xjan t:meta.view.metadata.custom_fields.common_core d:2017-03-08T00:50:44.401Z v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```