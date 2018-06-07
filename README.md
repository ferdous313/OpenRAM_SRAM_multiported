# OpenRAM_SRAM_multiported

 MultiPorted SRAM:


  1.The multiported sram is coded in OpenRAM/compiler/multiport.py

  2. The test is coded in OpenRAM/tests/ 04_multiport_test.py and can be executed using the command:
    python2.7 04_multiport_test.py 
    python2.7 04_multiport_test.py -t scn3me_subm

  3. The Read_Write ports and Read_Only_ports are reconfigurable in the 
     OpenRAM/tests/ 04_multiport_test.py script as,

      tx = multiport.multiport(name="a_multiport",Read_Write_ports=4, Read_Only_ports=2,nmos_width=2 * tech.drc["minwidth_tx"]

  4. Wide range of variation and combinations of Read_Write_ports and Read_Only_ports are working in this program,
