# IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.State Tax Credits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ihda-illinois-housing-dev-auth-fy2010-governors-report-applications-state-tax-credits-5aa55) |
| Metadata | [Link](https://data.illinois.gov/api/views/hv6k-swkq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/hv6k-swkq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/hv6k-swkq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | hv6k-swkq |
| Name | IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.State Tax Credits |
| Category | Housing |
| Tags | ihda, illinois housing development authority |
| Created | 2012-01-25T21:30:44Z |
| Publication Date | 2012-01-25T21:58:19Z |

## Description

FY2010 Governor's Report - Applications.State Tax Credits

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| No       |                | fiscal_year      | FISCAL YEAR      | number        | text          |
| Yes      | series tag     | project_name     | PROJECT NAME     | text          | text          |
| No       |                | project_address  | PROJECT ADDRESS  | text          | text          |
| Yes      | series tag     | project_city     | PROJECT CITY     | text          | text          |
| Yes      | series tag     | project_sponsor  | PROJECT SPONSOR  | text          | text          |
| Yes      | series tag     | type             | TYPE             | text          | text          |
| Yes      | time           | application_date | APPLICATION DATE | calendar_date | calendar_date |
| Yes      | numeric metric | amount_          | AMOUNT           | number        | number        |
| Yes      | numeric metric | units            | UNITS            | number        | number        |
```

## Time Field

```ls
Value = application_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = project_address,fiscal_year
```

## Data Commands

```ls
series e:hv6k-swkq d:2010-05-21T00:00:00.000Z t:project_sponsor="Community Partners for Affordable Housing" t:project_name="Community Partners for Affordable Housing-1420 Cavell" t:project_city="Highland Park" t:type="State Tax Credits" m:amount_=107500 m:units=1

series e:hv6k-swkq d:2010-05-17T00:00:00.000Z t:project_sponsor="Country Club Hills Wellness Center, LP" t:project_name="Country Club Hills Wellness Center" t:project_city="Country Club Hills" t:type="State Tax Credits" m:amount_=656318 m:units=77

series e:hv6k-swkq d:2010-05-17T00:00:00.000Z t:project_sponsor="Thomas Crystal Lake, L.P." t:project_name="Crystal Lake Senior Apartments" t:project_city="Crystal Lake" t:type="State Tax Credits" m:amount_=482500 m:units=100
```

## Meta Commands

```ls
metric m:amount_ p:integer l:AMOUNT t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

entity e:hv6k-swkq l:"IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.State Tax Credits" t:url=https://data.illinois.gov/api/views/hv6k-swkq

property e:hv6k-swkq t:meta.view v:id=hv6k-swkq v:category=Housing v:averageRating=0 v:name="IHDA - Illinois Housing Dev Auth - FY2010 Governor's Report - Applications.State Tax Credits"

property e:hv6k-swkq t:meta.view.owner v:id=i46z-zq8e v:screenName="Larry Michalski" v:displayName="Larry Michalski"

property e:hv6k-swkq t:meta.view.tableauthor v:id=i46z-zq8e v:screenName="Larry Michalski" v:roleName=publisher v:displayName="Larry Michalski"
```

## Top Records

```ls
| fiscal_year | project_name                                          | project_address                   | project_city                                      | project_sponsor                              | type                                              | application_date    | amount_ | units | 
| =========== | ===================================================== | ================================= | ================================================= | ============================================ | ================================================= | =================== | ======= | ===== | 
| 2010        | Community Partners for Affordable Housing-1420 Cavell | 1420 Cavell                       | Highland Park                                     | Community Partners for Affordable Housing    | State Tax Credits                                 | 2010-05-21T00:00:00 | 107500  | 1     | 
| 2010        | Country Club Hills Wellness Center                    | W. 167th Street & S. Pulaski Road | Country Club Hills                                | Country Club Hills Wellness Center, LP       | State Tax Credits                                 | 2010-05-17T00:00:00 | 656318  | 77    | 
| 2010        | Crystal Lake Senior Apartments                        | 221 E. Congress Parkway           | Crystal Lake                                      | Thomas Crystal Lake, L.P.                    | State Tax Credits                                 | 2010-05-17T00:00:00 | 482500  | 100   | 
| 2010        | DuPage Habitat 2009 Scattered Site Homes              | Scattered Sites                   | Addison, Villa Park, Glendale Heights, W. Chicago | DuPage Habitat for Humanity                  | State Tax Credits                                 | 2009-09-09T00:00:00 | 104976  | 4     | 
| 2010        | DuPage Habitat Pioneer Prairie Phase II               | 308 W. Pomeroy & 316 W. Pomeroy   | West Chicago                                      | Pioneer Prairie, LLC                         | State Tax Credits                                 | 2009-11-03T00:00:00 | 43257   | 2     | 
| 2010        | Elgin Artspace Lofts                                  | 51 South Spring Street            | Elgin                                             | Elgin Artspace Lofts Limited Partnership     | State Tax Credits                                 | 2010-05-17T00:00:00 | 1280000 | 55    | 
| 2010        | Emerson Square                                        | 1600 West Foster Street           | Evanston                                          | EmSq, LLC                                    | State Tax Credits                                 | 2010-05-17T00:00:00 | 862500  | 30    | 
| 2010        | Live Work Rock Island Phase VI                        | 120 16 1/2 Street                 | Rock Island                                       | Rock Island Economic Growth Corp.            | Employer Assisted Housing (EAH) State Tax Credits | 2010-01-07T00:00:00 | 286437  | 73    | 
| 2010        | Moline Enterprise Live Work Lofts                     | 1809-1829 River Drive             | Moline                                            | Moline Enterprise Live-Work Lofts, LLC       | State Tax Credits                                 | 2010-04-13T00:00:00 | 451000  | 69    | 
| 2010        | Naomi & Smith Senior Living Center                    | 8019-47 South Halsted             | Chicago                                           | Naomi & Sylvester Smith Senior Living Center | State Tax Credits                                 | 2010-03-01T00:00:00 | 178500  | 60    | 
```