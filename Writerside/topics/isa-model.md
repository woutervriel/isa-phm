# The ISA Model


The ISA standard is commonly used for collecting, currating, managing and reusing datasets in the field of life, environmental and biomedical sciences such as toxicology and plant sciences. 

The <a href="https://rioned-web-prod.azurewebsites.net/media/1iljdccy/ribx-formaat-voor-inspectie-en-reiniging.pdf" target="_blank">**ISA standard**</a> focusses on describing an entire project's metadata. It does not prescribe a format for a project's measurement data, e.g. whether a data file should be in a cetain time series structure of file format.

> The ISA standard contains pointers, i.e. explicit references, of an experiment's measurement data to a data file. The content and data structure within a data file can be described in the ISA metadata, but it is up to the researcher(s) how to structure this.

The ISA standard is built upon:
- Investigation (I)
- Study (S), being part of Investigation 
- Assay (A), being part of Study

The Investigation, Study and Assay, and related concepts, are introduced here.

## Investigation

The investigation describes the general context of a project and ‘contains all the information needed to understand the overall goals and means used in an experiment’. First of all, it describes metadata of an experiment. Second, it introduces the studies and the assays that are part of the investigation. 

> An Investigation contains the information about a research project's overall administration and goals.
> 
{style="note"}


## Study

The study is the unit of research and contains ‘information on the subject under study, its characteristics and any treatments applied’. 

One investigation can contain multiple studies. The study describes characteristics of the subject under study, and manipulations performed on a set-up to affect the subject, in a way that an effect can be measured. 

> A Study contains the information about one or more experiment that are part of an investigation.
>
{style="note"}


## Assay

The Assay describes the measurements and 'represents a test performed either on material taken from a subject or on a whole initial subject, producing qualitative or quantitative measurements'. 

One study can contain multiple assays. Where the study describes the experiment itself, the assay describes how the data from an experiment is extracted. 

> An Assay contains the information about the production of data in an experiment.
>
{style="note"}


## Other relevant concepts

### Protocol
bla

### Protocol Parameter
bla

### Process
bla

### Study Factor
bla

### Factor Value
bla


## ISA exchange format

All captured information is stored in an output format. 


