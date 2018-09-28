==========
RAIL Stack
==========

Step 1: Clone repo to local and prepare for the execution

.. code-block:: tcl


  git clone railstack
  alias rail source <railstack>/rail.run
  cd <railstack>
  ln -s ./rail_src1/rail.run .


Step 2: Checklist

  cds.lib: include proper lib path to tsmcN65, analogLib, basic, rail65
  
  

Step 3: Run command

.. code-block:: tcl


  rail -libname <dest_library> -v <verilog netlist>


For example:

.. code-block:: tcl


  rail -libname demo -v /home/cxchen2/workspace/VTS_T65_RAIL/import_netlist/bench_test.v




This command will do the following:

  create new library to <dest_library>
  
  create .xil config file 
  
  run verilog_in to create schematic
  

The following files will be created:

  dest_library: new library that includes new designed created by rail
  
  .xil config file: saved in ~/simulation/icc/option.xil
  
  
  
  
