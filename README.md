Configure the ip address;

sudo ifconfig enp0s25 192.168.100.101 netmask 255.255.255.0

Launch the ros node:

roslaunch your_camera_package rtsp_stream.launch