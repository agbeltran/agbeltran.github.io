---
title: "Machine-Actionable Metadata Models: a toolbox including JSONLDSchema python module and JSONschema-documenter web application"
collection: talks
type: "Workshop Talk"
permalink: /talks/2019-02-07-machineactionablemetadatamodels
venue: "RSLondonSouthEast19"
date: 2019-02-07
location: "Royal Society, London, UK"
---


This talk combines two abstracts that we submitted to the  <a href="https://rslondon.ac.uk/rslondonse-2019/">Research Software London & SouthEast 2019</a> workshop that took place at the [Royal Society](https://royalsociety.org/) in London, UK, on 7th February 2019.

The presentation is available in Zenodo: 


[![Machine Actionable Metadata Models slides](https://agbeltran.github.com/images/MachineActionableMetadataModels-slide.png)](https://doi.org/10.5281/zenodo.2558716) 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2558716.svg)](https://doi.org/10.5281/zenodo.2558716)

You can see the conversations around the workshop in [twitter](https://twitter.com/hashtag/rslondonse19?src=hashtag_click&f=live).

The abstracts are as follows:

### JSON-LD Schema: A Python module with facilities to deal with JSON-schemas for JSON-LD

[Alejandra Gonzalez-Beltran](http://agbeltran.github.io/), [Dominique Batista](http://github.com/terazus/), Philippe Rocca-Serra, Susanna Sansone
Oxford e-Research Centre, Department of Engineering Science, University of Oxford

JSONschema is a vocabulary to validate JavaScript Object Notation (JSON) files. JSON-LD is an extension of JSON to support linked data: a way to create a machine-readable and standard way to share data on the web. While there are tools to deal with JSON-schemas and JSON-LD separately, to the best of our knowledge, JSON-schema has not been used for JSON-LD. While there are other languages to validate linked data (such as ShEx and SHACL), given the popularity of JSON and the facilities to produce JSON-LD from JSON, JSONschema is a very useful language for the validation of JSON-LD. Here we will present a new python module that provides facilities for dealing with JSON-schemas for JSON-LD data, including validation, semantic and syntactic comparison between schemas, conversion of schemas to templates for data entry. We will show how the module can be used for specific data, showing how it can help in making data FAIR (Findable, Accessible, Interoperable and Reusable). We will also describe the best practices used in the development of the module. The development has been open and the code is available at  [http://github.com/fairsharing/jsonldschema](http://github.com/fairsharing/jsonldschema) with license BSD-3-Clause.


### JSONschema documenter: a tool for documenting and visualising JSON-schemas

[Dominique Batista](http://github.com/terazus/), [Alejandra Gonzalez-Beltran](http://agbeltran.github.io/), Philippe Rocca-Serra, Susanna Sansone

Oxford e-Research Centre, Department of Engineering Science, University of Oxford

The JSONschema format is a powerful technology to help create (meta)data models by providing a syntax to describe object constraints for the JavaScript Object Notation (JSON). The syntax may become complex and hardly readable as constraints and references grow. In order to help users developing or consuming JSON-schemas, we created an AngularJS-based client-side web application that documents the metafields, fields and constraints of all online schemas resolved from a URL. The power of this app resides in its ability to create links between the schemas and fields of a set and to bind fields to vocabulary terms retrieved from context files.

Code availability: [http://github.com/fairsharing/jsonschema-documenter](http://github.com/fairsharing/jsonschema-documenter)  

