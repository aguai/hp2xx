# hp2xx
original from 
http://ftp.gnu.org/gnu/hp2xx/hp2xx-3.4.4.tar.gz	  
trying to figure out how to build under OSX
## Introduction to hp2xx
The hp2xx program is a versatile tool to convert vector-oriented graphics data given in Hewlett-Packard's HP-GL plotter language into a variety of popular graphics formats, both vector- and raster-oriented.

The various supported output formats include Encapsulated PostScript (EPS), PCX, IMG, and several formats intended to facilitate the generation of graphics within TeX documents. In addition, hp2xx output is printable on the HP Laserjet/Deskjet printer series, and it may be used as a HP-GL previewer on many platforms, e.g., X11 and DOS (VGA).

hp2xx first converts all HP-GL data into pure vectors and buffers them internally. It then converts these vectors into a specified output format (vector modes), or rasterizes them (raster modes) on an internal bitmap. In raster modes, hp2xx then translates the bitmap into the output format.

