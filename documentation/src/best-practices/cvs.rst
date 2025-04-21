Controlled Vocabulary
=====================
	
When initially created, Codebook added a number of attributes to descriptive text fields that were intended to support future controlled vocabularies. It was thought at the time that controlled vocabularies would be listed internally as simple enumerations. 

As the technology changed and XML developed into the standardized us of schemas, the use of external controlled vocabularies became the dominant use. To support the use of external controlled vocabularies new structures were needed. 
  
The "concept" is the standardized means of providing the information needed to provide access to and validation of the use of external controlled vocabularies. Version 2.5 provided a means of noting the external vocabulary used at any point in the Codebook. 
  
Version 2.6 expands the number of specific locations for controlled vocabularies and provides consistency across the scheme where concepts are used as sub-elements or as base type. It adds the ability to provide a direct link to the term within a controlled vocabulary used at a specific point through the use of a vocabInstanceURI and/or vocabInstanceCodeTerm. This allows the field content of "concept" to contain language specific labels and reflects the historical use of these fields in Codebook. 
  
The standard form for controlled vocabularies identified within Codebook are based on the "concept" element. This may be expressed by an element of type="conceptType" or through the use of a "conceptualTextType" which includes the option for using a "concept" in conjunction with descriptive text. This has resulted in a number of options for expressing the use of external controlled vocabularies.

Best Practices:
Existing documentation making use of various attributes intended to contain controlled vocabularies should be treated as terms with unspecified controlled vocabulary usage. If the controlled vocabulary is known, and the element supports the use of "concept", replicate the value in the attribute in "concept" and add the information identifying the controlled vocabulary used.

New documentation should use the "concept" option rather than the original attribute.

New documentation wishing to use a controlled vocabulary where the "concept" option is not available should use the "controlledVocabulary" structure and associate it with the element or attribute containing the value of the controlled vocabulary. Currently the link to the element/attribute using the controlled vocabulary is expressed through an XPath.

specify:
- controlled vocabulary term
- controlled vocabulary label (multilingual)
- vocabulary name
- vocabulary URI (facilitates validation)
- vocabulary instance URI (facilitates instance level linkages and validation)
