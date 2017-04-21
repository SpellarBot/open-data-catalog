# 2012 Primary - Candidates Who Filed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-candidates-who-filed) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/e4bv-d24r) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/e4bv-d24r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/e4bv-d24r/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | e4bv-d24r |
| Name | 2012 Primary - Candidates Who Filed |
| Attribution | King County Elections |
| Category | Elections |
| Tags | candidates; candidate filing; campaign; elections; voting |
| Created | 2016-04-27T17:16:34Z |
| Publication Date | 2016-04-27T17:33:08Z |

## Description

List of candidates who filed for office in 2012.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                     | Data Type | Render Type |
| ======== | =========== | ====================== | ======================== | ========= | =========== |
| Yes      | series tag  | contest                | Contest                  | text      | text        |
| Yes      | series tag  | office_line_1          | Office line 1            | text      | text        |
| Yes      | series tag  | office_line_2          | Office line 2            | text      | text        |
| Yes      | series tag  | candidate_name         | Candidate name           | text      | text        |
| Yes      | series tag  | party_preference       | Party preference         | text      | text        |
| No       |             | mailing_address        | Mailing address          | text      | text        |
| Yes      | series tag  | mailing_city_state_zip | Mailing city, state, zip | text      | text        |
| Yes      | series tag  | phone                  | Phone                    | text      | text        |
| Yes      | series tag  | website                | Website                  | url       | url         |
| Yes      | series tag  | email                  | Email                    | email     | email       |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:e4bv-d24r d:2012-01-01T00:00:00.000Z t:mailing_city_state_zip="KIRKLAND WA  98033" t:office_line_2="partisan office" t:phone="(206) 337-2242" t:email=michael@VoteBaumgartner.com t:website=http://www.VoteBaumgartner.com t:candidate_name="Michael Baumgartner" t:contest="United States Senator" t:party_preference=Republican m:row_number.e4bv-d24r=1

series e:e4bv-d24r d:2012-01-01T00:00:00.000Z t:mailing_city_state_zip="TACOMA WA  98401" t:office_line_2="partisan office" t:phone="(253) 627-1317" t:email=willpower76@hotmail.com t:candidate_name="Will Baker" t:contest="United States Senator" t:party_preference=Reform m:row_number.e4bv-d24r=2

series e:e4bv-d24r d:2012-01-01T00:00:00.000Z t:mailing_city_state_zip="SNOHOMISH WA  98290" t:office_line_2="partisan office" t:phone=NONE t:email=chuck@scaryreality.com t:website=http://www.scaryreality.com t:candidate_name="Chuck Jackson" t:contest="United States Senator" t:party_preference=Republican m:row_number.e4bv-d24r=3
```

## Meta Commands

```ls
metric m:row_number.e4bv-d24r p:long l:"Row Number"

entity e:e4bv-d24r l:"2012 Primary - Candidates Who Filed" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/e4bv-d24r

property e:e4bv-d24r t:meta.view v:id=e4bv-d24r v:category=Elections v:attributionLink=http://kingcounty.gov/elections v:averageRating=0 v:name="2012 Primary - Candidates Who Filed" v:attribution="King County Elections"

property e:e4bv-d24r t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:e4bv-d24r t:meta.view.owner v:id=dqgp-vryk v:screenName=Janice v:displayName=Janice

property e:e4bv-d24r t:meta.view.tableauthor v:id=dqgp-vryk v:screenName=Janice v:roleName=publisher v:displayName=Janice
```

## Top Records

```ls
| contest                      | office_line_1                | office_line_2   | candidate_name             | party_preference | mailing_address     | mailing_city_state_zip | phone          | website                                 | email                       | 
| ============================ | ============================ | =============== | ========================== | ================ | =================== | ====================== | ============== | ======================================= | =========================== | 
| United States Senator        |                              | partisan office | Michael Baumgartner        | Republican       | 218 MAIN ST STE 704 | KIRKLAND WA 98033      | (206) 337-2242 | [http://www.VoteBaumgartner.com, null]  | michael@VoteBaumgartner.com | 
| United States Senator        |                              | partisan office | Will Baker                 | Reform           | PO BOX 458          | TACOMA WA 98401        | (253) 627-1317 | [null, null]                            | willpower76@hotmail.com     | 
| United States Senator        |                              | partisan office | Chuck Jackson              | Republican       | 1429 AVE D #341     | SNOHOMISH WA 98290     | NONE           | [http://www.scaryreality.com, null]     | chuck@scaryreality.com      | 
| United States Senator        |                              | partisan office | Timmy (Doc) Wilson         | Democratic       | PO BOX 95647        | SEATTLE WA 98145       | (206) 769-0967 | [http://www.docwilsonusenate.com, null] | sluggertimm@yahoo.com       | 
| United States Senator        |                              | partisan office | Art Coday                  | Republican       | PO BOX 55683        | SHORELINE WA 98155     | (206) 992-6166 | [null, null]                            | artcoday@gmail.com          | 
| United States Senator        |                              | partisan office | Maria Cantwell             | Democratic       | PO BOX 12740        | SEATTLE WA 98111       | (206) 285-2012 | [null, null]                            | maria@cantwell.com          | 
| United States Senator        |                              | partisan office | Glen (Stocky) R. Stockwell | Republican       | 405 N DIVISION ST   | RITZVILLE WA 99169     | (509) 540-6899 | [null, null]                            | StockwellStocky@aol.com     | 
| United States Senator        |                              | partisan office | Mike the Mover             | Republican       | 16925 9TH AVE SE    | MILL CREEK WA 98012    | (206) 546-9545 | [null, null]                            | mike_the_mover@comcast.net  | 
| United States Representative | Congressional District No. 1 | partisan office | John Koster                | Republican       | PO BOX 231          | ARLINGTON WA 98223     | (360) 631-1894 | [null, null]                            | info@kosterforcongress.com  | 
| United States Representative | Congressional District No. 1 | partisan office | Darcy Burner               | Democratic       | PO BOX 3279         | REDMOND WA 98073       | (425) 749-8070 | [null, null]                            | info@darcyburner.net        | 
```