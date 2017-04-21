# Vendor Payments (Purchase Order Summary)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vendor-payments-purchase-order-summary-e68d7) |
| Metadata | [Link](https://data.sfgov.org/api/views/p5r5-fd7g) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/p5r5-fd7g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/p5r5-fd7g/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | p5r5-fd7g |
| Name | Vendor Payments (Purchase Order Summary) |
| Attribution | SF Controller's Office |
| Category | City Management and Ethics |
| Tags | spending, amount, vendor, purchase order, sfopenbook, open book, openbook |
| Created | 2014-03-26T21:58:58Z |
| Publication Date | 2014-10-07T16:00:09Z |

## Description

The San Francisco Controller's Office maintains a database of payments made to vendors from fiscal year 2007 forward. This data is presented on the Vendor Payments report hosted at http://openbook.sfgov.org, and is also available in this dataset in CSV format, which represents summary data by purchase order. We have removed sensitive information from this data ? this is intended to show payments made to entities providing goods and services to the City and County and to protect individuals. For example, we have removed payments to employees (reimbursements, garnishments) and jury members, revenue refunds, payments for judgments and claims, witnesses, relocation and rehousing, and a variety of human services payments. New data is added on a weekly basis.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | series tag     | purchase_order          | Purchase Order          | text      | text        |
| Yes      | series tag     | vendor                  | Vendor                  | text      | text        |
| Yes      | series tag     | related_gov_t_units     | Related Gov't Units     | text      | text        |
| Yes      | series tag     | organization_group_code | Organization Group Code | text      | text        |
| Yes      | series tag     | organization_group      | Organization Group      | text      | text        |
| Yes      | series tag     | department_code         | Department Code         | text      | text        |
| Yes      | series tag     | department              | Department              | text      | text        |
| Yes      | series tag     | program_code            | Program Code            | text      | text        |
| Yes      | series tag     | program                 | Program                 | text      | text        |
| Yes      | series tag     | character_code          | Character Code          | text      | text        |
| Yes      | series tag     | character               | Character               | text      | text        |
| Yes      | series tag     | object_code             | Object Code             | text      | text        |
| Yes      | series tag     | object                  | Object                  | text      | text        |
| Yes      | series tag     | sub_object_code         | Sub-object Code         | text      | text        |
| Yes      | series tag     | sub_object              | Sub-object              | text      | text        |
| Yes      | series tag     | fund_type_code          | Fund Type Code          | text      | text        |
| Yes      | series tag     | fund_type               | Fund Type               | text      | text        |
| Yes      | series tag     | fund_code               | Fund Code               | text      | text        |
| Yes      | series tag     | fund                    | Fund                    | text      | text        |
| Yes      | series tag     | fund_category_code      | Fund Category Code      | text      | text        |
| Yes      | series tag     | fund_category           | Fund Category           | text      | text        |
| Yes      | numeric metric | vouchers_paid           | Vouchers Paid           | number    | number      |
| Yes      | numeric metric | vouchers_pending        | Vouchers Pending        | number    | number      |
| Yes      | numeric metric | encumbrance_balance     | Encumbrance Balance     | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:p5r5-fd7g d:2007-01-01T00:00:00.000Z t:organization_group="Public Works, Transportation & Commerce" t:fund_code=5MCPF t:fund_type="MTA Municipal Railway Funds" t:program_code=BEK t:vendor="ANSALDOBREDA S P A" t:department="Municipal Transportation Agency" t:sub_object=Rail t:object="Equip Purchase" t:object_code=060 t:fund_type_code=5M t:purchase_order="CTPT9110059 01" t:character="Capital Outlay" t:character_code=060 t:fund_category_code=3 t:program="MRD-Construction Division (Const)" t:fund_category="Continuing Projects" t:sub_object_code=06022 t:department_code=DPT t:fund="Muni Capital Projects Fund" t:organization_group_code=02 t:related_gov_t_units=No m:encumbrance_balance=8307786.94 m:vouchers_pending=0 m:vouchers_paid=0

series e:p5r5-fd7g d:2007-01-01T00:00:00.000Z t:organization_group="Public Works, Transportation & Commerce" t:fund_code=5MCPF t:fund_type="MTA Municipal Railway Funds" t:program_code=BEK t:vendor="THALES TRANSPORT & SECURITY INC" t:department="Municipal Transportation Agency" t:sub_object=Rail t:object="Equip Purchase" t:object_code=060 t:fund_type_code=5M t:purchase_order="CTPT9220052 01" t:character="Capital Outlay" t:character_code=060 t:fund_category_code=3 t:program="MRD-Construction Division (Const)" t:fund_category="Continuing Projects" t:sub_object_code=06022 t:department_code=DPT t:fund="Muni Capital Projects Fund" t:organization_group_code=02 t:related_gov_t_units=No m:encumbrance_balance=516882.99 m:vouchers_pending=0 m:vouchers_paid=0

series e:p5r5-fd7g d:2007-01-01T00:00:00.000Z t:organization_group="Public Works, Transportation & Commerce" t:fund_code=8TCPF t:fund_type="SF Transportation Authority Funds" t:program_code=XXX t:vendor="MUNICIPAL RAILWAY" t:department="County Transportation Authority" t:sub_object="Other Professional Services" t:object="Professional & Specialized Services" t:object_code=027 t:fund_type_code=8T t:purchase_order="CTTA0015001 01" t:character="Non Personnel Services" t:character_code=021 t:fund_category_code=3 t:program="No Program Defined" t:fund_category="Continuing Projects" t:sub_object_code=02799 t:department_code=CTA t:fund="SFCTA Capital Project Fund" t:organization_group_code=02 t:related_gov_t_units=No m:encumbrance_balance=896051.79 m:vouchers_pending=0 m:vouchers_paid=0
```

## Meta Commands

```ls
metric m:vouchers_paid p:double l:"Vouchers Paid" d:"Completed payments to vendors." t:dataTypeName=number

metric m:vouchers_pending p:float l:"Vouchers Pending" d:"Payments to vendors that have been requested but not yet paid." t:dataTypeName=number

metric m:encumbrance_balance p:double l:"Encumbrance Balance" d:"The unused portion of an encumbrance document." t:dataTypeName=number

entity e:p5r5-fd7g l:"Vendor Payments (Purchase Order Summary)" t:attribution="SF Controller's Office" t:url=https://data.sfgov.org/api/views/p5r5-fd7g

property e:p5r5-fd7g t:meta.view v:id=p5r5-fd7g v:category="City Management and Ethics" v:attributionLink=http://openbook.sfgov.org v:averageRating=0 v:name="Vendor Payments (Purchase Order Summary)" v:attribution="SF Controller's Office"

property e:p5r5-fd7g t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:p5r5-fd7g t:meta.view.owner v:id=9ufn-6bwh v:screenName="Jeff Pera" v:displayName="Jeff Pera"

property e:p5r5-fd7g t:meta.view.tableauthor v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"
```

## Top Records

```ls
| fiscal_year | purchase_order | vendor                          | related_gov_t_units | organization_group_code | organization_group                      | department_code | department                      | program_code | program                           | character_code | character              | object_code | object                              | sub_object_code | sub_object                  | fund_type_code | fund_type                         | fund_code | fund                       | fund_category_code | fund_category       | vouchers_paid | vouchers_pending | encumbrance_balance | 
| =========== | ============== | =============================== | =================== | ======================= | ======================================= | =============== | =============================== | ============ | ================================= | ============== | ====================== | =========== | =================================== | =============== | =========================== | ============== | ================================= | ========= | ========================== | ================== | =================== | ============= | ================ | =================== | 
| 2007        | CTPT9110059 01 | ANSALDOBREDA S P A              | No                  | 02                      | Public Works, Transportation & Commerce | DPT             | Municipal Transportation Agency | BEK          | MRD-Construction Division (Const) | 060            | Capital Outlay         | 060         | Equip Purchase                      | 06022           | Rail                        | 5M             | MTA Municipal Railway Funds       | 5MCPF     | Muni Capital Projects Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 8307786.94          | 
| 2007        | CTPT9220052 01 | THALES TRANSPORT & SECURITY INC | No                  | 02                      | Public Works, Transportation & Commerce | DPT             | Municipal Transportation Agency | BEK          | MRD-Construction Division (Const) | 060            | Capital Outlay         | 060         | Equip Purchase                      | 06022           | Rail                        | 5M             | MTA Municipal Railway Funds       | 5MCPF     | Muni Capital Projects Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 516882.99           | 
| 2007        | CTTA0015001 01 | MUNICIPAL RAILWAY               | No                  | 02                      | Public Works, Transportation & Commerce | CTA             | County Transportation Authority | XXX          | No Program Defined                | 021            | Non Personnel Services | 027         | Professional & Specialized Services | 02799           | Other Professional Services | 8T             | SF Transportation Authority Funds | 8TCPF     | SFCTA Capital Project Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 896051.79           | 
| 2007        | CTTA0016H02 01 | MUNICIPAL RAILWAY               | No                  | 02                      | Public Works, Transportation & Commerce | CTA             | County Transportation Authority | XXX          | No Program Defined                | 021            | Non Personnel Services | 027         | Professional & Specialized Services | 02799           | Other Professional Services | 8T             | SF Transportation Authority Funds | 8TCPF     | SFCTA Capital Project Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 26053.00            | 
| 2007        | CTTA0020000 01 | DEPARTMENT OF PUBLIC WORKS      | No                  | 02                      | Public Works, Transportation & Commerce | CTA             | County Transportation Authority | XXX          | No Program Defined                | 021            | Non Personnel Services | 027         | Professional & Specialized Services | 02799           | Other Professional Services | 8T             | SF Transportation Authority Funds | 8TCPF     | SFCTA Capital Project Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 112788.74           | 
| 2007        | CTTA0025000 01 | DEPARTMENT OF PARKING & TRAFFIC | No                  | 02                      | Public Works, Transportation & Commerce | CTA             | County Transportation Authority | XXX          | No Program Defined                | 021            | Non Personnel Services | 027         | Professional & Specialized Services | 02799           | Other Professional Services | 8T             | SF Transportation Authority Funds | 8TCPF     | SFCTA Capital Project Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 637694.06           | 
| 2007        | CTTA0043D02 01 | DEPARTMENT OF PARKING & TRAFFIC | No                  | 02                      | Public Works, Transportation & Commerce | CTA             | County Transportation Authority | XXX          | No Program Defined                | 021            | Non Personnel Services | 027         | Professional & Specialized Services | 02799           | Other Professional Services | 8T             | SF Transportation Authority Funds | 8TCPF     | SFCTA Capital Project Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 20000.00            | 
| 2007        | CTTA0047C00 01 | DEPARTMENT OF PARKING & TRAFFIC | No                  | 02                      | Public Works, Transportation & Commerce | CTA             | County Transportation Authority | XXX          | No Program Defined                | 021            | Non Personnel Services | 027         | Professional & Specialized Services | 02799           | Other Professional Services | 8T             | SF Transportation Authority Funds | 8TCPF     | SFCTA Capital Project Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 10076.53            | 
| 2007        | CTTA0047D00 01 | DEPARTMENT OF PARKING & TRAFFIC | No                  | 02                      | Public Works, Transportation & Commerce | CTA             | County Transportation Authority | XXX          | No Program Defined                | 021            | Non Personnel Services | 027         | Professional & Specialized Services | 02799           | Other Professional Services | 8T             | SF Transportation Authority Funds | 8TCPF     | SFCTA Capital Project Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 30000.00            | 
| 2007        | CTTA0115000 01 | MUNICIPAL RAILWAY               | No                  | 02                      | Public Works, Transportation & Commerce | CTA             | County Transportation Authority | XXX          | No Program Defined                | 021            | Non Personnel Services | 027         | Professional & Specialized Services | 02799           | Other Professional Services | 8T             | SF Transportation Authority Funds | 8TCPF     | SFCTA Capital Project Fund | 3                  | Continuing Projects | 0.00          | 0.00             | 216675.82           | 
```