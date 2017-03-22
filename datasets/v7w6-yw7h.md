# Update Clean Fuels Program Rules

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/update-clean-fuels-program-rules) |
| Metadata | [Link](https://data.oregon.gov/api/views/v7w6-yw7h) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/v7w6-yw7h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/v7w6-yw7h/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | v7w6-yw7h |
| Name | Update Clean Fuels Program Rules |
| Created | 2015-09-11T22:24:54Z |
| Publication Date | 2015-09-14T17:37:40Z |
| Rows Updated | 2016-12-11T06:54:39Z |

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email               | Email               | email     | email       |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | comment             | Comment             | html      | html        |
| Yes      | series tag  | additional_document | Additional Document | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:v7w6-yw7h d:2015-10-18T23:37:28.000Z t:first_name=Charlie t:organization="Clean Air Performance Professionals" t:email=cappcharlie@earthlink.net t:state=California t:last_name=Peters t:comment="Voluntary GMO fuel may reduce CO2, ozone &amp; NOx
in 2016.

Monopoly patent mandate may lower BP-DuPont stock value and profit while a move to voluntary may improve employee and customer relationship with improved profit. Win-Win outcome.

MTBE is in our water and a pain to oil profit. Is it time to check California water for fuel ethanol? Time for food &amp; AB32 climate change performance? Time for an AG conversation for consideration of a California fuel ethanol waiver?

UN supports voluntary GMO fuel, a waiver." m:row_number.v7w6-yw7h=1

series e:v7w6-yw7h d:2015-10-19T10:40:28.000Z t:first_name=Ryan t:organization="Clean Energy" t:additional_document.filename="CLNE Support Letter CFP Oct 19 2015.pdf" t:email=ryan.kenny@cleanenergyfuels.com t:additional_document.size=75569 t:additional_document.content_type=application/pdf t:state=California t:last_name=Kenny t:additional_document.file_id=-WYugrQItXdFlPc9Bkp0_p9uZuKq9u1i8oUofL8dqA8 t:comment="Please find attached comments on the Clean Fuels Program from Clean Energy. Thank you." m:row_number.v7w6-yw7h=2

series e:v7w6-yw7h d:2015-10-19T14:50:00.000Z t:first_name=Jan t:organization=DuPont t:additional_document.filename=DuPont_ProposedRegs_CFP_101915.pdf t:email=Jan.Koninckx@dupont.com t:additional_document.size=190399 t:additional_document.content_type=application/pdf t:state=DE t:last_name=Koninckx t:additional_document.file_id=uj7bRtmApA-Z8nvKWHTrZqsGaW6syPn9lA4r2O8dGnY m:row_number.v7w6-yw7h=3
```

## Meta Commands

```ls
metric m:row_number.v7w6-yw7h p:long l:"Row Number"

entity e:v7w6-yw7h l:"Update Clean Fuels Program Rules" t:url=https://data.oregon.gov/api/views/v7w6-yw7h

property e:v7w6-yw7h t:meta.view v:id=v7w6-yw7h v:averageRating=0 v:name="Update Clean Fuels Program Rules"

property e:v7w6-yw7h t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:v7w6-yw7h t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```