# FCC wireline broadband service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fcc-wireline-broadband-service) |
| Metadata | [Link](https://data.wa.gov/api/views/uyg8-hybx) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/uyg8-hybx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/uyg8-hybx/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | uyg8-hybx |
| Name | FCC wireline broadband service |
| Attribution | FCC |
| Category | Economics |
| Tags | broadband |
| Created | 2016-06-29T13:12:54Z |
| Publication Date | 2017-03-28T18:35:50Z |

## Description

Form 477 wireline service data from FCC. Providers file lists of census blocks in which they can or do offer service to at least one location, with additional information about the service.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| No       | time           | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | numeric metric | logrecno           | LogRecNo           | number    | number      |
| Yes      | series tag     | provider_id        | Provider_Id        | text      | text        |
| Yes      | numeric metric | frn                | FRN                | number    | number      |
| Yes      | series tag     | providername       | ProviderName       | text      | text        |
| Yes      | series tag     | dbaname            | DBAName            | text      | text        |
| Yes      | series tag     | holdingcompanyname | HoldingCompanyName | text      | text        |
| Yes      | numeric metric | hoconum            | HocoNum            | number    | number      |
| Yes      | series tag     | hocofinal          | HocoFinal          | text      | text        |
| Yes      | series tag     | blockcode          | BlockCode          | text      | number      |
| Yes      | series tag     | techcode           | TechCode           | text      | number      |
| Yes      | numeric metric | consumer           | Consumer           | number    | number      |
| Yes      | numeric metric | maxaddown          | MaxAdDown          | number    | number      |
| Yes      | numeric metric | maxadup            | MaxAdUp            | number    | number      |
| Yes      | numeric metric | business           | Business           | number    | number      |
| Yes      | numeric metric | maxcirdown         | MaxCIRDown         | number    | number      |
| Yes      | numeric metric | maxcirup           | MaxCIRUp           | number    | number      |
| Yes      | series tag     | stateabbr          | StateAbbr          | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uyg8-hybx d:2017-03-28T18:04:54.000Z t:blockcode=530330006004024 t:holdingcompanyname="Towerstream, Inc." t:stateabbr=WA t:providername="TOWERSTREAM, INC." t:provider_id=20799 t:hocofinal="Towerstream, Inc." t:dbaname=Towerstream t:techcode=70 m:logrecno=48530 m:maxaddown=0 m:frn=7097355 m:maxadup=0 m:maxcirdown=1000 m:hoconum=190373 m:consumer=0 m:business=1 m:maxcirup=1000

series e:uyg8-hybx d:2017-03-28T18:04:54.000Z t:blockcode=530330108001008 t:holdingcompanyname="Towerstream, Inc." t:stateabbr=WA t:providername="TOWERSTREAM, INC." t:provider_id=20799 t:hocofinal="Towerstream, Inc." t:dbaname=Towerstream t:techcode=70 m:logrecno=48534 m:maxaddown=0 m:frn=7097355 m:maxadup=0 m:maxcirdown=1000 m:hoconum=190373 m:consumer=0 m:business=1 m:maxcirup=1000

series e:uyg8-hybx d:2017-03-28T18:04:54.000Z t:blockcode=530330058023036 t:holdingcompanyname="Towerstream, Inc." t:stateabbr=WA t:providername="TOWERSTREAM, INC." t:provider_id=20799 t:hocofinal="Towerstream, Inc." t:dbaname=Towerstream t:techcode=70 m:logrecno=48566 m:maxaddown=0 m:frn=7097355 m:maxadup=0 m:maxcirdown=1000 m:hoconum=190373 m:consumer=0 m:business=1 m:maxcirup=1000
```

## Meta Commands

```ls
metric m:logrecno p:integer l:LogRecNo t:dataTypeName=number

metric m:frn p:integer l:FRN t:dataTypeName=number

metric m:hoconum p:integer l:HocoNum t:dataTypeName=number

metric m:consumer p:integer l:Consumer t:dataTypeName=number

metric m:maxaddown p:double l:MaxAdDown t:dataTypeName=number

metric m:maxadup p:double l:MaxAdUp t:dataTypeName=number

metric m:business p:integer l:Business t:dataTypeName=number

metric m:maxcirdown p:double l:MaxCIRDown t:dataTypeName=number

metric m:maxcirup p:double l:MaxCIRUp t:dataTypeName=number

entity e:uyg8-hybx l:"FCC wireline broadband service" t:attribution=FCC t:url=https://data.wa.gov/api/views/uyg8-hybx

property e:uyg8-hybx t:meta.view v:id=uyg8-hybx v:category=Economics v:attributionLink=https://www.fcc.gov/general/broadband-deployment-data-fcc-form-477 v:averageRating=0 v:name="FCC wireline broadband service" v:attribution=FCC

property e:uyg8-hybx t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:uyg8-hybx t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | logrecno | provider_id | frn     | providername      | dbaname     | holdingcompanyname | hoconum | hocofinal         | blockcode       | techcode | consumer | maxaddown | maxadup | business | maxcirdown | maxcirup | stateabbr | 
| =========== | ======== | =========== | ======= | ================= | =========== | ================== | ======= | ================= | =============== | ======== | ======== | ========= | ======= | ======== | ========== | ======== | ========= | 
| 1490724294  | 48530    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330006004024 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
| 1490724294  | 48534    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330108001008 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
| 1490724294  | 48566    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330058023036 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
| 1490724294  | 48686    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330227012007 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
| 1490724294  | 48801    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330099004007 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
| 1490724294  | 48813    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330248003006 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
| 1490724294  | 48839    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330093003140 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
| 1490724294  | 48868    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330079003005 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
| 1490724294  | 48947    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330090002019 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
| 1490724294  | 48981    | 20799       | 7097355 | TOWERSTREAM, INC. | Towerstream | Towerstream, Inc.  | 190373  | Towerstream, Inc. | 530330249013005 | 70       | 0        | 0         | 0       | 1        | 1000       | 1000     | WA        | 
```