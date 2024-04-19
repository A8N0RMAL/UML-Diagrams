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
![UML Class Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/de3446bb-5daf-4cd4-9c0d-97f24c5074f4)
#### Class Diagram:
- Illustrates the structure of the system by describing classes, their attributes, methods and relationships between them.
- Let's remind what is a class, in a nutshell class is a template for creating objects
- (+ and - before the class attributes these are the access modifiers or class visibility notation).
![0](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/b826b62e-e5c4-4b26-a76b-120490d60954)
![1](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/dd29e5ec-fc0c-4a89-b446-1337f4a48aec)

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

---

### Deployment Diagram
- Deployment diagram illustrates the configuration of runtime processing nodes and the components that live on them.
- Deployment diagram is a kind of a structural diagram used in modeling the physical aspects of an object-oriented system.
- They're often used to simulate a static representation of a system deployment for example topology of the hardware.
- Deployment diagrams show the structure of the runtime system they model the elements of physical hardware and the ways of communicating between them.
- They can be used to plan a system architecture they can also be useful for documenting the deployment of software components or nodes.
![1](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/7058c501-29b3-48c7-b2f7-10ec1a658653)

- These diagrams are important for visualizing defining and documenting embedded client server and distributed systems as well as managing runtime systems through forward or reverse engineering.
![2](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/e25a70de-7ae5-4e74-b2ce-ab93f2870402)

- A deployment diagram is just a special kind of a class diagram that focuses on system nodes graphically deployment diagram looks like a collection of vertices and arcs.
![3](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/47b204b3-8c55-40df-8a16-a19c96d8a282)

- Deployment diagrams usually contain the following notation : a 3d box represents -> a node either software or hardware.
![4](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/865b2672-64dc-4067-bd3b-a3c51ae3826b)

- Hardware node -> may be marked with a stereotype notation.
![5](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/3aa7ff13-247c-47e1-a7e7-29c55e55d283)

- Connections between nodes are represented with a line with optional stereotype notation.
![6](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/992ec5be-ace5-4605-bb6d-90129d256262)

- Nodes can reside within other nodes the diagram can also reflect dependencies associations as well as nodes or restrictions.
![7](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/01ae25ab-c575-4030-abf1-0a982f5bf9e8)

#### These are the steps that are normally taken to model an embedded system :
1. identify devices and nodes that are unique to your system.
![8](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/cc9e5de8-4300-4a94-bf22-cb70bd97ea8f)

2. Provide visual cues especially for unusual devices using uml extensibility mechanisms to identify system stereotypes with matching icons you will also want to distinguish between processes that contain software components and devices that at this level of abstraction do not directly contain software.
![9](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/505bf2c1-a524-46f1-a530-385b1c6c41bf)

3. Model the relationships between these processors and devices in a deployment diagram similarly specify the relationships between the components in the implementation view of your system and the nodes in the deployment view of your system.
![10](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/c404c977-cb5d-4bad-a5f2-336a3af3f8a3)

4. If necessary expand the capabilities of any smart devices by modeling their structure with a more detailed deployment scheme.
![11](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/cd266cd8-3908-4afa-9381-8e809c7e03a3)

#### Here are the steps for modeling a client server system :
1. Identify the nodes that represent the client and server processors of your system.
![12](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f00db202-e4c3-4385-bd42-184e48675bb4)

2. Highlight those devices that are related to the behavior of your system for example you can simulate special devices such as credit card readers icon readers and display devices other than monitors since placement of the latter in the system's hardware topology is likely to be of a great architectural
importance.
![13](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/6cc0291f-ce3f-4ccc-b9bc-c6645e061718)

3. Provide a visual cues for these processors and devices through stereotyping.
![14](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f1c5a626-2fef-4999-9844-c50f4baabccb)

4. Model the topology of these nodes in the deployment diagram similarly specify the relationships between the components in the implementation view of your system and the nodes in the deployment view of your system.
![15](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/ca56155e-1cbd-4915-875d-524152a845fc)

#### And here are the steps you will need to take when modeling a distributed system :

1. Identify the devices and processors of the system as for simpler client server systems.
![16](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/528f4a13-b655-434e-9a70-0b5082082738)

2. If you need to reason about the network performance or the impact of changes on this network be sure to simulate communication devices at a level of detail that is sufficient to conduct these estimates, pay particular attention to logical groups of nodes that you can specify with packages. 
![17](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/d019ec2f-4f71-441f-b9fa-cd1dc8df9399)

3. Where possible use tools that discover the topology of your system by walking your system's network.
![18](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/6a624c68-0cfd-49d0-8c47-aea28509312e)

4. If you need to focus on the dynamics of your system use the use case diagram to indicate the types of behavior you're interested in and expand this use cases with interaction diagrams.
![19](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/e8241fa7-e350-4ba3-84f2-ae76f17a3784)

5. When modeling a fully distributed system it is common to transform or represent the network itself as a node that is the internet lan or one might be depicted as nodes in the form of a single box rather than a combination of elements.
![20](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/60fb8913-42e0-4f4c-befc-8ffdb93f0455)

#### When you develop a deployment plan for your company you might discover that you don't know where to start and what to focus on the following checklist can give you some ideas for planning your deployment:
![21](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/ae620225-e618-4e17-af09-f869510a1bd0)

- How will your system be installed?
- Where the installation can possibly fail?
- How long can it take to install your system?
- What backups do you need before the installation?
- Will data conversion be necessary?
- How did you know that the installation was successful?
- If different versions of the system work simultaneously, how will you resolve the conflicts?
- What physical sites do you need to deploy and in what order?
- How will you train your support and operational staff?
- Will it be necessary to deploy a production support system so that support staff will use their own environment to model problems?
- How will you train your users?
- What documentation and in what formats and languages do your users, as well as support team and operation specialists need?
- How will documentation updates be deployed?
- What existing systems should the new system interact with or integrate?
- How reliable should the system be, will any additional equipment be required in the event of a system failure?
- What or who will connect or interact with the system, and how will they do it?
- What software, including the operating systems, and communication protocols, will the system use?
- What hardware and software will users interact directly with (PCs, network computers, browsers, etc.)?
- How will you control the system after deployment?
- How secure should the system be (does it need a firewall, physically safe equipment, etc.)?

---

### OBJECT Diagram
