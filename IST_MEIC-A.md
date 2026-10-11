# IST Course Projects: MEIC-A / MSc CSE

This is a portfolio of the projects I developed for my Master's Degree in Computer Science and Engineering at [Instituto Superior Técnico](https://tecnico.ulisboa.pt/en/), University of Lisbon.

I specialized in Software Engineering and Distributed Systems, and also did some courses on Artificial Intelligence, Cybersecurity, and Engineering and Data Science.

## Areas

### Software Engineering

- (P1) **Software Specification**
    - Project 1: [Dafny-IST](https://github.com/TiDeane/Dafny-IST) [ Dafny ]  \
      Five formally verified Dafny exercises: serialising and deserialising expression ASTs, detecting repeated array elements in quadratic and linear time, a linked-list library, and two set implementations built on it.
    - Project 2: [Alloy-IST](https://github.com/TiDeane/Alloy-IST) [ Alloy ]  \
      Alloy model of OneAtATime, a broadcast protocol in which only the leader can send messages: static modelling of valid networks, dynamic modelling of the protocol, and verification of its properties.

- (P2) **Software Architecture**
    - Project: [Web Crawler Case Study](https://drive.google.com/file/d/1ynopk11kCrzBkzTSMUZu9iji_91PcrWR/view?usp=sharing)  \
      Architecture design for a web crawler: functionalities, quality attribute scenarios (availability, security, integrability, modifiability, performance), constraints, and an Attribute-Driven Design process.

- (P3) **Advanced Programming**
    - Project: [Julia Exceptions](https://github.com/TiDeane/Julia-Exceptions) [ Julia ]  \
      Condition and restart system for Julia in the style of Common Lisp: handlers, signalling, non-local escapes and restarts, plus an extension that prompts the user to pick a restart interactively.

- (P4) **Software Testing and Validation**
    - Project: [Client-Terminal Communication Testing](https://github.com/TiDeane/TVS_IST/blob/main/proj-28.pdf) [ Java, TestNG ]  \
      Test case specification for a client-terminal communication system, at class scope (Client, Terminal) and method scope (computeCost(), removeTerminal()), with eight of the cases implemented in TestNG.

### Distributed Systems

- (P1) **Design and Implementation of Distributed Applications** 
    - Project: [DIDA Meetings](https://github.com/TiDeane/dida-meetings) [ Java, gRPC ]  \
      Replicated meeting management service built on state-machine replication, evolved from a basic Paxos baseline to Multi-Paxos and then to reconfigurable Multi-Paxos with state transfer to new replicas.

- (P2) **Network and Computer Security**
    - Project: [Chain Of Product](https://github.com/TiDeane/ChainOfProduct) [ Java, Java Cryptography Architecture ]  \
      Secure service for sharing supply-chain transaction documents between companies that distrust each other. A custom cryptographic library (protect, check, unprotect) provides confidentiality, authentication and integrity, with selective disclosure to individual partners or to groups tracked by a separate group server.

- (P3) **Parallel and Distributed Computing**  \
    _Also part of the "Engineering and Data Science" area_
    - Project: [N-body Problem Particles](https://github.com/TiDeane/PDCParticles) [ C, OpenMP, Open MPI ]  \
      Particle simulation of gravitational forces and collisions on a grid of cells, implemented in serial, OpenMP and MPI versions, with a performance analysis from 1 to 64 parallel tasks.

- (P4) **Cloud Computing and Virtualization**  \
    _Also part of the "Engineering and Data Science" area_
    - Project: [Cloud Webserver](https://github.com/TiDeane/CNV-Cloud-Webserver) [ Java ]  \
      Games@Cloud, a custom cloud orchestration system on AWS for computationally demanding tasks. Instrumented webservers record request complexity metrics in DynamoDB, and a custom load balancer and auto-scaler uses them to route each request to EC2 or Lambda, balancing performance against cost.

### Artificial Intelligence

- (P1) **Natural Language Processing**
    - Project: [Movie Genre Classifier](https://github.com/LC1243/NLP-MovieGenreClassifier) [ Python ]  \
      Classifier that predicts a movie's genre from its plot summary. Compares Naive Bayes, Logistic Regression, Random Forests, a fine-tuned TinyBERT and an SVM over TF-IDF features, with the SVM performing best at 69% accuracy.

- (P2) **Data Science**  \
    _Also part of the "Engineering and Data Science" area_
    - Project: Private...  \
      One iteration of the KDD process (data profiling, preparation, modelling and evaluation) for classification and forecasting tasks on two domains, security (NYPD arrests) and economy (financial distress, European GDP), with an analysis of how each preparation choice affects model performance.

### Cyber-Security

- (P3) **Software Security**
    - Project: [JavaScript Vulnerabilities](https://github.com/TiDeane/Js-Vulnerabilities) [ Python ]  \
      Static analysis tool that tracks tainted information flows through JavaScript program slices and reports potential vulnerabilities such as DOM XSS, based on configurable patterns of sources, sanitizers and sinks.

### Engineering and Data Science

- (P1) **Data Analysis and Integration**
    - Project: Private... [ SQL, MDX ]  \
    [ Pentaho Data Integration, Pentaho DataCleaner, Pentaho Schema Workbench, Saiku Analytics, Pentaho Report Designer ]  \
      Data warehouse for the UK Price Paid Data on property sales: a MySQL star schema with location and time dimensions, populated through Pentaho Data Integration transformations, then analysed with an OLAP cube, MDX queries and reports.
