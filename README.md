# Content

1. [Chapter 1: Fundamentals of Software Quality](#chapter1)
    - [Chapter 1 - Part 1: Concepts and Terminology](#chapter1part1)
    - [Chapter 1 - Part 2: Functional and Non-Functional Quality](#chapter1part2)
    - [Chapter 1 - Part 3: Software Quality Attributes](#chapter1part3)
2. [Chapter 2: Software Dependability](#chapter2)
    - [Chapter 2 - Part 1: Attributes, Threats, and Means](#chapter2part1)
    - [Chapter 2 - Part 2: Software Dependability Techniques](#chapter2part2)
3. [Chapter 3: Analysis and Formal Methods (Static)](#chapter3)
    - [Chapter 3 - Part 1: Inspections, Reviews, and Audits](#chapter3part1)
    - [Chapter 3 - Part 2: Automated Static Analysis](#chapter3part2)
    - [Chapter 3 - Part 3: Formal Methods for Specification and Verification](#chapter3part3)
    - [Chapter 3 - Part 4: Model checking](#chapter3part4)
4. [Chapter 4: Software Testing (Dynamic)](#chapter4)
    - [Chapter 4 - Part 1: Unit Testing, Integration Testing, and System Testing](#chapter4part1)
    - [Chapter 4 - Part 2: Black-box and White-box Testing](#chapter4part2)
    - [Chapter 4 - Part 3: Model-based Testing](#chapter4part3)
    - [Chapter 4 - Part 4: Coverage Criteria](#chapter4part4)
    - [Chapter 4 - Part 5: Testing Parallel and Distributed Systems](#chapter4part5)
    - [Chapter 4 - Part 6: Regression Testing](#chapter4part6)
    - [Chapter 4 - Part 7: Defect tracking and ODC](#chapter4part7)
5. [Chapter 5: Development Models and Standards](#chapter5)
    - [Chapter 5 - Part 1: Software Life Cycle Processes](#chapter5part1)
    - [Chapter 5 - Part 2: Software Product Quality](#chapter5part2)
    - [Chapter 5 - Part 3: Test-Driven Development](#chapter5part3)
    - [Chapter 5 - Part 4: Contract-Based Specification](#chapter5part4)
6. [Chapter 6: Certification](#chapter6)
    - [Chapter 6 - Part 1: CMMI (Capability Maturity Model Integration)](#chapter6part1)
    - [Chapter 6 - Part 2: Measuring and Estimating Software Quality](#chapter6part2)
    - [Chapter 6 - Part 3: Verification and Validation (including non-code artifacts)](#chapter6part3)
    - [Chapter 6 - Part 4: Quality Assurance](#chapter6part4)
7. [Chapter 7: Software Dependability and Security Evaluation](#chapter7)
    - [Chapter 7 - Part 1: Software Dependability and Security Evaluation](#chapter7part1)
8. [Bibliography's](#biblio)

## <a name="chapter1"></a>Chapter 1: Fundamentals of Software Quality

#### <a name="chapter1part1"></a>Chapter 1 - Part 1: Concepts and Terminology

**Software quality – a definition**

Software quality is the degree to which a software product meets established requirements; however, quality depends upon the degree to which established requirements accurately represent stakeholder needs, wants, and expectations.

Two aspects of software quality are presented in the above definition: one is meeting the requirements, while the other is generating customer/stakeholder satisfaction. A high quality software product is expected to meet all written development requirements – whether defined fully before the development began, or later in the course of the development process – and to meet the relevant regulations and professional conventions. Quality is also achieved through fulfillment of stakeholder needs and wants.

**Software quality assurance – a definition**

A set of activities that define and assess the adequacy of software process to provide evidence that establishes confidence that the software processes are appropriate for producing software products of suitable quality, for their intended processes, or for their intended operation services and fulfils the requirements of schedule and budget keeping.

**The objectives of SQA activities are:**

- Ensuring an acceptable level of confidence that the software product and software operation services will conform to functional technical requirements and be suitable quality for its intended use.

- According to the extended SQA definition – ensuring an acceptable level of confidence that the software development and software operation process will conform to scheduling and budgetary requirements.

- Initiating and managing activities to improve and increase the efficiency of software development, software operation, and SQA activities. These activities yield improvements to the prospects’ achieving of functional and managerial requirements while reducing costs.

**Software product definition**

A collection of components necessary to ensure proper operation, and efficient maintenance during its life cycle. The components include (1) computer programs (“code”), (2) documentation, (3) data necessary for its operation and maintenance (including standard test), and (4) procedures.

The software product components are:

- **Computer programs “the code”**: The computer programs activate the computer system to perform the required applications. The computer programs include several types

- **Procedures**: Procedures define the order and schedule within which the software or project programs are performed, the method for handling common malfunctioning of software products, and so on.

- **Documentation**: The purpose of the documentation is to instruct or support new software product version developers, maintenance staff, and end users of the software product. It includes the various design reports, test reports, and user and software manuals, and so on.

- **Data necessary for operating the software system**: The required data include lists of codes and parameters, and also standard test data. The purpose of the standard test data is to ascertain that no undesirable changes in the code or software data have occurred during bug corrections and other software maintenance activities, and to support the detection of causes for any malfunctioning.

#### <a name="chapter1part2"></a>Chapter 1 - Part 2: Functional and Non-Functional Quality

In software engineering the functional versus non-functional view appears at the requirements level. That is, appear at the very beginning of the development process

**Functional view**

The Functional view of a software, is what the software system does. In this view, quality is related to match between the functionalities and the user needs and/expectations

**Functional requirements**

Describes what a software system should do. Function points is a usual metric to characterize and assess the size of the software

**Non-Functional view**

Non-Functional view of a software, is the quality attribute os a software system and is how the software system does it. Most of them cannot be measured directly

**Non-functional requirements**

Define constraints (or goals) on how the system will do so. Include basically everything that is not related to the functional aspects of the software system

#### <a name="chapter1part3"></a>Chapter 1 - Part 3: Software Quality Attributes

This quality attributes make sense at system level, not just at program/application level. Depend on both, software and hardware and architectural design choices and
configuration choices.

<br>

<div align="center"><img src="img/availability-w504-h285.png" width=504 height=285><br><sub>Fig 1 - Availability - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

<div align="center"><img src="img/reliability-w514-h203.png" width=514 height=203><br><sub>Fig 2 - Reliability - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

<div align="center"><img src="img/security-w510-h369.png" width=510 height=369><br><sub>Fig 3 - Security - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

<div align="center"><img src="img/performance-w525-h361.png" width=525 height=361><br><sub>Fig 4 - Performance - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

<div align="center"><img src="img/usability-w527-h412.png" width=527 height=412><br><sub>Fig 5 - Usability - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

<div align="center"><img src="img/maintainability-w495-h215.png" width=495 height=215><br><sub>Fig 6 - Maintainability - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

<div align="center"><img src="img/manageability-w490-h256.png" width=490 height=256><br><sub>Fig 7 - Manageability - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

<div align="center"><img src="img/cost-w516-h301.png" width=516 height=301><br><sub>Fig 8 - Cost - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

**Exam Question: Explain why availability is an attribute of security. Give examples.**

Security: is a composite of three properties: **Confidentiality**, **Integrity** and **Availability**

<br>

<div align="center"><img src="img/cia-w300-h259.png" width=300 height=259><br><sub>Fig 9 - Security Quality Attribute - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

**Confidentiality in cyber security**

When doing business with clients and prospects, it is common to collect and store their personal information. Names, email addresses and phone numbers are a few examples of personal information. This is sensitive data that your company is responsible for protecting and securing. Relying and trusting your cloud or CRM provider is not enough. Your business needs to enforce extra security measures to ensure that your clients and prospects’ privacy is safeguarded.

Protecting confidentiality can start from defining and controlling access levels of information internally and externally. For example, those who work in the IT department that typically don’t interact with clients and prospects, should not have access to client information. If someone does not need a type of information to perform their work, then they should not have access to that information.

When data accessibility is limited, you significantly lower the chances of having information being leaked accidentally or intentionally.

Examples of confidentiality risks include data breaches caused by criminals, insiders inappropriately accessing and/or sharing information, accidental distribution of sensitive information to too wide of an audience.

**Integrity in cyber security**

Integrity means that data or information in your system is maintained so that it is not modified or deleted by unauthorized parties. This is an important element of data hygiene, reliability and accuracy.

To reserve data integrity, the easiest methods are backing up your data, using access controls, monitoring your audit trail and encrypting your data.

Examples of attacks on integrity include email fraud attacks (which compromise the integrity of communications), financial fraud and embezzlement through modification of financial records, even attacks like Stuxnet that impacted the integrity of industrial control systems data flows to cause physical damage.

**Availability in cyber security**

The final component of the CIA Triad is availability. It means that systems and data are available to individuals when they need it under any circumstances, including power outages or natural disasters. Without availability, even if you have met the other two requirements of the CIA Triad, your business can be negatively impacted.

To ensure availability, your organization can use redundant networks, servers and applications. These can be programmed to become available when the primary system is broken down. Besides having backups, the design of IT architecture plays a key role as well. For instance, if high availability is a component of your IT systems, then you could maintain a certain level of operational performance for an extended period of time even in unexpected circumstances.

Examples of attacks on availability include Denial of Service attacks, Ransomware (which encrypts system data and files so they are not accessible to legitimate users), even swatting attacks which can interrupt business operations.

## <a name="chapter2"></a>Chapter 2: Software Dependability

#### <a name="chapter2part1"></a>Chapter 2 - Part 1: Attributes, Threats, and Means

<br>

<div align="center"><img src="img/dependability2-w786-h611.png" width=786 height=611><br><sub>Fig 10 - Software Dependability Taxonomy - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

**What is Software Dependability?**

Dependability is a term proposed in 1995 by Jean-Claude Laprie to reflect the user’s confidence and degree of trust to use a software system, covering some attributes like availability, reliability, safety, confidentiality, integrity, and maintainability. Systems that are not dependable, in other words, unsafe, insecure, and unreliable, tend to be rejected by the user because they are not safe enough.

Depending on the software type, dependability is an important attribute. In Critical Systems, dependability is the most crucial property because a system’s failure may result in injury, damage, or economic losses to the environment and/or people. Examples of critical systems:

- Embedded systems in medical devices (safety-critical).

- Spacecraft navigation systems (mission-critical).

- Online money transfer systems (business critical).

Dependable software needs to be secure, and for this, it is essential to have good coverage of tests to detect, prevent, or remove all possible failures. The more dependable the software is, the more expensive it is because better and more intensive tests have to be applied.

<br>

<div align="center"><img src="img/dependability-w433-h378.png" width=433 height=378><br><sub>Fig 11 - Cost/dependability curve - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

**Software Dependability Attributes**

- **Availability**: The probability of a system being available and delivering services to users at a given time;
- **Reliability**: The ability of a system to continuously deliver services as expected by the user under predefined conditions;
- **Safety**: The ability of a system to protect against damage.
- **Confidentiality**: The ability of the system to be private and not give access for no-authorized;
- **Integrity**: The ability of a system against improper information modification or destruction;
- **Maintainability**: The ability of a system to be modified effectively and efficiently by the maintainers.

**Robustness**

The degree to which a system or component can function correctly in the presence of invalid inputs or stressful environmental conditions.

Robustness is used very often to test software interfaces such as system calls, APIs, web services, etc. This is called **robustness testing**

Robustness is defined informally as: “dependability with respect to erroneous input”

**Resilience**

The persistence of dependability when facing changes = dependability + Robustness

That is, changes include all sort of upsets:

- Hardware and software faults
- Malicious attacks
- Configuration changes
- Software and hardware upgrades

Resilience is related to robustness in that the key is unforeseen changes: The changes apply to robustness in inputs and environmental conditions, and more generally to resilience in terms of any changes that affects the service delivery of the system.

**Exam Question: If a web service crashes when called with a give combination of valid inputs, can you claim that the web service is not robust? Explain.**

**Software Dependability Threats**

<br>

<div align="center"><img src="img/fault-w683-h383.png" width=683 height=383><br><sub>Fig 12 - Software Dependability Threats - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

**Fault**: A condition that may cause a system to fail in performing its required function

**Error**: A measure of the difference between the actual and the ideal.

**Failure**: The inability of a system or component to perform a required function according to its specifications

<br>

<div align="center"><img src="img/fault4-w407-h142.png" width=407 height=142><br><sub>Fig 12 - Failure/Restoration - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

**Correct service**: is delivered when the service implements the expected system function.

**Service failure**:is an event that occurs when the delivered service deviates from correct service

**Failure**: is a transition from correct service to incorrect service

**Restoration**: the transition from incorrect service to correct service.

**Classification of faults**

Caused by what?
– Physical faults
– Human-Made faults

Why?
– Accidental faults
– Intentional non malicious faults / Intentional malicious faults

When?
– Development faults: design, coding, configuration, upgrading
– Operational faults: in use

Where (with respect to the system)?
– Internal faults
– External faults

How long?
– Permanent faults
– Transient faults

<br>

<div align="center"><img src="img/fault3-w770-h636.png" width=770 height=636><br><sub>Fig 13 - Types of Software Faults - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

A fault can be originated in the software development process, since requirement, specification and so on...Residual software faults (bugs), originated from defects in design or implementation of software components and its integration in a system, that escape testing and other fault avoidance method.

**Different types of software faults**

Bohrbugs -> Bugs that cause failures deterministically and easiest to find during testing, 
- Fault tolerance = design diversity and redundancy

Mandelbugs -> Re-execution after a failure caused by a Mandelbug will generally not cause another failure and cery difficult to find and correct during testing
- Fault tolerance = simple retries and recovery-oriented computing using checkpointing

Aging-related -> Bugs tend to be activated and cause failures after long periods of system run-time and Difficult to find during testing (but static code analysis is effective for some of them)
- Fault tolerance = software rejuvenation

**Software Reliability Threats** (Other terminology - Vision) 

<br>

<div align="center"><img src="img/fault2-w647-h102.png" width=647 height=102><br><sub>Fig 13 - Software Reliability Threats - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

**Error**: **Human action** that results in software containing a fault.

**Fault**: A cause for an internal error

**Failure**: any observable divergence of software behavior in execution from user needs

The origin of software failures lies in a software error made by a programmer. An error can be a grammatical error in one or more of the code lines, or a logical error in carrying out one or more of the client’s requirements.

However, not all software errors become software faults. In other words, in some cases, the software error can cause improper functioning of the software in general or in a specific application. In many other cases, erroneous code lines will not affect the functionality of the software as a whole; in a part of these cases, the fault will be corrected or “neutralized” by subsequent code lines.

We are interested mainly in the software failures that disrupt our use of the software. This requires us to examine the relationship between software faults and software failures. Do all software faults end with software failures? Not necessarily: a software fault becomes a software failure only when it is “activated” – when the software user tries to apply the specific, faulty application. In many situations, a software fault is never activated due to the user’s lack of interest in the specific application or to the fact that the combination of conditions necessary to activate the fault never occurs.

**Failure Modes**

Computer failures are normally complex, as result of the high complexity of systems and simple failure modes such as pure silent failures (clean crash or halt failures) are relatively rare.

**Failure mode**: condensed description of the way a component/computer system fails

Mainly from the operating system perspective. CRASH = Catastrophic, Restart, Abort, Silent, Hindering

- Catastrophic (OS crashes/multiple tasks affected)
- Restart (task/process hangs, requiring restart)
- Abort (task/process aborts, e.g., segmentation violation)
- Silent (no error code returned when one should be)
- Hindering (incorrect error code returned)

<br>

<div align="center"><img src="img/failure-w479-h360.png" width=479 height=360><br><sub>Fig 14 - Tips of Failure - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

The Domain can be divided into Value Failures when an improper value is computed and Timing Failures when the system delivers its service either early or late.

The Perception by Several Users can be divided into Consistent Failures when all users have the same perception of the failure or Inconsistent Failures when users have different perceptions of the failure.

The types of failures can be divided into several levels, from the most negligible to the most impactful. The consequences of lesser impact are called benign failure, and those of more significant impact is called catastrophic failure

**Software Dependability Means**

<br>

<div align="center"><img src="img/means-w844-h470.png" width=844 height=470><br><sub>Fig 15 - Means in Dependability - (<a href='https://www.uc.pt/en/fctuc/dei'>Work by University of Coimbra - DEI - https://www.uc.pt/en/fctuc/dei </a>) </sub></div>

<br>

**Fault Prevention**: Is the prevent the occurrence of faults. Can be attained in three phases of software development. In the requirement phase, very well gathering and documented requirements can avoid ambiguity and mistakes. In the design phase, with the use of design validations like Proof of Concepts and using standards to design the architecture and the component. In the development phase, having good development practices, doing code review, and writing unit testings covering all possibles faults. 

Fault prevention techniques intended to keep faults out of the system. Applied at the design stage
Related to general system engineering techniques (design methodologies, construction rules, use of high reliable components). Include:

- Rigid software development process
- Formal methods
- Improve development process to avoid/minimize faults Ex: V-model
- Use selected technologies (better components, certified software tools, etc. )

**Fault Tolerance techniques**: to provide correct service in presence of faults. Can be attained when the software delivers its correct service even in the presence of an active fault or when an error is detected, and the system can recover. In fault tolerance, the core business of the software has to be available, preventing a total loss of the functionalities, which can be achieved by using fault tolerance techniques like graceful degradation.

- Triple modular redundancy, N-Version programming, check pointing and recovery

**Fault Removal techniques**: specific techniques to reduce the presence of faults (number, seriousness, ...). Can be attained in the development phase and consists of a process that verifies the fault by detecting and eliminating it. This process consists of verification and validations techniques, using test cases, cross-verification, continuous integration and testing.

- Development: regression and non-regression testing, static and dynamic verification, etc
- Operation: preventive maintenance such as patches, updates, SW rejuvenation, etc.

**Fault Forecasting techniques**: to estimate the present number, the future incidence, and the consequences of faults. Can be attained using models to predict potential faults in the system. It uses static models or historical data to predict faults in some module or component that had fault occurrence.

- Probabilistic assessment, modeling, operational evaluation,…

#### <a name="chapter2part2"></a>Chapter 2 - Part 2: Software Dependability Techniques

## <a name="chapter3"></a>Chapter 3: Analysis and Formal Methods (Static)

#### <a name="chapter3part1"></a>Chapter 3 - Part 1: Inspections, Reviews, and Audits

#### <a name="chapter3part2"></a>Chapter 3 - Part 2: Automated Static Analysis

#### <a name="chapter3part3"></a>Chapter 3 - Part 3: Formal Methods for Specification and Verification

#### <a name="chapter3part4"></a>Chapter 3 - Part 4: Model checking

## <a name="chapter4"></a>Chapter 4: Software Testing (Dynamic)

#### <a name="chapter4part1"></a>Chapter 4 - Part 1: Unit Testing, Integration Testing, and System Testing

#### <a name="chapter4part2"></a>Chapter 4 - Part 2: Black-box and White-box Testing

#### <a name="chapter4part3"></a>Chapter 4 - Part 3: Model-based Testing

#### <a name="chapter4part4"></a>Chapter 4 - Part 4: Coverage Criteria

#### <a name="chapter4part5"></a>Chapter 4 - Part 5: Testing Parallel and Distributed Systems

#### <a name="chapter4part6"></a>Chapter 4 - Part 6: Regression Testing

#### <a name="chapter4part7"></a>Chapter 4 - Part 7: Defect tracking and ODC

## <a name="chapter5"></a>Chapter 5: Development Models and Standards

#### <a name="chapter5part1"></a>Chapter 5 - Part 1: Software Life Cycle Processes

#### <a name="chapter5part2"></a>Chapter 5 - Part 2: Software Product Quality

#### <a name="chapter5part3"></a>Chapter 5 - Part 3: Test-Driven Development

#### <a name="chapter5part4"></a>Chapter 5 - Part 4: Contract-Based Specification

## <a name="chapter6"></a>Chapter 6: Development Models and Standards

#### <a name="chapter6part1"></a>Chapter 6 - Part 1: CMMI (Capability Maturity Model Integration)

#### <a name="chapter6part2"></a>Chapter 6 - Part 2: Measuring and Estimating Software Quality

#### <a name="chapter6part3"></a>Chapter 6 - Part 3: Verification and Validation (including non-code artifacts)

#### <a name="chapter6part4"></a>Chapter 6 - Part 4: Quality Assurance

## <a name="chapter7"></a>Chapter 7: Software Dependability and Security Evaluation

#### <a name="chapter7part1"></a>Chapter 7 - Part 1: Software Dependability and Security Evaluation

# Bibliography's <a name="biblio"></a>

Some of references that I use.

1. [Systems Engineering Body of Knowledge][sebok-url]
2. [Software Quality][sqa-url]
3. [Software Quality Assurance][sqaa-url]
4. [Software Engineering - Computer Notes][swcomputernotes-url]
5. [Software Engineering - Geeks for Geeks][swgeeks-url]
6. [Software Engineering - Java T Point][swjavatpoint-url]

<!-- URL's -->

[sebok-url]:https://www.sebokwiki.org/wiki/Guide_to_the_Systems_Engineering_Body_of_Knowledge_(SEBoK)
[sqa-url]: https://nibmehub.com/opac-service/pdf/read/Software%20quality%20%20concepts%20and%20practice.pdf
[sqaa-url]: http://desy.lecturer.pens.ac.id/Manajemen%20Kualitas%20Perangkat%20Lunak/ebook/Software%20Quality%20Assurance%20From%20Theory%20to%20Implementation.pdf
[swcomputernotes-url]: https://ecomputernotes.com/software-engineering
[swgeeks-url]: https://www.geeksforgeeks.org/software-engineering/?ref=lbp
[swjavatpoint-url]: https://www.javatpoint.com/software-engineering-tutorial
