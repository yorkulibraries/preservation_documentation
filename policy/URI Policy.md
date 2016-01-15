# York University Library URI Policy

## Policy Statement

URIs created by York University Digital Library

* York University Digital Library uses a systematic convention to generate unambiguously unique identification for digital objects within its repository. This convention will create a stable name or reference to an object that can be permanently associated with that object, regardless of future changes to organizational structure or to digital access protocols.
* This is in conformance with section 4.2.4 of Metrics for Digital Repository Audit and Certification (CCSDS, June 2009) which states that a compliant repository "shall have and use a convention that generates persistent, unique identifiers for all AIPs" and "its components."
* This convention will ensure that “each AIP can be unambiguously found in the future” and that "each AIP can be distinguished from all other AIPs in the repository"

## Implementation

### Islandora object

York University Digital Library canonical URIs are consistently constructed in the following manner:

* `/islandora/object/PID`

These URIs are aliased using [Islandora Pathauto](https://github.com/rosiel/islandora_pathauto) to the following pattern:

* `[fedora:pid]/[fedora:label]`

Example:

* **Photograph**: New Woodbine : racehorses train for opening of season
* **Canonical URI**: http://digital.library.yorku.ca/islandora/object/yul:88675
* **Aliases URL**: http://digital.library.yorku.ca/yul-88675/new-woodbine-racehorses-train-opening-season

### Islandora object datastream

York University Digital Library object datastream canonical URIs are consistently constructed in the following manner:

* `/islandora/object/PID/datastream/DATASTREAM_NAME/view`
* `/islandora/object/PID/datastream/DATASTREAM_NAME/download`
* `[fedora:pid]/[fedora:label]/datastream/DATASTREAM_NAME/view`
* `[fedora:pid]/[fedora:label]/datastream/DATASTREAM_NAME/download`

Example:

* **Photograph**: New Woodbine : racehorses train for opening of season
* **Canonical URI**: http://digital.library.yorku.ca/islandora/object/yul:88675/datastream/JPG/view
* **Aliases URL**: http://digital.library.yorku.ca/yul-88675/new-woodbine-racehorses-train-opening-season/datastream/JPG/download

### Publicly available datastream names

Audio:

* `TN` (Thumbnail)
* `PROXY_MP3` (Streaming quality MP3)

Book:

* `TN` (Thumbnail)
* `ORIGINAL_PDF` (Only for
Buddhism Across Boundaries: Buddhist Periodicals and Books from Colonial Burma collection )

Images:

* `TN` (Thumbnail)
* `JPG` (Medium sized JPG)
* `OCR` (OCR'd text)

Metadata:

* `MODS` (Descriptive metadata)
* `DC` (Descriptive metadata)
* `TECHMD_FITS` (Technical metadata)
* `RELS-EXT` (Fedora Object to Object Relationship)

Video:

* `TN` (Thumbnail)
* `MP4` (Streaming quality MP4)

Web ARChive:

* `TN` (Thumbnail)
* `JPG` (Medium sized JPEG)
* `WARC_CSV` (WARC Index)
* `WARC_FILTERED` (WARC filtered)
* `OBJ` (Warc)

#### Acknowledgements

Adapted from and inspired by:

* OCUL's Scholars Portal "[URI & File Naming Plan](https://spotdocs.scholarsportal.info/pages/viewpage.action?pageId=89916855)".

#### License

![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")

[CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/)
