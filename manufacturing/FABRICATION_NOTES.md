# Fabrication notes — Rev C engineering prototype

| Item | CU-01 | SU-01 |
|---|---|---|
| Quantity for one system | 1 | 4 |
| Outline | 230 x 180 mm | 90 x 70 mm |
| Copper layers | 2 | 2 |
| Finished copper target | 70 um / 2 oz each side | 70 um / 2 oz each side |
| Substrate | FR-4, 1.6 mm nominal | FR-4, 1.6 mm nominal |
| Finish | Lead-free HASL or ENIG | Lead-free HASL or ENIG |
| Minimum trace | 0.15 mm | 0.18 mm routed |
| Minimum native pad gap | approximately 0.125 mm, verify actual Gerbers | verify actual Gerbers |
| Minimum plated drill / via diameter | 0.20 / 0.40 mm | 0.30 / 0.60 mm |
| Mounting | eight 3.2 mm NPTH holes | four 3.2 mm NPTH holes |

Use the Edge.Cuts Gerber as the routing outline. Units are millimetres; Gerbers and Excellon files use the same absolute origin. Plated and nonplated holes are separate. Do not mirror bottom files. Both boards carry only isolated low-voltage electronics; the finished enclosure carries external mains wiring/contacts separately.

Fabricator must confirm fine-pitch clearance/etch capability with 2 oz copper before production. Confirm soldermask webs and stencil apertures. CU QFN exposed-pad vias require a process controlling solder wicking (for example an assembler-approved via treatment and paste design). F.Paste is exported from library footprints; assembly process review is still required. Do not automatically fill every plated through-hole.

Per-board fabrication ZIPs contain this note and Gerber/drill files. PDF drill maps are reference documents. The full hardware ZIP additionally contains editable source, assembly and validation documents.
