# mavros-4G-setup
How to connect to a mavros enabled BlueBoat using a 4G Sim over wireless VPN
`roslaunch mavros apm.launch fcu_url:=udp://IP_address` (Pixhawk connected to Rpi @IP_Address_of RPi connected over VPN.)
`roslaunch mavros apm.launch fcu_url:=udp://0.0.0.0:14550@10.2X2.XXX.94`
`rosrun mavros mavparam get SYSID_MYGS 1(For Computer Control) or 255(for QGC)
