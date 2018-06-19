# Professional Services Awards

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/professional-services-awards) |
| Metadata | [Link](https://data.hawaii.gov/api/views/4g8j-cesp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/4g8j-cesp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/4g8j-cesp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 4g8j-cesp |
| Name | Professional Services Awards |
| Created | 2015-04-20T23:36:16Z |
| Publication Date | 2015-04-20T23:37:53Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | category        | category        | text      | text        |
| Yes      | series tag     | services        | services        | text      | text        |
| Yes      | series tag     | awardee         | awardee         | text      | text        |
| No       |                | contractdate    | contractdate    | text      | text        |
| Yes      | numeric metric | awardamount     | awardamount     | number    | number      |
| Yes      | series tag     | commentsammount | commentsammount | text      | text        |
| Yes      | series tag     | official        | official        | text      | text        |
| Yes      | series tag     | agency          | agency          | text      | text        |
| Yes      | series tag     | relationship    | relationship    | text      | text        |
| Yes      | series tag     | contact         | contact         | text      | text        |
| Yes      | series tag     | phone           | phone           | text      | text        |
| Yes      | series tag     | email           | email           | text      | text        |
| Yes      | series tag     | name1           | name1           | text      | text        |
| Yes      | series tag     | name2           | name2           | text      | text        |
| Yes      | series tag     | name3           | name3           | text      | text        |
| Yes      | series tag     | name4           | name4           | text      | text        |
| Yes      | series tag     | name5           | name5           | text      | text        |
| Yes      | series tag     | name6           | name6           | text      | text        |
| Yes      | series tag     | name7           | name7           | text      | text        |
| Yes      | series tag     | name8           | name8           | text      | text        |
| Yes      | series tag     | name9           | name9           | text      | text        |
| Yes      | series tag     | name10          | name10          | text      | text        |
| Yes      | series tag     | review1         | review1         | text      | text        |
| Yes      | series tag     | review2         | review2         | text      | text        |
| Yes      | series tag     | review3         | review3         | text      | text        |
| Yes      | series tag     | review4         | review4         | text      | text        |
| Yes      | series tag     | review5         | review5         | text      | text        |
| Yes      | series tag     | review6         | review6         | text      | text        |
| Yes      | series tag     | review7         | review7         | text      | text        |
| Yes      | series tag     | review8         | review8         | text      | text        |
| Yes      | series tag     | review9         | review9         | text      | text        |
| Yes      | series tag     | review10        | review10        | text      | text        |
| Yes      | series tag     | selection1      | selection1      | text      | text        |
| Yes      | series tag     | selection2      | selection2      | text      | text        |
| Yes      | series tag     | selection3      | selection3      | text      | text        |
| Yes      | series tag     | selection4      | selection4      | text      | text        |
| Yes      | series tag     | selection5      | selection5      | text      | text        |
| Yes      | series tag     | selection6      | selection6      | text      | text        |
| Yes      | series tag     | selection7      | selection7      | text      | text        |
| Yes      | series tag     | selection8      | selection8      | text      | text        |
| Yes      | series tag     | selection9      | selection9      | text      | text        |
| Yes      | series tag     | selection10     | selection10     | text      | text        |
| No       |                | postingdate     | postingdate     | text      | text        |
| No       |                | modifieddate    | modifieddate    | text      | text        |
| Yes      | series tag     | modifiedreason  | modifiedreason  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = contractdate,postingdate,modifieddate
```

## Data Commands

```ls
series e:4g8j-cesp d:2015-04-20T16:36:26.000Z t:phone=808-973-1123 t:services="Professional services, Civil Engineering design.  Molokai Irrigation System, Concrete Flume and Miscellaneous Improvements, Molokai, Hawaii" t:awardee="HDR Engineering, Inc" t:agency="Department of Agriculture" t:contact="Gordon Chong" t:relationship=NONE t:review2="Glenn Okamoto" t:review3="Gordon Chong" t:category="Architecture and Engineering" t:name3="bowers & kubota" t:review1="Brian Kau" t:email=Gordon.W.Chong@hawaii.gov t:official="Scott E. Enright, Chairperson" t:name1=HDR t:selection2="Glenn Okamoto" t:name2="wilson okamoto" t:selection3="Gordon Chong" t:selection1="Brian Kau" m:awardamount=190000

series e:4g8j-cesp d:2015-04-20T16:36:26.000Z t:services="A/E Design Services for Electrical Upgrade and Infrastructure Upgrade, Building 2207, University of Hawaii Maui College, Project No. SW-13-5374" t:phone=808-956-8687 t:awardee="GYA Architects, Inc" t:agency="University of Hawaii" t:contact="Bruce Isaacs" t:relationship=NONE t:review2="Doris Wong" t:review3="Denise Yamamoto-Yoshimori" t:category="Architecture and Engineering" t:name3="Lou Chan & Associates, Inc." t:review1="Blake Araki" t:email=bisaacs@hawaii.edu t:review4="Lo-Li Chih" t:review5="Bruce Teramoto" t:official="Ryan Kurashige, Manager" t:name1="GYA Architects, Inc." t:selection2="Shawn Kodani" t:name2="Pacific Architects, Inc." t:selection3="Ray Teramae" t:selection1="Darren Ito" m:awardamount=235589

series e:4g8j-cesp d:2015-04-20T16:36:26.000Z t:services="A/E Design Services to Remove and Replace Asbestos Containing Roof Materials, Buildings 8816 Print Shop, 8818 O&M, and 8812 Pipe Fitters, Honolulu Community College, Project No. SW-14-1329" t:phone=808-956-8687 t:awardee="Lou Chan & Associates, Inc" t:agency="University of Hawaii" t:contact="Bruce Isaacs" t:relationship=NONE t:review2="Brian Kashiwaeda" t:review3="Blake Araki" t:category="Architecture and Engineering" t:name3="Design Partners, Inc." t:review1="Bruce Teramoto" t:review6="Loren Lau" t:email=bisaacs@hawaii.edu t:review4="Doris Wong" t:review5="Lo-Li Chih" t:official="Ryan Kurashige, Manager" t:name1="Lou Chan & Associates, Inc." t:selection2="Herbert Ishida" t:name2="Awa & Associates, LLC" t:selection3="Denise Yoshimori-Yamamoto" t:selection1="Darren Ito" m:awardamount=70052
```

## Meta Commands

```ls
metric m:awardamount p:integer l:awardamount t:dataTypeName=number

entity e:4g8j-cesp l:"Professional Services Awards" t:url=https://data.hawaii.gov/api/views/4g8j-cesp

property e:4g8j-cesp t:meta.view v:id=4g8j-cesp v:averageRating=0 v:name="Professional Services Awards"

property e:4g8j-cesp t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:4g8j-cesp t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| :updated_at | category                     | services                                                                                                                                                                                                                                   | awardee                                           | contractdate            | awardamount | commentsammount                            | official                        | agency                                                   | relationship | contact          | phone        | email                        | name1                                           | name2                      | name3                             | name4                                             | name5                     | name6 | name7            | name8    | name9 | name10 | review1        | review2          | review3                   | review4    | review5        | review6        | review7 | review8 | review9 | review10 | selection1     | selection2     | selection3                | selection4 | selection5 | selection6 | selection7 | selection8 | selection9 | selection10 | postingdate                    | modifieddate                   | modifiedreason                                                                                             | 
| =========== | ============================ | ========================================================================================================================================================================================================================================== | ================================================= | ======================= | =========== | ========================================== | =============================== | ======================================================== | ============ | ================ | ============ | ============================ | =============================================== | ========================== | ================================= | ================================================= | ========================= | ===== | ================ | ======== | ===== | ====== | ============== | ================ | ========================= | ========== | ============== | ============== | ======= | ======= | ======= | ======== | ============== | ============== | ========================= | ========== | ========== | ========== | ========== | ========== | ========== | =========== | ============================== | ============================== | ========================================================================================================== | 
| 1429547786  | Architecture and Engineering | Professional services, Civil Engineering design. Molokai Irrigation System, Concrete Flume and Miscellaneous Improvements, Molokai, Hawaii                                                                                                 | HDR Engineering, Inc                              | 2014/09/25 00:00:00 HST | 190000      |                                            | Scott E. Enright, Chairperson   | Department of Agriculture                                | NONE         | Gordon Chong     | 808-973-1123 | Gordon.W.Chong@hawaii.gov    | HDR                                             | wilson okamoto             | bowers & kubota                   |                                                   |                           |       |                  |          |       |        | Brian Kau      | Glenn Okamoto    | Gordon Chong              |            |                |                |         |         |         |          | Brian Kau      | Glenn Okamoto  | Gordon Chong              |            |            |            |            |            |            |             | 2014/10/13 08:26:31.340824 HST | 2014/10/13 08:30:5.237098 HST  |                                                                                                            | 
| 1429547786  | Architecture and Engineering | A/E Design Services for Electrical Upgrade and Infrastructure Upgrade, Building 2207, University of Hawaii Maui College, Project No. SW-13-5374                                                                                            | GYA Architects, Inc                               | 2014/09/30 00:00:00 HST | 235589      |                                            | Ryan Kurashige, Manager         | University of Hawaii                                     | NONE         | Bruce Isaacs     | 808-956-8687 | bisaacs@hawaii.edu           | GYA Architects, Inc.                            | Pacific Architects, Inc.   | Lou Chan & Associates, Inc.       |                                                   |                           |       |                  |          |       |        | Blake Araki    | Doris Wong       | Denise Yamamoto-Yoshimori | Lo-Li Chih | Bruce Teramoto |                |         |         |         |          | Darren Ito     | Shawn Kodani   | Ray Teramae               |            |            |            |            |            |            |             | 2014/10/01 16:05:31.432402 HST | 2014/10/01 16:05:31.431049 HST |                                                                                                            | 
| 1429547786  | Architecture and Engineering | A/E Design Services to Remove and Replace Asbestos Containing Roof Materials, Buildings 8816 Print Shop, 8818 O&M, and 8812 Pipe Fitters, Honolulu Community College, Project No. SW-14-1329                                               | Lou Chan & Associates, Inc                        | 2014/09/30 00:00:00 HST | 70052       |                                            | Ryan Kurashige, Manager         | University of Hawaii                                     | NONE         | Bruce Isaacs     | 808-956-8687 | bisaacs@hawaii.edu           | Lou Chan & Associates, Inc.                     | Awa & Associates, LLC      | Design Partners, Inc.             |                                                   |                           |       |                  |          |       |        | Bruce Teramoto | Brian Kashiwaeda | Blake Araki               | Doris Wong | Lo-Li Chih     | Loren Lau      |         |         |         |          | Darren Ito     | Herbert Ishida | Denise Yoshimori-Yamamoto |            |            |            |            |            |            |             | 2014/10/01 16:14:42.898342 HST | 2014/10/01 16:14:42.897000 HST |                                                                                                            | 
| 1429547786  | Architecture and Engineering | A/E Design Services for Saunders Hall Exterior Repairs and Reroof, University of Hawaii at Manoa, Project No. UHM 13-541-310                                                                                                               | WTN Architecture, Inc.                            | 2014/09/30 00:00:00 HST | 268276      |                                            | Ryan Kurashige, Manager         | University of Hawaii                                     | NONE         | Colleen Bird     | 808-956-8687 | crmbird@hawaii.edu           | WTN Architecture, Inc.                          | Fung Associates, Inc.      | Lou Chan & Associates, Inc.       |                                                   |                           |       |                  |          |       |        | Loren Lau      | Brian Kashiwaeda | Blake Araki               | Doris Wong | Lo-Li Chih     | Bruce Teramoto |         |         |         |          | Allan Sawai    | Alan Tarumoto  | Dean Uehara               |            |            |            |            |            |            |             | 2014/10/01 16:22:10.996416 HST | 2014/10/01 16:22:10.995078 HST |                                                                                                            | 
| 1429547786  | Accounting and Budget        | Audits of the financial statements of HSDC Capital Fund, LLC, a limited liability company of which HSDC (an attached agency of DBEDT) is the sole and managing member, for the years ending December 31, 2011, 2012, 2013, 2014, and 2015. | Kobayashi, Kanetoku, Doi, Lum & Yasuda CPAs LLC   | 2014/06/13 00:00:00 HST | 46859       | Contractor's error in calculation of fees. | Richard C. Lim, DBEDT Director  | Department of Business, Economic Development and Tourism | NONE         | Susan Gray-Ellis | 808-587-9002 | sgray-ellis@dbedt.hawaii.gov | Kobayashi, Kanetoku, Doi, Lum & Yasuda CPAs LLC | PKF Pacific Hawaii LLP     |                                   |                                                   |                           |       |                  |          |       |        | Phil Bossert   | Karl Fooks       | Jon Wallenstrom           |            |                |                |         |         |         |          | Phil Bossert   | Karl Fooks     | Jon Wallenstrom           |            |            |            |            |            |            |             | 2014/06/13 11:51:8.377026 HST  | 2014/10/06 13:22:44.908509 HST | 9/12/14 - Contract No. 63288 encumbered. 7/11/14 - Amended Contractor name to remove apostrophe after CPA. | 
| 1429547786  | Architecture and Engineering | A/E Design Services for the Administration and Allied Health Facility, University of Hawaii West Oahu, Project No. UH WO 13-828                                                                                                            | KYA Design Group, Inc.                            | 2014/07/24 00:00:00 HST | 383133      |                                            | Ryan Kurashige, Manager         | University of Hawaii                                     | NONE         | Michele Sonoda   | 808-956-8687 | mssonoda@hawaii.edu          | KYA Design Group, Inc.                          | John Hara Associates, Inc. | Benjamin Woo Architects           |                                                   |                           |       |                  |          |       |        | Loren Lau      | Brian Kashiwaeda | Blake Araki               | Doris Wong | Lo-Li Chih     | Bruce Teramoto |         |         |         |          | Loren Lau      | Bruce Teramoto | Denise Yoshimori-Yamamoto |            |            |            |            |            |            |             | 2014/07/24 17:10:5.366439 HST  | 2014/07/24 17:10:5.365104 HST  |                                                                                                            | 
| 1429547786  | Architecture and Engineering | A/E Design Services for Bilger Addition, Replace Electrical Service Equipment, University of Hawaii at Manoa, Project No. UHM 13-541-450                                                                                                   | MK Engineers, Ltd.                                | 2015/03/23 00:00:00 HST | 109598      |                                            | Ryan Kurashige, Manager         | University of Hawaii                                     | NONE         | Glen Shiraki     | 808-956-8687 | gshiraki@hawaii.edu          | MK Engineers, Ltd                               | Bennett Engineers, Inc.    | Ronald N.S. Ho & Associates, Inc. |                                                   |                           |       |                  |          |       |        | Blake Araki    | Doris Wong       | Denise Yamamoto-Yoshimori | Lo-Li Chih | Bruce Teramoto |                |         |         |         |          | Mark Nishimoto | Teri Wong      | Vernon Shiroma            |            |            |            |            |            |            |             | 2015/03/24 11:45:27.085772 HST | 2015/03/24 11:45:27.083069 HST |                                                                                                            | 
| 1429547786  | Architecture and Engineering | A/E Design Services for 8803 Auto Body Reroof, Honolulu Community College, Project No. SW-15-1333                                                                                                                                          | Pacific Architects, Inc.                          | 2015/03/23 00:00:00 HST | 67305       |                                            | Ryan Kurashige, Manager         | University of Hawaii                                     | NONE         | Bruce Isaacs     | 808-956-8687 | bisaacs@hawaii.edu           | Pacific Architects, Inc.                        | Ken Kajiwara, Architects   | Fung Associates, Inc.             |                                                   |                           |       |                  |          |       |        | Blake Araki    | Doris Wong       | Denise Yamamoto-Yoshimori | Lo-Li Chih | Bruce Teramoto |                |         |         |         |          | Darren Ito     | Ray Teramae    | Rodney Yim                |            |            |            |            |            |            |             | 2015/03/24 11:49:31.962999 HST | 2015/03/24 11:49:31.961680 HST |                                                                                                            | 
| 1429547786  | Education                    | Education and Training services in grant training and support and community economic development training                                                                                                                                  | Insight Center for Community Economic Development | 2015/04/20 00:00:00 HST | 100000      |                                            | Jobie Masagatani, Chairman, HHC | Department of Hawaiian Home Lands                        | NONE         | Gigi Cairel      | 808-620-9461 | gigi.o.cairel@hawaii.gov     | Hiilei Aloha LLC                                | HACBED                     | HANO                              | Insight Center for Community Economic Development | Hawaiian Community Assets | CNHA  | Honua Consulting | 3 others |       |        | Julie Cachola  | Kamana'o Mills   | Bob Freitas               |            |                |                |         |         |         |          | Julie Cachola  | Bob Freitas    | Kamana'o Mills            |            |            |            |            |            |            |             | 2015/04/20 10:11:23.771001 HST | 2015/04/20 10:11:23.769653 HST |                                                                                                            | 
| 1429547786  | Architecture and Engineering | Remove and Replace Asbestos Containing Materials, Building 391 Electricity, Hawaii Community College, Project No. SW-14-9079                                                                                                               | HiArch, LLC                                       | 2014/05/29 00:00:00 HST | 3826        |                                            | Ryan Kurashige, Manager         | University of Hawaii                                     | NONE         | Bruce Isaacs     | 808-956-8687 | bisaacs@hawaii.edu           | HiArch, LLC                                     | Fleming & Associates, LLC  | Excel Design, Inc                 |                                                   |                           |       |                  |          |       |        | Loren Lau      | Brian Kashiwaeda | Blake Araki               | Doris Wong | Lo-Li Chih     |                |         |         |         |          | Rodney Yim     | Darren Ito     | Denise Yoshimori          |            |            |            |            |            |            |             | 2014/06/02 10:46:5.831626 HST  | 2014/06/02 10:46:59.830456 HST |                                                                                                            | 
```