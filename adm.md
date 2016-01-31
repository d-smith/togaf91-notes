#Architecture Development Method

Interative, per phase and over the lifetime of the architecture

##What is the ADM?

Architecture Development Method

* A method for developing and managing the life cycle of an enterprise architecture

Nine phases

* Preliminary (done once)
* Eight in a cycles, requirements managment at the core interacting with all phases
* All phases have inputs, steps, outputs

[Preliminary Phase](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap06.html)

* Preperation and initiation activities

Preliminary Phase - Objectives

* Determine the architecture capability desired by the organization
* Establish an architecture capability

Preliminary Phase - Approach

* Defining the enterprise
	* Which lines of busines
	* Which applications
	* Which customer channels
	* Which outside partners are to be considered part of the enterprise
* Identify key drivers and elements of change
* Defining the requirements for architecture work (run it like any other project)
* Choosing frameworks
	* TOGAF for arch, ITIL for implementation and service mgmt, industry frameworks, etc.
	* Define the relationships between other frameworks in the organization
* Evaluate enterprise maturity and capability
* Define architecture principles - foundation for making decisions

Inputs

* TOGAF
* Other arch frameworks
* Board strategies, board business plans, IT strategy, business principles, business goals, business drivers
* Major frameworks operating within the business (scrum, etc)
* Arch capability
* Parnerships and contract agreements

Steps

1. Scope the enterprise organization impacted - what domain do you operate in? Businesses, applications, etc.
2. Confirm governance and support frameworks.
3. Define and establish architecture team
4. Identify and establish architecture principles
5. Tailor TOGAF and other frameworks
6. Implement architecture tools

Outputs

1. Organization model for enterprise architecture
2. Tailored architecture framework
3. Initial architecture repository
4. Restatement of business to business principles, goals, etc.
5. "Request for Architecture Work" (optional - for running it like a project)
6. Architecture governance framework - doc stores, log files, decisions, project plans, etc.

[Architecture Vision - Phase A](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap07.html)

* Problems defined, solutions to be delivered
* Develop a high level vision to be delivered
* Obtain approval for the statement of architecture work
	* Scope, estimate resources required, develop a roadmap and schedule
	* Define KPIs and metrics
* Developer a communications plan

Architecture Vision - Objectives

* Develop a high-level aspirational vision of the capabilities and business value to be delivered as a result of the proposed enterprise architecture
* Obtain approval for a Statement of Architecture Work that defines a program of works to develop and deploy the architecture outlined in the Architecture Vision

[Business Architeture - Phase B](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap08.html)

* The B in BDAT
* Develop a baseline business architecture v1.0 - current state, developed bottom-up
* Develop a target business architecture v1.0 - top down
* Identify gaps between baseline, target

Business Architecture - Objectives

* Develop the Target Business Architecture that describes how the enterprise needs to operate to achieve the business goals, and respond to the strategic drivers set out in the Architecture Vision, in a way that addresses the Request for Architecture Work and stakeholder concerns
* Identify candidate Architecture Roadmap components based upon gaps between the Baseline and Target Business Architectures

[Information System Architecture - Phase C](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap09.html)

* The D and A in BDAT
* Data and applications done separately
* Develop baseline [data architecture](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap10.html) v1.0
* Develop target data architecture v1.0
* Develop baseline [application architecture](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap11.html) 1.0
* Develop target app architecture 1.0

Objectives

* Develop the Target Information Systems (Data and Application) Architecture, describing how the enterprise's Information Systems Architecture will enable the Business Architecture and the Architecture Vision, in a way that addresses the Request for Architecture Work and stakeholder concerns
* Identify candidate Architecture Roadmap components based upon gaps between the Baseline and Target Information Systems (Data and Application) Architectures


[Technology Architecture - Phase D](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap12.html)

* T in BDAT
* Same story - baseline and target, gap analysis

Objectives:

* Develop the Target Technology Architecture that enables the logical and physical application and data components and the Architecture Vision, addressing the Request for Architecture Work and stakeholder concerns
* Identify candidate Architecture Roadmap components based upon gaps between the Baseline and Target Technology Architectures

Phase E - Opportunities and Solutions

* Initial complete version of the architecture roadmap, based on gap analysis of the bdat
* Consolidation of phases B, C, and D into a roadmap
* Determine if incremental approach needed
	* If you can't swap new solution for old in one step, you may need to define incremental work
	packages that represent transition architectures.
* Formulate implementation strategy
* Identify and group work packages
	* Sequencing of work
	* Grouping of work (what can be done at the same time?)

Phase F - Migration Planning

* Finalize the architecture roadmap and the implementation and migration plans from phase E
* Ensure the plan is coordinated with the enterprise's approach to change
	* Risk averse organizations vs risk taking organizations	
* Ensure the business value of the approach is understood by the stakeholders
* Start thinking about implementation: costs, resources, timing
* Transition from developing the architecture to implementing

Phase G - Implementation Govenernance

* Ensure conformance with the target architecture
* Governance duties
* Handling change requests from the implementation team
* Update baseline architecture as changes are implemented
	* Done when a transition architecture goes live
* Phase G ends when the solutions are fully deployed

Phase H - Architecture Change Management

* Keeping the architecture alive
* Ensure architecture governance is happening
* Ensure the enterprise architecture capability is maintained
* Monitoring: changes to the business enterprise, changes to the industry, changes
to technology, formal change requests.


Requirements Management

* Center of the hub
* Operates continuously during the ADM process
* Requirements change all the time
	* New competitor, new legislation, disproven assumption, new company policy
* RM involves assessing the impact of these changes

[ADM Iterations](http://pubs.opengroup.org/architecture/togaf9-doc/arch/chap19.html)

* Not mandatory, can just follow A - H, normal one phase at a time approach
* Architecture development iteration
	* Example: baseline first
		* Do B - H to do the baseline 
		* Go back to B - H to go light pass target arch
		* B - H again, target detail
	* Example: target first
		* Hit the target arch first, then go back lightly on baseline
* Transition planning iteration
	* Loop between E and F
* Architecture Governance
	* Loop between G and H
* Architecture capability
	* Done with H, back to A - access your capability, do some iteration on it halfway through between A and H


