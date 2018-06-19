# New York State Revenue: Beginning Fiscal Year 1991-92

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-revenue-beginning-fiscal-year-1991-92) |
| Metadata | [Link](https://data.ny.gov/api/views/eda3-in2f) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/eda3-in2f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/eda3-in2f/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | eda3-in2f |
| Name | New York State Revenue: Beginning Fiscal Year 1991-92 |
| Attribution | Division of the Budget |
| Category | Government & Finance |
| Tags | financial plan category, receipt, revenue, actuals, budget, integrity |
| Created | 2013-03-20T18:55:36Z |
| Publication Date | 2016-05-17T20:02:48Z |

## Description

This data set includes historical receipt actuals data beginning fiscal year 1991-92 for the General Fund and All Governmental Funds.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | fund_group      | Fund Group      | text      | text        |
| Yes      | series tag     | fp_category     | FP Category     | text      | text        |
| Yes      | series tag     | detail_receipt  | Detail Receipt  | text      | text        |
| Yes      | numeric metric | 2015_16_actuals | 2015-16 Actuals | number    | number      |
| Yes      | numeric metric | 2014_15_actuals | 2014-15 Actuals | number    | number      |
| Yes      | numeric metric | 2013_14_actuals | 2013-14 Actuals | number    | number      |
| Yes      | numeric metric | 2012_13_actuals | 2012-13 Actuals | number    | number      |
| Yes      | numeric metric | 2011_12_actuals | 2011-12 Actuals | number    | number      |
| Yes      | numeric metric | 2010_11_actuals | 2010-11 Actuals | number    | number      |
| Yes      | numeric metric | 2009_10_actuals | 2009-10 Actuals | number    | number      |
| Yes      | numeric metric | 2008_09_actuals | 2008-09 Actuals | number    | number      |
| Yes      | numeric metric | 2007_08_actuals | 2007-08 Actuals | number    | number      |
| Yes      | numeric metric | 2006_07_actuals | 2006-07 Actuals | number    | number      |
| Yes      | numeric metric | 2005_06_actuals | 2005-06 Actuals | number    | number      |
| Yes      | numeric metric | 2004_05_actuals | 2004-05 Actuals | number    | number      |
| Yes      | numeric metric | 2003_04_actuals | 2003-04 Actuals | number    | number      |
| Yes      | numeric metric | 2002_03_actuals | 2002-03 Actuals | number    | number      |
| Yes      | numeric metric | 2001_02_actuals | 2001-02 Actuals | number    | number      |
| Yes      | numeric metric | 2000_01_actuals | 2000-01 Actuals | number    | number      |
| Yes      | numeric metric | 1999_00_actuals | 1999-00 Actuals | number    | number      |
| Yes      | numeric metric | 1998_99_actuals | 1998-99 Actuals | number    | number      |
| Yes      | numeric metric | 1997_98_actuals | 1997-98 Actuals | number    | number      |
| Yes      | numeric metric | 1996_97_actuals | 1996-97 Actuals | number    | number      |
| Yes      | numeric metric | 1995_96_actuals | 1995-96 Actuals | number    | number      |
| Yes      | numeric metric | 1994_95_actuals | 1994-95 Actuals | number    | number      |
| Yes      | numeric metric | 1993_94_actuals | 1993-94 Actuals | number    | number      |
| Yes      | numeric metric | 1992_93_actuals | 1992-93 Actuals | number    | number      |
| Yes      | numeric metric | 1991_92_actuals | 1991-92 Actuals | number    | number      |
```

## Time Field

```ls
Value = 1991
Format & Zone = yyyy
```

## Data Commands

```ls
series e:eda3-in2f d:1991-01-01T00:00:00.000Z t:fund_group="General Fund" t:detail_receipt="Gross collections" t:fp_category="Personal income tax" m:1998_99_actuals=23371.1 m:2005_06_actuals=36544.1 m:2014_15_actuals=52248.3 m:2013_14_actuals=51575.3 m:2007_08_actuals=43170.2 m:2001_02_actuals=29089.5 m:2004_05_actuals=32767.6 m:1993_94_actuals=18727.4 m:1997_98_actuals=21088 m:1995_96_actuals=19857.6 m:1991_92_actuals=17028.1 m:2006_07_actuals=40090.3 m:2008_09_actuals=44010.9 m:2011_12_actuals=46030.4 m:1999_00_actuals=26235.6 m:1996_97_actuals=20238.3 m:2009_10_actuals=41393 m:2015_16_actuals=56600.1 m:2000_01_actuals=30071.6 m:2003_04_actuals=29089.3 m:2012_13_actuals=47442.6 m:1992_93_actuals=18074.4 m:2002_03_actuals=26944.5 m:2010_11_actuals=44002.3 m:1994_95_actuals=19028.1

series e:eda3-in2f d:1991-01-01T00:00:00.000Z t:fund_group="General Fund" t:detail_receipt="State/City Offset" t:fp_category="Personal income tax" m:1998_99_actuals=-299.6 m:2005_06_actuals=-466 m:2014_15_actuals=-590.8 m:2013_14_actuals=-615 m:2007_08_actuals=-479.2 m:2001_02_actuals=-225.2 m:2004_05_actuals=-357 m:1993_94_actuals=-167.9 m:1997_98_actuals=-278.2 m:1995_96_actuals=-152 m:1991_92_actuals=-113.2 m:2006_07_actuals=-522 m:2008_09_actuals=-474.7 m:2011_12_actuals=-366 m:1999_00_actuals=-324.7 m:1996_97_actuals=-189 m:2009_10_actuals=61.9 m:2015_16_actuals=-675.3 m:2000_01_actuals=-169.4 m:2003_04_actuals=-261.3 m:2012_13_actuals=-309 m:1992_93_actuals=-137.1 m:2002_03_actuals=-287.5 m:2010_11_actuals=-100.2 m:1994_95_actuals=-191.9

series e:eda3-in2f d:1991-01-01T00:00:00.000Z t:fund_group="General Fund" t:detail_receipt=Refunds t:fp_category="Personal income tax" m:1998_99_actuals=-2495.4 m:2005_06_actuals=-5265.2 m:2014_15_actuals=-7947.7 m:2013_14_actuals=-7999.3 m:2007_08_actuals=-6127.2 m:2001_02_actuals=-3290.6 m:2004_05_actuals=-4310.5 m:1993_94_actuals=-2057.5 m:1997_98_actuals=-2520.8 m:1995_96_actuals=-2307.1 m:1991_92_actuals=-1972.3 m:2006_07_actuals=-4988.3 m:2008_09_actuals=-6696.2 m:2011_12_actuals=-6896.6 m:1999_00_actuals=-2716.5 m:1996_97_actuals=-2494.9 m:2009_10_actuals=-6703.7 m:2015_16_actuals=-8869.5 m:2000_01_actuals=-3459.6 m:2003_04_actuals=-4180.8 m:2012_13_actuals=-6906.8 m:1992_93_actuals=-1976.6 m:2002_03_actuals=-4008.6 m:2010_11_actuals=-7692.2 m:1994_95_actuals=-2108.3
```

## Meta Commands

```ls
metric m:2015_16_actuals p:float l:"2015-16 Actuals" d:"Financial plan revenue actuals, in millions of dollars" t:dataTypeName=number

metric m:2014_15_actuals p:float l:"2014-15 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2013_14_actuals p:float l:"2013-14 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2012_13_actuals p:float l:"2012-13 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2011_12_actuals p:float l:"2011-12 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2010_11_actuals p:float l:"2010-11 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2009_10_actuals p:float l:"2009-10 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2008_09_actuals p:float l:"2008-09 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2007_08_actuals p:float l:"2007-08 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2006_07_actuals p:float l:"2006-07 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2005_06_actuals p:float l:"2005-06 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2004_05_actuals p:float l:"2004-05 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2003_04_actuals p:float l:"2003-04 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2002_03_actuals p:float l:"2002-03 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2001_02_actuals p:float l:"2001-02 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:2000_01_actuals p:float l:"2000-01 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:1999_00_actuals p:float l:"1999-00 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:1998_99_actuals p:float l:"1998-99 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:1997_98_actuals p:float l:"1997-98 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:1996_97_actuals p:float l:"1996-97 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:1995_96_actuals p:float l:"1995-96 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:1994_95_actuals p:float l:"1994-95 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:1993_94_actuals p:float l:"1993-94 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:1992_93_actuals p:float l:"1992-93 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

metric m:1991_92_actuals p:float l:"1991-92 Actuals" d:"Financial plan disbursement and actuals" t:dataTypeName=number

entity e:eda3-in2f l:"New York State Revenue: Beginning Fiscal Year 1991-92" t:attribution="Division of the Budget" t:url=https://data.ny.gov/api/views/eda3-in2f

property e:eda3-in2f t:meta.view v:id=eda3-in2f v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Revenue: Beginning Fiscal Year 1991-92" v:attribution="Division of the Budget"

property e:eda3-in2f t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:eda3-in2f t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| fund_group   | fp_category         | detail_receipt              | 2015_16_actuals | 2014_15_actuals | 2013_14_actuals | 2012_13_actuals | 2011_12_actuals | 2010_11_actuals | 2009_10_actuals | 2008_09_actuals | 2007_08_actuals | 2006_07_actuals | 2005_06_actuals | 2004_05_actuals | 2003_04_actuals | 2002_03_actuals | 2001_02_actuals | 2000_01_actuals | 1999_00_actuals | 1998_99_actuals | 1997_98_actuals | 1996_97_actuals | 1995_96_actuals | 1994_95_actuals | 1993_94_actuals | 1992_93_actuals | 1991_92_actuals | 
| ============ | =================== | =========================== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | 
| General Fund | Personal income tax | Gross collections           | 56600.1         | 52248.3         | 51575.3         | 47442.6         | 46030.4         | 44002.3         | 41393.0         | 44010.9         | 43170.2         | 40090.3         | 36544.1         | 32767.6         | 29089.3         | 26944.5         | 29089.5         | 30071.6         | 26235.6         | 23371.1         | 21088.0         | 20238.3         | 19857.6         | 19028.1         | 18727.4         | 18074.4         | 17028.1         | 
| General Fund | Personal income tax | State/City Offset           | -675.3          | -590.8          | -615.0          | -309.0          | -366.0          | -100.2          | 61.9            | -474.7          | -479.2          | -522.0          | -466.0          | -357.0          | -261.3          | -287.5          | -225.2          | -169.4          | -324.7          | -299.6          | -278.2          | -189.0          | -152.0          | -191.9          | -167.9          | -137.1          | -113.2          | 
| General Fund | Personal income tax | Refunds                     | -8869.5         | -7947.7         | -7999.3         | -6906.8         | -6896.6         | -7692.2         | -6703.7         | -6696.2         | -6127.2         | -4988.3         | -5265.2         | -4310.5         | -4180.8         | -4008.6         | -3290.6         | -3459.6         | -2716.5         | -2495.4         | -2520.8         | -2494.9         | -2307.1         | -2108.3         | -2057.5         | -1976.6         | -1972.3         | 
| General Fund | Personal income tax | STAR                        | -3334.7         | -3296.9         | -3356.8         | -3286.2         | -3232.9         | -3263.4         | -3408.9         | -4434.0         | -4663.5         | -3994.0         | -3213.2         | -3058.9         | -2819.5         | -2664.1         | -1310.1         | -3076.5         | -1194.6         | -582.2          | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 
| General Fund | Personal income tax | Refund Reserve              | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | -103.4          | -597.2          | 1050.0          | 1840.0          | 449.6           | -1661.1         | 86.3            | -530.4          | -1183.5         | -400.4          | 861.6           | -468.5          | -641.9          | -29.2           | 
| General Fund | Personal income tax | RBTF                        | -11763.8        | -10927.5        | -10740.3        | -10056.7        | -9692.0         | -9052.4         | -8687.9         | -9210.0         | -9141.0         | -7646.5         | -6899.9         | -6260.3         | -5456.9         | -4243.4         | -250.0          | -250.0          | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 
| General Fund | User taxes          | Sales and use taxes         | 6242.6          | 6084.3          | 5884.8          | 8423.1          | 8345.5          | 8084.8          | 7404.5          | 7707.1          | 7944.9          | 7538.9          | 7977.9          | 8094.5          | 7241.1          | 6327.6          | 6131.3          | 6271.6          | 6141.0          | 5696.7          | 5442.3          | 5225.0          | 4994.8          | 4897.8          | 4559.6          | 4486.8          | 4359.2          | 
| General Fund | User taxes          | Cigarette and tobacco taxes | 322.2           | 355.4           | 426.2           | 442.7           | 471.4           | 480.2           | 456.4           | 446.4           | 408.8           | 410.7           | 403.6           | 405.8           | 419.2           | 446.5           | 531.7           | 528.3           | 643.2           | 666.6           | 675.5           | 667.0           | 693.4           | 726.5           | 707.6           | 555.1           | 596.2           | 
| General Fund | User taxes          | Motor fuel tax              | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 17.3            | 179.9           | 171.1           | 165.3           | 157.5           | 173.6           | 169.0           | 173.6           | 413.0           | 417.2           | 
| General Fund | User taxes          | Highway use tax             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 0.0             | 10.9            | 152.2           | 138.9           | 
```