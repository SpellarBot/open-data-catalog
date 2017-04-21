# Public Health Statistics - Asthma hospitalizations in Chicago, by year, 2000 - 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-statistics-asthma-hospitalizations-in-chicago-by-year-2000-2011-dcdbb) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/vazh-t57q) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/vazh-t57q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/vazh-t57q/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | vazh-t57q |
| Name | Public Health Statistics - Asthma hospitalizations in Chicago, by year, 2000 - 2011 |
| Attribution | Illinois Department of Public Health (IDPH) |
| Category | Health & Human Services |
| Tags | asthma, chronic, hospitalization, respiratory, sustainability |
| Created | 2012-01-10T16:19:21Z |
| Publication Date | 2012-09-17T17:01:24Z |

## Description

This dataset contains the annual number of hospital discharges, crude hospitalization rates with corresponding 95% confidence intervals, and age-adjusted hospitalization rates (per 10,000 children and adults aged 5 to 64 years) with corresponding 95% confidence intervals, for the years 2000 ? 2011, by Chicago U.S. Postal Service ZIP code or ZIP code aggregate. See the full dataset description for more information at http://bit.ly/PKI8p0.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                | Data Type | Render Type |
| ======== | ============== | ================================== | =================================== | ========= | =========== |
| Yes      | series tag     | zip_code_or_aggregate_             | ZIP code (or aggregate)             | text      | text        |
| Yes      | numeric metric | hospitalizations_2000              | Hospitalizations 2000               | number    | number      |
| Yes      | numeric metric | crude_rate_2000                    | Crude Rate 2000                     | number    | number      |
| Yes      | numeric metric | crude_rate_2000_lower_ci           | Crude Rate 2000 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2000_upper_ci           | Crude Rate 2000 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2000_ages_5_64_only_ | Adjusted Rate 2000 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2000_lower_ci        | Adjusted Rate 2000 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2000_upper_ci        | Adjusted Rate 2000 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2001              | Hospitalizations 2001               | number    | number      |
| Yes      | numeric metric | crude_rate_2001                    | Crude Rate 2001                     | number    | number      |
| Yes      | numeric metric | crude_rate_2001_lower_ci           | Crude Rate 2001 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2001_upper_ci           | Crude Rate 2001 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2001_ages_5_64_only_ | Adjusted Rate 2001 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2001_lower_ci        | Adjusted Rate 2001 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2001_upper_ci        | Adjusted Rate 2001 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2002              | Hospitalizations 2002               | number    | number      |
| Yes      | numeric metric | crude_rate_2002                    | Crude Rate 2002                     | number    | number      |
| Yes      | numeric metric | crude_rate_2002_lower_ci           | Crude Rate 2002 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2002_upper_ci           | Crude Rate 2002 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2002_ages_5_64_only_ | Adjusted Rate 2002 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2002_lower_ci        | Adjusted Rate 2002 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2002_upper_ci        | Adjusted Rate 2002 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2003              | Hospitalizations 2003               | number    | number      |
| Yes      | numeric metric | crude_rate_2003                    | Crude Rate 2003                     | number    | number      |
| Yes      | numeric metric | crude_rate_2003_lower_ci           | Crude Rate 2003 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2003_upper_ci           | Crude Rate 2003 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2003_ages_5_64_only_ | Adjusted Rate 2003 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2003_lower_ci        | Adjusted Rate 2003 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2003_upper_ci        | Adjusted Rate 2003 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2004              | Hospitalizations 2004               | number    | number      |
| Yes      | numeric metric | crude_rate_2004                    | Crude Rate 2004                     | number    | number      |
| Yes      | numeric metric | crude_rate_2004_lower_ci           | Crude Rate 2004 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2004_upper_ci           | Crude Rate 2004 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2004_ages_5_64_only_ | Adjusted Rate 2004 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2004_lower_ci        | Adjusted Rate 2004 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2004_upper_ci        | Adjusted Rate 2004 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2005              | Hospitalizations 2005               | number    | number      |
| Yes      | numeric metric | crude_rate_2005                    | Crude Rate 2005                     | number    | number      |
| Yes      | numeric metric | crude_rate_2005_lower_ci           | Crude Rate 2005 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2005_upper_ci           | Crude Rate 2005 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2005_ages_5_64_only_ | Adjusted Rate 2005 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2005_lower_ci        | Adjusted Rate 2005 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2005_upper_ci        | Adjusted Rate 2005 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2006              | Hospitalizations 2006               | number    | number      |
| Yes      | numeric metric | crude_rate_2006                    | Crude Rate 2006                     | number    | number      |
| Yes      | numeric metric | crude_rate_2006_lower_ci           | Crude Rate 2006 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2006_upper_ci           | Crude Rate 2006 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2006_ages_5_64_only_ | Adjusted Rate 2006 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2006_lower_ci        | Adjusted Rate 2006 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2006_upper_ci        | Adjusted Rate 2006 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2007              | Hospitalizations 2007               | number    | number      |
| Yes      | numeric metric | crude_rate_2007                    | Crude Rate 2007                     | number    | number      |
| Yes      | numeric metric | crude_rate_2007_lower_ci           | Crude Rate 2007 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2007_upper_ci           | Crude Rate 2007 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2007_ages_5_64_only_ | Adjusted Rate 2007 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2007_lower_ci        | Adjusted Rate 2007 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2007_upper_ci        | Adjusted Rate 2007 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2008              | Hospitalizations 2008               | number    | number      |
| Yes      | numeric metric | crude_rate_2008                    | Crude Rate 2008                     | number    | number      |
| Yes      | numeric metric | crude_rate_2008_lower_ci           | Crude Rate 2008 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2008_upper_ci           | Crude Rate 2008 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2008_ages_5_64_only_ | Adjusted Rate 2008 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2008_lower_ci        | Adjusted Rate 2008 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2008_upper_ci        | Adjusted Rate 2008 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2009              | Hospitalizations 2009               | number    | number      |
| Yes      | numeric metric | crude_rate_2009                    | Crude Rate 2009                     | number    | number      |
| Yes      | numeric metric | crude_rate_2009_lower_ci           | Crude Rate 2009 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2009_upper_ci           | Crude Rate 2009 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2009_ages_5_64_only_ | Adjusted Rate 2009 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2009_lower_ci        | Adjusted Rate 2009 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2009_upper_ci        | Adjusted Rate 2009 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2010              | Hospitalizations 2010               | number    | number      |
| Yes      | numeric metric | crude_rate_2010                    | Crude Rate 2010                     | number    | number      |
| Yes      | numeric metric | crude_rate_2010_lower_ci           | Crude Rate 2010 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2010_upper_ci           | Crude Rate 2010 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2010_ages_5_64_only_ | Adjusted Rate 2010 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2010_lower_ci        | Adjusted Rate 2010 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2010_upper_ci        | Adjusted Rate 2010 Upper CI         | number    | number      |
| Yes      | numeric metric | hospitalizations_2011              | Hospitalizations 2011               | number    | number      |
| Yes      | numeric metric | crude_rate_2011                    | Crude Rate 2011                     | number    | number      |
| Yes      | numeric metric | crude_rate_2011_lower_ci           | Crude Rate 2011 Lower CI            | number    | number      |
| Yes      | numeric metric | crude_rate_2011_upper_ci           | Crude Rate 2011 Upper CI            | number    | number      |
| Yes      | numeric metric | adjusted_rate_2011_ages_5_64_only  | Adjusted Rate 2011 (Ages 5-64 only) | number    | number      |
| Yes      | numeric metric | adjusted_rate_2011_lower_ci        | Adjusted Rate 2011 Lower CI         | number    | number      |
| Yes      | numeric metric | adjusted_rate_2011_upper_ci        | Adjusted Rate 2011 Upper CI         | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vazh-t57q d:2000-01-01T00:00:00.000Z t:zip_code_or_aggregate_="60606, 60607 & 60661" m:adjusted_rate_2008_upper_ci=20.2 m:crude_rate_2003_upper_ci=21 m:crude_rate_2011_upper_ci=14 m:adjusted_rate_2007_lower_ci=8.5 m:crude_rate_2011_lower_ci=6.9 m:adjusted_rate_2003_ages_5_64_only_=13.4 m:crude_rate_2010_lower_ci=9.2 m:crude_rate_2010_upper_ci=17 m:adjusted_rate_2011_upper_ci=24.9 m:adjusted_rate_2003_upper_ci=20.1 m:crude_rate_2004_lower_ci=7.6 m:adjusted_rate_2002_upper_ci=22.9 m:hospitalizations_2011=34 m:hospitalizations_2010=43 m:crude_rate_2000_lower_ci=19.6 m:adjusted_rate_2009_lower_ci=6.1 m:crude_rate_2008_lower_ci=10.1 m:crude_rate_2003=15.4 m:crude_rate_2004=11.3 m:adjusted_rate_2003_lower_ci=8 m:crude_rate_2001_lower_ci=14.7 m:crude_rate_2005=16.9 m:crude_rate_2006_upper_ci=18.8 m:crude_rate_2006=13.8 m:crude_rate_2007=12.2 m:crude_rate_2008=14 m:crude_rate_2009=10.7 m:adjusted_rate_2004_ages_5_64_only_=8.7 m:adjusted_rate_2008_lower_ci=8.5 m:adjusted_rate_2001_lower_ci=10.5 m:crude_rate_2000=25.9 m:crude_rate_2009_lower_ci=7.4 m:crude_rate_2001=20.1 m:crude_rate_2002=18.7 m:adjusted_rate_2000_upper_ci=30.8 m:adjusted_rate_2000_lower_ci=13.9 m:adjusted_rate_2006_upper_ci=19.1 m:adjusted_rate_2004_lower_ci=4.2 m:crude_rate_2004_upper_ci=16.1 m:adjusted_rate_2000_ages_5_64_only_=21.5 m:crude_rate_2009_upper_ci=14.9 m:adjusted_rate_2009_ages_5_64_only_=11.3 m:crude_rate_2011=10 m:crude_rate_2010=12.6 m:adjusted_rate_2005_lower_ci=7.8 m:crude_rate_2008_upper_ci=18.7 m:adjusted_rate_2010_ages_5_64_only_=15.1 m:crude_rate_2003_lower_ci=10.9 m:adjusted_rate_2007_ages_5_64_only_=15 m:adjusted_rate_2004_upper_ci=14.9 m:adjusted_rate_2008_ages_5_64_only_=13.7 m:crude_rate_2007_lower_ci=8.6 m:crude_rate_2002_lower_ci=13.6 m:crude_rate_2007_upper_ci=16.8 m:adjusted_rate_2001_ages_5_64_only_=16.7 m:adjusted_rate_2010_lower_ci=7.8 m:adjusted_rate_2010_upper_ci=24.7 m:adjusted_rate_2005_ages_5_64_only_=12.1 m:adjusted_rate_2009_upper_ci=18 m:crude_rate_2000_upper_ci=33.6 m:adjusted_rate_2002_ages_5_64_only_=15.6 m:adjusted_rate_2011_ages_5_64_only=15.9 m:crude_rate_2002_upper_ci=25 m:crude_rate_2006_lower_ci=9.8 m:adjusted_rate_2005_upper_ci=17.4 m:crude_rate_2005_lower_ci=12.4 m:adjusted_rate_2001_upper_ci=24.3 m:crude_rate_2005_upper_ci=22.5 m:hospitalizations_2004=30 m:adjusted_rate_2006_lower_ci=7.9 m:hospitalizations_2005=47 m:adjusted_rate_2006_ages_5_64_only_=12.9 m:hospitalizations_2006=40 m:hospitalizations_2007=37 m:hospitalizations_2008=44 m:hospitalizations_2009=35 m:adjusted_rate_2007_upper_ci=23.4 m:adjusted_rate_2002_lower_ci=9.7 m:adjusted_rate_2011_lower_ci=8.9 m:hospitalizations_2000=56 m:crude_rate_2001_upper_ci=26.8 m:hospitalizations_2001=46 m:hospitalizations_2002=45 m:hospitalizations_2003=39

