## Process this file with automake to produce Makefile.in

AM_CPPFLAGS = $(MOD_CPPFLAGS)

AM_CFLAGS=$(AM_CXXFLAGS)

libgraph_tool_topologydir = $(MOD_DIR)/topology

libgraph_tool_topology_LTLIBRARIES = libgraph_tool_topology.la

libgraph_tool_topology_la_includedir = $(MOD_DIR)/include

libgraph_tool_topology_la_LIBADD = $(MOD_LIBADD)

libgraph_tool_topology_la_LDFLAGS = $(MOD_LDFLAGS)

libgraph_tool_topology_la_SOURCES = \
    graph_topology.cc \
    graph_isomorphism.cc \
    graph_subgraph_isomorphism.cc \
    graph_minimum_spanning_tree.cc \
    graph_dominator_tree.cc \
    graph_topological_sort.cc \
    graph_transitive_closure.cc \
    graph_components.cc \
    graph_distance.cc \
    graph_all_distances.cc \
    graph_planar.cc


libgraph_tool_topology_la_include_HEADERS = \
    graph_components.hh \
    graph_subgraph_isomorphism.hh