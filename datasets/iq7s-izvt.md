# County Building Codes for Missouri

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-building-codes-for-missouri-50936) |
| Metadata | [Link](https://data.mo.gov/api/views/iq7s-izvt) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/iq7s-izvt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/iq7s-izvt/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | iq7s-izvt |
| Name | County Building Codes for Missouri |
| Attribution | DED |
| Category | Economic Development |
| Tags | building codes, economic development |
| Created | 2014-02-13T15:48:20Z |
| Publication Date | 2017-04-06T17:04:46Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | fips                 | FIPS                 | text      | number      |
| Yes      | series tag     | county               | County               | text      | text        |
| Yes      | series tag     | energy_building_code | Energy Building Code | text      | text        |
| Yes      | series tag     | residential_code     | Residential Code     | text      | text        |
| Yes      | series tag     | commercial_code      | Commercial Code      | text      | text        |
| Yes      | numeric metric | population           | Population           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:iq7s-izvt d:2014-02-13T07:48:25.000Z t:commercial_code=- t:county="Adair County" t:energy_building_code=- t:residential_code=- t:fips=1 m:population=25607

series e:iq7s-izvt d:2014-02-13T07:48:25.000Z t:commercial_code=- t:county="Andrew County" t:energy_building_code=- t:residential_code=- t:fips=3 m:population=17291

series e:iq7s-izvt d:2014-02-13T07:48:25.000Z t:commercial_code=- t:county="Atchison County" t:energy_building_code=- t:residential_code=- t:fips=5 m:population=5685
```

## Meta Commands

```ls
metric m:population p:integer l:Population t:dataTypeName=number

entity e:iq7s-izvt l:"County Building Codes for Missouri" t:attribution=DED t:url=https://data.mo.gov/api/views/iq7s-izvt

property e:iq7s-izvt t:meta.view v:id=iq7s-izvt v:category="Economic Development" v:averageRating=0 v:name="County Building Codes for Missouri" v:attribution=DED

property e:iq7s-izvt t:meta.view.owner v:id=jbwu-ft8c v:screenName="Andy Popp" v:displayName="Andy Popp"

property e:iq7s-izvt t:meta.view.tableauthor v:id=jbwu-ft8c v:screenName="Andy Popp" v:roleName=editor v:displayName="Andy Popp"
```

## Top Records

```ls
| :updated_at | fips | county           | energy_building_code | residential_code | commercial_code | population | 
| =========== | ==== | ================ | ==================== | ================ | =============== | ========== | 
| 1392277705  | 1    | Adair County     | -                    | -                | -               | 25607      | 
| 1392277705  | 3    | Andrew County    | -                    | -                | -               | 17291      | 
| 1392277705  | 5    | Atchison County  | -                    | -                | -               | 5685       | 
| 1392277705  | 7    | Audrain County   | -                    | -                | -               | 25529      | 
| 1392277705  | 9    | Barry County     | -                    | -                | -               | 35597      | 
| 1392277705  | 11   | Barton County    | -                    | -                | -               | 12402      | 
| 1392277705  | 13   | Bates County     | -                    | -                | -               | 17049      | 
| 1392277705  | 15   | Benton County    | -                    | -                | -               | 19056      | 
| 1392277705  | 17   | Bollinger County | -                    | -                | -               | 12363      | 
| 1392277705  | 19   | Boone County     | -                    | 2009 IRC         | 2009 IBC        | 162642     | 
```