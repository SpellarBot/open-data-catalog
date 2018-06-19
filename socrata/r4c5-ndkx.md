# Lot Cleaning Dispositions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/lot-cleaning-dispositions) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/r4c5-ndkx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/r4c5-ndkx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/r4c5-ndkx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | r4c5-ndkx |
| Name | Lot Cleaning Dispositions |
| Attribution | Department of Sanitation (DSNY) |
| Category | City Government |
| Created | 2016-03-29T15:39:17Z |
| Publication Date | 2016-03-29T15:40:49Z |

## Description

Dispositions of Lots for which cleaning requests were received, with DSNY clean-up cost where applicable.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag     | lotid                       | LotId                       | text      | text        |
| Yes      | series tag     | inspectionrequestid         | InspectionRequestId         | text      | text        |
| Yes      | series tag     | lotno                       | LotNo                       | text      | text        |
| Yes      | numeric metric | privateind                  | PrivateInd                  | number    | text        |
| Yes      | series tag     | areaid                      | AreaId                      | text      | text        |
| Yes      | series tag     | lotstatusid                 | LotStatusId                 | text      | text        |
| No       |                | lotstatusdate               | LotStatusDate               | text      | text        |
| Yes      | numeric metric | lotstatusreason             | LotStatusReason             | number    | text        |
| Yes      | series tag     | operid                      | OperId                      | text      | text        |
| No       |                | lotentrydate                | LotEntryDate                | text      | text        |
| No       |                | billingdate                 | BillingDate                 | text      | text        |
| Yes      | numeric metric | lotbllingtotal              | LotBllingTotal              | number    | text        |
| Yes      | numeric metric | overriteind                 | OverriteInd                 | number    | text        |
| Yes      | numeric metric | perimeter_ind               | perimeter_ind               | number    | text        |
| Yes      | numeric metric | fivedayletterno             | FiveDayLetterNo             | number    | text        |
| Yes      | series tag     | notes                       | Notes                       | text      | text        |
| Yes      | series tag     | psid                        | PSId                        | text      | text        |
| Yes      | series tag     | dupccu                      | DupCCU                      | text      | text        |
| Yes      | series tag     | activityid                  | ActivityId                  | text      | text        |
| No       |                | noofaddresses               | NoOfAddresses               | number    | text        |
| Yes      | series tag     | refno                       | RefNo                       | text      | text        |
| Yes      | series tag     | lotnjinspectionrequestid    | LotNJInspectionRequestId    | text      | text        |
| Yes      | series tag     | lotdupinspectionrequestid   | LotDupInspectionRequestId   | text      | text        |
| Yes      | numeric metric | lotissysflageddupoverridden | LotIsSysFlagedDupOverridden | number    | text        |
| Yes      | numeric metric | lotissysflagednjoverridden  | LotIsSysFlagedNJOverridden  | number    | text        |
| Yes      | series tag     | lotprevstatusidbfrdupornj   | LotPrevStatusIdBfrDupOrNJ   | text      | text        |
| Yes      | series tag     | legalnotes                  | LegalNotes                  | text      | text        |
| Yes      | series tag     | fieldnotes                  | FieldNotes                  | text      | text        |
| Yes      | series tag     | supp_ind                    | supp_ind                    | text      | text        |
| Yes      | series tag     | old_lot_id                  | Old_lot_id                  | text      | text        |
| Yes      | series tag     | old_status_dd               | Old_status_dd               | text      | text        |
| Yes      | series tag     | old_status_rea_dd           | Old_status_rea_dd           | text      | text        |
| Yes      | series tag     | lotconversion_notes         | LotConversion_Notes         | text      | text        |
| Yes      | series tag     | ownerlotlcd                 | OwnerLotLCD                 | text      | text        |
| Yes      | series tag     | logno                       | logno                       | text      | text        |
| Yes      | series tag     | indexno                     | Indexno                     | text      | text        |
| No       |                | refferedtodohmhdate         | RefferedToDOHMHDate         | text      | text        |
| Yes      | numeric metric | structure                   | Structure                   | number    | text        |
| Yes      | series tag     | activitydetailid            | ActivityDetailId            | text      | text        |
| Yes      | series tag     | titleid                     | TitleId                     | text      | text        |
| Yes      | numeric metric | hours                       | Hours                       | number    | text        |
| Yes      | numeric metric | operatorid_detail           | OperatorId_Detail           | number    | text        |
| No       |                | detailentrydate             | DetailEntryDate             | text      | text        |
| Yes      | series tag     | dumpsiteid                  | DumpSiteId                  | text      | text        |
| Yes      | series tag     | vehicleno                   | VehicleNo                   | text      | text        |
| No       |                | act_date                    | Act_Date                    | text      | text        |
| No       |                | activityentrydate           | ActivityEntryDate           | text      | text        |
| Yes      | numeric metric | abandonedcars               | AbandonedCars               | number    | text        |
| Yes      | series tag     | activitystatusid            | ActivityStatusID            | text      | text        |
| No       |                | enddate                     | EndDate                     | text      | text        |
| Yes      | numeric metric | activitybllingtotal         | ActivityBllingTotal         | number    | text        |
| No       |                | activitystatusdate          | ActivityStatusDate          | text      | text        |
| Yes      | numeric metric | total_hrs                   | Total_hrs                   | number    | text        |
| Yes      | numeric metric | total_tonnage               | Total_tonnage               | number    | text        |
| Yes      | numeric metric | total_loads                 | Total_loads                 | number    | text        |
| Yes      | numeric metric | s_tires                     | S_tires                     | number    | text        |
| Yes      | numeric metric | l_tires                     | l_tires                     | number    | text        |
| Yes      | numeric metric | civilian_hrs                | civilian_hrs                | number    | text        |
| Yes      | numeric metric | fel_tires                   | fel_tires                   | number    | text        |
| Yes      | numeric metric | uniform_hrs                 | uniform_hrs                 | number    | text        |
| Yes      | series tag     | old_main_lot_id             | Old_Main_lot_id             | text      | text        |
| No       |                | startdate                   | StartDate                   | text      | text        |
| Yes      | series tag     | act_old_lot_id              | Act_Old_lot_id              | text      | text        |
| Yes      | numeric metric | lotcleaningtotal            | LotCleaningTotal            | number    | text        |
| Yes      | numeric metric | salestax                    | SalesTax                    | number    | text        |
| Yes      | numeric metric | isbillgenerated             | IsBillGenerated             | number    | text        |
| Yes      | numeric metric | prefix                      | Prefix                      | number    | text        |
| Yes      | series tag     | house1                      | House1                      | text      | text        |
| Yes      | series tag     | house2                      | House2                      | text      | text        |
| Yes      | series tag     | streetaddress               | StreetAddress               | text      | text        |
| No       |                | requestdate                 | RequestDate                 | text      | text        |
| Yes      | series tag     | lastname                    | LastName                    | text      | text        |
| Yes      | series tag     | firstname                   | FirstName                   | text      | text        |
| Yes      | series tag     | boroid                      | BoroId                      | text      | text        |
| Yes      | series tag     | districtid                  | DistrictId                  | text      | text        |
| Yes      | series tag     | note                        | Note                        | text      | text        |
| Yes      | series tag     | ccuyear                     | CCUYear                     | text      | text        |
| Yes      | numeric metric | ccuno                       | CCUNo                       | number    | text        |
| Yes      | series tag     | userid                      | UserId                      | text      | text        |
| No       |                | requestentrydate            | RequestEntryDate            | text      | text        |
| Yes      | series tag     | refid                       | RefId                       | text      | text        |
| Yes      | series tag     | requestsourceid             | RequestSourceId             | text      | text        |
| Yes      | series tag     | scanno                      | ScanNo                      | text      | text        |
| Yes      | numeric metric | isdeleted                   | IsDeleted                   | number    | text        |
| Yes      | series tag     | assignedtoinspector         | AssignedToInspector         | text      | text        |
| Yes      | series tag     | crossstreetone              | CrossStreetOne              | text      | text        |
| Yes      | series tag     | crossstreettwo              | CrossStreettwo              | text      | text        |
| Yes      | numeric metric | channel                     | Channel                     | number    | text        |
| Yes      | numeric metric | program                     | Program                     | number    | text        |
| Yes      | numeric metric | area                        | Area                        | number    | text        |
| Yes      | series tag     | crmno                       | CRMNo                       | text      | text        |
| Yes      | series tag     | phone                       | Phone                       | text      | text        |
| Yes      | numeric metric | coordinatex                 | CoordinateX                 | number    | text        |
| Yes      | numeric metric | coordinatey                 | CoordinateY                 | number    | text        |
| Yes      | series tag     | segmentid                   | SegmentId                   | text      | text        |
| Yes      | numeric metric | bin                         | Bin                         | number    | text        |
| Yes      | series tag     | block                       | Block                       | text      | text        |
| Yes      | series tag     | requeststatusid             | RequestStatusID             | text      | text        |
| Yes      | numeric metric | requeststatusreason         | RequestStatusReason         | number    | text        |
| No       |                | requeststatusdate           | RequestStatusDate           | text      | text        |
| Yes      | numeric metric | flp                         | FLP                         | number    | text        |
| No       |                | inspectiondate              | InspectionDate              | text      | text        |
| Yes      | series tag     | inspectorfindings           | InspectorFindings           | text      | text        |
| Yes      | series tag     | isduplicate                 | IsDuplicate                 | text      | text        |
| Yes      | numeric metric | used_prefix                 | Used_Prefix                 | number    | text        |
| Yes      | series tag     | used_house1                 | Used_House1                 | text      | text        |
| Yes      | series tag     | used_house2                 | Used_House2                 | text      | text        |
| Yes      | series tag     | used_streetaddress          | Used_StreetAddress          | text      | text        |
| Yes      | series tag     | used_crossstreetone         | Used_CrossStreetOne         | text      | text        |
| Yes      | series tag     | used_crossstreettwo         | Used_CrossStreetTwo         | text      | text        |
| Yes      | series tag     | dupinspectionrequestid      | DupInspectionRequestId      | text      | text        |
| Yes      | series tag     | njinspectionrequestid       | NJInspectionRequestId       | text      | text        |
| Yes      | numeric metric | issysflageddupoverridden    | IsSysFlagedDupOverridden    | number    | text        |
| Yes      | numeric metric | issysflagednjoverridden     | IsSysFlagedNJOverridden     | number    | text        |
| Yes      | numeric metric | zone                        | Zone                        | number    | text        |
| Yes      | numeric metric | importfromscan              | ImportFromScan              | number    | text        |
| No       |                | copyexistingaddress         | CopyExistingAddress         | number    | text        |
| Yes      | series tag     | old_inspect_id              | Old_Inspect_ID              | text      | text        |
| Yes      | series tag     | block_loc                   | Block_loc                   | text      | text        |
| Yes      | series tag     | used_block_loc              | Used_Block_loc              | text      | text        |
| Yes      | series tag     | loc_id                      | loc_id                      | text      | text        |
| Yes      | series tag     | requestconversion_notes     | RequestConversion_Notes     | text      | text        |
| Yes      | numeric metric | originaloverride            | OriginalOverride            | number    | text        |
| Yes      | numeric metric | usedoverride                | UsedOverride                | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = lotstatusdate,lotentrydate,billingdate,noofaddresses,refferedtodohmhdate,detailentrydate,act_date,activityentrydate,enddate,activitystatusdate,startdate,requestdate,requestentrydate,requeststatusdate,inspectiondate,copyexistingaddress
```

## Data Commands

```ls
series e:r4c5-ndkx d:2016-04-07T10:44:21.000Z t:activitystatusid=750 t:inspectionrequestid=9121 t:userid=608 t:block=03461 t:lotid=104327 t:titleid=49 t:used_block_loc="B/T  50 & 40  GRANITE ST." t:old_lot_id=LOT25511 t:boroid=7 t:operid=332 t:act_old_lot_id=LOT25509 t:assignedtoinspector=N t:activitydetailid=197329 t:lotstatusid=702 t:old_main_lot_id=LOT25509 t:ccuyear=99 t:activityid=34722 t:areaid=39 t:requestsourceid=502 t:vehicleno=AL-304 t:requestconversion_notes="PB STATUS = ASSIGNED TO INTAKE" t:loc_id=LOC11018 t:requeststatusid=1048 t:lotno=0026 t:lotconversion_notes="PB STATUS = COMPLETE;" t:districtid=20 t:old_status_dd=MST117 m:l_tires=0 m:privateind=682 m:abandonedcars=0 m:structure=0 m:total_loads=3 m:originaloverride=0 m:overriteind=1 m:hours=6.5 m:importfromscan=0 m:uniform_hrs=12 m:total_tonnage=11.6 m:flp=1 m:usedoverride=0 m:fel_tires=0 m:ccuno=9903091 m:total_hrs=0 m:area=39 m:s_tires=0 m:isdeleted=0 m:operatorid_detail=694 m:civilian_hrs=0 m:channel=929 m:zone=12 m:isbillgenerated=0

