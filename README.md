# birth_control
# Accidental Ingestion of Birth Control by Children: A National Population-Based Analysis
Masten, Muffly

* Video about how I analyzed the data: https://youtu.be/lLAF9xJQYbM

Our objective was to analyze trends in birth control tablet ingestion by non-users epidemiology, demographics, and mechanisms of injury.

* NEISS coding manual, https://www.cpsc.gov/s3fs-public/2018-NEISS-CPSC-only-CodingManual.pdf?FY0UWXTUPXns1FCZe6d3.1x.d1RHLeP_
* NEISS, https://www.cpsc.gov/cgibin/NEISSQuery/UserCriteria.aspx?UserAff=CvbkBwSYvXoJ%2blc0Tfzwdg%3d%3d&UserAffOther=9OYR9kUytIsLilKZieD5xg%3d%3d
* Sample paper, https://www.dropbox.com/s/6b8wz2isgwwpgk8/soccer_injury.pdf?dl=0
* https://www.cpsc.gov/Research--Statistics/NEISS-Injury-Data
* https://www.cpsc.gov/cgibin/NEISSQuery/WebEstimates.html
* https://www.cpsc.gov/cgibin/NEISSQuery/home.aspx
* https://lenagroeger.s3.amazonaws.com/talks/orlando/exercises/ExcelMath/math.html
* https://www.dropbox.com/s/nfo87g26mz93d0r/svider_article.pdf?dl=0

# Abstract to model on
Purpose: Soccer participation continues to increase among all ages in the US. Our objective was to analyze trends in soccer-related facial injury epidemiology, demographics, and mechanisms of injury.

Materials and methods: The National Electronic Injury Surveillance System was evaluated for soccer-related facial injuries from 2010 through 2014. Results for product code "soccer" were filtered for injures to the face. Number of injuries was extrapolated, and data were analyzed for age, sex, specific injury diagnoses, locations, and mechanisms.

Results: In all, 2054 soccer-related facial trauma entries were analyzed. During this time, the number of injures remained relatively stable. Lacerations were the most common diagnosis (44.2%), followed by contusions and fractures. The most common sites of fracture were the nose (75.1%). Of fractures with a reported mechanism of injury, the most common was head-to-head collisions (39.0%). Patients <19 years accounted for 66.9% of injuries, and athletes over 18 years old had a higher risk of fractures.

Conclusions: The incidence of soccer-related facial trauma has remained stable, but the severity of such injuries remain a danger. Facial protection in soccer is virtually absent, and our findings reinforce the need to educate athletes, families, and physicians on injury awareness and prevention.

Keywords: NEISS; National Electronic Injury Surveillance System; facial trauma; soccer; soccer-related injury.

# Materials and Methods
The National Electronic Injury Surveillance System (NEISS), a nationwide resource offered by the Consumer Product Safety Commission, was evaluated for emergency department (ED) visits related to accidental ingestion of birth control tablets. The NEISS collects data from a representative sample of EDs and weighs results based on ED setting, providing weighted national incidence. This database has been of great importance in numerous prior analyses.(citation needed)

In August 2020, the most recent 10-year period of data was searched using the product of interest “tablets” (NEISS code 1931) with focus on accidental ingestion "poisoning" (NEISS code 68) of birth control. Data were recorded and evaluated for patient age, sex, injury type, and a brief narrative description of the incident. Injuries unrelated to ingestion of birth control were excluded from the study (eg, patient on birth control and developed a pulmonary embolism). This database provided annual sample sizes as well as derived national estimates for poisoning due to tablet medications. The annual sample size of poisonings by tablet organized was multiplied by the annual percentage of birth-control related poisonings, and this proportion was multiplied by the nationwide estimate to come up with specific values for injury incidence. For example, the NEISS reported 9 birth control-related ED visits for poisoning in 2019 with 882 poisonings via tablet medications in 2019 within the NEISS hospitals.  Therefore (9/882) one percent of poisonings with tablets were from birth control.  In 2019, the poisoning with tablets had a derived estimate of 25,508 nationwide ED visits. Because one percent of these 882 visits (1%) were related to birth control, we multiplied 25,508 by one percent to come up with an estimate of 255 birth control related poisoning injuries for 2019. In addition to annual estimates, we also analyzed data by patient demographics (including age and gender), injury diagnosis, and patient disposition. We examined data from the most recent available 10-year block (2010–2019). Data collection was completed in August 2020.

