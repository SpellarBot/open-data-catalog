# Grant Information Collection Act - 1 2nd Quarter

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grant-information-collection-act-1-2nd-quarter-24148) |
| Metadata | [Link](https://data.illinois.gov/api/views/phym-p7aq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/phym-p7aq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/phym-p7aq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | phym-p7aq |
| Name | Grant Information Collection Act - 1 2nd Quarter |
| Attribution | Illinois Arts Council Agency |
| Tags | illinois arts council agency |
| Created | 2013-12-20T21:11:12Z |
| Publication Date | 2013-12-23T17:47:06Z |

## Description

Illinois Arts Council Grants

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | agency              | Agency              | text          | text          |
| Yes      | series tag     | grantee_name        | Grantee Name        | text          | text          |
| Yes      | series tag     | project_description | Project Description | text          | text          |
| Yes      | numeric metric | grant_amount        | Grant Amount        | money         | money         |
| Yes      | time           | grant_award_date    | Grant Award Date    | calendar_date | calendar_date |
| No       |                | beginning_date      | Beginning Date      | calendar_date | calendar_date |
| No       |                | endning_date        | Endning Date        | calendar_date | calendar_date |
```

## Time Field

```ls
Value = grant_award_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = beginning_date,endning_date
```

## Data Commands

```ls
series e:phym-p7aq d:2013-10-21T00:00:00.000Z t:grantee_name="The Lira Ensemble" t:agency="Illinois Arts Council Agency" t:project_description="for general operating support" m:grant_amount=8050

series e:phym-p7aq d:2013-10-21T00:00:00.000Z t:grantee_name="The Summer Place Inc" t:agency="Illinois Arts Council Agency" t:project_description="for general operating support" m:grant_amount=1515

series e:phym-p7aq d:2013-10-21T00:00:00.000Z t:grantee_name="Southside Community Art Center" t:agency="Illinois Arts Council Agency" t:project_description="for general operating support" m:grant_amount=7025
```

## Meta Commands

```ls
metric m:grant_amount p:integer l:"Grant Amount" t:dataTypeName=money

entity e:phym-p7aq l:"Grant Information Collection Act - 1  2nd Quarter" t:attribution="Illinois Arts Council Agency" t:url=https://data.illinois.gov/api/views/phym-p7aq

property e:phym-p7aq t:meta.view v:id=phym-p7aq v:averageRating=0 v:name="Grant Information Collection Act - 1  2nd Quarter" v:attribution="Illinois Arts Council Agency"

property e:phym-p7aq t:meta.view.owner v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"

property e:phym-p7aq t:meta.view.tableauthor v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"
```

## Top Records

```ls
| agency                       | grantee_name                   | project_description                                    | grant_amount | grant_award_date    | beginning_date      | endning_date        | 
| ============================ | ============================== | ====================================================== | ============ | =================== | =================== | =================== | 
| Illinois Arts Council Agency | The Lira Ensemble              | for general operating support                          | 8050         | 2013-10-21T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| Illinois Arts Council Agency | The Summer Place Inc           | for general operating support                          | 1515         | 2013-10-21T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| Illinois Arts Council Agency | Southside Community Art Center | for general operating support                          | 7025         | 2013-10-21T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| Illinois Arts Council Agency | About Face Theatre Collective  | for general operating support                          | 11050        | 2013-10-09T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| Illinois Arts Council Agency | Oak Park Concert Chorale       | for general operating support                          | 1850         | 2013-11-04T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| Illinois Arts Council Agency | Macomb Community Theatre       | for general operating support                          | 1150         | 2013-10-03T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| Illinois Arts Council Agency | Columbia College Chicago       | for Community Arts Ed conference participation support | 595          | 2013-12-02T00:00:00 | 2013-10-30T00:00:00 | 2013-11-30T00:00:00 | 
| Illinois Arts Council Agency | Illinois Symphony Orchestra    | for general operating support                          | 12100        | 2013-11-25T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| Illinois Arts Council Agency | Fund for Innovative TV         | for general operating support                          | 2515         | 2013-10-10T00:00:00 | 2013-09-15T00:00:00 | 2014-08-31T00:00:00 | 
| Illinois Arts Council Agency | Old Town School of Folk Music  | for Community Arts Ed conference participation support | 650          | 2013-11-14T00:00:00 | 2013-10-29T00:00:00 | 2013-11-30T00:00:00 | 
```