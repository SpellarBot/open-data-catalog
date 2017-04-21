# Unofficial candidate filings : 2012 election cycle

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/unofficial-candidate-filings-2012-election-cycle-9a250) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/rtwm-wmu6) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/rtwm-wmu6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/rtwm-wmu6/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | rtwm-wmu6 |
| Name | Unofficial candidate filings : 2012 election cycle |
| Attribution | King County Elections |
| Category | Election operations |
| Tags | 2012 election, candidates, king county elections, kce |
| Created | 2012-05-21T19:32:03Z |
| Publication Date | 2012-05-21T19:40:27Z |

## Description

Unofficial candidate filings with King County Elections; 2012 general and primary elections

## Columns

```ls
| Included | Schema Type | Field Name             | Name                     | Data Type | Render Type |
| ======== | =========== | ====================== | ======================== | ========= | =========== |
| Yes      | series tag  | candidate_name         | Candidate name           | text      | text        |
| Yes      | series tag  | registered_name        | Registered name          | text      | text        |
| Yes      | series tag  | contest                | Contest                  | text      | text        |
| Yes      | series tag  | office_line_1          | Office line 1            | text      | text        |
| Yes      | series tag  | office_line_2          | Office line 2            | text      | text        |
| Yes      | series tag  | party_preference       | Party preference         | text      | text        |
| No       |             | mailing_address        | Mailing address          | text      | text        |
| Yes      | series tag  | mailing_city_state_zip | Mailing city, state, zip | text      | text        |
| Yes      | series tag  | website                | Website                  | text      | text        |
| Yes      | series tag  | email                  | Email                    | text      | text        |
| Yes      | series tag  | phone                  | Phone                    | text      | text        |
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
series e:rtwm-wmu6 d:2012-01-01T00:00:00.000Z t:mailing_city_state_zip="KIRKLAND WA  98033" t:office_line_2="partisan office" t:phone="(206) 337-2242" t:email=michael@VoteBaumgartner.com t:website=www.VoteBaumgartner.com t:registered_name="MICHAEL  BAUMGARTNER" t:candidate_name="Michael Baumgartner" t:contest="United States Senator" t:party_preference=Republican m:row_number.rtwm-wmu6=1

series e:rtwm-wmu6 d:2012-01-01T00:00:00.000Z t:mailing_city_state_zip="TACOMA WA  98401" t:office_line_2="partisan office" t:phone="(253) 627-1317" t:email=willpower76@hotmail.com t:registered_name="WILLIAM  BAKER" t:candidate_name="Will Baker" t:contest="United States Senator" t:party_preference=Reform m:row_number.rtwm-wmu6=2

series e:rtwm-wmu6 d:2012-01-01T00:00:00.000Z t:mailing_city_state_zip="SNOHOMISH WA  98290" t:office_line_2="partisan office" t:phone=NONE t:email=chuck@scaryreality.com t:website=www.scaryreality.com t:registered_name="CHARLIE  JACKSON" t:candidate_name="Chuck Jackson" t:contest="United States Senator" t:party_preference=Republican m:row_number.rtwm-wmu6=3
```

## Meta Commands

```ls
metric m:row_number.rtwm-wmu6 p:long l:"Row Number"

entity e:rtwm-wmu6 l:"Unofficial candidate filings : 2012 election cycle" t:attribution="King County Elections" t:url=https://data.kingcounty.gov/api/views/rtwm-wmu6

property e:rtwm-wmu6 t:meta.view v:id=rtwm-wmu6 v:category="Election operations" v:attributionLink=http://kingcounty.gov/elections/currentelections/201208/candidatefiling.aspx v:averageRating=0 v:name="Unofficial candidate filings : 2012 election cycle" v:attribution="King County Elections"

property e:rtwm-wmu6 t:meta.view.license v:name="Public Domain"

property e:rtwm-wmu6 t:meta.view.owner v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:displayName="Kathy Gill"

property e:rtwm-wmu6 t:meta.view.tableauthor v:id=iw7b-ptyg v:profileImageUrlMedium=/api/users/iw7b-ptyg/profile_images/THUMB v:profileImageUrlLarge=/api/users/iw7b-ptyg/profile_images/LARGE v:screenName="Kathy Gill" v:profileImageUrlSmall=/api/users/iw7b-ptyg/profile_images/TINY v:roleName=publisher v:displayName="Kathy Gill"
```

## Top Records

```ls
| candidate_name             | registered_name      | contest                      | office_line_1                | office_line_2   | party_preference | mailing_address     | mailing_city_state_zip | website                  | email                       | phone          | 
| ========================== | ==================== | ============================ | ============================ | =============== | ================ | =================== | ====================== | ======================== | =========================== | ============== | 
| Michael Baumgartner        | MICHAEL BAUMGARTNER  | United States Senator        |                              | partisan office | Republican       | 218 MAIN ST STE 704 | KIRKLAND WA 98033      | www.VoteBaumgartner.com  | michael@VoteBaumgartner.com | (206) 337-2242 | 
| Will Baker                 | WILLIAM BAKER        | United States Senator        |                              | partisan office | Reform           | PO BOX 458          | TACOMA WA 98401        |                          | willpower76@hotmail.com     | (253) 627-1317 | 
| Chuck Jackson              | CHARLIE JACKSON      | United States Senator        |                              | partisan office | Republican       | 1429 AVE D #341     | SNOHOMISH WA 98290     | www.scaryreality.com     | chuck@scaryreality.com      | NONE           | 
| Timmy (Doc) Wilson         | TIMOTHY D WILSON     | United States Senator        |                              | partisan office | Democratic       | PO BOX 95647        | SEATTLE WA 98145       | www.docwilsonusenate.com | sluggertimm@yahoo.com       | (206) 769-0967 | 
| Art Coday                  | ARTHUR CODAY         | United States Senator        |                              | partisan office | Republican       | PO BOX 55683        | SHORELINE WA 98155     |                          | artcoday@gmail.com          | (206) 992-6166 | 
| Maria Cantwell             | MARIA CANTWELL       | United States Senator        |                              | partisan office | Democratic       | PO BOX 12740        | SEATTLE WA 98111       |                          | maria@cantwell.com          | (206) 285-2012 | 
| Glen (Stocky) R. Stockwell | GLEN STOCKWELL       | United States Senator        |                              | partisan office | Republican       | 405 N DIVISION ST   | RITZVILLE WA 99169     |                          | StockwellStocky@aol.com     | (509) 540-6899 | 
| Mike the Mover             | MIKE MOVER           | United States Senator        |                              | partisan office | Republican       | 16925 9TH AVE SE    | MILL CREEK WA 98012    |                          | mike_the_mover@comcast.net  | (206) 546-9545 | 
| John Koster                | JOHN KOSTER          | United States Representative | Congressional District No. 1 | partisan office | Republican       | PO BOX 231          | ARLINGTON WA 98223     |                          | info@kosterforcongress.com  | (360) 631-1894 | 
| Darcy Burner               | DARCY GIBBONS BURNER | United States Representative | Congressional District No. 1 | partisan office | Democratic       | PO BOX 3279         | REDMOND WA 98073       |                          | info@darcyburner.net        | (425) 749-8070 | 
```