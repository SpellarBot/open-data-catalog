# Active Corporations: Beginning 1800

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-corporations-beginning-1800) |
| Metadata | [Link](https://data.ny.gov/api/views/n9v6-gdp6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/n9v6-gdp6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/n9v6-gdp6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | n9v6-gdp6 |
| Name | Active Corporations: Beginning 1800 |
| Attribution | New York State Department of State |
| Category | Economic Development |
| Tags | corporation, limited liability company, limited partnership, limited liability partnership, integrity |
| Created | 2013-02-14T19:00:49Z |
| Publication Date | 2017-04-04T00:39:25Z |

## Description

The Department of State keeps a record of every filing for every incorporated business in the state of New York. This dataset contains information on all active corporations as of the last business day of the specified month and year.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | =========== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag  | dos_id                     | DOS ID                     | text          | text          |
| Yes      | series tag  | current_entity_name        | Current Entity Name        | text          | text          |
| Yes      | time        | initial_dos_filing_date    | Initial DOS Filing Date    | calendar_date | calendar_date |
| Yes      | series tag  | county                     | County                     | text          | text          |
| Yes      | series tag  | jurisdiction               | Jurisdiction               | text          | text          |
| Yes      | series tag  | entity_type                | Entity Type                | text          | text          |
| Yes      | series tag  | dos_process_name           | DOS Process Name           | text          | text          |
| No       |             | dos_process_address_1      | DOS Process Address 1      | text          | text          |
| No       |             | dos_process_address_2      | DOS Process Address 2      | text          | text          |
| Yes      | series tag  | dos_process_city           | DOS Process City           | text          | text          |
| Yes      | series tag  | dos_process_state          | DOS Process State          | text          | text          |
| Yes      | series tag  | dos_process_zip            | DOS Process Zip            | text          | text          |
| Yes      | series tag  | chairman_name              | CEO Name                   | text          | text          |
| No       |             | chairman_address_1         | CEO Address 1              | text          | text          |
| No       |             | chairman_address_2         | CEO Address 2              | text          | text          |
| Yes      | series tag  | chairman_city              | CEO City                   | text          | text          |
| Yes      | series tag  | chairman_state             | CEO State                  | text          | text          |
| Yes      | series tag  | chairman_zip               | CEO Zip                    | text          | text          |
| Yes      | series tag  | registered_agent_name      | Registered Agent Name      | text          | text          |
| No       |             | registered_agent_address_1 | Registered Agent Address 1 | text          | text          |
| No       |             | registered_agent_address_2 | Registered Agent Address 2 | text          | text          |
| Yes      | series tag  | registered_agent_city      | Registered Agent City      | text          | text          |
| Yes      | series tag  | registered_agent_state     | Registered Agent State     | text          | text          |
| Yes      | series tag  | registered_agent_zip       | Registered Agent Zip       | text          | text          |
| Yes      | series tag  | location_name              | Location Name              | text          | text          |
| No       |             | location_address_1         | Location Address 1         | text          | text          |
| No       |             | location_address_2         | Location Address 2         | text          | text          |
| Yes      | series tag  | location_city              | Location City              | text          | text          |
| Yes      | series tag  | location_state             | Location State             | text          | text          |
| Yes      | series tag  | location_zip               | Location Zip               | text          | text          |
```

## Time Field

```ls
Value = initial_dos_filing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = dos_process_address_1,dos_process_address_2,chairman_address_1,chairman_address_2,registered_agent_address_1,registered_agent_address_2,location_address_1,location_address_2
```

## Data Commands

```ls
series e:n9v6-gdp6 d:1944-11-17T00:00:00.000Z t:dos_process_city="NEW YORK" t:chairman_zip=06907 t:dos_id=55570 t:dos_process_zip=10016 t:county="NEW YORK" t:dos_process_name="WAGNER DAVIS P.C." t:dos_process_state="NEW YORK" t:chairman_name="RANDALL K. VOGES" t:jurisdiction="NEW YORK" t:entity_type="DOMESTIC BUSINESS CORPORATION" t:current_entity_name="RADAR ASSOCIATES, INC." t:chairman_state=CONNECTICUT t:chairman_city=STAMFORD m:row_number.n9v6-gdp6=1

series e:n9v6-gdp6 d:1949-02-25T00:00:00.000Z t:dos_process_city=MINEOLA t:chairman_zip=11501-0456 t:dos_id=61305 t:dos_process_zip=11501 t:county=SUFFOLK t:dos_process_name="ABE ZUCKERMAN" t:dos_process_state="NEW YORK" t:chairman_name="ABE ZUCKERMAN" t:jurisdiction="NEW YORK" t:entity_type="DOMESTIC BUSINESS CORPORATION" t:current_entity_name="SEVERIN CORP." t:chairman_state="NEW YORK" t:chairman_city=MINEOLA m:row_number.n9v6-gdp6=2

series e:n9v6-gdp6 d:2011-05-03T00:00:00.000Z t:dos_process_city=HOUGHTON t:dos_id=4088934 t:dos_process_zip=14744 t:county=ALLEGANY t:dos_process_name="ALLEGANY HARVEST COOPERATIVE MARKET, INC." t:dos_process_state="NEW YORK" t:jurisdiction="NEW YORK" t:entity_type="DOMESTIC COOPERATIVE CORPORATION" t:current_entity_name="ALLEGANY HARVEST COOPERATIVE MARKET, INC." m:row_number.n9v6-gdp6=3
```

## Meta Commands

```ls
metric m:row_number.n9v6-gdp6 p:long l:"Row Number"

entity e:n9v6-gdp6 l:"Active Corporations:  Beginning 1800" t:attribution="New York State Department of State" t:url=https://data.ny.gov/api/views/n9v6-gdp6

property e:n9v6-gdp6 t:meta.view v:id=n9v6-gdp6 v:category="Economic Development" v:attributionLink=http://www.dos.ny.gov/corps/bus_entity_search.html v:averageRating=0 v:name="Active Corporations:  Beginning 1800" v:attribution="New York State Department of State"

property e:n9v6-gdp6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:n9v6-gdp6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| dos_id  | current_entity_name                         | initial_dos_filing_date | county    | jurisdiction | entity_type                      | dos_process_name                            | dos_process_address_1       | dos_process_address_2         | dos_process_city | dos_process_state | dos_process_zip | chairman_name    | chairman_address_1 | chairman_address_2 | chairman_city | chairman_state | chairman_zip | registered_agent_name | registered_agent_address_1 | registered_agent_address_2 | registered_agent_city | registered_agent_state | registered_agent_zip | location_name | location_address_1 | location_address_2 | location_city | location_state | location_zip | 
| ======= | =========================================== | ======================= | ========= | ============ | ================================ | =========================================== | =========================== | ============================= | ================ | ================= | =============== | ================ | ================== | ================== | ============= | ============== | ============ | ===================== | ========================== | ========================== | ===================== | ====================== | ==================== | ============= | ================== | ================== | ============= | ============== | ============ | 
| 55570   | RADAR ASSOCIATES, INC.                      | 1944-11-17T00:00:00     | NEW YORK  | NEW YORK     | DOMESTIC BUSINESS CORPORATION    | WAGNER DAVIS P.C.                           | ATTN: JOHN R. WAGNER, ESQ.  | 99 MADISON AVENUE, 11TH FLOOR | NEW YORK         | NEW YORK          | 10016           | RANDALL K. VOGES | PO BOX 4560        |                    | STAMFORD      | CONNECTICUT    | 06907        |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
| 61305   | SEVERIN CORP.                               | 1949-02-25T00:00:00     | SUFFOLK   | NEW YORK     | DOMESTIC BUSINESS CORPORATION    | ABE ZUCKERMAN                               | PO BOX 456                  |                               | MINEOLA          | NEW YORK          | 11501           | ABE ZUCKERMAN    | 225 FIRST STREET   |                    | MINEOLA       | NEW YORK       | 11501-0456   |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
| 4088934 | ALLEGANY HARVEST COOPERATIVE MARKET, INC.   | 2011-05-03T00:00:00     | ALLEGANY  | NEW YORK     | DOMESTIC COOPERATIVE CORPORATION | ALLEGANY HARVEST COOPERATIVE MARKET, INC.   | P.O. BOX 83                 |                               | HOUGHTON         | NEW YORK          | 14744           |                  |                    |                    |               |                |              |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
| 3918578 | BUSHWICK FOOD COOPERATIVE INCORPORATED      | 2010-03-02T00:00:00     | KINGS     | NEW YORK     | DOMESTIC COOPERATIVE CORPORATION | BUSHWICK FOOD COOPERATIVE INCORPORATED      | 1237 WILLOUGHBY AVENUE, #1R |                               | BROOKLYN         | NEW YORK          | 11237           |                  |                    |                    |               |                |              |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
| 3866648 | SUSTAINABLE SEA CLIFF COOPERATIVE, INC.     | 2009-10-13T00:00:00     | NASSAU    | NEW YORK     | DOMESTIC COOPERATIVE CORPORATION | SUSTAINABLE SEA CLIFF COOPERATIVE, INC.     | 105 8TH AVENUE              |                               | SEA CLIFF        | NEW YORK          | 11579           |                  |                    |                    |               |                |              |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
| 1126882 | UNITED NORTH COUNTRY BARGAINING CO-OP       | 1986-11-14T00:00:00     | JEFFERSON | NEW YORK     | DOMESTIC COOPERATIVE CORPORATION |                                             |                             |                               |                  |                   |                 |                  |                    |                    |               |                |              |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
| 986929  | CYNTHIA FITZPATRICK COOPERATIVE CORPORATION | 1985-04-04T00:00:00     | MONROE    | NEW YORK     | DOMESTIC COOPERATIVE CORPORATION | CYNTHIA FITZPATRICK COOPERATIVE CORPORATION | 121 N. FITZHUGH ST.         |                               | ROCHESTER        | NEW YORK          | 14614           |                  |                    |                    |               |                |              |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
| 960532  | SUNSET PARK MEAT COOPERATIVE CORP.          | 1984-12-17T00:00:00     | KINGS     | NEW YORK     | DOMESTIC COOPERATIVE CORPORATION | S/SFEDER BARNETT & PLATT                    | ATT FRANK D PLATT           | 265 WEST 14TH ST              | NEW YORK         | NEW YORK          | 10011           |                  |                    |                    |               |                |              |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
| 785867  | COMMON PLACE LAND COOPERATIVE               | 1982-08-05T00:00:00     | CORTLAND  | NEW YORK     | DOMESTIC COOPERATIVE CORPORATION | COMMON PLACE LAND COOPERATIVE               | 4211 CUYLER RD.             |                               | TRUXTON          | NEW YORK          | 13158           |                  |                    |                    |               |                |              |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
| 750485  | YESTER-YEAR COOPERATIVE, INC.               | 1982-02-09T00:00:00     | WYOMING   | NEW YORK     | DOMESTIC COOPERATIVE CORPORATION | YESTER-YEAR COOPERATIVE, INC.               | PO BOX 206                  | 8 MARKET ST.                  | ATTICA           | NEW YORK          | 14011           |                  |                    |                    |               |                |              |                       |                            |                            |                       |                        |                      |               |                    |                    |               |                |              | 
```