# Brownfield Cleanup Program, Certificates of Completion

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/brownfield-cleanup-program-certificates-of-completion) |
| Metadata | [Link](https://data.ny.gov/api/views/ir93-7qzi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ir93-7qzi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ir93-7qzi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ir93-7qzi |
| Name | Brownfield Cleanup Program, Certificates of Completion |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | brownfield, cleanup, remediation, tax credits, certification |
| Created | 2015-03-24T15:43:20Z |
| Publication Date | 2016-04-30T15:33:35Z |

## Description

This dataset shows Brownfield Cleanup Program (BCP) Sites that have been completed and issued a Certificate of Completion (COC) in the State of New York. Included in the data is the program site identification number; site name; site locality; site acreage; year certificate issued; length of time from the date the New York State Department of Environmental Conservation (NYSDEC) approved the BCP application to the date the COC was issued; and, highest allowable future use for the site and its potential redevelopment (as determined by: remedial program soil cleanup objectives; see 6NYCRR Part 375-6: http://www.dec.ny.gov/regs/15507.html.)

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | series tag     | bcp_site_number               | BCP Site Number               | text      | text        |
| Yes      | series tag     | site_name                     | Site Name                     | text      | text        |
| Yes      | series tag     | location                      | Location                      | text      | text        |
| Yes      | numeric metric | acreage                       | Acreage                       | number    | number      |
| Yes      | time           | year_coc_issued               | Year COC Issued               | number    | number      |
| Yes      | numeric metric | years_from_application_to_coc | Years from Application to COC | number    | number      |
| Yes      | series tag     | highest_allowable_future_use  | Highest Allowable Future Use  | text      | text        |
```

## Time Field

```ls
Value = year_coc_issued
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ir93-7qzi d:2014-01-01T00:00:00.000Z t:bcp_site_number=C130143 t:location=Hempstead t:highest_allowable_future_use=Commercial t:site_name="Former Husslein Plating Corp. & Sempke Bus Garage" m:years_from_application_to_coc=8.85 m:acreage=0.37

series e:ir93-7qzi d:2015-01-01T00:00:00.000Z t:bcp_site_number=C915283 t:location=Buffalo t:highest_allowable_future_use=Restricted-Residential t:site_name="89 LaSalle Avenue Site" m:years_from_application_to_coc=1.61 m:acreage=9.23

series e:ir93-7qzi d:2011-01-01T00:00:00.000Z t:bcp_site_number=C360110 t:location=Ossining t:highest_allowable_future_use=Commercial t:site_name="Clinton Terrace Shopping Center" m:years_from_application_to_coc=2.25 m:acreage=0.9
```

## Meta Commands

```ls
metric m:acreage p:float l:Acreage d:"The size of the site in acres" t:dataTypeName=number

metric m:years_from_application_to_coc p:float l:"Years from Application to COC" d:"Length of time from the date NYSDEC approved the BCP application to the date the COC was issued" t:dataTypeName=number

entity e:ir93-7qzi l:"Brownfield Cleanup Program, Certificates of Completion" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/ir93-7qzi

property e:ir93-7qzi t:meta.view v:id=ir93-7qzi v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/8450.html v:averageRating=0 v:name="Brownfield Cleanup Program, Certificates of Completion" v:attribution="New York State Department of Environmental Conservation"

property e:ir93-7qzi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ir93-7qzi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ir93-7qzi t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bcp_site_number | site_name                                         | location   | acreage | year_coc_issued | years_from_application_to_coc | highest_allowable_future_use | 
| =============== | ================================================= | ========== | ======= | =============== | ============================= | ============================ | 
| C130143         | Former Husslein Plating Corp. & Sempke Bus Garage | Hempstead  | 0.37    | 2014            | 8.85                          | Commercial                   | 
| C915283         | 89 LaSalle Avenue Site                            | Buffalo    | 9.23    | 2015            | 1.61                          | Restricted-Residential       | 
| C360110         | Clinton Terrace Shopping Center                   | Ossining   | 0.9     | 2011            | 2.25                          | Commercial                   | 
| C704046         | NYSEG-Washington St MGP                           | Binghamton | 1.326   | 2011            | 6.28                          | Restricted-Residential       | 
| C224158         | Former Domsey Fiber Corp.                         | Brooklyn   | 2.56    | 2014            | 2.64                          | Restricted-Residential       | 
| C356049         | Former Miron Pre-Cast Facility                    | Ulster     | 10.755  | 2014            | 2.24                          | Restricted-Residential       | 
| C231013         | The Greater Waterside Site                        | New York   | 6.34    | 2011            | 6.43                          | Restricted-Residential       | 
| C241157         | 112-21 Northern Boulevard                         | Corona     | 1.68    | 2015            | 1.68                          | Unrestricted                 | 
| C915195         | Buffalo Urban Renewal Agency West Property        | Buffalo    | 1.64    | 2006            | 1.35                          | Commercial                   | 
| C905038         | 211 Franklin Street                               | Olean      | 5.787   | 2015            | 1.51                          | Commercial                   | 
```