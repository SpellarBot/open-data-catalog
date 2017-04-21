# Businesses Registered with EBR Parish

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/businesses-registered-with-ebr-parish) |
| Metadata | [Link](https://data.brla.gov/api/views/xw6s-bcqm) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/xw6s-bcqm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/xw6s-bcqm/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | xw6s-bcqm |
| Name | Businesses Registered with EBR Parish |
| Attribution | Finance Department |
| Category | Business and Financial |
| Tags | business, ownership, naic |
| Created | 2014-10-18T12:01:53Z |
| Publication Date | 2017-01-20T15:48:46Z |

## Description

All businesses registered with EBR Parish for Occupational License Tax and/or Sales Tax Registration. This dataset includes both active and inactive businesses.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                        | Data Type     | Render Type   |
| ======== | ============== | ================== | =========================== | ============= | ============= |
| Yes      | series tag     | taccount           | ACCOUNT NO                  | text          | text          |
| Yes      | series tag     | tname              | ACCOUNT NAME                | text          | text          |
| Yes      | series tag     | tlegalname         | LEGAL NAME                  | text          | text          |
| Yes      | series tag     | tacctlocation      | ACCOUNT LOCATION CODE       | text          | text          |
| Yes      | series tag     | location           | ACCOUNT LOCATION            | text          | text          |
| Yes      | series tag     | tcontactperson     | CONTACT PERSON              | text          | text          |
| Yes      | time           | topendate          | BUSINESS OPEN DATE          | calendar_date | calendar_date |
| Yes      | series tag     | tstatus            | BUSINESS STATUS             | text          | text          |
| No       |                | tclosedate         | BUSINESS CLOSE DATE         | calendar_date | calendar_date |
| Yes      | series tag     | townership         | OWNERSHIP TYPE              | text          | text          |
| Yes      | series tag     | taccttype          | ACCOUNT TYPE CODE           | text          | text          |
| Yes      | series tag     | typename           | ACCOUNT TYPE                | text          | text          |
| Yes      | series tag     | tnaic              | NAICS Code                  | text          | text          |
| Yes      | series tag     | naicname           | NAICS CATEGORY              | text          | text          |
| Yes      | series tag     | naicgroupname      | NAICS GROUP                 | text          | text          |
| Yes      | series tag     | tabc               | ABC STATUS CODE             | text          | text          |
| Yes      | series tag     | abcname            | ABC STATUS                  | text          | text          |
| Yes      | numeric metric | consolidated_filer | CONSOLIDATED FILER          | number        | number        |
| No       |                | tmailaddress1      | MAILING ADDRESS - LINE 1    | text          | text          |
| No       |                | tmailaddress2      | MAILING ADDRESS - LINE 2    | text          | text          |
| No       |                | tmailcity          | MAILING ADDRESS - CITY      | text          | text          |
| No       |                | tmailstate         | MAILING ADDRESS - STATE     | text          | text          |
| No       |                | tmailzipcode5      | MAILING ADDRESS - ZIP CODE  | text          | text          |
| No       |                | tphysicaladdress1  | PHYSICAL ADDRESS - LINE 1   | text          | text          |
| No       |                | tphysicaladdress2  | PHYSICAL ADDRESS - LINE 2   | text          | text          |
| No       |                | tphysicalcity      | PHYSICAL ADDRESS - CITY     | text          | text          |
| No       |                | tphysicalstate     | PHYSICAL ADDRESS - STATE    | text          | text          |
| No       |                | tphysicalzipcode5  | PHYSICAL ADDRESS - ZIP CODE | text          | text          |
```

## Time Field

```ls
Value = topendate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = tclosedate,tmailaddress1,tmailaddress2,tmailcity,tmailstate,tmailzipcode5,tphysicaladdress1,tphysicaladdress2,tphysicalcity,tphysicalstate,tphysicalzipcode5
```

## Data Commands

```ls
series e:xw6s-bcqm d:2016-07-01T00:00:00.000Z t:tnaic=454000 t:location="Outside EBR Parish" t:tstatus=O t:tlegalname="TODD HINE" t:taccount=00921479 t:naicname="Nonstore Retailers" t:naicgroupname="RETAIL TRADE (G)" t:tabc=0 t:tacctlocation=0009 t:typename="No Occupational License" t:tname="TODD HINE" t:tcontactperson="AMANDA PARRETT" t:taccttype=9999 t:townership=INDV t:abcname="Not  a  ABC vendor" m:consolidated_filer=0

series e:xw6s-bcqm d:1988-04-06T00:00:00.000Z t:tnaic=811000 t:location="Baker (Baker School Distrtict)" t:tstatus=O t:tlegalname="JOSEPH G FERTITTA" t:taccount=00293055 t:naicname="Repair & Maintenance" t:naicgroupname="OTHER SERVICES (I)" t:tabc=0 t:tacctlocation=0003 t:typename="No Occupational License" t:tname="J&J STARTER SHOP" t:tcontactperson="FERTITTA  JOSEPH G" t:taccttype=9999 t:townership=UNKN t:abcname="Not  a  ABC vendor" m:consolidated_filer=0

series e:xw6s-bcqm d:2017-01-02T00:00:00.000Z t:tnaic=454000 t:location="Outside Louisiana" t:tstatus=O t:tlegalname="WOOT INC" t:taccount=00922645 t:naicname="Nonstore Retailers" t:naicgroupname="RETAIL TRADE (G)" t:tabc=0 t:tacctlocation=0010 t:typename="No Occupational License" t:tname="WOOT INC" t:tcontactperson="JIM JACKSON" t:taccttype=9999 t:townership=CORP t:abcname="Not  a  ABC vendor" m:consolidated_filer=0
```

## Meta Commands

```ls
metric m:consolidated_filer p:integer l:"CONSOLIDATED FILER" d:"Indicates whether the business is filing as consolidated (1 = Yes, 0 = No)." t:dataTypeName=number

entity e:xw6s-bcqm l:"Businesses Registered with EBR Parish" t:attribution="Finance Department" t:url=https://data.brla.gov/api/views/xw6s-bcqm

property e:xw6s-bcqm t:meta.view v:id=xw6s-bcqm v:category="Business and Financial" v:attributionLink=http://brgov.com/dept/finance v:averageRating=0 v:name="Businesses Registered with EBR Parish" v:attribution="Finance Department"

property e:xw6s-bcqm t:meta.view.license v:name="Public Domain"

property e:xw6s-bcqm t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:xw6s-bcqm t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| taccount | tname                        | tlegalname                   | tacctlocation | location                       | tcontactperson           | topendate           | tstatus | tclosedate          | townership | taccttype | typename                | tnaic  | naicname                      | naicgroupname       | tabc | abcname          | consolidated_filer | tmailaddress1 | tmailaddress2           | tmailcity | tmailstate | tmailzipcode5 | tphysicaladdress1 | tphysicaladdress2          | tphysicalcity | tphysicalstate | tphysicalzipcode5 | 
| ======== | ============================ | ============================ | ============= | ============================== | ======================== | =================== | ======= | =================== | ========== | ========= | ======================= | ====== | ============================= | =================== | ==== | ================ | ================== | ============= | ======================= | ========= | ========== | ============= | ================= | ========================== | ============= | ============== | ================= | 
| 00921479 | TODD HINE                    | TODD HINE                    | 0009          | Outside EBR Parish             | AMANDA PARRETT           | 2016-07-01T00:00:00 | O       |                     | INDV       | 9999      | No Occupational License | 454000 | Nonstore Retailers            | RETAIL TRADE (G)    | 0    | Not a ABC vendor | 0                  |               | 4327 HWY 27 S           | SULPHUR   | LA         | 70665         |                   | 4327 HWY 27 S              | SULPHUR       | LA             | 70665             | 
| 00293055 | J&J STARTER SHOP             | JOSEPH G FERTITTA            | 0003          | Baker (Baker School Distrtict) | FERTITTA JOSEPH G        | 1988-04-06T00:00:00 | O       |                     | UNKN       | 9999      | No Occupational License | 811000 | Repair & Maintenance          | OTHER SERVICES (I)  | 0    | Not a ABC vendor | 0                  |               | 1814 B MAIN             | BAKER     | LA         | 70714         |                   | 01814 B MAIN               | BAKER         | LA             | 70714             | 
| 00922645 | WOOT INC                     | WOOT INC                     | 0010          | Outside Louisiana              | JIM JACKSON              | 2017-01-02T00:00:00 | O       |                     | CORP       | 9999      | No Occupational License | 454000 | Nonstore Retailers            | RETAIL TRADE (G)    | 0    | Not a ABC vendor | 0                  |               | PO BOX 81207            | SEATTLE   | WA         | 98108         |                   | 4121 INTERNATIONAL PARKWAY | CARROLLTON    | TX             | 75007             | 
| 00443395 | AVANTI                       | AVANTI                       | 0010          | Outside Louisiana              |                          | 1995-05-01T00:00:00 | O       |                     | UNKN       | 9999      | No Occupational License | 453000 | Miscellaneous Store Retailers | RETAIL TRADE (G)    | 0    | Not a ABC vendor | 0                  |               | 905 WALL ST             | REDDING   | LA         | 96002         |                   | 07000 DANYEUR              | REDDING       | CA             | 96001             | 
| 00455926 | TERMCOR                      | TERMCOR                      | 0010          | Outside Louisiana              |                          | 1995-09-01T00:00:00 | C       | 2012-06-30T00:00:00 | UNKN       | 9999      | No Occupational License | 236000 | Construction of Buildings     | CONSTRUCTION ( C )  | 0    | Not a ABC vendor | 0                  |               | 498 NORTH LOOP 336 EAST | CONROE    | TX         | 77301         |                   | 498 NORTH LOOP 336 EAST    | CONROE        | TX             | 77301             | 
| 00609342 | PENINSULAR SLATE CO OF TEXAS | PENINSULAR SLATE CO OF TEXAS | 0010          | Outside Louisiana              |                          | 1999-12-01T00:00:00 | O       |                     | UNKN       | 9999      | No Occupational License | 454000 | Nonstore Retailers            | RETAIL TRADE (G)    | 0    | Not a ABC vendor | 0                  |               | P O BOX 1126            | TROY M    | LA         | 48099         |                   | 01166 E BIG BEAVER RD      | TROY          | MI             | 48099             | 
| 00630023 | VERIFONE INC                 | VERIFONE INC                 | 0010          | Outside Louisiana              | LYNDA HAUSWIRTH          | 2000-06-01T00:00:00 | O       |                     | CORP       | 9999      | No Occupational License | 454000 | Nonstore Retailers            | RETAIL TRADE (G)    | 0    | Not a ABC vendor | 0                  |               | 88 WEST PLUMERIA DR     | SAN JOSE  | CA         | 95134         |                   | 88 WEST PLUMERIA DR        | SAN JOSE      | CA             | 95134             | 
| 00682675 | LOUISIANA MOTORS             | LOUISIANA MOTORS             | 0009          | Outside EBR Parish             |                          | 2001-09-01T00:00:00 | O       |                     | UNKN       | 9999      | No Occupational License | 532000 | Rental & Leasing Services     | FINANCE & INSURANCE | 0    | Not a ABC vendor | 0                  |               | P O BOX 90209           | LAFAYETTE | LA         | 70509         |                   | 00900 E SIMCOE ST          | LAFAYETTE     | LA             | 70509             | 
| 00768727 | NASCO SERVICES               | NASCO SERVICES               | 0010          | Outside Louisiana              | NASCO SERVICES           | 2004-06-01T00:00:00 | O       |                     | UNKN       | 9999      | No Occupational License | 454000 | Nonstore Retailers            | RETAIL TRADE (G)    | 0    | Not a ABC vendor | 0                  |               | 2201 ROYAL LN STE 230   | IRVING    | TX         | 75063         |                   | 02201 ROYAL LN             | IRVING        | TX             | 75063             | 
| 00820902 | QUALITY RENTAL TOOLS INC     | QUALITY RENTAL TOOLS INC     | 0009          | Outside EBR Parish             | QUALITY RENTAL TOOLS INC | 2005-12-02T00:00:00 | O       |                     | CORP       | 9999      | No Occupational License | 454000 | Nonstore Retailers            | RETAIL TRADE (G)    | 0    | Not a ABC vendor | 0                  |               | PO BOX 2218             | HOUMA     | LA         | 70361         |                   | 2218                       | HOUMA         | LA             | 70361             | 
```