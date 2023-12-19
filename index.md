This repository contains a curated list of 3rd party contributions to VCML not part of the [MachineWare GmbH](https://www.machineware.de/) owned and maintained set of models and components.

## VCML

[VCML (Virtual Components Modeling Library)](https://github.com/machineware-gmbh/vcml) is a utility library for [SystemC/TLM](https://systemc.org/). 
It contains a set of SystemC/TLM modeling primitives and component models that can be used to swiftly assemble system level simulators for embedded systems, i.e. Virtual Platforms. 
Based on these design primitives, TLM models for frequently deployed components are also provided, such as memories, memory-mapped buses, UARTs, etc.

vcml is owned and maintained by [MachineWare GmbH](https://www.machineware.de/).

## How to Contribute

Contribution to VCML can be submitted as patchfiles by email via the [CONTACT US](https://www.machineware.de/) process of MachineWare.


### Virtual Platforms 

| Virtual Platform | Description| License |
|-------------------|-|-|
| [AVP64](https://github.com/aut0/avp64) | An ARMv8 virtual platform based on QEMU and VCML. AVP64 uses [Unicorn engine](https://www.unicorn-engine.org/) for its qemu integration. This VP comes with a bootable Linux example. | MIT |
|[or1kmvp](https://github.com/janweinstock/or1kmvp) | or1kmvp is an OpenRISC 1000 Multicore Virtual Platform. It comes with a configurable number of processors. It is fast enough to run Linux with an interactive command line. | Apache-2.0 |

### Models

#### Peripheral Models

|Models| Description| License |
|-|-|-|
|[vcml-nvdla](https://github.com/aut0/vcml-nvdla)|A VCML integration of [Nvidia's NVDLA SystemC model](https://github.com/nvdla/vp)|Apache-2.0

#### Processor Models

|Models| Description| License |
|-|-|-|
|[or1kiss](https://github.com/janweinstock/or1kiss)|An OpenRISC 1000 Instruction Set Simulator|Apache-2.0

<p style="text-align: center;">
<a href="https://www.machineware.de/pages/about.html"> About Us </a>
-
<a href="https://www.machineware.de/pages/imprint.html"> Impressum </a>
</p>
