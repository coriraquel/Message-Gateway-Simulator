# Message-Gateway-Simulator
## Overview: 
This project is a Message Gateway Simulator designed to mimic the behavior of a simplified data link gateway system. It receives JSON messages, translates them into XML, stores them in a database, and then transmits them to an output file. This workflow models the fundamental steps in systems integration and verification, providing a hands-on environment to practice core systems engineering concepts.
## Problem Statement: 
In modern systems engineering, especially in domains such as defense and aerospace, systems often need to receive, translate, store, and transmit data between components. These tasks can become complex when multiple formats and protocols are involved. This project simulates a toy gateway system to demonstrate how such message pipelines can be designed, implemented, and tested.
## Learning Objectives: 
1. __Systems V Engineering Model:__ Show comprehensive understanding of the V-model at a small scale
2. __Modular Components:__ Demonstrate an understanding of breaking down systems into small testable components
3. __Automated Testing:__ Perform automated testing using Pytest
## Technologies Used:
1. __Python:__ Core implementation
2. __SQLite:__ Lightweight database for message storage
3. __Pytest:__ Testing framework 
4. __XML & JSON:__ Message formats for translation
5. __Diagramming tools (draw.io):__ For architecture modeling

## Data Description
1. _Input:_ JSON formatted messages, one per line
2. _Translated Output:_ Equivalent XML representation of each message
3. _Database Storage:_ SQLite database containing XML strings
4. _Transmitted Output:_ File where XML messages are appended

## Learner Growth: 
By completing this project, I will demonstrate an understanding of systems thinking by structuring a software project following a real-world engineering system. In addition, I will show the ability to integrate software by connecting independent modules into a working pipeline, as well as test and verify the system using unit and system tests. Finally, I will show documentation competency through creating requirement work papers, architecture diagrams, and test plans.  

## Potential Questions: 
1. How could this system be extended to support multiple protocols?
2. What would hardward integration look like?
3. How can MBSE tools enhance traceability from requirements to implementation?
4. How could automated testing be scaled to handle real-time message streams? 

## Timeline: 
Phase 1: Implementation of Receiver, Translator, Storahe, and Transmitter modules. <br>
Phase 2: Add unit tests and documentation (requirements + architecture diagram) <br>
Phase 3: Build an integration pipeline and add GitHub Actions for testing <br>
Phase 4: Expand with stretch goal features (REST API, hardware integration, error handling) <br>

## License: 
This project is licensed under the MIT License. See the LICENSE file for details.
