# UML-Diagrams
## In this repo, I'll try to talk about UML diagrams
![UML Diagrams](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a0a50764-a982-4c36-99aa-434ebda5e81f)

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
![2](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a93c85f3-1bc4-4665-aa7d-37041df4959a)
![3](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/2df7c342-3da2-4df8-ac32-be1ab9773217)
![4](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/605d0fda-91ba-49d4-8ad5-2870e964d76b)

#### There are 3 different levels of specifications we can use:
##### 1. Conceptual Perspective -> Is when class diagrams are interpreted as describing entities of the real world, in conceptual we can construct a diagram that represents the concepts in the domain, these concepts relate to classes that implement them, the conceptual perspective is considered language independent.
![Conceptual Perspective](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/68f0ef0e-de6f-42e4-b638-98b8d43d15e8)
![Conceptual Perspective_](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/aed8cc47-3876-499f-89f8-ab78061ef2c7)

##### 2. Specification Perspective -> Is when diagrams are interpreted as describing abstractions of SW or components with specification and interfaces but without any reference to specific implementation.
![Specification Perspective](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/176bada4-23b6-49c5-a48a-bc175ac92849)
![Specification Perspective_](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/cdfa8b73-976f-47c3-9f14-ce9ad35fcafb)

##### 3. Implementation Perspective -> Is when diagrams are interpreted as a description of SW implementations in a particular technology or programming language.
![Implementation Perspective_](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/0f9108ff-fa7d-4b41-a268-865616757e73)
![Implementation Perspective](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/660dd836-9bee-4c8c-95f7-e97206625e1d)

#### Relationships between classes in UML(6 main types of notation that are most common):
![Relationships between classes in UML](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/b7743b86-2278-4b9f-8376-bdc716c600f7)
![Relationships between classes in UML 6](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/b09696d9-ccc2-4f23-9588-3fd502f4467a)

##### 1. Association -> Similar to relationships connect objects, association connect classes.
![Association](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f4864e85-a1ae-4312-852d-f5f1ebb468a3)

##### 2. Inheritance(Generalization) -> It is a schematic representation of the relationship between the parent class and its descendants.
![Inheritance](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/64110977-3bed-4200-ba5e-0bd7730c73b6)
![Inheritance_](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/93fdb852-d345-487e-aba9-30908722c232)

##### 3. Realization -> This refers to the relationships between an interface and objects that implement this interface.
![Realization](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/edfc0347-6dd2-4f4e-8dd9-f1cf2a82556e)

##### 4. Dependency -> When an object of one class uses and object of another class in its method and this object is not stored in any field, it is a special case of association of two classes, changes in one class will inexorably entail changes in the other.
![Dependency](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/ce24d0c6-d507-4ffd-bd34-3ac6a124b022)
![Dependency_](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/1d004f9b-91b2-4690-bed4-bbea75166ab2)
![Dependency__](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/c1fc5d7b-27b6-4c75-a09f-11a1906c5676)

##### 5. Aggregation -> A special type between classes when one class is a composite part of another.
![Aggregation](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/87f514d6-2a14-4d34-88fb-3c17a6ebb1e0)
![Aggregation_](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/096cbb35-f15b-47fa-863a-c00e3d2352e3)
![Aggregation__](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f537a3c6-cf29-4925-a731-ead50f9d0e01)

##### 6. Composition -> Is a type of aggregation but this time classes that form the aggregator class are destroyed when the aggregator class is destroyed.
![Composition](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/46e98d53-0932-4f87-bcef-1d13794245d0)
![Composition_](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/315e6d0d-442b-4f8a-872d-4015ebd4c74a)

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
![Deployment Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/c655713e-5d41-4490-bdb9-d2cbc322e1c7)

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
![UML Object Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/d6ab9c8d-3e9e-4f96-bb54-0335eb0a6731)

- Uml objectn diagram is an instance of a class diagram.
- It captures a snapshot of the detailed state of the system objects and their relationship at a specific pointin time. 
- It can be considered as a special case of a class diagram or a communication diagram.
- The use of the object diagrams is quite limited and mainly comes down to demonstrating examples of data structures.
- During the project analysis phase you can create a class diagram to describe the structure of the system and then create a set of object diagrams as test cases to verify the accuracy and completeness of the class diagram. 
![1](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/c8569288-47c5-4fad-bb9d-def0d85d28f5)
---
- Prior to creating a class diagram you can create an object diagram to find out facts about specific model elements and their relationships or to illustrate specific examples of the required classifiers.
![2](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/6d31d46a-2c13-4f9d-95ea-2fc058b81c62)
 ---
