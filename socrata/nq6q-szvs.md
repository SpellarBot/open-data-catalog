# Rates of TBI-related Deaths by Age Group ??? United States, 2001 - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rates-of-tbi-related-deaths-by-age-group-united-states-20012010-956de) |
| Metadata | [Link](https://data.cdc.gov/api/views/nq6q-szvs) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/nq6q-szvs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/nq6q-szvs/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | nq6q-szvs |
| Name | Rates of TBI-related Deaths by Age Group ??? United States, 2001 - 2010 |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Traumatic Brain Injury |
| Tags | traumatic brain injury, tbi, brain injury, head trauma |
| Created | 2014-04-01T19:19:56Z |
| Publication Date | 2014-04-01T19:40:58Z |

## Description

Changes in the rates of TBI-related deaths vary depending on age.  For persons 44 years of age and younger, TBI-related deaths decreased between the periods of 2001???2002 and 2009???2010.  Rates for age groups 45???64 years of age remained stable for this same ten-year period.  For persons 65 years and older, rates of TBI-related deaths increased during this time period, from 41.2 to 45.2 deaths per 100,000.Go to http://www.cdc.gov/traumaticbraininjury/data/index.html to view more TBI data & statistics.Source: http://www.cdc.gov/traumaticbraininjury/data/rates_deaths_byage.html

## Columns

```ls
| Included | Schema Type    | Field Name | Name     | Data Type | Render Type |
| ======== | ============== | ========== | ======== | ========= | =========== |
| Yes      | series tag     | year       | Years    | text      | text        |
| Yes      | numeric metric | 0_4_yr     | 0?4 yr   | number    | number      |
| Yes      | numeric metric | 5_14_yr    | 5?14 yr  | number    | number      |
| Yes      | numeric metric | 15_24_yr   | 15?24 yr | number    | number      |
| Yes      | numeric metric | 25_44_yr   | 25?44 yr | number    | number      |
| Yes      | numeric metric | 45_64_yr   | 45?64 yr | number    | number      |
| Yes      | numeric metric | 65_yr      | 65+ yr   | number    | number      |
```

## Time Field

```ls
Value = 2001
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nq6q-szvs d:2001-01-01T00:00:00.000Z t:year=2001?2002 m:0_4_yr=5.2 m:5_14_yr=3.2 m:45_64_yr=17.5 m:15_24_yr=23.4 m:65_yr=41.2 m:25_44_yr=17.6

series e:nq6q-szvs d:2001-01-01T00:00:00.000Z t:year=2003?2004 m:0_4_yr=5.2 m:5_14_yr=3 m:45_64_yr=17.7 m:15_24_yr=22 m:65_yr=42.1 m:25_44_yr=16.8

series e:nq6q-szvs d:2001-01-01T00:00:00.000Z t:year=2005?2006 m:0_4_yr=5 m:5_14_yr=2.7 m:45_64_yr=18.1 m:15_24_yr=21.2 m:65_yr=43.8 m:25_44_yr=16.8
```

## Meta Commands

```ls
metric m:0_4_yr p:float l:"0?4 yr" t:dataTypeName=number

metric m:5_14_yr p:float l:"5?14 yr" t:dataTypeName=number

metric m:15_24_yr p:float l:"15?24 yr" t:dataTypeName=number

metric m:25_44_yr p:float l:"25?44 yr" t:dataTypeName=number

metric m:45_64_yr p:float l:"45?64 yr" t:dataTypeName=number

metric m:65_yr p:float l:"65+ yr" t:dataTypeName=number

entity e:nq6q-szvs l:"Rates of TBI-related Deaths by Age Group ??? United States, 2001 - 2010" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/nq6q-szvs

property e:nq6q-szvs t:meta.view v:id=nq6q-szvs v:category="Traumatic Brain Injury" v:attributionLink=http://www.cdc.gov/traumaticbraininjury/data/rates_deaths_byage.html v:averageRating=0 v:name="Rates of TBI-related Deaths by Age Group ??? United States, 2001 - 2010" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention"

property e:nq6q-szvs t:meta.view.license v:name="Public Domain"

property e:nq6q-szvs t:meta.view.owner v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:displayName=iqw7@cdc.gov

property e:nq6q-szvs t:meta.view.tableauthor v:id=cg4e-25jx v:screenName=iqw7@cdc.gov v:roleName=publisher v:displayName=iqw7@cdc.gov

property e:nq6q-szvs t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| year      | 0_4_yr             | 5_14_yr            | 15_24_yr | 25_44_yr           | 45_64_yr           | 65_yr | 
| ========= | ================== | ================== | ======== | ================== | ================== | ===== | 
| 2001?2002 | 5.2                | 3.2                | 23.4     | 17.600000000000001 | 17.5               | 41.2  | 
| 2003?2004 | 5.2                | 3                  | 22       | 16.8               | 17.7               | 42.1  | 
| 2005?2006 | 5                  | 2.7                | 21.2     | 16.8               | 18.100000000000001 | 43.8  | 
| 2007?2008 | 4.5999999999999996 | 2.2000000000000002 | 18.7     | 16                 | 17.899999999999999 | 44.9  | 
| 2009?2010 | 4.3                | 1.9                | 15.6     | 14.6               | 17.600000000000001 | 45.2  | 
```