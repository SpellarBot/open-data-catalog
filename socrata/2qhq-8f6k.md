# Office of Hearings and Mediation Services (OHMS) Docket Management System: Beginning 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-of-hearings-and-mediation-services-ohms-docket-management-system-beginning-2005) |
| Metadata | [Link](https://data.ny.gov/api/views/2qhq-8f6k) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2qhq-8f6k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2qhq-8f6k/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2qhq-8f6k |
| Name | Office of Hearings and Mediation Services (OHMS) Docket Management System: Beginning 2005 |
| Attribution | Office of Hearings and Mediation Services (OHMS), NYS DEC |
| Category | Energy & Environment |
| Tags | hearings, decision, cases, docket, status |
| Created | 2015-02-19T16:26:21Z |
| Publication Date | 2017-04-01T10:12:24Z |

## Description

The docket management system is a database of cases that have been referred to OHMS for public hearings or other action by an administrative law judge and a decision by the Commissioner of the New York State Department of Environmental Conservation. The docket contains cases that were open on or after January 1, 2005.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | case_ohms_number | Case OHMS Number | text      | text        |
| Yes      | series tag  | case_name        | Case Name        | text      | text        |
| Yes      | series tag  | alj_last_name    | ALJ Last Name    | text      | text        |
| Yes      | series tag  | case_type_name   | Case Type Name   | text      | text        |
| Yes      | series tag  | status_type_name | Status Type Name | text      | text        |
| Yes      | series tag  | case_text_update | Case Text Update | text      | text        |
| Yes      | series tag  | case_towncity    | Case Town City   | text      | text        |
| Yes      | series tag  | county           | County           | text      | text        |
| Yes      | series tag  | decision         | Decision         | url       | url         |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2qhq-8f6k d:2005-01-01T00:00:00.000Z t:case_ohms_number=201570332 t:status_type_name="Decision Issued" t:county="NEW YORK" t:case_name="10 East 85th Street, Inc." t:case_towncity="MANHATTAN (ENTIRE)" t:decision=http://www.dec.ny.gov/docs/legal_protection_pdf/10easto.pdf t:case_text_update="Petroleum bulk storage (PBS) facility enforcement.  Alleged failure to comply with a consent order for a residential PBS facility located in Manhattan, New York County.  Department staff filed a motion for order without hearing in lieu of complaint.  Respondent has not answered. Commissioner Order 2/22/16. [http://www.dec.ny.gov/docs/legal_protection_pdf/10easto.pdf]" t:alj_last_name=Bassinson t:case_type_name=Enforcement m:row_number.2qhq-8f6k=1

series e:2qhq-8f6k d:2005-01-01T00:00:00.000Z t:case_ohms_number=201670966 t:status_type_name="Decision Issued" t:county=BRONX t:case_name="1001 Jerome Associates" t:case_towncity="BRONX (ENTIRE)" t:decision=http://www.dec.ny.gov/docs/legal_protection_pdf/1001jeromeassociateso.pdf t:case_text_update="Expedited PBS registration proceeding.  Alleged failure to register a residential PBS facility located in the Bronx, Bronx County.  Respondent failed to appear at 4/26/16 calendar call.  Hearing re-noticed for 7/21/16 in Central Office.  Commissioner Order issued 1/20/17. [http://www.dec.ny.gov/docs/legal_protection_pdf/1001jeromeassociateso.pdf]" t:alj_last_name=Caruso t:case_type_name=Enforcement m:row_number.2qhq-8f6k=2

series e:2qhq-8f6k d:2005-01-01T00:00:00.000Z t:case_ohms_number=201469407 t:status_type_name="Decision Issued" t:county="NEW YORK" t:case_name="101-09 West 115th Street Housing Development Fund Corporation" t:case_towncity="MANHATTAN (ENTIRE)" t:decision=http://www.dec.ny.gov/docs/legal_protection_pdf/10109westo.pdf t:case_text_update="PBS registration enforcement.  Alleged failure to renew registration for a residential PBS facility located in Manhattan, New York County.  Hearing held 8/4/14. Commissioner Order 10/14/14.  [http://www.dec.ny.gov/docs/legal_protection_pdf/10109westo.pdf]" t:alj_last_name=Bassinson t:case_type_name=Enforcement m:row_number.2qhq-8f6k=3
```

## Meta Commands

```ls
metric m:row_number.2qhq-8f6k p:long l:"Row Number"

entity e:2qhq-8f6k l:"Office of Hearings and Mediation Services (OHMS) Docket Management System: Beginning 2005" t:attribution="Office of Hearings and Mediation Services (OHMS), NYS DEC" t:url=https://data.ny.gov/api/views/2qhq-8f6k

property e:2qhq-8f6k t:meta.view v:id=2qhq-8f6k v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/cfmx/extapps/docket/ v:averageRating=0 v:name="Office of Hearings and Mediation Services (OHMS) Docket Management System: Beginning 2005" v:attribution="Office of Hearings and Mediation Services (OHMS), NYS DEC"

property e:2qhq-8f6k t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2qhq-8f6k t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| case_ohms_number | case_name                                                                                   | alj_last_name | case_type_name          | status_type_name | case_text_update                                                                                                                                                                                                                                                                                                                                                                                                                                                                | case_towncity      | county   | decision                                                                          | 
| ================ | =========================================================================================== | ============= | ======================= | ================ | =============================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ================== | ======== | ================================================================================= | 
| 201570332        | 10 East 85th Street, Inc.                                                                   | Bassinson     | Enforcement             | Decision Issued  | Petroleum bulk storage (PBS) facility enforcement. Alleged failure to comply with a consent order for a residential PBS facility located in Manhattan, New York County. Department staff filed a motion for order without hearing in lieu of complaint. Respondent has not answered. Commissioner Order 2/22/16. [http://www.dec.ny.gov/docs/legal_protection_pdf/10easto.pdf]                                                                                                  | MANHATTAN (ENTIRE) | NEW YORK | [http://www.dec.ny.gov/docs/legal_protection_pdf/10easto.pdf, null]               | 
| 201670966        | 1001 Jerome Associates                                                                      | Caruso        | Enforcement             | Decision Issued  | Expedited PBS registration proceeding. Alleged failure to register a residential PBS facility located in the Bronx, Bronx County. Respondent failed to appear at 4/26/16 calendar call. Hearing re-noticed for 7/21/16 in Central Office. Commissioner Order issued 1/20/17. [http://www.dec.ny.gov/docs/legal_protection_pdf/1001jeromeassociateso.pdf]                                                                                                                        | BRONX (ENTIRE)     | BRONX    | [http://www.dec.ny.gov/docs/legal_protection_pdf/1001jeromeassociateso.pdf, null] | 
| 201469407        | 101-09 West 115th Street Housing Development Fund Corporation                               | Bassinson     | Enforcement             | Decision Issued  | PBS registration enforcement. Alleged failure to renew registration for a residential PBS facility located in Manhattan, New York County. Hearing held 8/4/14. Commissioner Order 10/14/14. [http://www.dec.ny.gov/docs/legal_protection_pdf/10109westo.pdf]                                                                                                                                                                                                                    | MANHATTAN (ENTIRE) | NEW YORK | [http://www.dec.ny.gov/docs/legal_protection_pdf/10109westo.pdf, null]            | 
| 200561192        | 102 Elmont Realty Corp. (Nejdet Yetim)                                                      | DuBois        | Enforcement             | Settled          | Alleged violation of petroleum bulk storage facility regulations for a facility in Elmont, New York. DEC Staff filed statement of readiness for adjudicatory hearing. Settled by consent order 6/9/06.                                                                                                                                                                                                                                                                          | BABYLON            | SUFFOLK  | [null, null]                                                                      | 
| 200964225        | 102 Elmont Realty Corporation, Elmont Gasoline Co., Inc., and Nedjet Yetim (River Gas Inc.) | Villa         | Summary Abatement Order | Decision Issued  | Alleged imminent threat to the environment at a PBS facility located in Elmont, Nassau County. DEC staff issued a summary abatement order. Hearing scheduled for 3/13/09. DEC staff also moves for an order without hearing against these and additional respondents. Commissioner order continuing summary abatement order issued 3/26/09. Commissioner order on motion for order without hearing issued 4/6/09. [http://www.dec.ny.gov/docs/legal_protection_pdf/elmonto.pdf] | HEMPSTEAD          | NASSAU   | [http://www.dec.ny.gov/docs/legal_protection_pdf/elmonto.pdf, null]               | 
| 201570048        | 1033 Cauldwell Ave. Housing Develop. Fund Corp.                                             | McBride       | Enforcement             | Decision Issued  | PBS registration enforcement. Respondent allegedly failed to re-register residential PBS facility located in the Bronx, Bronx County. Expedited hearing held 5/12/15. Commissioner Order issued 8/21/15. [http://www.dec.ny.gov/docs/legal_protection_pdf/1033cauldwello.pdf]                                                                                                                                                                                                   | BRONX (ENTIRE)     | BRONX    | [http://www.dec.ny.gov/docs/legal_protection_pdf/1033cauldwello.pdf, null]        | 
| 2005J380         | 110 Cleaners                                                                                | DuBois        | Enforcement             | Settled          | The above case was settled under a consent order executed on March 31, 2000.                                                                                                                                                                                                                                                                                                                                                                                                    |                    |          | [null, null]                                                                      | 
| 201570278        | 1113-17 Grant Avenue HDFC                                                                   | Bassinson     | Enforcement             | Decision Issued  | PBS registration enforcement. Alleged failure to renew PBS registration for a facility located in the Bronx, Bronx County. Hearing held 8/4/15. Acting Commissioner Order 9/8/15 [http://www.dec.ny.gov/docs/legal_protection_pdf/1113.17granto.pdf]                                                                                                                                                                                                                            | BRONX (ENTIRE)     | BRONX    | [http://www.dec.ny.gov/docs/legal_protection_pdf/1113.17granto.pdf, null]         | 
| 201166921        | 12 Martense Associates LLC                                                                  | Wissler       | Enforcement             | Decision Issued  | Alleged failure to register PBS facility located in Brooklyn, Kings County. No appearance at adjudicatory hearing held 8/30/11. DEC staff moves for a default judgment. Commissioner Order issued 12/19/11. [http://www.dec.ny.gov/docs/legal_protection_pdf/12martenseo.pdf]                                                                                                                                                                                                   | BROOKLYN (ENTIRE)  | KINGS    | [http://www.dec.ny.gov/docs/legal_protection_pdf/12martenseo.pdf, null]           | 
| 200661755        | 125 Broadway LLC and Michael O'Brien                                                        | DuBois        | Enforcement             | Decision Issued  | Status: Alleged violations of a consent order governing a PBS facility. DEC staff motion for default judgment. Decision and Order issued 12/15/06. [http://www.dec.ny.gov/docs/legal_protection_pdf/125broadwaydo.pdf]                                                                                                                                                                                                                                                          | ALBANY             | ALBANY   | [http://www.dec.ny.gov/docs/legal_protection_pdf/125broadwaydo.pdf, null]         | 
```