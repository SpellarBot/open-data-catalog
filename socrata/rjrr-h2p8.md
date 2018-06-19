# IDVA - Field Offices and Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idva-field-offices-and-locations-503d1) |
| Metadata | [Link](https://data.illinois.gov/api/views/rjrr-h2p8) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rjrr-h2p8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rjrr-h2p8/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rjrr-h2p8 |
| Name | IDVA - Field Offices and Locations |
| Attribution | Illinois Department of Veterans Affairs |
| Category | Reference |
| Tags | idva, vet, field office, veteran |
| Created | 2012-01-31T21:39:37Z |
| Publication Date | 2012-01-31T21:46:46Z |

## Description

This data shows the contact information of the Illinois Department of Veterans Affairs field offices.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | county_location   | County Location   | text      | text        |
| No       |                | address_1         | Address 1         | text      | text        |
| No       |                | address_2         | Address 2         | text      | text        |
| Yes      | series tag     | city              | City              | text      | text        |
| Yes      | series tag     | zip_code          | Zip Code          | text      | text        |
| Yes      | series tag     | primary_phone     | Primary Phone     | text      | text        |
| Yes      | numeric metric | ext               | Ext               | number    | number      |
| Yes      | series tag     | fax               | Fax               | text      | text        |
| Yes      | series tag     | primary_contact   | Primary Contact   | text      | text        |
| Yes      | series tag     | secondary_contact | Secondary Contact | text      | text        |
| Yes      | series tag     | region            | Region            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_1,address_2
```

## Data Commands

```ls
series e:rjrr-h2p8 d:2012-01-31T13:39:47.000Z t:region=Central t:county_location="Adams County" t:fax=(217)-222-8578 t:zip_code=62301 t:secondary_contact="Curtis Davis" t:primary_phone=(217)-222-8641 t:primary_contact="Robert Sloan" t:city=Quincy m:ext=259

series e:rjrr-h2p8 d:2012-01-31T13:39:47.000Z t:region=Southern t:county_location="Jefferson County" t:fax=(618)246-2912 t:zip_code=62864 t:primary_phone=(618)246-2910 t:primary_contact="Jeffrey Lewis" t:city=MtVernon m:ext=73404

series e:rjrr-h2p8 d:2012-01-31T13:39:47.000Z t:region=Northern t:county_location="Kankakee County" t:fax=(815)468-8495 t:zip_code=60950 t:primary_phone=(815)468-6581 t:primary_contact="Fredrick Tetter" t:city=Manteno m:ext=230
```

## Meta Commands

```ls
metric m:ext p:integer l:Ext t:dataTypeName=number

entity e:rjrr-h2p8 l:"IDVA -  Field Offices and Locations" t:attribution="Illinois Department of Veterans Affairs" t:url=https://data.illinois.gov/api/views/rjrr-h2p8

property e:rjrr-h2p8 t:meta.view v:id=rjrr-h2p8 v:category=Reference v:averageRating=0 v:name="IDVA -  Field Offices and Locations" v:attribution="Illinois Department of Veterans Affairs"

property e:rjrr-h2p8 t:meta.view.owner v:id=ajuq-3qfp v:screenName="Chris Pence" v:displayName="Chris Pence"

property e:rjrr-h2p8 t:meta.view.tableauthor v:id=ajuq-3qfp v:screenName="Chris Pence" v:displayName="Chris Pence"
```

## Top Records

```ls
| :updated_at | county_location             | address_1                      | address_2             | city        | zip_code | primary_phone  | ext | fax            | primary_contact | secondary_contact | region   | 
| =========== | =========================== | ============================== | ===================== | =========== | ======== | ============== | === | ============== | =============== | ================= | ======== | 
| 1328017187  | Adams County                | 1707 N 12th St                 |                       | Quincy      | 62301    | (217)-222-8641 | 259 | (217)-222-8578 | Robert Sloan    | Curtis Davis      | Central  | 
| 1328017187  | Alexander County            | 22nd & Poplar St               |                       | Cairo       | 62914    | (618)-724-0535 |     |                | R.J. Schuler    |                   | Southern | 
| 1328017187  | Bond County                 | 305 S 3rd St                   |                       | Greenville  | 62246    | (618)-664-1465 |     |                | Ed Barnes       |                   | Southern | 
| 1328017187  | Bureau County               | 2 S Main Street                |                       | Princeton   | 61356    | (815)-879-8404 |     | (815)-879-8613 | Brian Butler    |                   | Northern | 
| 1328017187  | Cambridge House (Maryville) | 6960 State Route 162           |                       | Maryville   | 62062    |                |     |                |                 |                   | Southern | 
| 1328017187  | Cambridge House (OFallon)   | 844 Cambridge Blvd             |                       | OFallon     | 62269    |                |     |                |                 |                   | Southern | 
| 1328017187  | Cambridge House (Swansea)   | 3900 Sullivan Dr               |                       | Swansea     | 62226    |                |     |                |                 |                   | Southern | 
| 1328017187  | Champaign County            | State Regional Office Building | 2125 South 1st Street | Champaign   | 61820    | (217)278-3388  |     | (217)278-3375  | Robbie Walker   | Terry Baer        | Central  | 
| 1328017187  | Christian County            | IDVA                           | 1100 N. Cheney        | Taylorville | 62568    | (217)287-7474  |     | (217)287-7668  | Kellie Cravens  |                   | Central  | 
| 1328017187  | Clinton County              | Clinton County Senior Center   | 630 8th Street        | Carlyle     | 62231    | (618)594-2321  |     |                | Tom Sabo        |                   | Southern | 
```