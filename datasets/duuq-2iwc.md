# OWEB Small Grant Teams

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oweb-small-grant-teams) |
| Metadata | [Link](https://data.oregon.gov/api/views/duuq-2iwc) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/duuq-2iwc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/duuq-2iwc/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | duuq-2iwc |
| Name | OWEB Small Grant Teams |
| Category | Natural Resources |
| Tags | oweb, small grants, teams, contact, address, email, location, phone |
| Created | 2016-12-16T18:03:00Z |
| Publication Date | 2016-12-22T18:32:24Z |

## Description

OWEB Small Grant Teams with contact information and team leader name.

## Columns

```ls
| Included | Schema Type | Field Name  | Name         | Data Type | Render Type |
| ======== | =========== | =========== | ============ | ========= | =========== |
| No       | time        | :updated_at | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | area        | Area         | text      | text        |
| Yes      | series tag  | name        | Team Contact | text      | text        |
| Yes      | series tag  | team        | Team         | text      | text        |
| Yes      | series tag  | phone       | Phone        | text      | text        |
| Yes      | series tag  | email       | Email        | email     | email       |
| Yes      | series tag  | email_2     | Email 2      | email     | email       |
| Yes      | series tag  | po_box      | PO Box       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:duuq-2iwc d:2016-12-16T20:35:49.000Z t:phone="(541) 947-5855" t:area="20 Lake" t:email=lakeviewswcd2@hotmail.com t:name="Nancey Pennington" t:team="Lakeview SWCD" m:row_number.duuq-2iwc=1

series e:duuq-2iwc d:2016-12-16T20:32:50.000Z t:phone="(503) 397-4555" t:area="01 Lower Columbia" t:email=nathan.herr@columbiaswcd.com t:name="Nathan Herr" t:team="Columbia SWCD" m:row_number.duuq-2iwc=2

series e:duuq-2iwc d:2016-12-16T20:33:16.000Z t:phone="(541) 765-2229" t:area="03 Mid Coast" t:email=franrecht@centurytel.net t:name="Fran Recht" t:team="MidCoast Watershed Council" t:po_box="PO Box 221" m:row_number.duuq-2iwc=3
```

## Meta Commands

```ls
metric m:row_number.duuq-2iwc p:long l:"Row Number"

entity e:duuq-2iwc l:"OWEB Small Grant Teams" t:url=https://data.oregon.gov/api/views/duuq-2iwc

property e:duuq-2iwc t:meta.view v:id=duuq-2iwc v:category="Natural Resources" v:averageRating=0 v:name="OWEB Small Grant Teams"

property e:duuq-2iwc t:meta.view.owner v:id=p4qe-76q4 v:screenName=gkirchner v:displayName=gkirchner

property e:duuq-2iwc t:meta.view.tableauthor v:id=p4qe-76q4 v:screenName=gkirchner v:roleName=editor v:displayName=gkirchner
```

## Top Records

```ls
| :updated_at | area              | name                 | team                            | phone               | email                             | email_2 | po_box     | 
| =========== | ================= | ==================== | =============================== | =================== | ================================= | ======= | ========== | 
| 1481920549  | 20 Lake           | Nancey Pennington    | Lakeview SWCD                   | (541) 947-5855      | lakeviewswcd2@hotmail.com         |         |            | 
| 1481920370  | 01 Lower Columbia | Nathan Herr          | Columbia SWCD                   | (503) 397-4555      | nathan.herr@columbiaswcd.com      |         |            | 
| 1481920396  | 03 Mid Coast      | Fran Recht           | MidCoast Watershed Council      | (541) 765-2229      | franrecht@centurytel.net          |         | PO Box 221 | 
| 1481920402  | 04 Coos Coquille  | Mike Mader           | Tenmile Lakes Basin Partnership | (541) 759-2414      | tlbp@presys.com                   |         | PO Box L   | 
| 1481920407  | 04 Coos Coquille  | Kelly Miles          | Coquille Watershed Association  | (541) 396-2541      | coqwa@hotmail.com                 |         |            | 
| 1481920413  | 05 South Coast    | Kelly Timchak        | Lower Rogue WC                  | (541) 247-2755 x4#  | kelly@currywatersheds.org         |         | PO Box 666 | 
| 1481920418  | 05 South Coast    | Liesl Coleman        | Curry SWCD                      | (541) 247-2755 x0#  | liesl.coleman@currywatersheds.org |         | PO Box 666 | 
| 1481920424  | 06 Rogue Basin    | Donna Chickering     | Rogue River WC                  | (541) 644-1070 x431 | dchickering@rogueriverwc.org      |         |            | 
| 1481920430  | 06 Rogue Basin    | Barbara Neidermeyer  | Jackson SWCD                    | (541) 659-3984      | barbara.neidermeyer@jswcd.org     |         |            | 
| 1481920436  | 07 Umpqua         | Brian Jenkins        | Smith River WC                  | (541) 271-2223      | jenkins.smithriver@gmail.com      |         | PO Box 114 | 
```