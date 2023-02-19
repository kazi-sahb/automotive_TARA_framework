# automotive_TARA_framework

Developed by: 

Qazi Mairaj ud din

Centre for Automotive Research

mairajuddin.1@osu.edu

# About the Framework

The framework is designed to automate the TARA process for the users as much as possible. The framework complies with all the guidelines of ISO-21434 and UN Reg 155.

Identify assets, their cybersecurity properties and their damage scenarios

Identify Threat Scenario 

Determine the impact rating of damage scenarios

Identify the attack paths that realize threat scenarios

Determine the ease with which attack paths can be exploited

Determine the risk values of threat scenarios

Select appropriate risk treatment options for threat scenarios

Auto_TARA_Framework_ver1.tb7 is developed in the STRIDE based Microsoft Threat Modeling Tool (MSTM) to perform Threat Modeling and Risk Assessment for Vehicular Networks. A case study of Diagnostic Session "Diagnostic Session.tm7" has been evaluated for this type of network. This may be loaded in MSTM and be used as a reference to perform TARA for other vehicular systems.

Version 1 for Automotive TARA framework along with a use case of Diagnostic session.

Basic help on using MSTM may be referred from: https://learn.microsoft.com/en-us/azure/security/develop/threat-modeling-tool-getting-started

# How to use the Framework for TARA:

![image](https://user-images.githubusercontent.com/70536971/219961480-b439150e-2e8e-4d03-9483-c8ecdaa0d456.png)


The threat modeling is  

![image](https://user-images.githubusercontent.com/70536971/219912512-d34e60ed-83d6-4519-8328-79e21ec87566.png)

Simplified diagram of a conventional powertrain Heavy-Duty Vehicular Network.

To perform Threat Assessment and Risk Analysis (TARA) of a case study, the following steps need to performed in sequence:

1. Start off with designing architecural model of the system using Data Flow Diagrams (DFDs). A general layout (schematic) of the system may be used for this purpose.  A team of Cybersecurity experts and system developers may perform this task jointly. For demonstartion purposes here, the system of evaluation (SOE) is a diagnostic network connected to the ECM on CAN BUS 1 network. A simplified diagram of the SOE is given below: 
![image](https://user-images.githubusercontent.com/70536971/219919390-a75b4ab2-7cab-496b-8582-0cd4ecfd83b3.png)
The SOE is translated into Data Flow Diagram based on the function assignment. The stencils are provided for the modeling purpose as shown in the figure below.

![image](https://user-images.githubusercontent.com/70536971/219959564-37359a49-3615-4405-99d4-2aa2ca4778f0.png)![image](https://user-images.githubusercontent.com/70536971/219959577-6b12ad44-5160-49e5-84f3-9b421da397fe.png)![image](https://user-images.githubusercontent.com/70536971/219959937-37eb4a76-7824-4cac-b257-6b1e06ef52b9.png)

Once the data flow diagram (DFD) is completed based on the network design, the layout would look similar to the figure given below.

![image](https://user-images.githubusercontent.com/70536971/219920055-32d19f86-03dc-471f-a6e5-f70de845e3e8.png)

DFD for Diagnostic Session

2. After completing the design, the user needs to go to analysis view as shown here.

![image](https://user-images.githubusercontent.com/70536971/219960754-b29cffe4-d9a9-4aa0-9b22-eaf727138c53.png)

Pressing the analysis view will generate a list of possible threats associated with the network. The number of threats generated for case study are 102 in total as shown in the figure below.

![image](https://user-images.githubusercontent.com/70536971/219960857-0b7d8b7a-d224-411c-b2d7-e6ed4766c613.png)

The threats may be segregated or filtered by the cybersecurity experts from this list based on their criticality. The properties of more critical threats may be edited based on their nautre. This completes the threat modeling and damage scenerio evaluation.

3. For risk calculations, a step by step guidance has been provided in each column as shown below. The impact rating, attack feasiblity and the total risk factor may be calculated using the information provided in each column and entered in the report. 

![image](https://user-images.githubusercontent.com/70536971/219961247-4e1713a2-ca51-4f09-8777-0e98c67a0024.png)

The information from attack propogation tab may directly be used to geenrate attack trees.

![image](https://user-images.githubusercontent.com/70536971/219961283-9aa430d7-024d-4d6f-a06c-4f79b30fa38c.png)


4. The framework will provide list of approporiate mitigations for each threat automatically as shown below.

![image](https://user-images.githubusercontent.com/70536971/219961328-fa7ed5e2-3d05-4d3b-96cf-d80b39b18e72.png)







