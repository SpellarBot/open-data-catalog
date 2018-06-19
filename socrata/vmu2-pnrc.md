# Contracts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-63144) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/vmu2-pnrc) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/vmu2-pnrc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/vmu2-pnrc/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | vmu2-pnrc |
| Name | Contracts |
| Category | Government |
| Tags | contracts, procurement, contract |
| Created | 2012-10-04T13:15:58Z |
| Publication Date | 2016-03-09T20:41:14Z |

## Description

The following dataset is a listing of all active County contracts.  This list is updated daily.  Contract spending information can be found at:  https://data.montgomerycountymd.gov/Finance-Tax-Property/Contract-Spending/wv2m-su7v

Update Frequency:  Daily

## Columns

```ls
| Included | Schema Type | Field Name             | Name                         | Data Type     | Render Type   |
| ======== | =========== | ====================== | ============================ | ============= | ============= |
| Yes      | series tag  | contractno             | Contract Number              | text          | text          |
| Yes      | series tag  | solicitationnumber     | SolicitationNumber           | text          | text          |
| Yes      | series tag  | buyerfirst             | Buyer First Name             | text          | text          |
| Yes      | series tag  | buyerlast              | Buyer Last Name              | text          | text          |
| Yes      | series tag  | buyerphone             | BuyerPhone                   | text          | text          |
| Yes      | series tag  | buyeremail             | BuyerEmail                   | text          | text          |
| Yes      | series tag  | buyertitle             | BuyerTitle                   | text          | text          |
| Yes      | series tag  | contracttype           | ContractType                 | text          | text          |
| Yes      | series tag  | contractdesc           | ContractDesc                 | text          | text          |
| Yes      | series tag  | vendor                 | Vendor                       | text          | text          |
| No       |             | vendoraddress          | Vendor Address Line 1        | text          | text          |
| No       |             | vendoraddress2         | Vendor Address Line 2        | text          | text          |
| Yes      | series tag  | vendorcity             | Vendor City                  | text          | text          |
| Yes      | series tag  | vendorst               | Vendor State                 | text          | text          |
| Yes      | series tag  | vendorzip              | Vendor Zip Code              | text          | text          |
| Yes      | series tag  | vendorcontact          | Vendor Contact               | text          | text          |
| Yes      | series tag  | vendoremail            | Vendor Email                 | text          | text          |
| Yes      | series tag  | vendorphone            | Vendor Phone Number          | text          | text          |
| Yes      | series tag  | nonprofit              | Non-Profit                   | text          | text          |
| Yes      | series tag  | deptname               | DeptName                     | text          | text          |
| Yes      | series tag  | division               | Division                     | text          | text          |
| Yes      | series tag  | cadmin                 | Contract Administrator       | text          | text          |
| Yes      | series tag  | cadminphone            | Contract Administrator Phone | text          | text          |
| Yes      | series tag  | cadminemail            | Contract Administrator Email | text          | text          |
| No       |             | execution              | Execution Date               | calendar_date | calendar_date |
| Yes      | time        | expiration             | Expiration Date              | calendar_date | calendar_date |
| No       |             | extend                 | Extend Date                  | calendar_date | calendar_date |
| Yes      | series tag  | prevailingwagecontract | Prevailing Wage Contracts    | text          | text          |
| Yes      | series tag  | livingwagecontract     | Living Wage Contracts        | text          | text          |
```

## Time Field

```ls
Value = expiration
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = vendoraddress,vendoraddress2,execution,extend
```

## Data Commands

