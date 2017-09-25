# State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-construction-fund-sucf-short-listed-firms-beginning-2000) |
| Metadata | [Link](https://data.ny.gov/api/views/kbn3-a3jv) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/kbn3-a3jv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/kbn3-a3jv/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | kbn3-a3jv |
| Name | State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000 |
| Attribution | State University Construction Fund |
| Category | Education |
| Tags | state university construction fund, sucf, construction, suny, education, capital, projects |
| Created | 2014-01-24T19:37:22Z |
| Publication Date | 2017-09-01T10:19:17Z |

## Description

The SUCF Projects dataset contains relevant data for all design contracts for projects managed by the State University Construction Fund that are advertised for procurement. This dataset identifies all firms that responded to requests for qualifications that went on to be interviewed for design work on a project.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | series tag  | project                 | Project                 | text          | text          |
| Yes      | series tag  | campus_name             | Campus Name             | text          | text          |
| Yes      | series tag  | project_title           | Project Title           | text          | text          |
| Yes      | time        | contract_advertise_date | Contract Advertise Date | calendar_date | calendar_date |
| Yes      | series tag  | firm_name               | Firm Name               | text          | text          |
| No       |             | address_line_1          | Address Line 1          | text          | text          |
| No       |             | address_line_2          | Address Line 2          | text          | text          |
| Yes      | series tag  | city                    | City                    | text          | text          |
| Yes      | series tag  | state                   | State                   | text          | text          |
| Yes      | series tag  | zip_code                | Zip Code                | text          | text          |
| Yes      | series tag  | phone_number            | Phone Number            | text          | text          |
```

## Time Field

```ls
Value = contract_advertise_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2
```

## Data Commands

```ls
series e:kbn3-a3jv d:2017-05-12T00:00:00.000Z t:city=Syracuse t:firm_name="C&S Engineers, Inc." t:phone_number="(315) 703-4287" t:state=NY t:zip_code=13212 m:row_number.kbn3-a3jv=1

series e:kbn3-a3jv d:2017-05-12T00:00:00.000Z t:city=Syracuse t:firm_name="C&S Engineers, Inc." t:phone_number="(315) 703-4287" t:state=NY t:zip_code=13027 m:row_number.kbn3-a3jv=2

series e:kbn3-a3jv d:2017-05-12T00:00:00.000Z t:city=Syracuse t:firm_name="C&S Engineers, Inc." t:phone_number="(315) 703-4287" t:state=NY t:zip_code=13027 m:row_number.kbn3-a3jv=3
```

## Meta Commands

```ls
metric m:row_number.kbn3-a3jv p:long l:"Row Number"

entity e:kbn3-a3jv l:"State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000" t:attribution="State University Construction Fund" t:url=https://data.ny.gov/api/views/kbn3-a3jv

property e:kbn3-a3jv t:meta.view d:2017-09-25T07:22:45.822Z v:averageRating=0 v:name="State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000" v:attribution="State University Construction Fund" v:attributionLink=http://sucf.suny.edu v:id=kbn3-a3jv v:category=Education

property e:kbn3-a3jv t:meta.view.owner d:2017-09-25T07:22:45.822Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:kbn3-a3jv t:meta.view.tableauthor d:2017-09-25T07:22:45.822Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:kbn3-a3jv t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:22:45.822Z v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY" v:Publisher="State of New York"
```

## Top Records

```ls
| project   | campus_name                            | project_title                        | contract_advertise_date | firm_name                                         | address_line_1            | address_line_2        | city        | state | zip_code   | phone_number   | 
| ========= | ====================================== | ==================================== | ======================= | ================================================= | ========================= | ===================== | =========== | ===== | ========== | ============== | 
|           |                                        |                                      | 2017-05-12T00:00:00     | C&S Engineers, Inc.                               | 499 Col Eileen Collins Bv |                       | Syracuse    | NY    | 13212      | (315) 703-4287 | 
|           |                                        |                                      | 2017-05-12T00:00:00     | C&S Engineers, Inc.                               | 499 Col Eileen Collins Bv |                       | Syracuse    | NY    | 13027      | (315) 703-4287 | 
|           |                                        |                                      | 2017-05-12T00:00:00     | C&S Engineers, Inc.                               | 499 Col Eileen Collins Bv |                       | Syracuse    | NY    | 13027      | (315) 703-4287 | 
| 01X842-00 | State University of New York at Albany | Program Study - Renovate Page Hall   | 2008-09-18T00:00:00     | EINHORN YAFFEE PRESCOTT ARCHITECTURE & ENGR, P.C. | Broadway At Beaver Street | PO Box 617            | Albany      | NY    | 12201-0617 | (518) 431-3300 | 
| 01X842-00 | State University of New York at Albany | Program Study - Renovate Page Hall   | 2008-09-18T00:00:00     | ELEMENTAL ARCHITECTURE, LLC                       | 4th Floor                 | 154 West 14th Street  | New York    | NY    | 10011      | (212) 616-4110 | 
| 01X842-00 | State University of New York at Albany | Program Study - Renovate Page Hall   | 2008-09-18T00:00:00     | MITCHELL/GIURGOLA ARCHITECTS                      | Film Center Bldg, Ste 711 | 630 Ninth Avenue      | New York    | NY    | 10036      | (212) 663-4000 | 
| 01X844-00 | State University of New York at Albany | Facilities Master Plan - Albany      | 2009-09-11T00:00:00     | H2L2 ARCHITECTS/PLANNERS, LLP                     | Suite 1801                | 80 Broad Street       | New York    | NY    | 10004      | (212) 688-9800 | 
| 01X844-00 | State University of New York at Albany | Facilities Master Plan - Albany      | 2009-09-11T00:00:00     | PERKINS & WILL ARCHITECTS P.C.                    | 4th Floor                 | 215 Park Avenue South | New York    | NY    | 10003      | (212) 251-7024 | 
| 01XA41-00 | State University of New York at Albany | Campus Storm Water Pond Improvements | 2008-04-10T00:00:00     | GREENMAN-PEDERSEN, INC                            | Suite 207                 | 400 Rella Boulevard   | Montebello  | NY    | 10901      | (845) 368-4050 | 
| 01XA47-00 | State University of New York at Albany | Renovate Health Center               | 2012-06-29T00:00:00     | JMZ Architects and Planners, P.C.                 | PO Box 725                | 190 Glen Street       | Glens Falls | NY    | 12801-0725 | (518) 793-0786 | 
```