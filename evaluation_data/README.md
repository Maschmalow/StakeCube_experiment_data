This folder contains all the data from StakeCube's evaluation.
The folder 'out' contains the raw data. Each folder in 'out' is a run with timestand, node count and security parameters in the name. Their content is organised as follow:
 * 'dump.json' contains all the run data for all nodes. It's a single list where each element is a the list of metadata output of all nodes. Note that although metadata may have a "node" item, it is not an identifier and nodes are only identified by their position in the list.
 * 'all_blocs.json' is the metrics for each bloc, i.e., "dump.json" aggregated over nodes.
 * 'aggregated.json' is the metrics for the run, i.e., "all_blocs.json" aggregated over blocks.
 * 'parameters.json' is the run's parameters.
 
Finally, all this data is gathered into the charts at top level. For readability, "B=10" couple have trimmed versions that has been use for plotting in the paper.
