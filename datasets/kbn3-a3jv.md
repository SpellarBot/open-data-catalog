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
| Publication Date | 2017-04-01T10:11:38Z |

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
series e:kbn3-a3jv d:2015-09-11T00:00:00.000Z t:project=011006-00 t:phone_number="(212) 643-9898" t:zip_code=10018-0000 t:project_title="Upgrade Central Plant - SUCF" t:state=NY t:campus_name="State University of New York at Albany" t:firm_name="Kallen & Lemelson, Consulting Engineers, LLP" t:city="New York" m:row_number.kbn3-a3jv=1

series e:kbn3-a3jv d:2015-09-11T00:00:00.000Z t:project=011006-00 t:phone_number="(646) 827-6400" t:zip_code=10121 t:project_title="Upgrade Central Plant - SUCF" t:state=NY t:campus_name="State University of New York at Albany" t:firm_name="WM Group Engineers, P.C." t:city="New York" m:row_number.kbn3-a3jv=2

series e:kbn3-a3jv d:2016-03-07T00:00:00.000Z t:project=011009-00 t:phone_number="(716) 565-9190" t:zip_code=14225 t:project_title="Upgrade Controls Study/Pilot Campus Wide" t:state=NY t:campus_name="State University of New York at Albany" t:firm_name="C. J. Brown Energy Engineering & Architectur" t:city=Buffalo m:row_number.kbn3-a3jv=3
```

## Meta Commands

```ls
metric m:row_number.kbn3-a3jv p:long l:"Row Number"

entity e:kbn3-a3jv l:"State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000" t:attribution="State University Construction Fund" t:url=https://data.ny.gov/api/views/kbn3-a3jv

property e:kbn3-a3jv t:meta.view v:id=kbn3-a3jv v:category=Education v:attributionLink=http://sucf.suny.edu v:averageRating=0 v:name="State University Construction Fund (SUCF) Short-Listed Firms: Beginning 2000" v:attribution="State University Construction Fund"

property e:kbn3-a3jv t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:kbn3-a3jv t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:kbn3-a3jv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project   | campus_name                            | project_title                            | contract_advertise_date | firm_name                                         | address_line_1            | address_line_2          | city     | state | zip_code   | phone_number   | 
| ========= | ====================================== | ======================================== | ======================= | ================================================= | ========================= | ======================= | ======== | ===== | ========== | ============== | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF             | 2015-09-11T00:00:00     | Kallen & Lemelson, Consulting Engineers, LLP      | 17th Flr                  | 520 Eighth Avenue       | New York | NY    | 10018-0000 | (212) 643-9898 | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF             | 2015-09-11T00:00:00     | WM Group Engineers, P.C.                          | Two Penn Plaza,           | 380 Seventh Avenue #552 | New York | NY    | 10121      | (646) 827-6400 | 
| 011009-00 | State University of New York at Albany | Upgrade Controls Study/Pilot Campus Wide | 2016-03-07T00:00:00     | C. J. Brown Energy Engineering & Architectur      | Suite 204                 | 4245 Union Road         | Buffalo  | NY    | 14225      | (716) 565-9190 | 
| 011009-00 | State University of New York at Albany | Upgrade Controls Study/Pilot Campus Wide | 2016-03-07T00:00:00     | M/E Engineering, P.C.                             | Suite 320                 | 60 Lakefront Boulevard  | Buffalo  | NY    | 14202      | (716) 845-5092 | 
| 011009-00 | State University of New York at Albany | Upgrade Controls Study/Pilot Campus Wide | 2016-03-07T00:00:00     | WM Group Engineers, P.C.                          | Two Penn Plaza,           | 380 Seventh Avenue #552 | New York | NY    | 10121      | (646) 827-6400 | 
| 01X842-00 | State University of New York at Albany | Program Study - Renovate Page Hall       | 2008-09-18T00:00:00     | Einhorn Yaffee Prescott Architecture & Engr, P.C. | Broadway At Beaver Street | PO Box 617              | Albany   | NY    | 12201-0617 | (518) 431-3300 | 
| 01X842-00 | State University of New York at Albany | Program Study - Renovate Page Hall       | 2008-09-18T00:00:00     | Elemental Architecture, LLC                       | 4th Floor                 | 154 West 14th Street    | New York | NY    | 10011      | (212) 616-4110 | 
| 01X842-00 | State University of New York at Albany | Program Study - Renovate Page Hall       | 2008-09-18T00:00:00     | Mitchell/Giurgola Architects                      | Film Center Bldg, Ste 711 | 630 Ninth Avenue        | New York | NY    | 10036      | (212) 663-4000 | 
| 01X844-00 | State University of New York at Albany | Facilities Master Plan - Albany          | 2009-09-11T00:00:00     | H2L2 Architects/Planners, LLP                     | Suite 1801                | 80 Broad Street         | New York | NY    | 10004      | (212) 688-9800 | 
| 01X844-00 | State University of New York at Albany | Facilities Master Plan - Albany          | 2009-09-11T00:00:00     | Perkins & Will Architects P.C.                    | 4th Floor                 | 215 Park Avenue South   | New York | NY    | 10003      | (212) 251-7024 | 
```