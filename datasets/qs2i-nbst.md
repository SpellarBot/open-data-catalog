# Report Card 4c Tax TAT

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/report-card-4c-tax-tat-82b4d) |
| Metadata | [Link](https://data.hawaii.gov/api/views/qs2i-nbst) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/qs2i-nbst/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/qs2i-nbst/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | qs2i-nbst |
| Name | Report Card 4c Tax TAT |
| Created | 2012-11-19T02:37:30Z |
| Publication Date | 2012-11-19T02:38:22Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | year                        | Year                        | number    | text        |
| Yes      | numeric metric | transient_accommodation_tax | Transient Accommodation Tax | money     | money       |
| Yes      | numeric metric | dollars                     | 1982 Dollars                | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qs2i-nbst d:1990-01-01T00:00:00.000Z m:dollars=6043134 m:transient_accommodation_tax=8345568

series e:qs2i-nbst d:1991-01-01T00:00:00.000Z m:dollars=5265590 m:transient_accommodation_tax=7793073

series e:qs2i-nbst d:1992-01-01T00:00:00.000Z m:dollars=5212667 m:transient_accommodation_tax=8084847
```

## Meta Commands

```ls
metric m:transient_accommodation_tax p:integer l:"Transient Accommodation Tax" t:dataTypeName=money

metric m:dollars p:integer l:"1982 Dollars" t:dataTypeName=money

entity e:qs2i-nbst l:"Report Card 4c Tax TAT" t:url=https://data.hawaii.gov/api/views/qs2i-nbst

property e:qs2i-nbst t:meta.view v:id=qs2i-nbst v:averageRating=0 v:name="Report Card 4c Tax TAT"

property e:qs2i-nbst t:meta.view.owner v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:displayName="Daniel Nahoopii"

property e:qs2i-nbst t:meta.view.tableauthor v:id=pvmv-89ja v:screenName="Daniel Nahoopii" v:roleName=editor v:displayName="Daniel Nahoopii"
```

## Top Records

```ls
| year | transient_accommodation_tax | dollars | 
| ==== | =========================== | ======= | 
| 1990 | 8345568                     | 6043134 | 
| 1991 | 7793073                     | 5265590 | 
| 1992 | 8084847                     | 5212667 | 
| 1993 | 7540577                     | 4709917 | 
| 1994 | 8649740                     | 5258200 | 
| 1995 | 10561757                    | 6283020 | 
| 1996 | 12398251                    | 7263182 | 
| 1997 | 12689206                    | 7381738 | 
| 1998 | 12588189                    | 7340052 | 
| 1999 | 15336694                    | 8849795 | 
```