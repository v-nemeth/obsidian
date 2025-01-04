Tags: [[University]] [[Exam]]
Time: 03-01-2025-09:00

# End User Development Exam

## End-User Development
### Slides
[[L2. EUD, EUP, and EUSE (2).pdf]]
[[L3. EUP Models (2).pdf]]
[[L4. EUD In-Context - Cobots (2).pdf]] (Guest lecture OBS (Annehide))
[[L5. EUD In-Context - RobotTrainer.pdf]] (Guest lecture)
[[L6. EUD In-Context - EUP for Kids.pdf]] (Guest lecture)
### Lecture 2 - EUD, EUP and EUSE
- End-User Development (EUD): Enabling non-professional developers to modify or create software artifacts.
- Tailoring: Adjusting parameters or creating full-fledged programs within applications.
- EUD methods and tools span the entire software development lifecycle.
- End-User Programming (EUP): Creation of programs primarily for personal use.
- Interaction styles include programming using visual attributes, programming-by-demonstration, programming-by-specification, and programming with text.
- Visual programming examples include Scratch, LabVIEW, and spreadsheets.
- Programming-by-demonstration involves user demonstrations to infer logic, with examples like FlashFill in Excel.
- Programming-by-specification allows tools to generate programs from user descriptions, e.g., converting natural language to Python.
- End-User Software Engineering (EUSE): Emphasizes systematic activities to ensure software quality.
- Methods include requirements gathering, design and specification, testing and verification, debugging, and reuse.
- Testing approaches include WYSIWYT for spreadsheets and automated error checks based on types and dimensions.
- Debugging tools include proactive assertions and visual explanations like Whyline for Alice.
- Reuse focuses on components, APIs, and opportunistic sharing to save time.
- Early EUD tools: Spreadsheets like VisiCalc, Lotus 1-2-3, and Excel.
- Applications include automating tasks, personalizing software behavior, and performing complex computations.
- Challenges in EUD include lack of professional programming knowledge, short-term focus, and limited reusability of programs.
- Ensuring quality in EUSE involves addressing reliability, performance, security, and maintainability.
- Difficulties with programming-by-specification include unpredictability and limited input handling by tools.
- Future directions include the adoption of low-code/no-code platforms and increased focus on quality for diverse user needs.
### Lecture 3 EUP Models
- Programming models as a set of abstractions for developing programs
- Programming models categorized into low-code vs. traditional and domain-specific vs. general-purpose
- Visual Programming (VPL) uses visual representation like boxes-and-arrows and interlocking puzzle pieces
- Examples of VPL include BPMN and Scratch
- Strengths of VPL: easy readability and reduced syntax errors
- Weaknesses of VPL: high screen space usage and dependency on visual tools
- Programming by Demonstration (PBD) involves users demonstrating tasks for systems to record and replay
- Strengths of PBD: familiarity for users and concrete demonstrations
- Weaknesses of PBD: difficulty in generalizing tasks and brittleness to GUI changes
- Programming by Natural Language (PBNL) translates natural language input into programs
- Strengths of PBNL: expressiveness and low user effort
- Weaknesses of PBNL: ambiguity in input and NLP technology limitations
- Rule-Based Programming focuses on customization for IoT and smart devices
- Trigger-Action Programming (TAP) supports automations via triggers and actions
- TAP examples include managing events like opening garage doors or sending emails
- Issues with TAP include rule conflicts and unintended interactions
- Text-Based Techniques rely on domain-specific languages (DSLs) and scripts
- Building blocks of low-code platforms include code canvas, palette, text box, player, stage, and configuration pane
- Scenario-based specifications use concrete examples like Behavior-Driven Development (BDD)
- BDD employs Gherkin syntax for executable specifications
- Examples of BDD scenarios include account management and conveyor belt automation
- DSLs for BDD scenarios allow declarative and imperative abstractions
- Domain-specific languages enable behavioral and domain specification modeling
- Strengths of low-code techniques: accessibility, reduced errors, and user familiarity
- Weaknesses of low-code techniques: challenges with scaling, generalization, and understanding user intent
- Applications include IoT, Ambient Intelligence, and smart system automation
- Challenges in low-code programming involve ambiguity resolution, scalability, and rule conflicts
### Lecture 4 Cobots
- Collaborative robots (cobots) designed for logistics and mobile robotics tasks
- Communication barriers between non-technical users and robots leading to challenges in precise instructions and miscommunication
- Complex interfaces of robotic systems that are not user-friendly for non-technical users
- Low-code programming approaches with block-based and domain-specific languages (DSLs)
- ER-FLEX mobile collaborative robot features:
    - Drag-and-drop block-based programming interface
    - Laser sensors for 2D environmental mapping
    - Vision tools and AI algorithms for object detection and pose estimation
    - REST and OPC UA interfaces for integration with external systems
    - ROS interface for direct R&D use
