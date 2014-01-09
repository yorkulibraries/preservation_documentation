## Definition of AIP

### Archival Information Package (AIP)

- The information package consisting of the Content Information (CI), Preservation Description Information (PDI), Packaging Information (PI), and Descriptive Information (DI) that is archived at York University Library.
- The level of content in a York University Digital Library AIP can vary, depending on the amount of content provided by the submitter.
- This description will use the OAIS Information Model to illustrate completeness of our conceptual model, and will describe, in general terms, what a York University Library AIP looks like.

**Content Information (CI)**

- The Content Data Object is generally stored with from the primary preservation metadata file, which is held in Fedora Commons.
- Representation Information is maintained, and contains information on the CDO's file format, version, and a reference to a format registry in order to provide information on how to interpret the file. See: [registry of file formats](http://digital.library.yorku.ca/content/registry-file-formats) 

**Preservation Description Information (PDI)**

- *Reference Information* - Identifiers are stored for each object identifying it globally (e.g. YUL PID) and locally (e.g. URI).
- *Provenance Information* - Provenance metadata is maintained for each object that provides a history of preservation events in the object's lifetime, beginning at ingest into the YUL Digital Library repository and referencing any preservation activities taken on the object (e.g., replacement due to corruption, format migration, etc.).
- *Context Information* - As appropriate, information on how a CDO relates to other CDOs or to other conceptual entities. Examples of these relationships can include: a newer version of an object that supersedes an older one.
- *Fixity Information* - Fixity information is generated at the time of ingest in order to later determine whether or not the item remains in the same state as when it was ingested. This information can be used to determine integrity of an object being copied within the system (as in the case of a change in storage location), or for periodic integrity checks.

**Packaging Information (PI)**

- YUL preservation metadata packages both the descriptive and preservation metadata together. 

**Descriptive Information (DI)**

- Depending on the type of CDO, the format of this descriptive metadata can vary (MODS or Dublin Core), but is selected to maximize findability. In all cases, the descriptive metadata will be recreated within the preservation metadata.
