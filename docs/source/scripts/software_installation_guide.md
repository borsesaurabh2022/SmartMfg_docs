# Software Installation Guide

Here you fuínd the list of softwares to be installaed as prerequisite to complete this tutorial

* Ubuntu 24.04
* ROS2
* webots
* webots ROS2 Interface
* webots simulation with robot environment (Preconfigured)
* Moveit2 (debian / source installation)

We use the webots simulation in the practical part to learn ROS. This simulation is developed by the  MASKOR institute.

## Ubunt 24.04 LTS 

1. Download Ubuntu 24.04 LTS (Jammy Jellyfish) from https://releases.ubuntu.com/noble/

2. If you want to install Ubuntu on a computer you need to create a bootable USB stick out of the downloaded image. A guide on how to do that for several operating systems can be found e.g. [here](https://ubuntu.com/tutorials/create-a-usb-stick-on-windows#1-overview). After creating the bootable USB stick you have to boot your system from it in order to install the operating system to your harddisk.

## ROS2 Jazzy Jalisco 

Install ROS2 Jazzy Jalisco by following this [installation guide](https://docs.ros.org/en/jazzy/Installation/Ubuntu-Install-Debs.html). Additionally install python common extension using following command. 

* **Install python colcon extension**:  
   ```bash
   sudo apt install python3-colcon-common-extensions

After successfull installation, configure the environment by following configuration guide [here](https://docs.ros.org/en/jazzy/Tutorials/Beginner-CLI-Tools/Configuring-ROS2-Environment.html)

## Webots and ROS 2 Interface

Install Webots locally on your machine by following this [installation guide](https://cyberbotics.com/doc/guide/installation-procedure). In this tutorial, we use the 2023b version, so ensure you install the correct version.

  ```{admonition} Hint
  If you have problems running the simulation smoothly you can try to reduce the graphic settings. In webots: `Tools->Preferences->OpenGL`. Disable everything.
  ```

The Webots ROS 2 interface is essential for ROS 2 control and can be installed either as Debian packages or built from source. We recommend debian installation. 

* **Binary installation**:  
   ```bash
   sudo apt install ros-jazzy-webots-ros2


* **Installation from source**:

  Here you find a complete installation procedure.

  https://docs.ros.org/en/iron/Tutorials/Advanced/Simulators/Webots/Installation-Ubuntu.html

## Moveit 2

MoveIt 2 is a flexible and scalable framework for motion planning, manipulation, and control of robotic arms in ROS 2. It can be installed as binary packages for ease of use or built from source for custom configurations and development. 

 ```{admonition} SUggestion
  To have servoing capabilities we recommend to install moveit form source. 
  ```

* **Binary Installation**:
  ```bash
    sudo apt install ros-jazzy-moveit

* **Installation from source**:

  Here you find a complete installation procedure. Make sure while installing from source you select a correct `<branch>`, in this case use `main`.

  https://moveit.picknik.ai/main/doc/tutorials/getting_started/getting_started.html#create-a-colcon-workspace-and-download-tutorials
  

Once all the necessary software is installed correctly, you can proceed to the next section.