# CS6.401 Software Engineering Project 3

## Project Title -

### Date -

### Group Number -

| Name | Roll Number | Email |
| ---- | ----------- | ----- |
| Name | Rno         | Email |
| Name | Rno         | Email |
| Name | Rno         | Email |
| Name | Rno         | Email |
| Name | Rno         | Email |

# Requirements Refinement

In this section, you should revise/improve/specialize the list of system requirements or features (both functional and non-functional) presented in the Project document.

> _Do not spend time in over-documenting requirements. This assignment is about the system architecture and architecture decisions._

In particular

- Identify the user stories/requirements that are most architecturally significant
- Prioritize requirements
- Use any notation you want (Use Case diagrams, SysML Requirements model, User stories, list of feature, etc.) to represent the overall requirements.

# Informal Description of your system and its Software/System Architecture

Here you provide a brief description of the system you have in mind and its architecture,, possibly by using also an informal drawing (e.g., by using a Powerpoint-like figure, Visio, a drawing, or any other).

In particular, your submission should clearly include the following

- The description of the system you have in mind;
- The identification of sub-systems;
- The identification of clear boundaries between the identified architecture, and external/existing components or sub-systems (the architectural picture shall clearly distinguish legacy components from new system-specific components);
- Pictures of the overall architecture, identifying different components
- Brief Description on how your solution is expected to satisfy the requirements

# Design Decisions

In this section, you are required to document up to four (4) most important architecture design decisions using the Architecture Decision Records  
For “most important” we mean those that may have a bigger impact on your architecture, those that you discussed more, or you think are the most relevant. The ADR Template is available [here](https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/templates/decision-record-template-by-michael-nygard/index.md)

# Views and Viewpoints

Based on the informal description of the SA, identify:

- Stakeholders
- Concerns
- Concern–Stakeholder Traceability (see example below, to be adapted to the assigned system)

|                            | Service Provider | Customer | WSN Developer | Mobile App Developer | System Integrator |
| -------------------------- | ---------------- | -------- | ------------- | -------------------- | ----------------- |
| Dependability              | X                |          | X             | X                    | X                 |
| Energy Consumption         |                  |          | X             |                      |                   |
| Networking & Communication |                  |          | X             | X                    | X                 |
| Usability                  | X                | X        |               | X                    |                   |
| Performance                |                  |          | X             | X                    | X                 |
| Security                   | X                | X        |               |                      | X                 |
| Cost                       | X                |          | X             |                      |                   |

# Architectural Tactics and Patterns

What are the architectural tactics you intend to use and why?

What are the pattern(s) that you plan to use? Provide a brief description. Some of these decisions can also go in the above section related to design decision

Here you shall provide a detailed description of the SA you have in mind, using UML component and deployment diagrams (other UML diagrams can be used, if needed). You can also make use of C4 Modelling diagram instead of UML if needed.

Please provide a detailed description of each single component, its interfaces, interface attributes, and expected behavior.

# Architectural Analysis

- What part of the system is going to be analysed?

- What Quality attributes will be analysed?

- Mention the pattern that you are using for comparison and why?

- Report the results of the analysis (in the form of graphs and tables)

- What do you infer from the analysis?

# Bonus: From Architecture to Code

Please describe the prototype you implemented and explain how it supports your claims about the functional and non functional requirement of your project (Make use of diagrams and screenshots, don’t make this section verbose with too many details)

The prototype shall demonstrate that your architecture, when implemented, brings the quality characteristics you wanted/expected.

# Summary

In this section, you should describe how the addressed design topic has been expressed in the various parts of the document.
