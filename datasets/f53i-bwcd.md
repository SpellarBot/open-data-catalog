# Total Number of Drug Intoxication Deaths by Selected Substances: 2007-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-number-of-drug-intoxication-deaths-by-selected-substances-2007-2012-66e68) |
| Metadata | [Link](https://data.maryland.gov/api/views/f53i-bwcd) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/f53i-bwcd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/f53i-bwcd/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | f53i-bwcd |
| Name | Total Number of Drug Intoxication Deaths by Selected Substances: 2007-2015 |
| Attribution | DHMH (Department of Health and Mental Hygiene) |
| Category | Health and Human Services |
| Tags | substance abuse, drug, overdose, heroin, alcohol, rx, opiod, dhmh |
| Created | 2013-07-15T14:06:07Z |
| Publication Date | 2016-10-25T16:45:04Z |

## Description

These data show total annual Maryland drug intoxication deaths from 2007 to 2015, broken down by substance. Since an intoxication death may involve more than one substance, counts of deaths related to specific substances do not sum to the total number of deaths. Benzodiazepine deaths include deaths caused by benzodiazepines and related drugs with similar sedative effects.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                       | Data Type | Render Type |
| ======== | ============== | ========================= | ========================== | ========= | =========== |
| Yes      | time           | calendar_year             | Calendar Year              | number    | text        |
| Yes      | numeric metric | heroin_deaths             | Heroin Deaths              | number    | number      |
| Yes      | numeric metric | prescription_opiod_deaths | Prescription Opioid Deaths | number    | number      |
| Yes      | numeric metric | alcohol_deaths            | Alcohol Deaths             | number    | number      |
| Yes      | numeric metric | benzodiazepine_deaths     | Benzodiazepine Deaths      | number    | number      |
| Yes      | numeric metric | cocaine_deaths            | Cocaine Deaths             | number    | number      |
| Yes      | numeric metric | fentanyl_deaths           | Fentanyl Deaths            | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:f53i-bwcd d:2008-01-01T00:00:00.000Z m:heroin_deaths=289 m:cocaine_deaths=157 m:prescription_opiod_deaths=280 m:alcohol_deaths=175 m:fentanyl_deaths=25 m:benzodiazepine_deaths=48

series e:f53i-bwcd d:2009-01-01T00:00:00.000Z m:heroin_deaths=360 m:cocaine_deaths=162 m:prescription_opiod_deaths=251 m:alcohol_deaths=162 m:fentanyl_deaths=27 m:benzodiazepine_deaths=52

series e:f53i-bwcd d:2010-01-01T00:00:00.000Z m:heroin_deaths=238 m:cocaine_deaths=135 m:prescription_opiod_deaths=311 m:alcohol_deaths=160 m:fentanyl_deaths=39 m:benzodiazepine_deaths=58
```

## Meta Commands

```ls
metric m:heroin_deaths p:integer l:"Heroin Deaths" t:dataTypeName=number

metric m:prescription_opiod_deaths p:integer l:"Prescription Opioid Deaths" t:dataTypeName=number

metric m:alcohol_deaths p:integer l:"Alcohol Deaths" t:dataTypeName=number

metric m:benzodiazepine_deaths p:integer l:"Benzodiazepine Deaths" t:dataTypeName=number

metric m:cocaine_deaths p:integer l:"Cocaine Deaths" t:dataTypeName=number

metric m:fentanyl_deaths p:integer l:"Fentanyl Deaths" t:dataTypeName=number

entity e:f53i-bwcd l:"Total Number of Drug Intoxication Deaths by Selected Substances: 2007-2015" t:attribution="DHMH (Department of Health and Mental Hygiene)" t:url=https://data.maryland.gov/api/views/f53i-bwcd

property e:f53i-bwcd t:meta.view v:id=f53i-bwcd v:category="Health and Human Services" v:attributionLink=http://bha.dhmh.maryland.gov/OVERDOSE_PREVENTION/Pages/Data-and-Reports.aspx v:averageRating=0 v:name="Total Number of Drug Intoxication Deaths by Selected Substances: 2007-2015" v:attribution="DHMH (Department of Health and Mental Hygiene)"

property e:f53i-bwcd t:meta.view.license v:name="Public Domain"

property e:f53i-bwcd t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:f53i-bwcd t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| calendar_year | heroin_deaths | prescription_opiod_deaths | alcohol_deaths | benzodiazepine_deaths | cocaine_deaths | fentanyl_deaths | 
| ============= | ============= | ========================= | ============== | ===================== | ============== | =============== | 
| 2008          | 289           | 280                       | 175            | 48                    | 157            | 25              | 
| 2009          | 360           | 251                       | 162            | 52                    | 162            | 27              | 
| 2010          | 238           | 311                       | 160            | 58                    | 135            | 39              | 
| 2011          | 247           | 342                       | 161            | 68                    | 148            | 26              | 
| 2012          | 392           | 311                       | 195            | 73                    | 153            | 29              | 
| 2007          | 399           | 302                       | 187            | 37                    | 248            | 26              | 
| 2013          | 464           | 316                       | 238            | 69                    | 154            | 58              | 
| 2014          | 578           | 330                       | 270            | 103                   | 198            | 186             | 
| 2015          | 748           | 351                       | 309            | 91                    | 221            | 340             | 
```