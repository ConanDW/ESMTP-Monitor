# ESMTP-Monitor
Monitor to check if ESMPT is able/ready to connect.

The script downloads the cmd tool plink. This is command line version of Putty. The script then trys to conenct to the endpoint via telnet from a server. If it then able to see esmtp is ready. If it is not the script then sends an alert to Datto RMM.