- The object diagram illustrates the relation between the instantiated classes and the defined class as well as the relationship between the objects in the model system at a fixed point in time.
- It's fair to say that it's a snapshot of your system at a certain point in time which will depict system objects in a certain state which will directly represent real instances and prototypes these diagrams are useful for example when you want to depict a small part of a large system.
- In which case the use of a class diagram would be an overkill as well as in case you want to model recursive relationships or to study the behavior of a system at a particular moment in time.
![3](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a7605d52-ace2-40fb-a9e9-36d4744ecf4e)
---
- The best way to show what an object diagram looks like is to show an object diagram derived from the corresponding class diagram. 
- This humble class diagram illustrates a simple example in which a department depicted consisting of many other departments and this object diagram is nothing more than a detailed representation of the previous class diagram with examples and links.
![4](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/e5f57cdd-7d32-4db9-9c61-1981efc14e9e)
![5](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4ffb3492-4e51-44ac-b67d-fc30b0af45a1)
---
- Let's walk through the basic notation of an object diagram. 
- Each object is drawn as a rectangle.
- The name of the object and its class are usually underlined and separated with a column.
- The name of the object is on the left the name of the class is on the right.
![6](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/d51e5e7f-9377-4913-a9d0-0061f162aa57)
---
- The attributes of an object are listed in a separate compartment under the name of the class or object and must indicate the values assigned to them.
![7](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/392cc191-990e-4c0d-98b5-968c331c2cb3)
---
- Links in general are varieties of associations betweenclasses and are discussed in detail above about class diagrams.
 ![8](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/27170998-96c8-4e38-964d-28b98e560419)
---
 - Since uml object diagrams provide a snapshot of instances and the relationships between them in the system.
 - We can create object diagrams by instantiating the model elements on class diagrams, deployment diagrams, components and use case diagrams. 
![9](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/b8af5900-df17-4dac-b420-312467f277ad)
---
- For example we can represent a part of the company's structure with the object diagram. 
- A communication diagram without any messages can also be called an object diagram and relationships between objects can be called links.
![10](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/53b8d679-31a0-4eea-8dd2-05328922ee8a)
---
 - An object diagram must be a valid instance of a static class diagram.
 - Objects must have classes and relationships between objects must be the instances of associations between classes, that is relationships between objects will essentially be similar to relationships between classes.
![11](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/9ded606e-e8d0-4a69-a4a3-0fa91a09ce0c)
---
- Let's look at some steps for modeling object structures.
- First of all define the mechanism that you would like to model this mechanism can represent some function or behavior of the part of the system that you are modeling which is basically the result of the interactions between classes interfaces and other elements, therefore it is necessary to identify the classes interfaces and elements for each mechanism that participate in this model and determine the relationships between them.
![12](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/ef6c12a5-4014-4934-8979-607a10003b90)
---
- After that consider for example one scenario that walks through this mechanism and at a certain point in time  renders each object that participates in the mechanism, expand the state and attribute values of each such object to understand this scenario.
![13](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/70c2f477-4406-4501-bf5b-134a5e0f426c)
---
- A kind of analogy would be the mechanical clocks imagine it is noon and we pretend to freeze the time to examine the elements of the mechanism, what do they do where do the hour and minute, hands point to which gears and sprockets are involved and so on.
![14](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4f8d515b-d3c9-4d5b-b983-b9b4a7ae78d9)
---
- let's have a look at another example robot moving behavior.
![15](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/6cd36d74-8773-4e53-b5e6-a1e20aa8458a)
---
- here one object represents the robot itself r is an instance of a robot and r is currently in a state marked moving this object has a link to w.
![16](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/1191effc-ec4b-419c-8325-f9e6859157cd)
---
- W is an instance of the world which is an abstraction of a model of the world for the robot this object is linked with several objects consisting of instances of the element that represents entities that the robot has identified but has not yet assigned in its world view. 
![17](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/58a85cf7-b4b7-484d-bfcd-dc57a5ce0abc)
---
- These elements are marked as part of the global state of the robot. 
![18](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/ed87c3e0-258d-4e18-8bc5-e9ce0e199d05)
---
- Currently w is associated with two instances of area.
![19](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4775f7ea-32fc-464e-99ef-d2918f6a9bee)
---
- One of them a2 is shown with its own links to the three wall objects and one door object. 
![20](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/8a6d7e30-1d4e-4d24-9f42-02c8ea057df9)
---
- Each of these walls has an attribute width and each wall is linked with neighboring walls. 
- By and large this diagram graphically shows how the robot recognizes this enclosed area which has walls on three sides and a door on the fourth.
![21](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/cb6c3d20-1c42-4523-8178-01ee7ecb25da)
---
- The next example is deriving an object structure similar to communication diagram, in addition to displaying the state of objects at a certain point in time, an object diagram can also be used for example to represent the occurrences of interactions between classes during the runtime.
![22](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/bee21b7b-c20c-437c-9acf-f68a9fb04f6b)

---

