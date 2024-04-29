# STEP 02 - SSH Connection With PUTTY

- When I connect it to our computer with an Ethernet cable, I check the connection in the view networks status and tasks section in the control panel. Also, green and orange lights are on on the Ethernet socket.
<p align="center">
<img src="/images/18.png/" style="width:50%">
</p>

- It appears here as an unidentified network.
<p align="center">
<img src="/images/19.png/" style="width:50%">
</p>

[Putty - Official Download Page](https://www.putty.org/)
- I download the putty program and install it by pressing the "Next" button in all options. When I run the program by typing putty in the search field on the start bar, it appears as follows.
<p align="center">
<img src="/images/20.png/" style="width:50%">
</p>

- I write raspberrypi.local in the host name section and press the "Open" button.
<p align="center">
<img src="/images/21.png/" style="width:50%">
</p>

- I select the "Accept" option in the window that appears.
<p align="center">
<img src="/images/22.png/" style="width:50%">
</p>

- I enter the username I determined when preparing the operating system and press enter.
<p align="center">
<img src="/images/23.png/" style="width:50%">
</p>

- We enter our password and press enter. At this stage, it will appear as if we are not writing anything for security reasons. You can delete the wrong character with the Backspace key or press enter and try to enter the password again.
<p align="center">
<img src="/images/24.png/" style="width:50%">
</p>

- I accessed my system via ssh connection.
<p align="center">
<img src="/images/25.png/" style="width:50%">
</p>

- I access Raspberry settings with sudo raspi-config.
<p align="center">
<img src="/images/26.png/" style="width:50%">
</p>
<p align="center">
<img src="/images/27.png/" style="width:50%">
</p>

- I activate VNC under the Interface menu. You can move with the arrow keys and press the content with enter.
<p align="center">
<img src="/images/28.png/" style="width:50%">
</p>
<p align="center">
<img src="/images/29.png/" style="width:50%">
</p>

- This is what it looks like when I complete all the operations successfully.
<p align="center">
<img src="/images/30.png/" style="width:50%">
</p>

- I complete the process by pressing the Ok and Finish buttons. Necessary services have been opened.
<p align="center">
<img src="/images/31.png/" style="width:50%">
</p>

- I reboot the system with sudo reboot now. I press OK and close putty.
<p align="center">
<img src="/images/32.png/" style="width:50%">
</p>

Next Section : [STEP 03 - VNC Connection](vnc.md)
