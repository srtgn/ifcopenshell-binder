# ifcopenshell-binder
Binder configuration for an ifcopenshell JupyterLab environment 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/srtgn/ifcopenshell-binder/main?urlpath=lab?git-pull?repo=https://github.com/jakob-beetz/ifcopenshell-notebooks)

IfcOpenShell is an open source (LGPL) software library that helps users and software developers to work with the IFC file format. The IFC file format can be used to describe building and construction data. The format is commonly used for Building Information Modelling.

IfcOpenShell uses Open CASCADE (the Open CASCADE Community Edition) internally to convert the implicit geometry in IFC files into explicit geometry that any software CAD or modelling package can understand.

Please note that IfcOpenShell is a work in progress. At the moment only files with the .ifc extension are supported (technically known as IFC-SPF). Support for IFC-XML and IFC-ZIP will be added in the future. Please note that at this moment IfcOpenShell may not fully understand all geometry that is present in an .ifc file, rest assured that it’ll do the very best it can and support for the other types of geometry is already on its way.

Currently on the menu is an importer for Autodesk 3ds Max, an importer for Blender and a stand-alone application to convert an IFC file into a Wavefront .obj file. Furthermore, software developers are explicitly encouraged to use the IfcOpenShell library in their own applications.

This content is intended as Open Educational Resource (OER) and was created at RWTH Aachen University
Contact info: saeeed.rastegarian@rwth-aachen.de
