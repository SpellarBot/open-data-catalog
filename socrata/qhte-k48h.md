# WAOFM - April 1 - Population Density by County, 2000 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/waofm-april-1-population-density-by-county-2000-to-present-e7e7b) |
| Metadata | [Link](https://data.wa.gov/api/views/qhte-k48h) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qhte-k48h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qhte-k48h/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qhte-k48h |
| Name | WAOFM - April 1 - Population Density by County, 2000 to Present |
| Attribution | Washington State Office of Financial Management, Forecasting and Research Division |
| Category | Demographics |
| Tags | wa, washington, ofm, state, county, city, population, density, intercensal, postcensal |
| Created | 2014-06-30T22:38:29Z |
| Publication Date | 2016-06-30T18:13:52Z |

## Description

Intercensal and postcensal housing estimates of population density for the state, counties, and cities, 1990 to present.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | county      | COUNTY      | text      | text        |
| Yes      | numeric metric | popden_2000 | POPDEN_2000 | number    | number      |
| Yes      | numeric metric | popden_2001 | POPDEN_2001 | number    | number      |
| Yes      | numeric metric | popden_2002 | POPDEN_2002 | number    | number      |
| Yes      | numeric metric | popden_2003 | POPDEN_2003 | number    | number      |
| Yes      | numeric metric | popden_2004 | POPDEN_2004 | number    | number      |
| Yes      | numeric metric | popden_2005 | POPDEN_2005 | number    | number      |
| Yes      | numeric metric | popden_2006 | POPDEN_2006 | number    | number      |
| Yes      | numeric metric | popden_2007 | POPDEN_2007 | number    | number      |
| Yes      | numeric metric | popden_2008 | POPDEN_2008 | number    | number      |
| Yes      | numeric metric | popden_2009 | POPDEN_2009 | number    | number      |
| Yes      | numeric metric | popden_2010 | POPDEN_2010 | number    | number      |
| Yes      | numeric metric | popden_2011 | POPDEN_2011 | number    | number      |
| Yes      | numeric metric | popden_2012 | POPDEN_2012 | number    | number      |
| Yes      | numeric metric | popden_2013 | POPDEN_2013 | number    | number      |
| Yes      | numeric metric | popden_2014 | POPDEN_2014 | number    | number      |
| Yes      | numeric metric | popden_2015 | POPDEN_2015 | number    | number      |
| Yes      | numeric metric | popden_2016 | POPDEN_2016 | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qhte-k48h d:2000-01-01T00:00:00.000Z t:county=Adams m:popden_2009=9.57 m:popden_2008=9.46 m:popden_2007=9.33 m:popden_2002=8.79 m:popden_2011=9.84 m:popden_2010=9.73 m:popden_2001=8.67 m:popden_2000=8.53 m:popden_2013=9.97 m:popden_2012=9.9 m:popden_2006=9.19 m:popden_2015=10.08 m:popden_2005=9.17 m:popden_2014=10.08 m:popden_2004=9.09 m:popden_2003=8.87 m:popden_2016=10.14

series e:qhte-k48h d:2000-01-01T00:00:00.000Z t:county=Asotin m:popden_2009=33.99 m:popden_2008=33.87 m:popden_2007=33.7 m:popden_2002=32.51 m:popden_2011=34.03 m:popden_2010=33.99 m:popden_2001=32.5 m:popden_2000=32.35 m:popden_2013=34.27 m:popden_2012=34.11 m:popden_2006=33.33 m:popden_2015=34.6 m:popden_2005=32.96 m:popden_2014=34.5 m:popden_2004=32.71 m:popden_2003=32.6 m:popden_2016=34.82

series e:qhte-k48h d:2000-01-01T00:00:00.000Z t:county=Benton m:popden_2009=100.64 m:popden_2008=98.41 m:popden_2007=96.94 m:popden_2002=87.07 m:popden_2011=104.62 m:popden_2010=103.02 m:popden_2001=85.3 m:popden_2000=83.66 m:popden_2013=107.86 m:popden_2012=105.86 m:popden_2006=95.27 m:popden_2015=110.91 m:popden_2005=93.53 m:popden_2014=109.68 m:popden_2004=91.52 m:popden_2003=89.21 m:popden_2016=112.03
```

## Meta Commands

```ls
metric m:popden_2000 p:float l:POPDEN_2000 d:"Population density 2000" t:dataTypeName=number

metric m:popden_2001 p:float l:POPDEN_2001 d:"Population density 2001" t:dataTypeName=number

metric m:popden_2002 p:float l:POPDEN_2002 d:"Population density 2002" t:dataTypeName=number

metric m:popden_2003 p:float l:POPDEN_2003 d:"Population density 2003" t:dataTypeName=number

metric m:popden_2004 p:float l:POPDEN_2004 d:"Population density 2004" t:dataTypeName=number

metric m:popden_2005 p:float l:POPDEN_2005 d:"Population density 2005" t:dataTypeName=number

metric m:popden_2006 p:float l:POPDEN_2006 d:"Population density 2006" t:dataTypeName=number

metric m:popden_2007 p:float l:POPDEN_2007 d:"Population density 2007" t:dataTypeName=number

metric m:popden_2008 p:float l:POPDEN_2008 d:"Population density 2008" t:dataTypeName=number

metric m:popden_2009 p:float l:POPDEN_2009 d:"Population density 2009" t:dataTypeName=number

metric m:popden_2010 p:float l:POPDEN_2010 d:"Population density 2010" t:dataTypeName=number

metric m:popden_2011 p:float l:POPDEN_2011 d:"Population density 2011" t:dataTypeName=number

metric m:popden_2012 p:float l:POPDEN_2012 d:"Population density 2012" t:dataTypeName=number

metric m:popden_2013 p:float l:POPDEN_2013 d:"Population density 2013" t:dataTypeName=number

metric m:popden_2014 p:float l:POPDEN_2014 d:"Population density 2014" t:dataTypeName=number

metric m:popden_2015 p:float l:POPDEN_2015 d:"Population density 2015" t:dataTypeName=number

metric m:popden_2016 p:float l:POPDEN_2016 d:"Population density 2016" t:dataTypeName=number

entity e:qhte-k48h l:"WAOFM - April 1 - Population Density by County, 2000 to Present" t:attribution="Washington State Office of Financial Management, Forecasting and Research Division" t:url=https://data.wa.gov/api/views/qhte-k48h

property e:qhte-k48h t:meta.view v:id=qhte-k48h v:category=Demographics v:attributionLink=http://www.ofm.wa.gov/pop/popden/default.asp v:averageRating=0 v:name="WAOFM - April 1 - Population Density by County, 2000 to Present" v:attribution="Washington State Office of Financial Management, Forecasting and Research Division"

property e:qhte-k48h t:meta.view.license v:name="Public Domain"

property e:qhte-k48h t:meta.view.owner v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:displayName="Thomas Kimpel"

property e:qhte-k48h t:meta.view.tableauthor v:id=qav9-tahu v:profileImageUrlMedium=/api/users/qav9-tahu/profile_images/THUMB v:profileImageUrlLarge=/api/users/qav9-tahu/profile_images/LARGE v:screenName="Thomas Kimpel" v:profileImageUrlSmall=/api/users/qav9-tahu/profile_images/TINY v:roleName=administrator v:displayName="Thomas Kimpel"
```

## Top Records

```ls
| county   | popden_2000 | popden_2001 | popden_2002 | popden_2003 | popden_2004 | popden_2005 | popden_2006 | popden_2007 | popden_2008 | popden_2009 | popden_2010 | popden_2011 | popden_2012 | popden_2013 | popden_2014 | popden_2015 | popden_2016 | 
| ======== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | 
| Adams    | 8.53        | 8.67        | 8.79        | 8.87        | 9.09        | 9.17        | 9.19        | 9.33        | 9.46        | 9.57        | 9.73        | 9.84        | 9.90        | 9.97        | 10.08       | 10.08       | 10.14       | 
| Asotin   | 32.35       | 32.50       | 32.51       | 32.60       | 32.71       | 32.96       | 33.33       | 33.70       | 33.87       | 33.99       | 33.99       | 34.03       | 34.11       | 34.27       | 34.5        | 34.60       | 34.82       | 
| Benton   | 83.66       | 85.30       | 87.07       | 89.21       | 91.52       | 93.53       | 95.27       | 96.94       | 98.41       | 100.64      | 103.02      | 104.62      | 105.86      | 107.86      | 109.68      | 110.91      | 112.03      | 
| Chelan   | 22.80       | 22.90       | 23.07       | 23.11       | 23.28       | 23.61       | 23.93       | 24.23       | 24.58       | 24.71       | 24.81       | 24.89       | 25.06       | 25.20       | 25.44       | 25.69       | 25.99       | 
| Clallam  | 36.90       | 37.21       | 37.60       | 37.90       | 38.36       | 38.90       | 39.64       | 40.15       | 40.60       | 40.83       | 41.08       | 41.19       | 41.42       | 41.62       | 41.71       | 41.79       | 42.23       | 
| Clark    | 549.55      | 561.45      | 580.78      | 595.48      | 613.43      | 628.12      | 644.26      | 656.92      | 667.11      | 674.56      | 676.25      | 680.45      | 685.61      | 692.37      | 703.97      | 718.31      | 732.93      | 
| Columbia | 4.68        | 4.74        | 4.74        | 4.73        | 4.74        | 4.76        | 4.75        | 4.71        | 4.72        | 4.72        | 4.69        | 4.72        | 4.72        | 4.72        | 4.7         | 4.71        | 4.66        | 
| Cowlitz  | 81.63       | 82.63       | 83.30       | 84.18       | 84.83       | 85.78       | 87.03       | 88.16       | 89.18       | 89.73       | 89.82       | 90.08       | 90.38       | 90.60       | 90.95       | 91.46       | 91.96       | 
| Douglas  | 17.91       | 18.03       | 18.06       | 18.43       | 18.65       | 18.93       | 19.50       | 19.96       | 20.45       | 20.89       | 21.12       | 21.24       | 21.38       | 21.59       | 21.82       | 21.98       | 22.38       | 
| Ferry    | 3.29        | 3.33        | 3.35        | 3.36        | 3.34        | 3.36        | 3.39        | 3.40        | 3.42        | 3.43        | 3.43        | 3.45        | 3.47        | 3.47        | 3.48        | 3.50        | 3.49        | 
```