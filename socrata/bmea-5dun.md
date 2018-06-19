# Bills Signed by Governor Kitzhaber (2012)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bills-signed-by-governor-kitzhaber-2012-ea0aa) |
| Metadata | [Link](https://data.oregon.gov/api/views/bmea-5dun) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/bmea-5dun/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/bmea-5dun/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | bmea-5dun |
| Name | Bills Signed by Governor Kitzhaber (2012) |
| Tags | bills, governor, signed, legislature, legislative, kitzhaber, 2012, session |
| Created | 2012-02-28T17:30:56Z |
| Publication Date | 2012-04-13T23:19:21Z |

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag  | measure_number           | Measure Number           | url       | url         |
| Yes      | series tag  | signed_or_vetoed         | Signed or Vetoed         | url       | url         |
| Yes      | series tag  | date                     | Date                     | html      | html        |
| Yes      | series tag  | relating_to_clause       | Relating to clause       | html      | html        |
| Yes      | series tag  | link_to_more_information | Link to more information | url       | url         |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:bmea-5dun d:2012-01-01T00:00:00.000Z t:relating_to_clause="<p>Relating to medical imaging;</p>" t:measure_number=http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4008.en.pdf t:date=<p>02/27/2012</p> m:row_number.bmea-5dun=1

series e:bmea-5dun d:2012-01-01T00:00:00.000Z t:relating_to_clause="<p>Relating to the impaired health professional program;</p>" t:measure_number=http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4009.en.pdf t:date=<p>02/27/2012</p> m:row_number.bmea-5dun=2

series e:bmea-5dun d:2012-01-01T00:00:00.000Z t:relating_to_clause="<p>Relating to Central Background Registry;</p>" t:measure_number=http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4024.en.pdf t:date=<p>02/27/2012</p> m:row_number.bmea-5dun=3
```

## Meta Commands

```ls
metric m:row_number.bmea-5dun p:long l:"Row Number"

entity e:bmea-5dun l:"Bills Signed by Governor Kitzhaber (2012)" t:url=https://data.oregon.gov/api/views/bmea-5dun

property e:bmea-5dun t:meta.view v:id=bmea-5dun v:averageRating=0 v:name="Bills Signed by Governor Kitzhaber (2012)"

property e:bmea-5dun t:meta.view.owner v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:displayName="Linda Morrell"

property e:bmea-5dun t:meta.view.tableauthor v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:roleName=editor v:displayName="Linda Morrell"
```

## Top Records

```ls
| measure_number                                                               | signed_or_vetoed | date       | relating_to_clause                                                    | link_to_more_information                                                        | 
| ============================================================================ | ================ | ========== | ===================================================================== | =============================================================================== | 
| [http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4008.en.pdf, HB 4008] | [null, null]     | 02/27/2012 | Relating to medical imaging;                                          | [null, null]                                                                    | 
| [http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4009.en.pdf, HB 4009] | [null, null]     | 02/27/2012 | Relating to the impaired health professional program;                 | [null, null]                                                                    | 
| [http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4024.en.pdf, HB4024]  | [null, null]     | 02/27/2012 | Relating to Central Background Registry;                              | [null, null]                                                                    | 
| [http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4034.en.pdf, HB4034]  | [null, null]     | 02/27/2012 | Relating to prompt progress payments on public improvement contracts; | [null, null]                                                                    | 
| [http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4068.en.pdf, HB4068]  | [null, null]     | 02/27/2012 | Relating to food banks;                                               | [null, null]                                                                    | 
| [http://www.leg.state.or.us/12reg/measpdf/hb4100.dir/hb4117.en.pdf, HB4117]  | [null, null]     | 02/27/2012 | Relating to funeral products;                                         | [null, null]                                                                    | 
| [http://www.leg.state.or.us/12reg/measpdf/sb1500.dir/sb1535.en.pdf, SB1535]  | [null, null]     | 02/27/2012 | Relating to use of master form instruments;                           | [null, null]                                                                    | 
| [http://www.leg.state.or.us/12reg/measpdf/sb1500.dir/sb1580.en.pdf, SB1580]  | [null, null]     | 03/02/2012 | Relating to health care delivery;                                     | [http://www.youtube.com/watch?v=AteWtyxiuV0&feature=youtu.be, Watch the video.] | 
| [http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4011.en.pdf, HB4011]  | [null, null]     | 03/05/2012 | Relating to proof of treatment for substance abuse;                   | [null, null]                                                                    | 
| [http://www.leg.state.or.us/12reg/measpdf/hb4000.dir/hb4013.en.pdf, HB4013]  | [null, null]     | 03/05/2012 | Relating to accelerated college credit programs;                      | [null, null]                                                                    | 
```