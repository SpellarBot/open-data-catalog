# City of Champaign Most Common Violation Tickets 1999-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-champaign-most-common-violation-tickets-1999-2011-47d5e) |
| Metadata | [Link](https://data.illinois.gov/api/views/nnhd-ku5t) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/nnhd-ku5t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/nnhd-ku5t/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | nnhd-ku5t |
| Name | City of Champaign Most Common Violation Tickets 1999-2011 |
| Attribution | City of Champaign |
| Category | Municipality |
| Tags | ticket, citation, violation, champaign |
| Created | 2012-11-29T15:57:27Z |
| Publication Date | 2012-11-29T17:55:40Z |

## Description

Based on the Champaign City Court Reporters for 2001-2011 2010 (attached). Blank Entries mean that data is unknown for that statistic.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name           | Data Type | Render Type |
| ======== | ============== | ============================ | ============== | ========= | =========== |
| Yes      | series tag     | violation_type               | Violation Type | text      | text        |
| Yes      | numeric metric | number_of_violations_in_2011 | 2011           | number    | number      |
| Yes      | numeric metric | number_of_violations_in_2010 | 2010           | number    | number      |
| Yes      | numeric metric | number_of_violations_in_2009 | 2009           | number    | number      |
| Yes      | numeric metric | number_of_violations_in_2008 | 2008           | number    | number      |
| Yes      | numeric metric | number_of_violations_in_2007 | 2007           | number    | number      |
| No       |                | _                            | 2006           | number    | number      |
| No       |                | _2                           | 2005           | number    | number      |
| No       |                | _3                           | 2004           | number    | number      |
| No       |                | _4                           | 2003           | number    | number      |
| No       |                | _5                           | 2002           | number    | number      |
| No       |                | _6                           | 2001           | number    | number      |
| No       |                | _7                           | 2000           | number    | number      |
| No       |                | _8                           | 1999           | number    | number      |
```

## Time Field

```ls
Value = 1999
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = _,_2,_3,_4,_5,_6,_7,_8
```

## Data Commands

```ls
series e:nnhd-ku5t d:1999-01-01T00:00:00.000Z t:violation_type="Sale of Tobacco to a Minor" m:number_of_violations_in_2011=16 m:number_of_violations_in_2010=21 m:number_of_violations_in_2007=5 m:number_of_violations_in_2008=1 m:number_of_violations_in_2009=9

series e:nnhd-ku5t d:1999-01-01T00:00:00.000Z t:violation_type="Minor Present in Liquor Establishment" m:number_of_violations_in_2011=10 m:number_of_violations_in_2010=3 m:number_of_violations_in_2008=2 m:number_of_violations_in_2009=10

series e:nnhd-ku5t d:1999-01-01T00:00:00.000Z t:violation_type="Unlawful Use of ID" m:number_of_violations_in_2011=16 m:number_of_violations_in_2010=23 m:number_of_violations_in_2007=23 m:number_of_violations_in_2008=15 m:number_of_violations_in_2009=8
```

## Meta Commands

```ls
metric m:number_of_violations_in_2011 p:integer l:2011 d:"Number of Violations in 2011" t:dataTypeName=number

metric m:number_of_violations_in_2010 p:integer l:2010 d:"Number of Violations in 2010" t:dataTypeName=number

metric m:number_of_violations_in_2009 p:integer l:2009 d:"Number of Violations in 2009" t:dataTypeName=number

metric m:number_of_violations_in_2008 p:integer l:2008 d:"Number of Violations in 2008" t:dataTypeName=number

metric m:number_of_violations_in_2007 p:integer l:2007 d:"Number of Violations in 2007" t:dataTypeName=number

entity e:nnhd-ku5t l:"City of Champaign Most Common Violation Tickets 1999-2011" t:attribution="City of Champaign" t:url=https://data.illinois.gov/api/views/nnhd-ku5t

property e:nnhd-ku5t t:meta.view v:id=nnhd-ku5t v:category=Municipality v:averageRating=0 v:name="City of Champaign Most Common Violation Tickets 1999-2011" v:attribution="City of Champaign"

property e:nnhd-ku5t t:meta.view.license v:name="Public Domain"

property e:nnhd-ku5t t:meta.view.owner v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"

property e:nnhd-ku5t t:meta.view.tableauthor v:id=v5dz-wzd9 v:screenName="Patrick East" v:displayName="Patrick East"
```

## Top Records

```ls
| violation_type                          | number_of_violations_in_2011 | number_of_violations_in_2010 | number_of_violations_in_2009 | number_of_violations_in_2008 | number_of_violations_in_2007 | _    | _2   | _3   | _4  | _5   | _6   | _7   | _8   | 
| ======================================= | ============================ | ============================ | ============================ | ============================ | ============================ | ==== | ==== | ==== | === | ==== | ==== | ==== | ==== | 
| Sale of Tobacco to a Minor              | 16                           | 21                           | 9                            | 1                            | 5                            |      |      |      |     |      |      |      |      | 
| Minor Present in Liquor Establishment   | 10                           | 3                            | 10                           | 2                            |                              | 28   | 26   | 12   | 10  | 19   |      |      |      | 
| Unlawful Use of ID                      | 16                           | 23                           | 8                            | 15                           | 23                           | 37   | 38   | 29   | 33  | 68   | 25   | 60   | 14   | 
| Possession of Tobacco Products by Minor |                              |                              | 22                           | 10                           | 23                           | 21   |      |      |     |      |      |      |      | 
| Throwing Dangerous Materials            | 35                           | 54                           | 13                           | 8                            | 22                           | 7    | 22   | 21   |     |      |      |      |      | 
| Underage Alcohol Offenses               | 1157                         | 1149                         | 1175                         | 1018                         | 1509                         | 1416 | 1977 | 1419 | 914 | 1129 | 1271 | 1690 | 1069 | 
| Theft                                   | 209                          | 215                          | 206                          | 190                          | 160                          | 110  | 172  | 200  | 177 | 225  | 253  | 221  | 189  | 
| Possession of Cannabis                  | 232                          | 212                          | 219                          | 279                          | 193                          | 161  | 164  | 164  | 148 | 168  | 149  | 239  | 194  | 
| Alcohol Possession on Public Property   | 376                          | 352                          | 312                          | 360                          | 258                          | 207  | 206  | 239  | 163 | 173  | 185  | 237  | 213  | 
| Noise                                   | 167                          | 195                          | 272                          | 218                          | 238                          | 167  | 125  | 112  | 93  | 111  | 118  | 201  | 109  | 
```