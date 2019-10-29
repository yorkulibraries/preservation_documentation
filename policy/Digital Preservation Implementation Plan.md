## Digital Preservation Implementation Plan

### Preservation Activities

YUL’s preservation strategies are based around the preservation of the intellectual content of the digital objects contained in YUL’s digital repositories ([YorkSpace](http://yorkspace.library.yorku.ca), [YUDL](http://digital.library.yorku.ca)) through the transformation of these objects to delay or present file obsolescence. In the course of these transformations, priority is given to maintaining the information contained in an individual content object, as opposed to preserving its appearance or a specific question.

To this end, YUL utilizes the following approaches to preservation:

**Archival File Formats**: YUL is committed to the use of file formats that support long term sustainability. In general, the considerations for selecting file formats include the “openness” of the file format, its level of support as a preservation format in the academic/scholarly community, and its uptake among YUL’s [Designated Community](http://digital.library.yorku.ca/content/digital-preservation-designated-community-definition), as well as its well-suitedness to later format migration.

**Normalization**: As mentioned above, YUL works to identify file formats well-suited to its approach to preservation and access. Upon ingest, materials not conforming to YUL’s accepted standards will be converted to one of the previously identified formats. To the extent possible, YUL will attempt to preserve the essential characteristics of the object. In cases requiring compromise, transformations that maintain the content of the object will be prioritized over those that preserve the presentation.

**Format Migration**: When YUL perceives that a portion of its content is stored in a format that is at risk of obsolescence, a new version of this content will be created in a format more suited to long-term preservation and use. This transformation may consist of migration to a newer version of the content’s existing format, or transformation to a different format altogether. In all cases, preservation of the object’s intellectual content will be prioritized over the preservation of a specific presentation style.

**Bit Stream Copying**: YUL maintains regularly scheduled backups of all information contained in YUL’s digital repositories, for use in the event of data loss. In combination with regular fixity checks, which identify potentially damaged content, this process ensures the integrity of content in YUL’s digital repositories, and provides a foundation for its disaster recovery plans.

**Fixity Checking**: All materials in the repository are subject to regular fixity checks - comparisons of checksum values calculated at a given point in time with those generated at the material’s time of ingest. This activity, when combined with bit stream copying, mitigates the risk of objects becoming corrupt in the repository, as it enables the repository managers to identify damaged or corrupted content, and to revert to a valid version of the object from a previous point in time.

**Documentation of File Formats**: Upon ingest, every file in the repository is subject to identification of its file format and other significant characteristics. Also generated is a reference to the file format’s entry (if it exists) in PRONOM, the National Archive’s online format registry. This association ensures that information is always available on the internal structure of the file, and can be further used to determine when the format migration activity should take place (if allowed by the object’s preservation level) in order to mitigate the risks posed by the obsolete file formats.

### Preservation Levels

These preservation activities are applied to materials in the repository according to the material’s designated Preservation Level, as described in the [Digital Preservation Strategic Plan](http://digital.library.yorku.ca/content/digital-preservation-strategic-plan).

**Bit-level Preservation**: Items preserved at the Bit-level Preservation level will be subject to Bit Stream Copying, Fixity Checking, and Documentation of File Formats preservation activities. This is a baseline level of preservation activity which ensures that object, once ingested into the repository, can be maintained in a valid and uncorrupted state. It also attempts to provide representation information for the object through documentation of its file format, though at this level no migration activities will take place. This preservation level should be considered less robust than the “Full Preservation” level, and should only be considered in situations where Full Preservation is not a viable strategy. Common issues of unsuitability include lack of privilege to perform migration activities on the material, the presence of material in unknown or unsupported file formats, or the material’s failure to conform to a valid format.

**Full Preservation**: Items preserved at this level will receive the benefit of all of the above-mentioned preservation activities, as appropriate. Upon ingest into the repository, the material will undergo file format identification and normalization/transformation to archival file formats. As time goes on, these formats will be monitored by YUL staff, and should the criteria for format migration be met, the files will be migrated to a new format. In addition, all activities associated with the “Bit-level Preservation” preservation level will be carried out.

**No Preservation**: In rare cases, the repository may contain material for which YUL is unable or unwilling to accept preservation responsibility. Although incidental preservation activities may take place upon this material, YUL accepts no responsibility for its long-term accessibility or validity. This level is an exception to YUL’s digital preservation activities, rather than a part of its preservation strategy, but is included here for completeness. Examples of materials at this level would include objects that are known to be corrupt or not authorized for preservation at any level but which, for some reason, cannot be deleted immediately.

#### Acknowledgements

Adapted from and inspired by:

* OCUL's Scholars Portal "[Preservation Implementation Plan](https://spotdocs.scholarsportal.info/display/OAIS/Preservation+Implementation+Plan)".

#### License

![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")

[CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/)
