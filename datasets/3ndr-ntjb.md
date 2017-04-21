# Bills Signed By Governor Brown 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bills-signed-by-governor-brown-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/3ndr-ntjb) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/3ndr-ntjb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/3ndr-ntjb/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 3ndr-ntjb |
| Name | Bills Signed By Governor Brown 2016 |
| Attribution | Adminstrative Services |
| Category | Administrative |
| Tags | bills signed governor brown 2016 |
| Created | 2016-02-12T23:42:20Z |
| Publication Date | 2016-04-11T17:51:06Z |

## Description

Bills Signed By Governor Brown 2016

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | measure_number     | Measure Number     | url       | url         |
| Yes      | series tag  | signed_or_vetoed   | Signed or Vetoed   | text      | text        |
| Yes      | series tag  | links              | Links              | url       | url         |
| Yes      | time        | date               | Date               | text      | text        |
| Yes      | series tag  | relating_to_clause | Relating to clause | text      | text        |
```

## Time Field

```ls
Value = date
Format & Zone = MM/dd/yyyy
```

## Data Commands

```ls
series e:3ndr-ntjb d:2016-02-23T00:00:00.000Z t:relating_to_clause="Relating to speed limits on highways that traverse state lines" t:signed_or_vetoed=Signed t:measure_number=https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/HB4047/Enrolled m:row_number.3ndr-ntjb=1

series e:3ndr-ntjb d:2016-02-29T00:00:00.000Z t:relating_to_clause="Relating  to  voting  methods  for  cooperative  corporations;" t:signed_or_vetoed=Signed t:measure_number=https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/HB4038/Enrolled m:row_number.3ndr-ntjb=2

series e:3ndr-ntjb d:2016-02-29T00:00:00.000Z t:relating_to_clause="Relating to brewery licensees" t:signed_or_vetoed=Signed t:measure_number=https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/HB4053/Enrolled m:row_number.3ndr-ntjb=3
```

## Meta Commands

```ls
metric m:row_number.3ndr-ntjb p:long l:"Row Number"

entity e:3ndr-ntjb l:"Bills Signed By Governor Brown 2016" t:attribution="Adminstrative Services" t:url=https://data.oregon.gov/api/views/3ndr-ntjb

property e:3ndr-ntjb t:meta.view v:id=3ndr-ntjb v:category=Administrative v:averageRating=0 v:name="Bills Signed By Governor Brown 2016" v:attribution="Adminstrative Services"

property e:3ndr-ntjb t:meta.view.owner v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:displayName="Linda Morrell"

property e:3ndr-ntjb t:meta.view.tableauthor v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:roleName=editor v:displayName="Linda Morrell"
```

## Top Records

```ls
| measure_number                                                                               | signed_or_vetoed | links        | date       | relating_to_clause                                                       | 
| ============================================================================================ | ================ | ============ | ========== | ======================================================================== | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/HB4047/Enrolled, HB 4047] | Signed           | [null, null] | 02/23/2016 | Relating to speed limits on highways that traverse state lines           | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/HB4038/Enrolled, HB 4038] | Signed           | [null, null] | 02/29/2016 | Relating to voting methods for cooperative corporations;                 | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/HB4053/Enrolled, HB 4053] | Signed           | [null, null] | 02/29/2016 | Relating to brewery licensees                                            | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/SB1504/Enrolled, SB 1504] | Signed           | [null, null] | 03/03/2016 | Relating to physical therapy                                             | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/SB1514/Enrolled, SB 1514] | Signed           | [null, null] | 03/03/2016 | Relating to prescription drugs                                           | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/SB1534/Enrolled, SB 1534] | Signed           | [null, null] | 03/03/2016 | Relating to unemployment insurance                                       | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/SB1540/Enrolled, SB 1540] | Signed           | [null, null] | 03/03/2016 | Relating to higher education tuition waiver                              | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/SB1554/Enrolled, SB 1554] | Signed           | [null, null] | 03/03/2016 | Relating to access to digital assets                                     | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/SB1558/Enrolled, SB 1558] | Signed           | [null, null] | 03/03/2016 | Relating to student health records                                       | 
| [https://olis.leg.state.or.us/liz/2016R1/Downloads/MeasureDocument/SB1564/Enrolled, SB 1564] | Signed           | [null, null] | 03/03/2016 | Relating to reporting requirements for English language learner programs | 
```