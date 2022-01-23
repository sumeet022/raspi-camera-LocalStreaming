# raspi-camera-LocalStreaming
With these help of code , You can able to do live streaming on a localnetwork
Please Follow Below Steps to Perform Live streaming with raspi-camera

//Please follow the below commands on your raspi
sudo apt-get update

sudo apt-get upgrade

sudo raspi-config

 Interfacing Options
 Enable the Camera
 Enable IC2

sudo reboot

ifconfig (For the IP address of the RPi the camera is connected to)

sudo vi rpi_video_streaming.py (Create this file where ever you want to)

Copy the code below to the file

python3 rpi_video_streaming.py (Run this in terminal)

After running the above code the other RPi can open http://&lt;IPAddressOfRPiwithCamera&gt;:8000 on the
browser and the live stream can be viewed.