### PACKAGE Diagram
![UML Package Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/33af2f63-7645-4977-a921-79bdf0ac2f10)
- Uml package diagram is a kind of a structural diagram that shows the location and organization of model elements in a medium scale and large scale projects.
- A package diagram can display both this structure and the dependencies between subsystems or modules illustrating various kinds of systems such as a layered application for example.
![1](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/100c9955-f68f-4c17-bd0d-5d16d1f57f1b)
---
- If the system is of a significant size it should be divided into smaller subsystems, each with its own class diagram.
- In uml notation these partitions or subsystems are called packages.
- A package is a group of elements of the model and it can also be used in other uml diagrams.
- Packages themselves can be nested in other packages which is basically a uml version of folders.
![2](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/60a9f0ae-aef4-41bf-ab09-dd906a6fdc91)
---
- Package diagrams are usually used when it is necessary to group a related uml elements and determine the scope of their names or when you need to provide a way to visualize dependencies between parts of the system. as well as to provide some support for analysis or determine the compilation order.
- Package diagrams are used to structure high-level system elements.
![3](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/8f2e8918-896c-4536-b30a-adcc4b8be8d9)
---
- When modeling a package diagram you should bear in mind that a package is a uml mechanism for grouping elements including other packages.
![4](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/3dc49178-3910-4bc9-b5ea-aea02530c66b)
---
- Each package has its own namespace in which all names must be unique.
![5](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/55172756-750f-4be2-a1fe-88e6f294dec1)
---
- Each model element belongs to a single package.
![6](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/c4a780b8-ce7e-4a4e-a744-895a892ff410)
---
- Packages form a hierarchy, packages are displayed as rectangles with small tabs at the top.
- Package's name is normally written on its tab or dedicated rectangle namespace.
![7](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4b00b9ea-a79f-43d0-8338-451437b9b21d)
---
- Dotted lines with arrows depict dependencies.
- One package is said to be dependent on another if changes in that other package can cause changes in the first one as well.
![8](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/85f14807-6358-4731-9106-7b12b8045e9a)
---
- A system could be depicted in the form of a package with the stereotype system and it represents all the elements of the model that are relevant to a particular project.
- You can also break the system apart into business systems and application systems when creating more detailed models to make them smaller but more efficient.
- Package diagram can also display the logical architecture of a system.
![9](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/b7a92e35-7500-4f4e-9309-c1097a689e6e)
---
- A subsystem is a group of model elements that are part of some larger system.
- Since the system or subsystem is a stereotypical package it has all the properties of the package and it also follows the rules of the package and all those model elements that are contained inside the system or the subsystem will also belong to the package and follow the same rules.
![10](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/8b9ce8d9-c36b-4c4f-98de-c46dbebe81b5)
---
#### Now what does this word stereotype actually mean: 
- stereotype is a high level classification of an object that gives some idea of what the object is.
- Classes can be grouped by stereotypes their names are written inside the angle brackets above the class name.
- Stereotype allows us to extend uml to fit our modeling needs more specifically.
- In other words stereotyping a uml element makes it act as something that has specific properties.
![11](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/944d6cb0-d96d-43a2-b656-25186a5cdd51)
---
- Elements in packages may also have different visibility of elements of other packages and this also needs to be taken into the count during the process of modeling of a system.
- Elements of a package with public visibility are available outside the package, while elements with private visibility are available only for other elements within the package.
![12](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/5db7fb6b-024f-4f84-9e0c-415fa95f00d8)
---
- In uml public protected and private visibilities correspond to a class that is a public, protected or private.
- A public element is visible to all elements that can access the content of the namespace to which it belongs.
- Public visibility is represented by the plus sign.
- A protected element is visible to elements related to generalization relationship to the namespace that owns it.
- Protected visibility is represented by the hash sign.
- A package element is owned by a namespace that is not a package and is visible to all elements that are in the same package.
- Package visibility is marked by a tilde.
- A private element is visible only inside the namespace that owns it.
- Private visibility is represented by the minus sign.
![13](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/eff0e42a-153b-47db-af3f-4681bcef3d2b)
---
#### Let's look at the types of dependency relationships represented by the stereotypes: 
- The element in the client package uses the public element in the supplier package the client depends on the supplier.
- If the package dependency is shown without a stereotype then it should be marked with a use stereotype.
![14](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/00c2b3cf-45ef-4e10-8a68-c200c4898e04)
---
- Public elements of the supplier namespace are added as public elements to the client namespace.
- Elements in the client's namespace can access all public elements in the supplier namespace using unqualified names.
![15](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/d10f846d-23bc-45b4-834d-3250a3cd0874)
---
- Public supplier namespace elements are added as private elements to the client namespace.
- Elements in the client namespace can access all public elements in the supplier namespace using unqualified names.
![16](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/03e99452-5925-4986-bdba-ad9325e50ad8)
---
- Trace normally represents a historical development of one element into another more developed version.
- Usually this is the relationship between models not elements.
![17](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/ed8f5f83-8d4a-46ed-a10f-fa85d06e26fb)
---
- Public elements of the supplier package are combined merge with the client package elements.
![18](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/aef63ef7-1cb9-4295-8a4d-0f1ab27a7b0c)
---
- The dependency is used only in metamodeling and the chance of encountering it in the modern object oriented analysis and design is even less than encountering an elephant in the central london.
![19](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4dd6c4c9-0851-4e1d-80ef-a1865892b5e5)
---
- Next we will analyze an example diagram of the order tracking scenario for an online store:
![20](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/d9f035a9-4afe-491f-be28-3c8a7105bd89)
---
- In this diagram the track order module is responsible for providing tracking information for product ordered by our customers.
- The types of customers are encrypted inside the tracking number.
- Truck order module refers to the system and updates the current delivery status for the customer.
![21](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/9d41b3e5-ec28-4d72-ae22-8769ad6c3cd6)
---
- Based on the description of the project first we must determine what packages will be present in the system and figure out the relationships between them.
#### So how to determine which packages do we need to model the system:
- Suppose that we have a module that tracks an order it could be some sort of a tracking module and in order to perform its duty it must communicate with another module in order to figure out the details of the order.
- Let's call this module order details. after receiving the details of the order it needs to know the shipping details, so let's introduce a shipping module.
- And now let's determine the dependencies between them.
- The track order module must receive the order details from the order details module.
- In response order details module requires to know the information provided by the client.
- Two modules communicate with each other which provides the access dual dependency.
- To learn the shipping information the shipping module can import the truck or the module to make the navigation easier.
- Finally the truck order is dependent on the ui framework and this completes our order processing subsystem design.
![22](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/693ef202-240a-408b-82d9-e2c9ddf2e24b)
---
### COMPOSITE Diagram
![UML Composite Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a06376f7-bccc-4c53-b711-b0a5962b536c)

