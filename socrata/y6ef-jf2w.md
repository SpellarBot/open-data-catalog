# Sold Fleet Equipment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sold-fleet-equipment-42558) |
| Metadata | [Link](https://data.seattle.gov/api/views/y6ef-jf2w) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/y6ef-jf2w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/y6ef-jf2w/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | y6ef-jf2w |
| Name | Sold Fleet Equipment |
| Category | City Business |
| Tags | fleet, equipment, cars, trucks, auction, surplus |
| Created | 2014-02-06T16:40:51Z |
| Publication Date | 2017-03-30T15:49:30Z |

## Description

This dataset includes sales data for fleet equipment that was sold in the current and previous two years. This dataset does not include sales data for Seattle City Light (SCL) fleet equipment.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type     | Render Type   |
| ======== | ============== | =========== | =========== | ============= | ============= |
| Yes      | series tag     | equip_id    | EQUIP_ID    | text          | text          |
| Yes      | time           | year        | YEAR        | number        | number        |
| Yes      | series tag     | make        | MAKE        | text          | text          |
| Yes      | series tag     | model       | MODEL       | text          | text          |
| Yes      | series tag     | description | DESCRIPTION | text          | text          |
| Yes      | series tag     | dept        | DEPT        | text          | text          |
| Yes      | numeric metric | sale_price  | SALE_PRICE  | number        | number        |
| No       |                | sale_date   | SALE_DATE   | calendar_date | calendar_date |
| Yes      | series tag     | sold_by     | SOLD_BY     | text          | text          |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = sale_date
```

## Data Commands

```ls
series e:y6ef-jf2w d:2003-01-01T00:00:00.000Z t:model=ASTRO t:equip_id=33294 t:description="MINIVAN K-9" t:sold_by="BIDADOO ONLINE AUCTION" t:dept=SPD t:make=CHEVROLET m:sale_price=4550.09

series e:y6ef-jf2w d:2005-01-01T00:00:00.000Z t:model=ASTRO t:equip_id=53535 t:description="CARGO MINIVAN" t:sold_by="BIDADOO ONLINE AUCTION" t:dept=SDOT t:make=CHEVROLET m:sale_price=4905

series e:y6ef-jf2w d:2005-01-01T00:00:00.000Z t:model=EXPRESS t:equip_id=53873 t:description="PASSENGER VAN" t:sold_by="BIDADOO ONLINE AUCTION" t:dept=DPR t:make=CHEVROLET m:sale_price=9900
```

## Meta Commands

```ls
metric m:sale_price p:float l:SALE_PRICE t:dataTypeName=number

entity e:y6ef-jf2w l:"Sold Fleet Equipment" t:url=https://data.seattle.gov/api/views/y6ef-jf2w

property e:y6ef-jf2w t:meta.view v:id=y6ef-jf2w v:category="City Business" v:averageRating=0 v:name="Sold Fleet Equipment"

property e:y6ef-jf2w t:meta.view.license v:name="Public Domain"

property e:y6ef-jf2w t:meta.view.owner v:id=sb28-e8im v:screenName="FAS - Fleet Management" v:displayName="FAS - Fleet Management"

property e:y6ef-jf2w t:meta.view.tableauthor v:id=sb28-e8im v:screenName="FAS - Fleet Management" v:roleName=publisher v:displayName="FAS - Fleet Management"
```

## Top Records

```ls
| equip_id | year | make      | model    | description      | dept | sale_price | sale_date | sold_by                | 
| ======== | ==== | ========= | ======== | ================ | ==== | ========== | ========= | ====================== | 
| 33294    | 2003 | CHEVROLET | ASTRO    | MINIVAN K-9      | SPD  | 4550.09    |           | BIDADOO ONLINE AUCTION | 
| 53535    | 2005 | CHEVROLET | ASTRO    | CARGO MINIVAN    | SDOT | 4905       |           | BIDADOO ONLINE AUCTION | 
| 53873    | 2005 | CHEVROLET | EXPRESS  | PASSENGER VAN    | DPR  | 9900       |           | BIDADOO ONLINE AUCTION | 
| 53874    | 2005 | CHEVROLET | EXPRESS  | CARGO VAN        | DPR  | 5200       |           | BIDADOO ONLINE AUCTION | 
| 43415    | 2004 | CHEVROLET | EXPRESS  | CARGO VAN        | DPR  | 11050      |           | MURPHYS AUCTION        | 
| 03015    | 2000 | CHEVROLET | G3500    | CARGO VAN - HVAC | FAS  | 6600       |           | MURPHYS AUCTION        | 
| 61731    | 2006 | CHEVROLET | IMPALA   | MIDSIZE SEDAN    | SPD  | 3217       |           | BIDADOO ONLINE AUCTION | 
| 41711    | 2004 | CHEVROLET | IMPALA   | MIDSIZE SEDAN    | SPD  | 2550       |           | BIDADOO ONLINE AUCTION | 
| 34550    | 2003 | CHEVROLET | S10      | COMPACT PICKUP   | SPU  | 3355       |           | BIDADOO ONLINE AUCTION | 
| 7019     | 1991 | YALE      | FORKLIFT | FORKLIFT         | CEN  | 5101       |           | BIDADOO ONLINE AUCTION | 
```