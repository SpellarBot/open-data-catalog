# 2014 Monthly Housing Permit Data From Census

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-monthly-housing-permit-data-from-census) |
| Metadata | [Link](https://data.ct.gov/api/views/kgin-wrhv) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/kgin-wrhv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/kgin-wrhv/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | kgin-wrhv |
| Name | 2014 Monthly Housing Permit Data From Census |
| Attribution | Department of Economic and Community Development |
| Category | Housing and Development |
| Tags | housing, permits |
| Created | 2016-03-07T20:50:55Z |
| Publication Date | 2016-03-07T20:53:19Z |

## Description

Note: *: Beginning in 2005, only town level permit data will be reported as the Bureau of Census changed its sampling method and only 128 municipalities will have monthly permit data. Towns with "na" represent annual reporters. 
Note: **: Revised 2004 data with towns reporting on a monthly basis. The remaining towns are coded as "na" for month-over-month comparison.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| Yes      | series tag  | town              | TOWN              | text      | text        |
| Yes      | series tag  | county            | County            | text      | text        |
| Yes      | series tag  | labor_market_area | Labor Market Area | text      | text        |
| Yes      | series tag  | jan_2014          | Jan-2014          | text      | text        |
| Yes      | series tag  | feb_2014          | Feb-2014          | text      | text        |
| Yes      | series tag  | mar_2014          | Mar-2014          | text      | text        |
| Yes      | series tag  | apr_2014          | Apr-2014          | text      | text        |
| Yes      | series tag  | may_2014          | May-2014          | text      | text        |
| Yes      | series tag  | jun_2014          | Jun-2014          | text      | text        |
| Yes      | series tag  | jul_2014          | Jul-2014          | text      | text        |
| Yes      | series tag  | aug_2014          | Aug-2014          | text      | text        |
| Yes      | series tag  | sep_2014          | Sep-2014          | text      | text        |
| Yes      | series tag  | oct_2014          | Oct-2014          | text      | text        |
| Yes      | series tag  | nov_2014          | Nov-2014          | text      | text        |
| Yes      | series tag  | dec_2014          | Dec-2014          | text      | text        |
| Yes      | series tag  | ytd               | YTD               | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kgin-wrhv d:2014-01-01T00:00:00.000Z t:jul_2014=0 t:jan_2014=0 t:oct_2014=0 t:nov_2014=0 t:dec_2014=0 t:may_2014=1 t:apr_2014=0 t:county=Tolland t:ytd=2 t:aug_2014=0 t:town=Andover t:feb_2014=0 t:labor_market_area=Hartford t:sep_2014=0 t:mar_2014=0 t:jun_2014=1 m:row_number.kgin-wrhv=1

series e:kgin-wrhv d:2014-01-01T00:00:00.000Z t:jul_2014=0 t:jan_2014=0 t:oct_2014=0 t:nov_2014=0 t:dec_2014=0 t:may_2014=0 t:apr_2014=0 t:county="New Haven" t:ytd=0 t:aug_2014=0 t:town=Ansonia t:feb_2014=0 t:labor_market_area=Bridgeport-Stamford t:sep_2014=0 t:mar_2014=0 t:jun_2014=0 m:row_number.kgin-wrhv=2

series e:kgin-wrhv d:2014-01-01T00:00:00.000Z t:jul_2014=0 t:jan_2014=0 t:oct_2014=0 t:nov_2014=0 t:dec_2014=0 t:may_2014=0 t:apr_2014=2 t:county=Windham t:ytd=5 t:aug_2014=0 t:town=Ashford t:feb_2014=1 t:labor_market_area=Hartford t:sep_2014=0 t:mar_2014=0 t:jun_2014=2 m:row_number.kgin-wrhv=3
```

## Meta Commands

```ls
metric m:row_number.kgin-wrhv p:long l:"Row Number"

entity e:kgin-wrhv l:"2014 Monthly Housing Permit Data From Census" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/kgin-wrhv

property e:kgin-wrhv t:meta.view v:id=kgin-wrhv v:category="Housing and Development" v:attributionLink="http://www.ct.gov/ecd/cwp/view.asp?a=1106&q=250640" v:averageRating=0 v:name="2014 Monthly Housing Permit Data From Census" v:attribution="Department of Economic and Community Development"

property e:kgin-wrhv t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:kgin-wrhv t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town         | county     | labor_market_area   | jan_2014 | feb_2014 | mar_2014 | apr_2014 | may_2014 | jun_2014 | jul_2014 | aug_2014 | sep_2014 | oct_2014 | nov_2014 | dec_2014 | ytd | 
| ============ | ========== | =================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | === | 
| Andover      | Tolland    | Hartford            | 0        | 0        | 0        | 0        | 1        | 1        | 0        | 0        | 0        | 0        | 0        | 0        | 2   | 
| Ansonia      | New Haven  | Bridgeport-Stamford | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0   | 
| Ashford      | Windham    | Hartford            | 0        | 1        | 0        | 2        | 0        | 2        | 0        | 0        | 0        | 0        | 0        | 0        | 5   | 
| Avon         | Hartford   | Hartford            | 3        | 1        | 2        | 1        | 3        | 3        | 1        | 2        | 3        | 0        | 1        | 2        | 22  | 
| Barkhamsted  | Litchfield | Hartford            | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
| Beacon Falls | New Haven  | Waterbury           | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
| Berlin       | Hartford   | Hartford            | 1        | 0        | 0        | 3        | 4        | 3        | 4        | 1        | 4        | 3        | 3        | 0        | 26  | 
| Bethany      | New Haven  | New Haven           | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
| Bethel       | Fairfield  | Danbury             | 12       | 13       | 12       | 4        | 8        | 3        | 2        | 8        | 1        | 1        | 0        | 4        | 68  | 
| Bethlehem    | Litchfield | Torrington          | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
```