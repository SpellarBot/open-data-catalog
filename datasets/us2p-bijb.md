# Minority and Women's Business Enterprises Certifications - MBE/WBE

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/minority-and-womens-business-enterprises-certifications-mbe-wbe-3cf96) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/us2p-bijb) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/us2p-bijb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/us2p-bijb/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | us2p-bijb |
| Name | Minority and Women's Business Enterprises Certifications - MBE/WBE |
| Attribution | Law / Minority and Women's Business Opportunity Office |
| Category | City Services |
| Tags | minority, contracts, mwboo, mbe, wbe, businesses, women |
| Created | 2012-02-02T20:22:25Z |
| Publication Date | 2014-04-03T23:29:15Z |

## Description

It is the policy of the City of Baltimore to promote equal business opportunity in the City's contracting process by encouraging full and equitable participation by minority and women's business enterprises in the provision of goods and services to the City on a contractual basis.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | certno             | certNo             | text      | text        |
| Yes      | series tag  | company            | company            | text      | text        |
| Yes      | series tag  | county             | county             | text      | text        |
| Yes      | series tag  | zipcode            | zipCode            | text      | text        |
| Yes      | series tag  | title              | title              | text      | text        |
| Yes      | series tag  | firstname          | firstName          | text      | text        |
| Yes      | series tag  | lastname           | lastName           | text      | text        |
| Yes      | series tag  | position           | position           | text      | text        |
| Yes      | series tag  | phone              | phone              | text      | text        |
| Yes      | series tag  | avgcontractsize    | avgContractSize    | text      | text        |
| Yes      | series tag  | race               | race               | text      | text        |
| Yes      | series tag  | contracttype       | contractType       | text      | text        |
| Yes      | series tag  | contractstatus     | contractStatus     | text      | text        |
| Yes      | time        | origcert           | origCert           | date      | date        |
| No       |             | certdate           | certDate           | date      | date        |
| No       |             | expirationdate     | expirationDate     | date      | date        |
| No       |             | extensiondate      | extensionDate      | date      | date        |
| Yes      | series tag  | fax                | fax                | text      | text        |
| Yes      | series tag  | email              | email              | email     | email       |
| Yes      | series tag  | website            | website            | url       | url         |
| Yes      | series tag  | cetegory           | category           | text      | text        |
| Yes      | series tag  | description        | description        | text      | text        |
| Yes      | series tag  | servicedescription | serviceDescription | text      | text        |
| Yes      | series tag  | code               | code               | text      | text        |
```

## Time Field

```ls
Value = origcert
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = certdate,expirationdate,extensiondate
```

## Data Commands

```ls
series e:us2p-bijb d:2010-11-22T08:00:00.000Z t:position=Owner t:cetegory=CONSTRUCTION t:phone=(443)600-2597 t:fax=(410)889-0630 t:servicedescription="CARPENTRY, CONCRETE, DRYWALL, PAINTING, FLOORING, DEMOLITION" t:zipcode=21218- t:lastname=Minor t:firstname=Everett t:code=1002 t:certno=10-358026 t:race="African American" t:title=Mr. t:contracttype=MBE t:county="Baltimore City" t:email=poominor2@verizon.net t:contractstatus=CERTIFY t:description=CARPENTRY t:company="Minor Enterprises" t:avgcontractsize=<$25K m:row_number.us2p-bijb=1

series e:us2p-bijb d:2008-03-12T07:00:00.000Z t:position=Owner t:cetegory=CONSTRUCTION t:phone=(410)828-0545 t:fax=(443)499-0055 t:servicedescription="LAND DEVELOPMENT, CARPENTRY" t:zipcode=21204- t:lastname=Tidar t:firstname="Yank P." t:code=1002 t:certno=08-005005 t:race="Asian American" t:title=Mr. t:contracttype=MBE t:county="Baltimore County" t:email=sivani96@yahoo.com t:contractstatus=CERTIFY t:description=CARPENTRY t:company="Shivani Investment Co., Llc" t:avgcontractsize=<$25K m:row_number.us2p-bijb=2

series e:us2p-bijb d:2011-06-22T07:00:00.000Z t:position=President t:cetegory=CONSTRUCTION t:phone=(443)324-4639 t:fax=()- t:servicedescription=DEMOLITION t:zipcode=21212- t:lastname=Phillips t:firstname=James t:code=1004 t:certno=11-358129 t:race="African American" t:title=Mr. t:contracttype=MBE t:county="Baltimore City" t:email=Jptycus@gmail.com t:contractstatus=CERTIFY t:description=DEMOLITION t:company="J Phillips And Tycus, Llc" t:avgcontractsize=<$25K m:row_number.us2p-bijb=3
```

## Meta Commands

```ls
metric m:row_number.us2p-bijb p:long l:"Row Number"

entity e:us2p-bijb l:"Minority and Women's Business Enterprises Certifications - MBE/WBE" t:attribution="Law / Minority and Women's Business Opportunity Office" t:url=https://data.baltimorecity.gov/api/views/us2p-bijb

property e:us2p-bijb t:meta.view v:id=us2p-bijb v:category="City Services" v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Law/MinorityandWomensBusinessOpportunityOffice.aspx v:averageRating=0 v:name="Minority and Women's Business Enterprises Certifications - MBE/WBE" v:attribution="Law / Minority and Women's Business Opportunity Office"

