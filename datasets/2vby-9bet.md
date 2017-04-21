# Pharmacies offering Narcan, Evzio and other brands of Naloxone

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/pharmacies-offering-narcan-evzio-and-other-brands-of-naloxone) |
| Metadata | [Link](https://data.ct.gov/api/views/2vby-9bet) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/2vby-9bet/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/2vby-9bet/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 2vby-9bet |
| Name | Pharmacies offering Narcan, Evzio and other brands of Naloxone |
| Attribution | DAS/BEST |
| Category | Public Safety |
| Tags | naloxone, pharmacy, substance abuse |
| Created | 2016-06-16T19:28:55Z |
| Publication Date | 2017-03-01T19:22:02Z |

## Description

Pharmacies that are able to dispense Naloxone. Naloxone is a medication approved by the Food and Drug Administration (FDA) to prevent overdose by opioids such as heroin, morphine, and oxycodone.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | pharmacy_name | Pharmacy-Name | text      | text        |
| Yes      | series tag  | phone         | Phone         | text      | text        |
| Yes      | series tag  | credential    | Credential    | text      | text        |
| No       |             | address       | Address       | text      | text        |
| Yes      | series tag  | city          | City          | text      | text        |
| Yes      | series tag  | state         | State         | text      | text        |
| Yes      | series tag  | zip           | Zip           | text      | text        |
| Yes      | series tag  | credentialid  | CredentialId  | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:2vby-9bet d:2017-04-13T08:00:37.000Z t:zip=06320-5040 t:credentialid=222256 t:phone="(860) 440-3566" t:state=CT t:pharmacy_name="WALGREENS #10483" t:credential=PCY.0001728 t:city="NEW LONDON" m:row_number.2vby-9bet=1

series e:2vby-9bet d:2017-04-13T08:00:53.000Z t:zip=06415-1159 t:credentialid=175335 t:phone=8605372570 t:state=CT t:pharmacy_name="STOP & SHOP PHARMACY #608" t:credential=PCY.0001599 t:city=COLCHESTER m:row_number.2vby-9bet=2

series e:2vby-9bet d:2017-04-13T08:00:28.000Z t:zip=06109-4232 t:credentialid=37780 t:phone="(860) 721-7224" t:state=CT t:pharmacy_name="WALGREENS #04490" t:credential=PCY.0000951 t:city=WETHERSFIELD m:row_number.2vby-9bet=3
```

## Meta Commands

```ls
metric m:row_number.2vby-9bet p:long l:"Row Number"

entity e:2vby-9bet l:"Pharmacies offering Narcan, Evzio and other brands of Naloxone" t:attribution=DAS/BEST t:url=https://data.ct.gov/api/views/2vby-9bet

property e:2vby-9bet t:meta.view v:id=2vby-9bet v:category="Public Safety" v:averageRating=0 v:name="Pharmacies offering Narcan, Evzio and other brands of Naloxone" v:attribution=DAS/BEST

property e:2vby-9bet t:meta.view.license v:name="Public Domain"

property e:2vby-9bet t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:2vby-9bet t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| :updated_at | pharmacy_name             | phone          | credential  | address               | city         | state | zip        | credentialid | 
| =========== | ========================= | ============== | =========== | ===================== | ============ | ===== | ========== | ============ | 
| 1492070437  | WALGREENS #10483          | (860) 440-3566 | PCY.0001728 | 698 BANK ST           | NEW LONDON   | CT    | 06320-5040 | 222256       | 
| 1492070453  | STOP & SHOP PHARMACY #608 | 8605372570     | PCY.0001599 | 99 LINWOOD AVE        | COLCHESTER   | CT    | 06415-1159 | 175335       | 
| 1492070428  | WALGREENS #04490          | (860) 721-7224 | PCY.0000951 | 1100 SILAS DEANE HWY  | WETHERSFIELD | CT    | 06109-4232 | 37780        | 
| 1492070436  | CVS PHARMACY #857         | (203) 467-8876 | PCY.0001304 | 660 FOXON RD          | EAST HAVEN   | CT    | 06513-1863 | 38455        | 
| 1492070445  | MANCHESTER RX LLC         | (860) 649-1025 | PCY.0001290 | 348 MAIN ST           | MANCHESTER   | CT    | 06040-4123 | 38449        | 
| 1492070453  | WALGREENS #09785          | (203) 777-8001 | PCY.0001349 | 436 WHALLEY AVE       | NEW HAVEN    | CT    | 06511-3012 | 38656        | 
| 1492070453  | CVS PHARMACY #696         | (203) 775-9593 | PCY.0001210 | 14 CANDLEWOOD LAKE RD | BROOKFIELD   | CT    | 06804-2529 | 38227        | 
| 1492070454  | CVS PHARMACY #840         | (860) 956-7107 | PCY.0001286 | 908 MAPLE AVE         | HARTFORD     | CT    | 06114-2723 | 38445        | 
| 1492070454  | HOPMEADOW APOTHECARY      | (860)651-3331  | PCY.0001100 | 1300 HOPMEADOW ST     | SIMSBURY     | CT    | 06070-1411 | 38004        | 
| 1492070454  | RITE AID #10341           | (860) 824-5481 | PCY.0001677 | 76 MAIN ST            | CANAAN       | CT    | 06018-2460 | 159990       | 
```