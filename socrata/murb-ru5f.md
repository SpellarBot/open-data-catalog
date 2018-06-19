# Bills Signed By Governor Kitzhaber 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bills-signed-by-governor-kitzhaber-2014-fb2b7) |
| Metadata | [Link](https://data.oregon.gov/api/views/murb-ru5f) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/murb-ru5f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/murb-ru5f/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | murb-ru5f |
| Name | Bills Signed By Governor Kitzhaber 2014 |
| Category | Administrative |
| Created | 2014-02-27T19:02:07Z |
| Publication Date | 2015-01-21T00:30:37Z |

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type     | Render Type   |
| ======== | =========== | ================== | ================== | ============= | ============= |
| Yes      | series tag  | measure_number     | Measure Number     | url           | url           |
| Yes      | series tag  | signed_or_vetoed   | Signed or Vetoed   | html          | html          |
| Yes      | series tag  | links              | Links              | url           | url           |
| Yes      | time        | date               | Date               | calendar_date | calendar_date |
| Yes      | series tag  | relating_to_clause | Relating to clause | html          | html          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:murb-ru5f d:2014-02-26T00:00:00.000Z t:relating_to_clause="<p>Relating to the Oregon Ocean Science Trust;</p>" t:signed_or_vetoed=<p>Signed</p> t:measure_number=https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/SB1545 m:row_number.murb-ru5f=1

series e:murb-ru5f d:2014-02-26T00:00:00.000Z t:relating_to_clause="<p>Relating to vessel ocean Dungeness crab permits; creating new provisions;</p>" t:signed_or_vetoed=<p>Signed</p> t:measure_number=https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/HB4049 m:row_number.murb-ru5f=2

series e:murb-ru5f d:2014-02-26T00:00:00.000Z t:relating_to_clause="<p>Relating to entrepreneurial development;</p>" t:signed_or_vetoed=<p>Signed</p> t:measure_number=https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/SB1563 m:row_number.murb-ru5f=3
```

## Meta Commands

```ls
metric m:row_number.murb-ru5f p:long l:"Row Number"

entity e:murb-ru5f l:"Bills Signed By Governor Kitzhaber  2014" t:url=https://data.oregon.gov/api/views/murb-ru5f

property e:murb-ru5f t:meta.view v:id=murb-ru5f v:category=Administrative v:averageRating=0 v:name="Bills Signed By Governor Kitzhaber  2014"

property e:murb-ru5f t:meta.view.owner v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:displayName="Linda Morrell"

property e:murb-ru5f t:meta.view.tableauthor v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:roleName=editor v:displayName="Linda Morrell"
```

## Top Records

```ls
| measure_number                                                                      | signed_or_vetoed | links        | date                | relating_to_clause                                                                   | 
| =================================================================================== | ================ | ============ | =================== | ==================================================================================== | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/SB1545, SB 1545] | Signed           | [null, null] | 2014-02-26T00:00:00 | Relating to the Oregon Ocean Science Trust;                                          | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/HB4049, HB 4049] | Signed           | [null, null] | 2014-02-26T00:00:00 | Relating to vessel ocean Dungeness crab permits; creating new provisions;            | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/SB1563, SB 1563] | Signed           | [null, null] | 2014-02-26T00:00:00 | Relating to entrepreneurial development;                                             | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/SB1584, SB 1584] | Signed           | [null, null] | 2014-02-26T00:00:00 | Relating to applications for exotic animal permits;                                  | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/HB4007, HB 4007] | Signed           | [null, null] | 2014-03-03T00:00:00 | Relating to continuity in the enrollment of nonresident students;                    | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/HB4008, HB 4008] | Signed           | [null, null] | 2014-03-03T00:00:00 | Relating to distributions of state funds for the education of youths in confinement; | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/HB4039, HB 4039] | Signed           | [null, null] | 2014-03-03T00:00:00 | Relating to exemption from property taxation for low-income housing;                 | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/HB4081, HB 4081] | Signed           | [null, null] | 2014-03-03T00:00:00 | Relating to regulation of charitable organizations;                                  | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/HB4085, HB 4085] | Signed           | [null, null] | 2014-03-03T00:00:00 | Relating to colorectal cancer screening;                                             | 
| [https://olis.leg.state.or.us/liz/2014R1/Downloads/MeasureDocument/HB4090, HB 4090] | Signed           | [null, null] | 2014-03-03T00:00:00 | Relating to school food programs;                                                    | 
```