series e:r4c5-ndkx d:2016-04-07T10:44:21.000Z t:activitystatusid=750 t:inspectionrequestid=9492 t:userid=608 t:block=03031 t:lotid=108504 t:titleid=49 t:used_block_loc="B/T 2338 & 2352  WEBSTER AVE" t:old_lot_id=LOT29591 t:boroid=9 t:operid=332 t:act_old_lot_id=LOT29591 t:assignedtoinspector=N t:activitydetailid=195737 t:lotstatusid=702 t:old_main_lot_id=LOT29591 t:ccuyear=99 t:activityid=20155 t:areaid=39 t:requestsourceid=919 t:vehicleno=AC-110 t:requestconversion_notes="PB STATUS = ASSIGNED TO INTAKE" t:loc_id=LOC11243 t:requeststatusid=1048 t:lotno=0021 t:lotconversion_notes="PB STATUS = COMPLETE;" t:districtid=10 t:old_status_dd=MST117 m:l_tires=0 m:privateind=682 m:abandonedcars=0 m:structure=0 m:total_loads=29 m:originaloverride=0 m:overriteind=1 m:hours=6.5 m:importfromscan=0 m:uniform_hrs=68 m:total_tonnage=138.79 m:flp=1 m:usedoverride=0 m:fel_tires=0 m:ccuno=9903600 m:total_hrs=0 m:area=39 m:s_tires=0 m:program=30 m:isdeleted=0 m:operatorid_detail=694 m:civilian_hrs=0 m:channel=929 m:zone=7 m:isbillgenerated=0

