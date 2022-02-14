# Lecture 2 - 14/10/2021: 

- Checklist and hints for good graphics. [Slides](https://github.com/alegrand/SMPE/blob/master/sessions/2021_10_Grenoble/02_Check-list-good-graphics-tableau-en.pdf).
- Getting information from a data set: [Slides](https://github.com/alegrand/SMPE/blob/master/sessions/2021_10_Grenoble/02_Stat-desc1-en.pdf).
     - Vocabulary: Population, sub-population, variables and their types: quantitative and qualitative.
     - Statistical approaches:  
          1.  Defining the protocol to be followed for data collection.
          2.  Data collection, coding, cleaning.
          3.  Data exploration without trying to model them.
          4.  Data pre-processing.
          5.  If the data are from a sample, statistical modelling of the data.
          6.  Forecasting and/or decision making (answer to the initial question).
- **Activity**: Getting the wrong picture from the data 


# Lecture 3 - 21/10/2021:

- What is tidy data and why it must be used before any data processing ? [Slides](https://github.com/alegrand/SMPE/blob/master/sessions/2021_10_Grenoble/03_Tidy-data.pdf)
  - Tidy data = clean data.  They make the data analysis easier to model, to visualize and process. 
  - Any non-tidy data can be transformed to tidy-data. This process is called "Tidying". It may be performed using an available package in R called _dplyr_
- Open science: 
  - Sharing science and knowlegde is very important for ourselves and others.
  - Multiple tools exist to make this happen: Gitlab, Github and the more reliable one is Software Heritage
  - The most known reproducible research practices :
    1. Taking notes and documentations
    2. Controling software Environment. Tools: Containers and Package managers like GUIX
    3. Version controlling and archieving : FAIR principles (Findable, Accessible, Interoperable and Reusable). Tools: Articles archives like HAL or ArXiv. Data archives like zenodo and Software Archive like Software Heritage


# Lecture 4 - 28/10/21

- Before starting any project using data. First necessary step must be: describing _Data management plan_.In order to make the reseach reproducible and the data FAIR so as to gain time. And it should include:
   1. Data description and collection or re-use of existing data: 
        - Describe data to be re-used and Describe new data to be collected or produced
        - Detail kind, format and volume of data
   2. Documentation and data quality
        - Describe the metadata accompanying your data
        - Use controlled vocabularies if relevant
        - Explain organization and followed methodology
        - Add README file describing how information is captured and recorded
   3. Storage and backup during the research process
        - Create Minimum 3 back-ups on 2 different supports at 2 distant locations
        - Explain data recovery strategies in the event of an incident
        - Who will have access to the data during the research 

   4. Legal and ethical requirements, codes of conduct
        - _Personal Data_ are the data that can directly identify the person: last name, first name, address, picture, voice or Data that can indirectly identify the person: Telephone number, cross-referencing.
        - _Sensitive personal data_ like: Presumed race or ethnicity, Political opinions, Philosophical or religious beliefs, Trade union membership or Sexual orientation ...
        - Take responsabilities for data processing and protection
        - Detail achievement of compliance with GDPR
        - consider possibal ethical issues
   5. Data sharing and long-term preservation
        - Share data using A _TRUSTWORTHY REPOSITORY _.
      
   6. Data management responsibilities and resources 
        - Define Who will be responsible for Data Management and What resources will be dedicated to data management

- Introduction to data statistics.
     - Data Production:
          1. Define the purpose of producing the dataset
          2. Describe the method and approach useed to collect the data
          3. Describe the nature of the dataset, its characterization and semantic.
     - Analysis of the set of variables:
          1. Identification of the variables types
          2. Identification of the variables role
          3. Identification of the variables semantic
     - Usage of variables:
          1. Response Variables
          2. Explanatory Variables
          3. Univariate or Multivariate
     - Data production process : Global Process = Question ⇨ Experiment, Survey ⇨ Decision

     - Criteria for the quality of data (from EuroStat):
          1. Relevance
          2. Accuracy
          3. Timeliness
          4. Comparability
          5. Coherence
          6. Accessibility
          7. Interpretability
          8. Unicity
          9. Conformity to Norm
          10. Consistency

     - Pre-processing of data: Before any analysis:
          1. Question on the Quality 
          2. Identification of Data Problems
          3. Distributions of Data Problems
          4. Processing Missing Data

# Lecture 5 - 18/11/21:
- Review Challenger Exercice about Confidance interval
- Short and quick tuto about ggplot. A framewrok for displaying plots using python or R.
- Working on Parallel Quicksort by changing plots and parameters.

# Lecture 6 - 25/11/21
- Probabilistics and statistics: [Slides](https://github.com/alegrand/SMPE/blob/master/lectures/3_introduction_to_statistics.pdf)
     - Variance, Expected values and Probability distribtution
     - Central limit theorem and Normal distribution
     - Comparing alternatives using confidence interval: if overlap then we can not conclude anything. If they do not then they are different for sure. If they overlap, we may compute the difference between both.
    
# Lecture 7 - 2/12/21
- The course was about Linear regression. The [Slides](https://github.com/alegrand/SMPE/blob/master/sessions/2021_10_Grenoble/07_linear_regression.pdf) are complete and important.

# Lecture 8 - 9/12/21
-  The course was about Analysis of variance (one factor and two factor ANOVA). The [Slides](https://github.com/alegrand/SMPE/blob/master/sessions/2021_10_Grenoble/08_anova.pdf) are complete and important.


# Lecture 10 - 06/01/22
- The lecture was about Design of experiments. [Slides](https://github.com/alegrand/SMPE/blob/master/lectures/5_design_of_experiments.pdf)

# Lecture 11 - 06/01/22 and Lecture 12 -  20/01/22

- THREE PILLARS
     1. Ethics
          - Deep questions raised by science progress on society; Moral values motivating our acts and their consequences.
          - Retrospective [law, approval] vs prospective view
     2. Scientific Integrity
          - Rules governing research practices. Different definitions in different countries.
          - Examples of no respect of integrity: 
               - Data Fabrication
               - Data Falsification
               - Photo manipulation(Examples: Data manipulation)
               - Plagiarism : self plagiarism and Citation plagiarism
               - Authorship, guest authorship, and ghostwriting
           

     3. Deontology
          - Garantee Independence, equity of civil servants and  intellectual property
          - Avoid Conflicts of interest, harassment
        
