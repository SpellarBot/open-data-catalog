# SC Fields Summary Statementof Apprentice- Journeyman Participation - OHNO Construction

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sc-fields-summary-statementof-apprentice-journeyman-participation-ohno-construction) |
| Metadata | [Link](https://data.wa.gov/api/views/7ipt-eqqd) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/7ipt-eqqd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/7ipt-eqqd/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 7ipt-eqqd |
| Name | SC Fields Summary Statementof Apprentice- Journeyman Participation - OHNO Construction |
| Tags | shorecrest, ohno, shoreline school district |
| Created | 2016-05-17T15:50:07Z |
| Publication Date | 2016-05-17T15:53:39Z |

## Description

Shorecrest Athletic Fields Apprentice Records - Ohno Construction

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | projno             | PROJNO             | text          | text          |
| Yes      | series tag     | projtitle          | PROJTITLE          | text          | text          |
| Yes      | series tag     | agency_code        | AGENCY CODE        | text          | text          |
| Yes      | series tag     | agency_name        | AGENCY NAME        | text          | text          |
| Yes      | series tag     | firm_name          | FIRM NAME          | text          | text          |
| Yes      | numeric metric | proj_summ_total    | PROJ_SUMM_TOTAL    | number        | number        |
| Yes      | time           | actual_constntp_dt | ACTUAL_CONSTNTP_DT | calendar_date | calendar_date |
| Yes      | series tag     | worker_type        | WORKER TYPE        | text          | text          |
| Yes      | series tag     | worker_name        | WORKER_NAME        | text          | text          |
| Yes      | series tag     | worker_reg_num     | WORKER_REG_NUM     | text          | text          |
| Yes      | series tag     | trade_code         | TRADE_CODE         | text          | text          |
| Yes      | series tag     | trade_desc         | TRADE_DESC         | text          | text          |
| Yes      | numeric metric | hrs                | HRS                | number        | number        |
| No       |                | report_period_date | REPORT_PERIOD_DATE | calendar_date | calendar_date |
```

## Time Field

```ls
Value = actual_constntp_dt
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = report_period_date
```

## Data Commands

```ls
series e:7ipt-eqqd d:2015-06-23T00:00:00.000Z t:worker_name="Daniel Jones" t:worker_reg_num=182856 t:projtitle="SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT" t:worker_type=APPRENTICE t:trade_code=L t:agency_name="SHORELINE PUBLIC SCHOOL DISTRICT #412" t:firm_name="OHNO CONSTRUCTION" t:trade_desc=Laborer t:agency_code=SSD m:hrs=879 m:proj_summ_total=2594000

series e:7ipt-eqqd d:2015-06-23T00:00:00.000Z t:worker_name="Jameszetta Anderson" t:worker_reg_num=174411 t:projtitle="SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT" t:worker_type=APPRENTICE t:trade_code=L t:agency_name="SHORELINE PUBLIC SCHOOL DISTRICT #412" t:firm_name="OHNO CONSTRUCTION" t:trade_desc=Laborer t:agency_code=SSD m:hrs=156 m:proj_summ_total=2594000

series e:7ipt-eqqd d:2015-06-23T00:00:00.000Z t:worker_name="Jeremy German" t:worker_reg_num=182875 t:projtitle="SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT" t:worker_type=APPRENTICE t:trade_code=L t:agency_name="SHORELINE PUBLIC SCHOOL DISTRICT #412" t:firm_name="OHNO CONSTRUCTION" t:trade_desc=Laborer t:agency_code=SSD m:hrs=96 m:proj_summ_total=2594000
```

## Meta Commands

```ls
metric m:proj_summ_total p:integer l:PROJ_SUMM_TOTAL t:dataTypeName=number

metric m:hrs p:float l:HRS t:dataTypeName=number

entity e:7ipt-eqqd l:"SC Fields Summary Statementof Apprentice- Journeyman Participation - OHNO Construction" t:url=https://data.wa.gov/api/views/7ipt-eqqd

property e:7ipt-eqqd t:meta.view v:id=7ipt-eqqd v:averageRating=0 v:name="SC Fields Summary Statementof Apprentice- Journeyman Participation - OHNO Construction"

property e:7ipt-eqqd t:meta.view.owner v:id=vqc5-3vxz v:screenName="Garnet Osborn" v:displayName="Garnet Osborn"

property e:7ipt-eqqd t:meta.view.tableauthor v:id=vqc5-3vxz v:screenName="Garnet Osborn" v:roleName=editor v:displayName="Garnet Osborn"
```

## Top Records

```ls
| projno | projtitle                                                              | agency_code | agency_name                           | firm_name         | proj_summ_total | actual_constntp_dt  | worker_type | worker_name         | worker_reg_num | trade_code | trade_desc   | hrs  | report_period_date  | 
| ====== | ====================================================================== | =========== | ===================================== | ================= | =============== | =================== | =========== | =================== | ============== | ========== | ============ | ==== | =================== | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Daniel Jones        | 182856         | L          | Laborer      | 879  | 2016-03-31T00:00:00 | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Jameszetta Anderson | 174411         | L          | Laborer      | 156  | 2016-03-31T00:00:00 | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Jeremy German       | 182875         | L          | Laborer      | 96   | 2016-03-31T00:00:00 | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Matthew Mitchell    | 168878         | CE         | Cement Mason | 10   | 2016-03-31T00:00:00 | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Peter Hayes         | 177316         | CE         | Cement Mason | 16.5 | 2016-03-31T00:00:00 | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Ronald Boyd         | 184666         | CE         | Cement Mason | 8.5  | 2016-03-31T00:00:00 | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Jeremey Cornett     | 183717         | CE         | Cement Mason | 21   | 2016-03-31T00:00:00 | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Michael Holly       | 183792         | CE         | Cement Mason | 9.5  | 2016-03-31T00:00:00 | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Bret Johnson        | 175129         | CE         | Cement Mason | 8    | 2016-03-31T00:00:00 | 
|        | SHORECREST HIGH SCHOOL BASEBALL AND SOFTBALL FIELD IMPROVEMENT PROJECT | SSD         | SHORELINE PUBLIC SCHOOL DISTRICT #412 | OHNO CONSTRUCTION | 2594000         | 2015-06-23T00:00:00 | APPRENTICE  | Logan Miller        | 176121         | CE         | Cement Mason | 18   | 2016-03-31T00:00:00 | 
```