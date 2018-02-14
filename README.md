# Reproducibility-General
Integrating reproducibility best practices into your research workflow: A survey of best practices with hands-on exercises

# Abstract
This is a general overview of reproducibility best practices applicable to most disciplines. The workshop will provide a survey of the history and current landscape of reproducibility and identify the common barriers. We will introduce best practices and solutions as well as present additional resources. We will demonstrate tools that help researchers overcome barriers to reproducibility and participants will practice using the tools during hands-on activities. 

# Essential information about reproducibility
* The role of replication in the scientific method.
* The history of the reproducibility conversation.
* Definitions and measurement of reproducibility.
* Barriers to reproducibility across disciplines.
* Benefits to integrating reproducibiity best practices into research.

# Practical steps towards reproducibility

## Plan for reproducibility before you start

### Create a study plan or protocol.
* Begin documentation at study inception and track changes as your plan changes.
* Set-up a reproducible project
* Centralize and organize your project management using an electronic lab notebook or a central repository for all research files.
* Separate your data from your code.
* Make your raw data read-only and keep separate from processed data.
* Use relative paths.
* Avoid proprietary file formats.
### Power 
* Calculate your power. Underpowered studies are more likely to have irreproducibible results.
### Informative file naming and location
* Choose a naming system for files in advance. Files should be human readable and machine readable.

## Keep track of things
### Registration
* Preregister important study design and analysis information
* Free tools to help you make your first registration include AsPredicted, Open Science Framework, and Registered Reports. Clinical trials use Clinicaltrials.gov.
### Track changes to your files using version control.
### Documentation
* Document everything done by hand in a README file. 
* Create a data dictionary (also known as a codebook) to describe important information about your data. For an easy introduction, use Karl Broman’s Data Organization module: http://kbroman.org/dataorg/pages/dictionary.html
### Literate programming
* Consider using Jupyter Notebooks, KnitR, Sweave, or other approaches to literate programming to integrate your code with your narrative and documentation. 

## Share and licence your research
### Data
* Avoid supplementary files, licence, and share your data using a repository. 
### Materials & reagents
* Licence your published materials so they can be reused. 
* Deposit reagents with repositories like Addgene, The Bloomington Drosophila Stock Center, and ATCC to make them easily accessible to other researchers.
### Software, notebooks, and containers
* Licence your code to signal how you wish it to be used
* Share notebooks with services such as mybinder that allow for public viewing and execution of the entire notebook on shared resources.
* Share containers or notebooks with services such as Rocker or Code Ocean.

## Report your research transparently
* Report and publish your protocols and interventions explicitly and transparently.
* Share your methods fully to allow for replication. 
* Guidelines from the Equator Network, tools like Protocols.io, or processes like Registered Reports can help you report reproducibly.
* Licence your published materials so they can be reused.

