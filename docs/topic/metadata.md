# Metadata mapping 
The SIB Training group has launched an effort to standardize the terminology used to describe SIB courses and to make training materials used in SIB courses [Open and FAIR](https://sib-training.gitlab.io/sib-training-cookbook/topic/open_FAIR/). The [The FAIR Data Principles](https://doi.org/10.1038/sdata.2016.18) are a set of guidelines to make data findable, accessible, interoperable, and reusable. Training materials can be any digital object used to deliver training, such as slide decks, recorded videos, exercise descriptions (with or without solutions), datasets for exercises, etc.

This chapter provides all the necessary information to help the SIB Training group and SIB members make their training materials discoverable by Google or other search engines and scraped by TeSS. This involves using a metadata standard called BioSchemas, which is based on Schema.org.

[Schema.org](https://schema.org/) is a set of vocabularies used to describe various entities on the Internet (films, events, people, organizations, etc.). These vocabularies include properties that define specific entity attributes, such as the director of a film or the start date of a course. Developers can use these properties and attributes to annotate their websites, allowing search engines to better understand their content and connect searchers with relevant information. For example, [Schema.org](https://schema.org/) annotated content may be promoted in ranked search results or used to generate knowledge panels (like those provided by Google searches). Vocabularies can be implemented on websites using three formats: RDFa, Microdata, or JSON-LD, with JSON-LD being the most popular. In SIB Training webpages, the vocabularies are implemented in HTML.

#### SIB Metadata, BioSchemas, and TeSS Mapping

There are three BioSchemas profiles of direct interest to SIB Training:

- [Course](https://docs.google.com/spreadsheets/d/17mbgeqBxkCFvp66XdOJWyDhMLyO_PdoIAYW39xuBuS0/edit#gid=292464567) 
- [Course Instance](https://docs.google.com/spreadsheets/d/1YwvQxc3oUPusbpIsu1Q3MjXdFcQVj1Drdq_h7Xo8TOA/edit#gid=292464567) 
- [Training Material](https://docs.google.com/spreadsheets/d/1PIHHW17cnKezQrrT4JCpnCB_Q8bJEBdSZaGVcH7WH3Q/edit#gid=292464567) 

A course description page in SIB is mapped to Course and CourseInstance. A training material page in SIB is mapped to TrainingMaterial. TeSS uses the same BioSchemas profiles to scrape SIB course webpages. The mapping between the terminology used in SIB (the fields in **#courseadmin**), the BioSchemas profiles, and TeSS is summarized in this table.

At SIB, we use specific terms in the “XXX” **#courseadmin** field to describe our courses, based on EDAM terminology and SIB’s own terms. EDAM terms are also used by TeSS and recommended in the BioSchemas training-related profiles.
