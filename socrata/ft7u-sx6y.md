# Oregon Section 18 exemptions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-section-18-exemptions-15f45) |
| Metadata | [Link](https://data.oregon.gov/api/views/ft7u-sx6y) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ft7u-sx6y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ft7u-sx6y/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ft7u-sx6y |
| Name | Oregon Section 18 exemptions |
| Category | Natural Resources |
| Tags | pesticides |
| Created | 2014-07-25T17:45:19Z |
| Publication Date | 2015-02-11T19:28:57Z |

## Columns

```ls
| Included | Schema Type | Field Name               | Name                       | Data Type | Render Type |
| ======== | =========== | ======================== | ========================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | crop_pest                | Crop, pest                 | text      | text        |
| Yes      | series tag  | pesticide_epa_reg_number | Pesticide, EPA reg. number | text      | text        |
| Yes      | series tag  | dates_section_18_number  | Effective dates            | text      | text        |
| Yes      | series tag  | oregon_label_number      | Oregon label number        | text      | text        |
| Yes      | series tag  | label                    | Label                      | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ft7u-sx6y d:2015-02-11T11:28:53.000Z t:label.file_id=DvxqbqQrBy24JWfv734jzjYdXQSA7PdNzntEV6CnI4M t:dates_section_18_number=02/4/2015-12/31/2015 t:label.content_type="application/pdf; charset=binary" t:crop_pest="Honey bees, varroa mite" t:label.filename=HopGuardIILabel.pdf t:pesticide_epa_reg_number="HopGuard II, not EPA registered" t:oregon_label_number=15-OR-01 t:label.size=91172 m:row_number.ft7u-sx6y=1
```

## Meta Commands

```ls
metric m:row_number.ft7u-sx6y p:long l:"Row Number"

entity e:ft7u-sx6y l:"Oregon Section 18 exemptions" t:url=https://data.oregon.gov/api/views/ft7u-sx6y

property e:ft7u-sx6y t:meta.view v:id=ft7u-sx6y v:category="Natural Resources" v:averageRating=0 v:name="Oregon Section 18 exemptions"

property e:ft7u-sx6y t:meta.view.owner v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:displayName="Andy Zimmerman"

property e:ft7u-sx6y t:meta.view.tableauthor v:id=xzpq-yk3z v:screenName="Andy Zimmerman" v:roleName=editor v:displayName="Andy Zimmerman"
```

## Top Records

```ls
| :updated_at | crop_pest               | pesticide_epa_reg_number        | dates_section_18_number | oregon_label_number | label                                                                                                      | 
| =========== | ======================= | =============================== | ======================= | =================== | ========================================================================================================== | 
| 1423654133  | Honey bees, varroa mite | HopGuard II, not EPA registered | 02/4/2015-12/31/2015    | 15-OR-01            | [application/pdf; charset=binary, DvxqbqQrBy24JWfv734jzjYdXQSA7PdNzntEV6CnI4M, HopGuardIILabel.pdf, 91172] | 
```