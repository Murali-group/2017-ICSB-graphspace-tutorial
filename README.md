# GraphSpace Tutorial: Interdisciplinary Collaborations in Network Biology

## Before the tutorial

If you are planning to participate in the tutorial on "**GraphSpace: Stimulating interdisciplinary collaborations in Network Biology**" at ICSB 2017, here is some information you need to know.

We will be leading the tutorial using the [Jupyter](http://jupyter.readthedocs.io/en/latest/install.html)/[IPython](https://ipython.org/install.html) notebook, and will provide a pre-written notebook to the attendees.

Attendees will need to bring a laptop with [Jupyter](http://jupyter.readthedocs.io/en/latest/install.html) and [Python](https://www.continuum.io/downloads) installed.  Both Python 2 and 3 are welcome. But **Python 3 is recommended**. 

Installing the [Anaconda distribution of Python](https://www.continuum.io/downloads) is an easy way to install Jupyter and Python at the same time.

You can also install Anaconda distribution of Python using the following links:

- [Windows](https://repo.continuum.io/archive/Anaconda3-4.4.0-Windows-x86_64.exe)
- [MacOS](https://repo.continuum.io/archive/Anaconda3-4.4.0-MacOSX-x86_64.pkg)
- [Linux](https://repo.continuum.io/archive/Anaconda3-4.4.0-Linux-x86_64.sh)

If you want to know more about GraphSpace in preparation for the tutorial, here are some useful links:

1. GraphSpace is free to use at [http://www.graphspace.org](http://www.graphspace.org)
2. Documentation is available at [http://manual.graphspace.org/](http://manual.graphspace.org)
3. Bharadwaj, Aditya, et al. "[GraphSpace: Stimulating Interdisciplinary Collaborations in Network Biology](https://doi.org/10.1093/bioinformatics/btx382)" [Bioinformatics](https://doi.org/10.1093/bioinformatics/btx382), in press, 2017.


## Description

Computational analysis of molecular interaction networks has become pervasive in systems biology. Nearly every publication that uses network analysis includes a visualization of a graph in which the nodes and edges are laid out in two dimensions. Several systems implement methods for creating such layouts. Despite these advances, interdisciplinary research teams in network biology face several challenges in sharing, exploring, and interpreting computed networks in their collaborations.

GraphSpace is a web-based system that provides a rich set of user-friendly features designed to enhance network-based collaboration:
1. Users can upload richly-annotated networks, irrespective of the algorithms or software used to generate them. 
2. Users can create private groups, invite other users to join groups, and share networks with group members.   
3. A user may search for networks that contain a specific node or edge, or a collection of nodes and edges. 
4. A powerful layout editor allows users to efficiently modify node positions, edit node and edge styles, save new layouts, and share them with other users. 
5. Researchers may make networks public and provide a persistent URL in a publication, enabling other researchers to explore these networks.

## Objective

This tutorial will provide an in-depth introduction to GraphSpace. Attendees will receive hands-on training on the GraphSpace web interface and how to incorporate programmatic interaction with GraphSpace into their network analysis projects. 

## Schedule (180 minutes)

We will be leading the tutorial using the IPython/Jupyter notebook, and have added a pre-written notebook to this repository. 

**Session 1**: Using GraphSpace as a collaborative tool and a cloud store for networks 

This session will begin with the main challenges faced by interdisciplinary research groups who collaborate on network analysis projects. It will present the main features of GraphSpace that are intended to address these challenges and compare GraphSpace to other prevalent systems.

The session will familiarize users with the main features of GraphSpace, including uploading graphs, sharing them with other users, creating layouts and manipulating node and edge styles, sharing layouts, searching across graphs, and publishing graphs. Attendees will also learn how to export their networks from Cytoscape into GraphSpace.


**Session 2**: Integrating GraphSpace into network analysis projects

Starting with a brief introduction to Python, this session will use the NetworkX package and the graphspace_python package to demonstrate the ease with which a researcher can networks that can be readily uploaded to GraphSpace programmatically. Attendees will also learn how to use the graphspace_python package to manage groups, share graphs and layouts with a group, publish graphs and layouts for public viewing, and use tags for organizing graphs.

**Session 3**: Demonstrating use cases for GraphSpace 

In this session, users will engage in developing more complex analysis pipelines around NetworkX and GraphSpace. They will use heterogeneous data sources to build networks, perform different types of network analyses, and encode the results visually in networks that they will upload to GraphSpace. 
