# New Liquor Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-liquor-licenses-2b7cf) |
| Metadata | [Link](https://data.mo.gov/api/views/dymb-xy5c) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/dymb-xy5c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/dymb-xy5c/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | dymb-xy5c |
| Name | New Liquor Licenses |
| Attribution | Missouri Division of Alcohol and Tobacco Control |
| Category | Regulatory |
| Tags | new, liquor, license, missouri, alcohol, tobacco, control |
| Created | 2012-06-26T13:10:26Z |
| Publication Date | 2017-04-20T12:40:48Z |

## Description

Weekly listing of new Liquor Licenses for the past 3 weeks

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | license_number | License Number | text          | text          |
| Yes      | series tag     | licensee       | Licensee       | text          | text          |
| Yes      | series tag     | dbaname        | DBAName        | text          | text          |
| Yes      | series tag     | businesstype   | BusinessType   | text          | text          |
| Yes      | series tag     | license_type   | License Type   | text          | text          |
| Yes      | series tag     | current_status | Current Status | text          | text          |
| Yes      | time           | original_date  | Original Date  | calendar_date | calendar_date |
| Yes      | series tag     | district       | District       | text          | number        |
| Yes      | series tag     | subdistrict    | SubDistrict    | text          | number        |
| Yes      | numeric metric | county         | County         | number        | number        |
| Yes      | series tag     | street_number  | Street Number  | text          | text          |
| Yes      | series tag     | street         | Street         | text          | text          |
| Yes      | series tag     | city           | City           | text          | text          |
| Yes      | series tag     | state          | State          | text          | text          |
| Yes      | series tag     | zip_code       | Zip Code       | text          | text          |
```

## Time Field

```ls
Value = original_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:dymb-xy5c d:2017-04-06T00:00:00.000Z t:license_type=RBDP t:zip_code=63131 t:license_number=241432 t:street="S. LINDBERGH BLVD." t:businesstype=C t:state=MO t:current_status=OB t:city="CREVE COEUR" t:street_number=401 t:district=3 t:licensee="OUR LADY OF THE PILLAR" t:subdistrict=0 t:dbaname="(REED B. ROHLFING)" m:county=95

series e:dymb-xy5c d:2017-04-13T00:00:00.000Z t:license_type=RBDP t:zip_code=63131 t:license_number=241433 t:street="S. LINDBERGH BLVD." t:businesstype=C t:state=MO t:current_status=OB t:city="CREVE COEUR" t:street_number=401 t:district=3 t:licensee="OUR LADY OF THE PILLAR" t:subdistrict=0 t:dbaname="(REED B. ROHLFING)" m:county=95

series e:dymb-xy5c d:2017-04-06T00:00:00.000Z t:license_type=RBDP t:zip_code=64506 t:license_number=243352 t:street="NORTH 49TH TERRACE" t:businesstype=C t:state=MO t:current_status=OB t:city="ST. JOSEPH" t:street_number=1205 t:district=1 t:licensee="BISHOP LEBLOND COUNCIL 5067 K OF C" t:subdistrict=0 t:dbaname="(STEVE CULVER)" m:county=11
```

## Meta Commands

```ls
metric m:county p:long l:County t:dataTypeName=number

entity e:dymb-xy5c l:"New Liquor Licenses" t:attribution="Missouri Division of Alcohol and Tobacco Control" t:url=https://data.mo.gov/api/views/dymb-xy5c

property e:dymb-xy5c t:meta.view v:id=dymb-xy5c v:category=Regulatory v:attributionLink=http://www.atc.dps.mo.gov v:averageRating=0 v:name="New Liquor Licenses" v:attribution="Missouri Division of Alcohol and Tobacco Control"

property e:dymb-xy5c t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:dymb-xy5c t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| license_number | licensee                               | dbaname                   | businesstype | license_type | current_status | original_date       | district | subdistrict | county | street_number | street                     | city              | state | zip_code | 
| ============== | ====================================== | ========================= | ============ | ============ | ============== | =================== | ======== | =========== | ====== | ============= | ========================== | ================= | ===== | ======== | 
| 241432         | OUR LADY OF THE PILLAR                 | (REED B. ROHLFING)        | C            | RBDP         | OB             | 2017-04-06T00:00:00 | 3        | 0           | 95     | 401           | S. LINDBERGH BLVD.         | CREVE COEUR       | MO    | 63131    | 
| 241433         | OUR LADY OF THE PILLAR                 | (REED B. ROHLFING)        | C            | RBDP         | OB             | 2017-04-13T00:00:00 | 3        | 0           | 95     | 401           | S. LINDBERGH BLVD.         | CREVE COEUR       | MO    | 63131    | 
| 243352         | BISHOP LEBLOND COUNCIL 5067 K OF C     | (STEVE CULVER)            | C            | RBDP         | OB             | 2017-04-06T00:00:00 | 1        | 0           | 11     | 1205          | NORTH 49TH TERRACE         | ST. JOSEPH        | MO    | 64506    | 
| 243382         | QUIKTRIP CORPORATION                   | QUIKTRIP #217             | C            | OPL          | ACT            | 2017-04-01T00:00:00 | 1        | 0           | 48     | 705           | SW WESTBOUND US 40 HIGHWAY | BLUE SPRINGS      | MO    | 64015    | 
| 243393         | ST. MARGARET'S OF SCOTLAND CATHOLIC    | (SUZANNE E. NICHOLS)      | C            | RBDP         | OB             | 2017-04-06T00:00:00 | 1        | 0           | 48     | 777           | NE BLACKWELL ROAD          | LEE'S SUMMIT      | MO    | 64086    | 
| 243451         | CITY OF WENTZVILLE                     | PERUQUE VALLEY CONCESSION | L            | 5BD          | ACT            | 2017-04-01T00:00:00 | 3        | 0           | 92     | 1335          | S. POINTE PRAIRIE ROAD     | WENTZVILLE        | MO    | 63385    | 
| 243457         | ST. FRANCIS XAVIER CHURCH              | (RONALD WILL)             | C            | RBDP         | ACT            | 2017-04-20T00:00:00 | 1        | 0           | 11     | 2618          | SENECA STREET              | ST. JOSEPH        | MO    | 64507    | 
| 243491         | OUR LADY OF PROVIDENCE CATHOLIC CHURCH | (RICHARD SCHILLI)         | C            | RBDP         | OB             | 2017-04-04T00:00:00 | 3        | 0           | 95     | 8866          | PARDEE ROAD                | ST. LOUIS         | MO    | 63123    | 
| 243525         | ST. FRANCIS OF ASSISI PARISH           | (ROBERT L. BANKEN)        | C            | RBDP         | OB             | 2017-04-06T00:00:00 | 3        | 0           | 95     | 1355          | FARNHAM STREET             | PORTAGE DES SIOUX | MO    | 63373    | 
| 243601         | OUR LADY OF LOURDES CHURCH             | (JAMES THEBY)             | C            | RBDP         | OB             | 2017-03-31T00:00:00 | 2        | 0           | 36     | 1014          | MADISON AVENUE             | WASHINGTON        | MO    | 63089    | 
```