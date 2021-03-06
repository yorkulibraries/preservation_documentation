## Geospatial Vector Data - Preservation Action Plan

#### Introduction

This document describes the preservation plan for geospatial vector content in the York University Digital Library.  Most of the geospatial vector content is from the Data Library. The preservation plan for geospatial vector content follows from policies and practices described in the [Digital Preservation Strategic Plan](http://digital.library.yorku.ca/documentation/digital-preservation-implementation-plan) and the [Digital Preservation Implementation Plan](http://digital.library.yorku.ca/documentation/digital-preservation-implementation-plan). This document explains practical steps that York University Libraries take to preserve the intellectual content of geospatial vector in digital format. It outlines the basic tools, methods, and standards used for the long-term preservation of geospatial vector content.

#### Content Formats

For the preservation of geospatial vector content, York University Libraries require uncompressed SHP-SHX-DBF versions of the content, and descriptive metadata. During the ingest process, the packages are also compressed into a zip folder. York University Libraries continuously monitors developments in file formats to determine if and when formats require migration (see [Environmental Monitoring of Preservation Formats](http://digital.library.yorku.ca/documentation/environmental-monitoring-preservation-formats)).

#### SIP Format

Geospatial vector SIPs (see [Definition of SIP](http://digital.library.yorku.ca/content/definition-sip)) generally consist of a SHP file, SHX file and DBF file and an associated MODS descriptive metadata file.

#### Analysis on Ingest

Upon ingest, every file in the repository is subject to identification of its file format and validation using FITS. The output of the FITS identification and validation processes are recorded to a techincal metadata datastream (TECHMD_FITS) that is associated with the object in the repository.


#### Content Excluded

York University Libraries do not ingest files that are not referenced (either as part of a representation or as associated datastreams) in the associated metadata. As the SIP is retained, these files can later be ingested if necessary.

#### Format Normalization

There is no format normailziation if the submitted object is a SHP.

#### Metadata Normalization

When necessary, York University Libraries crosswalk descriptive metadata from MODS to Dublin Core. The repository creates preservation metadata for each file. The preservation level, explained in the [Digital Preservation Implementation Plan](http://digital.library.yorku.ca/content/digital-preservation-implementation-plan), is applied to each file upon ingest and recorded in the preservation metadata for each file.

#### Acceptable Formats

For the Full Preservation level for geospatial vector data, currently the acceptable formats are SHP. Geospatial vector submissions may also be geoJSON format.

