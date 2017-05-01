### Specification of the PERFoRM Architecture for the Seamless Production System Reconfiguration

+++
#### What is PERFoRM (1)
> The EU HORIZON 2020 project PERFoRM (Production harmonizEd Reconfiguration of Flexible Robots and Machinery) is aiming at the conceptual transformation of existing production systems towards agile, networked plug-and-produce production systems in order to achieve a flexible manufacturing environment based on fast reconfiguration of machinery and robots as response to operational or business events.

+++
#### What is PERFoRM? (2)
* Project of the EU Horizon 2020 research and innovation programme
* Architecture (currently researched and specified) to support the production digitalization by providing:
 * a distributed control system for smart components (CPS)
 * seamless system reconfiguration
 * ways to allow integrated planning and simulation

+++
#### What is PERFoRM? (3)
* ... support the production digitalization by providing:
 * service-orientation to expose system functionalities as services
 * a middleware as a common platform for information exchange
 * a common language for standard interfaces
 * technology adapters to integrate legacy systems
 * a proper Human-Machine-Interface (HMI) to allow the human to interact with the system and drive its flexibility  

+++
#### Assumptions for PERFoRM
* While specifiying the requirements for the PERFoRM architecture there were assumptions made for...

 * enhancing planning, simulation and operation features
 * seamless system reconfiguration
 * system based smart production components

+++
<font size="6">Assumptions for enhancing Planning, Simulation and Operation Features</font>
![Assumptions for enhancing Planning, Simulation and Operation Features](assets/Specification-PERFoRM/Assumptions-Enhance-Planning-Simulation-Operation-Features.png)
<font size="4"><p><strong>Acronyms:</strong> MES (Manufacturing Execution Program), SCADA (Supervisory Control and Data Acquisition), M2M (Machine to Machine), ESB (Enterprise Service Bus), MAS (Multi Agent System)</p></font>
<font size="4"><strong>Source:</strong> <em>Specification of the PERFoRM Architecture
for the Seamless Production System Reconfiguration</em></font>

+++
<font size="6">Assumptions for Seamless System Reconfiguration</font>
![Assumptions for Seamless System Reconfiguration](assets/Specification-PERFoRM/Assumptions-Seamless-System-Reconfiguration.png)
<font size="4"><strong>Source:</strong> <em>Specification of the PERFoRM Architecture
for the Seamless Production System Reconfiguration</em></font>

+++
<font size="6">Assumptions for System Based Smart Production Components</font>
![Assumptions for System Based Smart Production Components](assets/Specification-PERFoRM/Assumptions-System-Based-Smart-Production-Components.png)
<font size="4"><strong>Source:</strong> <em>Specification of the PERFoRM Architecture
for the Seamless Production System Reconfiguration</em></font>

+++
#### PERFoRM Architecture
* Resulting out of the assumptions the architecture needs to provide the following components:

 * Middleware
 * Standard Interface
 * Technology Adapter

+++
#### PERFoRM Architecture - Overview
<img src="assets/Specification-PERFoRM/PERFoRM-Architecture.png" width="70%" height="55%" alt="PERFoRM Architecture"/>
<font size="4"><strong>Source:</strong> <em>Specification of the PERFoRM Architecture
for the Seamless Production System Reconfiguration</em></font>

+++
#### PERFoRM Architecture - Middleware
* Gateway between back-bone and machinery levels
* Service registration and discovery
* data transformation
* routing of message exchange
* prioritization of messages delivery
* and some more

+++
#### PERFoRM Architecture - Standard Interface
* allows to interconnect heterogenous HW devices and SW applications
* enhances seamless interoperability and plugability
* describes a contract implementation of each service (i.e. name, input and output parameters)
* definition of the data model

+++
#### PERFoRM Architecture - Technology Adapter
* exposes legacy systems' data and functionalities according to the PERFoRM standard interfaces
* converts information about the data format of the legacy systems to the PERFoRM data model
* dependant on the technology for the middleware
* heavily involves the HW and SW development
