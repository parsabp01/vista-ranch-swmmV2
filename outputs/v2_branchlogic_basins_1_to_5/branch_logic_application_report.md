# Branch Logic Application Report

- branch_logic readable
- terminal_notes readable
- HYDROLOGY readable
- source lookup overrides file present: False
- AC overrides file present: False
- Crown/soffit matching attempted for conduits; invert fallback used when crown match would produce negative slope.
## Source Readability
- branch_logic: readable
- terminal_notes: readable
- HYDROLOGY: readable

## Method
- Topology from branch_logic columns B/C for basins 1-5.
- Attributes from HYDROLOGY columns B/C/R/AA/AC/S/V (rows <= 684).
- DI TABLE ignored for hydraulics.
- branch_logic B/C used as authoritative topology for basins 1-5.
- HYDROLOGY B/C/R/AA/AC/S/V used as authoritative attributes (rows <= 684).
- DI TABLE not used.

## Non-blocking assumptions
- Inlet lateral = 5 ft, slope 0.002, diameter 24 in.
- Inlet rim inherited from receiving junction rim.
- ID normalization and default TOP orientation where needed.

