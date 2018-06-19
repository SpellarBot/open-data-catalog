# Active Trademark Registrations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/active-trademark-registrations-72ae8) |
| Metadata | [Link](https://data.oregon.gov/api/views/ny3n-dx3v) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ny3n-dx3v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ny3n-dx3v/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ny3n-dx3v |
| Name | Active Trademark Registrations |
| Category | Business |
| Tags | trademark, service mark, registration |
| Created | 2011-02-02T16:02:47Z |
| Publication Date | 2017-04-11T19:06:34Z |

## Description

(Updated 4/10/2017) List of trademark registrations that are active on the record of the Secretary of State Corporation Division as of the end of the previous month.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag  | registration_number   | Registration Number   | text          | text          |
| Yes      | time        | registration_date     | Registration Date     | calendar_date | calendar_date |
| Yes      | series tag  | trademark_description | Trademark Description | text          | text          |
| Yes      | series tag  | correspondent_name    | Correspondent Name    | text          | text          |
| No       |             | address1              | Address1              | text          | text          |
| No       |             | address2              | Address2              | text          | text          |
| Yes      | series tag  | city                  | City                  | text          | text          |
| Yes      | series tag  | state                 | State                 | text          | text          |
| Yes      | series tag  | zip                   | Zip                   | text          | text          |
| Yes      | series tag  | image_link            | Image Link            | url           | url           |
```

## Time Field

```ls
Value = registration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address1,address2
```

## Data Commands

```ls
series e:ny3n-dx3v d:1968-03-15T00:00:00.000Z t:zip=90049 t:state=CA t:image_link="http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=102&sm_schedule=2007-0027-133&bool" t:trademark_description="""SR""  MONOGRAM" t:registration_number=102 t:city="LOS ANGELES" t:correspondent_name="SUNRIVER RESORT LIMITED PARTNERSHIP" m:row_number.ny3n-dx3v=1

series e:ny3n-dx3v d:1968-03-15T00:00:00.000Z t:zip=90049 t:state=CA t:image_link="http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=103&sm_schedule=2007-0027-133&bool" t:trademark_description="""SUNRIVER""" t:registration_number=103 t:city="LOS ANGELES" t:correspondent_name="SUNRIVER RESORT LIMITED PARTNERSHIP" m:row_number.ny3n-dx3v=2

series e:ny3n-dx3v d:1969-01-24T00:00:00.000Z t:zip=97214 t:state=OR t:image_link="http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=158&sm_schedule=2007-0027-133&bool" t:trademark_description="THREE TENNIS BALLS AND FOUR TENNIS RACQUETS" t:registration_number=158 t:city=PORTLAND t:correspondent_name="WEST HILLS RACQUET CLUB" m:row_number.ny3n-dx3v=3
```

## Meta Commands

```ls
metric m:row_number.ny3n-dx3v p:long l:"Row Number"

entity e:ny3n-dx3v l:"Active Trademark Registrations" t:url=https://data.oregon.gov/api/views/ny3n-dx3v

property e:ny3n-dx3v t:meta.view v:id=ny3n-dx3v v:category=Business v:averageRating=0 v:name="Active Trademark Registrations"

property e:ny3n-dx3v t:meta.view.license v:name="Public Domain"

property e:ny3n-dx3v t:meta.view.owner v:id=ngr9-eh9y v:screenName="Judy Weems" v:displayName="Judy Weems"

property e:ny3n-dx3v t:meta.view.tableauthor v:id=ngr9-eh9y v:screenName="Judy Weems" v:roleName=editor v:displayName="Judy Weems"
```

## Top Records

```ls
| registration_number | registration_date   | trademark_description                                                                                                                                                 | correspondent_name                  | address1                         | address2         | city        | state | zip        | image_link                                                                                                                         | 
| =================== | =================== | ===================================================================================================================================================================== | =================================== | ================================ | ================ | =========== | ===== | ========== | ================================================================================================================================== | 
| 102                 | 1968-03-15T00:00:00 | "SR" MONOGRAM                                                                                                                                                         | SUNRIVER RESORT LIMITED PARTNERSHIP | 11777 SAN VICENTE STE 900        |                  | LOS ANGELES | CA    | 90049      | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=102&sm_schedule=2007-0027-133&bool, null]  | 
| 103                 | 1968-03-15T00:00:00 | "SUNRIVER"                                                                                                                                                            | SUNRIVER RESORT LIMITED PARTNERSHIP | 11777 SAN VICENTE STE 900        |                  | LOS ANGELES | CA    | 90049      | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=103&sm_schedule=2007-0027-133&bool, null]  | 
| 158                 | 1969-01-24T00:00:00 | THREE TENNIS BALLS AND FOUR TENNIS RACQUETS                                                                                                                           | WEST HILLS RACQUET CLUB             | C/O NORTH PACIFIC MANAGEMENT INC | 1905 SE 10TH AVE | PORTLAND    | OR    | 97214      | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=158&sm_schedule=2007-0027-133&bool, null]  | 
| 272                 | 1970-10-26T00:00:00 | G.I. TYPE CHARACTER OF A MAN WITH A JARHEAD - TAKE OFF OF A MARINE                                                                                                    | ROBERT C WICKMAN                    | 720 MENLO DRIVE N                |                  | SALEM       | OR    | 97303      | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=272&sm_schedule=2007-0027-133&bool, null]  | 
| 3606                | 1935-02-01T00:00:00 | "PYREX"                                                                                                                                                               | MICHELE N KEEFER-MEHLENBACHER       | CORNING INCORPORATED             | SP-TI-3-1        | CORNING     | NY    | 14831      | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=3606&sm_schedule=2007-0027-133&bool, null] | 
| 3957                | 1936-04-21T00:00:00 | "CORNING"                                                                                                                                                             | MICHELE N KEEFER-MEHLENBACHER       | CORNING INCORPORATED             | SP-TI-3-1        | CORNING     | NY    | 14831      | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=3957&sm_schedule=2007-0027-133&bool, null] | 
| 4020                | 1936-08-29T00:00:00 | "MOLY-KROME"                                                                                                                                                          | PACIFIC MACHINERY & TOOL STEEL CO   | 3445 NW LUZON ST                 |                  | PORTLAND    | OR    | 97210      | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=4020&sm_schedule=2007-0027-133&bool, null] | 
| 4622                | 2000-10-06T00:00:00 | THE WORDS "CAPPUCCINO COWBOY" WITH A LOGO OF A BUCKING HORSE RIDDEN BY A COWBOY HOLDING A CUP OF COFFEE AT ARMS LENGTH, HEAD LEVEL. THE HORSE HAS A BRAND MARKED CCC. | TLC INC                             | PO BOX 159                       |                  | RONAN       | MT    | 59864      | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=4622&sm_schedule=2007-0027-133&bool, null] | 
| 4838                | 1940-06-14T00:00:00 | "ACRALLOY"                                                                                                                                                            | PACIFIC MACHINERY & TOOL STEEL CO   | 3445 NW LUZON ST                 |                  | PORTLAND    | OR    | 97210-1694 | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=4838&sm_schedule=2007-0027-133&bool, null] | 
| 5639                | 1945-01-29T00:00:00 | "GOLD BRICK" RED LETTERS ON GOLD BACKGROUND                                                                                                                           | ELMER CANDY CORPORATION             | PO BOX 788                       | ATTN: SUE WALL   | PONCHATOULA | LA    | 70454-0788 | [http://records.sos.state.or.us/webdrawer/webdrawer.dll/webdrawer/search/rec&sm_anyword=5639&sm_schedule=2007-0027-133&bool, null] | 
```