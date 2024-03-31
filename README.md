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
![Class Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/56b0f89d-a362-498d-b532-f8deae0b1169)

#### 2. Object diagram:
- An instance of class diagram, it shows a detailed snapshot of a system state at a particular point in time.
- The difference is that the class diagram is an abstract model of classes and their relationships however the object diagram represents an instance at a specific moment which is concrete in nature(the use of obj. diagrams is rather limited namely to show examples of Data Structures).
![Object Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/08448eeb-fe22-4652-a757-3e8fd1af3307)

#### 3. Component diagram:
- Illustrate how components are put together to form a larger components or software systems and illustrates the architecture of SW components and dependencies between them, these SW components can include runtime components, executable components and source code components.
![Component Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/2fa639f0-a697-4ae8-a4b1-974b2c36952a)

#### 4. Deployment diagram:
- Helps to model the physical aspects of an OO SW system, this is a block diagram that shows the system architecture as deployment or distribution of SW artifacts, artifacts represent specific elements in the physical world that are the result of development process.
- the diagram simulates the runtime configuration in a static view and visualize the distribution of the artifacts in the application, in most cases this involve simulating HW configurations along with the SW components that host them.
![Deployment Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/940950c2-16ee-4f78-ad88-7e4879363db7)

#### 5. Package diagram:
- It shows packages and dependencies between them, it allows us to display different views of the system(ex. it is easy to simulate a layered application).
![Package Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/3e69c8cf-eaef-4f01-ad94-8bdac541a3fb)

#### 6. Composite diagram:
- It is similar to a class diagram, used mainly in micro level system modeling but it depicts individual parts instead of whole classes, it shows the internal structure of a class and interaction that the structure makes possible.
- This diagram can include internal parts, ports through which the parts can communicate with each other or through which the class instances can communicate with various parts and with the outside world as well as connectors between parts and ports.
- Composite structural diagram is a set of interrelated elements that interact at runtime to achieve a specific goal, each element has a dedicated role in this collaboration.
![Composite Structure Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/3a0c8831-6c67-4336-90ea-d376c8e8df03)

#### 7. Profile diagram:
-   Allows us to create domain and platform specific stereotypes and define relationships between them, we can create stereotypes by drawing shapes of stereotypes and linking them to composition or generalization through a resource oriented interface, we can also define and visualize stereotypes values.
![Profile Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/06ad4b13-dbb3-4c19-890b-d78d8d5a717c)

---

### Class Diagram
#### Class Diagram:
- Illustrates the structure of the system by describing classes, their attributes, methods and relationships between them.
- Let's remind what is a class, in a nutshell class is a template for creating objects
- (+ and - before the class attributes these are the access modifiers or class visibility notation).

#### There are 3 different levels of specifications we can use:
##### 1. Conceptual Perspective -> Is when class diagrams are interpreted as describing entities of the real world, in conceptual we can construct a diagram that represents the concepts in the domain, these concepts relate to classes that implement them, the conceptual perspective is considered language independent.
##### 2. Specification Perspective -> Is when diagrams are interpreted as describing abstractions of SW or components with specification and interfaces but without any reference to specific implementation.
##### 3. Implementation Perspective -> Is when diagrams are interpreted as a description of SW implementations in a particular technology or programming language.

#### Relationships between classes in UML(6 main types of notation that are most common):
##### 1. Association -> Similar to relationships connect objects, association connect classes.
##### 2. Inheritance(Generalization) -> It is a schematic representation of the relationship between the parent class and its descendants.
##### 3. Realization -> This refers to the relationships between an interface and objects that implement this interface.
##### 4. Dependency -> When an object of one class uses and object of another class in its method and this object is not stored in any field, it is a special case of association of two classes, changes in one class will inexorably entail changes in the other.
##### 5. Aggregation -> A special type between classes when one class is a composite part of another.
##### 6. Composition -> Is a type of aggregation but this time classes that form the aggregator class are destroyed when the aggregator class is destroyed.

---

### Component Diagram
Component Diagram:
- Used for modelling physical aspects of object oriented systems that are used for visualizing, defining and documenting component-based systems as well as construction executable systems using forward and reverse engineering.

