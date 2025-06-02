# Awesome Digital Preservation [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->

> Carefully curated list of awesome digital preservation resources.

This [Awesome List](https://github.com/sindresorhus/awesome/blob/main/awesome.md) is one a suite of community-owned resources for digital preservation. See [digipres.org](https://www.digipres.org) or [the digipres.org discussion forum](https://github.com/orgs/digipres/discussions) for more information.

Contributions are welcome. Please add links through pull requests, or create an issue to start a discussion. Please refer to [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidance.  And if obsolescence claims something awesome, there's always the [Archive](ARCHIVED.md).

The text of an annual reminder email about these resources is also held here, in [reminder.md](reminder.md). This will be sent around various mailings list once per year, ahead of [World Digital Preservation Day](https://www.dpconline.org/events/world-digital-preservation-day).

<!-- omit in toc -->
## Contents

<!--lint disable double-link-->

- [Get Started](#get-started)
  - [Save Digital Stuff Right Now](#save-digital-stuff-right-now)
  - [Learn About Digital Preservation](#learn-about-digital-preservation)
  - [Find Formats](#find-formats)
  - [Experiment with Tools](#experiment-with-tools)
  - [Engage Stakeholders](#engage-stakeholders)
  - [Become Part Of The Digital Preservation Community](#become-part-of-the-digital-preservation-community)
- [Store Digital Content](#store-digital-content)
- [Create Preservation Metadata](#create-preservation-metadata)
- [Find Test Files](#find-test-files)
  - [Multi-format Corpora](#multi-format-corpora)
  - [Format-specific Corpora](#format-specific-corpora)
  - [Building Corpora](#building-corpora)
  - [Sourcing test files from web archives](#sourcing-test-files-from-web-archives)
  - [Sourcing test files](#sourcing-test-files)
- [Find More Tools](#find-more-tools)
- [Build Workflows](#build-workflows)
- [Improve The Tools](#improve-the-tools)
  - [Improving Identification](#improving-identification)
  - [Improving Characterisation/Metadata Extraction](#improving-characterisationmetadata-extraction)

<!--lint enable double-link-->


## Get Started

### Save Digital Stuff Right Now

Spotted digital data at risk, but don't know who can save it?

- Save web pages via:
    - [Internet Archive Nominations](http://blog.archive.org/2013/10/25/fixing-broken-links/#save_page)
    - [archive.is](http://archive.is/) - Also known as _archive.today_. <!-- markdown-link-check-disable-line --><!-- arhive.is seems to block link checks -->
    - [perma.cc](https://perma.cc/)
    - [webcitation.org](http://webcitation.org/)
    - [UK Web Archive Site Nomination](https://www.webarchive.org.uk/ukwa/info/nominate) - Suggest URLs for the UK Web Archive. _Note that UKWA is offline at present._ <!-- markdown-link-check-disable-line -->
- Alert the [Archive Team](http://archiveteam.org/), and [help them save digital stuff](http://archiveteam.org/index.php?title=Who_We_Are)

### Learn About Digital Preservation

- The [Getting Started chapter of the Digital Preservation Handbook](https://www.dpconline.org/handbook/getting-started) is a great place to start.
- [The Digital Preservation Handbook Glossary](https://www.dpconline.org/handbook/glossary) - Introduces a lot of the core terminology.
- For material that describes the broader issues, you can refer to [Digital Preservation on Wikipedia](https://en.wikipedia.org/wiki/Digital_preservation), and consider contributing to the [Digital Preservation Wikipedia Project](http://en.wikipedia.org/wiki/Wikipedia:WikiProject_Digital_Preservation).
- Build your roadmap, guided by [the NDSA Levels of Digital Preservation](http://ndsa.org/activities/levels-of-digital-preservation/)
- Use the [Digital Preservation Business Case Toolkit](http://wiki.dpconline.org/index.php?title=Digital_Preservation_Business_Case_Toolkit) to help get funding.
- Understanding your costs can help to plan your preservation work more effectively. The [Curation Costs Exchange](http://www.curationexchange.org/) allows you to compare your costing data with that of many other organisations.
- Learn about [Preserving digital Objects with Restricted Resources](http://digitalpowrr.niu.edu/)
- Learn how to [Authenticate, Manage, and Preserve Video](https://archiving.witness.org/) -- WITNESS trains activists to archive and preserve their video so that human rights abuses cannot be denied or forgotten over time.
- Explore and contribute to the [DP Requirements and Solutions wiki](http://wiki.opf-labs.org/display/REQ/Digital+Preservation+and+Data+Curation+Requirements+and+Solutions)
- [Brainscape Digital Preservation Flash Cards](https://www.brainscape.com/p/1FA8-LH-5DKH7) - See <https://github.com/ross-spencer/brainscape-digital-preservation#readme> for more information.

### Find Formats

We need to understand the file formats of the resources we care for, and the software they depend on.

- [Search across format registries](https://digipres.org/formats/)
- Find or add formats to the [File Formats Wiki](http://justsolve.archiveteam.org)
- Understand [file format risks](http://wiki.opf-labs.org/display/TR/OPF+File+Format+Risk+Registry) ([e.g. JP2](http://wiki.opf-labs.org/display/TR/JP2))
- [Game File Format Central (_archived version_)](https://web.archive.org/web/20230314075220/http://wiki.xentax.com/index.php/Game_File_Format_Central) - Community project documenting over 1300 game related file-formats.
- [Just Solve It - File Formats Wiki](http://fileformats.archiveteam.org/wiki/Main_Page) - Community project documenting a wide-variety of file formats.

If you have good examples of digital resources and their risks, please consider adding them to a test corpus.


### Experiment with Tools

<!--lint ignore double-link -->

There are a lot of tools out there (see [the tools section below](#find-more-tools)), but some tools are particularly great for early experimentation. These tools can be used right in your web browser, so you can get started without installing software locally.

#### Remote Services <!-- omit in toc -->

These tools are accessed using your browser, and work by sending a copy of your files to a remote server.

- [Siegfried](http://www.itforarchivists.com/siegfried) - You can use the side bar to upload a file for Siegfried to identify the format.
- [Online TrID File Identifier](https://mark0.net/onlinetrid.html) - A web service that identifies files using [TrID](https://mark0.net/soft-trid-e.html).

#### In-Browser Tools <!-- omit in toc -->

These tools run entirely in your web browser, so no data is sent anywhere.

- [Siegfried JS](https://siegfried-js.glitch.me/) - This runs the Siegfried format identification tool on your files in your browser.
- [CyberChef](https://gchq.github.io/CyberChef/) - The Cyber Swiss Army Knife. Capable of running lots of basic data operations on text or files, including computing things like MD5 or SHA hashes.
- [warc-analyser](https://edsu.github.io/warc-analyzer/) - Proof-of-concept that analyses WARC files in your browser. See <https://github.com/edsu/warc-analyzer> for more information.
- [Demystify Lite](https://ross-spencer.github.io/demystify-lite/) - This runs [Siegfried WASM](https://github.com/richardlehane/siegfried/tree/5e86c0355bcf30bc74e75bc3c4d3ee8a3be35ab8/wasm) on your files in your browser and outputs a [Demystify](https://github.com/exponential-decay/demystify) formatted report profiling your collection and highlighting files that might require specific attention during appraisal, such as duplicates; and through various preservation activities, such as caring for file names encoded using specific character-encodings.

### Engage Stakeholders

- Visual examples of digital preservation challenges, such as graphic corruption, can be incredibly useful in communicating the digital preservation message. That's why we built the Atlas of Digital Damages [Gallery](http://www.flickr.com/groups/2121762@N23/) and [website](http://www.atlasofdigitaldamages.info). Please add your own images of a digital preservation challenge, failed rendering, encoding damage, corrupt data, or visual evidence documenting to the Atlas of Digital Damages.
- Use the [POWRR One Pagers](http://powrr-wiki.lib.niu.edu/index.php/One_Pagers_tailored_to_educate_different_professionals) to educate stakeholders about the issues.
- Working with your IT department (some responses arising from [this question on twitter](https://twitter.com/anjacks0n/status/809343452995522560):
  - Backup versus preservation: ["I had useful discussions about 'for the long-term' and what issues that might throw up as a starting point."](https://twitter.com/CriticalSteph/status/809365764549595136)
  - ["often it comes down to language - avoid the word archiving. means 1 thing to IT & another DP professionals"](https://twitter.com/pnwagner/status/809356219471302656)
  - [Ten IT skills you need to have to work with digital preservation](https://www.dpconline.org/blog/ten-it-skills-you-need) - written by [Dave Thompson](https://twitter.com/d_n_t)
  - ["Am going to go all Bruce Lee 'adjust to the object'. What drives IT? Delivery, efficiency, user needs etc."](https://twitter.com/C_Fryer/status/809547404366192642)


### Become Part Of The Digital Preservation Community

Advance digital preservation by pooling our experience, sharing our stories and finding the answers to the big questions.

- Q&A:
   - [Ask and answer digital preservation questions](http://qanda.digipres.org)
   - We tried to run a Digital Preservation Stack Exchange, but it didn't work out. The [content is available here](http://anjackson.github.io/zombse/)
- Forums
    - Discussion forums and active [blogs](http://dpconline.org/blog) provide the opportunity to share informal advice and war stories, get recommendations and discuss the finer points of digital preservation. By sharing both your intentions for digital preservation work and your results, you can [ensure your work benefits from a wealth of community experience](http://openpreservation.org/blogs/2012-05-17-do-others-share-your-digital-preservation-challenges-and-know-about-best-solutions).
    - Discuss preservation issues on the [Digital Curation](https://groups.google.com/g/digital-curation) forum
    - Share war stories on [OPF](http://openpreservation.org/knowledge/blogs/) blogs
    - Mastodon - Join these federations with a digital preservation or general GLAM focus:
         - <https://digipres.club>
         - <https://glammr.us>
         - <https://ausglam.space>
         - <https://code4lib.social>
    - Twitter - Use these lists to find people to follow:
        - <https://twitter.com/DavidUnderdown9/lists/digipres1>
        - <https://twitter.com/An_Old_Hand/lists/digi-pres-rdm>
        - <https://twitter.com/digipresnews/followers>
        - <https://twitter.com/NKrabben/lists>
    - [r/DataHoarder](https://www.reddit.com/r/DataHoarder/) - "We are digital librarians." <!-- markdown-link-check-disable-line -->
    - [r/Archiveteam](https://www.reddit.com/r/Archiveteam/) - "Archive Team is a loose collective of rogue archivists, programmers, writers and loudmouths dedicated to saving our digital heritage." <!-- markdown-link-check-disable-line -->
    - Join the [Digital POWRR Slack](http://digitalpowrr.niu.edu/slack-off-with-digital-powrr/)
- Face-to-Face communities/support groups:
    - [Digital Cultural Heritage DC](https://www.meetup.com/digital-cultural-heritage-dc/)
    - [Mid Michigan Digital Practitioners](https://midmichdp.wordpress.com/)
    - [XFR Collective: NYC-based media preservation membership organization preserving at-risk and obsolete audiovisual artwork by providing low-cost migration services](https://twitter.com/XFR_collective)
- Collaborations (inc. groups that build things together):
    - [Association of Moving Image Archivists (AMIA) Open Source Committee on GitHub](https://github.com/amiaopensource)
    - [Zenodo Digital Preservation Community](https://zenodo.org/communities/digital-preservation/) - Building a comprehensive bibliography of publications, presentations, instructions and data sets related to digital preservation.
- Models, Standards & Certification:
    - [The Reference Model for an Open Archival Information System (OAIS)](http://www.oais.info/)
    - [CoreTrustSeal](https://www.coretrustseal.org/) - CoreTrustSeal offers to any interested data repository a core level certification based on the Core Trustworthy Data Repositories Requirements. 
- Conferences:
    - [PASIG](http://www.preservationandarchivingsig.org/)
    - [iPres](https://ipres-conference.org/)
- Membership organizations:
    - [DPC](http://dpconline.org/) (International)
    - [OPF](http://openpreservation.org/) (International)
    - [NCDD](http://www.ncdd.nl/) (Netherlands)
    - [NDSA](http://ndsa.org/) (USA)
    - [NESTOR](https://www.langzeitarchivierung.de/) (Germany)


## Store Digital Content

- [A history of storage media](https://codewords.recurse.com/issues/seven/a-history-of-storage-media)
- File system conventions:
  - [BagIt](https://en.wikipedia.org/wiki/BagIt)
      - [BagIt](http://fileformats.archiveteam.org/wiki/BagIt) - BagIt's page on the File Format Wiki.
      - [Unexpected errors in the BagIt area](https://alexwlchan.net/2025/bagit-errors/) - Detailed advice on how to approach testing your Bags.
  - [Oxford Common File Layout (OCFL)](https://ocfl.io/)


## Create Preservation Metadata

- [The PREMIS Data Dictionary for Preservation Metadata](https://www.loc.gov/standards/premis/)
- [Metadata Encoding & Transmission Standard (METS)](http://www.loc.gov/standards/mets/)
- [Portland Common Data Model (PCDM)](https://pcdm.org/)
- [Coalition for Content Provenance and Authenticity (C2PA)](https://c2pa.org/) - A related, emerging industry standard.
    - [WITNESS and the C2PA Harms and Misuse Assessment Process](https://blog.witness.org/2021/12/witness-and-the-c2pa-harms-and-misuse-assessment-process/)
    - [First Camera With CAI Content Credentials Introduced](https://www.carlseibert.com/first-camera-with-cai-content-credentials-introduced/)
    - [Mark the good stuff: Content provenance and the fight against disinformation (BBC)](https://www.bbc.co.uk/rd/blog/2024-03-c2pa-verification-news-journalism-credentials)
    - Some criticism and exploration of the the limitations of the C2PA approach:
        - [C2PA's Butterfly Effect](https://www.hackerfactor.com/blog/index.php?/archives/1010-C2PAs-Butterfly-Effect.html) - Broad context as well as limitations.<!-- markdown-link-check-disable-line --><!-- seems to block link checks -->
        - [IEEE, BBC, and C2PA](https://www.hackerfactor.com/blog/index.php?/archives/1024-IEEE,-BBC,-and-C2PA.html) - Includes detailed analysis of a specific case.<!-- markdown-link-check-disable-line --><!-- seems to block link checks -->

## Find Test Files

To improve our digital preservation tools, we need to be able to test them and evaluate of their performance. Publicly available sample files make this much easier. Tool developers can use them to test their work, discover bugs, and hone their tools ready for others to use. A test corpus can contain real digital objects from a collection, or be created specifically for exhibiting certain characteristics for testing purposes. Real data, particularly with examples of broken, badly formed or corrupted files can be particularly useful.

- See also [Where are the Born-Digital Archives Test Data Sets?](https://blogs.loc.gov/thesignal/2014/03/where-are-the-born-digital-archives-test-data-sets/)

### Multi-format Corpora

- The [OPF Format Corpus](https://github.com/openpreserve/format-corpus)
- The [iPres System Showcase Test Suite](http://www.webarchive.org.uk/datasets/ipres.ds.1/) - Hosted by the UK Web Archive. _Note that UKWA is offline at present._ <!-- markdown-link-check-disable-line -->
- The [Encyclopedia of Graphics File Formats Companion CD-ROM](https://archive.org/details/EncyclopediaOfGraphicsFileFormatsCompanionCd-rom) contains lots of test files for image formats:
    - [EGFF ISO Image](https://archive.org/download/EncyclopediaOfGraphicsFileFormatsCompanionCd-rom/GFF_CD.ISO)
- [EDRM Data Set Files (_archived version_)](https://web.archive.org/web/20150414060529/http://www.edrm.net/projects/dataset/data-set-files)
    - [EDRM File Formats Data Set 1.0.1 (_archived version_)](https://web.archive.org/web/20150414060529/http://www.edrm.net/download/all_projects/data_set/EDRM_Data-Set_File-Formats_1-0.zip)
- [digitalcorpora.org's corpora](http://digitalcorpora.org/corpora/) - including [govdocs1](http://digitalcorpora.org/corpora/govdocs).
- Open Preservation Foundation had a corpora page [(_archived version_)](https://web.archive.org/web/20191231165648/https://openpreservation.org/technology/corpora/).
    - OPF govdocs [here](https://web.archive.org/web/20191231165744/https://openpreservation.org/technology/corpora/govdocs/)
    - OPF also created a [by-format subset of govdocs1](https://web.archive.org/web/20191231202941/https://openpreservation.org/technology/corpora/govdocs-selected/).
- [digicam corpus](https://github.com/thorsted/digicam_corpus) - Contains a corpus of Digital Camera files collected by Tyler Thorsted.
- [The Skeleton Test Suite](https://github.com/exponential-decay/skeleton-test-suite) - Builds test files from PRONOM binary and container signatures. These can be used to test DROID and other (compatible) identification tools.
- [Fine Free File Test Suite](https://fedorahosted.org/file-tests/) - Set up for Fedora testing.
- [JHOVE's test files](http://jhove.cvs.sourceforge.net/viewvc/jhove/jhove/examples/)
- [JHOVE2's test files](https://github.com/opf-labs/jhove2/tree/master/src/test/resources/examples/)
- The [disktype test files](http://disktype.cvs.sourceforge.net/viewvc/disktype/file-system-sampler/)
- The [Metadata Working Group specifications (_archived version_)](https://web.archive.org/web/20180402195758/http://www.metadataworkinggroup.org/specs/) and [embedded image metadata test corpus (_archived version_)](https://web.archive.org/web/20180402200035/http://www.metadataworkinggroup.org/specs/test_files.html)
- [Apache Tika issue about setting up a nightly test corpus](https://issues.apache.org/jira/browse/TIKA-1302) - See also [tika-parsers/src/test/resources/test-documents](http://svn.apache.org/repos/asf/tika/trunk/tika-parsers/src/test/resources/test-documents/)
- [The Chemical MIME Home Page](https://web.archive.org/web/20220321053449/https://www.ch.ic.ac.uk/chemime/)
- [Online-convert.com example files](https://www.online-convert.com/file-type) (use [this link to browse the folder structure](https://example-files.online-convert.com/))
- [RDSS Archivematica Test Data Corpus](https://github.com/artefactual-labs/rdss-archivematica-test-data-corpus) - A collection of research dataset files used for testing Archivematica integration and functionality in the JISC Research Data Shared Service (RDSS).
- [Archivematica Sample Data](https://github.com/artefactual/archivematica-sampledata) - Includes OPF format corpus, as well as other test material.
- [ExifTool test files](https://sourceforge.net/p/exiftool/code/ci/master/tree/t/images/) - Test file folder in the source code directory tree.<!-- markdown-link-check-disable-line --><!-- seems to block link checks -->
- [PREFORMA Ground Truth Classes](https://github.com/preforma/groundtruth) - Instructions how to reproduce validation-failing files for Matroska, FFV1, LPCM, TIFF, and PDF formats.
- ["Small"](https://github.com/mathiasbynens/small) - Collection of "the smallest possible syntactically valid files in different programming/scripting/markup languages."
- [MediaArea-RegressionTestingFiles](https://github.com/MediaArea/MediaArea-RegressionTestingFiles) - Public regression testing fi