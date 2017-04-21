# 2012 Provider- Level Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-provider-level-data-ae7f2) |
| Metadata | [Link](https://data.illinois.gov/api/views/fb9d-x3ms) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/fb9d-x3ms/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/fb9d-x3ms/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | fb9d-x3ms |
| Name | 2012 Provider- Level Data |
| Category | Health-Medicaid |
| Tags | hfs, medicaid, health |
| Created | 2014-04-23T17:37:19Z |
| Publication Date | 2014-04-23T17:52:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | providerkeyid             | #ProviderKeyID            | text      | number      |
| Yes      | numeric metric | npi                       | NPI                       | number    | number      |
| Yes      | numeric metric | providertypecd            | ProviderTypeCd            | number    | number      |
| Yes      | series tag     | providertypedesc          | ProviderTypeDesc          | text      | text        |
| Yes      | series tag     | providername              | ProviderName              | text      | text        |
| Yes      | series tag     | provzipcd                 | ProvZipCd                 | text      | number      |
| Yes      | numeric metric | officecountycd            | OfficeCountyCd            | number    | number      |
| Yes      | series tag     | officecountydesc          | OfficeCountyDesc          | text      | text        |
| Yes      | numeric metric | reimbursementtypecd       | ReimbursementTypeCd       | number    | number      |
| Yes      | series tag     | reimbursementtypedesc     | ReimbursementTypeDesc     | text      | text        |
| Yes      | numeric metric | criticalaccessind         | CriticalAccessInd         | number    | number      |
| Yes      | numeric metric | pcpind                    | PCPInd                    | number    | number      |
| Yes      | series tag     | primspeccddesc            | PrimSpecCdDesc            | text      | text        |
| Yes      | numeric metric | casemgmt_insurancerins    | CaseMgmt_InsuranceRINS    | number    | number      |
| Yes      | numeric metric | clinicservicesrins        | ClinicServicesRINS        | number    | number      |
| Yes      | numeric metric | dentalservicesrins        | DentalServicesRINS        | number    | number      |
| Yes      | numeric metric | epsdtrins                 | EPSDTRINS                 | number    | number      |
| Yes      | numeric metric | errins                    | ERRINS                    | number    | number      |
| Yes      | numeric metric | hcbsrins                  | HCBSRINS                  | number    | number      |
| Yes      | numeric metric | homehealthrins            | HomeHealthRINS            | number    | number      |
| Yes      | numeric metric | hospicerins               | HospiceRINS               | number    | number      |
| Yes      | numeric metric | icfmrrins                 | ICFMRRINS                 | number    | number      |
| Yes      | numeric metric | inpatientcarerins         | InpatientCareRINS         | number    | number      |
| Yes      | numeric metric | labradiologyrins          | LabRadiologyRINS          | number    | number      |
| Yes      | numeric metric | nursingfacilityrins       | NursingFacilityRINS       | number    | number      |
| Yes      | numeric metric | otherservicesrins         | OtherServicesRINS         | number    | number      |
| Yes      | numeric metric | outpatientrins            | OutPatientRINS            | number    | number      |
| Yes      | numeric metric | pddrins                   | PDDRINS                   | number    | number      |
| Yes      | numeric metric | prescdrugsrins            | PrescDRUGsRINS            | number    | number      |
| Yes      | numeric metric | rehabrins                 | RehabRINS                 | number    | number      |
| Yes      | numeric metric | schoolbasedrins           | SchoolBasedRINS           | number    | number      |
| Yes      | numeric metric | therapyrins               | TherapyRINS               | number    | number      |
| Yes      | numeric metric | casemgmt_insuranceevents  | CaseMgmt_InsuranceEvents  | number    | number      |
| Yes      | numeric metric | clinicservicesevents      | ClinicServicesEvents      | number    | number      |
| Yes      | numeric metric | dentalservicesevents      | DentalServicesEvents      | number    | number      |
| Yes      | numeric metric | epsdtevents               | EPSDTEvents               | number    | number      |
| Yes      | numeric metric | erevents                  | EREvents                  | number    | number      |
| Yes      | numeric metric | hcbsevents                | HCBSEvents                | number    | number      |
| Yes      | numeric metric | homehealthevents          | HomeHealthEvents          | number    | number      |
| Yes      | numeric metric | hospiceevents             | HospiceEvents             | number    | number      |
| Yes      | numeric metric | icfmrevents               | ICFMREvents               | number    | number      |
| Yes      | numeric metric | inpatientcareevents       | InpatientCareEvents       | number    | number      |
| Yes      | numeric metric | labradiologyevents        | LabRadiologyEvents        | number    | number      |
| Yes      | numeric metric | nursingfacilityevents     | NursingFacilityEvents     | number    | number      |
| Yes      | numeric metric | otherservicesevents       | OtherServicesEvents       | number    | number      |
| Yes      | numeric metric | outpatientevents          | OutPatientEvents          | number    | number      |
| Yes      | numeric metric | pddevents                 | PDDEvents                 | number    | number      |
| Yes      | numeric metric | prescdrugsevents          | PrescDRUGsEvents          | number    | number      |
| Yes      | numeric metric | rehabevents               | RehabEvents               | number    | number      |
| Yes      | numeric metric | schoolbasedevents         | SchoolBasedEvents         | number    | number      |
| Yes      | numeric metric | therapyevents             | TherapyEvents             | number    | number      |
| Yes      | numeric metric | casemgmt_insuranceuos     | CaseMgmt_InsuranceUOS     | number    | number      |
| Yes      | numeric metric | clinicservicesuos         | ClinicServicesUOS         | number    | number      |
| Yes      | numeric metric | dentalservicesuos         | DentalServicesUOS         | number    | number      |
| Yes      | numeric metric | epsdtuos                  | EPSDTUOS                  | number    | number      |
| Yes      | numeric metric | eruos                     | ERUOS                     | number    | number      |
| Yes      | numeric metric | hcbsuos                   | HCBSUOS                   | number    | number      |
| Yes      | numeric metric | homehealthuos             | HomeHealthUOS             | number    | number      |
| Yes      | numeric metric | hospiceuos                | HospiceUOS                | number    | number      |
| Yes      | numeric metric | icfmruos                  | ICFMRUOS                  | number    | number      |
| Yes      | numeric metric | inpatientcareuos          | InpatientCareUOS          | number    | number      |
| Yes      | numeric metric | labradiologyuos           | LabRadiologyUOS           | number    | number      |
| Yes      | numeric metric | nursingfacilityuos        | NursingFacilityUOS        | number    | number      |
| Yes      | numeric metric | otherservicesuos          | OtherServicesUOS          | number    | number      |
| Yes      | numeric metric | outpatientuos             | OutPatientUOS             | number    | number      |
| Yes      | numeric metric | pdduos                    | PDDUOS                    | number    | number      |
| Yes      | numeric metric | prescdrugsuos             | PrescDRUGsUOS             | number    | number      |
| Yes      | numeric metric | rehabuos                  | RehabUOS                  | number    | number      |
| Yes      | numeric metric | schoolbaseduos            | SchoolBasedUOS            | number    | number      |
| Yes      | numeric metric | therapyuos                | TherapyUOS                | number    | number      |
| Yes      | numeric metric | casemgmt_insurancecost    | CaseMgmt_InsuranceCost    | number    | number      |
| Yes      | numeric metric | clinicservicescost        | ClinicServicesCost        | number    | number      |
| Yes      | numeric metric | dentalservicescost        | DentalServicesCost        | number    | number      |
| Yes      | numeric metric | epsdtcost                 | EPSDTCost                 | number    | number      |
| Yes      | numeric metric | ercost                    | ERCost                    | number    | number      |
| Yes      | numeric metric | hcbscost                  | HCBSCost                  | number    | number      |
| Yes      | numeric metric | homehealthcost            | HomeHealthCost            | number    | number      |
| Yes      | numeric metric | hospicecost               | HospiceCost               | number    | number      |
| Yes      | numeric metric | icfmrcost                 | ICFMRCost                 | number    | number      |
| Yes      | numeric metric | inpatientcarecost         | InpatientCareCost         | number    | number      |
| Yes      | numeric metric | labradiologycost          | LabRadiologyCost          | number    | number      |
| Yes      | numeric metric | nursingfacilitycost       | NursingFacilityCost       | number    | number      |
| Yes      | numeric metric | otherservicescost         | OtherServicesCost         | number    | number      |
| Yes      | numeric metric | outpatientcost            | OutPatientCost            | number    | number      |
| Yes      | numeric metric | pddcost                   | PDDCost                   | number    | number      |
| Yes      | numeric metric | prescdrugscost            | PrescDRUGsCost            | number    | number      |
| Yes      | numeric metric | rehabcost                 | RehabCost                 | number    | number      |
| Yes      | numeric metric | schoolbasedcost           | SchoolBasedCost           | number    | number      |
| Yes      | numeric metric | therapycost               | TherapyCost               | number    | number      |
| Yes      | numeric metric | totalcost                 | TotalCost                 | number    | number      |
| Yes      | numeric metric | encounterclaims           | EncounterClaims           | number    | number      |
| Yes      | numeric metric | hospencounteraddonpayment | HospEncounterAddOnPayment | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fb9d-x3ms d:2012-01-01T00:00:00.000Z t:provzipcd=631101010 t:officecountydesc=Missouri t:providername="HIROSE KEIKO" t:providerkeyid=1101283205 t:primspeccddesc=Otorhinolaryngology t:providertypedesc=Physicians m:schoolbaseduos=0 m:otherservicesrins=111 m:criticalaccessind=0 m:otherservicesuos=190 m:clinicservicescost=0 m:npi=1376506287 m:rehabcost=0 m:homehealthevents=0 m:hcbsevents=0 m:inpatientcareuos=0 m:schoolbasedevents=0 m:inpatientcarecost=0 m:errins=0 m:epsdtevents=0 m:casemgmt_insurancecost=0 m:outpatientcost=0 m:prescdrugsuos=0 m:outpatientevents=0 m:labradiologyuos=0 m:hospicerins=0 m:dentalservicesevents=0 m:erevents=0 m:dentalservicesrins=0 m:homehealthcost=0 m:outpatientrins=0 m:prescdrugscost=0 m:pddrins=0 m:providertypecd=10 m:pdduos=0 m:labradiologyrins=0 m:labradiologycost=0 m:otherservicesevents=190 m:officecountycd=826 m:schoolbasedrins=0 m:therapyrins=0 m:pcpind=0 m:hcbsuos=0 m:homehealthrins=0 m:clinicservicesevents=0 m:icfmruos=0 m:pddcost=0 m:epsdtrins=0 m:epsdtcost=0 m:casemgmt_insuranceevents=0 m:icfmrrins=0 m:pddevents=0 m:prescdrugsevents=0 m:labradiologyevents=0 m:clinicservicesuos=0 m:encounterclaims=0 m:hospencounteraddonpayment=0 m:icfmrcost=0 m:totalcost=17933.87 m:rehabuos=0 m:hcbsrins=0 m:clinicservicesrins=0 m:eruos=0 m:rehabrins=0 m:hospiceuos=0 m:nursingfacilityrins=0 m:nursingfacilityuos=0 m:inpatientcarerins=0 m:nursingfacilitycost=0 m:otherservicescost=17933.87 m:casemgmt_insuranceuos=0 m:dentalservicescost=0 m:hcbscost=0 m:hospicecost=0 m:schoolbasedcost=0 m:epsdtuos=0 m:ercost=0 m:therapycost=0 m:rehabevents=0 m:therapyevents=0 m:nursingfacilityevents=0 m:dentalservicesuos=0 m:casemgmt_insurancerins=0 m:inpatientcareevents=0 m:therapyuos=0 m:icfmrevents=0 m:hospiceevents=0 m:outpatientuos=0 m:prescdrugsrins=0 m:homehealthuos=0

series e:fb9d-x3ms d:2012-01-01T00:00:00.000Z t:officecountydesc=Peoria t:providerkeyid=1101228208 t:providertypedesc="Waiver service provider--Disability (DHS/DRS)" m:schoolbaseduos=0 m:otherservicesrins=0 m:criticalaccessind=0 m:otherservicesuos=0 m:clinicservicescost=0 m:rehabcost=0 m:homehealthevents=0 m:hcbsevents=9 m:inpatientcareuos=0 m:errins=0 m:schoolbasedevents=0 m:inpatientcarecost=0 m:epsdtevents=0 m:casemgmt_insurancecost=0 m:outpatientcost=0 m:prescdrugsuos=0 m:outpatientevents=0 m:labradiologyuos=0 m:hospicerins=0 m:dentalservicesevents=0 m:erevents=0 m:dentalservicesrins=0 m:homehealthcost=0 m:outpatientrins=0 m:prescdrugscost=0 m:pddrins=0 m:providertypecd=92 m:pdduos=0 m:labradiologyrins=0 m:labradiologycost=0 m:otherservicesevents=0 m:officecountycd=80 m:schoolbasedrins=0 m:therapyrins=0 m:pcpind=0 m:hcbsuos=9 m:homehealthrins=0 m:clinicservicesevents=0 m:icfmruos=0 m:pddcost=0 m:epsdtrins=0 m:epsdtcost=0 m:casemgmt_insuranceevents=0 m:icfmrrins=0 m:pddevents=0 m:prescdrugsevents=0 m:labradiologyevents=0 m:clinicservicesuos=0 m:encounterclaims=0 m:hospencounteraddonpayment=0 m:icfmrcost=0 m:totalcost=4559.04 m:rehabuos=0 m:hcbsrins=1 m:clinicservicesrins=0 m:eruos=0 m:rehabrins=0 m:hospiceuos=0 m:nursingfacilityrins=0 m:nursingfacilityuos=0 m:inpatientcarerins=0 m:nursingfacilitycost=0 m:otherservicescost=0 m:casemgmt_insuranceuos=0 m:dentalservicescost=0 m:hcbscost=4559.04 m:hospicecost=0 m:schoolbasedcost=0 m:epsdtuos=0 m:ercost=0 m:therapycost=0 m:rehabevents=0 m:therapyevents=0 m:nursingfacilityevents=0 m:dentalservicesuos=0 m:casemgmt_insurancerins=0 m:inpatientcareevents=0 m:therapyuos=0 m:icfmrevents=0 m:hospiceevents=0 m:outpatientuos=0 m:prescdrugsrins=0 m:homehealthuos=0

series e:fb9d-x3ms d:2012-01-01T00:00:00.000Z t:officecountydesc=Cook t:providerkeyid=1101248396 t:providertypedesc="Waiver service provider--Children's support (DHS/DDD)" m:schoolbaseduos=0 m:otherservicesrins=0 m:criticalaccessind=0 m:otherservicesuos=0 m:clinicservicescost=0 m:rehabcost=0 m:homehealthevents=0 m:hcbsevents=168 m:inpatientcareuos=0 m:errins=0 m:schoolbasedevents=0 m:inpatientcarecost=0 m:epsdtevents=0 m:casemgmt_insurancecost=0 m:outpatientcost=0 m:prescdrugsuos=0 m:outpatientevents=0 m:labradiologyuos=0 m:hospicerins=0 m:dentalservicesevents=0 m:erevents=0 m:dentalservicesrins=0 m:homehealthcost=0 m:outpatientrins=0 m:prescdrugscost=0 m:pddrins=0 m:providertypecd=94 m:pdduos=0 m:labradiologyrins=0 m:labradiologycost=0 m:otherservicesevents=0 m:officecountycd=200 m:schoolbasedrins=0 m:therapyrins=0 m:pcpind=0 m:hcbsuos=168 m:homehealthrins=0 m:clinicservicesevents=0 m:icfmruos=0 m:pddcost=0 m:epsdtrins=0 m:epsdtcost=0 m:casemgmt_insuranceevents=0 m:icfmrrins=0 m:pddevents=0 m:prescdrugsevents=0 m:labradiologyevents=0 m:clinicservicesuos=0 m:encounterclaims=0 m:hospencounteraddonpayment=0 m:icfmrcost=0 m:totalcost=15087.8 m:rehabuos=0 m:hcbsrins=1 m:clinicservicesrins=0 m:eruos=0 m:rehabrins=0 m:hospiceuos=0 m:nursingfacilityrins=0 m:nursingfacilityuos=0 m:inpatientcarerins=0 m:nursingfacilitycost=0 m:otherservicescost=0 m:casemgmt_insuranceuos=0 m:dentalservicescost=0 m:hcbscost=15087.8 m:hospicecost=0 m:schoolbasedcost=0 m:epsdtuos=0 m:ercost=0 m:therapycost=0 m:rehabevents=0 m:therapyevents=0 m:nursingfacilityevents=0 m:dentalservicesuos=0 m:casemgmt_insurancerins=0 m:inpatientcareevents=0 m:therapyuos=0 m:icfmrevents=0 m:hospiceevents=0 m:outpatientuos=0 m:prescdrugsrins=0 m:homehealthuos=0
```

## Meta Commands

```ls
metric m:npi p:integer l:NPI t:dataTypeName=number

metric m:providertypecd p:integer l:ProviderTypeCd t:dataTypeName=number

metric m:officecountycd p:integer l:OfficeCountyCd t:dataTypeName=number

metric m:reimbursementtypecd p:long l:ReimbursementTypeCd t:dataTypeName=number

metric m:criticalaccessind p:integer l:CriticalAccessInd t:dataTypeName=number

metric m:pcpind p:integer l:PCPInd t:dataTypeName=number

metric m:casemgmt_insurancerins p:integer l:CaseMgmt_InsuranceRINS t:dataTypeName=number

metric m:clinicservicesrins p:integer l:ClinicServicesRINS t:dataTypeName=number

metric m:dentalservicesrins p:integer l:DentalServicesRINS t:dataTypeName=number

metric m:epsdtrins p:integer l:EPSDTRINS t:dataTypeName=number

metric m:errins p:integer l:ERRINS t:dataTypeName=number

metric m:hcbsrins p:integer l:HCBSRINS t:dataTypeName=number

metric m:homehealthrins p:integer l:HomeHealthRINS t:dataTypeName=number

metric m:hospicerins p:integer l:HospiceRINS t:dataTypeName=number

metric m:icfmrrins p:integer l:ICFMRRINS t:dataTypeName=number

metric m:inpatientcarerins p:integer l:InpatientCareRINS t:dataTypeName=number

metric m:labradiologyrins p:integer l:LabRadiologyRINS t:dataTypeName=number

metric m:nursingfacilityrins p:integer l:NursingFacilityRINS t:dataTypeName=number

metric m:otherservicesrins p:integer l:OtherServicesRINS t:dataTypeName=number

metric m:outpatientrins p:integer l:OutPatientRINS t:dataTypeName=number

metric m:pddrins p:integer l:PDDRINS t:dataTypeName=number

metric m:prescdrugsrins p:integer l:PrescDRUGsRINS t:dataTypeName=number

metric m:rehabrins p:integer l:RehabRINS t:dataTypeName=number

metric m:schoolbasedrins p:integer l:SchoolBasedRINS t:dataTypeName=number

metric m:therapyrins p:integer l:TherapyRINS t:dataTypeName=number

metric m:casemgmt_insuranceevents p:integer l:CaseMgmt_InsuranceEvents t:dataTypeName=number

metric m:clinicservicesevents p:integer l:ClinicServicesEvents t:dataTypeName=number

metric m:dentalservicesevents p:integer l:DentalServicesEvents t:dataTypeName=number

metric m:epsdtevents p:integer l:EPSDTEvents t:dataTypeName=number

metric m:erevents p:integer l:EREvents t:dataTypeName=number

metric m:hcbsevents p:integer l:HCBSEvents t:dataTypeName=number

metric m:homehealthevents p:integer l:HomeHealthEvents t:dataTypeName=number

metric m:hospiceevents p:integer l:HospiceEvents t:dataTypeName=number

metric m:icfmrevents p:integer l:ICFMREvents t:dataTypeName=number

metric m:inpatientcareevents p:integer l:InpatientCareEvents t:dataTypeName=number

metric m:labradiologyevents p:integer l:LabRadiologyEvents t:dataTypeName=number

metric m:nursingfacilityevents p:integer l:NursingFacilityEvents t:dataTypeName=number

metric m:otherservicesevents p:integer l:OtherServicesEvents t:dataTypeName=number

metric m:outpatientevents p:integer l:OutPatientEvents t:dataTypeName=number

metric m:pddevents p:integer l:PDDEvents t:dataTypeName=number

metric m:prescdrugsevents p:integer l:PrescDRUGsEvents t:dataTypeName=number

metric m:rehabevents p:integer l:RehabEvents t:dataTypeName=number

metric m:schoolbasedevents p:integer l:SchoolBasedEvents t:dataTypeName=number

metric m:therapyevents p:integer l:TherapyEvents t:dataTypeName=number

metric m:casemgmt_insuranceuos p:integer l:CaseMgmt_InsuranceUOS t:dataTypeName=number

metric m:clinicservicesuos p:integer l:ClinicServicesUOS t:dataTypeName=number

metric m:dentalservicesuos p:integer l:DentalServicesUOS t:dataTypeName=number

metric m:epsdtuos p:integer l:EPSDTUOS t:dataTypeName=number

metric m:eruos p:integer l:ERUOS t:dataTypeName=number

metric m:hcbsuos p:integer l:HCBSUOS t:dataTypeName=number

metric m:homehealthuos p:integer l:HomeHealthUOS t:dataTypeName=number

metric m:hospiceuos p:integer l:HospiceUOS t:dataTypeName=number

metric m:icfmruos p:integer l:ICFMRUOS t:dataTypeName=number

metric m:inpatientcareuos p:integer l:InpatientCareUOS t:dataTypeName=number

metric m:labradiologyuos p:integer l:LabRadiologyUOS t:dataTypeName=number

metric m:nursingfacilityuos p:integer l:NursingFacilityUOS t:dataTypeName=number

metric m:otherservicesuos p:integer l:OtherServicesUOS t:dataTypeName=number

metric m:outpatientuos p:integer l:OutPatientUOS t:dataTypeName=number

metric m:pdduos p:integer l:PDDUOS t:dataTypeName=number

metric m:prescdrugsuos p:integer l:PrescDRUGsUOS t:dataTypeName=number

metric m:rehabuos p:integer l:RehabUOS t:dataTypeName=number

metric m:schoolbaseduos p:integer l:SchoolBasedUOS t:dataTypeName=number

metric m:therapyuos p:integer l:TherapyUOS t:dataTypeName=number

metric m:casemgmt_insurancecost p:decimal l:CaseMgmt_InsuranceCost t:dataTypeName=number

metric m:clinicservicescost p:decimal l:ClinicServicesCost t:dataTypeName=number

metric m:dentalservicescost p:double l:DentalServicesCost t:dataTypeName=number

metric m:epsdtcost p:double l:EPSDTCost t:dataTypeName=number

metric m:ercost p:decimal l:ERCost t:dataTypeName=number

metric m:hcbscost p:decimal l:HCBSCost t:dataTypeName=number

metric m:homehealthcost p:float l:HomeHealthCost t:dataTypeName=number

metric m:hospicecost p:decimal l:HospiceCost t:dataTypeName=number

metric m:icfmrcost p:decimal l:ICFMRCost t:dataTypeName=number

metric m:inpatientcarecost p:double l:InpatientCareCost t:dataTypeName=number

metric m:labradiologycost p:decimal l:LabRadiologyCost t:dataTypeName=number

metric m:nursingfacilitycost p:double l:NursingFacilityCost t:dataTypeName=number

metric m:otherservicescost p:decimal l:OtherServicesCost t:dataTypeName=number

metric m:outpatientcost p:decimal l:OutPatientCost t:dataTypeName=number

metric m:pddcost p:decimal l:PDDCost t:dataTypeName=number

metric m:prescdrugscost p:decimal l:PrescDRUGsCost t:dataTypeName=number

metric m:rehabcost p:double l:RehabCost t:dataTypeName=number

metric m:schoolbasedcost p:decimal l:SchoolBasedCost t:dataTypeName=number

metric m:therapycost p:double l:TherapyCost t:dataTypeName=number

metric m:totalcost p:decimal l:TotalCost t:dataTypeName=number

metric m:encounterclaims p:integer l:EncounterClaims t:dataTypeName=number

metric m:hospencounteraddonpayment p:double l:HospEncounterAddOnPayment t:dataTypeName=number

entity e:fb9d-x3ms l:"2012 Provider- Level Data" t:url=https://data.illinois.gov/api/views/fb9d-x3ms

property e:fb9d-x3ms t:meta.view v:id=fb9d-x3ms v:category=Health-Medicaid v:averageRating=60 v:name="2012 Provider- Level Data"

property e:fb9d-x3ms t:meta.view.owner v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:displayName="HFS - Administrator"

property e:fb9d-x3ms t:meta.view.tableauthor v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:roleName=publisher v:displayName="HFS - Administrator"
```

## Top Records

```ls
| providerkeyid | npi        | providertypecd | providertypedesc                                      | providername           | provzipcd | officecountycd | officecountydesc | reimbursementtypecd | reimbursementtypedesc | criticalaccessind | pcpind | primspeccddesc      | casemgmt_insurancerins | clinicservicesrins | dentalservicesrins | epsdtrins | errins | hcbsrins | homehealthrins | hospicerins | icfmrrins | inpatientcarerins | labradiologyrins | nursingfacilityrins | otherservicesrins | outpatientrins | pddrins | prescdrugsrins | rehabrins | schoolbasedrins | therapyrins | casemgmt_insuranceevents | clinicservicesevents | dentalservicesevents | epsdtevents | erevents | hcbsevents | homehealthevents | hospiceevents | icfmrevents | inpatientcareevents | labradiologyevents | nursingfacilityevents | otherservicesevents | outpatientevents | pddevents | prescdrugsevents | rehabevents | schoolbasedevents | therapyevents | casemgmt_insuranceuos | clinicservicesuos | dentalservicesuos | epsdtuos | eruos | hcbsuos | homehealthuos | hospiceuos | icfmruos | inpatientcareuos | labradiologyuos | nursingfacilityuos | otherservicesuos | outpatientuos | pdduos | prescdrugsuos | rehabuos | schoolbaseduos | therapyuos | casemgmt_insurancecost | clinicservicescost | dentalservicescost | epsdtcost | ercost | hcbscost           | homehealthcost | hospicecost | icfmrcost | inpatientcarecost | labradiologycost | nursingfacilitycost | otherservicescost | outpatientcost | pddcost | prescdrugscost | rehabcost | schoolbasedcost | therapycost | totalcost          | encounterclaims | hospencounteraddonpayment | 
| ============= | ========== | ============== | ===================================================== | ====================== | ========= | ============== | ================ | =================== | ===================== | ================= | ====== | =================== | ====================== | ================== | ================== | ========= | ====== | ======== | ============== | =========== | ========= | ================= | ================ | =================== | ================= | ============== | ======= | ============== | ========= | =============== | =========== | ======================== | ==================== | ==================== | =========== | ======== | ========== | ================ | ============= | =========== | =================== | ================== | ===================== | =================== | ================ | ========= | ================ | =========== | ================= | ============= | ===================== | ================= | ================= | ======== | ===== | ======= | ============= | ========== | ======== | ================ | =============== | ================== | ================ | ============= | ====== | ============= | ======== | ============== | ========== | ====================== | ================== | ================== | ========= | ====== | ================== | ============== | =========== | ========= | ================= | ================ | =================== | ================= | ============== | ======= | ============== | ========= | =============== | =========== | ================== | =============== | ========================= | 
| 1101283205    | 1376506287 | 10             | Physicians                                            | HIROSE KEIKO           | 631101010 | 826            | Missouri         |                     |                       | 0                 | 0      | Otorhinolaryngology | 0                      | 0                  | 0                  | 0         | 0      | 0        | 0              | 0           | 0         | 0                 | 0                | 0                   | 111               | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 0          | 0                | 0             | 0           | 0                   | 0                  | 0                     | 190                 | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 0       | 0             | 0          | 0        | 0                | 0               | 0                  | 190              | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 0                  | 0              | 0           | 0         | 0                 | 0                | 0                   | 17933.87          | 0              | 0       | 0              | 0         | 0               | 0           | 17933.87           | 0               | 0                         | 
| 1101228208    |            | 92             | Waiver service provider--Disability (DHS/DRS)         |                        |           | 80             | Peoria           |                     |                       | 0                 | 0      |                     | 0                      | 0                  | 0                  | 0         | 0      | 1        | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 9          | 0                | 0             | 0           | 0                   | 0                  | 0                     | 0                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 9       | 0             | 0          | 0        | 0                | 0               | 0                  | 0                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 4559.04            | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 4559.04            | 0               | 0                         | 
| 1101248396    |            | 94             | Waiver service provider--Children's support (DHS/DDD) |                        |           | 200            | Cook             |                     |                       | 0                 | 0      |                     | 0                      | 0                  | 0                  | 0         | 0      | 1        | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 168        | 0                | 0             | 0           | 0                   | 0                  | 0                     | 0                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 168     | 0             | 0          | 0        | 0                | 0               | 0                  | 0                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 15087.8            | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 15087.8            | 0               | 0                         | 
| 1101079041    |            | 92             | Waiver service provider--Disability (DHS/DRS)         |                        |           | 109            | Winnebago        |                     |                       | 0                 | 0      |                     | 0                      | 0                  | 0                  | 0         | 0      | 1        | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 15         | 0                | 0             | 0           | 0                   | 0                  | 0                     | 0                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 15      | 0             | 0          | 0        | 0                | 0               | 0                  | 0                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 10680.44           | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 10680.44           | 0               | 0                         | 
| 1101017335    | 1700814183 | 10             | Physicians                                            | TAMAYO RAUL            | 608042411 | 200            | Cook             |                     |                       | 0                 | 1      | Pediatrics          | 1152                   | 0                  | 0                  | 777       | 0      | 0        | 0              | 0           | 0         | 0                 | 82               | 0                   | 967               | 0              | 0       | 0              | 0         | 0               | 0           | 11450                    | 0                    | 0                    | 4283        | 0        | 0          | 0                | 0             | 0           | 0                   | 97                 | 0                     | 2431                | 0                | 0         | 0                | 0           | 0                 | 0             | 11450                 | 0                 | 0                 | 4283     | 0     | 0       | 0             | 0          | 0        | 0                | 97              | 0                  | 2431             | 0             | 0      | 0             | 0        | 0              | 0          | 22900                  | 0                  | 0                  | 113317.63 | 0      | 0                  | 0              | 0           | 0         | 0                 | 223.19           | 0                   | 102719.41         | 0              | 0       | 0              | 0         | 0               | 0           | 239160.23          | 0               | 0                         | 
| 1101388509    | 1780683953 | 10             | Physicians                                            | GOTTUMUKKALA GANAPATHI | 604771758 | 200            | Cook             |                     |                       | 0                 | 1      | Family Practice     | 34                     | 0                  | 0                  | 6         | 0      | 0        | 0              | 0           | 0         | 0                 | 1                | 0                   | 42                | 0              | 0       | 0              | 0         | 0               | 0           | 307                      | 0                    | 0                    | 11          | 0        | 0          | 0                | 0             | 0           | 0                   | 1                  | 0                     | 132                 | 0                | 0         | 0                | 0           | 0                 | 0             | 307                   | 0                 | 0                 | 11       | 0     | 0       | 0             | 0          | 0        | 0                | 1               | 0                  | 132              | 0             | 0      | 0             | 0        | 0              | 0          | 757                    | 0                  | 0                  | 455.78    | 0      | 0                  | 0              | 0           | 0         | 0                 | 2.6              | 0                   | 2588.27           | 0              | 0       | 0              | 0         | 0               | 0           | 3803.65            | 0               | 0                         | 
| 1101523524    |            | 98             | Waiver service provider--TBI (DHS/DRS)                |                        |           | 200            | Cook             |                     |                       | 0                 | 0      |                     | 0                      | 0                  | 0                  | 0         | 0      | 1        | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 14         | 0                | 0             | 0           | 0                   | 0                  | 0                     | 0                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 14      | 0             | 0          | 0        | 0                | 0               | 0                  | 0                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 10736.36           | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 10736.36           | 0               | 0                         | 
| 1101453233    | 1518904739 | 10             | Physicians                                            | LABRIOLA JOANNE        | 605152268 | 30             | DuPage           |                     |                       | 0                 | 0      | Orthopedic Surgery  | 0                      | 0                  | 0                  | 0         | 0      | 0        | 0              | 0           | 0         | 0                 | 13               | 0                   | 40                | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 0          | 0                | 0             | 0           | 0                   | 27                 | 0                     | 77                  | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 0       | 0             | 0          | 0        | 0                | 27              | 0                  | 77               | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 0                  | 0              | 0           | 0         | 0                 | 554.1            | 0                   | 7853.79           | 0              | 0       | 0              | 0         | 0               | 0           | 8407.89            | 0               | 0                         | 
| 1101082059    | 1972624609 | 55             | Early Intervention Services                           | MOSSMAN JAIME          | 601812618 | 30             | DuPage           |                     |                       | 0                 | 0      |                     | 0                      | 0                  | 0                  | 0         | 0      | 0        | 0              | 0           | 0         | 0                 | 0                | 0                   | 59                | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 0          | 0                | 0             | 0           | 0                   | 0                  | 0                     | 143                 | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 0       | 0             | 0          | 0        | 0                | 0               | 0                  | 143              | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 0                  | 0              | 0           | 0         | 0                 | 0                | 0                   | 13580.94          | 0              | 0       | 0              | 0         | 0               | 0           | 13580.94           | 0               | 0                         | 
| 1101320767    |            | 92             | Waiver service provider--Disability (DHS/DRS)         |                        |           | 54             | Kankakee         |                     |                       | 0                 | 0      |                     | 0                      | 0                  | 0                  | 0         | 0      | 1        | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 24         | 0                | 0             | 0           | 0                   | 0                  | 0                     | 0                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 24      | 0             | 0          | 0        | 0                | 0               | 0                  | 0                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 8859.9599999999991 | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 8859.9599999999991 | 0               | 0                         | 
```