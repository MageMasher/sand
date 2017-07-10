## SAND
### Python code and notebooks to model System Architecture as a Network of Dependencies

SAND uses Python and Jupyter Notebooks to explore applications of representing system architecture as a network of engineered
artifacts and their interactions. For a software library, the artifacts are functions and the interactions are function
calls. For RESTful microservices, an artifact is a service and the interactions are API calls.

Imagine we have two microservices, A and B.

If B calls A, then B has a dependency on A.

The transpose of this relationship is that A impacts or influences B: Non backwards-compatible changes in A's interface that
B calls can break B.

A might not know anything about B.

This simple model proves to be extremely powerful in describing arbitrarily complicated system architectures.

## Installing

1. You'll also need a working Jupyter installation running on Python 3.

1. Start Jupyter in the `sandbook` directory:

```bash
git clone git@github.com:bobbyno/sandbook.git
cd sandbook
pip install -r requirements.txt
jupyter notebook
```

1. [Install Cytoscape](http://cytoscape.org/).
Start Cytoscape up and close the welcome screen.
You probably want to check "Don't show again" in the lower left.


## Getting Started

[Table of Contents](./Table%20of%20Contents.ipynb)


## Learn More

See a presentation from Bobby Norton at [Windy City GraphDB][wcgdb] for a more detailed introduction to the concept.

The Notebooks leverage [Cytoscape's RESTful API](http://apps.cytoscape.org/apps/cyrest) and [python-igraph](http://igraph.org/python/).


[wcgdb]: https://github.com/bobbyno/windy-city-graphdb-9-22-16/blob/master/windy_city_graphdb_presentation.ipynb


## License

Copyright © Bobby Norton and [Tested Minds, LLC](http://www.testedminds.com).

Released under the [Apache License, Version 2.0](./LICENSE.txt)
