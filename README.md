# Data Science: Dialect map

- PI: Kyle Cranmer
- Student: Jiayi Du
- Advisor: Sinclert Pérez


## Project description
It is well known that terminology and jargon are one of the barriers to communication across disciplines.
The same mathematical concepts have different names (eg. Gaussian Processes & Krigging; ELBO and free energy; etc.).

Similarly, dialects vary geographically.
Sometimes geographical maps that show how different words are used for the same concept are very helpful.
I propose to make a similar map, where the geographic map is replaced with a 2-d visualization (embedding) of literature
and then overlay how a certain concept is named on this fixed 2-d representation of the domain literature.

Initially this would be done with a hand created dictionary and displayed with an interactive website.
Stretch goals for the project would include using NLP to automate parts of this process.


## Project repositories

- [Project UI][dialect-map-ui]: the front-end interface
- [Project Server][dialect-map-server]: the database access point
- [Project Retrieval][dialect-map-retrieval]: the paper retrieval and analytic part

## Additional resources

- Similar project: https://blog.paperscape.org
- Front code: https://github.com/paperscape/paperscape-mapclient 
- Back code: https://github.com/paperscape/paperscape-backend 
- Data: https://github.com/paperscape/paperscape-data 


[dialect-map-ui]: https://github.com/ds3-nyu-archive/ds-dialect-map-ui
[dialect-map-server]: https://github.com/ds3-nyu-archive/ds-dialect-map-server
[dialect-map-retrieval]: https://github.com/ds3-nyu-archive/ds-dialect-map-retrieval