---
- Composite structure diagram contains classes interfaces packages and their relationships and it provides a logical representation of a software system or its part.
- This diagram is one of the new artifacts added in uml 2.0 and it shows the internal structure including parts and connectors of a structured classifier or collaboration.
- The composite structure diagram plays a role similar to the class diagram but allows you to delve into details of the internal structure of multiple classes and show the interactions between them.
- You can graphically represent inner classes and parts and show associations both between classes and within them.
![1](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/36527a2a-1632-4ee3-88f1-05265a02085e)
---
- In other words composite structure diagrams show the internal parts of a class.
- The part's name is usually constructed with parts name then column then parts type with multiplicity stated inside the square brackets.
- Aggregated classes are parts of a class but parts are not necessarily classes.
- A part is any element that is used to make up the containing class.
![2](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/3f870632-7ab3-4916-a5ed-f3910779b642)
---
- Suppose we are modeling a system for an online store in which customers can join a loyalty program that provides them with some benefits discounted shipping for example.
- In order to allow such a feature we expanded the customer object so now we have a regular customer and a member of our loyalty program.
![3](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/745c2257-5ccf-4873-9d43-3fbc5d9772f9)
---
- let's start by simulating an online store using a class diagram.
- We have a class for item which can be aggregated by the order class which is composed by the customer class which itself is composed by the store manager class.
- we have many objects that end up within other objects. 
- On the diagram everything looks as if it ends up inside the store manager, so we can create a composite structure diagram to clearly demonstrate what this manager consists of.
![4](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/15d20440-e673-46e7-924c-1b22f875e0a6)
---
- Composite structure diagram shows us a clear picture of the store manager from its own point of view instead of this system as a whole.
![5](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/572a2aaa-5938-41c0-9d5f-a2eade24ee47)
---
- Store manager directly contains two types of objects customer and item as indicated by th two composition arrows in the class diagram.
- The composite structure diagram here shows the inclusion of customer subtypes explicitly.
- Please note that the type of both parts is declared as customer because the store treats both objects as customer objects.
![6](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/9a03f7aa-0914-441d-a214-2828bee7b354)
---
- We also see a connector that shows the relationship between item and order.
![7](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f99f7507-1c7b-43a7-bce7-df7469b277b3)
---
- Order is not contained directly in the store manager class, but we can show relationships with parts nested in the object that it aggregates.
![8](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f908db7e-4d4d-4c46-b262-e40b890f8e7e)
---
- The question is do these two diagrams essentially describe the same thing or have the same meaning?
![9](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/22bd1f40-908b-48e1-a012-6d91469962a0)
---
- Well in the class diagram the relationship between the description and pricing is ambiguous strictly speaking there are not exactly the same.
- The class diagram shows that description will have a reference to the pricing object, but this does not specify whether the link between the two objects is contained inside the item explicitly.
![10](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/6df43adc-d6d2-4a2e-8aa5-2a645e6bac32)
---
- If we use a composite structure diagram the relationship between the description and pricing objects becomes obvious, specific implementations of an object's activity can be clearly modeled.
![11](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/306015a8-cab0-4d1c-8199-ea4e7546ad96)
---
- Composite structure diagrams are good for describing aggregation, but in this case models will also need to contain references to objects outside the class that we are modeling.
![12](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/665b7842-83a5-4666-90dd-7b6045277c64)
---
- References to external objects are shown with a dashed rectangle, even if they refer to an object outside the class the link itself is inside the model class and it is an important step in demonstrating its implementation.
![13](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/8032220f-12f7-45fd-a9c5-504a111ac2a0)
---
- The key object of composite structure specified in the uml 2.0 are structured classifiers parts, ports, connectors and collaborations.
- Collaboration describes the structure of collaborating parts and their roles in the interaction and is used when we want to determine only those roles and connections that are necessary to achieve a specific goal of such collaboration, for example the purpose of a collaboration may be to define the roles of components of a classifier.
- Having identified the main roles the collaboration simplifies the structure and clarifies the behavior of elements in the model itself.  
- In this example the wheels and the engine are parts of the collaboration and front axle and rear axle are connectors.
- A car is a composite structure that shows parts and connections between parts.
![14](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/e1e8c061-3ae3-4783-9f96-355f087fa446)
---
- A part is a diagram element that represents a set of one or more instances owned by a structured classifier.
- A part describes the role of the instance in the classifier.
- We can create parts in the structure compartment of the classifier and in several uml diagrams such as composite structure diagram, class diagram object diagram, component diagram, deployment diagram and package diagram.
![15](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/e3302527-433c-48fa-a54b-f18208da9375)
---
- A port defines the point of interaction between the classifier instance and its environment or between the behavior of the classifier and its internal parts.
![16](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4bf2edd1-9d61-411c-a07a-8ee58c781dfe)
---
- Composite structure diagram supports the notation for provided and required interfaces.
- If necessary interfaces can be shown or hidden in the diagram.
![17](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f88b0cc4-5b62-4177-aba1-3aa287523172)
---
- A line that represents the relationships within the model is called a connector.
- when modeling the internal structure of a classifier we can use a connector to indicate a link between two or more instances of a part or a port.
- A connector defines the relationships between the objects or instances that are associated with the roles in the same structured classifier and define the communication between those roles.
![18](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/b5e4c6ac-dc7f-4a07-a753-bb8151c19fb4)
---
- As an example here's a simplified composite structured diagram for a computer system which includes the following components power supply unit, hard disk, dvd, motherboard, central processing unit and memory module.
![19](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/fa36aa15-f2f9-4aea-8777-cbfe95925427)
![20](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/00a0d01f-ba36-4d15-b616-8243b8b16414)
---
### PROFILE Diagram
![UML Profile Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/dce43077-45ed-4265-9dba-438abe45d55c)

