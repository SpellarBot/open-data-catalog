# Vendor Payments (Vouchers)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vendor-payments-vouchers-64994) |
| Metadata | [Link](https://data.sfgov.org/api/views/n9pm-xkyq) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/n9pm-xkyq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/n9pm-xkyq/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | n9pm-xkyq |
| Name | Vendor Payments (Vouchers) |
| Attribution | SF Controller's Office |
| Category | City Management and Ethics |
| Tags | spending, amount, vendor, voucher, sfopenbook, open book, openbook |
| Created | 2014-03-26T23:20:23Z |
| Publication Date | 2014-10-07T15:51:40Z |

## Description

The San Francisco Controller's Office maintains a database of payments made to vendors from fiscal year 2007 forward. This data is presented on the Vendor Payments report hosted at http://openbook.sfgov.org, and is also available in this dataset in CSV format, which represents detailed data by voucher. We have removed sensitive information from this data ? this is intended to show payments made to entities providing goods and services to the City and County and to protect individuals. For example, we have removed payments to employees (reimbursements, garnishments) and jury members, revenue refunds, payments for judgments and claims, witnesses, relocation and rehousing, and a variety of human services payments. New data is added on a weekly basis.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | series tag     | purchase_order          | Purchase Order          | text      | text        |
| Yes      | series tag     | voucher                 | Voucher                 | text      | text        |
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
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:n9pm-xkyq d:2013-01-01T00:00:00.000Z t:organization_group="Culture & Recreation" t:fund_code=1GAGF t:fund_type="General Fund" t:program_code=EEI t:vendor="C M S C" t:department="Asian Art Museum" t:sub_object="Janitorial Services" t:object="Maintenance Svcs-Building & Structures" t:object_code=028 t:fund_type_code=1G t:purchase_order=DPAA1300000101 t:character="Non Personnel Services" t:character_code=021 t:fund_category_code=2 t:program="Asian Arts Museum" t:fund_category="Annual Projects" t:sub_object_code=02802 t:department_code=AAM t:fund="General Fund" t:voucher=VCAA1300000101 t:organization_group_code=05 t:related_gov_t_units=No m:vouchers_pending=0 m:vouchers_paid=27374.82

series e:n9pm-xkyq d:2013-01-01T00:00:00.000Z t:organization_group="Culture & Recreation" t:fund_code=1GAGF t:fund_type="General Fund" t:program_code=EEI t:vendor="C M S C" t:department="Asian Art Museum" t:sub_object="Janitorial Services" t:object="Maintenance Svcs-Building & Structures" t:object_code=028 t:fund_type_code=1G t:purchase_order=DPAA1300000101 t:character="Non Personnel Services" t:character_code=021 t:fund_category_code=2 t:program="Asian Arts Museum" t:fund_category="Annual Projects" t:sub_object_code=02802 t:department_code=AAM t:fund="General Fund" t:voucher=VCAA1300000201 t:organization_group_code=05 t:related_gov_t_units=No m:vouchers_pending=0 m:vouchers_paid=13166.15

series e:n9pm-xkyq d:2013-01-01T00:00:00.000Z t:organization_group="Culture & Recreation" t:fund_code=1GAGF t:fund_type="General Fund" t:program_code=EEI t:vendor="C M S C" t:department="Asian Art Museum" t:sub_object="Janitorial Services" t:object="Maintenance Svcs-Building & Structures" t:object_code=028 t:fund_type_code=1G t:purchase_order=DPAA1300000101 t:character="Non Personnel Services" t:character_code=021 t:fund_category_code=2 t:program="Asian Arts Museum" t:fund_category="Annual Projects" t:sub_object_code=02802 t:department_code=AAM t:fund="General Fund" t:voucher=VCAA1300000301 t:organization_group_code=05 t:related_gov_t_units=No m:vouchers_pending=0 m:vouchers_paid=13782.7
```

## Meta Commands

```ls
metric m:vouchers_paid p:double l:"Vouchers Paid" d:"Completed payments to vendors." t:dataTypeName=number

metric m:vouchers_pending p:float l:"Vouchers Pending" d:"Payments to vendors that have been requested but not yet paid." t:dataTypeName=number

entity e:n9pm-xkyq l:"Vendor Payments (Vouchers)" t:attribution="SF Controller's Office" t:url=https://data.sfgov.org/api/views/n9pm-xkyq

property e:n9pm-xkyq t:meta.view v:id=n9pm-xkyq v:category="City Management and Ethics" v:attributionLink=http://openbook.sfgov.org v:averageRating=0 v:name="Vendor Payments (Vouchers)" v:attribution="SF Controller's Office"

property e:n9pm-xkyq t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:n9pm-xkyq t:meta.view.owner v:id=9ufn-6bwh v:screenName="Jeff Pera" v:displayName="Jeff Pera"

property e:n9pm-xkyq t:meta.view.tableauthor v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"
```

## Top Records

```ls
| fiscal_year | purchase_order | voucher        | vendor  | related_gov_t_units | organization_group_code | organization_group   | department_code | department       | program_code | program           | character_code | character              | object_code | object                                 | sub_object_code | sub_object          | fund_type_code | fund_type    | fund_code | fund         | fund_category_code | fund_category   | vouchers_paid | vouchers_pending | 
| =========== | ============== | ============== | ======= | =================== | ======================= | ==================== | =============== | ================ | ============ | ================= | ============== | ====================== | =========== | ====================================== | =============== | =================== | ============== | ============ | ========= | ============ | ================== | =============== | ============= | ================ | 
| 2013        | DPAA1300000101 | VCAA1300000101 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 27374.82      | 0.00             | 
| 2013        | DPAA1300000101 | VCAA1300000201 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 13166.15      | 0.00             | 
| 2013        | DPAA1300000101 | VCAA1300000301 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 13782.70      | 0.00             | 
| 2013        | DPAA1300000101 | VCAA1300000401 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 13339.90      | 0.00             | 
| 2013        | DPAA1300000101 | VCAA1300000501 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 11630.38      | 0.00             | 
| 2013        | DPAA1300000101 | VCAA1300000601 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 15441.78      | 0.00             | 
| 2013        | DPAA1300000101 | VCAA1300000701 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 12706.54      | 0.00             | 
| 2013        | DPAA1300000101 | VCAA1300000901 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 12969.40      | 0.00             | 
| 2013        | DPAA1300000101 | VCAA1300001001 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 14859.80      | 0.00             | 
| 2013        | DPAA1300000101 | VCAA1300001101 | C M S C | No                  | 05                      | Culture & Recreation | AAM             | Asian Art Museum | EEI          | Asian Arts Museum | 021            | Non Personnel Services | 028         | Maintenance Svcs-Building & Structures | 02802           | Janitorial Services | 1G             | General Fund | 1GAGF     | General Fund | 2                  | Annual Projects | 21628.53      | 0.00             | 
```