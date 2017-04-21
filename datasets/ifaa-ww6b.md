# 2011 Provider- Level Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-provider-level-data-c8a7a) |
| Metadata | [Link](https://data.illinois.gov/api/views/ifaa-ww6b) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ifaa-ww6b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ifaa-ww6b/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ifaa-ww6b |
| Name | 2011 Provider- Level Data |
| Category | Health-Medicaid |
| Tags | hfs, medicaid, health |
| Created | 2014-04-23T17:19:14Z |
| Publication Date | 2014-04-23T17:26:42Z |

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
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ifaa-ww6b d:2011-01-01T00:00:00.000Z t:provzipcd=600043906 t:officecountydesc=Cook t:providername="PUNDY CHRISTINE" t:providerkeyid=1000362053 t:primspeccddesc=Ophthalmology t:providertypedesc=Physicians m:schoolbaseduos=0 m:otherservicesrins=13 m:criticalaccessind=0 m:otherservicesuos=28 m:clinicservicescost=0 m:npi=1831110733 m:rehabcost=0 m:homehealthevents=0 m:hcbsevents=0 m:inpatientcareuos=0 m:schoolbasedevents=0 m:inpatientcarecost=0 m:errins=0 m:epsdtevents=0 m:casemgmt_insurancecost=0 m:outpatientcost=0 m:prescdrugsuos=0 m:outpatientevents=0 m:labradiologyuos=0 m:hospicerins=0 m:dentalservicesevents=0 m:erevents=0 m:dentalservicesrins=0 m:homehealthcost=0 m:outpatientrins=0 m:prescdrugscost=0 m:pddrins=0 m:providertypecd=10 m:pdduos=0 m:labradiologyrins=0 m:labradiologycost=0 m:otherservicesevents=28 m:officecountycd=200 m:schoolbasedrins=0 m:therapyrins=0 m:pcpind=0 m:hcbsuos=0 m:homehealthrins=0 m:clinicservicesevents=0 m:icfmruos=0 m:pddcost=0 m:epsdtrins=0 m:epsdtcost=0 m:casemgmt_insuranceevents=0 m:icfmrrins=0 m:pddevents=0 m:prescdrugsevents=0 m:labradiologyevents=0 m:clinicservicesuos=0 m:encounterclaims=0 m:hospencounteraddonpayment=0 m:icfmrcost=0 m:totalcost=509.94 m:rehabuos=0 m:hcbsrins=0 m:clinicservicesrins=0 m:eruos=0 m:rehabrins=0 m:hospiceuos=0 m:nursingfacilityrins=0 m:nursingfacilityuos=0 m:inpatientcarerins=0 m:nursingfacilitycost=0 m:otherservicescost=509.94 m:casemgmt_insuranceuos=0 m:dentalservicescost=0 m:hcbscost=0 m:hospicecost=0 m:schoolbasedcost=0 m:epsdtuos=0 m:ercost=0 m:therapycost=0 m:rehabevents=0 m:therapyevents=0 m:nursingfacilityevents=0 m:dentalservicesuos=0 m:casemgmt_insurancerins=0 m:inpatientcareevents=0 m:therapyuos=0 m:icfmrevents=0 m:hospiceevents=0 m:outpatientuos=0 m:prescdrugsrins=0 m:homehealthuos=0

series e:ifaa-ww6b d:2011-01-01T00:00:00.000Z t:provzipcd=62864 t:officecountydesc=Jefferson t:providername="JEFFERSON COUNTY COMPREHENSIVE" t:providerkeyid=1000002013 t:providertypedesc="Waiver service provider--Disability (DHS/DRS)" m:schoolbaseduos=0 m:otherservicesrins=0 m:criticalaccessind=0 m:otherservicesuos=0 m:clinicservicescost=0 m:npi=1000002013 m:rehabcost=0 m:homehealthevents=0 m:hcbsevents=41 m:inpatientcareuos=0 m:schoolbasedevents=0 m:inpatientcarecost=0 m:errins=0 m:epsdtevents=0 m:casemgmt_insurancecost=0 m:outpatientcost=0 m:prescdrugsuos=0 m:outpatientevents=0 m:labradiologyuos=0 m:hospicerins=0 m:dentalservicesevents=0 m:erevents=0 m:dentalservicesrins=0 m:homehealthcost=0 m:outpatientrins=0 m:prescdrugscost=0 m:pddrins=0 m:providertypecd=92 m:pdduos=0 m:labradiologyrins=0 m:labradiologycost=0 m:otherservicesevents=0 m:officecountycd=49 m:schoolbasedrins=0 m:therapyrins=0 m:pcpind=0 m:hcbsuos=41 m:homehealthrins=0 m:clinicservicesevents=0 m:icfmruos=0 m:pddcost=0 m:epsdtrins=0 m:epsdtcost=0 m:casemgmt_insuranceevents=0 m:icfmrrins=0 m:pddevents=0 m:prescdrugsevents=0 m:labradiologyevents=0 m:clinicservicesuos=0 m:encounterclaims=0 m:hospencounteraddonpayment=0 m:icfmrcost=0 m:totalcost=5575.67 m:rehabuos=0 m:hcbsrins=7 m:clinicservicesrins=0 m:eruos=0 m:rehabrins=0 m:hospiceuos=0 m:nursingfacilityrins=0 m:nursingfacilityuos=0 m:inpatientcarerins=0 m:nursingfacilitycost=0 m:otherservicescost=0 m:casemgmt_insuranceuos=0 m:dentalservicescost=0 m:hcbscost=5575.67 m:hospicecost=0 m:schoolbasedcost=0 m:epsdtuos=0 m:ercost=0 m:therapycost=0 m:rehabevents=0 m:therapyevents=0 m:nursingfacilityevents=0 m:dentalservicesuos=0 m:casemgmt_insurancerins=0 m:inpatientcareevents=0 m:therapyuos=0 m:icfmrevents=0 m:hospiceevents=0 m:outpatientuos=0 m:prescdrugsrins=0 m:homehealthuos=0

series e:ifaa-ww6b d:2011-01-01T00:00:00.000Z t:officecountydesc=Cook t:providerkeyid=1000081358 t:providertypedesc="Waiver service provider--Disability (DHS/DRS)" m:schoolbaseduos=0 m:otherservicesrins=0 m:criticalaccessind=0 m:otherservicesuos=0 m:clinicservicescost=0 m:rehabcost=0 m:homehealthevents=0 m:hcbsevents=12 m:inpatientcareuos=0 m:errins=0 m:schoolbasedevents=0 m:inpatientcarecost=0 m:epsdtevents=0 m:casemgmt_insurancecost=0 m:outpatientcost=0 m:prescdrugsuos=0 m:outpatientevents=0 m:labradiologyuos=0 m:hospicerins=0 m:dentalservicesevents=0 m:erevents=0 m:dentalservicesrins=0 m:homehealthcost=0 m:outpatientrins=0 m:prescdrugscost=0 m:pddrins=0 m:providertypecd=92 m:pdduos=0 m:labradiologyrins=0 m:labradiologycost=0 m:otherservicesevents=0 m:officecountycd=200 m:schoolbasedrins=0 m:therapyrins=0 m:pcpind=0 m:hcbsuos=12 m:homehealthrins=0 m:clinicservicesevents=0 m:icfmruos=0 m:pddcost=0 m:epsdtrins=0 m:epsdtcost=0 m:casemgmt_insuranceevents=0 m:icfmrrins=0 m:pddevents=0 m:prescdrugsevents=0 m:labradiologyevents=0 m:clinicservicesuos=0 m:encounterclaims=0 m:hospencounteraddonpayment=0 m:icfmrcost=0 m:totalcost=9547.32 m:rehabuos=0 m:hcbsrins=1 m:clinicservicesrins=0 m:eruos=0 m:rehabrins=0 m:hospiceuos=0 m:nursingfacilityrins=0 m:nursingfacilityuos=0 m:inpatientcarerins=0 m:nursingfacilitycost=0 m:otherservicescost=0 m:casemgmt_insuranceuos=0 m:dentalservicescost=0 m:hcbscost=9547.32 m:hospicecost=0 m:schoolbasedcost=0 m:epsdtuos=0 m:ercost=0 m:therapycost=0 m:rehabevents=0 m:therapyevents=0 m:nursingfacilityevents=0 m:dentalservicesuos=0 m:casemgmt_insurancerins=0 m:inpatientcareevents=0 m:therapyuos=0 m:icfmrevents=0 m:hospiceevents=0 m:outpatientuos=0 m:prescdrugsrins=0 m:homehealthuos=0
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

metric m:ercost p:double l:ERCost t:dataTypeName=number

metric m:hcbscost p:decimal l:HCBSCost t:dataTypeName=number

metric m:homehealthcost p:float l:HomeHealthCost t:dataTypeName=number

metric m:hospicecost p:decimal l:HospiceCost t:dataTypeName=number

metric m:icfmrcost p:double l:ICFMRCost t:dataTypeName=number

metric m:inpatientcarecost p:decimal l:InpatientCareCost t:dataTypeName=number

metric m:labradiologycost p:decimal l:LabRadiologyCost t:dataTypeName=number

metric m:nursingfacilitycost p:decimal l:NursingFacilityCost t:dataTypeName=number

metric m:otherservicescost p:decimal l:OtherServicesCost t:dataTypeName=number

metric m:outpatientcost p:decimal l:OutPatientCost t:dataTypeName=number

metric m:pddcost p:decimal l:PDDCost t:dataTypeName=number

metric m:prescdrugscost p:decimal l:PrescDRUGsCost t:dataTypeName=number

metric m:rehabcost p:double l:RehabCost t:dataTypeName=number

metric m:schoolbasedcost p:decimal l:SchoolBasedCost t:dataTypeName=number

metric m:therapycost p:double l:TherapyCost t:dataTypeName=number

metric m:totalcost p:double l:TotalCost t:dataTypeName=number

metric m:encounterclaims p:integer l:EncounterClaims t:dataTypeName=number

metric m:hospencounteraddonpayment p:double l:HospEncounterAddOnPayment t:dataTypeName=number

entity e:ifaa-ww6b l:"2011 Provider- Level Data" t:url=https://data.illinois.gov/api/views/ifaa-ww6b

property e:ifaa-ww6b t:meta.view v:id=ifaa-ww6b v:category=Health-Medicaid v:averageRating=0 v:name="2011 Provider- Level Data"

property e:ifaa-ww6b t:meta.view.owner v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:displayName="HFS - Administrator"

property e:ifaa-ww6b t:meta.view.tableauthor v:id=xh33-g7e8 v:screenName="HFS - Administrator" v:roleName=publisher v:displayName="HFS - Administrator"
```

## Top Records

```ls
| providerkeyid | npi        | providertypecd | providertypedesc                              | providername                   | provzipcd | officecountycd | officecountydesc | reimbursementtypecd | reimbursementtypedesc | criticalaccessind | pcpind | primspeccddesc       | casemgmt_insurancerins | clinicservicesrins | dentalservicesrins | epsdtrins | errins | hcbsrins | homehealthrins | hospicerins | icfmrrins | inpatientcarerins | labradiologyrins | nursingfacilityrins | otherservicesrins | outpatientrins | pddrins | prescdrugsrins | rehabrins | schoolbasedrins | therapyrins | casemgmt_insuranceevents | clinicservicesevents | dentalservicesevents | epsdtevents | erevents | hcbsevents | homehealthevents | hospiceevents | icfmrevents | inpatientcareevents | labradiologyevents | nursingfacilityevents | otherservicesevents | outpatientevents | pddevents | prescdrugsevents | rehabevents | schoolbasedevents | therapyevents | casemgmt_insuranceuos | clinicservicesuos | dentalservicesuos | epsdtuos | eruos | hcbsuos | homehealthuos | hospiceuos | icfmruos | inpatientcareuos | labradiologyuos | nursingfacilityuos | otherservicesuos | outpatientuos | pdduos | prescdrugsuos | rehabuos | schoolbaseduos | therapyuos | casemgmt_insurancecost | clinicservicescost | dentalservicescost | epsdtcost | ercost | hcbscost           | homehealthcost | hospicecost | icfmrcost | inpatientcarecost | labradiologycost | nursingfacilitycost | otherservicescost | outpatientcost | pddcost | prescdrugscost | rehabcost | schoolbasedcost | therapycost | totalcost          | encounterclaims | hospencounteraddonpayment | 
| ============= | ========== | ============== | ============================================= | ============================== | ========= | ============== | ================ | =================== | ===================== | ================= | ====== | ==================== | ====================== | ================== | ================== | ========= | ====== | ======== | ============== | =========== | ========= | ================= | ================ | =================== | ================= | ============== | ======= | ============== | ========= | =============== | =========== | ======================== | ==================== | ==================== | =========== | ======== | ========== | ================ | ============= | =========== | =================== | ================== | ===================== | =================== | ================ | ========= | ================ | =========== | ================= | ============= | ===================== | ================= | ================= | ======== | ===== | ======= | ============= | ========== | ======== | ================ | =============== | ================== | ================ | ============= | ====== | ============= | ======== | ============== | ========== | ====================== | ================== | ================== | ========= | ====== | ================== | ============== | =========== | ========= | ================= | ================ | =================== | ================= | ============== | ======= | ============== | ========= | =============== | =========== | ================== | =============== | ========================= | 
| 1000362053    | 1831110733 | 10             | Physicians                                    | PUNDY CHRISTINE                | 600043906 | 200            | Cook             |                     |                       | 0                 | 0      | Ophthalmology        | 0                      | 0                  | 0                  | 0         | 0      | 0        | 0              | 0           | 0         | 0                 | 0                | 0                   | 13                | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 0          | 0                | 0             | 0           | 0                   | 0                  | 0                     | 28                  | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 0       | 0             | 0          | 0        | 0                | 0               | 0                  | 28               | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 0                  | 0              | 0           | 0         | 0                 | 0                | 0                   | 509.94            | 0              | 0       | 0              | 0         | 0               | 0           | 509.94             | 0               | 0                         | 
| 1000002013    | 1000002013 | 92             | Waiver service provider--Disability (DHS/DRS) | JEFFERSON COUNTY COMPREHENSIVE | 62864     | 49             | Jefferson        |                     |                       | 0                 | 0      |                      | 0                      | 0                  | 0                  | 0         | 0      | 7        | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 41         | 0                | 0             | 0           | 0                   | 0                  | 0                     | 0                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 41      | 0             | 0          | 0        | 0                | 0               | 0                  | 0                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 5575.67            | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 5575.67            | 0               | 0                         | 
| 1000081358    |            | 92             | Waiver service provider--Disability (DHS/DRS) |                                |           | 200            | Cook             |                     |                       | 0                 | 0      |                      | 0                      | 0                  | 0                  | 0         | 0      | 1        | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 12         | 0                | 0             | 0           | 0                   | 0                  | 0                     | 0                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 12      | 0             | 0          | 0        | 0                | 0               | 0                  | 0                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 9547.32            | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 9547.32            | 0               | 0                         | 
| 1000323084    | 1255388906 | 10             | Physicians                                    | BOCHICCHIO GRANT               | 631101010 | 826            | Missouri         |                     |                       | 0                 | 0      | Surgery General      | 0                      | 0                  | 0                  | 0         | 0      | 0        | 0              | 0           | 0         | 0                 | 0                | 0                   | 28                | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 0          | 0                | 0             | 0           | 0                   | 0                  | 0                     | 74                  | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 0       | 0             | 0          | 0        | 0                | 0               | 0                  | 74               | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 0                  | 0              | 0           | 0         | 0                 | 0                | 0                   | 5896.31           | 0              | 0       | 0              | 0         | 0               | 0           | 5896.31            | 0               | 0                         | 
| 1000359973    | 1578501896 | 10             | Physicians                                    | MCGRADY DOUGLAS                | 616144823 | 80             | Peoria           |                     |                       | 0                 | 0      | Pathology            | 0                      | 0                  | 0                  | 2         | 0      | 0        | 0              | 0           | 0         | 0                 | 2948             | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 2           | 0        | 0          | 0                | 0             | 0           | 0                   | 10904              | 0                     | 0                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 2        | 0     | 0       | 0             | 0          | 0        | 0                | 10904           | 0                  | 0                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 11.86     | 0      | 0                  | 0              | 0           | 0         | 0                 | 48777.06         | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 48788.92           | 0               | 0                         | 
| 1000237764    |            | 10             | Physicians                                    |                                |           | 200            | Cook             |                     |                       | 0                 | 0      | Internal Medicine    | 0                      | 0                  | 0                  | 0         | 0      | 0        | 0              | 0           | 0         | 0                 | 0                | 0                   | 4                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 0          | 0                | 0             | 0           | 0                   | 0                  | 0                     | 8                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 0       | 0             | 0          | 0        | 0                | 0               | 0                  | 8                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 0                  | 0              | 0           | 0         | 0                 | 0                | 0                   | 124               | 0              | 0       | 0              | 0         | 0               | 0           | 124                | 0               | 0                         | 
| 1000016634    | 1972679355 | 10             | Physicians                                    | EGBUJIOBI LEO                  | 535111842 | 852            | Wisconsin        |                     |                       | 0                 | 0      | Emergency Medicine   | 0                      | 0                  | 0                  | 0         | 0      | 0        | 0              | 0           | 0         | 0                 | 2                | 0                   | 35                | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 0          | 0                | 0             | 0           | 0                   | 8                  | 0                     | 132                 | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 0       | 0             | 0          | 0        | 0                | 8               | 0                  | 132              | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 0                  | 0              | 0           | 0         | 0                 | 86.53            | 0                   | 3302.47           | 0              | 0       | 0              | 0         | 0               | 0           | 3389               | 0               | 0                         | 
| 1000193167    |            | 10             | Physicians                                    |                                |           | 200            | Cook             |                     |                       | 0                 | 0      | Obstetric-Gynecology | 0                      | 0                  | 0                  | 0         | 0      | 0        | 0              | 0           | 0         | 0                 | 0                | 0                   | 1                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 0          | 0                | 0             | 0           | 0                   | 0                  | 0                     | 1                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 0       | 0             | 0          | 0        | 0                | 0               | 0                  | 1                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 0                  | 0              | 0           | 0         | 0                 | 0                | 0                   | 24.25             | 0              | 0       | 0              | 0         | 0               | 0           | 24.25              | 0               | 0                         | 
| 1000104360    |            | 92             | Waiver service provider--Disability (DHS/DRS) |                                |           | 200            | Cook             |                     |                       | 0                 | 0      |                      | 0                      | 0                  | 0                  | 0         | 0      | 2        | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 48         | 0                | 0             | 0           | 0                   | 0                  | 0                     | 0                   | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 48      | 0             | 0          | 0        | 0                | 0               | 0                  | 0                | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 17963.830000000002 | 0              | 0           | 0         | 0                 | 0                | 0                   | 0                 | 0              | 0       | 0              | 0         | 0               | 0           | 17963.830000000002 | 0               | 0                         | 
| 1000329589    | 1639153471 | 10             | Physicians                                    | CORBOY DANIEL                  | 601814828 | 30             | DuPage           |                     |                       | 0                 | 0      | Emergency Medicine   | 0                      | 0                  | 0                  | 0         | 0      | 0        | 0              | 0           | 0         | 0                 | 6                | 0                   | 840               | 0              | 0       | 0              | 0         | 0               | 0           | 0                        | 0                    | 0                    | 0           | 0        | 0          | 0                | 0             | 0           | 0                   | 7                  | 0                     | 926                 | 0                | 0         | 0                | 0           | 0                 | 0             | 0                     | 0                 | 0                 | 0        | 0     | 0       | 0             | 0          | 0        | 0                | 7               | 0                  | 926              | 0             | 0      | 0             | 0        | 0              | 0          | 0                      | 0                  | 0                  | 0         | 0      | 0                  | 0              | 0           | 0         | 0                 | 224.91           | 0                   | 29041.41          | 0              | 0       | 0              | 0         | 0               | 0           | 29266.32           | 2               | 0                         | 
```