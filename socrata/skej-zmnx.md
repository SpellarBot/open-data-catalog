# DSL Land Sales

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dsl-land-sales) |
| Metadata | [Link](https://data.oregon.gov/api/views/skej-zmnx) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/skej-zmnx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/skej-zmnx/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | skej-zmnx |
| Name | DSL Land Sales |
| Attribution | Department of State Lands |
| Category | Natural Resources |
| Created | 2016-07-14T16:37:45Z |
| Publication Date | 2016-09-02T00:01:16Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name         | Data Type | Render Type |
| ======== | =========== | =========== | ============ | ========= | =========== |
| No       | time        | :updated_at | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | sale        | Sale         | text      | text        |
| Yes      | series tag  | title       | Title        | text      | text        |
| Yes      | series tag  | county      | County       | text      | text        |
| Yes      | series tag  | description | Description  | text      | text        |
| Yes      | series tag  | map         | Map          | document  | document    |
| Yes      | series tag  | catalog     | Sale catalog | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:skej-zmnx d:2016-09-01T23:53:41.000Z t:catalog.filename=RMNWBrochureSample.pdf t:catalog.file_id=9d6d418e-7bc5-4cce-9879-6e04efddcf0a t:title="Long Hollow" t:map.size=817245 t:county=Gilliam t:catalog.content_type="application/pdf; charset=binary" t:description="T5S R24E Sec 36: Tx Lt 2400" t:map.content_type="application/pdf; charset=binary" t:map.filename="56107-LS 2015 Long Hollow Map.pdf" t:map.file_id=d31acaed-d5f7-498c-9524-1156c4918f0d t:catalog.size=2494319 t:sale="2016 Spring" m:row_number.skej-zmnx=1

series e:skej-zmnx d:2016-09-01T23:55:14.000Z t:catalog.filename=RMNWBrochureSample.pdf t:catalog.file_id=91e864b5-5438-45e7-8caa-effe46ede0a0 t:title="Thirty Mile Creek North" t:map.size=718191 t:county=Gilliam t:catalog.content_type="application/pdf; charset=binary" t:description="T5S R21E Sec 13: Tx Lt 2300" t:map.content_type="application/pdf; charset=binary" t:map.filename="56109-LS 2015 Thirty Mile Creek North Map.pdf" t:map.file_id=d27bda07-90ad-4dea-9942-2a4e4e84bce3 t:catalog.size=2494319 t:sale="2016 Spring" m:row_number.skej-zmnx=2

series e:skej-zmnx d:2016-09-01T23:56:27.000Z t:catalog.filename=RMNWBrochureSample.pdf t:catalog.file_id=355685a0-9aa7-4871-afcf-41485f26e0c5 t:title="Thirty Mile Creek South" t:map.size=718349 t:county=Gilliam t:catalog.content_type="application/pdf; charset=binary" t:description="T5S R21E Sec 13: Tx Lt 2400" t:map.content_type="application/pdf; charset=binary" t:map.filename="56110-LSS 2015 Thirty Mile Creek South Map.pdf" t:map.file_id=c4c09994-5334-4ddd-80fd-996322fab609 t:catalog.size=2494319 t:sale="2016 Spring" m:row_number.skej-zmnx=3
```

## Meta Commands

```ls
metric m:row_number.skej-zmnx p:long l:"Row Number"

entity e:skej-zmnx l:"DSL Land Sales" t:attribution="Department of State Lands" t:url=https://data.oregon.gov/api/views/skej-zmnx

property e:skej-zmnx t:meta.view v:id=skej-zmnx v:category="Natural Resources" v:attributionLink=http://oregon.gov/DSL v:averageRating=0 v:name="DSL Land Sales" v:attribution="Department of State Lands"

property e:skej-zmnx t:meta.view.owner v:id=tpuj-u6fw v:screenName="Katherine LeaMaster" v:displayName="Katherine LeaMaster"

property e:skej-zmnx t:meta.view.tableauthor v:id=tpuj-u6fw v:screenName="Katherine LeaMaster" v:roleName=editor v:displayName="Katherine LeaMaster"
```

## Top Records

```ls
| :updated_at | sale        | title                   | county  | description                  | map                                                                                                                             | catalog                                                                                                  | 
| =========== | =========== | ======================= | ======= | ============================ | =============================================================================================================================== | ======================================================================================================== | 
| 1472774021  | 2016 Spring | Long Hollow             | Gilliam | T5S R24E Sec 36: Tx Lt 2400  | [application/pdf; charset=binary, d31acaed-d5f7-498c-9524-1156c4918f0d, 56107-LS 2015 Long Hollow Map.pdf, 817245]              | [application/pdf; charset=binary, 9d6d418e-7bc5-4cce-9879-6e04efddcf0a, RMNWBrochureSample.pdf, 2494319] | 
| 1472774114  | 2016 Spring | Thirty Mile Creek North | Gilliam | T5S R21E Sec 13: Tx Lt 2300  | [application/pdf; charset=binary, d27bda07-90ad-4dea-9942-2a4e4e84bce3, 56109-LS 2015 Thirty Mile Creek North Map.pdf, 718191]  | [application/pdf; charset=binary, 91e864b5-5438-45e7-8caa-effe46ede0a0, RMNWBrochureSample.pdf, 2494319] | 
| 1472774187  | 2016 Spring | Thirty Mile Creek South | Gilliam | T5S R21E Sec 13: Tx Lt 2400  | [application/pdf; charset=binary, c4c09994-5334-4ddd-80fd-996322fab609, 56110-LSS 2015 Thirty Mile Creek South Map.pdf, 718349] | [application/pdf; charset=binary, 355685a0-9aa7-4871-afcf-41485f26e0c5, RMNWBrochureSample.pdf, 2494319] | 
| 1472774214  | 2016 Spring | Portuguese Canyon       | Grant   | T9S R26E Sec 3: Tx Lt 800    | [application/pdf; charset=binary, d01f761c-ce8c-41eb-a1bd-b6015e22c5f4, 56114-LS 2015 Portuguese Canyon Map.pdf, 857183]        | [application/pdf; charset=binary, f83a6627-b30f-42b4-b6de-ca4ea64ba8c3, RMNWBrochureSample.pdf, 2494319] | 
| 1472774257  | 2016 Spring | Old Mill Canyon         | Wheeler | T8S R21E Sec 16: Tx Lt 1600  | [application/pdf; charset=binary, 6f964de2-af57-42ad-9844-0aacbacf0f99, 56119-LS 2015Old Mill Canyon Map.pdf, 894700]           | [application/pdf; charset=binary, fb86463f-8a6e-4cbf-940d-863b4e0713b3, RMNWBrochureSample.pdf, 2494319] | 
| 1472774287  | 2016 Spring | Fopiano Ranch           | Wheeler | T11S R23E Sec 26: Tx Lt 3300 | [application/pdf; charset=binary, 49b40d69-229a-43e9-8ee9-eab7f702be4d, 56118-LS 2015Fopiano Map.pdf, 913701]                   | [application/pdf; charset=binary, e26fc9ed-d64c-4ccb-aae3-f1b1bcf246d6, RMNWBrochureSample.pdf, 2494319] | 
```