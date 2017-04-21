# Rates of TBI-related Emergency Department Visits, Hospitalizations, and Deaths by Sex ??? United States, 2001 ? 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rates-of-tbi-related-emergency-department-visits-hospitalizations-and-deaths-by-sex-united-408b7) |
| Metadata | [Link](https://data.cdc.gov/api/views/b4av-siev) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/b4av-siev/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/b4av-siev/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | b4av-siev |
| Name | Rates of TBI-related Emergency Department Visits, Hospitalizations, and Deaths by Sex ??? United States, 2001 ? 2010 |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Traumatic Brain Injury |
| Tags | traumatic brain injury, tbi, brain injury, head trauma |
| Created | 2014-04-02T16:38:08Z |
| Publication Date | 2014-04-02T16:43:35Z |

## Description

Overall rates of TBI climbed slowly from 2001 through 2007, then spiked sharply in 2008 and continued to climb through 2010.  The increase in TBI rates in 2008 was much sharper for men (nearly 40% increase) than for women (20% increase).  In 2007, overall rates of TBI were 26% higher in men compared to women.  In 2008, that gap began to widen, reaching 61% in 2009 before narrowing to 29% in 2010.  Rates of overall TBI are largely driven by rates of TBI-related ED visits.

## Columns

```ls
| Included | Schema Type    | Field Name | Name  | Data Type | Render Type |
| ======== | ============== | ========== | ===== | ========= | =========== |
| Yes      | time           | year       | Year  | number    | text        |
| Yes      | numeric metric | men        | Men   | number    | number      |
| Yes      | numeric metric | women      | Women | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:b4av-siev d:2001-01-01T00:00:00.000Z m:men=626.4 m:women=420.9

series e:b4av-siev d:2002-01-01T00:00:00.000Z m:men=660.6 m:women=419.3

series e:b4av-siev d:2003-01-01T00:00:00.000Z m:men=649.8 m:women=426.3
```

## Meta Commands

```ls
metric m:men p:float l:Men t:dataTypeName=number

metric m:women p:float l:Women t:dataTypeName=number

entity e:b4av-siev l:"Rates of TBI-related Emergency Department Visits, Hospitalizations, and Deaths by Sex ??? United States, 2001 ? 2010" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/b4av-siev

property e:b4av-siev t:meta.view v:id=b4av-siev v:category="Traumatic Brain Injury" v:attributionLink=http://www.cdc.gov/traumaticbraininjury/data/rates_bysex.html v:averageRating=0 v:name="Rates of TBI-related Emergency Department Visits, Hospitalizations, and Deaths by Sex ??? United States, 2001 ? 2010" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:b4av-siev t:meta.view.license v:name="Public Domain"

property e:b4av-siev t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:b4av-siev t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:b4av-siev t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| year | men                | women | 
| ==== | ================== | ===== | 
| 2001 | 626.4              | 420.9 | 
| 2002 | 660.6              | 419.3 | 
| 2003 | 649.79999999999995 | 426.3 | 
| 2004 | 732.1              | 475.9 | 
| 2005 | 732.3              | 503.9 | 
| 2006 | 689.6              | 504.7 | 
| 2007 | 634.1              | 502.5 | 
| 2008 | 863.6              | 599   | 
| 2009 | 982.3              | 607.6 | 
| 2010 | 932.1              | 720.3 | 
```