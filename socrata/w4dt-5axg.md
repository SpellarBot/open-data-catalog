# Puget Sound Final Abundance Steelhead 10222012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/puget-sound-final-abundance-steelhead-10222012-4ad4e) |
| Metadata | [Link](https://data.wa.gov/api/views/w4dt-5axg) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/w4dt-5axg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/w4dt-5axg/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | w4dt-5axg |
| Name | Puget Sound Final Abundance Steelhead 10222012 |
| Created | 2012-10-23T13:36:23Z |
| Publication Date | 2012-10-26T16:21:52Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | population_stock_number | Population/Stock Number | text      | number      |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | numeric metric | wild                    | Wild                    | number    | number      |
| Yes      | series tag     | hatchery                | Hatchery                | text      | text        |
| Yes      | numeric metric | wild_hatchery           | Wild + Hatchery         | number    | number      |
| Yes      | series tag     | goal_wild               | Goal (Wild)             | text      | text        |
| Yes      | series tag     | population_stock_name   | Population/Stock Name   | text      | text        |
| No       |                | listing_year            | Listing Year            | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = listing_year
```

## Data Commands

```ls
series e:w4dt-5axg d:2004-01-01T00:00:00.000Z t:population_stock_number=6015 t:population_stock_name="Nooksack Winter Steelhead" t:goal_wild=unknown m:wild=1574 m:wild_hatchery=1574

series e:w4dt-5axg d:2010-01-01T00:00:00.000Z t:population_stock_number=6015 t:population_stock_name="Nooksack Winter Steelhead" t:goal_wild=unknown m:wild=1897 m:wild_hatchery=1897

series e:w4dt-5axg d:2011-01-01T00:00:00.000Z t:population_stock_number=6015 t:population_stock_name="Nooksack Winter Steelhead" t:goal_wild=unknown m:wild=1774 m:wild_hatchery=1774
```

## Meta Commands

```ls
metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

entity e:w4dt-5axg l:"Puget Sound Final Abundance Steelhead 10222012" t:url=https://data.wa.gov/api/views/w4dt-5axg

property e:w4dt-5axg t:meta.view v:id=w4dt-5axg v:averageRating=0 v:name="Puget Sound Final Abundance Steelhead 10222012"

property e:w4dt-5axg t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:w4dt-5axg t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| population_stock_number | year | wild | hatchery | wild_hatchery | goal_wild | population_stock_name                       | listing_year | 
| ======================= | ==== | ==== | ======== | ============= | ========= | =========================================== | ============ | 
| 6007                    | 1997 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
| 6007                    | 1998 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
| 6007                    | 1999 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
| 6007                    | 2000 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
| 6007                    | 2001 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
| 6007                    | 2002 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
| 6007                    | 2003 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
| 6007                    | 2004 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
| 6007                    | 2005 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
| 6007                    | 2006 |      |          |               | unknown   | Drayton Harbor Tributaries Winter Steelhead | 2007         | 
```