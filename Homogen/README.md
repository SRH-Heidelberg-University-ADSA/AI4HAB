**Goal of HOMOGEN Agent**

To autonomously:
1. Identify and collect raw HAB-relevant data from diverse sources
2. Detect mismatches in formats, semantics, or resolution
3. Harmonize them into a standard structure
4. Output usable, semantically-aligned data for downstream agents (e.g., FORECAST)

**Perceive**
HOMOGEN should monitor and retrieve:
1.New data from sources (e.g., API feeds, satellite updates)
2.Changes in source schema or variable names
3.Missing data periods

**Reason**
1.Matches variables (e.g., “Chla” = chlorophyll-a)
2.Decides on unit conversions (e.g., ppb → µg/L)
3. Resolves geospatial inconsistencies
4. Infers interpolation strategies or data fusion techniques

**Act**
1. Data transformations (cleaning, merging, aligning)
2.Semantic tagging
3.Delivery to a shared storage system or message broker

