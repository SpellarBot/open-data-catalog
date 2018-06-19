# Number of Drug and Alcohol-Related Intoxication Deaths by County of Incident, 2007-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-drug-and-alcohol-related-intoxication-deaths-by-county-of-incident-2007-2013-2ab0c) |
| Metadata | [Link](https://data.maryland.gov/api/views/eprz-kexz) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/eprz-kexz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/eprz-kexz/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | eprz-kexz |
| Name | Number of Drug and Alcohol-Related Intoxication Deaths by County of Incident, 2007-2013 |
| Attribution | Vital Statistics Administration, Maryland Department of Health and Mental Hygiene |
| Category | Health and Human Services |
| Tags | drug, alcohol, poison, intox, death, mortality, medical examiner, vital statistics |
| Created | 2014-10-02T16:24:40Z |
| Publication Date | 2014-10-02T21:18:06Z |

## Description

Drug and alcohol-related Intoxication death data is prepared using drug and alcohol intoxication data housed in a registry developed and maintained by the Vital Statistics Administration (VSA) of the Maryland Department of Health and Mental Hygiene (DHMH). The methodology for reporting on drug-related intoxication deaths in Maryland was developed by VSA with assistance from the DHMH Alcohol and Drug Abuse Administration, the Office of the Chief Medical Examiner (OCME) and the Maryland Poison Control Center. Assistance was also provided by authors of a 2008 Baltimore City Health Department report on intoxication deaths. Data in this table is by incident location, where the death occurred, rather than by county of residence.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | county     | County | text      | text        |
| Yes      | numeric metric | 2007       | 2007   | number    | number      |
| Yes      | numeric metric | 2008       | 2008   | number    | number      |
| Yes      | numeric metric | 2009       | 2009   | number    | number      |
| Yes      | numeric metric | 2010       | 2010   | number    | number      |
| Yes      | numeric metric | 2011       | 2011   | number    | number      |
| Yes      | numeric metric | 2012       | 2012   | number    | number      |
| Yes      | numeric metric | 2013       | 2013   | number    | number      |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:eprz-kexz d:2007-01-01T00:00:00.000Z t:county=Allegany m:2008=9 m:2009=9 m:2007=14 m:2013=15 m:2012=14 m:2011=12 m:2010=15

series e:eprz-kexz d:2007-01-01T00:00:00.000Z t:county="Anne Arundel" m:2008=70 m:2009=63 m:2007=71 m:2013=78 m:2012=83 m:2011=79 m:2010=56

series e:eprz-kexz d:2007-01-01T00:00:00.000Z t:county="Baltimore City" m:2008=184 m:2009=239 m:2007=287 m:2013=246 m:2012=225 m:2011=167 m:2010=172
```

## Meta Commands

```ls
metric m:2007 p:integer l:2007 t:dataTypeName=number

metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2013 p:integer l:2013 t:dataTypeName=number

entity e:eprz-kexz l:"Number of Drug and Alcohol-Related Intoxication Deaths by County of Incident, 2007-2013" t:attribution="Vital Statistics Administration, Maryland Department of Health and Mental Hygiene" t:url=https://data.maryland.gov/api/views/eprz-kexz

property e:eprz-kexz t:meta.view v:id=eprz-kexz v:category="Health and Human Services" v:attributionLink=http://dhmh.maryland.gov/vsa/SitePages/Home.aspx v:averageRating=0 v:name="Number of Drug and Alcohol-Related Intoxication Deaths by County of Incident, 2007-2013" v:attribution="Vital Statistics Administration, Maryland Department of Health and Mental Hygiene"

property e:eprz-kexz t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:eprz-kexz t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| county           | 2007 | 2008 | 2009 | 2010 | 2011 | 2012 | 2013 | 
| ================ | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| Allegany         | 14   | 9    | 9    | 15   | 12   | 14   | 15   | 
| Anne Arundel     | 71   | 70   | 63   | 56   | 79   | 83   | 78   | 
| Baltimore City   | 287  | 184  | 239  | 172  | 167  | 225  | 246  | 
| Baltimore County | 131  | 118  | 106  | 115  | 107  | 119  | 144  | 
| Calvert          | 14   | 9    | 14   | 6    | 12   | 12   | 6    | 
| Caroline         | 1    | 4    | 2    | 2    | 11   | 4    | 2    | 
| Carroll          | 14   | 17   | 22   | 15   | 8    | 29   | 24   | 
| Cecil            | 25   | 10   | 24   | 24   | 28   | 25   | 26   | 
| Charles          | 13   | 16   | 11   | 13   | 11   | 13   | 9    | 
| Dorchester       | 4    | 5    | 2    | 6    | 2    | 5    | 5    | 
```