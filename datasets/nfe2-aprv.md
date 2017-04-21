# CT Department of Labor, Office of Research - LAUS Substate January 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ct-department-of-labor-office-of-research-laus-substate-mar-2016) |
| Metadata | [Link](https://data.ct.gov/api/views/nfe2-aprv) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/nfe2-aprv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/nfe2-aprv/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | nfe2-aprv |
| Name | CT Department of Labor, Office of Research - LAUS Substate January 2017 |
| Attribution | Department of Labor, Office of Research |
| Category | Government |
| Tags | laus, monthly, employment, unemployment, labor force data |
| Created | 2016-04-25T18:13:21Z |
| Publication Date | 2017-03-24T15:27:42Z |

## Description

The Local Area Unemployment Statistics (LAUS) program produces monthly employment, unemployment, and labor force data for Census regions and divisions, States, counties, metropolitan areas, and many cities, by place of residence. The LAUS program is a federal-state cooperative endeavor in which states develop state and sub-state data using concepts, definitions, and technical procedures prescribed by the Bureau of Labor Statistics (BLS). A major source of labor force data estimates, the Current Population Survey (CPS) includes a sample of over 1,600 Connecticut households each month regarding the labor force status of their occupants

## Columns

```ls
| Included | Schema Type    | Field Name | Name         | Data Type | Render Type |
| ======== | ============== | ========== | ============ | ========= | =========== |
| Yes      | numeric metric | method     | Method       | number    | text        |
| Yes      | series tag     | area_code  | Area Code    | text      | text        |
| Yes      | series tag     | area_title | Area Title   | text      | text        |
| Yes      | series tag     | data_type  | Data Type    | text      | text        |
| Yes      | numeric metric | jan_2016_r | Jan 2017 (R) | number    | number      |
| Yes      | numeric metric | feb_2017_p | Feb 2017 (P) | number    | number      |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nfe2-aprv d:2017-01-01T00:00:00.000Z t:data_type="Labor Force" t:area_title="Bridgeport-New Haven-Stamford, CT Combined NECTA" t:area_code=CA0972000000000 m:method=7 m:jan_2016_r=1002721 m:feb_2017_p=1007497

series e:nfe2-aprv d:2017-01-01T00:00:00.000Z t:data_type=Employment t:area_title="Bridgeport-New Haven-Stamford, CT Combined NECTA" t:area_code=CA0972000000000 m:method=7 m:jan_2016_r=948346 m:feb_2017_p=951540

series e:nfe2-aprv d:2017-01-01T00:00:00.000Z t:data_type=Unemployment t:area_title="Bridgeport-New Haven-Stamford, CT Combined NECTA" t:area_code=CA0972000000000 m:method=7 m:jan_2016_r=54375 m:feb_2017_p=55957
```

## Meta Commands

```ls
metric m:method p:integer l:Method t:dataTypeName=number

metric m:jan_2016_r p:double l:"Jan 2017 (R)" t:dataTypeName=number

metric m:feb_2017_p p:double l:"Feb 2017 (P)" t:dataTypeName=number

entity e:nfe2-aprv l:"CT Department of Labor, Office of Research - LAUS Substate January 2017" t:attribution="Department of Labor, Office of Research" t:url=https://data.ct.gov/api/views/nfe2-aprv

property e:nfe2-aprv t:meta.view v:id=nfe2-aprv v:category=Government v:attributionLink=http://www1.ctdol.state.ct.us/lmi/index.asp v:averageRating=0 v:name="CT Department of Labor, Office of Research - LAUS Substate January 2017" v:attribution="Department of Labor, Office of Research"

property e:nfe2-aprv t:meta.view.license v:name="Public Domain"

property e:nfe2-aprv t:meta.view.owner v:id=dm7v-mmvk v:screenName="Andrew Condon" v:displayName="Andrew Condon"

property e:nfe2-aprv t:meta.view.tableauthor v:id=dm7v-mmvk v:screenName="Andrew Condon" v:roleName=editor v:displayName="Andrew Condon"
```

## Top Records

```ls
| method | area_code       | area_title                                               | data_type         | jan_2016_r | feb_2017_p | 
| ====== | =============== | ======================================================== | ================= | ========== | ========== | 
| 7      | CA0972000000000 | Bridgeport-New Haven-Stamford, CT Combined NECTA         | Labor Force       | 1002721    | 1007497    | 
| 7      | CA0972000000000 | Bridgeport-New Haven-Stamford, CT Combined NECTA         | Employment        | 948346     | 951540     | 
| 7      | CA0972000000000 | Bridgeport-New Haven-Stamford, CT Combined NECTA         | Unemployment      | 54375      | 55957      | 
| 7      | CA0972000000000 | Bridgeport-New Haven-Stamford, CT Combined NECTA         | Unemployment Rate | 5.4        | 5.6        | 
| 7      | CA0979000000000 | Springfield-Hartford-West Hartford, MA-CT Combined NECTA | Labor Force       | 1027784    | 1038796    | 
| 7      | CA0979000000000 | Springfield-Hartford-West Hartford, MA-CT Combined NECTA | Employment        | 974313     | 983617     | 
| 7      | CA0979000000000 | Springfield-Hartford-West Hartford, MA-CT Combined NECTA | Unemployment      | 53471      | 55179      | 
| 7      | CA0979000000000 | Springfield-Hartford-West Hartford, MA-CT Combined NECTA | Unemployment Rate | 5.2        | 5.3        | 
| 7      | CN0900100000000 | Fairfield County, CT                                     | Labor Force       | 480233     | 481051     | 
| 7      | CN0900100000000 | Fairfield County, CT                                     | Employment        | 455282     | 455324     | 
```