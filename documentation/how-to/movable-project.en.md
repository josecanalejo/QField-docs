---
title: Portable project
tx_slug: documentation_how-to_movable-project
---

# Portable project

To manually synchronise your QGIS project, you will need a portable
version of your .qgs file. Portable means that all paths are relative
and datasets are reachable from the device.


## Configure a portable project
:material-monitor: Desktop preparation

Check that
*Project > Project Properties > General > Save paths*
is set to *Relative* and that all required data
files are in the same folder like the .qgs file or in a subfolder.

For increased productivity, we suggest having a look at
`qfieldcloud` and `qfieldsync`
