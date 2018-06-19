# Hazardous Waste Manifest Data (CT) 1984 ? 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hazardous-waste-manifest-data-ct-1984-2008) |
| Metadata | [Link](https://data.ct.gov/api/views/h6d8-qiar) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/h6d8-qiar/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/h6d8-qiar/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | h6d8-qiar |
| Name | Hazardous Waste Manifest Data (CT) 1984 ? 2008 |
| Attribution | Department of Energy and Environmental Protection |
| Category | Environment and Natural Resources |
| Tags | manifest, hazardous waste, rcra, generator |
| Created | 2016-08-16T20:11:17Z |
| Publication Date | 2016-11-01T20:37:50Z |

## Description

PLEASE NOTE:  We know there are errors in the data although we strive to minimize them.  Examples include:
?	Manifests completed incorrectly by the generator or the transporter - data was entered based on the incorrect information. We can only enter the information we receive.
?	Data entry errors ? we now have QA/QC procedures in place to prevent or catch and fix a lot of these.
?	Historically there are multiple records of the same generator.  Each variation in spelling in name or address generated a separate handler record.  We have worked to minimize these but many remain.  The good news is that as long as they all have the same EPA ID they will all show up in your search results.
?	Handlers provide erroneous data to obtain an EPA ID - data entry was based on erroneous information.  Examples include incorrect or bogus addresses and names. There are also a lot of MISSPELLED NAMES AND ADDRESSES!
?	Missing manifests ? Not every required manifest gets submitted to the DEP. Also, of the more than 100,000 paper manifests we receive each year, some were incorrectly handled and never entered.
?	Missing data ? we know that the records for approximately 25 boxes of manifests, mostly prior to 1985 were lost from the database in the 1980?s. 
?	Translation errors ? the data has been migrated to newer data platforms numerous times, and each time there have been errors and data losses.
?	Wastes incorrectly entered ? mostly due to complex names that were difficult to spell, or typos in quantities or units of measure.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | manifest             | manifest             | text          | text          |
| Yes      | time           | dtshipp              | dtshipp              | calendar_date | calendar_date |
| Yes      | series tag     | batch_numbers        | batch-numbers        | text          | text          |
| Yes      | series tag     | genepa               | genepa               | text          | text          |
| Yes      | series tag     | genname              | genname              | text          | text          |
| Yes      | series tag     | gensitestreetaddress | gensitestreetaddress | text          | text          |
| Yes      | series tag     | gensitetown          | gensitetown          | text          | text          |
| Yes      | series tag     | gensitezipcode       | gensitezipcode       | text          | text          |
| Yes      | numeric metric | wasteoccr            | wasteoccr            | number        | number        |
| Yes      | series tag     | usdot                | usdot                | text          | text          |
| Yes      | series tag     | contno               | contno               | text          | text          |
| Yes      | series tag     | contty               | contty               | text          | text          |
| Yes      | numeric metric | qty                  | qty                  | number        | number        |
| Yes      | series tag     | wtvol                | wtvol                | text          | text          |
| Yes      | series tag     | epa_waste_codes      | epa-waste-codes      | text          | text          |
| Yes      | series tag     | copies               | copies               | text          | text          |
| Yes      | series tag     | tsdfepa              | tsdfepa              | text          | text          |
| Yes      | series tag     | tsdfname             | tsdfname             | text          | text          |
| Yes      | series tag     | tsdfstreetaddress    | tsdfstreetaddress    | text          | text          |
| Yes      | series tag     | tsdftown             | tsdftown             | text          | text          |
| Yes      | series tag     | tsdfzipcode          | tsdfzipcode          | text          | text          |
| Yes      | series tag     | tsdfcountry          | tsdfcountry          | text          | text          |
| Yes      | series tag     | tran1epa             | tran1epa             | text          | text          |
| Yes      | series tag     | tran1name            | tran1name            | text          | text          |
| Yes      | series tag     | tran1streetaddress   | tran1streetaddress   | text          | text          |
| Yes      | series tag     | tran1town            | tran1town            | text          | text          |
| Yes      | series tag     | tran1state           | tran1state           | text          | text          |
| Yes      | series tag     | tran1zipcode         | tran1zipcode         | text          | text          |
| Yes      | series tag     | tran1country         | tran1country         | text          | text          |
| Yes      | series tag     | tran2epa             | tran2epa             | text          | text          |
| Yes      | series tag     | tran2name            | tran2name            | text          | text          |
| Yes      | series tag     | tran2streetaddress   | tran2streetaddress   | text          | text          |
| Yes      | series tag     | tran2town            | tran2town            | text          | text          |
| Yes      | series tag     | tran2state           | tran2state           | text          | text          |
| Yes      | series tag     | tran2zipcode         | tran2zipcode         | text          | text          |
| Yes      | series tag     | tran2country         | tran2country         | text          | text          |
| No       |                | genmailaddress       | genmailaddress       | text          | text          |
| Yes      | series tag     | genmailtown          | genmailtown          | text          | text          |
| Yes      | series tag     | genmailstate         | genmailstate         | text          | text          |
| Yes      | series tag     | genmailzipcode       | genmailzipcode       | text          | text          |
| Yes      | series tag     | discrep              | discrep              | text          | text          |
| No       |                | recdate              | recdate              | calendar_date | calendar_date |
| No       |                | tr2date              | tr2date              | calendar_date | calendar_date |
| Yes      | series tag     | altfacepa            | altfacepa            | text          | text          |
| Yes      | series tag     | altfacname           | altfacname           | text          | text          |
| Yes      | series tag     | altfacstreetaddress  | altfacstreetaddress  | text          | text          |
| Yes      | series tag     | altfactown           | altfactown           | text          | text          |
| Yes      | series tag     | altfacstate          | altfacstate          | text          | text          |
| Yes      | series tag     | altfaczip            | altfaczip            | text          | text          |
| No       |                | altfacdate           | altfacdate           | text          | text          |
| Yes      | series tag     | tsdfstate            | tsdfstate            | text          | text          |
| Yes      | series tag     | uniquekey            | uniqueKey            | text          | text          |
```

## Time Field

```ls
Value = dtshipp
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = genmailaddress,recdate,tr2date,altfacdate
```

## Data Commands

```ls
series e:h6d8-qiar d:1987-07-13T00:00:00.000Z t:tran2state=CT t:tran1state=CT t:gensitezipcode=06820 t:tran2country=USA t:genepa=CTD095232401 t:discrep=S t:tran1epa=NYD088658646 t:genname="EVANS CHEMETICS UNIT OF WR GRACE" t:uniquekey=AR1643752 t:manifest=AR164375 t:genmailzipcode=06820 t:gensitestreetaddress="90 TOKENEKE RD" t:tsdfepa=ARD069748192 t:usdot="WASTE COMBUSTIBLE LIQUID NOS" t:genmailstate=CT t:genmailtown=DARIEN t:epa_waste_codes=D001 t:tsdfstate=AR t:gensitetown=DARIEN t:contno=001 t:tran1name="D & J TRANSPORTATION SPECIALISTS INC" t:tsdfname="ENSCO INC" t:copies=2 t:tran1country=USA t:batch_numbers=999999 t:tsdfzipcode=71730 t:tsdftown="EL DORADO" t:tsdfstreetaddress="AMERICAN OIL RD" t:wtvol=P t:contty=DM t:tsdfcountry=USA m:wasteoccr=2 m:qty=201

series e:h6d8-qiar d:1987-07-13T00:00:00.000Z t:tran2state=CT t:tran1state=CT t:gensitezipcode=06820 t:tran2country=USA t:genepa=CTD095232401 t:discrep=S t:tran1epa=NYD088658646 t:genname="EVANS CHEMETICS UNIT OF WR GRACE" t:uniquekey=AR1643753 t:manifest=AR164375 t:genmailzipcode=06820 t:gensitestreetaddress="90 TOKENEKE RD" t:tsdfepa=ARD069748192 t:usdot="WASTE POISON B SOLID NOS" t:genmailstate=CT t:genmailtown=DARIEN t:epa_waste_codes=D005 t:tsdfstate=AR t:gensitetown=DARIEN t:contno=001 t:tran1name="D & J TRANSPORTATION SPECIALISTS INC" t:tsdfname="ENSCO INC" t:copies=2 t:tran1country=USA t:batch_numbers=999999 t:tsdfzipcode=71730 t:tsdftown="EL DORADO" t:tsdfstreetaddress="AMERICAN OIL RD" t:wtvol=P t:contty=DM t:tsdfcountry=USA m:wasteoccr=3 m:qty=148

series e:h6d8-qiar d:1987-07-13T00:00:00.000Z t:tran2state=CT t:tran1state=CT t:gensitezipcode=06820 t:tran2country=USA t:genepa=CTD095232401 t:discrep=S t:tran1epa=NYD088658646 t:genname="EVANS CHEMETICS UNIT OF WR GRACE" t:uniquekey=AR1643754 t:manifest=AR164375 t:genmailzipcode=06820 t:gensitestreetaddress="90 TOKENEKE RD" t:tsdfepa=ARD069748192 t:usdot="HAZARDOUS WASTE LIQUID NOS" t:genmailstate=CT t:genmailtown=DARIEN t:epa_waste_codes=D003 t:tsdfstate=AR t:gensitetown=DARIEN t:contno=001 t:tran1name="D & J TRANSPORTATION SPECIALISTS INC" t:tsdfname="ENSCO INC" t:copies=2 t:tran1country=USA t:batch_numbers=999999 t:tsdfzipcode=71730 t:tsdftown="EL DORADO" t:tsdfstreetaddress="AMERICAN OIL RD" t:wtvol=P t:contty=DM t:tsdfcountry=USA m:wasteoccr=4 m:qty=264
```

## Meta Commands

```ls
metric m:wasteoccr p:integer l:wasteoccr t:dataTypeName=number

metric m:qty p:integer l:qty t:dataTypeName=number

entity e:h6d8-qiar l:"Hazardous Waste Manifest Data (CT) 1984 ? 2008" t:attribution="Department of Energy and Environmental Protection" t:url=https://data.ct.gov/api/views/h6d8-qiar

property e:h6d8-qiar t:meta.view v:id=h6d8-qiar v:category="Environment and Natural Resources" v:averageRating=0 v:name="Hazardous Waste Manifest Data (CT) 1984 ? 2008" v:attribution="Department of Energy and Environmental Protection"

property e:h6d8-qiar t:meta.view.license v:name="Public Domain"

property e:h6d8-qiar t:meta.view.owner v:id=ksrh-ut6b v:screenName="Open Data Hub" v:displayName="Open Data Hub"

property e:h6d8-qiar t:meta.view.tableauthor v:id=ksrh-ut6b v:screenName="Open Data Hub" v:roleName=publisher v:displayName="Open Data Hub"
```

## Top Records

```ls
| manifest | dtshipp             | batch_numbers | genepa       | genname                          | gensitestreetaddress | gensitetown | gensitezipcode | wasteoccr | usdot                               | contno | contty | qty | wtvol | epa_waste_codes | copies | tsdfepa      | tsdfname  | tsdfstreetaddress | tsdftown  | tsdfzipcode | tsdfcountry | tran1epa     | tran1name                            | tran1streetaddress | tran1town | tran1state | tran1zipcode | tran1country | tran2epa | tran2name | tran2streetaddress | tran2town | tran2state | tran2zipcode | tran2country | genmailaddress | genmailtown | genmailstate | genmailzipcode | discrep | recdate             | tr2date | altfacepa | altfacname | altfacstreetaddress | altfactown | altfacstate | altfaczip | altfacdate | tsdfstate | uniquekey | 
| ======== | =================== | ============= | ============ | ================================ | ==================== | =========== | ============== | ========= | =================================== | ====== | ====== | === | ===== | =============== | ====== | ============ | ========= | ================= | ========= | =========== | =========== | ============ | ==================================== | ================== | ========= | ========== | ============ | ============ | ======== | ========= | ================== | ========= | ========== | ============ | ============ | ============== | =========== | ============ | ============== | ======= | =================== | ======= | ========= | ========== | =================== | ========== | =========== | ========= | ========== | ========= | ========= | 
| AR164375 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 2         | WASTE COMBUSTIBLE LIQUID NOS        | 001    | DM     | 201 | P     | D001            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643752 | 
| AR164375 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 3         | WASTE POISON B SOLID NOS            | 001    | DM     | 148 | P     | D005            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643753 | 
| AR164375 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 4         | HAZARDOUS WASTE LIQUID NOS          | 001    | DM     | 264 | P     | D003            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643754 | 
| AR164376 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 1         | HAZARDOUS WASTE LIQUID OR SOLID NOS | 001    | DM     | 170 | P     | D003            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643761 | 
| AR164376 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 2         | WASTE FLAMMABLE LIQUID NOS          | 001    | DM     | 171 | P     | D001            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643762 | 
| AR164376 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 3         | WASTE FLAMMABLE SOLID NOS           | 001    | DM     | 123 | P     | D001            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643763 | 
| AR164376 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 4         | WASTE CORROSIVE SOLIDS NOS          | 001    | DM     | 134 | P     | D002            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643764 | 
| AR164377 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 1         | WASTE OXIDIZER NOS                  | 001    | DM     | 108 | P     | D003            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643771 | 
| AR164377 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 2         | WASTE POISONOUS LIQUID NOS          | 001    | DM     | 128 | 0     | D004            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643772 | 
| AR164377 | 1987-07-13T00:00:00 | 999999        | CTD095232401 | EVANS CHEMETICS UNIT OF WR GRACE | 90 TOKENEKE RD       | DARIEN      | 06820          | 3         | WASTE CORROSIVE LIQUID & SOLID NOS  | 001    | DM     | 152 | P     | D002            | 2      | ARD069748192 | ENSCO INC | AMERICAN OIL RD   | EL DORADO | 71730       | USA         | NYD088658646 | D & J TRANSPORTATION SPECIALISTS INC |                    |           | CT         |              | USA          |          |           |                    |           | CT         |              | USA          | 90 TOKENEKE RD | DARIEN      | CT           | 06820          | S       | 1987-07-17T00:00:00 |         |           |            |                     |            |             |           |            | AR        | AR1643773 | 
```