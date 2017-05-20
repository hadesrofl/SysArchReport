### Comparison

+++
#### Seamless reconfiguration (1)
* PRIME shows a good solution in terms of reconfiguration time
 * PSA as bottleneck has yet to be tested
 * PSA is single point of failure
 <p>=> Backup plan needed!</p>
 <p>First ideas: Heartbeat algorithm, reboot of dead agents, remapping of children of dead PMAs</p>

+++
#### Seamless reconfiguration (2)
* PERFoRM recognizes the need for seamless reconfiguration and...
 * suggests MAS or SoA for this issue
 * assumes that components will be enriched with Artifical Intelligence methods

+++
#### Seamless reconfiguration (3)
* PERFoRM might adopt PRIMEs approach to fulfill the requirement of seamless reconfiguration
 * where will PRIMEs MAS find its place?
 <p>=> Middleware? As a PERFoRM Tool? A combination of both?</p>

+++
#### Integration of existing systems (1)
* PRIMEs Component Agents handle
 * communication,
 * parametrization and
 * configuration of physical components
* PRIME leaves no hint about legacy system integration

+++
#### Integration of existing systems (2)
* PERFoRM specifies standard interfaces and technology adapters for integrating software and hardware
* Specification demand common data models
* Middleware handles communication
<p>=> single point of failure (as PSA in PRIME)</p>

+++
#### Integration of existing systems (3)
* MAS and PRIMEs approach will benefit from PERFoRMs communication infrastructure
* PRIME fulfills the requirement of seamless reconfiguration mentioned by PERFoRMs specification
* Skills of PRIME can be described as services in PERFoRM for a SoA approach

+++
#### Conclusion
* PRIME and PERFoRM tackle other challenges of the digitization
* Integrating PRIMEs reconfiguration aspect in PERFoRM might lead to an important and strong backbone
* Reevaluation necessary once PERFoRMs full specification is clear and an implementation is presented
