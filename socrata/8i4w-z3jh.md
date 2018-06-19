# King County Health Reform Indicator Metadata

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/king-county-health-reform-indicator-metadata-c9b62) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/8i4w-z3jh) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/8i4w-z3jh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/8i4w-z3jh/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | 8i4w-z3jh |
| Name | King County Health Reform Indicator Metadata |
| Attribution | Public Health - Seattle & King County |
| Category | Health |
| Tags | aca, health reform, health, community health, metadata |
| Created | 2014-03-16T03:57:29Z |
| Publication Date | 2014-10-09T03:28:43Z |

## Description

Metadata table for King County Health Reform indicators.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | indicator  | indicator | text      | text        |
| Yes      | series tag     | topic      | topic     | text      | text        |
| Yes      | time           | year       | year      | number    | number      |
| Yes      | series tag     | yearagg    | yearagg   | text      | text        |
| Yes      | series tag     | yearstr    | yearstr   | text      | text        |
| Yes      | series tag     | datasrc    | datasrc   | text      | text        |
| Yes      | series tag     | datatype   | datatype  | text      | text        |
| Yes      | series tag     | stattype   | stattype  | text      | text        |
| Yes      | series tag     | geo        | geo       | text      | text        |
| Yes      | numeric metric | kcest      | kcest     | number    | number      |
| Yes      | numeric metric | kcnum      | kcnum     | number    | number      |
| Yes      | series tag     | unit       | unit      | text      | text        |
| Yes      | series tag     | indname    | indname   | text      | text        |
| Yes      | series tag     | inddesc    | inddesc   | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8i4w-z3jh d:2012-01-01T00:00:00.000Z t:topic=access t:stattype=percent t:unit=adults t:indicator=medcost t:indname="Unmet medical need" t:inddesc="Did not seek medical care because of the cost" t:geo=hra t:yearstr="2008 2009 2010 2011 2012" t:datatype=survey t:datasrc=brfss t:yearagg=2008-2012 m:kcnum=221000 m:kcest=14.4

series e:8i4w-z3jh d:2012-01-01T00:00:00.000Z t:topic=utilization t:stattype=percent t:unit=adults t:indicator=chkup1yr t:indname="Routine checkup" t:inddesc="No routine checkup within the past year" t:geo=hra t:yearstr="2008 2009 2010 2011 2012" t:datatype=survey t:datasrc=brfss t:yearagg=2008-2012 m:kcnum=613000 m:kcest=40

series e:8i4w-z3jh d:2012-01-01T00:00:00.000Z t:topic=utilization t:stattype=percent t:unit=adults t:indicator=denvst1 t:indname="Dental visit" t:inddesc="No visit  to dentist, dental hygenist or dental clinic within the past year" t:geo=hra t:yearstr="2008 2010 2011 2012" t:datatype=survey t:datasrc=brfss t:yearagg=2008-2012 m:kcnum=438000 m:kcest=28.6
```

## Meta Commands

```ls
metric m:kcest p:float l:kcest t:dataTypeName=number

metric m:kcnum p:integer l:kcnum t:dataTypeName=number

entity e:8i4w-z3jh l:"King County Health Reform Indicator Metadata" t:attribution="Public Health - Seattle & King County" t:url=https://data.kingcounty.gov/api/views/8i4w-z3jh

property e:8i4w-z3jh t:meta.view v:id=8i4w-z3jh v:category=Health v:averageRating=0 v:name="King County Health Reform Indicator Metadata" v:attribution="Public Health - Seattle & King County"

property e:8i4w-z3jh t:meta.view.owner v:id=byna-c6yy v:profileImageUrlMedium=/api/users/byna-c6yy/profile_images/THUMB v:profileImageUrlLarge=/api/users/byna-c6yy/profile_images/LARGE v:screenName="Eli Kern" v:profileImageUrlSmall=/api/users/byna-c6yy/profile_images/TINY v:displayName="Eli Kern"

property e:8i4w-z3jh t:meta.view.tableauthor v:id=byna-c6yy v:profileImageUrlMedium=/api/users/byna-c6yy/profile_images/THUMB v:profileImageUrlLarge=/api/users/byna-c6yy/profile_images/LARGE v:screenName="Eli Kern" v:profileImageUrlSmall=/api/users/byna-c6yy/profile_images/TINY v:roleName=publisher v:displayName="Eli Kern"
```

## Top Records

```ls
| indicator      | topic       | year | yearagg   | yearstr                  | datasrc | datatype | stattype | geo | kcest | kcnum  | unit     | indname                  | inddesc                                                                                          | 
| ============== | =========== | ==== | ========= | ======================== | ======= | ======== | ======== | === | ===== | ====== | ======== | ======================== | ================================================================================================ | 
| medcost        | access      | 2012 | 2008-2012 | 2008 2009 2010 2011 2012 | brfss   | survey   | percent  | hra | 14.4  | 221000 | adults   | Unmet medical need       | Did not seek medical care because of the cost                                                    | 
| chkup1yr       | utilization | 2012 | 2008-2012 | 2008 2009 2010 2011 2012 | brfss   | survey   | percent  | hra | 40.0  | 613000 | adults   | Routine checkup          | No routine checkup within the past year                                                          | 
| denvst1        | utilization | 2012 | 2008-2012 | 2008 2010 2011 2012      | brfss   | survey   | percent  | hra | 28.6  | 438000 | adults   | Dental visit             | No visit to dentist, dental hygenist or dental clinic within the past year                       | 
| mam2yrs        | health      | 2012 | 2008-2012 | 2008 2010 2011 2012      | brfss   | survey   | percent  | hra | 24.2  | 62000  | women    | Mammogram                | No mammogram within 2 years, women age 50-74                                                     | 
| crcscrn2       | health      | 2012 | 2008-2012 | 2008 2011 2012           | brfss   | survey   | percent  | hra | 34.2  | 170000 | adults   | Colorectal cancer screen | No recommended colorectal cancer screening, adults age 50-75                                     | 
| flushot        | health      | 2012 | 2008-2012 | 2008 2009 2010 2011 2012 | brfss   | survey   | percent  | hra | 61.6  | 943000 | adults   | Flu shot                 | Did not receive a flu shot within the past year                                                  | 
| genhlth2       | health      | 2012 | 2008-2012 | 2008 2009 2010 2011 2012 | brfss   | survey   | percent  | hra | 12.7  | 194000 | adults   | General health status    | Self-reported general health is fair or poor                                                     | 
| adult_uninsure | access      | 2012 | 2008-2012 | 2008 2009 2010 2011 2012 | acs     | survey   | percent  | hra | 16.4  | 220555 | adults   | Uninsurance (adult)      | Adults ages 18-64 without health insurance                                                       | 
| child_uninsure | access      | 2012 | 2008-2012 | 2008 2009 2010 2011 2012 | acs     | survey   | percent  | hra | 4.9   | 20753  | children | Uninsurance (child)      | Children ages 0-17 without health insurance                                                      | 
| pnc            | utilization | 2011 | 2010-2011 | 2010 2011                | birth   | vs       | percent  | hra | 4.5   | 1004   | births   | Late prenatal care       | Mother began prenatal care in the 3rd trimester of pregnancy or received no prenatal care at all | 
```