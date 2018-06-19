# Admissions to Maryland State-Supported Alcohol and Drug Abuse Treatment Programs by Patient Residence, SFY 2008-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/admissions-to-maryland-state-supported-alcohol-and-drug-abuse-treatment-programs-by-p-2008-1bf73) |
| Metadata | [Link](https://data.maryland.gov/api/views/9xzh-zqbf) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/9xzh-zqbf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/9xzh-zqbf/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 9xzh-zqbf |
| Name | Admissions to Maryland State-Supported Alcohol and Drug Abuse Treatment Programs by Patient Residence, SFY 2008-2012 |
| Attribution | Alcohol and Drug Abuse Administration |
| Category | Health and Human Services |
| Tags | alcohol, drug abuse, treatment, alcohol and drug abuse administration |
| Created | 2013-01-03T23:11:24Z |
| Publication Date | 2013-01-04T18:29:31Z |

## Description

Only includes data from state-supported treatment programs. Data is by state fiscal year (SFY) which runs from July 1 - June 30.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | patient_residence | Patient Residence | text      | text        |
| Yes      | numeric metric | fy_2008           | 2008 (SFY)        | number    | number      |
| Yes      | numeric metric | fy_2009           | 2009 (SFY)        | number    | number      |
| Yes      | numeric metric | fy_2010           | 2010 (SFY)        | number    | number      |
| Yes      | numeric metric | fy_2011           | 2011 (SFY)        | number    | number      |
| Yes      | numeric metric | fy_2012           | 2012 (SFY)        | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9xzh-zqbf d:2008-01-01T00:00:00.000Z t:patient_residence=Allegany m:fy_2010=848 m:fy_2012=687 m:fy_2011=729 m:fy_2008=929 m:fy_2009=851

series e:9xzh-zqbf d:2008-01-01T00:00:00.000Z t:patient_residence="Anne Arundel" m:fy_2010=3335 m:fy_2012=4173 m:fy_2011=3770 m:fy_2008=2839 m:fy_2009=3050

series e:9xzh-zqbf d:2008-01-01T00:00:00.000Z t:patient_residence="Baltimore City" m:fy_2010=12782 m:fy_2012=13427 m:fy_2011=13310 m:fy_2008=12484 m:fy_2009=12510
```

## Meta Commands

```ls
metric m:fy_2008 p:integer l:"2008 (SFY)" t:dataTypeName=number

metric m:fy_2009 p:integer l:"2009 (SFY)" t:dataTypeName=number

metric m:fy_2010 p:integer l:"2010 (SFY)" t:dataTypeName=number

metric m:fy_2011 p:integer l:"2011 (SFY)" t:dataTypeName=number

metric m:fy_2012 p:integer l:"2012 (SFY)" t:dataTypeName=number

entity e:9xzh-zqbf l:"Admissions to Maryland State-Supported Alcohol and Drug Abuse Treatment Programs by Patient Residence, SFY 2008-2012" t:attribution="Alcohol and Drug Abuse Administration" t:url=https://data.maryland.gov/api/views/9xzh-zqbf

property e:9xzh-zqbf t:meta.view v:id=9xzh-zqbf v:category="Health and Human Services" v:averageRating=0 v:name="Admissions to Maryland State-Supported Alcohol and Drug Abuse Treatment Programs by Patient Residence, SFY 2008-2012" v:attribution="Alcohol and Drug Abuse Administration"

property e:9xzh-zqbf t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:9xzh-zqbf t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| patient_residence | fy_2008 | fy_2009 | fy_2010 | fy_2011 | fy_2012 | 
| ================= | ======= | ======= | ======= | ======= | ======= | 
| Allegany          | 929     | 851     | 848     | 729     | 687     | 
| Anne Arundel      | 2839    | 3050    | 3335    | 3770    | 4173    | 
| Baltimore City    | 12484   | 12510   | 12782   | 13310   | 13427   | 
| Baltimore County  | 3737    | 3837    | 4299    | 4326    | 3663    | 
| Calvert           | 1043    | 1182    | 1440    | 1573    | 1568    | 
| Caroline          | 361     | 463     | 473     | 454     | 452     | 
| Carroll           | 864     | 928     | 1135    | 1276    | 928     | 
| Cecil             | 798     | 777     | 806     | 1109    | 1367    | 
| Charles           | 1223    | 1195    | 1186    | 1095    | 1098    | 
| Dorchester        | 572     | 593     | 654     | 720     | 680     | 
```