.. _structures:

##########################
df-structures descriptions
##########################

DF-structures is the core information on which DFHack depends.

It consists of XML files which describe the memory layout used by
Dwarf Fortress, which are translated into C++ header files and eventually
the named data structures that DFHack plugins and scripts can access.

The following documents describe how this process works:

.. toctree::
   :maxdepth: 2

   /library/xml/SYNTAX
   /library/xml/how-to-update

This experimental section includes the ``df-structures`` xml files in our
documentation, so you can read about what structures are available.

.. toctree::
   :maxdepth: 1
   :glob:

   /docs/_auto/structures/*
