Identification
==============

Codebook was originally developed using an XML DTD. It was intended to support internal referencing using the standard XML ID and IDRef9s) element types. As it developed and the newer schema based version eventually named DDI-Lifecycle was established, the approach switched to the use of a three part URN of agency identification, item identification, and version number. 

This is the approach that was continued through the development of major DDI products. It is important to recognize that while Codebook supports both approaches, identifiers are not required in DDI-Codebook and all internal referencing is done through the ID IDRef(s) structure. Links to external products are limited in Codebook, and with Codebook v.2.6 the use of ExtLink has been deprecated. External links are made by creating another material for an external object and referencing the othMat using the IDRef(s) available at most elements within DDI-Codebook. 

Codebook contains the following set of identifiers and related referencing objects.

Native XML identification for internal references:

ID is available for all base elements
	This is not a required element in Codebook
	Use of this ID is strongly recommended at the codebook level (many systems, such as NESSTAR required the use of ID for codebook)
	ID must be provided if you wish to reference the element (such as locMap, qstn, var, nCube, etc.) from another internal element.

External identifiers


Deprecated
----------

ExtLink
.......

This is a deprecated structure used to provide an external link to an identifiable object using that objects URI. The preferred approach is to create an othMat with the external URI and reference that othMat description using the IDRef(s) attributes in the related DDI element.
	
DDI URN	
.......

A ddiLifecycleUrn is provided to hold the DDI URN for content transferred from a DDI-Lifecycle instance. A ddiCodebookUrn allows for entering a similarly constructed DDI URN for the DDI-Codebook element. A common approach is to use the concatenation of the codebook ID and the element ID in addition to the agency ID of the authoring agency and existing version ID to create a unique URN. It is assumed that the authoring agency will create unique codebook IDs within the agency.