- Use case: warehouse management, moving boxes/items between storage and production
- Key challenges in robot programming:
    - Simplifying programming complexity for intuitive user interfaces
    - Ensuring scalability across diverse environments and systems
    - Developing autonomous object-picking solutions
- Objectives of the project:
    - User-friendly programming through natural language
    - Real-time simulation and monitoring with digital twins
    - Enhanced safety and recovery procedures for robots
    - Improved navigation and 3D scene planning
- Low-code approaches focusing on DSLs for robotic programming
- Results:
    - Object handling and assembly using neural network-based trajectory generation
    - Experiments assessing the cognitive load of end-users programming with DSLs
    - Synchronization between block and text-based programming for flexibility
- Enhanced debugging and validation through:
    - Breakpoints at the scenario step level
    - Visualization tools for execution paths
- Scenario-based programming with modularity and reuse:
    - Step/scenario discovery and reuse features
    - Automatic alignment with UML and BPMN diagrams for conceptual and behavioral representation
- Web-based interfaces for improved accessibility
- Focus on enhancing human-robot interaction with better tools and user-friendly interfaces

## Low Code Development

### Slides
[[L7. Consistency Assurance Across Software Artifacts.pdf]]
[[L8. Low-Code Development and EUP Learning Barriers.pdf]]
[[L9. Low-Code Development and Generative AI.pdf]]
[[L10. Low-Code Platforms - PowerApps.pdf]] (Guest lecture)
[[L11. Low-Code Platforms - DCR Solutions.pdf]] (Guest lecture)
### Lecture 7 Consistensy assurance across Software Artifacts
- Requirements must align consistently across various software development artifacts
- Manual verification is currently prevalent but is time-consuming and error-prone
- Traceability approaches often fail to assess consistency between requirements and software artifacts
- BDD stories are used as the central artifact to ensure alignment across development stages
- BDD stories can represent scenarios in formats such as state machines and are linked to GUI elements
- Ontologies describe expected user interactions in natural language, aiding in consistency assessment
- Task models systematically capture user goals and pathways for achieving them
- Task models support usability assessments and predictive workload analyses
- Usability evaluations can identify supported tasks and potential issues in user interfaces
- Task modeling notations like HTA, GOMS, and HAMSTERS facilitate structured representations
- HAMSTERS provides hierarchical task modeling with temporal operators and graphical task types
- XML exports from HAMSTERS enable automated consistency checking with BDD stories
- Common inconsistencies include task mismatches, unpaired behaviors, and missing elements
- GUI prototypes, such as those created in Balsamiq, are assessed for grouping and element consistency
- UML class diagrams are checked against BDD stories for alignment and accuracy
- Types of inconsistencies in GUI prototypes include semantic inconsistencies, untraceable interactions, and duplicate elements
- HAMSTERS automates the extraction and validation of task models against scenarios
- Tools like HAMSTERS reduce the need for manual intervention by designers during consistency checks
- The process involves syntactic and semantic analysis of extracted artifacts for detailed assessments
- Consistency checks between task models and BDD stories ensure both share the same level of granularity
- Identified issues are addressed to improve the alignment between requirements and task models
- Future enhancements may involve integrating more advanced tools and improving automation capabilities
### Lecture 8 Low Code Development and EUP learning barriers
- A global shortage of software developers exists despite rising demand for software systems
- Increased computer literacy and programming education contribute to a growing pool of "citizen developers"
- LCDPs enable rapid application delivery with minimal coding, reducing development time and costs
- Gartner predicts that by 2024, LCDPs will drive over 65% of software development activity
- Definitions of LCDPs emphasize visual, declarative techniques and low initial cost barriers
- No-code platforms eliminate programming entirely through graphical interfaces but are distinct from LCDPs
- LCDPs support several key steps:
    - Domain modeling: representing concepts and relationships
    - UI definition: creating forms and pages for data interaction
    - Business logic specification: defining control and data flows via workflows or rules
    - External service integration: connecting to APIs and third-party systems
    - Application generation and deployment: automating app creation and cloud-based deployment
    - Application maintenance: tools for system monitoring and updates
