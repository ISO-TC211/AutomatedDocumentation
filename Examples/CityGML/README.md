CityGML 3.0 Examples
===========

Normative content for the CityGML 3.0 Standards document was generated semi-automatically from a UML model using Enterprise Architect. The files in this directory demonstrate the use of this tool.

While the content was generated automatically, some manual editing was required to place the content in proper order and to fix a few formatting issues.

## The CityGML 3.0 Standard (Draft)

The file 20-01.pdf is the draft CityGML 3.0 Standard in pdf format. This document was written in AsciiDoc. The PDF was generated using AscciDoctor.

Chapters 8 and 9 contain significant ammounts of automated generated content. Most requirements and conformance tests were generated from templates using shell scripts.

## Legacy Enterprise Architect Templates

The file CityGML.rtf was generated using the Enterprise Architect template available from the [UML Best Practices](https://github.com/ISO-TC211/UML-Best-Practices/raw/master/DocumentationOfUMLModels/EA-template/ISOTC11_EA_report_template.zip) GitHub repository. This rtf was generated from the same UML model as was used for the OGC standard.

## OGC Enterprise Architect Templates

Chapters 8 and 9 of the CityGML 3.0 Standard contain content which was auto-generated from the UML model. 

Chapter 8 provides a description of the CityGML model. It is a combination of descriptive text, UML diagrams, and summaries of the CityGML classes. The UML diagrams and summary tables are generated from the UML model.

Chapter 9 provides a data dictionary for the UML model. This Chapter is almost entirely auto-generated content.

Relevant files are:

* Data_Dictionaries/* : RTF output of the Data Dictionaries from EA
* Data_Summaries/* : RTF output of the Summary Tables from EA
* CityGML-Data-Dictionary.xml: EA template for generating the Data Dictionaries
* Summary-Tables.xml: EA template for generating the Summary Tables.

Note that since EA does not have a text output option, cut and paste was used to transfer the RTF content from Word into AsciiDoc format using AsciiDocFX. Since the RTF includes the AsciiDoc formatting, no changes to the content were required.




