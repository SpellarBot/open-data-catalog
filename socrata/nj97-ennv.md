# IEPA Groundwater Ordinance Reviews

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iepa-groundwater-ordinance-reviews-d5a97) |
| Metadata | [Link](https://data.illinois.gov/api/views/nj97-ennv) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/nj97-ennv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/nj97-ennv/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | nj97-ennv |
| Name | IEPA Groundwater Ordinance Reviews |
| Attribution | Lorraine Robinson |
| Category | Environment |
| Tags | gw ordinance, environment, iepa |
| Created | 2012-01-13T16:53:03Z |
| Publication Date | 2012-01-13T17:01:45Z |

## Description

The Groundwater Ordinance Status Chart is an informal listing of the groundwater ordinances reviewed for suitability as environmental institutional controls under 35 Ill. Adm. Code 742.1015.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       |                | id                | ID                | text      | number      |
| Yes      | series tag     | county            | County            | text      | text        |
| Yes      | series tag     | countyfips        | CountyFIPS        | text      | text        |
| Yes      | series tag     | cityfips          | CityFIPS          | text      | text        |
| Yes      | series tag     | countycityfips    | CountyCityFIPS    | text      | text        |
| Yes      | numeric metric | bolregion         | BOLRegion         | number    | text        |
| Yes      | series tag     | municipality      | Municipality      | text      | text        |
| Yes      | series tag     | internaldocid     | InternalDocID     | text      | text        |
| Yes      | series tag     | lpc               | LPC Number        | text      | text        |
| Yes      | series tag     | citation          | Citation          | text      | text        |
| Yes      | series tag     | ordinance         | Ordinance         | text      | text        |
| Yes      | time           | date_dlc_complete | Date DLC Complete | date      | date        |
| Yes      | series tag     | comments          | Comments          | text      | text        |
| No       |                | review_date       | Review Date       | date      | date        |
```

## Time Field

```ls
Value = date_dlc_complete
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,review_date
```

## Data Commands

```ls
series e:nj97-ennv d:1999-06-16T07:00:00.000Z t:ordinance=6376 t:countyfips=119 t:countycityfips=119010 t:county=Madison t:municipality=Alton t:internaldocid=99061004 t:cityfips=010 t:comments="Ordinance approved subject to MOU.  MOU completed on 7/23/99. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of August 2006." m:bolregion=6

series e:nj97-ennv d:2001-01-09T08:00:00.000Z t:ordinance=2000-11-2 t:countyfips=031 t:countycityfips=031003 t:county=Cook t:municipality=Alsip t:internaldocid=00111501 t:cityfips=003 t:comments="Ordinance approved subject to MOU.  MOU completed on 1/9/01. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of August 2006." m:bolregion=2

series e:nj97-ennv d:1998-08-24T07:00:00.000Z t:ordinance=98-1009 t:countyfips=031 t:countycityfips=031012 t:county=Cook t:municipality="Bedford Park" t:internaldocid=98061901 t:cityfips=012 t:comments="Ordinance approved subject to MOU.  MOU completed on 8/24/98. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of August 2006." m:bolregion=2
```

## Meta Commands

```ls
metric m:bolregion p:integer l:BOLRegion t:dataTypeName=number

entity e:nj97-ennv l:"IEPA Groundwater Ordinance Reviews" t:attribution="Lorraine Robinson" t:url=https://data.illinois.gov/api/views/nj97-ennv

property e:nj97-ennv t:meta.view v:id=nj97-ennv v:category=Environment v:averageRating=0 v:name="IEPA Groundwater Ordinance Reviews" v:attribution="Lorraine Robinson"

property e:nj97-ennv t:meta.view.owner v:id=9fir-prid v:screenName="Greg Sullivan" v:displayName="Greg Sullivan"

property e:nj97-ennv t:meta.view.tableauthor v:id=9fir-prid v:screenName="Greg Sullivan" v:displayName="Greg Sullivan"
```

## Top Records

```ls
| id | county  | countyfips | cityfips | countycityfips | bolregion | municipality | internaldocid | lpc | citation                                 | ordinance | date_dlc_complete | comments                                                                                                                                                                                                                                                                                                                                           | review_date | 
| == | ======= | ========== | ======== | ============== | ========= | ============ | ============= | === | ======================================== | ========= | ================= | ================================================================================================================================================================================================================================================================================================================================================== | =========== | 
| 1  | Madison | 119        | 010      | 119010         | 6         | Alton        | 99061004      |     |                                          | 6376      | 929516400         | Ordinance approved subject to MOU. MOU completed on 7/23/99. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of August 2006.                                                                              | 1149058800  | 
| 2  | Cook    | 031        | 003      | 031003         | 2         | Alsip        | 00111501      |     |                                          | 2000-11-2 | 979027200         | Ordinance approved subject to MOU. MOU completed on 1/9/01. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of August 2006.                                                                               | 1149058800  | 
| 3  | Cook    | 031        | 012      | 031012         | 2         | Bedford Park | 98061901      |     |                                          | 98-1009   | 903942000         | Ordinance approved subject to MOU. MOU completed on 8/24/98. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of August 2006.                                                                              | 1149058800  | 
| 4  | Cook    | 031        | 015      | 031015         | 2         | Bellwood     | 98111001      |     | Code of Ordinances: Sec. 35-6.1          |           | 910857600         | Ordinance no longer effective as of 5/20/10. Replaced by ordinance # 10-46. Ordinance approved subject to MOU. MOU completed on 11/12/98. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of August 2006. | 1149058800  | 
| 5  | Cook    | 031        | 024      | 031024         | 2         | Blue Island  | 00040403      |     |                                          | 2000-295  | 960793200         | Ordinance approved subject to MOU. MOU completed on 6/12/00. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of May 2006.                                                                                 | 1149058800  | 
| 6  | Cook    | 031        | 027      | 031027         | 2         | Bridgeview   | 00071202      |     | Section 13-1-19, Mun. Code of Bridgeview | 99-33     | 963990000         | Ordinance approved. No MOU required. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of August 2006.                                                                                                      | 1149058800  | 
| 7  | Cook    | 031        | 030      | 031030         | 2         | Broadview    | 01030609      |     |                                          | 2000-10   | 987577200         | Ordinance approved. No MOU required. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of April 2010.                                                                                                       | 1149058800  | 
| 8  | Cook    | 031        | 036      | 031036         | 2         | Burnham      | 00073101      |     |                                          | 99-O-007  | 966927600         | Ordinance approved subject to MOU. MOU completed on 8/22/00. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of August 2010.                                                                              |             | 
| 9  | Cook    | 031        | 600      | 031600         | 2         | Chicago      | 97070701      |     | Chic. Mun. Code: 11-8-390                |           | 863593200         | Ordinance approved subject to MOU. MOU completed on 7/3/97.                                                                                                                                                                                                                                                                                        | 1149058800  | 
| 10 | Cook    | 031        | 051      | 031051         | 2         | Cicero       | 97112501      |     |                                          |           | 880444800         | Ordinance approved subject to MOU. MOU completed on 12/17/97. The Agency's survey of approved groundwater ordinances confirms that this ordinance remains valid for use as an environmental institutional control pursuant to 35 Ill. Adm. Code 742 as of April 2010.                                                                              |             | 
```