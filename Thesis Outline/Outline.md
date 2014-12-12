Title:	Thesis Outline  
Author:	Patrick Linehan  
Date:	20141023  

# Outline   
### This thesis outline will be using the PRISMA Checklist for systematic reviews, so items corresponding to the PRISMA Checklist have their corresponding number appended _(#)_.

1. Introduction
    1. Rationale _(# 3)_
    1. Objectives _(# 4)_
        1. Optimal dose of morphine
        1. Comparison of other opiods with morphine
1. Methods
    1. Reproducible Research
    1. PRISMA Methods 
        1. Protocol and Registration _(# 5)_
        1. Eligibility Criteria _(# 6)_
        1. Information sources _(# 7)_
        1. Search Strategy _(# 8)_
        1. Study Selection Process _(# 9)_
        1. Data Collection Process _(# 10)_
        1. Data Items _(# 11)_
        1. Risk of Bias Tool (Within Studies) _(# 12)_
        1. Summary Measures to Include _(# 13)_
        1. Synthesis Methods _(# 14)_
        1. Risk of Bias Across Studies _(# 15)_
        1. Additional Analyses _(# 16)_

    1. Prisma Results
        1. Study Flow Diagram _(# 17)_
        1. Study Characteristics (Table) _(# 18)_
        1. Study Risk of Bias (Table) _(# 19)_
        1. Study Results (Table) _(# 20)_
        1. Across Study Risk of Bias _(# 23)_
        1. Additional Analyses _(# 24)_
        
    1. PRISMA Discussion
        1. Summary of Evidence _(# 24)_
        1. Limitations _(# 25)_
        1. Conclusions _(# 26)_
        
    1. Funding _(# 27)_

# Introduction

## Rationale _(# 3)_
1. Oligoanalgesia  
1. Prior Reviews  

### Oligoanalgesia 
Oligoanalgesia is the practise of undertreatment of pain, and this is a common problem for patients with acutely painful conditions who present for emergency care. The processes that lead to undertreatment of pain are complex. One factor that contributes is a difference of opinion on what dosing regime of opioid analgesic is appropriate for treatment of acute pain. Another factor is concern over side effects, such as nausea, vomiting, respiratory depression, or hypotension. A third concern is that treating acute pain may delay making a diagnosis and lead to delay in surgical treatment and subsequent complications. 

### Prior Reviews 
There are several systematic reviews that have examined the issue of administration of opioid analgesia for acutely painful conditions. They are listed with a brief summary of their findings.

####_Opioid Analgesia for Acute Abdominal Pain in Children: A Systematic Review and Meta-analysis._ [#Poonai:2014hv]

This is a systematic review limited to children with abdominal pain that asked the primary outcome questions: compared to placebo, does opioid analgesia work (yes), does it result in increased perforation or abscesses (no), and does it result in a delay to diagnosis (no). It asked a secondary question: compared to placebo, does opioid analgesia cause increased side effects (yes, as long as continuing to have pain is not included as a "side effect" of placebo.) 

####_Analgesia in the emergency department: a GRADE-based evaluation of research evidence and recommendations for practice_.[#Lipp:2013bw]

This paper is a summary of a systematic review on seven different PICO questions performed by one author who then had his two co-authors review his findings. The three PICO questions posed that are pertinent to this review were 

> 1. For adults accessing the emergency department with acute pain, should parenteral morphine or fentanyl be used to manage acute moderate-severe pain based on reported change in pain using the visual analog scale? _(fentanyl)_
> 2. For adults accessing the emergency department with acute pain, should parenteral hydromorphone or morphine be used to manage acute severe pain based on reported change in pain using the visual analog scale? _(hydromorphone)_
> 3. For adults accessing the emergency department with acute pain, should a parenteral hydromorphone 1 + 1 mg patient-driven protocol or other intravenous opioids at any dose (physician-driven protocol) be used to manage acute pain based on reported change in pain using the visual analog scale? _(use 1 + 1)_

These are **unusually specific** PICO questions, and appear to have been driven by the publication of specific articles in the emergency medicine literature, rather than by an _a priori_ research question. The review does not include enough information to make it reproducible.

####_Analgesia in patients with acute abdominal pain_.[#Manterola:2011fk]  

This is a Cochrane systematic review of administering opioid analgesia to patients over 14 years of age with acute abdominal pain. It asked the primary question, when compared with placebo, does the use of analgesia result in "unsuitable treatment decisions" (no), and secondarily did its use improve patient comfort (yes), delay surgery (unknown), or prolong hospital stay (unknown). 

####_Parenteral opioids in emergency medicine–A systematic review of efficacy and safety_.[#NiemiMurola:2011fk]

This review was limited to adults with acute pain treated in prehospital and emergency settings. They chose to do a qualitative review due to the heterogeneity of the studies included in the review, some of which compared different opioid regimes. The primary questions in this study were: is opioid analgesia efficacious in the prehospital setting (yes), and in the emergency department (yes); and is it safe (free of severe adverse effects) in the prehospital setting (unsure), and in the emergency department (unsure).


####_Intravenous opioids for severe acute pain in the emergency department_.[#Patanwala:2010er]

This review is similar to the proposed reviews of the current thesis. It is a mixture of a systematic review and narrative review, and the method section is very limited so it is not a reproducible review. It is also five years old and due for an update.

####_Do opiates affect the clinical evaluation of patients with acute abdominal pain?_[#Ranji:2006ki]

Theis review is part of the JAMA Rational Clinical Exam series, and addressed the effect of opiates on management errors of patients with acute abdominal pain. It concludes that opiate administration had no association with management errors. It did not address the issue of dosing for pain control.

## Objectives

In emergency conditions morphine is considered the standard against which other analgesics are measured. The effects of morphine are dose-dependent, so it the first PICO question for review is 
> In patients presenting to prehospital care or the emergency department with an acutely painful condition, is there a treatment regime using intravenous morphine that is more effective at treating pain than usual care?

There are other opiates that have different side effect profiles than morphine or a different duration of action, so the second PICO question to be reviewed is

> In patients presenting to prehospital care or the emergency department with an acutely painful condition, is there another intravenous opioid that is more effective than morphine at treating pain?


# Methods

## Reproducible Research 
1. Open formats (text, markdown)
1. Open analysis
1. Open access (Open Source Software, website)
1. Open publication
1. Collaboration and tracking tools

### Open Formats 
Open formats allow for the use of Free and Open Source Software (FOSS) available to perform a systematic review and metaanalyis. This in turn opens the the study for external review by anyone. There is no lockdown to any particular piece of software. 

### Open analysis 
The steps of the analyis are clearly documented and accessible over the web. This increases the transparency of the review process and increases confidence in the process.

### Open access 
Open access over the web to each step of the process improves the reproducibility of the results and will allow the review to be updated easily in the future. Each step of the study will be maintained in a git repository that others can copy and use.

### Open Publication
Open publication will allow anyone interested to view the results over the internet without any restrictions.

### Collaboration and tracking tools
In computer programming version control software is used to keep track of changes to software and to allow people to collaborate on a project without interfering with each others work. Git, n open source program, will be used to provide version control and collaboration for this review.

## PRISMA Methods _(Checklist Item #)_

### Protocol and Registration _(# 5)_

These reviews will use the PRISMA ( Preferred Reporting Items for Systematic Reviews and Meta-Analyses) [#PRISMA] statement and checklist as a guide.  It will be registered in the PROSPERO [#PROSPERO] database of systematic reviews.  

At each step below where two reviewers independently make assessments and then compare their results the degree of concordance between the two reviewers will be reported.

### Eligibility Criteria _(# 6)_
1. Inclusion criteria  
	1. Randomised controlled trials that compare an opioid analgesic to placebo or to
	another dose of the same or a different analgesic.
	1. Cohort studies for evidence on secondary outcomes (adverse effects)
1. Exclusion criteria
	1. Abstracts, conference proceedings, that do not contain enough information


### Information sources _(# 7)_

1. Medline
1. Embase
1. CENTRAL
1. CINAHL
1. Clinicaltrials.gov

### Search Strategy _(# 8)_

The search strategiews for each database will be developed in concert with a librarian and then peer-reviewed by another librarian.

### Study Selection Process _(# 9)_

Study selection will be taken in two steps: first, there will be a review of titles and abstracts of the sudies found by electronic search by two different reviewers using a prespecified data form. The discrepancies between the two reviewers in choosing studies for further analysis at this stage will be resolved by consensus between the two reviewers.
Second, the studies identified in the first stage will be retrieved as full text, and these will in turn be reviewed by two reviewers using a prespecified data form to analyse the studies for quality of methods.  Again, the discrepancies will be resolved by consensus. 

### Data Collection Process _(# 10)_

Data will be collected by two reviewers using a prespecified data form. Disagreements about the data will be resolved by consensus.

### Data Items _(# 11)_
1. Study eligibility
    1. inclusion criteria
    
1. Study design
    1. randomisation
    1. allocation concealment
    
1. Study participants
    1. age
    1. gender
    1. presenting complaint
    1. final diagnosis
    
1. Treatment
    1. drug and comparison (placebo or other active drug)
    1. dose, fixed or weight based
    1. treatment regime, single or multiple dose, patient guided analgesia
    1. co-adminstration of other drugs (antiemetics, NSAIDS)

1. Pain (numeric score, VAS, other scoring system, patient satisfaction with treatment)
    1. baseline pain
    1. pain at other times (fixed interval, at discharge or admission)
    
1. Adverse events
    1. nausea and vomiting
    1. respiratory depression (minor: decreased respiratory rate or needing supplemental oxygen, major: needing naloxone or an airway intervention)
    1. rescue analgesia
    1. persistent pain
    1. diagnostic interference (has been assessed in other studies and will not be a major outcome in these reviews)
    
1. Follow up duration
    1. while in emergency
    1. after discharge or admission

1. Withdrawals, lost to follow up

1. Study risk of bias

    
### Risk of Bias Tool (Within Studies) _(# 12)_

Randomized controlled trials will be assessed using the Cochrane Risk of Bias Tool.
Cohort studies will be assessed using the SIGN tool for cohort studies.
### Summary Measures to Include _(# 13)_

The main summary  measure will be the mean difference in pain score. 
Secondary measures will be rates of adverse events.

### Synthesis Methods _(# 14)_
### Risk of Bias Across Studies _(# 15)_
### Additional Analyses _(# 16)_

Subgroups that will be analysed include:

1. prehospital and emergency department studies
1. adult and pediatric patients
1. studies in different risk of bias categories

## Prisma Results

### Study Flow Diagram _(# 17)_

The results of the literature search and study selection will be presented in a flow diagram.

### Study Characteristics (Table) _(# 18)_
### Study Risk of Bias (Table) _(# 19)_
### Study Results (Table) _(# 20)_
### Across Study Risk of Bias _(# 23)_

There will be a summary of publication bias and risk of biased reporting.

### Additional Analyses _(# 24)_

There will be tables summarizing study characteristics, risk of bias, and results, and additional analyses.

## PRISMA Discussion
### Summary of Evidence _(# 24)_

The summary of evidence will be done using the Grading of Recommendations Assessment, Development and Evaluation (GRADE)[#GRADE] guidelines.

### Limitations _(# 25)_

The limitations of the review will be discussed.

### Conclusions _(# 26)_

Recommendations will be made as recommended in the GRADE guidelines. [#Andrews:2013cm]

### Funding _(# 27)_




[#Poonai:2014hv]: Poonai N, Paskar D, Konrad S-L, Rieder M, Joubert G, Lim R, et al. Opioid Analgesia for Acute Abdominal Pain in Children: A Systematic Review and Meta-analysis. Academic emergency medicine : official journal of the Society for Academic Emergency Medicine. 2014 Nov;21(11):1183–92.  

[#Lipp:2013bw]: Lipp C, Dhaliwal R, Lang E. Analgesia in the emergency department: a GRADE-based evaluation of research evidence and recommendations for practice. Critical care (London, England). 2013 Mar 19;17(2):212. 

[#Manterola:2011fk]: Manterola C, Vial M, Moraga J, Astudillo P. Analgesia in patients with acute abdominal pain. Cochrane database of systematic reviews (Online). 2011;(1):CD005660.  
[#Patanwala:2010er]: Patanwala AE, Keim SM, Erstad BL. Intravenous opioids for severe acute pain in the emergency department. Ann Pharmacother. 2010 Nov;44(11):1800–9. 

[#NiemiMurola:2011fk]: Niemi-Murola L, Unkuri J, Hamunen K. Parenteral opioids in emergency medicine–A systematic review of efficacy and safety. Scandinavian Journal of Pain. Elsevier; 2011;2(4):187–94. 

[#Ranji:2006ki]: Ranji SR, Goldman LE, Simel DL, Shojania KG. Do opiates affect the clinical evaluation of patients with acute abdominal pain? JAMA. American Medical Association; 2006 Oct 11;296(14):1764–74. 

[#PRISMA]: <http://www.prisma-statement.org>

[#PROSPERO]: <http://www.crd.york.ac.uk/PROSPERO>

[#GRADE]: <http://www.gradeworkinggroup.org/index.htm>

[#Andrews:2013cm]: Andrews J, Guyatt G, Oxman AD, Alderson P, Dahm P, Falck-Ytter Y, et al. GRADE guidelines: 14. Going from evidence to recommendations: the significance and presentation of recommendations. Journal of clinical epidemiology. 2013 Jul;66(7):719–25. 