# Dog Licenses Sold per Town, by Fiscal Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dog-licenses-sold-per-town-by-fiscal-year) |
| Metadata | [Link](https://data.ct.gov/api/views/j9dq-in2k) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/j9dq-in2k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/j9dq-in2k/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | j9dq-in2k |
| Name | Dog Licenses Sold per Town, by Fiscal Year |
| Attribution | Department of Agriculture |
| Category | Government |
| Tags | dog, license, towns, doag |
| Created | 2014-05-09T18:38:06Z |
| Publication Date | 2017-01-24T20:01:56Z |

## Description

Listing of Dog licenses sold in each Town per fiscal year

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | town        | TOWN       | text      | text        |
| Yes      | numeric metric | 2015_16     | 2015/16    | number    | number      |
| Yes      | numeric metric | 2014_15     | 2014/15    | number    | number      |
| Yes      | numeric metric | 2013_2014   | 2013/14    | number    | number      |
| Yes      | numeric metric | 2012_13     | 2012/13    | number    | number      |
| Yes      | numeric metric | 2011_12     | 2011/12    | number    | number      |
| Yes      | numeric metric | 2010_11     | 2010/11    | number    | number      |
| Yes      | numeric metric | 2009_10     | 2009/10    | number    | number      |
| Yes      | numeric metric | 2008_09     | 2008/09    | number    | number      |
| Yes      | numeric metric | 2007_08     | 2007/08    | number    | number      |
| Yes      | numeric metric | 2006_07     | 2006/07    | number    | number      |
| Yes      | numeric metric | 2005_06     | 2005/06    | number    | number      |
| Yes      | numeric metric | 2004_05     | 2004/05    | number    | number      |
| Yes      | numeric metric | 2003_04     | 2003/04    | number    | number      |
| Yes      | numeric metric | 2002_03     | 2002/03    | number    | number      |
| Yes      | numeric metric | 2001_02     | 2001/02    | number    | number      |
| Yes      | numeric metric | 2000_01     | 2000/01    | number    | number      |
| Yes      | numeric metric | 1999_00     | 1999/00    | number    | number      |
| Yes      | numeric metric | 1998_99     | 1998/99    | number    | number      |
| Yes      | numeric metric | 1997_98     | 1997/98    | number    | number      |
| Yes      | numeric metric | 1996_97     | 1996/97    | number    | number      |
| Yes      | numeric metric | 1995_96     | 1995/96    | number    | number      |
| Yes      | numeric metric | 1994_95     | 1994/95    | number    | number      |
| Yes      | numeric metric | 1993_94     | 1993/94    | number    | number      |
| Yes      | numeric metric | 1992_93     | 1992/93    | number    | number      |
| Yes      | numeric metric | 1991_92     | 1991/92    | number    | number      |
| Yes      | numeric metric | 1990_91     | 1990/91    | number    | number      |
| Yes      | numeric metric | 1989_90     | 1989/90    | number    | number      |
| Yes      | numeric metric | 1988_89     | 1988/89    | number    | number      |
| Yes      | numeric metric | 1987_88     | 1987/88    | number    | number      |
| Yes      | numeric metric | 1986_87     | 1986/87    | number    | number      |
| Yes      | numeric metric | 1985_86     | 1985/86    | number    | number      |
| Yes      | numeric metric | 1984_85     | 1984/85    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:j9dq-in2k d:2017-01-24T20:01:23.000Z t:town=ANDOVER m:1996_97=437 m:2007_08=401 m:1985_86=539 m:2002_03=457 m:2001_02=474 m:1997_98=440 m:1986_87=507 m:1998_99=432 m:2015_16=281 m:2004_05=444 m:2014_15=257 m:2003_04=420 m:2013_2014=261 m:1990_91=462 m:1984_85=584 m:2012_13=318 m:1991_92=559 m:2000_01=474 m:2006_07=406 m:1992_93=465 m:2005_06=408 m:2011_12=332 m:2008_09=395 m:1989_90=489 m:1999_00=465 m:2009_10=377 m:1993_94=436 m:1988_89=507 m:2010_11=335 m:1987_88=514 m:1994_95=408 m:1995_96=451

series e:j9dq-in2k d:2017-01-24T20:01:23.000Z t:town=ANSONIA m:1996_97=718 m:2007_08=1127 m:1985_86=1023 m:2002_03=1218 m:2001_02=1313 m:1997_98=782 m:1986_87=910 m:1998_99=986 m:2015_16=931 m:2004_05=1102 m:2014_15=899 m:2003_04=1139 m:2013_2014=969 m:1990_91=729 m:1984_85=920 m:2012_13=939 m:1991_92=799 m:2000_01=1200 m:2006_07=1138 m:1992_93=800 m:2005_06=1143 m:2011_12=955 m:2008_09=1222 m:1989_90=683 m:1999_00=1100 m:2009_10=989 m:1993_94=800 m:1988_89=728 m:2010_11=986 m:1987_88=755 m:1994_95=697 m:1995_96=614

series e:j9dq-in2k d:2017-01-24T20:01:23.000Z t:town=ASHFORD m:1996_97=686 m:2007_08=599 m:1985_86=488 m:2002_03=689 m:2001_02=704 m:1997_98=715 m:1986_87=497 m:1998_99=727 m:2015_16=531 m:2004_05=647 m:2014_15=539 m:2003_04=690 m:2013_2014=499 m:1990_91=580 m:1984_85=429 m:2012_13=527 m:1991_92=613 m:2000_01=720 m:2006_07=630 m:1992_93=644 m:2005_06=593 m:2011_12=570 m:2008_09=607 m:1989_90=547 m:1999_00=741 m:2009_10=586 m:1993_94=680 m:1988_89=561 m:2010_11=602 m:1987_88=511 m:1994_95=683 m:1995_96=736
```

## Meta Commands

```ls
metric m:2015_16 p:integer l:2015/16 t:dataTypeName=number

metric m:2014_15 p:integer l:2014/15 t:dataTypeName=number

metric m:2013_2014 p:integer l:2013/14 t:dataTypeName=number

metric m:2012_13 p:integer l:2012/13 t:dataTypeName=number

metric m:2011_12 p:integer l:2011/12 t:dataTypeName=number

metric m:2010_11 p:integer l:2010/11 t:dataTypeName=number

metric m:2009_10 p:integer l:2009/10 t:dataTypeName=number

metric m:2008_09 p:integer l:2008/09 t:dataTypeName=number

metric m:2007_08 p:integer l:2007/08 t:dataTypeName=number

metric m:2006_07 p:integer l:2006/07 t:dataTypeName=number

metric m:2005_06 p:integer l:2005/06 t:dataTypeName=number

metric m:2004_05 p:integer l:2004/05 t:dataTypeName=number

metric m:2003_04 p:integer l:2003/04 t:dataTypeName=number

metric m:2002_03 p:integer l:2002/03 t:dataTypeName=number

metric m:2001_02 p:integer l:2001/02 t:dataTypeName=number

metric m:2000_01 p:integer l:2000/01 t:dataTypeName=number

metric m:1999_00 p:integer l:1999/00 t:dataTypeName=number

metric m:1998_99 p:integer l:1998/99 t:dataTypeName=number

metric m:1997_98 p:integer l:1997/98 t:dataTypeName=number

metric m:1996_97 p:integer l:1996/97 t:dataTypeName=number

metric m:1995_96 p:integer l:1995/96 t:dataTypeName=number

metric m:1994_95 p:integer l:1994/95 t:dataTypeName=number

metric m:1993_94 p:integer l:1993/94 t:dataTypeName=number

metric m:1992_93 p:integer l:1992/93 t:dataTypeName=number

metric m:1991_92 p:integer l:1991/92 t:dataTypeName=number

metric m:1990_91 p:integer l:1990/91 t:dataTypeName=number

metric m:1989_90 p:integer l:1989/90 t:dataTypeName=number

metric m:1988_89 p:integer l:1988/89 t:dataTypeName=number

metric m:1987_88 p:integer l:1987/88 t:dataTypeName=number

metric m:1986_87 p:integer l:1986/87 t:dataTypeName=number

metric m:1985_86 p:integer l:1985/86 t:dataTypeName=number

metric m:1984_85 p:integer l:1984/85 t:dataTypeName=number

entity e:j9dq-in2k l:"Dog Licenses Sold per Town, by Fiscal Year" t:attribution="Department of Agriculture" t:url=https://data.ct.gov/api/views/j9dq-in2k

property e:j9dq-in2k t:meta.view v:id=j9dq-in2k v:category=Government v:attributionLink="http://www.ct.gov/doag/cwp/view.asp?a=1367&q=259098" v:averageRating=0 v:name="Dog Licenses Sold per Town, by Fiscal Year" v:attribution="Department of Agriculture"

property e:j9dq-in2k t:meta.view.license v:name="Public Domain"

property e:j9dq-in2k t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:j9dq-in2k t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | town         | 2015_16 | 2014_15 | 2013_2014 | 2012_13 | 2011_12 | 2010_11 | 2009_10 | 2008_09 | 2007_08 | 2006_07 | 2005_06 | 2004_05 | 2003_04 | 2002_03 | 2001_02 | 2000_01 | 1999_00 | 1998_99 | 1997_98 | 1996_97 | 1995_96 | 1994_95 | 1993_94 | 1992_93 | 1991_92 | 1990_91 | 1989_90 | 1988_89 | 1987_88 | 1986_87 | 1985_86 | 1984_85 | 
| =========== | ============ | ======= | ======= | ========= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | 
| 1485288083  | ANDOVER      | 281     | 257     | 261       | 318     | 332     | 335     | 377     | 395     | 401     | 406     | 408     | 444     | 420     | 457     | 474     | 474     | 465     | 432     | 440     | 437     | 451     | 408     | 436     | 465     | 559     | 462     | 489     | 507     | 514     | 507     | 539     | 584     | 
| 1485288083  | ANSONIA      | 931     | 899     | 969       | 939     | 955     | 986     | 989     | 1222    | 1127    | 1138    | 1143    | 1102    | 1139    | 1218    | 1313    | 1200    | 1100    | 986     | 782     | 718     | 614     | 697     | 800     | 800     | 799     | 729     | 683     | 728     | 755     | 910     | 1023    | 920     | 
| 1485288083  | ASHFORD      | 531     | 539     | 499       | 527     | 570     | 602     | 586     | 607     | 599     | 630     | 593     | 647     | 690     | 689     | 704     | 720     | 741     | 727     | 715     | 686     | 736     | 683     | 680     | 644     | 613     | 580     | 547     | 561     | 511     | 497     | 488     | 429     | 
| 1485288083  | AVON         | 1935    | 1952    | 1922      | 1918    | 1876    | 1873    | 1825    | 1776    | 1640    | 1504    | 1361    | 1298    | 1320    | 1269    | 1257    | 1187    | 1150    | 1101    | 1070    | 1071    | 1079    | 1111    | 1089    | 1132    | 1108    | 1101    | 1101    | 1137    | 1181    | 1260    | 1209    | 963     | 
| 1485288083  | BARKHAMSTED  | 605     | 665     | 640       | 736     | 522     | 547     | 547     | 549     | 547     | 505     | 512     | 488     | 530     | 490     | 508     | 493     | 488     | 497     | 492     | 437     | 443     | 459     | 465     | 535     | 454     | 449     | 404     | 372     | 357     | 392     | 371     | 381     | 
| 1485288083  | BEACON FALLS | 355     | 364     | 331       | 332     | 372     | 349     | 386     | 380     | 313     | 469     | 435     | 514     | 529     | 460     | 466     | 365     | 345     | 337     | 340     | 324     | 318     | 338     | 320     | 341     | 306     | 277     | 259     | 275     | 291     | 320     | 378     | 342     | 
| 1485288083  | BERLIN       | 1814    | 1785    | 1882      | 1868    | 1919    | 2023    | 1831    | 1828    | 1890    | 2000    | 2034    | 2075    | 2018    | 1938    | 1976    | 1921    | 1886    | 1775    | 1630    | 1624    | 1608    | 1615    | 1766    | 1777    | 1726    | 1651    | 1695    | 1737    | 1470    | 1931    | 2196    | 1735    | 
| 1485288083  | BETHANY      | 554     | 517     | 522       | 510     | 568     | 589     | 564     | 601     | 601     | 667     | 663     | 664     | 659     | 690     | 684     | 701     | 665     | 721     | 689     | 679     | 692     | 737     | 730     | 688     | 705     | 736     | 692     | 702     | 779     | 710     | 820     | 498     | 
| 1485288083  | BETHEL       | 1231    | 1237    | 1282      | 1326    | 1334    | 1334    | 1375    | 1296    | 1249    | 1288    | 1408    | 1500    | 1589    | 1949    | 1821    | 1848    | 1914    | 1837    | 1652    | 1617    | 1320    | 1350    | 1302    | 1326    | 1127    | 1272    | 1412    | 1444    | 1479    | 1756    | 2007    | 1802    | 
| 1485288083  | BETHLEHEM    | 409     | 591     | 577       | 620     | 652     | 687     | 738     | 768     | 838     | 847     | 859     | 914     | 886     | 838     | 767     | 821     | 852     | 793     | 792     | 757     | 750     | 778     | 757     | 789     | 718     | 631     | 724     | 750     | 730     | 696     | 719     | 782     | 
```