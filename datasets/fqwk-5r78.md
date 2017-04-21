# City of Frederick Code Enforcement Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-frederick-code-enforcement-violations-ef60b) |
| Metadata | [Link](https://data.maryland.gov/api/views/fqwk-5r78) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/fqwk-5r78/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/fqwk-5r78/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | fqwk-5r78 |
| Name | City of Frederick Code Enforcement Violations |
| Attribution | City of Frederick |
| Tags | code enforcement, violation |
| Created | 2014-06-05T13:41:52Z |
| Publication Date | 2014-06-06T15:11:54Z |

## Description

This dataset includes the City of Frederick code enforcement violations from 1/1/14 to 6/6/14

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | number             | Number             | text          | text          |
| Yes      | series tag     | violation          | Violation          | text          | text          |
| Yes      | series tag     | case_type          | Case Type          | text          | text          |
| Yes      | series tag     | inspector          | Inspector          | text          | text          |
| Yes      | series tag     | status             | Status             | text          | text          |
| Yes      | time           | infraction         | Infraction         | calendar_date | calendar_date |
| Yes      | series tag     | complaint_received | Complaint Received | text          | text          |
| Yes      | series tag     | parcel             | Parcel             | text          | text          |
| Yes      | numeric metric | nac                | NAC                | number        | text          |
```

## Time Field

```ls
Value = infraction
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:fqwk-5r78 d:2014-05-27T00:00:00.000Z t:parcel=1102039826-- t:inspector="DAVID BEERS" t:status=Open t:complaint_received="In Person" t:violation="LMC001 Sign Prohibited" t:number=CE-14-01760 t:case_type="LAND MANAGEMENT CODE (HPC)" m:nac=11

series e:fqwk-5r78 d:2014-05-27T00:00:00.000Z t:parcel=1102038587-- t:inspector="DAVID BEERS" t:status=Open t:complaint_received="In Person" t:violation="LMC001 Sign Prohibited" t:number=CE-14-01759 t:case_type="LAND MANAGEMENT CODE (HPC)" m:nac=11

series e:fqwk-5r78 d:2014-06-03T00:00:00.000Z t:parcel=1102102765-- t:inspector="BRITTANY PARKS" t:status=Open t:complaint_received=patrol t:violation="CC002 Grass and Weeds 10-9.1" t:number=CE-14-01758 t:case_type="CITY CODE" m:nac=6
```

## Meta Commands

```ls
metric m:nac p:integer l:NAC t:dataTypeName=number

entity e:fqwk-5r78 l:"City of Frederick Code Enforcement Violations" t:attribution="City of Frederick" t:url=https://data.maryland.gov/api/views/fqwk-5r78

property e:fqwk-5r78 t:meta.view v:id=fqwk-5r78 v:averageRating=0 v:name="City of Frederick Code Enforcement Violations" v:attribution="City of Frederick"

property e:fqwk-5r78 t:meta.view.owner v:id=qfp5-ru6q v:screenName=spiresgis v:displayName=spiresgis

property e:fqwk-5r78 t:meta.view.tableauthor v:id=qfp5-ru6q v:screenName=spiresgis v:roleName=editor v:displayName=spiresgis
```

## Top Records

```ls
| number      | violation                     | case_type                  | inspector       | status | infraction          | complaint_received | parcel           | nac | 
| =========== | ============================= | ========================== | =============== | ====== | =================== | ================== | ================ | === | 
| CE-14-01760 | LMC001 Sign Prohibited        | LAND MANAGEMENT CODE (HPC) | DAVID BEERS     | Open   | 2014-05-27T00:00:00 | In Person          | 1102039826--     | 11  | 
| CE-14-01759 | LMC001 Sign Prohibited        | LAND MANAGEMENT CODE (HPC) | DAVID BEERS     | Open   | 2014-05-27T00:00:00 | In Person          | 1102038587--     | 11  | 
| CE-14-01758 | CC002 Grass and Weeds 10-9.1  | CITY CODE                  | BRITTANY PARKS  | Open   | 2014-06-03T00:00:00 | patrol             | 1102102765--     | 6   | 
| CE-14-01757 | CC002 Grass and Weeds 10-9.1  | CITY CODE                  | BRITTANY PARKS  | Open   | 2014-06-03T00:00:00 | ITSystem           | 1102245310-53-WH | 1   | 
| CE-14-01756 | CC006 Trimming & Removal 22-9 | CITY CODE                  | DEAN BRIGHTBILL | Open   | 2014-06-03T00:00:00 | ITSystem           | 1102150182--     | 5   | 
| CE-14-01755 | LMC001 Sign Prohibited        | LAND MANAGEMENT CODE (HPC) | DAVID BEERS     | Open   | 2014-05-27T00:00:00 | In Person          | 1102067366-26-   | 11  | 
| CE-14-01754 | LMC001 Sign Prohibited        | LAND MANAGEMENT CODE (HPC) | DAVID BEERS     | Open   | 2014-05-27T00:00:00 | In Person          | 1102081385--     | 11  | 
| CE-14-01753 | LMC001 Sign Prohibited        | LAND MANAGEMENT CODE (HPC) | DAVID BEERS     | Open   | 2014-05-27T00:00:00 | In Person          | 1102022168--     | 11  | 
| CE-14-01752 | LMC001 Sign Prohibited        | LAND MANAGEMENT CODE (HPC) | DAVID BEERS     | Open   | 2014-05-27T00:00:00 | In Person          | 1102067374--     | 11  | 
| CE-14-01751 | LMC001 Sign Prohibited        | LAND MANAGEMENT CODE (HPC) | DAVID BEERS     | Open   | 2014-05-27T00:00:00 | In Person          | 1102456265--     | 11  | 
```