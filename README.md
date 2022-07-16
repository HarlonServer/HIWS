# HIWS
Repository containing the files that make up the Harlon Integrated Wayfinding System (HIWS), a wayfinding system designed to be able to be reused across multiple operators.

## Repository Structure
This repository is made up of four folders:
* The **Experimental** folder contains prototypes from various stages of development of the HIWS, including those from Old Harlon.
* The **General** folder contains general public transport mode icons as well as Olympics-branded icons/signage.
* The **HN** folder contains logos and signage for **Harlonian National (HN)**, Harlon's national intercity rail operator.
* The **HT** folder contains logos and signage for **Harlon Transit (HT)**, Harlon City's public transport operator.

### Naming scheme
For the **HN** and **HT** folders, the vast majority of signage is named according to a coding scheme. There are several variants of this scheme.
* For **general** signage (i.e., informational, regulatory, warning, or promotional signage/graphics), the format is `XX-filename` - `XX` being the operator's abbreviated name/code - in Harlon's case, `HT` for Harlon Transit and `HN` for Harloninan National and `filename` being a good description of what the file is, for example, a "No Entry" sign could have the filename  `no-entry`.
* For **station-specific** signage, the format is `XX-YY-filename-Z` - `XX` again being the operator's abbreviated name/code, `YY` being the station code (please see the wiki for the list) and `filename` being the purpose of the signage. Usually this will be `entrance`, for station entrance signage. `Z` is the first letter of the transport mode name, for example `C` for Commuter.
* For **platform-specific** signage within stations, the format is `XX-YY-PlatformLineDirection`. `XX` and `YY` are the same as above, `Platform` is simply to denote that this is a platform-specific sign, `Line` is the line number the diagram is made for, for example, `M3`, and `Direction` is a geographical location to denote the direction of travel along the line the diagram is showing, i.e., `East`. `Line` and `Direction` are optional if the signage is just general platform signage, such as the station name signs used on Harlonian National station platforms.

### Station codes
For the full list of station codes, please see the wiki.
