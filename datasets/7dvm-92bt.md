# Population Estimates 2000-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/population-estimates-2000-2013-7fc99) |
| Metadata | [Link](https://data.maryland.gov/api/views/7dvm-92bt) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/7dvm-92bt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/7dvm-92bt/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 7dvm-92bt |
| Name | Population Estimates 2000-2014 |
| Attribution | Maryland Department of Planning |
| Category | Planning |
| Tags | total, resident, population, planning, mdp |
| Created | 2014-09-03T16:49:27Z |
| Publication Date | 2015-11-17T17:15:40Z |

## Description

Maryland Total Resident Population from 2000 to 2014 based on US Census data.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | year            | Year             | text      | text        |
| Yes      | numeric metric | population_2000 | Population, 2000 | number    | number      |
| Yes      | numeric metric | population_2001 | Population, 2001 | number    | number      |
| Yes      | numeric metric | population_2002 | Population, 2002 | number    | number      |
| Yes      | numeric metric | population_2003 | Population, 2003 | number    | number      |
| Yes      | numeric metric | population_2004 | Population, 2004 | number    | number      |
| Yes      | numeric metric | population_2005 | Population, 2005 | number    | number      |
| Yes      | numeric metric | population_2006 | Population, 2006 | number    | number      |
| Yes      | numeric metric | population_2007 | Population, 2007 | number    | number      |
| Yes      | numeric metric | population_2008 | Population, 2008 | number    | number      |
| Yes      | numeric metric | population_2009 | Population, 2009 | number    | number      |
| Yes      | numeric metric | population_2010 | Population, 2010 | number    | number      |
| Yes      | numeric metric | population_2011 | Population, 2011 | number    | number      |
| Yes      | numeric metric | population_2012 | Population, 2012 | number    | number      |
| Yes      | numeric metric | population_2013 | Population, 2013 | number    | number      |
| Yes      | numeric metric | population_2014 | Population, 2014 | number    | number      |
```

## Time Field

```ls
Value = 2000
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7dvm-92bt d:2000-01-01T00:00:00.000Z t:year=MARYLAND m:population_2001=5374691 m:population_2000=5311034 m:population_2003=5496269 m:population_2002=5440389 m:population_2005=5592379 m:population_2004=5546935 m:population_2007=5653408 m:population_2006=5627367 m:population_2009=5730388 m:population_2008=5684965 m:population_2013=5938737 m:population_2014=5976407 m:population_2011=5843833 m:population_2012=5891819 m:population_2010=5788101

series e:7dvm-92bt d:2000-01-01T00:00:00.000Z t:year="Allegany County" m:population_2001=74525 m:population_2000=74804 m:population_2003=74076 m:population_2002=74204 m:population_2005=73979 m:population_2004=74408 m:population_2007=74449 m:population_2006=73980 m:population_2009=75101 m:population_2008=74638 m:population_2013=73531 m:population_2014=72952 m:population_2011=74527 m:population_2012=73883 m:population_2010=74988

series e:7dvm-92bt d:2000-01-01T00:00:00.000Z t:year="Anne Arundel County" m:population_2001=498559 m:population_2000=491670 m:population_2003=507769 m:population_2002=504884 m:population_2005=516171 m:population_2004=513259 m:population_2007=520503 m:population_2006=517698 m:population_2009=532395 m:population_2008=525304 m:population_2013=556348 m:population_2014=560133 m:population_2011=544976 m:population_2012=550715 m:population_2010=539174
```

## Meta Commands

```ls
metric m:population_2000 p:integer l:"Population, 2000" t:dataTypeName=number

metric m:population_2001 p:integer l:"Population, 2001" t:dataTypeName=number

metric m:population_2002 p:integer l:"Population, 2002" t:dataTypeName=number

metric m:population_2003 p:integer l:"Population, 2003" t:dataTypeName=number

metric m:population_2004 p:integer l:"Population, 2004" t:dataTypeName=number

metric m:population_2005 p:integer l:"Population, 2005" t:dataTypeName=number

metric m:population_2006 p:integer l:"Population, 2006" t:dataTypeName=number

metric m:population_2007 p:integer l:"Population, 2007" t:dataTypeName=number

metric m:population_2008 p:integer l:"Population, 2008" t:dataTypeName=number

metric m:population_2009 p:integer l:"Population, 2009" t:dataTypeName=number

metric m:population_2010 p:integer l:"Population, 2010" t:dataTypeName=number

metric m:population_2011 p:integer l:"Population, 2011" t:dataTypeName=number

metric m:population_2012 p:integer l:"Population, 2012" t:dataTypeName=number

metric m:population_2013 p:integer l:"Population, 2013" t:dataTypeName=number

metric m:population_2014 p:integer l:"Population, 2014" t:dataTypeName=number

entity e:7dvm-92bt l:"Population Estimates 2000-2014" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/7dvm-92bt

property e:7dvm-92bt t:meta.view v:id=7dvm-92bt v:category=Planning v:attributionLink=http://planning.maryland.gov/msdc/S2_Estimate.shtml v:averageRating=0 v:name="Population Estimates 2000-2014" v:attribution="Maryland Department of Planning"

property e:7dvm-92bt t:meta.view.owner v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:displayName=MDP

property e:7dvm-92bt t:meta.view.tableauthor v:id=85mq-rt9c v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:screenName=MDP v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:roleName=editor v:displayName=MDP
```

## Top Records

```ls
| year                | population_2000 | population_2001 | population_2002 | population_2003 | population_2004 | population_2005 | population_2006 | population_2007 | population_2008 | population_2009 | population_2010 | population_2011 | population_2012 | population_2013 | population_2014 | 
| =================== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | =============== | 
| MARYLAND            | 5311034         | 5374691         | 5440389         | 5496269         | 5546935         | 5592379         | 5627367         | 5653408         | 5684965         | 5730388         | 5788101         | 5843833         | 5891819         | 5938737         | 5976407         | 
| Allegany County     | 74804           | 74525           | 74204           | 74076           | 74408           | 73979           | 73980           | 74449           | 74638           | 75101           | 74988           | 74527           | 73883           | 73531           | 72952           | 
| Anne Arundel County | 491670          | 498559          | 504884          | 507769          | 513259          | 516171          | 517698          | 520503          | 525304          | 532395          | 539174          | 544976          | 550715          | 556348          | 560133          | 
| Baltimore City      | 649086          | 640733          | 634115          | 629033          | 624222          | 621560          | 621109          | 620306          | 620184          | 620509          | 621317          | 620889          | 622950          | 623404          | 622793          | 
| Baltimore County    | 755598          | 762925          | 770147          | 777756          | 784371          | 789110          | 793733          | 796073          | 798651          | 801808          | 806233          | 813136          | 818425          | 823883          | 826925          | 
| Calvert County      | 75118           | 77218           | 80153           | 83007           | 84928           | 86294           | 87043           | 87445           | 87788           | 88244           | 88940           | 89272           | 89661           | 90480           | 90613           | 
| Caroline County     | 29773           | 29814           | 30054           | 30553           | 30653           | 31416           | 32214           | 32720           | 32983           | 33013           | 33068           | 32919           | 32628           | 32642           | 32538           | 
| Carroll County      | 151454          | 154037          | 157930          | 161389          | 163915          | 165519          | 166950          | 167390          | 167433          | 167028          | 167220          | 167260          | 167190          | 167494          | 167830          | 
| Cecil County        | 86448           | 88228           | 90061           | 92444           | 94809           | 96836           | 98821           | 99628           | 100232          | 100816          | 101160          | 101653          | 101822          | 101999          | 102383          | 
| Charles County      | 121229          | 124745          | 128079          | 131942          | 135601          | 138560          | 141164          | 142721          | 143783          | 144804          | 147118          | 149242          | 150791          | 152900          | 154747          | 
```