# Health and Human Services Prequalification Catalog

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-and-human-services-prequalification-catalog-b04f0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/68rr-d3jr) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/68rr-d3jr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/68rr-d3jr/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 68rr-d3jr |
| Name | Health and Human Services Prequalification Catalog |
| Attribution | HHS Accelerator |
| Category | Social Services |
| Tags | procurement, rfp, request for proposal, accelerator, hhs, health, human service, social service, client service, community service, catalog, definition |
| Created | 2014-11-26T21:32:03Z |
| Publication Date | 2014-11-26T21:34:34Z |

## Description

The services and definitions used by HHS Accelerator, the City's system for procuring health and human services, to prequalify providers and describe services procured through RFPs.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| No       | time        | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag  | service_area        | Service Area        | text      | text        |
| Yes      | series tag  | service_description | Service Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:68rr-d3jr d:2014-11-26T13:32:11.000Z t:service_area="Academic Supports" t:service_description="Academic Supports consist of education and enrichment to promote academic performance and advancement. Examples include Academic Counseling, Academic Engagement, Continuing Education/Lifelong Learning, Educational Neglect Prevention, Homework Help, Post-Secondary/College Awareness, Project Based Learning, Truancy Prevention and Tutoring." m:row_number.68rr-d3jr=1

series e:68rr-d3jr d:2014-11-26T13:32:11.000Z t:service_area="Adoption Services" t:service_description="Adoption Services consist of services to provide information, counseling, and support to birth parents, children, youth, and prospective adoptive parents to facilitate permanent caring relationships for children within families. Adoption services also provide support to birth parents, adopted individuals, and adoptive parents after an adoption has been finalized. Examples include Family Finding and Post Adoption Support." m:row_number.68rr-d3jr=2

series e:68rr-d3jr d:2014-11-26T13:32:11.000Z t:service_area="Alternative Justice Management" t:service_description="Alternative Justice Management consists of services to provide alternatives to incarceration for individuals involved in the adult or juvenile justice system. Alternative Justice Management may include the formal supervision of offenders released conditionally on probation or parole or confined to their homes or other venues in the community. Services may also provide the option of participating in counseling, educational or work programs as an alternative to incarceration in a correctional facility, payment of a fine or other sanctions. Examples include Community Service Management, Parole Management, Probation Management, Alternative Placement, and Alternatives to Incarceration." m:row_number.68rr-d3jr=3
```

## Meta Commands

```ls
metric m:row_number.68rr-d3jr p:long l:"Row Number"

entity e:68rr-d3jr l:"Health and Human Services Prequalification Catalog" t:attribution="HHS Accelerator" t:url=https://data.cityofnewyork.us/api/views/68rr-d3jr

property e:68rr-d3jr t:meta.view v:id=68rr-d3jr v:category="Social Services" v:averageRating=0 v:name="Health and Human Services Prequalification Catalog" v:attribution="HHS Accelerator"

property e:68rr-d3jr t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:68rr-d3jr t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | service_area                      | service_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 
| =========== | ================================= | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1417008731  | Academic Supports                 | Academic Supports consist of education and enrichment to promote academic performance and advancement. Examples include Academic Counseling, Academic Engagement, Continuing Education/Lifelong Learning, Educational Neglect Prevention, Homework Help, Post-Secondary/College Awareness, Project Based Learning, Truancy Prevention and Tutoring.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 
| 1417008731  | Adoption Services                 | Adoption Services consist of services to provide information, counseling, and support to birth parents, children, youth, and prospective adoptive parents to facilitate permanent caring relationships for children within families. Adoption services also provide support to birth parents, adopted individuals, and adoptive parents after an adoption has been finalized. Examples include Family Finding and Post Adoption Support.                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| 1417008731  | Alternative Justice Management    | Alternative Justice Management consists of services to provide alternatives to incarceration for individuals involved in the adult or juvenile justice system. Alternative Justice Management may include the formal supervision of offenders released conditionally on probation or parole or confined to their homes or other venues in the community. Services may also provide the option of participating in counseling, educational or work programs as an alternative to incarceration in a correctional facility, payment of a fine or other sanctions. Examples include Community Service Management, Parole Management, Probation Management, Alternative Placement, and Alternatives to Incarceration.                                                                                                                                                                                        | 
| 1417008731  | Caregiver Support                 | Caregiver Support Services consist of supportive counseling and assistance provided to help individuals who care for a family member or loved one who has physical, mental, or developmental issues. Examples include Caregiver Support Group and Caregiver Counseling.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 1417008731  | Case Management                   | Case Management consists of services to help persons and families achieve or maintain optimum social, psychological, and physical functioning by planning, securing, coordinating, and monitoring services from different organizations and personnel on behalf of those served. Case Management may include services to establish and maintain client engagement in needed services. Services may also include client team communications to facilitate the exchange of information between two or more parties in relation to the status of or service delivery to a client. Examples include Advocacy (Community and Individual), Aftercare, Case Assistance, Case Conferencing, Client Evaluation/Assessment, Client Monitoring, Client Referrals, Counseling, Crisis Intervention/Management, Diversion Services, Intake, Safety Planning, Service/Care Planning and Transition/Discharge Planning. | 
| 1417008731  | Child Care                        | Child Care consists of services to provide supervision to children and promote family well being by allowing parents to maintain employment, supporting protective, foster care, and preventive services, and serving families that are homeless or need child care for medical or social reasons. Child Care services may also include educational programming and family support. Examples include Day Care, Family Day Care, Head Start, Pre-Kindergarten and Children's Room in a Service Location.                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 1417008731  | Child Support Enforcement         | Child Support Enforcement consists of services to ensure that children receive financial and medical support from both parents. Services may include establishing paternity; locating noncustodial parents; establishing child support and medical support orders; and collecting, distributing, and enforcing child support payments. Examples also include programs to assist noncustodial parents in managing their child support obligation.                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 
| 1417008731  | Community Engagement              | Community Engagement consists of the facilitation and oversight of clients' meaningful participation in community processes and programs to provide enrichment, socialization, and development. Community Engagement may include projects to support local community spaces, including park revitalization and green spaces, and enables clients to become active and engaged members of their community. Examples include Civic Engagement and Community Service opportunities.                                                                                                                                                                                                                                                                                                                                                                                                                         | 
| 1417008731  | Conflict Resolution/Mediation     | Conflict Resolution/Mediation consists of services to provide methods of negotiation and objective intervention to resolve social disputes. Conflict Resolution/Mediation may include assistance with disputes in areas of landlord-tenant conflicts, family-related matters, and workplace disputes. Examples include Group Conflict Resolution/Mediation and Single/Interpersonal Conflict Resolution/Mediation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
| 1417008731  | Court Appointed Guardian Services | Court Appointed Guardian Services consists of services to assign an individual or institution authorized by a court to manage the personal and/or financial affairs of a person who cannot manage for himself or herself because of incapacity. Court Appointed Guardian Services also consist of monitoring and overseeing the services provided. Court Appointed Guardian Services may prevent financial exploitation and help individuals maintain financial health. Examples include Adult Protective Services, Community Court Appointed Guardian Services and Private Court Appointed Guardian Services.                                                                                                                                                                                                                                                                                           | 
```