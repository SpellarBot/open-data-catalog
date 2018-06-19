# Exemption Classification Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/exemption-classification-codes) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/myn9-hwsy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/myn9-hwsy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/myn9-hwsy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | myn9-hwsy |
| Name | Exemption Classification Codes |
| Attribution | Department of Finance (DOF) |
| Category | City Government |
| Tags | finance, dof, codes |
| Created | 2016-05-24T18:38:41Z |
| Publication Date | 2016-05-24T18:42:36Z |

## Description

Table of codes and the corresponding description

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | exempt_code | Exempt Code | text          | number        |
| Yes      | series tag  | sdea_code   | SDEA Code   | text          | text          |
| Yes      | series tag  | description | Description | text          | text          |
| Yes      | series tag  | status      | Status      | text          | text          |
| Yes      | series tag  | legal_ref   | Legal Ref   | text          | text          |
| Yes      | series tag  | comments    | Comments    | text          | text          |
| Yes      | time        | updated     | Updated     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = updated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:myn9-hwsy d:2013-11-25T00:00:00.000Z t:status=ACTIVE t:description=VETERAN t:sdea_code=41101 t:legal_ref="RPTL ? 458" t:exempt_code=1010 m:row_number.myn9-hwsy=1

series e:myn9-hwsy d:2013-11-25T00:00:00.000Z t:status=ACTIVE t:description="New Law Veteran" t:sdea_code=41121 t:legal_ref="RPTL ? 458" t:exempt_code=1010 m:row_number.myn9-hwsy=2

series e:myn9-hwsy d:2013-11-25T00:00:00.000Z t:status=ACTIVE t:description="New Law Veteran" t:sdea_code=41131 t:legal_ref="RPTL ? 458" t:exempt_code=1010 m:row_number.myn9-hwsy=3
```

## Meta Commands

```ls
metric m:row_number.myn9-hwsy p:long l:"Row Number"

entity e:myn9-hwsy l:"Exemption Classification Codes" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/myn9-hwsy

property e:myn9-hwsy t:meta.view v:id=myn9-hwsy v:category="City Government" v:averageRating=0 v:name="Exemption Classification Codes" v:attribution="Department of Finance (DOF)"

property e:myn9-hwsy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:myn9-hwsy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| exempt_code | sdea_code | description       | status | legal_ref    | comments | updated             | 
| =========== | ========= | ================= | ====== | ============ | ======== | =================== | 
| 1010        | 41101     | VETERAN           | ACTIVE | RPTL ? 458   |          | 2013-11-25T00:00:00 | 
| 1010        | 41121     | New Law Veteran   | ACTIVE | RPTL ? 458   |          | 2013-11-25T00:00:00 | 
| 1010        | 41131     | New Law Veteran   | ACTIVE | RPTL ? 458   |          | 2013-11-25T00:00:00 | 
| 1010        | 41141     | New Law Veteran   | ACTIVE | RPTL ? 458   |          | 2013-11-25T00:00:00 | 
| 1011        | 41300     | SER DISABLED VET  | ACTIVE | RPTL ?458(3) |          | 2013-03-01T00:00:00 | 
| 1015        | 41800     | SENIOR CITIZEN    | ACTIVE | RPTL ?467    |          | 2013-03-01T00:00:00 | 
| 1016        | 41910     | CRIME VICTIMS     | ACTIVE | RPTL ?459-b  |          | 2013-03-01T00:00:00 | 
| 1017        | 41836     | SCHOOL TAX RELIEF | ACTIVE | RPTL ? 425   |          | 2013-03-01T00:00:00 | 
| 1017        | 41856     | SCHOOL TAX RELIEF | ACTIVE | RPTL ? 425   |          | 2013-03-01T00:00:00 | 
| 1019        | 41930     | DISABLE HOMEOWNER | ACTIVE | RPTL ? 459C  |          | 2013-03-01T00:00:00 | 
```