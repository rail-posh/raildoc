.. Read the Docs Template documentation master file, created by
   sphinx-quickstart on Tue Aug 26 14:19:49 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

RAIL: Resilient Analog Instance Language Enabled Mixed-Signal Circuits
======================================================================

It is an open source project for integrated circuits design. 
The project first releases a 65nm-based RAIL cell library and a tutorial to complete a simple RAIL design on September 2018.

The motivation of the RAIL project is,

- **to accelerate the analog/mixed-signal (AMS) designs**. Traditional analog/mixed-signal integrated circuit design exploits a fully custom flow. In other words, all manual works make it time-consuming, thereby increasing the design cycle time. RAIL ameliorates the methodology for design by introducing a verilog-like topology description language (TDL) and generates its behavior/schematic/layout automatically.

- **to enable process-portable design methodology**. Traditional AMS designs are highly process-dependent because of the performance requirements of analog blocks in a new process, making it one of the major bottlenecks for analog designers to migrate their design across different technologies. This attribute seriously constraint the AMS to be an open source technology. Conventionally, even an IP is released, analog designers developing under other processes still need to put comparable efforts to redesign it. RAIL is used to alleviate the burden by the TDL and the automatic flow. 

- **to exploit new methodolgy for digitized AMS design**. In the past decades, advances in integrated circuit technology make fabrication processes very suitable for digital designs. Reducing the amount of analog circuitry can improve the scalability of these mixed-signal integrated circuits. Today's PLL contains digital filters and DCOs, rather than the charge-pump and analog filters. The architecture of ADCs are more on SAR-based, rather than on pipelined based. The basic cells of analog blocks are no longer amplifier now, because of the challenges in traditional analog design flow on advanced technologies. The RAIL project decides to develop a new methodology to embrace the trend.



RAIL Project Repo link
----------------------
Release 0.1: https://github.com/rail-posh/rail65

Contents
--------

.. toctree::
   :maxdepth: 2
      
   railib/index
   compiler
   ip

