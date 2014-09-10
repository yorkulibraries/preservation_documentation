## Metadata Specificiations

**1. Policy Statement**

York University Digital Library requires thorough, well-structured metadata in order to preserve the content, relationships, activities and logical structure of the object.

**2. Implementation**

* Each object in YUDL has a [MODS (Metadata Object Description Schema)](http://www.loc.gov/standards/mods/) datastream to provide descriptive metadata.
* Each object in YUDL has a TECHMD_FITS ([see Registry of file formats](https://digital.library.yorku.ca/documentation/registry-file-formats)) datastream to provide file identification and characterizationi information.
* Each object in YUDL has a RELS-EXT (Releationship External) datastream that describes the object's relationship(s) to other object's in the repository.
* Each object in YUDL has a POLICY (XACML) datastream for AuthZ.
* YUDL utilizes the PREMIS (Preservation Metadata Implementation Strategy) vocabulary via [Islandora PREMIS](https://github.com/islandora/islandora_premis). PREMIS's data dictionary provides ways of describing objects and processes that are necessary for digital preservation. YUDL makes use of the objects, events and rights entities described in the PREMIS Data Model.
