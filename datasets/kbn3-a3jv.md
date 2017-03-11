# State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/kbn3-a3jv/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/state-university-construction-fund-sucf-short-listed-firms-beginning-2000)
* [Metadata URL](https://data.ny.gov/api/views/kbn3-a3jv)
* Id = kbn3-a3jv
* Name = State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000
* Attribution = State University Construction Fund
* [Attribution Link](http://sucf.suny.edu)
* Category = Education
* Tags = [state university construction fund, sucf, construction, suny, education, capital, projects]
* Created = 2014-01-24T19:37:22Z
* Publication Date = 2017-03-01T11:12:30Z
* Rows Updated = 2017-03-01T11:12:20Z

## Description

The SUCF Projects dataset contains relevant data for all design contracts for projects managed by the State University Construction Fund that are advertised for procurement. This dataset identifies all firms that responded to requests for qualifications that went on to be interviewed for design work on a project.

## Columns

```ls
| Name                    | Field Name              | Data Type     | Render Type   | Schema Type | Included | 
| ======================= | ======================= | ============= | ============= | =========== | ======== | 
| Project                 | project                 | text          | text          | series tag  | Yes      | 
| Campus Name             | campus_name             | text          | text          | series tag  | Yes      | 
| Project Title           | project_title           | text          | text          | series tag  | Yes      | 
| Contract Advertise Date | contract_advertise_date | calendar_date | calendar_date | time        | Yes      | 
| Firm Name               | firm_name               | text          | text          | series tag  | Yes      | 
| Address Line 1          | address_line_1          | text          | text          | series tag  | Yes      | 
| Address Line 2          | address_line_2          | text          | text          | series tag  | Yes      | 
| City                    | city                    | text          | text          | series tag  | Yes      | 
| State                   | state                   | text          | text          | series tag  | Yes      | 
| Zip Code                | zip_code                | text          | text          | series tag  | Yes      | 
| Phone Number            | phone_number            | text          | text          | series tag  | Yes      | 
```

## Time Field

```ls
Value = contract_advertise_date
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





```

## Meta Commands

```ls
entity e:kbn3-a3jv l:"State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000" t:attribution="State University Construction Fund" t:url=https://data.ny.gov/api/views/kbn3-a3jv

property e:kbn3-a3jv t:meta.view d:2017-03-08T02:02:08.498Z v:id=kbn3-a3jv v:category=Education v:attributionLink=http://sucf.suny.edu v:averageRating=0 v:name="State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000" v:attribution="State University Construction Fund"

property e:kbn3-a3jv t:meta.view.owner d:2017-03-08T02:02:08.498Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kbn3-a3jv t:meta.view.tableauthor d:2017-03-08T02:02:08.498Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kbn3-a3jv t:meta.view.metadata.custom_fields.common_core d:2017-03-08T02:02:08.498Z v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```