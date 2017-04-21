# Table 3.22 HEADCOUNT ENROLLMENT AT THE UNIVERSITY OF HAWAII, BY CAMPUS FALL 1997 TO 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-3-22-headcount-enrollment-at-the-university-of-hawaii-by-campus-fall-1997-to-2013) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rjsa-twkk) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rjsa-twkk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rjsa-twkk/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rjsa-twkk |
| Name | Table 3.22 HEADCOUNT ENROLLMENT AT THE UNIVERSITY OF HAWAII, BY CAMPUS FALL 1997 TO 2014 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | enrollment |
| Created | 2012-08-27T20:12:21Z |
| Publication Date | 2015-10-27T00:16:12Z |

## Description

* Fall headcount of credit students, includes special students (early admits and concurrent registrants) for all years shown																
* Unclassified at UH Manoa includes no data on educational level.																
     Source:  University of Hawai'i, Institutional Research and Analysis Office, records.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                         | Data Type | Render Type |
| ======== | ============== | =========================== | ============================ | ========= | =========== |
| Yes      | time           | year                        | Year                         | number    | text        |
| Yes      | numeric metric | total_all_campuses          | Total, all campuses          | number    | number      |
| Yes      | numeric metric | uh_at_manoa_total           | UH at Manoa (Total)          | number    | number      |
| Yes      | numeric metric | uh_at_manoa_under_graduates | UH at Manoa(Undergraduates)  | number    | number      |
| Yes      | numeric metric | uh_at_manoa_graduates       | UH at Manoa (Graduates)      | number    | number      |
| Yes      | numeric metric | uh_at_mahoa_unclassified    | UH at Manoa(Unclassified)    | number    | number      |
| Yes      | numeric metric | uh_at_hilo                  | UH at Hilo                   | number    | number      |
| Yes      | numeric metric | uh_at_west_oahu             | UH at West Oahu              | number    | number      |
| Yes      | numeric metric | uh_community_colleges_total | UH Community Colleges(Total) | number    | number      |
| Yes      | numeric metric | honolulu_community_college  | Honolulu Community College   | number    | number      |
| Yes      | numeric metric | kapiolani_community_college | Kapiolani Community College  | number    | number      |
| Yes      | numeric metric | leeward_community_college   | Leeward Community College    | number    | number      |
| Yes      | numeric metric | windward_community_college  | Windward Community College   | number    | number      |
| Yes      | numeric metric | hawaii_community_college    | Hawaii Community College     | number    | number      |
| Yes      | numeric metric | kauai_community_college     | Kauai Community College      | number    | number      |
| Yes      | numeric metric | maui_community_college      | Maui Community College       | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rjsa-twkk d:1997-01-01T00:00:00.000Z m:uh_community_colleges_total=24899 m:uh_at_mahoa_unclassified=1069 m:leeward_community_college=5936 m:kapiolani_community_college=7189 m:uh_at_manoa_under_graduates=11782 m:maui_community_college=2787 m:uh_at_west_oahu=648 m:uh_at_manoa_total=17365 m:hawaii_community_college=2221 m:uh_at_manoa_graduates=4514 m:uh_at_hilo=2639 m:total_all_campuses=45551 m:kauai_community_college=1283 m:windward_community_college=1513 m:honolulu_community_college=3970

series e:rjsa-twkk d:1998-01-01T00:00:00.000Z m:uh_community_colleges_total=24909 m:uh_at_mahoa_unclassified=1005 m:leeward_community_college=5765 m:kapiolani_community_college=7236 m:uh_at_manoa_under_graduates=11500 m:maui_community_college=2849 m:uh_at_west_oahu=685 m:uh_at_manoa_total=17013 m:hawaii_community_college=2308 m:uh_at_manoa_graduates=4508 m:uh_at_hilo=2730 m:total_all_campuses=45337 m:kauai_community_college=1136 m:windward_community_college=1491 m:honolulu_community_college=4124

series e:rjsa-twkk d:1999-01-01T00:00:00.000Z m:uh_community_colleges_total=25390 m:uh_at_mahoa_unclassified=1413 m:leeward_community_college=5570 m:kapiolani_community_college=7254 m:uh_at_manoa_under_graduates=11458 m:maui_community_college=2862 m:uh_at_west_oahu=687 m:uh_at_manoa_total=17612 m:hawaii_community_college=2279 m:uh_at_manoa_graduates=4741 m:uh_at_hilo=2790 m:total_all_campuses=46479 m:kauai_community_college=1142 m:windward_community_college=1514 m:honolulu_community_college=4769
```

## Meta Commands

```ls
metric m:total_all_campuses p:integer l:"Total, all campuses" t:dataTypeName=number

metric m:uh_at_manoa_total p:integer l:"UH at Manoa (Total)" t:dataTypeName=number

metric m:uh_at_manoa_under_graduates p:integer l:"UH at Manoa(Undergraduates)" t:dataTypeName=number

