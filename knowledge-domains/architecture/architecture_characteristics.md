# Architecture Characteristics

Architecture characteristics as important aspects of a software system that are not directly related to its functional domain but are critical to the system's success. Architecture characteristics constitute another dimension that defines software architecture, beyond the system structure.

## A. Criteria for Architecture Characteristics
- **Specifies a non-domain design consideration** - Architecture characteristics specify operational and design criteria for success, concerning how to implement requirements and why certain choices were made, rather than what the application should do.
- **Influences some structural aspect of the design** - Architecture characteristics must impact the system's structure, such as components, relationships between components, or communication methods between components.
- **Is critical or important to application success** - Not all design decisions qualify as architecture characteristics; only those that are important or critical to the application's success.

## B. Categories of Architecture Characteristics

### 1. Operational Architecture Characteristics
Operational architecture characteristics encompass capabilities related to how a system operates in a production environment.

1. **Availability**: How long the system needs to be available for use.
2. **Continuity**: Disaster recovery capability.
3. **Performance**: How quickly the system responds to and processes requests.
4. **Recoverability**: How quickly the system can return to operation after a failure.
5. **Reliability/safety**: The ability of the system to operate without failure under specified conditions for a specified period.
6. **Robustness**: Ability to handle error and boundary conditions while running.
7. **Scalability**: The ability of the system to handle increased load.

### 2. Structural Architecture Characteristics
Structural architecture characteristics relate to the internal structure of code and how the system is organized.

1. **Configurability**: The ability for end users to easily change aspects of the software's
2. **Extensibility**:  How important it is to plug new pieces of functionality into the system.
3. **Installability**: Ease of system installation on all necessary platforms.
4. **Leverageability**: Ability to leverage common components across multiple products.
5. **Maintainability**: How easy it is to apply changes and enhance the system.
6. **Portability**: Whether the system needs to run on more than one platform.
7. **Supportability**: What level of technical support is needed by the application and what level of logging and other facilities are required to debug errors.
8. **Upgradeability:**: Ability to easily/quickly upgrade from a previous version of the application/solution to a newer version on servers and clients.

### 3. Cross-Cutting Architecture Characteristics
Cross-cutting architecture characteristics are those that influence various aspects of the system.

1. **Accessibility**: Access to all your users, including those with disabilities like colorblindness or hearing loss.
2. **Archivability**: Whether the data will need to be archived or deleted after a period of time.
3. **Authentication**: Security requirements to ensure users are who they say they are.
4. **Authorization**: Security requirements to ensure users can access only certain functions within the application.
5. **Legal**: Legislative constraints the system is operating under and regulatory compliance requirements.
6. **Privacy**: Ability to hide transactions from internal company employees.
7. **Security**: Measures and practices to protect data and systems from unauthorized access or attacks.
8. **Supportability**: What level of technical support is needed by the application and what level of logging and other facilities are required to debug errors.
9. **Usability/achievability**: Level of training required for users to achieve their goals with the application.

## C. References

