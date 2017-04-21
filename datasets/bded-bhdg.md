# Vital Signs 13 Codebook

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vital-signs-13-codebook) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/bded-bhdg) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/bded-bhdg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/bded-bhdg/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | bded-bhdg |
| Name | Vital Signs 13 Codebook |
| Attribution | The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI) |
| Category | Neighborhoods |
| Tags | vital signs, bnia |
| Created | 2015-05-14T20:41:28Z |
| Publication Date | 2015-05-14T20:43:06Z |

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | indicator            | Indicator            | text      | text        |
| Yes      | series tag  | section              | Section              | text      | text        |
| Yes      | series tag  | full_source          | Full Source          | text      | text        |
| Yes      | series tag  | years                | Years                | text      | text        |
| Yes      | series tag  | normalization_source | Normalization Source | text      | text        |
| Yes      | series tag  | shortname            | ShortName            | text      | text        |
| Yes      | series tag  | definition           | Definition           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bded-bhdg d:2015-05-14T13:41:32.000Z t:normalization_source="U.S. Bureau of the Census" t:indicator="Number of Persons with Library Cards per 1,000 Residents" t:definition="The rate of persons per 1,000 residents that possess a valid public library system card. This includes all library card types (first card, juvenile, young adult, adult)." t:shortname=libcardXX t:full_source="Enoch Pratt Free Library" t:years="2011, 2012, 2013" t:section="Arts and Culture" m:row_number.bded-bhdg=1

series e:bded-bhdg d:2015-05-14T13:41:32.000Z t:normalization_source="U.S. Bureau of the Census" t:indicator="Number of Businesses that are Arts-Related per 1,000 residents" t:definition="The rate of businesses (both for-profit and non-profit) that are related to arts and culture per 1,000 residents.  These industries are identified by their primary NAICS code and include the following: theatre companies and dinner theaters (711110), dance companies (711120), musical groups and artists (711130), other performing arts companies (711190), motion picture theaters (52131), museums (712110), historical sites (712120), zoos and botanical gardens (712130), nature parks (712190), art schools (611610), independent artists (711510), bookstores (451211), music stores (451220), video rental stores (532230), and retail art dealerships (453920)." t:shortname=artbusXX t:full_source=InfoUSA t:years="2011, 2012, 2013" t:section="Arts and Culture" m:row_number.bded-bhdg=2

series e:bded-bhdg d:2015-05-14T13:41:32.000Z t:indicator="Total Employment in Arts-Related Businesses" t:definition="The number of persons employed in arts-related businesses (both for-profit and non-profit). This number does not count those persons who identify themselves as being artists and does not count sole proprietorships or persons who work part-time in the arts. The same industries are used to determine the rate of arts-related businesses." t:shortname=artempXX t:full_source=InfoUSA t:years="2011, 2012, 2013" t:section="Arts and Culture" m:row_number.bded-bhdg=3
```

## Meta Commands

```ls
metric m:row_number.bded-bhdg p:long l:"Row Number"

entity e:bded-bhdg l:"Vital Signs 13 Codebook" t:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)" t:url=https://data.baltimorecity.gov/api/views/bded-bhdg

property e:bded-bhdg t:meta.view v:id=bded-bhdg v:category=Neighborhoods v:attributionLink=http://bniajfi.org v:averageRating=0 v:name="Vital Signs 13 Codebook" v:attribution="The Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore (known as BNIA-JFI)"

