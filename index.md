# IT4IT

The Open Group IT4IT is a standard reference architecture for managing the business of IT. It uses a value chain approach to create a model of the functions that IT performs to help organizations identify the activities that contribute to business competitiveness.


## Principles

### Flexible to support frequent changes

### Defined in practical terms for real world applications

### Phased approach not rip and replace technology and vendor agnostic

### Accessible to anyone

### Complementary to current industry standard best practices

## IT Value Chain

The standard is focused on defining, sourcing, consuming, and managing IT services by looking holistically at the entire IT Value Chain.

It is an information model based on the concept of an IT Value Chain that models the functions that IT performs.


### Activities

- Primary (Value streams)

  Each IT Value Stream is centered on a key aspect of the service model, the essential data objects (information model), and functional components (functional model) that support it. Together, the four value streams play a vital role in helping IT control the service model as it advances through its lifecycle.
  
  Primary-production of goods or delivery of service.
  

	- S2P - Strategy to Portfolio

	  The Strategy to Portfolio (S2P) Value Stream receives strategic demands for new or improved services from the business or IT itself and develops the Conceptual Service to represent the new or enhanced service that is requested. The Conceptual Service is the bridge between business and IT in that it provides the business context for the service along with the high-level architectural attributes. 
	  
	  

		- Key Value Propositions

			- Holistic IT portfolio based on business priorities
			- Well-defined system of records
			- Full service lifecycle tracking

		- Activities

			- Strategy

			  Define objectives 
			  Align business and IT roadmaps 
			  Set up standards and policies
			  

			- Service Portfolio

			  Enterprise Architecture
			  Service portfolio rationalization
			  Create service blueprint and roadmap 
			  

			- Demand

			  Consolidate demand 
			  Analyze priority, urgency, and impact
			  Create new or tag existing demand
			  

			- Selection

			  Business value, risk,costs, benefits and resources 
			  What-if analysis
			  Ensure governance
			  

		- Functional Components

			- Enterprise Architecture

			  The Enterprise Architecture functional component creates and manages long-term IT investment and execution plan-of-action that are critical to business strategic objectives.
			  
			  

				- Key Data Objects

					- Enterprise Architecture

					  The Enterprise Architecture data object includes references to collateral in the target state architecture landscape representing planned and deployed IT services.
					  
					  

				- Key Data Object Relationships

					- Enterprise Architecture to Conceptual Service (n:m)

					  Helps track which service components and service diagrams are allocated to which service(s).
					  
					  

			- Policy

			  The Policy functional component manages creation, review, approval, and audit of all IT policies.
			  
			  

				- Key Data Objects

					- Policy

					  The Policy data object is a central repository for storing and organizing all types of IT policies based on various templates and classification criteria.
					  

				- Key Data Object Relationships

					- Policy to Conceptual Service (n:m

					  Multiple policies might be applicable for a single service or a single policy may be applicable for multiple services.
					  

					- Policy to Requirement (n:m)

					  Requirements may be sourced from policies or may reference policies in order to remain in compliance with previously agreed policies for an organization.
					  

			- Proposal

			  The Proposal functional component manages the portfolio of IT proposals that are proposed, approved, active, deferred, or rejected. 
			  

				- Key Data Objects

					- Scope Agreement

					  The Scope Agreement data object reflects budget, cost/benefit projections, scope, status, and other key attributes of proposed work.
					  
					  

				- Key Data Object Relationships

					- Scope Agreement to Portfolio Backlog Item (n:m)

					  One Scope Agreement can be associated to one or more demand data objects
					  

					- Scope Agreement to IT Budget Item (n:1)

					  This relationship helps track budget allocated to which Scope Agreement.
					  

					- Scope Agreement to IT Initiative (1:n)

					  This relationship helps track IT Initiative(s) to which Scope Agreement.
					  

			- Portfolio Demand

			  The Portfolio Demand functional component logs, maintains, and evaluates all demands (new service, enhancements, defects) coming into IT through a single funnel.
			  
			  

				- Key Data Objects

					- Portfolio Backlog Item

					  The Portfolio Backlog Item data object represents the repository of all incoming demands including but not limited to new requests, enhancement requests, and defect fix requests.
					  
					  

				- Key Data Object Relationships

					- Portfolio Backlog Item to Conceptual Service (n:1)

					  One Conceptual Service may be related to one or more Portfolio Backlog Items.
					  

					- Portfolio Backlog Item to Requirement (1:n)

					  A Portfolio Backlog Item is mapped to one or more Requirements that will need to be delivered to successfully fulfill the demand.
					  

					- Portfolio Backlog Item to Scope Agreement (n:1)

					  One or more Portfolio Backlog Items may be included in a Scope Agreement.
					  

			- Service Portfolio

			  The purpose of the Service Portfolio functional component is to manage the portfolio of services in plan, transition, production, and retirement. 
			  

				- Key Data Objects

					- Conceptual Service

					  Conceptual Service represents the business perspective of the service and is the service interaction or the business capability of the service.
					  

					- Conceptual Service Blueprint

					  The conceptual service model contains the various delivery options for a given Conceptual Service.
					  

				- Key Data Object Relationships

					- Conceptual Service to Logical Service (1:n)

					  Traceability is maintained between one Conceptual Service and one or more Logical Services.
					  

					- Enterprise Architecture to Conceptual Service (n:m)

					  Traceability is maintained between one or more Conceptual Services and the Enterprise Architecture drawings, diagrams, and other documents that describe those services.
					  

					- Conceptual Service to Portfolio Backlog Item (1:n)

					  One Conceptual Service may be related to one or more Portfolio Backlog Items.
					  

					- Conceptual Service to IT Budget Item (1:n)

					  Budget for one Conceptual Service may be spread across multiple budget items and one budget item should hold budget for a single Conceptual Service.
					  

					- Conceptual Service to Policy (n:m)

					  Multiple Policies might be applicable for a single service or a single Policy may be applicable for multiple services.
					  

					- Conceptual Service to Conceptual Service Blueprint (1:n)

					  One Conceptual Service may have multiple Conceptual Service Blueprints.
					  

					- IT Cost Model to Conceptual Service Blueprint (1:n)

					  One IT cost model (rule engine) can be applicable for multiple Conceptual Service Blueprints.
					  

					- Conceptual Service Blueprint to Logical Service Blueprint (1:n)

					  One Conceptual Service Blueprint could have one or more Logical Service Blueprints.
					  

			- IT Investment Portfolio

				- Key Data Objects

					- IT Budget Item

					  The IT Budget Item data object is an authoritative list of approved IT investment pertaining to a service. This set of records will help to identify approved budget over different time periods; e.g., by financial year, by Conceptual Service.
					  
					  

				- Key Data Object Relationships

					- IT Budget Item to Conceptual Service (n:1)

					  One IT Budget Item shall hold budget for a single Conceptual Service and budget for one Conceptual Service may be spread across multiple IT Budget Items.
					  

					- IT Budget Item to Scope Agreement (1:n)

					  This relationship helps track how much IT budget is allocated to which Scope Agreement(s).
					  

	- R2D - Requirement to Deploy

	  The Requirement to Deploy (R2D) Value Stream receives the Conceptual Service and designs and develops the Logical Service with more detailed requirements that describe how the newly requested service and its components shall be designed. The Logical Service can be thought of as a user-friendly name for the “service system” to be created/enhanced which delivers the value to the business.
	  
	  

		- Key Value Propositions

			- Quality
			- Utility
			- Lake service delivery predictable while preserving innovation
			- Standardize service development and delivery for re-use
			- Collaboration culture between operations and development

		- Activities

			- Plan & Design

			  planning and creating a detailed logical view of the service - IT project plan
			  logical service model
			  requirements
			  functional and technical
			  standard and policies.
			  

			- Develop

			  development including testing - agile, iterative or waterfall
			  source and set up dev environment
			  version control
			  developer testing.
			  

			- Test

			  Functional
			  Performance
			  Security
			  

			- Deploy

			  Documentation
			  Release plan
			  Change and configuration process
			  Knowledge management
			  Application and security monitors.
			  

		- Functional Components

			- Project

	- R2F - Request to Fulfill

	  The Request to Fulfill (R2F) Value Stream receives the Service Release Blueprint and creates Service Catalog Entries which represent how the service is technically delivered. Service owners build out Offers based on what technical capabilities (Service Catalog Entries) are available. The Offers are viewable to the consumer and can be ordered for a set price and service contract as detailed in the Offer.
	  
	  

		- Activities
		- Functional Components

	- D2C - Detect to Correct

	  The Detect to Correct (D2C) Value Stream provides a framework for integrating the monitoring, management, remediation, and other operational aspects associated with realized services and/or those under construction. It also provides a comprehensive overview of the business of IT operations and the services these teams deliver. Output from the D2C Value Stream enters the lifecycle as new demands within the S2P Value Stream.
	  
	  

		- Activities
		- Functional Components

- Supporting

  Supporting-facilitate efficiency and effectiveness of primary
  

	- Governance Risk & Compliance
	- Sourcing & Vendor
	- Intelligence & Reporting
	- Finance & Assets
	- Resource & Project

### Key Pillars

- The Service Model

  The Service Model construct in the architecture captures, connects, and maintains these service lifecycle attributes as the service progresses through its lifecycle. 
  

	- Abstraction Levels

		- Conceptual
		- Logical
		- Realized

	- Types

		- Conceptual Model

		  Describes why we need a service, who the customers are, the cost, and benefits realized if implemented.
		  

		- Logical Service
		- Service Release
		- Service Release BluePrint
		- Service Catalog Entry
		- Desired Service
		- Actual Service

- The Information Model

  The Information Model comprises the set of service lifecycle data objects and their relationships.
  

	- Data Objects

		- Key Data Objects
		- Auxiliary Data Objects
		- Service Model

- The Functional Model

  A capability is the ability that an organization, person, or system possesses (function or activity it can perform) which produces an outcome of value through the utilization of a combination of people, process, methods, technology resources, and/or tools.
  Functional components can be logically associated to IT capabilities for organizational clarity and underpinned with processes to drive uniformity and consistency.
  

	- Primary Functional Component
	- Secondary Functional Component

- The Integration Model

  Integration between components in the traditional IT management ecosystem is based on capability and processes.
  

	- System of record integrations

	  Data-centric integration, SoR in short form.
	  
	  

	- System of engagement integrations

	  Describes the relationships which control authoritative source data via a system-to- system interface; the relationships are prescriptive.
	  
	  Experience-centric integration, SoE in short form
	  

	- System of insight integrations

	  Intelligence, analytics, and KPI-centric integrations, SoI in short form.
	  
	  Describes the relationships between data objects for the purpose of generating knowledge, information, or analytics.
	  

### Levels

- Upper levels

  The upper levels (1-3) are vendor-agnostic and provide more generic views that are suitable for strategy and planning purposes as well as for creating IT management product roadmaps.
  

	- Level 1: End-to-End Overview
	- Level 2: Value Stream Documentation
	- Level 3: Vendor-independent Architecture

- Lower levels

  The lower levels (4-5) provide more specific details, ultimately arriving at implementation level or vendor-owned/controlled information.
  

	- Level 4: Vendor-specific Refinement Architecture
	- Level 5: Solution Architecture

## IT Service

An IT service is a performance of an act that applies computing and information management competencies or resources for the benefit of another party.


### Aspects

- Service interaction

  The interaction between provider and consumer
  

- Service offer

  The offer that exposes the value proposition to consumers.
  

- Service system

  he people, process, and technology that facilitate the outcome.
  

