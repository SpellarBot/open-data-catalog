# Human Resources - Collective Bargaining Agreements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/human-resources-collective-bargaining-agreements) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/8tar-cztq) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8tar-cztq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/8tar-cztq/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 8tar-cztq |
| Name | Human Resources - Collective Bargaining Agreements |
| Attribution | Bureau of Human Resources |
| Category | Finance & Administration |
| Tags | cba, labor agreement, union |
| Created | 2016-08-24T21:52:22Z |
| Publication Date | 2017-01-17T20:07:29Z |

## Description

Collective Bargaining Agreements from Cook County for the periods of 2004 to 2017. This is an initial collection and will be revised as new data becomes available.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | folder                    | Agreement Period          | text      | text        |
| Yes      | series tag     | bargaining_unit           | Bargaining Unit           | text      | text        |
| Yes      | series tag     | link                      | Link                      | url       | url         |
| Yes      | numeric metric | locals                    | Locals                    | number    | number      |
| Yes      | series tag     | bargaining_unit_full_name | Bargaining Unit Full Name | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8tar-cztq d:2016-10-11T19:09:17.000Z t:folder=2004-2008 t:link=http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-1767-Investigators.pdf t:bargaining_unit=AFSCME t:bargaining_unit_full_name="American Federation State County Municipal Employees" m:locals=1767

series e:8tar-cztq d:2016-10-11T19:09:17.000Z t:folder=2004-2008 t:link=http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-2060-States-Attorney.pdf t:bargaining_unit=AFSCME t:bargaining_unit_full_name="American Federation State County Municipal Employees" m:locals=2060

series e:8tar-cztq d:2016-10-11T19:09:17.000Z t:folder=2004-2008 t:link=http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-2226-Correctional-Lieutenants.pdf t:bargaining_unit=AFSCME t:bargaining_unit_full_name="American Federation State County Municipal Employees" m:locals=2226
```

## Meta Commands

```ls
metric m:locals p:integer l:Locals t:dataTypeName=number

entity e:8tar-cztq l:"Human Resources - Collective Bargaining Agreements" t:attribution="Bureau of Human Resources" t:url=https://datacatalog.cookcountyil.gov/api/views/8tar-cztq

property e:8tar-cztq t:meta.view v:id=8tar-cztq v:category="Finance & Administration" v:attributionLink=https://www.cookcountyil.gov/agency/bureau-human-resources-0 v:averageRating=0 v:name="Human Resources - Collective Bargaining Agreements" v:attribution="Bureau of Human Resources"

property e:8tar-cztq t:meta.view.license v:name="Public Domain"

property e:8tar-cztq t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:8tar-cztq t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| :updated_at | folder    | bargaining_unit | link                                                                                                                                                                                     | locals | bargaining_unit_full_name                            | 
| =========== | ========= | =============== | ======================================================================================================================================================================================== | ====== | ==================================================== | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-1111-1178--1276-Health-Facilities.pdf, AFSCME-1111-1178--1276-Health-Facilities.pdf]                 |        | American Federation State County Municipal Employees | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-1767-Investigators.pdf, AFSCME-1767-Investigators.pdf]                                               | 1767   | American Federation State County Municipal Employees | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-2060-States-Attorney.pdf, AFSCME-2060-States-Attorney.pdf]                                           | 2060   | American Federation State County Municipal Employees | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-2226-Correctional-Lieutenants.pdf, AFSCME-2226-Correctional-Lieutenants.pdf]                         | 2226   | American Federation State County Municipal Employees | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-2264-County-Police-Officers.pdf, AFSCME-2264-County-Police-Officers.pdf]                             | 2264   | American Federation State County Municipal Employees | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-3315-Assist-Public-Defenders.pdf, AFSCME-3315-Assist-Public-Defenders.pdf]                           | 3315   | American Federation State County Municipal Employees | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-3368-Circuit-Court.pdf, AFSCME-3368-Circuit-Court.pdf]                                               | 3368   | American Federation State County Municipal Employees | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-3477-Chief-Judge-Probation-Officers.pdf, AFSCME-3477-Chief-Judge-Probation-Officers.pdf]             | 3477   | American Federation State County Municipal Employees | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-3486-Chief-Judge-Adult-Probation-Officers.pdf, AFSCME-3486-Chief-Judge-Adult-Probation-Officers.pdf] | 3486   | American Federation State County Municipal Employees | 
| 1476212957  | 2004-2008 | AFSCME          | [http://opendocs.cookcountyil.gov/human-resources/labor-agreements/2004-2008/AFSCME-3692-Correctional-Sergeants.pdf, AFSCME-3692-Correctional-Sergeants.pdf]                             | 3692   | American Federation State County Municipal Employees | 
```