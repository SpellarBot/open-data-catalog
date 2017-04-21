# 2015 Monthly Housing Permit Data From Census

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-monthly-housing-permit-data-from-census) |
| Metadata | [Link](https://data.ct.gov/api/views/gsuv-mkqb) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/gsuv-mkqb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/gsuv-mkqb/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | gsuv-mkqb |
| Name | 2015 Monthly Housing Permit Data From Census |
| Attribution | Department of Economic and Community Development |
| Category | Housing and Development |
| Tags | housing, permits |
| Created | 2016-03-07T20:59:20Z |
| Publication Date | 2016-03-07T21:03:36Z |

## Description

Note: *: Every ten years the Bureau of Census selects a new universe sample for the survey of building permit data.  Starting in 2015, it will collect permit information from 104 municipalities on a monthly basis.
Towns coded as "na" do not provide data.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| Yes      | series tag  | town              | TOWN              | text      | text        |
| Yes      | series tag  | county            | County            | text      | text        |
| Yes      | series tag  | labor_market_area | Labor Market Area | text      | text        |
| Yes      | series tag  | jan_2015          | Jan-2015          | text      | text        |
| Yes      | series tag  | feb_2015          | Feb-2015          | text      | text        |
| Yes      | series tag  | mar_2015          | Mar-2015          | text      | text        |
| Yes      | series tag  | apr_2015          | Apr-2015          | text      | text        |
| Yes      | series tag  | may_2015          | May-2015          | text      | text        |
| Yes      | series tag  | jun_2015          | Jun-2015          | text      | text        |
| Yes      | series tag  | jul_2015          | Jul-2015          | text      | text        |
| Yes      | series tag  | aug_2015          | Aug-2015          | text      | text        |
| Yes      | series tag  | sep_2015          | Sep-2015          | text      | text        |
| Yes      | series tag  | oct_2015          | Oct-2015          | text      | text        |
| Yes      | series tag  | nov_2015          | Nov-2015          | text      | text        |
| Yes      | series tag  | dec_2015          | Dec-2015          | text      | text        |
| Yes      | series tag  | ytd               | YTD               | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gsuv-mkqb d:2015-01-01T00:00:00.000Z t:jan_2015=0 t:oct_2015=2 t:nov_2015=1 t:dec_2015=0 t:aug_2015=0 t:may_2015=0 t:county=Tolland t:ytd=4 t:apr_2015=0 t:feb_2015=0 t:labor_market_area=Hartford t:town=Andover t:jun_2015=0 t:sep_2015=1 t:jul_2015=0 t:mar_2015=0 m:row_number.gsuv-mkqb=1

series e:gsuv-mkqb d:2015-01-01T00:00:00.000Z t:jan_2015=na t:oct_2015=na t:nov_2015=na t:dec_2015=na t:aug_2015=na t:may_2015=na t:county="New Haven" t:ytd=na t:apr_2015=na t:feb_2015=na t:labor_market_area=Bridgeport-Stamford t:town=Ansonia t:jun_2015=na t:sep_2015=na t:jul_2015=na t:mar_2015=na m:row_number.gsuv-mkqb=2

series e:gsuv-mkqb d:2015-01-01T00:00:00.000Z t:jan_2015=na t:oct_2015=na t:nov_2015=na t:dec_2015=na t:aug_2015=na t:may_2015=na t:county=Windham t:ytd=na t:apr_2015=na t:feb_2015=na t:labor_market_area=Hartford t:town=Ashford t:jun_2015=na t:sep_2015=na t:jul_2015=na t:mar_2015=na m:row_number.gsuv-mkqb=3
```

## Meta Commands

```ls
metric m:row_number.gsuv-mkqb p:long l:"Row Number"

entity e:gsuv-mkqb l:"2015 Monthly Housing Permit Data From Census" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/gsuv-mkqb

property e:gsuv-mkqb t:meta.view v:id=gsuv-mkqb v:category="Housing and Development" v:attributionLink="http://www.ct.gov/ecd/cwp/view.asp?a=1106&q=250640" v:averageRating=0 v:name="2015 Monthly Housing Permit Data From Census" v:attribution="Department of Economic and Community Development"

property e:gsuv-mkqb t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:gsuv-mkqb t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:gsuv-mkqb t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town         | county     | labor_market_area   | jan_2015 | feb_2015 | mar_2015 | apr_2015 | may_2015 | jun_2015 | jul_2015 | aug_2015 | sep_2015 | oct_2015 | nov_2015 | dec_2015 | ytd | 
| ============ | ========== | =================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | === | 
| Andover      | Tolland    | Hartford            | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 0        | 1        | 2        | 1        | 0        | 4   | 
| Ansonia      | New Haven  | Bridgeport-Stamford | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
| Ashford      | Windham    | Hartford            | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
| Avon         | Hartford   | Hartford            | 2        | 0        | 1        | 6        | 2        | 3        | 2        | 6        | 3        | 2        | 2        | 2        | 31  | 
| Barkhamsted  | Litchfield | Hartford            | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
| Beacon Falls | New Haven  | Waterbury           | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
| Berlin       | Hartford   | Hartford            | 2        | 2        | 3        | 1        | 1        | 1        | 4        | 1        | 1        | 1        | 1        | 1        | 19  | 
| Bethany      | New Haven  | New Haven           | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
| Bethel       | Fairfield  | Danbury             | 3        | 2        | 3        | 7        | 7        | 6        | 8        | 8        | 8        | 7        | 7        | 6        | 72  | 
| Bethlehem    | Litchfield | Torrington          | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na       | na  | 
```