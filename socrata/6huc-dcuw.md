# Campaign Contributions Made To Candidates By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-contributions-made-to-candidates-by-hawaii-noncandidate-committees-from-january-1-fbf97) |
| Metadata | [Link](https://data.hawaii.gov/api/views/6huc-dcuw) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/6huc-dcuw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/6huc-dcuw/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 6huc-dcuw |
| Name | Campaign Contributions Made To Candidates By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016 |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending |
| Created | 2013-02-22T21:05:40Z |
| Publication Date | 2017-03-17T23:58:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | noncandidate_committee_name | Noncandidate Committee Name | text          | text          |
| Yes      | series tag     | candidate_name              | Candidate Name              | text          | text          |
| Yes      | series tag     | cc_reg_no                   | CC Reg No                   | text          | text          |
| Yes      | series tag     | candidate_committee_name    | Candidate Committee Name    | text          | text          |
| Yes      | time           | date                        | Date                        | calendar_date | calendar_date |
| Yes      | numeric metric | amount                      | Amount                      | money         | money         |
| Yes      | numeric metric | aggregate                   | Aggregate                   | money         | money         |
| No       |                | address_1                   | Address 1                   | text          | text          |
| No       |                | address_2                   | Address 2                   | text          | text          |
| Yes      | series tag     | city                        | City                        | text          | text          |
| Yes      | series tag     | state                       | State                       | text          | text          |
| Yes      | series tag     | zip_code                    | Zip Code                    | text          | text          |
| Yes      | series tag     | non_monetary_yes_or_no      | Non-Monetary (Yes or No)    | text          | text          |
| Yes      | series tag     | non_monetary_category       | Non-Monetary Category       | text          | text          |
| Yes      | series tag     | non_monetary_description    | Non-Monetary Description    | text          | text          |
| Yes      | series tag     | reg_no                      | Reg No                      | text          | text          |
| Yes      | series tag     | election_period             | Election Period             | text          | text          |
| Yes      | series tag     | office                      | Office                      | text          | text          |
| Yes      | series tag     | district                    | District                    | text          | text          |
| Yes      | series tag     | county                      | County                      | text          | text          |
| Yes      | series tag     | party                       | Party                       | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:6huc-dcuw d:2016-03-09T10:03:31.000Z t:office=Mayor t:election_period=2014-2016 t:zip_code=96745 t:county=Hawaii t:candidate_name="Lau, Wally" t:noncandidate_committee_name="327 Kona, LLC" t:candidate_committee_name="Friends of Wally Lau" t:state=HI t:non_monetary_yes_or_no=N t:party=Democrat t:cc_reg_no=CC11199 t:reg_no=NC20672 t:city=Kailau-Kona m:amount=2000 m:aggregate=2000

series e:6huc-dcuw d:2013-05-10T13:23:35.000Z t:office="Lt. Governor" t:election_period=2012-2014 t:zip_code=96744 t:candidate_name="Hee, Clayton" t:noncandidate_committee_name="808 Hits, LLC" t:candidate_committee_name="Friends of Clayton Hee" t:state=HI t:non_monetary_yes_or_no=N t:party=Democrat t:cc_reg_no=CC10144 t:reg_no=NC20412 t:city=Kaneohe m:amount=2500 m:aggregate=2500

series e:6huc-dcuw d:2010-08-10T15:44:57.000Z t:office=Senate t:zip_code=96825 t:candidate_name="Slom, Sam" t:state=HI t:candidate_committee_name="Friends for Sam Slom" t:party=Republican t:cc_reg_no=CC10287 t:reg_no=NC20197 t:city=Honolulu t:election_period=2008-2010 t:noncandidate_committee_name="8th Senatorial District" t:non_monetary_yes_or_no=N t:district=9 m:amount=1285.43 m:aggregate=1285.43
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=money

metric m:aggregate p:double l:Aggregate t:dataTypeName=money

entity e:6huc-dcuw l:"Campaign Contributions Made To Candidates By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/6huc-dcuw

property e:6huc-dcuw t:meta.view v:id=6huc-dcuw v:category=Community v:attributionLink=http://www.hawaii.gov/campaign v:averageRating=0 v:name="Campaign Contributions Made To Candidates By Hawaii Noncandidate Committees From January 1, 2008 Through December 31, 2016" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:6huc-dcuw t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:6huc-dcuw t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| noncandidate_committee_name | candidate_name | cc_reg_no | candidate_committee_name     | date                | amount  | aggregate | address_1                     | address_2 | city        | state | zip_code | non_monetary_yes_or_no | non_monetary_category | non_monetary_description | reg_no  | election_period | office           | district | county   | party        | 
| =========================== | ============== | ========= | ============================ | =================== | ======= | ========= | ============================= | ========= | =========== | ===== | ======== | ====================== | ===================== | ======================== | ======= | =============== | ================ | ======== | ======== | ============ | 
| 327 Kona, LLC               | Lau, Wally     | CC11199   | Friends of Wally Lau         | 2016-03-09T10:03:31 | 2000    | 2000      | P.O. Box 5259                 |           | Kailau-Kona | HI    | 96745    | N                      |                       |                          | NC20672 | 2014-2016       | Mayor            |          | Hawaii   | Democrat     | 
| 808 Hits, LLC               | Hee, Clayton   | CC10144   | Friends of Clayton Hee       | 2013-05-10T13:23:35 | 2500    | 2500      | P.O. Box 4484                 |           | Kaneohe     | HI    | 96744    | N                      |                       |                          | NC20412 | 2012-2014       | Lt. Governor     |          |          | Democrat     | 
| 8th Senatorial District     | Slom, Sam      | CC10287   | Friends for Sam Slom         | 2010-08-10T15:44:57 | 1285.43 | 1285.43   | 6600 Kalaninaole #212         |           | Honolulu    | HI    | 96825    | N                      |                       |                          | NC20197 | 2008-2010       | Senate           | 9        |          | Republican   | 
| A-1 A-lectrician, Inc.      | Bean, Tracy    | CC10557   | Friends of Tracy Nakano Bean | 2010-10-19T08:25:50 | 500     | 500       | P. O. BOX 1635                |           | KANEOHE     | HI    | 96744    | N                      |                       |                          | NC20001 | 2008-2010       | Senate           | 24       |          | Republican   | 
| A-1 A-lectrician, Inc.      | Berg, Tom      | CC10470   | Friends of Tom Berg          | 2010-10-19T08:43:27 | 250     | 250       | 91-203 Hanapouli Circle #39 U |           | Ewa Beach   | HI    | 96706    | N                      |                       |                          | NC20001 | 2008-2010       | Honolulu Council | 1        | Honolulu | Non-Partisan | 
| A-1 A-lectrician, Inc.      | Chang, David   | CC10562   | Friends for David Chang      | 2010-08-23T11:43:58 | 250     | 250       | P.O. Box 4128                 |           | Honolulu    | HI    | 96812    | N                      |                       |                          | NC20001 | 2008-2010       | House            | 28       |          | Republican   | 
| A-1 A-lectrician, Inc.      | Chang, David   | CC10562   | Friends for David Chang      | 2010-10-19T08:39:18 | 500     | 750       | P.O. Box 4128                 |           | Honolulu    | HI    | 96812    | N                      |                       |                          | NC20001 | 2008-2010       | House            | 28       |          | Republican   | 
| A-1 A-lectrician, Inc.      | Curtis, Samuel | CC10771   | Friends of Sam Curtis        | 2010-08-23T11:40:53 | 250     | 250       | P.O. Box 861029               |           | Wahiawa     | HI    | 96786    | N                      |                       |                          | NC20001 | 2008-2010       | House            | 39       |          | Republican   | 
| A-1 A-lectrician, Inc.      | Curtis, Samuel | CC10771   | Friends of Sam Curtis        | 2010-10-19T08:42:05 | 250     | 500       | P.O. Box 861029               |           | Wahiawa     | HI    | 96786    | N                      |                       |                          | NC20001 | 2008-2010       | House            | 39       |          | Republican   | 
| A-1 A-lectrician, Inc.      | Fale, Richard  | CC10394   | Friends of Richard Fale      | 2010-10-19T08:35:10 | 500     | 500       | P.O. Box 316                  |           | Hauula      | HI    | 96717    | N                      |                       |                          | NC20001 | 2008-2010       | Senate           | 23       |          | Republican   | 
```