- Component diagrams are essentially class diagrams that focus on system components that are often used to model the static implementation view of a system.

- Component diagram breaks down the system under development into various high levels of functionality, each component is responsible for one clear goal within the entire system and interacts with other essential elements only on a need to know basis, so how does it work, data for example account and inspection id flows into the component through the port on the right and gets converted to a format that internal components can utilize interfaces on the right are known as required interfaces they represent the services the component needs to fulfill its responsibilities, data then passes through various connections and other components before it is output through the ports on the left.

- Those interfaces on the left are also known as provided interfaces and other components of the system can interact with them in order to take advantage of the output results of the component it is important to note that the internal components are surrounded by a large box which can represent the system as a whole in that case there will be no component symbol in the upper right corner or a subsystem or component of the overall system in this case the box itself is a component.

- A component is a modular part of a system that encapsulates its content, in UML 2.0 a component is drawn as a rectangle with optional compartments arranged vertically the following example shows two types of interface components.

1. Provided interface is drawn with a complete circle at its end and represents the interface that the component provides to the system, this symbol is known by the nickname lollipop and is a shorthand for a realization relationship of an interface classifier.

2. Required interface is indicated by a semicircle at the end and as you might guess it indicates the interface that a component needs to perform a task, in both cases the interface's name is placed next to the interface symbol.

- Subsystem classifier is a special kind of a component classifier because of this the subsystem notation element inherits the same rules as the component notation element, the only difference is that the subsystem element is marked with the keyword subsystem instead of the keyword component.

- ports are depicted with a square drawn along the edge of the system or a component, a port is mainly used to expose required and provided component interfaces.

- Graphically a component diagram resembles a system of components and logical nodes connecting them, in general some relationships might already be familiar to you as they are widely used in the class diagram but there are some unique ones.

1. Association -> defines the semantic relationship that can occur between typed instances, it is drawn as a straight line connecting two or more components of the system.

2. Composition -> composite aggregation is a strong form of aggregation that requires a part instance to be included in at most one composite at a time, if a composite is deleted all its parts are usually deleted with it.

3. Aggregation -> very similar to composition but in this case the child component can exist on its own even without being a part of the aggregator class, aggregation is drawn with a hollow diamond pointing towards the aggregator.

4. Constraint -> A Condition or Restriction expressed as a text in a natural language or in a machine-readable language in order to declare some of the semantics of an element dependency, dependency is a relationship where an element or set of elements require other elements for their specification or implementation, this means that the full semantics of the dependent elements are either semantically or structurally dependent on the definition of the supplier element or elements.

5. Inheritance or Generalization -> is a taxonomic relationship between a more general classifier and a more specific classifier, each instance of a specific classifier is also an indirect instance of the general classifier thus the specific classifier inherits the features of the more general classifier.

Let's have a look at some use cases:(java.jpg and c++)
- Consider a typical step-by-step process of modeling a source code that shows how we would approach creating a component diagram for a program, first of all with the help of forward or reverse engineering we determine the set of source code files of interest and model them as components for larger systems, we can use entire packages to display groups of files don't forget about tags that indicate the version of the source code file in use you can also specify its author or the date and time of the last change, we can also model the compilation dependencies between these files using dependencies.

Let's have a look at a step-by-step process for modeling an executable release:(exe release)
- First we define a set of components that we want to model typically this will include some or even all components that are on a single node or a distributed system of these sets of components across all nodes in the model it's worth considering the type of each component in this set for most systems there is only a small number of different kinds of components such as executable files libraries tables other files and documents we can also use UML extensibility mechanisms to provide visual cues for these types it is important not to forget to consider the relationship of each element in the system with its neighbours most often this will be associated with interfaces that are exported or realized by certain components and then imported or used by others but if we want our model to be at a higher level of abstraction then we can exclude these intermediate interfaces that hold such relations together showing only dependencies among the components themselves.

Finally in modeling a physical database:(database.jpg)
- First we identify the classes that will represent our logical database schema then we choose a mapping strategy for mapping these classes to tables, it is also worth taking into the physical distribution of our database because the mapping strategy will also be affected by the location in which you want to store data after the databases deployment. 
To visualize, define, build and document our mapping we need to create a component diagram that will contain these components as tables.
