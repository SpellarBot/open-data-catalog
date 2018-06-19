# Organizational Reports For Hawaii Noncandidate Committees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/organizational-reports-for-hawaii-noncandidate-committees-48ae6) |
| Metadata | [Link](https://data.hawaii.gov/api/views/i4e7-rcnc) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/i4e7-rcnc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/i4e7-rcnc/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | i4e7-rcnc |
| Name | Organizational Reports For Hawaii Noncandidate Committees |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-06-19T22:09:17Z |
| Publication Date | 2017-03-17T19:32:46Z |

## Columns

```ls
| Included | Schema Type | Field Name                            | Name                                  | Data Type     | Render Type   |
| ======== | =========== | ===================================== | ===================================== | ============= | ============= |
| Yes      | series tag  | reg_no                                | Reg No                                | text          | text          |
| Yes      | series tag  | nc_type                               | NC Type                               | text          | text          |
| Yes      | series tag  | noncandidate_committee_name           | Noncandidate Committee Name           | text          | text          |
| No       |             | address_1                             | Address 1                             | text          | text          |
| No       |             | address_2                             | Address 2                             | text          | text          |
| Yes      | series tag  | city                                  | City                                  | text          | text          |
| Yes      | series tag  | state                                 | State                                 | text          | text          |
| Yes      | series tag  | zip_code                              | Zip Code                              | text          | text          |
| Yes      | series tag  | chairperson_name                      | Chairperson Name                      | text          | text          |
| No       |             | chair_address_1                       | Chair Address 1                       | text          | text          |
| No       |             | chair_address_2                       | Chair Address 2                       | text          | text          |
| Yes      | series tag  | chair_city                            | Chair City                            | text          | text          |
| Yes      | series tag  | chair_state                           | Chair State                           | text          | text          |
| Yes      | series tag  | chair_zip_code                        | Chair Zip Code                        | text          | text          |
| Yes      | series tag  | chair_business_phone                  | Chair Business Phone                  | text          | text          |
| Yes      | series tag  | chair_occupation                      | Chair Occupation                      | text          | text          |
| Yes      | series tag  | chair_principal_place_of_business     | Chair Principal Place of Business     | text          | text          |
| Yes      | series tag  | treasurer_name                        | Treasurer Name                        | text          | text          |
| No       |             | treasurer_address_1                   | Treasurer Address 1                   | text          | text          |
| No       |             | treasurer_address_2                   | Treasurer Address 2                   | text          | text          |
| Yes      | series tag  | treasurer_city                        | Treasurer City                        | text          | text          |
| Yes      | series tag  | treasurer_state                       | Treasurer State                       | text          | text          |
| Yes      | series tag  | treasurer_zip_code                    | Treasurer Zip Code                    | text          | text          |
| Yes      | series tag  | treasurer_business_phone              | Treasurer Business Phone              | text          | text          |
| Yes      | series tag  | treasurer_occupation                  | Treasurer Occupation                  | text          | text          |
| Yes      | series tag  | treasurer_principal_place_of_business | Treasurer Principal Place of Business | text          | text          |
| Yes      | series tag  | area_scope_or_jurisdiction            | Area, Scope, or Jurisdiction          | text          | text          |
| Yes      | series tag  | political_party                       | Political Party                       | text          | text          |
| Yes      | series tag  | ballot_issue_description              | Ballot Issue Description              | text          | text          |
| Yes      | series tag  | single_candidate_name                 | Single Candidate Name                 | text          | text          |
| Yes      | series tag  | terminated                            | Terminated                            | text          | text          |
| Yes      | time        | filing_date                           | Filing Date                           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = filing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_1,address_2,chair_address_1,chair_address_2,treasurer_address_1,treasurer_address_2
```

## Data Commands

```ls
series e:i4e7-rcnc d:2016-11-14T12:53:08.000Z t:chair_city="Santa Monica" t:treasurer_name="Sigal, Jose Pepe" t:area_scope_or_jurisdiction="Real Estate" t:nc_type=Standard t:zip_code=90402 t:treasurer_state=CA t:treasurer_principal_place_of_business=CA t:state=CA t:treasurer_city="santa monica" t:reg_no=NC20672 t:city="Santa Monica" t:chairperson_name="Sigal, Jose Pepe" t:chair_zip_code=90402 t:terminated=Y t:chair_state=CA t:treasurer_business_phone=3104513111 t:noncandidate_committee_name="327 Kona, LLC" t:chair_business_phone=3104513111 t:treasurer_occupation="real estate" t:treasurer_zip_code=90402 t:chair_occupation="real estate" t:chair_principal_place_of_business=CA m:row_number.i4e7-rcnc=1

series e:i4e7-rcnc d:2014-01-30T13:17:29.000Z t:chair_city=Waianae t:treasurer_name="Ioane, Abbie" t:area_scope_or_jurisdiction="Business / General Commerce" t:nc_type=Standard t:zip_code=96792 t:treasurer_state=HI t:treasurer_principal_place_of_business=Waipahu t:state=HI t:treasurer_city=Waianae t:reg_no=NC20412 t:city=Waianae t:chairperson_name="Ioane, Abbie" t:chair_zip_code=96792 t:terminated=Y t:chair_state=HI t:treasurer_business_phone="(808) 671-8022" t:noncandidate_committee_name="808 Hits, LLC" t:chair_business_phone="(808) 671-8022" t:treasurer_occupation="Self Employed" t:treasurer_zip_code=96792 t:chair_occupation="Self Employed" t:chair_principal_place_of_business=Waipahu m:row_number.i4e7-rcnc=2

series e:i4e7-rcnc d:2008-08-25T13:40:16.000Z t:chair_city=Honolulu t:treasurer_name="Baker, Margaret K." t:area_scope_or_jurisdiction=Other t:nc_type=Standard t:zip_code=96825 t:treasurer_state=HI t:treasurer_principal_place_of_business=N/A t:state=HI t:treasurer_city=Honolulu t:reg_no=NC20197 t:city=Honolulu t:chairperson_name="Rosebrough, Cynthia J." t:chair_zip_code=96825 t:terminated=Y t:chair_state=HI t:treasurer_business_phone="(808) 396-6021" t:noncandidate_committee_name="8th Senatorial District" t:chair_business_phone="(808) 396-6021" t:treasurer_occupation=retired t:treasurer_zip_code=96825 t:chair_occupation=retired t:chair_principal_place_of_business=N/A m:row_number.i4e7-rcnc=3
```

## Meta Commands

```ls
metric m:row_number.i4e7-rcnc p:long l:"Row Number"

entity e:i4e7-rcnc l:"Organizational Reports For Hawaii Noncandidate Committees" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/i4e7-rcnc

property e:i4e7-rcnc t:meta.view v:id=i4e7-rcnc v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Organizational Reports For Hawaii Noncandidate Committees" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:i4e7-rcnc t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:i4e7-rcnc t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| reg_no  | nc_type  | noncandidate_committee_name                 | address_1                   | address_2 | city         | state | zip_code | chairperson_name       | chair_address_1             | chair_address_2 | chair_city   | chair_state | chair_zip_code | chair_business_phone | chair_occupation      | chair_principal_place_of_business                 | treasurer_name         | treasurer_address_1         | treasurer_address_2 | treasurer_city | treasurer_state | treasurer_zip_code | treasurer_business_phone | treasurer_occupation    | treasurer_principal_place_of_business | area_scope_or_jurisdiction  | political_party | ballot_issue_description | single_candidate_name | terminated | filing_date         | 
| ======= | ======== | =========================================== | =========================== | ========= | ============ | ===== | ======== | ====================== | =========================== | =============== | ============ | =========== | ============== | ==================== | ===================== | ================================================= | ====================== | =========================== | =================== | ============== | =============== | ================== | ======================== | ======================= | ===================================== | =========================== | =============== | ======================== | ===================== | ========== | =================== | 
| NC20672 | Standard | 327 Kona, LLC                               | 256 26th Street- Suite 200  |           | Santa Monica | CA    | 90402    | Sigal, Jose Pepe       | 256 26th Street- Suite 200  |                 | Santa Monica | CA          | 90402          | 3104513111           | real estate           | CA                                                | Sigal, Jose Pepe       | 256 26th Street- Suite 200  |                     | santa monica   | CA              | 90402              | 3104513111               | real estate             | CA                                    | Real Estate                 |                 |                          |                       | Y          | 2016-11-14T12:53:08 | 
| NC20412 | Standard | 808 Hits, LLC                               | 89-1007 Pohakupalena Street |           | Waianae      | HI    | 96792    | Ioane, Abbie           | 89-1007 Pohakupalena Street |                 | Waianae      | HI          | 96792          | (808) 671-8022       | Self Employed         | Waipahu                                           | Ioane, Abbie           | 89-1007 Pohakupalena Street |                     | Waianae        | HI              | 96792              | (808) 671-8022           | Self Employed           | Waipahu                               | Business / General Commerce |                 |                          |                       | Y          | 2014-01-30T13:17:29 | 
| NC20197 | Standard | 8th Senatorial District                     | 206 Lumahai Pl              |           | Honolulu     | HI    | 96825    | Rosebrough, Cynthia J. | 206 Lumahai Pl              |                 | Honolulu     | HI          | 96825          | (808) 396-6021       | retired               | N/A                                               | Baker, Margaret K.     | 206 Lumahai Pl              |                     | Honolulu       | HI              | 96825              | (808) 396-6021           | retired                 | N/A                                   | Other                       |                 |                          |                       | Y          | 2008-08-25T13:40:16 | 
| NC20313 | Standard | A Better Hawaii PAC                         | POST OFFICE BOX 143         |           | HONOLULU     | HI    | 96810    | Racine, Christopher J. | POST OFFICE BOX 143         |                 | HONOLULU     | HI          | 96810          | (808) 356-0400       | INTERNET/BROADCASTING | 875 WAIMANU STREET, SUITE 640, HONOLULU, HI 96813 | Sandlin, Diane M.      | 150 HAMAKUA DRIVE           | SUITE 417           | KAILUA         | HI              | 96734              | 808.356.0400             | CPA-ACCOUNTANT          | ABOVE                                 | Single Candidate            |                 |                          | BENJAMIN CAYETANO     | Y          | 2012-03-15T16:22:18 | 
| NC20001 | Standard | A-1 A-lectrician, Inc.                      | 2849 Kaihikapu Street       |           | Honolulu     | HI    | 96819    | Yamada, James T. Jr.   | 2849 Kaihikapu Street       |                 | Honolulu     | HI          | 96819          | (808) 839-2771       | CEO                   | A-1 A-Lectrician, Inc.                            | Yamada, James T. Jr.   | 2849 Kaihikapu Street       |                     | Honolulu       | HI              | 96819              | (808) 839-2771           | CEO                     | A-1 A-Lectrician, Inc.                | Construction                |                 |                          |                       | N          | 2008-09-08T16:28:05 | 
| NC20002 | Standard | Abercrombie for Congress                    | 1050 Ala Moana Blvd. #D28   |           | Honolulu     | HI    | 96814    | Kaneko, William        | 1050 Ala Moana Blvd. #D28   |                 | Honolulu     | HI          | 96814          | 808-589-1439         | Attorney              | Honolulu, Hawaii                                  | Endo, Jack Y.          | 1357 Kapiolani Blvd #1005   |                     | Honolulu       | HI              | 96814              | 808-941-4811             | CPA                     | Honolulu, Hawaii                      | Other                       |                 |                          |                       | Y          | 2008-08-14T09:16:11 | 
| NC20247 | Standard | Abercrombie for Congress                    | 1050 Ala Moana Blvd. #D28   |           | Honolulu     | HI    | 96814    | Kaneko, William        | 1050 Ala Moana Blvd. #D28   |                 | Honolulu     | HI          | 96814          | 808-589-1439         | Attorney              | Honolulu, HI                                      | Agbayani, Amefil       | 1357 Kapiolani Blvd #1005   |                     | Honolulu       | HI              | 96814              | 808-941-4811             | CPA                     | Honolulu, HI                          | Other                       |                 |                          |                       | Y          | 2009-02-24T12:58:29 | 
| NC20028 | Standard | Ace Land Surveying LLC                      | 735 Bishop Street           | Suite 330 | Honolulu     | HI    | 96813    | Kea, Kevin K.          | 735 Bishop Street           | Suite 330       | Honolulu     | HI          | 96813          | 521-3990             | President             | Ace Land Surveying LLC                            | Aquino-Lacio, Destiney | 735 Bishop Street           | Suite 330           | Honolulu       | HI              | 96813              | 521-3990                 | Executive Administrator | Ace Land Surveying LLC                | Architect / Engineer        |                 |                          |                       | Y          | 2009-01-28T14:53:15 | 
| NC20302 | Standard | ActBlue Hawaii                              | P.O. Box 441146             |           | Somerville   | MA    | 02144    | Gold, Steven M.        | P.O. Box 441146             |                 | Somerville   | MA          | 02144          | (617) 517-7600       | General Counsel       | ActBlue                                           | Hill, Erin M.          | P.O. Box 441146             |                     | Somerville     | MA              | 02144              | (617) 517-7600           | Executive Director      | ActBlue                               | Other                       |                 |                          |                       | N          | 2011-06-30T23:54:12 | 
| NC20657 | Standard | Adult Foster Homecare Association of Hawaii | 2389 Ahaiki Street          |           | Pearl City   | HI    | 96782    | Lazo, Jocelyn A.       | 2389 Ahaiki Street          |                 | Pearl City   | HI          | 96782          | 808-386-5090         | caregiver             | Pearl City                                        | Lazo, Jocelyn A.       | 2390 Ahaiki Street          |                     | Pearl city     | HI              | 96782              | 808-386-5090             | caregiver               | Pealr city                            | Healthcare / Medical        |                 |                          |                       | N          | 2016-11-09T09:54:56 | 
```