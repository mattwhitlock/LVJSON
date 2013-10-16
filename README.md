LVJSON
======

JSON library for LabVIEW

Works similarly to "To Variant" and "Variant to Data" VIs.

Works with changing typedefs, therefore is much more flexible than any of the built-in To/From VIs.
For example, if a new item is added to a cluster, the JSON to Anything VI will still work, just
leaving default value in the output cluster.  This is especially useful with configuration files
based on typedefs. If a typedef is changed between revisions, the old configuration file will still
work.
