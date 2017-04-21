# 2016 Community Digital Training Resources

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2016-community-digital-training-resources) |
| Metadata | [Link](https://data.austintexas.gov/api/views/87kb-nami) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/87kb-nami/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/87kb-nami/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 87kb-nami |
| Name | 2016 Community Digital Training Resources |
| Created | 2016-10-03T20:10:36Z |
| Publication Date | 2016-10-03T20:41:33Z |

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                           | Data Type | Render Type |
| ======== | =========== | ============================== | ============================== | ========= | =========== |
| Yes      | series tag  | program                        | Program                        | text      | text        |
| Yes      | series tag  | branch_lab                     | Branch/Lab                     | text      | text        |
| Yes      | series tag  | location                       | Location                       | text      | text        |
| Yes      | series tag  | council_district               | Council District               | text      | number      |
| Yes      | series tag  | hours                          | Hours                          | text      | text        |
| Yes      | series tag  | phone                          | Phone                          | text      | text        |
| Yes      | series tag  | on_site_trainer                | On-Site Trainer                | text      | text        |
| Yes      | series tag  | of_machines                    | # of Machines                  | text      | text        |
| Yes      | series tag  | sub_training_programs_offered  | Sub Training Programs Offered  | text      | text        |
| Yes      | series tag  | public_access                  | Public Access?                 | text      | text        |
| Yes      | series tag  | non_english_speaking_languages | Non-English Speaking Languages | text      | text        |
| Yes      | series tag  | disabled_accessibility         | Disabled Accessibility         | text      | text        |
| Yes      | series tag  | last_updated                   | Last Updated                   | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:87kb-nami d:2016-01-01T00:00:00.000Z t:branch_lab="Pleasant Hill Branch" t:phone=512-974-3940 t:location="211 E WIlliam Cannon Dr 78745" t:program="Austin Public Library" t:on_site_trainer="no specific trainer" t:public_access=Yes t:hours="M-Th: 10a-9p; F: 1p-6p; Sa: 10a-5p" t:last_updated=2016- t:council_district=2 t:sub_training_programs_offered="No programming currently offered" t:disabled_accessibility="Braille displays, screen magnification software for visually impaired" t:of_machines=14 t:non_english_speaking_languages="Yes, when Spanish-speaking librarians are available" m:row_number.87kb-nami=1

series e:87kb-nami d:2016-01-01T00:00:00.000Z t:branch_lab="Manchaca Road Branch" t:phone="512 974 8700" t:location="5500 Manchaca Rd 78745" t:program="Austin Public Library" t:on_site_trainer="no specific trainer" t:public_access=Yes t:hours="M-Th: 10a-9p; F: 1p-6p; Sa: 10a-5p" t:last_updated=2016- t:council_district=5 t:sub_training_programs_offered="Connected Youth" t:disabled_accessibility="Braille displays, screen magnification software for visually impaired" t:of_machines=34 t:non_english_speaking_languages="Yes, when Spanish-speaking librarians are available" m:row_number.87kb-nami=2

series e:87kb-nami d:2016-01-01T00:00:00.000Z t:branch_lab="The Henry Flores Learning Center at Meadowbrook" t:phone="515 814 3278" t:location="1201 W Live Oak St, Austin, TX 78704" t:program="Skillpoint Alliance" t:on_site_trainer=Yes t:public_access=Yes t:hours="M-F 8a-4p" t:last_updated=2016- t:council_district=4 t:sub_training_programs_offered="10 Week Empower Computer Proficiency Program: professional development skills (MS Office, Internet, Email, Outlook)" t:disabled_accessibility=Uknown t:of_machines=Uknown t:non_english_speaking_languages=No m:row_number.87kb-nami=3
```

## Meta Commands

```ls
metric m:row_number.87kb-nami p:long l:"Row Number"

entity e:87kb-nami l:"2016 Community Digital Training Resources" t:url=https://data.austintexas.gov/api/views/87kb-nami

property e:87kb-nami t:meta.view v:id=87kb-nami v:averageRating=0 v:name="2016 Community Digital Training Resources"

property e:87kb-nami t:meta.view.owner v:id=xyvj-5d85 v:screenName=jesse.rodriguez v:displayName=jesse.rodriguez

property e:87kb-nami t:meta.view.tableauthor v:id=xyvj-5d85 v:screenName=jesse.rodriguez v:roleName=editor_stories v:displayName=jesse.rodriguez
```

## Top Records

```ls
| program               | branch_lab                                      | location                             | council_district | hours                                                   | phone          | on_site_trainer     | of_machines | sub_training_programs_offered                                                                                                                         | public_access                          | non_english_speaking_languages                      | disabled_accessibility                                                | last_updated | 
| ===================== | =============================================== | ==================================== | ================ | ======================================================= | ============== | =================== | =========== | ===================================================================================================================================================== | ====================================== | =================================================== | ===================================================================== | ============ | 
| Austin Public Library | Pleasant Hill Branch                            | 211 E WIlliam Cannon Dr 78745        | 2                | M-Th: 10a-9p; F: 1p-6p; Sa: 10a-5p                      | 512-974-3940   | no specific trainer | 14          | No programming currently offered                                                                                                                      | Yes                                    | Yes, when Spanish-speaking librarians are available | Braille displays, screen magnification software for visually impaired | 2016-        | 
| Austin Public Library | Manchaca Road Branch                            | 5500 Manchaca Rd 78745               | 5                | M-Th: 10a-9p; F: 1p-6p; Sa: 10a-5p                      | 512 974 8700   | no specific trainer | 34          | Connected Youth                                                                                                                                       | Yes                                    | Yes, when Spanish-speaking librarians are available | Braille displays, screen magnification software for visually impaired | 2016-        | 
| Skillpoint Alliance   | The Henry Flores Learning Center at Meadowbrook | 1201 W Live Oak St, Austin, TX 78704 | 4                | M-F 8a-4p                                               | 515 814 3278   | Yes                 | Uknown      | 10 Week Empower Computer Proficiency Program: professional development skills (MS Office, Internet, Email, Outlook)                                   | Yes                                    | No                                                  | Uknown                                                                | 2016-        | 
| Austin Public Library | Hampton Branch at Oak Hill                      | 5125 Convict Hill Rd 78749           | 8                | M-Th: 10a-9p; F: 1p-6p; Sa: 10a-5p; Classes: Th 2-3pm   | 512 974 9900   | no specific trainer | 13          | Tech Time: Training for mobile and reading devices (Tablets, eReaders, Smartphones etc)                                                               | Yes                                    | Yes, when Spanish-speaking librarians are available | Braille displays, screen magnification software for visually impaired | 2016-        | 
| Austin Free-Net       | Oak Springs Villas                              | 3001 Oak Springs Dr 78702            | 3                | Uknown                                                  | (512) 928-2015 | No                  | 3           | Uknown                                                                                                                                                | Residents Only                         |                                                     | Uknown                                                                | 2016-        | 
| YMCA                  | Southwest Center                                | 6219 Oakclaire Dr. 78753             | 1                | 5a-10p                                                  | 512.891.9622   | Uknown              | Uknown      | Uknown                                                                                                                                                | Yes, with free membership registration | Uknown                                              | Wheel chair accessible                                                | 2016-        | 
| Skillpoint Alliance   | Mendez Middle School                            | 5106 Village Square 78744            | 2                | M-F 8a-4p                                               | 514 814 3278   | Yes                 | Uknown      | 10 Week Empower Computer Proficiency Program: professional development skills (MS Office, Internet, Email, Outlook)                                   | Yes                                    | Yes, Spanish                                        | Wheel chair accessible                                                | 2016-        | 
| Austin Public Library | Twin Oaks Branch                                | 1800 S Fifth St 78704                | 9                | M-Th: 10a-9p; F: 1p-6p; Sa: 10a-5p Classes: Wed. 6-7 PM | 512 974 9980   | no specific trainer | 35          | Tech Time: Training for mobile and reading devices (Tablets, eReaders, Smartphones etc)                                                               | Yes                                    | Yes, when Spanish-speaking librarians are available | Braille displays, screen magnification software for visually impaired | 2016-        | 
| Austin Free-Net       | Trinity Center                                  | 304 E. 7th St.78701                  | 9                | M-F: 9-1                                                | (512) 610-3542 | No                  | 4           | Providing services to Austin?s homeless neighbors, Trinity Center has a mix of open lab time staffed by trainers and volunteers and computer classes. | Trinity Clients Only                   | No                                                  | Uknown                                                                | 2016-        | 
| Austin Public Library | St. John Branch                                 | 7500 Blessing Ave 78752              | 4                | M-Th: 10a-9p; F: 1p-6p; Sa: 10a-4p                      | 512 974 7570   | no specific trainer | 38          | Connected Youth and New Immigrants Center Resource Site                                                                                               | Yes                                    | Yes, when Spanish-speaking librarians are available | Braille displays, screen magnification software for visually impaired | 2016-        | 
```