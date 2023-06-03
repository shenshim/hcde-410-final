Notebook contains markdown cells before every code cell, and these markdown cells clearly describe what steps are being performed in the following code cell - DELETE LATER

# Generations: A Study of the Life and Health of LGBTQ People in a Changing Society, United States 2016-2019
    
## The dataset can be accessed [here](https://www.icpsr.umich.edu/web/DSDR/studies/37166/summary). 

**It is sourced from the ICPSR (Inter-university Consortium for Political and Social Research), including members such as Johns Hopkins University and the Mayo Clinic.** The ICPSR is the world's largest collection of digital social science data, providing leadership training in data access, curation, and methods of analysis for the social science research community.This dataset was selected to examine health and well-being across three generations of LGBTQ+ people in America. **In total, 366,644 participants of the LGBT+ community were screened by Gallup for inclusion in the Generations study** (Demographic information redacted).

*Variables to note: Wave 1 (W1) is the oldest, farthest back in time, Wave 2 (W2) is the generation after, and Wave 1 (W1) is the currentmost generation at the time the study was conducted (2016-2019). 
    
## Mini Abstract 

The study explores identity, stress, health outcomes, and health care/service utilization among the three generations of adults who came of age during different historical contexts. Being a member of the community, I am interested in this data and wish to broaden my knowledge of how the treatment (social, medical, personal) of LGBTQ+ people in America has changed over different generations. The study will cover three main topics: **societal attitudes, healthcare outcomes (gender affirming treatments, HIV care), and mental health of queer youth across three generations.**

## Related Works

Numerous studies have examined changes in attitudes towards LGBTQ+ individuals across different generations. For example, a study conducted by Herek and colleagues found that younger generations tend to exhibit more positive attitudes and greater support for LGBTQ+ rights compared to older generations. Other research has explored the impact of generational differences on attitudes towards same-sex relationships, transgender rights, and overall LGBTQ+ acceptance. [1][2]

Additionally, several studies have examined changes in healthcare access and utilization among LGBTQ+ individuals over time. For instance, a study by Grant and colleagues found that LGBTQ+ individuals reported improvements in healthcare access and more affirming experiences with healthcare providers over the years. Other research has investigated the impact of inclusive healthcare policies and the availability of affirming treatments on the well-being and health outcomes of LGBTQ+ individuals. [3][4]

Previous studies have explored the availability and utilization of affirming resources among LGBTQ+ individuals across different generations. For example, research has examined changes in the types of support networks utilized by LGBTQ+ individuals, considering factors such as generational differences, geographic location, and community dynamics. Studies have also investigated the impact of affirming resources on mental health, social connectedness, and resilience among LGBTQ+ individuals.[5][6][7]

References:

1. Bränström R, Hatzenbuehler ML, Pachankis JE. Sexual orientation disparities in physical health: age and gender effects in a population-based study. Soc Psychiatry Psychiatr Epidemiol. doi: 10.1007/s00127-015-1116-0. 

2. Pachankis JE, Goldfried MR. Expressive writing for gay-related stress: psychosocial benefits and mechanisms underlying improvement. J Consult Clin Psychol. doi: 10.1037/a0017580. PMID: 20099955.

3. https://www.thetrevorproject.org/survey-2023/#support-youth

4. National Academies Press. (2011). The Health of Lesbian, Gay, Bisexual, and Transgender People: Building a Foundation for Better Understanding.

5. https://www.thetrevorproject.org/survey-2023/#access-to-care

6. Herek, G. M. (2000). The psychology of sexual prejudice. Current Directions in Psychological Science, 9(1), 19-22. 

7. https://www.thetrevorproject.org/survey-2023/

## Methodology 

I have exported the dataset in R, creating derived variables or recode existing variables as needed to align with the research questions. I also used the interface given to me on the data sharng platform to refer to its codebook when filtering the dataset to include relevant variables and observations for each research question. I am unable to share some parts of the data (liscence and agreement from ICPSR), but I have included data visualizations to go along with each finding. 

## Limitations

There are a few major limitations to our study, the first pertaining to ethics. There is a lot of sensitive data in this dataset, and filtering through that would have been impossible if it weren't for the built-in interface. This data is meant for research purposes, wih a pretty strict usage guideline. The amount of variables, themes, and questions within it are massive so I have had to greatly condense and redact information. Ultimately I am exploring how the lives of lives of LGBTQ+ people in America changed over three generations. This branches out to examining changes in terms of accessible care, affirming treatments, and mental health of youth.

## Research Questions, Hypothesis, and Findings

1: ***How have attitudes towards LGBTQ+ individuals change across three generations in America?***
- Sub 1: Are there significant differences in identity exploration and self-acceptance among LGBTQ+ individuals across generations? -

- Hypothesis for Q1) 

There will be an increase in positive attitudes towards LGBTQ+ individuals across three generations in America. The hypothesis is based on the assumption that societal attitudes towards LGBTQ+ individuals have generally become more accepting over time. This can be attributed to increased visibility, advocacy efforts, and legal advancements that have aimed to promote equality and inclusivity. 