---
- Profile diagram is one of the uml structural diagrams it is well known for providing a general extension mechanism for customizing uml models for specific domains and platforms.
- Profiles are defined using stereotypes tag value definitions and constraints that apply to specific elements of the model, such as classes, attributes, operations and actions.
- A profile is a set of extensions that jointly configure uml for a specific domain for example aerospace medical or financial or specific platforms such as j2ee or .net .
![1](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/b400ee0b-39db-4b29-9c5a-ba1c07a14a21)

---
- Profile diagrams have three major types of extension mechanisms stereotypes, tags and constraints.
![2](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/3c6f79a7-8486-4d82-83a7-3349f8d47291)

---
- Stereotypes allow us to increase the vocabulary of uml you can add and create new model elements derive from the existing ones but having more specific properties that are suitable for a specific domain.
- Stereotypes are used to introduce new building blocks that speak the language of your domain and look primitive, this allows you to introduce new graphical symbols.
- For example when modelling a network you may need annotation for router, switch, hub etc..., a stereotype allows you to make these things appear as primitive as possible.
![3](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4013ff80-eb98-41dc-829c-c8ca8ba4a75c)

---
- Why would you need that?
- For example a box labeled with a stereotype button makes more sense than a picture of green rooster that was added to the schema just because someone ran out of meaningful symbols.
![4](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/446362b8-79a5-497d-b82c-142751c9146a)

---
- Tags are used to extend the properties of uml so you can add additional information to the specification of a model element, this allows you to specify keyword value pairs of a model where keywords are attributes tagged values are graphically displayed as strings enclosed by the curly braces.
![5](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/9ff86375-3e93-4391-9705-6fb33187b51b)

---
- For example imagine a team that is responsible for assembling testing and deploying a system for them it is necessary to monitor the version and test results of the main subsystem and this is where tags come in handy.
![6](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a1b332e2-7573-4bd4-b393-9cdd56396c32)

---
- Tags can also be useful to add properties to the model such as code generation, version control, configuration management and authorship.
![7](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/c2b62393-8932-4653-9f13-560a03f90695)

---
- Constraints are properties used for semantics or conditions that should always be satisfied they allow us to expand the semantics of the uml building blocks by adding new protocols.
- A constraint is displayed as a string enclosed by the square brackets next to the corresponding element.
![8](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f818e9e7-a488-45e7-b0a6-9998b24bc08d)

