# Energy Usage From DOE Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-usage-from-doe-buildings-4803c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mq6n-s45c) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mq6n-s45c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mq6n-s45c/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mq6n-s45c |
| Name | Energy Usage From DOE Buildings |
| Attribution | Department of Education (DOE) |
| Category | Environment |
| Tags | energy usage from doe buildings, electricity, steam, data, building, btu, watts, heat, oil, doe, lifelong learning |
| Created | 2012-09-06T18:18:22Z |
| Publication Date | 2013-06-26T17:13:51Z |

## Description

Energy data from a select portfolio of City-owned buildings (DOE)

## Columns

```ls
| Included | Schema Type    | Field Name       | Name               | Data Type | Render Type |
| ======== | ============== | ================ | ================== | ========= | =========== |
| No       | time           | :updated_at      | updated_at         | meta_data | meta_data   |
| Yes      | series tag     | measurement      | Measurement        | text      | text        |
| No       |                | _1               | -                  | money     | money       |
| No       |                | _2               | _                  | money     | money       |
| Yes      | numeric metric | fy_2009_7_1_2008 | (FY 2009) 7/1/2008 | money     | money       |
| Yes      | numeric metric | aug_08           | Aug-08             | money     | money       |
| Yes      | numeric metric | sep_08           | Sep-08             | money     | money       |
| Yes      | numeric metric | oct_08           | Oct-08             | money     | money       |
| Yes      | numeric metric | nov_08           | Nov-08             | money     | money       |
| Yes      | numeric metric | dec_08           | Dec-08             | money     | money       |
| Yes      | numeric metric | jan_09           | Jan-09             | money     | money       |
| Yes      | numeric metric | feb_09           | Feb-09             | money     | money       |
| Yes      | numeric metric | mar_09           | Mar-09             | money     | money       |
| Yes      | numeric metric | apr_09           | Apr-09             | money     | money       |
| Yes      | numeric metric | may_09           | May-09             | money     | money       |
| Yes      | numeric metric | jun_09           | Jun-09             | money     | money       |
| Yes      | numeric metric | fy_2010_7_1_2009 | (FY 2010)7/1/2009  | money     | money       |
| Yes      | numeric metric | aug_09           | Aug-09             | money     | money       |
| Yes      | numeric metric | sep_09           | Sep-09             | money     | money       |
| Yes      | numeric metric | oct_09           | Oct-09             | money     | money       |
| Yes      | numeric metric | nov_09           | Nov-09             | money     | money       |
| Yes      | numeric metric | dec_09           | Dec-09             | money     | money       |
| Yes      | numeric metric | jan_10           | Jan-10             | money     | money       |
| Yes      | numeric metric | feb_10           | Feb-10             | money     | money       |
| Yes      | numeric metric | mar_10           | Mar-10             | money     | money       |
| Yes      | numeric metric | apr_10           | Apr-10             | money     | money       |
| Yes      | numeric metric | may_10           | May-10             | money     | money       |
| Yes      | numeric metric | jun_10           | Jun-10             | money     | money       |
| Yes      | numeric metric | fy_2011_7_1_2010 | (FY 2011)7/1/2010  | money     | money       |
| Yes      | numeric metric | aug_10           | Aug-10             | money     | money       |
| Yes      | numeric metric | sep_10           | Sep-10             | money     | money       |
| Yes      | numeric metric | oct_10           | Oct-10             | money     | money       |
| Yes      | numeric metric | nov_10           | Nov-10             | money     | money       |
| Yes      | numeric metric | dec_10           | Dec-10             | money     | money       |
| Yes      | numeric metric | jan_11           | Jan-11             | money     | money       |
| Yes      | numeric metric | feb_11           | Feb-11             | money     | money       |
| Yes      | numeric metric | mar_11           | Mar-11             | money     | money       |
| Yes      | numeric metric | apr_11           | Apr-11             | money     | money       |
| Yes      | numeric metric | may_11           | May-11             | money     | money       |
| Yes      | numeric metric | jun_11           | Jun-11             | money     | money       |
| Yes      | numeric metric | fy_2012_7_1_2011 | (FY 2012)7/1/2011  | money     | money       |
| Yes      | numeric metric | aug_11           | Aug-11             | money     | money       |
| Yes      | numeric metric | sep_11           | Sep-11             | money     | money       |
| Yes      | numeric metric | oct_11           | Oct-11             | money     | money       |
| Yes      | numeric metric | nov_11           | Nov-11             | money     | money       |
| Yes      | numeric metric | dec_11           | Dec-11             | money     | money       |
| Yes      | numeric metric | jan_12           | Jan-12             | money     | money       |
| Yes      | numeric metric | feb_12           | Feb-12             | money     | money       |
| Yes      | numeric metric | mar_12           | Mar-12             | money     | money       |
| Yes      | numeric metric | apr_12           | Apr-12             | money     | money       |
| Yes      | series tag     | may_12           | May-12             | text      | text        |
| Yes      | series tag     | jun_12           | Jun-12             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _1,_2
```

