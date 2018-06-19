# State Vendor Payments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-vendor-payments) |
| Metadata | [Link](https://data.wa.gov/api/views/sufm-u7rz) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/sufm-u7rz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/sufm-u7rz/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | sufm-u7rz |
| Name | State Vendor Payments |
| Attribution | fiscal.wa.gov |
| Category | Procurements and Contracts |
| Tags | fiscal, spending, expenditures, checkbook |
| Created | 2015-09-28T18:30:46Z |
| Publication Date | 2015-09-29T00:28:08Z |

## Description

This dataset combines multiple extracts from the state's Open Checkbook, provided at fiscal.wa.gov

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | series tag     | biennium     | Biennium     | text          | text          |
| No       |                | fy           | FY           | number        | number        |
| Yes      | numeric metric | fymo         | FYMo         | number        | number        |
| Yes      | time           | monthttl     | MonthTtl     | calendar_date | calendar_date |
| Yes      | series tag     | agycode      | AgyCode      | text          | number        |
| Yes      | series tag     | agyttl       | AgyTtl       | text          | text          |
| Yes      | series tag     | object       | Object       | text          | text          |
| Yes      | series tag     | subobject    | SubObject    | text          | text          |
| Yes      | series tag     | recipient    | Recipient    | text          | text          |
| Yes      | series tag     | objectttl    | ObjectTtl    | text          | text          |
| Yes      | series tag     | subobjectttl | SubObjectTtl | text          | text          |
| Yes      | series tag     | description  | Description  | text          | text          |
| Yes      | numeric metric | amount       | Amount       | number        | number        |
```

## Time Field

```ls
Value = monthttl
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:sufm-u7rz d:2015-05-01T00:00:00.000Z t:objectttl="Personal Service Contracts" t:description="The amounts expended for financial services, actuarial services, economic analysis, cost/benefit analysis, cost allocation, accounting and financial audit services. Also includes investment management, cash management and stockbroker services." t:subobjectttl="Financial Services" t:biennium=2013-15 t:agyttl="Bond Retirement and Interest" t:subobject=CC t:object=C t:agycode=10 t:recipient="MONTAGUE DEROSE & ASSOCIATES LLC" m:amount=22237.93 m:fymo=23

series e:sufm-u7rz d:2015-05-01T00:00:00.000Z t:objectttl="Personal Service Contracts" t:description="The amounts expended for legal services and legal research and consultation by non-state employed attorneys, bond counsel, patent counsel, hearing examiners, etc. Expert witness contracts are for the purpose of providing expert testimony in litigation, but may also include other services such as case consultation, research, and legal services. Does not include services for court reporters, legal aides or lay witnesses, which are classified as purchased services under Subobject ER." t:subobjectttl="Legal/Expert Witness Services" t:biennium=2013-15 t:agyttl="Bond Retirement and Interest" t:subobject=CB t:object=C t:agycode=10 t:recipient="FOSTER PEPPER PLLC" m:amount=83938.15 m:fymo=23

series e:sufm-u7rz d:2015-05-01T00:00:00.000Z t:objectttl="Goods and Services" t:description="The amounts expended for contractual services provided to accomplish routine, continuing and necessary functions not otherwise specifically mentioned or included under the other subobjects within Object E ?Goods and Services,? Object C ?Personal Service Contracts,? Object N ?Grants, Benefits, and Client Services,? or Subobject JK ?Architectural and Engineering Services.? Other contractual services could include, but are not limited to, custodial, interagency, court reporters, lay witnesses, process servers, security, data entry, keypunch, testing and application programming services, offsite data storage, and network monitoring." t:subobjectttl="Other Contractual Services" t:biennium=2013-15 t:agyttl="Bond Retirement and Interest" t:subobject=ER t:object=E t:agycode=10 t:recipient="FITCH INC" m:amount=35000 m:fymo=23
```

## Meta Commands

```ls
metric m:fymo p:integer l:FYMo t:dataTypeName=number

metric m:amount p:long l:Amount t:dataTypeName=number

entity e:sufm-u7rz l:"State Vendor Payments" t:attribution=fiscal.wa.gov t:url=https://data.wa.gov/api/views/sufm-u7rz

property e:sufm-u7rz t:meta.view v:id=sufm-u7rz v:category="Procurements and Contracts" v:attributionLink=http://fiscal.wa.gov/CheckbookExtracts.aspx v:averageRating=0 v:name="State Vendor Payments" v:attribution=fiscal.wa.gov

property e:sufm-u7rz t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:sufm-u7rz t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| biennium | fy   | fymo | monthttl            | agycode | agyttl                       | object | subobject | recipient                        | objectttl                  | subobjectttl                      | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | amount             | 
| ======== | ==== | ==== | =================== | ======= | ============================ | ====== | ========= | ================================ | ========================== | ================================= | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================ | ================== | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 10      | Bond Retirement and Interest | C      | CC        | MONTAGUE DEROSE & ASSOCIATES LLC | Personal Service Contracts | Financial Services                | The amounts expended for financial services, actuarial services, economic analysis, cost/benefit analysis, cost allocation, accounting and financial audit services. Also includes investment management, cash management and stockbroker services.                                                                                                                                                                                                                                                                                                                                                                                                          | 22237.93           | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 10      | Bond Retirement and Interest | C      | CB        | FOSTER PEPPER PLLC               | Personal Service Contracts | Legal/Expert Witness Services     | The amounts expended for legal services and legal research and consultation by non-state employed attorneys, bond counsel, patent counsel, hearing examiners, etc. Expert witness contracts are for the purpose of providing expert testimony in litigation, but may also include other services such as case consultation, research, and legal services. Does not include services for court reporters, legal aides or lay witnesses, which are classified as purchased services under Subobject ER.                                                                                                                                                        | 83938.15           | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 10      | Bond Retirement and Interest | E      | ER        | FITCH INC                        | Goods and Services         | Other Contractual Services        | The amounts expended for contractual services provided to accomplish routine, continuing and necessary functions not otherwise specifically mentioned or included under the other subobjects within Object E ?Goods and Services,? Object C ?Personal Service Contracts,? Object N ?Grants, Benefits, and Client Services,? or Subobject JK ?Architectural and Engineering Services.? Other contractual services could include, but are not limited to, custodial, interagency, court reporters, lay witnesses, process servers, security, data entry, keypunch, testing and application programming services, offsite data storage, and network monitoring. | 35000              | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 10      | Bond Retirement and Interest | E      | ER        | MOODYS INVESTORS SERVICE         | Goods and Services         | Other Contractual Services        | The amounts expended for contractual services provided to accomplish routine, continuing and necessary functions not otherwise specifically mentioned or included under the other subobjects within Object E ?Goods and Services,? Object C ?Personal Service Contracts,? Object N ?Grants, Benefits, and Client Services,? or Subobject JK ?Architectural and Engineering Services.? Other contractual services could include, but are not limited to, custodial, interagency, court reporters, lay witnesses, process servers, security, data entry, keypunch, testing and application programming services, offsite data storage, and network monitoring. | 68560.990000000005 | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 10      | Bond Retirement and Interest | E      | EZ        | FEDERAL EXPRESS                  | Goods and Services         | Other Goods and Services          | The amounts expended for goods and services other than those described above. Includes such items as bonds, freight (when not allocable to items purchased), advertising, and other goods and services from vendors or other agencies.                                                                                                                                                                                                                                                                                                                                                                                                                       | 14.62              | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 10      | Bond Retirement and Interest | E      | EZ        | INTERCALL INC                    | Goods and Services         | Other Goods and Services          | The amounts expended for goods and services other than those described above. Includes such items as bonds, freight (when not allocable to items purchased), advertising, and other goods and services from vendors or other agencies.                                                                                                                                                                                                                                                                                                                                                                                                                       | 9.64               | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 10      | Bond Retirement and Interest | E      | EF        | DES PRINTING & IMAGING SERVICES  | Goods and Services         | Printing and Reproduction         | The amounts expended for contractual printing and reproduction, binding operations, and all common processes of duplication performed by the Department of Enteprise Services' Printing and Imaging or commercial printers. Includes printed matter such as publications, books, pamphlets, digital and scanned images, and the cost of office copier supplies.                                                                                                                                                                                                                                                                                              | 97.27              | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 10      | Bond Retirement and Interest | E      | EY        | SS&C TECHNOLOGIES INC            | Goods and Services         | Software Licenses and Maintenance | Amounts expended for purchased software or licenses of commercially available software with a useful life of one year or less, including upgrades and/or maintenance agreements. Software licensing includes, but is not limited to, the right to use the software, support for the software, and upgrades.Note: Prior to July 1, 2009, software repairs and maintenance were coded to Subobject EE and software rentals and leases were coded to Subobject EH.                                                                                                                                                                                              | 11315.2            | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 11      | House of Representatives     | E      | EB        | CAMPAIGN MARKETING STRATEGIES    | Goods and Services         | Communications                    | The amounts expended for transmission of voice and data messages. This category includes: contractual charges for land telegraph service, radio and wireless telegraph services, telephone, including wireless service, teletype, and facsimile services; letter postage; rental of post office boxes or postage meter machines and/or mailing machines; contractual messenger service; switchboard service charges; telephone installation costs; and internet access charges. Also includes amounts expended for videoconferencing and data communication, such as data line costs, modems, routers, gateways, Internet and other bundled service costs.   | 4250               | 
| 2013-15  | 2015 | 23   | 2015-05-01T00:00:00 | 11      | House of Representatives     | G      | GA        | CLIBBORN, JUDY                   | Travel                     | In-State Subsistence & Lodging    | The amounts paid for lodging and/or subsistence expenses incurred while traveling within the state's boundary on official state business, including lodging taxes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 720                | 
```