# Designated Landmarks

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/designated-landmarks-c13be) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/cpd3-yi9b) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/cpd3-yi9b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/cpd3-yi9b/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | cpd3-yi9b |
| Name | Designated Landmarks |
| Attribution | City of Baltimore |
| Category | Culture & Arts |
| Tags | landmarks |
| Created | 2011-12-14T16:23:01Z |
| Publication Date | 2014-04-03T23:46:36Z |

## Description

This data shows designated landmarks within the City of Baltimore

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
| Yes      | series tag  | zipcode         | zipCode         | text      | text        |
| Yes      | series tag  | neighborhood    | neighborhood    | text      | text        |
| Yes      | series tag  | councildistrict | councilDistrict | text      | number      |
| Yes      | series tag  | policedistrict  | policeDistrict  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cpd3-yi9b d:2011-12-14T08:23:31.000Z t:councildistrict=11 t:zipcode=21202 t:name="City Hall" t:neighborhood=Downtown t:policedistrict=CENTRAL m:row_number.cpd3-yi9b=1

series e:cpd3-yi9b d:2011-12-14T08:23:31.000Z t:councildistrict=11 t:zipcode=21201 t:name="Otterbein Church" t:neighborhood="Inner Harbor" t:policedistrict=CENTRAL m:row_number.cpd3-yi9b=2

series e:cpd3-yi9b d:2011-12-14T08:23:31.000Z t:councildistrict=12 t:zipcode=21202 t:name="McKim Free School" t:neighborhood=Jonestown t:policedistrict=SOUTHEASTERN m:row_number.cpd3-yi9b=3
```

## Meta Commands

```ls
metric m:row_number.cpd3-yi9b p:long l:"Row Number"

entity e:cpd3-yi9b l:"Designated Landmarks" t:attribution="City of Baltimore" t:url=https://data.baltimorecity.gov/api/views/cpd3-yi9b

property e:cpd3-yi9b t:meta.view v:id=cpd3-yi9b v:category="Culture & Arts" v:attributionLink=http://www.baltimorecity.gov/ v:averageRating=0 v:name="Designated Landmarks" v:attribution="City of Baltimore"

property e:cpd3-yi9b t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:cpd3-yi9b t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:cpd3-yi9b t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                                           | zipcode | neighborhood    | councildistrict | policedistrict | 
| =========== | ============================================== | ======= | =============== | =============== | ============== | 
| 1323851011  | City Hall                                      | 21202   | Downtown        | 11              | CENTRAL        | 
| 1323851011  | Otterbein Church                               | 21201   | Inner Harbor    | 11              | CENTRAL        | 
| 1323851011  | McKim Free School                              | 21202   | Jonestown       | 12              | SOUTHEASTERN   | 
| 1323851011  | First Unitarian Church                         | 21201   | Mount Vernon    | 11              | CENTRAL        | 
| 1323851011  | Ebenezer A.M.E. Church                         | 21230   | Federal Hill    | 11              | SOUTHERN       | 
| 1323851011  | Municipal Museum of Balt (Peale Museum)        | 21202   | Downtown        | 11              | CENTRAL        | 
| 1323851011  | Lovely Lane Methodist Church (First Methodist) | 21218   | Charles Village | 12              | NORTHERN       | 
| 1323851011  | Lloyd Street Synagogue                         | 21202   | Jonestown       | 12              | SOUTHEASTERN   | 
| 1323851011  | Bethel A.M.E. Church                           | 21217   | Upton           | 11              | CENTRAL        | 
| 1323851011  | Eutaw Place Baptist Church                     | 21217   | Madison Park    | 11              | CENTRAL        | 
```