## Data Commands

```ls
series e:mq6n-s45c d:2012-09-06T11:18:26.000Z t:measurement="Electricity Demand (KW)" m:mar_10=158 m:may_11=156 m:mar_11=154 m:may_10=136 m:jan_09=166 m:mar_12=146 m:fy_2009_7_1_2008=148 m:feb_09=162 m:apr_09=146 m:aug_09=152 m:feb_11=164 m:feb_12=146 m:apr_10=154 m:aug_08=158 m:apr_11=170 m:sep_10=166 m:feb_10=172 m:sep_11=164 m:apr_12=156 m:nov_08=168 m:may_09=146 m:nov_09=184 m:jun_11=82 m:nov_10=178 m:jun_10=64 m:dec_09=190 m:oct_08=180 m:nov_11=166 m:dec_08=166 m:mar_09=142 m:aug_11=168 m:fy_2012_7_1_2011=58 m:oct_09=178 m:aug_10=156 m:fy_2010_7_1_2009=148 m:jan_10=188 m:jun_09=90 m:oct_11=162 m:jan_11=172 m:fy_2011_7_1_2010=140 m:sep_09=170 m:jan_12=156 m:oct_10=178 m:dec_11=160 m:dec_10=178 m:sep_08=166

series e:mq6n-s45c d:2012-09-06T11:18:26.000Z t:measurement="Electricity Usage (KWH)" m:mar_10=50800 m:may_11=31400 m:mar_11=49600 m:may_10=33000 m:jan_09=55200 m:mar_12=47400 m:fy_2009_7_1_2008=46200 m:feb_09=44200 m:apr_09=47400 m:aug_09=52400 m:feb_11=48200 m:feb_12=43800 m:apr_10=52200 m:aug_08=45200 m:apr_11=52000 m:sep_10=53800 m:feb_10=48200 m:sep_11=58800 m:apr_12=53600 m:nov_08=56600 m:may_09=34200 m:nov_09=60800 m:jun_11=20600 m:nov_10=55600 m:jun_10=28600 m:dec_09=63200 m:oct_08=58400 m:nov_11=57600 m:dec_08=52200 m:mar_09=48600 m:aug_11=91600 m:fy_2012_7_1_2011=9800 m:oct_09=63200 m:aug_10=52800 m:fy_2010_7_1_2009=44800 m:jan_10=58000 m:jun_09=30600 m:oct_11=53400 m:jan_11=58000 m:fy_2011_7_1_2010=42600 m:sep_09=54200 m:jan_12=50400 m:oct_10=65200 m:dec_11=58600 m:dec_10=59600 m:sep_08=51800

series e:mq6n-s45c d:2012-09-06T11:18:26.000Z t:measurement="Gas (Therms)" m:mar_10=1298 m:may_11=124 m:mar_11=831 m:may_10=106 m:jan_09=10322 m:mar_12=1410 m:fy_2009_7_1_2008=305 m:feb_09=4660 m:apr_09=348 m:aug_09=2835 m:feb_11=5373 m:feb_12=3781 m:apr_10=275 m:aug_08=2298 m:apr_11=339 m:sep_10=6448 m:feb_10=2966 m:sep_11=6037 m:apr_12=302 m:nov_08=16197 m:may_09=150 m:nov_09=15662 m:jun_11=115 m:nov_10=16787 m:jun_10=93 m:dec_09=16322 m:oct_08=13710 m:nov_11=13972 m:dec_08=12846 m:mar_09=1138 m:aug_11=778 m:fy_2012_7_1_2011=273 m:oct_09=14903 m:aug_10=1645 m:fy_2010_7_1_2009=243 m:jan_10=8197 m:jun_09=112 m:oct_11=8103 m:jan_11=10629 m:fy_2011_7_1_2010=193 m:sep_09=5873 m:jan_12=6866 m:oct_10=16825 m:dec_11=12298 m:dec_10=14045 m:sep_08=7666
```

