---
title: "Experimental Design Study"
date: 2019-06-10
tags: [Experimental Design, Simulation]
header:
  overlay_image: "/images/danapointharbor.jpg"
  show_overlay_excerpt: false
excerpt:
mathjax: true
---

# Effects of Alcohol and Cannabis on Islanders’ Serotonin Levels
#### *Justin Yee, Anthony Tooley, Michelle Vang*

**I. Abstract**        
The purpose of this study was to learn about the effectiveness of alcohol and cannabis on blood serotonin levels. Especially in times when stress levels are high and emotions are negative, these two substances are often seen as short-term means to alleviate these feelings. As this behavior is reasonably apparent at university, we as undergraduates, felt intrigued to learn more about if the usage of alcohol and cannabis actually are effective coping mechanisms or if their effects are simply results of the placebo effect. Serotonin, a neurotransmitter also known as the happy chemical, has been linked to depression and the treatment of depression. To help us approach a better understanding of alcohol and cannabis effects on mood, we decided upon a two-way basic factorial design with one blocking factor, age. The results of our study indicate that there is a strong relationship between the treatment substances and the dosage levels of each treatment. Additionally, there was a significant difference in the mean serotonin change for the treatments of cannabis and alcohol, with cannabis showing higher levels of serotonin change compared to alcohol.

**II. Introduction**       
According to World Health Organization, it is estimated that over 300 million people across the world have been affected by depression. With the pervasiveness of this mental health condition, many have turned to substances such as alcohol and cannabis to manage their negative thoughts and emotions. In particular, there is a high incidence of alcohol and cannabis use among college students compared to the overall population. Additionally, it has been found that college students also experience depression at a higher proportion compared to the overall population, yet only about half of college students seek outside help in dealing with their depression. As such, there is clear evidence for the general public to show great concern over depression among young adults, and an increased usage of alcohol and cannabis among the college population. This study will help us determine the effectiveness of alcohol and cannabis usage as a common coping mechanism among college students.    

When attempting to measure the effects of alcohol and cannabis on one’s depression and negative emotions, an objective measurement over subjective measurement is preferred. The objective measurement that we chose to use in this study is serotonin levels as measured by blood serotonin tests. Serotonin is a neurotransmitter chemical in the brain that has been linked to levels of well-being and happiness. Common medical treatments for depression attempt to regulate serotonin levels in individuals who have lower serotonin levels than the average person. With this study, we will focus on the link between the substances of alcohol and cannabis and serotonin levels when subjects are evoked with sad emotions and memories.   

Current literature suggests that there is a definite connection between alcohol and cannabis with brain cognition, as participants in studies past have performed cognitive tasks significantly different from control groups. Additionally, there appears to be a clear effect between these substances and on the user’s mood. However, there are mixed opinions on the exact effects of alcohol and cannabis on the production of serotonin.    

Therefore, the aspirations for this study are to shed light on the serotonin level changes corresponding to alcohol and cannabis use among college-aged individuals. By answering the question about the possible association between these substances and serotonin levels, we hope to gain some insight into the rationale of why college students are choosing to use alcohol and cannabis at a high rate. Perhaps if, at a neural chemical level, these substances are altering the moods of individuals who take them, we can better understand the effects of such substances and look further into employing alcohol and cannabis in moderation to treat depression.

**III. Methods**

__**Participants:**__    
For this study, we plan to focus on young adults ages ranging from 18 to 24 years old. Our sample of virtual participants will be gathered from an online resource known as the Island on a voluntary basis. The participants will be selected from Macondo, the most populated city on the island. Treatments will be randomly assigned.

__**Design:**__        
The experimental design we will implement in this study is a two-way basic factorial with one blocking factor. The blocking factor of choice will be gender(male and female). Some studies in the past have suggested a possible difference in male and female serotonin production levels as well as different tolerance levels to alcohol and cannabis. For this reason, we have chosen to block by gender, considering it as a nuisance factor that we are not interested in directly studying its effects on serotonin levels.

![Factor Diagram](/images/Factor Diagram.PNG)

