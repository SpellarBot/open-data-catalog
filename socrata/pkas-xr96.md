# NNDSS - Table IV. Tuberculosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-iv-tuberculosis) |
| Metadata | [Link](https://data.cdc.gov/api/views/pkas-xr96) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/pkas-xr96/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/pkas-xr96/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | pkas-xr96 |
| Name | NNDSS - Table IV. Tuberculosis |
| Attribution | Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention |
| Category | NNDSS |
| Tags | 2016, mmwr, nndss, wonder, nedss, netss, tuberculosis, tb |
| Created | 2016-04-14T14:28:45Z |
| Publication Date | 2017-01-13T16:57:21Z |

## Description

NNDSS - Table IV. Tuberculosis - 2016.This Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States will exclude counts from US territories.  Footnote: C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable    Cum: Cumulative year-to-date counts.    Min: Minimum.    Max: Maximum. * Case counts for reporting year 2015 and 2016 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf Data for TB are displayed quarterly.

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
| Yes      | numeric metric | tuberculosis_cum_2016                     | Tuberculosis?, Cum 2016                      | number    | number      |
| No       |                | tuberculosis_cum_2016_flag                | Tuberculosis?, Cum 2016, flag                | text      | text        |
| Yes      | numeric metric | tuberculosis_cum_2015                     | Tuberculosis?, Cum 2015                      | number    | number      |
| No       |                | tuberculosis_cum_2015_flag                | Tuberculosis?, Cum 2015, flag                | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = tuberculosis_current_quarter,tuberculosis_current_quarter_flag,tuberculosis_previous_4_quarters_min_flag,tuberculosis_previous_4_quarters_max_flag,tuberculosis_cum_2016_flag,tuberculosis_cum_2015_flag,mmwr_year,mmwr_quarter
```

## Data Commands

```ls
series e:pkas-xr96 d:2016-01-01T00:00:00.000Z t:reporting_area="UNITED STATES" m:tuberculosis_cum_2016=1289 m:tuberculosis_previous_4_quarters_max=2717 m:tuberculosis_previous_4_quarters_min=1289 m:tuberculosis_cum_2015=1305

series e:pkas-xr96 d:2016-01-01T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:tuberculosis_cum_2016=40 m:tuberculosis_previous_4_quarters_max=90 m:tuberculosis_previous_4_quarters_min=40 m:tuberculosis_cum_2015=41

series e:pkas-xr96 d:2016-01-01T00:00:00.000Z t:reporting_area=CONNECTICUT m:tuberculosis_cum_2016=4 m:tuberculosis_previous_4_quarters_max=24 m:tuberculosis_previous_4_quarters_min=4 m:tuberculosis_cum_2015=9
```

## Meta Commands

```ls
metric m:tuberculosis_previous_4_quarters_min p:integer l:"Tuberculosis?, Previous 4 quarters Min" t:dataTypeName=number

metric m:tuberculosis_previous_4_quarters_max p:integer l:"Tuberculosis?, Previous 4 quarters Max" t:dataTypeName=number

metric m:tuberculosis_cum_2016 p:integer l:"Tuberculosis?, Cum 2016" t:dataTypeName=number

metric m:tuberculosis_cum_2015 p:integer l:"Tuberculosis?, Cum 2015" t:dataTypeName=number

entity e:pkas-xr96 l:"NNDSS - Table IV. Tuberculosis" t:attribution="Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention" t:url=https://data.cdc.gov/api/views/pkas-xr96

property e:pkas-xr96 t:meta.view v:id=pkas-xr96 v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table IV. Tuberculosis" v:attribution="Division of STD Prevention, National Center for HIV/AIDS, Viral Hepatitis, STD, and TB Prevention"

property e:pkas-xr96 t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:pkas-xr96 t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:pkas-xr96 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_quarter | tuberculosis_current_quarter | tuberculosis_current_quarter_flag | tuberculosis_previous_4_quarters_min | tuberculosis_previous_4_quarters_min_flag | tuberculosis_previous_4_quarters_max | tuberculosis_previous_4_quarters_max_flag | tuberculosis_cum_2016 | tuberculosis_cum_2016_flag | tuberculosis_cum_2015 | tuberculosis_cum_2015_flag | 
| ============== | ========= | ============ | ============================ | ================================= | ==================================== | ========================================= | ==================================== | ========================================= | ===================== | ========================== | ===================== | ========================== | 
| UNITED STATES  | 2016      | 1            | 1289                         |                                   | 1289                                 |                                           | 2717                                 |                                           | 1289                  |                            | 1305                  |                            | 
| NEW ENGLAND    | 2016      | 1            | 40                           |                                   | 40                                   |                                           | 90                                   |                                           | 40                    |                            | 41                    |                            | 
| CONNECTICUT    | 2016      | 1            | 4                            |                                   | 4                                    |                                           | 24                                   |                                           | 4                     |                            | 9                     |                            | 
| MAINE          | 2016      | 1            | 5                            |                                   | 3                                    |                                           | 7                                    |                                           | 5                     |                            | 1                     |                            | 
| MASSACHUSETTS  | 2016      | 1            | 28                           |                                   | 28                                   |                                           | 56                                   |                                           | 28                    |                            | 26                    |                            | 
| NEW HAMPSHIRE  | 2016      | 1            |                              | -                                 | 0                                    |                                           | 4                                    |                                           |                       | -                          | 2                     |                            | 
| RHODE ISLAND   | 2016      | 1            | 3                            |                                   | 3                                    |                                           | 13                                   |                                           | 3                     |                            | 1                     |                            | 
| VERMONT        | 2016      | 1            |                              | -                                 | 0                                    |                                           | 2                                    |                                           |                       | -                          | 2                     |                            | 
| MID. ATLANTIC  | 2016      | 1            | 224                          |                                   | 224                                  |                                           | 364                                  |                                           | 224                   |                            | 181                   |                            | 
| NEW JERSEY     | 2016      | 1            | 38                           |                                   | 38                                   |                                           | 118                                  |                                           | 38                    |                            | 20                    |                            | 
```