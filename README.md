# arcview_utilities
Utilities is an Avenue extension used in ArcView GIS that provides many useful functions for different purposes.

## Purpose
Utilities contains the following tools:
* Save projects with relative pathnames
* Copy view
* Select all graphic features
* Unselect all graphic features
* Buffer a polyline theme and square the buffer
* Pan to the defined coordinates
* Generate vector grid
* Convert gpx track to a LV03 point shape file (same as standalone tool https://github.com/ABoehlen/gpx2shp_lv03
* Georeference image
* Create world file
* Export point shape to ASCII file

## Background
ESRI's ArcView GIS is a rather old (1995 – 2002), but for many purposes still useful GIS application. Due to its age it's very fast on modern hardware and has full support for the still widely used vector data format _Shape_ (SHP).

Avenue is ArcView's built-in object oriented scripting language. "By using Avenue, you can customize the program and further extend its power", describes Amir H. Razavi the language's purpose in his 1999 book \[1\].

## System requirements
An ArcView GIS 3.x installation is required.

## Installation
Download the repository into your desired directory:

```
cd <directory>
git clone https://github.com/ABoehlen/arcview_utilities
```

* Copy Utilities.avx into the ext32 directory of your ArcView installation.
* Open ArcView GIS with a new empty project or with an existing one.
* Choose File –> Extensions
* Turn on the Extension Splinepolylines and close the Extension dialog again.
* In the View documents open an existing view or create a new one.
* In the button list of the View document GUI click on the new button "Utilities toolbar". The toolbar should open.

## License

This project is licensed under the MIT License - see the LICENSE file for details

***

## Literature
\[1\] Razavi, Amir H.: ArcView GIS Developer's Guide, 1999
