# NeTEx-Profile-EPIP

## Overview

This repository contains the XSD files for the NeTEx European Passenger Information Profile (EPIP). EPIP XSD is a subset of the [full NeTEx XML Schema](https://github.com/TransmodelEcosystem/NeTEx).
It was created in 2021 in the context of the Data4PT project, based on the NeTEx XSD v1.3.1. **This XSD is no longer maintained by the NeTEx subgroup.**

## Objectives

This XSD primary objectives were to:
- support generation of NeTEx files covering the EPIP functional scope (top locations, routes, timetables, etc.);
- faciliate NeTEx datasets validation agasint EPIP.

## Content

The following XSD files are available in this repository:

XSD File Name                          | Description
--------------------------------------|-------------------------------------------------------------
**`NeTEx_publication_EPIP.xsd`**            | Defines the schema for a NeTEx publication that conforms to the EPIP.
**`NeTEx_publication_EPIP-NoConstraint.xsd`**  | A simplified version of NeTEx_publication_EPIP.xsd, removing optional elements and constraints for easier use.
**`_content_NeTEx_EPIP.xsd`**                | Defines the content model for the NeTExPublication element in the EPIP. Specifies elements and their order.
**`gml_combo_v3_2_1_simplified.xsd`**        | A simplified version of the GML 3.2.1 schema, removing optional elements and constraints for easier use.


A graphic interactive technical presentation is available [here]([https://github.com/NeTEx-CEN/NeTEx-Profile-EPIP/wiki/Graphic-Interactive-Technical-Presentation](https://github.com/TransmodelEcosystem/NeTEx-Profile-EPIP/wiki/Graphic-Interactive-Technical-Presentation).
