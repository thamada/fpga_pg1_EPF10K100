#!Time-stamp: <2000-02-28 14:49:57 hamada>

- FPGA for computing
-- ALTERA EPF10K100GC503-4

- FPGA for I/O
-- ALTERA EPF10K20RC208-4

- MAX+plus II Compiler Version 8.0 6/12/97


AHDL: Altera Hardware Description Language

--------

[reference paper 1](http://dl.acm.org/citation.cfm?id=795780)

[reference paper 2](https://arxiv.org/abs/astro-ph/9906419)

--------
Project Information                                e:\usr\hamada\intf\intf.rpt

MAX+plus II Compiler Report File
Version 8.0 6/12/97
Compiled: 10/19/97 12:10:08

Copyright (C) 1991-1997 Altera Corporation
Any megafunction design, and related net list (encrypted or decrypted),
support information, device programming or simulation file, and any other
associated documentation or information provided by Altera or a partner
under Altera's Megafunction Partnership Program may be used only to
program PLD devices (but not masked PLD devices) from Altera.  Any other
use of such megafunction design, net list, support information, device
programming or simulation file, or any other related documentation or
information is prohibited for any other purpose, including, but not
limited to modification, reverse engineering, de-compiling, or use with
any other silicon devices, unless such use is explicitly licensed under
a separate agreement with Altera or a megafunction partner.  Title to
the intellectual property, including patents, copyrights, trademarks,
trade secrets, or maskworks, embodied in any such megafunction design,
net list, support information, device programming or simulation file, or
any other related documentation or information provided by Altera or a
megafunction partner, remains with Altera, the megafunction partner, or
their respective licensors.  No other licenses, including any licenses
needed under any third party's intellectual property, are provided herein.



***** Project compilation was successful


PROGRAPE Controller


** DEVICE SUMMARY **

Chip/                     Input Output Bidir  Memory  Memory  			 LCs
POF       Device          Pins  Pins   Pins   Bits % Utilized  LCs  % Utilized

intf      EPF10K20RC208-4  32     39     0    0         0  %    424      36 %

User Pins:                 32     39     0  



Project Information                                e:\usr\hamada\intf\intf.rpt

** PROJECT COMPILATION MESSAGES **

Warning: Line 41, File e:\usr\hamada\intf\intf.tdf:
   Symbolic name "piocom16" was declared but never used
Warning: Line 41, File e:\usr\hamada\intf\intf.tdf:
   Symbolic name "piocom14" was declared but never used
Warning: Line 41, File e:\usr\hamada\intf\intf.tdf:
   Symbolic name "piocom15" was declared but never used
Warning: Line 41, File e:\usr\hamada\intf\intf.tdf:
   Symbolic name "piocom19" was declared but never used
Warning: Line 41, File e:\usr\hamada\intf\intf.tdf:
   Symbolic name "piocom20" was declared but never used
Warning: Ignored unnecessary INPUT pin 'hl_data27'
Warning: Ignored unnecessary INPUT pin 'hl_data26'
Warning: Ignored unnecessary INPUT pin 'hl_data25'
Warning: Ignored assignment on carry node ':1038' to intf@LC5_A3, assignment on register node 'ncnt5' to intf@LC1_A3 has precedence
Warning: Ignored assignment on carry node ':1027' to intf@LC1_A3, assignment on register node 'ncnt3' to intf@LC6_A1 has precedence
Warning: Ignored assignment on carry node ':1022' to intf@LC8_A1, assignment on register node 'ncnt2' to intf@LC4_A1 has precedence
Info: Trying to find new partition/fit after discarding assignments as requested with the Partitioner/Fitter Status dialog box
Warning: Node ':106' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node ':292' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1011~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1011~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1016~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1016~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1032~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1032~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1105~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1107~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1109~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1111~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1113~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1115~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1117~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1119~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1123~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1125~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1129~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1166~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1166~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1166~3' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1314~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1320~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1326~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1328~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1332~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1336~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1342~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1348~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1350~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1362~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1362~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1362~3' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1381~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~1395~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~309~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~312~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~323~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~368~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~368~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~368~3' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~540~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~546~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~552~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~554~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~558~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~562~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~568~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~574~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~576~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~580~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~582~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~586~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~604~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~604~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~647~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~650~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~653~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~656~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~707~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~707~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~707~3' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~855~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~861~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~867~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~869~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~873~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~877~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~883~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~889~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~891~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~912~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~912~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~961~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~961~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~961~3' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~961~4' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~995~1' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~995~2' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~995~3' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem
Warning: Node '~995~4' has assignments but doesn't exist or is a primitive array -- edit the project's ACF to fix the problem


Project Information                                e:\usr\hamada\intf\intf.rpt

** PIN/LOCATION/CHIP ASSIGNMENTS **

                  Actual                  
    User       Assignments                
Assignments   (if different)     Node Name

intf@LC2_E14     intf@LC1_D16     adr_drram0
intf@LC7_E23     intf@LC6_B15     adr_drram1
intf@LC1_E23     intf@LC3_B15     adr_drram2
intf@LC6_E18     intf@LC7_B3      adr_drram3
intf@LC8_D2      intf@LC6_B8      adr_drram4
intf@LC6_D2      intf@LC7_B6      adr_drram5
intf@LC5_D2      intf@LC8_B3      adr_drram6
intf@LC2_F9      intf@LC2_F6      adr_drram7
intf@LC1_F9      intf@LC2_F9      adr_drram8
intf@LC3_F10     intf@LC3_F5      adr_drram9
intf@LC2_F16     intf@LC3_F6      adr_drram10
intf@LC5_F17     intf@LC8_F16     adr_drram11
intf@LC4_F17     intf@LC4_F13     adr_drram12
intf@LC4_F16     intf@LC2_F16     adr_drram13
intf@LC4_E14     intf@LC5_E24     adr_drreg0
intf@LC8_D24     intf@LC3_C19     adr_drreg1
intf@LC6_D5      intf@LC5_C18     adr_drreg2
intf@LC8_D5      intf@LC6_C12     adr_drreg3
intf@LC1_E6      intf@LC6_C19     adr_drreg4
intf@LC6_E1      intf@LC2_E1      adr_drreg5
intf@LC5_E1      intf@LC7_E4      adr_drreg6
intf@LC2_E6      intf@LC3_E15     adr_drreg7
intf@LC5_E7      intf@LC1_E19     adr_drreg8
intf@LC3_E7      intf@LC4_E15     adr_drreg9
intf@LC1_E14     intf@LC1_E24     adr_dwreg0
intf@LC2_C9      intf@LC1_E22     adr_dwreg1
intf@LC7_C12     intf@LC7_E9      adr_dwreg2
intf@LC8_C12     intf@LC6_E9      adr_dwreg3
intf@LC3_C9      intf@LC2_E5      adr_dwreg4
intf@LC3_E8      intf@LC8_E8      adr_dwreg5
intf@LC6_C4      intf@LC5_E8      adr_dwreg6
intf@LC4_E3      intf@LC4_E22     adr_dwreg7
intf@LC8_E3      intf@LC7_E22     adr_dwreg8
intf@LC1_E8      intf@LC5_E20     adr_dwreg9
intf@LC4_E15     intf@LC6_F13     bncnt_drram0
intf@LC1_D20     intf@LC4_D5      bncnt_drram1
intf@LC5_D12     intf@LC5_B7      bncnt_drram2
intf@LC7_D12     intf@LC7_B7      bncnt_drram3
intf@LC8_D11     intf@LC1_B8      bncnt_drram4
intf@LC7_D11     intf@LC8_B6      bncnt_drram5
intf@LC6_D11     intf@LC1_B10     bncnt_drram6
intf@LC2_D20     intf@LC4_B15     bncnt_drram7
intf@LC6_D20     intf@LC3_B14     bncnt_drram8
intf@LC4_D22     intf@LC4_B14     bncnt_drram9
intf@LC5_D22     intf@LC3_B8      bncnt_drram10
intf@LC2_E15     intf@LC6_E24     bncnt_drreg0
intf@LC2_B17     intf@LC2_C16     bncnt_drreg1
intf@LC3_B10     intf@LC5_C3      bncnt_drreg2
intf@LC5_B4      intf@LC8_C3      bncnt_drreg3
intf@LC4_B4      intf@LC1_C19     bncnt_drreg4
intf@LC5_B8      intf@LC7_C2      bncnt_drreg5
intf@LC6_B8      intf@LC5_C2      bncnt_drreg6
intf@LC7_B17     intf@LC5_C16     bncnt_drreg7
intf@LC3_B17     intf@LC4_C16     bncnt_drreg8
intf@LC5_B16     intf@LC3_C24     bncnt_drreg9
intf@LC3_B16     intf@LC4_C24     bncnt_drreg10
intf@LC6_E15     intf@LC3_E20     bncnt_dwreg0
intf@LC6_C15     intf@LC3_D15     bncnt_dwreg1
intf@LC5_C24     intf@LC6_D10     bncnt_dwreg2
intf@LC6_C24     intf@LC5_D10     bncnt_dwreg3
intf@LC3_C15     intf@LC4_D4      bncnt_dwreg4
intf@LC8_C23     intf@LC5_D11     bncnt_dwreg5
intf@LC5_C23     intf@LC6_D11     bncnt_dwreg6
intf@LC2_C19     intf@LC2_D22     bncnt_dwreg7
intf@LC1_C19     intf@LC1_D22     bncnt_dwreg8
intf@LC5_C15     intf@LC4_D15     bncnt_dwreg9
intf@LC5_C19     intf@LC5_D21     bncnt_dwreg10
intf@LC4_A15     intf@LC3_A6      ce
intf@LC6_A15     intf@LC1_A6      cstart
intf@LC5_F12     intf@LC3_F18     cs0
intf@LC6_F12     intf@LC5_F18     cs1
intf@LC2_B21     intf@LC6_A4      dmaack_drns
intf@LC8_B21     intf@LC4_A4      dmaack_drram
intf@LC1_E16     intf@LC3_A4      dmaack_drreg
intf@LC3_B22     intf@LC1_A5      dmar_drns
intf@LC6_B22     intf@LC8_B2      dmar_drram
intf@LC4_B22     intf@LC7_B5      dmar_drram0
intf@LC8_B11     intf@LC2_C8      dmar_drreg
intf@LC6_F24     intf@LC6_D17     d_write0
intf@LC7_F24     intf@LC5_D17     d_write1
intf@LC8_F24     intf@LC2_D17     d_write2
intf@149                          hl_calc_sts
intf@79                           hl_clk
intf@186                          hl_data0
intf@180                          hl_data1
intf@161                          hl_data2
intf@75                           hl_data3
intf@189                          hl_data4
intf@158                          hl_data5
intf@74                           hl_data6
intf@207                          hl_data7
intf@8                            hl_data8
intf@208                          hl_data9
intf@183                          hl_data10
intf@182                          hl_data11
intf@184                          hl_data12
intf@80                           hl_data13
intf@17                           hl_data14
intf@16                           hl_data15
intf@40                           hl_data16
intf@18                           hl_data17
intf@115                          hl_data18
intf@116                          hl_data19
intf@36                           hl_data20
intf@45                           hl_data21
intf@46                           hl_data22
intf@47                           hl_data23
intf@53                           hl_data24
intf@11                           hl_data28
intf@159                          hl_data29
intf@114                          hl_data30
intf@113                          hl_data31
intf@78                           hl_dma_ack
intf@13                           hl_dma_r
intf@55                           hl_dma_w
intf@56                           hl_d_read
intf@205                          hl_d_write
intf@44                           hl_io_req
intf@LC2_F13     intf@LC3_F23     io_req0
intf@LC4_F13     intf@LC4_F23     io_req1
intf@LC1_F3      intf@LC5_F23     io_req2
intf@LC3_F3      intf@LC6_F23     io_req3
intf@LC2_F3      intf@LC7_F23     io_req4
intf@LC3_F11     intf@LC2_F23     io_req5
intf@LC4_B20     intf@LC2_B19     iram0
intf@LC1_B19     intf@LC6_B21     iram1
intf@LC2_B19     intf@LC7_B21     iram2
intf@LC1_B20     intf@LC1_B21     iram3
intf@LC2_A22     intf@LC3_A17     ncnt0
intf@LC3_A1      intf@LC3_A20     ncnt1
intf@LC4_A1      intf@LC4_A20     ncnt2
intf@LC6_A1      intf@LC6_A20     ncnt3
intf@LC8_A1      intf@LC8_A20     ncnt4
intf@LC1_A3      intf@LC1_A22     ncnt5
intf@LC3_A3      intf@LC3_A22     ncnt6
intf@LC5_A3      intf@LC5_A22     ncnt7
intf@LC5_A18     intf@LC3_A12     ncnt8
intf@LC3_A18     intf@LC5_A12     ncnt9
intf@LC6_A19     intf@LC6_F3      ncnt10
intf@LC1_A17     intf@LC2_F21     ncnt11
intf@LC8_A19     intf@LC5_F3      ncnt12
intf@LC1_A15     intf@LC8_A24     ncnt13
intf@LC2_B24     intf@LC1_A18     nors
intf@LC4_A13     intf@LC5_A2      nread
intf@38                           pg_adrpf0
intf@136                          pg_adrpf1
intf@131                          pg_adrpf2
intf@133                          pg_adrpf3
intf@134                          pg_adrpf4
intf@122                          pg_adrpf5
intf@120                          pg_adrpf6
intf@119                          pg_adrpf7
intf@121                          pg_adrpf8
intf@41                           pg_adrpf9
intf@9                            pg_adrram0
intf@7                            pg_adrram1
intf@39                           pg_adrram2
intf@148                          pg_adrram3
intf@10                           pg_adrram4
intf@157                          pg_adrram5
intf@147                          pg_adrram6
intf@112                          pg_adrram7
intf@150                          pg_adrram8
intf@111                          pg_adrram9
intf@57                           pg_adrram10
intf@65                           pg_adrram11
intf@73                           pg_adrram12
intf@69                           pg_adrram13
intf@179                          pg_cspf0
intf@86                           pg_cspf1
intf@70                           pg_g
intf@LC1_F24     intf@LC5_D16     pg_gg
intf@67                           pg_oepf
intf@204                          pg_runpf
intf@140                          pg_wepf
intf@14                           pg_weram0
intf@15                           pg_weram1
intf@12                           pg_weram2
intf@139                          pg_weram3
intf@LC3_F8      intf@LC1_F19     pio
intf@LC5_E15     intf@LC8_A15     piobn0
intf@LC1_B17     intf@LC2_D12     piobn1
intf@LC4_B10     intf@LC8_D7      piobn2
intf@LC2_D18     intf@LC4_C6      piobn3
intf@LC3_B14     intf@LC5_A9      piobn4
intf@LC4_D13     intf@LC6_D7      piobn5
intf@LC2_D13     intf@LC5_C10     piobn6
intf@LC2_A23     intf@LC1_A19     piobn7
intf@LC1_A20     intf@LC1_A21     piobn8
intf@LC3_A20     intf@LC2_A23     piobn9
intf@LC3_D22     intf@LC4_F2      piobn10
intf@LC7_E14     intf@LC3_E18     piocom0
intf@LC6_E23     intf@LC5_C19     piocom1
intf@LC3_E13     intf@LC7_C18     piocom2
intf@LC2_C14     intf@LC1_C7      piocom3
intf@LC1_C9      intf@LC2_C19     piocom4
intf@LC8_E8      intf@LC4_E1      piocom5
intf@LC2_C11     intf@LC1_C10     piocom6
intf@LC4_F9      intf@LC7_F6      piocom7
intf@LC3_F9                       piocom8
intf@LC5_E4      intf@LC2_E17     piocom9
intf@LC3_F16     intf@LC5_F6      piocom10
intf@LC6_F17     intf@LC7_F16     piocom11
intf@LC3_F17     intf@LC8_F13     piocom12
intf@LC1_F16     intf@LC6_F16     piocom13
intf@LC1_B18     intf@LC3_B20     piocom17
intf@LC1_B13     intf@LC1_B24     piocom18
intf@LC1_F6      intf@LC2_F17     piosts0
intf@LC2_F6      intf@LC4_F17     piosts1
intf@LC3_A23                      run
intf@LC7_B20     intf@LC6_B12     :101
intf@LC4_B19     intf@LC4_B21     :102
intf@LC8_B19     intf@LC8_B21     :103
intf@LC6_B20     intf@LC7_B19     :104
intf@LC1_A23                      :105
intf@LC4_C17     ---------        :106
intf@LC2_F24     intf@LC1_D23     :107
intf@LC3_F24     intf@LC2_D23     :108
intf@LC1_F15     intf@LC2_D16     :109
intf@LC1_F23     ---------        :292
intf@LC4_F6      ---------        ~309~1
intf@LC3_F6      ---------        ~312~1
intf@LC4_F12     intf@LC3_F17     ~322~1
intf@LC3_F12     ---------        ~323~1
intf@LC6_E14     intf@LC5_F13     :344
intf@LC2_E23     intf@LC3_D7      :346
intf@LC2_C21     intf@LC3_C6      :347
intf@LC2_E8      intf@LC2_D7      :349
intf@LC1_C11     intf@LC7_C10     :350
intf@LC1_D10     ---------        ~368~1
intf@LC2_D10     ---------        ~368~2
intf@LC3_D10     ---------        ~368~3
intf@LC1_D12     intf@LC8_F1      :383
intf@LC1_D11     intf@LC1_B7      :399
intf@LC2_D12     intf@LC3_B16     :433
intf@LC2_E18     intf@LC2_F13     :510
intf@LC4_E18     intf@LC5_F16     :512
intf@LC7_D20     ---------        ~540~1
intf@LC5_D11     ---------        ~546~1
intf@LC5_D20     ---------        ~552~1
intf@LC4_D20     ---------        ~554~1
intf@LC7_D22     ---------        ~558~1
intf@LC3_E23     ---------        ~562~1
intf@LC7_D2      ---------        ~568~1
intf@LC8_F9      ---------        ~574~1
intf@LC7_F9      ---------        ~576~1
intf@LC7_F16     ---------        ~580~1
intf@LC8_F17     ---------        ~582~1
intf@LC6_F16     ---------        ~586~1
intf@LC4_D10     ---------        ~604~1
intf@LC5_D10     ---------        ~604~2
intf@LC1_B15     intf@LC7_B2      :615
intf@LC3_B20     ---------        ~647~1
intf@LC3_B19     ---------        ~650~1
intf@LC5_B19     ---------        ~653~1
intf@LC2_B20     ---------        ~656~1
intf@LC8_E14     intf@LC2_E24     :687
intf@LC1_E5      intf@LC5_D7      :689
intf@LC2_C3      intf@LC2_C6      :690
intf@LC4_E8      intf@LC4_D7      :692
intf@LC3_C11     intf@LC2_C10     :693
intf@LC1_B11     ---------        ~707~1
intf@LC2_B11     ---------        ~707~2
intf@LC3_B11     ---------        ~707~3
intf@LC1_B10     intf@LC3_E14     :722
intf@LC3_B8      intf@LC1_C3      :738
intf@LC2_B10     intf@LC5_C24     :772
intf@LC4_B17     ---------        ~855~1
intf@LC6_B4      ---------        ~861~1
intf@LC6_B17     ---------        ~867~1
intf@LC8_B17     ---------        ~869~1
intf@LC6_B16     ---------        ~873~1
intf@LC1_D24     ---------        ~877~1
intf@LC4_E6      ---------        ~883~1
intf@LC3_E6      ---------        ~889~1
intf@LC7_E7      ---------        ~891~1
intf@LC4_B11     ---------        ~912~1
intf@LC5_B11     ---------        ~912~2
intf@LC7_B22     intf@LC8_C8      :923
intf@LC4_A4      ---------        ~961~1
intf@LC5_A4      ---------        ~961~2
intf@LC6_A4      ---------        ~961~3
intf@LC3_A15     ---------        ~961~4
intf@LC4_A17     ---------        ~995~1
intf@LC1_A4      ---------        ~995~2
intf@LC2_A4      ---------        ~995~3
intf@LC3_A4      ---------        ~995~4
intf@LC5_A1      ---------        ~1011~1
intf@LC5_A1      ---------        ~1011~2
intf@LC7_A1      ---------        ~1016~1
intf@LC7_A1      ---------        ~1016~2
intf@LC2_A3      intf@LC7_A20     ~1027~2
intf@LC4_A3      ---------        ~1032~1
intf@LC4_A3      ---------        ~1032~2
intf@LC2_A6      ---------        ~1105~1
intf@LC1_A6      ---------        ~1107~1
intf@LC2_A1      ---------        ~1109~1
intf@LC1_A1      ---------        ~1111~1
intf@LC4_A6      ---------        ~1113~1
intf@LC8_A3      ---------        ~1115~1
intf@LC7_A3      ---------        ~1117~1
intf@LC4_A18     ---------        ~1119~1
intf@LC3_A19     ---------        ~1123~1
intf@LC2_A17     ---------        ~1125~1
intf@LC2_A15     ---------        ~1129~1
intf@LC1_C8      intf@LC7_F3      :1137
intf@LC5_E14     intf@LC6_E20     :1146
intf@LC1_E11     intf@LC1_D7      :1148
intf@LC1_C2      intf@LC1_C6      :1149
intf@LC7_E8      intf@LC7_D7      :1151
intf@LC4_C11     intf@LC3_C10     :1152
intf@LC1_C17     ---------        ~1166~1
intf@LC2_C17     ---------        ~1166~2
intf@LC3_C17     ---------        ~1166~3
intf@LC3_C24     intf@LC4_D14     :1181
intf@LC3_C23     intf@LC3_D10     :1197
intf@LC4_C24     intf@LC7_D21     :1231
intf@LC4_C15     ---------        ~1314~1
intf@LC7_C15     ---------        ~1320~1
intf@LC6_C19     ---------        ~1326~1
intf@LC7_C19     ---------        ~1328~1
intf@LC8_C19     ---------        ~1332~1
intf@LC4_C9      ---------        ~1336~1
intf@LC5_C9      ---------        ~1342~1
intf@LC5_E3      ---------        ~1348~1
intf@LC3_E3      ---------        ~1350~1
intf@LC7_C17     ---------        ~1362~1
intf@LC6_C17     ---------        ~1362~2
intf@LC5_C17     ---------        ~1362~3
intf@LC4_F24     ---------        ~1381~1
intf@LC5_F24     ---------        ~1395~1
intf@LC2_B22     intf@LC6_E10     :1544


Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

***** Logic for device 'intf' compiled without errors.




Device: EPF10K20RC208-4

FLEX 10K Configuration Scheme: Passive Serial

Device Options:
    User-Supplied Start-Up Clock               = OFF
    Auto-Restart Configuration on Frame Error  = OFF
    Release Clears Before Tri-States           = OFF
    Enable Chip_Wide Reset                     = OFF
    Enable Chip-Wide Output Enable             = OFF
    Enable INIT_DONE Output                    = OFF
    JTAG User Code                             = 7f
                                                                                                                          
                       h                                                                                               p  
                       l                                         h h h                                             h   g  
                 h h R _ p R R   R R R R R R   R R R R h   R h   l l l   h p   R R R R R R   R R R R R   R R R h R l h _  
                 l l E d g E E   E E E E E E   E E E E l   E l   _ _ _   l g   E E E E E E   E E E E E   E E E l E _ l a  
                 _ _ S _ _ S S   S S S S S S   S S S S _   S _ G d d d V _ _   S S S S S S   S S S S S   S S S _ S d _ d  
                 d d E w r E E G E E E E E E V E E E E d G E d N a a a C d c V E E E E E E G E E E E E V E E E d E a d r  
                 a a R r u R R N R R R R R R C R R R R a N R a D t t t C a s C R R R R R R N R R R R R C R R R a R t a r  
                 t t V i n V V D V V V V V V C V V V V t D V t I a a a I t p C V V V V V V D V V V V V C V V V t V a t a  
                 a a E t p E E I E E E E E E I E E E E a I E a N 1 1 1 N a f I E E E E E E I E E E E E I E E E a E 2 a m  
                 9 7 D e f D D O D D D D D D O D D D D 4 O D 0 T 2 0 1 T 1 0 O D D D D D D O D D D D D O D D D 2 D 9 5 5  
               ----------------------------------------------------------------------------------------------------------_ 
              / 208 206 204 202 200 198 196 194 192 190 188 186 184 182 180 178 176 174 172 170 168 166 164 162 160 158   |_ 
             /    207 205 203 201 199 197 195 193 191 189 187 185 183 181 179 177 175 173 171 169 167 165 163 161 159 157    | 
       #TCK |  1                                                                                                         156 | ^DATA0 
 ^CONF_DONE |  2                                                                                                         155 | ^DCLK 
      ^nCEO |  3                                                                                                         154 | ^nCE 
       #TDO |  4                                                                                                         153 | #TDI 
      VCCIO |  5                                                                                                         152 | GNDIO 
     VCCINT |  6                                                                                                         151 | GNDINT 
 pg_adrram1 |  7                                                                                                         150 | pg_adrram8 
   hl_data8 |  8                                                                                                         149 | hl_calc_sts 
 pg_adrram0 |  9                                                                                                         148 | pg_adrram3 
 pg_adrram4 | 10                                                                                                         147 | pg_adrram6 
  hl_data28 | 11                                                                                                         146 | VCCIO 
  pg_weram2 | 12                                                                                                         145 | VCCINT 
   hl_dma_r | 13                                                                                                         144 | RESERVED 
  pg_weram0 | 14                                                                                                         143 | RESERVED 
  pg_weram1 | 15                                                                                                         142 | RESERVED 
  hl_data15 | 16                                                                                                         141 | RESERVED 
  hl_data14 | 17                                                                                                         140 | pg_wepf 
  hl_data17 | 18                                                                                                         139 | pg_weram3 
   RESERVED | 19                                                                                                         138 | VCCIO 
      GNDIO | 20                                                                                                         137 | VCCINT 
     GNDINT | 21                                                                                                         136 | pg_adrpf1 
      VCCIO | 22                                                                                                         135 | RESERVED 
     VCCINT | 23                                                                                                         134 | pg_adrpf4 
   RESERVED | 24                                                                                                         133 | pg_adrpf3 
   RESERVED | 25                                                                                                         132 | RESERVED 
   RESERVED | 26                                                                                                         131 | pg_adrpf2 
   RESERVED | 27                                             EPF10K20RC208-4                                             130 | GNDIO 
   RESERVED | 28                                                                                                         129 | GNDINT 
   RESERVED | 29                                                                                                         128 | RESERVED 
   RESERVED | 30                                                                                                         127 | RESERVED 
   RESERVED | 31                                                                                                         126 | RESERVED 
      GNDIO | 32                                                                                                         125 | RESERVED 
     GNDINT | 33                                                                                                         124 | GNDIO 
      VCCIO | 34                                                                                                         123 | GNDINT 
     VCCINT | 35                                                                                                         122 | pg_adrpf5 
  hl_data20 | 36                                                                                                         121 | pg_adrpf8 
   RESERVED | 37                                                                                                         120 | pg_adrpf6 
  pg_adrpf0 | 38                                                                                                         119 | pg_adrpf7 
 pg_adrram2 | 39                                                                                                         118 | VCCIO 
  hl_data16 | 40                                                                                                         117 | VCCINT 
  pg_adrpf9 | 41                                                                                                         116 | hl_data19 
      VCCIO | 42                                                                                                         115 | hl_data18 
     VCCINT | 43                                                                                                         114 | hl_data30 
  hl_io_req | 44                                                                                                         113 | hl_data31 
  hl_data21 | 45                                                                                                         112 | pg_adrram7 
  hl_data22 | 46                                                                                                         111 | pg_adrram9 
  hl_data23 | 47                                                                                                         110 | VCCIO 
      GNDIO | 48                                                                                                         109 | VCCINT 
     GNDINT | 49                                                                                                         108 | ^MSEL0 
       #TMS | 50                                                                                                         107 | ^MSEL1 
     #nTRST | 51                                                                                                         106 | VCCINT 
   ^nSTATUS | 52                                                                                                         105 | ^nCONFIG 
            |      54  56  58  60  62  64  66  68  70  72  74  76  78  80  82  84  86  88  90  92  94  96  98 100 102 104  _| 
             \   53  55  57  59  61  63  65  67  69  71  73  75  77  79  81  83  85  87  89  91  93  95  97  99 101 103   | 
              \----------------------------------------------------------------------------------------------------------- 
                 h R h h p R G R R R R R p V p R p p R G p h h V V h h h G G R V R p R R R R G R R R R R R V R R R R R R  
                 l E l l g E N E E E E E g C g E g g E N g l l C C l l l N N E C E g E E E E N E E E E E E C E E E E E E  
                 _ S _ _ _ S D S S S S S _ C _ S _ _ S D _ _ _ C C _ _ _ D D S C S _ S S S S D S S S S S S C S S S S S S  
                 d E d d a E I E E E E E a I o E a g E I a d d I I d c d I I E I E c E E E E I E E E E E E I E E E E E E  
                 a R m _ d R O R R R R R d O e R d   R O d a a N N m l a N N R O R s R R R R O R R R R R R O R R R R R R  
                 t V a r r V   V V V V V r   p V r   V   r t t T T a k t T T V   V p V V V V   V V V V V V   V V V V V V  
                 a E _ e r E   E E E E E r   f E r   E   r a a     _   a     E   E f E E E E   E E E E E E   E E E E E E  
                 2 D w a a D   D D D D D a     D a   D   a 6 3     a   1     D   D 1 D D D D   D D D D D D   D D D D D D  
                 4     d m               m       m       m         c   3                                                  
                         1               1       1       1         k                                                      
                         0               1       3       2                                                                


N.C. = Not Connected.
VCCINT = Dedicated power pin, which MUST be connected to VCC.
VCCIO = Dedicated power pin, which MUST be connected to VCC.
GNDINT = Dedicated ground pin or unused dedicated input, which MUST be connected to GND.
GNDIO = Dedicated ground pin, which MUST be connected to GND.
RESERVED = Unused I/O pin, which MUST be left unconnected.

^ = Dedicated configuration pin.
+ = Reserved configuration pin, which will be tri-stated during user mode.
* = Reserved configuration pin, which drives out in user mode.
PDn = Power Down pin. 
@ = Special-purpose pin. 
# = JTAG Boundary Scan Testing Pin.


Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

** RESOURCE USAGE **

Logic                Column       Row                                   
Array                Interconnect Interconnect         Clear/     External  
Block   Logic Cells  Driven       Driven       Clocks  Preset   Interconnect
A1       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
A2       2/ 8( 25%)   1/ 8( 12%)   2/ 8( 25%)    0/2    0/2       7/22( 31%)   
A3       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
A4       3/ 8( 37%)   3/ 8( 37%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
A5       3/ 8( 37%)   2/ 8( 25%)   1/ 8( 12%)    1/2    0/2       4/22( 18%)   
A6       3/ 8( 37%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2       6/22( 27%)   
A7       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
A8       2/ 8( 25%)   1/ 8( 12%)   2/ 8( 25%)    0/2    0/2       5/22( 22%)   
A9       2/ 8( 25%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       5/22( 22%)   
A10      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
A11      2/ 8( 25%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       6/22( 27%)   
A12      6/ 8( 75%)   2/ 8( 25%)   2/ 8( 25%)    1/2    0/2       9/22( 40%)   
A13      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
A14      7/ 8( 87%)   1/ 8( 12%)   2/ 8( 25%)    0/2    0/2      13/22( 59%)   
A15      1/ 8( 12%)   1/ 8( 12%)   0/ 8(  0%)    1/2    0/2       1/22(  4%)   
A16      3/ 8( 37%)   0/ 8(  0%)   3/ 8( 37%)    0/2    0/2       8/22( 36%)   
A17      2/ 8( 25%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2       5/22( 22%)   
A18      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       2/22(  9%)   
A19      1/ 8( 12%)   1/ 8( 12%)   0/ 8(  0%)    1/2    0/2       1/22(  4%)   
A20      8/ 8(100%)   1/ 8( 12%)   4/ 8( 50%)    1/2    0/2       9/22( 40%)   
A21      1/ 8( 12%)   1/ 8( 12%)   0/ 8(  0%)    1/2    0/2       1/22(  4%)   
A22      8/ 8(100%)   2/ 8( 25%)   4/ 8( 50%)    1/2    0/2       6/22( 27%)   
A23      3/ 8( 37%)   2/ 8( 25%)   0/ 8(  0%)    1/2    0/2       2/22(  9%)   
A24      3/ 8( 37%)   1/ 8( 12%)   2/ 8( 25%)    1/2    0/2       7/22( 31%)   
B1       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
B2       7/ 8( 87%)   1/ 8( 12%)   2/ 8( 25%)    1/2    1/2      15/22( 68%)   
B3       8/ 8(100%)   3/ 8( 37%)   1/ 8( 12%)    1/2    0/2      12/22( 54%)   
B5       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
B6       8/ 8(100%)   1/ 8( 12%)   3/ 8( 37%)    1/2    0/2      12/22( 54%)   
B7       6/ 8( 75%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2       8/22( 36%)   
B8       6/ 8( 75%)   1/ 8( 12%)   3/ 8( 37%)    1/2    0/2       9/22( 40%)   
B9       3/ 8( 37%)   0/ 8(  0%)   2/ 8( 25%)    0/2    0/2       6/22( 27%)   
B10      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2       3/22( 13%)   
B11      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
B12      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2       3/22( 13%)   
B14      7/ 8( 87%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2      11/22( 50%)   
B15      7/ 8( 87%)   2/ 8( 25%)   3/ 8( 37%)    1/2    0/2      12/22( 54%)   
B16      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
B18      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       3/22( 13%)   
B19      3/ 8( 37%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2       8/22( 36%)   
B20      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
B21      8/ 8(100%)   0/ 8(  0%)   3/ 8( 37%)    1/2    0/2       8/22( 36%)   
B22      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       1/22(  4%)   
B24      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
C1       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
C2       6/ 8( 75%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2       9/22( 40%)   
C3       6/ 8( 75%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2       8/22( 36%)   
C4       2/ 8( 25%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       8/22( 36%)   
C5       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
C6       4/ 8( 50%)   2/ 8( 25%)   1/ 8( 12%)    1/2    0/2       4/22( 18%)   
C7       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
C8       7/ 8( 87%)   2/ 8( 25%)   1/ 8( 12%)    1/2    0/2      14/22( 63%)   
C9       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
C10      6/ 8( 75%)   4/ 8( 50%)   1/ 8( 12%)    1/2    0/2       5/22( 22%)   
C11      2/ 8( 25%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       6/22( 27%)   
C12      6/ 8( 75%)   1/ 8( 12%)   2/ 8( 25%)    1/2    0/2      12/22( 54%)   
C16      7/ 8( 87%)   0/ 8(  0%)   3/ 8( 37%)    1/2    0/2       8/22( 36%)   
C18      7/ 8( 87%)   2/ 8( 25%)   1/ 8( 12%)    1/2    0/2      10/22( 45%)   
C19      8/ 8(100%)   3/ 8( 37%)   3/ 8( 37%)    1/2    0/2       9/22( 40%)   
C22      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       3/22( 13%)   
C24      7/ 8( 87%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2      12/22( 54%)   
D2       1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
D3       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
D4       2/ 8( 25%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2       5/22( 22%)   
D5       5/ 8( 62%)   2/ 8( 25%)   0/ 8(  0%)    1/2    0/2       5/22( 22%)   
D6       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
D7       8/ 8(100%)   4/ 8( 50%)   2/ 8( 25%)    1/2    0/2       5/22( 22%)   
D10      6/ 8( 75%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2       8/22( 36%)   
D11      6/ 8( 75%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2       9/22( 40%)   
D12      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
D14      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
D15      8/ 8(100%)   1/ 8( 12%)   3/ 8( 37%)    1/2    0/2      12/22( 54%)   
D16      5/ 8( 62%)   2/ 8( 25%)   0/ 8(  0%)    1/2    0/2       8/22( 36%)   
D17      6/ 8( 75%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       9/22( 40%)   
D21      7/ 8( 87%)   1/ 8( 12%)   2/ 8( 25%)    1/2    0/2      14/22( 63%)   
D22      5/ 8( 62%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2       6/22( 27%)   
D23      7/ 8( 87%)   2/ 8( 25%)   2/ 8( 25%)    1/2    0/2       4/22( 18%)   
E1       5/ 8( 62%)   1/ 8( 12%)   2/ 8( 25%)    1/2    0/2       6/22( 27%)   
E2       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
E3       1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
E4       6/ 8( 75%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2      11/22( 50%)   
E5       2/ 8( 25%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       5/22( 22%)   
E6       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
E7       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
E8       7/ 8( 87%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2      11/22( 50%)   
E9       7/ 8( 87%)   2/ 8( 25%)   1/ 8( 12%)    1/2    0/2       9/22( 40%)   
E10      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
E11      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
E12      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
E14      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
E15      6/ 8( 75%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2      11/22( 50%)   
E16      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       3/22( 13%)   
E17      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
E18      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
E19      3/ 8( 37%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2       6/22( 27%)   
E20      7/ 8( 87%)   1/ 8( 12%)   2/ 8( 25%)    1/2    0/2      14/22( 63%)   
E21      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
E22      7/ 8( 87%)   1/ 8( 12%)   3/ 8( 37%)    1/2    0/2       8/22( 36%)   
E24      7/ 8( 87%)   2/ 8( 25%)   3/ 8( 37%)    1/2    0/2       9/22( 40%)   
F1       1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
F2       1/ 8( 12%)   1/ 8( 12%)   0/ 8(  0%)    1/2    0/2       1/22(  4%)   
F3       7/ 8( 87%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2      11/22( 50%)   
F4       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
F5       4/ 8( 50%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2      10/22( 45%)   
F6       6/ 8( 75%)   1/ 8( 12%)   2/ 8( 25%)    1/2    0/2       7/22( 31%)   
F7       1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
F8       1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
F9       5/ 8( 62%)   2/ 8( 25%)   2/ 8( 25%)    1/2    0/2       8/22( 36%)   
F10      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    0/2    0/2       3/22( 13%)   
F11      2/ 8( 25%)   2/ 8( 25%)   0/ 8(  0%)    0/2    0/2       3/22( 13%)   
F12      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    0/2    0/2       4/22( 18%)   
F13      8/ 8(100%)   2/ 8( 25%)   2/ 8( 25%)    1/2    0/2      13/22( 59%)   
F15      1/ 8( 12%)   0/ 8(  0%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
F16      8/ 8(100%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2      12/22( 54%)   
F17      6/ 8( 75%)   3/ 8( 37%)   2/ 8( 25%)    1/2    0/2       7/22( 31%)   
F18      4/ 8( 50%)   0/ 8(  0%)   2/ 8( 25%)    1/2    0/2       6/22( 27%)   
F19      1/ 8( 12%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       2/22(  9%)   
F20      1/ 8( 12%)   1/ 8( 12%)   0/ 8(  0%)    0/2    0/2       4/22( 18%)   
F21      5/ 8( 62%)   2/ 8( 25%)   1/ 8( 12%)    1/2    0/2      12/22( 54%)   
F23      7/ 8( 87%)   1/ 8( 12%)   1/ 8( 12%)    1/2    0/2       1/22(  4%)   
F24      1/ 8( 12%)   1/ 8( 12%)   0/ 8(  0%)    0/2    0/2       4/22( 18%)   


Embedded             Column       Row                                   
Array     Embedded   Interconnect Interconnect         Read/      External  
Block     Cells      Driven       Driven       Clocks  Write    Interconnect


Total dedicated input pins used:                 6/6      (100%)
Total I/O pins used:                            65/141    ( 46%)
Total logic cells used:                        424/1152   ( 36%)
Total embedded cells used:                       0/48     (  0%)
Total EABs used:                                 0/6      (  0%)
Average fan-in:                                 3.27/4    ( 81%)
Total fan-in:                                1389/4608    ( 30%)

Total input pins required:                      32
Total input registers required:                  0
Total output pins required:                     39
Total output registers required:                 0
Total buried I/O cell registers required:        0
Total bidirectional pins required:               0
Total reserved pins required                     0
Total logic cells required:                    424
Total flipflops required:                      155
Total packed registers required:                 0
Total logic cells in carry chains:              12
Total number of carry chains:                    1
Total number of carry chains of length  1-8 :    0
Total number of carry chains of length  9-16:    1
Total logic cells in cascade chains:            89
Total number of cascade chains:                 41
Total single-pin Clock Enables required:         0
Total single-pin Output Enables required:        0
Logic cells inserted for fitting:                1

Synthesized logic cells:                        85/1152   (  7%)

Logic Cell and Embedded Cell Counts

Column:  01  02  03  04  05  06  07  08  09  10  11  12  EA  13  14  15  16  17  18  19  20  21  22  23  24  Total(LC/EC)
 A:      1   2   1   3   3   3   1   2   2   1   2   6   0   1   7   1   3   2   1   1   8   1   8   3   3     66/0  
 B:      1   7   8   0   1   8   6   6   3   1   1   1   0   0   7   7   1   0   1   3   1   8   1   0   1     73/0  
 C:      1   6   6   2   1   4   1   7   1   6   2   6   0   0   0   0   7   0   7   8   0   0   1   0   7     73/0  
 D:      0   1   1   2   5   1   8   0   0   6   6   1   0   0   1   8   5   6   0   0   0   7   5   7   0     70/0  
 E:      5   1   1   6   2   1   1   7   7   1   1   1   0   0   1   6   1   1   1   3   7   1   7   0   7     69/0  
 F:      1   1   7   1   4   6   1   1   5   1   2   1   0   8   0   1   8   6   4   1   1   5   0   7   1     73/0  

Total:   9  18  24  14  16  23  18  23  18  16  14  16   0   9  16  23  25  15  14  16  17  22  22  17  19    424/0  



Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

** INPUTS **

                                                    Fan-In    Fan-Out
 Pin     LC     EC   Row  Col  Primitive    Code     INP  FBK  OUT  FBK  Name
  79      -     -    -    --      INPUT                0    0    0    0  hl_clk
 186      -     -    -    13      INPUT                0    0    0    2  hl_data0
 180      -     -    -    13      INPUT                0    0    0    2  hl_data1
 161      -     -    -    02      INPUT                0    0    0    2  hl_data2
  75      -     -    -    13      INPUT                0    0    0    2  hl_data3
 189      -     -    -    14      INPUT                0    0    0    2  hl_data4
 158      -     -    -    01      INPUT                0    0    0    2  hl_data5
  74      -     -    -    13      INPUT                0    0    0    2  hl_data6
 207      -     -    A    --      INPUT                0    0    0    2  hl_data7
   8      -     -    A    --      INPUT                0    0    0    2  hl_data8
 208      -     -    A    --      INPUT                0    0    0    2  hl_data9
 183      -     -    -    --      INPUT                0    0    0    2  hl_data10
 182      -     -    -    --      INPUT                0    0    0    2  hl_data11
 184      -     -    -    --      INPUT                0    0    0    2  hl_data12
  80      -     -    -    --      INPUT                0    0    0    2  hl_data13
  17      -     -    C    --      INPUT                0    0    0    1  hl_data14
  16      -     -    C    --      INPUT                0    0    0    1  hl_data15
  40      -     -    E    --      INPUT                0    0    0    1  hl_data16
  18      -     -    C    --      INPUT                0    0    0    1  hl_data17
 115      -     -    F    --      INPUT                0    0    0    1  hl_data18
 116      -     -    F    --      INPUT                0    0    0    1  hl_data19
  36      -     -    E    --      INPUT                0    0    0    1  hl_data20
  45      -     -    F    --      INPUT                0    0    0    3  hl_data21
  46      -     -    F    --      INPUT                0    0    0    3  hl_data22
  47      -     -    F    --      INPUT                0    0    0    3  hl_data23
  53      -     -    F    --      INPUT                0    0    0    3  hl_data24
  11      -     -    B    --      INPUT                0    0    0    1  hl_data28
 159      -     -    -    01      INPUT                0    0    0    3  hl_data29
 114      -     -    F    --      INPUT                0    0    0    1  hl_data30
 113      -     -    F    --      INPUT                0    0    0    3  hl_data31
  78      -     -    -    --      INPUT                0    0    0    3  hl_dma_ack
  44      -     -    F    --      INPUT                0    0    0    2  hl_io_req


Code:

s = Synthesized pin or logic cell
+ = Synchronous flipflop
/ = Slow slew-rate output
! = NOT gate push-back
r = Fitter-inserted logic cell
^ = Increased input delay
$ = Driven by fast output logic cell
@ = Uses single-pin Clock Enable
& = Uses single-pin Output Enable


Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

** OUTPUTS **

       Fed By Fed By                                Fan-In    Fan-Out
 Pin     LC     EC   Row  Col  Primitive    Code     INP  FBK  OUT  FBK  Name
 149      -     -    A    --     OUTPUT                0    1    0    0  hl_calc_sts
  13      -     -    B    --     OUTPUT                0    1    0    0  hl_dma_r
  55      -     -    -    24     OUTPUT                0    1    0    0  hl_dma_w
  56      -     -    -    23     OUTPUT                0    1    0    0  hl_d_read
 205      -     -    -    24     OUTPUT                0    1    0    0  hl_d_write
  38      -     -    E    --     OUTPUT                0    1    0    0  pg_adrpf0
 136      -     -    C    --     OUTPUT                0    1    0    0  pg_adrpf1
 131      -     -    C    --     OUTPUT                0    1    0    0  pg_adrpf2
 133      -     -    C    --     OUTPUT                0    1    0    0  pg_adrpf3
 134      -     -    C    --     OUTPUT                0    1    0    0  pg_adrpf4
 122      -     -    E    --     OUTPUT                0    1    0    0  pg_adrpf5
 120      -     -    E    --     OUTPUT                0    1    0    0  pg_adrpf6
 119      -     -    E    --     OUTPUT                0    1    0    0  pg_adrpf7
 121      -     -    E    --     OUTPUT                0    1    0    0  pg_adrpf8
  41      -     -    E    --     OUTPUT                0    1    0    0  pg_adrpf9
   9      -     -    A    --     OUTPUT                0    1    0    0  pg_adrram0
   7      -     -    A    --     OUTPUT                0    1    0    0  pg_adrram1
  39      -     -    E    --     OUTPUT                0    1    0    0  pg_adrram2
 148      -     -    A    --     OUTPUT                0    1    0    0  pg_adrram3
  10      -     -    A    --     OUTPUT                0    1    0    0  pg_adrram4
 157      -     -    A    --     OUTPUT                0    1    0    0  pg_adrram5
 147      -     -    A    --     OUTPUT                0    1    0    0  pg_adrram6
 112      -     -    F    --     OUTPUT                0    1    0    0  pg_adrram7
 150      -     -    A    --     OUTPUT                0    1    0    0  pg_adrram8
 111      -     -    F    --     OUTPUT                0    1    0    0  pg_adrram9
  57      -     -    -    22     OUTPUT                0    1    0    0  pg_adrram10
  65      -     -    -    18     OUTPUT                0    1    0    0  pg_adrram11
  73      -     -    -    14     OUTPUT                0    1    0    0  pg_adrram12
  69      -     -    -    15     OUTPUT                0    1    0    0  pg_adrram13
 179      -     -    -    12     OUTPUT                0    1    0    0  pg_cspf0
  86      -     -    -    11     OUTPUT                0    1    0    0  pg_cspf1
  70      -     -    -    15     OUTPUT                0    1    0    0  pg_g
  67      -     -    -    17     OUTPUT                0    1    0    0  pg_oepf
 204      -     -    -    23     OUTPUT                0    1    0    0  pg_runpf
 140      -     -    B    --     OUTPUT                0    1    0    0  pg_wepf
  14      -     -    B    --     OUTPUT                0    1    0    0  pg_weram0
  15      -     -    B    --     OUTPUT                0    1    0    0  pg_weram1
  12      -     -    B    --     OUTPUT                0    1    0    0  pg_weram2
 139      -     -    B    --     OUTPUT                0    1    0    0  pg_weram3


Code:

s = Synthesized pin or logic cell
+ = Synchronous flipflop
/ = Slow slew-rate output
! = NOT gate push-back
r = Fitter-inserted logic cell
^ = Increased input delay
$ = Driven by fast output logic cell
@ = Uses single-pin Clock Enable
& = Uses single-pin Output Enable


Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

** BURIED LOGIC **

                                                    Fan-In    Fan-Out
 IOC     LC     EC   Row  Col  Primitive    Code     INP  FBK  OUT  FBK  Name
   -      1     -    D    16       DFFE  +            0    3    0    5  adr_drram0
   -      6     -    B    15       DFFE  +            0    3    0    5  adr_drram1
   -      3     -    B    15       DFFE  +            0    3    0    4  adr_drram2
   -      7     -    B    03       DFFE  +            0    3    0    3  adr_drram3
   -      6     -    B    08       DFFE  +            0    3    0    5  adr_drram4
   -      7     -    B    06       DFFE  +            0    3    0    4  adr_drram5
   -      8     -    B    03       DFFE  +            0    3    0    3  adr_drram6
   -      2     -    F    06       DFFE  +            0    3    0    5  adr_drram7
   -      2     -    F    09       DFFE  +            0    3    0    5  adr_drram8
   -      3     -    F    05       DFFE  +            0    4    0    5  adr_drram9
   -      3     -    F    06       DFFE  +            0    3    0    4  adr_drram10
   -      8     -    F    16       DFFE  +            0    3    0    4  adr_drram11
   -      4     -    F    13       DFFE  +            0    4    0    4  adr_drram12
   -      2     -    F    16       DFFE  +            0    3    0    2  adr_drram13
   -      5     -    E    24       DFFE  +            0    3    0    5  adr_drreg0
   -      3     -    C    19       DFFE  +            0    3    0    5  adr_drreg1
   -      5     -    C    18       DFFE  +            0    3    0    4  adr_drreg2
   -      6     -    C    12       DFFE  +            0    3    0    3  adr_drreg3
   -      6     -    C    19       DFFE  +            0    3    0    5  adr_drreg4
   -      2     -    E    01       DFFE  +            0    3    0    4  adr_drreg5
   -      7     -    E    04       DFFE  +            0    3    0    3  adr_drreg6
   -      3     -    E    15       DFFE  +            0    3    0    4  adr_drreg7
   -      1     -    E    19       DFFE  +            0    3    0    3  adr_drreg8
   -      4     -    E    15       DFFE  +            0    4    0    3  adr_drreg9
   -      1     -    E    24       DFFE  +            0    3    0    5  adr_dwreg0
   -      1     -    E    22       DFFE  +            0    3    0    5  adr_dwreg1
   -      7     -    E    09       DFFE  +            0    3    0    4  adr_dwreg2
   -      6     -    E    09       DFFE  +            0    3    0    3  adr_dwreg3
   -      2     -    E    05       DFFE  +            0    3    0    5  adr_dwreg4
   -      8     -    E    08       DFFE  +            0    3    0    4  adr_dwreg5
   -      5     -    E    08       DFFE  +            0    3    0    3  adr_dwreg6
   -      4     -    E    22       DFFE  +            0    3    0    4  adr_dwreg7
   -      7     -    E    22       DFFE  +            0    3    0    3  adr_dwreg8
   -      5     -    E    20       DFFE  +            0    4    0    3  adr_dwreg9
   -      6     -    F    13       DFFE  +            0    3    0   18  bncnt_drram0
   -      4     -    D    05       DFFE  +            0    3    0    6  bncnt_drram1
   -      5     -    B    07       DFFE  +            0    3    0    5  bncnt_drram2
   -      7     -    B    07       DFFE  +            0    3    0    4  bncnt_drram3
   -      1     -    B    08       DFFE  +            0    3    0    6  bncnt_drram4
   -      8     -    B    06       DFFE  +            0    3    0    5  bncnt_drram5
   -      1     -    B    10       DFFE  +            0    3    0    4  bncnt_drram6
   -      4     -    B    15       DFFE  +            0    3    0    6  bncnt_drram7
   -      3     -    B    14       DFFE  +            0    3    0    5  bncnt_drram8
   -      4     -    B    14       DFFE  +            0    4    0    5  bncnt_drram9
   -      3     -    B    08       DFFE  +            0    3    0    3  bncnt_drram10
   -      6     -    E    24       DFFE  +            0    3    0   17  bncnt_drreg0
   -      2     -    C    16       DFFE  +            0    3    0    6  bncnt_drreg1
   -      5     -    C    03       DFFE  +            0    3    0    5  bncnt_drreg2
   -      8     -    C    03       DFFE  +            0    3    0    4  bncnt_drreg3
   -      1     -    C    19       DFFE  +            0    3    0    6  bncnt_drreg4
   -      7     -    C    02       DFFE  +            0    3    0    5  bncnt_drreg5
   -      5     -    C    02       DFFE  +            0    3    0    4  bncnt_drreg6
   -      5     -    C    16       DFFE  +            0    3    0    6  bncnt_drreg7
   -      4     -    C    16       DFFE  +            0    3    0    5  bncnt_drreg8
   -      3     -    C    24       DFFE  +            0    4    0    5  bncnt_drreg9
   -      4     -    C    24       DFFE  +            0    3    0    3  bncnt_drreg10
   -      3     -    E    20       DFFE  +            0    3    0   17  bncnt_dwreg0
   -      3     -    D    15       DFFE  +            0    3    0    6  bncnt_dwreg1
   -      6     -    D    10       DFFE  +            0    3    0    5  bncnt_dwreg2
   -      5     -    D    10       DFFE  +            0    3    0    4  bncnt_dwreg3
   -      4     -    D    04       DFFE  +            0    3    0    6  bncnt_dwreg4
   -      5     -    D    11       DFFE  +            0    3    0    5  bncnt_dwreg5
   -      6     -    D    11       DFFE  +            0    3    0    4  bncnt_dwreg6
   -      2     -    D    22       DFFE  +            0    3    0    6  bncnt_dwreg7
   -      1     -    D    22       DFFE  +            0    3    0    5  bncnt_dwreg8
   -      4     -    D    15       DFFE  +            0    4    0    5  bncnt_dwreg9
   -      5     -    D    21       DFFE  +            0    3    0    3  bncnt_dwreg10
   -      3     -    A    06       DFFE  +            0    3    1    2  ce
   -      1     -    A    06       AND2               0    3    0    1  cstart
   -      3     -    F    18       DFFE  +            0    3    0    1  cs0
   -      5     -    F    18       DFFE  +            0    3    0    1  cs1
   -      6     -    A    04       DFFE  +            1    0    0   11  dmaack_drns
   -      4     -    A    04       DFFE  +            1    0    0   18  dmaack_drram
   -      3     -    A    04       DFFE  +            1    0    0   14  dmaack_drreg
   -      1     -    A    05       DFFE  +            0    3    0   11  dmar_drns
   -      8     -    B    02       DFFE  +    !       0    4    0    2  dmar_drram
   -      7     -    B    05       DFFE  +            0    1    0    4  dmar_drram0
   -      2     -    C    08       DFFE  +            0    3    0    2  dmar_drreg
   -      6     -    D    17       DFFE  +            0    4    0    1  d_write0
   -      5     -    D    17       DFFE  +            0    1    0    1  d_write1
   -      2     -    D    17       DFFE  +            0    1    0    3  d_write2
   -      5     -    B    22       SOFT   s    r      0    1    1    0  hl_dma_r~fit~in1
   -      5     -    D    23       DFFE  +            0    1    0    1  img_dma_ack0
   -      6     -    D    23       DFFE  +            0    1    0    1  img_dma_ack1
   -      7     -    D    23       DFFE  +            0    1    0    1  img_dma_ack2
   -      3     -    D    23       DFFE  +            0    1    0    1  img_dma_ack3
   -      8     -    D    15       DFFE  +            0    1    0    1  img_dma_ack4
   -      5     -    D    15       DFFE  +            0    1    0   14  img_dma_ack5
   -      3     -    F    23       DFFE  +            1    0    0    1  io_req0
   -      4     -    F    23       DFFE  +            0    1    0    2  io_req1
   -      5     -    F    23       DFFE  +            0    1    0    1  io_req2
   -      6     -    F    23       DFFE  +            0    1    0    1  io_req3
   -      7     -    F    23       DFFE  +            0    1    0    1  io_req4
   -      2     -    F    23       DFFE  +            0    1    0    7  io_req5
   -      7     -    F    15       DFFE  +            0    1    0    6  io_req6
   -      2     -    B    19       DFFE  +            0    4    0    2  iram0
   -      6     -    B    21       DFFE  +            0    4    0    2  iram1
   -      7     -    B    21       DFFE  +            0    4    0    2  iram2
   -      1     -    B    21       DFFE  +            0    4    0    2  iram3
   -      3     -    A    17       DFFE  +            1    2    0    5  ncnt0
   -      3     -    A    20       DFFE  +            0    3    0    4  ncnt1
   -      4     -    A    20       DFFE  +            0    2    0    4  ncnt2
   -      6     -    A    20       DFFE  +            0    2    0    4  ncnt3
   -      8     -    A    20       DFFE  +            0    2    0    4  ncnt4
   -      1     -    A    22       DFFE  +            0    2    0    4  ncnt5
   -      3     -    A    22       DFFE  +            0    2    0    4  ncnt6
   -      5     -    A    22       DFFE  +            0    2    0    4  ncnt7
   -      3     -    A    12       DFFE  +            0    3    0    7  ncnt8
   -      5     -    A    12       DFFE  +            1    3    0    7  ncnt9
   -      6     -    F    03       DFFE  +            1    2    0    6  ncnt10
   -      2     -    F    21       DFFE  +            0    3    0    6  ncnt11
   -      5     -    F    03       DFFE  +            1    3    0    6  ncnt12
   -      8     -    A    24       DFFE  +            0    3    0    4  ncnt13
   -      1     -    A    18       DFFE  +            0    2    0   10  nors
   -      5     -    A    02       AND2               0    3    0   17  nread
   -      5     -    D    16       DFFE  +            0    4    0    2  pg_gg
   -      1     -    F    19       DFFE  +            0    2    0   81  pio
   -      8     -    A    15       DFFE  +            1    0    0    3  piobn0
   -      2     -    D    12       DFFE  +            1    0    0    3  piobn1
   -      8     -    D    07       DFFE  +            1    0    0    3  piobn2
   -      4     -    C    06       DFFE  +            1    0    0    3  piobn3
   -      5     -    A    09       DFFE  +            1    0    0    3  piobn4
   -      6     -    D    07       DFFE  +            1    0    0    3  piobn5
   -      5     -    C    10       DFFE  +            1    0    0    3  piobn6
   -      1     -    A    19       DFFE  +            1    0    0    3  piobn7
   -      1     -    A    21       DFFE  +            1    0    0    3  piobn8
   -      2     -    A    23       DFFE  +            1    0    0    3  piobn9
   -      4     -    F    02       DFFE  +            1    0    0    3  piobn10
   -      3     -    E    18       DFFE  +            1    0    0    3  piocom0
   -      5     -    C    19       DFFE  +            1    0    0    3  piocom1
   -      7     -    C    18       DFFE  +            1    0    0    3  piocom2
   -      1     -    C    07       DFFE  +            1    0    0    3  piocom3
   -      2     -    C    19       DFFE  +            1    0    0    3  piocom4
   -      4     -    E    01       DFFE  +            1    0    0    3  piocom5
   -      1     -    C    10       DFFE  +            1    0    0    3  piocom6
   -      7     -    F    06       DFFE  +            1    0    0    3  piocom7
   -      3     -    F    09       DFFE  +            1    0    0    3  piocom8
   -      2     -    E    17       DFFE  +            1    0    0    3  piocom9
   -      5     -    F    06       DFFE  +            1    0    0    1  piocom10
   -      7     -    F    16       DFFE  +            1    0    0    1  piocom11
   -      8     -    F    13       DFFE  +            1    0    0    1  piocom12
   -      6     -    F    16       DFFE  +            1    0    0    1  piocom13
   -      3     -    B    20       DFFE  +            1    0    0    5  piocom17
   -      1     -    B    24       DFFE  +            1    0    0    4  piocom18
   -      2     -    F    17       DFFE  +            1    2    0   72  piosts0
   -      4     -    F    17       DFFE  +            1    2    0   70  piosts1
   -      3     -    D    05       DFFE  +            0    0    0    1  reset0
   -      2     -    D    05       DFFE  +            0    1    0    1  reset1
   -      5     -    D    05       DFFE  +            0    1    0    1  reset2
   -      3     -    A    23       DFFE  +            0    1    0    1  run
   -      6     -    B    12       DFFE  +            0    3    1    0  :101
   -      4     -    B    21       DFFE  +            0    3    1    0  :102
   -      8     -    B    21       DFFE  +            0    3    1    0  :103
   -      7     -    B    19       DFFE  +            0    3    1    0  :104
   -      1     -    A    23       DFFE  +            0    1    1    0  :105
   -      1     -    D    23       DFFE  +            0    1    1    2  :107
   -      2     -    D    23       DFFE  +            0    4    1    2  :108
   -      2     -    D    16       DFFE  +            0    1    1    0  :109
   -      1     -    F    23        OR2       !       1    1    1    0  :304
   -      6     -    F    17       AND2               2    2    0    2  :311
   -      5     -    F    17        OR2   s           1    3    0    1  ~319~1
   -      3     -    F    17        OR2   s           1    3    0    1  ~322~1
   -      2     -    F    18       AND2   s           4    0    0    1  ~332~1
   -      1     -    F    18       AND2   s           4    0    0    1  ~333~1
   -      7     -    F    10       AND2               0    3    0   15  :343
   -      5     -    F    13       AND2               0    4    0    1  :344
   -      3     -    D    07       AND2               0    4    0    1  :346
   -      3     -    C    06       AND2               0    4    0    1  :347
   -      2     -    D    07       AND2               0    4    0    1  :349
   -      7     -    C    10       AND2               0    4    0    1  :350
   -      4     -    D    16       AND2               0    4    0    1  :355
   -      3     -    C    18       AND2               0    4    0    1  :357
   -      4     -    C    11       AND2               0    4    0    1  :358
   -      1     -    E    01       AND2               0    4    0    1  :360
   -      4     -    C    10       AND2               0    4    0    1  :361
   -      2     -    B    02       AND2   s           0    3    0    1  ~379~1
   -      3     -    B    02       AND2   s           0    4    0    1  ~379~2
   -      4     -    B    02       AND2   s           0    5    0   13  ~379~3
   -      8     -    F    01        OR2               0    4    0   14  :383
   -      3     -    B    07        OR2               0    3    0    1  :394
   -      1     -    B    07        OR2               0    4    0    1  :399
   -      1     -    B    11        OR2               0    4    0    4  :401
   -      3     -    B    06        OR2               0    3    0    1  :410
   -      1     -    B    06        OR2               0    4    0    1  :415
   -      5     -    B    01        OR2               0    4    0    4  :417
   -      5     -    B    14        OR2               0    2    0    1  :423
   -      1     -    B    14        OR2               0    4    0    1  :431
   -      3     -    B    16        OR2               0    4    0    1  :433
   -      4     -    B    07        OR2               0    5    0    1  :444
   -      2     -    B    07        OR2               0    5    0    1  :446
   -      4     -    B    06        OR2               0    5    0    1  :450
   -      2     -    B    06        OR2               0    5    0    1  :452
   -      2     -    B    14        OR2               0    5    0    1  :458
   -      1     -    B    15        OR2               0    3    0    1  :470
   -      3     -    B    03        OR2               0    4    0    1  :474
   -      6     -    B    03       AND2               0    4    0    4  :476
   -      5     -    B    06        OR2               0    3    0    1  :482
   -      1     -    B    03        OR2               0    4    0    1  :486
   -      5     -    B    03       AND2               0    4    0    4  :488
   -      5     -    F    09       AND2               0    2    0    2  :492
   -      1     -    F    05        OR2               0    4    0    1  :498
   -      6     -    F    04       AND2               0    4    0    2  :500
   -      1     -    F    09       AND2               0    4    0    2  :504
   -      2     -    F    13        OR2               0    3    0    1  :510
   -      5     -    F    16       AND2               0    4    0    1  :512
   -      2     -    B    15        OR2               0    5    0    1  :521
   -      4     -    B    03        OR2               0    5    0    1  :523
   -      6     -    B    06        OR2               0    5    0    1  :527
   -      2     -    B    03        OR2               0    5    0    1  :529
   -      2     -    F    05        OR2               0    5    0    1  :535
   -      3     -    F    13        OR2               0    5    0    1  :541
   -      2     -    F    07        OR2               0    4    0   25  :547
   -      1     -    D    05        OR2   s           0    4    0    1  ~551~1
   -      5     -    B    08        OR2   s           0    4    0    1  ~557~1
   -      7     -    B    15        OR2   s           0    4    0    1  ~563~1
   -      7     -    B    14        OR2   s           0    4    0    1  ~565~1
   -      6     -    B    14       AND2               0    2    0    1  :566
   -      4     -    B    08        OR2   s           0    4    0    1  ~569~1
   -      5     -    B    15        OR2   s           0    4    0    1  ~573~1
   -      2     -    B    08        OR2   s           0    4    0    1  ~579~1
   -      4     -    F    06        OR2   s           0    4    0    1  ~585~1
   -      4     -    F    09        OR2   s           0    4    0    1  ~587~1
   -      4     -    F    05       AND2               0    2    0    1  :588
   -      1     -    F    06        OR2   s           0    4    0    1  ~591~1
   -      4     -    F    16        OR2   s           0    4    0    1  ~593~1
   -      7     -    F    13       AND2               0    2    0    1  :594
   -      3     -    F    16        OR2   s           0    4    0    1  ~597~1
   -      6     -    A    11       AND2       !       0    2    0    1  :598
   -      5     -    B    02       AND2   s   !       0    4    0    1  ~615~1
   -      6     -    B    02       AND2   s   !       0    5    0    1  ~615~2
   -      7     -    B    02       AND2               0    5    0    1  :615
   -      2     -    B    18       AND2               0    3    0    4  :626
   -      1     -    B    19        OR2   s           0    4    0    1  ~658~1
   -      3     -    B    21        OR2   s           0    4    0    1  ~661~1
   -      2     -    B    21        OR2   s           0    4    0    1  ~664~1
   -      5     -    B    21        OR2   s           0    4    0    1  ~667~1
   -      7     -    C    22       AND2               0    3    0   11  :686
   -      2     -    E    24       AND2               0    4    0    1  :687
   -      5     -    D    07       AND2               0    4    0    1  :689
   -      2     -    C    06       AND2               0    4    0    1  :690
   -      4     -    D    07       AND2               0    4    0    1  :692
   -      2     -    C    10       AND2               0    4    0    1  :693
   -      4     -    E    24       AND2               0    4    0    1  :698
   -      6     -    C    18       AND2               0    4    0    1  :700
   -      4     -    C    12       AND2               0    4    0    1  :701
   -      3     -    E    01       AND2               0    4    0    1  :703
   -      5     -    E    04       AND2               0    4    0    1  :704
   -      3     -    C    08       AND2   s           0    3    0    1  ~718~1
   -      4     -    C    08       AND2   s           0    4    0    1  ~718~2
   -      5     -    C    08       AND2   s           0    5    0   12  ~718~3
   -      3     -    E    14        OR2               0    4    0   11  :722
   -      3     -    C    03        OR2               0    3    0    1  :733
   -      1     -    C    03        OR2               0    4    0    1  :738
   -      7     -    C    04        OR2               0    4    0    4  :740
   -      3     -    C    02        OR2               0    3    0    1  :749
   -      1     -    C    02        OR2               0    4    0    1  :754
   -      2     -    C    09        OR2               0    4    0    4  :756
   -      1     -    C    16        OR2               0    2    0    1  :762
   -      1     -    C    24        OR2               0    4    0    1  :770
   -      5     -    C    24        OR2               0    4    0    1  :772
   -      4     -    C    03        OR2               0    5    0    1  :783
   -      2     -    C    03        OR2               0    5    0    1  :785
   -      4     -    C    02        OR2               0    5    0    1  :789
   -      2     -    C    02        OR2               0    5    0    1  :791
   -      2     -    C    24        OR2               0    5    0    1  :797
   -      1     -    C    18        OR2               0    3    0    1  :809
   -      1     -    C    12        OR2               0    4    0    1  :813
   -      3     -    C    12       AND2               0    4    0    4  :815
   -      1     -    E    04        OR2               0    3    0    1  :821
   -      3     -    E    04        OR2               0    4    0    1  :825
   -      8     -    E    02       AND2               0    4    0    3  :827
   -      2     -    E    19       AND2               0    2    0    1  :831
   -      1     -    E    15        OR2               0    4    0    1  :837
   -      2     -    C    18        OR2               0    5    0    1  :844
   -      2     -    C    12        OR2               0    5    0    1  :846
   -      2     -    E    04        OR2               0    5    0    1  :850
   -      4     -    E    04        OR2               0    5    0    1  :852
   -      2     -    E    15        OR2               0    5    0    1  :858
   -      1     -    E    03        OR2               0    4    0   21  :862
   -      3     -    C    16        OR2   s           0    4    0    1  ~866~1
   -      4     -    C    19        OR2   s           0    4    0    1  ~872~1
   -      6     -    C    16        OR2   s           0    4    0    1  ~878~1
   -      7     -    C    16        OR2   s           0    4    0    1  ~880~1
   -      6     -    C    24       AND2               0    2    0    1  :881
   -      7     -    C    24        OR2   s           0    4    0    1  ~884~1
   -      7     -    C    19        OR2   s           0    4    0    1  ~888~1
   -      8     -    C    19        OR2   s           0    4    0    1  ~894~1
   -      6     -    E    15        OR2   s           0    4    0    1  ~900~1
   -      3     -    E    19        OR2   s           0    4    0    1  ~902~1
   -      5     -    E    15       AND2               0    2    0    1  :903
   -      5     -    A    05        OR2               0    2    0    1  :906
   -      6     -    C    08       AND2   s           0    4    0    1  ~923~1
   -      7     -    C    08       AND2   s           0    5    0    1  ~923~2
   -      8     -    C    08       AND2               0    5    0    1  :923
   -      6     -    B    09        OR2               0    2    1    0  :932
   -      2     -    A    05        OR2               0    2    0    1  :934
   -      2     -    A    14       AND2   s   !       0    3    0    1  ~972~1
   -      3     -    A    14       AND2   s   !       0    4    0    1  ~972~2
   -      4     -    A    14       AND2   s   !       0    5    0    1  ~972~3
   -      1     -    F    20        OR2   s           0    4    0    1  ~972~4
   -      5     -    A    06       AND2               1    3    0    1  :981
   -      2     -    A    08       AND2               1    3    0    1  :983
   -      2     -    A    11       AND2               1    3    0    1  :984
   -      1     -    A    03       AND2               1    3    0    1  :986
   -      1     -    A    10       AND2               1    3    0    1  :987
   -      6     -    F    24        OR2   s   !       0    4    0    1  ~1006~1
   -      5     -    A    14       AND2   s           0    2    0    1  ~1006~2
   -      6     -    A    14       AND2   s           0    4    0    1  ~1006~3
   -      7     -    A    14       AND2   s           0    5    0    1  ~1006~4
   -      8     -    A    14        OR2               0    4    0   17  :1007
   -      3     -    A    08        OR2               0    4    0    5  :1009
   -      5     -    A    20       AND2   s           0    0    0    1  ~1022~2
   -      7     -    A    20       AND2   s           0    0    0    1  ~1027~2
   -      2     -    A    22       AND2   s           0    0    0    1  ~1038~2
   -      4     -    A    22       AND2   s           0    0    0    1  ~1043~2
   -      6     -    A    22       AND2   s           0    0    0    4  ~1049~1
   -      1     -    A    12        OR2               0    3    0    1  :1057
   -      3     -    F    03        OR2               0    3    0    2  :1059
   -      3     -    F    21        OR2               0    4    0    2  :1065
   -      1     -    F    03        OR2               0    4    0    1  :1073
   -      7     -    F    21        OR2               0    3    0    1  :1075
   -      2     -    A    12        OR2               0    5    0    1  :1100
   -      2     -    F    03        OR2               0    5    0    1  :1106
   -      1     -    A    24        OR2   s   !       0    4    0    1  ~1116~1
   -      8     -    A    17        OR2   s   !       1    3    0    1  ~1118~1
   -      1     -    A    20        OR2   s   !       0    4    0    1  ~1120~1
   -      2     -    A    20        OR2   s   !       0    4    0    1  ~1122~1
   -      5     -    A    13        OR2   s   !       1    3    0    1  ~1124~1
   -      7     -    A    22        OR2   s   !       0    4    0    1  ~1126~1
   -      8     -    A    22        OR2   s   !       0    4    0    1  ~1128~1
   -      4     -    A    12        OR2   s           1    3    0    1  ~1130~1
   -      6     -    A    12       AND2               0    3    0    1  :1131
   -      4     -    F    03        OR2   s           0    4    0    1  ~1134~1
   -      4     -    F    21        OR2   s           1    3    0    1  ~1136~1
   -      7     -    F    03       AND2               0    3    0    1  :1137
   -      2     -    A    24        OR2   s           1    3    0    1  ~1140~1
   -      6     -    E    16       AND2               0    3    0   11  :1145
   -      6     -    E    20       AND2               0    4    0    1  :1146
   -      1     -    D    07       AND2               0    4    0    1  :1148
   -      1     -    C    06       AND2               0    4    0    1  :1149
   -      7     -    D    07       AND2               0    4    0    1  :1151
   -      3     -    C    10       AND2               0    4    0    1  :1152
   -      7     -    E    24       AND2               0    4    0    1  :1157
   -      4     -    C    18       AND2               0    4    0    1  :1159
   -      1     -    C    04       AND2               0    4    0    1  :1160
   -      5     -    E    01       AND2               0    4    0    1  :1162
   -      6     -    E    08       AND2               0    4    0    1  :1163
   -      1     -    D    21       AND2   s           0    3    0    1  ~1177~1
   -      2     -    D    21       AND2   s           0    4    0    1  ~1177~2
   -      3     -    D    21       AND2   s           0    5    0   12  ~1177~3
   -      4     -    D    14        OR2               0    4    0   11  :1181
   -      1     -    D    10        OR2               0    3    0    1  :1192
   -      3     -    D    10        OR2               0    4    0    1  :1197
   -      1     -    D    03        OR2               0    4    0    4  :1199
   -      3     -    D    11        OR2               0    3    0    1  :1208
   -      1     -    D    11        OR2               0    4    0    1  :1213
   -      6     -    D    06        OR2               0    4    0    4  :1215
   -      5     -    D    22        OR2               0    2    0    1  :1221
   -      1     -    D    15        OR2               0    4    0    1  :1229
   -      7     -    D    21        OR2               0    4    0    1  :1231
   -      2     -    D    10        OR2               0    5    0    1  :1242
   -      4     -    D    10        OR2               0    5    0    1  :1244
   -      4     -    D    11        OR2               0    5    0    1  :1248
   -      2     -    D    11        OR2               0    5    0    1  :1250
   -      2     -    D    15        OR2               0    5    0    1  :1256
   -      3     -    E    09        OR2               0    3    0    1  :1268
   -      1     -    E    09        OR2               0    4    0    1  :1272
   -      5     -    E    09       AND2               0    4    0    4  :1274
   -      3     -    E    08        OR2               0    3    0    1  :1280
   -      1     -    E    08        OR2               0    4    0    1  :1284
   -      2     -    E    11       AND2               0    4    0    3  :1286
   -      2     -    E    22       AND2               0    2    0    1  :1290
   -      1     -    E    20        OR2               0    4    0    1  :1296
   -      4     -    E    09        OR2               0    5    0    1  :1303
   -      2     -    E    09        OR2               0    5    0    1  :1305
   -      4     -    E    08        OR2               0    5    0    1  :1309
   -      2     -    E    08        OR2               0    5    0    1  :1311
   -      2     -    E    20        OR2               0    5    0    1  :1317
   -      2     -    D    02        OR2               0    4    0   21  :1321
   -      7     -    D    15        OR2   s           0    4    0    1  ~1325~1
   -      1     -    D    04        OR2   s           0    4    0    1  ~1331~1
   -      4     -    D    22        OR2   s           0    4    0    1  ~1337~1
   -      3     -    D    22        OR2   s           0    4    0    1  ~1339~1
   -      6     -    D    15       AND2               0    2    0    1  :1340
   -      6     -    D    21        OR2   s           0    4    0    1  ~1343~1
   -      3     -    E    22        OR2   s           0    4    0    1  ~1347~1
   -      1     -    E    05        OR2   s           0    4    0    1  ~1353~1
   -      5     -    E    22        OR2   s           0    4    0    1  ~1359~1
   -      6     -    E    22        OR2   s           0    4    0    1  ~1361~1
   -      4     -    E    20       AND2               0    2    0    1  :1362
   -      4     -    D    21       AND2   s           0    4    0    2  ~1373~1
   -      4     -    D    17       AND2   s           0    3    0    2  ~1373~2
   -      3     -    D    17       AND2   s           0    4    0    2  ~1373~3
   -      1     -    D    17        OR2       !       0    4    1    0  :1375
   -      4     -    D    23        OR2   s           0    3    0    1  ~1392~1
   -      3     -    D    16        OR2   s           0    3    0    1  ~1406~1
   -      1     -    B    09        OR2       !       0    3    0    1  :1466
   -      5     -    A    16        OR2               0    4    1    0  :1472
   -      2     -    A    16        OR2               0    4    1    0  :1475
   -      5     -    E    21        OR2               0    4    1    0  :1478
   -      6     -    A    09        OR2               0    4    1    0  :1481
   -      6     -    A    16        OR2               0    4    1    0  :1484
   -      4     -    A    02        OR2               0    4    1    0  :1487
   -      8     -    A    07        OR2               0    4    1    0  :1490
   -      5     -    F    08        OR2               0    4    1    0  :1493
   -      2     -    A    01        OR2               0    4    1    0  :1496
   -      6     -    F    12        OR2               0    4    1    0  :1499
   -      1     -    F    21        OR2               0    4    1    0  :1502
   -      1     -    F    17        OR2               0    4    1    0  :1505
   -      1     -    F    13        OR2               0    4    1    0  :1508
   -      1     -    F    16        OR2               0    4    1    0  :1511
   -      1     -    F    11       AND2               0    2    1    0  :1520
   -      2     -    F    11       AND2               0    2    1    0  :1523
   -      3     -    E    24        OR2               0    4    1    0  :1526
   -      1     -    C    11        OR2               0    4    1    0  :1529
   -      7     -    C    01        OR2               0    4    1    0  :1532
   -      5     -    C    12        OR2               0    4    1    0  :1535
   -      4     -    C    05        OR2               0    4    1    0  :1538
   -      5     -    E    12        OR2               0    4    1    0  :1541
   -      6     -    E    10        OR2               0    4    1    0  :1544
   -      8     -    E    07        OR2               0    4    1    0  :1547
   -      5     -    E    06        OR2               0    4    1    0  :1550
   -      7     -    E    20        OR2               0    4    1    0  :1553
   -      2     -    B    09        OR2       !       0    5    0    1  :1555
   -      3     -    A    20        OR2               1    4    0    1  :1017
   -      5     -    A    20       AND2   s           0    1    0    1  ~1022~1
   -      4     -    A    20        OR2               1    4    0    1  :1022
   -      7     -    A    20       AND2   s           0    1    0    1  ~1027~1
   -      6     -    A    20        OR2               1    4    0    1  :1027
   -      8     -    A    20        OR2               1    4    0    1  :1033
   -      2     -    A    22       AND2   s           0    1    0    1  ~1038~1
   -      1     -    A    22        OR2               1    4    0    1  :1038
   -      4     -    A    22       AND2   s           0    1    0    1  ~1043~1
   -      3     -    A    22        OR2               1    4    0    1  :1043
   -      5     -    A    22        OR2               1    4    0    1  :1049


Code:

s = Synthesized pin or logic cell
+ = Synchronous flipflop
/ = Slow slew-rate output
! = NOT gate push-back
r = Fitter-inserted logic cell
^ = Increased input delay
$ = Driven by fast output logic cell
p = Packed register


Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

** FASTTRACK INTERCONNECT UTILIZATION **

Row FastTrack Interconnect:

          Global         Left Half-      Right Half-
         FastTrack       FastTrack       FastTrack 
Row     Interconnect    Interconnect    Interconnect    Input Pins     Output Pins     Bidir Pins
A:      31/ 96( 32%)    10/ 48( 20%)    18/ 48( 37%)    3/16( 18%)      8/16( 50%)     0/16(  0%)
B:      23/ 96( 23%)    29/ 48( 60%)    12/ 48( 25%)    1/16(  6%)      6/16( 37%)     0/16(  0%)
C:      29/ 96( 30%)    17/ 48( 35%)     5/ 48( 10%)    3/16( 18%)      4/16( 25%)     0/16(  0%)
D:      23/ 96( 23%)     8/ 48( 16%)    11/ 48( 22%)    0/16(  0%)      0/16(  0%)     0/16(  0%)
E:      28/ 96( 29%)    15/ 48( 31%)    12/ 48( 25%)    2/16( 12%)      7/16( 43%)     0/16(  0%)
F:      36/ 96( 37%)     8/ 48( 16%)     6/ 48( 12%)    9/16( 56%)      2/16( 12%)     0/16(  0%)


Column FastTrack Interconnect:

         FastTrack                                 
Column  Interconnect    Input Pins     Output Pins     Bidir Pins
01:      7/24( 29%)     2/4( 50%)      0/4(  0%)       0/4(  0%)
02:      3/24( 12%)     1/4( 25%)      0/4(  0%)       0/4(  0%)
03:      5/24( 20%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
04:      3/24( 12%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
05:      3/24( 12%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
06:      6/24( 25%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
07:      5/24( 20%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
08:      4/24( 16%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
09:      3/24( 12%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
10:      7/24( 29%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
11:      4/24( 16%)     0/4(  0%)      1/4( 25%)       0/4(  0%)
12:      4/24( 16%)     0/4(  0%)      1/4( 25%)       0/4(  0%)
13:      6/24( 25%)     4/4(100%)      0/4(  0%)       0/4(  0%)
14:      5/24( 20%)     1/4( 25%)      1/4( 25%)       0/4(  0%)
15:      5/24( 20%)     0/4(  0%)      2/4( 50%)       0/4(  0%)
16:      3/24( 12%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
17:      3/24( 12%)     0/4(  0%)      1/4( 25%)       0/4(  0%)
18:      6/24( 25%)     0/4(  0%)      1/4( 25%)       0/4(  0%)
19:      4/24( 16%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
20:      5/24( 20%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
21:      4/24( 16%)     0/4(  0%)      0/4(  0%)       0/4(  0%)
22:      4/24( 16%)     0/4(  0%)      1/4( 25%)       0/4(  0%)
23:      5/24( 20%)     0/4(  0%)      2/4( 50%)       0/4(  0%)
24:      4/24( 16%)     0/4(  0%)      2/4( 50%)       0/4(  0%)
EA:      0/24(  0%)     0/4(  0%)      0/4(  0%)       0/4(  0%)


Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

** CLOCK SIGNALS **

Type     Fan-out       Name
INPUT      155         hl_clk


Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

** CLEAR SIGNALS **

Type     Fan-out       Name
DFF          1         reset2


Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

** CARRY CHAINS **

Type             Member Length   Member Name: SUM, (CARRY)
UP/DOWN COUNTER        1         ncnt1, (:1017)
UP/DOWN COUNTER        2         ncnt2, (:1022)
ARITHMETIC             3         ~1022~2, (~1022~1)
UP/DOWN COUNTER        4         ncnt3, (:1027)
ARITHMETIC             5         ~1027~2, (~1027~1)
UP/DOWN COUNTER        6         ncnt4, (:1033)
UP/DOWN COUNTER        7         ncnt5, (:1038)
ARITHMETIC             8         ~1038~2, (~1038~1)
UP/DOWN COUNTER        9         ncnt6, (:1043)
ARITHMETIC            10         ~1043~2, (~1043~1)
UP/DOWN COUNTER       11         ncnt7, (:1049)
NORMAL                12         ~1049~1



Device-Specific Information:                       e:\usr\hamada\intf\intf.rpt
intf

** EQUATIONS **

hl_clk   : INPUT;
hl_data0 : INPUT;
hl_data1 : INPUT;
hl_data2 : INPUT;
hl_data3 : INPUT;
hl_data4 : INPUT;
hl_data5 : INPUT;
hl_data6 : INPUT;
hl_data7 : INPUT;
hl_data8 : INPUT;
hl_data9 : INPUT;
hl_data10 : INPUT;
hl_data11 : INPUT;
hl_data12 : INPUT;
hl_data13 : INPUT;
hl_data14 : INPUT;
hl_data15 : INPUT;
hl_data16 : INPUT;
hl_data17 : INPUT;
hl_data18 : INPUT;
hl_data19 : INPUT;
hl_data20 : INPUT;
hl_data21 : INPUT;
hl_data22 : INPUT;
hl_data23 : INPUT;
hl_data24 : INPUT;
hl_data28 : INPUT;
hl_data29 : INPUT;
hl_data30 : INPUT;
hl_data31 : INPUT;
hl_dma_ack : INPUT;
hl_io_req : INPUT;

-- Node name is 'adr_drram0' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram0', location is LC1_D16, type is buried.
adr_drram0 = DFFE( _EQ001, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ001 = !adr_drram0 &  _LC8_F1
         #  adr_drram0 &  _LC2_F7
         #  _LC4_D16;

-- Node name is 'adr_drram1' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram1', location is LC6_B15, type is buried.
adr_drram1 = DFFE( _EQ002, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ002 =  _LC5_B15
         #  _LC7_F10 &  piocom1;

-- Node name is 'adr_drram2' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram2', location is LC3_B15, type is buried.
adr_drram2 = DFFE( _EQ003, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ003 =  _LC2_B15
         #  adr_drram2 &  _LC2_F7
         #  _LC3_C18;

-- Node name is 'adr_drram3' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram3', location is LC7_B3, type is buried.
adr_drram3 = DFFE( _EQ004, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ004 =  _LC4_B3
         #  adr_drram3 &  _LC2_F7
         #  _LC4_C11;

-- Node name is 'adr_drram4' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram4', location is LC6_B8, type is buried.
adr_drram4 = DFFE( _EQ005, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ005 =  _LC2_B8
         #  _LC7_F10 &  piocom4;

-- Node name is 'adr_drram5' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram5', location is LC7_B6, type is buried.
adr_drram5 = DFFE( _EQ006, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ006 =  _LC6_B6
         #  adr_drram5 &  _LC2_F7
         #  _LC1_E1;

-- Node name is 'adr_drram6' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram6', location is LC8_B3, type is buried.
adr_drram6 = DFFE( _EQ007, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ007 =  _LC2_B3
         #  adr_drram6 &  _LC2_F7
         #  _LC4_C10;

-- Node name is 'adr_drram7' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram7', location is LC2_F6, type is buried.
adr_drram7 = DFFE( _EQ008, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ008 =  _LC4_F6
         #  _LC7_F10 &  piocom7;

-- Node name is 'adr_drram8' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram8', location is LC2_F9, type is buried.
adr_drram8 = DFFE( _EQ009, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ009 =  adr_drram8 & !_LC5_F9 &  _LC8_F1
         # !adr_drram8 &  _LC5_F9 &  _LC8_F1
         #  _LC4_F9;

-- Node name is 'adr_drram9' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram9', location is LC3_F5, type is buried.
adr_drram9 = DFFE( _EQ010, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ010 =  _LC2_F5
         #  _LC4_F5
         #  _LC7_F10 &  piocom9;

-- Node name is 'adr_drram10' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram10', location is LC3_F6, type is buried.
adr_drram10 = DFFE( _EQ011, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ011 =  _LC1_F6
         #  _LC7_F10 &  piocom10;

-- Node name is 'adr_drram11' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram11', location is LC8_F16, type is buried.
adr_drram11 = DFFE( _EQ012, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ012 =  adr_drram11 & !_LC1_F9 &  _LC8_F1
         # !adr_drram11 &  _LC1_F9 &  _LC8_F1
         #  _LC4_F16;

-- Node name is 'adr_drram12' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram12', location is LC4_F13, type is buried.
adr_drram12 = DFFE( _EQ013, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ013 =  _LC3_F13
         #  _LC7_F13
         #  _LC7_F10 &  piocom12;

-- Node name is 'adr_drram13' from file "intf.tdf" line 46, column 48
-- Equation name is 'adr_drram13', location is LC2_F16, type is buried.
adr_drram13 = DFFE( _EQ014, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ014 =  _LC3_F16
         #  _LC7_F10 &  piocom13;

-- Node name is 'adr_drreg0' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg0', location is LC5_E24, type is buried.
adr_drreg0 = DFFE( _EQ015, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ015 = !adr_drreg0 &  _LC3_E14
         #  adr_drreg0 &  _LC1_E3
         #  _LC4_E24;

-- Node name is 'adr_drreg1' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg1', location is LC3_C19, type is buried.
adr_drreg1 = DFFE( _EQ016, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ016 =  _LC7_C19
         #  _LC7_C22 &  piocom1;

-- Node name is 'adr_drreg2' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg2', location is LC5_C18, type is buried.
adr_drreg2 = DFFE( _EQ017, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ017 =  _LC2_C18
         #  adr_drreg2 &  _LC1_E3
         #  _LC6_C18;

-- Node name is 'adr_drreg3' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg3', location is LC6_C12, type is buried.
adr_drreg3 = DFFE( _EQ018, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ018 =  _LC2_C12
         #  adr_drreg3 &  _LC1_E3
         #  _LC4_C12;

-- Node name is 'adr_drreg4' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg4', location is LC6_C19, type is buried.
adr_drreg4 = DFFE( _EQ019, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ019 =  _LC8_C19
         #  _LC7_C22 &  piocom4;

-- Node name is 'adr_drreg5' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg5', location is LC2_E1, type is buried.
adr_drreg5 = DFFE( _EQ020, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ020 =  _LC2_E4
         #  adr_drreg5 &  _LC1_E3
         #  _LC3_E1;

-- Node name is 'adr_drreg6' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg6', location is LC7_E4, type is buried.
adr_drreg6 = DFFE( _EQ021, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ021 =  _LC4_E4
         #  adr_drreg6 &  _LC1_E3
         #  _LC5_E4;

-- Node name is 'adr_drreg7' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg7', location is LC3_E15, type is buried.
adr_drreg7 = DFFE( _EQ022, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ022 =  _LC6_E15
         #  _LC7_C22 &  piocom7;

-- Node name is 'adr_drreg8' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg8', location is LC1_E19, type is buried.
adr_drreg8 = DFFE( _EQ023, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ023 =  adr_drreg8 & !_LC2_E19 &  _LC3_E14
         # !adr_drreg8 &  _LC2_E19 &  _LC3_E14
         #  _LC3_E19;

-- Node name is 'adr_drreg9' from file "intf.tdf" line 51, column 33
-- Equation name is 'adr_drreg9', location is LC4_E15, type is buried.
adr_drreg9 = DFFE( _EQ024, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ024 =  _LC2_E15
         #  _LC5_E15
         #  _LC7_C22 &  piocom9;

-- Node name is 'adr_dwreg0' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg0', location is LC1_E24, type is buried.
adr_dwreg0 = DFFE( _EQ025, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ025 = !adr_dwreg0 &  _LC4_D14
         #  adr_dwreg0 &  _LC2_D2
         #  _LC7_E24;

-- Node name is 'adr_dwreg1' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg1', location is LC1_E22, type is buried.
adr_dwreg1 = DFFE( _EQ026, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ026 =  _LC3_E22
         #  _LC6_E16 &  piocom1;

-- Node name is 'adr_dwreg2' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg2', location is LC7_E9, type is buried.
adr_dwreg2 = DFFE( _EQ027, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ027 =  _LC4_E9
         #  adr_dwreg2 &  _LC2_D2
         #  _LC4_C18;

-- Node name is 'adr_dwreg3' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg3', location is LC6_E9, type is buried.
adr_dwreg3 = DFFE( _EQ028, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ028 =  _LC2_E9
         #  adr_dwreg3 &  _LC2_D2
         #  _LC1_C4;

-- Node name is 'adr_dwreg4' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg4', location is LC2_E5, type is buried.
adr_dwreg4 = DFFE( _EQ029, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ029 =  _LC1_E5
         #  _LC6_E16 &  piocom4;

-- Node name is 'adr_dwreg5' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg5', location is LC8_E8, type is buried.
adr_dwreg5 = DFFE( _EQ030, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ030 =  _LC4_E8
         #  adr_dwreg5 &  _LC2_D2
         #  _LC5_E1;

-- Node name is 'adr_dwreg6' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg6', location is LC5_E8, type is buried.
adr_dwreg6 = DFFE( _EQ031, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ031 =  _LC2_E8
         #  adr_dwreg6 &  _LC2_D2
         #  _LC6_E8;

-- Node name is 'adr_dwreg7' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg7', location is LC4_E22, type is buried.
adr_dwreg7 = DFFE( _EQ032, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ032 =  _LC5_E22
         #  _LC6_E16 &  piocom7;

-- Node name is 'adr_dwreg8' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg8', location is LC7_E22, type is buried.
adr_dwreg8 = DFFE( _EQ033, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ033 =  adr_dwreg8 & !_LC2_E22 &  _LC4_D14
         # !adr_dwreg8 &  _LC2_E22 &  _LC4_D14
         #  _LC6_E22;

-- Node name is 'adr_dwreg9' from file "intf.tdf" line 57, column 33
-- Equation name is 'adr_dwreg9', location is LC5_E20, type is buried.
adr_dwreg9 = DFFE( _EQ034, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ034 =  _LC2_E20
         #  _LC4_E20
         #  _LC6_E16 &  piocom9;

-- Node name is 'bncnt_drram0' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram0', location is LC6_F13, type is buried.
bncnt_drram0 = DFFE( _EQ035, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ035 = !bncnt_drram0 &  _LC8_F1
         #  bncnt_drram0 &  _LC2_F7
         #  _LC5_F13;

-- Node name is 'bncnt_drram1' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram1', location is LC4_D5, type is buried.
bncnt_drram1 = DFFE( _EQ036, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ036 =  _LC1_D5
         #  _LC7_F10 &  piobn1;

-- Node name is 'bncnt_drram2' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram2', location is LC5_B7, type is buried.
bncnt_drram2 = DFFE( _EQ037, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ037 =  _LC4_B7
         #  bncnt_drram2 &  _LC2_F7
         #  _LC3_D7;

-- Node name is 'bncnt_drram3' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram3', location is LC7_B7, type is buried.
bncnt_drram3 = DFFE( _EQ038, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ038 =  _LC2_B7
         #  bncnt_drram3 &  _LC2_F7
         #  _LC3_C6;

-- Node name is 'bncnt_drram4' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram4', location is LC1_B8, type is buried.
bncnt_drram4 = DFFE( _EQ039, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ039 =  _LC5_B8
         #  _LC7_F10 &  piobn4;

-- Node name is 'bncnt_drram5' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram5', location is LC8_B6, type is buried.
bncnt_drram5 = DFFE( _EQ040, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ040 =  _LC4_B6
         #  bncnt_drram5 &  _LC2_F7
         #  _LC2_D7;

-- Node name is 'bncnt_drram6' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram6', location is LC1_B10, type is buried.
bncnt_drram6 = DFFE( _EQ041, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ041 =  _LC2_B6
         #  bncnt_drram6 &  _LC2_F7
         #  _LC7_C10;

-- Node name is 'bncnt_drram7' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram7', location is LC4_B15, type is buried.
bncnt_drram7 = DFFE( _EQ042, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ042 =  _LC7_B15
         #  _LC7_F10 &  piobn7;

-- Node name is 'bncnt_drram8' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram8', location is LC3_B14, type is buried.
bncnt_drram8 = DFFE( _EQ043, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ043 = !bncnt_drram8 & !_LC5_B14 &  _LC8_F1
         #  bncnt_drram8 &  _LC5_B14 &  _LC8_F1
         #  _LC7_B14;

-- Node name is 'bncnt_drram9' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram9', location is LC4_B14, type is buried.
bncnt_drram9 = DFFE( _EQ044, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ044 =  _LC2_B14
         #  _LC6_B14
         #  _LC7_F10 &  piobn9;

-- Node name is 'bncnt_drram10' from file "intf.tdf" line 46, column 16
-- Equation name is 'bncnt_drram10', location is LC3_B8, type is buried.
bncnt_drram10 = DFFE( _EQ045, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ045 =  _LC4_B8
         #  _LC7_F10 &  piobn10;

-- Node name is 'bncnt_drreg0' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg0', location is LC6_E24, type is buried.
bncnt_drreg0 = DFFE( _EQ046, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ046 = !bncnt_drreg0 &  _LC3_E14
         #  bncnt_drreg0 &  _LC1_E3
         #  _LC2_E24;

-- Node name is 'bncnt_drreg1' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg1', location is LC2_C16, type is buried.
bncnt_drreg1 = DFFE( _EQ047, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ047 =  _LC3_C16
         #  _LC7_C22 &  piobn1;

-- Node name is 'bncnt_drreg2' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg2', location is LC5_C3, type is buried.
bncnt_drreg2 = DFFE( _EQ048, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ048 =  _LC4_C3
         #  bncnt_drreg2 &  _LC1_E3
         #  _LC5_D7;

-- Node name is 'bncnt_drreg3' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg3', location is LC8_C3, type is buried.
bncnt_drreg3 = DFFE( _EQ049, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ049 =  _LC2_C3
         #  bncnt_drreg3 &  _LC1_E3
         #  _LC2_C6;

-- Node name is 'bncnt_drreg4' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg4', location is LC1_C19, type is buried.
bncnt_drreg4 = DFFE( _EQ050, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ050 =  _LC4_C19
         #  _LC7_C22 &  piobn4;

-- Node name is 'bncnt_drreg5' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg5', location is LC7_C2, type is buried.
bncnt_drreg5 = DFFE( _EQ051, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ051 =  _LC4_C2
         #  bncnt_drreg5 &  _LC1_E3
         #  _LC4_D7;

-- Node name is 'bncnt_drreg6' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg6', location is LC5_C2, type is buried.
bncnt_drreg6 = DFFE( _EQ052, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ052 =  _LC2_C2
         #  bncnt_drreg6 &  _LC1_E3
         #  _LC2_C10;

-- Node name is 'bncnt_drreg7' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg7', location is LC5_C16, type is buried.
bncnt_drreg7 = DFFE( _EQ053, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ053 =  _LC6_C16
         #  _LC7_C22 &  piobn7;

-- Node name is 'bncnt_drreg8' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg8', location is LC4_C16, type is buried.
bncnt_drreg8 = DFFE( _EQ054, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ054 = !bncnt_drreg8 & !_LC1_C16 &  _LC3_E14
         #  bncnt_drreg8 &  _LC1_C16 &  _LC3_E14
         #  _LC7_C16;

-- Node name is 'bncnt_drreg9' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg9', location is LC3_C24, type is buried.
bncnt_drreg9 = DFFE( _EQ055, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ055 =  _LC2_C24
         #  _LC6_C24
         #  _LC7_C22 &  piobn9;

-- Node name is 'bncnt_drreg10' from file "intf.tdf" line 51, column 16
-- Equation name is 'bncnt_drreg10', location is LC4_C24, type is buried.
bncnt_drreg10 = DFFE( _EQ056, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ056 =  _LC7_C24
         #  _LC7_C22 &  piobn10;

-- Node name is 'bncnt_dwreg0' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg0', location is LC3_E20, type is buried.
bncnt_dwreg0 = DFFE( _EQ057, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ057 = !bncnt_dwreg0 &  _LC4_D14
         #  bncnt_dwreg0 &  _LC2_D2
         #  _LC6_E20;

-- Node name is 'bncnt_dwreg1' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg1', location is LC3_D15, type is buried.
bncnt_dwreg1 = DFFE( _EQ058, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ058 =  _LC7_D15
         #  _LC6_E16 &  piobn1;

-- Node name is 'bncnt_dwreg2' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg2', location is LC6_D10, type is buried.
bncnt_dwreg2 = DFFE( _EQ059, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ059 =  _LC2_D10
         #  bncnt_dwreg2 &  _LC2_D2
         #  _LC1_D7;

-- Node name is 'bncnt_dwreg3' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg3', location is LC5_D10, type is buried.
bncnt_dwreg3 = DFFE( _EQ060, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ060 =  _LC4_D10
         #  bncnt_dwreg3 &  _LC2_D2
         #  _LC1_C6;

-- Node name is 'bncnt_dwreg4' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg4', location is LC4_D4, type is buried.
bncnt_dwreg4 = DFFE( _EQ061, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ061 =  _LC1_D4
         #  _LC6_E16 &  piobn4;

-- Node name is 'bncnt_dwreg5' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg5', location is LC5_D11, type is buried.
bncnt_dwreg5 = DFFE( _EQ062, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ062 =  _LC4_D11
         #  bncnt_dwreg5 &  _LC2_D2
         #  _LC7_D7;

-- Node name is 'bncnt_dwreg6' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg6', location is LC6_D11, type is buried.
bncnt_dwreg6 = DFFE( _EQ063, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ063 =  _LC2_D11
         #  bncnt_dwreg6 &  _LC2_D2
         #  _LC3_C10;

-- Node name is 'bncnt_dwreg7' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg7', location is LC2_D22, type is buried.
bncnt_dwreg7 = DFFE( _EQ064, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ064 =  _LC4_D22
         #  _LC6_E16 &  piobn7;

-- Node name is 'bncnt_dwreg8' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg8', location is LC1_D22, type is buried.
bncnt_dwreg8 = DFFE( _EQ065, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ065 = !bncnt_dwreg8 &  _LC4_D14 & !_LC5_D22
         #  bncnt_dwreg8 &  _LC4_D14 &  _LC5_D22
         #  _LC3_D22;

-- Node name is 'bncnt_dwreg9' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg9', location is LC4_D15, type is buried.
bncnt_dwreg9 = DFFE( _EQ066, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ066 =  _LC2_D15
         #  _LC6_D15
         #  _LC6_E16 &  piobn9;

-- Node name is 'bncnt_dwreg10' from file "intf.tdf" line 57, column 16
-- Equation name is 'bncnt_dwreg10', location is LC5_D21, type is buried.
bncnt_dwreg10 = DFFE( _EQ067, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ067 =  _LC6_D21
         #  _LC6_E16 &  piobn10;

-- Node name is 'ce' from file "intf.tdf" line 53, column 32
-- Equation name is 'ce', location is LC3_A6, type is buried.
ce       = DFFE( _EQ068, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ068 =  ce &  _LC4_A14
         #  ce &  _LC1_F20
         #  cstart;

-- Node name is 'cstart' from file "intf.tdf" line 280, column 45
-- Equation name is 'cstart', location is LC1_A6, type is buried.
cstart   = LCELL( _EQ069);
  _EQ069 = !dmaack_drns & !dmar_drns &  nors;

-- Node name is 'cs0' from file "intf.tdf" line 43, column 7
-- Equation name is 'cs0', location is LC3_F18, type is buried.
cs0      = DFFE( _EQ070, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ070 =  cs0 & !io_req6
         #  cs0 &  io_req5
         # !io_req5 &  io_req6 &  _LC2_F18;

-- Node name is 'cs1' from file "intf.tdf" line 43, column 7
-- Equation name is 'cs1', location is LC5_F18, type is buried.
cs1      = DFFE( _EQ071, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ071 =  cs1 & !io_req6
         #  cs1 &  io_req5
         # !io_req5 &  io_req6 &  _LC1_F18;

-- Node name is 'dmaack_drns' from file "intf.tdf" line 53, column 5
-- Equation name is 'dmaack_drns', location is LC6_A4, type is buried.
dmaack_drns = DFFE( hl_dma_ack, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'dmaack_drram' from file "intf.tdf" line 46, column 25
-- Equation name is 'dmaack_drram', location is LC4_A4, type is buried.
dmaack_drram = DFFE( hl_dma_ack, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'dmaack_drreg' from file "intf.tdf" line 50, column 5
-- Equation name is 'dmaack_drreg', location is LC3_A4, type is buried.
dmaack_drreg = DFFE( hl_dma_ack, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'dmar_drns' from file "intf.tdf" line 53, column 17
-- Equation name is 'dmar_drns', location is LC1_A5, type is buried.
dmar_drns = DFFE( _EQ072, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ072 =  _LC2_A5 &  pio
         #  dmar_drns & !pio
         # !dmaack_drns & !pio;

-- Node name is 'dmar_drram' from file "intf.tdf" line 47, column 18
-- Equation name is 'dmar_drram', location is LC8_B2, type is buried.
!dmar_drram = dmar_drram~NOT;
dmar_drram~NOT = DFFE( _EQ073, GLOBAL( hl_clk),  reset2,  VCC,  VCC);
  _EQ073 = !dmar_drram & !_LC6_A11 & !_LC7_B2
         # !_LC6_A11 &  pio
         # !dmar_drram & !_LC7_B2 & !pio;

-- Node name is 'dmar_drram0' from file "intf.tdf" line 47, column 5
-- Equation name is 'dmar_drram0', location is LC7_B5, type is buried.
dmar_drram0 = DFFE( dmar_drram, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'dmar_drreg' from file "intf.tdf" line 50, column 18
-- Equation name is 'dmar_drreg', location is LC2_C8, type is buried.
dmar_drreg = DFFE( _EQ074, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ074 =  dmar_drreg & !pio
         #  _LC8_C8 & !pio
         #  _LC5_A5 &  pio;

-- Node name is 'd_write0' from file "intf.tdf" line 58, column 12
-- Equation name is 'd_write0', location is LC6_D17, type is buried.
d_write0 = DFFE( _EQ075, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ075 =  _LC3_D17 &  _LC4_D17 &  _LC4_D21
         #  img_dma_ack5;

-- Node name is 'd_write1' from file "intf.tdf" line 58, column 12
-- Equation name is 'd_write1', location is LC5_D17, type is buried.
d_write1 = DFFE( d_write0, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'd_write2' from file "intf.tdf" line 58, column 12
-- Equation name is 'd_write2', location is LC2_D17, type is buried.
d_write2 = DFFE( d_write1, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'hl_calc_sts' from file "intf.tdf" line 302, column 5
-- Equation name is 'hl_calc_sts', type is output 
hl_calc_sts =  ce;

-- Node name is 'hl_dma_r' from file "intf.tdf" line 391, column 9
-- Equation name is 'hl_dma_r', type is output 
hl_dma_r = !_LC5_B22;

-- Node name is 'hl_dma_r~fit~in1' from file "intf.tdf" line 391, column 9
-- Equation name is 'hl_dma_r~fit~in1', location is LC5_B22, type is buried.
-- synthesized logic cell 
_LC5_B22 = LCELL(!_LC2_B9);

-- Node name is 'hl_dma_w' from file "intf.tdf" line 59, column 16
-- Equation name is 'hl_dma_w', type is output 
hl_dma_w =  _LC2_D23;

-- Node name is 'hl_d_read' from file "intf.tdf" line 101, column 5
-- Equation name is 'hl_d_read', type is output 
hl_d_read = !_LC1_F23;

-- Node name is 'hl_d_write' from file "intf.tdf" line 59, column 5
-- Equation name is 'hl_d_write', type is output 
hl_d_write =  _LC1_D23;

-- Node name is 'img_dma_ack0' from file "intf.tdf" line 63, column 13
-- Equation name is 'img_dma_ack0', location is LC5_D23, type is buried.
img_dma_ack0 = DFFE( _LC2_D23, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'img_dma_ack1' from file "intf.tdf" line 63, column 13
-- Equation name is 'img_dma_ack1', location is LC6_D23, type is buried.
img_dma_ack1 = DFFE( img_dma_ack0, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'img_dma_ack2' from file "intf.tdf" line 63, column 13
-- Equation name is 'img_dma_ack2', location is LC7_D23, type is buried.
img_dma_ack2 = DFFE( img_dma_ack1, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'img_dma_ack3' from file "intf.tdf" line 63, column 13
-- Equation name is 'img_dma_ack3', location is LC3_D23, type is buried.
img_dma_ack3 = DFFE( img_dma_ack2, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'img_dma_ack4' from file "intf.tdf" line 63, column 13
-- Equation name is 'img_dma_ack4', location is LC8_D15, type is buried.
img_dma_ack4 = DFFE( img_dma_ack3, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'img_dma_ack5' from file "intf.tdf" line 63, column 13
-- Equation name is 'img_dma_ack5', location is LC5_D15, type is buried.
img_dma_ack5 = DFFE( img_dma_ack4, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'io_req0' from file "intf.tdf" line 39, column 11
-- Equation name is 'io_req0', location is LC3_F23, type is buried.
io_req0  = DFFE( hl_io_req, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'io_req1' from file "intf.tdf" line 39, column 11
-- Equation name is 'io_req1', location is LC4_F23, type is buried.
io_req1  = DFFE( io_req0, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'io_req2' from file "intf.tdf" line 39, column 11
-- Equation name is 'io_req2', location is LC5_F23, type is buried.
io_req2  = DFFE( io_req1, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'io_req3' from file "intf.tdf" line 39, column 11
-- Equation name is 'io_req3', location is LC6_F23, type is buried.
io_req3  = DFFE( io_req2, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'io_req4' from file "intf.tdf" line 39, column 11
-- Equation name is 'io_req4', location is LC7_F23, type is buried.
io_req4  = DFFE( io_req3, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'io_req5' from file "intf.tdf" line 39, column 11
-- Equation name is 'io_req5', location is LC2_F23, type is buried.
io_req5  = DFFE( io_req4, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'io_req6' from file "intf.tdf" line 39, column 11
-- Equation name is 'io_req6', location is LC7_F15, type is buried.
io_req6  = DFFE( io_req5, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'iram0' from file "intf.tdf" line 47, column 33
-- Equation name is 'iram0', location is LC2_B19, type is buried.
iram0    = DFFE( _EQ076, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ076 =  _LC2_B18 &  piocom18
         #  _LC2_B18 &  piocom17
         #  _LC1_B19;

-- Node name is 'iram1' from file "intf.tdf" line 47, column 33
-- Equation name is 'iram1', location is LC6_B21, type is buried.
iram1    = DFFE( _EQ077, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ077 =  _LC2_B18 &  piocom18
         #  _LC2_B18 & !piocom17
         #  _LC3_B21;

-- Node name is 'iram2' from file "intf.tdf" line 47, column 33
-- Equation name is 'iram2', location is LC7_B21, type is buried.
iram2    = DFFE( _EQ078, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ078 =  _LC2_B18 &  piocom17
         #  _LC2_B18 & !piocom18
         #  _LC2_B21;

-- Node name is 'iram3' from file "intf.tdf" line 47, column 33
-- Equation name is 'iram3', location is LC1_B21, type is buried.
iram3    = DFFE( _EQ079, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ079 =  _LC2_B18 & !piocom17
         #  _LC2_B18 & !piocom18
         #  _LC5_B21;

-- Node name is 'ncnt0' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt0', location is LC3_A17, type is buried.
ncnt0    = DFFE( _EQ080, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ080 =  _LC8_A14 & !ncnt0 & !nread
         # !_LC8_A14 &  ncnt0 & !nread
         #  hl_data0 &  nread;

-- Node name is 'ncnt1' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt1', location is LC3_A20, type is buried.
-- ncnt1 is in Up/Down Counter Mode
-- synchronous load = !_LC1_A24
ncnt1    = DFFE(( _LC5_A6 & !_LC1_A24 #  _LC1_A24), GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'ncnt2' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt2', location is LC4_A20, type is buried.
-- ncnt2 is in Up/Down Counter Mode
-- synchronous load = !_LC8_A17
ncnt2    = DFFE(( _EQ081 & !_LC8_A17 #  _LC8_A17), GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ081 =  _LC3_A8 & !_LC3_A20_CARRY & !ncnt2
         #  _LC3_A8 &  _LC3_A20_CARRY &  ncnt2;

-- Node name is 'ncnt3' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt3', location is LC6_A20, type is buried.
-- ncnt3 is in Up/Down Counter Mode
-- synchronous load = !_LC1_A20
ncnt3    = DFFE(( _LC2_A8 & !_LC1_A20 #  _LC1_A20), GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'ncnt4' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt4', location is LC8_A20, type is buried.
-- ncnt4 is in Up/Down Counter Mode
-- synchronous load = !_LC2_A20
ncnt4    = DFFE(( _LC2_A11 & !_LC2_A20 #  _LC2_A20), GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'ncnt5' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt5', location is LC1_A22, type is buried.
-- ncnt5 is in Up/Down Counter Mode
-- synchronous load = !_LC5_A13
ncnt5    = DFFE(( _EQ082 & !_LC5_A13 #  _LC5_A13), GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ082 =  _LC3_A8 & !_LC8_A20_CARRY & !ncnt5
         #  _LC3_A8 &  _LC8_A20_CARRY &  ncnt5;

-- Node name is 'ncnt6' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt6', location is LC3_A22, type is buried.
-- ncnt6 is in Up/Down Counter Mode
-- synchronous load = !_LC7_A22
ncnt6    = DFFE(( _LC1_A3 & !_LC7_A22 #  _LC7_A22), GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'ncnt7' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt7', location is LC5_A22, type is buried.
-- ncnt7 is in Up/Down Counter Mode
-- synchronous load = !_LC8_A22
ncnt7    = DFFE(( _LC1_A10 & !_LC8_A22 #  _LC8_A22), GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'ncnt8' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt8', location is LC3_A12, type is buried.
ncnt8    = DFFE( _EQ083, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ083 =  _LC3_A8 & !_LC6_A22 & !ncnt8
         #  _LC3_A8 &  _LC6_A22 &  ncnt8
         #  _LC4_A12;

-- Node name is 'ncnt9' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt9', location is LC5_A12, type is buried.
ncnt9    = DFFE( _EQ084, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ084 =  _LC2_A12
         #  _LC6_A12
         #  hl_data9 &  nread;

-- Node name is 'ncnt10' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt10', location is LC6_F3, type is buried.
ncnt10   = DFFE( _EQ085, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ085 =  _LC4_F3
         #  hl_data10 &  nread;

-- Node name is 'ncnt11' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt11', location is LC2_F21, type is buried.
ncnt11   = DFFE( _EQ086, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ086 =  _LC3_A8 & !_LC3_F21 & !ncnt11
         #  _LC3_A8 &  _LC3_F21 &  ncnt11
         #  _LC4_F21;

-- Node name is 'ncnt12' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt12', location is LC5_F3, type is buried.
ncnt12   = DFFE( _EQ087, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ087 =  _LC2_F3
         #  _LC7_F3
         #  hl_data12 &  nread;

-- Node name is 'ncnt13' from file "intf.tdf" line 53, column 39
-- Equation name is 'ncnt13', location is LC8_A24, type is buried.
ncnt13   = DFFE( _EQ088, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ088 =  _LC3_A8 & !_LC7_F21 & !ncnt13
         #  _LC3_A8 &  _LC7_F21 &  ncnt13
         #  _LC2_A24;

-- Node name is 'nors' from file "intf.tdf" line 53, column 27
-- Equation name is 'nors', location is LC1_A18, type is buried.
nors     = DFFE( _EQ089, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ089 =  pio &  piocom17
         #  nors & !pio;

-- Node name is 'nread' from file "intf.tdf" line 279, column 44
-- Equation name is 'nread', location is LC5_A2, type is buried.
nread    = LCELL( _EQ090);
  _EQ090 = !dmaack_drns & !dmar_drns & !nors;

-- Node name is 'pg_adrpf0' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf0', type is output 
pg_adrpf0 =  _LC3_E24;

-- Node name is 'pg_adrpf1' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf1', type is output 
pg_adrpf1 =  _LC1_C11;

-- Node name is 'pg_adrpf2' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf2', type is output 
pg_adrpf2 =  _LC7_C1;

-- Node name is 'pg_adrpf3' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf3', type is output 
pg_adrpf3 =  _LC5_C12;

-- Node name is 'pg_adrpf4' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf4', type is output 
pg_adrpf4 =  _LC4_C5;

-- Node name is 'pg_adrpf5' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf5', type is output 
pg_adrpf5 =  _LC5_E12;

-- Node name is 'pg_adrpf6' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf6', type is output 
pg_adrpf6 =  _LC6_E10;

-- Node name is 'pg_adrpf7' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf7', type is output 
pg_adrpf7 =  _LC8_E7;

-- Node name is 'pg_adrpf8' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf8', type is output 
pg_adrpf8 =  _LC5_E6;

-- Node name is 'pg_adrpf9' from file "intf.tdf" line 390, column 17
-- Equation name is 'pg_adrpf9', type is output 
pg_adrpf9 =  _LC7_E20;

-- Node name is 'pg_adrram0' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram0', type is output 
pg_adrram0 =  _LC5_A16;

-- Node name is 'pg_adrram1' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram1', type is output 
pg_adrram1 =  _LC2_A16;

-- Node name is 'pg_adrram2' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram2', type is output 
pg_adrram2 =  _LC5_E21;

-- Node name is 'pg_adrram3' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram3', type is output 
pg_adrram3 =  _LC6_A9;

-- Node name is 'pg_adrram4' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram4', type is output 
pg_adrram4 =  _LC6_A16;

-- Node name is 'pg_adrram5' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram5', type is output 
pg_adrram5 =  _LC4_A2;

-- Node name is 'pg_adrram6' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram6', type is output 
pg_adrram6 =  _LC8_A7;

-- Node name is 'pg_adrram7' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram7', type is output 
pg_adrram7 =  _LC5_F8;

-- Node name is 'pg_adrram8' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram8', type is output 
pg_adrram8 =  _LC2_A1;

-- Node name is 'pg_adrram9' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram9', type is output 
pg_adrram9 =  _LC6_F12;

-- Node name is 'pg_adrram10' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram10', type is output 
pg_adrram10 =  _LC1_F21;

-- Node name is 'pg_adrram11' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram11', type is output 
pg_adrram11 =  _LC1_F17;

-- Node name is 'pg_adrram12' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram12', type is output 
pg_adrram12 =  _LC1_F13;

-- Node name is 'pg_adrram13' from file "intf.tdf" line 388, column 18
-- Equation name is 'pg_adrram13', type is output 
pg_adrram13 =  _LC1_F16;

-- Node name is 'pg_cspf0' from file "intf.tdf" line 389, column 16
-- Equation name is 'pg_cspf0', type is output 
pg_cspf0 =  _LC1_F11;

-- Node name is 'pg_cspf1' from file "intf.tdf" line 389, column 16
-- Equation name is 'pg_cspf1', type is output 
pg_cspf1 =  _LC2_F11;

-- Node name is 'pg_g' from file "intf.tdf" line 60, column 2
-- Equation name is 'pg_g', type is output 
pg_g     =  _LC2_D16;

-- Node name is 'pg_gg' from file "intf.tdf" line 61, column 5
-- Equation name is 'pg_gg', location is LC5_D16, type is buried.
pg_gg    = DFFE( _EQ091, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ091 =  _LC3_D16 & !pio
         #  pio &  piosts0 &  piosts1;

-- Node name is 'pg_oepf' from file "intf.tdf" line 62, column 2
-- Equation name is 'pg_oepf', type is output 
pg_oepf  = !_LC1_D17;

-- Node name is 'pg_runpf' from file "intf.tdf" line 55, column 5
-- Equation name is 'pg_runpf', type is output 
pg_runpf =  _LC1_A23;

-- Node name is 'pg_wepf' from file "intf.tdf" line 252, column 5
-- Equation name is 'pg_wepf', type is output 
pg_wepf  =  _LC6_B9;

-- Node name is 'pg_weram0' from file "intf.tdf" line 48, column 13
-- Equation name is 'pg_weram0', type is output 
pg_weram0 =  _LC7_B19;

-- Node name is 'pg_weram1' from file "intf.tdf" line 48, column 13
-- Equation name is 'pg_weram1', type is output 
pg_weram1 =  _LC8_B21;

-- Node name is 'pg_weram2' from file "intf.tdf" line 48, column 13
-- Equation name is 'pg_weram2', type is output 
pg_weram2 =  _LC4_B21;

-- Node name is 'pg_weram3' from file "intf.tdf" line 48, column 13
-- Equation name is 'pg_weram3', type is output 
pg_weram3 =  _LC6_B12;

-- Node name is 'pio' from file "intf.tdf" line 41, column 5
-- Equation name is 'pio', location is LC1_F19, type is buried.
pio      = DFFE( _EQ092, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ092 = !io_req5 &  io_req6;

-- Node name is 'piobn0' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn0', location is LC8_A15, type is buried.
piobn0   = DFFE( hl_data0, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn1' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn1', location is LC2_D12, type is buried.
piobn1   = DFFE( hl_data1, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn2' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn2', location is LC8_D7, type is buried.
piobn2   = DFFE( hl_data2, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn3' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn3', location is LC4_C6, type is buried.
piobn3   = DFFE( hl_data3, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn4' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn4', location is LC5_A9, type is buried.
piobn4   = DFFE( hl_data4, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn5' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn5', location is LC6_D7, type is buried.
piobn5   = DFFE( hl_data5, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn6' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn6', location is LC5_C10, type is buried.
piobn6   = DFFE( hl_data6, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn7' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn7', location is LC1_A19, type is buried.
piobn7   = DFFE( hl_data7, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn8' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn8', location is LC1_A21, type is buried.
piobn8   = DFFE( hl_data8, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn9' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn9', location is LC2_A23, type is buried.
piobn9   = DFFE( hl_data9, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piobn10' from file "intf.tdf" line 41, column 41
-- Equation name is 'piobn10', location is LC4_F2, type is buried.
piobn10  = DFFE( hl_data10, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom0' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom0', location is LC3_E18, type is buried.
piocom0  = DFFE( hl_data11, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom1' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom1', location is LC5_C19, type is buried.
piocom1  = DFFE( hl_data12, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom2' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom2', location is LC7_C18, type is buried.
piocom2  = DFFE( hl_data13, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom3' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom3', location is LC1_C7, type is buried.
piocom3  = DFFE( hl_data14, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom4' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom4', location is LC2_C19, type is buried.
piocom4  = DFFE( hl_data15, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom5' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom5', location is LC4_E1, type is buried.
piocom5  = DFFE( hl_data16, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom6' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom6', location is LC1_C10, type is buried.
piocom6  = DFFE( hl_data17, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom7' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom7', location is LC7_F6, type is buried.
piocom7  = DFFE( hl_data18, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom8' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom8', location is LC3_F9, type is buried.
piocom8  = DFFE( hl_data19, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom9' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom9', location is LC2_E17, type is buried.
piocom9  = DFFE( hl_data20, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom10' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom10', location is LC5_F6, type is buried.
piocom10 = DFFE( hl_data21, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom11' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom11', location is LC7_F16, type is buried.
piocom11 = DFFE( hl_data22, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom12' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom12', location is LC8_F13, type is buried.
piocom12 = DFFE( hl_data23, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom13' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom13', location is LC6_F16, type is buried.
piocom13 = DFFE( hl_data24, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom17' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom17', location is LC3_B20, type is buried.
piocom17 = DFFE( hl_data28, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piocom18' from file "intf.tdf" line 41, column 28
-- Equation name is 'piocom18', location is LC1_B24, type is buried.
piocom18 = DFFE( hl_data29, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'piosts0' from file "intf.tdf" line 41, column 15
-- Equation name is 'piosts0', location is LC2_F17, type is buried.
piosts0  = DFFE( _EQ093, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ093 =  _LC5_F17
         # !hl_data29 &  _LC6_F17;

-- Node name is 'piosts1' from file "intf.tdf" line 41, column 15
-- Equation name is 'piosts1', location is LC4_F17, type is buried.
piosts1  = DFFE( _EQ094, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ094 =  _LC3_F17
         #  hl_data29 &  _LC6_F17;

-- Node name is 'reset0' from file "intf.tdf" line 44, column 7
-- Equation name is 'reset0', location is LC3_D5, type is buried.
reset0   = DFFE( reset0, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'reset1' from file "intf.tdf" line 44, column 7
-- Equation name is 'reset1', location is LC2_D5, type is buried.
reset1   = DFFE(!reset0, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'reset2' from file "intf.tdf" line 44, column 7
-- Equation name is 'reset2', location is LC5_D5, type is buried.
reset2   = DFFE( reset1, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is 'run' from file "intf.tdf" line 53, column 47
-- Equation name is 'run', location is LC3_A23, type is buried.
run      = DFFE( ce, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is ':101' from file "intf.tdf" line 48, column 13
-- Equation name is '_LC6_B12', type is buried 
_LC6_B12 = DFFE( _EQ095, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ095 =  dmar_drram0
         #  dmaack_drram
         #  iram3;

-- Node name is ':102' from file "intf.tdf" line 48, column 13
-- Equation name is '_LC4_B21', type is buried 
_LC4_B21 = DFFE( _EQ096, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ096 =  dmar_drram0
         #  dmaack_drram
         #  iram2;

-- Node name is ':103' from file "intf.tdf" line 48, column 13
-- Equation name is '_LC8_B21', type is buried 
_LC8_B21 = DFFE( _EQ097, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ097 =  dmar_drram0
         #  dmaack_drram
         #  iram1;

-- Node name is ':104' from file "intf.tdf" line 48, column 13
-- Equation name is '_LC7_B19', type is buried 
_LC7_B19 = DFFE( _EQ098, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ098 =  dmar_drram0
         #  dmaack_drram
         #  iram0;

-- Node name is ':105' from file "intf.tdf" line 55, column 5
-- Equation name is '_LC1_A23', type is buried 
_LC1_A23 = DFFE( run, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is ':107' from file "intf.tdf" line 59, column 5
-- Equation name is '_LC1_D23', type is buried 
_LC1_D23 = DFFE( d_write2, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is ':108' from file "intf.tdf" line 59, column 16
-- Equation name is '_LC2_D23', type is buried 
_LC2_D23 = DFFE( _EQ099, GLOBAL( hl_clk),  VCC,  VCC,  VCC);
  _EQ099 =  _LC4_D23 & !pio
         #  pio & !piosts1
         #  pio & !piosts0;

-- Node name is ':109' from file "intf.tdf" line 60, column 2
-- Equation name is '_LC2_D16', type is buried 
_LC2_D16 = DFFE( pg_gg, GLOBAL( hl_clk),  VCC,  VCC,  VCC);

-- Node name is ':304' from file "intf.tdf" line 101, column 33
-- Equation name is '_LC1_F23', type is buried 
!_LC1_F23 = _LC1_F23~NOT;
_LC1_F23~NOT = LCELL( _EQ100);
  _EQ100 = !io_req1
         #  hl_io_req;

-- Node name is ':311' from file "intf.tdf" line 117, column 9
-- Equation name is '_LC6_F17', type is buried 
_LC6_F17 = LCELL( _EQ101);
  _EQ101 =  hl_data30 & !hl_data31 & !io_req5 &  io_req6;

-- Node name is '~319~1' from file "intf.tdf" line 128, column 18
-- Equation name is '~319~1', location is LC5_F17, type is buried.
-- synthesized logic cell 
_LC5_F17 = LCELL( _EQ102);
  _EQ102 =  hl_data31 & !io_req5 &  io_req6
         # !io_req6 &  piosts0
         #  io_req5 &  piosts0;

-- Node name is '~322~1' from file "intf.tdf" line 128, column 18
-- Equation name is '~322~1', location is LC3_F17, type is buried.
-- synthesized logic cell 
_LC3_F17 = LCELL( _EQ103);
  _EQ103 = !io_req6 &  piosts1
         #  io_req5 &  piosts1
         #  hl_data31 & !io_req5 &  io_req6;

-- Node name is '~332~1' from file "intf.tdf" line 141, column 14
-- Equation name is '~332~1', location is LC2_F18, type is buried.
-- synthesized logic cell 
_LC2_F18 = LCELL( _EQ104);
  _EQ104 =  hl_data21 & !hl_data22 & !hl_data23 & !hl_data24;

-- Node name is '~333~1' from file "intf.tdf" line 141, column 14
-- Equation name is '~333~1', location is LC1_F18, type is buried.
-- synthesized logic cell 
_LC1_F18 = LCELL( _EQ105);
  _EQ105 = !hl_data21 & !hl_data22 & !hl_data23 & !hl_data24;

-- Node name is ':343' from file "intf.tdf" line 161, column 7
-- Equation name is '_LC7_F10', type is buried 
_LC7_F10 = LCELL( _EQ106);
  _EQ106 =  pio & !piosts0 & !piosts1;

-- Node name is ':344' from file "intf.tdf" line 162, column 25
-- Equation name is '_LC5_F13', type is buried 
_LC5_F13 = LCELL( _EQ107);
  _EQ107 =  pio &  piobn0 & !piosts0 & !piosts1;

-- Node name is ':346' from file "intf.tdf" line 162, column 25
-- Equation name is '_LC3_D7', type is buried 
_LC3_D7  = LCELL( _EQ108);
  _EQ108 =  pio &  piobn2 & !piosts0 & !piosts1;

-- Node name is ':347' from file "intf.tdf" line 162, column 25
-- Equation name is '_LC3_C6', type is buried 
_LC3_C6  = LCELL( _EQ109);
  _EQ109 =  pio &  piobn3 & !piosts0 & !piosts1;

-- Node name is ':349' from file "intf.tdf" line 162, column 25
-- Equation name is '_LC2_D7', type is buried 
_LC2_D7  = LCELL( _EQ110);
  _EQ110 =  pio &  piobn5 & !piosts0 & !piosts1;

-- Node name is ':350' from file "intf.tdf" line 162, column 25
-- Equation name is '_LC7_C10', type is buried 
_LC7_C10 = LCELL( _EQ111);
  _EQ111 =  pio &  piobn6 & !piosts0 & !piosts1;

-- Node name is ':355' from file "intf.tdf" line 163, column 23
-- Equation name is '_LC4_D16', type is buried 
_LC4_D16 = LCELL( _EQ112);
  _EQ112 =  pio &  piocom0 & !piosts0 & !piosts1;

-- Node name is ':357' from file "intf.tdf" line 163, column 23
-- Equation name is '_LC3_C18', type is buried 
_LC3_C18 = LCELL( _EQ113);
  _EQ113 =  pio &  piocom2 & !piosts0 & !piosts1;

-- Node name is ':358' from file "intf.tdf" line 163, column 23
-- Equation name is '_LC4_C11', type is buried 
_LC4_C11 = LCELL( _EQ114);
  _EQ114 =  pio &  piocom3 & !piosts0 & !piosts1;

-- Node name is ':360' from file "intf.tdf" line 163, column 23
-- Equation name is '_LC1_E1', type is buried 
_LC1_E1  = LCELL( _EQ115);
  _EQ115 =  pio &  piocom5 & !piosts0 & !piosts1;

-- Node name is ':361' from file "intf.tdf" line 163, column 23
-- Equation name is '_LC4_C10', type is buried 
_LC4_C10 = LCELL( _EQ116);
  _EQ116 =  pio &  piocom6 & !piosts0 & !piosts1;

-- Node name is '~379~1' from file "intf.tdf" line 169, column 42
-- Equation name is '~379~1', location is LC2_B2, type is buried.
-- synthesized logic cell 
_LC2_B2  = LCELL( _EQ117C);
 _EQ117C =  _EQ117;
  _EQ117 = !bncnt_drram4 & !bncnt_drram5 & !bncnt_drram6;

-- Node name is '~379~2' from file "intf.tdf" line 169, column 42
-- Equation name is '~379~2', location is LC3_B2, type is buried.
-- synthesized logic cell 
_LC3_B2  = LCELL( _EQ118C);
 _EQ118C =  _EQ118 & CASCADE( _EQ117C);
  _EQ118 = !bncnt_drram1 & !bncnt_drram2 & !bncnt_drram3;

-- Node name is '~379~3' from file "intf.tdf" line 169, column 42
-- Equation name is '~379~3', location is LC4_B2, type is buried.
-- synthesized logic cell 
_LC4_B2  = LCELL( _EQ119C);
 _EQ119C =  _EQ119 & CASCADE( _EQ118C);
  _EQ119 = !bncnt_drram7 & !bncnt_drram8 & !bncnt_drram9 & !bncnt_drram10;

-- Node name is ':383' from file "intf.tdf" line 169, column 7
-- Equation name is '_LC8_F1', type is buried 
_LC8_F1  = LCELL( _EQ120);
  _EQ120 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':394' from file "intf.tdf" line 170, column 43
-- Equation name is '_LC3_B7', type is buried 
_LC3_B7  = LCELL( _EQ121C);
 _EQ121C =  _EQ121;
  _EQ121 = !bncnt_drram0 & !bncnt_drram1 & !bncnt_drram2
         #  bncnt_drram0 &  bncnt_drram2
         #  bncnt_drram1 &  bncnt_drram2;

-- Node name is ':399' from file "intf.tdf" line 170, column 43
-- Equation name is '_LC1_B7', type is buried 
_LC1_B7  = LCELL( _EQ122C);
 _EQ122C =  _EQ122;
  _EQ122 = !bncnt_drram0 & !bncnt_drram1 & !bncnt_drram2 & !bncnt_drram3
         #  bncnt_drram0 &  bncnt_drram3
         #  bncnt_drram1 &  bncnt_drram3
         #  bncnt_drram2 &  bncnt_drram3;

-- Node name is ':401' from file "intf.tdf" line 170, column 43
-- Equation name is '_LC1_B11', type is buried 
_LC1_B11 = LCELL( _EQ123);
  _EQ123 =  bncnt_drram3
         #  bncnt_drram2
         #  bncnt_drram0
         #  bncnt_drram1;

-- Node name is ':410' from file "intf.tdf" line 170, column 43
-- Equation name is '_LC3_B6', type is buried 
_LC3_B6  = LCELL( _EQ124C);
 _EQ124C =  _EQ124;
  _EQ124 = !bncnt_drram4 & !bncnt_drram5 & !_LC1_B11
         #  bncnt_drram4 &  bncnt_drram5
         #  bncnt_drram5 &  _LC1_B11;

-- Node name is ':415' from file "intf.tdf" line 170, column 43
-- Equation name is '_LC1_B6', type is buried 
_LC1_B6  = LCELL( _EQ125C);
 _EQ125C =  _EQ125;
  _EQ125 = !bncnt_drram4 & !bncnt_drram5 & !bncnt_drram6 & !_LC1_B11
         #  bncnt_drram5 &  bncnt_drram6
         #  bncnt_drram4 &  bncnt_drram6
         #  bncnt_drram6 &  _LC1_B11;

-- Node name is ':417' from file "intf.tdf" line 170, column 43
-- Equation name is '_LC5_B1', type is buried 
_LC5_B1  = LCELL( _EQ126);
  _EQ126 =  bncnt_drram5
         #  bncnt_drram4
         #  _LC1_B11
         #  bncnt_drram6;

-- Node name is ':423' from file "intf.tdf" line 170, column 43
-- Equation name is '_LC5_B14', type is buried 
_LC5_B14 = LCELL( _EQ127);
  _EQ127 =  bncnt_drram7
         #  _LC5_B1;

-- Node name is ':431' from file "intf.tdf" line 170, column 43
-- Equation name is '_LC1_B14', type is buried 
_LC1_B14 = LCELL( _EQ128C);
 _EQ128C =  _EQ128;
  _EQ128 = !bncnt_drram7 & !bncnt_drram8 & !bncnt_drram9 & !_LC5_B1
         #  bncnt_drram8 &  bncnt_drram9
         #  bncnt_drram7 &  bncnt_drram9
         #  bncnt_drram9 &  _LC5_B1;

-- Node name is ':433' from file "intf.tdf" line 170, column 43
-- Equation name is '_LC3_B16', type is buried 
_LC3_B16 = LCELL( _EQ129);
  _EQ129 =  bncnt_drram9
         #  bncnt_drram8
         #  bncnt_drram7
         #  _LC5_B1;

-- Node name is ':444' from file "intf.tdf" line 170, column 25
-- Equation name is '_LC4_B7', type is buried 
_LC4_B7  = LCELL( _EQ130C);
 _EQ130C =  _EQ130 & CASCADE( _EQ121C);
  _EQ130 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':446' from file "intf.tdf" line 170, column 25
-- Equation name is '_LC2_B7', type is buried 
_LC2_B7  = LCELL( _EQ131C);
 _EQ131C =  _EQ131 & CASCADE( _EQ122C);
  _EQ131 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':450' from file "intf.tdf" line 170, column 25
-- Equation name is '_LC4_B6', type is buried 
_LC4_B6  = LCELL( _EQ132C);
 _EQ132C =  _EQ132 & CASCADE( _EQ124C);
  _EQ132 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':452' from file "intf.tdf" line 170, column 25
-- Equation name is '_LC2_B6', type is buried 
_LC2_B6  = LCELL( _EQ133C);
 _EQ133C =  _EQ133 & CASCADE( _EQ125C);
  _EQ133 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':458' from file "intf.tdf" line 170, column 25
-- Equation name is '_LC2_B14', type is buried 
_LC2_B14 = LCELL( _EQ134C);
 _EQ134C =  _EQ134 & CASCADE( _EQ128C);
  _EQ134 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':470' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC1_B15', type is buried 
_LC1_B15 = LCELL( _EQ135C);
 _EQ135C =  _EQ135;
  _EQ135 = !adr_drram0 &  adr_drram2
         # !adr_drram1 &  adr_drram2
         #  adr_drram0 &  adr_drram1 & !adr_drram2;

-- Node name is ':474' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC3_B3', type is buried 
_LC3_B3  = LCELL( _EQ136C);
 _EQ136C =  _EQ136;
  _EQ136 = !adr_drram2 &  adr_drram3
         # !adr_drram0 &  adr_drram3
         # !adr_drram1 &  adr_drram3
         #  adr_drram0 &  adr_drram1 &  adr_drram2 & !adr_drram3;

-- Node name is ':476' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC6_B3', type is buried 
_LC6_B3  = LCELL( _EQ137);
  _EQ137 =  adr_drram0 &  adr_drram1 &  adr_drram2 &  adr_drram3;

-- Node name is ':482' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC5_B6', type is buried 
_LC5_B6  = LCELL( _EQ138C);
 _EQ138C =  _EQ138;
  _EQ138 = !adr_drram4 &  adr_drram5
         #  adr_drram5 & !_LC6_B3
         #  adr_drram4 & !adr_drram5 &  _LC6_B3;

-- Node name is ':486' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC1_B3', type is buried 
_LC1_B3  = LCELL( _EQ139C);
 _EQ139C =  _EQ139;
  _EQ139 = !adr_drram5 &  adr_drram6
         # !adr_drram4 &  adr_drram6
         #  adr_drram6 & !_LC6_B3
         #  adr_drram4 &  adr_drram5 & !adr_drram6 &  _LC6_B3;

-- Node name is ':488' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC5_B3', type is buried 
_LC5_B3  = LCELL( _EQ140);
  _EQ140 =  adr_drram4 &  adr_drram5 &  adr_drram6 &  _LC6_B3;

-- Node name is ':492' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC5_F9', type is buried 
_LC5_F9  = LCELL( _EQ141);
  _EQ141 =  adr_drram7 &  _LC5_B3;

-- Node name is ':498' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC1_F5', type is buried 
_LC1_F5  = LCELL( _EQ142C);
 _EQ142C =  _EQ142;
  _EQ142 = !adr_drram8 &  adr_drram9
         # !adr_drram7 &  adr_drram9
         #  adr_drram9 & !_LC5_B3
         #  adr_drram7 &  adr_drram8 & !adr_drram9 &  _LC5_B3;

-- Node name is ':500' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC6_F4', type is buried 
_LC6_F4  = LCELL( _EQ143);
  _EQ143 =  adr_drram7 &  adr_drram8 &  adr_drram9 &  _LC5_B3;

-- Node name is ':504' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC1_F9', type is buried 
_LC1_F9  = LCELL( _EQ144);
  _EQ144 =  adr_drram8 &  adr_drram9 &  adr_drram10 &  _LC5_F9;

-- Node name is ':510' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC2_F13', type is buried 
_LC2_F13 = LCELL( _EQ145C);
 _EQ145C =  _EQ145;
  _EQ145 = !adr_drram11 &  adr_drram12
         #  adr_drram12 & !_LC1_F9
         #  adr_drram11 & !adr_drram12 &  _LC1_F9;

-- Node name is ':512' from file "intf.tdf" line 171, column 39
-- Equation name is '_LC5_F16', type is buried 
_LC5_F16 = LCELL( _EQ146);
  _EQ146 =  adr_drram10 &  adr_drram11 &  adr_drram12 &  _LC6_F4;

-- Node name is ':521' from file "intf.tdf" line 171, column 23
-- Equation name is '_LC2_B15', type is buried 
_LC2_B15 = LCELL( _EQ147C);
 _EQ147C =  _EQ147 & CASCADE( _EQ135C);
  _EQ147 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':523' from file "intf.tdf" line 171, column 23
-- Equation name is '_LC4_B3', type is buried 
_LC4_B3  = LCELL( _EQ148C);
 _EQ148C =  _EQ148 & CASCADE( _EQ136C);
  _EQ148 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':527' from file "intf.tdf" line 171, column 23
-- Equation name is '_LC6_B6', type is buried 
_LC6_B6  = LCELL( _EQ149C);
 _EQ149C =  _EQ149 & CASCADE( _EQ138C);
  _EQ149 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':529' from file "intf.tdf" line 171, column 23
-- Equation name is '_LC2_B3', type is buried 
_LC2_B3  = LCELL( _EQ150C);
 _EQ150C =  _EQ150 & CASCADE( _EQ139C);
  _EQ150 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':535' from file "intf.tdf" line 171, column 23
-- Equation name is '_LC2_F5', type is buried 
_LC2_F5  = LCELL( _EQ151C);
 _EQ151C =  _EQ151 & CASCADE( _EQ142C);
  _EQ151 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':541' from file "intf.tdf" line 171, column 23
-- Equation name is '_LC3_F13', type is buried 
_LC3_F13 = LCELL( _EQ152C);
 _EQ152C =  _EQ152 & CASCADE( _EQ145C);
  _EQ152 =  bncnt_drram0 & !dmaack_drram & !pio
         # !dmaack_drram & !_LC4_B2 & !pio;

-- Node name is ':547' from file "intf.tdf" line 169, column 7
-- Equation name is '_LC2_F7', type is buried 
_LC2_F7  = LCELL( _EQ153);
  _EQ153 =  dmaack_drram & !pio
         # !bncnt_drram0 &  _LC4_B2 & !pio;

-- Node name is '~551~1' from file "intf.tdf" line 173, column 25
-- Equation name is '~551~1', location is LC1_D5, type is buried.
-- synthesized logic cell 
_LC1_D5  = LCELL( _EQ154);
  _EQ154 =  bncnt_drram0 &  bncnt_drram1 &  _LC8_F1
         # !bncnt_drram0 & !bncnt_drram1 &  _LC8_F1
         #  bncnt_drram1 &  _LC2_F7;

-- Node name is '~557~1' from file "intf.tdf" line 173, column 25
-- Equation name is '~557~1', location is LC5_B8, type is buried.
-- synthesized logic cell 
_LC5_B8  = LCELL( _EQ155);
  _EQ155 = !bncnt_drram4 & !_LC1_B11 &  _LC8_F1
         #  bncnt_drram4 &  _LC1_B11 &  _LC8_F1
         #  bncnt_drram4 &  _LC2_F7;

-- Node name is '~563~1' from file "intf.tdf" line 173, column 25
-- Equation name is '~563~1', location is LC7_B15, type is buried.
-- synthesized logic cell 
_LC7_B15 = LCELL( _EQ156);
  _EQ156 = !bncnt_drram7 & !_LC5_B1 &  _LC8_F1
         #  bncnt_drram7 &  _LC5_B1 &  _LC8_F1
         #  bncnt_drram7 &  _LC2_F7;

-- Node name is '~565~1' from file "intf.tdf" line 173, column 25
-- Equation name is '~565~1', location is LC7_B14, type is buried.
-- synthesized logic cell 
_LC7_B14 = LCELL( _EQ157);
  _EQ157 =  bncnt_drram8 &  _LC2_F7
         #  _LC7_F10 &  piobn8;

-- Node name is ':566' from file "intf.tdf" line 173, column 25
-- Equation name is '_LC6_B14', type is buried 
_LC6_B14 = LCELL( _EQ158);
  _EQ158 =  bncnt_drram9 &  _LC2_F7;

-- Node name is '~569~1' from file "intf.tdf" line 173, column 25
-- Equation name is '~569~1', location is LC4_B8, type is buried.
-- synthesized logic cell 
_LC4_B8  = LCELL( _EQ159);
  _EQ159 = !bncnt_drram10 & !_LC3_B16 &  _LC8_F1
         #  bncnt_drram10 &  _LC3_B16 &  _LC8_F1
         #  bncnt_drram10 &  _LC2_F7;

-- Node name is '~573~1' from file "intf.tdf" line 174, column 23
-- Equation name is '~573~1', location is LC5_B15, type is buried.
-- synthesized logic cell 
_LC5_B15 = LCELL( _EQ160);
  _EQ160 =  adr_drram0 & !adr_drram1 &  _LC8_F1
         # !adr_drram0 &  adr_drram1 &  _LC8_F1
         #  adr_drram1 &  _LC2_F7;

-- Node name is '~579~1' from file "intf.tdf" line 174, column 23
-- Equation name is '~579~1', location is LC2_B8, type is buried.
-- synthesized logic cell 
_LC2_B8  = LCELL( _EQ161);
  _EQ161 =  adr_drram4 & !_LC6_B3 &  _LC8_F1
         # !adr_drram4 &  _LC6_B3 &  _LC8_F1
         #  adr_drram4 &  _LC2_F7;

-- Node name is '~585~1' from file "intf.tdf" line 174, column 23
-- Equation name is '~585~1', location is LC4_F6, type is buried.
-- synthesized logic cell 
_LC4_F6  = LCELL( _EQ162);
  _EQ162 =  adr_drram7 & !_LC5_B3 &  _LC8_F1
         # !adr_drram7 &  _LC5_B3 &  _LC8_F1
         #  adr_drram7 &  _LC2_F7;

-- Node name is '~587~1' from file "intf.tdf" line 174, column 23
-- Equation name is '~587~1', location is LC4_F9, type is buried.
-- synthesized logic cell 
_LC4_F9  = LCELL( _EQ163);
  _EQ163 =  adr_drram8 &  _LC2_F7
         #  _LC7_F10 &  piocom8;

-- Node name is ':588' from file "intf.tdf" line 174, column 23
-- Equation name is '_LC4_F5', type is buried 
_LC4_F5  = LCELL( _EQ164);
  _EQ164 =  adr_drram9 &  _LC2_F7;

-- Node name is '~591~1' from file "intf.tdf" line 174, column 23
-- Equation name is '~591~1', location is LC1_F6, type is buried.
-- synthesized logic cell 
_LC1_F6  = LCELL( _EQ165);
  _EQ165 =  adr_drram10 & !_LC6_F4 &  _LC8_F1
         # !adr_drram10 &  _LC6_F4 &  _LC8_F1
         #  adr_drram10 &  _LC2_F7;

-- Node name is '~593~1' from file "intf.tdf" line 174, column 23
-- Equation name is '~593~1', location is LC4_F16, type is buried.
-- synthesized logic cell 
_LC4_F16 = LCELL( _EQ166);
  _EQ166 =  adr_drram11 &  _LC2_F7
         #  _LC7_F10 &  piocom11;

-- Node name is ':594' from file "intf.tdf" line 174, column 23
-- Equation name is '_LC7_F13', type is buried 
_LC7_F13 = LCELL( _EQ167);
  _EQ167 =  adr_drram12 &  _LC2_F7;

-- Node name is '~597~1' from file "intf.tdf" line 174, column 23
-- Equation name is '~597~1', location is LC3_F16, type is buried.
-- synthesized logic cell 
_LC3_F16 = LCELL( _EQ168);
  _EQ168 =  adr_drram13 & !_LC5_F16 &  _LC8_F1
         # !adr_drram13 &  _LC5_F16 &  _LC8_F1
         #  adr_drram13 &  _LC2_F7;

-- Node name is ':598' from file "intf.tdf" line 179, column 18
-- Equation name is '_LC6_A11', type is buried 
!_LC6_A11 = _LC6_A11~NOT;
_LC6_A11~NOT = LCELL( _EQ169);
  _EQ169 = !piosts0 & !piosts1;

-- Node name is '~615~1' from file "intf.tdf" line 185, column 28
-- Equation name is '~615~1', location is LC5_B2, type is buried.
-- synthesized logic cell 
!_LC5_B2 = _LC5_B2~NOT;
_LC5_B2~NOT = LCELL( _EQ170C);
 _EQ170C =  _EQ170;
  _EQ170 = !bncnt_drram4 & !bncnt_drram5 & !bncnt_drram6 & !bncnt_drram7;

-- Node name is '~615~2' from file "intf.tdf" line 185, column 28
-- Equation name is '~615~2', location is LC6_B2, type is buried.
-- synthesized logic cell 
!_LC6_B2 = _LC6_B2~NOT;
_LC6_B2~NOT = LCELL( _EQ171C);
 _EQ171C =  _EQ171 & CASCADE( _EQ170C);
  _EQ171 = !bncnt_drram8 & !bncnt_drram9 & !bncnt_drram10 & !dmaack_drram;

-- Node name is ':615' from file "intf.tdf" line 185, column 28
-- Equation name is '_LC7_B2', type is buried 
_LC7_B2  = LCELL( _EQ172C);
 _EQ172C =  _EQ172 & CASCADE( _EQ171C);
  _EQ172 =  bncnt_drram0 & !bncnt_drram1 & !bncnt_drram2 & !bncnt_drram3;

-- Node name is ':626' from file "intf.tdf" line 193, column 7
-- Equation name is '_LC2_B18', type is buried 
_LC2_B18 = LCELL( _EQ173);
  _EQ173 =  pio & !piosts0 & !piosts1;

-- Node name is '~658~1' from file "intf.tdf" line 204, column 16
-- Equation name is '~658~1', location is LC1_B19, type is buried.
-- synthesized logic cell 
_LC1_B19 = LCELL( _EQ174);
  _EQ174 =  iram0 & !pio
         #  pio &  piosts1
         #  pio &  piosts0;

-- Node name is '~661~1' from file "intf.tdf" line 204, column 16
-- Equation name is '~661~1', location is LC3_B21, type is buried.
-- synthesized logic cell 
_LC3_B21 = LCELL( _EQ175);
  _EQ175 =  pio &  piosts1
         #  pio &  piosts0
         #  iram1 & !pio;

-- Node name is '~664~1' from file "intf.tdf" line 204, column 16
-- Equation name is '~664~1', location is LC2_B21, type is buried.
-- synthesized logic cell 
_LC2_B21 = LCELL( _EQ176);
  _EQ176 =  pio &  piosts1
         #  pio &  piosts0
         #  iram2 & !pio;

-- Node name is '~667~1' from file "intf.tdf" line 204, column 16
-- Equation name is '~667~1', location is LC5_B21, type is buried.
-- synthesized logic cell 
_LC5_B21 = LCELL( _EQ177);
  _EQ177 =  pio &  piosts1
         #  pio &  piosts0
         #  iram3 & !pio;

-- Node name is ':686' from file "intf.tdf" line 221, column 7
-- Equation name is '_LC7_C22', type is buried 
_LC7_C22 = LCELL( _EQ178);
  _EQ178 =  pio &  piosts0 & !piosts1;

-- Node name is ':687' from file "intf.tdf" line 222, column 25
-- Equation name is '_LC2_E24', type is buried 
_LC2_E24 = LCELL( _EQ179);
  _EQ179 =  pio &  piobn0 &  piosts0 & !piosts1;

-- Node name is ':689' from file "intf.tdf" line 222, column 25
-- Equation name is '_LC5_D7', type is buried 
_LC5_D7  = LCELL( _EQ180);
  _EQ180 =  pio &  piobn2 &  piosts0 & !piosts1;

-- Node name is ':690' from file "intf.tdf" line 222, column 25
-- Equation name is '_LC2_C6', type is buried 
_LC2_C6  = LCELL( _EQ181);
  _EQ181 =  pio &  piobn3 &  piosts0 & !piosts1;

-- Node name is ':692' from file "intf.tdf" line 222, column 25
-- Equation name is '_LC4_D7', type is buried 
_LC4_D7  = LCELL( _EQ182);
  _EQ182 =  pio &  piobn5 &  piosts0 & !piosts1;

-- Node name is ':693' from file "intf.tdf" line 222, column 25
-- Equation name is '_LC2_C10', type is buried 
_LC2_C10 = LCELL( _EQ183);
  _EQ183 =  pio &  piobn6 &  piosts0 & !piosts1;

-- Node name is ':698' from file "intf.tdf" line 223, column 23
-- Equation name is '_LC4_E24', type is buried 
_LC4_E24 = LCELL( _EQ184);
  _EQ184 =  pio &  piocom0 &  piosts0 & !piosts1;

-- Node name is ':700' from file "intf.tdf" line 223, column 23
-- Equation name is '_LC6_C18', type is buried 
_LC6_C18 = LCELL( _EQ185);
  _EQ185 =  pio &  piocom2 &  piosts0 & !piosts1;

-- Node name is ':701' from file "intf.tdf" line 223, column 23
-- Equation name is '_LC4_C12', type is buried 
_LC4_C12 = LCELL( _EQ186);
  _EQ186 =  pio &  piocom3 &  piosts0 & !piosts1;

-- Node name is ':703' from file "intf.tdf" line 223, column 23
-- Equation name is '_LC3_E1', type is buried 
_LC3_E1  = LCELL( _EQ187);
  _EQ187 =  pio &  piocom5 &  piosts0 & !piosts1;

-- Node name is ':704' from file "intf.tdf" line 223, column 23
-- Equation name is '_LC5_E4', type is buried 
_LC5_E4  = LCELL( _EQ188);
  _EQ188 =  pio &  piocom6 &  piosts0 & !piosts1;

-- Node name is '~718~1' from file "intf.tdf" line 229, column 43
-- Equation name is '~718~1', location is LC3_C8, type is buried.
-- synthesized logic cell 
_LC3_C8  = LCELL( _EQ189C);
 _EQ189C =  _EQ189;
  _EQ189 = !bncnt_drreg4 & !bncnt_drreg5 & !bncnt_drreg6;

-- Node name is '~718~2' from file "intf.tdf" line 229, column 43
-- Equation name is '~718~2', location is LC4_C8, type is buried.
-- synthesized logic cell 
_LC4_C8  = LCELL( _EQ190C);
 _EQ190C =  _EQ190 & CASCADE( _EQ189C);
  _EQ190 = !bncnt_drreg1 & !bncnt_drreg2 & !bncnt_drreg3;

-- Node name is '~718~3' from file "intf.tdf" line 229, column 43
-- Equation name is '~718~3', location is LC5_C8, type is buried.
-- synthesized logic cell 
_LC5_C8  = LCELL( _EQ191C);
 _EQ191C =  _EQ191 & CASCADE( _EQ190C);
  _EQ191 = !bncnt_drreg7 & !bncnt_drreg8 & !bncnt_drreg9 & !bncnt_drreg10;

-- Node name is ':722' from file "intf.tdf" line 229, column 7
-- Equation name is '_LC3_E14', type is buried 
_LC3_E14 = LCELL( _EQ192);
  _EQ192 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':733' from file "intf.tdf" line 230, column 43
-- Equation name is '_LC3_C3', type is buried 
_LC3_C3  = LCELL( _EQ193C);
 _EQ193C =  _EQ193;
  _EQ193 = !bncnt_drreg0 & !bncnt_drreg1 & !bncnt_drreg2
         #  bncnt_drreg0 &  bncnt_drreg2
         #  bncnt_drreg1 &  bncnt_drreg2;

-- Node name is ':738' from file "intf.tdf" line 230, column 43
-- Equation name is '_LC1_C3', type is buried 
_LC1_C3  = LCELL( _EQ194C);
 _EQ194C =  _EQ194;
  _EQ194 = !bncnt_drreg0 & !bncnt_drreg1 & !bncnt_drreg2 & !bncnt_drreg3
         #  bncnt_drreg2 &  bncnt_drreg3
         #  bncnt_drreg0 &  bncnt_drreg3
         #  bncnt_drreg1 &  bncnt_drreg3;

-- Node name is ':740' from file "intf.tdf" line 230, column 43
-- Equation name is '_LC7_C4', type is buried 
_LC7_C4  = LCELL( _EQ195);
  _EQ195 =  bncnt_drreg3
         #  bncnt_drreg2
         #  bncnt_drreg0
         #  bncnt_drreg1;

-- Node name is ':749' from file "intf.tdf" line 230, column 43
-- Equation name is '_LC3_C2', type is buried 
_LC3_C2  = LCELL( _EQ196C);
 _EQ196C =  _EQ196;
  _EQ196 = !bncnt_drreg4 & !bncnt_drreg5 & !_LC7_C4
         #  bncnt_drreg4 &  bncnt_drreg5
         #  bncnt_drreg5 &  _LC7_C4;

-- Node name is ':754' from file "intf.tdf" line 230, column 43
-- Equation name is '_LC1_C2', type is buried 
_LC1_C2  = LCELL( _EQ197C);
 _EQ197C =  _EQ197;
  _EQ197 = !bncnt_drreg4 & !bncnt_drreg5 & !bncnt_drreg6 & !_LC7_C4
         #  bncnt_drreg5 &  bncnt_drreg6
         #  bncnt_drreg4 &  bncnt_drreg6
         #  bncnt_drreg6 &  _LC7_C4;

-- Node name is ':756' from file "intf.tdf" line 230, column 43
-- Equation name is '_LC2_C9', type is buried 
_LC2_C9  = LCELL( _EQ198);
  _EQ198 =  bncnt_drreg5
         #  bncnt_drreg4
         #  _LC7_C4
         #  bncnt_drreg6;

-- Node name is ':762' from file "intf.tdf" line 230, column 43
-- Equation name is '_LC1_C16', type is buried 
_LC1_C16 = LCELL( _EQ199);
  _EQ199 =  bncnt_drreg7
         #  _LC2_C9;

-- Node name is ':770' from file "intf.tdf" line 230, column 43
-- Equation name is '_LC1_C24', type is buried 
_LC1_C24 = LCELL( _EQ200C);
 _EQ200C =  _EQ200;
  _EQ200 = !bncnt_drreg7 & !bncnt_drreg8 & !bncnt_drreg9 & !_LC2_C9
         #  bncnt_drreg8 &  bncnt_drreg9
         #  bncnt_drreg7 &  bncnt_drreg9
         #  bncnt_drreg9 &  _LC2_C9;

-- Node name is ':772' from file "intf.tdf" line 230, column 43
-- Equation name is '_LC5_C24', type is buried 
_LC5_C24 = LCELL( _EQ201);
  _EQ201 =  bncnt_drreg9
         #  bncnt_drreg8
         #  bncnt_drreg7
         #  _LC2_C9;

-- Node name is ':783' from file "intf.tdf" line 230, column 25
-- Equation name is '_LC4_C3', type is buried 
_LC4_C3  = LCELL( _EQ202C);
 _EQ202C =  _EQ202 & CASCADE( _EQ193C);
  _EQ202 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':785' from file "intf.tdf" line 230, column 25
-- Equation name is '_LC2_C3', type is buried 
_LC2_C3  = LCELL( _EQ203C);
 _EQ203C =  _EQ203 & CASCADE( _EQ194C);
  _EQ203 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':789' from file "intf.tdf" line 230, column 25
-- Equation name is '_LC4_C2', type is buried 
_LC4_C2  = LCELL( _EQ204C);
 _EQ204C =  _EQ204 & CASCADE( _EQ196C);
  _EQ204 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':791' from file "intf.tdf" line 230, column 25
-- Equation name is '_LC2_C2', type is buried 
_LC2_C2  = LCELL( _EQ205C);
 _EQ205C =  _EQ205 & CASCADE( _EQ197C);
  _EQ205 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':797' from file "intf.tdf" line 230, column 25
-- Equation name is '_LC2_C24', type is buried 
_LC2_C24 = LCELL( _EQ206C);
 _EQ206C =  _EQ206 & CASCADE( _EQ200C);
  _EQ206 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':809' from file "intf.tdf" line 231, column 39
-- Equation name is '_LC1_C18', type is buried 
_LC1_C18 = LCELL( _EQ207C);
 _EQ207C =  _EQ207;
  _EQ207 = !adr_drreg0 &  adr_drreg2
         # !adr_drreg1 &  adr_drreg2
         #  adr_drreg0 &  adr_drreg1 & !adr_drreg2;

-- Node name is ':813' from file "intf.tdf" line 231, column 39
-- Equation name is '_LC1_C12', type is buried 
_LC1_C12 = LCELL( _EQ208C);
 _EQ208C =  _EQ208;
  _EQ208 = !adr_drreg2 &  adr_drreg3
         # !adr_drreg0 &  adr_drreg3
         # !adr_drreg1 &  adr_drreg3
         #  adr_drreg0 &  adr_drreg1 &  adr_drreg2 & !adr_drreg3;

-- Node name is ':815' from file "intf.tdf" line 231, column 39
-- Equation name is '_LC3_C12', type is buried 
_LC3_C12 = LCELL( _EQ209);
  _EQ209 =  adr_drreg0 &  adr_drreg1 &  adr_drreg2 &  adr_drreg3;

-- Node name is ':821' from file "intf.tdf" line 231, column 39
-- Equation name is '_LC1_E4', type is buried 
_LC1_E4  = LCELL( _EQ210C);
 _EQ210C =  _EQ210;
  _EQ210 = !adr_drreg4 &  adr_drreg5
         #  adr_drreg5 & !_LC3_C12
         #  adr_drreg4 & !adr_drreg5 &  _LC3_C12;

-- Node name is ':825' from file "intf.tdf" line 231, column 39
-- Equation name is '_LC3_E4', type is buried 
_LC3_E4  = LCELL( _EQ211C);
 _EQ211C =  _EQ211;
  _EQ211 = !adr_drreg5 &  adr_drreg6
         # !adr_drreg4 &  adr_drreg6
         #  adr_drreg6 & !_LC3_C12
         #  adr_drreg4 &  adr_drreg5 & !adr_drreg6 &  _LC3_C12;

-- Node name is ':827' from file "intf.tdf" line 231, column 39
-- Equation name is '_LC8_E2', type is buried 
_LC8_E2  = LCELL( _EQ212);
  _EQ212 =  adr_drreg4 &  adr_drreg5 &  adr_drreg6 &  _LC3_C12;

-- Node name is ':831' from file "intf.tdf" line 231, column 39
-- Equation name is '_LC2_E19', type is buried 
_LC2_E19 = LCELL( _EQ213);
  _EQ213 =  adr_drreg7 &  _LC8_E2;

-- Node name is ':837' from file "intf.tdf" line 231, column 39
-- Equation name is '_LC1_E15', type is buried 
_LC1_E15 = LCELL( _EQ214C);
 _EQ214C =  _EQ214;
  _EQ214 = !adr_drreg8 &  adr_drreg9
         # !adr_drreg7 &  adr_drreg9
         #  adr_drreg9 & !_LC8_E2
         #  adr_drreg7 &  adr_drreg8 & !adr_drreg9 &  _LC8_E2;

-- Node name is ':844' from file "intf.tdf" line 231, column 23
-- Equation name is '_LC2_C18', type is buried 
_LC2_C18 = LCELL( _EQ215C);
 _EQ215C =  _EQ215 & CASCADE( _EQ207C);
  _EQ215 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':846' from file "intf.tdf" line 231, column 23
-- Equation name is '_LC2_C12', type is buried 
_LC2_C12 = LCELL( _EQ216C);
 _EQ216C =  _EQ216 & CASCADE( _EQ208C);
  _EQ216 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':850' from file "intf.tdf" line 231, column 23
-- Equation name is '_LC2_E4', type is buried 
_LC2_E4  = LCELL( _EQ217C);
 _EQ217C =  _EQ217 & CASCADE( _EQ210C);
  _EQ217 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':852' from file "intf.tdf" line 231, column 23
-- Equation name is '_LC4_E4', type is buried 
_LC4_E4  = LCELL( _EQ218C);
 _EQ218C =  _EQ218 & CASCADE( _EQ211C);
  _EQ218 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':858' from file "intf.tdf" line 231, column 23
-- Equation name is '_LC2_E15', type is buried 
_LC2_E15 = LCELL( _EQ219C);
 _EQ219C =  _EQ219 & CASCADE( _EQ214C);
  _EQ219 =  bncnt_drreg0 & !dmaack_drreg & !pio
         # !dmaack_drreg & !_LC5_C8 & !pio;

-- Node name is ':862' from file "intf.tdf" line 229, column 7
-- Equation name is '_LC1_E3', type is buried 
_LC1_E3  = LCELL( _EQ220);
  _EQ220 =  dmaack_drreg & !pio
         # !bncnt_drreg0 &  _LC5_C8 & !pio;

-- Node name is '~866~1' from file "intf.tdf" line 233, column 25
-- Equation name is '~866~1', location is LC3_C16, type is buried.
-- synthesized logic cell 
_LC3_C16 = LCELL( _EQ221);
  _EQ221 =  bncnt_drreg0 &  bncnt_drreg1 &  _LC3_E14
         # !bncnt_drreg0 & !bncnt_drreg1 &  _LC3_E14
         #  bncnt_drreg1 &  _LC1_E3;

-- Node name is '~872~1' from file "intf.tdf" line 233, column 25
-- Equation name is '~872~1', location is LC4_C19, type is buried.
-- synthesized logic cell 
_LC4_C19 = LCELL( _EQ222);
  _EQ222 = !bncnt_drreg4 &  _LC3_E14 & !_LC7_C4
         #  bncnt_drreg4 &  _LC3_E14 &  _LC7_C4
         #  bncnt_drreg4 &  _LC1_E3;

-- Node name is '~878~1' from file "intf.tdf" line 233, column 25
-- Equation name is '~878~1', location is LC6_C16, type is buried.
-- synthesized logic cell 
_LC6_C16 = LCELL( _EQ223);
  _EQ223 = !bncnt_drreg7 & !_LC2_C9 &  _LC3_E14
         #  bncnt_drreg7 &  _LC2_C9 &  _LC3_E14
         #  bncnt_drreg7 &  _LC1_E3;

-- Node name is '~880~1' from file "intf.tdf" line 233, column 25
-- Equation name is '~880~1', location is LC7_C16, type is buried.
-- synthesized logic cell 
_LC7_C16 = LCELL( _EQ224);
  _EQ224 =  bncnt_drreg8 &  _LC1_E3
         #  _LC7_C22 &  piobn8;

-- Node name is ':881' from file "intf.tdf" line 233, column 25
-- Equation name is '_LC6_C24', type is buried 
_LC6_C24 = LCELL( _EQ225);
  _EQ225 =  bncnt_drreg9 &  _LC1_E3;

-- Node name is '~884~1' from file "intf.tdf" line 233, column 25
-- Equation name is '~884~1', location is LC7_C24, type is buried.
-- synthesized logic cell 
_LC7_C24 = LCELL( _EQ226);
  _EQ226 = !bncnt_drreg10 &  _LC3_E14 & !_LC5_C24
         #  bncnt_drreg10 &  _LC3_E14 &  _LC5_C24
         #  bncnt_drreg10 &  _LC1_E3;

-- Node name is '~888~1' from file "intf.tdf" line 234, column 23
-- Equation name is '~888~1', location is LC7_C19, type is buried.
-- synthesized logic cell 
_LC7_C19 = LCELL( _EQ227);
  _EQ227 =  adr_drreg0 & !adr_drreg1 &  _LC3_E14
         # !adr_drreg0 &  adr_drreg1 &  _LC3_E14
         #  adr_drreg1 &  _LC1_E3;

-- Node name is '~894~1' from file "intf.tdf" line 234, column 23
-- Equation name is '~894~1', location is LC8_C19, type is buried.
-- synthesized logic cell 
_LC8_C19 = LCELL( _EQ228);
  _EQ228 =  adr_drreg4 & !_LC3_C12 &  _LC3_E14
         # !adr_drreg4 &  _LC3_C12 &  _LC3_E14
         #  adr_drreg4 &  _LC1_E3;

-- Node name is '~900~1' from file "intf.tdf" line 234, column 23
-- Equation name is '~900~1', location is LC6_E15, type is buried.
-- synthesized logic cell 
_LC6_E15 = LCELL( _EQ229);
  _EQ229 =  adr_drreg7 &  _LC3_E14 & !_LC8_E2
         # !adr_drreg7 &  _LC3_E14 &  _LC8_E2
         #  adr_drreg7 &  _LC1_E3;

-- Node name is '~902~1' from file "intf.tdf" line 234, column 23
-- Equation name is '~902~1', location is LC3_E19, type is buried.
-- synthesized logic cell 
_LC3_E19 = LCELL( _EQ230);
  _EQ230 =  adr_drreg8 &  _LC1_E3
         #  _LC7_C22 &  piocom8;

-- Node name is ':903' from file "intf.tdf" line 234, column 23
-- Equation name is '_LC5_E15', type is buried 
_LC5_E15 = LCELL( _EQ231);
  _EQ231 =  adr_drreg9 &  _LC1_E3;

-- Node name is ':906' from file "intf.tdf" line 239, column 19
-- Equation name is '_LC5_A5', type is buried 
_LC5_A5  = LCELL( _EQ232);
  _EQ232 =  piosts1
         # !piosts0;

-- Node name is '~923~1' from file "intf.tdf" line 245, column 29
-- Equation name is '~923~1', location is LC6_C8, type is buried.
-- synthesized logic cell 
_LC6_C8  = LCELL( _EQ233C);
 _EQ233C =  _EQ233;
  _EQ233 = !bncnt_drreg4 & !bncnt_drreg5 & !bncnt_drreg6 & !bncnt_drreg7;

-- Node name is '~923~2' from file "intf.tdf" line 245, column 29
-- Equation name is '~923~2', location is LC7_C8, type is buried.
-- synthesized logic cell 
_LC7_C8  = LCELL( _EQ234C);
 _EQ234C =  _EQ234 & CASCADE( _EQ233C);
  _EQ234 = !bncnt_drreg8 & !bncnt_drreg9 & !bncnt_drreg10 & !dmaack_drreg;

-- Node name is ':923' from file "intf.tdf" line 245, column 29
-- Equation name is '_LC8_C8', type is buried 
_LC8_C8  = LCELL( _EQ235C);
 _EQ235C =  _EQ235 & CASCADE( _EQ234C);
  _EQ235 =  bncnt_drreg0 & !bncnt_drreg1 & !bncnt_drreg2 & !bncnt_drreg3;

-- Node name is ':932' from file "intf.tdf" line 252, column 28
-- Equation name is '_LC6_B9', type is buried 
_LC6_B9  = LCELL( _EQ236);
  _EQ236 =  dmar_drreg
         #  dmaack_drreg;

-- Node name is ':934' from file "intf.tdf" line 260, column 19
-- Equation name is '_LC2_A5', type is buried 
_LC2_A5  = LCELL( _EQ237);
  _EQ237 = !piosts1
         #  piosts0;

-- Node name is '~972~1' from file "intf.tdf" line 284, column 17
-- Equation name is '~972~1', location is LC2_A14, type is buried.
-- synthesized logic cell 
!_LC2_A14 = _LC2_A14~NOT;
_LC2_A14~NOT = LCELL( _EQ238C);
 _EQ238C =  _EQ238;
  _EQ238 = !ncnt3 & !ncnt4 & !ncnt5;

-- Node name is '~972~2' from file "intf.tdf" line 284, column 17
-- Equation name is '~972~2', location is LC3_A14, type is buried.
-- synthesized logic cell 
!_LC3_A14 = _LC3_A14~NOT;
_LC3_A14~NOT = LCELL( _EQ239C);
 _EQ239C =  _EQ239 & CASCADE( _EQ238C);
  _EQ239 =  ncnt0 & !ncnt1 & !ncnt2;

-- Node name is '~972~3' from file "intf.tdf" line 284, column 17
-- Equation name is '~972~3', location is LC4_A14, type is buried.
-- synthesized logic cell 
!_LC4_A14 = _LC4_A14~NOT;
_LC4_A14~NOT = LCELL( _EQ240C);
 _EQ240C =  _EQ240 & CASCADE( _EQ239C);
  _EQ240 = !ncnt6 & !ncnt7 & !ncnt8 & !ncnt9;

-- Node name is '~972~4' from file "intf.tdf" line 284, column 17
-- Equation name is '~972~4', location is LC1_F20, type is buried.
-- synthesized logic cell 
_LC1_F20 = LCELL( _EQ241);
  _EQ241 =  ncnt12
         #  ncnt13
         #  ncnt11
         #  ncnt10;

-- Node name is ':981' from file "intf.tdf" line 291, column 16
-- Equation name is '_LC5_A6', type is buried 
_LC5_A6  = LCELL( _EQ242);
  _EQ242 = !dmaack_drns & !dmar_drns &  hl_data1 & !nors;

-- Node name is ':983' from file "intf.tdf" line 291, column 16
-- Equation name is '_LC2_A8', type is buried 
_LC2_A8  = LCELL( _EQ243);
  _EQ243 = !dmaack_drns & !dmar_drns &  hl_data3 & !nors;

-- Node name is ':984' from file "intf.tdf" line 291, column 16
-- Equation name is '_LC2_A11', type is buried 
_LC2_A11 = LCELL( _EQ244);
  _EQ244 = !dmaack_drns & !dmar_drns &  hl_data4 & !nors;

-- Node name is ':986' from file "intf.tdf" line 291, column 16
-- Equation name is '_LC1_A3', type is buried 
_LC1_A3  = LCELL( _EQ245);
  _EQ245 = !dmaack_drns & !dmar_drns &  hl_data6 & !nors;

-- Node name is ':987' from file "intf.tdf" line 291, column 16
-- Equation name is '_LC1_A10', type is buried 
_LC1_A10 = LCELL( _EQ246);
  _EQ246 = !dmaack_drns & !dmar_drns &  hl_data7 & !nors;

-- Node name is '~1006~1' from file "intf.tdf" line 293, column 25
-- Equation name is '~1006~1', location is LC6_F24, type is buried.
-- synthesized logic cell 
!_LC6_F24 = _LC6_F24~NOT;
_LC6_F24~NOT = LCELL( _EQ247);
  _EQ247 =  ncnt9
         #  ncnt10
         #  ncnt11
         #  ncnt12;

-- Node name is '~1006~2' from file "intf.tdf" line 293, column 25
-- Equation name is '~1006~2', location is LC5_A14, type is buried.
-- synthesized logic cell 
_LC5_A14 = LCELL( _EQ248C);
 _EQ248C =  _EQ248;
  _EQ248 = !ncnt3 & !ncnt4;

-- Node name is '~1006~3' from file "intf.tdf" line 293, column 25
-- Equation name is '~1006~3', location is LC6_A14, type is buried.
-- synthesized logic cell 
_LC6_A14 = LCELL( _EQ249C);
 _EQ249C =  _EQ249 & CASCADE( _EQ248C);
  _EQ249 = !ncnt0 & !ncnt1 & !ncnt2;

-- Node name is '~1006~4' from file "intf.tdf" line 293, column 25
-- Equation name is '~1006~4', location is LC7_A14, type is buried.
-- synthesized logic cell 
_LC7_A14 = LCELL( _EQ250C);
 _EQ250C =  _EQ250 & CASCADE( _EQ249C);
  _EQ250 = !ncnt5 & !ncnt6 & !ncnt7 & !ncnt8;

-- Node name is ':1007' from file "intf.tdf" line 293, column 17
-- Equation name is '_LC8_A14', type is buried 
_LC8_A14 = LCELL( _EQ251);
  _EQ251 =  ce &  ncnt13
         #  ce & !_LC6_F24
         #  ce & !_LC7_A14;

-- Node name is ':1009' from file "intf.tdf" line 293, column 7
-- Equation name is '_LC3_A8', type is buried 
_LC3_A8  = LCELL( _EQ252);
  _EQ252 =  dmaack_drns &  _LC8_A14
         #  _LC8_A14 &  nors
         #  dmar_drns &  _LC8_A14;

-- Node name is ':1017' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC3_A20_CARRY', type is buried 
-- :1017 is in Up/Down Counter Mode
_LC3_A20_CARRY = CARRY( _EQ253);
  _EQ253 =  ncnt0
         #  ncnt1;

-- Node name is '~1022~1' from file "intf.tdf" line 294, column 29
-- Equation name is '~1022~1', location is LC5_A20_CARRY, type is buried.
-- synthesized logic cell 
_LC5_A20_CARRY = CARRY( _LC4_A20_CARRY);

-- Node name is '~1022~2' from file "intf.tdf" line 294, column 29
-- Equation name is '~1022~2', location is LC5_A20, type is buried.
-- synthesized logic cell 
_LC5_A20 = LCELL( _LC4_A20_CARRY);

-- Node name is ':1022' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC4_A20_CARRY', type is buried 
-- :1022 is in Up/Down Counter Mode
_LC4_A20_CARRY = CARRY( _EQ254);
  _EQ254 =  ncnt2
         #  _LC3_A20_CARRY;

-- Node name is '~1027~1' from file "intf.tdf" line 294, column 29
-- Equation name is '~1027~1', location is LC7_A20_CARRY, type is buried.
-- synthesized logic cell 
_LC7_A20_CARRY = CARRY( _LC6_A20_CARRY);

-- Node name is '~1027~2' from file "intf.tdf" line 294, column 29
-- Equation name is '~1027~2', location is LC7_A20, type is buried.
-- synthesized logic cell 
_LC7_A20 = LCELL( _LC6_A20_CARRY);

-- Node name is ':1027' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC6_A20_CARRY', type is buried 
-- :1027 is in Up/Down Counter Mode
_LC6_A20_CARRY = CARRY( _EQ255);
  _EQ255 =  ncnt3
         #  _LC5_A20_CARRY;

-- Node name is ':1033' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC8_A20_CARRY', type is buried 
-- :1033 is in Up/Down Counter Mode
_LC8_A20_CARRY = CARRY( _EQ256);
  _EQ256 =  ncnt4
         #  _LC7_A20_CARRY;

-- Node name is '~1038~1' from file "intf.tdf" line 294, column 29
-- Equation name is '~1038~1', location is LC2_A22_CARRY, type is buried.
-- synthesized logic cell 
_LC2_A22_CARRY = CARRY( _LC1_A22_CARRY);

-- Node name is '~1038~2' from file "intf.tdf" line 294, column 29
-- Equation name is '~1038~2', location is LC2_A22, type is buried.
-- synthesized logic cell 
_LC2_A22 = LCELL( _LC1_A22_CARRY);

-- Node name is ':1038' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC1_A22_CARRY', type is buried 
-- :1038 is in Up/Down Counter Mode
_LC1_A22_CARRY = CARRY( _EQ257);
  _EQ257 =  ncnt5
         #  _LC8_A20_CARRY;

-- Node name is '~1043~1' from file "intf.tdf" line 294, column 29
-- Equation name is '~1043~1', location is LC4_A22_CARRY, type is buried.
-- synthesized logic cell 
_LC4_A22_CARRY = CARRY( _LC3_A22_CARRY);

-- Node name is '~1043~2' from file "intf.tdf" line 294, column 29
-- Equation name is '~1043~2', location is LC4_A22, type is buried.
-- synthesized logic cell 
_LC4_A22 = LCELL( _LC3_A22_CARRY);

-- Node name is ':1043' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC3_A22_CARRY', type is buried 
-- :1043 is in Up/Down Counter Mode
_LC3_A22_CARRY = CARRY( _EQ258);
  _EQ258 =  ncnt6
         #  _LC2_A22_CARRY;

-- Node name is '~1049~1' from file "intf.tdf" line 294, column 29
-- Equation name is '~1049~1', location is LC6_A22, type is buried.
-- synthesized logic cell 
_LC6_A22 = LCELL( _LC5_A22_CARRY);

-- Node name is ':1049' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC5_A22_CARRY', type is buried 
-- :1049 is in Up/Down Counter Mode
_LC5_A22_CARRY = CARRY( _EQ259);
  _EQ259 =  ncnt7
         #  _LC4_A22_CARRY;

-- Node name is ':1057' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC1_A12', type is buried 
_LC1_A12 = LCELL( _EQ260C);
 _EQ260C =  _EQ260;
  _EQ260 = !_LC6_A22 & !ncnt8 & !ncnt9
         #  ncnt8 &  ncnt9
         #  _LC6_A22 &  ncnt9;

-- Node name is ':1059' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC3_F3', type is buried 
_LC3_F3  = LCELL( _EQ261);
  _EQ261 =  ncnt9
         #  ncnt8
         #  _LC6_A22;

-- Node name is ':1065' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC3_F21', type is buried 
_LC3_F21 = LCELL( _EQ262);
  _EQ262 =  ncnt10
         #  ncnt9
         #  ncnt8
         #  _LC6_A22;

-- Node name is ':1073' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC1_F3', type is buried 
_LC1_F3  = LCELL( _EQ263C);
 _EQ263C =  _EQ263;
  _EQ263 = !_LC3_F3 & !ncnt10 & !ncnt11 & !ncnt12
         #  ncnt11 &  ncnt12
         #  ncnt10 &  ncnt12
         #  _LC3_F3 &  ncnt12;

-- Node name is ':1075' from file "intf.tdf" line 294, column 29
-- Equation name is '_LC7_F21', type is buried 
_LC7_F21 = LCELL( _EQ264);
  _EQ264 =  ncnt12
         #  ncnt11
         #  _LC3_F21;

-- Node name is ':1100' from file "intf.tdf" line 294, column 18
-- Equation name is '_LC2_A12', type is buried 
_LC2_A12 = LCELL( _EQ265C);
 _EQ265C =  _EQ265 & CASCADE( _EQ260C);
  _EQ265 =  dmaack_drns &  _LC8_A14
         #  _LC8_A14 &  nors
         #  dmar_drns &  _LC8_A14;

-- Node name is ':1106' from file "intf.tdf" line 294, column 18
-- Equation name is '_LC2_F3', type is buried 
_LC2_F3  = LCELL( _EQ266C);
 _EQ266C =  _EQ266 & CASCADE( _EQ263C);
  _EQ266 =  dmaack_drns &  _LC8_A14
         #  _LC8_A14 &  nors
         #  dmar_drns &  _LC8_A14;

-- Node name is '~1116~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1116~1', location is LC1_A24, type is buried.
-- synthesized logic cell 
!_LC1_A24 = _LC1_A24~NOT;
_LC1_A24~NOT = LCELL( _EQ267);
  _EQ267 =  ncnt0 & !ncnt1
         #  nread
         # !_LC8_A14 & !ncnt1
         #  _LC8_A14 & !ncnt0 &  ncnt1;

-- Node name is '~1118~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1118~1', location is LC8_A17, type is buried.
-- synthesized logic cell 
!_LC8_A17 = _LC8_A17~NOT;
_LC8_A17~NOT = LCELL( _EQ268);
  _EQ268 = !ncnt2 & !nread
         #  _LC8_A14 & !nread
         # !hl_data2 & !ncnt2
         # !hl_data2 &  _LC8_A14
         # !hl_data2 &  nread;

-- Node name is '~1120~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1120~1', location is LC1_A20, type is buried.
-- synthesized logic cell 
!_LC1_A20 = _LC1_A20~NOT;
_LC1_A20~NOT = LCELL( _EQ269);
  _EQ269 =  _LC5_A20 & !ncnt3
         #  nread
         # !_LC8_A14 & !ncnt3
         # !_LC5_A20 &  _LC8_A14 &  ncnt3;

-- Node name is '~1122~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1122~1', location is LC2_A20, type is buried.
-- synthesized logic cell 
!_LC2_A20 = _LC2_A20~NOT;
_LC2_A20~NOT = LCELL( _EQ270);
  _EQ270 =  _LC7_A20 & !ncnt4
         #  nread
         # !_LC8_A14 & !ncnt4
         # !_LC7_A20 &  _LC8_A14 &  ncnt4;

-- Node name is '~1124~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1124~1', location is LC5_A13, type is buried.
-- synthesized logic cell 
!_LC5_A13 = _LC5_A13~NOT;
_LC5_A13~NOT = LCELL( _EQ271);
  _EQ271 = !ncnt5 & !nread
         #  _LC8_A14 & !nread
         # !hl_data5 & !ncnt5
         # !hl_data5 &  _LC8_A14
         # !hl_data5 &  nread;

-- Node name is '~1126~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1126~1', location is LC7_A22, type is buried.
-- synthesized logic cell 
!_LC7_A22 = _LC7_A22~NOT;
_LC7_A22~NOT = LCELL( _EQ272);
  _EQ272 =  _LC2_A22 & !ncnt6
         #  nread
         # !_LC8_A14 & !ncnt6
         # !_LC2_A22 &  _LC8_A14 &  ncnt6;

-- Node name is '~1128~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1128~1', location is LC8_A22, type is buried.
-- synthesized logic cell 
!_LC8_A22 = _LC8_A22~NOT;
_LC8_A22~NOT = LCELL( _EQ273);
  _EQ273 =  _LC4_A22 & !ncnt7
         #  nread
         # !_LC8_A14 & !ncnt7
         # !_LC4_A22 &  _LC8_A14 &  ncnt7;

-- Node name is '~1130~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1130~1', location is LC4_A12, type is buried.
-- synthesized logic cell 
_LC4_A12 = LCELL( _EQ274);
  _EQ274 = !_LC8_A14 &  ncnt8 & !nread
         #  hl_data8 &  nread;

-- Node name is ':1131' from file "intf.tdf" line 296, column 18
-- Equation name is '_LC6_A12', type is buried 
_LC6_A12 = LCELL( _EQ275);
  _EQ275 = !_LC8_A14 &  ncnt9 & !nread;

-- Node name is '~1134~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1134~1', location is LC4_F3, type is buried.
-- synthesized logic cell 
_LC4_F3  = LCELL( _EQ276);
  _EQ276 = !_LC3_F3 &  _LC8_A14 & !ncnt10 & !nread
         #  _LC3_F3 &  ncnt10 & !nread
         # !_LC8_A14 &  ncnt10 & !nread;

-- Node name is '~1136~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1136~1', location is LC4_F21, type is buried.
-- synthesized logic cell 
_LC4_F21 = LCELL( _EQ277);
  _EQ277 = !_LC8_A14 &  ncnt11 & !nread
         #  hl_data11 &  nread;

-- Node name is ':1137' from file "intf.tdf" line 296, column 18
-- Equation name is '_LC7_F3', type is buried 
_LC7_F3  = LCELL( _EQ278);
  _EQ278 = !_LC8_A14 &  ncnt12 & !nread;

-- Node name is '~1140~1' from file "intf.tdf" line 296, column 18
-- Equation name is '~1140~1', location is LC2_A24, type is buried.
-- synthesized logic cell 
_LC2_A24 = LCELL( _EQ279);
  _EQ279 = !_LC8_A14 &  ncnt13 & !nread
         #  hl_data13 &  nread;

-- Node name is ':1145' from file "intf.tdf" line 310, column 7
-- Equation name is '_LC6_E16', type is buried 
_LC6_E16 = LCELL( _EQ280);
  _EQ280 =  pio &  piosts0 &  piosts1;

-- Node name is ':1146' from file "intf.tdf" line 311, column 25
-- Equation name is '_LC6_E20', type is buried 
_LC6_E20 = LCELL( _EQ281);
  _EQ281 =  pio &  piobn0 &  piosts0 &  piosts1;

-- Node name is ':1148' from file "intf.tdf" line 311, column 25
-- Equation name is '_LC1_D7', type is buried 
_LC1_D7  = LCELL( _EQ282);
  _EQ282 =  pio &  piobn2 &  piosts0 &  piosts1;

-- Node name is ':1149' from file "intf.tdf" line 311, column 25
-- Equation name is '_LC1_C6', type is buried 
_LC1_C6  = LCELL( _EQ283);
  _EQ283 =  pio &  piobn3 &  piosts0 &  piosts1;

-- Node name is ':1151' from file "intf.tdf" line 311, column 25
-- Equation name is '_LC7_D7', type is buried 
_LC7_D7  = LCELL( _EQ284);
  _EQ284 =  pio &  piobn5 &  piosts0 &  piosts1;

-- Node name is ':1152' from file "intf.tdf" line 311, column 25
-- Equation name is '_LC3_C10', type is buried 
_LC3_C10 = LCELL( _EQ285);
  _EQ285 =  pio &  piobn6 &  piosts0 &  piosts1;

-- Node name is ':1157' from file "intf.tdf" line 312, column 23
-- Equation name is '_LC7_E24', type is buried 
_LC7_E24 = LCELL( _EQ286);
  _EQ286 =  pio &  piocom0 &  piosts0 &  piosts1;

-- Node name is ':1159' from file "intf.tdf" line 312, column 23
-- Equation name is '_LC4_C18', type is buried 
_LC4_C18 = LCELL( _EQ287);
  _EQ287 =  pio &  piocom2 &  piosts0 &  piosts1;

-- Node name is ':1160' from file "intf.tdf" line 312, column 23
-- Equation name is '_LC1_C4', type is buried 
_LC1_C4  = LCELL( _EQ288);
  _EQ288 =  pio &  piocom3 &  piosts0 &  piosts1;

-- Node name is ':1162' from file "intf.tdf" line 312, column 23
-- Equation name is '_LC5_E1', type is buried 
_LC5_E1  = LCELL( _EQ289);
  _EQ289 =  pio &  piocom5 &  piosts0 &  piosts1;

-- Node name is ':1163' from file "intf.tdf" line 312, column 23
-- Equation name is '_LC6_E8', type is buried 
_LC6_E8  = LCELL( _EQ290);
  _EQ290 =  pio &  piocom6 &  piosts0 &  piosts1;

-- Node name is '~1177~1' from file "intf.tdf" line 318, column 44
-- Equation name is '~1177~1', location is LC1_D21, type is buried.
-- synthesized logic cell 
_LC1_D21 = LCELL( _EQ291C);
 _EQ291C =  _EQ291;
  _EQ291 = !bncnt_dwreg4 & !bncnt_dwreg5 & !bncnt_dwreg6;

-- Node name is '~1177~2' from file "intf.tdf" line 318, column 44
-- Equation name is '~1177~2', location is LC2_D21, type is buried.
-- synthesized logic cell 
_LC2_D21 = LCELL( _EQ292C);
 _EQ292C =  _EQ292 & CASCADE( _EQ291C);
  _EQ292 = !bncnt_dwreg1 & !bncnt_dwreg2 & !bncnt_dwreg3;

-- Node name is '~1177~3' from file "intf.tdf" line 318, column 44
-- Equation name is '~1177~3', location is LC3_D21, type is buried.
-- synthesized logic cell 
_LC3_D21 = LCELL( _EQ293C);
 _EQ293C =  _EQ293 & CASCADE( _EQ292C);
  _EQ293 = !bncnt_dwreg7 & !bncnt_dwreg8 & !bncnt_dwreg9 & !bncnt_dwreg10;

-- Node name is ':1181' from file "intf.tdf" line 318, column 7
-- Equation name is '_LC4_D14', type is buried 
_LC4_D14 = LCELL( _EQ294);
  _EQ294 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1192' from file "intf.tdf" line 319, column 43
-- Equation name is '_LC1_D10', type is buried 
_LC1_D10 = LCELL( _EQ295C);
 _EQ295C =  _EQ295;
  _EQ295 = !bncnt_dwreg0 & !bncnt_dwreg1 & !bncnt_dwreg2
         #  bncnt_dwreg0 &  bncnt_dwreg2
         #  bncnt_dwreg1 &  bncnt_dwreg2;

-- Node name is ':1197' from file "intf.tdf" line 319, column 43
-- Equation name is '_LC3_D10', type is buried 
_LC3_D10 = LCELL( _EQ296C);
 _EQ296C =  _EQ296;
  _EQ296 = !bncnt_dwreg0 & !bncnt_dwreg1 & !bncnt_dwreg2 & !bncnt_dwreg3
         #  bncnt_dwreg0 &  bncnt_dwreg3
         #  bncnt_dwreg1 &  bncnt_dwreg3
         #  bncnt_dwreg2 &  bncnt_dwreg3;

-- Node name is ':1199' from file "intf.tdf" line 319, column 43
-- Equation name is '_LC1_D3', type is buried 
_LC1_D3  = LCELL( _EQ297);
  _EQ297 =  bncnt_dwreg3
         #  bncnt_dwreg2
         #  bncnt_dwreg0
         #  bncnt_dwreg1;

-- Node name is ':1208' from file "intf.tdf" line 319, column 43
-- Equation name is '_LC3_D11', type is buried 
_LC3_D11 = LCELL( _EQ298C);
 _EQ298C =  _EQ298;
  _EQ298 = !bncnt_dwreg4 & !bncnt_dwreg5 & !_LC1_D3
         #  bncnt_dwreg4 &  bncnt_dwreg5
         #  bncnt_dwreg5 &  _LC1_D3;

-- Node name is ':1213' from file "intf.tdf" line 319, column 43
-- Equation name is '_LC1_D11', type is buried 
_LC1_D11 = LCELL( _EQ299C);
 _EQ299C =  _EQ299;
  _EQ299 = !bncnt_dwreg4 & !bncnt_dwreg5 & !bncnt_dwreg6 & !_LC1_D3
         #  bncnt_dwreg5 &  bncnt_dwreg6
         #  bncnt_dwreg4 &  bncnt_dwreg6
         #  bncnt_dwreg6 &  _LC1_D3;

-- Node name is ':1215' from file "intf.tdf" line 319, column 43
-- Equation name is '_LC6_D6', type is buried 
_LC6_D6  = LCELL( _EQ300);
  _EQ300 =  bncnt_dwreg4
         #  _LC1_D3
         #  bncnt_dwreg5
         #  bncnt_dwreg6;

-- Node name is ':1221' from file "intf.tdf" line 319, column 43
-- Equation name is '_LC5_D22', type is buried 
_LC5_D22 = LCELL( _EQ301);
  _EQ301 =  bncnt_dwreg7
         #  _LC6_D6;

-- Node name is ':1229' from file "intf.tdf" line 319, column 43
-- Equation name is '_LC1_D15', type is buried 
_LC1_D15 = LCELL( _EQ302C);
 _EQ302C =  _EQ302;
  _EQ302 = !bncnt_dwreg7 & !bncnt_dwreg8 & !bncnt_dwreg9 & !_LC6_D6
         #  bncnt_dwreg8 &  bncnt_dwreg9
         #  bncnt_dwreg7 &  bncnt_dwreg9
         #  bncnt_dwreg9 &  _LC6_D6;

-- Node name is ':1231' from file "intf.tdf" line 319, column 43
-- Equation name is '_LC7_D21', type is buried 
_LC7_D21 = LCELL( _EQ303);
  _EQ303 =  bncnt_dwreg9
         #  bncnt_dwreg8
         #  bncnt_dwreg7
         #  _LC6_D6;

-- Node name is ':1242' from file "intf.tdf" line 319, column 25
-- Equation name is '_LC2_D10', type is buried 
_LC2_D10 = LCELL( _EQ304C);
 _EQ304C =  _EQ304 & CASCADE( _EQ295C);
  _EQ304 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1244' from file "intf.tdf" line 319, column 25
-- Equation name is '_LC4_D10', type is buried 
_LC4_D10 = LCELL( _EQ305C);
 _EQ305C =  _EQ305 & CASCADE( _EQ296C);
  _EQ305 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1248' from file "intf.tdf" line 319, column 25
-- Equation name is '_LC4_D11', type is buried 
_LC4_D11 = LCELL( _EQ306C);
 _EQ306C =  _EQ306 & CASCADE( _EQ298C);
  _EQ306 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1250' from file "intf.tdf" line 319, column 25
-- Equation name is '_LC2_D11', type is buried 
_LC2_D11 = LCELL( _EQ307C);
 _EQ307C =  _EQ307 & CASCADE( _EQ299C);
  _EQ307 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1256' from file "intf.tdf" line 319, column 25
-- Equation name is '_LC2_D15', type is buried 
_LC2_D15 = LCELL( _EQ308C);
 _EQ308C =  _EQ308 & CASCADE( _EQ302C);
  _EQ308 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1268' from file "intf.tdf" line 320, column 39
-- Equation name is '_LC3_E9', type is buried 
_LC3_E9  = LCELL( _EQ309C);
 _EQ309C =  _EQ309;
  _EQ309 = !adr_dwreg0 &  adr_dwreg2
         # !adr_dwreg1 &  adr_dwreg2
         #  adr_dwreg0 &  adr_dwreg1 & !adr_dwreg2;

-- Node name is ':1272' from file "intf.tdf" line 320, column 39
-- Equation name is '_LC1_E9', type is buried 
_LC1_E9  = LCELL( _EQ310C);
 _EQ310C =  _EQ310;
  _EQ310 = !adr_dwreg2 &  adr_dwreg3
         # !adr_dwreg0 &  adr_dwreg3
         # !adr_dwreg1 &  adr_dwreg3
         #  adr_dwreg0 &  adr_dwreg1 &  adr_dwreg2 & !adr_dwreg3;

-- Node name is ':1274' from file "intf.tdf" line 320, column 39
-- Equation name is '_LC5_E9', type is buried 
_LC5_E9  = LCELL( _EQ311);
  _EQ311 =  adr_dwreg0 &  adr_dwreg1 &  adr_dwreg2 &  adr_dwreg3;

-- Node name is ':1280' from file "intf.tdf" line 320, column 39
-- Equation name is '_LC3_E8', type is buried 
_LC3_E8  = LCELL( _EQ312C);
 _EQ312C =  _EQ312;
  _EQ312 = !adr_dwreg4 &  adr_dwreg5
         #  adr_dwreg5 & !_LC5_E9
         #  adr_dwreg4 & !adr_dwreg5 &  _LC5_E9;

-- Node name is ':1284' from file "intf.tdf" line 320, column 39
-- Equation name is '_LC1_E8', type is buried 
_LC1_E8  = LCELL( _EQ313C);
 _EQ313C =  _EQ313;
  _EQ313 = !adr_dwreg5 &  adr_dwreg6
         # !adr_dwreg4 &  adr_dwreg6
         #  adr_dwreg6 & !_LC5_E9
         #  adr_dwreg4 &  adr_dwreg5 & !adr_dwreg6 &  _LC5_E9;

-- Node name is ':1286' from file "intf.tdf" line 320, column 39
-- Equation name is '_LC2_E11', type is buried 
_LC2_E11 = LCELL( _EQ314);
  _EQ314 =  adr_dwreg4 &  adr_dwreg5 &  adr_dwreg6 &  _LC5_E9;

-- Node name is ':1290' from file "intf.tdf" line 320, column 39
-- Equation name is '_LC2_E22', type is buried 
_LC2_E22 = LCELL( _EQ315);
  _EQ315 =  adr_dwreg7 &  _LC2_E11;

-- Node name is ':1296' from file "intf.tdf" line 320, column 39
-- Equation name is '_LC1_E20', type is buried 
_LC1_E20 = LCELL( _EQ316C);
 _EQ316C =  _EQ316;
  _EQ316 = !adr_dwreg8 &  adr_dwreg9
         # !adr_dwreg7 &  adr_dwreg9
         #  adr_dwreg9 & !_LC2_E11
         #  adr_dwreg7 &  adr_dwreg8 & !adr_dwreg9 &  _LC2_E11;

-- Node name is ':1303' from file "intf.tdf" line 320, column 23
-- Equation name is '_LC4_E9', type is buried 
_LC4_E9  = LCELL( _EQ317C);
 _EQ317C =  _EQ317 & CASCADE( _EQ309C);
  _EQ317 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1305' from file "intf.tdf" line 320, column 23
-- Equation name is '_LC2_E9', type is buried 
_LC2_E9  = LCELL( _EQ318C);
 _EQ318C =  _EQ318 & CASCADE( _EQ310C);
  _EQ318 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1309' from file "intf.tdf" line 320, column 23
-- Equation name is '_LC4_E8', type is buried 
_LC4_E8  = LCELL( _EQ319C);
 _EQ319C =  _EQ319 & CASCADE( _EQ312C);
  _EQ319 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1311' from file "intf.tdf" line 320, column 23
-- Equation name is '_LC2_E8', type is buried 
_LC2_E8  = LCELL( _EQ320C);
 _EQ320C =  _EQ320 & CASCADE( _EQ313C);
  _EQ320 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1317' from file "intf.tdf" line 320, column 23
-- Equation name is '_LC2_E20', type is buried 
_LC2_E20 = LCELL( _EQ321C);
 _EQ321C =  _EQ321 & CASCADE( _EQ316C);
  _EQ321 =  bncnt_dwreg0 & !img_dma_ack5 & !pio
         # !img_dma_ack5 & !_LC3_D21 & !pio;

-- Node name is ':1321' from file "intf.tdf" line 318, column 7
-- Equation name is '_LC2_D2', type is buried 
_LC2_D2  = LCELL( _EQ322);
  _EQ322 =  img_dma_ack5 & !pio
         # !bncnt_dwreg0 &  _LC3_D21 & !pio;

-- Node name is '~1325~1' from file "intf.tdf" line 322, column 25
-- Equation name is '~1325~1', location is LC7_D15, type is buried.
-- synthesized logic cell 
_LC7_D15 = LCELL( _EQ323);
  _EQ323 =  bncnt_dwreg0 &  bncnt_dwreg1 &  _LC4_D14
         # !bncnt_dwreg0 & !bncnt_dwreg1 &  _LC4_D14
         #  bncnt_dwreg1 &  _LC2_D2;

-- Node name is '~1331~1' from file "intf.tdf" line 322, column 25
-- Equation name is '~1331~1', location is LC1_D4, type is buried.
-- synthesized logic cell 
_LC1_D4  = LCELL( _EQ324);
  _EQ324 = !bncnt_dwreg4 & !_LC1_D3 &  _LC4_D14
         #  bncnt_dwreg4 &  _LC1_D3 &  _LC4_D14
         #  bncnt_dwreg4 &  _LC2_D2;

-- Node name is '~1337~1' from file "intf.tdf" line 322, column 25
-- Equation name is '~1337~1', location is LC4_D22, type is buried.
-- synthesized logic cell 
_LC4_D22 = LCELL( _EQ325);
  _EQ325 = !bncnt_dwreg7 &  _LC4_D14 & !_LC6_D6
         #  bncnt_dwreg7 &  _LC4_D14 &  _LC6_D6
         #  bncnt_dwreg7 &  _LC2_D2;

-- Node name is '~1339~1' from file "intf.tdf" line 322, column 25
-- Equation name is '~1339~1', location is LC3_D22, type is buried.
-- synthesized logic cell 
_LC3_D22 = LCELL( _EQ326);
  _EQ326 =  bncnt_dwreg8 &  _LC2_D2
         #  _LC6_E16 &  piobn8;

-- Node name is ':1340' from file "intf.tdf" line 322, column 25
-- Equation name is '_LC6_D15', type is buried 
_LC6_D15 = LCELL( _EQ327);
  _EQ327 =  bncnt_dwreg9 &  _LC2_D2;

-- Node name is '~1343~1' from file "intf.tdf" line 322, column 25
-- Equation name is '~1343~1', location is LC6_D21, type is buried.
-- synthesized logic cell 
_LC6_D21 = LCELL( _EQ328);
  _EQ328 = !bncnt_dwreg10 &  _LC4_D14 & !_LC7_D21
         #  bncnt_dwreg10 &  _LC4_D14 &  _LC7_D21
         #  bncnt_dwreg10 &  _LC2_D2;

-- Node name is '~1347~1' from file "intf.tdf" line 323, column 23
-- Equation name is '~1347~1', location is LC3_E22, type is buried.
-- synthesized logic cell 
_LC3_E22 = LCELL( _EQ329);
  _EQ329 =  adr_dwreg0 & !adr_dwreg1 &  _LC4_D14
         # !adr_dwreg0 &  adr_dwreg1 &  _LC4_D14
         #  adr_dwreg1 &  _LC2_D2;

-- Node name is '~1353~1' from file "intf.tdf" line 323, column 23
-- Equation name is '~1353~1', location is LC1_E5, type is buried.
-- synthesized logic cell 
_LC1_E5  = LCELL( _EQ330);
  _EQ330 =  adr_dwreg4 &  _LC4_D14 & !_LC5_E9
         # !adr_dwreg4 &  _LC4_D14 &  _LC5_E9
         #  adr_dwreg4 &  _LC2_D2;

-- Node name is '~1359~1' from file "intf.tdf" line 323, column 23
-- Equation name is '~1359~1', location is LC5_E22, type is buried.
-- synthesized logic cell 
_LC5_E22 = LCELL( _EQ331);
  _EQ331 =  adr_dwreg7 & !_LC2_E11 &  _LC4_D14
         # !adr_dwreg7 &  _LC2_E11 &  _LC4_D14
         #  adr_dwreg7 &  _LC2_D2;

-- Node name is '~1361~1' from file "intf.tdf" line 323, column 23
-- Equation name is '~1361~1', location is LC6_E22, type is buried.
-- synthesized logic cell 
_LC6_E22 = LCELL( _EQ332);
  _EQ332 =  adr_dwreg8 &  _LC2_D2
         #  _LC6_E16 &  piocom8;

-- Node name is ':1362' from file "intf.tdf" line 323, column 23
-- Equation name is '_LC4_E20', type is buried 
_LC4_E20 = LCELL( _EQ333);
  _EQ333 =  adr_dwreg9 &  _LC2_D2;

-- Node name is '~1373~1' from file "intf.tdf" line 327, column 42
-- Equation name is '~1373~1', location is LC4_D21, type is buried.
-- synthesized logic cell 
_LC4_D21 = LCELL( _EQ334);
  _EQ334 = !bncnt_dwreg7 & !bncnt_dwreg8 & !bncnt_dwreg9 & !bncnt_dwreg10;

-- Node name is '~1373~2' from file "intf.tdf" line 327, column 42
-- Equation name is '~1373~2', location is LC4_D17, type is buried.
-- synthesized logic cell 
_LC4_D17 = LCELL( _EQ335);
  _EQ335 = !bncnt_dwreg0 & !bncnt_dwreg1 & !bncnt_dwreg2;

-- Node name is '~1373~3' from file "intf.tdf" line 327, column 42
-- Equation name is '~1373~3', location is LC3_D17, type is buried.
-- synthesized logic cell 
_LC3_D17 = LCELL( _EQ336);
  _EQ336 = !bncnt_dwreg3 & !bncnt_dwreg4 & !bncnt_dwreg5 & !bncnt_dwreg6;

-- Node name is ':1375' from file "intf.tdf" line 327, column 27
-- Equation name is '_LC1_D17', type is buried 
!_LC1_D17 = _LC1_D17~NOT;
_LC1_D17~NOT = LCELL( _EQ337);
  _EQ337 =  _LC3_D17 &  _LC4_D17 &  _LC4_D21
         #  img_dma_ack5;

-- Node name is '~1392~1' from file "intf.tdf" line 347, column 20
-- Equation name is '~1392~1', location is LC4_D23, type is buried.
-- synthesized logic cell 
_LC4_D23 = LCELL( _EQ338);
  _EQ338 =  _LC2_D23
         #  d_write2 & !_LC1_D23;

-- Node name is '~1406~1' from file "intf.tdf" line 361, column 17
-- Equation name is '~1406~1', location is LC3_D16, type is buried.
-- synthesized logic cell 
_LC3_D16 = LCELL( _EQ339);
  _EQ339 =  _LC1_D23 &  pg_gg
         # !d_write2 &  pg_gg;

-- Node name is ':1466' from file "intf.tdf" line 381, column 18
-- Equation name is '_LC1_B9', type is buried 
!_LC1_B9 = _LC1_B9~NOT;
_LC1_B9~NOT = LCELL( _EQ340C);
 _EQ340C =  _EQ340;
  _EQ340 =  piosts1
         # !piosts0
         # !dmar_drreg;

-- Node name is ':1472' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC5_A16', type is buried 
_LC5_A16 = LCELL( _EQ341);
  _EQ341 =  adr_drram0 & !piosts0 & !piosts1
         #  ncnt0 & !piosts0 &  piosts1;

-- Node name is ':1475' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC2_A16', type is buried 
_LC2_A16 = LCELL( _EQ342);
  _EQ342 =  adr_drram1 & !piosts0 & !piosts1
         #  ncnt1 & !piosts0 &  piosts1;

-- Node name is ':1478' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC5_E21', type is buried 
_LC5_E21 = LCELL( _EQ343);
  _EQ343 =  adr_drram2 & !piosts0 & !piosts1
         #  ncnt2 & !piosts0 &  piosts1;

-- Node name is ':1481' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC6_A9', type is buried 
_LC6_A9  = LCELL( _EQ344);
  _EQ344 =  adr_drram3 & !piosts0 & !piosts1
         #  ncnt3 & !piosts0 &  piosts1;

-- Node name is ':1484' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC6_A16', type is buried 
_LC6_A16 = LCELL( _EQ345);
  _EQ345 =  adr_drram4 & !piosts0 & !piosts1
         #  ncnt4 & !piosts0 &  piosts1;

-- Node name is ':1487' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC4_A2', type is buried 
_LC4_A2  = LCELL( _EQ346);
  _EQ346 =  adr_drram5 & !piosts0 & !piosts1
         #  ncnt5 & !piosts0 &  piosts1;

-- Node name is ':1490' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC8_A7', type is buried 
_LC8_A7  = LCELL( _EQ347);
  _EQ347 =  adr_drram6 & !piosts0 & !piosts1
         #  ncnt6 & !piosts0 &  piosts1;

-- Node name is ':1493' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC5_F8', type is buried 
_LC5_F8  = LCELL( _EQ348);
  _EQ348 =  adr_drram7 & !piosts0 & !piosts1
         #  ncnt7 & !piosts0 &  piosts1;

-- Node name is ':1496' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC2_A1', type is buried 
_LC2_A1  = LCELL( _EQ349);
  _EQ349 =  adr_drram8 & !piosts0 & !piosts1
         #  ncnt8 & !piosts0 &  piosts1;

-- Node name is ':1499' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC6_F12', type is buried 
_LC6_F12 = LCELL( _EQ350);
  _EQ350 =  adr_drram9 & !piosts0 & !piosts1
         #  ncnt9 & !piosts0 &  piosts1;

-- Node name is ':1502' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC1_F21', type is buried 
_LC1_F21 = LCELL( _EQ351);
  _EQ351 =  adr_drram10 & !piosts0 & !piosts1
         #  ncnt10 & !piosts0 &  piosts1;

-- Node name is ':1505' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC1_F17', type is buried 
_LC1_F17 = LCELL( _EQ352);
  _EQ352 =  adr_drram11 & !piosts0 & !piosts1
         #  ncnt11 & !piosts0 &  piosts1;

-- Node name is ':1508' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC1_F13', type is buried 
_LC1_F13 = LCELL( _EQ353);
  _EQ353 =  adr_drram12 & !piosts0 & !piosts1
         #  ncnt12 & !piosts0 &  piosts1;

-- Node name is ':1511' from file "intf.tdf" line 383, column 21
-- Equation name is '_LC1_F16', type is buried 
_LC1_F16 = LCELL( _EQ354);
  _EQ354 =  adr_drram13 & !piosts0 & !piosts1
         #  ncnt13 & !piosts0 &  piosts1;

-- Node name is ':1520' from file "intf.tdf" line 389, column 19
-- Equation name is '_LC1_F11', type is buried 
_LC1_F11 = LCELL( _EQ355);
  _EQ355 =  cs0 &  piosts0;

-- Node name is ':1523' from file "intf.tdf" line 389, column 19
-- Equation name is '_LC2_F11', type is buried 
_LC2_F11 = LCELL( _EQ356);
  _EQ356 =  cs1 &  piosts0;

-- Node name is ':1526' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC3_E24', type is buried 
_LC3_E24 = LCELL( _EQ357);
  _EQ357 =  adr_drreg0 &  piosts0 & !piosts1
         #  adr_dwreg0 &  piosts0 &  piosts1;

-- Node name is ':1529' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC1_C11', type is buried 
_LC1_C11 = LCELL( _EQ358);
  _EQ358 =  adr_drreg1 &  piosts0 & !piosts1
         #  adr_dwreg1 &  piosts0 &  piosts1;

-- Node name is ':1532' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC7_C1', type is buried 
_LC7_C1  = LCELL( _EQ359);
  _EQ359 =  adr_drreg2 &  piosts0 & !piosts1
         #  adr_dwreg2 &  piosts0 &  piosts1;

-- Node name is ':1535' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC5_C12', type is buried 
_LC5_C12 = LCELL( _EQ360);
  _EQ360 =  adr_drreg3 &  piosts0 & !piosts1
         #  adr_dwreg3 &  piosts0 &  piosts1;

-- Node name is ':1538' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC4_C5', type is buried 
_LC4_C5  = LCELL( _EQ361);
  _EQ361 =  adr_drreg4 &  piosts0 & !piosts1
         #  adr_dwreg4 &  piosts0 &  piosts1;

-- Node name is ':1541' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC5_E12', type is buried 
_LC5_E12 = LCELL( _EQ362);
  _EQ362 =  adr_drreg5 &  piosts0 & !piosts1
         #  adr_dwreg5 &  piosts0 &  piosts1;

-- Node name is ':1544' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC6_E10', type is buried 
_LC6_E10 = LCELL( _EQ363);
  _EQ363 =  adr_drreg6 &  piosts0 & !piosts1
         #  adr_dwreg6 &  piosts0 &  piosts1;

-- Node name is ':1547' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC8_E7', type is buried 
_LC8_E7  = LCELL( _EQ364);
  _EQ364 =  adr_drreg7 &  piosts0 & !piosts1
         #  adr_dwreg7 &  piosts0 &  piosts1;

-- Node name is ':1550' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC5_E6', type is buried 
_LC5_E6  = LCELL( _EQ365);
  _EQ365 =  adr_drreg8 &  piosts0 & !piosts1
         #  adr_dwreg8 &  piosts0 &  piosts1;

-- Node name is ':1553' from file "intf.tdf" line 390, column 20
-- Equation name is '_LC7_E20', type is buried 
_LC7_E20 = LCELL( _EQ366);
  _EQ366 =  adr_drreg9 &  piosts0 & !piosts1
         #  adr_dwreg9 &  piosts0 &  piosts1;

-- Node name is ':1555' from file "intf.tdf" line 391, column 18
-- Equation name is '_LC2_B9', type is buried 
!_LC2_B9 = _LC2_B9~NOT;
_LC2_B9~NOT = LCELL( _EQ367C);
 _EQ367C =  _EQ367 & CASCADE( _EQ340C);
  _EQ367 = !dmar_drns & !piosts0 &  piosts1
         #  piosts0 & !piosts1
         # !dmar_drram & !piosts1
         # !dmar_drns & !dmar_drram & !piosts0;



Project Information                                e:\usr\hamada\intf\intf.rpt

** COMPILATION SETTINGS & TIMES **

Processing Menu Commands
------------------------

Design Doctor                             = off

Logic Synthesis:

   Synthesis Type Used                    = Multi-Level

   Default Synthesis Style                = FAST

      Logic option settings in 'FAST' style for 'FLEX10K' family

      CARRY_CHAIN                         = auto
      CARRY_CHAIN_LENGTH                  = 32
      CASCADE_CHAIN                       = auto
      CASCADE_CHAIN_LENGTH                = 2
      DECOMPOSE_GATES                     = on
      DUPLICATE_LOGIC_EXTRACTION          = off
      MINIMIZATION                        = full
      MULTI_LEVEL_FACTORING               = on
      NOT_GATE_PUSH_BACK                  = on
      REDUCE_LOGIC                        = on
      REFACTORIZATION                     = off
      REGISTER_OPTIMIZATION               = on
      RESYNTHESIZE_NETWORK                = on
      SLOW_SLEW_RATE                      = off
      SUBFACTOR_EXTRACTION                = off
      IGNORE_SOFT_BUFFERS                 = on
      USE_LPM_FOR_AHDL_OPERATORS          = off

   Other logic synthesis settings:

      Automatic Global Clock              = on
      Automatic Global Clear              = on
      Automatic Global Preset             = on
      Automatic Global Output Enable      = on
      Automatic Fast I/O                  = off
      Automatic Register Packing          = off
      Automatic Open-Drain Pins           = on
      Automatic Implement in EAB          = off
      One-Hot State Machine Encoding      = off
      Optimize                            = 10

Default Timing Specifications: None

Cut All Bidir Feedback Timing Paths       = on
Cut All Clear & Preset Timing Paths       = on

Ignore Timing Assignments                 = off

Functional SNF Extractor                  = off

Linked SNF Extractor                      = off
Timing SNF Extractor                      = on
Optimize Timing SNF                       = off
Generate AHDL TDO File                    = off
Fitter Settings                           = NORMAL
Smart Recompile                           = off
Total Recompile                           = off

Interface Menu Commands
-----------------------

EDIF Netlist Writer                       = off
Verilog Netlist Writer                    = off
VHDL Netlist Writer                       = off

Compilation Times
-----------------

   Compiler Netlist Extractor             00:00:02
   Database Builder                       00:00:01
   Logic Synthesizer                      00:00:04
   Partitioner                            00:00:02
   Fitter                                 00:00:13
   Timing SNF Extractor                   00:00:03
   Assembler                              00:00:02
   --------------------------             --------
   Total Time                             00:00:27


Memory Allocated
-----------------

Peak memory allocated during compilation  = 17,036K



