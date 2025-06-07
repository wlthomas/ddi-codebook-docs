- Numbering locations are valid for version 2.6 only and reflect the current order and nesting of this version

- Field Name (min-max) [attributes] 

- Heavily repeated (GLOBAL) attributes have not been inlcuded in the tree description

- All elements support a basic set of attributes including: ID, xml:lang, source, elementVersion, elementVersionDate, DDILifecycleUrn, DDICodebookUrn

- See High Level documentation for details on sets of string and concept types and their specific attributes (Text Types and Contolled Vocabuary)


``0            codeBook [version, codeBookAgency]
1               docDscr (0-n)
1.1                citation (0-1) [MARCURI]
1.1.1                 titlStmt (1-1)
1.1.1.1                  titl (1-1)
1.1.1.2                  subTitl (0-n)
1.1.1.3                  altTitl (0-n)
1.1.1.4                  parTitl (0-n)
1.1.1.5                  IDNo (0-n) [agency, isPersistentIdentifier, level]
1.1.2                 rspStmt (0-1)
1.1.2.1                  AuthEnty (0-n) [affiliation, abbr, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
1.1.2.2                  othId (0-n) [type, role, abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
1.1.3                 prodStmt (0-1)
1.1.3.1                  language (0-n) [typeOfLanguageCode, languageCode]
1.1.3.2                  producer (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
1.1.3.3                  copyright (0-n)
1.1.3.4                  license (0-n) [URI, type, scope]
1.1.3.5                  prodDate (0-n)
1.1.3.6                  prodPlac (0-n)
1.1.3.7                  software (0-n) [version, date]
1.1.3.8                  fundAg (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
1.1.3.9                  grantNo (0-n) [agency, fundingProgram, grantName, role]
1.1.4                 distStmt (0-1)
1.1.4.1                  distrbtr (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
1.1.4.2                  contact (0-n) [URI, email, abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
1.1.4.3                  depositr (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
1.1.4.4                  depDate (0-n)
1.1.4.5                  distDate (0-n)
1.1.5                 serStmt (0-n) [URI]
1.1.5.1                  serName (0-n) [abbr]
1.1.5.2                  serInfo (0-n)
1.1.6                 verStmt (0-n)
1.1.6.1                  version (0-n) [type]
1.1.6.2                  verResp (0-n) [affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
1.1.6.3                  notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
1.1.7                 biblCit (0-n) [format]
1.1.8                 holdings (0-n) [location, callno, URI, media]
1.1.9                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
1.1.10                dc:elementsAndRefinementsGroup 
1.2                guide (0-n)
1.3                docStatus (0-n)
1.4                docSrc (0-n) [MARCURI}  --SEE Citation Contents section 1.1 inclusive--
1.5                controlledVocabUsed (0-n)
1.5.1                 codeListID (0-1)
1.5.2                 codeListName (0-1)
1.5.3                 codeListAgencyName (0-1)
1.5.4                 codeListVersionID (0-1)
1.5.5                 codeListURN (0-1)
1.5.6                 codeListSchemeURN (0-1)
1.5.7                 usage (1-n)
1.5.7.1                  selector (0-1)
1.5.7.2                  specificElements (0-1) [refs, authorizedCodeValue]
1.5.7.3                  attribute (0-1)
1.6                notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
2               stdyDscr (1-n) [access]
2.1                citation (1-n) --SEE Citation Contents section 1.1 inclusive--
2.2                studyAuthorization (0-n) [date]
2.2.1                 authorizingAgency (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
2.2.2                 authorizationStatement (0-n)
2.3                stdyInfo (0-n)
2.3.1                 studyBudget (0-n)
2.3.2                 subject (0-n)
2.3.2.1                  keyword (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.3.2.2                  topcClas (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.3.3                 abstract (0-n) [contentType]
2.3.4                 sumDscr (0-n)
2.3.4.1                  timePrd (0-n) [event, cycle]
2.3.4.2                  collDate (0-n) [event, cycle]
2.3.4.3                  nation (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm, abbr]
2.3.4.4                  geogCover (0-n)
2.3.4.5                  geogUnit (0-n)
2.3.4.6                  geoBndBox (0-1)
2.3.4.6.1                   westBL (1-1)
2.3.4.6.2                   eastBL (1-1)
2.3.4.6.3                   southBL (1-1)
2.3.4.6.4                   northBL (1-1)
2.3.4.7                  boundPoly (0-n)
2.3.4.7.1                   polygon (1-n)
2.3.4.7.1.2                    point (1-n)
2.3.4.7.1.2.1                     gringLat (1-1)
2.3.4.7.1.2.2                     gringLon (1-1)
2.3.4.8                  anlyUnit (0-n) [unit]
2.3.4.9                  universe (0-n) [level, clusion]
2.3.4.10                 dataKind (0-n) [type]
2.3.4.11                 generalDataFormat (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.3.5                 qualityStatement (0-1)
2.3.5.1                  standardsCompliance (0-n)
2.3.5.1.1                   standard (1-1)
2.3.5.1.2                      standardName (0-n) [date, version, URI]
2.3.5.1.3                      producer (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
2.3.5.2                     complianceDescription (0-n)
2.3.5.2                  otherQualityStatement (0-1)
2.3.6                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
2.3.7                 exPostEvaluation (0-n) [completionDate, type]
2.3.7.1                  typeOfExPostEvaluation (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.3.7.2                  evaluator (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
2.3.7.3                  evaluationProcess (0-n)
2.3.7.4                  outcomes (0-n)
2.4                studyDevelopment (0-n)
2.4.1                 developmentActivity (0-n) [type]
2.4.1.1                  typeOfDevelopmentActivity (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.4.1.2                  description (0-n)
2.4.1.3                  participant (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
2.4.1.4                  resource (0-n)
2.4.1.4.1                   typeOfDataSrc (0-1) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.4.1.4.2                   dataSrc (0-n)
2.4.1.4.3                   srcOrig (0-n)
2.4.1.4.4                   srcChar (0-n)
2.4.1.4.5                   srcDocu (0-n)
2.4.1.5                  outcome (0-n)
2.5                method (0-n)
2.5.1                 dataColl (0-n)
2.5.1.1                  timeMeth (0-n) [method]
2.5.1.2                  dataCollector (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
2.5.1.3                  collectorTraining (0-n) [type]
2.5.1.4                  frequenc (0-n) [freq]
2.5.1.5                  sampProc (0-n)
2.5.1.6                  sampleFrame (0-n)
2.5.1.6.1                   sampleFrameName (0-n)
2.5.1.6.2                   labl (0-n) [level, vendor, country, sdatrefs]
2.5.1.6.3                   txt (0-n) [level, sdatrefs]
2.5.1.6.4                   validPeriod (0-n) [event]
2.5.1.6.5                   custodian (0-n) [abbr, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
2.5.1.6.6                   useStmt (0-n)
2.5.1.6.6.1                    confDec (0-n) [required, formNo, URI]
2.5.1.6.6.2                    specPerm (0-n) [required, formNo]
2.5.1.6.6.3                    restrctn (0-n)
2.5.1.6.6.4                    contact (0-n) [required, formNo, URI]
2.5.1.6.6.5                    citReq (0-n)
2.5.1.6.6.5                    deposReq (0-n)
2.5.1.6.6.6                    conditions (0-n)
2.5.1.6.6.7                    disclaimer (0-n)
2.5.1.6.7                   universe (0-n) [level, clusion]
2.5.1.6.8                   frameUnit (0-n) [isPrimary]
2.5.1.6.8.1                    unitType (1-1) [numberOfUnits]
2.5.1.6.8.2                    txt (0-n) [level, sdatrefs]
2.5.1.6.9                   referencePeriod (0-n)
2.5.1.6.10                  updateProcedure (0-n)
2.5.1.7                  targetSampleSize (0-n)
2.5.1.7.1                   sampleSize (0-1)
2.5.1.7.2                   sampleSizeFormula (0-n)
2.5.1.8                  deviat (0-n)
2.5.1.9                  collMode (0-n)
2.5.1.10                 resInstru (0-n) [type]
2.5.1.11                 instrumentDevelopment (0-n) [type]
2.5.1.12                 sources (0-1) 
2.5.1.12.1                  typeOfDataSrc (0-1) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.5.1.12.2                  dataSrc (0-n)
2.5.1.12.3                  sourceCitation (0-n)
2.5.1.12.4                  srcOrig (0-n)
2.5.1.12.5                  srcChar (0-n)
2.5.1.12.6                  srcDocu (0-n)
2.5.1.12.7                  sources (0-n) --RECURSIVE--
2.5.1.13                 collSitu (0-n)
2.5.1.14                 actMin (0-n)
2.5.1.15                 ConOps (0-n) [agency]
2.5.1.16                 weight (0-n) 
2.5.1.17                 cleanOps (0-n) [agency]
2.5.2                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
2.5.3                 anlyInfo (0-1)
2.5.3.1                  respRate (0-n)
2.5.3.2                  EstSmpErr (0-n)
2.5.3.1                  dataAppr (0-n) [type]
2.5.4                 stdyClas (0-n) [type]
2.5.5                 dataProcessing (0-n) [type]
2.5.6                 codingInstructions (0-n) [type, relatedProcesses]
2.5.6.1                  typeOfCodingInstruction (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.5.6.2                  txt (0-n) [level, sdatrefs]
2.5.6.3                  command (0-n) [formalLanguage]
2.6                dataAccs (0-n)
2.6.1                 typeOfAccess (0-1) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.6.2                 setAvail (0-n) [media, callno, label, type]
2.6.2.1                  typeOfSetAvailability (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.6.2.2                  accsPlac (0-n) [URI]
2.6.2.3                  origArch (0-n) [abbr, URI, affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
2.6.2.4                  avlStatus (0-n)
2.6.2.5                  collSize (0-n)
2.6.2.6                  complete (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.6.2.7                  fileQnty (0-n)
2.6.2.8                  notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
2.6.3                 useStmt (0-n)
2.6.3.1                  confDec (0-n) [required, formNo, URI]
2.6.3.2                  specPerm (0-n) [required, formNo, URI]
2.6.3.3                  restrctn (0-n)
2.6.3.4                  contact (0-n) [affiliation, URI, email, agentIdentifier, typeOfAgentIdentifier, isPersistentIdentifier, agentType]
2.6.3.5                  citReq (0-n)
2.6.3.6                  deposReq (0-n)
2.6.3.7                  conditions (0-n)
2.6.3.8                  disclaimer (0-n)
2.6.4                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
2.7                metadataAccs (0-n)
2.7.1                 typeOfAccess (0-1) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
2.7.2                 license (0-n) [URI, type, scope]
2.7.3                 useStmt (0-n)
2.7.3.1                  confDec (0-n) [required, formNo, URI]
2.7.3.2                  specPerm (0-n) [required, formNo]
2.7.3.3                  restrctn (0-n)
2.7.3.4                  contact (0-n) [required, formNo, URI]
2.7.3.5                  citReq (0-n)
2.7.3.6                  deposReq (0-n)
2.7.3.7                  conditions (0-n)
2.7.3.8                  disclaimer (0-n)
2.7.4                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
2.8                othrStdyMat (0-n)
2.8.1                 relMat (0-n) [callno, label, media, type]
2.8.1.1                  citation (0-n) --SEE Citation Contents section 1.1 inclusive--
2.8.2                 relStdy (0-n)
2.8.2.1                  citation (0-n) --SEE Citation Contents section 1.1 inclusive--
2.8.3                 relPubl (0-n)
2.8.3.1                  citation (0-n) --SEE Citation Contents section 1.1 inclusive--
2.8.4                 othRefs (0-n)
2.8.4.1                  citation (1-1) --SEE Citation Contents section 1.1 inclusive--
2.9                notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
3               fileDscr (0-n) [URI, sdatrefs, methrefs, pubrefs, access]
3.1                fileTxt (0-n) [mimeType]
3.1.1                 fileName (0-n)
3.1.2                 fileCitation (0-1) --SEE Citation Contents section 1.1 inclusive--
3.1.3                 dataFingerprint (0-n) [type]
3.1.3.1                  digitalFingerprintValue (1-1)
3.1.3.2                  algorithmSpecification (0-1)
3.1.3.3                  algorithmVersion (0-1)
3.1.4                 fileCont (0-n)
3.1.5                 fileStrc (0-1) [type, otherType, fileStrcRef]
3.1.5.1                  recGrp (0-n) [recGrp, rectype, keyvar, rtypeloc, rtypewidth, rtypevtype, recidvar]
3.1.5.1.1                   labl (0-n) [level, vendor, country, sdatrefs]
3.1.5.1.2                   recDimnsn (0-1) [level]
3.1.5.1.2.1                    varQnty (0-1)
3.1.5.1.2.2                    caseQnty (0-1)
3.1.5.1.2.3                    logRecL (0-1)
3.1.5.2                  notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
3.1.6                 dimensns (0-1)
3.1.6.1                  caseQnty (0-n)
3.1.6.2                  varQnty (0-n)
3.1.6.3                  logRecL (0-n)
3.1.6.4                  recPrCas (0-n)
3.1.6.4                  recNumTot (0-n)
3.1.7                 fileType (0-n) [charset]
3.1.8                 format (0-n)
3.1.9                 filePlac (0-n)
3.1.10                dataChck (0-n)
3.1.11                ProcStat (0-n)
3.1.12                dataMsng (0-n)
3.1.13                software (0-n) [version, date]
3.1.14                verStmt (0-n)
3.1.14.1                 version (0-n) [type]
3.1.14.2                 verResp (0-n) [affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
3.1.14.3                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
3.2                fileDerivation (0-1) [sourceFiles]
3.2.1                 fileCommand (0-n) [fileDerivationCasesAction]
3.2.1.1                  drvdesc (0-1)
3.2.1.2                  drvcmd (1-n) [syntax]
3.2.1.3                  fileDerivationVars (0-1) [keep, drop, add]
3.3                locMap (0-1)
3.3.1                 dataItem (0-n) [varRef, nCubeRef, access]
3.3.1.1                  CubeCoord (0-n) [coordNo, coordVal, coordValRef]
3.3.1.2                  physLoc (0-n) [type, recRef, startPos, width, endPos]
3.4                notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
4               dataDscr (0-n) [access]
4.1                varGrp (0-n) [type, otherType, var, varGrp, name, sdatrefs, methrefs, pubrefs, access, nCube]
4.1.1                 labl (0-n) [level, vendor, country, sdatrefs]
4.1.2                 txt (0-n) [level, sdatrefs]
4.1.3                 concept (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
4.1.4                 defntn (0-n)
4.1.5                 universe (0-n) [level, clusion]
4.1.6                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
4.2                nCubeGrp (0-n) [name, sdatrefs, methrefs, pubrefs, access, dmnsQnty, cellQnty]
4.2.1                 labl (0-n) [level, vendor, country, sdatrefs]
4.2.2                 txt (0-n) [level, sdatrefs]
4.2.3                 concept (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
4.2.4                 defntn (0-n)
4.2.5                 universe (0-n) [level, clusion]
4.2.6                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
4.3                var (0-n) [name, wgt, wgt-var, weight, qstn, files, vendor, dcml, intrvl, rectype, sdatrefs, methrefs, pubrefs, access, aggrMeth, otherAggrMethmeasUnit, scale, origin, nature, additivity, otherAdditivity, temporal, geog, geoVocab, catQnty, representationType, otherRepresentationType]
4.3.1                 location (0-n) [StartPos, EndPos, width, RecSegNo, fileid, locMap]
4.3.2                 labl (0-n) [level, vendor, country, sdatrefs]
4.3.3                 imputation (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
4.3.4                 security (0-n)
4.3.5                 embargo (0-n) [event, format]
4.3.6                 respUnit (0-n)
4.3.7                 anlysUnit (0-n)
4.3.8                 qstn (0-n) [qstn, var, seqNo, sdatrefs, access, responseDomainType, otherResponseDomainType]
4.3.8.1                  preQTxt (0-n)
4.3.8.2                  qstnLit (0-n) [sdatrefs]
4.3.8.3                  postQTxt (0-n)
4.3.8.4                  forward (0-n) [qstn]
4.3.8.5                  backward (0-n) [qstn]
4.3.8.6                  ivuInstr (0-n)
4.3.9                 valrng (0-n) [access]
4.3.9.1                  item (0-n) [UNITS, VALUE]
4.3.9.2                  range (0-n) [UNITS, min, minExclusive, max, maxExclusive]
4.3.9.3                  key (0-n)
4.3.9.4                  notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
4.3.10                invalrng (0-n) [access]
4.3.10.1                 item (0-n) [UNITS, VALUE]
4.3.10.2                 range (0-n) [UNITS, min, minExclusive, max, maxExclusive]
4.3.10.3                 key (0-n)
4.3.10.4                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
4.3.11                undocCod (0-n)
4.3.12                universe (0-n) [level, clusion]
4.3.13                TotlResp (0-n)
4.3.14                sumStat (0-n) [wgtd, wgt-var, weight, type, access, otherType]
4.3.15                txt (0-n) [level, sdatrefs]
4.3.16                stdCatgry (0-n) [URI, access]
4.3.17                catgryGrp (0-n) [missing, missType, catgry, catGrp, levelno, levelnm, compl, excls]
4.3.17.1                 labl (0-n) [level, vendor, country, sdatrefs]
4.3.17.2                 catStat (0-n) [type, otherType, URI, methrefs, wgtd, wgt-var, weight, sdatrefs, access]
4.3.17.3                 txt (0-n) [level, sdatrefs]
4.3.18                catgry (0-n) [missing, missType, country, sdatrefs, access, excls, catgry, level]
4.3.18.1                 catValu (0-1)
4.3.18.2                 labl (0-n) [level, vendor, country, sdatrefs]
4.3.18.3                 txt (0-n) [level, sdatrefs]
4.3.18.4                 catStat (0-n) [type, otherType, URI, methrefs, wgtd, wgt-var, weight, sdatrefs, access]
4.3.18.5                 mrow (0-1)
4.3.18.5.1                  mi (0-n) [varRef]
4.3.19                codInstr (0-n)
4.3.20                verStmt (0-n)
4.3.20.1                 version (0-n) [type]
4.3.20.2                 verResp (0-n) [affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
4.3.20.3                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
4.3.21                concept (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
4.3.22                derivation (0-1) [var]
4.3.22.1                 varRange (0-n) [start, end]
4.3.22.2                 drvdesc (0-n)
4.3.22.3                 drvcmd (0-n) [syntax]
4.3.23                varFormat (0-1) [type, formatname, schema, otherSchema, category, otherCategory, URI]
4.3.24                geoMap (0-n) [URI, mapformat, levelno]
4.3.25                catLevel (0-n) [levelnm, geoMap]
4.3.26                notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
4.4                nCube (0-n) [name, sdatrefs, methrefs, pubrefs, access, dmnsQnty, cellQnty]
4.4.1                 location (0-n) [StartPos, EndPos, width, RecSegNo, fileid, locMap]
4.4.2                 labl (0-n) [level, vendor, country, sdatrefs]
4.4.3                 txt (0-n) [level, sdatrefs]
4.4.4                 universe (0-n) [level, clusion]
4.4.5                 imputation (0-n) [vocab, vocabURI, vocabInstanceURI, vocabID, vocabAgencyName, vocabVersionID, otherValue, vocabSchemeURN, vocabInstanceCodeTerm]
4.4.6                 security (0-n)
4.4.7                 embargo (0-n) [event, format]
4.4.8                 respUnit (0-n)
4.4.9                 anlysUnit (0-n)
4.4.10                verStmt (0-n)
4.4.10.1                 version (0-n) [type]
4.4.10.2                 verResp (0-n) [affiliation, agentIdentifier, typeOfAgentIdentifer, isPersistentIdentifier, agentType]
4.4.10.3                 notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
4.4.11                purpose (0-n) [sdatrefs, methrefs, pubrefs, URI]
4.4.12                dmns (0-n) [rank, varRef]
4.4.12.1                 cohort (0-n) [catRef, value]
4.4.12.1.1                  range (0-n) [UNITS, min, minExclusive, max, maxExclusive]
4.4.13                measure (0-n) [varRef, aggrMeth, otherAggrMeth, measUnit, scale, origin, additivity]
4.4.14                notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
4.5                notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
5               otherMat (0-n) [type, level, URI]
5.1                typeOfSetAvailability (0-n)
5.2                labl (0-n) [level, vendor, country, sdatrefs]
5.3                txt (0-n) [level, sdatrefs]
5.4                notes (0-n) [type, subject, level, resp, sdatrefs, parent, sameNote]
5.5                table (0-n) [frame, colsep, rowsep, pgwide]
5.5.1                 titl (0-n)
5.5.2                 tgroup (1-n) [cols, colsep, rowsep, align]
5.5.2.1                  colspec (0-n) [colnum, colname, colwidth, colsep, rowsep, align]
5.5.2.2                  thead (0-1) [valign]
5.5.2.2.1                   row (1-n) [rowsep, valign]
5.5.2.2.1.1                    entry (1-n) [colname, namest, nameend, morerows, colsep, rowsep, align, char, charoff, valign]
5.5.2.3                  tbody (1-1) [valign]
5.5.2.3.1                   row (1-n) [rowsep, valign]
5.5.2.3.1.1                    entry (1-n) [colname, namest, nameend, morerows, colsep, rowsep, align, char, charoff, valign]
5.6                citation (0-1) --SEE Citation Contents section 1.1 inclusive--
5.7                otherMat (0-n) --RECURSIVE--``
