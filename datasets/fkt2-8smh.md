# Missouri Beer, Wine and Liquor Wholesaler List with Zip Code

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-beer-wine-and-liquor-wholesaler-list-with-zip-code-1e403) |
| Metadata | [Link](https://data.mo.gov/api/views/fkt2-8smh) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/fkt2-8smh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/fkt2-8smh/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | fkt2-8smh |
| Name | Missouri Beer, Wine and Liquor Wholesaler List with Zip Code |
| Attribution | Missouri Division of Alcohol and Tobacco Control |
| Category | Regulatory |
| Tags | missouri, liquor, wine, wholesaler, solicitor, zip code, excise, tax |
| Created | 2012-08-07T14:42:57Z |
| Publication Date | 2017-04-20T13:05:11Z |

## Description

Listing of current Missouri beer, wine and liquor wholesalers with their associated zip codes. This listing is updated daily.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | business_name  | Business Name  | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | text        |
| Yes      | series tag  | license_number | License Number | text      | text        |
| Yes      | series tag  | license_type   | License Type   | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fkt2-8smh d:2017-04-20T13:05:04.000Z t:business_name="A. BOMMARITO WINES INC." t:license_type=LWS t:zip_code=631442711 t:license_number=63265 t:city=BRENTWOOD m:row_number.fkt2-8smh=1

series e:fkt2-8smh d:2017-04-20T13:05:04.000Z t:business_name="A-BLONDES INC." t:license_type=LWS t:zip_code=630053618 t:license_number=205575 t:city=CHESTERFIELD m:row_number.fkt2-8smh=2

series e:fkt2-8smh d:2017-04-20T13:05:04.000Z t:business_name="ALPHA BREWING COMPANY LLC" t:license_type=22WS t:zip_code=631031936 t:license_number=219074 t:city="ST. LOUIS" m:row_number.fkt2-8smh=3
```

## Meta Commands

```ls
metric m:row_number.fkt2-8smh p:long l:"Row Number"

entity e:fkt2-8smh l:"Missouri Beer, Wine and Liquor Wholesaler List with Zip Code" t:attribution="Missouri Division of Alcohol and Tobacco Control" t:url=https://data.mo.gov/api/views/fkt2-8smh

property e:fkt2-8smh t:meta.view v:id=fkt2-8smh v:category=Regulatory v:attributionLink=http://www.atc.dps.mo.gov v:averageRating=0 v:name="Missouri Beer, Wine and Liquor Wholesaler List with Zip Code" v:attribution="Missouri Division of Alcohol and Tobacco Control"

property e:fkt2-8smh t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:fkt2-8smh t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| :updated_at | business_name                            | zip_code  | license_number | license_type | city             | 
| =========== | ======================================== | ========= | ============== | ============ | ================ | 
| 1492693504  | A. BOMMARITO WINES INC.                  | 631442711 | 63265          | LWS          | BRENTWOOD        | 
| 1492693504  | A-BLONDES INC.                           | 630053618 | 205575         | LWS          | CHESTERFIELD     | 
| 1492693504  | ALPHA BREWING COMPANY LLC                | 631031936 | 219074         | 22WS         | ST. LOUIS        | 
| 1492693504  | ANSON DISTRIBUTING LLC                   | 646440000 | 235738         | 22WS         | HAMILTON         | 
| 1492693504  | APPELLATIONS LLC                         | 630433530 | 180068         | LWS          | MARYLAND HEIGHTS | 
| 1492693504  | APPELT'S QUALITY LIQUORS WHOLESALE DIST. | 633790000 | 238874         | 22WS         | TROY             | 
| 1492693504  | APPLE CREEK VINEYARD & WINERY LLC        | 637477313 | 209335         | 22WS         | FRIEDEIM         | 
| 1492693504  | ARTISAN SPIRITS, LLC                     | 630683206 | 201153         | LWS          | NEW HAVEN        | 
| 1492693504  | ARTISANS CELLAR INC.                     | 633763572 | 229372         | LWS          | ST. PETERS       | 
| 1492693504  | AUGUSTA WINE COMPANY                     | 633321703 | 182165         | 22WS         | AUGUSTA          | 
```