```ls
series e:vmu2-pnrc d:2018-09-30T00:00:00.000Z t:vendorzip=02043 t:vendorst=MA t:cadminphone=240-777-5808 t:contractno=1030160 t:vendorcontact="Michael A. Geden" t:buyeremail=jeffrey.steed@MontgomeryCountyMD.gov t:vendor="DIRECT MEDIA INC" t:buyertitle="Procurement Specialist III" t:vendorcity=Hingham t:livingwagecontract=Yes t:cadmin="Ken Sloate" t:buyerphone=240-777-9914 t:contracttype="RFP - Non-Construction" t:division="Division of Transit Services" t:contractdesc="Ride On Bus Advertising Services & Transit Releated Advertising Services" t:buyerfirst=Jeffrey t:prevailingwagecontract=No t:solicitationnumber=1030160 t:cadminemail=Ken.Sloate@montgomerycountymd.gov t:nonprofit=No t:deptname="Department of Transportation" t:buyerlast=Steed m:row_number.vmu2-pnrc=1

series e:vmu2-pnrc d:2017-06-25T00:00:00.000Z t:vendorzip=20742 t:vendorphone=3014058108 t:vendorst=MD t:cadminphone=240-777-7719 t:contractno=1052680 t:vendorcontact="Danette Boone" t:buyeremail=Robert.Norris@MontgomeryCountyMD.gov t:vendor="University of Maryland" t:buyertitle="Procurement Specialist III" t:vendoremail=dboone14@umd.edu t:vendorcity="Colleg Park" t:livingwagecontract=No t:cadmin="Carmen Ruby" t:buyerphone=240-777-9926 t:contracttype="Public Entity" t:division="Director's Office" t:contractdesc="Environmental Finance and Analysis Consulting Services" t:buyerfirst=Robert t:prevailingwagecontract=No t:cadminemail=Carmen.Ruby@montgomerycountymd.gov t:nonprofit=Yes t:deptname="Department of Environmental Protection" t:buyerlast=Norris m:row_number.vmu2-pnrc=2

series e:vmu2-pnrc d:2018-02-23T00:00:00.000Z t:vendorzip=22801 t:vendorphone=5404345965 t:vendorst=VA t:cadminphone=240-777-8739 t:contractno=1061793 t:vendorcontact="Mike Nesselrodt" t:buyeremail=eric.harris@montgomerycountymd.gov t:vendor="Consonics, Inc" t:buyertitle="Procurement Specialist II" t:vendorcity=Harrisonburg t:livingwagecontract=No t:cadmin="Javier Torres" t:buyerphone=240-777-9922 t:contracttype=Non-Competitive t:division="Division of Parking Management" t:contractdesc="Parking Equipment Extended Warranty Coverage" t:buyerfirst=Eric t:prevailingwagecontract=No t:cadminemail=Javier.Torres@montgomerycountymd.gov t:nonprofit=No t:deptname="Department of Transportation" t:buyerlast=Harris m:row_number.vmu2-pnrc=3
```

## Meta Commands

