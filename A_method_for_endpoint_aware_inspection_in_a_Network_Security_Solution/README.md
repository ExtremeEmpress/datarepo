# JA3 case study data set for IEEE Access article "A method for endpoint aware inspection in a Network Security Solution"

This repository contains the source data for the proof-of-concept case study for the IEEE Access article "A method for endpoint aware inspection in a Network Security Solution", Digital Object Identifier 10.1109/ACCESS.2022.3170456. Early Access: https://ieeexplore.ieee.org/document/9762961

The data is in csv format, and contains the JA3 hash fingerprint as well as the endpoint application information.
* source_db.csv: Contains the JA3 hash fingerprints and associated endpoint applications collected from the Source group during the Generate and Store phases.
* source_during_utilise_db.csv: Contains the JA3 hash fingerprints and associated endpoint applications collected from the Source group during the Utilise phase.
* win_util_db.csv: Contains the JA3 hash fingerprints and associated endpoint applications collected from all Windows machines in the Target group during the Utilise phase. This includes the machines in the Source group.
* linuxes_util_db.csv: Contains the JA3 hash fingerprints and associated endpoint applications collected from the Linux machines in the Target group during the Utilise phase.

This data set is licensed under the CC-BY License: https://creativecommons.org/licenses/by/4.0/
