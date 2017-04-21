# Energy Usage From DCAS Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-usage-from-dcas-buildings-34053) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pwva-zn2w) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pwva-zn2w/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pwva-zn2w/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pwva-zn2w |
| Name | Energy Usage From DCAS Buildings |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | Environment |
| Tags | energy usage from dcas buildings, electricity, steam, data, building, btu, watts, heat, oil, dcas |
| Created | 2012-09-06T17:48:28Z |
| Publication Date | 2013-06-26T17:14:57Z |

## Description

Energy data from a select portfolio of City-owned buildings (DCAS)

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       | time           | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag     | energy_type     | Energy Type     | text      | text        |
| No       |                | _1              | -               | number    | number      |
| No       |                | _2              | _               | number    | number      |
| Yes      | numeric metric | fy_2009jul_2008 | FY 2009Jul-2008 | number    | number      |
| Yes      | numeric metric | aug_2008        | Aug-2008        | number    | number      |
| Yes      | numeric metric | sep_2008        | Sep-2008        | number    | number      |
| Yes      | numeric metric | oct_2008        | Oct-2008        | number    | number      |
| Yes      | numeric metric | nov_2008        | Nov-2008        | number    | number      |
| Yes      | numeric metric | dec_2008        | Dec-2008        | number    | number      |
| Yes      | numeric metric | jan_2009        | Jan-2009        | number    | number      |
| Yes      | numeric metric | feb_2009        | Feb-2009        | number    | number      |
| Yes      | numeric metric | mar_2009        | Mar-2009        | number    | number      |
| Yes      | numeric metric | apr_2009        | Apr-2009        | number    | number      |
| Yes      | numeric metric | may_2009        | May-2009        | number    | number      |
| Yes      | numeric metric | jun_2009        | Jun-2009        | number    | number      |
| Yes      | numeric metric | fy_2010jul_2009 | FY 2010Jul-2009 | number    | number      |
| Yes      | numeric metric | aug_2009        | Aug-2009        | number    | number      |
| Yes      | numeric metric | sep_2009        | Sep-2009        | number    | number      |
| Yes      | numeric metric | oct_2009        | Oct-2009        | number    | number      |
| Yes      | numeric metric | nov_2009        | Nov-2009        | number    | number      |
| Yes      | numeric metric | dec_2009        | Dec-2009        | number    | number      |
| Yes      | numeric metric | jan_2010        | Jan-2010        | number    | number      |
| Yes      | numeric metric | feb_2010        | Feb-2010        | number    | number      |
| Yes      | numeric metric | mar_2010        | Mar-2010        | number    | number      |
| Yes      | numeric metric | apr_2010        | Apr-2010        | number    | number      |
| Yes      | numeric metric | may_2010        | May-2010        | number    | number      |
| Yes      | numeric metric | jun_2010        | Jun-2010        | number    | number      |
| Yes      | numeric metric | fy_2011jul_2010 | FY 2011Jul-2010 | number    | number      |
| Yes      | numeric metric | aug_2010        | Aug-2010        | number    | number      |
| Yes      | numeric metric | sep_2010        | Sep-2010        | number    | number      |
| Yes      | numeric metric | oct_2010        | Oct-2010        | number    | number      |
| Yes      | numeric metric | nov_2010        | Nov-2010        | number    | number      |
| Yes      | numeric metric | dec_2010        | Dec-2010        | number    | number      |
| Yes      | numeric metric | jan_2011        | Jan-2011        | number    | number      |
| Yes      | numeric metric | feb_2011        | Feb-2011        | number    | number      |
| Yes      | numeric metric | mar_2011        | Mar-2011        | number    | number      |
| Yes      | numeric metric | apr_2011        | Apr-2011        | number    | number      |
| Yes      | numeric metric | may_2011        | May-2011        | number    | number      |
| Yes      | numeric metric | jun_2011        | Jun-2011        | number    | number      |
| Yes      | numeric metric | fy_2012jul_2011 | FY 2012Jul-2011 | number    | number      |
| Yes      | numeric metric | aug_2011        | Aug-2011        | number    | number      |
| Yes      | numeric metric | sep_2011        | Sep-2011        | number    | number      |
| Yes      | numeric metric | oct_2011        | Oct-2011        | number    | number      |
| Yes      | numeric metric | nov_2011        | Nov-2011        | number    | number      |
| Yes      | numeric metric | dec_2011        | Dec-2011        | number    | number      |
| Yes      | numeric metric | jan_2012        | Jan-2012        | number    | number      |
| Yes      | numeric metric | feb_2012        | Feb-2012        | number    | number      |
| Yes      | numeric metric | mar_2012        | Mar-2012        | number    | number      |
| Yes      | numeric metric | apr_2012        | Apr-2012        | number    | number      |
| Yes      | series tag     | may_2012        | May-2012        | text      | text        |
| Yes      | series tag     | jun_2012        | Jun-2012        | text      | text        |
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
series e:pwva-zn2w d:2012-09-06T10:48:32.000Z t:energy_type="Electricity Demand (KW)" m:oct_2008=895.5 m:jun_2009=1704 m:fy_2010jul_2009=1644.5 m:oct_2009=888 m:aug_2009=1254 m:aug_2008=1213 m:apr_2009=1345.5 m:nov_2008=861.5 m:nov_2009=820.5 m:apr_2010=1693 m:apr_2012=1567.5 m:apr_2011=1639.5 m:fy_2012jul_2011=1455 m:oct_2010=883.5 m:jun_2011=1667 m:oct_2011=846 m:jun_2010=1650 m:mar_2012=1232 m:mar_2010=1386 m:mar_2011=1147 m:sep_2010=1253.5 m:sep_2011=882 m:feb_2009=1253.5 m:nov_2010=820.5 m:jan_2011=806 m:may_2009=1670.5 m:jan_2012=783 m:dec_2009=836.5 m:nov_2011=831 m:jan_2010=831.5 m:dec_2008=889.5 m:aug_2011=1322 m:may_2011=1683.5 m:aug_2010=1391.5 m:dec_2011=824 m:dec_2010=892.5 m:sep_2009=933 m:mar_2009=1307 m:fy_2011jul_2010=1584 m:jan_2009=867.5 m:sep_2008=894.5 m:feb_2011=1061.5 m:feb_2012=1121 m:fy_2009jul_2008=1534 m:feb_2010=1174.5 m:may_2010=1748.5

