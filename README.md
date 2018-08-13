# Kinect V2

This repository contains a NiTE folder with the libfreenect drivers to setup Kinect V2 in Ubuntu 16.04

## Installation process

- Follow the installation steps of [libfreenect2](https://github.com/OpenKinect/libfreenect2)

- You can download directly NiTE2 with the updated drivers from [here](https://mega.nz/#!iN5S3KLB!NOsxFN5iBuir7GW7UJInhQqmr_qHf-y_5FySn5Imyms)

- To use NiTE2, you have to update the drivers, the procedure follow this instructions:

  * Access to the folder called **freenect2**, follow the next path considering that you install in home libfreenect2:

        ~/freenect2/lib/OpenNI2/Drivers/
   
   * Inside of this folder will be the next two files:
   
    **libfreenect2-openni2.so**
   
    **libfreenect2-openni2.so.0**
   
   * Copy this files inside of the NiTE2 folder, in my case is the next route:
    
         ~/UserName/NiTE-Linux-x64-2.2/Samples/Bin/OpenNI2/Drivers
   
   * To prove if is working go to:
          
         ~/UserName/NiTE-Linux-x64-2.2/Samples/Bin/
   
   * And run:
   
         ./UserViewer

## Images

<img src="https://github.com/totovr/KinectV2/blob/master/Assets/tracking.JPG" width="600">