LGBTQ+ individuals from younger generations will exhibit higher levels of identity exploration and self-acceptance compared to older generations. This stems from the idea that younger generations have grown up in a more accepting and inclusive environment, with greater exposure to diverse gender and sexual identities. As a result, they may feel more empowered to explore their identities and be more accepting of themselves compared to older generations who may have faced more stigma and discrimination.

- Presentation)

For RQ 1, I have deployed line graphs and piecharts illustrate the percieved changes in attitudes towards LGBTQ+ individuals across generations.

- Results for Q1) 

![Society Wave 1](hcde-410-final/Data vis/Society W1.png)

![Society Wave 2](hcde-410-final/Data vis/Society W2.png)

![Society Wave 3](hcde-410-final/Data vis/Society W3.png)

Refering to the visualizations above, for the statement, "Society isn't improving for people like me", the overall % of people who chose disagree-strongly disagree rose as generations passed. 

This could be indicative of an improved perception of societal efforts to make the world a more inclusive place however, it was not a drastic or notable change. In wave 2 there seems to be an increase of people who felt strongly on both sides of the spectrum (strongly agree / strongly disagree). Implications may point to a societal shift near wave 2.  

![My Community Wave 1](hcde-410-final/Data vis/My comm W1.png)

![My Community Wave 1](hcde-410-final/Data vis/My comm W2.png)

![My Community Wave 1](hcde-410-final/Data vis/My comm W3.png)

Based on the statement, "My Community is A Source of Comfort", we can infer how LGBT+ spaces have chanced or become more/less welcoming as generations passed. The data you see above is really interesting, as it shows that there was (again) a bit of a disruption in sentiment in wave 2. It really makes me wonder what could have caused people to have such mixed perceptions of not only society but their own communities at the time. 

At its core, the data points to an increased sense of community and belonging for LGBT+ adults as time passed. The sentiment of belonging seems to have also gotten much more stable from wave 1 to wave 3. 

## Discussion for R1: ***How have attitudes towards LGBTQ+ individuals change across three generations in America?***

Frankly, the topic of increased societal and individual attitudes towards LGBT+ individuals is not only a subjective topic, but the findings from these graphs alone falls short of capturing its nuances. Through from our findings, both societal and communal percetions of belonging have increased from wave 1-3, we should not take it as a concrete answer. I am however, curious to find out what caused the societal and communial shift/division during wave 2. 

2: ***How has access to healthcare and services improved or changed for LGBTQ+ individuals over time?***
- Sub 1: How has the availability and utilization of affirming treatments for LGBTQ+ individuals evolved across generations? -
- Sub 2: What are the experiences of LGBTQ+ youth in terms of mental health and well-being compared to previous generations? -

- Hypothesis for Q2) 

Access to healthcare services for LGBTQ+ individuals has improved over time, leading to increased utilization and better health outcomes. This hypothesis is based on the expectation that as societal attitudes have become more accepting, healthcare systems have made efforts to address the specific needs of LGBTQ+ individuals. 

This includes providing LGBTQ+ culturally competent care, removing barriers to access, and increasing awareness among healthcare providers, which may have led to improved healthcare access and ultimately better health outcomes. Affirming treatments for LGBTQ+ individuals have become more available and have been improved across generations. The hypothesis assumes that advancements in medical and psychological understanding of LGBTQ+ identities have led to the development and increased availability of affirming treatments. 

- Presentation) 

For RQ 2, I will present the results of statistical tests in line and pie charts, showing the differences in healthcare perceptions across generations.

- Results for Q2)

![Seeking Healthcare - COMPOSITE OF W1,2,3](hcde-410-final/Data vis/When seeking healthcare.png)

Here is a composite view of all waves in relation to the statement, "When seeking healthcare… I worry that evaluations of me may be negatively affected by my sexual orientation or gender identity". 

![Place to go when sick W1](hcde-410-final/Data vis/Place to go when sick W1.png)

![Place to go when sick W2](hcde-410-final/Data vis/Place to go when sick W2.png)

![Place to go when sick W3](hcde-410-final/Data vis/Place to go when sick W3.png)

Additionally, for the question, "Is there a place that you usually go to when you are sick or need advice about your health?" the responses are depicted in the pie chart. 

Around 30% of LGBT+ adults feel worried (across all generations) that when seeking healthcare, their evaulations may be negatively affected due to their gender orientation or sexual identity. In regards to the visualizations below, it also does not appear like there has been much improvements surrounding access to healthcare or a place to go when people feel ill. 

It's interesting to see how vastly different community, societal, and personal perceptions of LGBT+ people have changed over the years, yet the amount of people who feel worried about healthcare is still very high + there is no noticable improvements in the access to a place to go when sick. 

My hypothesis stands incorrect- I had thought that as generations passed there would have been an improvement for both factors listed above. I do not doubt that there have been biomedical advancements and improvements in facilities that help, but access to healthcare is such a systemic issue. 

## Conclusion

This report and study has shown that whilst communal and societal attitudes have changed for the better in the lives of LGBT+ adults, more systemic changes such as changes in healthcare and access have remained relatively stagnant. I believe there is an implication/broader to this, considering how universal healthcare is not available in the States (moreso for gender affirming treatments or services for LGBT+ people). 


