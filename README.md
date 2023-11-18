## Assignment in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture(SOA).
- SOA uses reusable software services for specific business functions like crefit checks, sign-ins, or mortgage processing across enterprises
2. List and discuss the characteristics of SOA.
- Standardized Services Contracts: SOA abide by standardized contracts describing their purpose, Capabilities, and functionality ensuring clear expression and formal standardized service within the sysytem.
- Loose Coupling: it aim for minimal interdependence fostering specific relationships while reducing reliance between contracts, implementations and consumers.
- Abstraction: Conceal internal logic, reducing unnecessary information proliferation, preserving loose coupling and also enabling flexible service compositions.
- Service Reusability: it split logic to maximize reuse potential.
- Autonomy: it is for self-contained logic, promoting reliability, predictability and also independence from external influences.
- Statelessness: It is a services avoids storing data, enhancing scalability, logic agnosticism and facilitating service reuse within designs.
- Discoverability: It is enable discovery via registries using metadata in contracts to convey purpose, capabilities and also huma-readable information.
- Composability: it decompose complex tasks, leveraging reusable components efficiently optimizing execution allowing data exchange contacts.
- Interoperability: is about prioritize using universal standards for broad usage, sometimes overlooked due in practice.
3. Define Microservices.
- Microservices unlike SOA, it can create agile scalable applicaiotns by employing loosely coupled components, enabling idependent updates and cost in scaling.
4. List and discuss the benefits of using Microservices.
- Independently deployable: it can reduces time furstrations, aligning with agile small-teams structures fostering quick contributions and enhancing both speed and morale.
- Right tool for the job: In each component can use specialized tools, unlike the common stack in traditional architectures allowing flexibility optimization and also easier adaptation to evolving technologies.
- Precise Scaling: it can enable precise scaling by independently deploying and scaling specific services reducing infrastructure needs compared to monolithic applications that scale the entire application uniformly.
5. List and discuss the similarities and differences of SOA and Microservices.
- Communication: it can use individual communication protocols whereas SOA relies on a common enterprise service bus (ESB) posing potential single-point failure risks and system slowdowns if a service lag.
- Interoperability: it prioritize simplicity with lightweight messaging while SOAs accommodate diverse message protocols for interoperability and flexibility.
- Service granularity: it consist of specialized, focused services while SOA includes a spectrum from small to enterprise-wide services.
- Speed: it can prioritize a shared architecture, simplifying development but often running slower, unlike microservices, whice prioritize speed over sharing.
