---
title: Data
layout: default
---

[[Overview and index]](index.html)


# Data
- Data can be obtained by field work, remote sensing, lab work, scraping/mining,
  scanning (such as Optical Character Recognition (OCR)), open source
  repositories, private sharing, and public records requests.
- Data provenence might include the source, experimental design, instruments used
  (including model numbers), sampling techniques, licensing, anonymization, and
  the publishing of various formats (e.g. raw and processed, csv and xlsx).
- Primary sources can either be created by human input or by machine input; but
  a secondary data source such as OCR normally uses software (or human input) to
  create a data source in a more useful or accessible format; the nature of this
  input method points to the first layer of potential errors and mistakes.
- The process of cleaning and validating data should be documented, preferably
  with scripted code (not a GUI such as Excel or OpenRefine); however an
  [OpenRefine](http://openrefine.org/) process can be saved and exported as JSON; the R package [tidyr](http://tidyr.tidyverse.org/) (part of the R package group [tidyverse](http://tidyverse.org/)) is a scripting alternative.
- If any data is excluded, that should be documented (and coded), including the
  the policies and procedures for dealing with outliers, null sets, and error
  messages.
- If the data is split into testing and training sets, the splitting process and
  code should also be included and documented.
- Funding groups, government institutions, academic institutions, and publishers
  may retain rights to the intellectual property in articles, data, and code;
  otherwise the default legal status of data is as a "trade secret" but the
  public release of data ends most claims to trade secret rights; see
  [Sharing Research Data and Intellectual Property Law: A Primer](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4551669/) in PLOS Biology (2015) by William Carroll and
  [Who Owns Scientific Data? The Impact of Intellectual Property Rights on the Scientific Publication Chain](http://www.d.umn.edu/~pschoff/documents/ElliotR05WhoOwnsScientificDatapdf.pdf) (2005) by Roger Elliot, University of Oxford and [Enabling Reproducible Research: Licensing Scientific Innovation](https://web.stanford.edu/~vcs/papers/ijclp-STODDEN-2009.pdf) in the International Journal of Communications Law & Policy (2009) by Victoria Stodden.
- Researchers may choose an open data license; both [Creative Commons](https://creativecommons.org/) and
    [Open Data Commons](http://opendatacommons.org/) provide options.
- Ideally, a long term plan for storing data includes:
  - A Digital Object-Identifier [(DOI)](https://www.doi.org/), keeping the associated URL up to date;
  - Hosting the data in an open repository such as [Github](https://github.com/); see [Repositories](repositories.html).
  - Keeping a physical copy in private possession and another in a library or archive;
  - Consideration of the fragile nature of long term digital storage, because nobody
    knows how long digital storage mediums will last (see "Very Long-Term Backup"
    [The Rosetta Project](http://rosettaproject.org/blog/02008/aug/20/very-long-term-backup/)); and [Optical storage: an emerging option in long-term digital preservation](https://link.springer.com/article/10.1007/s12200-014-0442-2)).

## General Resources
- [Ten Simple Rules for the Care and Feeding of Scientific Data](http://www.ploscompbiol.org/article/info:doi/10.1371/journal.pcbi.1003542) in PLOS Computational Biology (2014) by Alyssa Goodman et al.
- [Ten Simple Rules for Experiments' Provenance](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004384) in PLOS Computational Biology (2015) by Toni Kazic.
- [Ten Simple Rules for Creating a Good Data Management Plan](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004525) in PLOS Computational Biology (2015) by William Michener.
- [Ten Simple Rules for Digital Data Storage](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005097) in PLOS Computational Biology (2016) by Edmund Hart et al.
- ["Choosing between data sharing repositories for Engineering"](https//data.library.virginia.edu/files/Choosing-Data-Sharing-Repositories-Engineering Nov 2013.pptx) (2013) by the University of Virginia ([Alternative Link](http://slideplayer.com/slide/8588743/)]) (much more than the title suggests, e.g. intellectual property policies by Universities).
- [Data Provenance--the foundation of data quality](https://www.sei.cmu.edu/measurement/research/upload/Davidson.pdf) (2010) by Peter Buneman (University of Edinburgh) and Susan Davidson (University of Pennsylvannia).
- Manipulative data practices described: ["The Nine Circles of Scientific Hell"](http://pages.ucsd.edu/~cmckenzie/Neuroskeptic2012Perspectives.pdf) in Perspectives on Pyschological Science (2012) by [neuroskeptic](https://blogs.discovermagazine.com/neuroskeptic/).
- Detailed overview of experimental design and the creation of data:
  [Quasi-Experimentation: Design and analysis for field settings](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=TCpyDZMAAAAJ&citation_for_view=TCpyDZMAAAAJ:0EnyYjriUFMC) (1979) by Cook and Campbell.
- [Frictionless Data Project](http://frictionlessdata.io/) creating standards for easier data sharing.

### Data repositories

See [Repositories](repositories.html).