property e:us2p-bijb t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:us2p-bijb t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:us2p-bijb t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| certno    | company                                       | county           | zipcode | title | firstname  | lastname      | position  | phone         | avgcontractsize | race             | contracttype | contractstatus | origcert   | certdate   | expirationdate | extensiondate | fax           | email                     | website      | cetegory      | description                                             | servicedescription                                           | code   | 
| ========= | ============================================= | ================ | ======= | ===== | ========== | ============= | ========= | ============= | =============== | ================ | ============ | ============== | ========== | ========== | ============== | ============= | ============= | ========================= | ============ | ============= | ======================================================= | ============================================================ | ====== | 
| 10-358026 | Minor Enterprises                             | Baltimore City   | 21218-  | Mr.   | Everett    | Minor         | Owner     | (443)600-2597 | <$25K           | African American | MBE          | CERTIFY        | 1290412800 | 1290457980 | 1353484800     |               | (410)889-0630 | poominor2@verizon.net     | [null, null] | CONSTRUCTION  | CARPENTRY                                               | CARPENTRY, CONCRETE, DRYWALL, PAINTING, FLOORING, DEMOLITION | 1002   | 
| 08-005005 | Shivani Investment Co., Llc                   | Baltimore County | 21204-  | Mr.   | Yank P.    | Tidar         | Owner     | (410)828-0545 | <$25K           | Asian American   | MBE          | CERTIFY        | 1205305200 | 1301986800 | 1365058800     |               | (443)499-0055 | sivani96@yahoo.com        | [null, null] | CONSTRUCTION  | CARPENTRY                                               | LAND DEVELOPMENT, CARPENTRY                                  | 1002   | 
| 11-358129 | J Phillips And Tycus, Llc                     | Baltimore City   | 21212-  | Mr.   | James      | Phillips      | President | (443)324-4639 | <$25K           | African American | MBE          | CERTIFY        | 1308726000 | 1308766500 | 1371798000     |               | ()-           | Jptycus@gmail.com         | [null, null] | CONSTRUCTION  | DEMOLITION                                              | DEMOLITION                                                   | 1004   | 
| 08-005234 | Ironshore Contracting, Llc                    | Anne Arundel     | 21090-  | Mr.   | Gregory    | Malcolm       | President | (443)552-5732 | <$25K           | African American | MBE          | CERTIFY        | 1228896000 | 1298534400 | 1361606400     |               | (443)552-7136 | gmalcolm@ironshoregrp.com | [null, null] | CONSTRUCTION  | ORNAM, METAL FAB, FENCEWK, GUARDRL, SHEET METAL, PILING | ROOFING, WATERPROOFING, SHEET METAL , SKYLIGHT               | 1010   | 
| 10-357984 | B R C Construction, Llc                       | Baltimore County | 21208-  | Mr.   | Anthony M. | Hill          | President | (410)599-6229 | <$25K           | African American | MBE          | CERTIFY        | 1283842800 | 1283898720 | 1346914800     |               | (410)484-4340 | ahill2716@gmail.com       | [null, null] | CONSTRUCTION  | WINDOW INSTALLATION AND REPLACEMENT, GLASS AND GLAZING  | CARPENTRY, DRYWALL, PAINTING, WINDOWS, SPECIALTY CARPENTRY   | 1015   | 
| 89-000741 | P & S Painting Company, Inc.                  | Baltimore County | 21162-  | Ms.   | Genevieve  | Stakias       | President | (410)256-7516 | $100K-$250K     | White            | WBE          | CERTIFY        | 612687600  | 1308639600 | 1371711600     |               | (410)256-7555 | gennystakias@comcast.net  | [null, null] | CONSTRUCTION  | SANDBLAST, EXTER RESTORATION, CLEANING AND MAINTENANCE  | PAINTING, SANDBLASTING                                       | 1018   | 
| 05-004635 | First Potomac Environmental Corporation, Inc. | Baltimore City   | 21231-  | Mr.   | Joe        | Chimah        | President | (443)220-6416 | <$25K           | African American | MBE          | CERTIFY        | 1134460800 | 1301986800 | 1365058800     |               | (410)823-6676 | jchimah@fpecinc1.com      | [null, null] | CONSTRUCTION  | LEAD PAINT ABATEMENT                                    | ASBESTOS AND LEAD ABATEMENT, CONSTRUCTION MANAGEMENT         | 1029   | 
| 11-358114 | Superior Designs                              | Baltimore County | 21244-  | Mr.   | Nathaniel  | Holland       | Owner     | (888)783-3903 | <$25K           | African American | MBE          | CERTIFY        | 1303974000 | 1304011020 | 1367046000     |               | (410)944-7464 | snprinting@msn.com        | [null, null] | PROF SERVICES | GRAPHIC DESIGN                                          | PRINTING AND GRAPHIC DESIGN SERVICES                         | 04002A | 
| 11-358153 | Paradigm Solutions, Llc                       | Baltimore County | 21239-  | Mr.   | Floyd      | Taliaferro Iv | President | (410)984-9978 | <$25K           | African American | MBE          | CERTIFY        | 1313478000 | 1313518140 | 1376550000     |               | ()-           | ftaliaferro@gmail.com     | [null, null] | PROF SERVICES | LECTURES, SEMINARS AND WORKSHOPS                        | EDUCATIONAL AND CURRICULUM CONSULTANT                        | 04005G | 
| 89-001566 | Alvi Associates, Inc.                         | Baltimore County | 21204-  | Mr.   | Irfan A.   | Alvi          | President | (410)321-8877 | $100K-$250K     | Asian American   | MBE          | CERTIFY        | 607420800  | 1308034800 | 1371106800     |               | (410)321-8970 | ialvi@alviassociates.com  | [null, null] | PROF SERVICES | STRUCTURAL                                              | CIVIL AND STRUCTURAL ENGINEERING                             | 04007G | 
```