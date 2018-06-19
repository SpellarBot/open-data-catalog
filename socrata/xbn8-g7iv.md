# Bills Signed by Governor Kitzhaber (2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bills-signed-by-governor-kitzhaber-2013-020bc) |
| Metadata | [Link](https://data.oregon.gov/api/views/xbn8-g7iv) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/xbn8-g7iv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/xbn8-g7iv/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | xbn8-g7iv |
| Name | Bills Signed by Governor Kitzhaber (2013) |
| Attribution | Office of the Governor |
| Category | Administrative |
| Tags | bills, legislature, legislative, signed, veto, vetoed, bill, session, 2013 |
| Created | 2013-03-13T16:47:21Z |
| Publication Date | 2013-10-15T17:47:53Z |

## Description

List of bills signed by Governor Kitzhaber in the 2013 Legislative Session

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
series e:xbn8-g7iv d:2013-03-11T00:00:00.000Z t:relating_to_clause="<p>Relating to correction of erroneous material in Oregon law;</p>" t:signed_or_vetoed=<p>Signed</p> t:measure_number=http://www.leg.state.or.us/13reg/measpdf/hb2100.dir/hb2148.en.pdf m:row_number.xbn8-g7iv=1

series e:xbn8-g7iv d:2013-03-11T00:00:00.000Z t:relating_to_clause="<p>Relating to jurors summoned by circuit courts; creating new provisions;</p>" t:signed_or_vetoed=<p>Signed</p> t:measure_number=http://www.leg.state.or.us/13reg/measpdf/hb2500.dir/hb2547.en.pdf m:row_number.xbn8-g7iv=2

series e:xbn8-g7iv d:2013-03-11T00:00:00.000Z t:relating_to_clause="<p>Relating&nbsp; to&nbsp; attorneys;&nbsp; creating&nbsp; new&nbsp; provisions;</p>" t:signed_or_vetoed=<p>Signed</p> t:measure_number=http://www.leg.state.or.us/13reg/measpdf/hb2500.dir/hb2565.en.pdf m:row_number.xbn8-g7iv=3
```

## Meta Commands

```ls
metric m:row_number.xbn8-g7iv p:long l:"Row Number"

entity e:xbn8-g7iv l:"Bills Signed by Governor Kitzhaber (2013)" t:attribution="Office of the Governor" t:url=https://data.oregon.gov/api/views/xbn8-g7iv

property e:xbn8-g7iv t:meta.view v:id=xbn8-g7iv v:category=Administrative v:averageRating=0 v:name="Bills Signed by Governor Kitzhaber (2013)" v:attribution="Office of the Governor"

property e:xbn8-g7iv t:meta.view.owner v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:displayName="Linda Morrell"

property e:xbn8-g7iv t:meta.view.tableauthor v:id=2qi6-2red v:profileImageUrlMedium=/api/users/2qi6-2red/profile_images/THUMB v:profileImageUrlLarge=/api/users/2qi6-2red/profile_images/LARGE v:screenName="Linda Morrell" v:profileImageUrlSmall=/api/users/2qi6-2red/profile_images/TINY v:roleName=editor v:displayName="Linda Morrell"
```

## Top Records

```ls
| measure_number                                                              | signed_or_vetoed | links        | date                | relating_to_clause                                                                | 
| =========================================================================== | ================ | ============ | =================== | ================================================================================= | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2100.dir/hb2148.en.pdf, HB2148] | Signed           | [null, null] | 2013-03-11T00:00:00 | Relating to correction of erroneous material in Oregon law;                       | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2500.dir/hb2547.en.pdf, HB2547] | Signed           | [null, null] | 2013-03-11T00:00:00 | Relating to jurors summoned by circuit courts; creating new provisions;           | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2500.dir/hb2565.en.pdf, HB2565] | Signed           | [null, null] | 2013-03-11T00:00:00 | Relating  to  attorneys;  creating  new  provisions;                              | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2800.dir/hb2800.en.pdf, HB2800] | Signed           | [null, null] | 2013-03-12T00:00:00 | Relating to the Interstate 5 bridge replacement project; creating new provisions; | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2000.dir/hb2043.en.pdf, HB2043] | Signed           | [null, null] | 2013-03-18T00:00:00 | Relating to jurisdiction in cases of denial;                                      | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2200.dir/hb2236.en.pdf, HB2236] | Signed           | [null, null] | 2013-03-18T00:00:00 | Relating to corrections;                                                          | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2100.dir/hb2105.en.pdf, HB2105] | Signed           | [null, null] | 2013-05-14T00:00:00 | Relating to the Energy Facility Siting Council;                                   | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2100.dir/hb2107.en.pdf, HB2107] | Signed           | [null, null] | 2013-05-14T00:00:00 | Relating to electronic proof of insurance;                                        | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2600.dir/hb2612.en.pdf, HB2612] | Signed           | [null, null] | 2013-05-14T00:00:00 | Relating to postpartum procedures;                                                | 
| [http://www.leg.state.or.us/13reg/measpdf/hb2600.dir/hb2698.en.pdf, HB2698] | Signed           | [null, null] | 2013-05-14T00:00:00 | Relating to the state building code;                                              | 
```