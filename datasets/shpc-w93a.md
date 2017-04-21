# Media Production & Development Zone Nominations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/media-production-development-zone-nominations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/shpc-w93a) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/shpc-w93a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/shpc-w93a/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | shpc-w93a |
| Name | Media Production & Development Zone Nominations |
| Category | Business |
| Created | 2016-06-24T19:07:43Z |
| Publication Date | 2016-06-24T21:08:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | ============== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag     | firm                              | Firm                              | text          | text          |
| Yes      | series tag     | project_description               | Project Description               | text          | text          |
| Yes      | time           | date_approved                     | Date Approved                     | calendar_date | calendar_date |
| Yes      | series tag     | city_council_ordinance_resolution | City Council Ordinance/Resolution | url           | url           |
| Yes      | series tag     | incentive_basis                   | Incentive Basis                   | text          | text          |
| Yes      | numeric metric | total_incentive                   | Total Incentive                   | money         | money         |
| Yes      | numeric metric | total_project_investment          | Total Project Investment          | money         | money         |
| Yes      | series tag     | location                          | Location                          | text          | text          |
| Yes      | series tag     | 3rd_party_economic_impact_report  | 3rd Party Economic Impact Report  | url           | url           |
```

## Time Field

```ls
Value = date_approved
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:shpc-w93a d:2016-06-23T00:00:00.000Z t:location="7620 Guadalupe Street, Austin, TX 78752" t:firm="Certain Affinity" t:incentive_basis="1% sales and use tax exemption" t:project_description="Digital Media & Gaming" t:3rd_party_economic_impact_report=http://www.austintexas.gov/sites/default/files/files/TXP_Certain_Affinity_051916.pdf m:total_project_investment=6926400 m:total_incentive=69264
```

## Meta Commands

```ls
metric m:total_incentive p:integer l:"Total Incentive" t:dataTypeName=money

metric m:total_project_investment p:integer l:"Total Project Investment" t:dataTypeName=money

entity e:shpc-w93a l:"Media Production & Development Zone Nominations" t:url=https://data.austintexas.gov/api/views/shpc-w93a

property e:shpc-w93a t:meta.view v:id=shpc-w93a v:category=Business v:averageRating=0 v:name="Media Production & Development Zone Nominations"

property e:shpc-w93a t:meta.view.owner v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:displayName="Melissa Alvarado"

property e:shpc-w93a t:meta.view.tableauthor v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:roleName=editor v:displayName="Melissa Alvarado"
```

## Top Records

```ls
| firm             | project_description    | date_approved       | city_council_ordinance_resolution | incentive_basis                | total_incentive | total_project_investment | location                                | 3rd_party_economic_impact_report                                                                              | 
| ================ | ====================== | =================== | ================================= | ============================== | =============== | ======================== | ======================================= | ============================================================================================================= | 
| Certain Affinity | Digital Media & Gaming | 2016-06-23T00:00:00 | [null, null]                      | 1% sales and use tax exemption | 69264           | 6926400                  | 7620 Guadalupe Street, Austin, TX 78752 | [http://www.austintexas.gov/sites/default/files/files/TXP_Certain_Affinity_051916.pdf, TXP Economic Analysis] | 
```