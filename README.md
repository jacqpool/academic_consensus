# A Research Tool for Insights in Academic Topics

This project applies NLP to the "Conclusions" sections of academic articles as a tool to researchers to gain insight into the field of "nutrition".  This is version 1.0 which serves as a proof of concept. Following versions will offer improved insight with the ultimate goal of measuring academic consensus in any academic or scientific field of study.

Go to Report: [PDF](https://github.com/jacqpool/academic_consensus/blob/master/reports/ResearchTool_Final.pdf)  
and presentation: [PDF](https://github.com/jacqpool/academic_consensus/blob/master/reports/ResearchTool_Presentation.pdf)

#
# Directory Content

- **Notebooks**: The notebooks for the data collection, exploratory analysis, topic modelling and summarisation are located in the /notebook directory and contain the following notebooks:
  - [1_api_get.ipynb](https://github.com/jacqpool/academic_consensus/blob/master/notebooks/1_api_get.ipynb)
  - [2_exploratory_analysis.ipynb](https://github.com/jacqpool/academic_consensus/blob/master/notebooks/2_exploratory_analysis.ipynb)
  - [3_topic_modelling_visualisation.ipynb](https://github.com/jacqpool/academic_consensus/blob/master/notebooks/3_topic_modelling_visualisation.ipynb)
  - [4_article_summarisation.ipynb](https://github.com/jacqpool/academic_consensus/blob/master/notebooks/4_article_summarisation.ipynb)
- **Data**: The CSV file containing the data obtained from the PLOS API:
  - [corpus_raw.csv](https://github.com/jacqpool/academic_consensus/blob/master/data/interim/corpus_raw.csv)
- **Models**: Saved models from Doc2Vec:
  - [d2v_docs.model](https://github.com/jacqpool/academic_consensus/blob/master/models/d2v_docs.model)
  - [d2v_sents.model](https://github.com/jacqpool/academic_consensus/blob/master/models/d2v_sents.model)
- **Reports**: The project report and presentation:
  - [ResearchTool_Final.pdf](https://github.com/jacqpool/academic_consensus/blob/master/reports/ResearchTool_Final.pdf)
  - [ResearchTool_Presentation.pdf](https://github.com/jacqpool/academic_consensus/blob/master/reports/ResearchTool_Presentation.pdf)
  - [ResearchTool_Milestone2.pdf](https://github.com/jacqpool/academic_consensus/blob/master/reports/ResearchTool_Milestone2.pdf)
  - [ResearchTool_Milestone1.pdf](https://github.com/jacqpool/academic_consensus/blob/master/reports/ResearchTool_Milestone1.pdf)
  - [ResearchTool_Proposal.pdf](https://github.com/jacqpool/academic_consensus/blob/master/reports/ResearchTool_Proposal.pdf)
  - [CapstoneProject2_ProjectIdeas.pdf](https://github.com/jacqpool/academic_consensus/blob/master/reports/CapstoneProject2_ProjectIdeas.pdf)

#
# Project Proposal

## **What is the goal?**

While it seems that there is no official approach to determine academic consensus, at least in the medical field, no algorithms or guidelines exist to this end. This is the first step towards capturing and presenting key opposing views and gaining insight into any academic field. Through automated meta-analysis, this project attempts to offer a research tool and a means to measure academic consensus. 

## **Who cares?**

This vision, in its end state, will benefit any researcher, business or academic, with access to the most current academic consensus in a field, validated by statistical models, summarised by topic analysis models and backed up with sources and citations. An automated visual Wikipedia, if you will, that requires no human contributors.

While this problem might not have clear business impact, yet, it could provide interesting information and insights on the degree of consensus in certain academic fields. An automated tool could analyse any keyword and provide a quick reference for researchers, news reporters interested in specific academic or scientific fields, as well as new technologies. A rapid meta-analysis could have further-reaching applications.

## **What data are you going to use?**

The goal of this project is to automate and scale the academic meta-analysis for any keyword representing a field in the academic domain. In this case, “nutrition”. This requires data collected from an API to satisfy automation. This project uses the Public Library of Science (PLOS) API.

## **What is your approach?**

Keeping in mind the vision of a self-service research tool, the scope of this project is larger than what could be accomplished in a single capstone project, however, the proof of concept approach allows for flexibility in testing a single case, with the idea of scaling to any field in the academic domain. To this end, and since the inspiration for this project resulted from a debate regarding “nutrition”, this project investigates the academic field of “nutrition” and “diet”. Although any academic or scientific field would suffice.

## **The Results**

The results are explained in the report. At the outset the project attempts to search for and find academic consensus. To achieve this, topic modelling must be able to effectively distinguish between topics and display it visually. This approach does not seem to achieve its aim at the moment and requires more research. 

Word and document vectorisation along with summarisation deliver interesting insights, especially with user interaction. A user can search for key words and find related words or articles and summarise content of interest. 

As it stands, the project currently leans itself more towards a research tool, rather than a tool to measure academic consensus. However, Section  5.2.3 "Hierarchical Vectorisation Topic Labelling" and "Optimum Number of Topics" explains the next steps in improving the topic model to determine academic consensus. 


#### **Found any issues?**

Any feedback or criticism is welcome. Please email me, [jacquespoolman@gmail.com](mailto:jacquespoolman@gmail.com), or find me on [LinkedIn](https://www.linkedin.com/in/jacques-poolman-a895331b).