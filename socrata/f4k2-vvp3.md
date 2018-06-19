# WAOFM - SAEP - Congressional District Population Estimates, 2000-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-saep-congressional-district-population-estimates-2000-2014-f4325) |
| Metadata | [Link](https://data.wa.gov/api/views/f4k2-vvp3) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/f4k2-vvp3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/f4k2-vvp3/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | f4k2-vvp3 |
| Name | WAOFM - SAEP - Congressional District Population Estimates, 2000-2016 |
| Attribution | Washington State Office of Financial Management, Forecasting and Research Division |
| Category | Demographics |
| Tags | wa, washington, ofm, congressional district, population, intercensal, postcensal |
| Created | 2014-10-08T20:30:11Z |
| Publication Date | 2015-09-17T18:31:14Z |

## Description

Small Area Estimate Program (SAEP) April 1 population estimates for congressional districts, 2000-present.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| Yes      | series tag     | congressional_district                    | Congressional District                    | text      | text        |
| Yes      | numeric metric | estimated_total_population_2000           | Estimated Total Population 2000           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2001           | Estimated Total Population 2001           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2002           | Estimated Total Population 2002           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2003           | Estimated Total Population 2003           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2004           | Estimated Total Population 2004           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2005           | Estimated Total Population 2005           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2006           | Estimated Total Population 2006           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2007           | Estimated Total Population 2007           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2008           | Estimated Total Population 2008           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2009           | Estimated Total Population 2009           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2010           | Estimated Total Population 2010           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2011           | Estimated Total Population 2011           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2012           | Estimated Total Population 2012           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2013           | Estimated Total Population 2013           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2014           | Estimated Total Population 2014           | number    | number      |
| Yes      | numeric metric | estimated_total_population_2015           | Estimated Total Population 2015           | number    | number      |
| Yes      | numeric metric | numeric_change_in_population_2000_to_2010 | Numeric Change in Population 2000 to 2010 | number    | number      |
| Yes      | numeric metric | percent_change_in_population_2000_to_2010 | Percent Change in Population 2000 to 2010 | percent   | percent     |
| Yes      | numeric metric | numeric_change_in_population_2010_to_2015 | Numeric Change in Population 2010 to 2015 | number    | number      |
| Yes      | numeric metric | percent_change_in_population_2010_to_2015 | Percent Change in Population 2010 to 2015 | percent   | percent     |
| Yes      | series tag     | saep_version                              | SAEP Version                              | text      | text        |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:f4k2-vvp3 d:2000-01-01T00:00:00.000Z t:saep_version="September 8, 2015" t:congressional_district=1 m:percent_change_in_population_2000_to_2010=17.83 m:numeric_change_in_population_2000_to_2010=101772 m:numeric_change_in_population_2010_to_2015=40189 m:estimated_total_population_2007=647317 m:estimated_total_population_2006=634305 m:estimated_total_population_2009=664594 m:estimated_total_population_2008=656859 m:estimated_total_population_2015=712633 m:percent_change_in_population_2010_to_2015=5.98 m:estimated_total_population_2001=581412 m:estimated_total_population_2014=701958 m:estimated_total_population_2000=570672 m:estimated_total_population_2013=691019 m:estimated_total_population_2003=600021 m:estimated_total_population_2012=683651 m:estimated_total_population_2002=592190 m:estimated_total_population_2011=677483 m:estimated_total_population_2010=672444 m:estimated_total_population_2005=620049 m:estimated_total_population_2004=609243

series e:f4k2-vvp3 d:2000-01-01T00:00:00.000Z t:saep_version="September 8, 2015" t:congressional_district=2 m:percent_change_in_population_2000_to_2010=15.36 m:numeric_change_in_population_2000_to_2010=89527 m:numeric_change_in_population_2010_to_2015=34659 m:estimated_total_population_2007=655216 m:estimated_total_population_2006=643475 m:estimated_total_population_2009=668092 m:estimated_total_population_2008=662916 m:estimated_total_population_2015=707113 m:percent_change_in_population_2010_to_2015=5.15 m:estimated_total_population_2001=592777 m:estimated_total_population_2014=693917 m:estimated_total_population_2000=582927 m:estimated_total_population_2013=685792 m:estimated_total_population_2003=610121 m:estimated_total_population_2012=680005 m:estimated_total_population_2002=602664 m:estimated_total_population_2011=675244 m:estimated_total_population_2010=672454 m:estimated_total_population_2005=630340 m:estimated_total_population_2004=618851

series e:f4k2-vvp3 d:2000-01-01T00:00:00.000Z t:saep_version="September 8, 2015" t:congressional_district=3 m:percent_change_in_population_2000_to_2010=17.95 m:numeric_change_in_population_2000_to_2010=102326 m:numeric_change_in_population_2010_to_2015=30996 m:estimated_total_population_2007=654792 m:estimated_total_population_2006=643996 m:estimated_total_population_2009=670070 m:estimated_total_population_2008=663718 m:estimated_total_population_2015=703444 m:percent_change_in_population_2010_to_2015=4.61 m:estimated_total_population_2001=579933 m:estimated_total_population_2014=693131 m:estimated_total_population_2000=570122 m:estimated_total_population_2013=684939 m:estimated_total_population_2003=604815 m:estimated_total_population_2012=680347 m:estimated_total_population_2002=593995 m:estimated_total_population_2011=676133 m:estimated_total_population_2010=672448 m:estimated_total_population_2005=630045 m:estimated_total_population_2004=618214
```

## Meta Commands

```ls
metric m:estimated_total_population_2000 p:integer l:"Estimated Total Population 2000" t:dataTypeName=number

metric m:estimated_total_population_2001 p:integer l:"Estimated Total Population 2001" t:dataTypeName=number

metric m:estimated_total_population_2002 p:integer l:"Estimated Total Population 2002" t:dataTypeName=number

metric m:estimated_total_population_2003 p:integer l:"Estimated Total Population 2003" t:dataTypeName=number

metric m:estimated_total_population_2004 p:integer l:"Estimated Total Population 2004" t:dataTypeName=number

metric m:estimated_total_population_2005 p:integer l:"Estimated Total Population 2005" t:dataTypeName=number

metric m:estimated_total_population_2006 p:integer l:"Estimated Total Population 2006" t:dataTypeName=number

metric m:estimated_total_population_2007 p:integer l:"Estimated Total Population 2007" t:dataTypeName=number

metric m:estimated_total_population_2008 p:integer l:"Estimated Total Population 2008" t:dataTypeName=number

metric m:estimated_total_population_2009 p:integer l:"Estimated Total Population 2009" t:dataTypeName=number

metric m:estimated_total_population_2010 p:integer l:"Estimated Total Population 2010" t:dataTypeName=number

metric m:estimated_total_population_2011 p:integer l:"Estimated Total Population 2011" t:dataTypeName=number

metric m:estimated_total_population_2012 p:integer l:"Estimated Total Population 2012" t:dataTypeName=number

metric m:estimated_total_population_2013 p:integer l:"Estimated Total Population 2013" t:dataTypeName=number

metric m:estimated_total_population_2014 p:integer l:"Estimated Total Population 2014" t:dataTypeName=number

metric m:estimated_total_population_2015 p:integer l:"Estimated Total Population 2015" t:dataTypeName=number

metric m:numeric_change_in_population_2000_to_2010 p:integer l:"Numeric Change in Population 2000 to 2010" t:dataTypeName=number

metric m:percent_change_in_population_2000_to_2010 p:float l:"Percent Change in Population 2000 to 2010" t:dataTypeName=percent

metric m:numeric_change_in_population_2010_to_2015 p:integer l:"Numeric Change in Population 2010 to 2015" t:dataTypeName=number

metric m:percent_change_in_population_2010_to_2015 p:float l:"Percent Change in Population 2010 to 2015" t:dataTypeName=percent

entity e:f4k2-vvp3 l:"WAOFM - SAEP - Congressional District Population Estimates, 2000-2016" t:attribution="Washington State Office of Financial Management, Forecasting and Research Division" t:url=https://data.wa.gov/api/views/f4k2-vvp3

property e:f4k2-vvp3 t:meta.view v:id=f4k2-vvp3 v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/smallarea/default.asp v:averageRating=0 v:name="WAOFM - SAEP - Congressional District Population Estimates, 2000-2016" v:attribution="Washington State Office of Financial Management, Forecasting and Research Division"

property e:f4k2-vvp3 t:meta.view.license v:name="Public Domain"

property e:f4k2-vvp3 t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:f4k2-vvp3 t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| congressional_district | estimated_total_population_2000 | estimated_total_population_2001 | estimated_total_population_2002 | estimated_total_population_2003 | estimated_total_population_2004 | estimated_total_population_2005 | estimated_total_population_2006 | estimated_total_population_2007 | estimated_total_population_2008 | estimated_total_population_2009 | estimated_total_population_2010 | estimated_total_population_2011 | estimated_total_population_2012 | estimated_total_population_2013 | estimated_total_population_2014 | estimated_total_population_2015 | numeric_change_in_population_2000_to_2010 | percent_change_in_population_2000_to_2010 | numeric_change_in_population_2010_to_2015 | percent_change_in_population_2010_to_2015 | saep_version      | 
| ====================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | ========================================= | ========================================= | ========================================= | ========================================= | ================= | 
| 1                      | 570672                          | 581412                          | 592190                          | 600021                          | 609243                          | 620049                          | 634305                          | 647317                          | 656859                          | 664594                          | 672444                          | 677483                          | 683651                          | 691019                          | 701958                          | 712633                          | 101772                                    | 17.83                                     | 40189                                     | 5.98                                      | September 8, 2015 | 
| 2                      | 582927                          | 592777                          | 602664                          | 610121                          | 618851                          | 630340                          | 643475                          | 655216                          | 662916                          | 668092                          | 672454                          | 675244                          | 680005                          | 685792                          | 693917                          | 707113                          | 89527                                     | 15.36                                     | 34659                                     | 5.15                                      | September 8, 2015 | 
| 3                      | 570122                          | 579933                          | 593995                          | 604815                          | 618214                          | 630045                          | 643996                          | 654792                          | 663718                          | 670070                          | 672448                          | 676133                          | 680347                          | 684939                          | 693131                          | 703444                          | 102326                                    | 17.95                                     | 30996                                     | 4.61                                      | September 8, 2015 | 
| 4                      | 567851                          | 575327                          | 582246                          | 592860                          | 604908                          | 616040                          | 628080                          | 639197                          | 650208                          | 661951                          | 672456                          | 680447                          | 687280                          | 695533                          | 703851                          | 709009                          | 104605                                    | 18.42                                     | 36553                                     | 5.44                                      | September 8, 2015 | 
| 5                      | 605331                          | 610933                          | 617271                          | 618404                          | 623356                          | 632197                          | 642319                          | 650915                          | 659716                          | 666548                          | 672455                          | 674086                          | 678812                          | 683884                          | 689812                          | 695281                          | 67124                                     | 11.09                                     | 22826                                     | 3.39                                      | September 8, 2015 | 
| 6                      | 618420                          | 623976                          | 630802                          | 636651                          | 642353                          | 646809                          | 657677                          | 666082                          | 671469                          | 673358                          | 672448                          | 676598                          | 679283                          | 680930                          | 684466                          | 689278                          | 54028                                     | 8.74                                      | 16830                                     | 2.50                                      | September 8, 2015 | 
| 7                      | 633112                          | 636795                          | 641655                          | 642617                          | 644192                          | 646544                          | 654335                          | 660564                          | 664647                          | 667875                          | 672457                          | 675089                          | 679029                          | 688645                          | 702345                          | 723611                          | 39345                                     | 6.21                                      | 51154                                     | 7.61                                      | September 8, 2015 | 
| 8                      | 556185                          | 566813                          | 578850                          | 588818                          | 599945                          | 611711                          | 627165                          | 641339                          | 653579                          | 663374                          | 672463                          | 676200                          | 682188                          | 692032                          | 702968                          | 712102                          | 116278                                    | 20.91                                     | 39639                                     | 5.90                                      | September 8, 2015 | 
| 9                      | 609248                          | 615209                          | 622482                          | 625850                          | 629968                          | 634643                          | 644828                          | 653429                          | 659896                          | 665570                          | 672460                          | 676558                          | 680873                          | 687686                          | 696127                          | 702882                          | 63212                                     | 10.38                                     | 30422                                     | 4.52                                      | September 8, 2015 | 
| 10                     | 580272                          | 587154                          | 597162                          | 606728                          | 617486                          | 630440                          | 644077                          | 656235                          | 665238                          | 670727                          | 672455                          | 680061                          | 686303                          | 691941                          | 699596                          | 706057                          | 92183                                     | 15.89                                     | 33602                                     | 5.00                                      | September 8, 2015 | 
```