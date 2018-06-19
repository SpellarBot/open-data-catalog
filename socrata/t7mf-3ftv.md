# Campaign Finance - San Francisco Campaign Committees and Other Campaign Filers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-san-francisco-campaign-committees-and-other-campaign-filers-22e5a) |
| Metadata | [Link](https://data.sfgov.org/api/views/t7mf-3ftv) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/t7mf-3ftv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/t7mf-3ftv/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | t7mf-3ftv |
| Name | Campaign Finance - San Francisco Campaign Committees and Other Campaign Filers |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, committees, campaign, elections, finance, ballot measure, candidate, major donor, independent expenditure, slate mailer, general purpose |
| Created | 2013-08-06T18:10:04Z |
| Publication Date | 2014-02-26T23:07:38Z |

## Description

This dataset contains a list of all active and terminated campaign committees and non-committee campaign finance filers in the Ethics Commission's records database.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | oid                      | OID                      | text      | number      |
| Yes      | series tag  | name                     | Name                     | text      | text        |
| Yes      | series tag  | isefiler                 | IsEfiler                 | text      | text        |
| Yes      | series tag  | status                   | Status                   | text      | text        |
| Yes      | series tag  | type                     | Type                     | text      | text        |
| Yes      | series tag  | fppcid                   | FPPCID                   | text      | text        |
| Yes      | series tag  | penid                    | PENID                    | text      | text        |
| Yes      | series tag  | disclosurecity           | DisclosureCity           | text      | text        |
| Yes      | series tag  | disclosurestate          | DisclosureState          | text      | text        |
| Yes      | series tag  | disclosurepostalcode     | DisclosurePostalCode     | text      | text        |
| Yes      | series tag  | treasurerfirst           | TreasurerFirst           | text      | text        |
| Yes      | series tag  | treasurerlast            | TreasurerLast            | text      | text        |
| Yes      | series tag  | treasurerprefix          | TreasurerPrefix          | text      | text        |
| Yes      | series tag  | t_disclosure_city        | T Disclosure City        | text      | text        |
| Yes      | series tag  | t_disclosure_state       | T Disclosure State       | text      | text        |
| Yes      | series tag  | t_disclosure_postalcode  | T Disclosure PostalCode  | text      | text        |
| Yes      | series tag  | asst_treasurer_first     | Asst Treasurer First     | text      | text        |
| Yes      | series tag  | asst_treasurer_last      | Asst Treasurer Last      | text      | text        |
| Yes      | series tag  | asst_treasurer_prefix    | Asst Treasurer Prefix    | text      | text        |
| Yes      | series tag  | at_disclosure_city       | AT Disclosure City       | text      | text        |
| Yes      | series tag  | at_disclosure_state      | AT Disclosure State      | text      | text        |
| Yes      | series tag  | at_disclosure_postalcode | AT Disclosure PostalCode | text      | text        |
| Yes      | series tag  | cont_cand_first          | Cont Cand First          | text      | text        |
| Yes      | series tag  | cont_cand_last           | Cont Cand Last           | text      | text        |
| Yes      | series tag  | cont_cand_prefix         | Cont Cand Prefix         | text      | text        |
| Yes      | series tag  | cc_disclosure_city       | CC Disclosure City       | text      | text        |
| Yes      | series tag  | cc_disclosure_state      | CC Disclosure State      | text      | text        |
| Yes      | series tag  | cc_disclosure_postalcode | CC Disclosure PostalCode | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:t7mf-3ftv d:2017-04-21T02:00:08.000Z t:cc_disclosure_postalcode=94116 t:t_disclosure_state=CA t:status=TERMINATED t:t_disclosure_city="San Francisco" t:cc_disclosure_state=CA t:fppcid=900804 t:cont_cand_first=Vu-Duc t:isefiler=FALSE t:type="Candidate or Officeholder" t:cc_disclosure_city="San Francisco" t:cont_cand_last=Vuong t:oid=127493855 t:name="Vu Duc Vuong for Supervisor" m:row_number.t7mf-3ftv=1

series e:t7mf-3ftv d:2017-04-21T02:00:08.000Z t:cc_disclosure_postalcode=94134 t:t_disclosure_state=CA t:status=TERMINATED t:cont_cand_last=Medina t:oid=146974120 t:t_disclosure_city="San Francisco" t:name="Medina for Supervisor" t:fppcid=921316 t:isefiler=FALSE t:cont_cand_first=Jose t:type="Candidate or Officeholder" m:row_number.t7mf-3ftv=2

series e:t7mf-3ftv d:2017-04-21T02:00:08.000Z t:cc_disclosure_postalcode=94132 t:t_disclosure_state=CA t:status=TERMINATED t:t_disclosure_city="San Francisco" t:cc_disclosure_state=CA t:fppcid=860315 t:cont_cand_first=Quentin t:isefiler=FALSE t:type="Candidate or Officeholder" t:cc_disclosure_city="San Francisco" t:cont_cand_last=Kopp t:oid=146000772 t:name="Kopp for Senate" m:row_number.t7mf-3ftv=3
```

## Meta Commands

```ls
metric m:row_number.t7mf-3ftv p:long l:"Row Number"

entity e:t7mf-3ftv l:"Campaign Finance - San Francisco Campaign Committees and Other Campaign Filers" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/t7mf-3ftv

property e:t7mf-3ftv t:meta.view v:id=t7mf-3ftv v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - San Francisco Campaign Committees and Other Campaign Filers" v:attribution="San Francisco Ethics Commission"

property e:t7mf-3ftv t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:t7mf-3ftv t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:t7mf-3ftv t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| :updated_at | oid       | name                                           | isefiler | status     | type                      | fppcid  | penid   | disclosurecity | disclosurestate | disclosurepostalcode | treasurerfirst | treasurerlast | treasurerprefix | t_disclosure_city | t_disclosure_state | t_disclosure_postalcode | asst_treasurer_first | asst_treasurer_last | asst_treasurer_prefix | at_disclosure_city | at_disclosure_state | at_disclosure_postalcode | cont_cand_first | cont_cand_last | cont_cand_prefix | cc_disclosure_city | cc_disclosure_state | cc_disclosure_postalcode | 
| =========== | ========= | ============================================== | ======== | ========== | ========================= | ======= | ======= | ============== | =============== | ==================== | ============== | ============= | =============== | ================= | ================== | ======================= | ==================== | =================== | ===================== | ================== | =================== | ======================== | =============== | ============== | ================ | ================== | =================== | ======================== | 
| 1492740008  | 127493855 | Vu Duc Vuong for Supervisor                    | FALSE    | TERMINATED | Candidate or Officeholder | 900804  |         |                |                 |                      |                |               |                 | San Francisco     | CA                 |                         |                      |                     |                       |                    |                     |                          | Vu-Duc          | Vuong          |                  | San Francisco      | CA                  | 94116                    | 
| 1492740008  | 146974120 | Medina for Supervisor                          | FALSE    | TERMINATED | Candidate or Officeholder | 921316  |         |                |                 |                      |                |               |                 | San Francisco     | CA                 |                         |                      |                     |                       |                    |                     |                          | Jose            | Medina         |                  |                    |                     | 94134                    | 
| 1492740008  | 146000772 | Kopp for Senate                                | FALSE    | TERMINATED | Candidate or Officeholder | 860315  |         |                |                 |                      |                |               |                 | San Francisco     | CA                 |                         |                      |                     |                       |                    |                     |                          | Quentin         | Kopp           |                  | San Francisco      | CA                  | 94132                    | 
| 1492740008  | 6679799   | Julie Brandt for DCCC                          | FALSE    | TERMINATED | Candidate or Officeholder | 1262493 |         |                |                 |                      |                |               |                 | San Francisco     | CA                 |                         |                      |                     |                       |                    |                     |                          | Julie           | Brandt         |                  | San Francisco      | CA                  | 94114                    | 
| 1492740008  | 6674352   | Committee to Elect Malik Looper                | FALSE    | NR         | Candidate or Officeholder | 1263667 |         |                |                 |                      |                |               |                 | San Francisco     | CA                 |                         |                      |                     |                       |                    |                     |                          | Malik           | Looper         |                  | San Francisco      | CA                  | 94112                    | 
| 1492740008  | 150233102 | San Franciscans for a Better Community College | FALSE    | TERMINATED | Candidate or Officeholder | 882003  |         |                |                 |                      |                |               |                 | San Francisco     | CA                 |                         |                      |                     |                       |                    |                     |                          | Robert          | Varni          |                  | San Francisco      | CA                  | 94108                    | 
| 1492740008  | 125378577 | Matthew Cohler                                 | TRUE     | ANNUAL     | Major Donor               | Pending |         |                |                 |                      |                |               |                 | San Rafael        | CA                 |                         |                      |                     |                       |                    |                     |                          |                 |                |                  |                    |                     |                          | 
| 1492740008  | 6667071   | Elect Christine Hughes to the GOP              | FALSE    | TERMINATED | Candidate or Officeholder | 1285301 |         |                |                 |                      |                |               |                 | San Francisco     | CA                 |                         |                      |                     |                       |                    |                     |                          | Christine       | Hughes         |                  | San Francisco      | CA                  | 94108                    | 
| 1492740008  | 146973427 | Jose Medina for Supervisor 1990                | FALSE    | TERMINATED | Candidate or Officeholder | 891370  |         |                |                 |                      |                |               |                 | Greenbrae         | CA                 |                         |                      |                     |                       |                    |                     |                          | Jose            | Medina         |                  |                    |                     | 94134                    | 
| 1492740008  | 6670388   | Rodney Hauge - PEN1215                         | FALSE    | ANNUAL     | Person                    |         | PEN1215 |                |                 |                      |                |               |                 |                   |                    |                         |                      |                     |                       |                    |                     |                          | Rodney          | Hauge          |                  | San Francisco      | CA                  | 94102                    | 
```