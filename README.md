
<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# Continuous Integration Cortex Module
The current Cortex Continuous Integration module focus on the promotion of a Cortex .studiopkg package into a single environment and the automated test execution of all the tests associated with the package flows. 

The module allows users to perform the following initial functionality:
* Import and publish flow packages via Cortex LivePortal
* Import test cases on the package
* Visualise previously executed test cases and test plans

Once a flow or a subtask has been imported:
* Further test cases may be defined, saved and executed
* Test cases may be grouped into test plans that may be saved and executed


## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other)
2) [Installation](#installation)
3) [How to use](#how-to-use)
4) [How you can contribute](#how-you-can-contribute)
5) [Versioning](#versioning)
6) [Licensing](#licensing)


## Dependencies
### Cortex Version
This version of the Continuous Integration module was developed in Cortex version 6.4. Some functionality may not be available on different versions of Cortex.

### OCIs
The  module requires the following Cortex OCIs:
* PowerShell
* HTTP

### Files
The Continuous Integration module requires the following files:
* [CTX-Logging.studiopkg](https://github.com/CortexIntelligentAutomation/CTX-Logging/releases/download/v1.0/CTX-Logging.studiopkg)
* [CTX-Logging Database create script](https://github.com/CortexIntelligentAutomation/CTX-Logging/releases/download/v1.0/Cortex-Logging-Install.sql)
* [CTX-Continuous-Integration.studiopkg](https://github.com/CortexIntelligentAutomation/CTX-Continuous-Integration/releases/download/v1.0/CTX-Continuous-Integration.studiopkg)
* [CTX-ContinuousIntegration Database update script](https://github.com/CortexIntelligentAutomation/CTX-Continuous-Integration/releases/download/v1.0/Cortex-ContinuousIntegration-Install.sql)

### Other
The Continuous Integration module has the following additional requirements:
* CTX-Logging module

## Installation
Details of the installation can be found in the [Continuous Integration Deployment Plan](https://github.com/CortexIntelligentAutomation/CTX-Continuous-Integration/blob/master/CTX-Continuous-Integration%20-%20Deployment%20Plan.pdf).
## How to use
A detailed User Guide has been provided with instructions on how to use the flows/subtasks, available [here](https://github.com/CortexIntelligentAutomation/CTX-Continuous-Integration/blob/master/CTX-Continuous-Integration%20-%20User%20Guide.pdf). Configuration of subtask inputs and outputs are detailed in notes on the subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
Continuous Integration has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.1 | 16/05/2019 | AutomatedTest-Subtask-Test-Flow-Template | Created
v1.1 | 16/05/2019 | CCI-Package-Deployment-UI | Updated
v1.1 | 16/05/2019 | CCI-Package-Deployment | Updated
v1.1 | 16/05/2019 | CCI-Test-Management-UI | Updated
v1.1 | 16/05/2019 | CCI-Test-Cases-Execution | Updated
v1.1 | 16/05/2019 | AutomatedTest-IVID-Insert-Variables-Into-Database | Updated
v1.1 | 16/05/2019 | AutomatedTest-RTOF-Run-Test-On-Flow | Updated
v1.0 | 21/02/2019 | CCI-Package-Deployment-UI | Created 
v1.0 | 21/02/2019 | CCI-Package-Deployment | Created 
v1.0 | 21/02/2019 | CCI-Deployment-Process-UI | Created 
v1.0 | 21/02/2019 | CCI-Test-Management-UI | Created 
v1.0 | 21/02/2019 | CCI-Test-Cases-Execution | Created 
v1.0 | 21/02/2019 | Gateway-EF-Export-Flows | Created 
v1.0 | 21/02/2019 | Gateway-GAT-Get-Authentication-Token | Created 
v1.0 | 21/02/2019 | Gateway-GIFS-Get-Ids-From-StudioPackage | Created 
v1.0 | 21/02/2019 | Gateway-ISP-Import-Studio-Package | Created 
v1.0 | 21/02/2019 | Gateway-PSP-Publish-Studio-Package | Created 
v1.0 | 21/02/2019 | AutomatedTest-GRTC-Get-Relevant-Test-Cases | Created 
v1.0 | 21/02/2019 | AutomatedTest-ITC-Import-Test-Case | Created 
v1.0 | 21/02/2019 | AutomatedTest-IVID-Insert-Variables-Into-Database | Created 
v1.0 | 21/02/2019 | AutomatedTest-RTOF-Run-Test-On-Flow | Created 
v1.0 | 21/02/2019 | AutomatedTest-VTCF-Validate-Test-Cases-Files | Created 
v1.0 | 21/02/2019 | CCI-PPR-Process-PowerShell-Response | Created 

## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2018 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


