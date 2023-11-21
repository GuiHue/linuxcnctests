# EtherCAT 4 LinuxCNC


## General Notes

dmesg -wH to monitor the output during startup (debugging)

ethercat slaves / ethercat master to see info

To see ethernet devices:
nmcli device status 


## Useful Gists:
https://gist.github.com/Bouni/8b4532d0bdf012bd83c65d3eb62f8aa2

## During Install of etherlab master
configure: error: Failed to find Linux sources. Use --with-linux-dir!

then
synaptic -> linux-headers
install for current kernel RT



## BK1120
TwinCat Dump shows registers and syncm... examle requires