series e:vazh-t57q d:2000-01-01T00:00:00.000Z t:zip_code_or_aggregate_="60601, 60602, 60603, 60604, 60605 & 60611" m:adjusted_rate_2008_upper_ci=8.4 m:crude_rate_2003_upper_ci=9 m:crude_rate_2011_upper_ci=12.2 m:adjusted_rate_2007_lower_ci=3.4 m:crude_rate_2011_lower_ci=7.4 m:adjusted_rate_2003_ages_5_64_only_=11.1 m:crude_rate_2010_lower_ci=5.9 m:crude_rate_2010_upper_ci=10.4 m:adjusted_rate_2011_upper_ci=12.8 m:adjusted_rate_2003_upper_ci=18.5 m:crude_rate_2004_lower_ci=5.6 m:adjusted_rate_2002_upper_ci=16.2 m:hospitalizations_2011=64 m:hospitalizations_2010=53 m:crude_rate_2000_lower_ci=10.2 m:adjusted_rate_2009_lower_ci=6.4 m:crude_rate_2008_lower_ci=4 m:crude_rate_2003=6.4 m:crude_rate_2004=7.8 m:adjusted_rate_2003_lower_ci=5.6 m:crude_rate_2001_lower_ci=6.4 m:crude_rate_2005=8.6 m:crude_rate_2006_upper_ci=10.4 m:crude_rate_2006=7.7 m:crude_rate_2007=7 m:crude_rate_2008=5.8 m:crude_rate_2009=7 m:adjusted_rate_2004_ages_5_64_only_=8.5 m:adjusted_rate_2008_lower_ci=2.6 m:adjusted_rate_2001_lower_ci=5 m:crude_rate_2000=13.3 m:crude_rate_2009_lower_ci=5.1 m:crude_rate_2001=8.9 m:crude_rate_2002=9.3 m:adjusted_rate_2000_upper_ci=25.7 m:adjusted_rate_2000_lower_ci=10 m:adjusted_rate_2006_upper_ci=13.5 m:adjusted_rate_2004_lower_ci=4.3 m:crude_rate_2004_upper_ci=10.6 m:adjusted_rate_2000_ages_5_64_only_=17 m:crude_rate_2009_upper_ci=9.3 m:adjusted_rate_2009_ages_5_64_only_=11.6 m:crude_rate_2011=9.6 m:crude_rate_2010=7.9 m:adjusted_rate_2005_lower_ci=5.7 m:crude_rate_2008_upper_ci=8 m:adjusted_rate_2010_ages_5_64_only_=9.6 m:crude_rate_2003_lower_ci=4.4 m:adjusted_rate_2007_ages_5_64_only_=6.7 m:adjusted_rate_2004_upper_ci=14.2 m:adjusted_rate_2008_ages_5_64_only_=5.1 m:crude_rate_2007_lower_ci=5 m:crude_rate_2002_lower_ci=6.8 m:crude_rate_2007_upper_ci=9.4 m:adjusted_rate_2001_ages_5_64_only_=8.3 m:adjusted_rate_2010_lower_ci=5.3 m:adjusted_rate_2010_upper_ci=15.2 m:adjusted_rate_2005_ages_5_64_only_=11.4 m:adjusted_rate_2009_upper_ci=18.4 m:crude_rate_2000_upper_ci=17.1 m:adjusted_rate_2002_ages_5_64_only_=10.1 m:adjusted_rate_2011_ages_5_64_only=8.6 m:crude_rate_2002_upper_ci=12.4 m:crude_rate_2006_lower_ci=5.7 m:adjusted_rate_2005_upper_ci=18.9 m:crude_rate_2005_lower_ci=6.3 m:adjusted_rate_2001_upper_ci=12.5 m:crude_rate_2005_upper_ci=11.4 m:hospitalizations_2004=42 m:adjusted_rate_2006_lower_ci=4 m:hospitalizations_2005=48 m:adjusted_rate_2006_ages_5_64_only_=8.1 m:hospitalizations_2006=45 m:hospitalizations_2007=42 m:hospitalizations_2008=36 m:hospitalizations_2009=45 m:adjusted_rate_2007_upper_ci=11.2 m:adjusted_rate_2002_lower_ci=5.5 m:adjusted_rate_2011_lower_ci=5.1 m:hospitalizations_2000=60 m:crude_rate_2001_upper_ci=12 m:hospitalizations_2001=42 m:hospitalizations_2002=46 m:hospitalizations_2003=33

