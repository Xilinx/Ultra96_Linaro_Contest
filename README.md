# Welcome to the Xilinx Ultra96 Design Challenge!

# Getting Started
You provided a design idea and we provided an Ultra96 board for you to realize your vision.  
To connect to your new board, refer to the “Getting Started with Ultra96 for Contest” document (above). This will get you set up to connect to the board via WIFI using SSID: zzsoc_<mac_id_of the board>.  

Once connected simply point your browser to 192.168.2.1  At this point you can SSH / VNC in to the board or you can connect a monitor, mouse and keyboard and use Ultra96 like a Raspberry Pi.  If you need a console use the USB port on the Seeed Studio Mezzanine card.   

As you poke around you will notice many things about your Ultra96 board.  First, it’s not called the Ultra96.  The board you got is a pre-production version of the board that was called alternately ZCU100 or ZZSOC.  Not to worry, the board you have is one of over a thousand produced and is exactly what is being sold as Ultra96.

Another thing to notice is that there are two different environments on your board.  It will start up and run a mainstream Linux that was created with the Xilinx PetaLinux tool.  There is another environment that you can click into (it will reboot the board) called “Pynq”, which is short for Python on Zynq.  It is an environment that is built on top of Ubuntu Linux.   Pynq is available publically on the Pynq-Z1 board and, experimentally, on the board you’ve been given.  It is NOT on the production version of the Ultra96.  You are welcome to use Pynq for your entry.  You can learn more about Pynq from www.pynq.io.  It’s very well-documented and has a very novel way of taking advantage of the programmable logic portion of the Ultra96 board. To make it even easier to use, it is built around Jypyter notebooks (as you’ll see if you boot into it).  

To install additional software on your Ultra96, you’ll need to either download and build manually, or use Yocto.  Pynq, being based on Ubuntu, uses apt-get.  
# Entering Your Design
When you are done your design and have a working prototype, upload it to a github folder on the contest github.  You must have minimally a readme, code and any scripts.  A video explaining and demonstrating your entry is also helpful but not required.  
You may use your github folder throughout your time working on your entry, so be sure to let us know when your entry is complete.  When that happens we will immediately send your gift card.
# Support
There’s a google group set up for support.  https://groups.google.com/forum/#!forum/ultra96-contest . You should have gotten an invite.  If not, let me know and it will be resent.
Deadline
The deadline for completing your design is July 15th, 2018.  Results will be announced August 1st, 2018.  
# Judging
Judging will take place a few weeks after the deadline for submitting your designs.  We’ll provide more details as they become available.
# Background on Programmable Logic
The real power of Ultra96 comes when you put additional functionality in in the programmable logic.  There are a few different ways to do this.  You can design that functionality in the Vivado software environment.  Alternately you can explore some of the Pynq overlays (learn what that means!) that are available in the Pynq environment.   
To learn more about how to use Vivado plus SDK, you should read through the tutorial at https://www.xilinx.com/support/documentation/sw_manuals/xilinx2017_4/ug1209-embedded-design-tutorial.pdf .  The tutorial targets a board other than the Ultra96, but it will give you a good idea of how FPGAs with ARM processors are developed with today.  

At Linaro Connect you were also exposed to an environment called SDSOC, where you could write c-code and SDSOC would enable the c-code to be executed in the FPGA gates.  To learn more about that flow, read through the SDSoC Environment Platform Development Guide. https://www.xilinx.com/support/documentation/sw_manuals/xilinx2017_4/ug1146-sdsoc-platform-development.pdf .  SDSoC is useful and powerful and worth understanding, but unfortunately is not available for you to use for the design contest. 

# Additional Files
These files allow you to rebuild the hardware design in the in Xilinx Vivado tools.

  zcu100_96b_sensors_18_1.tcl
  
  zcu100_96b_sensors_18_1.xdc
  
  

# Conclusion
So good luck, have fun, and we look forward to seeing your finished project!


