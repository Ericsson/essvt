# ESSVT

Ericsson Support Systems Validation Tool (ESSVT) is an orchestration tool that secures continuous testing, to deliver on time with quality. It's a powerful testing solution designed to enable test automation for Ericsson users and its customers. Its primary purpose is to facilitate testing in CI/CD workflows, although it can also be used for standalone testing. 

One of ESSVT's key features is its lightweight and user-friendly interface (GUI), which enables easy interaction with both humans and other services. It can be used for functional and non-functional testing. It supports most common protocols and is especially tailored for verification and validation of telecom equipment.

## ESSVT - NBI OpenAPI

All ESSVT operations that can be done in the GUI can also be done using the NBI REST interface. ESSVT  utilizes OpenAPI to implement a REST NBI interface. The interface for instance supports operations to trigger execution, get execution info, terminate and re-run execution. 

The OpenAPI definition for ESSVT NBI is available in this repository. 



## ESSVT - Robot Framework Support

ESSVT has built in support for Robot Framework and it can manage and orchestrate execution of test cases. Version 3.1 of ESSVT has a default runner that contains Robot Framework 6.0. This image contains a set of Robot Framework libraries that can be used to create test cases. In ESSVT we call this image the default runner.

If a library is missing one can either request to get that added to the default runner so it's available in next ESSVT release or its also possible to create a custom runner with own libraries.

The library documentation for the ESSVT default runner is available in this repository

