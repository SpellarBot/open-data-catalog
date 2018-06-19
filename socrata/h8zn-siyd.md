# Lead Worker Licensees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lead-worker-licensees) |
| Metadata | [Link](https://data.illinois.gov/api/views/h8zn-siyd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/h8zn-siyd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/h8zn-siyd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | h8zn-siyd |
| Name | Lead Worker Licensees |
| Attribution | IDPH - Division of Environmental Health |
| Category | Public Health |
| Tags | lead, worker, mitigation |
| Created | 2015-02-26T18:27:34Z |
| Publication Date | 2016-06-28T19:54:37Z |

## Description

This list contains Lead Mitigation Worker licensees with their license expiration date and employer information. updated June 2016

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | last              | Last Name         | text          | text          |
| Yes      | series tag  | first_m           | First Name        | text          | text          |
| Yes      | time        | worker_expiration | Worker Expiration | calendar_date | calendar_date |
| No       |             | address           | Address           | text          | text          |
| Yes      | series tag  | city              | City              | text          | text          |
| Yes      | series tag  | state             | State             | text          | text          |
| Yes      | series tag  | zip               | Zip               | text          | text          |
| Yes      | series tag  | county            | County            | text          | text          |
| Yes      | series tag  | phone             | Phone             | text          | text          |
| Yes      | series tag  | employer_name     | Employer Name     | text          | text          |
| No       |             | employer_address  | Employer Address  | text          | text          |
| Yes      | series tag  | employer_city     | Employer CIty     | text          | text          |
| Yes      | series tag  | employer_state    | Employer State    | text          | text          |
| Yes      | series tag  | employer_zip      | Employer Zip      | text          | text          |
| Yes      | series tag  | employer_phone    | Employer Phone    | text          | text          |
```

## Time Field

```ls
Value = worker_expiration
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,employer_address
```

## Data Commands

```ls
series e:h8zn-siyd d:2016-03-31T00:00:00.000Z t:zip=60609 t:phone=NA t:employer_zip=60609 t:last=Abarca t:county=Cook t:first_m=Joaquin t:employer_name="B.B. CONSTRUCTION ENTERPRISE, INC." t:state=IL t:employer_state=IL t:employer_city=CHICAGO t:city=Chicago m:row_number.h8zn-siyd=1

series e:h8zn-siyd d:2016-03-31T00:00:00.000Z t:zip=63115 t:phone="(314) 367-1765" t:last=Adams t:first_m=Annette t:state=MO t:city="St. Louis" m:row_number.h8zn-siyd=2

series e:h8zn-siyd d:2017-03-31T00:00:00.000Z t:zip=60406 t:phone=NA t:last=Aguayo t:county=Cook t:first_m=Raul t:state=IL t:city="Blue Island" m:row_number.h8zn-siyd=3
```

## Meta Commands

```ls
metric m:row_number.h8zn-siyd p:long l:"Row Number"

entity e:h8zn-siyd l:"Lead Worker Licensees" t:attribution="IDPH - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/h8zn-siyd

property e:h8zn-siyd t:meta.view v:id=h8zn-siyd v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/lead-poisoning-prevention v:averageRating=0 v:name="Lead Worker Licensees" v:attribution="IDPH - Division of Environmental Health"

property e:h8zn-siyd t:meta.view.license v:name="Public Domain"

property e:h8zn-siyd t:meta.view.owner v:id=6dyi-26tm v:screenName="ken mccann" v:displayName="ken mccann"

property e:h8zn-siyd t:meta.view.tableauthor v:id=6dyi-26tm v:screenName="ken mccann" v:roleName=publisher v:displayName="ken mccann"
```

## Top Records

```ls
| last      | first_m           | worker_expiration   | address                | city        | state | zip   | county    | phone          | employer_name                      | employer_address        | employer_city | employer_state | employer_zip | employer_phone | 
| ========= | ================= | =================== | ====================== | =========== | ===== | ===== | ========= | ============== | ================================== | ======================= | ============= | ============== | ============ | ============== | 
| Abarca    | Joaquin           | 2016-03-31T00:00:00 | NA                     | Chicago     | IL    | 60609 | Cook      | NA             | B.B. CONSTRUCTION ENTERPRISE, INC. |                         | CHICAGO       | IL             | 60609        |                | 
| Adams     | Annette           | 2016-03-31T00:00:00 | 4841 St. Louis Ave     | St. Louis   | MO    | 63115 |           | (314) 367-1765 |                                    |                         |               |                |              |                | 
| Aguayo    | Raul              | 2017-03-31T00:00:00 | NA                     | Blue Island | IL    | 60406 | Cook      | NA             |                                    |                         |               |                |              |                | 
| Aguiar    | Ruben             | 2017-03-31T00:00:00 | NA                     | Zion        | IL    | 60099 | Lake      | NA             |                                    |                         |               |                |              |                | 
| AGUILAR   | ISARAS            | 2016-03-31T00:00:00 | 5655 W GRACE           | CHICAGO     | IL    | 60634 | COOK      | (773) 951-6914 |                                    |                         |               |                |              |                | 
| Albert    | Lawrence A        | 2016-03-31T00:00:00 | 621 Furman Street      | Rockford    | IL    | 61101 | Winnebago | (773) 490-6402 | Community Action Agency.           |                         | Rockford      | IL             | 61103        |                | 
| Alcantara | Liborio           | 2017-03-31T00:00:00 | 5147 S. Winchester Ave | Chicago     | IL    | 60609 | Cook      | (708) 296-5024 |                                    |                         |               |                |              |                | 
| Alcantara | Fernando          | 2016-03-31T00:00:00 | NA                     | Mundelein   | IL    | 60060 | Lake      | NA             | Nancy DeLeon Enterprises           | 950 S. Butterfield Road | Mundelein     | IL             | 60060        | (847) 571-1286 | 
| Alford    | Craig             | 2017-03-31T00:00:00 | NA                     | Venice      | IL    | 62090 | St. Clair | NA             |                                    |                         |               |                |              |                | 
| Alvarado  | Benigno Alexander | 2016-03-31T00:00:00 | NA                     | CHICAGO     | IL    | 60652 | COOK      | NA             |                                    |                         |               |                |              |                | 
```