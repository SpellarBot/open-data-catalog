# Campaign Contributions Received By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-contributions-received-by-hawaii-state-and-county-candidates-from-november-8-2006-bc367) |
| Metadata | [Link](https://data.hawaii.gov/api/views/jexd-xbcg) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/jexd-xbcg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/jexd-xbcg/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | jexd-xbcg |
| Name | Campaign Contributions Received By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016 |
| Attribution | State of Hawaii; Campaign Spending Commission |
| Category | Community |
| Tags | campaign spending commission, campaign finance, candidate, hawaii candidates, contributions, political contributions, campaign contributions, campaign spending, elections |
| Created | 2012-10-09T01:25:57Z |
| Publication Date | 2017-03-13T23:34:34Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | candidate_name           | Candidate Name           | text          | text          |
| Yes      | series tag     | contributor_type         | Contributor Type         | text          | text          |
| Yes      | series tag     | contributor_name         | Contributor Name         | text          | text          |
| Yes      | time           | date                     | Date                     | calendar_date | calendar_date |
| Yes      | numeric metric | amount                   | Amount                   | money         | money         |
| Yes      | numeric metric | aggregate                | Aggregate                | money         | money         |
| Yes      | series tag     | employer                 | Employer                 | text          | text          |
| Yes      | series tag     | occupation               | Occupation               | text          | text          |
| No       |                | street_address_1         | Address 1                | text          | text          |
| No       |                | street_address_2         | Address 2                | text          | text          |
| Yes      | series tag     | city                     | City                     | text          | text          |
| Yes      | series tag     | state                    | State                    | text          | text          |
| Yes      | series tag     | zip_code                 | Zip Code                 | text          | text          |
| Yes      | series tag     | non_monetary_yes_or_no   | Non-Monetary (Yes or No) | text          | text          |
| Yes      | series tag     | non_monetary_category    | Non-Monetary Category    | text          | text          |
| Yes      | series tag     | non_monetary_description | Non-Monetary Description | text          | text          |
| Yes      | series tag     | office                   | Office                   | text          | text          |
| Yes      | series tag     | district                 | District                 | text          | text          |
| Yes      | series tag     | county                   | County                   | text          | text          |
| Yes      | series tag     | party                    | Party                    | text          | text          |
| Yes      | series tag     | reg_no                   | Reg No                   | text          | text          |
| Yes      | series tag     | election_period          | Election Period          | text          | text          |
| Yes      | series tag     | inoutstate               | InOutState               | text          | text          |
| Yes      | series tag     | range                    | Range                    | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = street_address_1,street_address_2
```

## Data Commands

```ls
series e:jexd-xbcg d:2014-09-18T08:23:23.000Z t:office="Hawaii Council" t:inoutstate=HI t:zip_code=96737 t:range=0-1000 t:contributor_type=Candidate t:candidate_name="Abbett, Richard" t:state=HI t:contributor_name="Abbett, Richard E." t:party=Non-Partisan t:reg_no=CC11028 t:city="Ocean View" t:election_period=2012-2014 t:county=Hawaii t:non_monetary_yes_or_no=N t:district=6 m:amount=100 m:aggregate=434.94

series e:jexd-xbcg d:2016-06-16T23:43:05.000Z t:office="Hawaii Council" t:inoutstate=HI t:occupation=Advocate t:zip_code=96793 t:range=0-1000 t:contributor_type=Candidate t:candidate_name="Abbett, Richard" t:state=HI t:employer=Self t:contributor_name="Abbett, Richard E." t:party=Non-Partisan t:reg_no=CC11028 t:city=Wailuku t:election_period=2014-2016 t:county=Hawaii t:non_monetary_yes_or_no=N t:district=6 m:amount=100 m:aggregate=125

series e:jexd-xbcg d:2014-09-17T08:23:02.000Z t:office="Hawaii Council" t:inoutstate=HI t:zip_code=96737 t:range=0-1000 t:contributor_type=Candidate t:candidate_name="Abbett, Richard" t:state=HI t:contributor_name="Abbett, Richard E." t:party=Non-Partisan t:reg_no=CC11028 t:city="Ocean View" t:election_period=2012-2014 t:county=Hawaii t:non_monetary_yes_or_no=N t:district=6 m:amount=234.94 m:aggregate=334.94
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

metric m:aggregate p:double l:Aggregate t:dataTypeName=money

entity e:jexd-xbcg l:"Campaign Contributions Received By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" t:attribution="State of Hawaii; Campaign Spending Commission" t:url=https://data.hawaii.gov/api/views/jexd-xbcg

property e:jexd-xbcg t:meta.view v:id=jexd-xbcg v:category=Community v:attributionLink=http://ags.hawaii.gov v:averageRating=0 v:name="Campaign Contributions Received By Hawaii State and County Candidates From November 8, 2006 Through December 31, 2016" v:attribution="State of Hawaii; Campaign Spending Commission"

property e:jexd-xbcg t:meta.view.license v:name="Public Domain"

property e:jexd-xbcg t:meta.view.owner v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:displayName="Hawaii Campaign Spending Commission"

property e:jexd-xbcg t:meta.view.tableauthor v:id=g6c2-gabj v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:roleName=editor v:displayName="Hawaii Campaign Spending Commission"
```

## Top Records

```ls
| candidate_name    | contributor_type       | contributor_name                   | date                | amount | aggregate | employer                                     | occupation      | street_address_1            | street_address_2 | city       | state | zip_code | non_monetary_yes_or_no | non_monetary_category | non_monetary_description | office         | district | county | party        | reg_no  | election_period | inoutstate | range  | 
| ================= | ====================== | ================================== | =================== | ====== | ========= | ============================================ | =============== | =========================== | ================ | ========== | ===== | ======== | ====================== | ===================== | ======================== | ============== | ======== | ====== | ============ | ======= | =============== | ========== | ====== | 
| Abbett, Richard   | Candidate              | Abbett, Richard E.                 | 2014-09-18T08:23:23 | 100    | 434.94    |                                              |                 | PO BOX 6201                 |                  | Ocean View | HI    | 96737    | N                      |                       |                          | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | HI         | 0-1000 | 
| Abbett, Richard   | Candidate              | Abbett, Richard E.                 | 2016-06-16T23:43:05 | 100    | 125       | Self                                         | Advocate        | PO Box 2734                 |                  | Wailuku    | HI    | 96793    | N                      |                       |                          | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2014-2016       | HI         | 0-1000 | 
| Abbett, Richard   | Candidate              | Abbett, Richard E.                 | 2014-09-17T08:23:02 | 234.94 | 334.94    |                                              |                 | PO BOX 6201                 |                  | Ocean View | HI    | 96737    | N                      |                       |                          | Hawaii Council | 6        | Hawaii | Non-Partisan | CC11028 | 2012-2014       | HI         | 0-1000 | 
| Abe, Michael      | Other Entity           | Citizens for Responsive Government | 2008-10-24T18:31:28 | 500    | 500       |                                              |                 | P. O Box 23031              |                  | Honolulu   | HI    | 96823    | N                      |                       |                          | House          | 19       |        | Democrat     | CC10496 | 2006-2008       | HI         | 0-1000 | 
| Abe, Michael      | Noncandidate Committee | Hawaii Optometric PAC              | 2008-09-25T10:26:20 | 250    | 250       |                                              |                 | 94-239 Waipahu Depot Street |                  | Waipahu    | HI    | 96797    | N                      |                       |                          | House          | 19       |        | Democrat     | CC10496 | 2006-2008       | HI         | 0-1000 | 
| Abercrombie, Neil | Individual             | Tu, Ok Soon                        | 2013-12-23T12:16:02 | 5200   | 5200      | Tu's Contracting                             | Owner           | 95-1048 Hookaau Street      |                  | Mililani   | HI    | 96789    | N                      |                       |                          | Governor       |          |        | Democrat     | CC10529 | 2012-2014       | HI         | > 1000 | 
| Abercrombie, Neil | Individual             | Barlow, Scott                      | 2013-09-19T09:43:13 | 3000   | 3000      | Aloha Gateway Media LLC                      | Member          | PO Box 5404                 |                  | Kaneohe    | HI    | 96744    | N                      |                       |                          | Governor       |          |        | Democrat     | CC10529 | 2012-2014       | HI         | > 1000 | 
| Abercrombie, Neil | Individual             | Tu, Paul                           | 2013-12-23T12:04:18 | 5200   | 5200      | Tu's Plumbing and Air Conditioning           | Owner           | 95-1045 Hookaau Street      |                  | Mililani   | HI    | 96789    | N                      |                       |                          | Governor       |          |        | Democrat     | CC10529 | 2012-2014       | HI         | > 1000 | 
| Abercrombie, Neil | Individual             | Min, Kyong Nok                     | 2013-12-23T12:14:20 | 5200   | 5200      | TU's Contracting                             | Engineer        | 92-1470 Hoalii Street       |                  | Kapolei    | HI    | 96707    | N                      |                       |                          | Governor       |          |        | Democrat     | CC10529 | 2012-2014       | HI         | > 1000 | 
| Abercrombie, Neil | Individual             | Young, Darrell T.                  | 2014-06-19T11:47:01 | 1500   | 2500      | State of Hawaii, Dept. of Hawaiian Home Land | Deputy Director | 94-209 Pulelo Place         |                  | Waipahu    | HI    | 96797    | N                      |                       |                          | Governor       |          |        | Democrat     | CC10529 | 2012-2014       | HI         | > 1000 | 
```