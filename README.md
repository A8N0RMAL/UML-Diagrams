# UML-Diagrams
## In this repo, I'll try to talk about UML diagrams
### Understanding UML, A Comprehensive Overview:
- UML (Unified Modelling Language) is an essential tool for software developers, offering a standardized set of diagrams to visualize, design, and document software systems. It provides a common notation for communicating complex system designs, aiding in collaboration and validation of architectural decisions. UML encompasses a variety of diagram types, including both structural and behavioural representations, each serving specific modelling purposes. Structural diagrams like class diagrams, component diagrams, and deployment diagrams focus on system architecture and physical aspects, while behavioural diagrams such as use case diagrams and sequence diagrams capture system functionalities and interactions. Understanding UML and its various diagram types is crucial for effective system modelling and software development.
![UML](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/d5a2b7a2-6daa-4660-9ab0-3dea3e3564c4)

---

### Behavioural Diagrams
#### 1. Use Case diagram:
- Describes the functional requirements of the system in terms of use cases.
- Allows u to link what u need from the system with how the system meets those needs.
![Use Case](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/d2419f96-67c4-4e62-9f2e-55d49a44ab03)

#### 2. Activity diagram:
- Graphical representations of workflows of stepwise activities and actions with the support of choice iteration and concurrency.
- They describe the control flow of the target system such as exploring complex business rules and operations as well as describing the use cases and business processes.
- In UML activity diagrams are meant for modelling both computational and organizational processes.
![Activity Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/6503e015-05c0-4ca4-bd38-7a9c21386d5f)

#### 3. State Machine diagram:
- Describes the system behaviour. 
- Visualize the entire life cycle of objects.
![State Machine Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a502f1cd-e5a3-4fa1-8853-5b8fb57f9984)

#### 4. Sequence diagram:
- Models the interaction of object based on a time sequence.
- It shows how objects interact with each other in a particular use case.
![Sequence Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/277541a8-11ad-4b38-b13e-c237c0beac3b)

#### 5. Communication diagram:
- Similar to sequence diagram is a communication diagram, it also used to model the dynamic behaviour of a use case, when compared to sequence diagram communication diagram focuses more on showing object collaborations rather than the time sequence (in fact both are semantically equivalent and one can be generated from the another)
![Communication Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/bdc33326-3400-435d-a85b-0f04cccc73ea)

#### 6. Interaction Overview diagram:
- Focuses on the overview of the flow of the control of the interactions(this is a variant of activity diagram where the nodes are the interactions).
- Describes interactions in which messages and lifelines are hidden, we can link up the real diagrams and achieve a high degree of navigation between diagrams within an interaction overview diagram.
![Interaction Overview diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/7cb735d2-2c0f-4b51-8c3d-c431505ce902)

#### 7. Timing diagram:
- Shows the behaviour of the object or objects at a given time period, In fact this is a special form of sequence diagram and the differences between them are that the axes are swapped, So that the time increases from left to right and the lifelines are displayed in separate compartments arranged vertically.
![Timing Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/6bc8083c-34f3-4545-8f05-05878e053882)
![Timing Diagram1](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/876b6bcf-1542-484c-9243-33e04b94ea22)

---

### Structural Diagrams
#### 1. Class diagram :  
- Describes the types of objects in the system and different kinds of static relationships that exist between them.
- Three most important types of relationships in class diagrams 
1. association -> which represents the relationships between instances of types (ex. A person works for a company or a company has multiple offices).
2. inheritance -> which corresponds directly to inheritance in object oriented design.
3. aggregation -> which is a form of object composition in object oriented design.

#### 2. Object diagram:
- An instance of class diagram, it shows a detailed snapshot of a system state at a particular point in time.
- The difference is that the class diagram is an abstract model of classes and their relationships however the object diagram represents an instance at a specific moment which is concrete in nature(the use of obj. diagrams is rather limited namely to show examples of Data Structures).

#### 3. Component diagram:
- Illustrate how components are put together to form a larger components or software systems and illustrates the architecture of SW components and dependencies between them, these SW components can include runtime components, executable components and source code components.

#### 4. Deployment diagram:
- Helps to model the physical aspects of an OO SW system, this is a block diagram that shows the system architecture as deployment or distribution of SW artifacts, artifacts represent specific elements in the physical world that are the result of development process.
- the diagram simulates the runtime configuration in a static view and visualize the distribution of the artifacts in the application, in most cases this involve simulating HW configurations along with the SW components that host them.

#### 5. Package diagram:
- It shows packages and dependencies between them, it allows us to display different views of the system(ex. it is easy to simulate a layered application).

#### 6. Composite diagram:
- It is similar to a class diagram, used mainly in micro level system modeling but it depicts individual parts instead of whole classes, it shows the internal structure of a class and interaction that the structure makes possible.
- This diagram can include internal parts, ports through which the parts can communicate with each other or through which the class instances can communicate with various parts and with the outside world as well as connectors between parts and ports.
- Composite structural diagram is a set of interrelated elements that interact at runtime to achieve a specific goal, each element has a dedicated role in this collaboration.

#### 7. Profile diagram:
-   Allows us to create domain and platform specific stereotypes and define relationships between them, we can create stereotypes by drawing shapes of stereotypes and linking them to composition or generalization through a resource oriented interface, we can also define and visualize stereotypes values.

---

