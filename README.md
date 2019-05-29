# AMI Project Administration and Handling

<!-- MarkdownTOC -->

- [Introduction](#introduction)
- [Documentation](#documentation)
- [Media Formats](#media-formats)
- [Digital Asset Deliverables](#digital-asset-deliverables)
- [Metadata](#metadata)
- [Images](#images)
- [Digital Asset and Hard Drive Structure](#digital-asset-and-hard-drive-structure)
- [Digital Asset Delivery](#digital-asset-delivery)
- [Quality Assurance and Quality Control](#quality-assurance-and-quality-control)
- [Environment and Security](#environment-and-security)
- [Shipment of Physical Media](#shipment-of-physical-media)
- [Treatment, Handling, and Rehousing of Physical Media](#treatment,-handling,-and-rehousing-of-physical-media)
- [Specifications for Digital Assets](#specifications-for-digital-assets)


<!-- /MarkdownTOC -->

<a name="introduction"></a>
## Introduction

All tasks must comply with NYPL specifications, which are maintained in publically available GitHub pages. Actions to resolve unforeseen issues must be approved in writing by NYPL. The winning vendor(s) is expected to subscribe and refer to (“watch”) updates to the following GitHub repositories or pages:

  * ami-handling: (https://github.com/NYPL/ami-handling)
  * ami-specifications: (https://github.com/NYPL/ami-specifications)
  * ami-metadata: (https://github.com/NYPL/ami-metadata)
  * external-storage: (https://github.com/NYPL/digpres-policies/blob/master/external_storage.md)

<a name="documentation"></a>
## Documentation

### Statement of Work (SOW)
  * Produced by: NYPL
  * Scope: description of body of work covered by a discrete budget, schedule, and quantity of materials.
### Metadata inventory
  * Produced by: NYPL
  * Scope: object inventory with starter metadata, covered by statement of work and purchase order.
### Vendor quote
  * Produced by: Vendor
  * Scope: Scope as described by a single Statement of Work (SOW)
  * Expected: following receipt of SOW or work request
  * Format: PDF and/or Excel Spreadsheet
  * Naming convention: add SOW prefix and date to Contractor’s naming convention.
  * Data fields / required information
    * Fee schedule: include line item quantity, cost per object, and subtotal for each:
      * Digitization of media formats
      * Rehousing, and supplies
      * Special treatment
      * Hard drive shipping fees
      * Hard drives storage
## Original Media Shipping Document
  * Produced by: Sender
  * Scope: Box-level inventory of physical media objects in shipment.
  * Format: PDF
  * Instructions: Sender, shipper, and recipient should sign and date the document. Completed document will be scanned to PDF and copied to NYPL and Vendor project coordinators.
### Discrepancy report
  * Produced by: Vendor
  * Scope: list of objects for which there are discrepancies between inventory and actual objects:
      * a) there are objects listed in inventory that were not received by vendor as expected; or
      * b) there are objects received by the vendor that were not listed in the inventory and/or for which accurate metadata was not yet provided by NYPL.
  * Template for Discrepancy Report: (https://github.com/NYPL/ami-handling/blob/master/templates/2020_000_discrepancies_yyyymmdd.xlsx )
### Hard Drive Manifest
  * Produced by: Vendor
  * Scope: assets contained on hard drive
  * Expected: with each hard drive shipped
  * Instructions: the hard drive manifest should be stored in the root directory of the hard drive (do not combine hard drives)
  * Template for "HD Manifest": (https://github.com/NYPL/ami-handling/blob/master/templates/2020_000_example1_DRIVEID_hdmanifest_yyyymmdd.xlsx
)
### Did Not Capture Report
  * Produced by: Vendor
  * Scope: list of physical objects that were unable to be fully transferred
  * Expected: via email at conclusion of project
  * Template for "Did Not Capture" report: (https://github.com/NYPL/ami-handling/blob/master/templates/2020_000_example1_didnotcapture_yyyymmdd.xlsx )

<a name="media-formats"></a>
## Media Formats

  The formats covered by this agreement are described in the following charts. Additional formats may be identified as inventory work continues.


  |Group| Type | Formats |
  | --- | --- | ---- |
  | Film Group 1 | Motion Picture Film, silent | <ul><li>8mm</li><li>Super 8mm</li><li>Double 8mm</li><li>16mm</li><li>35mm</li></ul>
  | Film Group 2 | Motion Picture Film, sound | <ul><li>8 mm</li><li>Super 8mm</li><li>16mm</li><li>35mm</li>
  | Film Group 3 | Audio Film | <ul><li>16mm full-coat magnetic audio</li><li>16mm optical track</li><li>35mm full-coat magnetic audio</li><li>35mm optical track</li></ul></li>
  | Film Group 4 | Filmstrip | <ul><li>16mm filmstrip</li><li>35mm filmstrip</li></ul></li>


  |Group| Type | Formats |
  | --- | --- | ---- |
  | Video Group 1 | Video Cassette Analog | <ul><li>Betacam Oxide</li><li>Betacam SP</li><li>Betamax</li><li>Hi8</li><li>MII</li><li>S-VHS</li><li>S-VHS-C</li><li>U-matic</li><li>U-matic SP</li><li>VHS</li><li>VHS-C</li><li>Video8</li></ul> | Video Cassette Digital | <ul><li>D-1</li><li>D-2</li><li>D-3</li><li>D-5</li><li>D-9</li><li>Digital Betacam</li><li>HDCAM</li><li>HDCAM SR</li><li>HDCAM SX</li><li>MPEG IMX</li></ul></li> | Video Reel Analog | <ul><li>Two-inch quad open-reel (LoBand, HiBand and SuperHiBand)</li><li>One-inch open-reel, Type A</li><li>One-inch open-reel, Type C</li><li>One-inch open-reel, EV</li><li>One-inch open reel video, IVC</li><li>One-inch open-reel, other/non-standard</li><li>Half-inch open-reel, Sony CV</li><li>Half-inch open-reel, EIAJ/AV Standard (Types 1 & 2)</li><li>Half-inch open-reel, other/non-standard</li></ul></li>
  | Video Group 2 | Video Cassette DV | <ul><li>Digital8</li><li>DVCam</li><li>MiniDV</li><li>HDV</li><li>DVCPRO</li><li>DVCPRO 50</li><li>DVCPRO HD</li></ul></li>
  | Video Group 3 | Video Optical Disc | <ul><li>DVD, pressed</li><li>DVD±R</li><li>DVD±RW</li><li>Blu-Ray</li><li>Laser Disc</li><li>VCD</li></ul></li>


  |Group | Type | Formats |
  | --- | --- | ---- |
  | Audio Group 1 (Analog Magnetic) | Audio Reels Analog | <ul><li>Half-inch open-reel audio</li><li>One-inch open-reel audio</li><li>Quarter-inch open-reel audio</li><li>Two-inch open-reel audio</li></ul>
  | Audio Group 1 (Analog Magnetic) | Audio Cassettes Analog | <ul><li>8-track</li><li>Compact Cassette</li><li>Microcassette</li><li>Minicassette</li><li>Fidelipac Cartridge</li><li>RCA Tape Cartridge</li><li>NAB Cartridge</li><li>Elcaset (L-Cassette)</li>
  | Audio Group 1 (Analog Magnetic) | Audio Wire | <ul><li>Magnetic Wire (Webster Chicago)</li>


  |Group | Type | Formats |
  | --- | --- | --- |
  | Audio Group 2 (Digital Magnetic) | Audio Cassettes Digital | <ul><li>ADAT</li><li>DAT</li><li>DA-88</li><li>Digital Compact Cassette</li><li>U-matic/PCM</li><li>Betamax/PCM</li><li>VHS/PCM</li><li>Hi8/PCM</li><ul>
  | Audio Group 2 (Digital Magnetic) | Audio Reels Digital | <ul><li>ProDigi</li><li>DASH</li></ul><ul><li>NAGRA-D</li>
  | Audio Group 3 | Audio Optical Disc | <ul><li>Audio CD-DA</li><li>Audio CD±R</li><li>Audio CD±RW</li><li>Audio CD, pressed</li><li>DVD-Audio</li><li>Minidisc</li><ul>
  | Audio Group 4 | Audio Grooved Disc | <ul><li>Aluminum-based lacquer coated discs</li><li>Glass-based lacquer coated discs</li><li>Paper-based lacquer coated discs</li><li>Microgroove discs (LP, Vinyl)</li><li>Replicated coarse groove disc (Shellac)</li><li>Gray Audograph discs</li><li>Edison Diamond Disc</li><li>Edison Voicewriter/li><li>Flexible disc/li><li>Gelatin disc/li><li>Metal disc/li><li>Metal master disc/li><ul>
  | Audio Group 5 | Audio Grooved Cylinder | <ul><li>Brown wax</li><li>Molded and Black Amberol</li><li>Blue Amberol / US Everlasting Indestructible</li><li>Dictabelt</li><ul>


  |Group | Type | Formats |
  | ----- | ----- | ------ |
  | Data Group 1 | Data optical disc | <ul><li>CD±R</li><li>CD±RW</li><li>DVD±RW</li><ul>


<a name="digital-asset-deliverables"></a>
## Digital Asset Deliverables

“Digital asset” is defined as a group of files resulting from digitization, and describes a single NYPL collection object with a single unique identifier. All digital assets must meet the provided specifications and packaging requirements. Specifications may be modified over time to reflect changes in best practices or NYPL’s digital infrastructure, or to accommodate unexpected media formats, configurations, or conditions. The following chart provides an overview of what files are expected within digital assets produced for each media type:

|Files| Film | Video | Audio | Data |
| ------ | --- | --- | --- | --- |
| Preservation master file (pm) | x | x | x | x |
| Edit (em) or mezzanine (mz) master file | x |  | x |  |
| Service file (sc) | x | x |  |  |
| Metadata file (for each media files) | x | x | x |  |
| Images | x | x | x | x |
| Sidecar files (gz, scc, cue, etc.) | as specified |  |
| BagIt manifests | as specified |


<a name="metadata"></a>
## Metadata

### NYPL Metadata inventory
NYPL will provide the vendor with a Microsoft Excel spreadsheet containing identifying and descriptive information about each NYPL collection object included in the PO.  Note that one collection object with a single unique primary id may contain multiple physical objects (for example: a double compact cassette case).

### NYPL JSON schema
NYPL metadata deliverables must adhere to customized fields and controlled vocabulary defined within NYPL’s JSON Schema. The schema, sample files, and validation instructions are hosted on GitHub: (https://github.com/NYPL/ami-metadata)
  * Metadata must be packaged as a single JSON file for each audio, video, or film media file (Images do not require JSON metadata).
  * Metadata must validate against JSON schema. Any invalid files or errors will be corrected by the vendor and require redelivery of an entire Bagged digital asset.
  * Metadata files must be named with the same root as the media file to which they pertain, but must not include the original extension of the media file. Example:
    * Correct: [filename].json
    * Incorrect: [filename].mov.json

The vendor will be responsible for the following:
  * maintaining a system that is able to easily sync with and incorporate updates from NYPL’s live GitHub repository, ami-metadata, and
* generating metadata about the source object, preservation master and derivative files, treatment and digitization processes, and the transfer operator.

### Metadata content

  * The required contents of the metadata files are defined by the JSON metadata schema. According to that schema, metadata will be produced for each deliverable that includes the following designated categories:
    * Bibliographic (provided by NYPL)
    * Source (partially provided by NYPL)
    * Technical
    * Digitization process
    * Digitizer
* Metadata must use the only the fields and values defined in the schema.
* If there is a question about a field, if the provided vocabulary does not accurately describe an object or process, or if a list of terms is insufficient, contact NYPL for guidance on how to proceed. NYPL may approve and release new terms on the schema depending on priority.
* Metadata fields must not be empty. Refer to the schema or contact NYPL for allowances of “unknown” as a value.

### Metadata notes fields

The metadata schema includes a number of ‘notes’ fields which must be used as described below:
  * bibliographic.accessNotes: NYPL added. No additional input required
  * bibliographic.contentNotes: any additional content notes (“title program ends mid-tape, followed by another program”; "contains explicit content")
  * technical.signalNotes: audiovisual signal characteristics noticed during capture ("tracking errors; audio buzz")
  * source.notes.physicalConditionDigitizationNotes: description of pre-existing damage or decay not already noted in PreShip notes (“broken leader”; "bad splices")
  * source.notes.physicalConditionPreShipNotes: NYPL added. No additional input required
  * digitizationProcess.notes.processNotes: rehousing, adding leader, baking, cleaning

### Metadata errors

  * If the technical characteristics or format of an object have provided by NYPL are incorrect (i.e. metadata inventory describes the format as “video cassette analog” and it is actually “audio cassette digital” with a format of “Umatic/PCM”), please
  * provide corrected metadata. Make any changes to source object metadata elements that would be appropriate, and note the correction in the "digitization.notes.processNotes". Example text:
    * "NYPL-provided metadata incorrectly listed [insert field name here] as [insert wrong content here]; JSON reflects correct [field name]"

### BEXT Metadata
The following BEXT metadata must be captured in the original Broadcast Wave files to ensure retention in the final FLAC deliverable.

| BEXT field | Explanation | Sample data |
| ---- | ----- | ---- |
| Description | Description of who created the file | File generated by Vendor Services, US |
| Originator | Country code, Institution | US, The New York Public Library |
| OriginatorReference | technicalFileName | myt_123456_v01f01_pm |
| OriginationDate | Date file created in YYYY-MM-DD format | 2017-06-23 |
| OriginationTime | Time file created in hh:mm:ss format | 11:20:47 |
| BextVersion | | 1 |
| CodingHistory | Signal chain from which the digital file was created, starting with the analog or digital source. There are six elements that can be included in the coding history: 1. A = coding algorithm (analog, PCM, etc.) 2. F = sampling frequency in Hz 3. B = bit rate (for MPEG only) 4. W = word length or bit depth 5. M = mode or sound field (mono, stereo) 6. T = free text to describe playback and capture equipment | A=PCM,F=44100,W=16,M=stereo,T=TSSTcorp DVDRW SH-216BB; Compact DiscA=PCM,F=44100,W=16,M=stereo,T=dBpoweramp 14.3; Import CDDA as WAV |

<a name="images"></a>
## Images

All magnetic and optical media and enclosures must be photographed in order to capture significant bibliographic annotations or other content. Film will not be photographed.

### Image file naming convention
Image files should follow the same pattern as the media files, and be placed in the Images directory, at the same hierarchical level as the PreservationMasters and EditMasters directory: division_PrimaryID_v#f#  (front/back/top/bottom/left/right/etc).jpg

  * PrimaryID
    * Data  
      * PreservationMasters
      * EditMasters
      * Images
        * division_PrimaryID_v01f01.jpg
        * division_PrimaryID_v01f02.jpg
        * division_PrimaryID_v01_front.jpg
        * division_PrimaryID_v01_back.jpg
        * division_PrimaryID_v01_side1.jpg
        * division_PrimaryID_v01_side2.jpg

**_Image Specifications for photographs of media objects:_**


|Attribute| Specification |
| --- | ------ |
| Source format | (all magnetic and optical media) |
| --- | ------ |
| Bit depth | 8 bits per RGB Channel |
| Colorspace (embedded ICC profile) | sRGB IEC61966-2.1 |
| File format & extension | JPEG (.jpg) |
| Resolution | Minimum 400 true DPI, without interpolation }
| Surfaces| All enclosures: Front, back, top, bottom, left side, right side (if applicable)
| Notes | Images with text or content to which ‘orientation’ applies should be oriented correctly (i.e. for the language in which any text is written); If sides, top, or bottom do not have content, do not capture. If media object itself has extensive labeling, please include media alongside enclosure in applicable photographs (i.e. side of tape with side of case in the same shot). |

<a name="digital-asset-and-hard-drive-structure"></a>
## Digital Asset and Hard Drive Structure

### Hard drive structure
Sort digital assets according to source object media types. Each hard drive must contain a directory at the root level that specifies the media type. Each media type directory must only contain completed digital assets (Bags). If a media type directory is present, it must contain digital assets (empty directories are not acceptable). Name root directories using the following terms where applicable:
  * Audio
  * Video
  * Film
  * Data

No hidden files may be stored on the drive or within the subdirectories or Bags (including .DS_Store, Trash or Recycling Bin, thumbs.db), and these files must not be listed in any manifests.

### Digital asset packaging
Package digital assets using the BagIt specification (V0.97) (https://tools.ietf.org/html/rfc8493).
  * Bag Requirements
    * The Bag payload must contain the digital assets organized within a directory structure described by NYPL.
    * The Bag directory must be named with the Primary ID of the collection object represented by the files in the bag.
    * The Bag must contain an md5 manifest that lists every file in the data directory and their md5 checksums.
    * The Bag must contain all of the media and metadata files from one, and only one, inventoried collection object.
    * The Bag should be created with a tool using BagIt Library 4.4 or higher.
    * The Bag may include a tagmanifest.txt file. Some bagging software produces this file automatically. It is not required to produce or delete these files.
    * The Bag and the files within it must not be compressed with zip, tar, etc.
  * Subdirectories
    * Sub-directories must be exactly named as they are written here, in plural form, regardless of the number of files within the directory.
    * Film Bags must contain the following subdirectories within the data directory:
      * PreservationMasters
      * Mezzanines
      * ServiceCopies
      * Images
    * Data Bags must contain the following subdirectories within the data directory:
      * PreservationMasters
      * Images

      * Files
      * For each preservation master file in the PreservationMasters directory, corresponding derivative file/s must exist.
      * Each audio, film, video media, or data file in the Bag must have a corresponding JSON metadata file (image files do not require metadata).
    * Example structure:
        * NYPL000001
          * 2017_001_jones1_hdmanifest_20171201.xls
          * Audio
            * division_PrimaryID
              * data
                * Images
                  * division_PrimaryID_v01f01.jpg
                  * division_PrimaryID_v01f02.jpg
                  * division_PrimaryID_v01_front.jpg
                  * division_PrimaryID_v01_back.jpg
                * PreservationMasters
                  * division_PrimaryID_v01f01_pm.flac
                  * division_PrimaryID_v01f01_pm.json
                  * division_PrimaryID_v01f02_pm.flac
                  * division_PrimaryID_v01f02_pm.json
                * EditMasters
                  * division_PrimaryID_v01f01_em.flac
                  * division_PrimaryID_v01f01_em.json
                  * division_PrimaryID_v01f02_em.flac
                  * division_PrimaryID_v01f02_em.json
                * bag-info.txt
                * bagit.txt
                * manifest-md5.txt
                * tagmanifest-md5.txt

### File naming convention

NYPL will provide the vendor with a filename “root” for each collection object, consisting of a three-letter prefix, the primary ID, a volume number (and a face number for audio objects), and a two-letter suffix indicating the role of the file.  These sections are each separated by an underscore: (prefix)_ primary ID)_ (components) _ (file role).ext

  * Video example: myd_123456_v01_pm.mkv
  * Audio example : myh_987654_v01f01r01_pm.flac

    It is the vendor’s responsibility to complete  the filename to accommodate multiple volumes, faces, regions, etc. where applicable, as defined by the filename components listed below.

### Filename components
  * A file name must use the following components to represent the portion of a physical media object represented by the file (see “component” chart). Example:
  * The file representing the second take of the second part of the third stream of the second region of the second face of an object marked as volume 1 is named as myd_259382_v01f02r02s03p02t02_pm.wav.

| **Component** | **Use** | **Note** |
| ---- | ----- | ---- |
| Volume: v## | <ul><li>A Volume is one video or audio object in a set of objects, when that set has been assigned a single primary identifier (i.e. NYPL Primary ID)</li> | Audio and video |
| Face: f## | <ul><li>A Face is a stream or track, or a group of streams or tracks which play synchronously, within an audio object. Every audio object has at least one Face.</li><li>Some optical video formats are double-sided (rare)</li> | Audio and video |
| Region: r## | <ul><li>A Region is a subdivision of a Face.</li><li>Regions are most often defined by a required change in playback characteristics of an object's Face (speed, EQ, track configuration, color encoding system etc.).</li> | Audio and video |
| Stream: s## | <ul><li>The Stream element is used to describe multi-track and multi-channel audio objects only.</li><li>Streams are one-channel or interleaved two-channel audio streams which comprise a multi-channel or multi-track audio object.</li> | Audio only |
| Part: p## | <ul><li>The part element is used when digitization of a single face of an audio or video object requires interruption because the size of the resulting file would exceed technical limits if captured all at once.</li><li>The part element may also be used when a single tape contains sections of content that are each given different unique identifiers (rare; each section would be a distinct Part).</li> | Audio and video |

### File role
A media file name must record its intended role using one of the following suffix codes:
  * pm: Preservation Master, created for every physical media object
  * mz: Mezzanine, created for every motion picture film (film groups 1 and 2)
  * em: Edit Master, created for audio files
  * sc: Service Copy, created for video files
  * image files do not require a role suffix

<a name="digital_asset_delivery"></a>
## Digital Asset Delivery

### Delivery method
  * New hard drive(s)  must adhere to the following specifications outlined by NYPL digital preservation requirements: (https://github.com/NYPL/digpres-policies) mustbe used.
  * In addition to the naming requirements listed on the linked hard drive specifications, the hard drive ID and volume name must be exactly 10-characters in length (i.e. NYPL000001 or NYPL_12345).
  * Alternate delivery methods may be explored during term of the agreement.

### Delivery schedule
  * Each volume delivered (either FTP directory or external hard drive) must only contain assets for a single purchase order.
  * Shipment of progress hard drives at regular intervals throughout the Purchase Order timeline is required. An agreed-upon schedule must facilitate ongoing NYPL quality control invoice approval by NYPL staff (rather than a single or small number of large-volume deliveries).
    * Delays in delivery of digital assets will result in extension of allotted NYPL quality control and invoice approval time.
    * Example schedule: 4 hard drives in a single shipment, every 4 weeks.
  * NYPL must approve the method of shipment for the hard drives.

### Pilot delivery
  * Before general production begins on a project, a shipment of "pilot" digital assets must be delivered as follows via FTP:
  * FTP login information must be provided via email to NYPL project managers at the onset of a given project.
  * 5 completed Bags each of audio, video, and film assets (15 bags total maximum)
  * Pilot shipment via FTP must be packaged within a directory that is given a shipment identification number.
  * Once pilot is approved, the FTP transfer may be considered a delivery, and the FTP transfer must be listed on the associated invoice by its identifying shipment ID (NYPL will identify this shipment using the name of the directory as given by the vendor on their FTP client).
  * Once pilot assets are retrieved via FTP they will be reviewed in a timely manner by NYPL. Approved assets will be kept by NYPL and treated as progress deliverables (as the first shipment of a given project).

<a name="quality-assurance-and-quality-control"></a>
## Quality Assurance and Quality Control

Great care must be used in the handling of original materials and comply with the standards and best practices established by the International Association of Sound and Audiovisual Archives (IASA). A thorough visual inspection must be completed before playback.  

A reformatting signal path must be established through the selection, installation, and calibration of equipment designed to ensure optimal signal transfer.

If any physical problems are detected, either during inspection or playback, contact NYPL with a proposed treatment plan before proceeding.  

### Capture Issues
NYPL recognizes that some media may pose challenges to capture or may not be able to be captured due to extremely poor condition or other circumstances.
    * If media exhibit audiovisual artifacts inherent to their source formats or conditions that impact the quality of transfer, but do not prevent a full capture, such artifacts must be described in the metadata signal notes.
    * If an object is not captured, the object must be listed in the required ‘did not capture’ (DNC) report, described in the documentation section of this RFP:
      * DNC report must adhere to the provided template: (https://github.com/NYPL/ami-handling/blob/master/templates/2020_000_example1_didnotcapture_yyyymmdd.xlsx)
      * **Capture Issue Category**: Issues that result in an an object not being captured must be described in the DNC report using the following categories, with additional notes provided as needed. **If additional categories are required, NYPL must approve before they are used**:
          * playback issue
          * condition issue
          * duplicate
          * blank media
          * unsupported AMI format
          * unopened commercial media
      * **Capture Issue Notes**: Notes must be added to provide supplemental information about the category issue selected. For example, if the category is “unsupported AMI format”, the notes must describe the format that is not supported and why; if the category is “condition issue”, the notes must indicate what treatments were attempted and failed to facilitate capture.

### Vendor Quality Assurance and Control
Quality control must be performed for all digital assets, prior to delivery, including preservation masters, derivatives, and metadata. The quality control must include, at minimum:
  1. a confirmation that all required files are present and are named correctly;
  2. confirmation of conformance to media file technical specifications;
  3. confirmation of BagIt specification conformance;
  4. a comparison of each file’s technical metadata to its actual technical specifications;
  5. validation of JSON metadata against NYPL’s JSON schema;
  6. a playback inspection of each file covering the beginning, middle, and end of the file; and
  7. confirmation that the delivery hard drive and subdirectories are formatted and structured according to NYPL specifications.

### NYPL Quality Control

Routine process
  * A quality control process, similar to what is prescribed for the vendor, will be conducted by NYPL within 30 days of receiving each hard drive.
  * If any errors are discovered after delivery to NYPL, by the vendor, NYPL must be informed as soon as possible.
  * **Delays or interruptions may require extending the 30-day QC window. affecting the initial scheduled deliveries and invoice approvals.**

Rework following QC failures
  * If any errors are discovered by NYPL during quality control, NYPL will communicate those errors to the vendor, and any necessary rework must be performed by the vendor and digital assets re-delivered at no additional charge.
  * Small volumes of rework (i.e. up to 10 bags), may be re-delivered via FTP if infrastructure allows.
  * **Extensive rework or redelivery of large volumes of Bags, that exceeds the 30 day QC timeframe will be subject to a new 30-day cycle upon receipt by NYPL.**

<a name="environment-and-security"></a>
## Environment and security

### Physical environment
Physical assets must be stored in an environment that is free of food, water, pests, contaminants, sunlight, and strong magnetic fields. Temperature in the storage area must be between 45-65ºF, with a relative humidity of 30-50%.

### Physical security
Physical assets are considered NYPL special collections. The vendor’s staff and site security methods, described in an AAM General Facilities Report, must meet NYPL approval.

### Digital security

General security and restrictions
  * Digital assets are considered NYPL special collections and may not be used without express NYPL approval.
  * The security methods used for the vendor’s digital storage system must meet NYPL approval.
  * Network based transfers must use encryption in-flight and, if a third-party intermediate storage provider is required, encryption at-rest.

Project Files
  * All media files, checksums, and metadata must be maintained for 60 days following NYPL’s quality control approval of all hard drives within a purchase order.
  * Immediately following this period, confirmation of secure deletion of NYPL digital assets from the any and all storage locations must be provided.

<a name="shipment-of-physical-media"></a>
## Shipment of Physical Media

### General logistics
  * NYPL shall approve all vehicles and plans for shipping.
  * Shipment of original physical media both to and from the vendor shall typically be arranged by NYPL, using a shipper selected by NYPL.

### Project assets
  * Return of the original media shall occur following successful quality control of the final digital assets covered by purchase order.
  * It is the vendors responsibility to return the physical media to NYPL per the set schedule in total. If the vendor omits physical media from the scheduled shipment, the vendor shall be responsible for return shipping to NYPL, using a shipping company and method approved by NYPL in writing.
  * Each shipment must have a packing list that lists the barcode and Box ID of each box included in the shipment. This packing list may be delivered electronically in the format of a searchable PDF document.

<a name="treatment,-handling,-and-rehousing-of-physical-media"></a>
## Treatment, Handling, and Rehousing of Physical Media

### General guidelines
  * Any treatment action must not result in loss of content.
  * All costs for supplies and rehousing labor should be included with the cost proposal, as described in the Vendor’s fee schedule.
  * Replace original housings in these cases:
      * Housing is no longer structurally sound and may compound media damage
      * Housing is contaminated with mold, pest droppings, etc.
      * Housing for 3- or 5-inch audio reels have been replaced with 7-inch reels
  * Discard original housings if replaced and meet these conditions:
      * Housing does not contain bibliographic content.
      * Housing is contaminated with mold, pest droppings, etc.
  * Unless discarded (see discard criteria), all original materials, including tapes, boxes, and reels will be returned to NYPL at the conclusion of the project.
  * New housings must be clearly labeled with the original primary id, written in indelible archival marker.
  * If any original media has been rehoused, all components (original plus new housing) shall be packed together in the original container. If some components no longer fit as a result of rehousing, additional containers may be used.
      * Overflow components must be grouped by original container (ensure that original plus new housings remain together).
      * Overflow container must be clearly labelled with the original objects’ Box ID (example: “MUS 1569”).
      * Original housings must be clearly associated with the rehoused materials.

### Treatment and rehousing: Film media
#### Film handling
  * Films on cores and in archival cans must be stored flat, horizontally.
  * Films in shipping containers and on shipping reels may be stored vertically until rehoused to archival cans and cores to prevent damage prior to rehousing.
  * Films should not be transported via sprockets through any equipment unless for syncing purposes through synchronizers. This should apply to all phases of film work, including winding, inspection, cleaning, scanning. Record footage count through scanning as opposed to synchronizer.

### Film cleaning
  * Prior to digitization, if condition of the film allows for cleaning, films shall be cleaned with a solvent approved by NYPL, preferably Perchloroethylene.
  * Precaution must be used when cleaning films with magnetic sound. Magnetic film cleaning chemicals must be discussed with with NYPL.
  * Cleaning solvents must not remove NYPL unique identifiers; otherwise, a method for reapplying identifiers to film leader must be proposed by the vendor.

#### Film repair
  * Repair deteriorated or broken splices and perforations as needed to achieve acceptable image capture.
      * Any repair actions taken must not result in any significant loss of content or annotations beyond what is necessary to achieve capture. Annotations on leader that must be cut off to make a repair must be included in the JSON metadata.
  * Chemical treatment for deshrinking or rehumidification of shrunken, brittle and/or curling film must be approved with NYPL prior to treatment.

#### Film rehousing
  * Cans and cores: NYPL anticipates that a majority of film objects will be rehoused to archival cores and containers prior to vendor work, but some objects may not be due to their condition. Only objects which have not been rehoused by NYPL may be rehoused.
    * If needed, non-archival containers, shipping reels, and cores must be replaced with archival containers, cores, and/or reels.
        * must comply with the Photographic Activity Test (PAT, ISO18916)
        * must be approved by NYPL
  * Leader: Most film objects will have 20 feet of new leader pre-attached (10 feet at head, 10 feet at tail), labeled with NYPL unique identifiers.
        * If leader must be added to an object, label the head and tail leader with the objects NYPL unique identifier.

### Treatment and rehousing: Video media
#### Video handling
  * Record tabs, if present, must be removed prior to digitization.
#### Video cleaning & baking
  * If professional-grade cleaning machines exist for a particular video format, they must be used, and the action noted in metadata digitization process notes. Cleaning machines should also undergo regular servicing to ensure that tapes will not be damaged during the cleaning process.
  * Video formats that regularly fall victim to Sticky-Shed Syndrome, or any other form of binder hydrolysis, should be baked to achieve optimal reformatting. NYPL is open to local baking customs, though these procedures must be communicated in a detailed manner as part of the response to this RFP.
#### Video repair and rehousing
  * Treatments such as re-shelling or rehousing should be performed, when needed, by skilled technicians to achieve optimal reformatting.

### Treatment and rehousing: Audio media
#### Audio reel and cassette rehousing:Reels and Cassettes
Slotless hubs are preferred, dependent on funds approval by NYPL. If slotless hubs are not commercially available, reuse the original reel and wind one-eighth inch of leader tape around the hub to minimize the effect of the slot.
  * Tape on 3-inch and 5-inch reels:
      * Wind onto new 7-inch reels with slotless hubs.
      * Retain original housing unless it meets housing discard criteria.
  * Tape on 7-inch reels with slotted hubs:
      * Wind onto new 7-inch reels with slotless hubs.  
      * Retain and re-use original housing unless it meets housing discard criteria.
  * Tape on 10.5-inch reels with slotted hubs:
      * Wind onto new 10.5-inch reels with slotless hubs.  If 10.5-inch slotless reels are not commercially available, reuse the original reel and wind 1/8 inch of leader tape around the hub to minimize the effect of the slot on the magnetic tape.
      * Retain and re-use original housing unless it meets housing discard criteria.
      * Reels should be re-boxed if the original box is damaging to the tape.
      * If original boxes are causing damage, or if the tape has been re-wound onto a larger reel, original boxes may be replaced with new 2-piece boxes should be constructed of either white paper-board or unbuffered Ph-neutral lignen-free board. Do not substitute polypropylene or other plastic cases unless specifically requested by NYPL.
  * Cassettes:
      * Replace broken shells and cases with new archival shells and cases, as approved by NYPL.

### Treatment and rehousing: Grooved Disc
#### Grooved Disc identification and rehousing
  * Glass discs have a piece of red tape wrapped around the edge.
    * **Blue tape below the red tape indicates  that the disc is either cracked, chipped, or broken, and should be handled with the utmost of care.**
    * All discs must be rehoused into acid-free and lignin-free buffered paper sleeves approved by NYPL.
    * Barcodes must be duplicated and affixed to the upper-left hand corner of the new sleeve.
    * Any IDs should be copied from the old sleeve to the new one in the upper right hand corner
    * All original materials (including old sleeves) must be returned to NYPL at the conclusion of the project.

### Grooved Disc cleaning
Discs must be cleaned according to procedures appropriate for their type, detailed below.  
  * **Cleaning and rehousing of shellac, shellac-vinyl compound, and vinyl discs:**
      * Cleaning and drying must be carried out with a disc-cleaning machine suitable for archival discs.
      * Clean each disc with a solution of distilled water and Photoflo 200 or 600, The Disc Doctor’s “Miracle Cleaner”, or comparable approved product.
  * **Cleaning and rehousing details for glass and aluminum based discs:**
      * Discs that appear to be relatively clean and in good condition may be cleaned using an archival disc-cleaning machine.
      * Glass and Aluminum based discs which exhibit “Palmitic Acid Syndrome” must be hand-cleaned.
      * Aluminum discs: Oxidation may be gently wiped with mineral or castor oil and a lint-free cloth, prior to gentle hand-washing
      * Glass discs: Oxidation may be cleaned with a solution of non-scented detergent and PhotoFlo (or comparable product approved by NYPL)
      * Hand-wash with a solution of non-scented liquid soap and PhotoFlo or similar product; rinse with lukewarm water; repeat as needed on both sides; vacuum and dry discs as normal.

#### Cylinder cleaning
  * No wet cleaning of cylinders. Only soft brushes are to be used for cleaning.

#### Cylinder rehousing
  * All cylinders should be rehoused into buffered board boxes approved by NYPL. The recommended product is the Wax Cylinder Storage Boxes designed under the guidance of the Northeast Document Conservation Center from University Products (#612-0364 for 4” cylinders, #612-0366 for 6” cylinders).
  * All associated original packaging, papers and ephemera should be included in the separate compartment in each box.
  * Consult IASA-TC 04, 2nd edition, Chapter 5 for best practices regarding cylinder handling, playback, and rehousing.

<a name="specifications-for-digital-assets"></a>
## Specifications For Digital assets

Specifications may be modified over time to reflect changes in best practices or NYPL’s digital infrastructure, or to reflect previously unspecified media or conditions.

The following sections are broken into format groups to define the file deliverables for different media types and format variations.

### FILM MEDIA
#### Film Groups 1 and 2: Motion Picture Film, Silent / Sound
**_Deliverables_**
For each original recording, the following shall be produced:
  * One preservation master file*
  * One mezzanine file*
  * One service copy file*
  * One metadata file per media file

If the object has audio content (i.e. composite sound print), audio must be synchronized and embedded in all final deliverables.

**_Capture tools_**
  * Film must be digitized and captured as DPX, then transcoded with any synchronous Broadcast Wave files to FFV1/FLAC/Matroska using RAWcooked (https://mediaarea.net/RAWcooked)

**_Preservation master file specifications: Film groups 1 & 2: Motion picture film, silent / sound_**

| Attribute | Specification |
| ---- | ---- | ---- | ---- |
| Source format | 35mm | 16mm | 8mm / Super 8mm / Double 8mm |
| Video bit depth | 16 bit | 10 bit |
| Resolution | 4K optical side overscan | 2K optical side overscan |
| Video codec | FFv1 version 3 from DPX |
| File wrapper | Matroska (.mkv) from DPX |
| Frame size | 4096x3112 | 2048x1556 |
| Frame rate | (Same as source. If not described, please determine on viewing and describe in metadata signal) |
| Pixel aspect ratio | 1.000 |
| Audio bit depth* | 24 bit |
| Audio sampling rate* | 96,000 Hz |
| Audio codec/data encoding* | FLAC from PCM/WAV |
| Audio channels* | Same as source object |
| Color space | Linear RGB | Color primaries | BT.709 |
| Transfer characteristics | Printing Density |
| Notes | Transcoded to FFV1/MKV from DPX using RAWCooked |

#### _Mezzanine file specifications: Film group 1 & 2 (Motion picture film, silent / sound)_

| Attribute | Specification |
| --- | ------ |
| Source format | 35mm | 16mm | 8mm / Super 8mm / Double 8mm |
| --- | ---| --- | --- |
| Bit depth | 10 bit |
| Resolution | 1920 x 1080 |
| Display aspect ratio | 16:9 pillarboxed / letter boxed as needed |
| Video codec | ProResHQ |
| File wrapper | Quicktime |
| Frame size | 1920 x 1080 |
| Frame rate | (Same as preservation master) |
| Broadcast standard | NTSC |
| Scan type | Progressive |
| Pixel aspect ration | 1.000 |
| Audio data encoding* | PCM |
| Audio bit rate* | 2304 kbps |
| Audio bit depth* | 24 bit |
| Audio sampling* rate* | 48,000 Hz |
| Audio channels* | same as Preservation Master* |
| Color space | 4:2:2 |
| Image corrections | Color corrected for dye fading,
Cropped to picture - no frame-lines or sound track visible, Non-anamorphic |

####_Service copy file specifications: Film group 1 & 2 (Motion picture film, silent / sound)_

| Attribute | Specification |
| --- | ------ |
| Source format | 35mm | 16mm | 8mm / Super 8mm / Double 8mm |
| --- | ---| --- | --- |
| Bit depth | 8 bit |
| Resolution | 720 x 486 |
| Display aspect ratio | 4:3 letterboxed as needed |
| Video codec | H264 |
| File wrapper | MPEG-4 (.mp4) |
| Color space | 4:2:2 |
| Frame size | 720 x 486 |
| Frame rate | (Same as preservation master) |
| Broadcast standard | NTSC |
| Scan type | Progressive |
| Pixel aspect ratio | 1.000 |
| Audio codec | AAC |
| Audio bit rate | 320 kbs |
| Audio sampling rate | 48,000 Hz |
| Audio channels | same as Mezzanine* |
| Image | Color corrected for dye fading |
| corrections | Cropped to picture - no frame-lines or sound track visible, Non-anamorphic |

### Film Group 3: Audio film

#### _Preservation master file specifications: Film group 3 (Audio film)_

| Attribute | Specification |
| --- | ------ |
| Source format | 35mm | 16mm | 8mm / Super 8mm / Double 8mm |
| --- | ---| --- | --- |
| Audio data encoding | Free Lossless Audio Encoding (FLAC) |
| Wrapper | FLAC (.flac) |
| Bit depth | 24 bit |
| Sampling rate | 96,000 Hz |
| Number of audio channels | (same as source) |
| Other characteristics | If there are tones / sync marks present, they must be captured or resolved and described in metadata signal notes. |
| BEXT metadata | If possible, BEXT metadata must be embedded as per specifications for audio deliverables |

#### _Edit master file specifications: Film group 3 (Audio film)_

| Attribute | Specification |
| --- | ------ |
| Source format | 35mm | 16mm | 8mm / Super 8mm / Double 8mm |
| --- | ---| --- | --- |
| Audio data encoding | Flac |
| Wrapper | Flac |
| Bit depth | equal to preservation master |
| Sampling rate | equal to preservation master |
| Number of audio channels | equal to preservation master |
| Other characteristics | If there are tones / sync marks present, they must be captured and described in metadata signal notes |
| BEXT metadata | BEXT metadata must be embedded as per specifications for audio deliverables |

### Film Group 4: Filmstrips
NYPL will review recommendations for digitization of filmstrips (and accompanying audio media, where applicable) before defining a specification. Requests for recommendations regarding these objects have been included in the Business Questions section.


### VIDEO MEDIA

#### _Deliverables_
For each original recording, the following shall be produced:
  * One preservation master file
      * If captions are present in source, one closed captions sidecar file
  * One service copy file
  * One metadata file per media file
  * Image files as described

#### _Capture tools_
Preservation master video files must be generated by professional-grade capture devices and software, with either direct capture to FFV1/FLAC/MKV, or transcoding from V210/PCM/MOV. Specific FFmpeg transcoding recipes will be provided by NYPL to ensure consistency.

### Preservation master files, all groups
  * Characteristics intrinsic to the broadcast standard of the source material, including frame rate, pixel aspect ratio, interlacing, resolution, and recording standard (NTSC, PAL, SECAM, etc.) should be preserved.
  * Signal extraction must be optimal, and carried out using the equipment and accessories that are appropriate for the original format characteristics.
  * The most direct and clean signal path must be used at all times from source to destination. There may be no devices inserted in the signal path that are not being used. If there are multiple destination formats being used in the transfer the signal path must be routed in parallel. No daisy-chaining of devices may occur.
  * The highest quality signal format (composite, S-Video, Component, SDI, etc.) available for the source media type must be used throughout the entirety of the signal path from source through destination. Exceptions to this must be explained and requested prior to performing the transfer.
  * Luminance, black, and color levels should be adjusted to existing color bars if they are present on tape and look accurate. If color bars are not present or are clearly inaccurate, preview each tape in order to adjust levels according to the content of the tape using known references (such as blue sky, known blacks and whites, flesh tone, etc.). Luma should be adjusted to fall within broadcast range (100 IRE max) and must not exceed 110 IRE.
  * The transfer should capture all content recorded on the original object, including any bars and tone, slates, or other material coming before the start of the recorded program.
  * The recording should run until the end of the recorded content (picture and sound).  If this endpoint cannot be unambiguously determined, the recording should run until the end of the original object.
  * If present on the source tape, closed captions must be captured.

### Video preservation master sidecar files
#### Closed captions
      * f captions are present in source object, an .scc sidecar file must be created and accompany the preservation master file (closed captioning must be embedded in service copies. See service copy specifications).
          * Format: Scenarist Closed Caption File (.scc)
          * Naming Convention: division_PrimaryID_v01_pm.scc
      * Closed captions specifications may change in the future to accommodate updates to standards or NYPL infrastructure needs.

### QCTools Reports
      * Each video preservation master file should receive a corresponding QCTools report, which will be included in the PreservationMasters Bagged directory as a sidecar file.
          * Format: QCTools Report (gzipped XML) (https://www.bavc.org/preserve-media/preservation-tools)
          * Naming Convention: division_PrimaryID_v01_pm.mkv.qctools.xml.gz

**_Preservation master file specifications:_**
**_video group 1: analog and digital cassettes, analog open reel_**

| Attribute | Specification |
| ---- | ------ |
| Video codec | FFv1 version 3 |
| Data compression | Lossless, Intra-frame (GOP-1) only |
| Chroma subsampling | 4:2:2 YUV |
| Bit depth | 10-bit |
| File wrapper | Matroska (.mkv) |
| Frame rate | (Same as original media) |
| Frame size | (Same as original media) |
| Broadcast standard | (Same as original media) |
| Pixel aspect ratio | D1 NTSC (.91) or PAL (1.09) |
| Slices | 24 |
| Slicecrc | 1 |
| Audio format | FLAC |
| Audio bit depth | 24-bit |
| Audio sampling rate | 48 kHz |
| Audio channels | (Same as original media, see guidelines for silent channels) |

### Silent audio channels
  * If a channel exists and is silent, the channel should be captured and a note should be included in the JSON file that the indicates that the tape and the channels delivered on preservation master file are silent. If a channel is non-existent, then it won't be captured. For example:
  * If soundField="ch.1:mono, ch.2: none" rather than soundField= "mono", then the second channel exists, and source.audioRecording.numberOfAudioChannels = 2 (and the preservation master file delivered will contain 2 channels of audio, one of which is silent).
  * Two silent channels If detected as actual channels / i.e. recorded with "black" vs. not recorded), both channels should be captured and delivered with the preservation master, and a signalNote should be included that the tape is silent.

### Timecode
  * Two forms of legacy/source timecode should be retained: LTC Timecode, recorded on an audio channel, should be captured as an audio stream in the resulting preservation master file; VITC timecode, if present, should be captured through the use of appropriate playback devices and a carefully routed SDI signal chain.

  **_Preservation master file specifications: video group 2: DV (digital video) cassettes_**

  NYPL prefers native capture of DV content, with the understanding that errors and varying conditions may require alternative approaches to signal capture. Below are NYPL primary specifications, followed by specifications for cases where the native DV capture with .dv wrapper is problematic due to problems with a given object.

| Attribute | Specification | Notes |
| ---- | ---- | ---- |
| Video codec | (Same as source) | See note |
| File wrapper | DV (.dv) | See note |
| Other characteristics | (Same as source) | If it is necessary to capture DV or HDV tapes via SDI (i.e. as V210/MOV), due to problematic tapes, deliverables must be transcoded and rewrapped as “.mkv”. |

**_Preservation master file specifications: video group 3: optical discs_**

| Attribute | Specification |
| ---- | ------ |
| File system | ISO 9660 / UDF |
| File wrapper | ISO (.iso) |
| Other characteristics | (Same as source) |

**_Service copy file specifications: all video groups_**

| Attribute | Specification |
| ---- | ------ |
| Video codec | H.264/MPEG-4 AVC (ISO/IEC 14496-10 - MPEG4 Part 10, Advanced Video Coding) |
| Video bit rate | 3.5 Mbit/second |
| Chroma subsampling | 4:2:0 YUV |
| Bit depth | 8-bit |
| File wrapper | MP4 |
| Frame rate | (Same as preservation master) |
| Frame size | (Same as preservation master) |
| Broadcast standard | (Same as original media) |
| Pixel aspect ratio | (Same as preservation master, see below for Anamorphic video) |
| Audio codec | AAC |
| Audio bit rate | 320 kbps |
| Audio sampling rate | 48 kHz |
| Audio channels | 2 (see examples) |
| Closed captions* | CEA-608  (*if applicable) |

#### _Anamorphic video_
  * For service copies created from Anamorphic preservation masters, treat source as D1/DV NTSC or PAL Widescreen to produce a 16 x 9 service copy without padding. Pixel aspect ratio should be 1.21 (NTSC) / 1.46 (PAL).

#### _Complex audio configurations_
  * 4 audio channels on source:
      * If a source tape has 4 audio channels of identical content (i.e. 4 mics in a single room recording the same content), the 4 channels captured in the preservation master should be mixed down to 2 for the service copy.
      * If each audio channel contains different content, consult with NYPL for how to proceed.
          * 2-channel Spanish / English language audio: If one channel contains Spanish dialogue and the other channel contains English dialogue, the audio content of the preservation master and the service copy must be identical.
      * Audible content in only one channel:
          * If there is only audible content in a single channel of any number of channels in a source tape and preservation master, the channel containing audible content should be mapped for production of a 2-channel service copy to provide a better user experience.

#### _Timecode_
      * Audible LTC Timecode should be eliminated, and “normal” content should be duplicated onto the second channel.

#### _Trimming of Heads and Tails_
      * Color bars must not be trimmed.
      * Long tails of black / “snow” / unrecorded content may be trimmed after confirmation that there is no visible or audible recorded content.
      * Trimming must not result in an abrupt end of visible or audible content.

### AUDIO MEDIA

**_Deliberables_**
For each collection object, the following shall be produced:
  * One or more preservation master file(s)
  * One edit master file per preservation master
  * One metadata file per media file
  * For optical audio only, one CUE file per preservation master file
  * Image files as described

**_Capture tools_**
Preservation master and edit master files must be captured/encoded as Broadcast Wave Format (BWF), with embedded BEXT metadata (see “Embedded Metadata” section).

Files that exceed the Broadcast Wave Format 4GB file size limitation should be captured as RF64, with the same embedded metadata values. Post-capture, all Broadcast Wave and RF64 files should be transcoded to the FLAC codec and container, with embedded metadata and original modification times retained through the use of the FLAC Utility (https://xiph.org/flac/download.html) by following the command listed on the FFmprovisr website (https://amiaopensource.github.io/ffmprovisr/#flac-tool). Original capture as Wave64 (.w64) is not acceptable.

Preservation master
  * Technical guidelines: The production of preservation master files will comply with the technical recommendations, practices and strategies outlined by the International Association of Audiovisual Archives
  * Strategic guidelines - IASA-TC 03, version 3: The production of preservation master files will comply with the ethical recommendations, practices and strategies outlined by the International Association of Audiovisual Archives.
  * Optimal signal extraction from analog sources seeks to be complete, and includes the transfer of the “lead-in” and “play-out” portions of a recording.
  * Analog signals will be converted to a digital bitstream by means of an Analog-to-Digital converter which complies with the specifications in FADGI’s Audio Analog-to-Digital Converter Performance Specification and Test Method.
  * No signal processing will be applied to the Analog-to-Digital converter’s digital bitstream, including, but not limited to equalization, level adjustment, dither, noise reduction.

Signal Extraction
  * Signal extraction from analog original audio recordings will comply with the technical recommendations, practices and strategies outlined by the International Association of Audiovisual Archives.
  * Optimal signal extraction for the production of preservation master files should aim to capture the complete dynamic and frequency ranges of the original recording.
  * Signal extraction must be carried out using the equipment and accessories that are appropriate and intended for the original format characteristics.
      * Example: a full-track mono recording on an open reel audio tape must be transferred using a full-track audio head (rather than a stereo head).
      * If this is not possible, provide an explicit proposal for work, subject to NYPL approval.
  * An optimal signal extraction from the original recording will be a flat (unmodified) transfer, free of signal processing, equalization, level adjustment, noise reduction, etc. Exceptions would include:
      * de-emphasis of a recording’s stated pre-emphasis (playback equalization)
      * decoding of a recording’s stated noise-reduction encoding
      * Optimal signal extraction from original sources includes the extraction of the intended signal, along with any unintended signal (such as artifacts and anomalies in the signal associated with the inherent limitations of historic recording technologies).
      * Preservation master files may be one or two-channel (interleaved), and the configuration employed will be determined by the needs of the original recording.
      * Levels may be adjusted ONLY if there is severe distortion or digital clipping from the source, and this adjustment must be noted clearly in the metadata.
      * If a sync tone is present (i.e. Pilottone), tone must be captured or resolved.  
      * For all grooved media, preservation master files must include the “needle-drop” and “needle-lift”.

#### Special circumstances and object-file relationships
    * **Faces:** In general, one preservation master file will be generated for each physically or technically discrete recording area of the original object.
        * For example, each side of an audio cassette or disc will be recorded as a separate preservation master file, identified with a designated Face number.
    * Considerations and circumstances that impact the number of preservation masters generated for each physical object, and/or for each discrete recording area:
        * For an object which is found to have content recorded both forwards and backwards on the same Face, a second Face may be created for the reversed content to be recorded in the proper direction.
        * **Region:** For an object with regions recorded at different speeds or sampling rates, a separate preservation master must be created for each Region (filename_v01f01r01_pm).

        * File overlap:
            * Speed Changes: If multiple preservation masters are created for a single recording due to speed changes, the cut should be made at a logical break in the audible content (if at all possible), and there must be exactly 5 seconds of audible content overlapping between the tail of the first preservation master and the head of the following PM so that the regions may be recombined in the future if necessary.
            * Sampling Rate Changes: If a digital source object has been recorded at multiple sampling rates, a separate preservation master must be created for each region. _These regions do not need to overlap, but please include a note listing the timestamp on the source object where each region begins._

**_Embedded metadata_**
BEXT metadata must be embedded in each audio file upon capturing to WAV. See Metadata section for details.

**_Preservation master file specifications: audio group 1: analog magnetic_**

  | **Preservation master file specification: audio group 1** |
  | Attribute | Specification |
  | ---- | ----- |
  |Audio data encoding | Free Lossless Audio Codec (FLAC) |
  | File wrapper | FLAC (.flac) |
  |Bit depth | 24 |
  | Sampling rate | 96,000 Hz |
  | Number of audio channels | (same as source) |

**_Preservation master file specifications: audio group 2: digital magnetic_**

  | **Preservation master file specification: audio group 2** |
  | Attribute | Specification |
  | ---- | ----- |
  | Audio codec | Free Lossless Audio Codec |
  | File wrapper | FLAC (.flac) |
  | Bit depth | (same as source) |
  | Sampling rate | (same as source) |
  | Number of audio channels | (same as source) |

**_Preservation master file specifications: audio group 3: optical disc_**

**CUE text files**

In congress with capturing a Broadcast Wave file prior to transcoding to .flac, a CUE file must be generated. The CUE file must:
    * Follow the same naming convention as the WAV file, but instead with a ".cue" extension. Example: "myh_123456_v01f01_pm.cue"
    * Be referenced in the JSON file under the technical.cueFile field, by its complete filename
    * Be nested within the Preservation Masters directory, accompanying the Preservation Master WAV file (the Edit master must not have a .cue file):
        * PrimaryID
            * data
                * PreservationMasters
                    * division_PrimaryID_v01f01.flac
                    * division_PrimaryID_v01f01.cue
                    * division_PrimaryID_v01f02.flac
                    * division_PrimaryID_v01f02.cue
                  * EditMasters
                    * division_PrimaryID_v01f01.flac
                    * division_PrimaryID_v01f02.flac

  **_Preservation master file specifications: audio group 3: optical disc_**

  | **Preservation master file specification: audio group 3** |
  | Attribute | Specification |
  | ---- | ----- |
  |Audio codec | Free Lossless Audio Codec (FLAC) |
  | File wrapper | FLAC (.flac) |
  | Bit depth | (same as source) |
  | Sampling rate | (same as source) |
  | Number of audio channels | 2 (left + right discrete) |
  | Other characteristics | CDs should be captured as a single file |

  **_Preservation master file specifications: audio group 4: grooved disc_**

  | **Preservation master file specification: audio group 4** |
  | Attribute | Specification |
  | ---- | ----- |
  | Audio data encoding | Free Lossless Audio Codec (FLAC) |
  | File wrapper | FLAC (.flac) |
  | Bit depth | 24 |
  | Sampling rate | 96,000 Hz |
  | Number of audio channels | 2 (left + right discrete) |

  Reproduction details  
      * Playback EQ curves for all discs should be utilized.
            * If a disc’s playback curve is not known or stated on the label, the phono EQ should be set to RIAA (for microgrooves 1948-present) or a “default” curve of 400Hz turnover and -12dB @ 10kHz rolloff (for transcription discs). **All EQ curves should be noted in the metadata digitization process notes.**
      * Equipment
            * NYPL requires either the Time-Step line of phono EQs, or the KAB Souvenir Equalizer. Owl EQs are not acceptable due to the age, added noise floor, and lack of versatility needed for our collections. **Other phono EQs may be submitted for approval.**
      * All discs should be transferred with the cartridge switched to "lateral" unless otherwise indicated on the label.
      * A full complement of stylus shapes and sizes should be on-hand at the vendor transfer station, and **he best sounding size/shape stylus used for transfer should be noted in the metadata digitization process notes.**
            * Modern LP styli must **not** be used to transfer shellac, shellac-vinyl compound, or early vinyl discs.
      * Tone arm requirements:
            * Arm must be long enough to comfortably reach the outer grooves.
            * Arm should be vertically adjustable to accommodate the various thicknesses of pressings.
            * During playback, the angle of the tonearm from front to back should be perfectly parallel in relationship to the disc while it is playing.
      * While playing a face, for any speed changes or instances where the stylus has to be repositioned to continue playing, a separate preservation master must be created for each Region.
      * If the stylus skips, attempt to correct and retransfer the area before and after, add this note into the metadata along with time stamp.
            * If unable to perform these functions, set aside and return to NYPL.

**_Preservation master file specifications: audio group 5: grooved cylinder_**

  | **Preservation master file specification: audio group 5** |
  | Attribute | Specification |
  | ---- | ----- |
  | Audio data encoding | Free Lossless Audio Codec (FLAC) |
  | File wrapper | FLAC (.flac) |
  | Bit depth | 24 |
  | Sampling rate | 96,000 Hz |
  | Number of audio channels | 2 (left + right discrete) |

Reproduction Details
    * No playback EQ curves for cylinder preservation masters. Must be transferred “flat”, with cartridge switched to “vertical”.  
    * At the start of the preservation master file, a 1kHz tone at operating level (-16 dBFS) for 30 seconds should be added.
    * Equipment must be approved by NYPL in writing. NYPL prefers use of Archeophone, Endpoint, or Levin CPS1 cylinder reproducers. Period equipment is not acceptable for use due to age and inconsistency of these machines and the greater potential for damage to the Archival Objects.
    * An appropriate assortment of stylus sizes and shapes for cylinders should be on-hand at the vendor transfer station and **the best sounding size/shape stylus used for transfer should be noted in the phonoCartridge metadata fields.**
    * Player setup and playback practices should adhere to best practices.
    * Careful determination of the groove pitch (Threads Per Inch or TPI), speed (with correction if needed), and cylinder material (brown wax, Gold Moulded, etc.) need to be determined BEFORE transfer and noted in metadata digitization process notes.

**_Edit master file specifications: all audio groups_**

  | **Preservation master file specification: all groups** |
  | Attribute | Specification |
  | ---- | ----- |
  | Audio data encoding | Free Lossless Audio Codec (FLAC) |
  | File wrapper | FLAC (.flac) |
  | Bit depth | equal to preservation master |
  | Sampling rate | equal to preservation master |
  | Number of audio channels | Mono, 1; Stereo, 2 |

Head and Tail Edits (Trimming)
    * The “needle-drop” and “needle-lift” present in preservation master files must be edited out of the edit master files.
    * Unrecorded portions of the collection object captured in the preservation master shall be eliminated.
    * Test tones and any equipment noise at the start and/or end of audible content (such as equipment on/off “clicks” or a stylus in the groove) should be trimmed. Trimming should not result in an abrupt start and/or end of audible content.
    * Elimination of the 5-second overlap included on any Preservation Masters that have been split out into multiple files for separate regions / streams / etc.

Level adjustment  
    * When balance and/or overall level are insufficient a peak level adjustment of max. -2db may be implemented as necessary.
Channel Adjustment
    * Ensuring that "mono" is true mono

### DATA MEDIA  
**_Deliverables_**
For each collection object, the following shall be produced:
  * One or more preservation master file(s)
  * One metadata file per media file
  * Image files as described

**_Capture tools_**
Preservation masters must be captured/encoded as ISO9660 Disc Images.

**_Preservation master file specifications: data optical disc_**
Media in Data Group 1 are distinguished from media in Audio Group 3 and Video Group 3 as follows:
  * Data Group 1 uses an ISO 9660 file system to encode data
  * Data Group 1 discs do not contain a top-level directory title “AUDIO_TS” or “VIDEO_TS”

  | **Preservation master file specification: all groups** |
  | Attribute | Specification |
  | ---- | ----- |
  |File system | ISO 9660 / UDF |
  | File wrapper | ISO (.iso) |
  | Other characteristics | (Same as source) |
