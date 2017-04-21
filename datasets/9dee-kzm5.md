# LCB Liquor Renewal

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lcb-liquor-renewal) |
| Metadata | [Link](https://data.wa.gov/api/views/9dee-kzm5) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/9dee-kzm5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/9dee-kzm5/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 9dee-kzm5 |
| Name | LCB Liquor Renewal |
| Category | Public Safety |
| Tags | lcb, renewal |
| Created | 2015-03-17T14:34:18Z |
| Publication Date | 2015-06-17T18:33:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | license          | License#         | text      | text        |
| Yes      | series tag     | ubi              | UBI              | text      | text        |
| Yes      | series tag     | designatedsignee | DesignatedSignee | text      | text        |
| Yes      | series tag     | countycode       | CountyCode       | text      | text        |
| Yes      | series tag     | countyname       | CountyName       | text      | text        |
| Yes      | series tag     | citycode         | CityCode         | text      | text        |
| Yes      | series tag     | cityname         | CityName         | text      | text        |
| Yes      | series tag     | dayphone         | DayPhone         | text      | text        |
| Yes      | series tag     | l_a_type         | L/A Type         | text      | text        |
| Yes      | series tag     | tradename        | TradeName        | text      | text        |
| Yes      | series tag     | streetaddress    | StreetAddress    | text      | text        |
| Yes      | series tag     | roomnumber       | RoomNumber       | text      | text        |
| Yes      | series tag     | city             | City             | text      | text        |
| Yes      | series tag     | state            | State            | text      | text        |
| Yes      | series tag     | zipcode          | ZipCode          | text      | text        |
| No       |                | mailaddress      | MailAddress      | text      | text        |
| Yes      | series tag     | mailroom         | MailRoom         | text      | text        |
| Yes      | series tag     | mailcity         | MailCity         | text      | text        |
| Yes      | series tag     | mailstate        | MailState        | text      | text        |
| Yes      | series tag     | mailzip          | MailZip          | text      | text        |
| Yes      | series tag     | privdesc01       | PrivDesc01       | text      | text        |
| Yes      | series tag     | privdesc02       | PrivDesc02       | text      | text        |
| Yes      | series tag     | privdesc03       | PrivDesc03       | text      | text        |
| Yes      | series tag     | privdesc04       | PrivDesc04       | text      | text        |
| Yes      | series tag     | privdesc05       | PrivDesc05       | text      | text        |
| Yes      | series tag     | privdesc06       | PrivDesc06       | text      | text        |
| Yes      | series tag     | privdesc07       | PrivDesc07       | text      | text        |
| Yes      | series tag     | privdesc08       | PrivDesc08       | text      | text        |
| Yes      | series tag     | applicants       | Applicants       | text      | text        |
| Yes      | numeric metric | renewaldate      | RenewalDate      | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailaddress
```

## Data Commands

```ls
series e:9dee-kzm5 d:2017-04-04T11:30:19.000Z t:applicants="FIVE Z'S, INC." t:zipcode=984072305 t:state=WA t:designatedsignee="TACOMA CHIEF OF POLICE" t:city=TACOMA t:ubi=6016417540010002 t:citycode=17 t:streetaddress="5928 N 26TH ST" t:countyname=PIERCE t:dayphone=2538758116 t:tradename="WESTGATE BAR & GRILL" t:privdesc01="SPIRITS/BR/WN REST LOUNGE -" t:l_a_type="LIQUOR RENEWAL" t:countycode=27 t:cityname=TACOMA t:license=357673 m:renewaldate=20170731

series e:9dee-kzm5 d:2017-04-04T11:30:19.000Z t:applicants="CARR,  BLAIRE  C" t:zipcode=986059177 t:state=WA t:designatedsignee="MAYOR OF BINGEN- CITY HALL" t:city=BINGEN t:ubi=6031568950010001 t:citycode=1 t:streetaddress="120 W STEUBEN ST" t:countyname=KLICKITAT t:dayphone=5099813100 t:tradename="MUGS COFFEE" t:privdesc01="BEER/WINE REST - BEER/WINE" t:l_a_type="LIQUOR RENEWAL" t:countycode=20 t:cityname=BINGEN t:license=409504 m:renewaldate=20170731

series e:9dee-kzm5 d:2017-04-04T11:30:19.000Z t:applicants="HAYLEY INVESTMENTS, LLC" t:zipcode=981224032 t:state=WA t:designatedsignee="TERESA EIDEM" t:city=SEATTLE t:ubi=6035263430010001 t:citycode=26 t:streetaddress="1408 E PINE ST" t:countyname=KING t:privdesc02="OFF-PREMISES SALE WINE" t:dayphone=2063229463 t:tradename="POCO WINE + SPIRITS" t:privdesc01="SPIRITS/BR/WN REST LOUNGE -" t:l_a_type="LIQUOR RENEWAL" t:countycode=17 t:cityname=SEATTLE t:license=089275 m:renewaldate=20170731
```

## Meta Commands

```ls
metric m:renewaldate p:integer l:RenewalDate t:dataTypeName=number

entity e:9dee-kzm5 l:"LCB Liquor Renewal" t:url=https://data.wa.gov/api/views/9dee-kzm5

property e:9dee-kzm5 t:meta.view v:id=9dee-kzm5 v:category="Public Safety" v:averageRating=0 v:name="LCB Liquor Renewal"

property e:9dee-kzm5 t:meta.view.owner v:id=v3pq-y2y4 v:screenName="Cameron McGee" v:displayName="Cameron McGee"

property e:9dee-kzm5 t:meta.view.tableauthor v:id=v3pq-y2y4 v:screenName="Cameron McGee" v:roleName=publisher v:displayName="Cameron McGee"
```

## Top Records

```ls
| :updated_at | license | ubi              | designatedsignee            | countycode | countyname   | citycode | cityname        | dayphone   | l_a_type       | tradename              | streetaddress               | roomnumber | city           | state | zipcode   | mailaddress | mailroom | mailcity | mailstate | mailzip | privdesc01                  | privdesc02             | privdesc03 | privdesc04 | privdesc05 | privdesc06 | privdesc07 | privdesc08 | applicants                  | renewaldate | 
| =========== | ======= | ================ | =========================== | ========== | ============ | ======== | =============== | ========== | ============== | ====================== | =========================== | ========== | ============== | ===== | ========= | =========== | ======== | ======== | ========= | ======= | =========================== | ====================== | ========== | ========== | ========== | ========== | ========== | ========== | =========================== | =========== | 
| 1491305419  | 357673  | 6016417540010002 | TACOMA CHIEF OF POLICE      | 27         | PIERCE       | 17       | TACOMA          | 2538758116 | LIQUOR RENEWAL | WESTGATE BAR & GRILL   | 5928 N 26TH ST              |            | TACOMA         | WA    | 984072305 |             |          |          |           |         | SPIRITS/BR/WN REST LOUNGE - |                        |            |            |            |            |            |            | FIVE Z'S, INC.              | 20170731    | 
| 1491305419  | 409504  | 6031568950010001 | MAYOR OF BINGEN- CITY HALL  | 20         | KLICKITAT    | 1        | BINGEN          | 5099813100 | LIQUOR RENEWAL | MUGS COFFEE            | 120 W STEUBEN ST            |            | BINGEN         | WA    | 986059177 |             |          |          |           |         | BEER/WINE REST - BEER/WINE  |                        |            |            |            |            |            |            | CARR, BLAIRE C              | 20170731    | 
| 1491305419  | 089275  | 6035263430010001 | TERESA EIDEM                | 17         | KING         | 26       | SEATTLE         | 2063229463 | LIQUOR RENEWAL | POCO WINE + SPIRITS    | 1408 E PINE ST              |            | SEATTLE        | WA    | 981224032 |             |          |          |           |         | SPIRITS/BR/WN REST LOUNGE - | OFF-PREMISES SALE WINE |            |            |            |            |            |            | HAYLEY INVESTMENTS, LLC     | 20170731    | 
| 1491305419  | 408817  | 6014009440010141 | MAYOR OF EAST WENATCHEE     | 9          | DOUGLAS      | 2        | EAST WENATCHEE  | 8475274196 | LIQUOR RENEWAL | WALGREENS #13971       | 470 GRANT RD                |            | EAST WENATCHEE | WA    | 988025336 |             |          |          |           |         | GROCERY STORE - BEER/WINE   | SPIRITS RETAILER       |            |            |            |            |            |            | WALGREEN CO.                | 20170731    | 
| 1491305419  | 406999  | 6033195360010001 | BURIEN POLICE SERVICES      | 17         | KING         | 34       | BURIEN          | 2065795141 | LIQUOR RENEWAL | KRUNGTHEP THAI CUISINE | 13260 1ST AVE S STE A       |            | BURIEN         | WA    | 981682696 |             |          |          |           |         | BEER/WINE REST - BEER/WINE  |                        |            |            |            |            |            |            | KRUNGTHEP THAI CUISINE, LLC | 20170731    | 
| 1491305419  | 407409  | 6035223800010002 | MAYOR OF BELLEVUE           | 17         | KING         | 4        | BELLEVUE        | 4252744600 | LIQUOR RENEWAL | FROST                  | 700 BELLEVUE WAY NE STE 140 |            | BELLEVUE       | WA    | 980045094 |             |          |          |           |         | BEER/WINE REST - BEER/WINE  |                        |            |            |            |            |            |            | FROST GROUP, INC.           | 20170731    | 
| 1491305419  | 075002  | 6026325540010001 | TERESA EIDEM                | 17         | KING         | 26       | SEATTLE         | 2068186937 | LIQUOR RENEWAL | TANGO RESTAURANT       | 1100 PIKE ST                |            | SEATTLE        | WA    | 981011924 |             |          |          |           |         | SPIRITS/BR/WN REST LOUNGE + | OFF-PREMISES SALE WINE |            |            |            |            |            |            | TANGO RESTAURANT, INC.      | 20170731    | 
| 1491305419  | 408792  | 6036204730010001 | KITSAP COUNTY COMMISSIONERS | 18         | KITSAP       | 0        | UNINCORP. AREAS | 2063193794 | LIQUOR RENEWAL | TINDERBOX COFFEE HOUSE | 38955 HANSVILLE RD NE       |            | HANSVILLE      | WA    | 98340     |             |          |          |           |         | BEER/WINE REST - BEER/WINE  | OFF PREMISES           |            |            |            |            |            |            | WANG, MEIFU                 | 20170731    | 
| 1491305419  | 072458  | 6027447220010001 | MAYOR OF REPUBLIC           | 10         | FERRY        | 1        | REPUBLIC        | 5097753231 | LIQUOR RENEWAL | GILLIES MARKET         | 30267 E HWY 20              |            | REPUBLIC       | WA    | 991660000 |             |          |          |           |         | GROCERY STORE - BEER/WINE   |                        |            |            |            |            |            |            | GILL BROTHERS LLC           | 20170731    | 
| 1491305419  | 077498  | 6026343000010001 | MAYOR OF HOQUIAM            | 14         | GRAYS HARBOR | 4        | HOQUIAM         | 3605370089 | LIQUOR RENEWAL | HOQUIAM MARKET         | 223 K STREET                |            | HOQUIAM        | WA    | 985500000 |             |          |          |           |         | GROCERY STORE - BEER/WINE   |                        |            |            |            |            |            |            | WORLD REMNANT CORP.         | 20170731    | 
```