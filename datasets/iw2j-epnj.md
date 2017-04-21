# 1Biennial Funding By Category (8-22-2016)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/biennial-funding-by-category-8-22-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/iw2j-epnj) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/iw2j-epnj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/iw2j-epnj/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | iw2j-epnj |
| Name | 1Biennial Funding By Category (8-22-2016) |
| Created | 2016-09-19T22:33:10Z |
| Publication Date | 2016-09-19T22:35:19Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | region              | Region              | text      | text        |
| Yes      | numeric metric | acquisition         | Acquisition         | money     | money       |
| Yes      | numeric metric | capacity            | Capacity            | money     | money       |
| Yes      | numeric metric | hatchery            | Hatchery            | money     | money       |
| Yes      | numeric metric | monitoring          | Monitoring          | money     | money       |
| Yes      | numeric metric | other               | Other               | money     | money       |
| Yes      | numeric metric | planning_assessment | Planning/Assessment | money     | money       |
| Yes      | numeric metric | restoration         | Restoration         | money     | money       |
| Yes      | numeric metric | total               | Total               | money     | money       |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:iw2j-epnj d:2016-01-01T00:00:00.000Z t:region=Northeast m:total=9893971 m:acquisition=0 m:restoration=8370495 m:monitoring=14888 m:other=17419 m:hatchery=0 m:planning_assessment=1178006 m:capacity=313164

series e:iw2j-epnj d:2016-01-01T00:00:00.000Z t:region=Snake m:total=28883751 m:acquisition=2015963 m:restoration=15986193 m:monitoring=1417665 m:other=0 m:hatchery=0 m:planning_assessment=9065342 m:capacity=398588

series e:iw2j-epnj d:2016-01-01T00:00:00.000Z t:region="Middle Columbia" m:total=32175617 m:acquisition=6359733 m:restoration=19619263 m:monitoring=14888 m:other=0 m:hatchery=0 m:planning_assessment=5492477 m:capacity=689256
```

## Meta Commands

```ls
metric m:acquisition p:double l:Acquisition t:dataTypeName=money

metric m:capacity p:integer l:Capacity t:dataTypeName=money

metric m:hatchery p:double l:Hatchery t:dataTypeName=money

metric m:monitoring p:integer l:Monitoring t:dataTypeName=money

metric m:other p:double l:Other t:dataTypeName=money

metric m:planning_assessment p:integer l:Planning/Assessment t:dataTypeName=money

metric m:restoration p:integer l:Restoration t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:iw2j-epnj l:"1Biennial Funding By Category (8-22-2016)" t:url=https://data.wa.gov/api/views/iw2j-epnj

property e:iw2j-epnj t:meta.view v:id=iw2j-epnj v:averageRating=0 v:name="1Biennial Funding By Category (8-22-2016)"

property e:iw2j-epnj t:meta.view.owner v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:displayName="Jennifer Johnson"

property e:iw2j-epnj t:meta.view.tableauthor v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:roleName=publisher v:displayName="Jennifer Johnson"
```

## Top Records

```ls
| region          | acquisition | capacity | hatchery | monitoring | other    | planning_assessment | restoration | total     | 
| =============== | =========== | ======== | ======== | ========== | ======== | =================== | =========== | ========= | 
| Northeast       | 0.0         | 313164   | 0.0      | 14888      | 17419    | 1178006             | 8370495     | 9893971   | 
| Snake           | 2015963     | 398588   | 0.0      | 1417665    | 0.0      | 9065342             | 15986193    | 28883751  | 
| Middle Columbia | 6359733     | 689256   | 0.0      | 14888      | 0.0      | 5492477             | 19619263    | 32175617  | 
| Upper Columbia  | 15488388    | 1103851  | 200000   | 115230     | 0.0      | 9002951             | 17893754    | 43804173  | 
| Hood Canal      | 9648423     | 15000    | 1627319  | 2770005    | 0.0      | 8843215             | 22528442    | 45432403  | 
| WA Coast        | 6426006     | 1245876  | 5872946  | 1481551    | 0.0      | 7821295             | 39176360    | 62024034  | 
| Statewide       | 0.0         | 755957   | 12040237 | 6415509    | 16812616 | 25510898            | 8954311     | 70489528  | 
| Lower Columbia  | 5221780     | 633250   | 10802967 | 11884840   | 44370    | 11036775            | 35065375    | 74689358  | 
| Puget Sound     | 136140572   | 13897555 | 28367347 | 47542336   | 3778592  | 80500611            | 206332176   | 516559189 | 
| All Projects    | 181300865   | 19052497 | 58910817 | 71656911   | 20652996 | 158451569           | 373926371   | 883952025 | 
```