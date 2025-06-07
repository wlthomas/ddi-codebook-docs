Overview
=========

.. toctree::
   :caption: Table of contents
   :maxdepth: 3

   tree.rst
   
This documentation is provided to assist in the usage of the XML specification (http://www.ddialliance.org/Specification/DDI-Codebook/2.6/XMLSchema/)

In addition there are three other main sources of documentation

- The Field Level documentation (https://docs.ddialliance.org/DDI-Codebook/2.6/xmlschema/index.html) is primarily aimed at developers or users of the standard. 
- The Change Log is aimed at those migrating content or systems from previous versions of DDI-Codebook.
- Examples - code fragments illustrating specific content usage.

The specification contains 258 global and 7 local elements. 

All elements support a basic set of `GLOBAL <https://docs.ddialliance.org/DDI-Codebook/2.6/xmlschema/codebook_xsd/attributeGroups/GLOBALS.html>`_ attributes in addition to the content. These are:

- ID [XML identifier within the context of the XML instance[
- xml:lang [indicates the language of the element's content]
- source [producer | archive]
- elementVersion [version number of the element]
- elementVersionDate [version date of the element]
- DDILifecycleUrn [URN in DDI standard format of the equivilent element in DDI=Lifecycle - used when transforming content from DDI-Lifecycle to DDI-Codebook]
- DDICodebookUrn [URN in DDI standard format of the DDI-Codebook element]

There are 5 top level elements

- Document Description [Description of the DDI document]
- Study Description [Description of the study defined in the DDI document]
- File Description [Description of the related data file(s)]
- Data Description [Description of the data content, variables, nCubes, and groupings]
- Other Study Related Materials [bibliographic descriptions and links to external materials]

Version 2.6 is a major update to the schema and has introduced a numner of new elements that replace existing ones, which it is recommended that these are migrated to in preperation for the next release.

Changes were made to better support:
-	Consistent attributes for all content defining individuals and organizations
-	Improved ability to link access rules to specific content
-	Expanded use of typeOfXxxx to support the use of controlled vocabularies in various locations
-	Consistent use of controlled vocabularies through the element concept
-	Updated internal enumerations
-	A new DDI controlled vocabulary references included
-	Metadata access information
-	Use of SDTL to describe file and variable derivations 
-  Consistent documentation structure and expanded examples
-  Addition of Usage Guide document

A number of attributes are deprecated:

- type and similar attributes where typeOfXxxx (concept type) were added
- Link
- External Link



