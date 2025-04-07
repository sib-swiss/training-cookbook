# Metadata mapping 

The SIB Training group has launched an effort to standardise the terminology used to describe SIB courses, and to make training materials used to teach in SIB courses [Open and FAIR](https://sib-training.gitlab.io/sib-training-cookbook/topic/open_FAIR/). [The FAIR Data Principles are a set of guiding principles to make data findable, accessible, interoperable, and reusable](https://doi.org/10.1038/sdata.2016.18), and training materials are any digital object that can be used to deliver training. For instance, it can be a slide deck, videos with the recording of the theory, the description of the exercises including or not the solutions, datasets for the exercises, etc. 

This chapter is a collection of all the needed information to help SIB Training group and SIB members make their training materials discoverable by Google or other search engines and scrapped by TeSS. This goes through the usage of a metadata standard called BioSchemas, which is based on Schema.org.  

[Schema.org](https://schema.org/) is a set of vocabularies used to describe a lot of entities on the Internet (films, events, people, organisations, etc.). The vocabularies comprise properties that define specific entity attributes: e.g., for a film, who the director is; for a course, when the start date is; etc. These properties, and their attributes, can be used by developers to annotate their websites, allowing search engines to better understand their content, and more effectively connect searchers with information sequestered in their pages. For example, Schema.org annotated content may be promoted in ranked search results or used to generate ‘knowledge panels’ (like those typically provided on the right-hand side by Google searches). Vocabularies can be implemented on websites using three formats: RDFa, Microdata or JSON-LD, the latter being the most popular. In SIB Training webpages, the vocabularies are implemented on HTML.  

 

SIB metadata, Bioschemas and TeSS mapping 

There are three Bioschemas profiles that are of direct interest to SIB Training: 

- [Course](https://docs.google.com/spreadsheets/d/17mbgeqBxkCFvp66XdOJWyDhMLyO_PdoIAYW39xuBuS0/edit#gid=292464567) 
- [Course Instance](https://docs.google.com/spreadsheets/d/1YwvQxc3oUPusbpIsu1Q3MjXdFcQVj1Drdq_h7Xo8TOA/edit#gid=292464567) 
- [Training Material](https://docs.google.com/spreadsheets/d/1PIHHW17cnKezQrrT4JCpnCB_Q8bJEBdSZaGVcH7WH3Q/edit#gid=292464567) 

A course description page in SIB, is mapped to Course and CourseInstance. A training material page in SIB is mapped to a TrainingMaterial. The same Bioschemas profiles are used by TeSS to scrape SIB course webpages. The mapping between the terminology used in SIB (the fields in **#courseadmin**), in the Bioschemas profiles and TeSS are summarised in this table.  

At SIB, we have been using a set of specific terms in the “XXX” **#courseadmin** field to describe our courses which are based on the EDAM terminology and SIB’s own terms. EDAM terms are also used by TeSS and recommended in the Bioschemas training-related profiles. 