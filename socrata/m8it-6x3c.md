# Lobbying Clients Sources of Funding for Lobbying Activities: Beginning 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbying-clients-sources-of-funding-for-lobbying-activities-beginning-2012) |
| Metadata | [Link](https://data.ny.gov/api/views/m8it-6x3c) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/m8it-6x3c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/m8it-6x3c/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | m8it-6x3c |
| Name | Lobbying Clients Sources of Funding for Lobbying Activities: Beginning 2012 |
| Attribution | NYS Joint Commission on Public Ethics |
| Category | Transparency |
| Tags | lobbying clients, funding, lobbying activities, integrity |
| Created | 2013-04-16T15:28:32Z |
| Publication Date | 2015-03-13T19:16:44Z |

## Description

Data provided by Clients in their Semi-Annual filings submitted to NYS Joint Commission on Public Ethics

## Columns

```ls
| Included | Schema Type | Field Name                                                            | Name                                                                    | Data Type | Render Type |
| ======== | =========== | ===================================================================== | ======================================================================= | ========= | =========== |
| Yes      | series tag  | client_name                                                           | Client Name                                                             | text      | text        |
| Yes      | time        | report_year                                                           | Report Year                                                             | number    | number      |
| Yes      | series tag  | reporting_period                                                      | Reporting Period                                                        | text      | text        |
| Yes      | series tag  | client_semi_annual_report_filed_includes_source_of_funding_disclosure | Client Semi Annual Report Filed (Includes Source of Funding Disclosure) | url       | url         |
```

## Time Field

```ls
Value = report_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:m8it-6x3c l:"Lobbying  Clients Sources of Funding for Lobbying Activities: Beginning 2012" t:attribution="NYS Joint Commission on Public Ethics" t:url=https://data.ny.gov/api/views/m8it-6x3c

property e:m8it-6x3c t:meta.view v:id=m8it-6x3c v:category=Transparency v:attributionLink=http://www.jcope.ny.gov v:averageRating=0 v:name="Lobbying  Clients Sources of Funding for Lobbying Activities: Beginning 2012" v:attribution="NYS Joint Commission on Public Ethics"

property e:m8it-6x3c t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:m8it-6x3c t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:m8it-6x3c t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| client_name                                           | report_year | reporting_period | client_semi_annual_report_filed_includes_source_of_funding_disclosure                                                               | 
| ===================================================== | =========== | ================ | =================================================================================================================================== | 
| NARAL NY                                              | 2014        | January - June   | [null, null]                                                                                                                        | 
| 125 MEC Center, LLC                                   | 2013        | January - June   | [http://www.jcope.ny.gov/source_funding/forms/2013.1.MECcenterLLC.pdf, null]                                                        | 
| AAA New York State, Inc.                              | 2013        | January - June   | [http://www.jcope.ny.gov/source_funding/forms/2013.1.AAANewYorkState.pdf, null]                                                     | 
| Academy of Trial Lawyers (NYS)                        | 2013        | January - June   | [http://www.jcope.ny.gov/source_funding/forms/2013.1.NYSAcademyofTrialLawyers.pdf, null]                                            | 
| Adult Day Health Care Council                         | 2013        | January - June   | [http://www.jcope.ny.gov/source_funding/forms/2013.1.AdultDayHealthCareCouncil.pdf, null]                                           | 
| Advantage Management                                  | 2013        | January - June   | [http://www.jcope.ny.gov/source_funding/forms/2013.1.AdvantageManagement.pdf, null]                                                 | 
| AFL-CIO (NYS)                                         | 2013        | January - June   | [http://www.jcope.ny.gov/source_funding/forms/2013.1.NYSAFL-CIO.pdf, null]                                                          | 
| Alliance of Fine Wine Wholesalers, Ltd. (NY)          | 2013        | January - June   | [http://www.jcope.ny.gov/source_funding/forms/2013.1.AllianceOfFineWine.pdf, null]                                                  | 
| American Council of Engineering Companies of New York | 2013        | January - June   | [http://www.jcope.ny.gov/source_funding/forms/2013.1.American%20Council%20of%20Engineering%20Companies%20of%20New%20York.pdf, null] | 
| Association for Affordable Housing (NYS)              | 2013        | January - June   | [http://www.jcope.ny.gov/source_funding/forms/2013.1.NYSAssocForAddordableHousing.pdf, null]                                        | 
```