I, with my group, developed the software component for controlling a Robotic Manipulator with four degrees of freedom (d.o.f.). To set up the system, we utilized Imager to initialize the Raspberry Pi, and VNC Viewer to configure the Virtual Desktop environment.

To facilitate communication between the user and the robotic manipulator, we implemented JavaScript. This allowed us to capture the duty cycle values inputted by the user and send them to Flask, a web framework for Python. Flask then processed the received duty cycle values to control the movements of the robotic manipulator effectively.