---
- For example when developing a real-time system it is necessary to supplement the model with some necessary information such as response time for instance.
- Constraints may be placed on attributes, derived attributes and associations.
- They can also be attached to one or more model elements shown as a node.
![9](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/1d2a3cff-e46e-4b11-b52b-588178a5448f)

---
- As an alternative to creating a new matter model you can also expand and modify the uml metamodel according to your requirements, in uml this is called a lightweight extension based on stereotypes and profiles.
![10](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/76a7c8cb-ed30-4693-a44a-0abda155082d)

---
- A uml profile can be defined in one of the following ways creation of a new meta-model, extension and modification of the uml metamodel, extension of the uml meta model with language inherent mechanisms.
- Uml 2.0 allows you to use arbitrary data structures for extended elements which means that wider and more accurate extensions of the model are now possible.
- The profile mechanism is not a first class extension mechanism because it does not allow changing existing or creating new meta models profile only allows adaptation or customization of an existing meta model.
- In uml 2.0 or above profiles can also be dynamically combined so that multiple profiles can be applied on the same model at the same time.
![11](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4c578d16-81da-478e-957e-e2053d1ae7cf)

---
- A stereotype can extend from one or more meta classes such extension is depicted as an arrow with a continuou align and filled arrowhead that goes in the direction from the stereotype to the meta class.
![12](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a2e56e5c-dff7-4ddc-9541-2766e38205be)

---
- Stereotypes can be presented in the form of text or graphics the normal class box can also be replaced by the icon.
- For example people often use these three stereotype class representations to model the mvc software infrastructure.
![13](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4eb4e539-14ca-4d91-aa2f-d8169662af74)

---
- To use stereotypes in a specific application you must first integrate a profile containing stereotypes, you do this with a dashed arrow, its open arrowhead is pointing away from the application package towards the profile.
- This arrow is marked with a keyword apply a profile is applied to another package to makestereotypes in the profile available for this package.
- This diagram shows the network telecommunications and software profiles that apply to the it company suite.
![14](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/ff2b4f78-3eb9-4638-b7bd-2ef99089e693)
---
- In this diagram we define the ejb profile as a package the bean itself expands from the component metamodel as an abstract bean an abstract bean can be instantiated as an entity bean or session bean ejb has two types of remote and home interfaces ejb also contains a special kind of an artifact called a jar file for storing a collection of java code.
![15](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/fe86f5f3-8209-4592-bd4f-0b16982e018c)
---
### USE-CASE Diagram
![Use Case Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a98a871c-a87a-49f3-824c-82cb5d061298)

---
- Use case diagrams are fairly simple they summarize some of the relationships between use cases, actors and systems.
- But they don't show the order in which steps to achieve the goals of each use case are taken.
- They usually contain only a few simple figures, therefore if you have more than 20 use cases you are probably using the diagram incorrectly.
- There are many different uml diagrams that serve various purposes very often it is possible to describe the details of a system using other uml diagrams and link them together with use cases because use cases represent only the functional requirements of the system.
![1](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/7d5d679e-69fd-400a-b199-d9ee962fdf3e)

---
- Other requirements such as business rules,  quality of service requirements and implementation restrictions must be presented separately again with othe uml diagrams.
![2](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4625287c-11a0-4152-9373-4a632dc99e13)

---
- Use case diagrams are usually constructed at an early stage of development and are often used for the following purposes:
1. To specify a system context.
2. To capture system requirements.
3. To validate system architecture.
4. To drive implementation and generate test cases.
- And usually all this is developed by analysts together with domain experts.
![3](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/e4dce8fd-015e-43d4-b1dd-6a579de05c05)

---
- So what does the use case diagram consists of?
- Actor: in a broad sense one who interacts with the system and in most cases one who creates a use case.
- Actor is usually drawn as a little genderless humanoid with a name on it.
![4](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a697c11f-da0b-4e29-b881-99f910e0f922)

---
- Actor plays a role in the business process quite similar to the concept of a user, but the user and this is important can play different roles.
- For instance a professor can be a lecturer at the uni as well as a scientist in some kind of a research lab, so in this case the professor plays two roles in two different systems.
![5](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/c1810b85-76b5-4427-b336-5a132abe9f4d)

---
- Actor triggers use cases in other words actors interaction with the system and how the system reacts to those interactions form the use case.
- Actor also has some expectations from interactions with the system, if we expect one thing but get something completely different then the system function responsible for the use case may have been either improperly modeled or improperly implemented.
![6](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/7e508805-3efd-4d50-b2e9-ad17a8e7d578)

---
- Use case: it is a system function or a process that can be either automatic or manual.
![7](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/e0c65106-51a4-498b-8880-38a7167c74f5)

