# How do I publish my data in the USLCI?

###### If you are ready to begin the publication process, [please use our online appraisal form](appraisal-form.md).

This page is part of the [USLCI Submission Guide](README.md).  The purpose of this page is to help you, the Data Provider, understand the process for publishing life cycle inventory (LCI) data in the U.S. Life Cycle Inventory Database (USLCI)][uslci-landing].  If you are looking for information to help you decide if publishing your data in the USLCI fits your publication goals, please see *[Should I publish in the USLCI?](should-i-publish-in-the-uslci.md)*.  You can also find a list of frequently asked questions [here](faq.md).

This page is divided into the following sections and subsections.
  1. [Overview of the `Digital Curation Process`]
  [What is the `Digital Curation Process`?](#what-is-digital-curation)
  2. What to expect during the digital curation process
    * Time requirements for publishing LCI data
    * USLCI publication schedule
    * [The digital curation life cyle](#The Data Curation Life Cycle)
    * What to expect during each life cycle phase
  3. Working with NREL
    * [How we communicate](#communication)
    * Our data publication platorm

<a id="digital-curation-overview"></a>
## Overview of the *Digital Curation Process*
NREL uses a *Digital Curation Process* for receiving, reviewing, publishing, and preserving data and metadata submitted to the USLCI.  The process is divided into five phases:
  1. [Appraisal](#appraisal)  
  2. [Ingest & Onboarding](#ingest-and-onboarding)  
  3. [Review](#review)  
  4. [Publication](#publication)  
  5. [Preservation](#preservation)  

One common question from potential Data Providers is, "How long will it take to publish my data in the USLCI?"  That question is answered in our [Frequently Asked Questions page](faq.md#how-long).

Each of the four phases is discussed in greater detail below.

<a id="appraisal"></a>
### Appraisal
The objectives of the Appraisal phase are to:
  * Verify the fitness of your data for publication in the USLCI
  * If appropriate, develop a plan for the [Ingest](#ingest) and [Review](#review) phases of the Digital Curation Process.

The Appraisal phase is composed of the following elements:
  * Submission of the [online appraisal form](appraisal-form.md)
  * Preliminary data review by the Data Curator
  * (If appropriate) An Appraisal Meeting

The Appraisal phase begins when you submit the [online appraisal form](appraisal-form.md).  That information will be reviewed by a USLCI Data Curator who will reach out to you via phone or email within five business days with a tentative decision regarding the fitness of your data for publication in the USLCI.  If the Data Provider decides that your data likely fits the USLCI's mission, she will coordinate with you to set up a 30-60 minute Appraisal Meeting.  

The Appraisal Meeting is an opportunity to evaluate the data at a deeper level and, if appropriate, develop a planfor the [Ingest](#ingest) and [Review](#review) phases of the Digital Curation Process.  The Appraisal Meeting will result in one of three outcomes:
  1. Data Approved
  2. Revise and Resubmit
  3. Data Denial

A *Data Approved* outcome means that your data is advanced to the [Ingest](#ingest) phase with no modifications.  This outcome is rare for an initial submission.  A *Revise and Resubmit* outcome means that the Data Curator will ask you to make specific changes to the data and metadata in your LCI model.  After those changes are made you will contact the Data Curator via email for a follow-up Appraisal Meeting.  A *Data Denial* outcome means that your data does not fit the USLCI's mission and will not be further considered for publication.

<a id="ingest-and-onboarding"></a>
### Ingest & Onboarding
The Ingest & Onboarding phase is concerned with entering a data submission into the USLCI's file management system and establishing norms of collaboration between the Data Provider and the Data Curator.

Currently data submissions are received via a dedicated Box.com folder, however NREL is currently developing an automated data submission process that may be implemented in the future.


<a id="review"></a>
### Review

<a id="publication"></a>
### Publication
The USLCI is updated with new and revised data on a quarterly basis:
  * March 31
  * June 30
  * September 30
  * December 31

<a id="preservation"></a>
### Preservation


## Working with NREL
The data publication process is a collaborative effort between you (i.e., the Data Provider) and the National Renewable Energy Laboratory (NREL).  Practically speaking, that means you will be working closely with one of NREL's Life Cycle Inventory (LCI) Data Curators throughout the publication process.

The Data Curator's role is to guide you through the publication process.  This person is trained in LCI data curation and can help you troubleshoot technical issues related to the openLCA platform.

Your role in the publication process is transform your raw LCI data into a polished product that is ready for publication in the USLCI.  This means putting your data into the USLCI's [chosen data format](#data-publication-platform) and also pairing your data with robust metadata so that users of your data understand how to use it properly.  

The documentation and resources in the USLCI Submission Guide will be important resources in that process.

### How we communicate
We use [Slack][slack] as our primary written communication tool.  Slack allows the user great flexibility in communication because of its ability to push communication to/from email accounts, mobile devices, etc.   Furthermore, it provides context during communication through the ability to set up various channels based on conversation topic.  

Early in the publication process the Data Curator will work with you to get you set up on Slack.

<a id="data-publication-platform"></a>
### Our data publication platorm
NREL uses [openLCA v1.6][openlca_v16] as its platform for receiving, reviewing, and publishing LCI data.  [OpenLCA][openlca] is a free, opensource LCA software platform that is able to import data from many commercial LCA software applications including GaBi and SimaPro.

Early in the publication process the Data Curator will work with you to get you set up on Slack.



###


  * General publication timeline
    * Quarterly publications

### Ingest
  * Short-term strategy
  * Long-term strategy

### Review  

#### Dataset requirements
* *Dataset* = data + metadata

##### Data quality
##### Data review

### Publication  
### Preservation

## USLCI field conventions
The USLCI uses the openLCA data model for publishing LCI data...

###### Key sources
* Class DataSetInformation (http://greendelta.github.io/olca-modules/olca-ilcd/apidocs/org/openlca/ilcd/flowproperties/DataSetInformation.html)
* LCAC Submission Guidelines
* LCAC Unit Process Template
* ILCD handbook: Nomenclature and other conventions (http://eplca.jrc.ec.europa.eu/uploads/MANPROJ-PR-ILCD-Handbook-Nomenclature-and-other-conventions-first-edition-ISBN-fin-v1.0-E.pdf)

### Process field conventions
&darr; Field contents are the same as the field above  
:small_red_triangle: Mandatory field  
:small_orange_diamond: Automatically populated field  
:small_blue_diamond: Optional field  

###### Table XX: Descriptive technical terms

| Category | Descriptive technical terms |   
|:---:|:---|    
| Treatment received |   |    
| Standard fulfilled |   |    
| Product quality |   |    
| Use information |   |    
| Treatment received |   |    
| Production route name |   |    
| Educt name |   |    
| Treatment received |   |    
| Treatment received |   |    

## Links
This section contains the URLs for the linked text in this page. These URLs are intentionally not rendered when this page is viewed as HTML.  To see the URLs, view this page as a text file or [Markdown][markdown] file.  

[markdown]: https://daringfireball.net/projects/markdown/  
[openlca]: http://www.openlca.org/  
[openlca-v16]: http://www.openlca.org/download/
[section-1]: https://github.nrel.gov/acarpent/uslci_admin/wiki/Should-I-publish-in-the-USLCI    
[section-2]: https://github.nrel.gov/acarpent/uslci_admin/wiki/How-to-publish-in-the-USLCI   
[section-3]: https://github.nrel.gov/acarpent/uslci_admin/wiki/FAQ    
[slack]: https://slack.com/  
[uslci-landing]: http://www.nrel.gov/lci/  
