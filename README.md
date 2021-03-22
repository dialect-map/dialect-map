# Dialect map 🗺️

- PI: Kyle Cranmer
- Main developer: Sinclert Pérez
- Research Assistant: Jiayi Du
- NLP Data Scientist: Quynh M. Nguyen


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

- [Project UI][dialect-map-ui]: the front-end interface.
- [Project Core][dialect-map-core]: the database core package.
- [Project Data][dialect-map-data]: the Arxiv-related static data.
- [Project Private API][dialect-map-private-api]: the private access API.
- [Project Public API][dialect-map-public-api]: the public access API.
- [Project Computing][dialect-map-computing]: the metrics computing pipeline.


## Additional resources

- Similar project: https://blog.paperscape.org
- Front code: https://github.com/paperscape/paperscape-mapclient 
- Back code: https://github.com/paperscape/paperscape-backend 


[dialect-map-ui]: https://github.com/dialect-map/dialect-map-ui
[dialect-map-core]: https://github.com/dialect-map/dialect-map-core
[dialect-map-data]: https://github.com/dialect-map/dialect-map-data
[dialect-map-private-api]: https://github.com/dialect-map/dialect-map-private-api
[dialect-map-public-api]: https://github.com/dialect-map/dialect-map-public-api
[dialect-map-computing]: https://github.com/dialect-map/dialect-map-computing
