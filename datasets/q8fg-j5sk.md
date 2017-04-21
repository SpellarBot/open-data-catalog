# FOIL Report ? All Markets Approved

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foil-report-all-markets-approved-02aaa) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/q8fg-j5sk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/q8fg-j5sk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/q8fg-j5sk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | q8fg-j5sk |
| Name | FOIL Report ? All Markets Approved |
| Attribution | Business Integrity Commission (BIC) |
| Category | City Government |
| Tags | wholesale, market, fulton, fish, gansevoort, hunts point, terminal, produce |
| Created | 2013-03-06T15:18:06Z |
| Publication Date | 2013-06-26T17:12:23Z |

## Description

Approved wholesale companies names , addresses and contact number

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | market       | Market       | text      | text        |
| Yes      | series tag  | company_name | Company Name | text      | text        |
| No       |             | address      | Address      | text      | text        |
| Yes      | series tag  | city         | City         | text      | text        |
| Yes      | series tag  | state        | State        | text      | text        |
| Yes      | series tag  | zip          | Zip          | text      | text        |
| Yes      | series tag  | telephone    | Telephone    | text      | text        |
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
series e:q8fg-j5sk d:2013-03-06T07:18:16.000Z t:zip=11220 t:market=BMM t:company_name="5600 MARKET CORP." t:state=NY t:telephone="(718) 491-9324" t:city=BROOKLYN m:row_number.q8fg-j5sk=1

series e:q8fg-j5sk d:2013-03-06T07:18:16.000Z t:zip=11220 t:market=BMM t:company_name="A. STEIN MEAT PRODUCTS, INC." t:state=NY t:telephone="(718) 492-0760" t:city=BROOKLYN m:row_number.q8fg-j5sk=2

series e:q8fg-j5sk d:2013-03-06T07:18:16.000Z t:zip=11210 t:market=BMM t:company_name="AGRI STAR DISTRIBUTION LLC" t:state=NY t:telephone="(718) 748-1721" t:city=BROOKLYN m:row_number.q8fg-j5sk=3
```

## Meta Commands

```ls
metric m:row_number.q8fg-j5sk p:long l:"Row Number"

entity e:q8fg-j5sk l:"FOIL Report ? All Markets Approved" t:attribution="Business Integrity Commission (BIC)" t:url=https://data.cityofnewyork.us/api/views/q8fg-j5sk

property e:q8fg-j5sk t:meta.view v:id=q8fg-j5sk v:category="City Government" v:averageRating=0 v:name="FOIL Report ? All Markets Approved" v:attribution="Business Integrity Commission (BIC)"

property e:q8fg-j5sk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:q8fg-j5sk t:meta.view.tableauthor v:id=ci6y-i73t v:screenName="Harish Pathria" v:displayName="Harish Pathria"
```

## Top Records

```ls
| :updated_at | market | company_name                            | address                      | city     | state | zip   | telephone      | 
| =========== | ====== | ======================================= | ============================ | ======== | ===== | ===== | ============== | 
| 1362554296  | BMM    | 5600 MARKET CORP.                       | 5600 FIRST AVENUE            | BROOKLYN | NY    | 11220 | (718) 491-9324 | 
| 1362554296  | BMM    | A. STEIN MEAT PRODUCTS, INC.            | 5600 FIRST AVENUE            | BROOKLYN | NY    | 11220 | (718) 492-0760 | 
| 1362554296  | BMM    | AGRI STAR DISTRIBUTION LLC              | 5600 1ST AVENUE              | BROOKLYN | NY    | 11210 | (718) 748-1721 | 
| 1362554296  | BMM    | ALEX MEAT & PROVISION, INC.             | 126 12TH STREET              | BROOKLYN | NY    | 11215 | (718) 499-7821 | 
| 1362554296  | BMM    | ALEX'S MEAT DISTRIBUTORS CORP           | 5600 FIRST AVENUE BLDG. A-35 | BROOKLYN | NY    | 11220 | (718) 238-7033 | 
| 1362554296  | BMM    | CHOW TRADING CO., INC.                  | 5600 FIRST AVENUE UNIT B14   | BROOKLYN | NY    | 11220 | (718) 238-8766 | 
| 1362554296  | BMM    | CHOWS BROTHERS WHOLESALE MEAT CO., INC. | 5600 FIRST AVENUE A9         | BROOKLYN | NY    | 11220 | (718) 836-8159 | 
| 1362554296  | BMM    | CREPINI LLC                             | 5600 FIRST AVENUE            | BROOKLYN | NY    | 11220 | (718) 372-0505 | 
| 1362554296  | BMM    | E & G FOODS, INC.                       | 5600 FIRST AVENUE            | BROOKLYN | NY    | 11220 | (718) 680-1300 | 
| 1362554296  | BMM    | FORT MEAT INC.                          | 5600 FIRST AVENUE            | BROOKLYN | NY    | 11220 | (718) 439-8375 | 
```