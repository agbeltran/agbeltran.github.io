---
title: 'ISA-explorer: A demo tool for discovering and exploring Scientific Data’s ISA-tab metadata'
date: 2015-12-17
permalink: /posts/2015/12/isa-explorer/
tags:
  - Scientific Data
  - metadata
  - ISA-explorer
  - search engine
---

This is blog post was published on the [Nature's Scientific Data blog](http://blogs.nature.com/scientificdata/2015/12/17/isa-explorer/). 

---

Since it’s inception, [Scientific Data](http://nature.com/scientificdata) has been working to encourage a “show me the data” culture, with the aim of publishing Data Descriptors on fully reusable datasets. Datasets can only be used if data have been rigorously described; as recently shown, even when journal policies on data archiving are strong, data are not always shared in a reusable manner.

However, even well documented data will only be reused, if they are discoverable. Published Data Descriptors are indexed in all major bibliographic indexing services, such as [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/), and so datasets can be discovered via these article indexes. However, [accompanying every Data Descriptor article there are metadata files](http://blogs.nature.com/scientificdata/2013/09/19/the-data-descriptor-making-your-data-reusable/), specifically created to aid discovery and understanding of the data itself. Using the [ISA](http://www.isa-tools.org/) (Investigation, Study, Assay) model, these metadata files provide a machine readable overview of the study that generated the data. The ISA model records the data’s provenance, how it was generated and where it is located – all prerequisites of publication with Scientific Data. The ISA-Tab metadata file is used to generate the Structured Summary table that appears after the abstract in every Data Descriptor article (see Figure 1). The ISA-Tab tabular metadata files available through Scientific Data are provided under the CC0 waiver to encourage their maximum re-use.

Currently ISA-Tab metadata files can be downloaded directly from the HTML page for each Data Descriptor. Scientific Data also provides a GitHub repository containing copies of these ISA-Tab files at https://github.com/ScientificDataLabs/ISA-tab.

However, we can do more! Given that datasets and their descriptions are made available, the next step is to enable a “find me the data” culture.

Aiming to increase the usefulness of the ISA-Tab metadata files, the ISA team based at the University of Oxford has produced a demo tool allowing the discovery and exploration of the datasets. This is aptly named the ISA-explorer, and uses the information in the ISA-Tab metadata files to facilitate dataset discovery (see Figure 2). Published Scientific Data ISA-Tab files can now be easily read and explored at the customised Scientific Data ISA-explorer at: http://scientificdata.isa-explorer.org/

The Scientific Data ISA-explorer allows users to filter datasets by data repository and the metadata in the Structured Summary table (see Figure 1). The filters can be combined in a boolean search allowing users to easily and quickly discover specific types of data; for example, a specific design type for data stored at a particular repository.

The ISA-explorer also offers a generic search box, allowing for keyword-based searches of the ISA-Tab metadata files. Additionally, the tool allows browsing of dataset specific information such as related publications. The tool shows a visualisation of the distribution of sample characteristics: for example, Figure 3 depicts how many samples of each organism type. To see all the samples information, the original metadata tables can also be visualised.