series e:pwva-zn2w d:2012-09-06T10:48:32.000Z t:energy_type="Electricity Usage (KWH)" m:oct_2008=419400 m:jun_2009=601800 m:fy_2010jul_2009=507600 m:oct_2009=420600 m:aug_2009=435000 m:aug_2008=397800 m:apr_2009=483000 m:nov_2008=393000 m:nov_2009=345000 m:apr_2010=543000 m:apr_2012=528600 m:apr_2011=544800 m:fy_2012jul_2011=516600 m:oct_2010=420600 m:jun_2011=546000 m:oct_2011=355800 m:jun_2010=594600 m:mar_2012=379800 m:mar_2010=427200 m:mar_2011=403800 m:sep_2010=387600 m:sep_2011=372600 m:feb_2009=387600 m:nov_2010=420600 m:jan_2011=341400 m:may_2009=601200 m:jan_2012=319200 m:dec_2009=369000 m:nov_2011=354000 m:jan_2010=340200 m:dec_2008=381000 m:aug_2011=430200 m:may_2011=587400 m:aug_2010=462000 m:dec_2011=370200 m:dec_2010=360000 m:sep_2009=378000 m:mar_2009=435600 m:fy_2011jul_2010=520800 m:jan_2009=393600 m:sep_2008=376200 m:feb_2011=332400 m:feb_2012=340800 m:fy_2009jul_2008=505800 m:feb_2010=378600 m:may_2010=646200

