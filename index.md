# IT4IT

The Open Group IT4IT is a standard reference architecture for managing the business of IT. It uses a value chain approach to create a model of the functions that IT performs to help organizations identify the activities that contribute to business competitiveness.


## IT Value Chain

The standard is focused on defining, sourcing, consuming, and managing IT services by looking holistically at the entire IT Value Chain.

It is an information model based on the concept of an IT Value Chain that models the functions that IT performs.



## Principles

### Flexible to support frequent changes

### Defined in practical terms for real world applications

### Phased approach not rip and replace technology and vendor agnostic

### Accessible to anyone

### Complementary to current industry standard best practices


## IT Service

An IT service is a performance of an act that applies computing and information management competencies or resources for the benefit of another party.


### Aspects

- Service interaction

  The interaction between provider and consumer
  

- Service offer

  The offer that exposes the value proposition to consumers.
  

- Service system

  The people, process, and technology that facilitate the outcome.


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

			  The Project functional component coordinates the creation and provides ongoing execution oversight of IT Initiatives aimed at the creation of new or enhancements to existing services. The IT Initiatives are based on the specifications outlined in the Scope Agreement.
			  

				- Key Data Objects

					- IT Initiative

					  The IT Initiative data object details the scope of the work to be performed, created from, and associated with the Scope Agreement.
					  

				- Key Data Object Relationships

					- Scope Agreement to IT Initiative (1:n)

					  Maintain a linkage between the proposal, which authorized one or more IT Initiatives.
					  

					- IT Initiative to Service Release (1:n)

					  An IT Initiative will manage the creation of one or more Service Releases required to deliver the IT Initiative.
					  

					- IT Initiative to Request for Change (RFC) (1:n)

					  An Initiative will be related to one or many RFC records in order to manage all changes resulting from a single work effort (initiative).
					  

			- Requirement

			  The Requirement functional component manages requirements through the lifecycle of a service. It collects, refines, scopes, and tracks progress of Requirements even before and after an IT Initiative has concluded. It maintains the traceability of each Requirement to the original source (demand, IT or business standard or policy, and/or requestor) and to appropriate Source and/or Test Cases throughout the service lifecycle.
			  

				- Key Data Objects

					- Requirement

					  The Requirement data object records details of the needs or conditions to meet for a new or altered service.
					  
					  

				- Key Data Object Relationships

					- Logical Service Blueprint to Requirement (1:n)

					  One or more Requirements are used to define the required behavior for the Logical Service.
					  

					- Service Release to Requirement (1:n)

					  The Service Release describes a version of the service which fulfills one or more Requirements.
					  

					- Requirement to Test Case (1:n)

					  A Requirement is traced to one or more Test Cases to ensure stated needs or conditions have been successfully delivered or met.
					  

					- Portfolio Backlog Item to Requirement (1:n)

					  A Portfolio Backlog Item is mapped to one or more Requirements that will need to be delivered to successfully fulfill the demand.
					  

					- Policy to Requirement (n:m)

					  Requirements may be sourced from policies or may reference policies in order to remain in compliance to previously agreed policies for an organization.
					  

					- Requirement to Source (n:m)

					  Source will fulfill one or many Requirements, and for a given Requirement, there could be multiple Sources created/modified.
					  

			- Service Design

			  The Service Design functional component identifies the new or existing services required to meet the needs of the Scope Agreement and IT Initiative, including both service systems and service offers. Based on the Conceptual Service and Portfolio Backlog Items, it produces a Logical Service that describes the service structure and behavior considering both the service system and the service offer.
			  
			  
			  

				- Key Data Objects

					- Logical Service

					  The Logical Service data object represents the bridge between the service interaction and service system. 
					  

					- Logical Service Blueprint

					  The Logical Service Blueprint auxiliary data object represents the design of the logical service which details the components and how those components relate to each other. 
					  

				- Key Data Object Relationships

					- Conceptual Service to Logical Service (1:n)

					  One or more Logical Services represents the logical components which are necessary to provide the expected outcome of the Conceptual Service.
					  

					- Logical Service to Requirement (1:n)

					  One or more Requirements will be used to define the required behavior from the Logical Service.
					  

					- Logical Service to Service Release (1:n)

					  A Logical Service can lead to the creation of one or more Service Releases in order to deliver the required service outcomes.
					  

					- Logical Service to Logical Service Blueprint (1:1)

					  A Logical Service structure and behavior can be detailed by one or more Logical Service Blueprints.
					  

			- Source Control

			  The Source Control functional component manages the development of source code or infrastructure based on the Logical Service, Service Design Package, and IT Initiative priorities. It ensures that the source code meets the design specifications, organizational policies, standards, and non-functional requirements so that the service can be operated successfully and meets customer expectations. 
			  
			  
			  

				- Key Data Objects

					- Source

					  The Source data object is the created or purchased solution to meet the requirements for a particular Service Release. 
					  
					  

				- Key Data Object Relationships

					- Source to Requirement (n:m)

					  Source will fulfill one or many Requirements, and for a given Requirement, there could be multiple Sources created/modified.
					  

					- Source to Build (1:n)

					  Source can be built multiple times to create several Build versions.
					  

			- Build

			  The Build functional component receives the Source data object from the Source Control functional component and manages the creation, implementation, automation, and security and storage of all Builds. It manages Builds and versioning in a Definitive Media Library (DML).
			  

				- Key Data Objects

					- Build

					  The Build data object is created from Source and versioned.
					  
					  

				- Key Data Object Relationships

					- Source to Build (1:n)

					  Source can be built multiple times to create several Build versions.
					  

					- Build to Test Case (n:m)

					  One or many Builds can be related to one or many Test Cases used as
					  

					- part of the Build creation.
					- Build Package to Build (1:n)

					  A Build Package is comprised of one or many Builds.
					  

			- Build Package

			  Creation of a deployable package made up of one or many Builds. Manage the Build Packages and relationships to the Service Release Blueprints.
			  
			  
			  

				- Key Data Objects

					- Build Package

					  The Build Package data object is a compilation of one or many Builds in a deployable package.
					  
					  

				- Key Data Object Relationships

					- Build Package to Build (1:n)

					  The Build Package is comprised of one or more Builds.
					  

					- Build Package to Service Release Blueprint (n:m)

					  Multiple Build Packages, which represent the deployable content of the service components, can be deployed using the instructions in the Service Release Blueprints.
					  

			- Release Composition

			  The Release Composition functional component creates the Release Package, Service Release Blueprints, and overall Service Release for developing and delivering new or changed services to the R2F Value Stream Fulfillment Execution functional component to facilitate a smooth transition to IT operations. 
			  
			  

				- Key Data Objects

					- Service Release

					  The Service Release (data object) represents a planned release of a version of the service system. 
					  
					  

					- Service Release Blueprint

					  The Service Release Blueprint (data object) provides the planned design/configuration of the components of the service system. 
					  
					  

				- Key Data Object Relationships

					- Logical Service Blueprint to Service Release (1:n)

					  A Logical Service Blueprint can lead to the creation of one or more Service Releases in order to deliver the required service.
					  

					- IT Initiative to Service Release (1:n)

					  An IT Initiative will manage the creation of one or more Service Releases defined to deliver the content of the IT Initiative.
					  

					- Service Release to Service Release Blueprint (1:n)

					  A Service Release can be released to different environments based on different Service Release Blueprints.
					  

					- Service Release to Requirement (1:n)

					  The Service Release describes a version of the service which fulfills one or more Requirements.
					  

					- Service Release to Test Case (1:n)

					  A Service Release can be validated by one or many Test Cases.
					  

					- Service Release to Service Release Blueprint (1:n)

					  A Service Release can be released to different environments based on different Service Release Blueprints.
					  

					- Service Release Blueprint to Build Package (n:m)

					  Multiple Build Packages, which represent the deployable content of the service components, can be deployed using the instructions contained in the Service Release Blueprints.
					  

					- Service Release Blueprint to Desired Service (1:n)

					  One Service Release Blueprint can be translated to one or more Desired Service(s).
					  

					- Service Release Blueprint to Fulfillment Request (1:n)

					  One Service Release Blueprint is used for service instantiation by one or many Fulfillment Requests.
					  

					- Service Release Blueprint to Service Contract (n:m)

					  One or more Service Release Blueprints contain the template of one or more Service Contracts.
					  

					- Service Catalog Entry to Service Release Blueprint (1:n)

					  Each Service Catalog Entry is created based on definitions of a Service Release Blueprint.
					  

					- Service Release Blueprint to Defect (n:m)

					  One or more Service Release Blueprints can contain one or more Defects in the form of Problems/Known Errors.
					  

			- Test

			  The Test functional component plans and executes tests that ensure the IT service will support the customer’s requirements at the agreed service levels. It prepares the test environment, plans and designs tests, and executes all functional and non-functional tests including performance and stress testing. 
			  
			  
			  

				- Key Data Objects

					- Test Case

					  The Test Case data object is used to validate that the Service Release is fit-for-purpose.
					  
					  

				- Key Data Object Relationships

					- Requirement to Test Case (1:n)

					  A Requirement is associated to one or more Test Cases that validates this Requirement.
					  

					- Service Release to Test Case (1:n)

					  A Service Release is associated to one or more Test Cases which are executed as part of this Service Release.
					  

					- Test Case to Build (n:m)

					  One or more Test Cases can be associated with one or more Builds that uses this Test Case as part of the Build creation.
					  

					- Test Case to Defect (1:n)

					  One Test Case can be associated to one or more Defects that are reported as a result of this test.
					  

			- Defect

			  The Defect functional component keeps track of all Defects by registering Defects of all types (including security-related Defects). It analyzes Defects and finds resolutions. It also associates Defects with Requirements. 
			  
			  
			  

				- Key Data Objects

					- Defect

					  The Defect data object is an issue with the Service Release Blueprint which should be remediated to fulfill the associated Requirements. 
					  
					  

				- Key Data Object Relationships

					- Test Case to Defect (1:n)

					  One Test Case can be associated to one or more Defects that results from the test.
					  

					- Defect to Service Release Blueprint (n:m)

					  One or more Service Release Blueprints are associated to one or more Defects which are included in the Release Package as Problems/Known Errors.
					  

					- Known Error to Defect (1:1)

					  A Known Error may be the source for submitting a new Defect. 
					  

					- Incident to Defect (1:1)

					  A current practice that replaces the Known Error path when that one does not exist. An Incident may be the source for submitting a new Defect.
					  

			- Release Composition

			  The Release Composition functional component creates the Release Package, Service Release Blueprints, and overall Service Release for developing and delivering new or changed services to the R2F Value Stream Fulfillment Execution functional component to facilitate a smooth transition to IT operations. 
			  
			  

				- Key Data Objects
				- Key Data Object Relationships

	- R2F - Request to Fulfill

	  The Request to Fulfill (R2F) Value Stream receives the Service Release Blueprint and creates Service Catalog Entries which represent how the service is technically delivered. Service owners build out Offers based on what technical capabilities (Service Catalog Entries) are available. The Offers are viewable to the consumer and can be ordered for a set price and service contract as detailed in the Offer.
	  
	  

		- Activities

			- Design & Publish
			- Subscribe
			- Fulfill
			- Measure

		- Functional Components

			- Offer Consumption
			- Offer Management
			- Catalog Composition
			- Request Rationalization
			- Fulfillment Execution

			  The Fulfillment Execution functional component orchestrates the delivery of the various requests amongst (one or more) fulfillment engines in order to deliver the IT service. 
			  
			  

				- Key Data Objects

					- Fulfillment Request

					  The Fulfillment Request data object describes all fulfillment aspects of an IT service. 
					  
					  
					  

					- Desired Service

					  The Desired Service data object is the specification of an instance of a service as required to meet the fulfillment requirements detailed in the consumer order (Request) and supported by a single Service Release Blueprint. 
					  
					  
					  

				- Key Data Object Relationships

					- Fulfillment Request to Request (n:1)

					  Informs on Fulfillment Request status.
					  

					- Fulfillment Request to Service Release Blueprint (n:1)

					  Allows the Service Release Blueprint to supply the Fulfillment Request with information needed to instantiate the service.
					  

					- Fulfillment Request to Desired Service (n:1)

					  Acquires relevant information.
					  

					- Fulfillment Request to RFC (1:1)

					  Enables, if applicable, the RFC created to be linked to the originating Request.
					  

			- Usage

			  The Usage functional component tracks and manages actual usage of subscribed IT services and their associated costs. 
			  
			  
			  

				- Key Data Objects

					- Usage Record

				- Key Data Object Relationships

					- Usage Record to Chargeback Contract (n:1)

					  Every Usage Record for a Subscription is associated with a Chargeback Contract. The Chargeback Contract defines the billing rule and frequency for a service Subscription.
					  

			- Chargeback/Showback

			  The Chargeback/Showback functional component provides chargeback or showback for services based on Subscription, Service Contract, and/or Usage information. 
			  
			  
			  

				- Key Data Objects

					- Chargeback Contract

					  The Chargeback Contract data object details the financial obligations between the service consumer and provider(s). 
					  
					  
					  

					- Chargeback Record

					  The Chargeback Record data object represents the actual charge to the subscriber based on the Usage of subscribed services in a given time period. 
					  
					  
					  

				- Key Data Object Relationships

					- Chargeback Contract to Subscription (n:1)

					  Provides the traceability between the service rendered and the expected charges for those services.
					  

					- Chargeback Contract to Chargeback Record (1:n)

					  Multiple billing records can be generated for a single Chargeback Contract as the Chargeback Record will be generated for each billing period.
					  

		- Supporting Function

			- Knowledge & Collaboration

			  The Knowledge & Collaboration supporting function provides knowledge and conversations that help to address the needs of IT service consumers. 
			  
			  
			  

				- Key Data Objects

					- Knowledge

					  The Knowledge data object is structured and unstructured Knowledge from the Knowledge & Collaboration component. 
					  
					  
					  

					- Conversation

					  The Conversation data object gathers user conversations from the Knowledge & Collaboration component. 
					  
					  

				- Key Data Object Relationships

					- Knowledge to Problem (n:m)

					  Links a Problem to the Knowledge involved. 
					  

					- Knowledge to Conversation (n:m)

					  Links a Conversation to the Knowledge involved.
					  

	- D2C - Detect to Correct

	  The Detect to Correct (D2C) Value Stream provides a framework for integrating the monitoring, management, remediation, and other operational aspects associated with realized services and/or those under construction. It also provides a comprehensive overview of the business of IT operations and the services these teams deliver. Output from the D2C Value Stream enters the lifecycle as new demands within the S2P Value Stream.
	  
	  

		- Activities

			- Detect

			  See events, alarms, and metrics across the entire infrastructure 
			  Understand user issues
			  Trace the relationship between events 
			  

			- Diagnose

			  Enrichment 
			  Root cause
			  Severity and business impact
			  Defined escalation path
			  Auto-fixed common issues 
			  

			- Change

			  &é
			  

			- Resolve

			  Implement change
			  Leverage run books
			  Verify recovery Close records
			  

		- Functional Components

			- Service Monitoring

			  The Service Monitoring function component is in charge of creating, running, and managing monitors, which measure all aspects/layers of a service such as infrastructure (system and network), application, and security. 
			  
			  
			  

				- Key Data Objects

					- Service Monitor

					  The Service Monitor data object performs the operational measurement aspects of a CI or an IT service. 
					  
					  
					  

				- Key Data Object Relationships

					- Service Monitor to Event (1:n)

					  Enables traceability from the Events that are created to the Service Monitor from which they originated.
					  

					- Service Monitor to Actual Service (1:n)

					  Identifies the Actual Service being monitored.
					  

			- Event

			  The Event functional component manages Events through the Event lifecycle for events that occur on any IT service. 
			  
			  
			  

				- Key Data Objects

					- Event

					  The Event data object represents an alert/notification signifying a change of state of a monitored CI. 
					  
					  

				- Key Data Object Relationships

					- Event to Incident (n:m)

					  Enables the connection between the Incidents and Events.
					  

					- Event to RFC (1:n)

					  Associates an Event for the RFC processing.
					  

					- Event to Actual Service (n:m)

					  Identifies Actual Service(s) associated with the Event(s).
					  

					- Service Monitor to Event (1:n)

					  Enables traceability from the Events that are created to the Service Monitor from which they originated.
					  

			- Incident

			  The Incident functional component facilitates normal service operations restoration as quickly as possible and minimizes the impact on business operations, thus optimizing service quality and availability. 
			  
			  

				- Key Data Objects

					- Incident
					- Interaction

				- Key Data Object Relationships

					- Incident to Problem, Known Error (n:m)

					  Establishes connection between the Incidents that are converted to Problems.
					  

					- Incident to RFC (1:n)

					  Connects RFCs to the Incidents from which they originated.
					  

					- Incident to Defect (1:1)

					  Determines there is a need for an emergency fix from development
					  

					- Incident to Actual Service (n:m)

					  Identifies Actual Service(s) to which the Incident is associated and usually the main subject of.
					  

					- Event to Incident (n:m)

					  Enables the connection between the Incidents and Events
					  

			- Problem

			  The Problem functional component is responsible for managing the lifecycle of all Problems. The objectives of the Problem functional component are to solve severe/repeating Incidents, prevent Incidents from happening, and minimize the impact of Incidents that cannot be prevented. 
			  
			  
			  

				- Key Data Objects

					- Problem
					- Known Error

				- Key Data Object Relationships

					- Problem, Known Error to RFC (1:n)

					  Enables the relation of an RFC record that is created when problem resolution requires a change.
					  

					- Problem, Known Error to Portfolio Backlog Item (1:1)

					  Ensures a Portfolio Backlog Item is created for Problems requiring a future fundamental/big fix/enhancement to the IT service.
					  

					- Problem, Known Error to Defect (1:1)

					  Enables the creation of Defects when emergency/specific fixes require development.
					  

					- Incident to Problem, Known Error (n:m)

					  Establishes connection between the Incidents that are converted to Problems.
					  

					- Problem, Known Error to Actual Service (n:m)

					  Identifies Actual Service(s) to which the Problem is associated.
					  

					- Problem, Known Error to Knowledge (n:m)

					  Creates a relationship between the Knowledge data object and the Problem from which it originated.
					  

			- Change Control

			  The Change Control functional component is the system that is responsible for managing the lifecycle of all the RFCs in the IT environment. It makes sure that changes are done in a standardized way so that the business risk is minimized. 
			  
			  
			  

				- Key Data Objects

					- RFC

					  The RFC data object records data required to manage the change lifecycle. An RFC includes details of the proposed change. 
					  
					  
					  

				- Key Data Object Relationships

					- Fulfillment Request to RFC (1:1)

					  Identifies the Fulfillment Request from the Fulfillment Execution functional component (R2F Value Stream) that will create an RFC on service implementation/instantiation.
					  

					- RFC to Actual Service (n:m)

					  Associates the RFC with affected Actual Service(s).
					  

					- Problem, Known Error to RFC (1:n)

					  Enables the relation of an RFC record that is created when problem resolution requires a change.
					  

					- Incident to RFC (1:n)

					  Connects RFCs to the Incidents from which they originated. RFC to Event (n:1): Associates an Event that is available for RFC processing
					  

			- Configuration Management

			  The Configuration Management functional component is focused on tracking the inventories of Actual Services and their associated relationships. It identifies, controls, records, reports, audits, and verifies service items. 
			  
			  
			  

				- Key Data Objects

					- Actual Service

					  The Actual Service data object represents the realized deployment of the service. It includes CIs that represent the implemented service components. 
					  
					  
					  

				- Key Data Object Relationships

					- Desired Service to Actual Service (1:1)

					  Create traceability between the Desired and Actual Service(s).
					  

					- RFC to Actual Service (n:m)

					  Associates the RFC with affected Actual Service(s).
					  

					- Problem, Known Error to Actual Service (n:m)

					  Identifies the Actual Service to which the Problem is associated.
					  

					- Run Book to Actual Service (n:m)

					  Maps Run Book records to the associated Actual Services.
					  

					- Incident to Actual Service (n:m)

					  Identifies the Actual Service to which the Incident is associated and usually the main subject of.
					  

					- Event to Actual Service (n:m)

					  Identifies the Actual Service associated with the Event (s). Actual Service to Service Contract (1:n): Connects the Actual Services and the Service Contract in which they are measured.
					  

					- Service Monitor to Actual Service (1:n)

					  Identifies the Actual Service being monitored.
					  

			- Diagnostics & Remediation

			  Through the use of Run Books, the Diagnostics & Remediation functional component provides diagnostics information and/or remediation steps to shorten the MTTR. Run Books help streamline diagnostics and remediation for service functions by applying knowledge solutions to service anomalies. 
			  
			  
			  

				- Key Data Objects

					- Run Book

					  The Run Book data object is a routine compilation of the procedures and operations which the administrator or operator of the system carries out. 
					  
					  
					  

				- Key Data Object Relationships

					- Actual Service to Run Book (n:m)

					  Enables tracking Run Books and the Actual Service(s).
					  

			- Service Level

			  The Service Level functional component enables the design, creation, and management of Service Contracts (SLAs). 
			  
			  
			  

				- Key Data Objects

					- Service Contract

					  The Service Contract data object describes the service characteristics and supports service measurement tracking, governance, and audit. 
					  
					  
					  

					- Key Performance Indicator

					  The Key Performance Indicator data object defines an objective that is measured, its requested threshold, and the calculation method to be used. 
					  
					  
					  

				- Key Data Object Relationships

					- Service Release Blueprint to Service Contract (n:m)

					  Identifies the Service Release Blueprint where the Service Contract templates are being stored.
					  

					- Actual Service to Service Contract (1:n)

					  Ensures functional component and data object traceability in the value stream.
					  

					- Service Contract to KPI (n:m)

					  Tracks the measurements associated with Service Contracts. Subscription to Service Contract (1:1): Allows to trigger the instantiation of a Service Contract instance once a Subscription is instantiated.
					  

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
