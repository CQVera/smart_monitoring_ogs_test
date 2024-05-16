# Smart Monitoring - OGS Test Cases

This repository contains test cases for OpenGeoSys pertaining to the Smart Monitoring project. It includes:
1. 0_
2. <test_case1>
3. <test_case2>
4. <test_case4>

## Installation
### Download Tests
Clone this repository using
```
git clone https://github.com/CQVera/smart_monitoring_ogs_test.git
```

### Download OGS Container 
The OpenGeoSys container based on Apptainer (Singularity) technology is available from the Official Website of OGS.
It can be downloaded using [this link](https://ogsstorage.blob.core.windows.net/binaries/ogs6/6.5.1/ogs-6.5.1-openmpi-4.0.5.sif). 
The downloaded file `ogs-6.5.1-openmpi-4.0.5.sif` needs to be copied into the folder of this repository (i.e. `smart_monitoring_ogs_test`).
Using the OpenGeoSys container requires Apptainer, which can be installed using instructions from [here](https://apptainer.org/docs/admin/main/installation.html#installation-on-linux).

## Usage
In order to run a test case:
- change to the specific test case directory using `cd <test_case>`. 
- run the OGS project through the container using `apptainer exec ../ogs-6.5.1-openmpi-4.0.5.sif ogs <test_case>.prj`, where `<test_case>` needs to be replaced with the name of the project.
