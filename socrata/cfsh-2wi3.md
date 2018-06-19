# Contracts: ODOT: Fiscal Year 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-odot-fiscal-year-2011-5210a) |
| Metadata | [Link](https://data.oregon.gov/api/views/cfsh-2wi3) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/cfsh-2wi3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/cfsh-2wi3/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | cfsh-2wi3 |
| Name | Contracts: ODOT: Fiscal Year 2011 |
| Category | Revenue & Expense |
| Created | 2011-12-18T22:43:52Z |
| Publication Date | 2011-12-18T22:45:54Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | contract_id      | Contract_ID      | text      | number      |
| Yes      | series tag     | project_name     | Project_Name     | text      | text        |
| Yes      | series tag     | fed_state_number | Fed_State_Number | text      | text        |
| Yes      | time           | award_date       | Award_Date       | text      | text        |
| Yes      | numeric metric | contract_amount  | Contract_Amount  | money     | money       |
| Yes      | series tag     | vendor_name      | Vendor_Name      | text      | text        |
```

## Time Field

```ls
Value = award_date
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:cfsh-2wi3 d:2010-07-08T00:00:00.000Z t:project_name="OR6: DEVILS LAKE FORK WILSON RIVER - BUNDLE 510" t:fed_state_number=X-STP-OTIA-S037(021) t:contract_id=14262 t:vendor_name="MOWAT CONSTRUCTION CO" m:contract_amount=1817216.4

series e:cfsh-2wi3 d:2010-07-12T00:00:00.000Z t:project_name="I-84: WB & EB BRIDGES OVER UPRR (RUFUS)" t:fed_state_number=X-BHF-S002(116) t:contract_id=14263 t:vendor_name="WILDISH STANDARD PAVING CO" m:contract_amount=652103.92

series e:cfsh-2wi3 d:2010-07-14T00:00:00.000Z t:project_name="LOST CREEK-PARVIN RD (PARVIN COVERED BR) #39C643" t:fed_state_number=X-HCBP-C039(037) t:contract_id=14261 t:vendor_name="JEFF CARTER CONSTRUCTION INC" m:contract_amount=512950.25
```

## Meta Commands

```ls
metric m:contract_amount p:double l:Contract_Amount t:dataTypeName=money

entity e:cfsh-2wi3 l:"Contracts: ODOT: Fiscal Year 2011" t:url=https://data.oregon.gov/api/views/cfsh-2wi3

property e:cfsh-2wi3 t:meta.view v:id=cfsh-2wi3 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: ODOT: Fiscal Year 2011"

property e:cfsh-2wi3 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:cfsh-2wi3 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| contract_id | project_name                                      | fed_state_number     | award_date | contract_amount | vendor_name                   | 
| =========== | ================================================= | ==================== | ========== | =============== | ============================= | 
| 14262       | OR6: DEVILS LAKE FORK WILSON RIVER - BUNDLE 510   | X-STP-OTIA-S037(021) | 7/8/10     | 1817216.40      | MOWAT CONSTRUCTION CO         | 
| 14263       | I-84: WB & EB BRIDGES OVER UPRR (RUFUS)           | X-BHF-S002(116)      | 7/12/10    | 652103.92       | WILDISH STANDARD PAVING CO    | 
| 14261       | LOST CREEK-PARVIN RD (PARVIN COVERED BR) #39C643  | X-HCBP-C039(037)     | 7/14/10    | 512950.25       | JEFF CARTER CONSTRUCTION INC  | 
| 14265       | MILL CREEK (COTTAGE ST) BRIDGE (SALEM)            | X-BRO-6490(052)      | 7/14/10    | 300000.00       | K & E EXCAVATING INC          | 
| 14268       | BUENA VISTA FERRY REPLACEMENT                     | X-STP-C047(050)      | 8/2/10     | 1359870.00      | MJ HUGHES CONSTRUCTION INC    | 
| 14266       | OR164 @ SCRAVEL HILL RD                           | X-HSIP-S164(007)     | 8/5/10     | 929317.80       | NORTH SANTIAM PAVING CO       | 
| 14270       | US20 SIGNAL UPGRADES (BEND)                       | X-STP-S017(009)      | 8/31/10    | 523768.05       | TOMCO ELECTRIC INC            | 
| 14271       | OR361: A ST - D ST SIDEWALK/STREETSCAPE (CULVER)  | X-TEA-1730(005)      | 8/31/10    | 353648.26       | JACK ROBINSON & SONS INC      | 
| 14274       | US20: HARRIS RD & WPRR - MARYS RIVER - BUNDLE 409 | X-AC-NH-S033(035)    | 8/31/10    | 559930.00       | 2KG CONTRACTORS INC           | 
| 14272       | TUALATIN-SHERWOOD RD ITS:TETON RD TO I-5          | X-CM-STP-C067(085)   | 9/2/10     | 525620.50       | SIGNAL CONSTRUCTION GROUP LLC | 
```