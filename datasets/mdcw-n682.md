# Greenbook

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/greenbook) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mdcw-n682) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mdcw-n682/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mdcw-n682/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mdcw-n682 |
| Name | Greenbook |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | City Government |
| Tags | greenbook, green, book, dcas |
| Created | 2015-04-27T21:26:31Z |
| Publication Date | 2017-04-20T20:00:48Z |

## Description

The Green Book Online is a fully searchable database which gives New Yorkers the opportunity to search for the agencies, offices, boards and commissions that keep our City running. It includes listings for New York City, County, Courts, and New York State government offices.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                        | Data Type | Render Type |
| ======== | =========== | ========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | agency_name                | Agency Name                 | text      | text        |
| Yes      | series tag  | agency_acronym             | Agency Acronym              | text      | text        |
| Yes      | series tag  | agency_website             | Agency Website              | text      | text        |
| Yes      | series tag  | first_name                 | First Name                  | text      | text        |
| Yes      | series tag  | last_name                  | Last Name                   | text      | text        |
| Yes      | series tag  | m_i                        | Middle Initial              | text      | text        |
| Yes      | series tag  | name_suffix                | Name Suffix                 | text      | text        |
| Yes      | series tag  | office_title               | Office Title                | text      | text        |
| Yes      | series tag  | division_name              | Division Name               | text      | text        |
| Yes      | series tag  | parent_division            | Parent Division             | text      | text        |
| Yes      | series tag  | grand_parent_division      | Grand Parent Division       | text      | text        |
| Yes      | series tag  | great_grand_parentdivision | Great Grand Parent Division | text      | text        |
| No       |             | address                    | Address                     | text      | text        |
| Yes      | series tag  | city                       | City                        | text      | text        |
| Yes      | series tag  | state                      | State                       | text      | text        |
| Yes      | series tag  | zip_code                   | Zip Code                    | text      | text        |
| Yes      | series tag  | phone_1                    | Phone 1                     | text      | text        |
| Yes      | series tag  | phone_2                    | Phone 2                     | text      | text        |
| Yes      | series tag  | fax_1                      | Fax 1                       | text      | text        |
| Yes      | series tag  | fax_2                      | Fax 2                       | text      | text        |
| Yes      | series tag  | agency_primary_phone       | Agency Primary Phone        | text      | text        |
| Yes      | series tag  | division_primary_phone     | Division Primary Phone      | text      | text        |
| Yes      | series tag  | section                    | Section                     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:mdcw-n682 d:2017-04-20T20:00:25.000Z t:first_name=Dawn t:agency_primary_phone="(866) 868-3692" t:office_title="Deputy Executive Director" t:zip_code=10004 t:agency_website=vote.nyc.ny.us t:last_name=Sandow t:agency_acronym=BOENY t:state=NY t:agency_name="Elections, Board of" t:section=City t:city="New York" m:row_number.mdcw-n682=1

series e:mdcw-n682 d:2017-04-20T20:00:25.000Z t:first_name=Shachi t:agency_primary_phone="(212) 669-3500" t:office_title="Chief Compliance Officer" t:zip_code=10007 t:phone_1="(212) 669-3651" t:agency_website=www.comptroller.nyc.gov t:last_name=Bhatt t:state=NY t:division_name="Asset Management" t:agency_name=Comptroller t:section=City t:city="New York" m:row_number.mdcw-n682=2

series e:mdcw-n682 d:2017-04-20T20:00:25.000Z t:office_title="State Assembly Member" t:zip_code=10462 t:state=NY t:parent_division="State Assembly Members from Bronx County" t:agency_name="Legislature of the State of NY" t:division_name="Dist. 87" t:section=State t:division_primary_phone="(718) 931-2620" t:city=Bronx t:first_name=Luis t:grand_parent_division="NY State Assembly Members from New York City" t:m_i=R t:last_name=Sepulveda m:row_number.mdcw-n682=3
```

## Meta Commands

```ls
metric m:row_number.mdcw-n682 p:long l:"Row Number"

entity e:mdcw-n682 l:Greenbook t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/mdcw-n682

