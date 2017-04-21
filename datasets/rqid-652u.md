# MDTA Accidents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mdta-accidents) |
| Metadata | [Link](https://data.maryland.gov/api/views/rqid-652u) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/rqid-652u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/rqid-652u/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | rqid-652u |
| Name | MDTA Accidents |
| Category | Public Safety |
| Tags | accidents, mdta, transportation authority, accident, crash, maryland transportation authority |
| Created | 2012-10-12T19:14:37Z |
| Publication Date | 2016-05-02T14:50:10Z |

## Description

Includes accidents that occured on MD Transportation Authority (MDTA) facilities, or were within a concurrent jurisdiction and were responded to by MDTA Police. MDTA facilities are the Francis Scott Key Bridge (I-695), John F. Kennedy Memorial Highway (I-95), Thomas J. Hatem Memorial Bridge (US 40), Fort McHenry Tunnel (I-95), Baltimore Harbor Tunnel (I-895), the Bay Bridge (US 50/301), Governor Harry W. Nice Memorial Bridge (US 301), and Intercounty Connector (ICC/MD200). MDTA Police are also responsible for accidents at BWI Airport and the Port of Baltimore.  This dataset will be updated monthly by the MD Transportation Authority

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | series tag     | cc_number     | CC Number     | text          | text          |
| Yes      | time           | date          | Date          | calendar_date | calendar_date |
| Yes      | numeric metric | time          | Time          | number        | number        |
| Yes      | series tag     | accident_type | Accident Type | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:rqid-652u d:2012-07-01T00:00:00.000Z t:cc_number=12T008826 t:accident_type=PD m:time=1630

series e:rqid-652u d:2012-07-02T00:00:00.000Z t:cc_number=12L005385 t:accident_type=PD m:time=1229

series e:rqid-652u d:2012-07-02T00:00:00.000Z t:cc_number=12L005388 t:accident_type=PD m:time=1229
```

## Meta Commands

```ls
metric m:time p:integer l:Time d:"Military Time format. Reflects the reported time the accident occured" t:dataTypeName=number

entity e:rqid-652u l:"MDTA Accidents" t:url=https://data.maryland.gov/api/views/rqid-652u

property e:rqid-652u t:meta.view v:id=rqid-652u v:category="Public Safety" v:averageRating=0 v:name="MDTA Accidents"

property e:rqid-652u t:meta.view.owner v:id=5x9h-2zmw v:screenName="Sarah Clifford" v:displayName="Sarah Clifford"

property e:rqid-652u t:meta.view.tableauthor v:id=5x9h-2zmw v:screenName="Sarah Clifford" v:roleName=publisher v:displayName="Sarah Clifford"
```

## Top Records

```ls
| cc_number | date                | time | accident_type | 
| ========= | =================== | ==== | ============= | 
| 12T008826 | 2012-07-01T00:00:00 | 1630 | PD            | 
| 12L005385 | 2012-07-02T00:00:00 | 1229 | PD            | 
| 12L005388 | 2012-07-02T00:00:00 | 1229 | PD            | 
| 12T008851 | 2012-07-02T00:00:00 | 445  | PI            | 
| 12T008858 | 2012-07-02T00:00:00 | 802  | PD            | 
| 12T008860 | 2012-07-02T00:00:00 | 832  | PD            | 
| 12T008863 | 2012-07-02T00:00:00 | 905  | PI            | 
| 12T008864 | 2012-07-02T00:00:00 | 847  | PD            | 
| 12T008901 | 2012-07-03T00:00:00 | 634  | PD            | 
| 12T008997 | 2012-07-05T00:00:00 | 2232 | PI            | 
```