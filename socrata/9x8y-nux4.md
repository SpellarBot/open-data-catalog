# Electricity Generation By Source In Maryland

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electricity-generation-by-source-in-maryland) |
| Metadata | [Link](https://data.maryland.gov/api/views/9x8y-nux4) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/9x8y-nux4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/9x8y-nux4/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 9x8y-nux4 |
| Name | Electricity Generation By Source In Maryland |
| Category | Energy and Environment |
| Tags | energy, generation, renewable |
| Created | 2013-08-06T22:23:44Z |
| Publication Date | 2015-09-09T20:27:37Z |

## Description

The energy source for all electricity generated in Maryland from 1990 through 2012. Numbers are in megawatt-hours (MWh). Note that Maryland imports a certain percentage of its electricity from out-of-state generators (around 45 percent in 2012). Data comes from the U.S. Energy Information Administration.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | energy_source | Energy Source | text      | text        |
| Yes      | numeric metric | 1990_mwh      | 1990 (MWh)    | number    | number      |
| Yes      | numeric metric | 1990          | 1990 (%)      | number    | number      |
| Yes      | numeric metric | 1991_mwh      | 1991 (MWh)    | number    | number      |
| Yes      | numeric metric | 1991          | 1991 (%)      | number    | number      |
| Yes      | numeric metric | 1992_mwh      | 1992 (MWh)    | number    | number      |
| Yes      | numeric metric | 1992          | 1992 (%)      | number    | number      |
| Yes      | numeric metric | 1993_mwh      | 1993 (MWh)    | number    | number      |
| Yes      | numeric metric | 1993          | 1993 (%)      | number    | number      |
| Yes      | numeric metric | 1994_mwh      | 1994 (MWh)    | number    | number      |
| Yes      | numeric metric | 1994          | 1994 (%)      | number    | number      |
| Yes      | numeric metric | 1995_mwh      | 1995 (MWh)    | number    | number      |
| Yes      | numeric metric | 1995          | 1995 (%)      | number    | number      |
| Yes      | numeric metric | 1996_mwh      | 1996 (MWh)    | number    | number      |
| Yes      | numeric metric | 1996          | 1996 (%)      | number    | number      |
| Yes      | numeric metric | 1997_mwh      | 1997 (MWh)    | number    | number      |
| Yes      | numeric metric | 1997          | 1997 (%)      | number    | number      |
| Yes      | numeric metric | 1998_mwh      | 1998 (MWh)    | number    | number      |
| Yes      | numeric metric | 1998          | 1998 (%)      | number    | number      |
| Yes      | numeric metric | 1999_mwh      | 1999 (MWh)    | number    | number      |
| Yes      | numeric metric | 1999          | 1999 (%)      | number    | number      |
| Yes      | numeric metric | 2000_mwh      | 2000 (MWh)    | number    | number      |
| Yes      | numeric metric | 2000          | 2000 (%)      | number    | number      |
| Yes      | numeric metric | 2001_mwh      | 2001 (MWh)    | number    | number      |
| Yes      | numeric metric | 2001          | 2001 (%)      | number    | number      |
| Yes      | numeric metric | 2002_mwh      | 2002 (MWh)    | number    | number      |
| Yes      | numeric metric | 2002          | 2002 (%)      | number    | number      |
| Yes      | numeric metric | 2003_mwh      | 2003 (MWh)    | number    | number      |
| Yes      | numeric metric | 2003          | 2003 (%)      | number    | number      |
| Yes      | numeric metric | 2004_mwh      | 2004 (MWh)    | number    | number      |
| Yes      | numeric metric | 2004          | 2004 (%)      | number    | number      |
| Yes      | numeric metric | 2005_mwh      | 2005 (MWh)    | number    | number      |
| Yes      | numeric metric | 2005          | 2005 (%)      | number    | number      |
| Yes      | numeric metric | 2006_mwh      | 2006 (MWh)    | number    | number      |
| Yes      | numeric metric | 2006          | 2006 (%)      | number    | number      |
| Yes      | numeric metric | 2007_mwh      | 2007 (MWh)    | number    | number      |
| Yes      | numeric metric | 2007          | 2007 (%)      | number    | number      |
| Yes      | numeric metric | 2008_mwh      | 2008 (MWh)    | number    | number      |
| Yes      | numeric metric | 2008          | 2008 (%)      | number    | number      |
| Yes      | numeric metric | 2009_mwh      | 2009 (MWh)    | number    | number      |
| Yes      | numeric metric | 2009          | 2009 (%)      | number    | number      |
| Yes      | numeric metric | 2010_mwh      | 2010 (MWh)    | number    | number      |
| Yes      | numeric metric | 2010          | 2010 (%)      | number    | number      |
| Yes      | numeric metric | 2011_mwh      | 2011 (MWh)    | number    | number      |
| Yes      | numeric metric | 2011          | 2011 (%)      | number    | number      |
| Yes      | numeric metric | 2012_mwh      | 2012 (MWh)    | number    | number      |
| Yes      | numeric metric | 2012          | 2012 (%)      | number    | number      |
| Yes      | numeric metric | 2013_mwh      | 2013 (MWh)    | number    | number      |
| Yes      | numeric metric | 2013          | 2013 (%)      | number    | number      |
| Yes      | numeric metric | 2014_mwh      | 2014 (MWh)    | number    | number      |
| Yes      | numeric metric | 2014          | 2014 (%)      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:9x8y-nux4 d:2013-08-06T15:24:09.000Z t:energy_source="Other Renewables" m:2008=0 m:2009=0 m:2006=0 m:1997_mwh=743498 m:2007=0 m:2004=1.1319435808710356 m:2005=0 m:2002=1.0804491584430924 m:2003=1.1408913649003742 m:1992_mwh=504655 m:1991_mwh=497153 m:1999_mwh=785562 m:1995=1.458700788426465 m:2000_mwh=818410 m:1996=1.5848688709838483 m:1997=1.5918207043698178 m:1998=1.5017723426030083 m:1991=1.2475331789377622 m:1992=1.225564271861146 m:1993=1.0648343470462642 m:1994=1.1488539669654914 m:2012=0 m:2011=0 m:2010=0 m:2001_mwh=373015 m:1999=1.5198849985762966 m:1996_mwh=733392 m:2004_mwh=589208 m:1995_mwh=676336 m:2002_mwh=521631 m:1998_mwh=760693 m:1990=1.5686249913003598 m:2003_mwh=596050 m:1994_mwh=520886 m:1990_mwh=520192 m:1993_mwh=478940 m:2001=0.7602878297284639 m:2000=1.6001640812914089

series e:9x8y-nux4 d:2013-08-06T15:24:09.000Z t:energy_source="Other Gases" m:2008=0.7132943460829431 m:2009=0.6149241470498 m:2006=0.6790547387437573 m:1997_mwh=564036 m:2007=0.7521426283627733 m:2008_mwh=337823 m:2004=0.7906687618993425 m:2005=0.6503144853295185 m:2002=1.0449928134516542 m:2003=0.6227576713818661 m:1992_mwh=506572 m:2011_mwh=154640.24999999997 m:2007_mwh=377560 m:1991_mwh=478704 m:1999_mwh=59891 m:1995=1.4789420692386386 m:1996=1.1655093763390845 m:2000_mwh=74572 m:1997=1.2075946173492522 m:1998=0.16250956976560743 m:1991=1.2012380954962003 m:1992=1.2302197428446053 m:1993=1.0578264590814046 m:1994=1.1066745202837835 m:2012=0.46933539565769355 m:2011=0.3697929063545891 m:2010=0.49241109216141354 m:2001_mwh=439980 m:1999=0.11587555463443112 m:2010_mwh=214727 m:1996_mwh=539335 m:2004_mwh=411565 m:1995_mwh=685721 m:2002_mwh=504513 m:1998_mwh=82316 m:1990=1.4721449289452009 m:2009_mwh=269182 m:2003_mwh=325355 m:1994_mwh=501762 m:2012_mwh=177480.1 m:1990_mwh=488197 m:2005_mwh=342466 m:1993_mwh=475788 m:2006_mwh=332444 m:2001=0.8967774468156227 m:2000=0.1458039807310064

series e:9x8y-nux4 d:2015-09-09T13:20:42.000Z t:energy_source=Solar m:2008=0 m:2009=0 m:2006=0 m:2007=0 m:2004=0 m:2005=0 m:2002=0 m:2003=0 m:2011_mwh=2706.02 m:1995=0 m:1996=0 m:1997=0 m:1998=0 m:1991=0 m:1992=0 m:1993=0 m:1994=0 m:2012=0.07325280017951938 m:2011=0.006470934963268913 m:2010=0.00018345567801400422 m:1999=0 m:2014_mwh=112825 m:2010_mwh=80 m:2013_mwh=63485 m:2013=0.2 m:2014=0.3 m:1990=0 m:2012_mwh=27700.690000000002 m:2001=0 m:2000=0
```

## Meta Commands

```ls
metric m:1990_mwh p:integer l:"1990 (MWh)" t:dataTypeName=number

metric m:1990 p:decimal l:"1990 (%)" t:dataTypeName=number

metric m:1991_mwh p:integer l:"1991 (MWh)" t:dataTypeName=number

metric m:1991 p:decimal l:"1991 (%)" t:dataTypeName=number

metric m:1992_mwh p:integer l:"1992 (MWh)" t:dataTypeName=number

metric m:1992 p:decimal l:"1992 (%)" t:dataTypeName=number

metric m:1993_mwh p:integer l:"1993 (MWh)" t:dataTypeName=number

metric m:1993 p:double l:"1993 (%)" t:dataTypeName=number

metric m:1994_mwh p:integer l:"1994 (MWh)" t:dataTypeName=number

metric m:1994 p:decimal l:"1994 (%)" t:dataTypeName=number

metric m:1995_mwh p:integer l:"1995 (MWh)" t:dataTypeName=number

metric m:1995 p:decimal l:"1995 (%)" t:dataTypeName=number

metric m:1996_mwh p:integer l:"1996 (MWh)" t:dataTypeName=number

metric m:1996 p:double l:"1996 (%)" t:dataTypeName=number

metric m:1997_mwh p:integer l:"1997 (MWh)" t:dataTypeName=number

metric m:1997 p:decimal l:"1997 (%)" t:dataTypeName=number

metric m:1998_mwh p:integer l:"1998 (MWh)" t:dataTypeName=number

metric m:1998 p:double l:"1998 (%)" t:dataTypeName=number

metric m:1999_mwh p:integer l:"1999 (MWh)" t:dataTypeName=number

metric m:1999 p:decimal l:"1999 (%)" t:dataTypeName=number

metric m:2000_mwh p:integer l:"2000 (MWh)" t:dataTypeName=number

metric m:2000 p:double l:"2000 (%)" t:dataTypeName=number

metric m:2001_mwh p:integer l:"2001 (MWh)" t:dataTypeName=number

metric m:2001 p:double l:"2001 (%)" t:dataTypeName=number

metric m:2002_mwh p:integer l:"2002 (MWh)" t:dataTypeName=number

metric m:2002 p:decimal l:"2002 (%)" t:dataTypeName=number

metric m:2003_mwh p:integer l:"2003 (MWh)" t:dataTypeName=number

metric m:2003 p:double l:"2003 (%)" t:dataTypeName=number

metric m:2004_mwh p:integer l:"2004 (MWh)" t:dataTypeName=number

metric m:2004 p:decimal l:"2004 (%)" t:dataTypeName=number

metric m:2005_mwh p:integer l:"2005 (MWh)" t:dataTypeName=number

metric m:2005 p:double l:"2005 (%)" t:dataTypeName=number

metric m:2006_mwh p:integer l:"2006 (MWh)" t:dataTypeName=number

metric m:2006 p:decimal l:"2006 (%)" t:dataTypeName=number

metric m:2007_mwh p:integer l:"2007 (MWh)" t:dataTypeName=number

metric m:2007 p:double l:"2007 (%)" t:dataTypeName=number

metric m:2008_mwh p:integer l:"2008 (MWh)" t:dataTypeName=number

metric m:2008 p:double l:"2008 (%)" t:dataTypeName=number

metric m:2009_mwh p:integer l:"2009 (MWh)" t:dataTypeName=number

metric m:2009 p:double l:"2009 (%)" t:dataTypeName=number

metric m:2010_mwh p:integer l:"2010 (MWh)" t:dataTypeName=number

metric m:2010 p:double l:"2010 (%)" t:dataTypeName=number

metric m:2011_mwh p:double l:"2011 (MWh)" t:dataTypeName=number

metric m:2011 p:decimal l:"2011 (%)" t:dataTypeName=number

metric m:2012_mwh p:double l:"2012 (MWh)" t:dataTypeName=number

metric m:2012 p:double l:"2012 (%)" t:dataTypeName=number

metric m:2013_mwh p:integer l:"2013 (MWh)" t:dataTypeName=number

metric m:2013 p:float l:"2013 (%)" t:dataTypeName=number

metric m:2014_mwh p:integer l:"2014 (MWh)" t:dataTypeName=number

metric m:2014 p:float l:"2014 (%)" t:dataTypeName=number

entity e:9x8y-nux4 l:"Electricity Generation By Source In Maryland" t:url=https://data.maryland.gov/api/views/9x8y-nux4

property e:9x8y-nux4 t:meta.view v:id=9x8y-nux4 v:category="Energy and Environment" v:averageRating=0 v:name="Electricity Generation By Source In Maryland"

property e:9x8y-nux4 t:meta.view.license v:name="Public Domain"

property e:9x8y-nux4 t:meta.view.owner v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:displayName="Kristen Ahearn"

property e:9x8y-nux4 t:meta.view.tableauthor v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:roleName=publisher v:displayName="Kristen Ahearn"
```

## Top Records

```ls
| :updated_at | energy_source    | 1990_mwh | 1990               | 1991_mwh | 1991               | 1992_mwh | 1992               | 1993_mwh | 1993               | 1994_mwh | 1994               | 1995_mwh | 1995               | 1996_mwh | 1996               | 1997_mwh | 1997               | 1998_mwh | 1998                | 1999_mwh | 1999                | 2000_mwh | 2000                | 2001_mwh | 2001                | 2002_mwh | 2002                | 2003_mwh | 2003                | 2004_mwh | 2004                | 2005_mwh | 2005                | 2006_mwh | 2006                | 2007_mwh | 2007                | 2008_mwh | 2008                | 2009_mwh | 2009                | 2010_mwh | 2010                   | 2011_mwh           | 2011                  | 2012_mwh           | 2012                 | 2013_mwh | 2013 | 2014_mwh | 2014 | 
| =========== | ================ | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | =================== | ======== | ====================== | ================== | ===================== | ================== | ==================== | ======== | ==== | ======== | ==== | 
| 1375802649  | Other Renewables | 520192   | 1.5686249913003598 | 497153   | 1.2475331789377622 | 504655   | 1.2255642718611459 | 478940   | 1.0648343470462642 | 520886   | 1.1488539669654914 | 676336   | 1.4587007884264649 | 733392   | 1.5848688709838483 | 743498   | 1.5918207043698178 | 760693   | 1.5017723426030083  | 785562   | 1.5198849985762966  | 818410   | 1.6001640812914089  | 373015   | 0.76028782972846387 | 521631   | 1.0804491584430924  | 596050   | 1.1408913649003742  | 589208   | 1.1319435808710356  |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                      |                    | 0                     |                    | 0                    |          |      |          |      | 
| 1375802649  | Other Gases      | 488197   | 1.4721449289452009 | 478704   | 1.2012380954962003 | 506572   | 1.2302197428446053 | 475788   | 1.0578264590814046 | 501762   | 1.1066745202837835 | 685721   | 1.4789420692386386 | 539335   | 1.1655093763390845 | 564036   | 1.2075946173492522 | 82316    | 0.16250956976560743 | 59891    | 0.11587555463443112 | 74572    | 0.14580398073100639 | 439980   | 0.89677744681562266 | 504513   | 1.0449928134516542  | 325355   | 0.62275767138186611 | 411565   | 0.79066876189934254 | 342466   | 0.65031448532951852 | 332444   | 0.67905473874375732 | 377560   | 0.75214262836277335 | 337823   | 0.71329434608294306 | 269182   | 0.61492414704980003 | 214727   | 0.49241109216141354    | 154640.24999999997 | 0.36979290635458911   | 177480.1           | 0.46933539565769355  |          |      |          |      | 
| 1441804842  | Solar            |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   | 80       | 0.00018345567801400422 | 2706.02            | 0.0064709349632689128 | 27700.690000000002 | 0.073252800179519378 | 63485    | 0.2  | 112825   | 0.3  | 
| 1441804859  | Petroleum        | 3571272  | 10.76907470689903  | 4078506  | 10.234417886438855 | 2749511  | 6.6772397909249106 | 4164790  | 9.2596388696596872 | 4275226  | 9.4293383768694294 | 1479469  | 3.1908734663725036 | 1472027  | 3.1810679275854401 | 1565010  | 3.3506684894186782 | 3454350  | 6.8196332708079357  | 4290788  | 8.3017054201593119  | 2388595  | 4.6702067713642954  | 3021639  | 6.158774734348178   | 2282432  | 4.7275789468102634  | 3572183  | 6.8374678945456155  | 3296842  | 6.3336532074344323  | 3805569  | 7.2264594021624635  | 580726   | 1.1861990055820144  | 984831   | 1.961895796252618   | 405840   | 0.85690843256469096 | 329900   | 0.75362942585956361 | 322438   | 0.73941352384349368    | 228966.74          | 0.54753064770094184   | 118706.37          | 0.31391181958449743  | 189533   | 0.5  | 492746   | 1.3  | 
| 1441804884  | Wood             |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   | 205984   | 0.39114650489717384 | 218064   | 0.44542055970153982 | 203099   | 0.4045963970702694  | 197704   | 0.41744092438342612 | 175058   | 0.39990560785730067 | 164688   | 0.3776618587596291     | 168432.28          | 0.40277393721964333   | 150959.38          | 0.39920295481318813  | 142789   | 0.4  | 154579   | 0.4  | 
| 1441804920  | Other            | 0        | 0                  | 0        | 0                  | 0        | 0                  | 0        | 0                  | 0        | 0                  | 0        | 0                  | 0        | 0                  | 0        | 0                  | 0        | 0                   | 0        | 0                   | 0        | 0                   | 247700   | 0.50486788848636244 | 255034   | 0.52824941515050994 | 278224   | 0.53254485212321412 | 288616   | 0.55446808009510196 | 293561   | 0.55744795287070481 | 304635   | 0.62225168851657575 | 286550   | 0.57084031718760653 | 285645   | 0.60312342110176709 | 255891   | 0.58456195032624914 | 269906   | 0.61894735287559788    | 298563.39          | 0.7139578713768161    | 296266.32          | 0.78345837374020444  | 302712   | 0.8  | 313218   | 0.8  | 
| 1441804951  | Wind             |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   | 1494     | 0.0034260347869115291  | 270713             | 0.6473589318302958    | 313590.48          | 0.82927106760299352  | 321670   | 0.9  | 323547   | 0.9  | 
| 1441804983  | Other Biomass    |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                  |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   |          | 0                   | 417380   | 0.79256994821919391 | 408095   | 0.83358052366002588 | 400365   | 0.79757279215081511 | 414782   | 0.87578896480398105 | 375721   | 0.85830373298993956 | 407402   | 0.93425262667826692    | 379889.85999999993 | 0.90843474078733044   | 389598.27          | 1.0302690735355846   | 413220   | 1.2  | 433089   | 1.1  | 
| 1441805016  | Hydroelectric    | 2298910  | 6.9323013017314974 | 1407287  | 3.5313821394777594 | 1824659  | 4.4312191075683121 | 1658271  | 3.6868583069084968 | 2009536  | 4.4321855556877434 | 1442006  | 3.1100744143675523 | 2457463  | 5.3106068927593713 | 1588375  | 3.4006926868712615 | 1739737  | 3.4346167376367731  | 1424197  | 2.7554994453873349  | 1732619  | 3.3876354032368128  | 1183518  | 2.4122738540395749  | 1660989  | 3.4403901747274097  | 2646984  | 5.0665568134039969  | 2507521  | 4.8172670769054733  | 1703639  | 3.2350689396094667  | 2104275  | 4.2982213857672864  | 1652216  | 3.2914029157300249  | 1974078  | 4.1681551467091467  | 1888769  | 4.3147374872729376  | 1667396  | 3.8236657962229823     | 2547123.0200000005 | 6.0909628923160595    | 1664318.28         | 4.4011890822922233   | 1727020  | 4.8  | 1622794  | 4.3  | 
| 1441805050  | Natural Gas      | 1522443  | 4.5908859375582356 | 1517463  | 3.8078527944323639 | 1077542  | 2.6168312542822378 | 772304   | 1.717074843532004  | 1172042  | 2.5850283961369063 | 1548884  | 3.3405856142230141 | 987627   | 2.1342737423412927 | 1412585  | 3.0243283098034408 | 1990596  | 3.9298666059713683  | 2125193  | 4.1117683388190311  | 2852876  | 5.5779740027349494  | 1760812  | 3.58892788236354    | 2214431  | 4.5867291445107661  | 1195643  | 2.2885643389037464  | 1183301  | 2.2732718686580586  | 1886986  | 3.5832296619635433  | 1770206  | 3.6158473994195464  | 2240927  | 4.4641824445097598  | 1848147  | 3.9022588924678101  | 1767845  | 4.0384965515571389  | 2896979  | 6.6433405829666485     | 2310660.4799999995 | 5.5255074568095299    | 4964718.0999999996 | 13.128896894876736   | 2887589  | 8.1  | 2612108  | 6.9  | 
```