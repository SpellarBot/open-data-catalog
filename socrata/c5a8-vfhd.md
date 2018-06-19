# Voter Registration Statistics 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/voter-registration-statistics-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/c5a8-vfhd) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/c5a8-vfhd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/c5a8-vfhd/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | c5a8-vfhd |
| Name | Voter Registration Statistics 2016 |
| Attribution | Oregon Secretary of State |
| Category | Administrative |
| Tags | election, voting, voters |
| Created | 2016-09-19T17:23:34Z |
| Publication Date | 2016-09-21T01:06:03Z |

## Description

Monthly voter registration statistics for registered voters in Oregon.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | county     | County     | text          | text          |
| Yes      | series tag     | srcode     | SRCode     | text          | text          |
| Yes      | series tag     | srdesc     | SRDesc     | text          | text          |
| Yes      | series tag     | congcode   | CongCode   | text          | text          |
| Yes      | series tag     | congdesc   | CongDesc   | text          | text          |
| Yes      | series tag     | party      | Party      | text          | text          |
| Yes      | numeric metric | partycount | PartyCount | number        | number        |
| Yes      | time           | date       | Date       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:c5a8-vfhd d:2016-09-01T00:00:00.000Z t:congdesc="US Congressional District 4" t:congcode="4th Cong" t:srcode=SR08 t:county=LANE t:party=Democrat t:srdesc="House District 08" m:partycount=24095

series e:c5a8-vfhd d:2016-09-01T00:00:00.000Z t:congdesc="US Congressional District 4" t:congcode="4th Cong" t:srcode=SR12 t:county=LANE t:party="Americans Elect" t:srdesc="House District 12" m:partycount=7

series e:c5a8-vfhd d:2016-09-01T00:00:00.000Z t:congdesc="US Congressional District 2" t:congcode="2nd Cong" t:srcode=SR58 t:county=UNION t:party="Independent Party" t:srdesc="House District 58" m:partycount=759
```

## Meta Commands

```ls
metric m:partycount p:integer l:PartyCount d:"Total number of registered voters as of the 1st of the month." t:dataTypeName=number

entity e:c5a8-vfhd l:"Voter Registration Statistics 2016" t:attribution="Oregon Secretary of State" t:url=https://data.oregon.gov/api/views/c5a8-vfhd

property e:c5a8-vfhd t:meta.view v:id=c5a8-vfhd v:category=Administrative v:averageRating=0 v:name="Voter Registration Statistics 2016" v:attribution="Oregon Secretary of State"

property e:c5a8-vfhd t:meta.view.license v:name="Public Domain"

property e:c5a8-vfhd t:meta.view.owner v:id=ibb7-gbfs v:profileImageUrlMedium=/api/users/ibb7-gbfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/ibb7-gbfs/profile_images/LARGE v:screenName="Secretary of State Open Data Admin" v:profileImageUrlSmall=/api/users/ibb7-gbfs/profile_images/TINY v:displayName="Secretary of State Open Data Admin"

property e:c5a8-vfhd t:meta.view.tableauthor v:id=ibb7-gbfs v:profileImageUrlMedium=/api/users/ibb7-gbfs/profile_images/THUMB v:profileImageUrlLarge=/api/users/ibb7-gbfs/profile_images/LARGE v:screenName="Secretary of State Open Data Admin" v:profileImageUrlSmall=/api/users/ibb7-gbfs/profile_images/TINY v:roleName=editor v:displayName="Secretary of State Open Data Admin"
```

## Top Records

```ls
| county    | srcode | srdesc            | congcode | congdesc                    | party                            | partycount | date                | 
| ========= | ====== | ================= | ======== | =========================== | ================================ | ========== | =================== | 
| LANE      | SR08   | House District 08 | 4th Cong | US Congressional District 4 | Democrat                         | 24095      | 2016-09-01T00:00:00 | 
| LANE      | SR12   | House District 12 | 4th Cong | US Congressional District 4 | Americans Elect                  | 7          | 2016-09-01T00:00:00 | 
| UNION     | SR58   | House District 58 | 2nd Cong | US Congressional District 2 | Independent Party                | 759        | 2016-09-01T00:00:00 | 
| UNION     | SR58   | House District 58 | 2nd Cong | US Congressional District 2 | Working Families Party of Oregon | 38         | 2016-09-01T00:00:00 | 
| JOSEPHINE | SR03   | House District 03 | 4th Cong | US Congressional District 4 | Pacific Green                    | 100        | 2016-09-01T00:00:00 | 
| JOSEPHINE | SR01   | House District 01 | 4th Cong | US Congressional District 4 | Nonaffiliated                    | 828        | 2016-09-01T00:00:00 | 
| JOSEPHINE | SR04   | House District 04 | 4th Cong | US Congressional District 4 | Republican                       | 196        | 2016-09-01T00:00:00 | 
| JOSEPHINE | SR02   | House District 02 | 4th Cong | US Congressional District 4 | Libertarian                      | 31         | 2016-09-01T00:00:00 | 
| JOSEPHINE | SR02   | House District 02 | 4th Cong | US Congressional District 4 | Constitution                     | 21         | 2016-09-01T00:00:00 | 
| JOSEPHINE | SR01   | House District 01 | 4th Cong | US Congressional District 4 | Constitution                     | 9          | 2016-09-01T00:00:00 | 
```