---
- The name is usually constructed from a combination of verb and a noun or phrases that guide to do something.
- Each actor must be associated with a use case while some use cases might not be associated with actors.
- Use cases determine the expected behavior that is what should happen but they don't describe how to make this happen.
- Use cases can be indicated in text or graphic form.
- For example in the form of a use case diagram.
- The main point of modeling the use cases is to help us to design the system from the perspective of the end user by indicating all possible actions of the system that may be externally visible.
![8](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/32841078-deea-49e2-acd1-fe2360bc473e)

---
- Communication link: actors can be connected with use cases via associations indicating that the actor and the use case communicate with each other through messages.
- This is graphically shown with a solid line.
![9](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/d24fbf1b-e191-4029-97d1-967ba21266f3)

---
- System boundaries: for large and complex systems each module may be the boundary of the system but potentially it may be the entire system.
- For instance if we'll have a look at an ERP system each one of the modules such as personnel payroll or accounting can form a system boundary for use cases specific to each of these business functions, the entire system can span through all of these modules displaying the overall boundary of the system.
![10](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/88c5f7c5-2e2e-4535-8641-a2128935ae6b)

---
- Use cases form various kinds of relationships.
- The duty of defining the relationships between two use cases falls on the shoulders of software analysts of the use case diagram.
- Reusing an existing use case with other types of relationships reduces the overall effort required to develop a system.
![11](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/360beb61-80cd-493c-9267-eefc2a2a1bc7)

---
- Let's look at the main relationships between use cases.
- Use case diagram illustrates a set of use cases for the system, an example subjects and relationships between subjects and use cases.
![12](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/0e42d4ff-0b9a-4650-8f63-8fdfadc9785c)

---
- Extends: indicates that for example use case invalid password may include under the conditions specified in the extension,  the behavior specified in the base use case login into account.
- Imagine that we have a use case that describes the interaction of an actor with an account for example the possibility of a login,  the basic use case is extended by two other use cases for example the already mentioned invalid password in which case the system will react in one way and on the contrary correct password in which case the system will most likely react differently.
- Extensions are important because they show additional functionality or system behavior.
- This type of relationship is used to include optional behavior of the use case that extends the base use case.
![13](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/2ebe3c0b-1d1d-4060-b889-20eb9e73530a)

---
- In our example the student requests a schedule and this requires the extension of the base use case request schedule with the use case search.
![14](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/b75255d5-eecb-4719-9fb6-775ed9e9776e)

---
- When one use case is shown using the functionality of another use case the relationship between them is indicated by their include stereotype.
- This type of relationship means that an instance of the base use case will include the behavior as specified in the child use case and it is indicated by a dashed arrow with its tip pointing to the child use case.
![15](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/e8e5c9e2-9230-494f-a1ab-b74f2ab1d290)

---
- Include adds additional functionality not specified in the base use case and is used to add general behavior from the included use case to the basis case in order to support the re-usage of the common behavior.
![16](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/a9ac4bb8-3f3b-448f-b285-2a07ec15b306)

---
- Generalization or inheritance: this is a parent-child relationship between use cases where the child use case is an extension of its parent use case generalization is depicted by a solid line with a triangular arrowhead pointing at the parent use case.
![17](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/aa342662-e5a4-48e7-b6ee-eeece26506d0)
![18](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/e4a60206-2694-4edf-97fb-4561585b72d6)
![19](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/fd79f90b-0ba4-4f10-aeff-f46a8465567c)

---
- In this type of relationship the child use case inherits the behavior and semantic component from the parent use case.
- A child use case may add or override the behavior of its parents.
- In this example the parent use case search has two children search by lecturer and search by date.
![20](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/948cb3cb-e728-4fdf-9c96-d3a00149b889)

---
- This use case diagram depicts a car sale system and you can probably notice that even such a complicated system can be described with just 10 use cases.
- Here you can observe extensions, inclusions and associations that connect actors with use cases.
![21](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/3a750be7-1d39-4e88-87da-ad70d46be2a5)

---
- Now a couple of tips to model a use case diagram more efficiently in case you will decide to do so in your project:
1. Always structure and organize a use case diagram from the perspective of actors.
2. Use cases should start off simple and at the highest view possible only then we can move towards refinement and high digitalization.
3. Use case diagrams are based on functionality and therefore should focus on what and not on the how.
![22](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/dcfb2647-f370-4250-b499-b86de48ac127)

---
### ACTIVITY Diagram
- Activity diagram is another important uml behavioral diagram used to describe the dynamic aspects of a system.
- Activity diagram is essentially an extended version of a flowchart that models the transition from one activity to another and it shows how system activities are coordinated to provide a service that can be at a different level of abstraction.
![UML Activity Diagram](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f6d85a4b-8ae1-4534-a07c-3c518bd6a92d)

---
- first of all let's go over the basic notation of the elements in the diagram and move on to the examples.
![1](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/cdf3f8af-716c-4948-bf43-335429f1b05d)

---
- initial node: it starts the flow when the activity is called from the outside.
![2](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/19d6e4a7-5698-4494-961d-0d83c3d733b5)

