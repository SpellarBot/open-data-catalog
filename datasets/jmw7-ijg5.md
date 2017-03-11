# Family and Support Services Delegate Agencies

## Dataset

* [Dataset URL](https://data.cityofchicago.org/api/views/jmw7-ijg5/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/family-and-support-services-delegate-agencies)
* Id = jmw7-ijg5
* Name = Family and Support Services Delegate Agencies
* Attribution = City of Chicago
* Attribution Link = http://www.cityofchicago.org
* Category = Health & Human Services
* Tags = [facilities, children, domestic violence, housing, homelessness, youth, seniors, workforce, human services, family and support services]
* Created = 2015-10-06T16:14:40Z
* Publication Date = 2015-10-07T21:49:36Z
* Rows Updated = 2015-10-07T21:47:48Z

## Description

A list of the delegate agencies with which the Department of Family and Support Services has contracted to provide services to residents of Chicago.  For more information on the department and its services, please see http://www.cityofchicago.org/city/en/depts/fss.html.

## Columns

```ls
| Name                  | Field Name            | Data Type | Render Type | Schema Type    | Included | 
| ===================== | ===================== | ========= | =========== | ============== | ======== | 
| updated_at            | :updated_at           | meta_data | meta_data   | time           | Yes      | 
| Agency                | agency                | text      | text        | series tag     | Yes      | 
| Program Model         | program_model         | text      | text        | series tag     | Yes      | 
| Division              | division              | text      | text        | series tag     | Yes      | 
| Site Name             | site_name             | text      | text        | series tag     | Yes      | 
| Address               | address               | text      | text        |                | No       | 
| Street Number         | street_number         | number    | number      | numeric metric | Yes      | 
| Street Direction      | street_direction      | number    | text        | numeric metric | Yes      | 
| Street Name           | street_name           | text      | text        | series tag     | Yes      | 
| Street Type           | street_type           | text      | text        | series tag     | Yes      | 
| Address Line 2        | address_line_2        | text      | text        | series tag     | Yes      | 
| City                  | city                  | text      | text        | series tag     | Yes      | 
| State                 | state                 | text      | text        | series tag     | Yes      | 
| ZIP                   | zip                   | number    | text        | numeric metric | Yes      | 
| Phone Number          | phone_number          | phone     | phone       | series tag     | Yes      | 
| Phone Extension       | phone_extension       | text      | text        | series tag     | Yes      | 
| Ward                  | ward                  | number    | number      | numeric metric | Yes      | 
| Community Area        | community_area        | text      | text        | series tag     | Yes      | 
| Community Area Number | community_area_number | number    | number      | numeric metric | Yes      | 
| X Coordinate          | x_coordinate          | number    | number      |                | No       | 
| Y Coordinate          | y_coordinate          | number    | number      |                | No       | 
| Latitude              | latitude              | number    | number      |                | No       | 
| Longitude             | longitude             | number    | number      |                | No       | 
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
Excluded Fields = address,y_coordinate,x_coordinate,longitude,latitude
Annotation Fields = 
```

## Data Commands

```ls
series e:jmw7-ijg5 d:2015-10-07T14:44:20.000Z t:program_model="Head Start Support Services" t:division="Children Services" t:phone_number=7733965556 t:street_name=91ST t:state=IL t:street_direction=W t:agency="A.M. Bus Company" t:community_area=ROSELAND t:site_name="A.M. Bus Company" t:street_type=ST t:city=Chicago m:zip=60620 m:ward=21 m:street_number=100 m:community_area_number=49

series e:jmw7-ijg5 d:2015-10-07T14:44:20.000Z t:program_model="Child Care Only" t:division="Children Services" t:phone_number=7732219711 t:street_name=EXCHANGE t:state=IL t:street_direction=S t:agency="Ada S. McKinley Community Services, Inc." t:community_area="SOUTH SHORE" t:site_name="McKinley-Ersula Howard" t:street_type=AVE t:city=Chicago m:zip=60649 m:ward=7 m:street_number=7222 m:community_area_number=43

series e:jmw7-ijg5 d:2015-10-07T14:44:20.000Z t:program_model="Child Care Only" t:division="Children Services" t:phone_number=7733738200 t:street_name=WABASH t:state=IL t:street_direction=S t:agency="Ada S. McKinley Community Services, Inc." t:community_area="GRAND BOULEVARD" t:site_name="McKinley-Maggie Drummond" t:street_type=AVE t:city=Chicago m:zip=60653 m:ward=3 m:street_number=4301 m:community_area_number=38
```

## Meta Commands

```ls
metric m:street_number p:integer l:"Street Number" t:dataTypeName=number

metric m:zip p:integer l:ZIP t:dataTypeName=number

metric m:ward p:integer l:Ward t:dataTypeName=number

metric m:community_area_number p:integer l:"Community Area Number" t:dataTypeName=number

entity e:jmw7-ijg5 l:"Family and Support Services Delegate Agencies" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/jmw7-ijg5

property e:jmw7-ijg5 t:meta.view d:2017-03-03T13:54:07.148Z v:id=jmw7-ijg5 v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Family and Support Services Delegate Agencies" v:attribution="City of Chicago"

property e:jmw7-ijg5 t:meta.view.owner d:2017-03-03T13:54:07.148Z v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"

property e:jmw7-ijg5 t:meta.view.tableauthor d:2017-03-03T13:54:07.148Z v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```