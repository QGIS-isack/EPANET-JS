# BUWASA GIS–EPANET Water Loss Risk Visualization Model

## Project Description

The BUWASA GIS–EPANET Water Loss Risk Visualization Model is a web-based application developed to support the identification and visualization of potential water loss (leakage) risk areas within the BUWASA water distribution network.

The project integrates Geographic Information Systems (GIS) data with EPANET hydraulic modelling to analyze hydraulic conditions such as pressure, flow velocity, and head-loss characteristics. The results are processed to generate a leakage risk index that highlights areas with higher potential for water loss occurrence.

The system provides an interactive visualization platform where users can explore the water distribution network, view hydraulic simulation results, and identify potential leakage hotspot areas without depending only on reported leakage incidents.

## Problem Solved

Water losses in distribution networks are a major challenge for water utilities because undetected leaks can reduce operational efficiency, increase production costs, and affect water supply reliability.

Traditional leak detection approaches often depend on customer complaints or field inspections, which may delay response. This project provides a proactive approach by using hydraulic modelling and spatial analysis to identify areas that require priority investigation and maintenance.

## Key Features

- Integration of GIS water network data with EPANET hydraulic simulation.
- Visualization of pipelines, nodes, valves, tanks, and hydraulic results.
- Mapping of potential water loss risk zones.
- Interactive web-based visualization using EPANET-JS.
- Support for decision-making in leakage monitoring and network management.

## Web Visualization

The `index.html` file contains the web interface that embeds the **EPANET-JS water network model**. It allows users to view and interact with the hydraulic model directly through a web browser without installing EPANET software.

The embedded model provides visualization of:

- Water distribution network layout.
- Hydraulic simulation results.
- Network components and attributes.
- Potential leakage risk areas.

## How to View the Live Site

The project is published using **GitHub Pages**.

To view the live visualization:

1. Open a web browser.
2. Visit the GitHub Pages link:
