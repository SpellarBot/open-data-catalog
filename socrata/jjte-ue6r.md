# Total Prosser Run 12182014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/total-prosser-run-12182014-9fdb1) |
| Metadata | [Link](https://data.wa.gov/api/views/jjte-ue6r) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/jjte-ue6r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/jjte-ue6r/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | jjte-ue6r |
| Name | Total Prosser Run 12182014 |
| Created | 2014-12-19T00:33:33Z |
| Publication Date | 2014-12-19T00:36:01Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name              | Data Type | Render Type |
| ======== | ============== | =============== | ================= | ========= | =========== |
| Yes      | time           | year            | Year              | number    | number      |
| Yes      | numeric metric | chinook         | Chinook           | number    | number      |
| Yes      | numeric metric | jack_chin       | Jack Chin         | number    | number      |
| Yes      | numeric metric | steelhead       | Steelhead         | number    | number      |
| Yes      | numeric metric | steelheadw      | SteelheadW        | number    | number      |
| Yes      | numeric metric | sockeye_total   | Sockeye (Total)   | number    | number      |
| Yes      | numeric metric | coho            | Coho              | number    | number      |
| Yes      | numeric metric | jack_coho       | Jack Coho         | number    | number      |
| Yes      | numeric metric | lamprey         | Lamprey           | number    | number      |
| Yes      | numeric metric | chinook_total   | Chinook (Total)   | number    | number      |
| Yes      | numeric metric | steelhead_total | Steelhead (Total) | number    | number      |
| Yes      | numeric metric | coho_total      | Coho (Total)      | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jjte-ue6r d:1983-01-01T00:00:00.000Z m:chinook=748 m:sockeye_total=0 m:coho_total=0 m:jack_coho=0 m:steelhead_total=0 m:chinook_total=867 m:jack_chin=119 m:lamprey=0 m:coho=0 m:steelhead=0 m:steelheadw=0

series e:jjte-ue6r d:1984-01-01T00:00:00.000Z m:chinook=2321 m:sockeye_total=0 m:coho_total=0 m:jack_coho=0 m:steelhead_total=1668 m:chinook_total=2539 m:jack_chin=218 m:lamprey=0 m:coho=0 m:steelhead=1668 m:steelheadw=1668

series e:jjte-ue6r d:1985-01-01T00:00:00.000Z m:chinook=3815 m:sockeye_total=0 m:coho_total=0 m:jack_coho=0 m:steelhead_total=1299 m:chinook_total=4239 m:jack_chin=424 m:lamprey=0 m:coho=0 m:steelhead=1299 m:steelheadw=1299
```

## Meta Commands

```ls
metric m:chinook p:integer l:Chinook t:dataTypeName=number

metric m:jack_chin p:integer l:"Jack Chin" t:dataTypeName=number

metric m:steelhead p:integer l:Steelhead t:dataTypeName=number

metric m:steelheadw p:integer l:SteelheadW t:dataTypeName=number

metric m:sockeye_total p:integer l:"Sockeye (Total)" t:dataTypeName=number

metric m:coho p:integer l:Coho t:dataTypeName=number

metric m:jack_coho p:integer l:"Jack Coho" t:dataTypeName=number

metric m:lamprey p:integer l:Lamprey t:dataTypeName=number

metric m:chinook_total p:integer l:"Chinook (Total)" t:dataTypeName=number

metric m:steelhead_total p:integer l:"Steelhead (Total)" t:dataTypeName=number

metric m:coho_total p:integer l:"Coho (Total)" t:dataTypeName=number

entity e:jjte-ue6r l:"Total Prosser Run 12182014" t:url=https://data.wa.gov/api/views/jjte-ue6r

property e:jjte-ue6r t:meta.view v:id=jjte-ue6r v:averageRating=0 v:name="Total Prosser Run 12182014"

property e:jjte-ue6r t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:jjte-ue6r t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| year | chinook | jack_chin | steelhead | steelheadw | sockeye_total | coho | jack_coho | lamprey | chinook_total | steelhead_total | coho_total | 
| ==== | ======= | ========= | ========= | ========== | ============= | ==== | ========= | ======= | ============= | =============== | ========== | 
| 1983 | 748     | 119       | 0         | 0          | 0             | 0    | 0         | 0       | 867           | 0               | 0          | 
| 1984 | 2321    | 218       | 1668      | 1668       | 0             | 0    | 0         | 0       | 2539          | 1668            | 0          | 
| 1985 | 3815    | 424       | 1299      | 1299       | 0             | 0    | 0         | 0       | 4239          | 1299            | 0          | 
| 1986 | 8686    | 355       | 2983      | 2945       | 0             | 0    | 0         | 0       | 9041          | 2983            | 0          | 
| 1987 | 3758    | 326       | 2021      | 1851       | 0             | 0    | 0         | 0       | 4084          | 2021            | 0          | 
| 1988 | 3590    | 323       | 2284      | 2143       | 0             | 0    | 0         | 0       | 3913          | 2284            | 0          | 
| 1989 | 4112    | 242       | 1185      | 1097       | 0             | 0    | 0         | 0       | 4354          | 1185            | 0          | 
| 1990 | 2202    | 53        | 863       | 757        | 4             | 0    | 0         | 0       | 2255          | 863             | 0          | 
| 1991 | 2750    | 129       | 1594      | 1409       | 1             | 0    | 0         | 0       | 2879          | 1594            | 0          | 
| 1992 | 5782    | 245       | 1480      | 1321       | 7             | 137  | 53        | 0       | 6027          | 1480            | 190        | 
```