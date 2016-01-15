## Fixity procedures

#### Policy Statement

York University Library are committed to maintaining the integrity of objects in its care. This includes creating checksums for all archival format objects -- plus associated datastreams -- ingested into the repository, and regular fixity checking of those objects.

#### Implementation

At the time of ingest an MD5 checksum value is calculated for the archival format object, and is stored along the object in the repository.

Daily, a set number of  files in the repository will have their current checksum calculated (using a single checksum) and compared to this stored value, which is expected to match. In cases where the calculated and stored values do not match, this is reported to the repository manager.

#### Acknowledgements

Adapted from and inspired by:

* OCUL's Scholars Portal "[Fixity Check Procedures](https://spotdocs.scholarsportal.info/display/OAIS/Fixity+Check+Procedures)".

#### License

![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")

[CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/)