Prior to any treatment, we will have each islander participating relive their sad memories for one minute. This treatment will be held constant for each participant and is conducted to simulate the negative emotions that are present during depression. The substance treatment factor will have three levels: alcohol, cannabis, and control. The dosage treatment factor will also have three levels: 1 drink, 2 drinks, and 3 drinks. We will also consider the interaction between these two factors of substance and dosage. The response variable that we will measure will be the serotonin level that is measured by the blood serotonin test. This response variable will be measured after the one minute of reliving sad memories, but prior to the two treatment factors of substance and dosage. Then, serotonin levels will be measured following the treatment of substance and dosage to compare the difference in the levels before and after treatment.

__**Instruments:**__

To conduct our study, we will be using virtual tasks to measure the blood serotonin level of the Islanders and to administer our treatments of interest.

__**Procedure:**__
1. First, we will have the islanders from the city of Macondo volunteer for the study until we have a total of 198 individuals, split evenly into 99 males and 99 females (2 blocks).

2. Secondly, we will randomly assign each of the individuals in their respective blocks to a treatment group. The treatment groups are the following:

  1. 1 drink of red wine, 2 drinks of red wine, 3 drinks of red wine
  2. 1 drink of cannabis tea, 2 drinks of cannabis tea, 3 drinks of cannabis tea
  3. 1 drink of herbal tea, 2 drinks of herbal tea, 3 drinks of herbal tea (Control Group)

3. Next, every islander will relive their sad memories for 1 minute. This is done to simulate the emotional state of a depressed person.

4. Now, we will measure each participant’s serotonin levels by administering a blood serotonin test to establish as their baseline levels before treatments.

5. After they relive their sad memories and have their serotonin levels measured, each participant will take their treatment at a certain dosage, dependent upon the treatment group they were randomly assigned to.

6. After administering this treatment, we will again measure each subject’s serotonin levels using the blood serotonin test.

7. Lastly, we will compute the difference between the before-treatment and after-treatment serotonin levels and use this difference as our response variable moving forward in our analysis.    

**IV. Data Analysis**    
__**Statistical Analysis:**__    
We utilized R to construct an ANOVA table with the corresponding F-tests and p-values to determine statistical significance of our results. We also constructed plot diagnostics for the Two-Way Effects Model with One Blocking Factor to determine the validity of our model.

__**Sample Size Determination:**__    
We selected an alpha of 0.05 and a power of 0.80 a priori. Also, we selected an effect size of 0.25 as a relatively small effect size to be detected under the significance testing thresholds that we have set. Using a numerator df of 4, since the Interaction Factor has 4 degrees of freedom, and there are a total of 18 groups in our study. Using G-Power, we calculated a total sample size of 197 to achieve these specifications, and we will round up to 198 participants to have a balanced design.

![Gpower sample size](/images/Gpower.png)

**V. Results**    
The two-factor, randomized block design model we have chosen for our experimental analysis is depicted below.

![Model Formula](/images/Model Formula.PNG)

The diagnostic plots for the model are shown below. They confirm that the model is valid based on the assumptions of normally distributed error terms and constant variance of the error terms.

![Diagnostic plots](/images/Rplot.png)

The results of our experiment are summarized in the following graphics shown below. These graphics aim to capture the information present in the Two-Way Effects Model with One Blocking Factor(Sex). Following these data visualizations and tables, the conclusions that we draw from our data will be listed in section **VI. Conclusions and Further Study**.


![](/images/AOV Summary Output.PNG)
*Figure 1: Two-way ANOVA output.*

![](/images/Tukey HSD Conf Int.PNG)
*Figure 2: 95% Tukey HSD Confidence Intervals*

![](/images/Effects Model Output.PNG)
*Figure 3: Effects Model Output*

![](/images/Substance Interaction Plot.PNG)
*Figure 4: An interaction plot between each treatment group and the number of doses of each substance.*

![](/images/Serotonin Boxplot.PNG)
*Figure 5: Box plot of the mean blood serotonin levels for each substance.*

![](/images/Dosage Boxplot.PNG)
*Figure 6: Box plot of the mean blood serotonin levels for the number of doses of each substance.*

![](/images/Substance Scatterplot.PNG)
*Figure 7: Dot plot of the mean change in serotonin level for each substance.*