series e:pwva-zn2w d:2012-09-06T10:48:32.000Z t:energy_type="Steam (mlbs)" m:oct_2008=6011 m:jun_2009=67 m:fy_2010jul_2009=78 m:oct_2009=4301 m:aug_2009=682 m:aug_2008=612 m:apr_2009=74 m:nov_2008=6988 m:nov_2009=4557 m:apr_2010=77 m:apr_2012=119 m:apr_2011=104 m:fy_2012jul_2011=116 m:oct_2010=4593 m:jun_2011=113 m:oct_2011=2801 m:jun_2010=63 m:mar_2012=171 m:mar_2010=284 m:mar_2011=242 m:sep_2010=1816 m:sep_2011=1603 m:feb_2009=1479 m:nov_2010=5146 m:jan_2011=3047 m:may_2009=74 m:jan_2012=1550 m:dec_2009=4469 m:nov_2011=3981 m:jan_2010=2096 m:dec_2008=5472 m:aug_2011=282 m:may_2011=93 m:aug_2010=385 m:dec_2011=2670 m:dec_2010=3560 m:sep_2009=1019 m:mar_2009=98 m:fy_2011jul_2010=69 m:jan_2009=4708 m:sep_2008=2760 m:feb_2011=1069 m:feb_2012=1062 m:fy_2009jul_2008=72 m:feb_2010=564 m:may_2010=56
```

## Meta Commands

```ls
metric m:fy_2009jul_2008 p:float l:"FY 2009Jul-2008" t:dataTypeName=number

metric m:aug_2008 p:float l:Aug-2008 t:dataTypeName=number

metric m:sep_2008 p:float l:Sep-2008 t:dataTypeName=number

metric m:oct_2008 p:float l:Oct-2008 t:dataTypeName=number

metric m:nov_2008 p:float l:Nov-2008 t:dataTypeName=number

metric m:dec_2008 p:float l:Dec-2008 t:dataTypeName=number

metric m:jan_2009 p:float l:Jan-2009 t:dataTypeName=number

metric m:feb_2009 p:float l:Feb-2009 t:dataTypeName=number

metric m:mar_2009 p:float l:Mar-2009 t:dataTypeName=number

metric m:apr_2009 p:float l:Apr-2009 t:dataTypeName=number

metric m:may_2009 p:float l:May-2009 t:dataTypeName=number

metric m:jun_2009 p:float l:Jun-2009 t:dataTypeName=number

metric m:fy_2010jul_2009 p:float l:"FY 2010Jul-2009" t:dataTypeName=number

metric m:aug_2009 p:float l:Aug-2009 t:dataTypeName=number

metric m:sep_2009 p:float l:Sep-2009 t:dataTypeName=number

metric m:oct_2009 p:float l:Oct-2009 t:dataTypeName=number

metric m:nov_2009 p:float l:Nov-2009 t:dataTypeName=number

metric m:dec_2009 p:float l:Dec-2009 t:dataTypeName=number

metric m:jan_2010 p:float l:Jan-2010 t:dataTypeName=number

metric m:feb_2010 p:float l:Feb-2010 t:dataTypeName=number

metric m:mar_2010 p:float l:Mar-2010 t:dataTypeName=number

metric m:apr_2010 p:float l:Apr-2010 t:dataTypeName=number

metric m:may_2010 p:float l:May-2010 t:dataTypeName=number

metric m:jun_2010 p:float l:Jun-2010 t:dataTypeName=number

metric m:fy_2011jul_2010 p:float l:"FY 2011Jul-2010" t:dataTypeName=number

metric m:aug_2010 p:float l:Aug-2010 t:dataTypeName=number

metric m:sep_2010 p:float l:Sep-2010 t:dataTypeName=number