```ls
metric m:row_number.vmu2-pnrc p:long l:"Row Number"

entity e:vmu2-pnrc l:Contracts t:url=https://data.montgomerycountymd.gov/api/views/vmu2-pnrc

property e:vmu2-pnrc t:meta.view v:id=vmu2-pnrc v:category=Government v:averageRating=0 v:name=Contracts

property e:vmu2-pnrc t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:vmu2-pnrc t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| contractno   | solicitationnumber | buyerfirst | buyerlast | buyerphone   | buyeremail                           | buyertitle                 | contracttype           | contractdesc                                                                                                                     | vendor                             | vendoraddress            | vendoraddress2                                    | vendorcity    | vendorst | vendorzip  | vendorcontact      | vendoremail                        | vendorphone  | nonprofit | deptname                               | division                               | cadmin            | cadminphone  | cadminemail                              | execution           | expiration          | extend              | prevailingwagecontract | livingwagecontract | 
| ============ | ================== | ========== | ========= | ============ | ==================================== | ========================== | ====================== | ================================================================================================================================ | ================================== | ======================== | ================================================= | ============= | ======== | ========== | ================== | ================================== | ============ | ========= | ====================================== | ====================================== | ================= | ============ | ======================================== | =================== | =================== | =================== | ====================== | ================== | 
| 1030160      | 1030160            | Jeffrey    | Steed     | 240-777-9914 | jeffrey.steed@MontgomeryCountyMD.gov | Procurement Specialist III | RFP - Non-Construction | Ride On Bus Advertising Services & Transit Releated Advertising Services                                                         | DIRECT MEDIA INC                   | 72 Sharp Street          | Unit C-12                                         | Hingham       | MA       | 02043      | Michael A. Geden   |                                    |              | No        | Department of Transportation           | Division of Transit Services           | Ken Sloate        | 240-777-5808 | Ken.Sloate@montgomerycountymd.gov        | 2015-10-01T00:00:00 | 2018-09-30T00:00:00 | 2020-09-30T00:00:00 | No                     | Yes                | 
| 1052680      |                    | Robert     | Norris    | 240-777-9926 | Robert.Norris@MontgomeryCountyMD.gov | Procurement Specialist III | Public Entity          | Environmental Finance and Analysis Consulting Services                                                                           | University of Maryland             | 3112 Lee Building        | Office of Research Administration and Advancement | Colleg Park   | MD       | 20742      | Danette Boone      | dboone14@umd.edu                   | 3014058108   | Yes       | Department of Environmental Protection | Director's Office                      | Carmen Ruby       | 240-777-7719 | Carmen.Ruby@montgomerycountymd.gov       | 2015-06-26T00:00:00 | 2017-06-25T00:00:00 | 2024-06-25T00:00:00 | No                     | No                 | 
| 1061793      |                    | Eric       | Harris    | 240-777-9922 | eric.harris@montgomerycountymd.gov   | Procurement Specialist II  | Non-Competitive        | Parking Equipment Extended Warranty Coverage                                                                                     | Consonics, Inc                     | 1350 Port Republic Road  |                                                   | Harrisonburg  | VA       | 22801      | Mike Nesselrodt    |                                    | 5404345965   | No        | Department of Transportation           | Division of Parking Management         | Javier Torres     | 240-777-8739 | Javier.Torres@montgomerycountymd.gov     | 2016-02-24T00:00:00 | 2018-02-23T00:00:00 | 2018-02-23T00:00:00 | No                     | No                 | 
| 8506000028AA | 8506000028         | Jeffrey    | Steed     | 240-777-9914 | jeffrey.steed@MontgomeryCountyMD.gov | Procurement Specialist III | Public Entity          | PUBLIC ENTITY GYPSY MOTH COUNT PROGRAM                                                                                           | STATE OF MARYLAND                  | 50 HARRY S. TRUMAN PKWK  |                                                   | ANNAPOLIS     | MD       | 21401      | DR. HENRY A. VIRTS |                                    |              | Yes       | Department of Transportation           |                                        | Leroy Anderson    | 2159         | Leroy.Anderson@montgomerycountymd.gov    |                     | 2099-01-01T00:00:00 | 2099-01-01T00:00:00 | No                     | No                 | 
| 1052748      | 1038745            | Robert     | Norris    | 240-777-9926 | Robert.Norris@MontgomeryCountyMD.gov | Procurement Specialist III | RFP - Non-Construction | Debris Management Services: Pre-Positioned Contracts                                                                             | Crowder Gulf, LLC                  | 5435 Business Parkway    |                                                   | Theodore      | AL       | 36582      | John Ramsay        | jramsay@crowdergulf.com            | 800-992-6207 | No        | Department of Environmental Protection | Division of Solid Waste Mgmt           | Peter Karasik     | 240-777-6569 | Peter.Karasik@montgomerycountymd.gov     | 2015-08-29T00:00:00 | 2022-08-28T00:00:00 | 2024-08-28T00:00:00 | No                     | Yes                | 
| 6504510208AA | 6504510208         | Robert     | Norris    | 240-777-9926 | Robert.Norris@MontgomeryCountyMD.gov | Procurement Specialist III | RFP - Non-Construction | Architectural/Engineering Services for 6th District Police Station: Design, Engineering and Construction Administration Services | Dewberry Architects, Inc.          | 8401 Arlington Boulevard |                                                   | Fairfax       | VA       | 22031-4666 | Eric D. Snellings  |                                    | 7036989050   | No        | Department of General Services         | Division of Bldg Design & Construction | Don Scheuerman    | 240-777-6075 | Don.Scheuerman@montgomerycountymd.gov    | 2006-09-26T00:00:00 | 2099-01-01T00:00:00 | 2099-01-01T00:00:00 | No                     | Yes                | 
| 1025092      | 1025092            | Jeffrey    | Steed     | 240-777-9914 | jeffrey.steed@MontgomeryCountyMD.gov | Procurement Specialist III | Open Solicitation      | Call-N-Ride Transportation Services (Taxicab Only)                                                                               | Sun Taxicab, Inc.                  | 8601 Georgia Ave.        | STE 703                                           | Silver Spring | MD       | 20910      | Andrew Moldawer    | andrew.mpldawer@veoliatransdev.com | 240-485-2123 | No        | Department of Transportation           | Division of Transit Services           | Ken Sloate        | 240-777-5808 | Ken.Sloate@montgomerycountymd.gov        | 2013-04-01T00:00:00 | 2018-03-31T00:00:00 | 2024-03-31T00:00:00 | No                     | Yes                | 
| 1052747      | 1038745            | Robert     | Norris    | 240-777-9926 | Robert.Norris@MontgomeryCountyMD.gov | Procurement Specialist III | RFP - Non-Construction | Debris Management Services: Pre-Positioned Contracts                                                                             | Ceres Environmental Services, Inc. | 3825 85th Avenue North   |                                                   | Brooklyn Park | MN       | 55443      | Gail Hanscom       | gail.hanscom@ceresenv.com          | 800-218-4424 | No        | Department of Environmental Protection | Division of Solid Waste Mgmt           | Peter Karasik     | 240-777-6569 | Peter.Karasik@montgomerycountymd.gov     | 2015-08-29T00:00:00 | 2022-08-28T00:00:00 | 2024-08-28T00:00:00 | No                     | Yes                | 
| 1023018      | 1023018            | Karen      | DeLuca    | 240-777-9917 | karen.deluca@montgomerycountymd.gov  | Procurement Specialist III | Bridge Contract        | Billing for Emergency Medical Transport Services and Associated Services                                                         | Med3000, Inc.                      | 3131 Newmark Dr.Ste. 100 |                                                   | Miamisburg    | OH       | 45342      | Glenn Goodpaster   | glenn_goodpaster@med3000.com       | 9376607002   | No        | Fire & Rescue Services                 | Office of the Fire Chief               | Andres Olaciregui | 240-777-2481 | Andres.Olaciregui@montgomerycountymd.gov | 2013-02-15T00:00:00 | 2017-12-31T00:00:00 | 2022-12-31T00:00:00 | No                     | No                 | 
| 8508000351AA | 8508000351         | Jeffrey    | Steed     | 240-777-9914 | jeffrey.steed@MontgomeryCountyMD.gov | Procurement Specialist III | Open Solicitation      | Medicaid and Call-N-Ride Transportation Services.                                                                                | THERESE T SIMS T/A EXACT           | ENTERPRISE               | 1629 K ST NW STE 300                              | WASHINGTON    | DC       | 20036      | THERESE T SIMS     |                                    | 3018617617   | No        | Department of Transportation           | Division of Transit Services           | Ken Sloate        | 240-777-5808 | Ken.Sloate@montgomerycountymd.gov        | 2008-06-30T00:00:00 | 2099-01-01T00:00:00 | 2099-01-01T00:00:00 | No                     | Yes                | 
```