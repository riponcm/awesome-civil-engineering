<p align="center">
  <img src="assets/banner.svg" alt="Awesome Civil Engineering — a curated list of open-source tools for structural, geotechnical, transportation, water and geospatial engineering" width="100%">
</p>

# Awesome Civil Engineering List

> Curated open-source civil engineering software: structural analysis, geotechnical engineering, earthquake engineering, transportation, hydraulics, BIM, GIS, surveying, and mining tools — free for engineers, researchers, and students.

![Awesome](https://awesome.re/badge.svg) ![License: CC0](https://img.shields.io/badge/license-CC0--1.0-lightgrey.svg)

**Awesome Civil Engineering** is a curated directory of free, open-source civil engineering software — structural analysis and finite element analysis (FEA), geotechnical engineering and soil mechanics, earthquake and seismic hazard analysis, traffic and transportation simulation, hydraulics and stormwater modeling, BIM/CAD, GIS and geospatial processing, land surveying and point cloud tools, and mining geostatistics.

Every entry is a real, public, open-source project you can download and use today. Star counts are live badges rendered on every page view, so the numbers stay current automatically — no scheduled job required. To add a project, see [CONTRIBUTING.md](CONTRIBUTING.md) — one pull request, one entry.

## Contents

- [Structural Engineering & Analysis](#structural-engineering)
- [Geotechnical Engineering](#geotechnical-engineering)
- [Earthquake Engineering](#earthquake-engineering)
- [Transportation Engineering](#transportation-engineering)
- [Environmental Engineering](#environmental-engineering)
- [Hydraulics & Water Resources](#hydraulics-water-resources)
- [BIM & CAD](#bim-cad)
- [GIS & Geospatial](#gis-geospatial)
- [Surveying & Point Cloud Processing](#surveying-point-cloud)
- [Mining Engineering](#mining-engineering)
- [FAQ](#faq--open-source-civil-engineering-software)
- [Contributing](#contributing)

<a id="structural-engineering"></a>
<img src="assets/headers/structural-engineering.svg" alt="Structural Engineering & Analysis — open-source tools" width="100%">

Open-source structural analysis software: finite element analysis (FEA) frameworks, 2D/3D frame and truss solvers, and seismic response simulation for buildings and bridges.

<table>
<tr>
<td width="25%" valign="top">
<a href="https://opensees.berkeley.edu"><b>OpenSees</b></a><br>
<sub><b>STRUCTURAL</b></sub><br><br>
<sub>Open-source framework for simulating the seismic response of structural and geotechnical systems.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/OpenSees/OpenSees?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for OpenSees/OpenSees">
</td>
<td width="25%" valign="top">
<a href="https://pynite.readthedocs.io"><b>PyNite</b></a><br>
<sub><b>STRUCTURAL</b></sub><br><br>
<sub>Simple, elastic 3D finite element analysis library for structural engineering, written in Python.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/JWock82/PyNite?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for JWock82/PyNite">
</td>
<td width="25%" valign="top">
<a href="https://sectionproperties.rtfd.io"><b>sectionproperties</b></a><br>
<sub><b>STRUCTURAL</b></sub><br><br>
<sub>Analysis of arbitrary structural cross-sections in Python: section properties, warping, and stress computation.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/robbievanleeuwen/section-properties?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for robbievanleeuwen/section-properties">
</td>
<td width="25%" valign="top">
<a href="https://anastruct.readthedocs.io"><b>anaStruct</b></a><br>
<sub><b>STRUCTURAL</b></sub><br><br>
<sub>Analyse 2D frames and trusses for slender structures: bending moments, shear, axial forces, and displacements.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/anastruct/anaStruct?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for anastruct/anaStruct">
</td>
</tr>
<tr>
<td width="25%" valign="top">
<a href="http://www.xcengineering.xyz/html_files/software.html"><b>XC</b></a><br>
<sub><b>STRUCTURAL</b></sub><br><br>
<sub>Open-source finite element analysis program oriented to civil and structural engineering problems.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/xcfem/xc?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for xcfem/xc">
</td>
<td width="25%" valign="top">
<a href="https://github.com/cmccomb/TrussMe"><b>TrussMe</b></a><br>
<sub><b>STRUCTURAL</b></sub><br><br>
<sub>Python library for analyzing and optimizing truss structures, including loads, reactions, member safety factors, and mass.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/cmccomb/TrussMe?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for cmccomb/TrussMe">
</td>
<td width="25%" valign="top">
<a href="https://docs.rs/trussx"><b>trussx</b></a><br>
<sub><b>STRUCTURAL</b></sub><br><br>
<sub>Rust library for designing and analyzing truss structures, including loads, stresses, buckling, and safety factors.</sub><br><br>
<img src="https://img.shields.io/badge/-Rust-24292f?style=flat-square" alt="Written in Rust">
<img src="https://img.shields.io/github/stars/cmccomb/trussx?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for cmccomb/trussx">
</td>
<td width="25%" valign="top">
<a href="https://rebarcount.com"><b>rebar-data</b></a><br>
<sub><b>STRUCTURAL</b></sub><br><br>
<sub>Nominal rebar sizes, weights and cross-sectional areas as CSV, plus a CLI estimator for rectangular rebar grids.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/rebarcount/rebar-data?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for rebarcount/rebar-data">
</td>
</tr>
</table>

<a id="geotechnical-engineering"></a>
<img src="assets/headers/geotechnical-engineering.svg" alt="Geotechnical Engineering — open-source tools" width="100%">

Open-source geotechnical engineering tools for soil mechanics, foundation design, SPT/CPT interpretation, bearing capacity, settlement, liquefaction, and slope stability analysis.

<table>
<tr>
<td width="25%" valign="top">
<a href="https://github.com/snakesonabrain/groundhog"><b>groundhog</b></a><br>
<sub><b>GEOTECHNICAL</b></sub><br><br>
<sub>General-purpose geotechnical Python library for site investigation data, foundation design, and soil profile analysis.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/snakesonabrain/groundhog?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for snakesonabrain/groundhog">
</td>
<td width="25%" valign="top">
<a href="https://geoeq.org"><b>GeoEq</b></a><br>
<sub><b>GEOTECHNICAL</b></sub><br><br>
<sub>170+ validated Python functions for soil mechanics, SPT, CPT, bearing capacity, settlement, liquefaction, and slope stability.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/geoeq/geoeq?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for geoeq/geoeq">
</td>
<td width="25%" valign="top">
<a href="https://cemsbv.github.io/pygef"><b>pygef</b></a><br>
<sub><b>GEOTECHNICAL</b></sub><br><br>
<sub>Parse and analyse CPT and borehole files (GEF/XML) from geotechnical site investigations into dataframes.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/cemsbv/pygef?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for cemsbv/pygef">
</td>
<td width="25%" valign="top">
<a href="https://docs.geolysis.io"><b>geolysis</b></a><br>
<sub><b>GEOTECHNICAL</b></sub><br><br>
<sub>Python package for geotechnical analysis: soil classification, SPT corrections, and allowable bearing capacity.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/patrickboateng/geolysis?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for patrickboateng/geolysis">
</td>
</tr>
</table>

<a id="earthquake-engineering"></a>
<img src="assets/headers/earthquake-engineering.svg" alt="Earthquake Engineering — open-source tools" width="100%">

Open-source earthquake engineering software for seismic hazard assessment, ground motion modeling, and earthquake risk analysis.

<table>
<tr>
<td width="25%" valign="top">
<a href="https://www.obspy.org"><b>ObsPy</b></a><br>
<sub><b>EARTHQUAKE</b></sub><br><br>
<sub>Python framework for processing seismological data: waveforms, event catalogs, and station metadata.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/obspy/obspy?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for obspy/obspy">
</td>
<td width="25%" valign="top">
<a href="https://www.globalquakemodel.org"><b>OpenQuake Engine</b></a><br>
<sub><b>EARTHQUAKE</b></sub><br><br>
<sub>Seismic hazard and risk analysis engine developed by the Global Earthquake Model (GEM) Foundation.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/gem/oq-engine?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for gem/oq-engine">
</td>
<td width="25%" valign="top">
<a href="https://github.com/usgs/groundmotion-processing"><b>gmprocess</b></a><br>
<sub><b>EARTHQUAKE</b></sub><br><br>
<sub>USGS software for automated processing of earthquake ground-motion records.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/usgs/groundmotion-processing?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for usgs/groundmotion-processing">
</td>
<td width="25%" valign="top">
<a href="https://eqsig.readthedocs.io"><b>eqsig</b></a><br>
<sub><b>EARTHQUAKE</b></sub><br><br>
<sub>Python library for seismic signal processing: response spectra, Arias intensity, and ground-motion metrics.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/eng-tools/eqsig?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for eng-tools/eqsig">
</td>
</tr>
</table>

<a id="transportation-engineering"></a>
<img src="assets/headers/transportation-engineering.svg" alt="Transportation Engineering — open-source tools" width="100%">

Open-source transportation engineering software for traffic simulation, highway modeling, and multi-modal transport network analysis.

<table>
<tr>
<td width="25%" valign="top">
<a href="https://a-b-street.github.io/docs/"><b>A/B Street</b></a><br>
<sub><b>TRANSPORTATION</b></sub><br><br>
<sub>Transportation planning and traffic simulation game exploring how small street changes affect a city.</sub><br><br>
<img src="https://img.shields.io/badge/-Rust-24292f?style=flat-square" alt="Written in Rust">
<img src="https://img.shields.io/github/stars/a-b-street/abstreet?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for a-b-street/abstreet">
</td>
<td width="25%" valign="top">
<a href="https://eclipse.dev/sumo/"><b>SUMO</b></a><br>
<sub><b>TRANSPORTATION</b></sub><br><br>
<sub>Microscopic, multi-modal traffic simulation package for modeling urban and highway transportation networks.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/eclipse-sumo/sumo?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for eclipse-sumo/sumo">
</td>
<td width="25%" valign="top">
<a href="https://matsim.org"><b>MATSim</b></a><br>
<sub><b>TRANSPORTATION</b></sub><br><br>
<sub>Agent-based transport simulation framework for large-scale, activity-based travel demand modeling.</sub><br><br>
<img src="https://img.shields.io/badge/-Java-24292f?style=flat-square" alt="Written in Java">
<img src="https://img.shields.io/github/stars/matsim-org/matsim-libs?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for matsim-org/matsim-libs">
</td>
<td width="25%" valign="top">
<a href="https://www.aequilibrae.com"><b>AequilibraE</b></a><br>
<sub><b>TRANSPORTATION</b></sub><br><br>
<sub>Python transportation modeling package: network editing, traffic assignment, and matrix estimation, with a QGIS plugin.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/AequilibraE/aequilibrae?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for AequilibraE/aequilibrae">
</td>
</tr>
</table>

<a id="environmental-engineering"></a>
<img src="assets/headers/environmental-engineering.svg" alt="Environmental Engineering — open-source tools" width="100%">

Open-source environmental engineering tools for water quality modeling and infrastructure resilience analysis.

<table>
<tr>
<td width="25%" valign="top">
<a href="https://flopy.readthedocs.io"><b>FloPy</b></a><br>
<sub><b>ENVIRONMENTAL</b></sub><br><br>
<sub>Python package to create, run, and post-process MODFLOW-based groundwater models.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/modflowpy/flopy?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for modflowpy/flopy">
</td>
<td width="25%" valign="top">
<a href="https://usepa.github.io/WNTR/"><b>WNTR</b></a><br>
<sub><b>ENVIRONMENTAL</b></sub><br><br>
<sub>Python package to simulate and analyze the resilience of water distribution networks under disruptive events.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/USEPA/WNTR?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for USEPA/WNTR">
</td>
<td width="25%" valign="top">
<a href="https://modflow6.readthedocs.io/"><b>MODFLOW 6</b></a><br>
<sub><b>ENVIRONMENTAL</b></sub><br><br>
<sub>USGS modular hydrologic model: the industry-standard simulator for groundwater flow and transport.</sub><br><br>
<img src="https://img.shields.io/badge/-Fortran-24292f?style=flat-square" alt="Written in Fortran">
<img src="https://img.shields.io/github/stars/MODFLOW-ORG/modflow6?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for MODFLOW-ORG/modflow6">
</td>
<td width="25%" valign="top">
<a href="https://qsdsan.com"><b>QSDsan</b></a><br>
<sub><b>ENVIRONMENTAL</b></sub><br><br>
<sub>Quantitative sustainable design of sanitation and resource recovery systems: process modeling and life cycle assessment.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/QSD-Group/QSDsan?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for QSD-Group/QSDsan">
</td>
</tr>
</table>

<a id="hydraulics-water-resources"></a>
<img src="assets/headers/hydraulics-water-resources.svg" alt="Hydraulics & Water Resources — open-source tools" width="100%">

Open-source hydraulic and hydrology software for stormwater management, sewer systems, and water resources engineering.

<table>
<tr>
<td width="25%" valign="top">
<a href="https://www.epa.gov/water-research/epanet"><b>EPANET</b></a><br>
<sub><b>HYDRAULICS</b></sub><br><br>
<sub>Hydraulic and water quality solver for pressurized drinking-water distribution networks (community repository).</sub><br><br>
<img src="https://img.shields.io/badge/-C-24292f?style=flat-square" alt="Written in C">
<img src="https://img.shields.io/github/stars/OpenWaterAnalytics/EPANET?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for OpenWaterAnalytics/EPANET">
</td>
<td width="25%" valign="top">
<a href="https://www.pyswmm.org"><b>PySWMM</b></a><br>
<sub><b>HYDRAULICS</b></sub><br><br>
<sub>Python interface to EPA SWMM: step through stormwater simulations and control hydraulic elements in real time.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/pyswmm/pyswmm?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for pyswmm/pyswmm">
</td>
<td width="25%" valign="top">
<a href="https://www.epa.gov/water-research/storm-water-management-model-swmm"><b>EPA SWMM</b></a><br>
<sub><b>HYDRAULICS</b></sub><br><br>
<sub>Dynamic hydrology-hydraulic water quality simulation model for stormwater, wastewater, and combined sewer systems.</sub><br><br>
<img src="https://img.shields.io/badge/-C-24292f?style=flat-square" alt="Written in C">
<img src="https://img.shields.io/github/stars/USEPA/Stormwater-Management-Model?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for USEPA/Stormwater-Management-Model">
</td>
<td width="25%" valign="top">
<a href="https://anuga.anu.edu.au"><b>ANUGA</b></a><br>
<sub><b>HYDRAULICS</b></sub><br><br>
<sub>Hydrodynamic modeling of floods, storm surges, and tsunamis using the shallow water wave equation.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/anuga-community/anuga_core?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for anuga-community/anuga_core">
</td>
</tr>
</table>

<a id="bim-cad"></a>
<img src="assets/headers/bim-cad.svg" alt="BIM & CAD — open-source tools" width="100%">

Open-source BIM and CAD software: Building Information Modeling, IFC interoperability, and parametric 3D modeling for architecture, engineering, and construction (AEC).

<table>
<tr>
<td width="25%" valign="top">
<a href="https://www.freecad.org"><b>FreeCAD</b></a><br>
<sub><b>BIM / CAD</b></sub><br><br>
<sub>Free and open-source multiplatform 3D parametric modeler, widely used for mechanical and architectural design.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/FreeCAD/FreeCAD?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for FreeCAD/FreeCAD">
</td>
<td width="25%" valign="top">
<a href="https://ifcopenshell.org"><b>IfcOpenShell</b></a><br>
<sub><b>BIM / CAD</b></sub><br><br>
<sub>Open source IFC library and geometry engine powering BIM interoperability tools.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/IfcOpenShell/IfcOpenShell?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for IfcOpenShell/IfcOpenShell">
</td>
<td width="25%" valign="top">
<a href="https://thatopen.github.io/engine_web-ifc/demo"><b>That Open Engine</b></a><br>
<sub><b>BIM / CAD</b></sub><br><br>
<sub>Fast IFC parsing and geometry engine for reading and writing BIM models in JavaScript and WebAssembly.</sub><br><br>
<img src="https://img.shields.io/badge/-TypeScript-24292f?style=flat-square" alt="Written in TypeScript">
<img src="https://img.shields.io/github/stars/ThatOpen/engine_web-ifc?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for ThatOpen/engine_web-ifc">
</td>
<td width="25%" valign="top">
<a href="https://speckle.systems"><b>Speckle</b></a><br>
<sub><b>BIM / CAD</b></sub><br><br>
<sub>Collaborative data hub for AEC: exchange 3D models and BIM data between design tools in real time.</sub><br><br>
<img src="https://img.shields.io/badge/-TypeScript-24292f?style=flat-square" alt="Written in TypeScript">
<img src="https://img.shields.io/github/stars/specklesystems/speckle-server?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for specklesystems/speckle-server">
</td>
</tr>
</table>

<a id="gis-geospatial"></a>
<img src="assets/headers/gis-geospatial.svg" alt="GIS & Geospatial — open-source tools" width="100%">

Open-source GIS software and geospatial libraries for spatial data management, mapping, and geographic analysis in civil and infrastructure projects.

<table>
<tr>
<td width="25%" valign="top">
<a href="https://qgis.org"><b>QGIS</b></a><br>
<sub><b>GIS</b></sub><br><br>
<sub>Full-featured, free and open-source geographic information system for spatial data management and analysis.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/qgis/QGIS?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for qgis/QGIS">
</td>
<td width="25%" valign="top">
<a href="https://geolibre.app"><b>GeoLibre</b></a><br>
<sub><b>GIS</b></sub><br><br>
<sub>Lightweight, cloud-native GIS platform that runs in the browser, on desktop, on mobile, and inside Jupyter notebooks.</sub><br><br>
<img src="https://img.shields.io/badge/-TypeScript-24292f?style=flat-square" alt="Written in TypeScript">
<img src="https://img.shields.io/github/stars/opengeos/GeoLibre?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for opengeos/GeoLibre">
</td>
<td width="25%" valign="top">
<a href="https://gdal.org"><b>GDAL</b></a><br>
<sub><b>GIS</b></sub><br><br>
<sub>Translator library for raster and vector geospatial data formats, powering most GIS software under the hood.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/OSGeo/gdal?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for OSGeo/gdal">
</td>
<td width="25%" valign="top">
<a href="https://geopandas.org"><b>GeoPandas</b></a><br>
<sub><b>GIS</b></sub><br><br>
<sub>Pandas-based Python library for geospatial vector data: geometry operations, spatial joins, and mapping.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/geopandas/geopandas?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for geopandas/geopandas">
</td>
</tr>
<tr>
<td width="25%" valign="top">
<a href="https://acadgis.com"><b>AcadGIS</b></a><br>
<sub><b>GIS</b></sub><br><br>
<sub>Study-area and research map generator: turns a place name and a data table into journal-ready maps in a few lines of Python.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/riponcm/AcadGIS?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for riponcm/AcadGIS">
</td>
</tr>
</table>

<a id="surveying-point-cloud"></a>
<img src="assets/headers/surveying-point-cloud.svg" alt="Surveying & Point Cloud Processing — open-source tools" width="100%">

Open-source surveying and point cloud software for LiDAR data, laser scanning, and 3D terrain processing.

<table>
<tr>
<td width="25%" valign="top">
<a href="https://www.open3d.org"><b>Open3D</b></a><br>
<sub><b>SURVEYING</b></sub><br><br>
<sub>Modern library for 3D data processing: point clouds, meshes, registration, and reconstruction in Python and C++.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/isl-org/Open3D?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for isl-org/Open3D">
</td>
<td width="25%" valign="top">
<a href="http://potree.org"><b>Potree</b></a><br>
<sub><b>SURVEYING</b></sub><br><br>
<sub>WebGL viewer for massive point clouds: stream and explore billions of laser-scan points in the browser.</sub><br><br>
<img src="https://img.shields.io/badge/-JavaScript-24292f?style=flat-square" alt="Written in JavaScript">
<img src="https://img.shields.io/github/stars/potree/potree?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for potree/potree">
</td>
<td width="25%" valign="top">
<a href="https://cloudcompare.org"><b>CloudCompare</b></a><br>
<sub><b>SURVEYING</b></sub><br><br>
<sub>3D point cloud and mesh processing software, widely used for comparing and analyzing laser-scan survey data.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/CloudCompare/CloudCompare?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for CloudCompare/CloudCompare">
</td>
<td width="25%" valign="top">
<a href="https://pdal.org"><b>PDAL</b></a><br>
<sub><b>SURVEYING</b></sub><br><br>
<sub>Point Data Abstraction Library: translates and processes point cloud data, the GDAL of point clouds.</sub><br><br>
<img src="https://img.shields.io/badge/-C%2B%2B-24292f?style=flat-square" alt="Written in C++">
<img src="https://img.shields.io/github/stars/PDAL/PDAL?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for PDAL/PDAL">
</td>
</tr>
</table>

<a id="mining-engineering"></a>
<img src="assets/headers/mining-engineering.svg" alt="Mining Engineering — open-source tools" width="100%">

Open-source mining engineering tools for geostatistics and mineral resource estimation.

<table>
<tr>
<td width="25%" valign="top">
<a href="https://gempy.org"><b>GemPy</b></a><br>
<sub><b>MINING</b></sub><br><br>
<sub>3D structural geological modeling in Python with implicit interpolation and probabilistic support.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/gempy-project/gempy?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for gempy-project/gempy">
</td>
<td width="25%" valign="top">
<a href="https://geostat-framework.org"><b>GSTools</b></a><br>
<sub><b>MINING</b></sub><br><br>
<sub>Geostatistical toolbox: variogram estimation, kriging, random field generation, and spatial interpolation.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/GeoStat-Framework/GSTools?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for GeoStat-Framework/GSTools">
</td>
<td width="25%" valign="top">
<a href="https://mmaelicke.github.io/scikit-gstat/"><b>SciKit-GStat</b></a><br>
<sub><b>MINING</b></sub><br><br>
<sub>SciPy-style variogram estimation and geostatistics toolbox for Python.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/mmaelicke/scikit-gstat?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for mmaelicke/scikit-gstat">
</td>
<td width="25%" valign="top">
<a href="https://opengeostat.github.io/pygslib/"><b>PyGSLIB</b></a><br>
<sub><b>MINING</b></sub><br><br>
<sub>Open-source geostatistics and mineral resource estimation toolkit, wrapping the classic GSLIB Fortran code in Python.</sub><br><br>
<img src="https://img.shields.io/badge/-Python-24292f?style=flat-square" alt="Written in Python">
<img src="https://img.shields.io/github/stars/opengeostat/pygslib?style=flat-square&label=%E2%98%85&color=ffd54f&labelColor=24292f" alt="GitHub stars for opengeostat/pygslib">
</td>
</tr>
</table>

## FAQ — Open-Source Civil Engineering Software

### What is the best open-source library for geotechnical engineering in Python?

[GeoEq](https://geoeq.org) provides 170+ validated Python functions covering soil mechanics, SPT and CPT correlations, bearing capacity, settlement, liquefaction triggering, and slope stability — making it the most comprehensive open-source geotechnical engineering library in Python.

### What is the best open-source structural analysis software?

[OpenSees](https://opensees.berkeley.edu) is the standard open-source framework for seismic and structural simulation in research and practice. For lighter workflows, [PyNite](https://pynite.readthedocs.io) offers 3D finite element analysis in Python, and [anaStruct](https://anastruct.readthedocs.io) handles 2D frame and truss analysis.

### What is the best free alternative to commercial FEA software for civil engineers?

For structural work, [OpenSees](https://opensees.berkeley.edu) and [PyNite](https://pynite.readthedocs.io) are free, open-source finite element analysis options that cover many workflows engineers otherwise license commercial packages for. They are scriptable, extensible, and used in both industry and academia.

### What is the best open-source software for seismic hazard analysis?

The [OpenQuake Engine](https://www.globalquakemodel.org), developed by the Global Earthquake Model (GEM) Foundation, is the leading open-source engine for probabilistic seismic hazard and earthquake risk assessment worldwide.

### What is the best open-source traffic simulation software?

[SUMO](https://eclipse.dev/sumo/) (Simulation of Urban MObility) is the most widely used open-source microscopic traffic simulator, supporting multi-modal road networks, signal control, and large-scale transportation studies.

### What open-source software can model stormwater and sewer systems?

[EPA SWMM](https://www.epa.gov/water-research/storm-water-management-model-swmm) is the industry-standard public-domain model for stormwater, wastewater, and combined sewer systems. For drinking-water distribution network resilience, see [WNTR](https://www.epa.gov/water-research/water-network-tool-resilience-wntr).

### What is the best open-source BIM software?

[FreeCAD](https://www.freecad.org) provides parametric 3D modeling with BIM workflows, and [IfcOpenShell](https://ifcopenshell.org) is the open-source IFC library that powers BIM interoperability across the AEC industry.

### What is the best open-source GIS software?

[QGIS](https://qgis.org) is the leading free and open-source desktop GIS application. Under the hood, most geospatial software relies on [GDAL](https://gdal.org) for reading and writing spatial data formats.

### What is the best open-source tool for processing LiDAR and point cloud survey data?

[CloudCompare](https://cloudcompare.org) is the go-to desktop application for comparing and analyzing laser-scan point clouds; [PDAL](https://pdal.org) is the processing library — often described as the GDAL of point clouds.

### Are these tools free for commercial use?

Most are, but licenses differ. Permissive licenses (MIT, BSD, Apache-2.0) allow commercial use with minimal conditions; copyleft licenses (GPL, LGPL, AGPL, EPL) allow commercial use but add obligations if you redistribute or, for AGPL, offer the software as a service. Each card lists the project's license — always check it before embedding a tool in a commercial product.

### How do I add a project to this list?

Open one pull request adding one entry to `data/tools.json`, following [CONTRIBUTING.md](https://github.com/riponcm/awesome-civil-engineering-list/blob/main/CONTRIBUTING.md). Entries must be real, public, OSI-licensed open-source projects with an honest one-line description.

## Related Lists

- [Awesome Geospatial](https://github.com/sacridini/Awesome-Geospatial) — a broad catalog of geospatial analysis tools and libraries.
- [Awesome GIS](https://github.com/sshuair/awesome-gis) — GIS software, data, and learning resources.
- [Awesome Open Geoscience](https://github.com/softwareunderground/awesome-open-geoscience) — open-source tools across the wider geoscience community.

## Contributing

Contributions are welcome and take one pull request. See [CONTRIBUTING.md](CONTRIBUTING.md) for the process: add a single entry to `data/tools.json` and run `python scripts/build_readme.py`. Entries must be real, public, OSI-licensed open-source projects with an honest one-line description.

## License

The curation in this list (not the linked projects themselves) is released under [CC0 1.0](LICENSE). Each listed project keeps its own license, shown on its card.

<p align="center"><sub>Designed & curated by <a href="https://github.com/riponcm">github.com/riponcm</a></sub></p>
