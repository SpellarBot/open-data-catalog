# 2013 Monthly Housing Permit Data From Census

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-monthly-housing-permit-data-from-census) |
| Metadata | [Link](https://data.ct.gov/api/views/nua2-26ye) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/nua2-26ye/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/nua2-26ye/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | nua2-26ye |
| Name | 2013 Monthly Housing Permit Data From Census |
| Attribution | Department of Economic and Community Development |
| Category | Housing and Development |
| Tags | housing, permits, towns |
| Created | 2014-03-22T19:31:54Z |
| Publication Date | 2014-03-22T19:33:23Z |

## Description

Note: *: Beginning in 2005, only town level permit data will be reported as the Bureau of Census changed its sampling method and only 128 municipalities will have monthly permit data.  Towns with "na" represent annual reporters.  
Note: **: Revised 2004 data with towns reporting on a monthly basis.  The remaining towns are coded as "na" for month-over-month comparison.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| Yes      | series tag  | town              | TOWN              | text      | text        |
| Yes      | series tag  | county            | County            | text      | text        |
| Yes      | series tag  | labor_market_area | Labor Market Area | text      | text        |
| Yes      | series tag  | jan_13            | Jan-13            | text      | text        |
| Yes      | series tag  | feb_13            | Feb-13            | text      | text        |
| Yes      | series tag  | mar_13            | Mar-13            | text      | text        |
| Yes      | series tag  | apr_13            | Apr-13            | text      | text        |
| Yes      | series tag  | may_13            | May-13            | text      | text        |
| Yes      | series tag  | jun_13            | Jun-13            | text      | text        |
| Yes      | series tag  | jul_13            | Jul-13            | text      | text        |
| Yes      | series tag  | aug_13            | Aug-13            | text      | text        |
| Yes      | series tag  | sep_13            | Sep-13            | text      | text        |
| Yes      | series tag  | oct_13            | Oct-13            | text      | text        |
| Yes      | series tag  | nov_13            | Nov-13            | text      | text        |
| Yes      | series tag  | ytd               | YTD               | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nua2-26ye d:2013-01-01T00:00:00.000Z t:jul_13=2 t:jun_13=1 t:oct_13=0 t:nov_13=0 t:mar_13=0 t:may_13=1 t:aug_13=1 t:feb_13=0 t:county=Tolland t:apr_13=0 t:ytd=5 t:sep_13=0 t:town=Andover t:labor_market_area=Hartford t:jan_13=0 m:row_number.nua2-26ye=1

series e:nua2-26ye d:2013-01-01T00:00:00.000Z t:jul_13=0 t:jun_13=0 t:oct_13=0 t:nov_13=0 t:mar_13=0 t:may_13=1 t:aug_13=0 t:feb_13=0 t:county="New Haven" t:apr_13=0 t:ytd=1 t:sep_13=0 t:town=Ansonia t:labor_market_area=Bridgeport-Stamford t:jan_13=0 m:row_number.nua2-26ye=2

series e:nua2-26ye d:2013-01-01T00:00:00.000Z t:jul_13=0 t:jun_13=1 t:oct_13=0 t:nov_13=0 t:mar_13=0 t:may_13=1 t:aug_13=1 t:feb_13=0 t:county=Windham t:apr_13=0 t:ytd=3 t:sep_13=0 t:town=Ashford t:labor_market_area=Hartford t:jan_13=0 m:row_number.nua2-26ye=3
```

## Meta Commands

```ls
metric m:row_number.nua2-26ye p:long l:"Row Number"

entity e:nua2-26ye l:"2013 Monthly Housing Permit Data From Census" t:attribution="Department of Economic and Community Development" t:url=https://data.ct.gov/api/views/nua2-26ye

property e:nua2-26ye t:meta.view v:id=nua2-26ye v:category="Housing and Development" v:attributionLink="http://www.ct.gov/ecd/cwp/view.asp?a=1106&q=250640" v:averageRating=0 v:name="2013 Monthly Housing Permit Data From Census" v:attribution="Department of Economic and Community Development"

property e:nua2-26ye t:meta.view.license v:name="Public Domain"

property e:nua2-26ye t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:nua2-26ye t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| town         | county     | labor_market_area   | jan_13 | feb_13 | mar_13 | apr_13 | may_13 | jun_13 | jul_13 | aug_13 | sep_13 | oct_13 | nov_13 | ytd | 
| ============ | ========== | =================== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | === | 
| Andover      | Tolland    | Hartford            | 0      | 0      | 0      | 0      | 1      | 1      | 2      | 1      | 0      | 0      | 0      | 5   | 
| Ansonia      | New Haven  | Bridgeport-Stamford | 0      | 0      | 0      | 0      | 1      | 0      | 0      | 0      | 0      | 0      | 0      | 1   | 
| Ashford      | Windham    | Hartford            | 0      | 0      | 0      | 0      | 1      | 1      | 0      | 1      | 0      | 0      | 0      | 3   | 
| Avon         | Hartford   | Hartford            | 2      | 4      | 1      | 6      | 5      | 6      | 3      | 2      | 2      | 4      | 3      | 38  | 
| Barkhamsted  | Litchfield | Hartford            | na     | na     | na     | na     | na     | na     | na     | na     | na     | na     | na     | na  | 
| Beacon Falls | New Haven  | Waterbury           | na     | na     | na     | na     | na     | na     | na     | na     | na     | na     | na     | na  | 
| Berlin       | Hartford   | Hartford            | 14     | 9      | 13     | 7      | 7      | 7      | 7      | 7      | 4      | 5      | 6      | 86  | 
| Bethany      | New Haven  | New Haven           | na     | na     | na     | na     | na     | na     | na     | na     | na     | na     | na     | na  | 
| Bethel       | Fairfield  | Danbury             | 6      | 3      | 0      | 5      | 5      | 5      | 5      | 4      | 4      | 6      | 6      | 49  | 
| Bethlehem    | Litchfield | Torrington          | na     | na     | na     | na     | na     | na     | na     | na     | na     | na     | na     | na  | 
```