series e:vazh-t57q d:2000-01-01T00:00:00.000Z t:zip_code_or_aggregate_=60608 m:adjusted_rate_2008_upper_ci=20.4 m:crude_rate_2003_upper_ci=26.7 m:crude_rate_2011_upper_ci=20.4 m:adjusted_rate_2007_lower_ci=10.6 m:crude_rate_2011_lower_ci=14.7 m:adjusted_rate_2003_ages_5_64_only_=19.7 m:crude_rate_2010_lower_ci=14 m:crude_rate_2010_upper_ci=19.6 m:adjusted_rate_2011_upper_ci=18.8 m:adjusted_rate_2003_upper_ci=23.3 m:crude_rate_2004_lower_ci=17 m:adjusted_rate_2002_upper_ci=21.1 m:hospitalizations_2011=145 m:hospitalizations_2010=139 m:crude_rate_2000_lower_ci=24.5 m:adjusted_rate_2009_lower_ci=14.6 m:crude_rate_2008_lower_ci=17.9 m:crude_rate_2003=23.6 m:crude_rate_2004=20 m:adjusted_rate_2003_lower_ci=16.5 m:crude_rate_2001_lower_ci=19.4 m:crude_rate_2005=18.9 m:crude_rate_2006_upper_ci=25.2 m:crude_rate_2006=22 m:crude_rate_2007=16.9 m:crude_rate_2008=21 m:crude_rate_2009=20.9 m:adjusted_rate_2004_ages_5_64_only_=16.2 m:adjusted_rate_2008_lower_ci=14 m:adjusted_rate_2001_lower_ci=14.5 m:crude_rate_2000=27.9 m:crude_rate_2009_lower_ci=17.8 m:crude_rate_2001=22.5 m:crude_rate_2002=21.1 m:adjusted_rate_2000_upper_ci=29.2 m:adjusted_rate_2000_lower_ci=21.6 m:adjusted_rate_2006_upper_ci=21.3 m:adjusted_rate_2004_lower_ci=13.4 m:crude_rate_2004_upper_ci=22.9 m:adjusted_rate_2000_ages_5_64_only_=25.3 m:crude_rate_2009_upper_ci=24 m:adjusted_rate_2009_ages_5_64_only_=17.6 m:crude_rate_2011=17.5 m:crude_rate_2010=16.8 m:adjusted_rate_2005_lower_ci=12.1 m:crude_rate_2008_upper_ci=24.1 m:adjusted_rate_2010_ages_5_64_only_=13.6 m:crude_rate_2003_lower_ci=20.4 m:adjusted_rate_2007_ages_5_64_only_=13.3 m:adjusted_rate_2004_upper_ci=19.4 m:adjusted_rate_2008_ages_5_64_only_=17.1 m:crude_rate_2007_lower_ci=14.2 m:crude_rate_2002_lower_ci=18.1 m:crude_rate_2007_upper_ci=19.7 m:adjusted_rate_2001_ages_5_64_only_=17.5 m:adjusted_rate_2010_lower_ci=10.9 m:adjusted_rate_2010_upper_ci=16.6 m:adjusted_rate_2005_ages_5_64_only_=15 m:adjusted_rate_2009_upper_ci=21 m:crude_rate_2000_upper_ci=31.3 m:adjusted_rate_2002_ages_5_64_only_=17.7 m:adjusted_rate_2011_ages_5_64_only=15.6 m:crude_rate_2002_upper_ci=24.1 m:crude_rate_2006_lower_ci=18.9 m:adjusted_rate_2005_upper_ci=18.1 m:crude_rate_2005_lower_ci=16.1 m:adjusted_rate_2001_upper_ci=20.8 m:crude_rate_2005_upper_ci=21.8 m:hospitalizations_2004=177 m:adjusted_rate_2006_lower_ci=14.8 m:hospitalizations_2005=166 m:adjusted_rate_2006_ages_5_64_only_=17.9 m:hospitalizations_2006=191 m:hospitalizations_2007=145 m:hospitalizations_2008=178 m:hospitalizations_2009=175 m:adjusted_rate_2007_upper_ci=16.2 m:adjusted_rate_2002_lower_ci=14.6 m:adjusted_rate_2011_lower_ci=12.7 m:hospitalizations_2000=258 m:crude_rate_2001_upper_ci=25.6 m:hospitalizations_2001=206 m:hospitalizations_2002=191 m:hospitalizations_2003=211
```

## Meta Commands

```ls
metric m:hospitalizations_2000 p:integer l:"Hospitalizations 2000" t:dataTypeName=number

