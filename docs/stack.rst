==========
RAIL Stack
==========

git clone railstack

.. code-block:: tcl
alias rail source <railstack>/rail.run


Run command:

.. code-block:: tcl
rail -libname <dest_library> -v <verilog netlist>


For example:

.. code-block:: tcl
rail -libname demo -v /home/cxchen2/workspace/VTS_T65_RAIL/import_netlist/bench_test.v


This command will do the following:

  create new library to <dest_library>
  
  create .xil config file 
  
  run verilog_in to create schematic
  
