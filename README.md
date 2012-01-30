README for upstart-hopmod
=========================
This document will help you run a hopmod server using Ubuntu's Upstart.
Prerequisites (and assumptions)
-------------------------------
* Ubuntu (with some flavour of upstart)
* A copy of hopmod, from http://hopmod.e-topic.info/new/index.php5?title=Main_Page
* Your copy of hopmod is configured and runs normally
Instructions
------------
1. Copy sauer.conf into /etc/init
2. Modify variables at the top of sauer.conf to match your installation
3. Create a symlink in /etc/init.d:
    ln -s /lib/init/upstart-job
