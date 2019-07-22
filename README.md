# WellRadPy

WellRadPy (Well Radius Python) is a Python package for calculating the radius of influence and radius of investigation of wells. These quantities frequently need to be estimated in well hydraulics and aquifer testing.

There are various ways by which radius of influence and radius of investigation may be precisely defined. Accordingly, a large number of methods have been proposed for estimating radius of influence and radius of investigation. This package implements most existing methods.

The calculations rely on major simplifying assumptions. Specifically: 2D (horizontal) confined flow, infinite domain, homogeneous hydraulic properties, single-porosity media, and fully-penetrating well. Also, only single-phase Newtonian fluids that flow according to Darcy’s law are considered.

A paper will (hopefully) soon be published with all the details.

## Usage

WellRadPy is simple and its use is straightforward. There are just as many functions as there are ways to precisely define radius of influence and radius of investigation.

The folder ``/examples`` contains a script where all the functions are exemplified.

## Installation

BLABLA.

WellRadPy depends on the Python package NumPy, which will be automatically installed if you choose to [REFER TO ABOVE].

## Authors

* **Etienne Bresciani** ([ebrescia](https://github.com/etiennebresciani))

## License

This project is licensed under the MIT License &ndash; see the [LICENSE.txt](LICENSE.txt) file for details.

## Acknowledgments

* Korea Ministry of Science and ICT through the Korea Research Fellowship program of the National Research Foundation of Korea (2016H1D3A1908042)
* Korea Institute of Science and Technology (KIST) through the Future Research Program (2E29660)
* Korea Ministry of Environment (MOE) through the Subsurface Environment Management (SEM) Project of the Korea Environment Industry & Technology Institute (KEITI) (2018002440006)