- Challenges of LCDPs:
    - Proprietary notations not suited for all users
    - Vendor lock-in and limited support for cyber-physical systems
- Perspectives on low-code:
    - Large language models (LLMs) enhance code generation and communication
    - Domain-Specific Languages (DSLs) improve program readability, auditing, and transformation
    - Combining multiple low-code techniques can offset individual limitations
    - Meta-tools, such as Blockly, support the creation of LCDP tools
- Learning barriers in EUP identified by Ko et al. (2004):
    - Design barriers: difficulty conceptualizing solutions systematically
    - Selection barriers: inability to identify suitable programming interfaces
    - Coordination barriers: challenges in combining interfaces
    - Use barriers: obscurity in interface usage
    - Understanding barriers: difficulty evaluating program behavior
    - Information barriers: challenges in diagnosing program behavior
- Learning barriers align with Norman's concepts of the gulf of execution and evaluation:
    - Execution barriers: design, coordination, and use barriers
    - Evaluation barriers: selection and information barriers
- Strategies for addressing learning barriers:
    - Scaffolding creativity with examples and inspiration
    - Enhancing tools to make invisible rules explicit
    - Improving feedback mechanisms to align user expectations with system behavior
- Current limitations in LCDPs focus on business process automation, lacking robust support for complex systems
- Future directions involve integrating AI, DSL exposure, and meta-tool advancements to improve low-code accessibility and **utility**

### Lecture 9 Low Code and Generative AI
- Generative AI breakthroughs, particularly LLMs, enable advancements in text, image, and code generation
- Program synthesis automatically generates code satisfying user constraints expressed as input-output examples, demonstrations, or natural language
- Early analysis predicts a $4.1 billion market for generative AI in application development by 2023, with a 32% annual growth rate
- Conversational AI combines natural language processing (NLP) and machine learning (ML) to simulate human-like conversation
- Constant learning from interactions improves response quality over time
- Prompt engineering is essential for interacting effectively with LLMs, given their non-deterministic nature
- Prompt engineering techniques include:
    - Zero-shot prompting: Providing task requests without examples
    - Few-shot prompting: Demonstrating desired outputs in examples
    - Chain-of-thought (CoT) prompting: Including intermediate reasoning steps
    - Generated knowledge prompting: Using pre-generated context to refine outputs
- LLM prompting for programming tasks uses techniques like Generated Knowledge and CoT to refine outputs
- Practical applications include generating implementation plans, refining task breakdowns, and creating testable code sections
- LLM-based LCDPs support broader application domains compared to traditional platforms
- Traditional LCDPs focus on web development, while LLM-based platforms handle general programming and deployment tasks
- Limitations of LLM-based LCDPs:
    - Higher uncertainty due to LLM behavior
    - Outdated data causing hallucinations
- Advantages of LLM-based LCDPs:
    - Greater flexibility, overcoming API and data migration challenges
- Both traditional and LLM-based LCDPs require professional programming knowledge for advanced tasks
- Version-related issues persist in both systems, with traditional LCDPs facing component conflicts and LLMs encountering outdated training data
- Continued advancements in LLMs and prompting techniques could enhance low-code development flexibility and reliability


___