series e:r4c5-ndkx d:2016-04-07T10:44:21.000Z t:activitystatusid=750 t:old_main_lot_id=LOT173157 t:lotstatusid=702 t:activitydetailid=122688 t:ccuyear=08 t:inspectionrequestid=75818 t:activityid=11703 t:userid=664 t:block=00035 t:areaid=39 t:used_block_loc="B/T  448 & 444 WESTERVELT AVE" t:titleid=49 t:lotid=65045 t:requestsourceid=502 t:old_lot_id=LOT173157 t:requestconversion_notes="PB STATUS = ASSIGNED TO INTAKE" t:boroid=10 t:loc_id=LOC78131 t:requeststatusid=1048 t:operid=332 t:lotconversion_notes="PB STATUS = COMPLETE;" t:lotno=0076 t:act_old_lot_id=LOT173157 t:districtid=57 t:assignedtoinspector=N t:old_status_dd=MST117 m:privateind=681 m:l_tires=0 m:abandonedcars=0 m:structure=0 m:originaloverride=0 m:total_loads=0 m:overriteind=1 m:hours=2 m:importfromscan=0 m:fivedayletterno=1 m:uniform_hrs=12 m:lotbllingtotal=392.62 m:total_tonnage=0 m:salestax=34.85 m:flp=0 m:usedoverride=0 m:ccuno=806304 m:fel_tires=0 m:lotcleaningtotal=392.62 m:total_hrs=0 m:area=39 m:s_tires=0 m:activitybllingtotal=427.47 m:isdeleted=0 m:operatorid_detail=693 m:civilian_hrs=0 m:channel=867 m:zone=11 m:isbillgenerated=1
```

## Meta Commands

```ls
metric m:privateind p:integer l:PrivateInd t:dataTypeName=number

