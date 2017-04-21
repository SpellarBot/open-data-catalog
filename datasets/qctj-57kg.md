# Illinois Racing Board 2012 Monthly Amounts Wagered at Illinois racetracks, OTB Parlors and Advanced Deposit Wagering

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-racing-board-2012-monthly-amounts-wagered-at-illinois-racetracks-otb-parlors-and--62ec8) |
| Metadata | [Link](https://data.illinois.gov/api/views/qctj-57kg) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qctj-57kg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qctj-57kg/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qctj-57kg |
| Name | Illinois Racing Board 2012 Monthly Amounts Wagered at Illinois racetracks, OTB Parlors and Advanced Deposit Wagering |
| Created | 2013-02-07T19:22:23Z |
| Publication Date | 2013-02-07T19:26:51Z |

## Description

IRB racing horse ADW OTB wagering handle

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       |                | month             | Month             | text      | text        |
| No       |                | year              | Year              | number    | text        |
| Yes      | series tag     | location          | Location          | text      | text        |
| Yes      | series tag     | live_or_simulcast | Live or Simulcast | text      | text        |
| Yes      | numeric metric | handle            | Handle            | money     | money       |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:qctj-57kg d:2012-01-01T00:00:00.000Z t:live_or_simulcast=LIVE t:location="ARLINGTON AT CHICAGO, JOE'S BAR - OTB" m:handle=268798.3

series e:qctj-57kg d:2012-01-01T00:00:00.000Z t:live_or_simulcast=SIMS t:location="ARLINGTON AT CHICAGO, JOE'S BAR - OTB" m:handle=2529237.4

series e:qctj-57kg d:2012-01-01T00:00:00.000Z t:live_or_simulcast=LIVE t:location="ARLINGTON AT HODGKINS - OTB" m:handle=110511.1
```

## Meta Commands

```ls
metric m:handle p:double l:Handle t:dataTypeName=money

entity e:qctj-57kg l:"Illinois Racing Board 2012 Monthly Amounts Wagered at Illinois racetracks, OTB Parlors and Advanced Deposit Wagering" t:url=https://data.illinois.gov/api/views/qctj-57kg

property e:qctj-57kg t:meta.view v:id=qctj-57kg v:averageRating=0 v:name="Illinois Racing Board 2012 Monthly Amounts Wagered at Illinois racetracks, OTB Parlors and Advanced Deposit Wagering"

property e:qctj-57kg t:meta.view.owner v:id=td6z-24zn v:screenName="Bob Lang" v:displayName="Bob Lang"

property e:qctj-57kg t:meta.view.tableauthor v:id=td6z-24zn v:screenName="Bob Lang" v:roleName=publisher v:displayName="Bob Lang"
```

## Top Records

```ls
| month   | year | location                              | live_or_simulcast | handle     | 
| ======= | ==== | ===================================== | ================= | ========== | 
| January | 2012 | ARLINGTON AT CHICAGO, JOE'S BAR - OTB | LIVE              | 268798.30  | 
| January | 2012 | ARLINGTON AT CHICAGO, JOE'S BAR - OTB | SIMS              | 2529237.40 | 
| January | 2012 | ARLINGTON AT HODGKINS - OTB           | LIVE              | 110511.10  | 
| January | 2012 | ARLINGTON AT HODGKINS - OTB           | SIMS              | 1257378.10 | 
| January | 2012 | ARLINGTON AT VILLA PARK - OTB         | LIVE              | 70069.30   | 
| January | 2012 | ARLINGTON AT VILLA PARK - OTB         | SIMS              | 762329.20  | 
| January | 2012 | ARLINGTON AT WAUKEGAN - OTB           | LIVE              | 83177.10   | 
| January | 2012 | ARLINGTON AT WAUKEGAN - OTB           | SIMS              | 1406680.80 | 
| January | 2012 | ARLINGTON PARK RACECOURSE - IT.       | LIVE              | 156604.70  | 
| January | 2012 | ARLINGTON PARK RACECOURSE - IT.       | SIMS              | 617239.50  | 
```