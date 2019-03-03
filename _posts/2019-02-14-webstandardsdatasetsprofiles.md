---
title: 'Web standards for describing datasets and profiles'
date: 2019-02-14
permalink: /posts/2019/02/webstandardsdatasetsprofiles
tags:
  - W3C
  - Web standards
  - Community
  - Interoperability
  - Datasets
  - Profiles
  - Data catalogues
---

This is blog post was published on the <a href="https://software.ac.uk/blog/2019-02-14-web-standards-describing-datasets-and-profiles">Software Sustainability Institute's website</a>. 

---

![Image of Database Land](https://agbeltran.github.com/images/database_land.jpg) Image by [chrisdlugosz](https://www.flickr.com/photos/chrisdlugosz/5577388841/). 

Supported by the UK [Software Sustainability Institute](http://software.ac.uk) Fellowship, I attended the fourth Face-to-Face (F2F) meeting of the [W3C Dataset eXchange Working Group](https://www.w3.org/2017/dxwg/wiki/Main_Page) (DXWG) in Lyon, France, at the end of October 2018. Here, I report on how W3C WGs work and the specific outputs we’ve been producing at DXWG.

W3C stands for [World Wide Web Consortium](https://www.w3.org/Consortium/) and is an organisation that works to develop web standards through an international community, which is built through a membership approach. Web standards are documents describing web technologies (for example HTML, CSS and XML) for which consensus, fairness, public accountability and quality have been reached. W3C follows a process that is designed to enable getting to that status where a document can be recommended for use, and this is done through Working Groups. Web standards are fundamental to achieve [interoperability](https://software.ac.uk/blog/2018-12-06-interact-interoperate).

Every year, W3C members come together over a week for the Technical Plenary and Advisory Committee (TPAC) meeting. This meeting brings together all the Technical Groups, the Advisory Board, the [Technical Architecture Group](https://www.w3.org/2001/tag/) and the Advisory Committee, as well as Working Groups and Community Groups. 

As a member of the [W3C Dataset eXchange Working Group](https://www.w3.org/2017/dxwg/wiki/Main_Page), I went to the F2F meeting, in which we continued our work related to the group’s charter to provide the following outcomes:
- **A revised version of the Data Catalog vocabulary (DCAT)**: The current DCAT Recommendation provides a vocabulary to publish datasets and data catalogs on the web. The working group is working on an update and expansion of the vocabulary, considering multiple new use cases and requirements.
- **Guidance on how to publish profiles of other standards**: This document is meant to include a definition of what is meant by profiles and an explanation of one or more methods for publishing and sharing them.
- **Content negotiation by Application Profile**: An explanation of how to implement the [expected Internet Engineering Task Force (IETF) Internet-Draft](http://profilenegotiation.github.io/I-D-Accept--Schema/I-D-accept-schema) and suitable fallback mechanisms as discussed at [the Smart Descriptions & Smarter Vocabularies (SDSVoc) workshop](https://www.w3.org/2016/11/sdsvoc/report#conneg).

![Image of AGB at TPAC](https://agbeltran.github.com/images/agb_tpac.jpg) 

To produce this work, we meet weekly in teleconferences online, communicate via a mailing list and collaborate through GitHub, where we keep all of the output documents (see the repository: [https://github.com/w3c/dxwg](https://github.com/w3c/dxwg)). We also meet in person from time to time, as it is a great way of progressing the work by focusing on specific issues in intensive meetings that run for two days. As not everyone is able to attend in person, there is always remote connection available and thorough minutes are taken via an Internet Relay Chat (IRC) system. The e-mails and minutes are archived and made public for anyone to follow the work of the Working Group, and public feedback is seeked and welcome at all times.

The whole W3C process is [extensively documented](https://www.w3.org/2018/Process-20180201/) and it includes the [development of a series of technical reports](https://www.w3.org/2018/Process-20180201/#Reports) until reaching the recommendation status. Working groups then publish a First Public Working Draft for each document, then zero or more revised Working Drafts, a Candidate Recommendation, a Proposed Recommendation and a W3C Recommendation (that can be later edited or amended, if needed). You can see all the W3C standards and drafts on the [W3C website](https://www.w3.org/TR/). 

The first step to produce these documents is to gather use cases and derive requirements from them. So, in DXWG, we first produced the [Use Cases and Requirements](https://w3c.github.io/dxwg/ucr/) document. The current status of the other documents is as follows.

**Revised DCAT.** Up until now, we have produced two working drafts of the revised version of DCAT. The latest working draft is [here](https://www.w3.org/TR/2018/WD-vocab-dcat-2-20181016/). The latest additions are always in the [Editors’ Draft](https://w3c.github.io/dxwg/dcat/). As I mentioned before, the original DCAT vocabulary provided terms to publish datasets and data catalogues on the web. For this revised version, we have been addressing new requirements around cataloguing data services and data distribution services, recording resources provenance, adding recommendations for catalogues that store datasets that are a bunch of files rather than explicitly splitting between a datasets and its different representations in different formats, guidance on how to describe the quality of a dataset, support for data citation, and many other relevant aspects of cataloguing resources.

**The Profiles Ontology.** A profile is a set of constraints over one or more standards of information resources. Thus, a profile may extend a standard by identifying new entities, or may  add more restrictions, options, parameters or semantic interpretations to a given standard. In the context of data catalogues, there have been several extensions or profiles of the DCAT vocabulary, but up until now there was no way to formalise profiles and to relate them to the standards they are based on, or to other profiles. In DXWG, we have produced a [first public working draft of an ontology for describing profiles](https://www.w3.org/TR/2018/WD-dx-prof-20181218/), including references to a test suite and to [an implementation report](https://github.com/CSIRO-enviro-informatics/prof-ont-implementation-results). The latest version of the document is the [Editors’ Draft](https://w3c.github.io/dxwg/profilesont/).

**Content Negotiation by Profile**. [Content negotiation](https://en.wikipedia.org/wiki/Content_negotiation) is a mechanism by which a server may have different representations of a resource (e.g. different versions of the same document) at the same location (or URI) and users or agents can specify what version to retrieve. However, up until now, there was no way for a client to negotiate for content based on what standard it complies with or what profile it conforms to. DXWG produced the [first public working draft](https://www.w3.org/TR/2018/WD-dx-prof-conneg-20181218/) of a specification for negotiating the content by profile. As per the other documents, the latest specification is always the [Editors’ Draft](https://w3c.github.io/dxwg/conneg-by-ap/).

If you have comments about these documents, we very much welcome them. To send feedback, you can do it via [GitHub issues](https://github.com/w3c/dxwg/issues) and/or by email at [public-dxwg-comments@w3.org](mailto:public-dxwg-comments@w3.org). We are especially looking for feedback around the direction we have taken in the different documents and also if you have any views on what we should prioritise next (you can check the list of open issues we have in GitHub to see the project roadmap). There are many [DXWG participants](https://www.w3.org/2000/09/dbwg/details?group=99375&public=1) who worked on these specifications and we look forward to hearing your views about them.

By using these specifications, we hope to enable high standards for describing datasets and profiles, which will contribute to data sharing and research reproducibility. 
