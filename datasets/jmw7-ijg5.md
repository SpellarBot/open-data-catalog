# Family and Support Services Delegate Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/family-and-support-services-delegate-agencies) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/jmw7-ijg5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/jmw7-ijg5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/jmw7-ijg5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | jmw7-ijg5 |
| Name | Family and Support Services Delegate Agencies |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | facilities, children, domestic violence, housing, homelessness, youth, seniors, workforce, human services, family and support services |
| Created | 2015-10-06T16:14:40Z |
| Publication Date | 2015-10-07T21:49:36Z |
| Rows Updated | 2015-10-07T21:47:48Z |

## Description

A list of the delegate agencies with which the Department of Family and Support Services has contracted to provide services to residents of Chicago.  For more information on the department and its services, please see http://www.cityofchicago.org/city/en/depts/fss.html.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | agency                | Agency                | text      | text        |
| Yes      | series tag  | program_model         | Program Model         | text      | text        |
| Yes      | series tag  | division              | Division              | text      | text        |
| Yes      | series tag  | site_name             | Site Name             | text      | text        |
| No       |             | address               | Address               | text      | text        |
| Yes      | series tag  | street_number         | Street Number         | text      | number      |
| Yes      | series tag  | street_direction      | Street Direction      | text      | text        |
| Yes      | series tag  | street_name           | Street Name           | text      | text        |
| Yes      | series tag  | street_type           | Street Type           | text      | text        |
| Yes      | series tag  | address_line_2        | Address Line 2        | text      | text        |
| Yes      | series tag  | city                  | City                  | text      | text        |
| Yes      | series tag  | state                 | State                 | text      | text        |
| Yes      | series tag  | zip                   | ZIP                   | text      | text        |
| Yes      | series tag  | phone_number          | Phone Number          | phone     | phone       |
| Yes      | series tag  | phone_extension       | Phone Extension       | text      | text        |
| Yes      | series tag  | ward                  | Ward                  | text      | number      |
| Yes      | series tag  | community_area        | Community Area        | text      | text        |
| Yes      | series tag  | community_area_number | Community Area Number | text      | number      |
| No       |             | x_coordinate          | X Coordinate          | number    | number      |
| No       |             | y_coordinate          | Y Coordinate          | number    | number      |
| No       |             | latitude              | Latitude              | number    | number      |
| No       |             | longitude             | Longitude             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:jmw7-ijg5 l:"Family and Support Services Delegate Agencies" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/jmw7-ijg5

property e:jmw7-ijg5 t:meta.view v:id=jmw7-ijg5 v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Family and Support Services Delegate Agencies" v:attribution="City of Chicago"

property e:jmw7-ijg5 t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"

property e:jmw7-ijg5 t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```