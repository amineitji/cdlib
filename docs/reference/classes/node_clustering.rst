***************
Node Clustering
***************

^^^^^^^^
Overview
^^^^^^^^

.. currentmodule:: nclib
.. autoclass:: NodeClustering
    :members:
    :inherited-members:

^^^^^^^
Methods
^^^^^^^

Data transformation and I\O
---------------------------

.. autosummary::

    NodeClustering.to_json
    NodeClustering.to_node_community_map

Evaluating Node Clustering
--------------------------

.. autosummary::

    NodeClustering.link_modularity
    NodeClustering.normalized_cut
    NodeClustering.internal_edge_density
    NodeClustering.average_internal_degree
    NodeClustering.fraction_over_median_degree
    NodeClustering.expansion
    NodeClustering.cut_ratio
    NodeClustering.edges_inside
    NodeClustering.conductance
    NodeClustering.max_odf
    NodeClustering.avg_odf
    NodeClustering.flake_odf
    NodeClustering.triangle_participation_ratio
    NodeClustering.newman_girvan_modularity
    NodeClustering.erdos_renyi_modularity
    NodeClustering.modularity_density
    NodeClustering.z_modularity
    NodeClustering.surprise
    NodeClustering.significance



Comparing Node Clusterings
--------------------------

.. autosummary::

    NodeClustering.normalized_mutual_information
    NodeClustering.overlapping_normalized_mutual_information
    NodeClustering.omega
    NodeClustering.f1
    NodeClustering.nf1
    NodeClustering.adjusted_rand_index
    NodeClustering.adjusted_mutual_information
    NodeClustering.variation_of_information
