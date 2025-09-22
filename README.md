# ororatech-fuelmap-integration

# Customer Success Engineer - Geospatial API Integration Challenge
Proposed self-serve workflow and API design for integrating customer fuel maps into OroraTech’s fire spread simulation platform.
Includes presentation slides, architecture diagrams, and example metadata files.

## Contents
- `/presentation` → Main slide deck (PDF).
- `/examples` → Sample files (STAC Item).
- `/diagrams` → UI and API Diagrams.
- `LICENSE.md` → Custom evaluation-only license.

## Overview
This solution demonstrates how customers could:
1. Upload their private fuel maps via UI or API.
2. Map their fuel classes to OroraTech’s canonical scheme.
3. Normalize rasters into Cloud-Optimized GeoTIFF (COG).
4. Catalog datasets with STAC metadata.
5. Automatically use custom fuel maps in fire spread simulations,
   falling back to the global dataset where needed.
   
## Next Steps
- Prototype ingestion flow
- UI polish for non-technical users (dropdown class mapping)
- Explore ESRI integration

## This repository is provided solely for evaluation purposes 
as part of the OroraTech interview process. 
See [LICENSE.md](./LICENSE.md) for details.

## Use of GenAI
Parts of this repository (e.g., README structure, LICENSE wording, and explanatory summaries) were drafted with the assistance of generative AI tools.  GenAI was used to create UI mock up drop-down table in slide 10 of presentation.
