# NNDSS - Table IV. Tuberculosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-iv-tuberculosis-83da5) |
| Metadata | [Link](https://data.cdc.gov/api/views/ei7y-3g6s) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/ei7y-3g6s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/ei7y-3g6s/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | ei7y-3g6s |
| Name | NNDSS - Table IV. Tuberculosis |
| Attribution | Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention |
| Category | NNDSS |
| Tags | 2015, mmwr, nndss, wonder, nedss, netss, tuberculosis, tb |
| Created | 2015-04-14T20:05:39Z |
| Publication Date | 2016-01-14T21:40:04Z |

## Description

NNDSS - Table IV. Tuberculosis - 2015.This Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States will exclude counts from US territories.  Footnote:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable    Cum: Cumulative year-to-date counts.    Min: Minimum.    Max: Maximum. * Case counts for reporting year 2014 and 2015 are provisional through the end of the quarter,  January 2, 2016. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf Data for TB are displayed quarterly.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                         | Data Type | Render Type |
| ======== | ============== | ========================================= | ============================================ | ========= | =========== |
| Yes      | series tag     | reporting_area                            | Reporting area                               | text      | text        |
| No       |                | mmwr_year                                 | MMWR Year                                    | number    | number      |
| No       |                | mmwr_quarter                              | MMWR Quarter                                 | number    | number      |
| No       |                | tuberculosis_current_quarter              | Tuberculosis?, Current quarter               | number    | number      |
| No       |                | tuberculosis_current_quarter_flag         | Tuberculosis?, Current quarter, flag         | text      | text        |
| Yes      | numeric metric | tuberculosis_previous_4_quarters_min      | Tuberculosis?, Previous 4 quarters Min       | number    | number      |
| No       |                | tuberculosis_previous_4_quarters_min_flag | Tuberculosis?, Previous 4 quarters Min, flag | text      | text        |
| Yes      | numeric metric | tuberculosis_previous_4_quarters_max      | Tuberculosis?, Previous 4 quarters Max       | number    | number      |
| No       |                | tuberculosis_previous_4_quarters_max_flag | Tuberculosis?, Previous 4 quarters Max, flag | text      | text        |
| Yes      | numeric metric | tuberculosis_cum_2015                     | Tuberculosis?, Cum 2015                      | number    | number      |
| No       |                | tuberculosis_cum_2015_flag                | Tuberculosis?, Cum 2015, flag                | text      | text        |
| Yes      | numeric metric | tuberculosis_cum_2014                     | Tuberculosis?, Cum 2014                      | number    | number      |
| No       |                | tuberculosis_cum_2014_flag                | Tuberculosis?, Cum 2014, flag                | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = tuberculosis_current_quarter,tuberculosis_current_quarter_flag,tuberculosis_previous_4_quarters_min_flag,tuberculosis_previous_4_quarters_max_flag,tuberculosis_cum_2015_flag,tuberculosis_cum_2014_flag,mmwr_year,mmwr_quarter
```

## Data Commands

```ls
series e:ei7y-3g6s d:2015-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:tuberculosis_previous_4_quarters_max=2849 m:tuberculosis_previous_4_quarters_min=1471 m:tuberculosis_cum_2014=1249 m:tuberculosis_cum_2015=1471

series e:ei7y-3g6s d:2015-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:tuberculosis_previous_4_quarters_max=86 m:tuberculosis_previous_4_quarters_min=45 m:tuberculosis_cum_2014=51 m:tuberculosis_cum_2015=45

series e:ei7y-3g6s d:2015-01-01T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:tuberculosis_previous_4_quarters_max=383 m:tuberculosis_previous_4_quarters_min=247 m:tuberculosis_cum_2014=157 m:tuberculosis_cum_2015=247
```

## Meta Commands

```ls
metric m:tuberculosis_previous_4_quarters_min p:integer l:"Tuberculosis?, Previous 4 quarters Min" t:dataTypeName=number

metric m:tuberculosis_previous_4_quarters_max p:integer l:"Tuberculosis?, Previous 4 quarters Max" t:dataTypeName=number

metric m:tuberculosis_cum_2015 p:integer l:"Tuberculosis?, Cum 2015" t:dataTypeName=number

metric m:tuberculosis_cum_2014 p:integer l:"Tuberculosis?, Cum 2014" t:dataTypeName=number

entity e:ei7y-3g6s l:"NNDSS - Table IV. Tuberculosis" t:attribution="Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention" t:url=https://data.cdc.gov/api/views/ei7y-3g6s

property e:ei7y-3g6s t:meta.view v:id=ei7y-3g6s v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table IV. Tuberculosis" v:attribution="Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention"

property e:ei7y-3g6s t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:ei7y-3g6s t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:ei7y-3g6s t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_quarter | tuberculosis_current_quarter | tuberculosis_current_quarter_flag | tuberculosis_previous_4_quarters_min | tuberculosis_previous_4_quarters_min_flag | tuberculosis_previous_4_quarters_max | tuberculosis_previous_4_quarters_max_flag | tuberculosis_cum_2015 | tuberculosis_cum_2015_flag | tuberculosis_cum_2014 | tuberculosis_cum_2014_flag | 
| ============== | ========= | ============ | ============================ | ================================= | ==================================== | ========================================= | ==================================== | ========================================= | ===================== | ========================== | ===================== | ========================== | 
| UNITED STATES  | 2015      | 1            | 1471                         |                                   | 1471                                 |                                           | 2849                                 |                                           | 1471                  |                            | 1249                  |                            | 
| NEW ENGLAND    | 2015      | 1            | 45                           |                                   | 45                                   |                                           | 86                                   |                                           | 45                    |                            | 51                    |                            | 
| MID. ATLANTIC  | 2015      | 1            | 247                          |                                   | 247                                  |                                           | 383                                  |                                           | 247                   |                            | 157                   |                            | 
| E.N. CENTRAL   | 2015      | 1            | 137                          |                                   | 137                                  |                                           | 239                                  |                                           | 137                   |                            | 103                   |                            | 
| W.N. CENTRAL   | 2015      | 1            | 37                           |                                   | 37                                   |                                           | 137                                  |                                           | 37                    |                            | 51                    |                            | 
| S. ATLANTIC    | 2015      | 1            | 257                          |                                   | 257                                  |                                           | 486                                  |                                           | 257                   |                            | 208                   |                            | 
| DIST. OF COL.  | 2015      | 1            | 6                            |                                   | 4                                    |                                           | 12                                   |                                           | 6                     |                            | 4                     |                            | 
| E.S. CENTRAL   | 2015      | 1            | 88                           |                                   | 88                                   |                                           | 137                                  |                                           | 88                    |                            | 62                    |                            | 
| W.S. CENTRAL   | 2015      | 1            | 319                          |                                   | 319                                  |                                           | 412                                  |                                           | 319                   |                            | 210                   |                            | 
| MOUNTAIN       | 2015      | 1            | 46                           |                                   | 46                                   |                                           | 168                                  |                                           | 46                    |                            | 27                    |                            | 
```