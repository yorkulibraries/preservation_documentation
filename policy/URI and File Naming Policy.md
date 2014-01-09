# York University Library URL and File Naming Policy

**DRAFT**

## Policy Statement

URIs created by York University Digital Library

* York University Digital Library uses a systematic convention to generate unambiguously unique identification for digital objects within its repository. This convention will create a stable name or reference to an object that can be permanently associated with that object, regardless of future changes to organizational structure or to digital access protocols.
* This is in conformance with section 4.2.4 of Metrics for Digital Repository Audit and Certification (CCSDS, June 2009) which states that a compliant repository "shall have and use a convention that generates persistent, unique identifiers for all AIPs" and "its components."
* This convention will ensure that “each AIP can be unambiguously found in the future” and that "each AIP can be distinguished from all other AIPs in the repository"

## Implementation

### Islandora object

York University Digital Library canonical URIs are consistently constructed in the folloiwng manner:

* `/islandora/object/PID`

These URIs are aliased using [Islandora Pathauto](https://github.com/rosiel/islandora_pathauto) to the following pattern:

* `[fedora:pid]/[fedora:label]`

Example:

* **Photograph**: New Woodbine : racehorses train for opening of season
* **Canonical URI**: http://digital.library.yorku.ca/islandora/object/yul:88675
* **Aliases URL**: http://digital.library.yorku.ca/yul-88675/new-woodbine-racehorses-train-opening-season

### URIs for individual files and events created by York University Libraries


