# User Story

## A. User Story

### 1. Definition and Explanation
A user story is a planning tool that serves as a promissory note for future conversation between team members. Stories are brief, customer-centric descriptions of functionality that represent work customers recognize and value, rather than implementation details.

**The Three Parts of a User Story**:
1. **Written Description** - A brief statement on a story card that describes the functionality 
2. **Conversation** - Discussions between the customer team and developers about the story details 
3. **Confirmation** - Acceptance tests that validate the story has been implemented correctly

User stories provide significant advantages over traditional requirements approaches:
- **Emphasize Verbal Communication** - Stories encourage face-to-face conversations rather than relying solely on written documents
- **Comprehensible by Everyone** - Both technical and non-technical stakeholders can understand and contribute to user stories
- **Build Tacit Knowledge** - Team understanding improves through conversations and collaboration
- **Right Size for Planning** - Stories provide appropriate granularity for iteration and release planning
- **Iterative Development** - Stories work naturally with agile development processes
- **Encourage Participatory Design** - Users become active participants in defining software behavior rather than passive recipients

### 2. Attributes
Six essential attributes that define good stories and ensure they are useful for both planning and development:

- **Independent** - A good story should stand on its own and not be dependent on other stories. Dependencies create prioritization and estimation problems.
- **Negotiable** - Stories are not fixed contracts, they are flexible and meant to be discussed and refined through conversation between customers and developers.
- **Valuable** - Every story must deliver value either to the end user or the purchaser of the system.
- **Estimatable** - Stories must be clear enough for developers to estimate the effort required.
- **Small** - Stories should be small enough to be completed within a short timeframe, typically from half a day to two weeks of work.
- **Testable** - A story must be written in a way that allows it to be tested. If it cannot be tested, the team cannot determine when it is finished.

## B. Acceptance Testing

**_TBA_**

## C. Gathering Stories

### 1. Definition and Explanation
Gathering stories is the process of identifying and documenting user stories through collaborative techniques that focus on understanding user needs and goals. 

### 2. How to Gather Stories

1. **User Interview** - User interviews are one-on-one conversations with actual users or user representatives to discover their needs, goals, and current workflows. They rely on asking open-ended, context-free questions that don't lead users toward predetermined answers.
2. **Story-Writing Workshops** - Story-writing workshops are collaborative meetings where developers, users, and product stakeholders work together to brainstorm and write as many user stories as possible. They combine group brainstorming with low-fidelity prototyping to systematically explore user workflows and generate stories.
3. **Questionnaires** - Questionnaires are structured surveys sent to users to gather specific information about requirements, priorities, or usage patterns. They are primarily useful for collecting feedback from large user populations about existing stories rather than discovering new ones.
4. **Observation** - Observation is the practice of watching users work with existing software or perform their current tasks in their natural environment. It reveals actual user behavior and real workflow needs that may differ from what users say they do or need.

### 3. User Proxies
User proxies are people who may not be users themselves but are included on a project to help represent users when real users are not available or accessible. They serve as stand-ins for actual users in the story writing and decision-making process.

**Here are different strategies depending on the situation**:
1. **When Users Exist But Access Is Limited**
   - **Situation**: Real users exist but you're blocked from direct access and must work through a proxy decision-maker
   - **Solution**: Create a user task force of real users who advise while the proxy makes final decisions.
   - **Result**: Task force gradually takes over day-to-day decisions through meetings where they write and prioritize stories.
2. **When No Users Are Available**
   - **Situation**: No real users are accessible to participate in the project at all.
   - **Solution**: Use multiple different types of proxies (e.g., domain expert + marketing person) and study competing products for ideas.
   - **Result**: Reduces single-person bias and provides story sources until early software release opens communication with real users.

**Priority who can be user proxies**:
1. **Business/Systems Analysts**: 
   Have both technology and business domain knowledge, making them natural bridges between users and developers who can balance technical requirements with business needs. Some prefer thinking about problems rather than researching them with real users, and may spend excessive time on upfront activities instead of iterative learning.
2. **Domain Experts**: 
   Excellent for complex domains with specialized terminology and essential for identifying business rules and building domain models. May create solutions too complex for average users and often focus on expert-level functionality rather than typical user workflows.
3. **Customers (Purchasers)**: 
   Understand purchasing priorities and budget constraints, and when they're also users, provide the ideal combination of authority and usage knowledge. Often have different needs and priorities than the actual end users who don't make purchasing decisions.
4. **Former Users**: 
   Have actual hands-on experience with similar software or processes and understand real user workflows from personal experience. Their knowledge becomes outdated quickly as systems and business processes evolve, and their goals may no longer align with current users.
5. **Marketing Group**:
   Understand markets and can provide useful high-level guidance about relative priorities and what features appeal to broad user segments. Focus more on quantity of features rather than quality since they understand what sells rather than what works well in practice.
6. **Salespeople**: 
   Excellent as conduits to real users with broad customer contact and can facilitate introductions during sales calls or trade shows. Tend to overemphasize features that could have won recent lost sales rather than providing comprehensive long-term product vision.
7. **Users' Manager**: 
   Has organizational authority and may have some user experience if they previously held user roles. Usually has different usage patterns than typical users and can be a source of misinformation as problems get exaggerated through reporting chains.
8. **Trainers/Technical Support**:
   Have daily contact with users and understand common problems and pain points that users experience. Focus on making software easy to train or support rather than optimizing for user productivity, and may deprioritize advanced features.
9. **Development Manager**: 
   Already involved in day-to-day project details and understands technical constraints and possibilities. Rarely an intended user with conflicting goals like introducing new technology over user needs, plus corporate incentives misaligned with user satisfaction.
10. **Developers Themselves**: 
    Understand technical possibilities and constraints of what can be built within the system architecture. Lack marketing backgrounds, domain expertise, and customer contact needed to understand user needs and feature value.

**Note**:
- It is vital that a project include one or more real users on the customer team because only real users truly know how they want the software to behave.
- Don't try to be the user proxy yourself. Developers typically lack marketing backgrounds, customer contact, and domain expertise needed to represent users effectively.


