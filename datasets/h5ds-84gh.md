# Hawaii Renewable Portfolio Standards ( RPS) (Source: Hawaii Public Utilities Commission)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-renewable-portfolio-standards-rps-source-hawaii-public-utilities-commission-7c05c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/h5ds-84gh) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/h5ds-84gh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/h5ds-84gh/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | h5ds-84gh |
| Name | Hawaii Renewable Portfolio Standards ( RPS) (Source: Hawaii Public Utilities Commission) |
| Created | 2012-11-16T00:31:02Z |
| Publication Date | 2016-07-25T21:45:40Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name                | Data Type     | Render Type   |
| ======== | ============== | =========== | =================== | ============= | ============= |
| No       |                | year        | Year                | number        | text          |
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
series e:h5ds-84gh d:2013-12-31T00:00:00.000Z m:state_total=17.97 m:helco=48.1 m:kiuc=13.7 m:meco=29.1 m:heco=11.7

series e:h5ds-84gh d:2012-12-31T00:00:00.000Z m:state_total=13.74 m:helco=46.7 m:kiuc=11 m:meco=20.8 m:heco=7.6

series e:h5ds-84gh d:2011-12-31T00:00:00.000Z m:state_total=11.91 m:helco=41.1 m:kiuc=10.5 m:meco=17.1 m:heco=6.7
```

## Meta Commands

```ls
metric m:heco p:float l:HECO/Oahu t:dataTypeName=percent

metric m:helco p:float l:"HELCO/Hawaii Island" t:dataTypeName=percent

metric m:meco p:float l:"MECO/Maui County" t:dataTypeName=percent

metric m:kiuc p:float l:KIUC/Kauai t:dataTypeName=percent

metric m:state_total p:float l:"State Total" t:dataTypeName=percent

entity e:h5ds-84gh l:"Hawaii Renewable Portfolio Standards ( RPS)  (Source: Hawaii Public Utilities Commission)" t:url=https://data.hawaii.gov/api/views/h5ds-84gh

property e:h5ds-84gh t:meta.view v:id=h5ds-84gh v:averageRating=0 v:name="Hawaii Renewable Portfolio Standards ( RPS)  (Source: Hawaii Public Utilities Commission)"

property e:h5ds-84gh t:meta.view.owner v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:displayName="Jerome Koehler"

property e:h5ds-84gh t:meta.view.tableauthor v:id=kpux-wcj8 v:screenName="Jerome Koehler" v:roleName=publisher v:displayName="Jerome Koehler"
```

## Top Records

```ls
| year | heco | helco | meco | kiuc | state_total | date                | 
| ==== | ==== | ===== | ==== | ==== | =========== | =================== | 
| 2013 | 11.7 | 48.1  | 29.1 | 13.7 | 17.97       | 2013-12-31T00:00:00 | 
| 2012 | 7.6  | 46.7  | 20.8 | 11   | 13.74       | 2012-12-31T00:00:00 | 
| 2011 | 6.7  | 41.1  | 17.1 | 10.5 | 11.91       | 2011-12-31T00:00:00 | 
| 2010 | 4.7  | 34.6  | 15.3 | 9.1  | 9.49        | 2010-12-31T00:00:00 | 
| 2009 | 5.1  | 33.7  | 13.9 | 9.6  | 9.53        | 2009-12-31T00:00:00 | 
| 2014 | 15.2 | 47.4  | 33.7 | 17.5 | 21.14       | 2014-12-31T12:00:00 | 
| 2015 | 17.2 | 48.7  | 35.4 | 27.3 | 23.42       | 2015-12-31T12:00:00 | 
```