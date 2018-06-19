# Oil and Gas Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oil-and-gas-permits) |
| Metadata | [Link](https://data.mo.gov/api/views/y64b-aec2) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/y64b-aec2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/y64b-aec2/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | y64b-aec2 |
| Name | Oil and Gas Permits |
| Category | Natural Resources |
| Created | 2015-07-15T21:04:36Z |
| Publication Date | 2017-03-23T21:34:03Z |

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| No       |                | id            | ID            | text      | text        |
| Yes      | series tag     | county        | COUNTY        | text      | text        |
| Yes      | series tag     | countycode    | COUNTYCODE    | text      | text        |
| Yes      | series tag     | ogcnumber     | OGCNUMBER     | text      | text        |
| Yes      | series tag     | apiwebaddress | APIWEBADDRESS | url       | url         |
| Yes      | series tag     | coname        | CONAME        | text      | text        |
| Yes      | series tag     | leasename     | LEASENAME     | text      | text        |
| Yes      | series tag     | wellno        | WELLNO        | text      | text        |
| Yes      | series tag     | status        | STATUS        | text      | text        |
| Yes      | numeric metric | township      | TOWNSHIP      | number    | text        |
| Yes      | numeric metric | range         | RANGE         | number    | text        |
| Yes      | series tag     | rangedir      | RANGEDIR      | text      | text        |
| Yes      | numeric metric | section       | SECTION       | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:y64b-aec2 d:2015-07-15T14:04:45.000Z t:county=ADAIR t:status=ABANDONED t:rangedir=W t:ogcnumber=00001 t:countycode=001 t:leasename=MCGONIGLE t:wellno=1 t:apiwebaddress=http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00001.pdf t:coname="MAYSON OIL CO." m:township=63 m:range=13 m:section=20

series e:y64b-aec2 d:2015-07-15T14:04:45.000Z t:county=ADAIR t:status=ABANDONED t:rangedir=W t:ogcnumber=00002 t:countycode=001 t:leasename="LAUGHLLIN, GEORGE W." t:wellno=1 t:apiwebaddress=http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00002.pdf t:coname="MCGINNIS, WARD" m:township=62 m:range=15 m:section=18

series e:y64b-aec2 d:2015-07-15T14:04:45.000Z t:county=ADAIR t:status=ABANDONED t:rangedir=W t:ogcnumber=00003 t:countycode=001 t:leasename="CLARK, H. W." t:wellno=1 t:apiwebaddress=http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00003.pdf t:coname="EDDINGTON, J. W." m:township=63 m:range=14 m:section=8
```

## Meta Commands

```ls
metric m:township p:integer l:TOWNSHIP t:dataTypeName=number

metric m:range p:integer l:RANGE t:dataTypeName=number

metric m:section p:integer l:SECTION t:dataTypeName=number

entity e:y64b-aec2 l:"Oil and Gas Permits" t:url=https://data.mo.gov/api/views/y64b-aec2

property e:y64b-aec2 t:meta.view v:id=y64b-aec2 v:category="Natural Resources" v:averageRating=0 v:name="Oil and Gas Permits"

property e:y64b-aec2 t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:lastNotificationSeenAt=1492723347 v:displayName=Breanna

property e:y64b-aec2 t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:lastNotificationSeenAt=1492723347 v:displayName=Breanna
```

## Top Records

```ls
| :updated_at | id        | county | countycode | ogcnumber | apiwebaddress                                                          | coname             | leasename            | wellno | status    | township | range | rangedir | section | 
| =========== | ========= | ====== | ========== | ========= | ====================================================================== | ================== | ==================== | ====== | ========= | ======== | ===== | ======== | ======= | 
| 1436969085  | 001-00001 | ADAIR  | 001        | 00001     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00001.pdf, null] | MAYSON OIL CO.     | MCGONIGLE            | 1      | ABANDONED | 63       | 13    | W        | 20      | 
| 1436969085  | 001-00002 | ADAIR  | 001        | 00002     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00002.pdf, null] | MCGINNIS, WARD     | LAUGHLLIN, GEORGE W. | 1      | ABANDONED | 62       | 15    | W        | 18      | 
| 1436969085  | 001-00003 | ADAIR  | 001        | 00003     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00003.pdf, null] | EDDINGTON, J. W.   | CLARK, H. W.         | 1      | ABANDONED | 63       | 14    | W        | 8       | 
| 1436969085  | 001-00004 | ADAIR  | 001        | 00004     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00004.pdf, null] | MORROW & ROGERS    | COOLEY, J. A.        | 1      | ABANDONED | 64       | 17    | W        | 33      | 
| 1436969085  | 001-00005 | ADAIR  | 001        | 00005     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00005.pdf, null] | EDDINGTON, J. W.   | CLARK                | 1-A    | ABANDONED | 63       | 14    | W        | 8       | 
| 1436969085  | 001-00006 | ADAIR  | 001        | 00006     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00006.pdf, null] | EDDINGTON, J. W.   | CAPPS                | 1      | ABANDONED | 64       | 15    | W        | 31      | 
| 1436969085  | 001-00007 | ADAIR  | 001        | 00007     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00007.pdf, null] | CITIES SERVICE OIL | KOINS                | 1      | ABANDONED | 62       | 14    | W        | 22      | 
| 1436969085  | 001-00008 | ADAIR  | 001        | 00008     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00008.pdf, null] | NOVINGER, D. D.    | FEE                  | 1      | ABANDONED | 62       | 17    | W        | 10      | 
| 1436969085  | 001-00009 | ADAIR  | 001        | 00009     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00009.pdf, null] | CITIES SERVICE OIL | CRAGG                | 1      | ABANDONED | 64       | 14    | W        | 21      | 
| 1436969085  | 001-00010 | ADAIR  | 001        | 00010     | [http://www.dnr.mo.gov/geology/geosrv/ogc/permits/001-00010.pdf, null] | B.F. & S. OIL CO.  | MONTGOMERY, DWANE    | 1      | ABANDONED | 64       | 16    | W        | 29      | 
```