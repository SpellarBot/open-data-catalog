# DCEO CSBG Clients Served

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dceo-csbg-clients-served-ea6a2) |
| Metadata | [Link](https://data.illinois.gov/api/views/x3mr-hcbn) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/x3mr-hcbn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/x3mr-hcbn/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | x3mr-hcbn |
| Name | DCEO CSBG Clients Served |
| Category | Social/Healthcare |
| Tags | csbg |
| Created | 2012-01-27T22:30:30Z |
| Publication Date | 2012-01-27T22:37:10Z |

## Description

Community Service Block Grant - clients served

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type     | Render Type   |
| ======== | =========== | ============ | ============ | ============= | ============= |
| Yes      | series tag  | acronym      | Acronym      | text          | text          |
| Yes      | series tag  | agency       | Agency       | text          | text          |
| Yes      | series tag  | servicename  | ServiceName  | text          | text          |
| Yes      | series tag  | servicecost_ | ServiceCost  | text          | text          |
| Yes      | time        | servicedate  | ServiceDate  | calendar_date | calendar_date |
| Yes      | series tag  | clientstatus | ClientStatus | text          | text          |
```

## Time Field

```ls
Value = servicedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:x3mr-hcbn d:2011-06-02T00:00:00.000Z t:acronym=BCMW t:clientstatus="In Progress" t:servicename="S-1.3-1 Referral to Employer" t:agency="BCMW Community Services" t:servicecost_=$115.00 m:row_number.x3mr-hcbn=1

series e:x3mr-hcbn d:2011-03-25T00:00:00.000Z t:acronym=BCMW t:clientstatus=Complete t:servicename="S-1.7-1 Equipment/Uniform/Supplies for employment" t:agency="BCMW Community Services" t:servicecost_=$163.53 m:row_number.x3mr-hcbn=2

series e:x3mr-hcbn d:2011-07-28T00:00:00.000Z t:acronym=BCMW t:clientstatus=Complete t:servicename="S-1.7-1 Equipment/Uniform/Supplies for employment" t:agency="BCMW Community Services" t:servicecost_=$86.47 m:row_number.x3mr-hcbn=3
```

## Meta Commands

```ls
metric m:row_number.x3mr-hcbn p:long l:"Row Number"

entity e:x3mr-hcbn l:"DCEO CSBG Clients Served" t:url=https://data.illinois.gov/api/views/x3mr-hcbn

property e:x3mr-hcbn t:meta.view v:id=x3mr-hcbn v:category=Social/Healthcare v:averageRating=0 v:name="DCEO CSBG Clients Served"

property e:x3mr-hcbn t:meta.view.owner v:id=t6h9-hze3 v:screenName=Nicole v:displayName=Nicole

property e:x3mr-hcbn t:meta.view.tableauthor v:id=t6h9-hze3 v:screenName=Nicole v:roleName=publisher v:displayName=Nicole
```

## Top Records

```ls
| acronym | agency                  | servicename                                       | servicecost_ | servicedate         | clientstatus | 
| ======= | ======================= | ================================================= | ============ | =================== | ============ | 
| BCMW    | BCMW Community Services | S-1.3-1 Referral to Employer                      | $115.00      | 2011-06-02T00:00:00 | In Progress  | 
| BCMW    | BCMW Community Services | S-1.7-1 Equipment/Uniform/Supplies for employment | $163.53      | 2011-03-25T00:00:00 | Complete     | 
| BCMW    | BCMW Community Services | S-1.7-1 Equipment/Uniform/Supplies for employment | $86.47       | 2011-07-28T00:00:00 | Complete     | 
| BCMW    | BCMW Community Services | S-1.7-1 Equipment/Uniform/Supplies for employment | $248.05      | 2011-04-18T00:00:00 | Complete     | 
| BCMW    | BCMW Community Services | S-1.7-1 Equipment/Uniform/Supplies for employment | $250.00      | 2011-03-17T00:00:00 | NULL         | 
| BCMW    | BCMW Community Services | S-1.7-1 Equipment/Uniform/Supplies for employment | $35.00       | 2011-07-29T00:00:00 | Complete     | 
| BCMW    | BCMW Community Services | S-1.7-1 Equipment/Uniform/Supplies for employment | $250.00      | 2011-04-19T00:00:00 | Complete     | 
| BCMW    | BCMW Community Services | S-1.7-1 Equipment/Uniform/Supplies for employment | $224.42      | 2011-05-27T00:00:00 | Failed       | 
| BCMW    | BCMW Community Services | S-1.7-1 Equipment/Uniform/Supplies for employment | $35.00       | 2011-07-01T00:00:00 | Failed       | 
| BCMW    | BCMW Community Services | S-1.7-1 Equipment/Uniform/Supplies for employment | $250.00      | 2011-08-15T00:00:00 | Complete     | 
```