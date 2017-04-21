# Passenger Counts International and Domestic May 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/passenger-counts-international-and-domestic-may-2013-a4a79) |
| Metadata | [Link](https://data.hawaii.gov/api/views/btiw-7vk4) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/btiw-7vk4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/btiw-7vk4/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | btiw-7vk4 |
| Name | Passenger Counts International and Domestic May 2013 |
| Attribution | DBEDT |
| Category | Economic Development |
| Created | 2013-05-30T17:35:51Z |
| Publication Date | 2013-05-30T21:14:00Z |

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | time           | date       | date       | text      | text        |
| Yes      | series tag     | day        | day        | text      | text        |
| Yes      | series tag     | flight     | flight     | text      | text        |
| Yes      | series tag     | location   | location   | text      | text        |
| Yes      | numeric metric | passengers | passengers | number    | number      |
```

## Time Field

```ls
Value = date
Format & Zone = MM/dd/yy
```

## Data Commands

```ls
series e:btiw-7vk4 d:2013-05-01T00:00:00.000Z t:flight=International t:location=Japan t:day=Wed m:passengers=4069

series e:btiw-7vk4 d:2013-05-02T00:00:00.000Z t:flight=International t:location=Japan t:day=Thu m:passengers=4699

series e:btiw-7vk4 d:2013-05-03T00:00:00.000Z t:flight=International t:location=Japan t:day=Fri m:passengers=4403
```

## Meta Commands

```ls
metric m:passengers p:integer l:passengers t:dataTypeName=number

entity e:btiw-7vk4 l:"Passenger Counts  International and Domestic May 2013" t:attribution=DBEDT t:url=https://data.hawaii.gov/api/views/btiw-7vk4

property e:btiw-7vk4 t:meta.view v:id=btiw-7vk4 v:category="Economic Development" v:averageRating=0 v:name="Passenger Counts  International and Domestic May 2013" v:attribution=DBEDT

property e:btiw-7vk4 t:meta.view.license v:name="Public Domain"

property e:btiw-7vk4 t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:btiw-7vk4 t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| date    | day | flight        | location | passengers | 
| ======= | === | ============= | ======== | ========== | 
| 5/1/13  | Wed | International | Japan    | 4069       | 
| 5/2/13  | Thu | International | Japan    | 4699       | 
| 5/3/13  | Fri | International | Japan    | 4403       | 
| 5/4/13  | Sat | International | Japan    | 3134       | 
| 5/5/13  | Sun | International | Japan    | 3265       | 
| 5/6/13  | Mon | International | Japan    | 2674       | 
| 5/7/13  | Tue | International | Japan    | 2451       | 
| 5/8/13  | Wed | International | Japan    | 3576       | 
| 5/9/13  | Thu | International | Japan    | 3323       | 
| 5/10/13 | Fri | International | Japan    | 2953       | 
```