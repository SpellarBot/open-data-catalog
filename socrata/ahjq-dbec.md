# Child Welfare and Community Services Funded Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/child-welfare-and-community-services-funded-programs) |
| Metadata | [Link](https://data.ny.gov/api/views/ahjq-dbec) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ahjq-dbec/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ahjq-dbec/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ahjq-dbec |
| Name | Child Welfare and Community Services Funded Programs |
| Attribution | New York State Office of Children and Family Services |
| Category | Human Services |
| Tags | child welfare, family services, elder care, advocacy, abuse prevention |
| Created | 2014-04-15T11:42:46Z |
| Publication Date | 2016-12-19T19:37:58Z |

## Description

Included in this data set are data elements that will help the public identify all the programs currently funded by the New York State Office of Children and Family Services' (OCFS) Division of Child Welfare and Community Services (CWCS).  Data elements include the name of the provider agency, the business address and phone number, the county served, type of program, funding source, description of services, contract dates, contract number, funding level and the agencies website, where available

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | agency              | Agency              | text      | text        |
| No       |                | address             | Street Address      | text      | text        |
| Yes      | series tag     | city                | City                | text      | text        |
| Yes      | series tag     | state               | State               | text      | text        |
| Yes      | series tag     | zip                 | Zip                 | text      | text        |
| Yes      | series tag     | phone               | Phone               | text      | text        |
| Yes      | series tag     | counties_served     | Counties Served     | text      | text        |
| Yes      | series tag     | program_type        | Program Type        | text      | text        |
| Yes      | series tag     | funding_source      | Funding Source      | text      | text        |
| Yes      | series tag     | program_description | Program Description | text      | text        |
| Yes      | series tag     | contract_dates      | Contract Dates      | text      | text        |
| Yes      | series tag     | contract_number     | Contract Number     | text      | text        |
| Yes      | numeric metric | funding_level       | Funding Level       | money     | money       |
| Yes      | series tag     | website             | Website             | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:ahjq-dbec d:2015-08-06T05:24:00.000Z t:zip=14209 t:program_type="Runaway and Homeless Youth Shelter" t:phone="(716) 886-1351" t:program_description="Shelter and services to help to stabilize runaway and homeless youth (male and female) ages 12-24 years." t:website=http://www.compasshouse.org t:funding_source="Public/Private Partnership/ State Aid to Localities" t:state=NY t:contract_number=C026937 t:counties_served=ERIE t:agency="Compass House" t:contract_dates=09/1/15-08/31/16 t:city=Buffalo m:funding_level=126843

series e:ahjq-dbec d:2015-08-06T05:23:33.000Z t:zip=12095 t:program_type="Multidisciplinary/Children's Advocacy Center" t:phone="(518) 736-2443" t:program_description="Children's Advocacy Center (CAC) serves child victims of sexual abuse or physical abuse through a comprehensive approach of providing services to the victim and their non-offending family members. The CAC provides a safe, neutral child-friendly environment where child victims meet with members of a multidisciplinary team for the purpose of the investigative interview and services. All 40 Child Advocacy Centers across New York State are Tier I programs. Tier I status indicates that a program is meeting or exceeding all ten standards set forth by OCFS to be considered an approved Child Advocacy Center." t:funding_source="State Aid to Localities" t:state=NY t:contract_number=C026727 t:counties_served=FULTON t:agency="Mental Health Assoc. in Fulton and Montgomery Counties, Inc." t:contract_dates=2/1/15-1/31/16 t:city=Johnstown m:funding_level=121777

series e:ahjq-dbec d:2015-08-06T05:23:33.000Z t:zip=10595 t:program_type="Multidisciplinary/Children's Advocacy Center" t:phone="(914) 493-5333" t:program_description="Children's Advocacy Center (CAC) serves child victims of sexual abuse or physical abuse through a comprehensive approach of providing services to the victim and their non-offending family members. The CAC provides a safe, neutral child-friendly environment where child victims meet with members of a multidisciplinary team for the purpose of the investigative interview and services. All 40 Child Advocacy Centers across New York State are Tier I programs. Tier I status indicates that a program is meeting or exceeding all ten standards set forth by OCFS to be considered an approved Child Advocacy Center." t:website=http://www.wihd.org t:funding_source="State Aid to Localities" t:state=NY t:contract_number=C026406 t:counties_served=WESTCHESTER t:agency="Westchester County District Attorneys Office" t:contract_dates=2/1/15-1/31/16 t:city=Valhalla m:funding_level=191825
```

## Meta Commands

```ls
metric m:funding_level p:integer l:"Funding Level" d:"Grant award amount for the contract period. No value is shown when funding level is to be determined." t:dataTypeName=money

entity e:ahjq-dbec l:"Child Welfare and Community Services Funded Programs" t:attribution="New York State Office of Children and Family Services" t:url=https://data.ny.gov/api/views/ahjq-dbec

property e:ahjq-dbec t:meta.view v:id=ahjq-dbec v:category="Human Services" v:attributionLink=http://www.ocfs.state.ny.us v:averageRating=0 v:name="Child Welfare and Community Services Funded Programs" v:attribution="New York State Office of Children and Family Services"

property e:ahjq-dbec t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ahjq-dbec t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ahjq-dbec t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | agency                                                       | address                        | city         | state | zip   | phone          | counties_served | program_type                                      | funding_source                                      | program_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | contract_dates   | contract_number | funding_level | website                                    | 
| =========== | ============================================================ | ============================== | ============ | ===== | ===== | ============== | =============== | ================================================= | =================================================== | =============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ================ | =============== | ============= | ========================================== | 
| 1438838640  | Compass House                                                | 1451 Main Street               | Buffalo      | NY    | 14209 | (716) 886-1351 | ERIE            | Runaway and Homeless Youth Shelter                | Public/Private Partnership/ State Aid to Localities | Shelter and services to help to stabilize runaway and homeless youth (male and female) ages 12-24 years.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 09/1/15-08/31/16 | C026937         | 126843        | [http://www.compasshouse.org, null]        | 
| 1438838613  | Mental Health Assoc. in Fulton and Montgomery Counties, Inc. | 307-309 Meadow Street          | Johnstown    | NY    | 12095 | (518) 736-2443 | FULTON          | Multidisciplinary/Children's Advocacy Center      | State Aid to Localities                             | Children's Advocacy Center (CAC) serves child victims of sexual abuse or physical abuse through a comprehensive approach of providing services to the victim and their non-offending family members. The CAC provides a safe, neutral child-friendly environment where child victims meet with members of a multidisciplinary team for the purpose of the investigative interview and services. All 40 Child Advocacy Centers across New York State are Tier I programs. Tier I status indicates that a program is meeting or exceeding all ten standards set forth by OCFS to be considered an approved Child Advocacy Center. | 2/1/15-1/31/16   | C026727         | 121777        | [null, null]                               | 
| 1438838613  | Westchester County District Attorneys Office                 | WIHD/Cedarwood Hall            | Valhalla     | NY    | 10595 | (914) 493-5333 | WESTCHESTER     | Multidisciplinary/Children's Advocacy Center      | State Aid to Localities                             | Children's Advocacy Center (CAC) serves child victims of sexual abuse or physical abuse through a comprehensive approach of providing services to the victim and their non-offending family members. The CAC provides a safe, neutral child-friendly environment where child victims meet with members of a multidisciplinary team for the purpose of the investigative interview and services. All 40 Child Advocacy Centers across New York State are Tier I programs. Tier I status indicates that a program is meeting or exceeding all ten standards set forth by OCFS to be considered an approved Child Advocacy Center. | 2/1/15-1/31/16   | C026406         | 191825        | [http://www.wihd.org, null]                | 
| 1438838613  | Y.W.C.A. of the Mohawk Valley                                | 205 North Wshington Street     | Herkimer     | NY    | 13350 | (315) 732-2159 | HERKIMER        | Multidisciplinary/Children's Advocacy Center      | State Aid to Localities                             | Children's Advocacy Center (CAC) serves child victims of sexual abuse or physical abuse through a comprehensive approach of providing services to the victim and their non-offending family members. The CAC provides a safe, neutral child-friendly environment where child victims meet with members of a multidisciplinary team for the purpose of the investigative interview and services. All 40 Child Advocacy Centers across New York State are Tier I programs. Tier I status indicates that a program is meeting or exceeding all ten standards set forth by OCFS to be considered an approved Child Advocacy Center. | 10/1/15-9/30/16  | C026601         | 162524        | [http://www.ywcamv.org, null]              | 
| 1438838613  | Grace Smith House, Inc.                                      | P. O. Box 5205                 | Poughkeepsie | NY    | 12602 | (845) 471-3033 | DUTCHESS        | Domestic Violence                                 | Federal Family Violence Prevention and Services Act | Approved and/or licensed residential and non-residential programs for victims of domestic violence which provide counseling, advocacy, information and referral, outreach and education, and hotline services for victims of domestic violence and their children.                                                                                                                                                                                                                                                                                                                                                              | 4/1/15-3/31/16   | C027507         | 35050         | [http://www.gracesmithhouse.org, null]     | 
| 1438838613  | Otsego County District Attorneys Office                      | 140 County Highway 33W Suite 2 | Cooperstown  | NY    | 13326 | (607) 547-1770 | OTSEGO          | Multidisciplinary/Children's Advocacy Center      | State Aid to Localities                             | Children's Advocacy Center (CAC) serves child victims of sexual abuse or physical abuse through a comprehensive approach of providing services to the victim and their non-offending family members. The CAC provides a safe, neutral child-friendly environment where child victims meet with members of a multidisciplinary team for the purpose of the investigative interview and services. All 40 Child Advocacy Centers across New York State are Tier I programs. Tier I status indicates that a program is meeting or exceeding all ten standards set forth by OCFS to be considered an approved Child Advocacy Center. | 10/1/15-9/30/16  | C027699         | 138339        | [http://www.otsegocounty.com, null]        | 
| 1438838613  | Brighter Tomorrows, Inc.                                     | P. O. Box 706                  | Shirley      | NY    | 11967 | (631) 395-1800 | SUFFOLK         | Domestic Violence                                 | Federal Family Violence Prevention and Services Act | Approved and/or licensed residential and non-residential programs for victims of domestic violence which provide counseling, advocacy, information and referral, outreach and education, and hotline services for victims of domestic violence and their children.                                                                                                                                                                                                                                                                                                                                                              | 4/1/15-3/31/16   | C027530         | 75250         | [http://www.brightertomorrowsli.org, null] | 
| 1438838613  | Advocacy Center of Tompkins County                           | P. O. Box 164                  | Ithaca       | NY    | 14851 | (607) 277-3203 | TOMPKINS        | Domestic Violence                                 | Federal Family Violence Prevention and Services Act | Approved and/or licensed residential and non-residential programs for victims of domestic violence which provide counseling, advocacy, information and referral, outreach and education, and hotline services for victims of domestic violence and their children.                                                                                                                                                                                                                                                                                                                                                              | 4/1/15-3/31/16   | C027470         | 80992         | [http://www.theadvocacycenter.org, null]   | 
| 1438838613  | Allen Women's Resource Center, Ltd.                          | P. O. Box 340316               | Jamaica      | NY    | 11434 | (718) 739-6200 | QUEENS          | Domestic Violence                                 | Federal Family Violence Prevention and Services Act | Approved and/or licensed residential and non-residential programs for victims of domestic violence which provide counseling, advocacy, information and referral, outreach and education, and hotline services for victims of domestic violence and their children.                                                                                                                                                                                                                                                                                                                                                              | 3/31/14-3/30/15  | C026830         | 32045         | [null, null]                               | 
| 1438838613  | Chances and Changes, Inc.                                    | P. O. Box 326                  | Genesee      | NY    | 14454 | (888) 252-9360 | LIVINGSTON      | Child Protective /Domestic Violence Collaboration | Federal Family Violence Prevention and Services Act | Collaboration project in which a domestic violence advocate is out-stationed at the local social service district child protective services office to provide consultation and participate in joint case work, safety planning and home visits with child protective services families experiencing domestic violence.                                                                                                                                                                                                                                                                                                          | 10/1/13-9/30/14  | C025843         | 37974         | [http://www.chancesandchanges.org, null]   | 
```