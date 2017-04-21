# Hospital Inpatient Discharge Rates, Average Charges, Average Payments, and Charge-to-Payment Ratios by DRG - U.S., Northwest, and Washington State - FY2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospital-inpatient-discharge-rates-average-charges-average-payments-and-charge-to-payment--6c7a7) |
| Metadata | [Link](https://data.wa.gov/api/views/xupn-4ych) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xupn-4ych/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xupn-4ych/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xupn-4ych |
| Name | Hospital Inpatient Discharge Rates, Average Charges, Average Payments, and Charge-to-Payment Ratios by DRG - U.S., Northwest, and Washington State - FY2011 |
| Category | Health |
| Tags | discharge rate, drg, hospital charges, covered payment, charge-to-payment ratio |
| Created | 2013-06-20T21:00:41Z |
| Publication Date | 2013-06-20T21:54:41Z |

## Description

The dataset contains hospital inpatient discharge rates, charges, covered payments, charge-to-payment ratios for the 100 most common DRGs among hospitals in the Medicare Prospective Payment System.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                            | Data Type | Render Type |
| ======== | ============== | ============================ | =============================== | ========= | =========== |
| Yes      | series tag     | drg_definiton                | DRG Definiton                   | text      | text        |
| Yes      | numeric metric | u_s_discharges_per_100_000   | U.S. - Discharges per 100,000   | number    | number      |
| Yes      | numeric metric | u_s_average_charges          | U.S. - Average Charges          | money     | money       |
| Yes      | numeric metric | u_s_average_covered_payments | U.S. - Average Covered Payments | money     | money       |
| Yes      | numeric metric | u_s_charge_to_payment_ratio  | U.S. - Charge-to-Payment Ratio  | number    | number      |
| Yes      | numeric metric | nw_discharges_per_100_000    | NW - Discharges per 100,000     | number    | number      |
| Yes      | numeric metric | nw_average_charges           | NW - Average Charges            | money     | money       |
| Yes      | numeric metric | nw_average_covered_payments  | NW - Average Covered Payments   | money     | money       |
| Yes      | numeric metric | nw_charge_to_payment_ratio   | NW - Charge-to-Payment Ratio    | number    | number      |
| Yes      | numeric metric | wa_discharges_per_100_000    | WA - Discharges per 100,000     | number    | number      |
| Yes      | numeric metric | wa_average_charges           | WA - Average Charges            | money     | money       |
| Yes      | numeric metric | wa_average_covered_payments  | WA - Average Covered Payments   | money     | money       |
| Yes      | numeric metric | wa_charge_to_payment_ratio   | WA - Charge-to-Payment Ratio    | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xupn-4ych d:2011-01-01T00:00:00.000Z t:drg_definiton="039 - EXTRACRANIAL PROCEDURES W/O CC/MCC" m:u_s_discharges_per_100_000=10.8 m:nw_average_charges=26928 m:wa_average_covered_payments=7668 m:u_s_average_covered_payments=6840 m:wa_charge_to_payment_ratio=4.1 m:nw_average_covered_payments=7344 m:u_s_charge_to_payment_ratio=4.2 m:wa_average_charges=31356 m:u_s_average_charges=28524 m:nw_charge_to_payment_ratio=3.7 m:nw_discharges_per_100_000=7.8 m:wa_discharges_per_100_000=7.8

series e:xupn-4ych d:2011-01-01T00:00:00.000Z t:drg_definiton="057 - DEGENERATIVE NERVOUS SYSTEM DISORDERS W/O MCC" m:u_s_discharges_per_100_000=9.7 m:nw_average_charges=22368 m:wa_average_covered_payments=6648 m:u_s_average_covered_payments=6960 m:wa_charge_to_payment_ratio=3.4 m:nw_average_covered_payments=7020 m:u_s_charge_to_payment_ratio=3.6 m:wa_average_charges=22464 m:u_s_average_charges=24792 m:nw_charge_to_payment_ratio=3.2 m:nw_discharges_per_100_000=1.9 m:wa_discharges_per_100_000=2.4

series e:xupn-4ych d:2011-01-01T00:00:00.000Z t:drg_definiton="064 - INTRACRANIAL HEMORRHAGE OR CEREBRAL INFARCTION W MCC" m:u_s_discharges_per_100_000=19.9 m:nw_average_charges=39204 m:wa_average_covered_payments=13524 m:u_s_average_covered_payments=13776 m:wa_charge_to_payment_ratio=3.1 m:nw_average_covered_payments=13632 m:u_s_charge_to_payment_ratio=3.7 m:wa_average_charges=41724 m:u_s_average_charges=50508 m:nw_charge_to_payment_ratio=2.9 m:nw_discharges_per_100_000=13.9 m:wa_discharges_per_100_000=16.9
```

## Meta Commands

```ls
metric m:u_s_discharges_per_100_000 p:float l:"U.S. - Discharges per 100,000" d:"Discharges per 100,000 population in the U.S." t:dataTypeName=number

metric m:u_s_average_charges p:integer l:"U.S. - Average Charges" d:"Average charges per discharge in U.S." t:dataTypeName=money

metric m:u_s_average_covered_payments p:integer l:"U.S. - Average Covered Payments" d:"Average covered payments per discharge in U.S." t:dataTypeName=money

metric m:u_s_charge_to_payment_ratio p:float l:"U.S. - Charge-to-Payment Ratio" d:"Charge-to-payment ratio in U.S." t:dataTypeName=number

metric m:nw_discharges_per_100_000 p:float l:"NW - Discharges per 100,000" d:"Discharges per 100,000 population in the Northwest region (Alaska, Idaho, Oregon, and Washington)" t:dataTypeName=number

metric m:nw_average_charges p:integer l:"NW - Average Charges" d:"Average charges per discharge in the Northwest region (Alaska, Idaho, Oregon, and Washington)" t:dataTypeName=money

metric m:nw_average_covered_payments p:integer l:"NW - Average Covered Payments" d:"Average covered payments per discharge in the Northwest region (Alaska, Idaho, Oregon and Washington)" t:dataTypeName=money

metric m:nw_charge_to_payment_ratio p:float l:"NW - Charge-to-Payment Ratio" d:"Charge-to-payment ratio in the Northwest region (Alaska, Idaho, Oregon, and Washington" t:dataTypeName=number

metric m:wa_discharges_per_100_000 p:float l:"WA - Discharges per 100,000" d:"Discharges per 100,000 population in Washington" t:dataTypeName=number

metric m:wa_average_charges p:integer l:"WA - Average Charges" d:"Average charges per discharge in Washington" t:dataTypeName=money

metric m:wa_average_covered_payments p:integer l:"WA - Average Covered Payments" d:"Average covered payments per discharge in Washington" t:dataTypeName=money

metric m:wa_charge_to_payment_ratio p:float l:"WA - Charge-to-Payment Ratio" d:"Charge-to-payment ratio in Washington" t:dataTypeName=number

entity e:xupn-4ych l:"Hospital Inpatient Discharge Rates, Average Charges, Average Payments, and Charge-to-Payment Ratios by DRG - U.S., Northwest, and Washington State - FY2011" t:url=https://data.wa.gov/api/views/xupn-4ych

property e:xupn-4ych t:meta.view v:id=xupn-4ych v:category=Health v:averageRating=0 v:name="Hospital Inpatient Discharge Rates, Average Charges, Average Payments, and Charge-to-Payment Ratios by DRG - U.S., Northwest, and Washington State - FY2011"

property e:xupn-4ych t:meta.view.owner v:id=8ghr-nmpd v:screenName="Wei Yen" v:displayName="Wei Yen"

property e:xupn-4ych t:meta.view.tableauthor v:id=8ghr-nmpd v:screenName="Wei Yen" v:roleName=publisher v:displayName="Wei Yen"
```

## Top Records

```ls
| drg_definiton                                                   | u_s_discharges_per_100_000 | u_s_average_charges | u_s_average_covered_payments | u_s_charge_to_payment_ratio | nw_discharges_per_100_000 | nw_average_charges | nw_average_covered_payments | nw_charge_to_payment_ratio | wa_discharges_per_100_000 | wa_average_charges | wa_average_covered_payments | wa_charge_to_payment_ratio | 
| =============================================================== | ========================== | =================== | ============================ | =========================== | ========================= | ================== | =========================== | ========================== | ========================= | ================== | =========================== | ========================== | 
| 039 - EXTRACRANIAL PROCEDURES W/O CC/MCC                        | 10.8                       | 28524               | 6840                         | 4.2                         | 7.8                       | 26928              | 7344                        | 3.7                        | 7.8                       | 31356              | 7668                        | 4.1                        | 
| 057 - DEGENERATIVE NERVOUS SYSTEM DISORDERS W/O MCC             | 9.7                        | 24792               | 6960                         | 3.6                         | 1.9                       | 22368              | 7020                        | 3.2                        | 2.4                       | 22464              | 6648                        | 3.4                        | 
| 064 - INTRACRANIAL HEMORRHAGE OR CEREBRAL INFARCTION W MCC      | 19.9                       | 50508               | 13776                        | 3.7                         | 13.9                      | 39204              | 13632                       | 2.9                        | 16.9                      | 41724              | 13524                       | 3.1                        | 
| 065 - INTRACRANIAL HEMORRHAGE OR CEREBRAL INFARCTION W CC       | 34.2                       | 30780               | 8052                         | 3.8                         | 25.1                      | 25512              | 8232                        | 3.1                        | 28.7                      | 27756              | 8160                        | 3.4                        | 
| 066 - INTRACRANIAL HEMORRHAGE OR CEREBRAL INFARCTION W/O CC/MCC | 17.9                       | 23868               | 5784                         | 4.1                         | 14.4                      | 20268              | 5964                        | 3.4                        | 17.3                      | 22536              | 5832                        | 3.9                        | 
| 069 - TRANSIENT ISCHEMIA                                        | 25.5                       | 21828               | 5076                         | 4.3                         | 11.0                      | 18024              | 5184                        | 3.5                        | 14.9                      | 19716              | 5136                        | 3.8                        | 
| 074 - CRANIAL & PERIPHERAL NERVE DISORDERS W/O MCC              | 7.0                        | 25320               | 6504                         | 3.9                         | 2.3                       | 22860              | 6240                        | 3.7                        | 3.5                       | 24132              | 6372                        | 3.8                        | 
| 101 - SEIZURES W/O MCC                                          | 15.7                       | 22428               | 5796                         | 3.9                         | 6.1                       | 20052              | 6096                        | 3.3                        | 8.6                       | 20736              | 5928                        | 3.5                        | 
| 149 - DYSEQUILIBRIUM                                            | 7.5                        | 18900               | 4668                         | 4.0                         | 0.9                       | 17952              | 4476                        | 4.0                        | 1.6                       | 18972              | 4500                        | 4.2                        | 
| 176 - PULMONARY EMBOLISM W/O MCC                                | 10.3                       | 26412               | 7356                         | 3.6                         | 8.1                       | 21996              | 7536                        | 2.9                        | 9.5                       | 24756              | 7608                        | 3.3                        | 
```