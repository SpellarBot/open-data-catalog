# List of Blocks Where DPW Has a Tree Maintenance Agreement

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/list-of-blocks-where-dpw-has-a-tree-maintenance-agreement-e0e71) |
| Metadata | [Link](https://data.sfgov.org/api/views/fati-simc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/fati-simc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/fati-simc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | fati-simc |
| Name | List of Blocks Where DPW Has a Tree Maintenance Agreement |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | list, blocks, dpw, tree, maintenance, agreement, trees, public, works |
| Created | 2012-09-25T00:34:02Z |
| Publication Date | 2015-07-17T15:35:03Z |

## Description

Location and count of trees by block where DPW has a tree maintenance agreement.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| No       | time           | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | numeric metric | cnn                   | CNN                   | number    | number      |
| Yes      | series tag     | evensidetrees         | EvenSideTrees         | text      | text        |
| Yes      | series tag     | oddsidetrees          | OddSideTrees          | text      | text        |
| Yes      | series tag     | mediantrees           | MedianTrees           | text      | text        |
| Yes      | series tag     | dpwcommitment         | DPWcommitment         | text      | text        |
| Yes      | series tag     | blockdescription      | BlockDescription      | text      | text        |
| Yes      | series tag     | commitmentdescription | CommitmentDescription | text      | text        |
| Yes      | numeric metric | dpwtreesitecount      | DPWTreeSiteCount      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fati-simc d:2015-07-17T08:34:48.000Z t:blockdescription="02nd St  :  Howard St  -  Tehama St" t:mediantrees=No t:evensidetrees=No t:oddsidetrees=Yes t:commitmentdescription="Mixed: Odd Side" t:dpwcommitment=Mixed m:dpwtreesitecount=1 m:cnn=135000

series e:fati-simc d:2015-07-17T08:34:48.000Z t:blockdescription="02nd St  :  Tehama St  -  Clementina St" t:mediantrees=No t:evensidetrees=Yes t:oddsidetrees=No t:commitmentdescription="Mixed: Even Side" t:dpwcommitment=Mixed m:dpwtreesitecount=4 m:cnn=136000

series e:fati-simc d:2015-07-17T08:34:48.000Z t:blockdescription="03rd St  :  Folsom St  -  Saint Francis Pl" t:mediantrees=No t:evensidetrees=Yes t:oddsidetrees=No t:commitmentdescription="Mixed: Even Side" t:dpwcommitment=Mixed m:dpwtreesitecount=1 m:cnn=170000
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

metric m:dpwtreesitecount p:integer l:DPWTreeSiteCount t:dataTypeName=number

entity e:fati-simc l:"List of Blocks Where DPW Has a Tree Maintenance Agreement" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/fati-simc

property e:fati-simc t:meta.view v:id=fati-simc v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="List of Blocks Where DPW Has a Tree Maintenance Agreement" v:attribution="San Francisco Department of Public Works"

property e:fati-simc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:fati-simc t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:fati-simc t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| :updated_at | cnn    | evensidetrees | oddsidetrees | mediantrees | dpwcommitment | blockdescription                        | commitmentdescription | dpwtreesitecount | 
| =========== | ====== | ============= | ============ | =========== | ============= | ======================================= | ===================== | ================ | 
| 1437122088  | 135000 | No            | Yes          | No          | Mixed         | 02nd St : Howard St - Tehama St         | Mixed: Odd Side       | 1                | 
| 1437122088  | 136000 | Yes           | No           | No          | Mixed         | 02nd St : Tehama St - Clementina St     | Mixed: Even Side      | 4                | 
| 1437122088  | 170000 | Yes           | No           | No          | Mixed         | 03rd St : Folsom St - Saint Francis Pl  | Mixed: Even Side      | 1                | 
| 1437122088  | 202201 | Yes           | No           | Yes         | DPW           | 03rd St : Evans Ave - Fairfax Ave       | DPW: Even Side/Median | 3                | 
| 1437122088  | 211201 | Yes           | No           | Yes         | DPW           | 03rd St : Newcomb Ave - Oakdale Ave     | DPW: Even Side/Median | 5                | 
| 1437122088  | 297000 | No            | Yes          | No          | Mixed         | 05th St : Tehama St - Clementina St     | Mixed: Odd Side       | 1                | 
| 1437122088  | 298000 | Yes           | No           | No          | Mixed         | 05th St : Clementina St - Folsom St     | Mixed: Even Side      | 2                | 
| 1437122088  | 368000 | No            | Yes          | No          | Mixed         | 07th St : Mission St - Minna St         | Mixed: Odd Side       | 1                | 
| 1437122088  | 449000 | Yes           | No           | No          | Mixed         | 09th St : Minna St - Natoma St          | Mixed: Even Side      | 1                | 
| 1437122088  | 461000 | No            | No           | Yes         | DPW           | 10th Ave : Start: 01-99 Block - Lake St | DPW: Median           | 1                | 
```