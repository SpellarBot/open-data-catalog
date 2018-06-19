# Cook County Clerk - Cook County TIF Districts & Revenue by Municipality - 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-clerk-cook-county-tif-districts-revenue-by-municipality-2010-da520) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/djva-8ge5) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/djva-8ge5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/djva-8ge5/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | djva-8ge5 |
| Name | Cook County Clerk - Cook County TIF Districts & Revenue by Municipality - 2010 |
| Attribution | Cook County Clerk |
| Created | 2011-10-25T16:06:46Z |
| Publication Date | 2014-10-09T23:16:00Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name                   | Data Type | Render Type |
| ======== | ============== | ============== | ====================== | ========= | =========== |
| Yes      | series tag     | agency         | Agency #               | text      | text        |
| Yes      | series tag     | municipality   | Municipality           | text      | text        |
| Yes      | series tag     | tif_district   | TIF District           | text      | text        |
| Yes      | time           | first_tax_year | First Tax Year         | number    | number      |
| No       |                | year_cancelled | Year Cancelled         | number    | number      |
| Yes      | numeric metric | tif_revenue_1  | 2010 TIF Revenue       | money     | money       |
| Yes      | numeric metric | tif_revenue_2  | 2009 TIF Revenue       | money     | money       |
| Yes      | numeric metric | difference     | 2010-2009 % Difference | percent   | percent     |
```

## Time Field

```ls
Value = first_tax_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = year_cancelled
```

## Data Commands

```ls
series e:djva-8ge5 d:1987-01-01T00:00:00.000Z t:tif_district="Berwyn Theater Area" t:municipality=Berwyn t:agency=03-0100-500 m:difference=-6.36 m:tif_revenue_2=2011502.06 m:tif_revenue_1=1883609.03

series e:djva-8ge5 d:1993-01-01T00:00:00.000Z t:tif_district="Ogden Avenue" t:municipality=Berwyn t:agency=03-0100-501 m:difference=-18.77 m:tif_revenue_2=1237973.71 m:tif_revenue_1=1005615.93

series e:djva-8ge5 d:1996-01-01T00:00:00.000Z t:tif_district="Roosevelt Road" t:municipality=Berwyn t:agency=03-0100-502 m:difference=5.33 m:tif_revenue_2=671187.96 m:tif_revenue_1=706959.36
```

## Meta Commands

```ls
metric m:tif_revenue_1 p:double l:"2010 TIF Revenue" t:dataTypeName=money

metric m:tif_revenue_2 p:double l:"2009 TIF Revenue" t:dataTypeName=money

metric m:difference p:float l:"2010-2009 % Difference" t:dataTypeName=percent

entity e:djva-8ge5 l:"Cook County Clerk - Cook County TIF Districts & Revenue by Municipality - 2010" t:attribution="Cook County Clerk" t:url=https://datacatalog.cookcountyil.gov/api/views/djva-8ge5

property e:djva-8ge5 t:meta.view v:id=djva-8ge5 v:attributionLink=http://www.cookcountyclerk.com v:averageRating=0 v:name="Cook County Clerk - Cook County TIF Districts & Revenue by Municipality - 2010" v:attribution="Cook County Clerk"

property e:djva-8ge5 t:meta.view.license v:name="Public Domain"

property e:djva-8ge5 t:meta.view.owner v:id=g8dv-kipf v:screenName=malexander v:displayName=malexander

property e:djva-8ge5 t:meta.view.tableauthor v:id=g8dv-kipf v:screenName=malexander v:roleName=publisher v:displayName=malexander
```

## Top Records

```ls
| agency      | municipality | tif_district                   | first_tax_year | year_cancelled | tif_revenue_1 | tif_revenue_2 | difference | 
| =========== | ============ | ============================== | ============== | ============== | ============= | ============= | ========== | 
| 03-0100-500 | Berwyn       | Berwyn Theater Area            | 1987           |                | 1883609.03    | 2011502.06    | -6.36      | 
| 03-0100-501 | Berwyn       | Ogden Avenue                   | 1993           |                | 1005615.93    | 1237973.71    | -18.77     | 
| 03-0100-502 | Berwyn       | Roosevelt Road                 | 1996           |                | 706959.36     | 671187.96     | 5.33       | 
| 03-0100-503 | Berwyn       | South Berwyn Corridor          | 1996           |                | 1016578.17    | 1180445.79    | -13.88     | 
| 03-0110-500 | Blue Island  | 1                              | 1989           | 2009           | 0.0           | 0.0           | 0.0        | 
| 03-0110-501 | Blue Island  | 2 (South Industrial Area)      | 1998           |                | 1039581.72    | 1087924.75    | -4.44      | 
| 03-0110-502 | Blue Island  | 3 (Southwest Residential Area) | 1993           |                | 917182.78     | 851821.29     | 7.67       | 
| 03-0110-503 | Blue Island  | 4                              | 2007           |                | 92560.62      | 68498.52      | 35.13      | 
| 03-0110-504 | Blue Island  | 5                              | 2008           |                | 1685604.24    | 1683824.14    | 0.11       | 
| 03-0190-500 | Calumet City | -                              | 1995           |                | 1067999.19    | 709029.75     | 50.63      | 
```