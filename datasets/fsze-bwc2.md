# Foreclosure data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/test-api) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/fsze-bwc2) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/fsze-bwc2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/fsze-bwc2/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | fsze-bwc2 |
| Name | Foreclosure data |
| Attribution | King County Finance and Business Operations |
| Category | Operations |
| Tags | foreclosure |
| Created | 2015-03-06T18:33:08Z |
| Publication Date | 2015-03-06T18:42:09Z |

## Description

Dataset for foreclosure data from mainframe

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | accountnumber    | AccountNumber    | text      | text        |
| Yes      | series tag     | legaldescription | LegalDescription | text      | text        |
| Yes      | numeric metric | land             | Land             | money     | text        |
| Yes      | numeric metric | imps             | Imps             | money     | text        |
| Yes      | series tag     | lot              | Lot              | text      | text        |
| Yes      | series tag     | block            | Block            | text      | text        |
| Yes      | series tag     | url              | Url              | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fsze-bwc2 d:2015-11-19T06:23:47.000Z t:lot=PORTION t:accountnumber=000720003102 t:url="http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=000720003102" t:legaldescription="H H TOBIN DONATION CLAIM #37 E 55 FT OF PORTION OF H.H. TOBIN DONATION CLAIM IN NE QTR STR 18-23-05 DAF:" m:imps=119000 m:land=124000

series e:fsze-bwc2 d:2015-11-19T06:23:47.000Z t:block=1 t:lot=25-26 t:accountnumber=003700014008 t:url="http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=003700014008" t:legaldescription="ADAMS HEIGHTS ADD W 30 FT OF 25 & ALL 26" m:imps=68000 m:land=195000

series e:fsze-bwc2 d:2015-11-19T06:23:47.000Z t:lot=99 t:accountnumber=010060099008 t:url="http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=010060099008" t:legaldescription="ALDER GROVE" m:imps=150000 m:land=58000
```

## Meta Commands

```ls
metric m:land p:long l:Land t:dataTypeName=money

metric m:imps p:long l:Imps t:dataTypeName=money

entity e:fsze-bwc2 l:"Foreclosure data" t:attribution="King County Finance and Business Operations" t:url=https://data.kingcounty.gov/api/views/fsze-bwc2

property e:fsze-bwc2 t:meta.view v:id=fsze-bwc2 v:category=Operations v:attributionLink=http://www.kingcounty.gov/operations/Finance v:averageRating=0 v:name="Foreclosure data" v:attribution="King County Finance and Business Operations"

property e:fsze-bwc2 t:meta.view.license v:name="Public Domain"

property e:fsze-bwc2 t:meta.view.owner v:id=ac9q-tkna v:screenName="King County Treasury Foreclosures" v:displayName="King County Treasury Foreclosures"

property e:fsze-bwc2 t:meta.view.tableauthor v:id=ac9q-tkna v:screenName="King County Treasury Foreclosures" v:roleName=publisher v:displayName="King County Treasury Foreclosures"
```

## Top Records

```ls
| :updated_at | accountnumber | legaldescription                                                                                                     | land     | imps     | lot       | block | url                                                                                             | 
| =========== | ============= | ==================================================================================================================== | ======== | ======== | ========= | ===== | =============================================================================================== | 
| 1447914227  | 000720003102  | H H TOBIN DONATION CLAIM #37 E 55 FT OF PORTION OF H.H. TOBIN DONATION CLAIM IN NE QTR STR 18-23-05 DAF:             | $124,000 | $119,000 | PORTION   |       | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=000720003102, null] | 
| 1447914227  | 003700014008  | ADAMS HEIGHTS ADD W 30 FT OF 25 & ALL 26                                                                             | $195,000 | $68,000  | 25-26     | 1     | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=003700014008, null] | 
| 1447914227  | 010060099008  | ALDER GROVE                                                                                                          | $58,000  | $150,000 | 99        |       | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=010060099008, null] | 
| 1447914227  | 016100004007  | ALL AROUND VIEW ADD LOTS 3 & 4 ALSO E 20 FT OF LOTS 8 & 9 LESS POR FOR ST                                            | $156,000 | $239,000 | 3-4 & 8-9 | 2     | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=016100004007, null] | 
| 1447914227  | 024300059003  | ANTHONY HEIGHTS ADD BEG SW COR LOT 9 BLK 2 ANTHONY HGTS ADD TH E 135 FT TO TPOB TH CONTG E 135 FT TH S 65 FT TH E 60 | $17,000  |          | RES       |       | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=024300059003, null] | 
| 1447914227  | 024850033002  | APPLE ORCHARD THE CONDOMINIUM PCT OF VALUE 2.506                                                                     | $54,200  | $95,800  | UNIT6     | BLD G | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=024850033002, null] | 
| 1447914227  | 025200066006  | AQUA VISTA ESTATES ADD THE VAL OF EACH LOT INCL AN UND INT IN COMMUNITY PROP LESS C & M RTS                          | $104,000 |          | 67        |       | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=025200066006, null] | 
| 1447914227  | 029369054001  | ASPEN GROVE CONDOMINIUM PCT UND INT 1.13                                                                             | $19,600  | $86,400  | UNIT 305  | F     | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=029369054001, null] | 
| 1447914227  | 029371002006  | ASPEN GLEN DIV NO 02                                                                                                 | $46,000  |          | 2         |       | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=029371002006, null] | 
| 1447914227  | 038000095000  | BALATON CONDO HOMES CONDOMINIUM PCT UND INT 0.78                                                                     | $61,700  | $63,300  | UNIT 139  | L     | [http://info.kingcounty.gov/Assessor/eRealProperty/Dashboard.aspx?ParcelNbr=038000095000, null] | 
```