metric m:crude_rate_2000 p:float l:"Crude Rate 2000" t:dataTypeName=number

metric m:crude_rate_2000_lower_ci p:float l:"Crude Rate 2000 Lower CI" t:dataTypeName=number

metric m:crude_rate_2000_upper_ci p:float l:"Crude Rate 2000 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2000_ages_5_64_only_ p:float l:"Adjusted Rate 2000 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2000_lower_ci p:float l:"Adjusted Rate 2000 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2000_upper_ci p:float l:"Adjusted Rate 2000 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2001 p:integer l:"Hospitalizations 2001" t:dataTypeName=number

metric m:crude_rate_2001 p:float l:"Crude Rate 2001" t:dataTypeName=number

metric m:crude_rate_2001_lower_ci p:float l:"Crude Rate 2001 Lower CI" t:dataTypeName=number

metric m:crude_rate_2001_upper_ci p:float l:"Crude Rate 2001 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2001_ages_5_64_only_ p:float l:"Adjusted Rate 2001 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2001_lower_ci p:float l:"Adjusted Rate 2001 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2001_upper_ci p:double l:"Adjusted Rate 2001 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2002 p:integer l:"Hospitalizations 2002" t:dataTypeName=number

metric m:crude_rate_2002 p:float l:"Crude Rate 2002" t:dataTypeName=number

metric m:crude_rate_2002_lower_ci p:float l:"Crude Rate 2002 Lower CI" t:dataTypeName=number

metric m:crude_rate_2002_upper_ci p:float l:"Crude Rate 2002 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2002_ages_5_64_only_ p:float l:"Adjusted Rate 2002 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2002_lower_ci p:double l:"Adjusted Rate 2002 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2002_upper_ci p:float l:"Adjusted Rate 2002 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2003 p:integer l:"Hospitalizations 2003" t:dataTypeName=number

metric m:crude_rate_2003 p:float l:"Crude Rate 2003" t:dataTypeName=number

metric m:crude_rate_2003_lower_ci p:float l:"Crude Rate 2003 Lower CI" t:dataTypeName=number