metric m:oct_2010 p:float l:Oct-2010 t:dataTypeName=number

metric m:nov_2010 p:float l:Nov-2010 t:dataTypeName=number

metric m:dec_2010 p:float l:Dec-2010 t:dataTypeName=number

metric m:jan_2011 p:float l:Jan-2011 t:dataTypeName=number

metric m:feb_2011 p:float l:Feb-2011 t:dataTypeName=number

metric m:mar_2011 p:float l:Mar-2011 t:dataTypeName=number

metric m:apr_2011 p:float l:Apr-2011 t:dataTypeName=number

metric m:may_2011 p:float l:May-2011 t:dataTypeName=number

metric m:jun_2011 p:float l:Jun-2011 t:dataTypeName=number

metric m:fy_2012jul_2011 p:float l:"FY 2012Jul-2011" t:dataTypeName=number

metric m:aug_2011 p:float l:Aug-2011 t:dataTypeName=number

metric m:sep_2011 p:float l:Sep-2011 t:dataTypeName=number

metric m:oct_2011 p:float l:Oct-2011 t:dataTypeName=number

metric m:nov_2011 p:float l:Nov-2011 t:dataTypeName=number

metric m:dec_2011 p:float l:Dec-2011 t:dataTypeName=number

metric m:jan_2012 p:float l:Jan-2012 t:dataTypeName=number

metric m:feb_2012 p:float l:Feb-2012 t:dataTypeName=number

metric m:mar_2012 p:float l:Mar-2012 t:dataTypeName=number

metric m:apr_2012 p:float l:Apr-2012 t:dataTypeName=number

entity e:pwva-zn2w l:"Energy Usage From DCAS Buildings" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/pwva-zn2w