property e:mdcw-n682 t:meta.view v:id=mdcw-n682 v:category="City Government" v:averageRating=0 v:name=Greenbook v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:mdcw-n682 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mdcw-n682 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency_name                                                                                                         | agency_acronym | agency_website          | first_name | last_name | m_i | name_suffix | office_title                                                           | division_name                              | parent_division                          | grand_parent_division                        | great_grand_parentdivision | address                        | city     | state | zip_code | phone_1        | phone_2 | fax_1 | fax_2 | agency_primary_phone | division_primary_phone | section | 
| =========== | =================================================================================================================== | ============== | ======================= | ========== | ========= | === | =========== | ====================================================================== | ========================================== | ======================================== | ============================================ | ========================== | ============================== | ======== | ===== | ======== | ============== | ======= | ===== | ===== | ==================== | ====================== | ======= | 
| 1492718425  | Elections, Board of                                                                                                 | BOENY          | vote.nyc.ny.us          | Dawn       | Sandow    |     |             | Deputy Executive Director                                              |                                            |                                          |                                              |                            | 32 Broadway                    | New York | NY    | 10004    |                |         |       |       | (866) 868-3692       |                        | City    | 
| 1492718425  | Comptroller                                                                                                         |                | www.comptroller.nyc.gov | Shachi     | Bhatt     |     |             | Chief Compliance Officer                                               | Asset Management                           |                                          |                                              |                            | 1 Centre St.                   | New York | NY    | 10007    | (212) 669-3651 |         |       |       | (212) 669-3500       |                        | City    | 
| 1492718425  | Legislature of the State of NY                                                                                      |                |                         | Luis       | Sepulveda | R   |             | State Assembly Member                                                  | Dist. 87                                   | State Assembly Members from Bronx County | NY State Assembly Members from New York City |                            | 1973 Westchester Ave.          | Bronx    | NY    | 10462    |                |         |       |       |                      | (718) 931-2620         | State   | 
| 1492718425  | New York State Supreme Court Appellate Division - Second Department (includes Kings, Queens and Richmond Counties ) |                |                         | Darrell    | Joseph    | M   |             | Associate Deputy Clerk                                                 | Administration                             |                                          |                                              |                            | 45 Monroe Pl.                  | Brooklyn | NY    | 11201    |                |         |       |       | (718) 875-1300       |                        | Courts  | 
| 1492718425  | Housing Authority, NYC                                                                                              | NYCHA          | NYC.gov/nycha           | Johnson    | Ohadoma   |     |             | Director, LHD Finance                                                  | Leased Housing                             |                                          |                                              |                            | 250 Broadway                   | New York | NY    | 10007    | (212) 306-4171 |         |       |       | (212) 306-3000       |                        | City    | 
| 1492718425  | City University of New York                                                                                         | CUNY           | www.cuny.edu            | Lakisha    | Murray    |     |             | Chief of Staff                                                         | Medgar Evers College                       | Senior Colleges                          |                                              |                            | 1650 Bedford Ave.              | Brooklyn | NY    | 11225    | (718) 270-6245 |         |       |       | 1-800-CUNY-YES       | (718) 270-4900         | City    | 
| 1492718425  | Empire State Development                                                                                            | ESD            | http://www.esd.ny.gov   | Bradley    | Austin    |     |             | Director, Government Affairs / Intergovernmental & Legislative Affairs |                                            |                                          |                                              |                            | 95 Perry St., Suite 500        | Buffalo  | NY    | 14203    |                |         |       |       | (716) 846-8200       |                        | State   | 
| 1492718425  | Small Business Services                                                                                             | SBS            | nyc.gov/sbs             | Dynishal   | Gross     |     |             | Assistant Commissioner, Business Programs                              | Division of Business Services              |                                          |                                              |                            | 110 William St.                | New York | NY    | 10038    | (212) 513-6456 |         |       |       | (212) 513-6300       |                        | City    | 
| 1492718425  | Corrections & Community Supervision, Department of                                                                  |                | www.doccs.ny.gov        | Anthony    | Annucci   |     |             | Acting Commissioner                                                    |                                            |                                          |                                              |                            | Bldg. #2, 1220 Washington Ave. | Albany   | NY    | 12226    |                |         |       |       | (518) 457-8126       |                        | State   | 
| 1492718425  | Small Business Services                                                                                             | SBS            | nyc.gov/sbs             | Kim        | Hardy     |     |             | Deputy Commissioner                                                    | Division Of Economic Financial Opportunity |                                          |                                              |                            | 110 William St.                | New York | NY    | 10038    | (212) 513-6435 |         |       |       | (212) 513-6300       |                        | City    | 
```