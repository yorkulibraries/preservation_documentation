## Backup Plan

**1. Policy Statement**

As part of YUL's implementation of the Bit-stream Copying Preservation Strategy (as detailed in the [Preservation Implementation Plan](https://digital.library.yorku.ca/documentation/digital-preservation-implementation-plan)), YUL is committed to regular backup procedures of both data storage areas and its operational areas (e.g. databases, application files). These backups are intended to serve as the basis for restoration of York University Library materials in the case of disaster recovery or corruption of data.

Data backup at York University Library is coordinated through Library Computing Systems and University Information Technology. Since the data is stored on physical hardware located in the university data centre, it uses the same backup hardware and software as the general university systems.

**2. Implementation Examples**

2.1 Database Backup

This backup strategy applies to content that is stored in a database. Primarily, this refers to objects located in YUDL's databases (MySQL).

2.1.1 MySQL Database Backup Strategy

* Database dumps are backed up daily and taken off site. Each backup is kept for 60 days.

2.2 Application Backup

2.2.1 Fedora Commons Backup Strategy

* Fedora Commons is backed up daily and taken off site. Each backup is kept for 60 days.

2.2.2 Drupal (Islandora)

* Drupal is backed up daily and taken off site. Each backup is kept for 60 days.

2.2.3 Solr

* Solr is backed up daily and taken off site. Each backup is kept for 60 days.

2.3 Objects

* Fedora objects are backed up daily and taken off site. Each backup is kept for 60 days.

#### Acknowledgements

Adapted from and inspired by:

* OCUL's Scholars Portal "[Backup Plan](https://spotdocs.scholarsportal.info/display/OAIS/Backup+Plan)".

#### License

![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")

[CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/)
