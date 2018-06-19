# Current Small Business Enterprise, SBE, Certfied Vendors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-small-business-enterprise-sbe-certfied-vendors) |
| Metadata | [Link](https://data.austintexas.gov/api/views/uxwx-55kj) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/uxwx-55kj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/uxwx-55kj/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | uxwx-55kj |
| Name | Current Small Business Enterprise, SBE, Certfied Vendors |
| Attribution | City of Austin |
| Category | Financial |
| Tags | small business enterprise, sbe, small, business, enterprise, certified, certification, vendor, finance, smbr |
| Created | 2015-07-15T19:26:50Z |
| Publication Date | 2015-07-15T20:09:26Z |

## Description

This is a listing of the currently certified small business enterprises registered with the City of Austin.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | vendor_code       | VENDOR_CODE       | text      | text        |
| Yes      | series tag     | legal_name        | LEGAL_NAME        | text      | text        |
| Yes      | series tag     | alias             | ALIAS             | text      | text        |
| Yes      | series tag     | principle_contact | PRINCIPLE_CONTACT | text      | text        |
| Yes      | series tag     | email             | EMAIL             | text      | text        |
| Yes      | series tag     | phone             | PHONE             | text      | number      |
| Yes      | numeric metric | phone_ext         | PHONE_EXT         | number    | number      |
| Yes      | series tag     | fax               | FAX               | text      | number      |
| Yes      | numeric metric | fax_ext           | FAX_EXT           | number    | number      |
| Yes      | series tag     | street_1          | STREET_1          | text      | text        |
| Yes      | series tag     | street_2          | STREET_2          | text      | text        |
| Yes      | series tag     | city              | CITY              | text      | text        |
| Yes      | series tag     | state             | STATE             | text      | text        |
| Yes      | series tag     | zip               | ZIP               | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uxwx-55kj d:2015-07-15T12:26:56.000Z t:vendor_code=VS0000035929 t:legal_name="MILLARD DRYWALL & ACOUSTICAL CONSTRUCTION INC" t:zip=78760 t:phone=5124428110 t:street_1="PO BOX 18926" t:fax=5124428010 t:email=mmillard@millarddrywall.com t:principle_contact="Mary Millard" t:state=TX t:city=AUSTIN m:phone_ext=105

series e:uxwx-55kj d:2015-07-15T12:26:56.000Z t:vendor_code=ITG8318552 t:legal_name="I T GONZALEZ ENGINEERS" t:zip=78723-5815 t:phone=5124477400 t:street_1="3501 MANOR RD" t:fax=5124476389 t:email=itgonz@swbell.net t:alias="I T, GONZALES" t:principle_contact="IT GONZALEZ" t:state=TX t:city=AUSTIN m:phone_ext=11

series e:uxwx-55kj d:2015-07-15T12:26:56.000Z t:vendor_code=LAN7050345 t:legal_name="LANDMARK SURVEYING L P" t:zip=78702 t:phone=5123287411 t:street_1="2205 E. 5th Street" t:fax=5123287413 t:email=dana@landmarksurveying.com t:principle_contact="DANA MARKUS-WOLF" t:state=TX t:city=AUSTIN m:phone_ext=104
```

## Meta Commands

```ls
metric m:phone_ext p:integer l:PHONE_EXT t:dataTypeName=number

metric m:fax_ext p:long l:FAX_EXT t:dataTypeName=number

entity e:uxwx-55kj l:"Current Small Business Enterprise, SBE, Certfied Vendors" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/uxwx-55kj

property e:uxwx-55kj t:meta.view v:id=uxwx-55kj v:category=Financial v:attributionLink=https://www.austintexas.gov/financeonline/finance/index.cfm v:averageRating=0 v:name="Current Small Business Enterprise, SBE, Certfied Vendors" v:attribution="City of Austin"

property e:uxwx-55kj t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:uxwx-55kj t:meta.view.owner v:id=jdd4-9bij v:screenName=carawaym v:lastNotificationSeenAt=1492616720 v:displayName=carawaym

property e:uxwx-55kj t:meta.view.tableauthor v:id=jdd4-9bij v:screenName=carawaym v:roleName=publisher v:lastNotificationSeenAt=1492616720 v:displayName=carawaym
```

## Top Records

```ls
| :updated_at | vendor_code  | legal_name                                    | alias                        | principle_contact | email                                  | phone      | phone_ext | fax        | fax_ext | street_1              | street_2        | city        | state | zip        | 
| =========== | ============ | ============================================= | ============================ | ================= | ====================================== | ========== | ========= | ========== | ======= | ===================== | =============== | =========== | ===== | ========== | 
| 1436963216  | VC0000102852 | MANUEL GARZA III                              | MG DRILLING                  | MANUEL GARZA III  | M45GARZA@MSN.COM                       | 5124968775 |           | 5122584756 |         | PO BOX 2143           |                 | CEDAR PARK  | TX    | 78630      | 
| 1436963216  | VS0000027333 | Green and Sustainable Services, LLC           |                              | Thomas Smith      | tsmith@grnserv.com                     | 9405973723 |           | 9404792009 |         | 2421 Amyx Ranch Drive |                 | Ponder      | TX    | 76259      | 
| 1436963216  | VC0000102842 | MG LIMON CORPORATION                          | LIMON CONSTRUCTION           | MARTHA LIMON      | GLIMONHAULINGCO@YAHOO.COM              | 5127914369 |           | 5122916132 |         | 124 JUAREZ CV         |                 | DEL VALLE   | TX    | 78617      | 
| 1436963216  | VS0000027653 | JUAN DEANDA TRUCKING LLC                      | JUAN DEANDA TRUCKING         | JUAN DEANDA       | juandeandatruckingllc@yahoo.com        | 5127481537 |           | 5122856596 |         | 5101 HWY 21           |                 | MAXWELL     | TX    | 78656      | 
| 1436963216  | MAR8301130   | MARS INDUSTRIES L L C                         |                              | ALVINO ROSALES    | AROS3B@SWBELL.NET                      | 5123034413 |           | 5123211199 |         | PO BOX 560            |                 | CEDAR CREEK | TX    | 78612-0560 | 
| 1436963216  | VS0000035929 | MILLARD DRYWALL & ACOUSTICAL CONSTRUCTION INC |                              | Mary Millard      | mmillard@millarddrywall.com            | 5124428110 | 105       | 5124428010 |         | PO BOX 18926          |                 | AUSTIN      | TX    | 78760      | 
| 1436963216  | VEN7075470   | VENICE ART TERRAZZO CO INC                    |                              | MARY DI FILIPPO   | VATRZO@SWBELL.NET                      | 2105337231 |           | 2105337269 |         | (THE)                 | 200 CALDWELL ST | SAN ANTONIO | TX    | 78223-1098 | 
| 1436963216  | VS0000016867 | PANTHER CREEK TRANSPORTATION INC              | Panther Creek Transportation | Natalia Taylor    | Natalia@panthercreektransportation.com | 5127464224 |           | 5127465103 |         | PO BOX 2715           |                 | GEORGETOWN  | TX    | 78627      | 
| 1436963216  | VS0000034071 | S E Packages Inc                              | Tres Mujeres Construction    | Sadie Pack        | spack@tres-mujeres.com                 | 5122692546 |           |            |         | 2105 fair oaks dr     |                 | Austin      | TX    | 78745      | 
| 1436963216  | VS0000027198 | ELITE TURFCARE GROUP LLC                      | ForeverLawn Austin           | Vicki Harkrider   | vicki@eliteturfcare.com                | 5123107320 |           | 5123107327 |         | 9601 Gray Blvd.       |                 | Austin      | TX    | 78758      | 
```