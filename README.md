# LABVIEW_OceanOptics_Spectrometer
[LABVIEW] Control of an Ocean Optics USB4000 spectrometer AND measure of the fluorescence transmission of filters

## Aim
This software is designed to control an Ocean Optics USB4000 spectrometer.
As you can see on the following video, the Labview GUI is simple and allows to read the infomation coming from the spectrometer, control it AND measure the transmission of fluorescence filter:

[![Watch the video](https://github.com/MAILFERT-Sebastien/LABVIEW_OceanOptics_Spectrometer/blob/main/Images/Labview_OceanOptics_USB4000.png)]([https://youtu.be/x3z7vbhCzYc](https://www.youtube.com/watch?v=lz8w-zJ4CPQ))


## Prerequisites
This program has been tested under Labview 2023 64-bit. It is therefore necessary to have at least one version of Labview 2023 installed.
> [!TIP]
> If you contact me, I can provide you with a version that is compatible with yours (older or newest).

## Installing

1. Ocean Optics drivers
   <ul>
      <li> Open <i>Labview</i></li>
      <li> In the <i>Help</i> tab, select <i>Find instrument drivers</i></li>
![image](https://github.com/MAILFERT-Sebastien/LABVIEW_OceanOptics_Spectrometer/blob/main/Images/Labview_OceanOptics_Drivers_0.png)
      <li> Select <i>Ocean Optics</i> in the list of manufacturers</li>
      <li> Click on <i>Search</i> </li>
![image](https://github.com/MAILFERT-Sebastien/LABVIEW_OceanOptics_Spectrometer/blob/main/Images/Labview_OceanOptics_Drivers_1.png)
      <li> Select the <i>ocean2000 Instrument Driver</i> item</li>
![image](https://github.com/MAILFERT-Sebastien/LABVIEW_OceanOptics_Spectrometer/blob/main/Images/Labview_OceanOptics_Drivers_2.png)
      <li> Click on <i>Install</i></li>
      <li> Log in or create a <i>NI profile</i></li>
![image](https://github.com/MAILFERT-Sebastien/LABVIEW_OceanOptics_Spectrometer/blob/main/Images/Labview_OceanOptics_Drivers_3.png)
      <li> Once installed, close this window</li>
![image](https://github.com/MAILFERT-Sebastien/LABVIEW_OceanOptics_Spectrometer/blob/main/Images/Labview_OceanOptics_Drivers_4.png)
      </ul>
      
2. Labview code
      Copy the 5 Labview files on your desktop. Several Labview files are provided:
      <ul>
      <li> <i>Nikon_Ti2_Control.lvproj</i> : the project file itself</li>
      <li> <i>231107_Nikon_Control.vi</i> : the main file</li>
      <li> <i>231107_Nikon_CheckStatus.vi</i> : the file used to retrieve microscope status in the form of a complete cluster</li>
      <li> <i>231107_Cluster_MAJ.vi</i> : the file used to convert the microscope's complete status cluster into a cluster usable for the interface</li>
      <li> <i>231106_Nikon_Led.vi</i> : file for generating green LEDs according to microscope status (eyepieces, left port, right port, mix)</li>
      </ul>

## Running the tests


## Versioning

V1.0, 231215

## Authors
Sébastien MAILFERT
Institut Fresnel (Marseille, France), CNRS, AMU

## Licence
GNU General Public License v3.0
GNU GPLv3.0

## Acknowledgments
Sébastien MAILFERT
