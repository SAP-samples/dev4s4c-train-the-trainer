# SAP-samples/dev4s4c-train-the-trainer
This default template for SAP Samples repositories includes files for README, LICENSE, and .reuse/dep5. All repositories on github.com/SAP-samples will be created based on this template.

# Containing Files

1. The LICENSE file:
In most cases, the license for SAP sample projects is `Apache 2.0`.

2. The .reuse/dep5 file: 
The [Reuse Tool](https://reuse.software/) must be used for your samples project. You can find the .reuse/dep5 in the project initial. Please replace the parts inside the single angle quotation marks < > by the specific information for your repository.

3. The README.md file (this file):
Please edit this file as it is the primary description file for your project. You can find some placeholder titles for sections below.

# Dev4S4C-Train-The-Trainer

<!--- Register repository https://api.reuse.software/register, then add REUSE badge:
[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/REPO-NAME)](https://api.reuse.software/info/github.com/SAP-samples/REPO-NAME)
-->

# Description

This repository contains technical artifacts required for running the Dev4S4C Hands-on workshop using some theory sessions with some hands-on exercises.
Dev4S4C enables both Architects and Developers via highly interactive and high-touch sessions over a 2-day period, where our partners can learn with SAP experts, and put their knowledge to the test with hands-on exercises.
Covering contents directly related to delivering cloud solutions keeping the core clean, such as: ABAP Cloud, custom code migration, Application Extension Methodology, SAP S/4HANA extensibility options, and Clean Core concepts.

This repository contains two packages 

1) Setup Content: (z_trainer_reuse_objects) : This contains the Trainer content which contains the re-usable artifacts to be used for the Hands-on Exercises.
2) Sample Artifacts:(z_trainer_solutions_d4s4) : The sample artifacts created after the completion of the hands-on exercises. These are given for reference purposes only. These artifacts are ideally created after the completion of the hands-on exercises as per the documents given for the workshop.

# Details of the Exercises

This repository is requires S/4HANA Cloud, Public Edition (Development Tenant) to be able to import the content.

# Exercise Details 
Exercise 1 : Build a small Extension in S/4HANA Cloud (Scenario Depiction) 

![image](https://github.com/SAP-samples/dev4s4c-train-the-trainer/assets/84840453/d50ca17a-9e73-4b6a-8012-1cab8c978238)
![image](https://github.com/SAP-samples/dev4s4c-train-the-trainer/assets/84840453/123e144c-d912-4229-ad99-5a0fef998bea)

Exercise 2 : Build a custom API for side-by-side extensibility

In this exercise, we will create a custom inbound OData API in an S/4HANA Cloud system. We will reuse the business object from the first day, i.e., the online shop, and create an OData service binding of type Web API on top of it. We will also create a custom communication scenario to expose our API.

We will consume the API from an ABAP system running on SAP BTP, i.e., an SAP BTP ABAP Environment service instance. We will use the API’s metadata to create a service consumption model, which will allow us to call the API directly from ABAP coding. As a simple example, we will consume the API from a plain HTTP
service, which will contain the custom coding in its handler class.

![image](https://github.com/SAP-samples/dev4s4c-train-the-trainer/assets/84840453/2c867ae6-44f0-4ce4-b3cb-7be9f72702da)

# Download and Installation

Import the ABAP development objects of this repository into your system using abapGit as described here and run the demo classes by choosing F9 in the ABAP development tools for Eclipse (ADT) for checking out the ABAP syntax in action. Import the repository into the development tenant of the S/4HANA Cloud, Public Edition. 
 
## Disclaimer
The code examples presented in this repository are only syntax examples and are not intended for direct use in a production system environment. The code examples are primarily intended to provide a better explanation and visualization of the syntax and semantics of ABAP statements and not to solve concrete programming tasks. For production application programs, a dedicated solution should therefore always be worked out for each individual case. There is no guarantee for either the correctness or the completeness of the code. In addition, there is no legal responsibility or liability for possible errors or their consequences, which occur through the use of the example code.

## Known Issues
No known issues
<!-- You may simply state "No known issues. -->
## How to obtain support
[Create an issue](https://github.com/SAP-samples/dev4s4c-train-the-trainer/issues) in this repository if you find a bug or have questions about the content.
 
For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## Contributing
This is not intended to be a contribution repository, so please do not create pull requests. If you like to address issues or suggestions, please create an issue. However, this project is provided "as-is": there is no guarantee that raised issues will be answered or addressed in future releases.

## License
Copyright (c) 2023 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSE) file.
