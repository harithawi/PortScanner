# PortScanner

This is a python based port scanner this is only supported in Linux distributions. This script supports TCP half scan and decoy scan
and normally uses the TCP half scan if you want to use decoy scan use -d but decoy scan is mostly suitable for outside scans.

       How to install requirements
               * pip3 install -r requirement.txt


       switches
               -i IPaddress
               -p singleport, port range(p1:p2), specific ports(p1, p2, p3), for common port( -i common), read port from a file (-i filen.txt)
               -t time stamps (1s to 4s)
               -o filename to store output

        * For decaoy scan
                -d number of IPs you want to use as decoy address
                -e interface name
