# New York State Budget and Actuals: Beginning Fiscal Year 1994-95

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-budget-and-actuals-beginning-fiscal-year-1994-95) |
| Metadata | [Link](https://data.ny.gov/api/views/4mpt-rfrw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4mpt-rfrw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4mpt-rfrw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4mpt-rfrw |
| Name | New York State Budget and Actuals: Beginning Fiscal Year 1994-95 |
| Attribution | New York State Division of the Budget |
| Category | Government & Finance |
| Tags | budget, actuals, spending |
| Created | 2013-02-20T19:34:03Z |
| Publication Date | 2017-02-27T18:39:18Z |

## Description

This data includes disbursement information for the budget year and prior years going back to 1994 for all governmental funds.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | function          | Function          | text      | text        |
| Yes      | series tag     | agency            | Agency            | text      | text        |
| Yes      | series tag     | fund_type         | Fund Type         | text      | text        |
| Yes      | series tag     | fp_category       | FP Category       | text      | text        |
| Yes      | series tag     | fund              | Fund              | text      | text        |
| Yes      | series tag     | subfund           | Subfund           | text      | text        |
| Yes      | series tag     | subfund_name      | Subfund Name      | text      | text        |
| Yes      | numeric metric | 2017_18_estimates | 2017-18 Estimates | money     | money       |
| Yes      | numeric metric | 2016_17_estimates | 2016-17 Estimates | money     | money       |
| Yes      | numeric metric | 2015_16_actuals   | 2015-16 Actuals   | money     | money       |
| Yes      | numeric metric | 2014_15_actuals   | 2014-15 Actuals   | money     | money       |
| Yes      | numeric metric | 2013_14_actuals   | 2013-14 Actuals   | money     | money       |
| Yes      | numeric metric | 2012_13_actuals   | 2012-13 Actuals   | money     | money       |
| Yes      | numeric metric | 2011_12_actuals   | 2011-12 Actuals   | money     | money       |
| Yes      | numeric metric | 2010_11_actuals   | 2010-11 Actuals   | money     | money       |
| Yes      | numeric metric | 2009_10_actuals   | 2009-10 Actuals   | money     | money       |
| Yes      | numeric metric | 2008_09_actuals   | 2008-09 Actuals   | money     | money       |
| Yes      | numeric metric | 2007_08_actuals   | 2007-08 Actuals   | money     | money       |
| Yes      | numeric metric | 2006_07_actuals   | 2006-07 Actuals   | money     | money       |
| Yes      | numeric metric | 2005_06_actuals   | 2005-06 Actuals   | money     | money       |
| Yes      | numeric metric | 2004_05_actuals   | 2004-05 Actuals   | money     | money       |
| Yes      | numeric metric | 2003_04_actuals   | 2003-04 Actuals   | money     | money       |
| Yes      | numeric metric | 2002_03_actuals   | 2002-03 Actuals   | money     | money       |
| Yes      | numeric metric | 2001_02_actuals   | 2001-02 Actuals   | money     | money       |
| Yes      | numeric metric | 2000_01_actuals   | 2000-01 Actuals   | money     | money       |
| Yes      | numeric metric | 1999_00_actuals   | 1999-00 Actuals   | money     | money       |
| Yes      | numeric metric | 1998_99_actuals   | 1998-99 Actuals   | money     | money       |
| Yes      | numeric metric | 1997_98_actuals   | 1997-98 Actuals   | money     | money       |
| Yes      | numeric metric | 1996_97_actuals   | 1996-97 Actuals   | money     | money       |
| Yes      | numeric metric | 1995_96_actuals   | 1995-96 Actuals   | money     | money       |
| Yes      | numeric metric | 1994_95_actuals   | 1994-95 Actuals   | money     | money       |
```

## Time Field

```ls
Value = 1994
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4mpt-rfrw d:1994-01-01T00:00:00.000Z t:fund_type="Capital Projects Funds - Other" t:subfund_name="Capital Project" t:fp_category="Capital Projects" t:agency="Agriculture and Markets, Department of" t:fund="Capital Projects Fund" t:subfund=30000 t:function="Economic Development and Government Oversight" m:2005_06_actuals=948 m:1998_99_actuals=2494 m:2017_18_estimates=4100 m:2014_15_actuals=10264 m:2011_12_actuals=1002 m:1999_00_actuals=2704 m:2013_14_actuals=3646 m:2007_08_actuals=1218 m:1996_97_actuals=1437 m:2009_10_actuals=1750 m:2015_16_actuals=4771 m:2000_01_actuals=2013 m:2004_05_actuals=1029 m:2001_02_actuals=1747 m:2003_04_actuals=573 m:2012_13_actuals=1020 m:2002_03_actuals=1545 m:1997_98_actuals=4056 m:2010_11_actuals=1750 m:1995_96_actuals=3108 m:2016_17_estimates=3501 m:2006_07_actuals=1650 m:1994_95_actuals=2912 m:2008_09_actuals=1769

series e:4mpt-rfrw d:1994-01-01T00:00:00.000Z t:fund_type="Capital Projects Funds - Other" t:subfund_name="CPF - Auth Bond" t:fp_category="Capital Projects" t:agency="Agriculture and Markets, Department of" t:fund="Capital Projects Fund" t:subfund=300CC t:function="Economic Development and Government Oversight" m:2005_06_actuals=0 m:1998_99_actuals=0 m:2017_18_estimates=16115 m:2014_15_actuals=737 m:2011_12_actuals=16954 m:1999_00_actuals=0 m:2013_14_actuals=2035 m:2007_08_actuals=483 m:1996_97_actuals=0 m:2009_10_actuals=1835 m:2015_16_actuals=5 m:2000_01_actuals=0 m:2004_05_actuals=0 m:2001_02_actuals=0 m:2003_04_actuals=0 m:2012_13_actuals=15738 m:2002_03_actuals=0 m:1997_98_actuals=0 m:2010_11_actuals=3455 m:1995_96_actuals=0 m:2016_17_estimates=5000 m:2006_07_actuals=4 m:1994_95_actuals=0 m:2008_09_actuals=670

series e:4mpt-rfrw d:1994-01-01T00:00:00.000Z t:fund_type="Capital Projects Funds - Other" t:subfund_name=CPF-1996CWA(Bon t:fp_category="Capital Projects" t:agency="Agriculture and Markets, Department of" t:fund="Clean Water/Clean Air Implementation" t:subfund=305BM t:function="Economic Development and Government Oversight" m:2005_06_actuals=0 m:1998_99_actuals=0 m:2017_18_estimates=0 m:2014_15_actuals=0 m:2011_12_actuals=0 m:1999_00_actuals=0 m:2013_14_actuals=0 m:2007_08_actuals=0 m:1996_97_actuals=0 m:2009_10_actuals=0 m:2015_16_actuals=0 m:2000_01_actuals=182 m:2004_05_actuals=0 m:2001_02_actuals=111 m:2003_04_actuals=0 m:2012_13_actuals=0 m:2002_03_actuals=0 m:1997_98_actuals=0 m:2010_11_actuals=0 m:1995_96_actuals=0 m:2016_17_estimates=0 m:2006_07_actuals=0 m:1994_95_actuals=0 m:2008_09_actuals=0
```

## Meta Commands

```ls
metric m:2017_18_estimates p:integer l:"2017-18 Estimates" d:"Financial plan disbursement estimates" t:dataTypeName=money

metric m:2016_17_estimates p:integer l:"2016-17 Estimates" d:"Financial plan disbursement estimates, in thousands of dollars" t:dataTypeName=money

metric m:2015_16_actuals p:integer l:"2015-16 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2014_15_actuals p:integer l:"2014-15 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2013_14_actuals p:integer l:"2013-14 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2012_13_actuals p:integer l:"2012-13 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2011_12_actuals p:integer l:"2011-12 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2010_11_actuals p:integer l:"2010-11 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2009_10_actuals p:integer l:"2009-10 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2008_09_actuals p:integer l:"2008-09 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2007_08_actuals p:integer l:"2007-08 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2006_07_actuals p:integer l:"2006-07 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2005_06_actuals p:integer l:"2005-06 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2004_05_actuals p:integer l:"2004-05 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2003_04_actuals p:integer l:"2003-04 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2002_03_actuals p:integer l:"2002-03 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2001_02_actuals p:integer l:"2001-02 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:2000_01_actuals p:integer l:"2000-01 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:1999_00_actuals p:integer l:"1999-00 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:1998_99_actuals p:integer l:"1998-99 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:1997_98_actuals p:integer l:"1997-98 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:1996_97_actuals p:integer l:"1996-97 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:1995_96_actuals p:integer l:"1995-96 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

metric m:1994_95_actuals p:integer l:"1994-95 Actuals" d:"Financial plan disbursement actuals, in thousands of dollars" t:dataTypeName=money

entity e:4mpt-rfrw l:"New York State Budget and Actuals: Beginning Fiscal Year 1994-95" t:attribution="New York State Division of the Budget" t:url=https://data.ny.gov/api/views/4mpt-rfrw

property e:4mpt-rfrw t:meta.view v:id=4mpt-rfrw v:category="Government & Finance" v:attributionLink=http://openbudget.ny.gov/ v:averageRating=0 v:name="New York State Budget and Actuals: Beginning Fiscal Year 1994-95" v:attribution="New York State Division of the Budget"

property e:4mpt-rfrw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4mpt-rfrw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4mpt-rfrw t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| function                                      | agency                                 | fund_type                      | fp_category          | fund                                 | subfund | subfund_name    | 2017_18_estimates | 2016_17_estimates | 2015_16_actuals | 2014_15_actuals | 2013_14_actuals | 2012_13_actuals | 2011_12_actuals | 2010_11_actuals | 2009_10_actuals | 2008_09_actuals | 2007_08_actuals | 2006_07_actuals | 2005_06_actuals | 2004_05_actuals | 2003_04_actuals | 2002_03_actuals | 2001_02_actuals | 2000_01_actuals | 1999_00_actuals | 1998_99_actuals | 1997_98_actuals | 1996_97_actuals | 1995_96_actuals | 1994_95_actuals | 
| ============================================= | ====================================== | ============================== | ==================== | ==================================== | ======= | =============== | ================= | ================= | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | Capital Projects Funds - Other | Capital Projects     | Capital Projects Fund                | 30000   | Capital Project | 4100              | 3501              | 4771            | 10264           | 3646            | 1020            | 1002            | 1750            | 1750            | 1769            | 1218            | 1650            | 948             | 1029            | 573             | 1545            | 1747            | 2013            | 2704            | 2494            | 4056            | 1437            | 3108            | 2912            | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | Capital Projects Funds - Other | Capital Projects     | Capital Projects Fund                | 300CC   | CPF - Auth Bond | 16115             | 5000              | 5               | 737             | 2035            | 15738           | 16954           | 3455            | 1835            | 670             | 483             | 4               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | Capital Projects Funds - Other | Capital Projects     | Clean Water/Clean Air Implementation | 305BM   | CPF-1996CWA(Bon | 0                 | 0                 | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 111             | 182             | 0               | 0               | 0               | 0               | 0               | 0               | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | Capital Projects Funds - Other | Grants to Local Gov. | Clean Water/Clean Air Implementation | 305BM   | CPF-1996CWA(Bon | 0                 | 0                 | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 211             | 53              | 0               | 0               | 0               | 0               | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | Capital Projects Funds - Other | Capital Projects     | Miscellaeous Capital Projects Fund   | 32200   | Misc. Capital P | 500               | 500               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 344             | -1              | 203             | 2590            | 21              | 753             | 385             | 0               | 0               | 0               | 0               | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | General Fund                   | Grants to Local Gov. | Community Projects Fund              | 10251   | Comm Proj AA    | 0                 | 0                 | 5               | 25              | 0               | 40              | 102             | 225             | 431             | 1558            | 1043            | 596             | 721             | 662             | 467             | 843             | 1202            | 1550            | 524             | 0               | 0               | 0               | 0               | 0               | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | General Fund                   | Non-Personal Service | Community Projects Fund              | 10251   | Comm Proj AA    | 0                 | 0                 | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 5               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | General Fund                   | Personal Service     | Community Projects Fund              | 10251   | Comm Proj AA    | 0                 | 0                 | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 95              | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | General Fund                   | Grants to Local Gov. | Community Projects Fund              | 10252   | Comm Proj BB    | 0                 | 0                 | 0               | 0               | 12              | 100             | 35              | 148             | 8               | 5               | 19              | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 0               | 
| Economic Development and Government Oversight | Agriculture and Markets, Department of | General Fund                   | Grants to Local Gov. | Community Projects Fund              | 10253   | Comm Proj CC    | 0                 | 94                | 53              | 17              | 253             | 0               | 0               | 186             | 659             | 145             | 103             | 130             | 235             | 351             | 137             | 167             | 2               | 24              | 158             | 0               | 0               | 0               | 0               | 0               | 
```