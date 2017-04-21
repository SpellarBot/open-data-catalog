# FDNY Fire Department Fire Code Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-fire-department-fire-code-data-1e743) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/msp3-x6rs) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/msp3-x6rs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/msp3-x6rs/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | msp3-x6rs |
| Name | FDNY Fire Department Fire Code Data |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, safety, fire safety, fire code, building standards |
| Created | 2013-01-23T16:47:07Z |
| Publication Date | 2013-01-29T15:37:21Z |

## Description

Lists the standards that are referenced in the code.

## Columns

```ls
| Included | Schema Type | Field Name                    | Name                          | Data Type | Render Type |
| ======== | =========== | ============================= | ============================= | ========= | =========== |
| No       | time        | :updated_at                   | updated_at                    | meta_data | meta_data   |
| Yes      | series tag  | standard_code                 | Standard Code                 | text      | text        |
| Yes      | series tag  | standard_name                 | Standard Name                 | text      | text        |
| No       |             | standard_agency_address       | Standard Agency Address       | text      | text        |
| Yes      | series tag  | standard_reference_number     | Standard Reference Number     | text      | text        |
| Yes      | series tag  | standard_title                | Standard Title                | text      | text        |
| Yes      | series tag  | reference_code_section_number | Reference Code Section Number | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = standard_agency_address
```

## Data Commands

```ls
series e:msp3-x6rs d:2013-01-23T08:47:09.000Z t:standard_code=ANSI t:standard_name="American National Standards Institute" t:reference_code_section_number="2609.3, 2703.2.2.1, 3003.2.3, 3403.5.2" t:standard_reference_number=A13.1?96 t:standard_title="Scheme for the Identification of Piping Systems" m:row_number.msp3-x6rs=1

series e:msp3-x6rs d:2013-01-23T08:47:09.000Z t:standard_code=ANSI t:standard_name="American National Standards Institute" t:reference_code_section_number=2703.2.2.2 t:standard_reference_number=B31.3?99 t:standard_title="Process Piping, including addendum" m:row_number.msp3-x6rs=2

series e:msp3-x6rs d:2013-01-23T08:47:09.000Z t:standard_code=ANSI t:standard_name="American National Standards Institute" t:reference_code_section_number="3403.6.2.1, 3403.6.3, 3403.6.11" t:standard_reference_number=B31.9?96 t:standard_title="Building Services Piping Code for Pressure Piping" m:row_number.msp3-x6rs=3
```

## Meta Commands

```ls
metric m:row_number.msp3-x6rs p:long l:"Row Number"

entity e:msp3-x6rs l:"FDNY Fire Department Fire Code Data" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/msp3-x6rs

property e:msp3-x6rs t:meta.view v:id=msp3-x6rs v:category="Public Safety" v:attributionLink="http://www.nyc.gov/html/fdny/pdf/firecode/2013/fire_code_ll26_2008_amended_ll37_39_41_64_2009_ll2_2013.pdf#page=617" v:averageRating=0 v:name="FDNY Fire Department Fire Code Data" v:attribution="Fire Department of New York City (FDNY)"

property e:msp3-x6rs t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:msp3-x6rs t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| :updated_at | standard_code | standard_name                                | standard_agency_address                              | standard_reference_number | standard_title                                                                      | reference_code_section_number          | 
| =========== | ============= | ============================================ | ==================================================== | ========================= | =================================================================================== | ====================================== | 
| 1358930829  | ANSI          | American National Standards Institute        | 25 West 43rd Street, Fourth Floor New York, NY 10036 | A13.1?96                  | Scheme for the Identification of Piping Systems                                     | 2609.3, 2703.2.2.1, 3003.2.3, 3403.5.2 | 
| 1358930829  | ANSI          | American National Standards Institute        | 26 West 43rd Street, Fourth Floor New York, NY 10036 | B31.3?99                  | Process Piping, including addendum                                                  | 2703.2.2.2                             | 
| 1358930829  | ANSI          | American National Standards Institute        | 27 West 43rd Street, Fourth Floor New York, NY 10036 | B31.9?96                  | Building Services Piping Code for Pressure Piping                                   | 3403.6.2.1, 3403.6.3, 3403.6.11        | 
| 1358930829  | API           | American Petroleum Institute                 | 1220 L Street, Northwest Washington, DC 20005        | 650?1998                  | Welded Steel Tanks for Oil Storage                                                  | 3406.8.3                               | 
| 1358930829  | API           | American Petroleum Institute                 | 1221 L Street, Northwest Washington, DC 20005        | RP 1604?1996              | Closure of Underground Petroleum Storage Tanks                                      | 3404.2.13                              | 
| 1358930829  | API           | American Petroleum Institute                 | 1222 L Street, Northwest Washington, DC 20005        | Std 2000?1998             | Venting Atmosphere and Low Pressure Storage Tanks: Nonrefrigerated and Refrigerated | 3404.2.7.3.6                           | 
| 1358930829  | API           | American Petroleum Institute                 | 1223 L Street, Northwest Washington, DC 20005        | Publ 2028?1991            | Flame Arrestors in Piping Systems                                                   | 3404.2.7.3.2                           | 
| 1358930829  | API           | American Petroleum Institute                 | 1224 L Street, Northwest Washington, DC 20005        | RP 2350?1996              | Overfill Protection for Storage Tanks in Petroleum Facilities                       | 3406.4.6                               | 
| 1358930829  | ASME          | The American Society of Mechanical Engineers | Three Park Avenue New York, NY 10016-5990            | A17.1?2000                | Safety Code for Elevators and Escalators                                            | 607.1                                  | 
| 1358930829  | ASME          | The American Society of Mechanical Engineers | Three Park Avenue New York, NY 10016-5991            | A17.3?1996                | Safety Code for Existing Elevators and Escalators with A17.3a-2000 Addenda          | 607.1                                  | 
```