metric m:lotstatusreason p:integer l:LotStatusReason t:dataTypeName=number

metric m:lotbllingtotal p:float l:LotBllingTotal t:dataTypeName=number

metric m:overriteind p:integer l:OverriteInd t:dataTypeName=number

metric m:perimeter_ind p:integer l:perimeter_ind t:dataTypeName=number

metric m:fivedayletterno p:integer l:FiveDayLetterNo t:dataTypeName=number

metric m:lotissysflageddupoverridden p:integer l:LotIsSysFlagedDupOverridden t:dataTypeName=number

metric m:lotissysflagednjoverridden p:integer l:LotIsSysFlagedNJOverridden t:dataTypeName=number

metric m:structure p:integer l:Structure t:dataTypeName=number

metric m:hours p:float l:Hours t:dataTypeName=number

metric m:operatorid_detail p:integer l:OperatorId_Detail t:dataTypeName=number

metric m:abandonedcars p:integer l:AbandonedCars t:dataTypeName=number

metric m:activitybllingtotal p:float l:ActivityBllingTotal t:dataTypeName=number

metric m:total_hrs p:float l:Total_hrs t:dataTypeName=number

metric m:total_tonnage p:float l:Total_tonnage t:dataTypeName=number

metric m:total_loads p:float l:Total_loads t:dataTypeName=number

metric m:s_tires p:integer l:S_tires t:dataTypeName=number

metric m:l_tires p:integer l:l_tires t:dataTypeName=number

metric m:civilian_hrs p:integer l:civilian_hrs t:dataTypeName=number

metric m:fel_tires p:integer l:fel_tires t:dataTypeName=number

metric m:uniform_hrs p:integer l:uniform_hrs t:dataTypeName=number

metric m:lotcleaningtotal p:float l:LotCleaningTotal t:dataTypeName=number

metric m:salestax p:float l:SalesTax t:dataTypeName=number

metric m:isbillgenerated p:integer l:IsBillGenerated t:dataTypeName=number

metric m:prefix p:integer l:Prefix t:dataTypeName=number

metric m:ccuno p:integer l:CCUNo t:dataTypeName=number

metric m:isdeleted p:integer l:IsDeleted t:dataTypeName=number

metric m:channel p:integer l:Channel t:dataTypeName=number

metric m:program p:integer l:Program t:dataTypeName=number

metric m:area p:integer l:Area t:dataTypeName=number

metric m:coordinatex p:integer l:CoordinateX t:dataTypeName=number

metric m:coordinatey p:integer l:CoordinateY t:dataTypeName=number

metric m:bin p:integer l:Bin t:dataTypeName=number

metric m:requeststatusreason p:integer l:RequestStatusReason t:dataTypeName=number

metric m:flp p:integer l:FLP t:dataTypeName=number

metric m:used_prefix p:integer l:Used_Prefix t:dataTypeName=number

metric m:issysflageddupoverridden p:integer l:IsSysFlagedDupOverridden t:dataTypeName=number

metric m:issysflagednjoverridden p:integer l:IsSysFlagedNJOverridden t:dataTypeName=number

metric m:zone p:integer l:Zone t:dataTypeName=number

metric m:importfromscan p:integer l:ImportFromScan t:dataTypeName=number

metric m:originaloverride p:integer l:OriginalOverride t:dataTypeName=number

metric m:usedoverride p:integer l:UsedOverride t:dataTypeName=number

