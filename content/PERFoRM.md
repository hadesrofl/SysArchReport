### PERFoRM Architecture

+++
#### What is PERFoRM (1)
<blockquote><font size="5">The EU HORIZON 2020 project PERFoRM (Production harmonizEd Reconfiguration of Flexible Robots and Machinery) is aiming at the <strong>conceptual transformation</strong> of <em>existing</em> production systems towards <strong>agile</strong>, <strong>networked plug-and-produce production systems</strong> in order to achieve a <em>flexible manufacturing environment</em> based on <strong>fast reconfiguration</strong> of machinery and robots as response to operational or business events.</font></blockquote>

+++
#### What is PERFoRM? (2)
* Architecture (currently researched and specified) to support the production digitalization by providing:
 * service-orientation to expose system functionalities as services
 * a middleware as a common platform for information exchange
 * a common language for standard interfaces
 * technology adapters to integrate legacy systems
 * a proper Human-Machine-Interface (HMI) to allow the human to interact with the system and drive its flexibility  

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
