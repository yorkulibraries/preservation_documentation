## Web Archives - Preservation Action Plan

#### Introduction

This document describes the preservation plan for web archives content in the York University Digital Library. Most of the web archive content content is York University web sites. The preservation plan for web archives content follows from policies and practices described in the [Digital Preservation Strategic Plan](http://digital.library.yorku.ca/documentation/digital-preservation-implementation-plan) and the [Digital Preservation Implementation Plan](http://digital.library.yorku.ca/documentation/digital-preservation-implementation-plan). This document explains practical steps that York University Libraries take to preserve the intellectual content of web archives in digital format. It outlines the basic tools, methods, and standards used for the long-term preservation of web archive content.

#### Content Formats

For the preservation of web archive content, York University Libraries require WARC versions of the content, descriptive metadata, and if possible, screen captures of the archived site. During the ingest process, derivatives are created for full-text searching of web archives. York University Libraries continuously monitors developments in file formats to determine if and when formats require migration (see [Environmental Monitoring of Preservation Formats](http://digital.library.yorku.ca/documentation/environmental-monitoring-preservation-formats)).

#### SIP Format

York University Libraries create their own web archive SIPs (see [Definition of SIP](http://digital.library.yorku.ca/content/definition-sip)) using its [YUDL Web archiving](https://github.com/yorkulibraries/YUDL-Web-archiving) scripts.

#### Analysis on Ingest

Upon ingest, every file in the repository is subject to identification of its file format and validation using FITS. The output of the FITS identification and validation processes are recorded to a techincal metadata datastream (TECHMD_FITS) that is associated with the object in the repository.

#### Content Excluded

York University Libraries do not ingest files that are not referenced (either as part of a representation or as associated datastreams) in the associated metadata. As the SIP is retained, these files can later be ingested if necessary.

#### Format Normalization

There is no format normailziation if the submitted object is a WARC.

#### Metadata Normalization

When necessary, York University Libraries crosswalk descriptive metadata from MODS to Dublin Core. The repository creates preservation metadata for each file. The preservation level, explained in the [Digital Preservation Implementation Plan](http://digital.library.yorku.ca/content/digital-preservation-implementation-plan), is applied to each file upon ingest and recorded in the preservation metadata for each file.

#### Acceptable Formats

For the Full Preservation level for web archives, currently the only acceptable format is WARC.

