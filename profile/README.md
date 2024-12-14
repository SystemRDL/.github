![banner](https://raw.githubusercontent.com/SystemRDL/.github/main/profile/banner.jpg)

# Welcome to the SystemRDL open source community!

The goal of this GitHub organization is to build high-quality free and
open-source tools for control & status register (CSR) automation, and to
promote [Accellera's SystemRDL](https://www.accellera.org/downloads/standards/systemrdl)
as the language of choice for CSR design entry. [^1]

If you are new to SystemRDL, check out [this quick language tutorial](https://peakrdl.readthedocs.io/en/latest/systemrdl-tutorial.html).


## PeakRDL Command Line Application
PeakRDL is a command-line application that provides a ready-to-use register
automation toolchain.

See the [PeakRDL Documentation](http://peakrdl.readthedocs.io) for more details.


## Individual PeakRDL Components
If the command line tool isn't your style, you can use the PeakRDL components
individually. Each component is installable as a separate Python package and has
a documented API you can use to integrate it into your own custom workflow.

* [PeakRDL-regblock](https://peakrdl-regblock.readthedocs.io) generates synthesizable SystemVerilog RTL.
* [PeakRDL-html](https://github.com/SystemRDL/PeakRDL-html/blob/main/README.md) produces intuitive and dynamic HTML documentation.
* [PeakRDL-uvm](https://github.com/SystemRDL/PeakRDL-uvm/blob/main/README.md) generates a UVM register model.
* [PeakRDL-ipxact](https://peakrdl-ipxact.readthedocs.io) lets you import and export IP-XACT XML.
* [PeakRDL-cheader](https://peakrdl-cheader.readthedocs.io) outputs a software abstraction layer C header.

Be sure to also check out the growing list of tools [others in the community](https://peakrdl.readthedocs.io/en/latest/community.html) have made.

## SystemRDL language front-end compiler
Need to build something custom? Don't [invent your own](https://xkcd.com/927/)
janky input format - Use SystemRDL! The SystemRDL compiler front-end handles all
the heavy-lifting of processing the SystemRDL language so you don't have to.
The compiler provides a rich and intuitive Python API that you can use for your
own custom register automation.

See the [SystemRDL Compiler Documentation](http://systemrdl-compiler.readthedocs.io)
for more details.


## How do I use my proprietary register specs with PeakRDL?
If you are just ramping up the use of SystemRDL and still need to support other
internal register spec formats, it is pretty easy to create an importer to help
transition your workflow from non-SystemRDL spec formats.

To learn how this works, check out [the tutorial on PeakRDL importer plugins](https://peakrdl.readthedocs.io/en/latest/for-devs/importer-plugin.html).


[^1]: This SystemRDL GitHub group is not affiliated with Accellera.
