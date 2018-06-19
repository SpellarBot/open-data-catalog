# WAOFM - SAEP - State Legislative District Population Estimates, 2000-2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-saep-state-legislative-district-population-estimates-2000-2014-93b38) |
| Metadata | [Link](https://data.wa.gov/api/views/ryk4-3vjy) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ryk4-3vjy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ryk4-3vjy/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ryk4-3vjy |
| Name | WAOFM - SAEP - State Legislative District Population Estimates, 2000-2016 |
| Attribution | Washington State Office of Financial Management, Forecasting and Research Division |
| Category | Demographics |
| Tags | wa, washington, ofm, legislative district, population, intercensal, postcensal |
| Created | 2014-10-08T20:37:34Z |
| Publication Date | 2016-09-24T00:11:56Z |

## Description

Small Area Estimate Program (SAEP) April 1 population estimates for state legislative districts, 2000-present.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type | Render Type |
| ======== | ============== | ========================================= | ========================================= | ========= | =========== |
| Yes      | series tag     | legislative_district                      | Legislative District                      | text      | text        |
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
| Yes      | numeric metric | estimated_total_population_2016           | Estimated Total Population 2016           | number    | number      |
| Yes      | numeric metric | numeric_change_in_population_2000_to_2010 | Numeric Change in Population 2000 to 2010 | number    | number      |
| Yes      | numeric metric | percent_change_in_population_2000_to_2010 | Percent Change in Population 2000 to 2010 | percent   | percent     |
| Yes      | numeric metric | numeric_change_in_population_2010_to_2015 | Numeric Change in Population 2010 to 2016 | number    | number      |
| Yes      | numeric metric | percent_change_in_population_2010_to_2014 | Percent Change in Population 2010 to 2016 | percent   | percent     |
| Yes      | series tag     | saep_version                              | SAEP Version                              | text      | text        |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ryk4-3vjy d:2000-01-01T00:00:00.000Z t:saep_version="September 21, 2016" t:legislative_district=1 m:percent_change_in_population_2000_to_2010=14.17 m:numeric_change_in_population_2000_to_2010=17030 m:numeric_change_in_population_2010_to_2015=17955 m:estimated_total_population_2007=133197 m:estimated_total_population_2006=131024 m:estimated_total_population_2009=135924 m:estimated_total_population_2008=134815 m:estimated_total_population_2016=155191 m:percent_change_in_population_2010_to_2014=13.08 m:estimated_total_population_2015=151647 m:estimated_total_population_2001=122039 m:estimated_total_population_2014=146969 m:estimated_total_population_2000=120206 m:estimated_total_population_2013=142644 m:estimated_total_population_2003=125396 m:estimated_total_population_2012=140013 m:estimated_total_population_2002=123892 m:estimated_total_population_2011=138300 m:estimated_total_population_2010=137236 m:estimated_total_population_2005=128541 m:estimated_total_population_2004=126698

series e:ryk4-3vjy d:2000-01-01T00:00:00.000Z t:saep_version="September 21, 2016" t:legislative_district=2 m:percent_change_in_population_2000_to_2010=38.69 m:numeric_change_in_population_2000_to_2010=38271 m:numeric_change_in_population_2010_to_2015=12340 m:estimated_total_population_2007=127888 m:estimated_total_population_2006=123476 m:estimated_total_population_2009=134862 m:estimated_total_population_2008=131716 m:estimated_total_population_2016=149542 m:percent_change_in_population_2010_to_2014=8.99 m:estimated_total_population_2015=146185 m:estimated_total_population_2001=102329 m:estimated_total_population_2014=143968 m:estimated_total_population_2000=98931 m:estimated_total_population_2013=142354 m:estimated_total_population_2003=110155 m:estimated_total_population_2012=140416 m:estimated_total_population_2002=106273 m:estimated_total_population_2011=138684 m:estimated_total_population_2010=137202 m:estimated_total_population_2005=118812 m:estimated_total_population_2004=114263

series e:ryk4-3vjy d:2000-01-01T00:00:00.000Z t:saep_version="September 21, 2016" t:legislative_district=3 m:percent_change_in_population_2000_to_2010=0.98 m:numeric_change_in_population_2000_to_2010=1335 m:numeric_change_in_population_2010_to_2015=2547 m:estimated_total_population_2007=136464 m:estimated_total_population_2006=135732 m:estimated_total_population_2009=137249 m:estimated_total_population_2008=136881 m:estimated_total_population_2016=139773 m:percent_change_in_population_2010_to_2014=1.86 m:estimated_total_population_2015=138802 m:estimated_total_population_2001=135979 m:estimated_total_population_2014=138367 m:estimated_total_population_2000=135891 m:estimated_total_population_2013=137884 m:estimated_total_population_2003=134710 m:estimated_total_population_2012=137234 m:estimated_total_population_2002=136208 m:estimated_total_population_2011=137374 m:estimated_total_population_2010=137226 m:estimated_total_population_2005=134613 m:estimated_total_population_2004=134143
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

metric m:estimated_total_population_2016 p:integer l:"Estimated Total Population 2016" t:dataTypeName=number

metric m:numeric_change_in_population_2000_to_2010 p:integer l:"Numeric Change in Population 2000 to 2010" t:dataTypeName=number

metric m:percent_change_in_population_2000_to_2010 p:float l:"Percent Change in Population 2000 to 2010" t:dataTypeName=percent

metric m:numeric_change_in_population_2010_to_2015 p:integer l:"Numeric Change in Population 2010 to 2016" t:dataTypeName=number

metric m:percent_change_in_population_2010_to_2014 p:float l:"Percent Change in Population 2010 to 2016" t:dataTypeName=percent

entity e:ryk4-3vjy l:"WAOFM - SAEP - State Legislative District Population Estimates, 2000-2016" t:attribution="Washington State Office of Financial Management, Forecasting and Research Division" t:url=https://data.wa.gov/api/views/ryk4-3vjy

property e:ryk4-3vjy t:meta.view v:id=ryk4-3vjy v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/smallarea/default.asp v:averageRating=0 v:name="WAOFM - SAEP - State Legislative District Population Estimates, 2000-2016" v:attribution="Washington State Office of Financial Management, Forecasting and Research Division"

property e:ryk4-3vjy t:meta.view.license v:name="Public Domain"

property e:ryk4-3vjy t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:ryk4-3vjy t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| legislative_district | estimated_total_population_2000 | estimated_total_population_2001 | estimated_total_population_2002 | estimated_total_population_2003 | estimated_total_population_2004 | estimated_total_population_2005 | estimated_total_population_2006 | estimated_total_population_2007 | estimated_total_population_2008 | estimated_total_population_2009 | estimated_total_population_2010 | estimated_total_population_2011 | estimated_total_population_2012 | estimated_total_population_2013 | estimated_total_population_2014 | estimated_total_population_2015 | estimated_total_population_2016 | numeric_change_in_population_2000_to_2010 | percent_change_in_population_2000_to_2010 | numeric_change_in_population_2010_to_2015 | percent_change_in_population_2010_to_2014 | saep_version       | 
| ==================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | =============================== | ========================================= | ========================================= | ========================================= | ========================================= | ================== | 
| 1                    | 120206                          | 122039                          | 123892                          | 125396                          | 126698                          | 128541                          | 131024                          | 133197                          | 134815                          | 135924                          | 137236                          | 138300                          | 140013                          | 142644                          | 146969                          | 151647                          | 155191                          | 17030                                     | 14.17                                     | 17955                                     | 13.08                                     | September 21, 2016 | 
| 2                    | 98931                           | 102329                          | 106273                          | 110155                          | 114263                          | 118812                          | 123476                          | 127888                          | 131716                          | 134862                          | 137202                          | 138684                          | 140416                          | 142354                          | 143968                          | 146185                          | 149542                          | 38271                                     | 38.69                                     | 12340                                     | 8.99                                      | September 21, 2016 | 
| 3                    | 135891                          | 135979                          | 136208                          | 134710                          | 134143                          | 134613                          | 135732                          | 136464                          | 136881                          | 137249                          | 137226                          | 137374                          | 137234                          | 137884                          | 138367                          | 138802                          | 139773                          | 1335                                      | 0.98                                      | 2547                                      | 1.86                                      | September 21, 2016 | 
| 4                    | 116892                          | 118892                          | 121015                          | 121582                          | 122956                          | 125277                          | 128219                          | 130818                          | 133128                          | 135397                          | 137281                          | 137902                          | 139594                          | 141391                          | 143229                          | 145115                          | 146700                          | 20389                                     | 17.44                                     | 9419                                      | 6.86                                      | September 21, 2016 | 
| 5                    | 105968                          | 109032                          | 112320                          | 114877                          | 117555                          | 120320                          | 124151                          | 127709                          | 130873                          | 133902                          | 137210                          | 138399                          | 140470                          | 143248                          | 146386                          | 148332                          | 150939                          | 31242                                     | 29.48                                     | 13729                                     | 10.01                                     | September 21, 2016 | 
| 6                    | 115090                          | 117262                          | 119556                          | 120310                          | 121860                          | 124348                          | 127454                          | 130221                          | 132701                          | 135142                          | 137198                          | 137620                          | 138543                          | 140119                          | 141665                          | 142768                          | 143942                          | 22108                                     | 19.21                                     | 6744                                      | 4.92                                      | September 21, 2016 | 
| 7                    | 123256                          | 124723                          | 126075                          | 126822                          | 127889                          | 129508                          | 131613                          | 133174                          | 134895                          | 136355                          | 137263                          | 137642                          | 138351                          | 138836                          | 139679                          | 140390                          | 140908                          | 14007                                     | 11.36                                     | 3645                                      | 2.66                                      | September 21, 2016 | 
| 8                    | 109556                          | 111952                          | 114525                          | 117577                          | 120861                          | 123736                          | 126267                          | 128698                          | 130862                          | 134043                          | 137202                          | 139374                          | 141053                          | 144092                          | 146869                          | 148787                          | 150253                          | 27646                                     | 25.23                                     | 13051                                     | 9.51                                      | September 21, 2016 | 
| 9                    | 106168                          | 107970                          | 110519                          | 112808                          | 116652                          | 120664                          | 124155                          | 127161                          | 131063                          | 133663                          | 137223                          | 139899                          | 143181                          | 145680                          | 147675                          | 149186                          | 151406                          | 31055                                     | 29.25                                     | 14183                                     | 10.34                                     | September 21, 2016 | 
| 10                   | 122283                          | 123598                          | 125573                          | 126691                          | 128454                          | 130752                          | 133145                          | 135178                          | 136306                          | 137083                          | 137233                          | 137696                          | 138661                          | 139426                          | 140521                          | 142037                          | 145282                          | 14950                                     | 12.23                                     | 8049                                      | 5.87                                      | September 21, 2016 | 
```