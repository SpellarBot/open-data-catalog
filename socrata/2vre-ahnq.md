# Maryland Total Residential Sales: 2002-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-residential-sales-2002-2013-c56b8) |
| Metadata | [Link](https://data.maryland.gov/api/views/2vre-ahnq) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/2vre-ahnq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/2vre-ahnq/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 2vre-ahnq |
| Name | Maryland Total Residential Sales: 2002-2015 |
| Attribution | Maryland Department of Planning |
| Tags | residential, sales, planning, mdp |
| Created | 2014-08-28T19:21:55Z |
| Publication Date | 2017-04-14T16:59:00Z |

## Description

Total Residential Sales in Maryland from 2002-2015 based on data extracted from MDProperty View. To browse the MDProperty View, click here: http://planning.maryland.gov/msdc/sale_data/saledata.shtml. Data for 2016 will be available at the end of 2017.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                    | Data Type | Render Type |
| ======== | ============== | ====================== | ======================= | ========= | =========== |
| Yes      | series tag     | jurisdiction           | Jurisdiction            | text      | text        |
| Yes      | numeric metric | residential_sales_2002 | Residential Sales, 2002 | number    | number      |
| Yes      | numeric metric | residential_sales_2003 | Residential Sales, 2003 | number    | number      |
| Yes      | numeric metric | residential_sales_2004 | Residential Sales, 2004 | number    | number      |
| Yes      | numeric metric | residential_sales_2005 | Residential Sales, 2005 | number    | number      |
| Yes      | numeric metric | residential_sales_2006 | Residential Sales, 2006 | number    | number      |
| Yes      | numeric metric | residential_sales_2007 | Residential Sales, 2007 | number    | number      |
| Yes      | numeric metric | residential_sales_2008 | Residential Sales, 2008 | number    | number      |
| Yes      | numeric metric | residential_sales_2009 | Residential Sales, 2009 | number    | number      |
| Yes      | numeric metric | residential_sales_2010 | Residential Sales, 2010 | number    | number      |
| Yes      | numeric metric | residential_sales_2011 | Residential Sales, 2011 | number    | number      |
| Yes      | numeric metric | residential_sales_2012 | Residential Sales, 2012 | number    | number      |
| Yes      | numeric metric | residential_sales_2013 | Residential Sales, 2013 | number    | number      |
| Yes      | numeric metric | residential_sales_2014 | Residential Sales, 2014 | number    | number      |
| Yes      | numeric metric | residential_sales_2015 | Residential Sales, 2015 | number    | number      |
```

## Time Field

```ls
Value = 2002
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2vre-ahnq d:2002-01-01T00:00:00.000Z t:jurisdiction=MARYLAND m:residential_sales_2013=58674 m:residential_sales_2014=59027 m:residential_sales_2011=44435 m:residential_sales_2012=49353 m:residential_sales_2010=45109 m:residential_sales_2002=100945 m:residential_sales_2003=105620 m:residential_sales_2005=130277 m:residential_sales_2004=121374 m:residential_sales_2007=83429 m:residential_sales_2006=109902 m:residential_sales_2009=45849 m:residential_sales_2008=53359 m:residential_sales_2015=65919

series e:2vre-ahnq d:2002-01-01T00:00:00.000Z t:jurisdiction="Allegany County" m:residential_sales_2013=315 m:residential_sales_2014=351 m:residential_sales_2011=348 m:residential_sales_2012=292 m:residential_sales_2010=358 m:residential_sales_2002=592 m:residential_sales_2003=688 m:residential_sales_2005=913 m:residential_sales_2004=673 m:residential_sales_2007=671 m:residential_sales_2006=836 m:residential_sales_2009=412 m:residential_sales_2008=490 m:residential_sales_2015=380

series e:2vre-ahnq d:2002-01-01T00:00:00.000Z t:jurisdiction="Anne Arundel County" m:residential_sales_2013=6745 m:residential_sales_2014=7273 m:residential_sales_2011=4659 m:residential_sales_2012=5637 m:residential_sales_2010=5303 m:residential_sales_2002=11245 m:residential_sales_2003=11862 m:residential_sales_2005=12477 m:residential_sales_2004=12573 m:residential_sales_2007=8109 m:residential_sales_2006=10319 m:residential_sales_2009=5578 m:residential_sales_2008=5778 m:residential_sales_2015=8263
```

## Meta Commands

```ls
metric m:residential_sales_2002 p:integer l:"Residential Sales, 2002" t:dataTypeName=number

metric m:residential_sales_2003 p:integer l:"Residential Sales, 2003" t:dataTypeName=number

metric m:residential_sales_2004 p:integer l:"Residential Sales, 2004" t:dataTypeName=number

metric m:residential_sales_2005 p:integer l:"Residential Sales, 2005" t:dataTypeName=number

metric m:residential_sales_2006 p:integer l:"Residential Sales, 2006" t:dataTypeName=number

metric m:residential_sales_2007 p:integer l:"Residential Sales, 2007" t:dataTypeName=number

metric m:residential_sales_2008 p:integer l:"Residential Sales, 2008" t:dataTypeName=number

metric m:residential_sales_2009 p:integer l:"Residential Sales, 2009" t:dataTypeName=number

metric m:residential_sales_2010 p:integer l:"Residential Sales, 2010" t:dataTypeName=number

metric m:residential_sales_2011 p:integer l:"Residential Sales, 2011" t:dataTypeName=number

metric m:residential_sales_2012 p:integer l:"Residential Sales, 2012" t:dataTypeName=number

metric m:residential_sales_2013 p:integer l:"Residential Sales, 2013" t:dataTypeName=number

metric m:residential_sales_2014 p:integer l:"Residential Sales, 2014" t:dataTypeName=number

metric m:residential_sales_2015 p:integer l:"Residential Sales, 2015" t:dataTypeName=number

entity e:2vre-ahnq l:"Maryland Total Residential Sales: 2002-2015" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/2vre-ahnq

property e:2vre-ahnq t:meta.view v:id=2vre-ahnq v:attributionLink=http://planning.maryland.gov/msdc/sale_data/saledata.shtml v:averageRating=0 v:name="Maryland Total Residential Sales: 2002-2015" v:attribution="Maryland Department of Planning"

property e:2vre-ahnq t:meta.view.owner v:id=n5xi-8ray v:screenName=Laura.Bruner v:displayName=Laura.Bruner

property e:2vre-ahnq t:meta.view.tableauthor v:id=n5xi-8ray v:screenName=Laura.Bruner v:roleName=administrator v:displayName=Laura.Bruner
```

## Top Records

```ls
| jurisdiction        | residential_sales_2002 | residential_sales_2003 | residential_sales_2004 | residential_sales_2005 | residential_sales_2006 | residential_sales_2007 | residential_sales_2008 | residential_sales_2009 | residential_sales_2010 | residential_sales_2011 | residential_sales_2012 | residential_sales_2013 | residential_sales_2014 | residential_sales_2015 | 
| =================== | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | ====================== | 
| MARYLAND            | 100945                 | 105620                 | 121374                 | 130277                 | 109902                 | 83429                  | 53359                  | 45849                  | 45109                  | 44435                  | 49353                  | 58674                  | 59027                  | 65919                  | 
| Allegany County     | 592                    | 688                    | 673                    | 913                    | 836                    | 671                    | 490                    | 412                    | 358                    | 348                    | 292                    | 315                    | 351                    | 380                    | 
| Anne Arundel County | 11245                  | 11862                  | 12573                  | 12477                  | 10319                  | 8109                   | 5778                   | 5578                   | 5303                   | 4659                   | 5637                   | 6745                   | 7273                   | 8263                   | 
| Baltimore City      | 5396                   | 7185                   | 10669                  | 16573                  | 15007                  | 10739                  | 6906                   | 4801                   | 3576                   | 4198                   | 3954                   | 4773                   | 7601                   | 6254                   | 
| Baltimore County    | 13398                  | 13832                  | 15482                  | 15064                  | 13813                  | 11232                  | 7942                   | 7362                   | 6490                   | 6169                   | 6983                   | 7843                   | 5262                   | 8610                   | 
| Calvert County      | 1837                   | 1883                   | 1871                   | 1874                   | 1386                   | 1071                   | 609                    | 648                    | 565                    | 583                    | 679                    | 826                    | 872                    | 1040                   | 
| Caroline County     | 382                    | 435                    | 583                    | 610                    | 652                    | 358                    | 166                    | 128                    | 55                     | 99                     | 105                    | 142                    | 178                    | 214                    | 
| Carroll County      | 3417                   | 3392                   | 3311                   | 3122                   | 2769                   | 2153                   | 1463                   | 1288                   | 1150                   | 1061                   | 1358                   | 1655                   | 1781                   | 2037                   | 
| Cecil County        | 1708                   | 1925                   | 2036                   | 2084                   | 1573                   | 1306                   | 798                    | 721                    | 669                    | 601                    | 667                    | 770                    | 819                    | 754                    | 
| Charles County      | 3288                   | 3458                   | 3709                   | 4066                   | 3580                   | 2685                   | 1411                   | 1147                   | 1264                   | 1319                   | 1359                   | 1677                   | 1707                   | 2031                   | 
```