## Meta Commands

```ls
metric m:fy_2009_7_1_2008 p:double l:"(FY 2009) 7/1/2008" t:dataTypeName=money

metric m:aug_08 p:double l:Aug-08 t:dataTypeName=money

metric m:sep_08 p:double l:Sep-08 t:dataTypeName=money

metric m:oct_08 p:double l:Oct-08 t:dataTypeName=money

metric m:nov_08 p:double l:Nov-08 t:dataTypeName=money

metric m:dec_08 p:double l:Dec-08 t:dataTypeName=money

metric m:jan_09 p:double l:Jan-09 t:dataTypeName=money

metric m:feb_09 p:double l:Feb-09 t:dataTypeName=money

metric m:mar_09 p:double l:Mar-09 t:dataTypeName=money

metric m:apr_09 p:double l:Apr-09 t:dataTypeName=money

metric m:may_09 p:double l:May-09 t:dataTypeName=money

metric m:jun_09 p:double l:Jun-09 t:dataTypeName=money

metric m:fy_2010_7_1_2009 p:double l:"(FY 2010)7/1/2009" t:dataTypeName=money

metric m:aug_09 p:double l:Aug-09 t:dataTypeName=money

metric m:sep_09 p:double l:Sep-09 t:dataTypeName=money

metric m:oct_09 p:double l:Oct-09 t:dataTypeName=money

metric m:nov_09 p:double l:Nov-09 t:dataTypeName=money

metric m:dec_09 p:double l:Dec-09 t:dataTypeName=money

metric m:jan_10 p:double l:Jan-10 t:dataTypeName=money

metric m:feb_10 p:double l:Feb-10 t:dataTypeName=money

metric m:mar_10 p:double l:Mar-10 t:dataTypeName=money

metric m:apr_10 p:double l:Apr-10 t:dataTypeName=money

metric m:may_10 p:double l:May-10 t:dataTypeName=money

metric m:jun_10 p:double l:Jun-10 t:dataTypeName=money

metric m:fy_2011_7_1_2010 p:double l:"(FY 2011)7/1/2010" t:dataTypeName=money

metric m:aug_10 p:double l:Aug-10 t:dataTypeName=money

metric m:sep_10 p:double l:Sep-10 t:dataTypeName=money

metric m:oct_10 p:double l:Oct-10 t:dataTypeName=money

metric m:nov_10 p:double l:Nov-10 t:dataTypeName=money

metric m:dec_10 p:double l:Dec-10 t:dataTypeName=money

metric m:jan_11 p:double l:Jan-11 t:dataTypeName=money

metric m:feb_11 p:double l:Feb-11 t:dataTypeName=money

metric m:mar_11 p:double l:Mar-11 t:dataTypeName=money

metric m:apr_11 p:double l:Apr-11 t:dataTypeName=money

metric m:may_11 p:double l:May-11 t:dataTypeName=money

metric m:jun_11 p:double l:Jun-11 t:dataTypeName=money

metric m:fy_2012_7_1_2011 p:double l:"(FY 2012)7/1/2011" t:dataTypeName=money

metric m:aug_11 p:double l:Aug-11 t:dataTypeName=money

metric m:sep_11 p:double l:Sep-11 t:dataTypeName=money

metric m:oct_11 p:double l:Oct-11 t:dataTypeName=money

metric m:nov_11 p:double l:Nov-11 t:dataTypeName=money

metric m:dec_11 p:double l:Dec-11 t:dataTypeName=money

metric m:jan_12 p:double l:Jan-12 t:dataTypeName=money

metric m:feb_12 p:double l:Feb-12 t:dataTypeName=money

metric m:mar_12 p:double l:Mar-12 t:dataTypeName=money

metric m:apr_12 p:double l:Apr-12 t:dataTypeName=money

entity e:mq6n-s45c l:"Energy Usage From DOE Buildings" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/mq6n-s45c

property e:mq6n-s45c t:meta.view v:id=mq6n-s45c v:category=Environment v:averageRating=0 v:name="Energy Usage From DOE Buildings" v:attribution="Department of Education (DOE)"

property e:mq6n-s45c t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mq6n-s45c t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | measurement             | _1        | _2        | fy_2009_7_1_2008 | aug_08    | sep_08    | oct_08    | nov_08    | dec_08    | jan_09    | feb_09    | mar_09    | apr_09    | may_09    | jun_09    | fy_2010_7_1_2009 | aug_09    | sep_09    | oct_09    | nov_09    | dec_09    | jan_10    | feb_10    | mar_10    | apr_10    | may_10    | jun_10    | fy_2011_7_1_2010 | aug_10    | sep_10    | oct_10    | nov_10    | dec_10    | jan_11    | feb_11    | mar_11    | apr_11    | may_11    | jun_11    | fy_2012_7_1_2011 | aug_11    | sep_11    | oct_11    | nov_11    | dec_11    | jan_12    | feb_12    | mar_12    | apr_12    | may_12 | jun_12 | 
| =========== | ======================= | ========= | ========= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ================ | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ====== | ====== | 
| 1346930306  | Electricity Demand (KW) | 144       | 68        | 148              | 158       | 166       | 180       | 168       | 166       | 166       | 162       | 142       | 146       | 146       | 90        | 148              | 152       | 170       | 178       | 184       | 190       | 188       | 172       | 158       | 154       | 136       | 64        | 140              | 156       | 166       | 178       | 178       | 178       | 172       | 164       | 154       | 170       | 156       | 82        | 58               | 168       | 164       | 162       | 166       | 160       | 156       | 146       | 146       | 156       |        |        | 
| 1346930306  | Electricity Usage (KWH) | 30400.00  | 31000.00  | 46200.00         | 45200.00  | 51800.00  | 58400.00  | 56600.00  | 52200.00  | 55200.00  | 44200.00  | 48600.00  | 47400.00  | 34200.00  | 30600.00  | 44800.00         | 52400.00  | 54200.00  | 63200.00  | 60800.00  | 63200.00  | 58000.00  | 48200.00  | 50800.00  | 52200.00  | 33000.00  | 28600.00  | 42600.00         | 52800.00  | 53800.00  | 65200.00  | 55600.00  | 59600.00  | 58000.00  | 48200.00  | 49600.00  | 52000.00  | 31400.00  | 20600.00  | 9800.00          | 91600.00  | 58800.00  | 53400.00  | 57600.00  | 58600.00  | 50400.00  | 43800.00  | 47400.00  | 53600.00  |        |        | 
| 1346930306  | Gas (Therms)            | 109       | 112       | 305              | 2298.00   | 7666.00   | 13710.00  | 16197.00  | 12846.00  | 10322.00  | 4660.00   | 1138.00   | 348       | 150       | 112       | 243              | 2835.00   | 5873.00   | 14903.00  | 15662.00  | 16322.00  | 8197.00   | 2966.00   | 1298.00   | 275       | 106       | 93        | 193              | 1645.00   | 6448.00   | 16825.00  | 16787.00  | 14045.00  | 10629.00  | 5373.00   | 831       | 339       | 124       | 115       | 273              | 778       | 6037.00   | 8103.00   | 13972.00  | 12298.00  | 6866.00   | 3781.00   | 1410.00   | 302       |        |        | 
| 1346930306  | Total Usage (mmBTUs)    | 114.65    | 117       | 188.18           | 384.07    | 943.39    | 1570.32   | 1812.87   | 1462.76   | 1220.60   | 616.85    | 279.67    | 196.57    | 131.72    | 115.64    | 177.2            | 462.34    | 772.28    | 1706.00   | 1773.71   | 1847.90   | 1017.65   | 461.11    | 303.18    | 205.66    | 123.23    | 106.91    | 164.69           | 344.7     | 828.42    | 1905.03   | 1868.46   | 1607.91   | 1260.85   | 701.81    | 252.38    | 211.37    | 119.57    | 81.81     | 60.75            | 390.43    | 804.38    | 992.55    | 1593.79   | 1429.80   | 858.61    | 527.59    | 302.77    | 213.14    |        |        | 
| 1346930306  | Electricity Demand (KW) | 123.2     | 150.4     | 150.4            | 124.8     | 136       | 144       | 144       | 144       | 142.4     | 142.4     | 145.6     | 140.8     | 128       | 134.4     | 148.8            | 128       | 128       | 128       | 126.4     | 126.4     | 124.8     | 121.6     | 140.8     | 160       | 153.6     | 139.2     | 156.8            | 148.8     | 134.4     | 134.4     | 134.4     | 134.4     | 129.6     | 131.2     | 124.8     | 182.4     | 171.2     | 145.6     | 174.4            | 169.6     | 139.2     | 132.8     | 132.8     | 132.8     | 128       | 158.4     | 134.4     | 187.2     |        |        | 
| 1346930306  | Electricity Usage (KWH) | 53920.00  | 58560.00  | 56640.00         | 48640.00  | 54560.00  | 61440.00  | 61600.00  | 60640.00  | 60800.00  | 51200.00  | 48160.00  | 45280.00  | 52000.00  | 57280.00  | 52160.00         | 52320.00  | 47040.00  | 57440.00  | 48800.00  | 52000.00  | 44160.00  | 38720.00  | 39200.00  | 48160.00  | 53280.00  | 50240.00  | 45440.00         | 46080.00  | 42080.00  | 48800.00  | 41600.00  | 44640.00  | 40800.00  | 37600.00  | 40160.00  | 53920.00  | 48320.00  | 54560.00  | 54560.00         | 44640.00  | 46400.00  | 42080.00  | 40640.00  | 43680.00  | 42560.00  | 38240.00  | 42880.00  | 52640.00  |        |        | 
| 1346930306  | Gas (Therms)            | 0         | 60        | 13               | 1041.00   | 4676.00   | 8096.00   | 5772.00   | 2498.00   | 288       | 196       | 270       | 237       | 275       | 114       | 97               | 1385.00   | 4321.00   | 3213.00   | 5039.00   | 4934.00   | 1640.00   | 1264.00   | 549       | 141       | 97        | 81        | 85               | 996       | 3815.00   | 5378.00   | 7478.00   | 9848.00   | 7440.00   | 4097.00   | 1691.00   | 174       | 148       | 58        | 98               | 456       | 2975.00   | 4647.00   | 6640.00   | 7107.00   | 4391.00   | 3673.00   | 1584.00   | 106       |        |        | 
| 1346930306  | Total Usage (mmBTUs)    | 184.03    | 205.86    | 194.61           | 270.11    | 653.81    | 1019.29   | 787.44    | 456.76    | 236.31    | 194.34    | 191.37    | 178.24    | 204.97    | 206.89    | 187.72           | 317.07    | 592.65    | 517.34    | 670.45    | 670.87    | 314.72    | 258.55    | 188.69    | 178.47    | 191.54    | 179.57    | 163.59           | 256.87    | 525.12    | 704.35    | 889.78    | 1137.15   | 883.25    | 538.03    | 306.16    | 201.43    | 179.71    | 192.01    | 196.01           | 197.95    | 455.86    | 608.32    | 802.7     | 859.78    | 584.36    | 497.81    | 304.75    | 190.26    |        |        | 
| 1346930306  | Electricity Demand (KW) | 576       | 552       | 700              | 708       | 584       | 676       | 676       | 636       | 660       | 524       | 600       | 580       | 500       | 528       | 636              | 656       | 648       | 664       | 648       | 712       | 712       | 576       | 616       | 700       | 668       | 520       | 652              | 604       | 628       | 708       | 708       | 708       | 664       | 632       | 696       | 808       | 608       | 532       | 628              | 708       | 616       | 620       | 704       | 632       | 608       | 620       | 656       | 664       |        |        | 
| 1346930306  | Electricity Usage (KWH) | 242400.00 | 277600.00 | 236000.00        | 204000.00 | 234000.00 | 298000.00 | 298800.00 | 267200.00 | 257600.00 | 189600.00 | 210000.00 | 209600.00 | 224400.00 | 210800.00 | 217200.00        | 242400.00 | 236000.00 | 302000.00 | 294000.00 | 297200.00 | 262000.00 | 185200.00 | 188000.00 | 223200.00 | 232400.00 | 191600.00 | 175200.00        | 192800.00 | 207600.00 | 318400.00 | 271600.00 | 292400.00 | 239200.00 | 176800.00 | 172800.00 | 244400.00 | 222000.00 | 192400.00 | 204400.00        | 177200.00 | 216400.00 | 217200.00 | 257200.00 | 222400.00 | 197200.00 | 158800.00 | 167600.00 | 205600.00 |        |        | 
```