Statistical Analysis
Fisher’s exact test and 2-tailed Student’s t test were used for comparison of categorical and continuous variables, as appropriate, with significance set at P < .05. Weighted national incidence estimates are provided by the NEISS from each query conducted. Exploratory.io version 6.1.1.4 was used for statistical calculations.

Ethical Considerations
Because this study is comprised solely of publicly searchable data freely available through online databases, it qualifies as nonhuman subject research and thus was exempted from requiring institutional review board approval.

# Results
During the 10-year period studied, we reviewed 74 NEISS recorded ED poisonings by birth control tables, which was extrapolated to a national incidence of 255 birth control-related poisonings per year. The number of US ED visits for birth control-related poisonings remained stable from 2010 to 2019 (Figure 1). The majority of patients poisoned by birth control were children with a majority being male (74.4%).

Age-related trends (need values)
Patients aged 18 and under accounted for 66.9% of injures, while 33.1% were adults over 18 years of age. The mean and median ages of those injured were 18.4 (±.21) and 16 years (interquartile range, 13-22), respectively. Of the pediatric population, 53.3% of injuries were involving children under 15 years of age while 46.7% were involving high school–aged athletes, from 15 to 18 years of age. Adults over 18 years of age had a higher risk of lacerations (52.7% vs 40.0%, P < .0001) and fractures (27.2% vs 17.2%, P < .0001), while patients 18 years of age and under had a significantly higher risk of contusions (31.8% vs 15.9% P < .0001) (Table 1). Similarly, males were significantly more likely to suffer from lacerations (49.2% vs 29.8%, P < .0001), and females were more likely to sustain a contusion (39.1% vs 22.2%, P < .0001) (Table 2).

![National Estimates of Ages of those poisoned by birth control tablets](Age group.png)



* Plots
* Create line graph of National estimate of birth control poisoning on y and years on x.  Similar to figure 2 of the battery paper.  Need ot build the table in Excel to input the national estimates for each year of tablet poisonings from NEISS.  

## Downloads from NEISS
We downloaded all the NEISS data for females with no restrictions.  Then we pulled out the data based on filtering specific words.  
```r
NEISS Query Results

National Estimate of Injuries Treated in Emergency Departments
Treatment Dates: 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019

National Estimate
66,485,379
Suggested Citation: Consumer Product Safety Commission. National Electronic Injury Surveillance System 2000-2019 on NEISS Online Database, released April, 2020. Generated at https://www.cpsc.gov/cgibin/NEISSQuery/home.aspx. on: August 16, 2020 at 0:00:46

User Selected On: Most Recent 10 Years (2010 - 2019); Gender: Female (2);
```

