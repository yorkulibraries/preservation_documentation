## Registry of file formats

### Policy Statement

YUDL requires immediate identification of the type of file format submitted in order to help mitigate risk posed by format obsolescence. To this end, YUDL employs the use of [DROID](http://www.nationalarchives.gov.uk/information-management/projects-and-work/droid.htm), [JHOVE](http://jhove.sourceforge.net/), [file utility](http://unixhelp.ed.ac.uk/CGI/man-cgi?file), [Exiftool](http://www.sno.phy.queensu.ca/~phil/exiftool/), [PRONOM](http://www.nationalarchives.gov.uk/PRONOM/Default.aspx), [NLNZ Metadata Extractor](http://meta-extractor.sourceforge.net/), [ffident](http://web.archive.org/web/20061106114156/http://schmidt.devlib.org/ffident/index.html), and [Tika](http://tika.apache.org/) through the [FITS](http://code.google.com/p/fits/) software package.

While YUDL is not dependent on or restricted to any particular format or group of formats, it aims to use well-known, widely accepted formats that support long-term preservation. If a submitter wants to use a specific format not meeting these criteria, an agreement must be reached between the submitter and YUDL.

### Implementation Examples

YUDL makes use of FITS for format identification during the ingestion process where a file format is associated with each file.

Example characterization and reference to format registry:

    <?xml version="1.0" encoding="UTF-8"?>
    <fits xmlns="http://hul.harvard.edu/ois/xml/ns/fits/fits_output" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://hul.harvard.edu/ois/xml/ns/fits/fits_output http://hul.harvard.edu/ois/xml/xsd/fits/fits_output.xsd" version="0.7.4 (fits-mcgath fork)" timestamp="02/07/13 4:26 PM">
      <identification>
        <identity format="Tagged Image File Format" mimetype="image/tiff" toolname="FITS" toolversion="0.7.4 (fits-mcgath fork)">
          <tool toolname="Jhove" toolversion="1.9" />
          <tool toolname="file utility" toolversion="5.09" />
          <tool toolname="Exiftool" toolversion="9.13" />
          <tool toolname="NLNZ Metadata Extractor" toolversion="3.4GA" />
          <tool toolname="ffident" toolversion="0.2" />
          <tool toolname="Tika" toolversion="1.3" />
          <version toolname="Jhove" toolversion="1.9">5.0</version>
        </identity>
      </identification>
      <fileinfo>
        <size toolname="Jhove" toolversion="1.9">33543972</size>
        <creatingApplicationName toolname="Exiftool" toolversion="9.13">Adobe Photoshop Elements 2.0</creatingApplicationName>
        <lastmodified toolname="Exiftool" toolversion="9.13" status="CONFLICT">2007:03:09 11:00:49-05:00</lastmodified>
        <lastmodified toolname="Tika" toolversion="1.3" status="CONFLICT">2007-03-09T11:00:48</lastmodified>
        <filepath toolname="OIS File Information" toolversion="0.1" status="SINGLE_RESULT">/mnt/DIY/Archives/ASC/tiffs/02000-02999/ASC02000.tif</filepath>
        <filename toolname="OIS File Information" toolversion="0.1" status="SINGLE_RESULT">/mnt/DIY/Archives/ASC/tiffs/02000-02999/ASC02000.tif</filename>
        <md5checksum toolname="OIS File Information" toolversion="0.1" status="SINGLE_RESULT">b2b263bf5207481e42ac5945538ec985</md5checksum>
        <fslastmodified toolname="OIS File Information" toolversion="0.1" status="SINGLE_RESULT">1173456049000</fslastmodified>
      </fileinfo>
      <filestatus>
        <well-formed toolname="Jhove" toolversion="1.9" status="SINGLE_RESULT">true</well-formed>
        <valid toolname="Jhove" toolversion="1.9" status="SINGLE_RESULT">true</valid>
      </filestatus>
      <metadata>
        <image>
          <byteOrder toolname="Jhove" toolversion="1.9" status="SINGLE_RESULT">little endian</byteOrder>
          <compressionScheme toolname="Jhove" toolversion="1.9">Uncompressed</compressionScheme>
          <imageWidth toolname="Jhove" toolversion="1.9">7108</imageWidth>
          <imageHeight toolname="Exiftool" toolversion="9.13">4716</imageHeight>
          <colorSpace toolname="Jhove" toolversion="1.9">BlackIsZero</colorSpace>
          <orientation toolname="Jhove" toolversion="1.9" status="SINGLE_RESULT">normal*</orientation>
          <samplingFrequencyUnit toolname="Jhove" toolversion="1.9" status="CONFLICT">in.</samplingFrequencyUnit>
          <samplingFrequencyUnit toolname="Tika" toolversion="1.3" status="CONFLICT">Inch</samplingFrequencyUnit>
          <xSamplingFrequency toolname="Jhove" toolversion="1.9" status="CONFLICT">6000000/10000</xSamplingFrequency>
          <xSamplingFrequency toolname="Exiftool" toolversion="9.13" status="CONFLICT">600</xSamplingFrequency>
          <xSamplingFrequency toolname="NLNZ Metadata Extractor" toolversion="3.4GA" status="CONFLICT">600.0</xSamplingFrequency>
          <ySamplingFrequency toolname="Jhove" toolversion="1.9" status="CONFLICT">6000000/10000</ySamplingFrequency>
          <ySamplingFrequency toolname="Exiftool" toolversion="9.13" status="CONFLICT">600</ySamplingFrequency>
          <ySamplingFrequency toolname="NLNZ Metadata Extractor" toolversion="3.4GA" status="CONFLICT">600.0</ySamplingFrequency>
          <bitsPerSample toolname="Jhove" toolversion="1.9" status="CONFLICT">integer</bitsPerSample>
          <bitsPerSample toolname="Exiftool" toolversion="9.13" status="CONFLICT">8</bitsPerSample>
          <samplesPerPixel toolname="Jhove" toolversion="1.9">1</samplesPerPixel>
          <scanningSoftwareName toolname="Jhove" toolversion="1.9">Adobe Photoshop Elements 2.0</scanningSoftwareName>
          <YSamplingFrequency toolname="Tika" toolversion="1.3" status="SINGLE_RESULT">600.0</YSamplingFrequency>
        </image>
      </metadata>
    </fits>
</pre>

#### Acknowledgements

Adapted from and inspired by:

* OCUL's Scholars Portal "[Collection Policy](https://spotdocs.scholarsportal.info/display/OAIS/Collection+Policy)".

#### License

![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")

[CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](http://creativecommons.org/publicdomain/zero/1.0/)