metric m:uh_at_manoa_graduates p:integer l:"UH at Manoa (Graduates)" t:dataTypeName=number

metric m:uh_at_mahoa_unclassified p:integer l:"UH at Manoa(Unclassified)" t:dataTypeName=number

metric m:uh_at_hilo p:integer l:"UH at Hilo" t:dataTypeName=number

metric m:uh_at_west_oahu p:integer l:"UH at West Oahu" t:dataTypeName=number

metric m:uh_community_colleges_total p:integer l:"UH Community Colleges(Total)" t:dataTypeName=number

metric m:honolulu_community_college p:integer l:"Honolulu Community College" t:dataTypeName=number

metric m:kapiolani_community_college p:integer l:"Kapiolani Community College" t:dataTypeName=number

metric m:leeward_community_college p:integer l:"Leeward Community College" t:dataTypeName=number

metric m:windward_community_college p:integer l:"Windward Community College" t:dataTypeName=number

metric m:hawaii_community_college p:integer l:"Hawaii Community College" t:dataTypeName=number

metric m:kauai_community_college p:integer l:"Kauai Community College" t:dataTypeName=number

metric m:maui_community_college p:integer l:"Maui Community College" t:dataTypeName=number

entity e:rjsa-twkk l:"Table 3.22 HEADCOUNT ENROLLMENT AT THE UNIVERSITY OF HAWAII, BY CAMPUS  FALL 1997 TO 2014" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/rjsa-twkk

property e:rjsa-twkk t:meta.view v:id=rjsa-twkk v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/databook v:averageRating=0 v:name="Table 3.22 HEADCOUNT ENROLLMENT AT THE UNIVERSITY OF HAWAII, BY CAMPUS  FALL 1997 TO 2014" v:attribution="Department of Economic Development and Tourism"

property e:rjsa-twkk t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:rjsa-twkk t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:rjsa-twkk t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | total_all_campuses | uh_at_manoa_total | uh_at_manoa_under_graduates | uh_at_manoa_graduates | uh_at_mahoa_unclassified | uh_at_hilo | uh_at_west_oahu | uh_community_colleges_total | honolulu_community_college | kapiolani_community_college | leeward_community_college | windward_community_college | hawaii_community_college | kauai_community_college | maui_community_college | 
| ==== | ================== | ================= | =========================== | ===================== | ======================== | ========== | =============== | =========================== | ========================== | =========================== | ========================= | ========================== | ======================== | ======================= | ====================== | 
| 1997 | 45551              | 17365             | 11782                       | 4514                  | 1069                     | 2639       | 648             | 24899                       | 3970                       | 7189                        | 5936                      | 1513                       | 2221                     | 1283                    | 2787                   | 
| 1998 | 45337              | 17013             | 11500                       | 4508                  | 1005                     | 2730       | 685             | 24909                       | 4124                       | 7236                        | 5765                      | 1491                       | 2308                     | 1136                    | 2849                   | 
| 1999 | 46479              | 17612             | 11458                       | 4741                  | 1413                     | 2790       | 687             | 25390                       | 4769                       | 7254                        | 5570                      | 1514                       | 2279                     | 1142                    | 2862                   | 
| 2000 | 44579              | 17263             | 11151                       | 4567                  | 1545                     | 2874       | 665             | 23777                       | 4487                       | 6760                        | 5259                      | 1451                       | 2090                     | 1052                    | 2678                   | 
| 2001 | 45994              | 17532             | 11485                       | 4536                  | 1511                     | 2913       | 740             | 24809                       | 4653                       | 7081                        | 5562                      | 1554                       | 2075                     | 1185                    | 2699                   | 
| 2002 | 48173              | 18706             | 12242                       | 4834                  | 1630                     | 3040       | 834             | 25593                       | 4478                       | 7041                        | 5918                      | 1761                       | 2182                     | 1224                    | 2989                   | 
| 2003 | 50317              | 19863             | 13069                       | 5167                  | 1627                     | 3300       | 810             | 26344                       | 4238                       | 7491                        | 6201                      | 1873                       | 2346                     | 1210                    | 2985                   | 
| 2004 | 50569              | 20549             | 13693                       | 5382                  | 1474                     | 3288       | 834             | 25898                       | 4336                       | 7174                        | 6060                      | 1775                       | 2440                     | 1117                    | 2996                   | 
| 2005 | 50157              | 20644             | 13826                       | 5409                  | 1409                     | 3422       | 858             | 25233                       | 4183                       | 7289                        | 5709                      | 1713                       | 2377                     | 1059                    | 2903                   | 
| 2006 | 49990              | 20357             | 13542                       | 5358                  | 1457                     | 3507       | 866             | 25260                       | 4143                       | 7272                        | 5746                      | 1781                       | 2358                     | 1119                    | 2841                   | 
```