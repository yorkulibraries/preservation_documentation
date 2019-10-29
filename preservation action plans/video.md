#### Introduction

This document describes the preservation plan for video content in the York University Digital Library. Most of the video content content is from the Sound and Moving Image Library and the Clara Thomas Archives and Special Collections. The preservation plan for video content follows from policies and practices described in the [Digital Preservation Strategic Plan](http://digital.library.yorku.ca/documentation/digital-preservation-implementation-plan) and the [Digital Preservation Implementation Plan](http://digital.library.yorku.ca/documentation/digital-preservation-implementation-plan). This document explains practical steps that York University Libraries take to preserve the intellectual content of video in digital format. It outlines the basic tools, methods, and standards used for the long-term preservation of video content.

#### Content Formats

For the preservation of video content, York University Libraries require uncompressed 8 or 10 bit AVI versions of the content, and descriptive metadata. During the ingest process, derivatives are created for streaming. York University Libraries continuously monitors developments in file formats to determine if and when formats require migration (see [Environmental Monitoring of Preservation Formats](http://digital.library.yorku.ca/documentation/environmental-monitoring-preservation-formats)).

#### SIP Format

Video SIPs (see [Definition of SIP](http://digital.library.yorku.ca/content/definition-sip)) generally consists of an AVI file, and an associated MODS descriptive metadata file.

#### Analysis on Ingest

Upon ingest, every file in the repository is subject to identification of its file format and validation using FITS. The output of the FITS identification and validation processes are recorded to a techincal metadata datastream (TECHMD_FITS) that is associated with the object in the repository.

#### Content Excluded

York University Libraries doe not ingest files that are not referenced (either as part of a representation or as associated datastreams) in the associated metadata. As the SIP is retained, these files can later be ingested if necessary.

#### Format Normalization

There is no format normailziation if the submitted object is an uncompressed 8 or 10 bit AVI.

#### Metadata Normalization

When necessary, York University Libraries crosswalk descriptive metadata from MODS to Dublin Core. The repository creates preservation metadata for each file. The preservation level, explained in the [Digital Preservation Implementation Plan](http://digital.library.yorku.ca/content/digital-preservation-implementation-plan), is applied to each file upon ingest and recorded in the preservation metadata for each file.

#### Acceptable Formats

For the Full Preservation level for video, currently the acceptable formats are AVI. Video submissions may be MPEG, MP4, OGG, MKV, or Quicktime format, however they will be preserved at the Bit-level Preservation level.

#### Acknowledgements

Adapted from and inspired by:

* OCUL's Scholars Portal "[Collection Policy](https://spotdocs.scholarsportal.info/display/OAIS/Collection+Policy)".

#### License

![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")

[CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/)
