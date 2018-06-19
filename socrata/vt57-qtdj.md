# IDOL 2016 Registered Owner Rides

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2016-registered-owner-rides) |
| Metadata | [Link](https://data.illinois.gov/api/views/vt57-qtdj) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vt57-qtdj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vt57-qtdj/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vt57-qtdj |
| Name | IDOL 2016 Registered Owner Rides |
| Attribution | IL Department of Labor |
| Category | Labor |
| Tags | rides owners |
| Created | 2016-07-02T21:31:26Z |
| Publication Date | 2016-07-02T21:40:00Z |

## Description

IDOL 2016 Registered Rides Owners Lists

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | ownername    | OwnerName    | text      | text        |
| Yes      | series tag     | contactname  | ContactName  | text      | text        |
| Yes      | series tag     | contactphone | ContactPhone | text      | text        |
| Yes      | series tag     | zipcode      | Zipcode      | text      | text        |
| Yes      | series tag     | serialnumber | SerialNumber | text      | text        |
| Yes      | numeric metric | permit       | Permit       | number    | number      |
| Yes      | series tag     | ridename     | Ridename     | text      | text        |
| Yes      | series tag     | manufacturer | Manufacturer | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vt57-qtdj d:2016-01-01T00:00:00.000Z t:ownername="A&A ATTRACTIONS/ BIG H AMUSEMENTS" t:contactname="SUSAN HEADLEY" t:manufacturer=SELLNER t:ridename="Berry Go Round" t:zipcode=61739 t:contactphone=815-692-2558 t:serialnumber=BGOR03T89 m:permit=2919

series e:vt57-qtdj d:2016-01-01T00:00:00.000Z t:ownername="A&A ATTRACTIONS/ BIG H AMUSEMENTS" t:contactname="SUSAN HEADLEY" t:manufacturer=WISDOM t:ridename="Dragon Wagon" t:zipcode=61739 t:contactphone=815-692-2558 t:serialnumber=831921 m:permit=2930

series e:vt57-qtdj d:2016-01-01T00:00:00.000Z t:ownername="A&A ATTRACTIONS/ BIG H AMUSEMENTS" t:contactname="SUSAN HEADLEY" t:manufacturer="ELI BRIDGE" t:ridename="Ferris Wheel" t:zipcode=61739 t:contactphone=815-692-2558 t:serialnumber=1E9G00000RJ008024 m:permit=2921
```

## Meta Commands

```ls
metric m:permit p:integer l:Permit t:dataTypeName=number

entity e:vt57-qtdj l:"IDOL 2016 Registered Owner Rides" t:attribution="IL Department of Labor" t:url=https://data.illinois.gov/api/views/vt57-qtdj

property e:vt57-qtdj t:meta.view v:id=vt57-qtdj v:category=Labor v:averageRating=0 v:name="IDOL 2016 Registered Owner Rides" v:attribution="IL Department of Labor"

property e:vt57-qtdj t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:vt57-qtdj t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| ownername                         | contactname   | contactphone | zipcode | serialnumber      | permit | ridename                  | manufacturer           | 
| ================================= | ============= | ============ | ======= | ================= | ====== | ========================= | ====================== | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   | BGOR03T89         | 2919   | Berry Go Round            | SELLNER                | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   | 1100              |        | Bumper Cars               | SELLNER                | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   | 831921            | 2930   | Dragon Wagon              | WISDOM                 | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   | 1E9G00000RJ008024 | 2921   | Ferris Wheel              | ELI BRIDGE             | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   | 1F9FBW4T5PM063063 | 2924   | Gee Whiz                  | WISDOM                 | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   | 14257             |        | Inflatable, Bounce House  | WAPELLO                | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   |                   | 3296   | Inflatable, Candyland     | CUTTING EDGE           | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   | 27227             | 3298   | Inflatable, Kiddie Pillar | CUTTING EDGE           | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   | 27334             | 3297   | Inflatable, Slide         | CUTTING EDGE CREATIONS | 
| A&A ATTRACTIONS/ BIG H AMUSEMENTS | SUSAN HEADLEY | 815-692-2558 | 61739   | 1F9SUW51          |        | Jolly Choo Choo           | WISDOM                 | 
```