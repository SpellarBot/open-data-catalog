# WAOFM - April 1 - Population by State, County and City, 1990 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-april-1-population-by-state-county-and-city-1990-to-present-22a1f) |
| Metadata | [Link](https://data.wa.gov/api/views/tecv-qzfm) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/tecv-qzfm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/tecv-qzfm/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | tecv-qzfm |
| Name | WAOFM - April 1 - Population by State, County and City, 1990 to Present |
| Attribution | Washington State Office of Financial Management, Forecasting and Research Division |
| Category | Demographics |
| Tags | wa, washington, ofm, state, county, city, population, intercensal, postcensal, state-of-the-salmon |
| Created | 2014-06-30T17:33:27Z |
| Publication Date | 2016-06-30T18:17:22Z |

## Description

Intercensal and postcensal population estimates for the state, counties and cities, 1990 to present.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | numeric metric | sequence     | SEQUENCE     | number    | number      |
| Yes      | numeric metric | filter       | FILTER       | number    | number      |
| Yes      | series tag     | county       | COUNTY       | text      | text        |
| Yes      | series tag     | jurisdiction | JURISDICTION | text      | text        |
| Yes      | numeric metric | pop_1990     | POP_1990     | number    | number      |
| Yes      | numeric metric | pop_1991     | POP_1991     | number    | number      |
| Yes      | numeric metric | pop_1992     | POP_1992     | number    | number      |
| Yes      | numeric metric | pop_1993     | POP_1993     | number    | number      |
| Yes      | numeric metric | pop_1994     | POP_1994     | number    | number      |
| Yes      | numeric metric | pop_1995     | POP_1995     | number    | number      |
| Yes      | numeric metric | pop_1996     | POP_1996     | number    | number      |
| Yes      | numeric metric | pop_1997     | POP_1997     | number    | number      |
| Yes      | numeric metric | pop_1998     | POP_1998     | number    | number      |
| Yes      | numeric metric | pop_1999     | POP_1999     | number    | number      |
| Yes      | numeric metric | pop_2000     | POP_2000     | number    | number      |
| Yes      | numeric metric | pop_2001     | POP_2001     | number    | number      |
| Yes      | numeric metric | pop_2002     | POP_2002     | number    | number      |
| Yes      | numeric metric | pop_2003     | POP_2003     | number    | number      |
| Yes      | numeric metric | pop_2004     | POP_2004     | number    | number      |
| Yes      | numeric metric | pop_2005     | POP_2005     | number    | number      |
| Yes      | numeric metric | pop_2006     | POP_2006     | number    | number      |
| Yes      | numeric metric | pop_2007     | POP_2007     | number    | number      |
| Yes      | numeric metric | pop_2008     | POP_2008     | number    | number      |
| Yes      | numeric metric | pop_2009     | POP_2009     | number    | number      |
| Yes      | numeric metric | pop_2010     | POP_2010     | number    | number      |
| Yes      | numeric metric | pop_2011     | POP_2011     | number    | number      |
| Yes      | numeric metric | pop_2012     | POP_2012     | number    | number      |
| Yes      | numeric metric | pop_2013     | POP_2013     | number    | number      |
| Yes      | numeric metric | pop_2014     | POP_2014     | number    | number      |
| Yes      | numeric metric | pop_2015     | POP_2015     | number    | number      |
| Yes      | numeric metric | pop_2016     | POP_2016     | number    | number      |
```

## Time Field

```ls
Value = 1990
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tecv-qzfm d:1990-01-01T00:00:00.000Z t:county=Adams t:jurisdiction="Adams County" m:pop_2002=16911 m:pop_2003=17081 m:pop_2000=16428 m:pop_2001=16699 m:pop_2015=19410 m:pop_2016=19510 m:pop_1990=13603 m:pop_1991=13823 m:pop_1992=14063 m:pop_1994=14679 m:pop_1993=14335 m:pop_1996=15323 m:pop_1995=15030 m:pop_1998=15879 m:pop_1997=15698 m:sequence=1 m:pop_1999=16151 m:pop_2014=19400 m:pop_2013=19200 m:pop_2009=18421 m:pop_2012=19050 m:pop_2008=18214 m:pop_2011=18950 m:pop_2007=17959 m:pop_2010=18728 m:pop_2006=17690 m:pop_2005=17643 m:filter=1 m:pop_2004=17489

series e:tecv-qzfm d:1990-01-01T00:00:00.000Z t:county=Adams t:jurisdiction="Unincorporated Adams County" m:pop_2002=8193 m:pop_2003=8324 m:pop_2000=7905 m:pop_2001=8037 m:pop_2015=9085 m:pop_2016=9105 m:pop_1990=6466 m:pop_1991=6698 m:pop_1992=6776 m:pop_1994=7162 m:pop_1993=7009 m:pop_1996=7530 m:pop_1995=7303 m:pop_1998=7647 m:pop_1997=7598 m:sequence=2 m:pop_1999=7815 m:pop_2014=9135 m:pop_2013=9040 m:pop_2009=8799 m:pop_2012=8980 m:pop_2008=8742 m:pop_2011=8960 m:pop_2007=8682 m:pop_2010=8818 m:pop_2006=8587 m:pop_2005=8507 m:filter=2 m:pop_2004=8451

series e:tecv-qzfm d:1990-01-01T00:00:00.000Z t:county=Adams t:jurisdiction="Incorporated Adams County" m:pop_2002=8718 m:pop_2003=8757 m:pop_2000=8523 m:pop_2001=8662 m:pop_2015=10325 m:pop_2016=10405 m:pop_1990=7137 m:pop_1991=7125 m:pop_1992=7287 m:pop_1994=7517 m:pop_1993=7326 m:pop_1996=7793 m:pop_1995=7727 m:pop_1998=8232 m:pop_1997=8100 m:sequence=3 m:pop_1999=8336 m:pop_2014=10265 m:pop_2013=10160 m:pop_2009=9622 m:pop_2012=10070 m:pop_2008=9472 m:pop_2011=9990 m:pop_2007=9277 m:pop_2010=9910 m:pop_2006=9103 m:pop_2005=9136 m:filter=3 m:pop_2004=9038
```

## Meta Commands

```ls
metric m:sequence p:integer l:SEQUENCE d:"Sequence number (use this field to return the table to the original sort order)" t:dataTypeName=number

metric m:filter p:integer l:FILTER d:"Filter (use this field to filter the data by geography: 1=county or state, 2=unincorporated county or state, 3=incorporated county or state, 4=city )" t:dataTypeName=number

metric m:pop_1990 p:integer l:POP_1990 d:"Total population 1990" t:dataTypeName=number

metric m:pop_1991 p:integer l:POP_1991 d:"Total population 1991" t:dataTypeName=number

metric m:pop_1992 p:integer l:POP_1992 d:"Total population 1992" t:dataTypeName=number

metric m:pop_1993 p:integer l:POP_1993 d:"Total population 1993" t:dataTypeName=number

metric m:pop_1994 p:integer l:POP_1994 d:"Total population 1994" t:dataTypeName=number

metric m:pop_1995 p:integer l:POP_1995 d:"Total population 1995" t:dataTypeName=number

metric m:pop_1996 p:integer l:POP_1996 d:"Total population 1996" t:dataTypeName=number

metric m:pop_1997 p:integer l:POP_1997 d:"Total population 1997" t:dataTypeName=number

metric m:pop_1998 p:integer l:POP_1998 d:"Total population 1998" t:dataTypeName=number

metric m:pop_1999 p:integer l:POP_1999 d:"Total population 1999" t:dataTypeName=number

metric m:pop_2000 p:integer l:POP_2000 d:"Total population 2000" t:dataTypeName=number

metric m:pop_2001 p:integer l:POP_2001 d:"Total population 2001" t:dataTypeName=number

metric m:pop_2002 p:integer l:POP_2002 d:"Total population 2002" t:dataTypeName=number

metric m:pop_2003 p:integer l:POP_2003 d:"Total population 2003" t:dataTypeName=number

metric m:pop_2004 p:integer l:POP_2004 d:"Total population 2004" t:dataTypeName=number

metric m:pop_2005 p:integer l:POP_2005 d:"Total population 2005" t:dataTypeName=number

metric m:pop_2006 p:integer l:POP_2006 d:"Total population 2006" t:dataTypeName=number

metric m:pop_2007 p:integer l:POP_2007 d:"Total population 2007" t:dataTypeName=number

metric m:pop_2008 p:integer l:POP_2008 d:"Total population 2008" t:dataTypeName=number

metric m:pop_2009 p:integer l:POP_2009 d:"Total population 2009" t:dataTypeName=number

metric m:pop_2010 p:integer l:POP_2010 d:"Total population 2010" t:dataTypeName=number

metric m:pop_2011 p:integer l:POP_2011 d:"Total population 2011" t:dataTypeName=number

metric m:pop_2012 p:integer l:POP_2012 d:"Total population 2012" t:dataTypeName=number

metric m:pop_2013 p:integer l:POP_2013 d:"Total population 2013" t:dataTypeName=number

metric m:pop_2014 p:integer l:POP_2014 d:"Total population 2014" t:dataTypeName=number

metric m:pop_2015 p:integer l:POP_2015 d:"Total population 2015" t:dataTypeName=number

metric m:pop_2016 p:integer l:POP_2016 d:"Total population 2016" t:dataTypeName=number

entity e:tecv-qzfm l:"WAOFM - April 1 - Population by State, County and City, 1990 to Present" t:attribution="Washington State Office of Financial Management, Forecasting and Research Division" t:url=https://data.wa.gov/api/views/tecv-qzfm

property e:tecv-qzfm t:meta.view v:id=tecv-qzfm v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/april1/default.asp v:averageRating=0 v:name="WAOFM - April 1 - Population by State, County and City, 1990 to Present" v:attribution="Washington State Office of Financial Management, Forecasting and Research Division"

property e:tecv-qzfm t:meta.view.license v:name="Public Domain"

property e:tecv-qzfm t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:tecv-qzfm t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| sequence | filter | county | jurisdiction                 | pop_1990 | pop_1991 | pop_1992 | pop_1993 | pop_1994 | pop_1995 | pop_1996 | pop_1997 | pop_1998 | pop_1999 | pop_2000 | pop_2001 | pop_2002 | pop_2003 | pop_2004 | pop_2005 | pop_2006 | pop_2007 | pop_2008 | pop_2009 | pop_2010 | pop_2011 | pop_2012 | pop_2013 | pop_2014 | pop_2015 | pop_2016 | 
| ======== | ====== | ====== | ============================ | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | 
| 1        | 1      | Adams  | Adams County                 | 13603    | 13823    | 14063    | 14335    | 14679    | 15030    | 15323    | 15698    | 15879    | 16151    | 16428    | 16699    | 16911    | 17081    | 17489    | 17643    | 17690    | 17959    | 18214    | 18421    | 18728    | 18950    | 19050    | 19200    | 19400    | 19410    | 19510    | 
| 2        | 2      | Adams  | Unincorporated Adams County  | 6466     | 6698     | 6776     | 7009     | 7162     | 7303     | 7530     | 7598     | 7647     | 7815     | 7905     | 8037     | 8193     | 8324     | 8451     | 8507     | 8587     | 8682     | 8742     | 8799     | 8818     | 8960     | 8980     | 9040     | 9135     | 9085     | 9105     | 
| 3        | 3      | Adams  | Incorporated Adams County    | 7137     | 7125     | 7287     | 7326     | 7517     | 7727     | 7793     | 8100     | 8232     | 8336     | 8523     | 8662     | 8718     | 8757     | 9038     | 9136     | 9103     | 9277     | 9472     | 9622     | 9910     | 9990     | 10070    | 10160    | 10265    | 10325    | 10405    | 
| 4        | 4      | Adams  | Hatton                       | 71       | 80       | 81       | 82       | 83       | 84       | 93       | 94       | 96       | 97       | 98       | 119      | 97       | 97       | 97       | 97       | 96       | 96       | 96       | 98       | 101      | 100      | 105      | 110      | 110      | 110      | 110      | 
| 5        | 4      | Adams  | Lind                         | 472      | 400      | 523      | 435      | 452      | 451      | 484      | 517      | 535      | 567      | 582      | 582      | 576      | 574      | 561      | 556      | 556      | 550      | 550      | 550      | 564      | 560      | 565      | 570      | 565      | 560      | 550      | 
| 6        | 4      | Adams  | Othello                      | 4638     | 4692     | 4735     | 4868     | 5033     | 5240     | 5265     | 5508     | 5614     | 5681     | 5847     | 5961     | 6062     | 6129     | 6434     | 6551     | 6523     | 6714     | 6931     | 7089     | 7364     | 7420     | 7495     | 7565     | 7695     | 7780     | 7875     | 
| 7        | 4      | Adams  | Ritzville                    | 1725     | 1728     | 1730     | 1729     | 1730     | 1733     | 1733     | 1731     | 1733     | 1733     | 1736     | 1745     | 1735     | 1716     | 1707     | 1695     | 1685     | 1678     | 1681     | 1675     | 1673     | 1705     | 1695     | 1700     | 1680     | 1670     | 1660     | 
| 8        | 4      | Adams  | Washtucna                    | 231      | 225      | 218      | 212      | 219      | 219      | 218      | 250      | 254      | 258      | 260      | 255      | 248      | 241      | 239      | 237      | 243      | 239      | 214      | 210      | 208      | 205      | 210      | 215      | 215      | 205      | 210      | 
| 9        | 1      | Asotin | Asotin County                | 17605    | 17677    | 17866    | 18124    | 18666    | 18937    | 19622    | 19943    | 20202    | 20442    | 20551    | 20650    | 20652    | 20709    | 20779    | 20939    | 21176    | 21413    | 21522    | 21593    | 21623    | 21650    | 21700    | 21800    | 21950    | 22010    | 22150    | 
| 10       | 2      | Asotin | Unincorporated Asotin County | 9871     | 10006    | 10058    | 10351    | 10521    | 11117    | 11554    | 11692    | 11739    | 11796    | 12119    | 12173    | 12238    | 12314    | 12386    | 12536    | 12744    | 12951    | 13072    | 13121    | 13143    | 13195    | 13240    | 13325    | 13460    | 13515    | 13620    | 
```