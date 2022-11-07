Mobila mapping data
===================


￼
Mobile Mapping is the process of collecting geospatial data from mobile vehicles such as cars, drones, boats, trains or aeroplanes.
In SmartGIS, we can use two types of data derived from Mobile Mapping: Point clouds and panoramic images.

A point cloud is a set of points in space that represent the surface of an object.
Two common methods are used to generate point clouds: LiDAR and photogrammetry.
**LiDAR** s a technology that uses lasers in order to measure distances from the sensor on the LiDAR device to objects in the environment.
**Photgrammetry** uses photographs taken from various angles of an object in order to calculate its dimensions and generate a 3D model by using triangulation. 
These point clouds can be used in SmartGIS for :ref:`3D digitization <3d_digitizing>` of map objects.

A panoramic photography is essentially a photo with a wide format, whether that's vertical or horizontal. Either way, they are taken by taking a series of photos which overlap to create one single image.
Mobile mapping data is always uploaded via FTP.

Trajectories
------------

The common file format for point clouds is LAS (or comressed LAZ). LAS files collected in a bundle are called **trajectories**. Such trajectories can be imported into the application packed in **.zip**, **.rar** or **.7z** format. 
In the process, the files are unpacked and prepared for web display, which requires the **Potree** format.

The application also accepts point clouds in Potree format, in which case it is only necessary to unpack the archive.

Panoramic images
----------------
In SmartGIS, each panorama image series must belong to a trajectory. The images of the trajectory should also be packed in a .zip .rar or .7z archive. Such a package should also include a .txt file containing a list of the images. This will include the position of each image and other information. 

.. Note:: This is a tab delimited CSV file with column names in the header which should be:
    GPS Time\tImage Filename\tEast\tNorth\tHeight\tOmega\tPhi\tKappa\



Create a trajectory
--------------------

Organize trajectories into folders
----------------------------------