entity e:r4c5-ndkx l:"Lot Cleaning Dispositions" t:attribution="Department of Sanitation (DSNY)" t:url=https://data.cityofnewyork.us/api/views/r4c5-ndkx

property e:r4c5-ndkx t:meta.view v:id=r4c5-ndkx v:category="City Government" v:averageRating=0 v:name="Lot Cleaning Dispositions" v:attribution="Department of Sanitation (DSNY)"

property e:r4c5-ndkx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:r4c5-ndkx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | lotid  | inspectionrequestid | lotno | privateind | areaid | lotstatusid | lotstatusdate       | lotstatusreason | operid | lotentrydate        | billingdate         | lotbllingtotal | overriteind | perimeter_ind | fivedayletterno | notes | psid | dupccu | activityid | noofaddresses | refno | lotnjinspectionrequestid | lotdupinspectionrequestid | lotissysflageddupoverridden | lotissysflagednjoverridden | lotprevstatusidbfrdupornj | legalnotes | fieldnotes | supp_ind | old_lot_id | old_status_dd | old_status_rea_dd | lotconversion_notes   | ownerlotlcd | logno | indexno | refferedtodohmhdate | structure | activitydetailid | titleid | hours | operatorid_detail | detailentrydate     | dumpsiteid | vehicleno | act_date            | activityentrydate   | abandonedcars | activitystatusid | enddate             | activitybllingtotal | activitystatusdate  | total_hrs | total_tonnage | total_loads | s_tires | l_tires | civilian_hrs | fel_tires | uniform_hrs | old_main_lot_id | startdate           | act_old_lot_id | lotcleaningtotal | salestax | isbillgenerated | prefix | house1 | house2 | streetaddress   | requestdate | lastname | firstname | boroid | districtid | note                                              | ccuyear | ccuno   | userid | requestentrydate    | refid | requestsourceid | scanno | isdeleted | assignedtoinspector | crossstreetone  | crossstreettwo  | channel | program | area | crmno | phone      | coordinatex | coordinatey | segmentid | bin     | block | requeststatusid | requeststatusreason | requeststatusdate   | flp | inspectiondate      | inspectorfindings                                               | isduplicate | used_prefix | used_house1 | used_house2 | used_streetaddress | used_crossstreetone | used_crossstreettwo | dupinspectionrequestid | njinspectionrequestid | issysflageddupoverridden | issysflagednjoverridden | zone | importfromscan | copyexistingaddress | old_inspect_id | block_loc                                                     | used_block_loc                                                | loc_id   | requestconversion_notes        | originaloverride | usedoverride | 
| =========== | ====== | =================== | ===== | ========== | ====== | =========== | =================== | =============== | ====== | =================== | =================== | ============== | =========== | ============= | =============== | ===== | ==== | ====== | ========== | ============= | ===== | ======================== | ========================= | =========================== | ========================== | ========================= | ========== | ========== | ======== | ========== | ============= | ================= | ===================== | =========== | ===== | ======= | =================== | ========= | ================ | ======= | ===== | ================= | =================== | ========== | ========= | =================== | =================== | ============= | ================ | =================== | =================== | =================== | ========= | ============= | =========== | ======= | ======= | ============ | ========= | =========== | =============== | =================== | ============== | ================ | ======== | =============== | ====== | ====== | ====== | =============== | =========== | ======== | ========= | ====== | ========== | ================================================= | ======= | ======= | ====== | =================== | ===== | =============== | ====== | ========= | =================== | =============== | =============== | ======= | ======= | ==== | ===== | ========== | =========== | =========== | ========= | ======= | ===== | =============== | =================== | =================== | === | =================== | =============================================================== | =========== | =========== | =========== | =========== | ================== | =================== | =================== | ====================== | ===================== | ======================== | ======================= | ==== | ============== | =================== | ============== | ============================================================= | ============================================================= | ======== | ============================== | ================ | ============ | 
| 1460025861  | 104327 | 9121                | 0026  | 682        | 39     | 702         | 01/14/2000 00:00:01 |                 | 332    |                     |                     |                | 1           |               |                 |       |      |        | 34722      | 0             |       |                          |                           |                             |                            |                           |            |            |          | LOT25511   | MST117        |                   | PB STATUS = COMPLETE; |             |       |         |                     | 0         | 197329           | 49      | 6.50  | 694               | 01/18/2000 14:42:30 |            | AL-304    | 01/14/2000 00:00:00 | 01/18/2000 14:39:52 | 0             | 750              | 01/14/2000 00:00:00 |                     | 11/02/2010 14:55:59 | 0.00      | 11.600        | 3.00        | 0       | 0       | 0            | 0         | 12          | LOT25509        | 01/14/2000 00:00:00 | LOT25509       |                  |          | 0               |        |        |        |                 |             |          |           | 7      | 20         |                                                   | 99      | 9903091 | 608    | 05/18/1999 10:32:12 |       | 502             |        | 0         | N                   |                 |                 | 929     |         | 39   |       |            |             |             |           |         | 03461 | 1048            |                     | 03/29/2011 16:02:34 | 1   | 05/03/1999 00:00:00 |                                                                 |             |             |             |             |                    |                     |                     |                        |                       |                          |                         | 12   | 0              |                     |                |                                                               | B/T 50 & 40 GRANITE ST.                                       | LOC11018 | PB STATUS = ASSIGNED TO INTAKE | 0                | 0            | 
| 1460025861  | 108504 | 9492                | 0021  | 682        | 39     | 702         | 12/24/1999 00:00:01 |                 | 332    |                     |                     |                | 1           |               |                 |       |      |        | 20155      | 0             |       |                          |                           |                             |                            |                           |            |            |          | LOT29591   | MST117        |                   | PB STATUS = COMPLETE; |             |       |         |                     | 0         | 195737           | 49      | 6.50  | 694               | 12/27/1999 08:49:57 |            | AC-110    | 12/21/1999 00:00:00 | 01/04/2000 11:57:56 | 0             | 750              | 12/24/1999 00:00:00 |                     | 11/02/2010 14:55:57 | 0.00      | 138.790       | 29.00       | 0       | 0       | 0            | 0         | 68          | LOT29591        | 12/17/1999 00:00:00 | LOT29591       |                  |          | 0               |        |        |        |                 |             |          |           | 9      | 10         |                                                   | 99      | 9903600 | 608    | 05/24/1999 09:50:06 |       | 919             |        | 0         | N                   |                 |                 | 929     | 30      | 39   |       |            |             |             |           |         | 03031 | 1048            |                     | 03/29/2011 16:02:34 | 1   | 03/17/1999 00:00:00 |                                                                 |             |             |             |             |                    |                     |                     |                        |                       |                          |                         | 7    | 0              |                     |                |                                                               | B/T 2338 & 2352 WEBSTER AVE                                   | LOC11243 | PB STATUS = ASSIGNED TO INTAKE | 0                | 0            | 
| 1460025861  | 65045  | 75818               | 0076  | 681        | 39     | 702         | 04/04/2008 00:00:01 |                 | 332    |                     | 05/15/2008 14:09:48 | 392.62         | 1           |               | 1               |       |      |        | 11703      | 1             |       |                          |                           |                             |                            |                           |            |            |          | LOT173157  | MST117        |                   | PB STATUS = COMPLETE; |             |       |         |                     | 0         | 122688           | 49      | 2.00  | 693               | 04/09/2008 14:33:10 |            |           | 04/04/2008 00:00:00 | 04/09/2008 00:00:00 | 0             | 750              | 04/04/2008 00:00:00 | 427.47              | 11/02/2010 14:55:56 | 0.00      | 0.000         | 0.00        | 0       | 0       | 0            | 0         | 12          | LOT173157       | 04/04/2008 00:00:00 | LOT173157      | 392.62           | 34.85    | 1               |        |        |        |                 |             |          |           | 10     | 57         |                                                   | 08      | 806304  | 664    | 03/03/2008 00:00:00 |       | 502             |        | 0         | N                   |                 |                 | 867     |         | 39   |       |            |             |             |           |         | 00035 | 1048            |                     | 03/29/2011 16:02:34 | 0   | 02/29/2008 00:00:00 |                                                                 |             |             |             |             |                    |                     |                     |                        |                       |                          |                         | 11   | 0              |                     |                |                                                               | B/T 448 & 444 WESTERVELT AVE                                  | LOC78131 | PB STATUS = ASSIGNED TO INTAKE | 0                | 0            | 
| 1460025861  | 196482 | 122191              | 0058  | 682        | 39     | 702         | 12/27/2013 00:00:00 |                 | 675    | 12/16/2013 07:05:02 | 12/16/2013 07:05:02 | 0.00           | 0           | 0             |                 |       | 0    |        | 46586      |               |       |                          |                           | 0                           | 0                          |                           |            |            |          |            |               |                   |                       |             |       |         |                     | 0         | 299667           | 49      | 6.50  | 694               | 03/05/2014 12:09:18 | 0          |           | 12/27/2013 00:00:00 | 03/05/2014 12:09:18 |               | 750              | 12/27/2013 00:00:00 |                     | 03/05/2014 12:09:18 | 0.00      | 1.590         | 1.00        | 0       | 0       | 0            | 0         | 78          |                 | 12/26/2013 00:00:00 |                | 0.00             | 0.00     | 0               | 600    | 415    |        | EAST 162 STREET |             |          |           | 9      | 7          | **                                                | 2013    | 1311626 | 686    | 12/03/2013 13:09:38 | 0     | 502             |        | 0         | N                   | DEAD END        | MELROSE AVENUE  | 867     | 0       | 0    |       | __________ | 1008338     | 239727      | 120963    | 2001531 | 02384 | 1048            |                     | 03/06/2014 00:02:17 | 0   | 12/03/2013 00:00:00 | ACCESSIBLE ON MELROSE,WEEDS,LITTER,BUXKETS,BOTTLES,CANS,DEBRIS. |             | 600         | 415         |             | EAST 162 STREET    | DEAD END            | MELROSE AVENUE      |                        |                       | 0                        | 0                       | 6    | 0              | 1                   |                | ADJ. 415 EAST 162 STREET betw DEAD END & MELROSE AVENUE       | ADJ. 415 EAST 162 STREET betw DEAD END & MELROSE AVENUE       |          |                                | 0                | 0            | 
| 1460025861  | 135852 | 20089               | 0014  | 682        | 39     | 702         | 08/27/2001 00:00:01 |                 | 332    |                     |                     |                | 1           |               |                 |       |      |        | 25725      | 0             |       |                          |                           |                             |                            |                           |            |            |          | LOT57590   | MST117        |                   | PB STATUS = COMPLETE; |             |       |         |                     | 0         | 234327           | 49      | 6.50  | 694               | 08/27/2001 09:35:12 |            | AB-006    | 08/24/2001 00:00:00 | 08/28/2001 00:00:00 | 0             | 750              | 08/27/2001 00:00:00 |                     | 11/02/2010 14:55:57 | 0.00      | 30.000        | 6.00        | 0       | 0       | 0            | 0         | 87          | LOT57584        | 08/23/2001 00:00:00 | LOT57584       |                  |          | 0               |        |        |        |                 |             |          |           | 9      | 7          |                                                   | 01      | 104114  | 623    | 06/11/2001 00:00:00 |       | 502             |        | 0         | N                   |                 |                 | 867     |         | 39   |       |            |             |             |           |         | 02929 | 1048            |                     | 03/29/2011 16:02:34 | 0   | 06/04/2001 00:00:00 |                                                                 |             |             |             |             |                    |                     |                     |                        |                       |                          |                         | 6    | 0              |                     |                |                                                               | ADJ. 3866 THIRD AVE                                           | LOC26991 | PB STATUS = ASSIGNED TO INTAKE | 0                | 0            | 
| 1460025861  | 37092  | 58854               | 0001  | 682        | 40     | 702         | 07/11/2006 00:00:01 |                 | 332    |                     |                     |                | 1           |               |                 |       |      |        | 6687       | 0             |       |                          |                           |                             |                            |                           |            |            |          | LOT145971  | MST117        |                   | PB STATUS = COMPLETE; |             |       |         |                     | 0         | 82749            | 49      | 6.50  | 694               | 07/12/2006 14:58:41 |            | CT-001    | 07/07/2006 00:00:00 | 07/12/2006 15:02:59 | 0             | 750              | 07/11/2006 00:00:00 |                     | 11/02/2010 14:55:54 | 0.00      | 4.680         | 1.00        | 0       | 0       | 0            | 0         | 120         | LOT145971       | 07/05/2006 00:00:00 | LOT145971      |                  |          | 0               |        |        |        |                 |             |          |           | 9      | 13         |                                                   | 06      | 607829  | 555    | 04/25/2006 09:24:35 |       | 502             |        | 0         | N                   |                 |                 | 867     |         | 40   |       |            |             |             |           |         | 03492 | 1048            |                     | 03/29/2011 16:02:34 | 1   | 04/24/2006 00:00:00 |                                                                 |             |             |             |             |                    |                     |                     |                        |                       |                          |                         | 7    | 0              |                     |                |                                                               | ADJ 1740 LACOMBE AVE                                          | LOC63467 | PB STATUS = ASSIGNED TO INTAKE | 0                | 0            | 
| 1460025861  | 109775 | 11185               | 0029  | 682        | 39     | 702         | 04/21/2000 00:00:01 |                 | 332    |                     |                     |                | 1           |               |                 |       |      |        | 20490      | 0             |       |                          |                           |                             |                            |                           |            |            |          | LOT30809   | MST117        |                   | PB STATUS = COMPLETE; |             |       |         |                     | 0         | 203482           | 49      | 5.50  | 694               | 04/27/2000 11:46:12 |            |           | 04/21/2000 00:00:00 | 04/27/2000 11:45:59 | 0             | 750              | 04/21/2000 00:00:00 |                     | 11/02/2010 14:55:57 | 0.00      | 15.800        | 3.00        | 0       | 0       | 0            | 0         | 14          | LOT30805        | 04/21/2000 00:00:00 | LOT30805       |                  |          | 0               |        |        |        |                 |             |          |           | 7      | 3          |                                                   | 99      | 9905673 | 469    | 08/24/1999 11:02:07 |       | 502             |        | 0         | N                   |                 |                 | 867     | 30      | 39   |       |            |             |             |           |         | 04004 | 1048            |                     | 03/29/2011 16:02:34 | 0   | 08/12/1999 00:00:00 |                                                                 |             |             |             |             |                    |                     |                     |                        |                       |                          |                         | 1    | 0              |                     |                |                                                               | NR. 387 ESSEX ST.                                             | LOC14055 | PB STATUS = ASSIGNED TO INTAKE | 0                | 0            | 
| 1460025861  | 86925  | 91973               | 0013  | 682        | 39     | 702         | 10/20/2009 00:00:01 |                 | 332    |                     |                     |                | 1           |               | 1               |       |      |        | 16198      | 0             |       |                          |                           |                             |                            |                           |            |            |          | LOT194592  | MST117        |                   | PB STATUS = COMPLETE; |             |       |         |                     | 0         | 154343           | 49      | 2.50  | 694               | 10/30/2009 07:39:59 |            |           | 10/20/2009 00:00:00 | 10/30/2009 00:00:00 | 0             | 750              | 10/20/2009 00:00:00 |                     | 11/02/2010 14:55:56 | 0.00      | 0.310         | 0.34        | 0       | 0       | 0            | 0         | 30          | LOT194588       | 10/20/2009 00:00:00 | LOT194588      |                  |          | 0               |        |        |        |                 |             |          |           | 8      | 56         |                                                   | 09      | 913740  | 336    | 10/16/2009 00:00:00 |       | 504             |        | 0         | N                   |                 |                 | 867     |         | 39   |       |            |             |             |           |         | 15967 | 1048            |                     | 03/29/2011 16:02:34 | 0   | 10/15/2009 00:00:00 |                                                                 |             |             |             |             |                    |                     |                     |                        |                       |                          |                         | 10   | 0              |                     |                |                                                               | ADJ 416 B 45 ST                                               | LOC91276 | PB STATUS = ASSIGNED TO INTAKE | 0                | 0            | 
| 1460025861  | 125105 | 14732               | 0225  | 681        | 40     | 702         | 12/28/2000 00:00:01 |                 | 332    |                     | 02/26/2002 11:01:52 | 697.86         | 1           |               |                 |       |      |        | 23447      |               |       |                          |                           |                             |                            |                           |            |            |          | LOT46059   | MST117        |                   | PB STATUS = COMPLETE; |             |       |         |                     | 0         | 220580           | 47      | 4.50  | 694               | 01/03/2001 10:28:08 |            |           | 12/28/2000 00:00:00 | 01/03/2001 10:27:23 | 0             | 750              | 12/28/2000 00:00:00 | 759.80              | 11/02/2010 14:55:57 | 0.00      | 0.400         | 1.00        | 0       | 0       | 18           | 0         | 9           | LOT46059        | 12/28/2000 00:00:00 | LOT46059       | 697.86           | 61.94    | 1               |        |        |        |                 |             |          |           | 8      | 55         |                                                   | 00      | 3365    | 478    | 03/16/2000 13:58:53 |       | 502             |        | 0         | N                   |                 |                 | 867     |         | 40   |       |            |             |             |           |         | 13268 | 1048            |                     | 03/29/2011 16:02:34 | 0   | 03/10/2000 00:00:00 |                                                                 |             |             |             |             |                    |                     |                     |                        |                       |                          |                         | 10   | 0              |                     |                |                                                               | B/T 166-05 & 166-11 144 AVE.                                  | LOC18164 | PB STATUS = ASSIGNED TO INTAKE | 0                | 0            | 
| 1460025861  | 188996 | 115120              | 0043  | 681        | 39     | 702         | 01/07/2013 00:00:00 |                 | 675    | 12/11/2012 10:54:10 | 02/19/2013 00:00:00 | 0.00           | 0           | 0             |                 |       | 0    |        | 43887      | 1             |       |                          |                           | 0                           | 0                          |                           |            |            | N        |            |               |                   |                       |             |       |         |                     | 0         | 284152           | 49      | 6.50  | 694               | 01/11/2013 15:00:25 | 0          |           | 01/07/2013 00:00:00 | 01/11/2013 15:00:25 |               | 750              | 01/07/2013 00:00:00 | 1210.29             | 01/11/2013 15:00:25 | 0.00      | 0.270         | 1.00        | 0       | 0       | 0            | 0         | 28          |                 | 01/07/2013 00:00:00 |                | 1111.63          | 98.66    | 1               | 679    | 600    |        | GRAND CONCOURSE |             |          |           | 9      | 8          | ACCESSIBLE,BLACK BAGS,BOTTELS,CANS,LITTER,DEBRIS. | 2012    | 1211516 | 685    | 12/06/2012 13:15:26 | 0     | 502             |        | 0         | N                   | EAST 151 STREET | EAST 150 STREET | 867     | 0       | 0    |       | __________ | 1004537     | 237970      | 69826     | 2002449 | 02443 | 1048            |                     | 01/10/2013 00:02:03 | 0   | 12/06/2012 00:00:00 | ACCESSIBLE,BLACK BAGS,BOTTLES,CANS,LITTER,DEBRIS.               |             | 679         | 600         |             | GRAND CONCOURSE    | EAST 151 STREET     | EAST 150 STREET     |                        |                       |                          |                         |      | 0              | 1                   |                | AT 600 GRAND CONCOURSE betw EAST 151 STREET & EAST 150 STREET | AT 600 GRAND CONCOURSE betw EAST 151 STREET & EAST 150 STREET |          |                                | 0                | 0            | 
```