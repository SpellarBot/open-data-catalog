# Lobbyists

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lobbyists) |
| Metadata | [Link](https://data.austintexas.gov/api/views/bqav-9x6a) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/bqav-9x6a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/bqav-9x6a/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | bqav-9x6a |
| Name | Lobbyists |
| Attribution | City of Austin |
| Tags | lobbyist |
| Created | 2011-12-13T14:55:21Z |
| Publication Date | 2017-04-17T14:51:15Z |

## Description

City Code Chapter 4-8 requires that persons who are hired by individuals, corporations or groups to influence public officials or specific boards and commissions must:

    - Register as lobbyists
    - File quarterly activity reports
    - File amendment forms as needed
    - Pay appropriate fees 
    - File a termination notice upon ceasing lobbyist activities.

Click here to view current registered lobbyists and their clients.
If you have questions, contact the Lobbyist Coordinator, 974-2210.

## Columns

```ls
| Included | Schema Type | Field Name                | Name               | Data Type     | Render Type   |
| ======== | =========== | ========================= | ================== | ============= | ============= |
| Yes      | series tag  | name                      | Last Name          | text          | text          |
| Yes      | series tag  | first_name                | First Name         | text          | text          |
| Yes      | time        | expiration_date           | Expiration Date    | calendar_date | calendar_date |
| Yes      | series tag  | client                    | Client             | text          | text          |
| Yes      | series tag  | client_nature_of_business | Nature of Business | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:bqav-9x6a d:2017-01-26T00:00:00.000Z t:first_name=Amelia t:client_nature_of_business=Zoning t:client="Southfield Office Owners" t:name="Lopez Saltarelli" m:row_number.bqav-9x6a=1

series e:bqav-9x6a d:2016-03-23T00:00:00.000Z t:first_name=Terrence t:client_nature_of_business=Residential t:client="Kalantari, Amir" t:name=Irion m:row_number.bqav-9x6a=2

series e:bqav-9x6a d:2016-03-23T00:00:00.000Z t:first_name=Terrence t:client_nature_of_business="Proposed Office Project" t:client="Sifuentes, Marina" t:name=Irion m:row_number.bqav-9x6a=3
```

## Meta Commands

```ls
metric m:row_number.bqav-9x6a p:long l:"Row Number"

entity e:bqav-9x6a l:Lobbyists t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/bqav-9x6a

property e:bqav-9x6a t:meta.view v:id=bqav-9x6a v:averageRating=0 v:name=Lobbyists v:attribution="City of Austin"

property e:bqav-9x6a t:meta.view.owner v:id=99uc-9byy v:screenName=opendataatx v:displayName=opendataatx

property e:bqav-9x6a t:meta.view.tableauthor v:id=99uc-9byy v:screenName=opendataatx v:roleName=administrator v:displayName=opendataatx
```

## Top Records

```ls
| name             | first_name   | expiration_date     | client                   | client_nature_of_business | 
| ================ | ============ | =================== | ======================== | ========================= | 
| Lopez Saltarelli | Amelia       | 2017-01-26T00:00:00 | Southfield Office Owners | Zoning                    | 
| Irion            | Terrence     | 2016-03-23T00:00:00 | Kalantari, Amir          | Residential               | 
| Irion            | Terrence     | 2016-03-23T00:00:00 | Sifuentes, Marina        | Proposed Office Project   | 
| Salinas III      | Derlis "Trey | 2017-10-21T00:00:00 | NXP Semiconductor, Inc.  | High Tech                 | 
| Salinas III      | Derlis "Trey | 2017-10-21T00:00:00 | Cypress Semiconductor    | High Tech                 | 
| Salinas III      | Derlis "Trey | 2017-10-21T00:00:00 | MWH Constructors         | Contractors               | 
| Salinas III      | Derlis "Trey | 2017-10-21T00:00:00 | Wal-Mart Stores, Inc     | Retail Merchant           | 
| Crocker          | Sarah        | 2011-12-16T00:00:00 | MU 13                    | Developer                 | 
| Cesaro           | Peter        | 2018-01-05T00:00:00 | Warshaw, Larry           | Property Owner            | 
| Meade            | Nikelle      | 2017-04-25T00:00:00 | SKV- Villas              | Zoning                    | 
```