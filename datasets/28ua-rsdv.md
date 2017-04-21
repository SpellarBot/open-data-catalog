# Hawaii Energy Efficiency Portfolio Standards (EEPS) (Source: Hawaii Public Utilities Commission)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-energy-efficiency-portfolio-standards-eeps-source-hawaii-public-utilities-commissio-45969) |
| Metadata | [Link](https://data.hawaii.gov/api/views/28ua-rsdv) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/28ua-rsdv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/28ua-rsdv/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 28ua-rsdv |
| Name | Hawaii Energy Efficiency Portfolio Standards (EEPS) (Source: Hawaii Public Utilities Commission) |
| Created | 2012-11-16T20:07:16Z |
| Publication Date | 2015-07-13T22:16:09Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                | Data Type     | Render Type   |
| ======== | ============== | =========== | =================== | ============= | ============= |
| No       |                | year        | Year                | number        | number        |
| Yes      | numeric metric | heco        | HECO/Oahu           | percent       | percent       |
| Yes      | numeric metric | helco       | HELCO/Hawaii Island | percent       | percent       |
| Yes      | numeric metric | meco        | MECO/Maui County    | percent       | percent       |
| Yes      | numeric metric | kiuc        | KIUC/Kauai          | percent       | percent       |
| Yes      | numeric metric | state_total | State Total         | percent       | percent       |
| Yes      | time           | date        | Date                | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:28ua-rsdv d:2008-12-31T00:00:00.000Z m:state_total=8.3 m:helco=5.3 m:kiuc=4.2 m:meco=8.7 m:heco=9

series e:28ua-rsdv d:2009-12-31T00:00:00.000Z m:state_total=9.3 m:helco=5.7 m:kiuc=4.4 m:meco=9.8 m:heco=10

series e:28ua-rsdv d:2010-12-31T00:00:00.000Z m:state_total=10.9 m:helco=7.4 m:kiuc=3.9 m:meco=10.8 m:heco=11.8
```

## Meta Commands

```ls
metric m:heco p:float l:HECO/Oahu t:dataTypeName=percent

metric m:helco p:float l:"HELCO/Hawaii Island" t:dataTypeName=percent

metric m:meco p:float l:"MECO/Maui County" t:dataTypeName=percent

metric m:kiuc p:float l:KIUC/Kauai t:dataTypeName=percent

metric m:state_total p:float l:"State Total" t:dataTypeName=percent

entity e:28ua-rsdv l:"Hawaii Energy Efficiency Portfolio Standards (EEPS)  (Source: Hawaii Public Utilities Commission)" t:url=https://data.hawaii.gov/api/views/28ua-rsdv

property e:28ua-rsdv t:meta.view v:id=28ua-rsdv v:averageRating=0 v:name="Hawaii Energy Efficiency Portfolio Standards (EEPS)  (Source: Hawaii Public Utilities Commission)"

property e:28ua-rsdv t:meta.view.owner v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:displayName="Jerome Koehler"

property e:28ua-rsdv t:meta.view.tableauthor v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```

## Top Records

```ls
| year | heco | helco | meco | kiuc | state_total | date                | 
| ==== | ==== | ===== | ==== | ==== | =========== | =================== | 
| 2008 | 9.0  | 5.3   | 8.7  | 4.2  | 8.3         | 2008-12-31T00:00:00 | 
| 2009 | 10   | 5.7   | 9.8  | 4.4  | 9.3         | 2009-12-31T00:00:00 | 
| 2010 | 11.8 | 7.4   | 10.8 | 3.9  | 10.9        | 2010-12-31T00:00:00 | 
| 2011 | 13.1 | 8.8   | 12.0 | 4.2  | 12.1        | 2011-12-31T00:00:00 | 
| 2012 | 15.6 | 11    | 14   | 5.6  | 14.5        | 2012-12-31T00:00:00 | 
| 2013 | 16.9 | 12.6  | 15.3 | 5.2  | 15.7        | 2013-12-31T00:00:00 | 
| 2014 | 18.1 | 13.5  | 16.1 | 5    | 16.8        |                     | 
```