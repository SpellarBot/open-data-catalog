# Adult Arrests by County: Beginning 1970

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/adult-arrests-by-county-beginning-1970) |
| Metadata | [Link](https://data.ny.gov/api/views/rikd-mt35) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/rikd-mt35/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/rikd-mt35/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | rikd-mt35 |
| Name | Adult Arrests by County: Beginning 1970 |
| Attribution | New York State Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | arrest, public safety, felony, misdemeanor, dwi |
| Created | 2013-03-01T17:38:50Z |
| Publication Date | 2016-04-13T22:00:56Z |

## Description

The counts of arrests are derived from information transmitted from law enforcement agencies to the Division of Criminal Justice Services Computerized Criminal History database for fingerprintable offenses.An adult arrest is defined as an arrest of a person 16 years old or older or a juvenile offender prosecuted in adult court.  Fingerprintable offenses (defined in Criminal Procedure Law ?160.10) include any felony, a misdemeanor defined in the penal law, a misdemeanor defined outside the penal law which would constitute a felony if such a person had a previous judgment of conviction for a crime, or loitering for the purpose of engaging in prostitution as defined in subdivision two of Penal Law ?240.37.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | county            | County            | text      | text        |
| Yes      | time           | year              | Year              | number    | number      |
| Yes      | numeric metric | total             | Total             | number    | number      |
| Yes      | numeric metric | felony_total      | Felony Total      | number    | number      |
| Yes      | numeric metric | drug_felony       | Drug Felony       | number    | number      |
| Yes      | numeric metric | violent_felony    | Violent Felony    | number    | number      |
| Yes      | numeric metric | dwi_felony        | DWI Felony        | number    | number      |
| Yes      | numeric metric | other_felony      | Other Felony      | number    | number      |
| Yes      | numeric metric | misdemeanor_total | Misdemeanor Total | number    | number      |
| Yes      | numeric metric | drug_misd         | Drug Misd         | number    | number      |
| Yes      | numeric metric | dwi_misd          | DWI Misd          | number    | number      |
| Yes      | numeric metric | property_misd     | Property Misd     | number    | number      |
| Yes      | numeric metric | other_misd        | Other Misd        | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rikd-mt35 d:1970-01-01T00:00:00.000Z t:county=Albany m:total=1222 m:misdemeanor_total=536 m:drug_misd=206 m:drug_felony=97 m:other_felony=394 m:dwi_felony=5 m:violent_felony=190 m:property_misd=95 m:dwi_misd=48 m:felony_total=686 m:other_misd=187

series e:rikd-mt35 d:1971-01-01T00:00:00.000Z t:county=Albany m:total=1831 m:misdemeanor_total=1003 m:drug_misd=204 m:drug_felony=130 m:other_felony=461 m:dwi_felony=6 m:violent_felony=231 m:property_misd=271 m:dwi_misd=111 m:felony_total=828 m:other_misd=417

series e:rikd-mt35 d:1972-01-01T00:00:00.000Z t:county=Albany m:total=3028 m:misdemeanor_total=1979 m:drug_misd=284 m:drug_felony=210 m:other_felony=577 m:dwi_felony=8 m:violent_felony=254 m:property_misd=539 m:dwi_misd=297 m:felony_total=1049 m:other_misd=859
```

## Meta Commands

```ls
metric m:total p:integer l:Total d:"Number of adult felony and misdemeanor arrests" t:dataTypeName=number

metric m:felony_total p:integer l:"Felony Total" d:"Number of adult arrests in which the top charge is an offense for which a sentence to a term of imprisonment in excess of one year may be imposed (Penal Law ?10.05)" t:dataTypeName=number

metric m:drug_felony p:integer l:"Drug Felony" d:"Number of adult arrests in which the top charge is a felony listed in Penal Law ?220 (Controlled Substances) or ?221 (Marijuana)" t:dataTypeName=number

metric m:violent_felony p:integer l:"Violent Felony" d:"Number of adult arrests in which the top charge is a Violent Felony Offense listed in Penal Law ?70.02" t:dataTypeName=number

metric m:dwi_felony p:integer l:"DWI Felony" d:"Number of adult arrests in which the top charge is a Driving While Intoxicated felony listed in Vehicle and Traffic Law ?1192" t:dataTypeName=number

metric m:other_felony p:integer l:"Other Felony" d:"Number of adult arrests in which the top charge is a felony not specified in another category" t:dataTypeName=number

metric m:misdemeanor_total p:integer l:"Misdemeanor Total" d:"# of adult arrests in which top charge is an offense, not a traffic infraction, for which a sentence to a term of imprisonment in excess of 15 days may be imposed, but for which a sentence to term of imprisonment cannot exceed 1 year (Penal Law ?10.04)" t:dataTypeName=number

metric m:drug_misd p:integer l:"Drug Misd" d:"Number of adult arrests in which the top charge is a Penal Law ?220 (Controlled Substances) or ?221 (Marijuana) misdemeanor" t:dataTypeName=number

metric m:dwi_misd p:integer l:"DWI Misd" t:dataTypeName=number

metric m:property_misd p:integer l:"Property Misd" d:"Number of arrests in which the top charge is a misdemeanor listed in Penal Law ?140, 145, 150, 155, and 165" t:dataTypeName=number

metric m:other_misd p:integer l:"Other Misd" d:"Number of adult arrests in which the top charge is a misdemeanor not specified in another category" t:dataTypeName=number

entity e:rikd-mt35 l:"Adult Arrests by County:  Beginning 1970" t:attribution="New York State Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/rikd-mt35

property e:rikd-mt35 t:meta.view v:id=rikd-mt35 v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/crimnet/ojsa/arrests/index.htm v:averageRating=0 v:name="Adult Arrests by County:  Beginning 1970" v:attribution="New York State Division of Criminal Justice Services"

property e:rikd-mt35 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:rikd-mt35 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:rikd-mt35 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county | year | total | felony_total | drug_felony | violent_felony | dwi_felony | other_felony | misdemeanor_total | drug_misd | dwi_misd | property_misd | other_misd | 
| ====== | ==== | ===== | ============ | =========== | ============== | ========== | ============ | ================= | ========= | ======== | ============= | ========== | 
| Albany | 1970 | 1222  | 686          | 97          | 190            | 5          | 394          | 536               | 206       | 48       | 95            | 187        | 
| Albany | 1971 | 1831  | 828          | 130         | 231            | 6          | 461          | 1003              | 204       | 111      | 271           | 417        | 
| Albany | 1972 | 3028  | 1049         | 210         | 254            | 8          | 577          | 1979              | 284       | 297      | 539           | 859        | 
| Albany | 1973 | 3568  | 1133         | 244         | 274            | 28         | 587          | 2435              | 369       | 497      | 667           | 902        | 
| Albany | 1974 | 4244  | 1324         | 281         | 307            | 17         | 719          | 2920              | 434       | 618      | 884           | 984        | 
| Albany | 1975 | 4167  | 1256         | 209         | 343            | 12         | 692          | 2911              | 399       | 461      | 975           | 1076       | 
| Albany | 1976 | 4586  | 1430         | 201         | 431            | 26         | 772          | 3156              | 359       | 573      | 1008          | 1216       | 
| Albany | 1977 | 4810  | 1337         | 122         | 403            | 45         | 767          | 3473              | 270       | 857      | 1132          | 1214       | 
| Albany | 1978 | 5754  | 1481         | 85          | 431            | 58         | 907          | 4273              | 156       | 1536     | 1330          | 1251       | 
| Albany | 1979 | 6525  | 1657         | 144         | 513            | 65         | 935          | 4868              | 223       | 1845     | 1416          | 1384       | 
```