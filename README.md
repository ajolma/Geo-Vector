Geo-Vector
==========

Perl extension for geospatial vectors

Geo::Vector is a wrapper from module ogr (from GDAL). The intended
functionality of Geo::Vector is to enable data transfer between GDAL,
libral, and Gtk2::Ex::Geo (the GUI). GDAL is used to access possibly
huge geospatial vector files and libral is used to rasterization,
visualization, and other tasks. The GUI may be used to let the user
manipulate, visualize etc vector data.

INSTALLATION

To install this module type the following:

   perl Makefile.PL
   make
   make test
   make install

DEPENDENCIES

This module requires these other modules and libraries:

ogr from GDAL and libral

COPYRIGHT AND LICENCE

Copyright (C) 2005- by Ari Jolma

This library is free software; you can redistribute it and/or modify
it under the terms of Artistic License 2.0 (included as LICENCE).
