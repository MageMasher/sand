## sandbook

This is a collection of Jupyter Notebooks to visualize and analyze system architecture as a network.

See a presentation from [Windy City GraphDB](https://github.com/bobbyno/windy-city-graphdb-9-22-16/blob/master/windy_city_graphdb_presentation.ipynb) for a more detailed introduction to the concept.

The Notebooks leverage [Cytoscape's RESTful API](http://apps.cytoscape.org/apps/cyrest) and [python-igraph](http://igraph.org/python/).


## Getting Started

* []Install Cytoscape

* `pip install -r requirements.txt`

* `jupyter notebook`

Use the [Exploratory Workflow](./exploratory_workflow.ipynb) to begin your analysis and create an initial visualization.

Use the [Iteration Workflow](./iteration_workflow.ipynb) to iterate on a visualization after the network has changed and you want to update the visualization.

The project contains an example using data from [lein-topology](https://github.com/testedminds/lein-topology).

Produce an edgelist of dependencies for your own analysis in the same format to use these notebooks for your own architecture analysis.