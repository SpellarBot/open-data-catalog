# Traffic Tickets Issued: Four Year Window

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/traffic-tickets-issued-beginning-2008) |
| Metadata | [Link](https://data.ny.gov/api/views/q4hy-kbtf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/q4hy-kbtf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/q4hy-kbtf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | q4hy-kbtf |
| Name | Traffic Tickets Issued: Four Year Window |
| Attribution | NYS DMV ? Data Services |
| Category | Transportation |
| Tags | nysdmv, tickets, violations, traffic, enforcement, law, vehicle, driver |
| Created | 2014-06-12T15:58:51Z |
| Publication Date | 2015-09-14T22:27:13Z |

## Description

Data extracted from records of tickets on file with NYS DMV. The tickets were issued to motorists for violations of:  NYS Vehicle & Traffic Law (VTL), Thruway Rules and Regulations, Tax Law, Transportation Law, Parks and Recreation Regulations, Local New York City Traffic Ordinances, and NYS Penal Law pertaining to the involvement of a motor vehicle in acts of assault, homicide, manslaughter and criminal negligence resulting in injury or death.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | violation_charged_code | Violation Charged Code | text      | text        |
| Yes      | series tag     | violation_description  | Violation Description  | text      | text        |
| Yes      | time           | violation_year         | Violation Year         | number    | number      |
| Yes      | numeric metric | violation_month        | Violation Month        | number    | number      |
| Yes      | series tag     | violation_dow          | Violation Day of Week  | text      | text        |
| Yes      | numeric metric | age_at_violation       | Age at Violation       | number    | number      |
| Yes      | series tag     | gender                 | Gender                 | text      | text        |
| Yes      | series tag     | state_of_license       | State of License       | text      | text        |
| Yes      | series tag     | police_agency          | Police Agency          | text      | text        |
| Yes      | series tag     | court                  | Court                  | text      | text        |
| Yes      | series tag     | source                 | Source                 | text      | text        |
```

## Time Field

```ls
Value = violation_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:q4hy-kbtf d:2014-01-01T00:00:00.000Z t:state_of_license="NEW YORK" t:source=TSLED t:police_agency="SYRACUSE POLICE DEPT" t:violation_charged_code=4024 t:violation_dow=FRIDAY t:court="SYRACUSE CITY COURT" t:gender=F t:violation_description="IMPROPER PLATES" m:age_at_violation=45 m:violation_month=6

series e:q4hy-kbtf d:2014-01-01T00:00:00.000Z t:state_of_license="NEW YORK" t:source=TSLED t:police_agency="SUFFOLK COUNTY POLICE DEPT" t:violation_charged_code=37510A t:violation_dow=TUESDAY t:court="SUFFOLK DISTRICT COURT" t:gender=M t:violation_description="NO MIRROR/NO LEFTSIDE VIEW MIRROR" m:age_at_violation=22 m:violation_month=11

series e:q4hy-kbtf d:2014-01-01T00:00:00.000Z t:state_of_license=UNKNOWN t:source=TSLED t:police_agency="FREEPORT VILLAGE POLICE DEPT" t:violation_charged_code=1140A t:violation_dow=THURSDAY t:court="FREEPORT VILLAGE COURT" t:gender=F t:violation_description="FLD TO YLD RT-OF-WAY AT INTERSECTION" m:age_at_violation=63 m:violation_month=8
```

## Meta Commands

```ls
metric m:violation_month p:integer l:"Violation Month" d:"Month in which the ticket was issued. 1=January; 12=December." t:dataTypeName=number

metric m:age_at_violation p:integer l:"Age at Violation" d:"Age, in years, of the person to whom the ticket was issued on the date of ticket issuance." t:dataTypeName=number

entity e:q4hy-kbtf l:"Traffic Tickets Issued: Four Year Window" t:attribution="NYS DMV ? Data Services" t:url=https://data.ny.gov/api/views/q4hy-kbtf

property e:q4hy-kbtf t:meta.view v:id=q4hy-kbtf v:category=Transportation v:attributionLink=http://dmv.ny.gov/nav/tickets-points-penalties v:averageRating=0 v:name="Traffic Tickets Issued: Four Year Window" v:attribution="NYS DMV ? Data Services"

property e:q4hy-kbtf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:q4hy-kbtf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:q4hy-kbtf t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| violation_charged_code | violation_description                | violation_year | violation_month | violation_dow | age_at_violation | gender | state_of_license | police_agency                 | court                   | source | 
| ====================== | ==================================== | ============== | =============== | ============= | ================ | ====== | ================ | ============================= | ======================= | ====== | 
| 4024                   | IMPROPER PLATES                      | 2014           | 6               | FRIDAY        | 45               | F      | NEW YORK         | SYRACUSE POLICE DEPT          | SYRACUSE CITY COURT     | TSLED  | 
| 37510A                 | NO MIRROR/NO LEFTSIDE VIEW MIRROR    | 2014           | 11              | TUESDAY       | 22               | M      | NEW YORK         | SUFFOLK COUNTY POLICE DEPT    | SUFFOLK DISTRICT COURT  | TSLED  | 
| 1140A                  | FLD TO YLD RT-OF-WAY AT INTERSECTION | 2014           | 8               | THURSDAY      | 63               | F      | UNKNOWN          | FREEPORT VILLAGE POLICE DEPT  | FREEPORT VILLAGE COURT  | TSLED  | 
| 1225C2A                | OPERATING MV MOBILE PHONE            | 2013           | 6               | TUESDAY       | 36               | F      | CONNECTICUT      | TRIBOROUGH BRIDGE TUNNEL AUTH | QUEENS NORTH TVB        | TVB    | 
| 1180D1A                | SPEED IN ZONE 11-30                  | 2014           | 5               | MONDAY        | 62               | M      | NEW YORK         | NYC POLICE DEPT               | BROOKLYN SOUTH TVB      | TVB    | 
| 37540B                 | INADEQUATE OR NO STOP LAMPS          | 2014           | 3               | FRIDAY        | 53               | F      | NEW YORK         | ROCHESTER POLICE DEPT         | ROCHESTER TVB           | TVB    | 
| 5111A                  | AGGRAVATED UNLIC OPER 3RD MISD       | 2014           | 9               | FRIDAY        | 34               | M      | NEW YORK         | CHEEKTOWAGA POLICE DEPT       | CHEEKTOWAGA TOWN COURT  | TSLED  | 
| 1110A                  | DISOBEYED TRAFFIC DEVICE             | 2013           | 9               | WEDNESDAY     | 37               | F      | VIRGINIA         | NYC POLICE DEPT               | BROOKLYN SOUTH TVB      | TVB    | 
| 37540A                 | INADEQUATE OR NO STOP LAMP OR LAMPS  | 2013           | 5               | FRIDAY        | 52               | M      | NEW YORK         | PEEKSKILL CITY POLICE DEPT    | PEEKSKILL CITY COURT    | TSLED  | 
| 1172A                  | FLD TO STOP AT STOP SIGN             | 2012           | 11              | WEDNESDAY     | 30               | M      | NEW YORK         | NEW ROCHELLE CITY POLICE DEPT | NEW ROCHELLE CITY COURT | TSLED  | 
```