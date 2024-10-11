===========
Xilinx Wiki
===========
https://xilinx-wiki.atlassian.net/wiki/spaces/A/overview?homepageId=18844350

==========
FPGA Specs
==========
https://www.electronicspecifier.com/attachment/view/5d5fb3495a8ec9e14f8b456d/Xilinx%20VU19P%20Datasheet


====
PCIe
====
pg213 - UltraScale+ Devices Integrated Block for PCI Express
pg239 - PCIe Express PHY
PCIe Debug - https://xilinx.github.io/pcie-debug-kmap/pciedebug/build/html/docs/PCIe_Collaterals/PCIe_LFARs_Long_Form_Answer_Records.html

===
DDR
===
UG586 - https://docs.amd.com/r/en-US/ug586_7Series_MIS/Clocking-Architecture?tocId=vKZi3JogyCep57tDVzAT3Q

===================
Gigabit Transceiver
===================
UG578 - https://docs.amd.com/v/u/en-US/ug578-ultrascale-gty-transceivers

Main Components: GTY_COMMON, GTY_CHANNEL, CPLL/QPLL, PCS/PMA, PCIE404E Block, GT Quad, 
Reading Material
1. https://billauer.co.il/blog/2016/03/mgt-gtx-fpga/#:~:text=QPLL%20vs.&text=In%20addition%2C%20each%20GTX%20has,the%20QPLL%20covers%20higher%20frequencies.
2. https://0x04.net/~mwk/xidocs/ug/ug578-ultrascale-gty-transceivers.pdf

Common Problems
1. CPLL calibration
https://billauer.co.il/blog/2020/08/xilinx-ultrascale-cpll-calibration/
2. QPLL vs CPLL
With 2.5GT/s, there will only a single CPLL to pair with GTY_CHANNEL. 
QPLL uses both GTY_COMMON and GTY_CHANNEL

GT Usage
pg239 - PCIe Express PHY

=========
Chipscope
=========
- Use pipeline to loosen timing

==============
Expensive FPGA
==============
https://docs.amd.com/r/en-US/Alveo-X3522PV-Adaptable-Accelerator-Card-User-Guide-UG1607/Introduction
