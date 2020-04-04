# Interior_and_Exterior
Private &amp; Public

Routing Protocols are interior gw protocols (IGPs) and exterior gw protocols(EGPs).



    Routing Protocols
           |
           |-----  Private to Interior Network ------|
           |                                         |------ Distance-vector -- RIP
           |                                         |                       -- IGRP
           |                                         |                       -- EIGRP
           |                                         |------ LSA |-------------- OSPF
           |                                                     |-------------- IS-IS
           |
           |
           |-----  Public to Exterior Network |------ EGP
                                              |------ BGP