## All poisonings (NEISS diagnosis code 68) in 2019 and unfiltered for gender with product "table" (NEISS code 1931)
```r
National Estimate of Injuries Treated in Emergency Departments
Treatment Dates: 01/01/2019 - 12/31/2019

National Estimate	25,508
Number of Cases	882
CV		0.12
95% CI Lower Bound		19,256	
95% CI Upper Bound  31,761

Suggested Citation: Consumer Product Safety Commission. National Electronic Injury Surveillance System 2000-2019 on NEISS Online Database, released April, 2020. Generated at https://www.cpsc.gov/cgibin/NEISSQuery/home.aspx. on: August 22, 2020 at 19:42:56
 
Prior to 2019, each NEISS record allowed a maximum of one diagnosis, one body part, and two product codes. In 2019 the NEISS began collecting up to two diagnoses and body parts, and three product codes per record. As a result, a NEISS record may be counted multiple times in producing national injury estimates and calculating variability of those estimates. A single record may be counted in up to three product groups, product sub-groups, or individual product codes. Likewise, an individual NEISS record may be counted in up to two different diagnosis/body part combinations.

User Selected On: Date Range from 01/01/2019 to 12/31/2019; Product Selection: Tablet Or Capsule Drugs (1931); Diagnosis Selection: Poisoning (68);
```
# Poisoning from 2017
```r
National Estimate of Injuries Treated in Emergency Departments
Treatment Dates: 01/01/2017 - 12/31/2017

National Estimate
31,007
Suggested Citation: Consumer Product Safety Commission. National Electronic Injury Surveillance System 2000-2019 on NEISS Online Database, released April, 2020. Generated at https://www.cpsc.gov/cgibin/NEISSQuery/home.aspx. on: August 22, 2020 at 20:18:57
 
Prior to 2019, each NEISS record allowed a maximum of one diagnosis, one body part, and two product codes. In 2019 the NEISS began collecting up to two diagnoses and body parts, and three product codes per record. As a result, a NEISS record may be counted multiple times in producing national injury estimates and calculating variability of those estimates. A single record may be counted in up to three product groups, product sub-groups, or individual product codes. Likewise, an individual NEISS record may be counted in up to two different diagnosis/body part combinations.

User Selected On: Date Range from 01/01/2017 to 12/31/2017; Product Selection: Tablet Or Capsule Drugs (1931); Diagnosis Selection: Poisoning (68);
```

## All ingested tablets because both boys and firls accidentally take birth control, 2019 only
```r
National Estimate of Injuries Treated in Emergency Departments
Treatment Dates: 2019

National Estimate
98,886
Suggested Citation: Consumer Product Safety Commission. National Electronic Injury Surveillance System 2000-2019 on NEISS Online Database, released April, 2020. Generated at https://www.cpsc.gov/cgibin/NEISSQuery/home.aspx. on: June 8, 2020 at 10:01:06
 
Prior to 2019, each NEISS record allowed a maximum of one diagnosis and body part. In 2019 the NEISS began collecting up to two diagnoses and body parts per record. As a result, a NEISS record may be counted multiple times in producing national injury estimates and calculating variability of those estimates. A single record may be counted in up to two different diagnosis/body part combinations.

User Selected On: Select Up to 5 Years: 2019; Diagnosis Selection: Ingested Object (41), Aspirated Object (42);
```

## All ten years of accidentally ingested tablets that are then filtered to birth control
Files:  NEISS_56011
```r
National Estimate of Injuries Treated in Emergency Departments
Treatment Dates: 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019

National Estimate
973,878
Suggested Citation: Consumer Product Safety Commission. National Electronic Injury Surveillance System 2000-2019 on NEISS Online Database, released April, 2020. Generated at https://www.cpsc.gov/cgibin/NEISSQuery/home.aspx. on: May 4, 2020 at 14:30:57

User Selected On: Most Recent 10 Years (2010 - 2019); Diagnosis Selection: Ingested Object (41), Aspirated Object (42);
```

## All ten years of all injuries for boys and girls, no filter
NEISS_50815.zip
```r
National Estimate of Injuries Treated in Emergency Departments
Treatment Dates: 2010, 2011, 2012, 2013, 2014, 2015, 2016, 2017, 2018, 2019

National Estimate
141,969,223
Suggested Citation: Consumer Product Safety Commission. National Electronic Injury Surveillance System 2000-2019 on NEISS Online Database, released April, 2020. Generated at https://www.cpsc.gov/cgibin/NEISSQuery/home.aspx. on: May 14, 2020 at 16:15:26

User Selected On: Most Recent 10 Years (2010 - 2019);
``
