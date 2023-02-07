Hi, my name is Juan Carlos Miranda, I am currently a PhD student at the University of Lleida in the Research Group on Precision Agriculture (GRAP) - Department of Agricultural and Forestry Engineering. My work focuses on the application of photonic sensors, computer vision and spatial sampling methods to estimate fruit load in apple trees.

* Researchgate -> https://www.researchgate.net/profile/Juan-Miranda-6
* ORCID -> https://orcid.org/0000-0001-5912-9704

# Guides / How To's

Some notes.

| Package                   | Description            |
|---------------------------|-------------------------|
| Azure Kinect camera setup (automated scripts for Linux and Windows) ([https://github.com/juancarlosmiranda/azure_kinect_notes](https://github.com/GRAP-UdL-AT/ak_acquisition_system)) | This document contains instructions/notes on how to install the Azure Kinect camera. Here we collect experiences that
have arisen with the development of [AK_SM_RECORDER](https://pypi.org/project/ak-sm-recorder/)
and [AK_FRAME_EXTRACTOR](https://pypi.org/project/ak-frame-extractor/). |


# Software packages

Currently maintaining software packages at (Pypi.org)[https://pypi.org].

| Package                   | Description            |
|---------------------------|-------------------------|
| AK_ACQS Azure Kinect Acquisition System ([https://github.com/GRAP-UdL-AT/ak_acquisition_system](https://github.com/GRAP-UdL-AT/ak_acquisition_system)) | AK_ACQS is a software solution for data acquisition in fruit orchards using a sensor system boarded on a terrestrial vehicle. It allows the coordination of computers and sensors through the sending of remote commands via a GUI. At the same time, it adds an abstraction layer on library stack of each sensor, facilitating its integration. This software solution is supported by a local area network (LAN), which connects computers and sensors from different manufacturers ( cameras of different technologies, GNSS receiver) for in-field fruit yield testing. |
| AK_SM_RECORDER - Azure Kinect Standalone Mode ([https://github.com/GRAP-UdL-AT/ak_sm_recorder](https://github.com/GRAP-UdL-AT/ak_sm_recorder)) | A simple GUI recorder based on Python to manage Azure Kinect camera devices in a standalone mode. https://pypi.org/project/ak-sm-recorder/ |
| AK_FRAEX - Azure Kinect Frame Extractor ([https://github.com/GRAP-UdL-AT/ak_frame_extractor](https://github.com/GRAP-UdL-AT/ak_frame_extractor)) | AK_FRAEX is a desktop tool created for post-processing tasks after field acquisition. It enables the extraction of information from videos recorded in MKV format with the Azure Kinect camera. Through a GUI, the user can configure initial parameters to extract frames and automatically create the necessary metadata for a set of images. ([https://pypi.org/project/ak-frame-extractor/](https://pypi.org/project/ak-frame-extractor/))|
