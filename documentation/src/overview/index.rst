Overview
=========

.. toctree::
   :caption: Table of contents
   :maxdepth: 3

   tree.rst
   
This documentation is provided to assist in the usage of the XML specification (http://www.ddialliance.org/Specification/DDI-Codebook/2.6/XMLSchema/)

In addition there are three other main sources of documentation

- The Field Level documentation (https://docs.ddialliance.org/DDI-Codebook/2.6/xmlschema/index.html) is primarily aimed at developers or advanced users of the standard. 
- The Change Log is aimed at those migrating content or systems from previous versions of DDI-Codebook.
- Examples - code fragments illustrating specific content usage.

The specification contains 258 global and 7 local elements. 

All elements support a basic set of `GLOBAL <https://docs.ddialliance.org/DDI-Codebook/2.6/xmlschema/codebook_xsd/attributeGroups/GLOBALS.html>`_ attributes in addition to the content. These are:

- ID 
- xml:lang 
- source 
- elementVersion
- elementVersionDate
- DDILifecycleUrn
- DDICodebookUrn

There are 5 top level elements

- Document Description
- Study Description 
- File Description 
- Data Description 
- Other Study Related Materials 

Version 2.6 is a major update to the schema and has introduced a numner of new elements that replace existing ones, which it is recommended that these are migrated to in preperation for the next release.

- Controlled Vocabularies
- External Identifiers
- Bounding Box
- Geographic hierachies
- Text types

A numner of attributes are deprecated

- text type
- External Link
- DDI URN



