# Advantage After School Program

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/ae9a-zs4q/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/advantage-after-school-program)
* [Metadata URL](https://data.ny.gov/api/views/ae9a-zs4q)
* Id = ae9a-zs4q
* Name = Advantage After School Program
* Attribution = NYS Office of Children and Family Services
* [Attribution Link](http://www.ocfs.state.ny.us/main/bcm/tanf/aas/contractlistAAS.pdf)
* Category = Human Services
* Tags = [after school, advantage after school, afterschool]
* Created = 2013-04-16T15:29:15Z
* Publication Date = 2016-02-18T14:55:28Z
* Rows Updated = 2016-02-18T14:43:56Z

## Description

Included in the data set are data elements that will help the public learn about the agencies currently contracting with New York State to provide Advantage After School Program services. The data elements are as follows:Contract Start Date, Contract End Date, Round Number, Contract Number, Contract Amount, School Levels Served (Elementary, Middle School, High School), Average Daily Attendance (MADA), Agency, Site Name, Street Address, Primary City, Zip Code.Also, the asterisks (*) indicate that the contract agency operates the program at two sites.

## Columns

```ls
| Name                | Field Name          | Data Type     | Render Type   | Schema Type    | Included | 
| =================== | =================== | ============= | ============= | ============== | ======== | 
| Contract Start Date | contract_start_date | calendar_date | calendar_date | time           | Yes      | 
| Contract End Date   | contract_end_date   | calendar_date | calendar_date |                | No       | 
| Round Number        | round_number        | number        | text          | numeric metric | Yes      | 
| Contract Number     | contract            | text          | text          | series tag     | Yes      | 
| Contract Amount     | contract_amount     | money         | money         | numeric metric | Yes      | 
| Elementary          | elementary          | number        | text          | numeric metric | Yes      | 
| Middle School       | middle_school       | number        | text          | numeric metric | Yes      | 
| High School         | high_school         | number        | text          | numeric metric | Yes      | 
| MADA for Site       | mada_for_site       | number        | number        | numeric metric | Yes      | 
| Agency              | agency              | text          | text          | series tag     | Yes      | 
| Site Name           | site_name           | text          | text          | series tag     | Yes      | 
| Street Address      | street_address      | text          | text          |                | No       | 
| Primary City        | primary_city        | text          | text          | series tag     | Yes      | 
| ZIP Code            | zip_code            | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = contract_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = contract_end_date,street_address
Annotation Fields = 
```

## Data Commands

```ls
series e:ae9a-zs4q d:2014-10-01T00:00:00.000Z t:contract=C027297 t:agency="Wayne County Action Program" t:site_name="North Rose/Wolcott Elementary" t:primary_city="North Rose" t:elementary=x m:mada_for_site=100 m:zip_code=14516 m:contract_amount=126041 m:round_number=9

series e:ae9a-zs4q d:2014-10-01T00:00:00.000Z t:contract=C027331 t:high_school=x t:agency="People and Possibilities" t:site_name="Niagara Falls High School" t:primary_city="Niagara Falls" m:mada_for_site=80 m:zip_code=14305 m:round_number=9

series e:ae9a-zs4q d:2014-10-01T00:00:00.000Z t:contract=C027330 t:agency="Catholic Charities of the Diocese of Albany" t:site_name="Sunnyside Center" t:primary_city=Troy t:elementary=x m:mada_for_site=80 m:zip_code=12180 m:contract_amount=110000 m:round_number=9
```

## Meta Commands

```ls
metric m:round_number p:integer l:"Round Number" d:"Identifies which procurement the contracts resulted from" t:dataTypeName=number

metric m:mada_for_site p:integer l:"MADA for Site" d:"Identifies the Maximum average daily attendance program is contracted to serve" t:dataTypeName=number

metric m:zip_code l:"ZIP Code" d:"Zip Code (5 digits) or Zip Plus 4 (9 digits)" t:dataTypeName=number

entity e:ae9a-zs4q l:"Advantage After School Program" t:attribution="NYS Office of Children and Family Services" t:url=https://data.ny.gov/api/views/ae9a-zs4q

property e:ae9a-zs4q t:meta.view d:2017-03-07T23:49:44.461Z v:id=ae9a-zs4q v:category="Human Services" v:attributionLink=http://www.ocfs.state.ny.us/main/bcm/tanf/aas/contractlistAAS.pdf v:averageRating=0 v:name="Advantage After School Program" v:attribution="NYS Office of Children and Family Services"

property e:ae9a-zs4q t:meta.view.owner d:2017-03-07T23:49:44.461Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ae9a-zs4q t:meta.view.tableauthor d:2017-03-07T23:49:44.461Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ae9a-zs4q t:meta.view.metadata.custom_fields.common_core d:2017-03-07T23:49:44.461Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```