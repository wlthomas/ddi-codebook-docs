
+Text types available in Codebook

Abstract Text Type
This type forms the basis of most textual elements. Elements using this type may have mixed content (text and child elements). The child elements are from the PHRASE, FORM, and xhtml:BlkNoForm.mix (a specific subset of XHTML) content groups. Note that if elements from the PHRASE and FORM groups must not be used with elements from the xhtml:BlkNoForm.mix group; one can use either elements from xhtml:BlkNoForm.mix or elements from the PHRASE and FORM groups. This type is extended in some cases to include additional attributes.

Simple Text Type
This type forms the basis of most textual elements. Elements using this type may have mixed content (text and child elements). The child elements are from the PHRASE, FORM, and xhtml:BlkNoForm.mix (a specific subset of XHTML) content groups. Note that if elements from the PHRASE and FORM groups must not be used with elements from the xhtml:BlkNoForm.mix group; one can use either elements from xhtml:BlkNoForm.mix or elements from the PHRASE and FORM groups. This type is extended in some cases to include additional attributes.

Conceptual Text Type
This type forms this basis for a textual element which may also provide for a conceptual (see concept) description of the element a longer description (see txt). If the concept and/or txt elements are used, then the element should contain no other child elements or text. Note that if elements from the PHRASE and FORM groups must not be used with elements from the xhtml:BlkNoForm.mix group; one can use either elements from xhtml:BlkNoForm.mix or elements from the PHRASE and FORM groups.

Table and Text Type
This type forms this basis for a textual element which may also provide for a table description using “table”. If the concept and/or txt elements are used, then the element should contain no other child elements or text. Note that if elements from the PHRASE and FORM groups must not be used with elements from the xhtml:BlkNoForm.mix group; one can use either elements from xhtml:BlkNoForm.mix or elements from the PHRASE and FORM groups.

Simple Text and Date Type
A simpleTextType with the addition of a “date” attribute. Indicates the date of the content, should follow ISO convention of YYYY-MM-DD.

String Type
This type restricts the base abstractTextType to only allow for text (i.e. no child elements).

Phrase Type
This type restricts the simpleTextType to allow for only child elements from the PHRASE content group. It still allows for mixed content (text and child elements).

Integer Type
This type restricts the base abstractTextType to only allow for an integer as text content. No child elements are allowed.

Date Simple Type
This simple type is a union of the various XML Schema date formats. Using this type, a date can be expressed as a year (YYYY), a year and month (YYYY-MM), a date (YYYY-MM-DD) or a complete date and time (YYYY-MM-DDThh:mm:ss). All of these formats allow for an optional timezone offset to be specified.

Date Type
This type restricts the base abstractTextType to allow for only the union of types defined in dateSimpleType as text content. No child elements are allowed.

+best approaches for structured text content - DDICODE-36
