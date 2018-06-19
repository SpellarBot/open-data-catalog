# IDoA Illinois Regional Transit Authorities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idoa-illinois-regional-transit-authorities-4bda1) |
| Metadata | [Link](https://data.illinois.gov/api/views/awaf-eqav) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/awaf-eqav/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/awaf-eqav/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | awaf-eqav |
| Name | IDoA Illinois Regional Transit Authorities |
| Category | Social/Healthcare |
| Tags | transit |
| Created | 2011-10-19T14:17:36Z |
| Publication Date | 2011-10-19T14:28:26Z |

## Description

Listing of Illinois Regional Mass Transit Authorities

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | transit_system | TRANSIT SYSTEM | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | text        |
| Yes      | series tag  | phone_1        | Phone 1        | text      | text        |
| Yes      | series tag  | phone_2        | Phone 2        | text      | text        |
| Yes      | series tag  | website        | Website        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:awaf-eqav d:2011-10-19T07:17:45.000Z t:phone_2="(309) 828-9833" t:zip_code=61761 t:website=info@bpts.com t:phone_1="(309) 828-9331" t:transit_system="Bloomingon-Normal Public Transit System" m:row_number.awaf-eqav=1

series e:awaf-eqav d:2011-10-19T07:17:45.000Z t:zip_code=61802 t:website=mtdweb@cumtd.com t:phone_1="(217) 384-8188" t:transit_system="Champaign-Urbana Mass Transit District" m:row_number.awaf-eqav=2

series e:awaf-eqav d:2011-10-19T07:17:45.000Z t:phone_2="(312) 913-3164" t:zip_code=60604 t:website=www.rtachicago.com t:phone_1="(312) 913-3200" t:transit_system="Chicago Regional Transportation Authority (RTA)" m:row_number.awaf-eqav=3
```

## Meta Commands

```ls
metric m:row_number.awaf-eqav p:long l:"Row Number"

entity e:awaf-eqav l:"IDoA Illinois Regional Transit Authorities" t:url=https://data.illinois.gov/api/views/awaf-eqav

property e:awaf-eqav t:meta.view v:id=awaf-eqav v:category=Social/Healthcare v:averageRating=0 v:name="IDoA Illinois Regional Transit Authorities"

property e:awaf-eqav t:meta.view.owner v:id=kcsp-4rdt v:screenName="Bernie Clancy IDoA" v:displayName="Bernie Clancy IDoA"

property e:awaf-eqav t:meta.view.tableauthor v:id=kcsp-4rdt v:screenName="Bernie Clancy IDoA" v:displayName="Bernie Clancy IDoA"
```

## Top Records

```ls
| :updated_at | transit_system                                  | zip_code | phone_1        | phone_2        | website                                | 
| =========== | =============================================== | ======== | ============== | ============== | ====================================== | 
| 1319008665  | Bloomingon-Normal Public Transit System         | 61761    | (309) 828-9331 | (309) 828-9833 | info@bpts.com                          | 
| 1319008665  | Champaign-Urbana Mass Transit District          | 61802    | (217) 384-8188 |                | mtdweb@cumtd.com                       | 
| 1319008665  | Chicago Regional Transportation Authority (RTA) | 60604    | (312) 913-3200 | (312) 913-3164 | www.rtachicago.com                     | 
| 1319008665  | Danville Mass Transit                           | 61832    | (217) 431-2200 |                | rbrazda@city of danville.org           | 
| 1319008665  | Decatur Public Transit System                   | 62523    | (217) 424-2814 |                | dpts@decaturil.gov                     | 
| 1319008665  | Galesburg Transit                               | 61401    | (309) 342-4242 |                | ci.galesburg.il.us/transit/citybus.htm | 
| 1319008665  | McDonough County Public Transportation          | 61455    | (309) 847-7433 |                | www.macomb.com/transportation          | 
| 1319008665  | Madison Co. Transit                             | 62040    | (618) 847-7433 | (618) 931-7433 | info@mct.org                           | 
| 1319008665  | Greater Peoria & Pekin Mass Transit District    | 61603    | (309) 676-4040 |                | jklopfen@ridecitylink.org              | 
| 1319008665  | Quincy Transit                                  | 62301    | (217) 228-4550 |                | JohnO@ci.quincy.il.us                  | 
```