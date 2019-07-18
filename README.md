# hw_check
a hardware check script only for physical servers

## support hardware type: 
cpu mem nic hdd nvme raid


Usage:
----
        ./hwinfo.run  <hardware name>


example:

        ./hwinfo.run mem
        
        mem_report :                
        +---------+---------+-------------+-------------------------+--------+-------------------+
        | size    | speed   | slot        | channel                 | vendor | product_version   | 
        +---------+---------+-------------+-------------------------+--------+-------------------+
        | 16384MB | 2400MHz | CPU0_DIMMA0 | A0_Node0_Channel0_Dimm0 | Micron | 18ASF2G72PZ-2G3B1 | 
        +---------+---------+-------------+-------------------------+--------+-------------------+
        | 16384MB | 2400MHz | CPU0_DIMMB0 | B0_Node0_Channel1_Dimm0 | Micron | 18ASF2G72PZ-2G3B1 | 
        +---------+---------+-------------+-------------------------+--------+-------------------+
        | 16384MB | 2400MHz | CPU0_DIMMC0 | C0_Node0_Channel2_Dimm0 | Micron | 18ASF2G72PZ-2G3B1 | 
        +---------+---------+-------------+-------------------------+--------+-------------------+
        | 16384MB | 2400MHz | CPU0_DIMMD0 | D0_Node0_Channel3_Dimm0 | Micron | 18ASF2G72PZ-2G3B1 | 
        +---------+---------+-------------+-------------------------+--------+-------------------+
        | 16384MB | 2400MHz | CPU1_DIMME0 | E0_Node1_Channel0_Dimm0 | Micron | 18ASF2G72PZ-2G3B1 | 
        +---------+---------+-------------+-------------------------+--------+-------------------+
        | 16384MB | 2400MHz | CPU1_DIMMF0 | F0_Node1_Channel1_Dimm0 | Micron | 18ASF2G72PZ-2G3B1 | 
        +---------+---------+-------------+-------------------------+--------+-------------------+
        | 16384MB | 2400MHz | CPU1_DIMMG0 | G0_Node1_Channel2_Dimm0 | Micron | 18ASF2G72PZ-2G3B1 | 
        +---------+---------+-------------+-------------------------+--------+-------------------+
        | 16384MB | 2400MHz | CPU1_DIMMH0 | H0_Node1_Channel3_Dimm0 | Micron | 18ASF2G72PZ-2G3B1 | 
        +---------+---------+-------------+-------------------------+--------+-------------------+