![](/images/Dosage Scatterplot.PNG)
*Figure 8: Dot plot of the mean change in serotonin level for the number of doses for each substance.*

**VI. Conclusions and Further Study**    

From the ANOVA output of our Two-Way, One Blocking Factor Effects Model, we can conclude the following:   

1. There is a statistically significant relationship between the Substance Factor (Alcohol, Cannabis, Control)
2. There is a statistically significant relationship between the Interaction of Substance and Dosage.

This experiment was designed in order to test the different effects both alcohol and cannabis may have on the negative emotions present during depression in college aged students. Our results aim to be thorough enough to either reject or fail to reject the null hypothesis that there is no different effects between these substances on emotions or depression.    

To begin our experiment, we calculated a sample size from a power of 0.8 and a significance level of 0.05 to comply with our Two-Way, One Blocking Factor Effects Model. Initially we calculated a sample size of 197 participants, however we rounded up to 198 to have an even number of participants in each group. First, we recorded the participants blood serotonin levels after reliving negative memories, as well as forty minutes after each group consumed their assigned substance. We decided to block our design based on gender and measured the effects of each substance and the control at three different doses.     

Our ANOVA output shows that both the substances used as well as the interaction between the substance and the dosage were both significant factors affecting blood serotonin levels, however the specific dosage of the substance was not. The plots that follow our ANOVA attempt to visualize the variability and relationships, if any exist, between our treatment substances, block, and dosage levels.    

From our interaction plot, we observe a clear relationship between alcohol and cannabis across all dosage levels. However our results vary for the control group (herbal tea) depending on the dosage level.    

Our boxplots show the variability between the treatments and also between the dosage levels. In our boxplot for our treatment groups, we observe the means of cannabis and alcohol are significantly different from one another.       

We observe that between our two treatment substances and the control, cannabis has the greatest effect on serotonin levels. The dot plots and boxplots above convey this, as well as show us that the most significant dosage level of the three in our experiment were groups consuming treatments with 2 doses. Possibly, this may be due to the fact that 1 dose was on average not strong enough for our group of participants, while 3 doses was on average too strong.     

One limiting factor in our experiment was that we were unable to control the amount of treatment consumed per dosage, as The Island only gave us the ability to select fixed rates. In a similar future study, this is one factor that could drastically change the outcome of the results. Another drawback of the study was that we had no prior knowledge of past mental illness or depression in our participants, or whether or not an individual had a history of substance abuse prior to experimentation. Therefore, being able to hold constant some criteria within these areas could allow for a more significant final outcome. We were also forced to perform our experiment within each participant’s home, where we had an uncontrolled environment which could have potentially allowed for underlying issues to occur in our results.      

Nevertheless, we hope our results can show how each of these two substances affect, and to what degree, college-aged individuals, providing insight into the reasons individuals of this age group tend to rely on them.    

**VII. References**

Gordis, Enoch. Are Women More Vulnerable to Alcohol Effects: A Commentary By NIAAA Director Enoch Gordis, M.D.. National Institute on Alcohol Abuse and Alcoholism. Vol. 46       

Heishman, Stephen. Arasteh, Kamyar. Stitzer, Maxine. Comparative Effects of Alcohol and Marijuana on Mood, Memory, and Performance. Pharmacology Biochemistry and Behaviour, Vol 58(1), 93-101.    

Jovanovic, H., Lundberg, J., Karlsson, P., Cerin, Å, Saijo, T., Varrone, A., Nordström, A. (2008). Sex Differences in the Serotonin 1A Receptor and Serotonin Transporter Binding in the Human Brain Measured by PET. NeuroImage, 1408-1419.    

Nishizawa, S., Benkelfat, C., Young, S. N., Leyton, M., Mzengeza, S., Montigny, C. D., Diksic, M. (1997, May 13). Differences Between Males and Females in Rates of Serotonin Synthesis in Human Brain (Vol. 94 no. 10.).  

Pihl, Robert, Peterson, Jordan. Alcohol, Serotonin, and Aggression.(1993) (Vol. 17 no. 2.). Alcohol Health and Research World,  113-116.    

Solomons, K., Neppe, V.M. Cannabis - its clinical effects. S Afr Med J 1989; 76: 102-104.