metric m:crude_rate_2003_upper_ci p:float l:"Crude Rate 2003 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2003_ages_5_64_only_ p:float l:"Adjusted Rate 2003 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2003_lower_ci p:float l:"Adjusted Rate 2003 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2003_upper_ci p:float l:"Adjusted Rate 2003 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2004 p:integer l:"Hospitalizations 2004" t:dataTypeName=number

metric m:crude_rate_2004 p:float l:"Crude Rate 2004" t:dataTypeName=number

metric m:crude_rate_2004_lower_ci p:float l:"Crude Rate 2004 Lower CI" t:dataTypeName=number

metric m:crude_rate_2004_upper_ci p:double l:"Crude Rate 2004 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2004_ages_5_64_only_ p:float l:"Adjusted Rate 2004 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2004_lower_ci p:float l:"Adjusted Rate 2004 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2004_upper_ci p:double l:"Adjusted Rate 2004 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2005 p:integer l:"Hospitalizations 2005" t:dataTypeName=number

metric m:crude_rate_2005 p:float l:"Crude Rate 2005" t:dataTypeName=number

metric m:crude_rate_2005_lower_ci p:float l:"Crude Rate 2005 Lower CI" t:dataTypeName=number

metric m:crude_rate_2005_upper_ci p:float l:"Crude Rate 2005 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2005_ages_5_64_only_ p:double l:"Adjusted Rate 2005 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2005_lower_ci p:float l:"Adjusted Rate 2005 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2005_upper_ci p:float l:"Adjusted Rate 2005 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2006 p:integer l:"Hospitalizations 2006" t:dataTypeName=number

metric m:crude_rate_2006 p:float l:"Crude Rate 2006" t:dataTypeName=number

metric m:crude_rate_2006_lower_ci p:float l:"Crude Rate 2006 Lower CI" t:dataTypeName=number

metric m:crude_rate_2006_upper_ci p:double l:"Crude Rate 2006 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2006_ages_5_64_only_ p:float l:"Adjusted Rate 2006 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2006_lower_ci p:float l:"Adjusted Rate 2006 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2006_upper_ci p:float l:"Adjusted Rate 2006 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2007 p:integer l:"Hospitalizations 2007" t:dataTypeName=number

metric m:crude_rate_2007 p:float l:"Crude Rate 2007" t:dataTypeName=number

metric m:crude_rate_2007_lower_ci p:float l:"Crude Rate 2007 Lower CI" t:dataTypeName=number

metric m:crude_rate_2007_upper_ci p:float l:"Crude Rate 2007 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2007_ages_5_64_only_ p:double l:"Adjusted Rate 2007 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2007_lower_ci p:float l:"Adjusted Rate 2007 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2007_upper_ci p:float l:"Adjusted Rate 2007 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2008 p:integer l:"Hospitalizations 2008" t:dataTypeName=number

metric m:crude_rate_2008 p:float l:"Crude Rate 2008" t:dataTypeName=number

metric m:crude_rate_2008_lower_ci p:float l:"Crude Rate 2008 Lower CI" t:dataTypeName=number

metric m:crude_rate_2008_upper_ci p:float l:"Crude Rate 2008 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2008_ages_5_64_only_ p:float l:"Adjusted Rate 2008 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2008_lower_ci p:float l:"Adjusted Rate 2008 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2008_upper_ci p:float l:"Adjusted Rate 2008 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2009 p:integer l:"Hospitalizations 2009" t:dataTypeName=number

metric m:crude_rate_2009 p:float l:"Crude Rate 2009" t:dataTypeName=number

metric m:crude_rate_2009_lower_ci p:float l:"Crude Rate 2009 Lower CI" t:dataTypeName=number

metric m:crude_rate_2009_upper_ci p:float l:"Crude Rate 2009 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2009_ages_5_64_only_ p:float l:"Adjusted Rate 2009 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2009_lower_ci p:float l:"Adjusted Rate 2009 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2009_upper_ci p:float l:"Adjusted Rate 2009 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2010 p:integer l:"Hospitalizations 2010" t:dataTypeName=number

metric m:crude_rate_2010 p:float l:"Crude Rate 2010" t:dataTypeName=number

metric m:crude_rate_2010_lower_ci p:float l:"Crude Rate 2010 Lower CI" t:dataTypeName=number

metric m:crude_rate_2010_upper_ci p:float l:"Crude Rate 2010 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2010_ages_5_64_only_ p:float l:"Adjusted Rate 2010 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2010_lower_ci p:float l:"Adjusted Rate 2010 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2010_upper_ci p:float l:"Adjusted Rate 2010 Upper CI" t:dataTypeName=number

metric m:hospitalizations_2011 p:integer l:"Hospitalizations 2011" t:dataTypeName=number

metric m:crude_rate_2011 p:float l:"Crude Rate 2011" t:dataTypeName=number

metric m:crude_rate_2011_lower_ci p:double l:"Crude Rate 2011 Lower CI" t:dataTypeName=number

metric m:crude_rate_2011_upper_ci p:float l:"Crude Rate 2011 Upper CI" t:dataTypeName=number

metric m:adjusted_rate_2011_ages_5_64_only p:float l:"Adjusted Rate 2011 (Ages 5-64 only)" t:dataTypeName=number

metric m:adjusted_rate_2011_lower_ci p:float l:"Adjusted Rate 2011 Lower CI" t:dataTypeName=number

metric m:adjusted_rate_2011_upper_ci p:float l:"Adjusted Rate 2011 Upper CI" t:dataTypeName=number

entity e:vazh-t57q l:"Public Health Statistics - Asthma hospitalizations in Chicago, by year, 2000 - 2011" t:attribution="Illinois Department of Public Health (IDPH)" t:url=https://data.cityofchicago.org/api/views/vazh-t57q