property e:bded-bhdg t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:bded-bhdg t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:bded-bhdg t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | indicator                                                          | section          | full_source                      | years                  | normalization_source      | shortname | definition                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| =========== | ================================================================== | ================ | ================================ | ====================== | ========================= | ========= | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1431610892  | Number of Persons with Library Cards per 1,000 Residents           | Arts and Culture | Enoch Pratt Free Library         | 2011, 2012, 2013       | U.S. Bureau of the Census | libcardXX | The rate of persons per 1,000 residents that possess a valid public library system card. This includes all library card types (first card, juvenile, young adult, adult).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 
| 1431610892  | Number of Businesses that are Arts-Related per 1,000 residents     | Arts and Culture | InfoUSA                          | 2011, 2012, 2013       | U.S. Bureau of the Census | artbusXX  | The rate of businesses (both for-profit and non-profit) that are related to arts and culture per 1,000 residents. These industries are identified by their primary NAICS code and include the following: theatre companies and dinner theaters (711110), dance companies (711120), musical groups and artists (711130), other performing arts companies (711190), motion picture theaters (52131), museums (712110), historical sites (712120), zoos and botanical gardens (712130), nature parks (712190), art schools (611610), independent artists (711510), bookstores (451211), music stores (451220), video rental stores (532230), and retail art dealerships (453920). | 
| 1431610892  | Total Employment in Arts-Related Businesses                        | Arts and Culture | InfoUSA                          | 2011, 2012, 2013       |                           | artempXX  | The number of persons employed in arts-related businesses (both for-profit and non-profit). This number does not count those persons who identify themselves as being artists and does not count sole proprietorships or persons who work part-time in the arts. The same industries are used to determine the rate of arts-related businesses.                                                                                                                                                                                                                                                                                                                                | 
| 1431610892  | Part 1 Crime Rate per 1,000 Residents                              | Crime and Safety | Baltimore City Police Department | 2010, 2011, 2012, 2013 | U.S. Bureau of the Census | crimeXX   | The part 1 crime rate captures incidents of homicide, rape, aggravated assault, robbery, burglary, larceny, and auto theft that are reported to the Police Department. These incidents are per 1,000 residents in the neighborhood to allow for comparison across areas.                                                                                                                                                                                                                                                                                                                                                                                                       | 
| 1431610892  | Violent Crime Rate per 1,000 Residents                             | Crime and Safety | Baltimore City Police Department | 2010, 2011, 2012, 2013 | U.S. Bureau of the Census | violXX    | The violent crime rate measures the number of Part 1 crimes identified as being violent (homicide, rape, aggravated assault, and robbery) that are reported to the Police Department. These incidents are per 1,000 residents in the neighborhood to allow for comparison across areas.                                                                                                                                                                                                                                                                                                                                                                                        | 
| 1431610892  | Property Crime Rate per 1,000 Residents                            | Crime and Safety | Baltimore City Police Department | 2010, 2011, 2012, 2013 | U.S. Bureau of the Census | propXX    | The property crime rate measures the number of Part 1 crimes identified as being property-based (burglary and auto theft) that are reported to the Police Department. These incidents are per 1,000 residents in the neighborhood to allow for comparison across areas.                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 1431610892  | Domestic Violence Calls For Service per 1,000 Residents            | Crime and Safety | Baltimore City Police Department | 2010, 2011, 2012       | U.S. Bureau of the Census | domvioXX  | The rate of calls to emergency 911 for domestic violence per 1,000 residents in an area. Calls for service are used rather than actual crime incidents since domestic violence can be classified as one of several types of criminal offenses. It is important to also note that not every case of domestic violence is reported and some claims of abuse may be unfounded.                                                                                                                                                                                                                                                                                                    | 
| 1431610892  | Juvenile Arrest Rate per 1,000 Juveniles                           | Crime and Safety | Baltimore City Police Department | 2011, 2012             | U.S. Bureau of the Census | juvarrXX  | The number of persons aged 10 to 17 arrested per 1,000 juveniles that live in an area. This indicator is calculated by where the arrested juvenile was arrested and not by where the crime is committed. Arrests are used instead of crimes committed since not all juveniles that are arrested are charged with committing a crime. This indicator also excludes offenders who are later charged as adults for their crime(s).                                                                                                                                                                                                                                                | 
| 1431610892  | Juvenile Arrest Rate for Violent Offenses per 1,000 Juveniles      | Crime and Safety | Baltimore City Police Department | 2011, 2012             | U.S. Bureau of the Census | juvviolXX | The number of persons aged 10 to 17 arrested for violent offenses per 1,000 juveniles that live in an area. Violent offenses may include homicide, rape, assault (with or without a weapon), and robbery. This indicator is calculated by where the arrested juvenile was arrested and not by where the crime is committed. Arrests are used instead of crimes committed since not all juveniles that are arrested are charged with committing a crime. This indicator also excludes offenders who are later charged as adults for their crime(s).                                                                                                                             | 
| 1431610892  | Juvenile Arrest Rate for Drug-Related Offenses per 1,000 Juveniles | Crime and Safety | Baltimore City Police Department | 2011, 2012             | U.S. Bureau of the Census | juvdrugXX | The number of persons aged 10 to 17 for drug-related offenses per 1,000 juveniles that live in an area. Drug-related offenses include arrests for possession, sale, manufacture, or abuse of illegal drugs, including alcohol. This indicator is calculated by where the arrested juvenile was arrested and not by where the crime is committed. Arrests are used instead of crimes committed since not all juveniles that are arrested are charged with committing a crime. This indicator also excludes offenders who are later charged as adults for their crime(s).                                                                                                        | 
```