---
title: Virtualization
layout: default
---

[[Overview and index]](index.html)


# Virtualization

Add discussion...

 - [VirtualBox](https://www.virtualbox.org/)
 - [vmware](http://www.vmware.com/)
 - [Vagrant](https://www.vagrantup.com/) ...
   [Vagrant4Scientists](http://hplgit.github.io/vagrantbox/doc/pub/._vagrant_box001.html)
 - [Docker](https://www.docker.com/)

### Reproducible environment tools

 - [Berkeley Computational Environment](http://collaboratool.berkeley.edu/)
 - [reprozip](http://cds.nyu.edu/projects/reprozip/)
 - [hashdist](http://hashdist.readthedocs.org/en/latest/)
 - The R package [Packrat](https://rstudio.github.io/packrat/) creates a portable private library of dependencies for a  specific project;
 - An open source version of R, [Microsoft R Open](https://mran.revolutionanalytics.com/rro/), formerlly called [Revolution Analytics](http://blog.revolutionanalytics.com/2016/01/microsoft-r-open.html), along with their R package [Checkpoints](https://cran.r-project.org/web/packages/checkpoint/index.html) can fix all the dependencies to a specific checkpoint (or rewind to a previous point); their goal is to eventually have a published schedule for their future checkpoints to encourage developers to sinc their releases just as [Bioconductor](https://www.bioconductor.org/)(a managed collection of bioinformatics packages) does with their two release dates each year; see ["Using Checkpoints for Reproducible Research"] (2016) by Andrie de Vries on The Reproducible R Toolkit, ["Introducing the Reproducible R Toolkit and the checkpoint package"](http://blog.revolutionanalytics.com/2014/10/introducing-rrt.html) and ["Microsoft Offers a Faster, More Efficient R, But Is It Right For You?"](https://blog.treasuredata.com/blog/2016/03/03/microsoft-offers-faster-efficient-r/); unlike packrat, packages do not need to be archived.

### Cloud computing

 - [SageMathCloud](https://cloud.sagemath.com/)
 - [Galaxy](https://galaxyproject.org/) for biomedical research
 - [Mathematica Cloud](https://www.wolframcloud.com/)
 - [Kaggle](https://www.kaggle.com/)
 - [Jupyter NBViewer](https://nbviewer.jupyter.org/), notebooks also [render on Gituhub](https://blog.jupyter.org/2015/05/07/rendering-notebooks-on-github/); ([Wakari](https://wakari.io/) has disbanded in favor of Jupyter).
 - [Shiny by RStudio](https://shiny.rstudio.com/); R-based web apps can be deployed at [shinyapps.io](http://www.shinyapps.io).
 - [Amazon Web Services (AWS)](https://aws.amazon.com/) including [Amazon Machine Images](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/AMIs.html)
 - [Microsoft Azure](https://azure.microsoft.com/) including [VM Images](https://azure.microsoft.com/en-us/blog/vm-image-blog-post/), [Azure Notebooks](https://notebooks.azure.com), and [Azure Machine Learning Studio](https://studio.azureml.net/)
 - [Git Large File Storage](https://git-lfs.github.com/) is an open source git extension for storing large data files in a remote server such as GitHub, AWS, Azure, or a university (options at the University of Washington listed here: [IT Connect](https://itconnect.uw.edu/wares/online-storage/)).
 - [Zooinverse](https://www.zooniverse.org/) allows researchers to upload data and code a project ([GalaxyZoo](https://www.galaxyzoo.org/) being a famous example) allowing volunteers to process data, paraticularly data that cannot be done (or done well) by computers.
