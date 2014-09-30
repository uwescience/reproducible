---
title: Guidelines
layout: default
---


# Guidelines for Reproducible and Open Science 

## Moore/Sloan Data Science Environment

Online version: <http://uwescience.github.io/reproducible/guidelines.html>


Our working definition for reproducible research is that a research result can
be replicated by another investigator. Our focus is data science and the
reproducibility of computational studies and/or analysis of digital data.

This note summarizes best practices to facilitate reproducible research in data
science (and computational science more generally). It is expected that all
research conducted with funding from the DSE will be performed in accordance
with these guidelines to the extent possible.

See [Goals](goals.html) for a discussion of the 
goals and benefits of adopting these guidelines. 

## Version control

Use version control for all code and documents describing software, workflow,
data provenance, etc. Get in the habit of doing this for all projects, whether
or not you intend to eventually share it with others.

Git is the recommended version control system. Back up your repositories by
maintaining clones on other computers or in the cloud. Using Github is
recommended since it greatly facilitates collaboration and eventual sharing.
See [Git](git.html) for more details.

## Replicable computations

Use scripts rather than GUIs with data analysis or visualization tools in order
in insure that you can reproduce the results. Keep the scripts under version
control.

When appropriate, use notebook environments as an easy way to capture and
replicate the sequence of instructions (interspersed with documentation and
commentary) that led to a result. Suggested tools include IPython notebooks,
Sage Worksheets, RStudio (all open source), or Mathematica, Maple, Matlab
Publish. See [Notebooks](notebooks.html) for more details.

More generally, document your code so that you can decipher it later and others
can understand what you have done. Use literate programming tools to facilitate
this when possible. Some examples include doxygen, CWEB, Sphinx. See
[Code](code.html) for more details.

When suitable, use workflow management systems to track a series of experiments
performed, versions of code used, data provenance, etc. Suggested tools include
VisTrails, Taverna, Galaxy. See [Workflow](workflow.html) for more details.

## Data and code provenance, sharing and archiving

Data used in publications (and associated metadata) should be available to
readers of the publication - subject of course to privacy requirements or
related issues, but sharing should be the default. Data should be deposited in
archives that are appropriate for the discipline, data size, and the nature of
access. Where possible, seek to provide a DOI for data in your publications.
See [Data](data.html) for more details.

Metadata and provenance of data (e.g. original source, date acquired, etc.)
should be recorded and archived with the data. See [Data](data.html) for more details.

Code developed as part of the research (e.g. to illustrate a new algorithm or
to perform data analysis) should be made available to readers.

Perform internal code reviews and replication studies within your research
group to insure that you have archived and adequately documented all code and
data needed to reproduce published results. See [Code](code.html) for more details.

Ensure that your code and data can be properly cited. Many repositories issue a
DOI, for example. See [Data](data.html) for more details.

Make it clear what the rules are for others to use your code or data, e.g. by
attaching a suitable license to code. This increases the chances that others
will build on it, and that you will get the proper credit. 
See [Data](data.html) for more details.

## Replicable environment

The computation environment should be documented with sufficient detail so that
others can create an equivalent environment. It is preferred to use automated
tools such as Vagrant for Virtual Machines or make for Unix. 

Use virtualization when appropriate to archive the environment in which a code
runs, e.g. VirtualBox (which is free) or VMWare, or machine images on cloud
computing platforms such as AWS or Windows Azure. 

See [Virtualization](virtualization.html) for more details.

## Other resources

See [Resources](resources.html) for more discussion of these guidelines and 
links to other resources and tutorials.
