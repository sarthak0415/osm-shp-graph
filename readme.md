steps-

1. download osm from osm website
2. convert to shaplite db(in qgis -> vector -> osm -> import)
3. convert db to shapefile (in qgis -> vector -> osm -> export)
4. import shape file to network graph

	a. import networkx as nx
	b. import matplotlib.pyplot as plt
	c. G = nx.read_shp('iiit_map.shp')
	d. nx.draw(G)
	e. plt.show()

	f. if networkx is missing intsall using pip install networkx==2.0
	g. if gdal is missing install using https://hackernoon.com/install-python-gdal-using-conda-on-mac-8f320ca36d90
	h. install qgis
