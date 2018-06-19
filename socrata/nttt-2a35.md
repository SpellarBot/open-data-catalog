# Adult and Children Vaccinations Provided

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adult-and-children-vaccinations-provided) |
| Metadata | [Link](https://data.austintexas.gov/api/views/nttt-2a35) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/nttt-2a35/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/nttt-2a35/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | nttt-2a35 |
| Name | Adult and Children Vaccinations Provided |
| Attribution | City of Austin |
| Category | Health |
| Tags | vaccinations, hhsd, vfc, immunized, fdhealth |
| Created | 2012-10-02T21:36:10Z |
| Publication Date | 2017-02-02T15:55:44Z |

## Description

Adults and Children immunized through our HHSD safety net system that are VFC eligible

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                    | Data Type     | Render Type   |
| ======== | ============== | =============== | ======================= | ============= | ============= |
| Yes      | time           | date            | Date                    | calendar_date | calendar_date |
| Yes      | series tag     | location        | Location                | text          | text          |
| Yes      | numeric metric | number_of_shots | Number of client visits | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:nttt-2a35 d:2012-06-30T00:00:00.000Z t:location="Big Shots Far South" m:number_of_shots=78

series e:nttt-2a35 d:2012-06-30T00:00:00.000Z t:location="Shots for Tots Far South" m:number_of_shots=167

series e:nttt-2a35 d:2012-07-31T00:00:00.000Z t:location="Big Shots Far South" m:number_of_shots=65
```

## Meta Commands

```ls
metric m:number_of_shots p:integer l:"Number of client visits" t:dataTypeName=number

entity e:nttt-2a35 l:"Adult and Children Vaccinations Provided" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/nttt-2a35

property e:nttt-2a35 t:meta.view v:id=nttt-2a35 v:category=Health v:attributionLink=http://www.austintexas.gov v:averageRating=0 v:name="Adult and Children Vaccinations Provided" v:attribution="City of Austin"

property e:nttt-2a35 t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:nttt-2a35 t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| date                | location                 | number_of_shots | 
| =================== | ======================== | =============== | 
| 2012-06-30T00:00:00 | Big Shots Far South      | 78              | 
| 2012-06-30T00:00:00 | Shots for Tots Far South | 167             | 
| 2012-07-31T00:00:00 | Big Shots Far South      | 65              | 
| 2012-07-31T00:00:00 | Shots for Tots Far South | 250             | 
| 2012-08-31T00:00:00 | Big Shots Far South      | 93              | 
| 2012-08-31T00:00:00 | Shots for Tots Far South | 774             | 
| 2012-09-30T00:00:00 | Big Shots Far South      | 86              | 
| 2012-09-30T00:00:00 | Shots for Tots Far South | 250             | 
| 2012-10-31T00:00:00 | Big Shots Far South      | 185             | 
| 2012-10-31T00:00:00 | Shots for Tots Far South | 319             | 
```