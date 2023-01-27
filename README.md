# Association between depressive disorders and various factors in adolescents by country
—

## Motivation

Depression is one of the most common affective spectrum disorders [^1]. The exact causes of depression have not been identified, but it is known that it is influenced by many factors: from genetic predisposition to environmental influences, as well as many socio-economic factors [^2]. Teenagers, due to rapid hormonal adjustment and growth, may be particularly vulnerable to depression [^3]. 

## Aim, tasks and data

**Aim:** To analyze the dependence of the number of adolescent patients suffering from depressive disorders on socio-economic factors in different countries.

**Tasks:**

* Search and data collection
* Exploratory analysis
* Hypotheses based on data
* Data analysis to find causal relationships between data

**Workflow**

1. Literature search
2. Selection of hypotheses
3. Search for open data to study hypotheses
4. Data analysis

**Data**

As the main dataset, we used data that was obtained from the [GBD](https://vizhub.healthdata.org/gbd-results/) open database of the Institute of Health Indicators and Assessment. They provide a quantitative assessment of the impact of the disease on health based on various indicators. 

| Search       |                                                  |
|--------------|--------------------------------------------------|
| GBD Estimate | Risk factor                                      |
| Measure      | DALYs, YLDs                                      |
| Metric       | Number, Percent                                  |
| Risk         | All risk factors                                 |
| Cause        | Depressive disorders                             |
| Location     | All country                                      |
| Age          | 5-9 years, 10-14 years, 15-19 years, 20-24 years |
| Sex          | Male, Female                                     |
| Year         | 2000 - 2019                                      |
Data to hypotheses will be added in the description of hypotheses.

## Methods and Results

* Descriptive statistics
* Data visualization
* Correlation analysis
* Regression analysis

## Hypothesis

We have decided to concentrate on three of them and, finally, put forward the following hypothesis:
1.      Gender equality can affect adolescent depression prevalence inversely.
2.      Hunger and poverty can increase adolescent depression.
3.      There is a connection between quality of secondary education and adolescent depression prevalence.

### **Hypothesis No. 1.** The relationship of the average level of school education with the level of depression [^5],[^6],[^7]

To test this hypothesis, data from the [PISA](https://www.oecd.org/pisa/) test and the [TIMSS](https://timssandpirls.bc.edu/timss-landing.html) test were used. PISA is the OECD's Programme for International Student Assessment. PISA measures 15-year-olds’ ability to use their reading, mathematics and science knowledge and skills to meet real-life challenges. TIMSS has monitored trends in mathematics and science achievement every four years, at the fourth and eighth grades. 
In both cases, there is a small dependence, which was further checked for correlation between factors. Also in the case of the PISA test, the trend repeats at the end of almost every test.

### **Hypothesis No. 2.** The relationship between hunger and the incidence of depression in adolescents and young people

To estimate the level of hunger by country we decided to look up the Global Hunger Index, its values were merged to the general dataset with prevalences and used in exploratory analysis and visualization. 
To estimate the level of hunger by country we decided to look up the Global Hunger Index, as well as TIMSS and PISA for the quality of secondary education. Exploratory data analysis has been provided to test all three hypotheses. After visualization and correlation analysis, we have built models by country with random slopes and intercepts. Unfortunately, we found a very weak association between level of secondary education and prevalence of adolescent depression. The same results were achieved for hunger. The only discovery was that slightly more girls suffer from depression than boys do for all ages.

### **Hypothesis No. 3.** The relationship of gender differences with the number of patients with depression

However, some linkages were found between adolescent depression prevalence and gender equity rates. We have addressed to open source data from Our World in Data and World Population Review to get some information about gender equality and socioeconomic factors.

## Summary

1. The difference between the groups of men and women was revealed – women suffer from depression more often;
2. The quality of school education in the country is not associated with a decrease in the likelihood of depression in adolescents;
3. The index of the level of hunger in the country is not associated with the incidence of depression in adolescents in adolescents and young people;
4. There is a connection between gender differences and the number of patients with depression.

## Literature
[^1]: Jääskeläinen E, Juola T, Korpela H, Lehtiniemi H, Nietola M, Korkeila J, Miettunen J. Epidemiology of psychotic depression - systematic review and meta-analysis. Psychol Med. 2018 Apr;48(6):905-918. doi: 10.1017/S0033291717002501. Epub 2017 Sep 12. PMID: 28893329.
[^2]: Sebastian Trautmann1 , Jürgen Rehm1,2 & Hans-Ulrich Wittchen. The economic costs of mental disorders
[^3]: Van de Velde S, Bracke P, Levecque K. Gender differences in depression in 23 European countries. Cross-national variation in the gender gap in depression. Soc Sci Med. 2010 Jul;71(2):305-313. doi: 10.1016/j.socscimed.2010.03.035. Epub 2010 Apr 24. PMID: 20483518.
[^4]: https://worldpopulationreview.com/country-rankings/depression-rates-by-country
[^5]: Robert Li Kitts, Stuart J. Goldman, Education and Depression, Child and Adolescent Psychiatric Clinics of North America, Volume 21, Issue 2, 2012,
[^6]: Catherine E. Ross, John Mirowsky, Sex differences in the effect of education on depression: Resource multiplication or resource substitution?, Social Science & Medicine, Volume 63, Issue 5, 2006
[^7]: Shawn Bauldry, Variation in the Protective Effect of Higher Education against Depression Society and Mental Health, 2015, Vol. 5(2) 145–161