property e:vazh-t57q t:meta.view v:id=vazh-t57q v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Statistics - Asthma hospitalizations in Chicago, by year, 2000 - 2011" v:attribution="Illinois Department of Public Health (IDPH)"

property e:vazh-t57q t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:vazh-t57q t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| zip_code_or_aggregate_                    | hospitalizations_2000 | crude_rate_2000 | crude_rate_2000_lower_ci | crude_rate_2000_upper_ci | adjusted_rate_2000_ages_5_64_only_ | adjusted_rate_2000_lower_ci | adjusted_rate_2000_upper_ci | hospitalizations_2001 | crude_rate_2001 | crude_rate_2001_lower_ci | crude_rate_2001_upper_ci | adjusted_rate_2001_ages_5_64_only_ | adjusted_rate_2001_lower_ci | adjusted_rate_2001_upper_ci | hospitalizations_2002 | crude_rate_2002 | crude_rate_2002_lower_ci | crude_rate_2002_upper_ci | adjusted_rate_2002_ages_5_64_only_ | adjusted_rate_2002_lower_ci | adjusted_rate_2002_upper_ci | hospitalizations_2003 | crude_rate_2003 | crude_rate_2003_lower_ci | crude_rate_2003_upper_ci | adjusted_rate_2003_ages_5_64_only_ | adjusted_rate_2003_lower_ci | adjusted_rate_2003_upper_ci | hospitalizations_2004 | crude_rate_2004 | crude_rate_2004_lower_ci | crude_rate_2004_upper_ci | adjusted_rate_2004_ages_5_64_only_ | adjusted_rate_2004_lower_ci | adjusted_rate_2004_upper_ci | hospitalizations_2005 | crude_rate_2005 | crude_rate_2005_lower_ci | crude_rate_2005_upper_ci | adjusted_rate_2005_ages_5_64_only_ | adjusted_rate_2005_lower_ci | adjusted_rate_2005_upper_ci | hospitalizations_2006 | crude_rate_2006 | crude_rate_2006_lower_ci | crude_rate_2006_upper_ci | adjusted_rate_2006_ages_5_64_only_ | adjusted_rate_2006_lower_ci | adjusted_rate_2006_upper_ci | hospitalizations_2007 | crude_rate_2007 | crude_rate_2007_lower_ci | crude_rate_2007_upper_ci | adjusted_rate_2007_ages_5_64_only_ | adjusted_rate_2007_lower_ci | adjusted_rate_2007_upper_ci | hospitalizations_2008 | crude_rate_2008 | crude_rate_2008_lower_ci | crude_rate_2008_upper_ci | adjusted_rate_2008_ages_5_64_only_ | adjusted_rate_2008_lower_ci | adjusted_rate_2008_upper_ci | hospitalizations_2009 | crude_rate_2009 | crude_rate_2009_lower_ci | crude_rate_2009_upper_ci | adjusted_rate_2009_ages_5_64_only_ | adjusted_rate_2009_lower_ci | adjusted_rate_2009_upper_ci | hospitalizations_2010 | crude_rate_2010 | crude_rate_2010_lower_ci | crude_rate_2010_upper_ci | adjusted_rate_2010_ages_5_64_only_ | adjusted_rate_2010_lower_ci | adjusted_rate_2010_upper_ci | hospitalizations_2011 | crude_rate_2011 | crude_rate_2011_lower_ci | crude_rate_2011_upper_ci | adjusted_rate_2011_ages_5_64_only | adjusted_rate_2011_lower_ci | adjusted_rate_2011_upper_ci | 
| ========================================= | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================== | =========================== | =========================== | ===================== | =============== | ======================== | ======================== | ================================= | =========================== | =========================== | 
| 60606, 60607 & 60661                      | 56                    | 25.9            | 19.6                     | 33.6                     | 21.5                               | 13.9                        | 30.8                        | 46                    | 20.1            | 14.7                     | 26.8                     | 16.7                               | 10.5                        | 24.3                        | 45                    | 18.7            | 13.6                     | 25                       | 15.6                               | 9.7                         | 22.9                        | 39                    | 15.4            | 10.9                     | 21                       | 13.4                               | 8                           | 20.1                        | 30                    | 11.3            | 7.6                      | 16.1                     | 8.7                                | 4.2                         | 14.9                        | 47                    | 16.9            | 12.4                     | 22.5                     | 12.1                               | 7.8                         | 17.4                        | 40                    | 13.8            | 9.8                      | 18.8                     | 12.9                               | 7.9                         | 19.1                        | 37                    | 12.2            | 8.6                      | 16.8                     | 15                                 | 8.5                         | 23.4                        | 44                    | 14              | 10.1                     | 18.7                     | 13.7                               | 8.5                         | 20.2                        | 35                    | 10.7            | 7.4                      | 14.9                     | 11.3                               | 6.1                         | 18                          | 43                    | 12.6            | 9.2                      | 17                       | 15.1                               | 7.8                         | 24.7                        | 34                    | 10              | 6.9                      | 14                       | 15.9                              | 8.9                         | 24.9                        | 
| 60601, 60602, 60603, 60604, 60605 & 60611 | 60                    | 13.3            | 10.2                     | 17.1                     | 17                                 | 10                          | 25.7                        | 42                    | 8.9             | 6.4                      | 12                       | 8.3                                | 5                           | 12.5                        | 46                    | 9.3             | 6.8                      | 12.4                     | 10.1                               | 5.5                         | 16.2                        | 33                    | 6.4             | 4.4                      | 9                        | 11.1                               | 5.6                         | 18.5                        | 42                    | 7.8             | 5.6                      | 10.6                     | 8.5                                | 4.3                         | 14.2                        | 48                    | 8.6             | 6.3                      | 11.4                     | 11.4                               | 5.7                         | 18.9                        | 45                    | 7.7             | 5.7                      | 10.4                     | 8.1                                | 4                           | 13.5                        | 42                    | 7               | 5                        | 9.4                      | 6.7                                | 3.4                         | 11.2                        | 36                    | 5.8             | 4                        | 8                        | 5.1                                | 2.6                         | 8.4                         | 45                    | 7               | 5.1                      | 9.3                      | 11.6                               | 6.4                         | 18.4                        | 53                    | 7.9             | 5.9                      | 10.4                     | 9.6                                | 5.3                         | 15.2                        | 64                    | 9.6             | 7.4                      | 12.2                     | 8.6                               | 5.1                         | 12.8                        | 
| 60608                                     | 258                   | 27.9            | 24.5                     | 31.3                     | 25.3                               | 21.6                        | 29.2                        | 206                   | 22.5            | 19.4                     | 25.6                     | 17.5                               | 14.5                        | 20.8                        | 191                   | 21.1            | 18.1                     | 24.1                     | 17.7                               | 14.6                        | 21.1                        | 211                   | 23.6            | 20.4                     | 26.7                     | 19.7                               | 16.5                        | 23.3                        | 177                   | 20              | 17                       | 22.9                     | 16.2                               | 13.4                        | 19.4                        | 166                   | 18.9            | 16.1                     | 21.8                     | 15                                 | 12.1                        | 18.1                        | 191                   | 22              | 18.9                     | 25.2                     | 17.9                               | 14.8                        | 21.3                        | 145                   | 16.9            | 14.2                     | 19.7                     | 13.3                               | 10.6                        | 16.2                        | 178                   | 21              | 17.9                     | 24.1                     | 17.1                               | 14                          | 20.4                        | 175                   | 20.9            | 17.8                     | 24                       | 17.6                               | 14.6                        | 21                          | 139                   | 16.8            | 14                       | 19.6                     | 13.6                               | 10.9                        | 16.6                        | 145                   | 17.5            | 14.7                     | 20.4                     | 15.6                              | 12.7                        | 18.8                        | 
| 60609                                     | 386                   | 48.6            | 43.7                     | 53.4                     | 46.3                               | 40.8                        | 52.1                        | 336                   | 43.1            | 38.5                     | 47.7                     | 39.6                               | 34.5                        | 45.1                        | 259                   | 33.8            | 29.7                     | 38                       | 30.1                               | 25.6                        | 35                          | 248                   | 33              | 28.9                     | 37.1                     | 30.5                               | 26                          | 35.4                        | 210                   | 28.5            | 24.7                     | 32.4                     | 24.8                               | 20.8                        | 29.3                        | 230                   | 31.9            | 27.7                     | 36                       | 27                                 | 22.8                        | 31.7                        | 243                   | 34.4            | 30                       | 38.7                     | 31.6                               | 27                          | 36.5                        | 212                   | 30.6            | 26.5                     | 34.7                     | 28.9                               | 24.4                        | 33.8                        | 195                   | 28.8            | 24.7                     | 32.8                     | 28.2                               | 23.8                        | 33                          | 209                   | 31.5            | 27.2                     | 35.8                     | 31.5                               | 26.7                        | 36.6                        | 168                   | 25.9            | 22                       | 29.8                     | 23.5                               | 19.5                        | 27.9                        | 195                   | 30              | 25.8                     | 34.3                     | 27.7                              | 23.3                        | 32.5                        | 
| 60610 & 60654                             | 160                   | 33.7            | 28.5                     | 38.9                     | 33.3                               | 26.7                        | 40.5                        | 172                   | 35.8            | 30.5                     | 41.2                     | 39.7                               | 32.5                        | 47.7                        | 146                   | 30.1            | 25.2                     | 35                       | 35.8                               | 28.7                        | 43.7                        | 130                   | 26.5            | 21.9                     | 31.1                     | 30.6                               | 23.8                        | 38.2                        | 105                   | 21.2            | 17.1                     | 25.2                     | 26.4                               | 20.4                        | 33.2                        | 108                   | 21.6            | 17.5                     | 25.6                     | 25                                 | 19.1                        | 31.8                        | 118                   | 23.3            | 19.1                     | 27.5                     | 25.5                               | 19.3                        | 32.7                        | 97                    | 19              | 15.4                     | 23.2                     | 21.9                               | 16.5                        | 28.1                        | 120                   | 23.3            | 19.1                     | 27.4                     | 26                                 | 20                          | 32.8                        | 135                   | 25.9            | 21.5                     | 30.3                     | 29.3                               | 22.2                        | 37.3                        | 98                    | 18.6            | 15.1                     | 22.7                     | 21.6                               | 15.8                        | 28.3                        | 84                    | 16              | 12.7                     | 19.8                     | 21.6                              | 15.2                        | 29.2                        | 
| 60612                                     | 302                   | 79.5            | 70.5                     | 88.5                     | 72.7                               | 63.3                        | 82.7                        | 298                   | 79.4            | 70.4                     | 88.4                     | 74.1                               | 64.4                        | 84.6                        | 277                   | 74.7            | 65.9                     | 83.5                     | 72                                 | 62.2                        | 82.5                        | 220                   | 60.1            | 52.1                     | 68                       | 56.7                               | 48                          | 66.2                        | 224                   | 61.9            | 53.8                     | 70                       | 58.1                               | 49.2                        | 67.7                        | 212                   | 59.3            | 51.3                     | 67.3                     | 57.2                               | 48.4                        | 66.7                        | 215                   | 60.9            | 52.8                     | 69.1                     | 59.6                               | 50.6                        | 69.3                        | 152                   | 43.6            | 36.7                     | 50.6                     | 39.9                               | 32.6                        | 48                          | 193                   | 56.1            | 48.2                     | 64.1                     | 52.3                               | 43.9                        | 61.5                        | 212                   | 62.5            | 54.1                     | 70.9                     | 60.6                               | 51.4                        | 70.5                        | 166                   | 49.6            | 42                       | 57.1                     | 46.1                               | 38.1                        | 54.8                        | 184                   | 55              | 47                       | 62.9                     | 49.7                              | 41.4                        | 58.8                        | 
| 60613                                     | 63                    | 12.5            | 9.6                      | 15.9                     | 13.8                               | 9.1                         | 19.5                        | 45                    | 8.9             | 6.5                      | 12                       | 9                                  | 5.6                         | 13.2                        | 60                    | 12              | 9.1                      | 15.4                     | 12.6                               | 7.9                         | 18.3                        | 45                    | 9               | 6.6                      | 12.1                     | 8.5                                | 4.9                         | 13.1                        | 46                    | 9.3             | 6.8                      | 12.4                     | 10.3                               | 6                           | 15.6                        | 44                    | 8.9             | 6.5                      | 12                       | 8.9                                | 4.8                         | 14.1                        | 44                    | 8.9             | 6.5                      | 12                       | 6.2                                | 3.4                         | 9.9                         | 41                    | 8.4             | 6                        | 11.4                     | 10.2                               | 6.3                         | 15                          | 56                    | 11.5            | 8.7                      | 14.9                     | 10.7                               | 7                           | 15.1                        | 41                    | 8.5             | 6.1                      | 11.5                     | 6.7                                | 3.5                         | 10.8                        | 49                    | 10.1            | 7.5                      | 13.4                     | 8.3                                | 5.5                         | 11.8                        | 40                    | 8.3             | 5.9                      | 11.3                     | 6.3                               | 4                           | 9.2                         | 
| 60614                                     | 60                    | 9.2             | 7                        | 11.8                     | 6.9                                | 4.2                         | 10.2                        | 78                    | 11.9            | 9.4                      | 14.8                     | 12.7                               | 8.8                         | 17.2                        | 64                    | 9.7             | 7.5                      | 12.4                     | 10                                 | 6.6                         | 13.9                        | 65                    | 9.9             | 7.6                      | 12.6                     | 10.2                               | 6.8                         | 14.2                        | 58                    | 8.8             | 6.7                      | 11.4                     | 8.1                                | 5                           | 12                          | 82                    | 12.4            | 9.9                      | 15.4                     | 11.1                               | 7.7                         | 15                          | 54                    | 8.2             | 6.1                      | 10.6                     | 7.5                                | 4.7                         | 11.1                        | 65                    | 9.8             | 7.6                      | 12.5                     | 9.9                                | 6.6                         | 13.7                        | 56                    | 8.4             | 6.4                      | 11                       | 8.1                                | 5.1                         | 11.7                        | 66                    | 9.9             | 7.7                      | 12.6                     | 12.7                               | 8.9                         | 17.2                        | 43                    | 6.5             | 4.7                      | 8.7                      | 5.7                                | 3.5                         | 8.4                         | 46                    | 6.9             | 5.1                      | 9.2                      | 6.6                               | 4.1                         | 9.7                         | 
| 60615                                     | 200                   | 44.3            | 38.2                     | 50.5                     | 36.9                               | 30.7                        | 43.8                        | 130                   | 29.1            | 24.1                     | 34.1                     | 24.8                               | 19.7                        | 30.4                        | 139                   | 31.4            | 26.2                     | 36.7                     | 27.8                               | 22.3                        | 33.9                        | 136                   | 31.1            | 25.9                     | 36.3                     | 29                                 | 23.5                        | 35.1                        | 110                   | 25.4            | 20.7                     | 30.2                     | 21.1                               | 16.5                        | 26.1                        | 108                   | 25.2            | 20.4                     | 30                       | 24.6                               | 19.5                        | 30.4                        | 108                   | 25.5            | 20.7                     | 30.3                     | 23.1                               | 18.1                        | 28.7                        | 100                   | 23.8            | 19.2                     | 28.5                     | 20.7                               | 16                          | 26                          | 91                    | 21.9            | 17.7                     | 26.9                     | 22.3                               | 17.5                        | 27.8                        | 93                    | 22.7            | 18.3                     | 27.8                     | 23.1                               | 18                          | 28.9                        | 82                    | 20.2            | 16.1                     | 25.1                     | 18                                 | 13.5                        | 23                          | 111                   | 27.3            | 22.3                     | 32.4                     | 26.7                              | 21.2                        | 32.8                        | 
| 60616                                     | 144                   | 30.6            | 25.6                     | 35.6                     | 25                                 | 20.1                        | 30.4                        | 90                    | 19.1            | 15.3                     | 23.4                     | 18.4                               | 14.1                        | 23.2                        | 124                   | 26.2            | 21.6                     | 30.8                     | 24.7                               | 19.8                        | 30.1                        | 112                   | 23.6            | 19.2                     | 28                       | 19.8                               | 15.4                        | 24.7                        | 96                    | 20.2            | 16.3                     | 24.6                     | 15.9                               | 12                          | 20.4                        | 109                   | 22.8            | 18.5                     | 27.1                     | 19.2                               | 14.9                        | 24                          | 91                    | 19              | 15.3                     | 23.3                     | 17.5                               | 13.5                        | 21.9                        | 74                    | 15.4            | 12.1                     | 19.3                     | 12.7                               | 9.5                         | 16.5                        | 88                    | 18.3            | 14.7                     | 22.5                     | 12.8                               | 9.4                         | 16.8                        | 74                    | 15.3            | 12                       | 19.2                     | 11.6                               | 8.5                         | 15.2                        | 55                    | 11.4            | 8.6                      | 14.8                     | 8.9                                | 6.2                         | 12.1                        | 91                    | 18.8            | 15.1                     | 23.1                     | 14.1                              | 10.5                        | 18.3                        | 
```