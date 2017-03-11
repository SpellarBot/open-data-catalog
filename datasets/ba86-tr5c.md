# City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/ba86-tr5c/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/city-university-of-new-york-cuny-university-retention-and-graduation-rates-beginning-1990)
* Id = ba86-tr5c
* Name = City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990
* Attribution = City University of New York
* Category = Education
* Tags = [higher education, enrollment]
* Created = 2014-01-17T17:03:53Z
* Publication Date = 2015-12-23T17:44:26Z
* Rows Updated = 2015-12-21T18:40:31Z

## Description

Data set contains one year retention rates and 150 time graduation rates (3yr rates for associate degree seekers and 6yr rates for baccalaureate seekers) for all CUNY colleges from 1990 through present where applicable for first-time, full-time freshmen.

## Columns

```ls
| Name                    | Field Name              | Data Type | Render Type | Schema Type    | Included | 
| ======================= | ======================= | ========= | =========== | ============== | ======== | 
| updated_at              | :updated_at             | meta_data | meta_data   | time           | Yes      | 
| College                 | college                 | text      | text        | series tag     | Yes      | 
| Fall Term               | fall_term               | text      | text        | series tag     | Yes      | 
| Record Type Code        | record_type_code        | text      | number      | series tag     | Yes      | 
| Record Type Description | record_type_description | text      | text        | series tag     | Yes      | 
| Head Count              | head_count              | number    | number      | numeric metric | Yes      | 
| Percentage              | percentage              | percent   | percent     | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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
series e:ba86-tr5c d:2014-01-17T09:03:56.000Z t:record_type_code=1 t:record_type_description="1 Year Retention" t:college="CUNY Baruch College" t:fall_term="Fall 1990" m:percentage=81.8 m:head_count=1278

series e:ba86-tr5c d:2014-01-17T09:03:56.000Z t:record_type_code=2 t:record_type_description="150 Time Graduation" t:college="CUNY Baruch College" t:fall_term="Fall 1990" m:percentage=39.3 m:head_count=1278

series e:ba86-tr5c d:2014-01-17T09:03:56.000Z t:record_type_code=1 t:record_type_description="1 Year Retention" t:college="CUNY Baruch College" t:fall_term="Fall 1991" m:percentage=84.4 m:head_count=1170
```

## Meta Commands

```ls
metric m:head_count p:integer l:"Head Count" t:dataTypeName=number

entity e:ba86-tr5c l:"City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990" t:attribution="City University of New York" t:url=https://data.ny.gov/api/views/ba86-tr5c

property e:ba86-tr5c t:meta.view d:2017-03-03T13:51:15.512Z v:id=ba86-tr5c v:category=Education v:averageRating=0 v:name="City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990" v:attribution="City University of New York"

property e:ba86-tr5c t:meta.view.owner d:2017-03-03T13:51:15.512Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ba86-tr5c t:meta.view.tableauthor d:2017-03-03T13:51:15.512Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ba86-tr5c t:meta.view.metadata.custom_fields.common_core d:2017-03-03T13:51:15.512Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```