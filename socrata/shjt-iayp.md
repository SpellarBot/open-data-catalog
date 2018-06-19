# WDFW-References

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wdfw-references-ee4e5) |
| Metadata | [Link](https://data.wa.gov/api/views/shjt-iayp) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/shjt-iayp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/shjt-iayp/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | shjt-iayp |
| Name | WDFW-References |
| Attribution | Washington Department of Fish and Wildlife |
| Category | Natural Resources & Environment |
| Tags | wdfw |
| Created | 2013-07-15T22:34:48Z |
| Publication Date | 2015-10-21T18:43:47Z |

## Description

A list of references used in the Salmon Conservation Reporting Engine (SCoRE)

## Columns

```ls
| Included | Schema Type | Field Name            | Name           | Data Type | Render Type |
| ======== | =========== | ===================== | ============== | ========= | =========== |
| No       | time        | :updated_at           | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | reference_name        | Reference Name | text      | text        |
| Yes      | series tag  | reference_description | Description    | text      | text        |
| Yes      | series tag  | reference_link        | Link           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:shjt-iayp d:2013-07-15T15:34:50.000Z t:reference_description="Puget Sound Indian Tribes and Washington Department of Fish and Wildlife. 2010. Revised Comprehensive management plan for Puget Sound Chinook:  harvest management  component." t:reference_link=http://wdfw.wa.gov/conservation/fisheries/chinook/ t:reference_name="Ref 2" m:row_number.shjt-iayp=1

series e:shjt-iayp d:2013-07-15T15:34:50.000Z t:reference_description="Washington Department of Fish and Wildlife, Puyallup Tribe of Indians, and Muckleshoot Indian Tribe. 1996. Recovery plan for White River spring chinook salmon. Report. Available from Washington Department of Fish and Wildlife, Olympia, WA." t:reference_name="Ref 3" m:row_number.shjt-iayp=2

series e:shjt-iayp d:2013-07-15T15:34:50.000Z t:reference_description="Washington Department of Fish and Wildlife. 2007. North of Falcon preseason forecast: Chinook http://wdfw.wa.gov/fish/northfalcon/chinook.htm" t:reference_link=http://wdfw.wa.gov/fishing/northfalcon/ t:reference_name="Ref 4" m:row_number.shjt-iayp=3
```

## Meta Commands

```ls
metric m:row_number.shjt-iayp p:long l:"Row Number"

entity e:shjt-iayp l:WDFW-References t:attribution="Washington Department of Fish and Wildlife" t:url=https://data.wa.gov/api/views/shjt-iayp

property e:shjt-iayp t:meta.view v:id=shjt-iayp v:category="Natural Resources & Environment" v:averageRating=0 v:name=WDFW-References v:attribution="Washington Department of Fish and Wildlife"

property e:shjt-iayp t:meta.view.owner v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:displayName="WDFW Data"

property e:shjt-iayp t:meta.view.tableauthor v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:roleName=publisher v:displayName="WDFW Data"
```

## Top Records

```ls
| :updated_at | reference_name | reference_description                                                                                                                                                                                                                                                                                  | reference_link                                                                                         | 
| =========== | ============== | ====================================================================================================================================================================================================================================================================================================== | ====================================================================================================== | 
| 1373902490  | Ref 2          | Puget Sound Indian Tribes and Washington Department of Fish and Wildlife. 2010. Revised Comprehensive management plan for Puget Sound Chinook: harvest management component.                                                                                                                           | http://wdfw.wa.gov/conservation/fisheries/chinook/                                                     | 
| 1373902490  | Ref 3          | Washington Department of Fish and Wildlife, Puyallup Tribe of Indians, and Muckleshoot Indian Tribe. 1996. Recovery plan for White River spring chinook salmon. Report. Available from Washington Department of Fish and Wildlife, Olympia, WA.                                                        |                                                                                                        | 
| 1373902490  | Ref 4          | Washington Department of Fish and Wildlife. 2007. North of Falcon preseason forecast: Chinook http://wdfw.wa.gov/fish/northfalcon/chinook.htm                                                                                                                                                          | http://wdfw.wa.gov/fishing/northfalcon/                                                                | 
| 1373902490  | Ref 5          | Ames, J.J. 1984. Puget Sound chum salmon escapement estimates using spawner curve methodology. In Proceedings of the Workshop on Stream Indexing for Salmon Escapement Estimation. Edited by P.E.K. Symons and M. Waldichuk. Canadian Technical Reports in Fishery and Aquatic Sciences. 1326:133-148. | http://www.dfo-mpo.gc.ca/Library/38315.pdf                                                             | 
| 1373902490  | Ref 6          | Comprehensive Coho Workgroup. 1998. Comprehensive Coho Management Plan, Second Interim Report. Puget Sound Treaty Tribes and Washington Department of Fish and Wildlife, Olympia, WA. 74 pp.                                                                                                           | http://wdfw.wa.gov/publications/00973/wdfw00973.pdf                                                    | 
| 1373902490  | Ref 7          | Zillges, G. 1977. Methodology for determining Puget Sound coho escapement goals, escapement estimates, 1977 pre-season run size prediction, and in-season run assessment. WDF Tech Rpt 28, WDFW, Olympia WA.                                                                                           |                                                                                                        | 
| 1373902490  | Ref 8          | Yakama Indian Nation and Washington Department of Fish and Wildlife. 2004. Klickitat Subbasin Anadromous Fishery Master Plan. Prepared for the Northwest Power Planning and Conservation Council. 172 pp.                                                                                              | http://www.efw.bpa.gov/IntegratedFWP/KlickitatPlan110804web.pdf                                        | 
| 1373902490  | Ref 9          | Washington Department of Fish and Wildlife and Point-No-Point Treaty Tribes. 2000. Summer chum salmon conservation initiative. Olympia, WA. 256 pp.                                                                                                                                                    | http://wdfw.wa.gov/publications/00155/wdfw00155.pdf                                                    | 
| 1373902490  | Ref 10         | Pacific Fishery Management Council. 2007. 2006 Review of Ocean Salmon Fisheries. PFMC, Portland, OR.                                                                                                                                                                                                   | http://www.pcouncil.org/wp-content/uploads/salsafe06.pdf                                               | 
| 1373902490  | Ref 11         | McIsaac, Don. 1990. Factors affecting the abundance of 1977-79 brood wild fall Chinook salmon in the North Fork Lewis River, Washington. Ph.D. dissertation. University of Washington, Seattle.                                                                                                        | http://uwashington.worldcat.org/oclc/24536414&referer=brief_results (link only, must request document) | 
```