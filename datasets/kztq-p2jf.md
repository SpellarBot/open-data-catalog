# National Vital Statistics System (NVSS) - National Cardiovascular Disease Surveillance Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/national-vital-statistics-system-nvss-mortality-data-8217e) |
| Metadata | [Link](https://data.cdc.gov/api/views/kztq-p2jf) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/kztq-p2jf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/kztq-p2jf/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | kztq-p2jf |
| Name | National Vital Statistics System (NVSS) - National Cardiovascular Disease Surveillance Data |
| Attribution | Centers for Disease Control and Prevention National Center for Health Statistics |
| Category | Heart Disease & Stroke Prevention |
| Tags | mortality, cardiovascular disease, stroke, coronary heart disease, diseases of the heart |
| Created | 2016-06-23T23:06:34Z |
| Publication Date | 2017-01-04T21:41:52Z |

## Description

2001 to 2013.  NVSS is a secure, web-based data management system that collects and disseminates the Nation's official vital statistics. Data for this dataset has been computed by personnel in CDC's Division for Heart Disease and Stroke Prevention (DHDSP).  This dataset is one of the datasets provided by National Cardiovascular Disease Surveillance System. The system is designed to integrate multiple indicators from many data sources to provide a comprehensive picture of the public health burden of CVDs and associated risk factors in the United States. The data are organized by location (national, state, region, and selected sites) and indicator; NVSS mortality data include CVDs (e.g., heart failure). The data can be viewed by temporal trends and stratified by age group, sex, and race/ethnicity.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | datasource                 | DataSource                 | text      | text        |
| Yes      | series tag     | priorityarea1              | PriorityArea1              | text      | text        |
| Yes      | series tag     | priorityarea2              | PriorityArea2              | text      | text        |
| Yes      | series tag     | priorityarea3              | PriorityArea3              | text      | text        |
| Yes      | series tag     | priorityarea4              | PriorityArea4              | text      | text        |
| Yes      | series tag     | category                   | Category                   | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | indicator                  | Indicator                  | text      | text        |
| Yes      | series tag     | break_out_category         | Break_Out_Category         | text      | text        |
| Yes      | series tag     | break_out                  | Break_Out                  | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | confidence_limit_low       | Confidence_limit_Low       | number    | number      |
| Yes      | numeric metric | confidence_limit_high      | Confidence_limit_High      | number    | number      |
| Yes      | series tag     | categoryid                 | CategoryId                 | text      | text        |
| Yes      | series tag     | topicid                    | TopicId                    | text      | text        |
| Yes      | series tag     | indicatorid                | IndicatorID                | text      | text        |
| Yes      | series tag     | breakoutcategoryid         | BreakOutCategoryId         | text      | text        |
| Yes      | series tag     | breakoutid                 | BreakOutId                 | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_type,data_value_unit,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:kztq-p2jf d:2012-01-01T00:00:00.000Z t:topic="Major Cardiovascular Disease" t:indicator="Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS" t:locationdesc="United States" t:locationabbr=US t:topicid=T1 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=Hispanic t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=0 t:indicatorid=NV001 t:breakoutid=RAC04 t:break_out_category=Race t:breakoutcategoryid=BOC04 t:datasource=NVSS m:confidence_limit_low=215.1 m:data_value=215.1 m:confidence_limit_high=215.1

series e:kztq-p2jf d:2009-01-01T00:00:00.000Z t:topic="Heart Failure" t:indicator="Rate of heart failure mortality among US adults (18+) (Rate per 100,000); NVSS" t:locationdesc="United States" t:locationabbr=US t:topicid=T5 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=Male t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=0 t:indicatorid=NV005 t:breakoutid=GEN01 t:break_out_category=Gender t:breakoutcategoryid=BOC02 t:datasource=NVSS m:confidence_limit_low=23.2 m:data_value=23.2 m:confidence_limit_high=23.2

series e:kztq-p2jf d:2001-01-01T00:00:00.000Z t:topic="Major Cardiovascular Disease" t:indicator="Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS" t:locationdesc=California t:locationabbr=CA t:topicid=T1 t:priorityarea3=None t:priorityarea4=None t:priorityarea1=None t:priorityarea2=None t:break_out=18-24 t:categoryid=C1 t:category="Cardiovascular Diseases" t:locationid=6 t:indicatorid=NV001 t:breakoutid=AGE01 t:break_out_category=Age t:breakoutcategoryid=BOC03 t:datasource=NVSS m:confidence_limit_low=2.3 m:data_value=2.3 m:confidence_limit_high=2.9
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value d:"Data value (point estimate)" t:dataTypeName=number

metric m:confidence_limit_low p:float l:Confidence_limit_Low d:"95% confidence interval lower bound" t:dataTypeName=number

metric m:confidence_limit_high p:float l:Confidence_limit_High d:"95% confidence interval upper bound" t:dataTypeName=number

entity e:kztq-p2jf l:"National Vital Statistics System (NVSS) - National Cardiovascular Disease Surveillance Data" t:attribution="Centers for Disease Control and Prevention National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/kztq-p2jf

property e:kztq-p2jf t:meta.view v:id=kztq-p2jf v:category="Heart Disease & Stroke Prevention" v:attributionLink=http://www.cdc.gov/nchs/nvss.htm v:averageRating=0 v:name="National Vital Statistics System (NVSS) - National Cardiovascular Disease Surveillance Data" v:attribution="Centers for Disease Control and Prevention National Center for Health Statistics"

property e:kztq-p2jf t:meta.view.license v:name="Public Domain"

property e:kztq-p2jf t:meta.view.owner v:id=6thr-55du v:screenName=Angelique v:displayName=Angelique

property e:kztq-p2jf t:meta.view.tableauthor v:id=6thr-55du v:screenName=Angelique v:roleName=publisher v:displayName=Angelique

property e:kztq-p2jf t:meta.view.metadata.custom_fields.common_core v:Publisher="CDC INFO" v:Contact_Email=cdcinfo@cdc.gov v:Public_Access_Level="Public Domain" v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:029
```

## Top Records

```ls
| year | locationabbr | locationdesc   | datasource | priorityarea1 | priorityarea2 | priorityarea3 | priorityarea4 | category                | topic                        | indicator                                                                                     | break_out_category | break_out | data_value_type | data_value_unit | data_value | data_value_footnote_symbol | data_value_footnote                                                                                                          | confidence_limit_low | confidence_limit_high | categoryid | topicid | indicatorid | breakoutcategoryid | breakoutid | locationid | 
| ==== | ============ | ============== | ========== | ============= | ============= | ============= | ============= | ======================= | ============================ | ============================================================================================= | ================== | ========= | =============== | =============== | ========== | ========================== | ============================================================================================================================ | ==================== | ===================== | ========== | ======= | =========== | ================== | ========== | ========== | 
| 2001 | AK           | Alaska         | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 2          | 
| 2001 | AZ           | Arizona        | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 4          | 
| 2001 | AR           | Arkansas       | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 5          | 
| 2001 | CO           | Colorado       | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 8          | 
| 2001 | CT           | Connecticut    | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 9          | 
| 2001 | DE           | Delaware       | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 10         | 
| 2001 | DC           | Washington, DC | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 11         | 
| 2001 | HI           | Hawaii         | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 15         | 
| 2001 | ID           | Idaho          | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 16         | 
| 2001 | IA           | Iowa           | NVSS       | None          | None          | None          | None          | Cardiovascular Diseases | Major Cardiovascular Disease | Rate of major cardiovascular disease mortality among US adults (18+) (Rate per 100,000); NVSS | Age                | 18-24     | Rate            | per 100,000     |            | ~                          | Statistically unstable estimates not presented [unstable by NCHS standards: (standard error/estimate>0.23 or numerator <20)] |                      |                       | C1         | T1      | NV001       | BOC03              | AGE01      | 19         | 
```