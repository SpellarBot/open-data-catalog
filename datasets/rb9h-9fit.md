# Design & Construction Capital Projects Vendor Payments: Beginning 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/design-construction-capital-projects-vendor-payments-beginning-2014) |
| Metadata | [Link](https://data.ny.gov/api/views/rb9h-9fit) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rb9h-9fit/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rb9h-9fit/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rb9h-9fit |
| Name | Design & Construction Capital Projects Vendor Payments: Beginning 2014 |
| Attribution | New York State Office of General Services |
| Category | Economic Development |
| Tags | state contract, vendor payments, design and construction |
| Created | 2014-09-29T13:00:25Z |
| Publication Date | 2017-01-26T23:06:52Z |

## Description

This dataset provides the public with the value of individual payments made to vendors for Professional Services or Construction contacts, by State Contract number.  Data includes individual payments recorded in the specified time frame to vendors for the County in which the work was performed. Statewide payments are also included that are not County specific.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name            | Data Type | Render Type |
| ======== | ============== | ============== | =============== | ========= | =========== |
| Yes      | series tag     | contractnumber | Contract Number | text      | text        |
| Yes      | series tag     | vendor         | Vendor          | text      | text        |
| Yes      | series tag     | typeofservice  | Type Of Service | text      | text        |
| Yes      | numeric metric | paymentamount  | Payment Amount  | money     | money       |
| Yes      | series tag     | fiscalyear     | Fiscal Year     | text      | text        |
| Yes      | numeric metric | quarter        | Quarter         | number    | number      |
| Yes      | series tag     | county         | County          | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rb9h-9fit d:2014-01-01T00:00:00.000Z t:county=Albany t:vendor="HIGHLAND ASSOCIATES PC" t:typeofservice="Professional Services" t:contractnumber=OGS01-D0S1047-1140247 t:fiscalyear=2014-2015 m:paymentamount=13014 m:quarter=1

series e:rb9h-9fit d:2014-01-01T00:00:00.000Z t:county=Albany t:vendor="HIGHLAND ASSOCIATES PC" t:typeofservice="Professional Services" t:contractnumber=OGS01-D0S1047-1140247 t:fiscalyear=2014-2015 m:paymentamount=24079 m:quarter=1

series e:rb9h-9fit d:2014-01-01T00:00:00.000Z t:county=Albany t:vendor="HIGHLAND ASSOCIATES PC" t:typeofservice="Professional Services" t:contractnumber=OGS01-D0S1047-1140247 t:fiscalyear=2014-2015 m:paymentamount=38865 m:quarter=1
```

## Meta Commands

```ls
metric m:paymentamount p:double l:"Payment Amount" d:"Amount paid to vendor" t:dataTypeName=money

metric m:quarter p:integer l:Quarter d:"Quarter of Fiscal Year in which Payment was made" t:dataTypeName=number

entity e:rb9h-9fit l:"Design & Construction Capital Projects Vendor Payments:  Beginning 2014" t:attribution="New York State Office of General Services" t:url=https://data.ny.gov/api/views/rb9h-9fit

property e:rb9h-9fit t:meta.view v:id=rb9h-9fit v:category="Economic Development" v:attributionLink=http://www.ogs.ny.gov/BU/DC/ v:averageRating=0 v:name="Design & Construction Capital Projects Vendor Payments:  Beginning 2014" v:attribution="New York State Office of General Services"

property e:rb9h-9fit t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rb9h-9fit t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:rb9h-9fit t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| contractnumber        | vendor                 | typeofservice         | paymentamount | fiscalyear | quarter | county   | 
| ===================== | ====================== | ===================== | ============= | ========== | ======= | ======== | 
| OGS01-D0S1047-1140247 | HIGHLAND ASSOCIATES PC | Professional Services | 13014.00      | 2014-2015  | 1       | Albany   | 
| OGS01-D0S1047-1140247 | HIGHLAND ASSOCIATES PC | Professional Services | 24079.00      | 2014-2015  | 1       | Albany   | 
| OGS01-D0S1047-1140247 | HIGHLAND ASSOCIATES PC | Professional Services | 38865.00      | 2014-2015  | 1       | Albany   | 
| OGS01-D0S1047-1140247 | HIGHLAND ASSOCIATES PC | Professional Services | 4650.00       | 2014-2015  | 2       | Albany   | 
| OGS01-D0S2228-1140247 | URS CORPORATION-NY     | Professional Services | 34182.00      | 2014-2015  | 1       | Kings    | 
| OGS01-D0S2228-1140247 | URS CORPORATION-NY     | Professional Services | 44116.00      | 2014-2015  | 2       | Kings    | 
| OGS01-D0S2228-1140247 | URS CORPORATION-NY     | Professional Services | 59715.00      | 2014-2015  | 2       | Kings    | 
| OGS01-D0S2228-1140247 | URS CORPORATION-NY     | Professional Services | 100861.00     | 2014-2015  | 2       | Kings    | 
| OGS01-D0S2244-1140247 | TDX CONSTRUCTION CORP  | Professional Services | 5196.00       | 2014-2015  | 1       | New York | 
| OGS01-D0S2244-1140247 | TDX CONSTRUCTION CORP  | Professional Services | 139118.00     | 2014-2015  | 1       | New York | 
```