---
- control flow: it shows the sequence of execution of flow.
![3](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/694c2472-ba70-4ede-b9e5-22135303dd5d)

---
- action: a task to be performed.
![4](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/835b76fc-de74-4316-860a-4b714a37c40c)

---
- decision node: it represents a test condition to ensure that the control flow or object flow only goes down one path.
![5](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/5f3ce661-dd49-4672-b588-e04710dbce22)

---
- merge node: it merges the various threads that were created after the decision node.
![6](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/f30e348a-69d8-4ca7-a75a-bfbe648a7303)

---
- fork node: splits behavior into a set of parallel or concurrent flows of activities.
![7](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/d3b2fc12-71aa-4327-8506-ee2a4571c424)

---
- join node: it combines several parallel flows usually separated by a fork node.
![8](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/3ad3aaad-b66b-452b-83d3-16e127832b72)

---
- object represents an object in a thread that is being acted upon this is an optional element of the diagram but in some cases it is necessary to show the object initiating the execution of activities or being created as a result of some early initiation.
![9](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/23a121c3-5a97-4b36-9320-66b818a14d45)

---
- activity final node: it terminates all flows in an activity.
![10](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/7e3dd2ff-77f5-4000-8c55-0728213db649)

---
- swim lane: a way to group activities performed by the same actor on an activity diagram or simply group them in a single thread.
![11](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/6192f867-d2d5-402c-9619-9455cabdd5e8)

---
- the following steps of the activity diagram describe the workflow for creating a document in a text editor.
![12](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/4b3cbda9-ffa7-4817-af00-93203ae4aae9)

---
- open the text editor, create a document, save the document, enter the text.
- if graphics are necessary, import them into the document.
- if a table or a spreadsheet is necessary, create the required table or spreadsheet and import it into the document.
- save the document, print the document and exit the text editor.
- seems pretty logical and simple.
![13](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/1c80cb4a-d654-4531-a47a-d0a3893054ec)

---
- now let's imagine that we were given a task to simulate the order processing workflow using an activity diagram.
![14](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/2581dfc4-3dac-431d-8ec3-c8b176bdc0a8)

---
- the description of the process is as follows:
- once the order is received the activities split into two parallel flows, one fulfills and sends the order and the other process the invoices on the order processing side the delivery method is determined depending on the conditions of the order and transformed into action overnight delivery or regular delivery
- After sending the invoice for the goods the payment process side is going to receive payment, hopefully finally to parallel flows join and finalize the order processing.
![15](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/6ede358a-4c5b-4a6a-994f-8bf5accbcbfb)

---
- Another example is the process for student enrolment in programming courses.
![16](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/448fa300-e4dd-40c1-a882-d5cf51a3acf5)

---
- A student decides that he or she wants to become a super coding guru goes online discovers some online courses and commits to enroll.
![17](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/75e58383-e1f2-439c-a4c2-60a6bf29182e)

---
- Then fills in the registration form on the company's website.
- if the form is filled in correctly then the student is registered if not the student is notified to correct the errors and try again.
- After that the student can check out our free introductory course.
- After completing or skipping it the student can start our full-fledged course straight away.
- Finally the student needs to pay for the course success.
![18](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/fae1f3e1-2053-4d76-bd58-99677904e1c3)

---
- But there is another interesting way to add clarity to the diagram i suspect that the person who has invented the first activity diagram was probably a passionate swimmer because he or she introduced the concept of a swim lane as a part of the diagram.
![19](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/bfeea01a-4510-4bee-a35d-969636395bea)

---
- Swimlane is a way of grouping activities performed by the same actor in a single thread.
- let's have a look at the activity diagram that describes the business process of onboarding a new client.
![20](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/3342d204-c468-4dd1-9229-63a66f7cfd60)

---
- First of all we reach out to our potential client and arrange a meeting depending on whether there will be a meeting and whether i will be in our company's office or in the client's office.
- We are preparing either a conference room or just take our laptop with us but regardless of where the meeting is going to take place we know that the client wants to meet with us.
- After the meeting we'll normally send a follow-up letter to the client we just had a meeting with.
- Decision point if we have a deal then we prepare the contract and we also add the comment that there is another a separate activity diagram that reflects this process and needs to be followed.
- We send the contract to the client and we get to the point where the process finalizes by the way we come here even if we didn't get the deal.
![21](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/480d963f-8043-46fc-ac4e-43cf36cd1701)

---
- And here is the schema of the same process but this time we're using swimlane.
- You can see that now it looks much more accurate because this time the process is divided into areas of responsibility for the salesperson who organizes the appointment as well as writes a follow-up letter to the client and the consultant who prepares the presentation for the client holds a meeting and crafts and sends the contract and a secretary whose task includes preparing the conference room in case the meeting takes place in our company's own office.
![22](https://github.com/A8N0RMAL/UML-Diagrams/assets/119806250/90628558-1b25-4d34-a77e-95e39dbc95af)

---
