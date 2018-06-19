# Top Manufacturing Companies in SSMMA Region

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-manufacturing-companies-in-ssmma-region-1580d) |
| Metadata | [Link](https://data.illinois.gov/api/views/8ych-bcfm) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8ych-bcfm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8ych-bcfm/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8ych-bcfm |
| Name | Top Manufacturing Companies in SSMMA Region |
| Category | Economics |
| Tags | manufacturing, ssmma, business |
| Created | 2013-03-14T19:21:34Z |
| Publication Date | 2013-03-14T19:42:20Z |

## Description

Top Manufacturing Companies in SSMMA Region

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | contact_first_name         | Contact First Name         | text      | text        |
| Yes      | series tag     | contact_last_name          | Contact Last Name          | text      | text        |
| Yes      | series tag     | contact_title              | Contact Title              | text      | text        |
| Yes      | series tag     | company_name               | Company Name               | text      | text        |
| No       |                | primary_address            | Primary Address            | text      | text        |
| Yes      | series tag     | primary_city               | Primary City               | text      | text        |
| Yes      | series tag     | primary_county             | Primary County             | text      | text        |
| Yes      | series tag     | primary_state              | Primary State              | text      | text        |
| Yes      | series tag     | primary_zip                | Primary Zip                | text      | number      |
| Yes      | series tag     | primary_country            | Primary Country            | text      | text        |
| Yes      | series tag     | phone_number               | Phone Number               | text      | text        |
| Yes      | series tag     | line_of_business           | Line Of Business           | text      | text        |
| Yes      | numeric metric | facility_size_sq_ft        | Facility Size (sq.Ft)      | number    | number      |
| Yes      | series tag     | d_u_n_s_number             | D-U-N-S Number             | text      | number      |
| Yes      | series tag     | ultimate_parent            | Ultimate Parent            | text      | text        |
| Yes      | numeric metric | revenue_million            | Revenue ($ million)        | number    | number      |
| Yes      | numeric metric | total_employees            | Total Employees            | number    | number      |
| Yes      | series tag     | employee_growth            | Employee Growth (%)        | text      | text        |
| Yes      | numeric metric | employees_at_this_location | Employees At This Location | number    | number      |
| Yes      | series tag     | primary_industry           | Primary Industry           | text      | text        |
| Yes      | series tag     | primary_us_naics_code      | Primary US NAICS Code      | text      | number      |
| Yes      | series tag     | all_naics_codes            | All NAICS Codes            | text      | text        |
| Yes      | series tag     | web_address                | Web Address                | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = primary_address
```

## Data Commands

```ls
series e:8ych-bcfm d:2013-03-14T12:21:37.000Z t:line_of_business="Railroads, line-haul operating, nsk" t:phone_number=708-332-3500 t:contact_first_name=E t:primary_us_naics_code=482111 t:d_u_n_s_number=59447961 t:primary_industry=Railroads t:contact_title=Pres-ceo t:primary_county="Cook County" t:ultimate_parent="Canadian National Railway Company" t:company_name="Illinois Central Railroad Company (inc)" t:all_naics_codes=482111 t:primary_zip=60430 t:contact_last_name=Harrison t:primary_city=Homewood t:primary_state=IL t:primary_country="United States" m:total_employees=3600 m:employees_at_this_location=3200 m:revenue_million=252.4 m:facility_size_sq_ft=20000

series e:8ych-bcfm d:2013-03-14T12:21:37.000Z t:line_of_business="Current-carrying wiring devices" t:phone_number=708-532-1800 t:web_address=http://www.panduit.com t:contact_first_name=Dennis t:primary_us_naics_code=33531 t:d_u_n_s_number=5178363 t:primary_industry="Electronic Connector Manufacturing" t:contact_title=Principle t:ultimate_parent="Panduit Corp." t:company_name="Panduit Corp." t:all_naics_codes=334290;334417;33531;335313;335999;423430 t:primary_zip=60487 t:contact_last_name=Colleran t:primary_city="Tinley Park" t:primary_state=IL t:primary_country="United States" m:total_employees=3500 m:employees_at_this_location=1100 m:revenue_million=799.172 m:facility_size_sq_ft=1000000

series e:8ych-bcfm d:2013-03-14T12:21:37.000Z t:line_of_business="Metals service centers and offices" t:phone_number=708-339-1610 t:web_address=http://www.alliedtube.net t:contact_first_name=Kim t:primary_us_naics_code=423510 t:d_u_n_s_number=828752332 t:primary_industry="Steel Service Centers & Other Metal Wholesalers" t:contact_title=Manager t:primary_county="Cook County" t:ultimate_parent="Atkore International Group Inc." t:company_name="Allied Tube & Conduit Corporation" t:all_naics_codes=423510 t:primary_zip=60426 t:contact_last_name=Koutski t:primary_city=Harvey t:primary_state=IL t:primary_country="United States" m:employees_at_this_location=1000 m:facility_size_sq_ft=53577
```

## Meta Commands

```ls
metric m:facility_size_sq_ft p:integer l:"Facility Size (sq.Ft)" t:dataTypeName=number

metric m:revenue_million p:float l:"Revenue ($ million)" t:dataTypeName=number

metric m:total_employees p:integer l:"Total Employees" t:dataTypeName=number

metric m:employees_at_this_location p:integer l:"Employees At This Location" t:dataTypeName=number

entity e:8ych-bcfm l:"Top Manufacturing Companies in SSMMA Region" t:url=https://data.illinois.gov/api/views/8ych-bcfm

property e:8ych-bcfm t:meta.view v:id=8ych-bcfm v:category=Economics v:averageRating=0 v:name="Top Manufacturing Companies in SSMMA Region"

property e:8ych-bcfm t:meta.view.owner v:id=v25s-g5ev v:screenName=Jalarcon v:displayName=Jalarcon

property e:8ych-bcfm t:meta.view.tableauthor v:id=v25s-g5ev v:screenName=Jalarcon v:roleName=publisher v:displayName=Jalarcon
```

## Top Records

```ls
| :updated_at | contact_first_name | contact_last_name | contact_title                                      | company_name                            | primary_address          | primary_city    | primary_county | primary_state | primary_zip | primary_country | phone_number | line_of_business                          | facility_size_sq_ft | d_u_n_s_number | ultimate_parent                   | revenue_million | total_employees | employee_growth | employees_at_this_location | primary_industry                                | primary_us_naics_code | all_naics_codes                          | web_address                             | 
| =========== | ================== | ================= | ================================================== | ======================================= | ======================== | =============== | ============== | ============= | =========== | =============== | ============ | ========================================= | =================== | ============== | ================================= | =============== | =============== | =============== | ========================== | =============================================== | ===================== | ======================================== | ======================================= | 
| 1363263697  | E                  | Harrison          | Pres-ceo                                           | Illinois Central Railroad Company (inc) | 17641 Ashland Ave        | Homewood        | Cook County    | IL            | 60430       | United States   | 708-332-3500 | Railroads, line-haul operating, nsk       | 20000               | 59447961       | Canadian National Railway Company | 252.4           | 3600            |                 | 3200                       | Railroads                                       | 482111                | 482111                                   | [null, null]                            | 
| 1363263697  | Dennis             | Colleran          | Principle                                          | Panduit Corp.                           | 18900 Panduit Dr.        | Tinley Park     |                | IL            | 60487       | United States   | 708-532-1800 | Current-carrying wiring devices           | 1000000             | 5178363        | Panduit Corp.                     | 799.172         | 3500            |                 | 1100                       | Electronic Connector Manufacturing              | 33531                 | 334290;334417;33531;335313;335999;423430 | [http://www.panduit.com, null]          | 
| 1363263697  | Kim                | Koutski           | Manager                                            | Allied Tube & Conduit Corporation       | 16100 Lathrop Ave        | Harvey          | Cook County    | IL            | 60426       | United States   | 708-339-1610 | Metals service centers and offices        | 53577               | 828752332      | Atkore International Group Inc.   |                 |                 |                 | 1000                       | Steel Service Centers & Other Metal Wholesalers | 423510                | 423510                                   | [http://www.alliedtube.net, null]       | 
| 1363263697  | John               | Caveney           | President                                          | Panduit Corp.                           | 17301 Ridgeland Ave      | Tinley Park     | Cook County    | IL            | 60477       | United States   | 708-532-1800 | Noncurrent-carrying wiring devices, nsk   | 115048              | 17611232       | Panduit Corp.                     |                 |                 |                 | 900                        | Electrical Products Manufacturing               | 335932                | 335931;335932                            | [http://www.panduit.com, null]          | 
| 1363263697  | John               | Daley             | Pres                                               | Consolidated Medical Transport          | 132 E Sibley Blvd        | Dolton          | Cook County    | IL            | 60419       | United States   | 708-331-3310 | Local passenger transportation, nec       | 200000              | 945626794      |                                   | 20.8            | 800             |                 | 800                        | Transportation Services Sector                  | 485999                | 485999                                   | [null, null]                            | 
| 1363263697  | Edward             | Breen             | Ceo                                                | Allied Tube & Conduit Corporation       | 16100 Lathrop Ave        | Harvey          | Cook County    | IL            | 60426       | United States   | 708-339-1610 | Steel pipe and tubes, nsk                 | 500000              | 57863847       | Atkore International Group Inc.   | 594.1           | 3100            |                 | 750                        | Steel Production                                | 331210                | 331210                                   | [http://www.alliedtube.com, null]       | 
| 1363263697  | Don                | Hall              | Director Of Is                                     | ABF Freight System, Inc.                | 1900 E Lincoln Hwy       | Lynwood         | Cook County    | IL            | 60411       | United States   | 708-757-7600 | Trucking, except local                    | 75087               | 799525642      | Arkansas Best Corporation         |                 |                 |                 | 700                        | Truckload Carriers                              | 484121                | 484121                                   | [http://www.abf.com, null]              | 
| 1363263697  | James              | Kellner           | Chairman and CEO                                   | Applied Systems, Inc.                   | 200 Applied Pkwy.        | University Park |                | IL            | 60484       | United States   | 708-534-5575 | Custom computer programming services, nsk | 150000              | 103187050      | Bc Asi Capital II Inc             | 48              | 622             |                 | 502                        | Financial Services, Legal & Government Software | 511210                | 511210                                   | [http://www.appliedsystems.com, null]   | 
| 1363263697  | Kathleen           | Bloch             | Chief Financial Officer                            | Silver Line Building Products LLC       | 16801 Exchange Ave Ste 2 | Lansing         | Cook County    | IL            | 60438       | United States   | 708-474-9100 | Plastics products, nec, nsk               | 115048              | 14120294       | Andersen Corporation              |                 |                 |                 | 500                        | Plastic & Rubber Product Manufacturing          | 326199                | 326199;332321                            | [http://www.silverlinewindow.com, null] | 
| 1363263697  | Gregory            | Heim              | Ceo; Owner; President; Senior Executive Management | Modern Drop Forge Co.                   | 13810 Western Ave        | Blue Island     | Cook County    | IL            | 60406       | United States   | 708-388-1806 | Iron and steel forgings, nsk              | 250000              | 5455597        | Modern Drop Forge Co.             | 66              | 610             |                 | 430                        | Fabricated Metal Product Manufacturing          | 332111                | 332111;333514                            | [http://www.modernforge.com, null]      | 
```