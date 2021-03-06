Upstream SatAPI
====================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Upstream powers remote monitoring of water-centric entities. Currently our API allows:

- Register a GeoJSON polygon to be monitored. We will extract historical satellite imagery and create data products (NDVI, Upstream Soil Moisture, etc). Every time one of our satellites passes the monitored entity, we create new products and imagery automatically.

- Retrieve images. At any time you can make a web request to access all historical imagery of a monitored entity

- Retrieve data products. We currently provide NDVI, Upstream Soil Moisture, and various statistical products. More coming soon.


Getting Started
^^^^^^^^^^^^^^^

1. Contact `team@upstream.tech` to get set up with API credentials.


Indices
^^^^^^^

* :ref:`genindex`
* :ref:`search`
