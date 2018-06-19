# City Building Codes for Missouri

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-building-codes-for-missouri-be778) |
| Metadata | [Link](https://data.mo.gov/api/views/hhyk-mgim) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/hhyk-mgim/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/hhyk-mgim/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | hhyk-mgim |
| Name | City Building Codes for Missouri |
| Attribution | DED |
| Category | Economic Development |
| Tags | building codes, fips, economic development |
| Created | 2014-02-13T15:01:50Z |
| Publication Date | 2016-09-19T13:41:13Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | city_fips               | City FIPS               | text      | number      |
| Yes      | series tag     | county_fips             | County FIPS             | text      | number      |
| Yes      | series tag     | jurisdiction            | Jurisdiction            | text      | text        |
| Yes      | series tag     | energy_building_code    | Energy Building Code    | text      | text        |
| Yes      | series tag     | residential_code        | Residential Code        | text      | text        |
| Yes      | series tag     | commercial_code         | Commercial Code         | text      | text        |
| Yes      | series tag     | population_jurisdiction | Population Jurisdiction | text      | text        |
| Yes      | numeric metric | 2010                    | 2010                    | number    | number      |
| Yes      | series tag     | county                  | County                  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hhyk-mgim d:2014-07-02T13:57:22.000Z t:county_fips=13 t:county=Bates t:city_fips=244 t:jurisdiction=Adrian t:population_jurisdiction=Adrian m:2010=1677

series e:hhyk-mgim d:2014-07-02T13:57:22.000Z t:county_fips=207 t:county=Stoddard t:city_fips=262 t:jurisdiction=Advance t:population_jurisdiction=Advance m:2010=1347

series e:hhyk-mgim d:2014-07-02T13:57:22.000Z t:commercial_code="2009 IBC" t:county_fips=189 t:county=St.Louis t:city_fips=280 t:energy_building_code="2009 IECC" t:jurisdiction=Affton t:population_jurisdiction=Affton t:residential_code="2009 IRC" m:2010=20307
```

## Meta Commands

```ls
metric m:2010 p:integer l:2010 t:dataTypeName=number

entity e:hhyk-mgim l:"City Building Codes for Missouri" t:attribution=DED t:url=https://data.mo.gov/api/views/hhyk-mgim

property e:hhyk-mgim t:meta.view v:id=hhyk-mgim v:category="Economic Development" v:averageRating=0 v:name="City Building Codes for Missouri" v:attribution=DED

property e:hhyk-mgim t:meta.view.owner v:id=jbwu-ft8c v:screenName="Andy Popp" v:displayName="Andy Popp"

property e:hhyk-mgim t:meta.view.tableauthor v:id=jbwu-ft8c v:screenName="Andy Popp" v:roleName=editor v:displayName="Andy Popp"
```

## Top Records

```ls
| :updated_at | city_fips | county_fips | jurisdiction  | energy_building_code | residential_code | commercial_code | population_jurisdiction | 2010  | county   | 
| =========== | ========= | =========== | ============= | ==================== | ================ | =============== | ======================= | ===== | ======== | 
| 1404309442  | 244       | 13          | Adrian        |                      |                  |                 | Adrian                  | 1677  | Bates    | 
| 1404309442  | 262       | 207         | Advance       |                      |                  |                 | Advance                 | 1347  | Stoddard | 
| 1404309442  | 280       | 189         | Affton        | 2009 IECC            | 2009 IRC         | 2009 IBC        | Affton                  | 20307 | St.Louis | 
| 1404309442  | 298       | 21          | Agency        |                      |                  |                 | Agency                  | 684   | Buchanan | 
| 1404309442  | 424       | 97          | Airport Drive |                      |                  |                 | Airport Drive           | 698   | Jasper   | 
| 1404309442  | 514       | 75          | Albany        |                      |                  |                 | Albany                  | 1730  | Gentry   | 
| 1404309442  | 568       | 167         | Aldrich       |                      |                  |                 | Aldrich                 | 80    | Polk     | 
| 1404309442  | 596       | 97          | Alba          |                      |                  |                 | Alba                    | 555   | Jasper   | 
| 1404309442  | 604       | 45          | Alexandria    |                      |                  |                 | Alexandria              | 159   | Clark    | 
| 1404309442  | 712       | 227         | Allendale     |                      |                  |                 | Allendale               | 53    | Worth    | 
```