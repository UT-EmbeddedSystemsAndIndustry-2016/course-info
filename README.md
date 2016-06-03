# EE319K Introduction to Embedded Systems

## Course Overview
EE319K will continue the bottom-up educational approach, started in BME303 and EE306. The overall educational objective is to allow students to discover how the computer interacts with its environment. It will provide hands-on experiences of how an embedded system could be used to solve EE problems. The focus will be understanding and analysis rather than design. The analog to digital converter (ADC) and digital to analog converter (DAC) are the chosen mechanism to bridge the CE and EE worlds. EE concepts include Ohms Law, LED voltage/current, resistance measurement, and stepper motor control. CE concepts include I/O device drivers, debugging, stacks, FIFO queues, local variables and interrupts.  You may use, edit, run or distribute these files as long as the copyright notices within the files remain. No specific warranty exists concerning the accuracy or reliability of these examples. I think they work, but history has shown, sometimes I can be wrong. 

## Syllabus
The syllabus for the course can be found [here] (/Syllabus-EE319K.pdf).

## Labs
#### Setup
To configure your workspace for the labs:

1. Install [Keil] (http://users.ece.utexas.edu/~valvano/Volume1/KeilInstall.htm).
2. Install drivers for [Windows XP] (http://users.ece.utexas.edu/~valvano/edX/InstallDriversXP.htm), [Windows Vista] (http://users.ece.utexas.edu/~valvano/edX/InstallDriversVista.htm), [Windows 7] (http://users.ece.utexas.edu/~valvano/edX/InstallDrivers7.htm), and [Windows 8] (http://users.ece.utexas.edu/~valvano/edX/InstallDrivers8.htm).
3. Install [EE319kWare] (http://edx-org-utaustinx.s3.amazonaws.com/UT601x/EE319K_InstallSpring2016.exe).

#### Starter files
The starter files for each lab are hosted in a separate repository. Links to the lab repositories can be found here:

* [Lab 1] (https://github.com/UT-EmbeddedSystemsAndIndustry-2016/Lab1)

#### Workflow
We will follow a standard Github workflow for working on and submitting labs. This process is widely used in industry and will be useful to you in future collaborative projects.

1. To start, [**fork** the repository][forking].
1. [**Clone**][ref-clone] the repository to your computer.
1. Modify the files and [**commit**][ref-commit] changes to complete your solution.
1. [**Push**][ref-push]/sync the changes up to GitHub.
1. [Create a **pull request**][pull-request] on the original repository to turn in the assignment.

## Resources
* [Datasheets] (http://users.ece.utexas.edu/%7Evalvano/Volume1/datasheets.htm)
* [Creating a new project in Keil] (http://users.ece.utexas.edu/~valvano/EE345L/Labs/Fall2011/CreatingProject.pdf)
* [How to reflash your chip] (http://users.ece.utexas.edu/~valvano/EE345L/Labs/Fall2011/Ifyoumessuptheboard.pdf)
* [How to port one uVision project into another] (http://users.ece.utexas.edu/~valvano/Volume1/Porting_Project.pdf)

<!-- Links -->
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md