property e:pwva-zn2w t:meta.view v:id=pwva-zn2w v:category=Environment v:averageRating=0 v:name="Energy Usage From DCAS Buildings" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:pwva-zn2w t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pwva-zn2w t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | energy_type             | _1        | _2        | fy_2009jul_2008 | aug_2008  | sep_2008  | oct_2008  | nov_2008  | dec_2008  | jan_2009  | feb_2009  | mar_2009  | apr_2009  | may_2009  | jun_2009  | fy_2010jul_2009 | aug_2009  | sep_2009  | oct_2009  | nov_2009  | dec_2009  | jan_2010  | feb_2010  | mar_2010  | apr_2010  | may_2010  | jun_2010  | fy_2011jul_2010 | aug_2010  | sep_2010  | oct_2010  | nov_2010  | dec_2010  | jan_2011  | feb_2011  | mar_2011  | apr_2011  | may_2011  | jun_2011  | fy_2012jul_2011 | aug_2011  | sep_2011  | oct_2011  | nov_2011  | dec_2011  | jan_2012  | feb_2012  | mar_2012  | apr_2012  | may_2012 | jun_2012 | 
| =========== | ======================= | ========= | ========= | =============== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =============== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =============== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | =============== | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ========= | ======== | ======== | 
| 1346928512  | Electricity Demand (KW) | 1741.50   | 1621.50   | 1534.00         | 1213.00   | 894.50    | 895.50    | 861.50    | 889.50    | 867.50    | 1253.50   | 1307.00   | 1345.50   | 1670.50   | 1704.00   | 1644.50         | 1254.00   | 933.00    | 888.00    | 820.50    | 836.50    | 831.50    | 1174.50   | 1386.00   | 1693.00   | 1748.50   | 1650.00   | 1584.00         | 1391.50   | 1253.50   | 883.50    | 820.50    | 892.50    | 806.00    | 1061.50   | 1147.00   | 1639.50   | 1683.50   | 1667.00   | 1455.00         | 1322.00   | 882.00    | 846.00    | 831.00    | 824.00    | 783.00    | 1121.00   | 1232.00   | 1567.50   |          |          | 
| 1346928512  | Electricity Usage (KWH) | 622200.00 | 581400.00 | 505800.00       | 397800.00 | 376200.00 | 419400.00 | 393000.00 | 381000.00 | 393600.00 | 387600.00 | 435600.00 | 483000.00 | 601200.00 | 601800.00 | 507600.00       | 435000.00 | 378000.00 | 420600.00 | 345000.00 | 369000.00 | 340200.00 | 378600.00 | 427200.00 | 543000.00 | 646200.00 | 594600.00 | 520800.00       | 462000.00 | 387600.00 | 420600.00 | 420600.00 | 360000.00 | 341400.00 | 332400.00 | 403800.00 | 544800.00 | 587400.00 | 546000.00 | 516600.00       | 430200.00 | 372600.00 | 355800.00 | 354000.00 | 370200.00 | 319200.00 | 340800.00 | 379800.00 | 528600.00 |          |          | 
| 1346928512  | Steam (mlbs)            | 73.00     | 64.00     | 72.00           | 612.00    | 2760.00   | 6011.00   | 6988.00   | 5472.00   | 4708.00   | 1479.00   | 98.00     | 74.00     | 74.00     | 67.00     | 78.00           | 682.00    | 1019.00   | 4301.00   | 4557.00   | 4469.00   | 2096.00   | 564.00    | 284.00    | 77.00     | 56.00     | 63.00     | 69.00           | 385.00    | 1816.00   | 4593.00   | 5146.00   | 3560.00   | 3047.00   | 1069.00   | 242.00    | 104.00    | 93.00     | 113.00    | 116.00          | 282.00    | 1603.00   | 2801.00   | 3981.00   | 2670.00   | 1550.00   | 1062.00   | 171.00    | 119.00    |          |          | 
| 1346928512  | Total Usage (mmBTUs)    | 2205.10   | 2055.80   | 1806.72         | 2041.39   | 4367.38   | 8146.77   | 9148.15   | 7413.55   | 6603.03   | 2975.18   | 1596.17   | 1731.14   | 2134.55   | 2128.78   | 1819.56         | 2246.56   | 2428.51   | 6240.49   | 6268.46   | 6252.06   | 3502.70   | 1922.24   | 1775.30   | 1939.27   | 2268.02   | 2099.73   | 1854.56         | 2006.91   | 3351.67   | 6566.70   | 7184.50   | 5205.83   | 4569.24   | 2328.74   | 1648.51   | 1975.57   | 2108.68   | 1989.72   | 1892.73         | 1783.30   | 3062.51   | 4343.56   | 5655.68   | 4246.35   | 2821.05   | 2349.59   | 1487.28   | 1937.04   |          |          | 
| 1346928512  | Electricity Demand (KW) | 252.00    | 236.00    | 224.00          | 172.00    | 164.00    | 164.00    | 136.00    | 148.00    | 136.00    | 224.00    | 232.00    | 228.00    | 248.00    | 260.00    | 236.00          | 196.00    | 168.00    | 156.00    | 152.00    | 144.00    | 152.00    | 240.00    | 236.00    | 296.00    | 272.00    | 272.00    | 272.00          | 220.00    | 200.00    | 160.00    | 160.00    | 160.00    | 156.00    | 188.00    | 208.00    | 248.00    | 268.00    | 228.00    | 212.00          | 184.00    | 148.00    | 140.00    | 140.00    | 136.00    | 164.00    | 200.00    | 156.00    | 228.00    |          |          | 
| 1346928512  | Electricity Usage (KWH) | 112800.00 | 104800.00 | 82000.00        | 65200.00  | 62000.00  | 66400.00  | 62400.00  | 58800.00  | 60400.00  | 61200.00  | 70800.00  | 76800.00  | 96400.00  | 102000.00 | 84800.00        | 73200.00  | 64000.00  | 68400.00  | 62800.00  | 62400.00  | 61200.00  | 65600.00  | 74400.00  | 104000.00 | 110400.00 | 96400.00  | 100800.00       | 70400.00  | 66400.00  | 72000.00  | 61200.00  | 66400.00  | 60000.00  | 62800.00  | 68000.00  | 88800.00  | 101200.00 | 92000.00  | 81600.00        | 64000.00  | 64800.00  | 59200.00  | 57200.00  | 60800.00  | 58400.00  | 54400.00  | 55600.00  | 74000.00  |          |          | 
| 1346928512  | Gas (Therms)            | 211.00    | 215.00    | 214.00          | 1200.00   | 1745.00   | 4971.00   | 3950.00   | 4338.00   | 3239.00   | 1230.00   | 240.00    | 229.00    | 225.00    | 190.00    | 198.00          | 1319.00   | 1878.00   | 4532.00   | 5113.00   | 3999.00   | 3942.00   | 1357.00   | 442.00    | 82.00     | 63.00     | 57.00     | 59.00           | 293.00    | 2170.00   | 5486.00   | 8188.00   | 1742.00   | 3419.00   | 1783.00   | 331.00    | 214.00    | 238.00    | 215.00    | 243.00          | 268.00    | 435.00    | 2986.00   | 6555.00   | 5237.00   | 2868.00   | 1726.00   | 828.00    | 284.00    |          |          | 
| 1346928512  | Total Usage (mmBTUs)    | 406.08    | 379.18    | 301.26          | 342.53    | 386.10    | 723.72    | 607.97    | 634.48    | 530.04    | 331.87    | 265.64    | 285.02    | 351.51    | 367.12    | 309.22          | 381.73    | 406.23    | 686.65    | 725.63    | 612.87    | 603.07    | 359.59    | 298.12    | 363.15    | 383.09    | 334.71    | 349.93          | 269.57    | 443.62    | 794.33    | 1027.67   | 400.82    | 546.68    | 392.63    | 265.18    | 324.47    | 369.19    | 335.49    | 302.80          | 245.23    | 264.66    | 500.65    | 850.72    | 731.21    | 486.12    | 358.27    | 272.56    | 280.96    |          |          | 
| 1346928512  | Electricity Demand (KW) | 1592.00   | 1394.00   | 1396.00         | 1370.00   | 912.00    | 908.00    | 888.00    | 892.00    | 894.00    | 1296.00   | 1320.00   | 1322.00   | 1366.00   | 1556.00   | 1306.00         | 1248.00   | 1222.00   | 886.00    | 886.00    | 888.00    | 888.00    | 1294.00   | 1326.00   | 1388.00   | 1432.00   | 1452.00   | 1342.00         | 1346.00   | 1282.00   | 860.00    | 886.00    | 888.00    | 866.00    | 872.00    | 1326.00   | 1388.00   | 1588.00   | 1320.00   | 1318.00         | 1320.00   | 846.00    | 836.00    | 832.00    | 826.00    | 822.00    | 1216.00   | 1218.00   | 1516.00   |          |          | 
| 1346928512  | Electricity Usage (KWH) | 553600.00 | 538400.00 | 506400.00       | 407200.00 | 372000.00 | 376000.00 | 406400.00 | 364800.00 | 368000.00 | 364800.00 | 403200.00 | 438400.00 | 507200.00 | 510400.00 | 458400.00       | 393600.00 | 344000.00 | 388800.00 | 348000.00 | 357600.00 | 362400.00 | 356000.00 | 385600.00 | 480000.00 | 558400.00 | 502400.00 | 469600.00       | 406400.00 | 327200.00 | 388800.00 | 388800.00 | 247200.00 | 327200.00 | 327200.00 | 366400.00 | 458400.00 | 485600.00 | 448800.00 | 440000.00       | 379200.00 | 324800.00 | 322400.00 | 320800.00 | 320000.00 | 300800.00 | 313600.00 | 341600.00 | 444000.00 |          |          | 
```