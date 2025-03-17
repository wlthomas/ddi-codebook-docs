Data Description
================

.. toctree::
   :caption: Table of contents
   :maxdepth: 3
   
Data Description `(dataDscr) <https://docs.ddialliance.org/DDI-Codebook/2.5/xmlschema/schemas/codebook_xsd/elements/dataDscr.html>`_ contains elements to support the description of variables, variables groups, nCubes and nCube groups.

For each add purpose

var (0-n) [name, wgt, wgt-var, weight, qstn, files, vendor, dcml, intrvl, rectype, sdatrefs, methrefs, pubrefs, access, aggrMeth, otherAggrMethmeasUnit, scale, origin, nature, additivity, otherAdditivity, temporal, geog, geoVocab, catQnty, representationType, otherRepresentationType]
nCube (0-n) [name, sdatrefs, methrefs, pubrefs, access, dmnsQnty, cellQnty]
varGrp (0-n) [type, otherType, var, varGrp, name, sdatrefs, methrefs, pubrefs, access, nCube]
nCubeGrp (0-n) [name, sdatrefs, methrefs, pubrefs, access, dmnsQnty, cellQnty]
