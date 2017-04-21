# State University Construction Fund (SUCF) Request for Qualifications (RFQs) Responders: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-university-construction-fund-sucf-request-for-qualifications-rfqs-responders-beginni) |
| Metadata | [Link](https://data.ny.gov/api/views/c6c2-n3if) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/c6c2-n3if/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/c6c2-n3if/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | c6c2-n3if |
| Name | State University Construction Fund (SUCF) Request for Qualifications (RFQs) Responders: Beginning 2000 |
| Attribution | State University Construction Fund |
| Category | Education |
| Tags | state university construction fund, sucf, construction, contract, education, capital, suny |
| Created | 2014-01-24T19:11:47Z |
| Publication Date | 2017-04-01T10:21:42Z |

## Description

Listing of design firms submitting qualifications for design procurements

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
series e:c6c2-n3if d:2015-09-11T00:00:00.000Z t:project=011006-00 t:phone_number="(212) 268-0950" t:zip_code=10001 t:project_title="Upgrade Central Plant - SUCF" t:state=NY t:campus_name="State University of New York at Albany" t:firm_name="A.G. Consulting Engineering, P.C." t:city="New York" m:row_number.c6c2-n3if=1

series e:c6c2-n3if d:2015-09-11T00:00:00.000Z t:project=011006-00 t:phone_number="(212) 643-9898" t:zip_code=10018-0000 t:project_title="Upgrade Central Plant - SUCF" t:state=NY t:campus_name="State University of New York at Albany" t:firm_name="Kallen & Lemelson, Consulting Engineers, LLP" t:city="New York" m:row_number.c6c2-n3if=2

series e:c6c2-n3if d:2015-09-11T00:00:00.000Z t:project=011006-00 t:phone_number="(585) 454-6110" t:zip_code=14614 t:project_title="Upgrade Central Plant - SUCF" t:state=NY t:campus_name="State University of New York at Albany" t:firm_name="Labella Associates, D.P.C" t:city=Rochester m:row_number.c6c2-n3if=3
```

## Meta Commands

```ls
metric m:row_number.c6c2-n3if p:long l:"Row Number"

entity e:c6c2-n3if l:"State University Construction Fund (SUCF) Request for Qualifications (RFQs) Responders: Beginning 2000" t:attribution="State University Construction Fund" t:url=https://data.ny.gov/api/views/c6c2-n3if

property e:c6c2-n3if t:meta.view v:id=c6c2-n3if v:category=Education v:attributionLink=http://sucf.suny.edu v:averageRating=0 v:name="State University Construction Fund (SUCF) Request for Qualifications (RFQs) Responders: Beginning 2000" v:attribution="State University Construction Fund"

property e:c6c2-n3if t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:c6c2-n3if t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:c6c2-n3if t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project   | campus_name                            | project_title                       | contract_advertise_date | firm_name                                      | address_line_1         | address_line_2            | city      | state | zip_code   | phone_number   | 
| ========= | ====================================== | =================================== | ======================= | ============================================== | ====================== | ========================= | ========= | ===== | ========== | ============== | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF        | 2015-09-11T00:00:00     | A.G. Consulting Engineering, P.C.              | 13th Floor             | 260 West 35th Street      | New York  | NY    | 10001      | (212) 268-0950 | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF        | 2015-09-11T00:00:00     | Kallen & Lemelson, Consulting Engineers, LLP   | 17th Flr               | 520 Eighth Avenue         | New York  | NY    | 10018-0000 | (212) 643-9898 | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF        | 2015-09-11T00:00:00     | Labella Associates, D.P.C                      | Suite 201              | 300 State Street          | Rochester | NY    | 14614      | (585) 454-6110 | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF        | 2015-09-11T00:00:00     | Parsons Brinckerhoff Construction Services,Inc | One Penn Plaza         |                           | New York  | NY    | 10119-0021 | (212) 465-5777 | 
| 011006-00 | State University of New York at Albany | Upgrade Central Plant - SUCF        | 2015-09-11T00:00:00     | WM Group Engineers, P.C.                       | Two Penn Plaza,        | 380 Seventh Avenue #552   | New York  | NY    | 10121      | (646) 827-6400 | 
| 011008-00 | State University of New York at Albany | Rehab Toilet Rooms for ADA - Podium | 2015-10-19T00:00:00     | Ashley McGraw Architects, P.C.                 | 15th Floor             | 125 East Jefferson Street | Syracuse  | NY    | 13202      | (315) 425-1811 | 
| 011008-00 | State University of New York at Albany | Rehab Toilet Rooms for ADA - Podium | 2015-10-19T00:00:00     | Bell & Spina Architects-Planners, P.C.         | Suite 201, The Bindery | 215 Wyoming Street        | Syracuse  | NY    | 13204      | (315) 488-0377 | 
| 011008-00 | State University of New York at Albany | Rehab Toilet Rooms for ADA - Podium | 2015-10-19T00:00:00     | DCS Infrastructure, LLC                        | Suite 1b               | 3249 Route 112, Building  | Medford   | NY    | 11763      | (631) 320-1706 | 
| 011008-00 | State University of New York at Albany | Rehab Toilet Rooms for ADA - Podium | 2015-10-19T00:00:00     | Kouzmanoff Bainton, Architects                 | Suite 21n              | 535 8th Avenue            | New York  | NY    | 10018      | (212) 290-8616 | 
| 011008-00 | State University of New York at Albany | Rehab Toilet Rooms for ADA - Podium | 2015-10-19T00:00:00     | Lacey Thaler Reilly Wilson Arch &Preservation  | 4th Floor              | 79 North Pearl Street     | Albany    | NY    | 12208      | (518) 375-1485 | 
```