# ororatech-fuelmap-integration

# Customer Success Engineer - Geospatial API Integration Challenge
Proposed self-serve workflow and API design for integrating customer fuel maps into OroraTech’s fire spread simulation platform.
Includes presentation slides, architecture diagrams, and example metadata files.

## Contents
- `/presentation` → Main slide deck (PDF).
- `/examples` → Sample STAC file (STAC Item).
- `/diagrams` → UI,API Diagrams and UI Mockup.
- `LICENSE.md` → Custom evaluation-only license.

## Overview
My solution demonstrates how customers could
- Upload their private fuel maps via UI or API.
- Map their fuel classes to OroraTech’s canonical scheme.
- Normalize rasters into Cloud-Optimized GeoTIFF (COG).
- Catalog datasets with STAC metadata.
- Automatically use custom fuel maps in fire spread simulations,
   falling back to the global dataset where needed.
   
## Next Steps
- Prototype ingestion flow
- Pilot
- UI polish for non-technical users (dropdown class mapping)
- Explore ESRI integration

## This repository is provided solely for evaluation purposes 
as part of the OroraTech interview process. 
See [LICENSE.md](./LICENSE.md) for details.

## Use of GenAI
Parts of this repository (README structure, LICENSE wording, and explanatory summaries) were drafted with the assistance of generative AI tools. GenAI was used to create UI mockup drop-down table in slide 10 of the presentation.
