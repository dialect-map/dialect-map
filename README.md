# Dialect map 💬

- PI: Kyle Cranmer
- Engineer: Sinclert Pérez
- Data Scientist: Quynh M. Nguyen


## Project description
It is well known that terminology and jargon are one of the barriers to communication across disciplines.
The same mathematical concepts have different names (eg. _ELBO and free energy_).

Similarly, dialects vary geographically. Sometimes geographical maps that show how different words are used
for the same concept are very helpful. Dialect map proposes to make a similar map, where the geographic map 
is replaced with a 2-D visualization (embedding) of literature and then overlays how a certain concept
is named on this fixed 2-D representation of the domain literature.

This would be done with a hand created list of jargon terms, displayed in an interactive website.

A more complete description of the project could be found on [NYU Data Science Blog](https://nyudatascience.medium.com/dialect-map-jargon-dialects-across-science-domains-908a62ead9ad). 
## Overview

![ui-overview][image-interface]


## Public repositories

- [Project UI][repo-dialect-map-ui]: the public web interface.
- [Project Data][repo-dialect-map-data]: the community sourced jargons.


## Architecture
For details about the software deployment and interconnection, check out the [architecture docs][docs-architecture].


## Additional resources

- Similar project: https://blog.paperscape.org
- Front code: https://github.com/paperscape/paperscape-mapclient 
- Back code: https://github.com/paperscape/paperscape-backend 


[repo-dialect-map-ui]: https://github.com/dialect-map/dialect-map-ui
[repo-dialect-map-data]: https://github.com/dialect-map/dialect-map-data
[docs-architecture]: docs/architecture.md
[image-interface]: images/web-interface.png
