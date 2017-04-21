# Labor Market Analysts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/labor-market-analysts) |
| Metadata | [Link](https://data.ny.gov/api/views/u56z-mms2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/u56z-mms2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/u56z-mms2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | u56z-mms2 |
| Name | Labor Market Analysts |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | labor market analyst economist |
| Created | 2013-12-13T14:30:11Z |
| Publication Date | 2016-10-07T14:45:29Z |

## Description

The New York State Department of Labor has labor market analysts in 10 regions across the state. This data set outlines where the labor market analysts are located by labor market region.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | name                | Name                | text      | text        |
| Yes      | series tag  | labor_market_region | Labor Market Region | text      | text        |
| Yes      | series tag  | street_address      | Street Address      | text      | text        |
| Yes      | series tag  | city                | City                | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | zip_code            | Zip Code            | text      | number      |
| Yes      | series tag  | phone               | Phone               | text      | text        |
| Yes      | series tag  | fax                 | Fax                 | text      | text        |
| Yes      | series tag  | email               | Email               | text      | text        |
| Yes      | series tag  | url                 | URL                 | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:u56z-mms2 d:2016-10-06T22:01:17.000Z t:phone="(518) 523-7157" t:fax="(518) 523-8957" t:zip_code=12946 t:email=Anthony.Hayden@labor.ny.gov? t:labor_market_region="North Country" t:name="Anthony Hayden" t:state=NY t:street_address="2693 Main Street, Suite 302" t:url=http://www.labor.ny.gov/stats/nor/index.shtm t:city="Lake Placid" m:row_number.u56z-mms2=1

series e:u56z-mms2 d:2016-10-06T22:01:17.000Z t:phone="(585) 258-8870" t:fax="(585) 258-8898" t:zip_code=14609 t:email=Tammy.Marino@labor.ny.gov t:labor_market_region="Finger Lakes" t:name="Tammy Marino" t:state=NY t:street_address="276 Waring Road" t:url=http://www.labor.ny.gov/stats/fin/default.asp t:city=Rochester m:row_number.u56z-mms2=2

series e:u56z-mms2 d:2016-10-06T22:01:17.000Z t:phone="(315) 793-2282" t:fax="(315) 793-2354" t:zip_code=13501 t:email=Mark.Barbano@labor.ny.gov t:labor_market_region="Mohawk Valley" t:name="Mark Barbano" t:state=NY t:street_address="207 Genesee St., Room 604" t:url=http://www.labor.ny.gov/stats/moh/index.shtm t:city=Utica m:row_number.u56z-mms2=3
```

## Meta Commands

```ls
metric m:row_number.u56z-mms2 p:long l:"Row Number"

entity e:u56z-mms2 l:"Labor Market Analysts" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/u56z-mms2

property e:u56z-mms2 t:meta.view v:id=u56z-mms2 v:category="Economic Development" v:attributionLink=http://www.labor.ny.gov/stats/lslma.shtm v:averageRating=0 v:name="Labor Market Analysts" v:attribution="New York State Department of Labor"

property e:u56z-mms2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:u56z-mms2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:u56z-mms2 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | name                | labor_market_region | street_address                 | city         | state | zip_code | phone          | fax            | email                            | url                                                    | 
| =========== | =================== | =================== | ============================== | ============ | ===== | ======== | ============== | ============== | ================================ | ====================================================== | 
| 1475791277  | Anthony Hayden      | North Country       | 2693 Main Street, Suite 302    | Lake Placid  | NY    | 12946    | (518) 523-7157 | (518) 523-8957 | Anthony.Hayden@labor.ny.gov?     | [http://www.labor.ny.gov/stats/nor/index.shtm, null]   | 
| 1475791277  | Tammy Marino        | Finger Lakes        | 276 Waring Road                | Rochester    | NY    | 14609    | (585) 258-8870 | (585) 258-8898 | Tammy.Marino@labor.ny.gov        | [http://www.labor.ny.gov/stats/fin/default.asp, null]  | 
| 1475791277  | Mark Barbano        | Mohawk Valley       | 207 Genesee St., Room 604      | Utica        | NY    | 13501    | (315) 793-2282 | (315) 793-2354 | Mark.Barbano@labor.ny.gov        | [http://www.labor.ny.gov/stats/moh/index.shtm, null]   | 
| 1475791277  | Karen Knapik-Scalzo | Central New York    | 450 S. Salina St., Room 300    | Syracuse     | NY    | 13202    | (315) 479-3390 | (315) 479-3271 | Karen.Knapik-Scalzo@labor.ny.gov | [http://www.labor.ny.gov/stats/cen/cnyindex.asp, null] | 
| 1475791277  | James Brown         | New York City       | 9 Bond Street, 4th Floor       | Brooklyn     | NY    | 11201    | (718) 613-3982 |                | James.Brown@labor.ny.gov?        | [http://www.labor.ny.gov/stats/nyc/index.shtm, null]   | 
| 1475791277  | Kevin Jack          | Statewide           | 1220 Washington Avenue         | Albany       | NY    | 12240    | (518) 457-3800 |                | Kevin.Jack@labor.ny.gov          | [http://www.labor.ny.gov/stats/index.shtm, null]       | 
| 1475791277  | James Ross          | Capital Region      | 175 Central Avenue             | Albany       | NY    | 12206    | (518) 242-8245 |                | James.Ross@labor.ny.gov          | [http://www.labor.ny.gov/stats/cap/index.shtm, null]   | 
| 1475791277  | John Nelson         | Hudson Valley       | 120 Bloomingdale Road          | White Plains | NY    | 10605    | (914) 997-8798 | (914) 997-4107 | Johny.Nelson@labor.ny.gov        | [http://www.labor.ny.gov/stats/hud/default.asp, null]  | 
| 1475791277  | Christian Harris    | Southern Tier       | 2001 Perimeter Road E. Suite 3 | Endicott     | NY    | 13760    | (607) 741-4485 | (607) 741-4527 | Christian.Harris@labor.ny.gov    | [http://www.labor.ny.gov/stats/sou/index.shtm, null]   | 
| 1475791277  | Shital Patel        | Long Island         | 303 W. Old Country Road        | Hicksville   | NY    | 11801    | (516) 934-8533 | (516) 433-3799 | Shital.Patel@labor.ny.gov        | [http://www.labor.ny.gov/stats/lon/index.shtm, null]   | 
```