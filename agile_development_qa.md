# Agile Development: Question and Answer Format

## Remember (K1) - Recall of Facts

### 1. What are the core values of the Agile Manifesto?
**Answer:** The core values of the Agile Manifesto are:
- Individuals and interactions over processes and tools
- Working software over comprehensive documentation
- Customer collaboration over contract negotiation
- Responding to change over following a plan

### 2. Define the term "Agile Software Development."
**Answer:** Agile Software Development is a software development methodology that values flexibility, collaboration, and customer satisfaction. It is an iterative and incremental approach to software development that emphasizes the importance of delivering a working product quickly and frequently. It involves close collaboration between the development team and the customer to ensure that the product meets their needs and expectations.

### 3. List any four Agile frameworks.
**Answer:** Four Agile frameworks are:
- Scrum
- Extreme Programming (XP)
- Feature Driven Development (FDD)
- Lean Software Development (LSD)

### 4. Who introduced Scrum as a framework?
**Answer:** Ken Schwaber and Jeff Sutherland developed Scrum in the early 1990s, taking inspiration from the Rugby game.

### 5. What is meant by "sprint" in Scrum?
**Answer:** In Scrum, sprints consist of work units that are required to achieve a requirement defined in the backlog that must be fit into a predefined time-box (typically 30 days). Each sprint is a short, focused work period.

## Understand (K2) - Explain Concepts

### 1. Explain the principle "responding to change over following a plan."
**Answer:** The principle "responding to change over following a plan" means that while planning is important, an Agile team values the ability to adapt to changing requirements more. It recognizes that plans are short-lived as customer priorities will change, and some requirements will persist while others will change. This principle acknowledges that in software development, being able to respond effectively to change is more valuable than rigidly adhering to a predetermined plan that may become outdated.

### 2. Differentiate between Scrum and Extreme Programming.
**Answer:** Scrum focuses on project management practices with defined roles (Product Owner, Scrum Master, Team Member) and events (Sprint Planning, Daily Scrum, Sprint Review, Sprint Retrospective). It manages work through a product backlog and sprints.

Extreme Programming (XP) focuses more on programming practices and technical aspects of software development. It emphasizes values like communication, simplicity, feedback, courage, and respect, and includes practices such as pair programming, test-driven development, continuous integration, and refactoring. While Scrum is primarily about how to manage the development process, XP provides specific engineering practices for developing high-quality software.

### 3. Describe the phases of Feature Driven Development (FDD).
**Answer:** The phases of Feature Driven Development are:
1. Develop a model - Define the domain model for the business problem.
2. Build a feature list - Identify and list features important to the client.
3. Plan by feature - Determine the order of feature development considering risks, dependencies, and workload.
4. Design by feature - The chief programmer determines features for a two-week iteration, defines priorities, and assigns team members.
5. Build by feature - Implement items necessary to support the feature design, design the user interface, build and test a prototype.

### 4. Why is "pair programming" encouraged in XP?
**Answer:** Pair programming is encouraged in XP because it promotes collaboration and knowledge sharing between developers. Two people working together at one workstation to create code for a story leads to better quality code with fewer defects as there is continuous code review. It also facilitates learning, improves team cohesion, and enhances problem-solving capabilities through different perspectives.

### 5. Explain how the cost of change is managed in Agile projects.
**Answer:** In Agile projects, the cost of change is managed by "flattening" the cost of change curve through practices such as:
- Using incremental delivery with short iterations
- Employing continuous unit testing
- Using practices like pair programming
- Focusing on simple design
- Regular refactoring to maintain code quality

These practices allow teams to accommodate changes late in the software project without dramatic cost and time impact, unlike conventional development where costs escalate quickly when changes are introduced late in the development cycle.

### 6. Describe the concept of self-organizing teams.
**Answer:** A self-organizing team is one that has the flexibility and authority to find its own methods for achieving its goals. Members take on work without waiting for it to be assigned, take responsibility for their work, and track their own progress. They communicate as a team to ensure the group is working toward its goals. The increased sense of ownership often makes them more enthusiastic and effective at finding good solutions to problems. This is in contrast to micromanaged teams where managers dictate exactly what to do and when.

### 7. Explain the role of the Product Owner in Scrum.
**Answer:** The Product Owner in Scrum represents the customers, users, and other stakeholders. Their responsibilities include:
- Writing user stories to describe the project's goals and prioritizing them
- Defining requirements and verifying the product meets those requirements
- Setting requirement priorities and helping determine which requirements go into the next iteration
- Keeping stakeholders posted on project status and demonstrating the product
- Planning and announcing releases
- Providing a point of contact between stakeholders and developers

### 8. Describe how Lean Software Development eliminates waste.
**Answer:** Lean Software Development eliminates waste by identifying and removing anything that doesn't contribute directly to the project's value. This includes:
- Clarifying or eliminating unclear requirements
- Removing unnecessary features and code
- Avoiding unnecessary repetition through refactoring, automated testing, and record keeping
- Reducing unnecessary meetings and bureaucracy
- Focusing only on features that add customer value
- Deferring commitment until enough information is available
- Using short iterations to deliver value quickly
- Building quality into the process rather than adding it later

### 9. Explain the importance of short iterations in Agile development.
**Answer:** Short iterations in Agile development are important because they:
- Allow for frequent delivery of working software to customers
- Provide regular opportunities for customer feedback and adjustments
- Help identify and fix bugs early when they're easier to address
- Keep the project moving briskly along due to time-boxing
- Reduce risk by delivering small increments of functionality
- Enable teams to learn and adapt quickly
- Maintain high code quality through frequent testing
- Provide tangible evidence of progress at regular intervals
- Help maintain team momentum and focus

### 10. Illustrate the difference between traditional and Agile lifecycle models.
**Answer:** Traditional lifecycle models (like Waterfall) are sequential and phase-based, where each phase (requirements, design, implementation, testing, deployment, maintenance) must be completed before the next begins. Changes are costly, especially in later phases.

Agile lifecycle models are iterative and incremental. They involve short cycles (iterations) where each iteration includes all development phases (requirements, design, implementation, testing). Agile models embrace change, focus on customer collaboration, and deliver working software frequently. While traditional models emphasize comprehensive documentation and following a plan, Agile prioritizes working software and responding to change.

## Apply (K3) - Use Concepts in Scenarios

### 1. Apply the Agile principle of "customer collaboration" to a scenario where a requirement changes mid-sprint.
**Answer:** When a requirement changes mid-sprint, applying the principle of "customer collaboration over contract negotiation" would involve:
1. Immediately engaging with the customer to understand the change and its importance
2. Discussing the impact of the change on the current sprint goals and deliverables
3. Working collaboratively to decide whether to implement the change now or defer it to the next sprint
4. If critical, the team might adjust the sprint scope through collaboration rather than rigidly refusing due to the "contract" of the sprint backlog
5. Ensuring transparency about what can realistically be accomplished given the change
6. Documenting the change for future planning
7. Using the situation as an opportunity to improve understanding of customer needs
8. Focusing on delivering value rather than adhering strictly to the original plan

This approach values the collaborative relationship with the customer and the ability to respond to their changing needs over strict adherence to the initially agreed sprint plan.

### 2. Given a sample backlog, identify how you would prioritize and plan a sprint in Scrum.
**Answer:** To prioritize and plan a sprint in Scrum with a sample backlog:

1. Review the product backlog with the Product Owner who has already prioritized items based on business value.
2. Determine the team's capacity for the upcoming sprint based on team velocity from previous sprints.
3. Select high-priority items from the top of the backlog that the team can realistically complete within the sprint.
4. Break down selected backlog items into specific tasks during sprint planning.
5. Estimate effort for each task and ensure the total fits within the team's capacity.
6. Discuss implementation approaches and potential challenges for selected items.
7. Confirm sprint goals that align with the selected backlog items.
8. Commit as a team to the sprint backlog and goals.
9. Update the sprint backlog with the selected items and their associated tasks.
10. Communicate the sprint plan and goals to stakeholders.

This process ensures that the most valuable items are worked on first and that the team commits to a realistic amount of work for the sprint duration.

### 3. Create a simple user story for an online banking feature.
**Answer:** User Story: As a bank customer, I want to transfer money between my accounts so that I can manage my funds without visiting a branch.

Acceptance Criteria:
- I can select source and destination accounts from a list of my accounts
- I can enter the transfer amount and see my available balance
- I can schedule the transfer for a future date if needed
- I receive immediate confirmation when the transfer is successful
- The transaction appears in my account activity history
- I receive an email notification after completing the transfer

Story Points: 5
Priority: High

### 4. Demonstrate how CRC cards would be used to design a class model for a login system.
**Answer:** Using Class-Responsibility-Collaborator (CRC) cards for a login system design:

**Card 1: User**
Responsibilities:
- Store user information (username, password hash, email)
- Validate credentials
- Update profile information
- Track login attempts

Collaborators:
- Authentication Controller
- User Repository

**Card 2: Authentication Controller**
Responsibilities:
- Process login requests
- Verify user credentials
- Generate authentication tokens
- Handle login failures
- Redirect to appropriate pages

Collaborators:
- User
- Session Manager
- Security Logger

**Card 3: Session Manager**
Responsibilities:
- Create new sessions
- Maintain active sessions
- Expire inactive sessions
- Validate session tokens
- Handle logout requests

Collaborators:
- Authentication Controller
- User
- Security Logger

**Card 4: Security Logger**
Responsibilities:
- Log login attempts
- Record successful/failed logins
- Track suspicious activities
- Generate security reports

Collaborators:
- Authentication Controller
- User

**Card 5: User Repository**
Responsibilities:
- Retrieve user data from database
- Store user information
- Update user records
- Search for users

Collaborators:
- User
- Authentication Controller

During an XP design session, team members would use these cards to roleplay interactions between classes, identify missing responsibilities, and refine the design collaboratively.

### 5. Apply the Lean principle "defer commitment" to a product planning session.
**Answer:** Applying the Lean principle "defer commitment" to a product planning session:

1. Instead of committing to a full feature set upfront, the team first identifies only the core features that are well-understood.

2. For features with uncertain requirements, the team decides to:
   - Gather more information before making implementation decisions
   - Create prototypes to test assumptions about complex features
   - Schedule research spikes for technically challenging areas
   - Plan only the next 1-2 iterations in detail

3. When discussing the technology stack, the team:
   - Postpones final architecture decisions until more is known about scaling needs
   - Chooses flexible technologies that don't lock them into one approach
   - Designs interfaces between components before committing to specific implementations

4. For the release timeline, the team:
   - Commits only to near-term milestones with high confidence
   - Uses ranges rather than specific dates for later milestones
   - Establishes decision points where commitments will be made when more information is available

5. The team also:
   - Keeps options open by identifying multiple implementation approaches
   - Creates a learning plan to acquire knowledge needed for better decisions
   - Establishes triggers that will indicate when a commitment needs to be made

This approach allows the team to make decisions at the "last responsible moment" when they have the most information, reducing waste from premature commitments that might need to be reversed later.

### 6. Show how Agile practices could be used in a college group project.
**Answer:** Implementing Agile practices in a college group project:

1. **Project Initiation**:
   - Hold an initial meeting to understand project requirements and create a shared vision
   - Create a simple product backlog of features/deliverables prioritized by importance
   - Assign roles: one student as Product Owner (liaising with professor), another as Scrum Master (facilitating team process)

2. **Sprint Planning**:
   - Divide the project duration into 1-2 week sprints
   - For each sprint, select the highest priority items the team can complete
   - Break down selected items into specific tasks and distribute them based on skills

3. **Daily Coordination**:
   - Use a messaging platform for daily updates (similar to daily standups)
   - Each member shares: what they completed, what they're working on, and any blockers
   - Maintain a simple Kanban board (using Trello or a physical board) to track progress

4. **Collaborative Work**:
   - Practice pair work for complex tasks (like research analysis or difficult coding)
   - Hold working sessions where team members co-locate to work together
   - Use cloud services (Google Docs, GitHub) for real-time collaboration

5. **Review and Feedback**:
   - At the end of each sprint, review completed work together
   - Get feedback from professor or other classmates when possible
   - Demonstrate working portions of the project rather than just discussing concepts

6. **Continuous Improvement**:
   - Hold brief retrospectives after each sprint to discuss what went well and what could improve
   - Adjust team processes based on these discussions
   - Document lessons learned for future projects

7. **Agile Tools**:
   - Use a shared digital space for the product backlog
   - Create user stories for project requirements ("As a reader of our research, I want...")
   - Track progress visually and celebrate completed tasks

This approach helps students deliver higher quality work, learn to collaborate effectively, and adapt to changes in project scope or requirements throughout the semester.

### 7. Design an XP planning game for a library management system.
**Answer:** XP Planning Game for a Library Management System:

**Setup Phase:**
1. Team roles: 3-5 developers, 1-2 customer representatives (librarians)
2. Materials: Index cards for user stories, planning poker cards, whiteboard

**Story Creation (Listening):**
1. Librarians describe key activities: book checkout, returns, catalog search, member management, etc.
2. Team writes user stories on cards with format: "As a [user], I want to [action] so that [benefit]"
   - Example stories:
     - "As a librarian, I want to check out books to members using their ID so that I can track borrowed items"
     - "As a member, I want to search the catalog by title, author, or subject so that I can find books easily"
     - "As an administrator, I want to generate overdue notices so that I can recover borrowed items"
     - "As a librarian, I want to add new books to the system so that they become available for borrowing"
     - "As a member, I want to view my current loans and due dates so that I can return items on time"

**Prioritization:**
1. Librarians assign a value (1-5) to each story based on importance to library operations
2. Team discusses technical dependencies between stories

**Estimation:**
1. Developers use planning poker to estimate effort for each story (in ideal programming weeks)
2. For stories estimated at over 3 weeks, librarians are asked to split them into smaller stories
3. Team discusses any stories where estimations significantly differ to reach consensus

**Release Planning:**
1. Based on team velocity assumption (initially set at 6 story points per 2-week iteration)
2. High-priority stories are grouped for first release:
   - Member registration system
   - Basic catalog functionality
   - Check-out/return processing

**Iteration Planning (First Iteration):**
1. Select highest priority stories that fit within a 2-week timeframe
2. Break selected stories into technical tasks on separate cards
3. Developers sign up for specific tasks
4. Create acceptance tests for each selected story with librarians' input

**Commitment:**
1. Team commits to delivering working software for selected stories in 2 weeks
2. Schedule daily standup meetings and end-of-iteration demo with librarians
3. Set date for next planning session after first iteration

This planning game ensures customer collaboration through librarian involvement, creates focused development cycles, and produces a prioritized plan that delivers the most valuable features first.

### 8. Draft a test case for a user story using Test Driven Development (TDD).
**Answer:** User Story: "As a bank customer, I want to withdraw money from my account so that I can have cash when needed."

TDD Test Case Development:

**Step 1: Write a failing test**
```java
public class AccountWithdrawalTest {
    @Test
    public void testSuccessfulWithdrawal() {
        // Arrange
        Account account = new Account("12345");
        account.deposit(1000.00);
        
        // Act
        WithdrawalResult result = account.withdraw(500.00);
        
        // Assert
        assertEquals(WithdrawalStatus.SUCCESS, result.getStatus());
        assertEquals(500.00, account.getBalance(), 0.001);
        assertTrue(result.getTransactionId() != null);
    }
    
    @Test
    public void testInsufficientFundsWithdrawal() {
        // Arrange
        Account account = new Account("12345");
        account.deposit(100.00);
        
        // Act
        WithdrawalResult result = account.withdraw(500.00);
        
        // Assert
        assertEquals(WithdrawalStatus.INSUFFICIENT_FUNDS, result.getStatus());
        assertEquals(100.00, account.getBalance(), 0.001);
    }
    
    @Test
    public void testDailyLimitExceeded() {
        // Arrange
        Account account = new Account("12345");
        account.deposit(2000.00);
        account.setDailyWithdrawalLimit(1000.00);
        account.withdraw(600.00); // First withdrawal
        
        // Act
        WithdrawalResult result = account.withdraw(500.00); // Second withdrawal
        
        // Assert
        assertEquals(WithdrawalStatus.DAILY_LIMIT_EXCEEDED, result.getStatus());
        assertEquals(1400.00, account.getBalance(), 0.001);
    }
    
    @Test
    public void testNegativeAmountWithdrawal() {
        // Arrange
        Account account = new Account("12345");
        account.deposit(1000.00);
        
        // Act
        WithdrawalResult result = account.withdraw(-50.00);
        
        // Assert
        assertEquals(WithdrawalStatus.INVALID_AMOUNT, result.getStatus());
        assertEquals(1000.00, account.getBalance(), 0.001);
    }
}
```

**Step 2: Implement the minimal code to pass the tests**
```java
public class Account {
    private String accountNumber;
    private double balance;
    private double dailyWithdrawalLimit;
    private double totalWithdrawnToday;
    
    public Account(String accountNumber) {
        this.accountNumber = accountNumber;
        this.balance = 0.0;
        this.dailyWithdrawalLimit = 1000.0; // Default limit
        this.totalWithdrawnToday = 0.0;
    }
    
    public void deposit(double amount) {
        if (amount > 0) {
            this.balance += amount;
        }
    }
    
    public WithdrawalResult withdraw(double amount) {
        WithdrawalResult result = new WithdrawalResult();
        
        if (amount <= 0) {
            result.setStatus(WithdrawalStatus.INVALID_AMOUNT);
            return result;
        }
        
        if (amount > balance) {
            result.setStatus(WithdrawalStatus.INSUFFICIENT_FUNDS);
            return result;
        }
        
        if (totalWithdrawnToday + amount > dailyWithdrawalLimit) {
            result.setStatus(WithdrawalStatus.DAILY_LIMIT_EXCEEDED);
            return result;
        }
        
        // Process successful withdrawal
        balance -= amount;
        totalWithdrawnToday += amount;
        result.setStatus(WithdrawalStatus.SUCCESS);
        result.setTransactionId(generateTransactionId());
        
        return result;
    }
    
    public double getBalance() {
        return balance;
    }
    
    public void setDailyWithdrawalLimit(double limit) {
        this.dailyWithdrawalLimit = limit;
    }
    
    private String generateTransactionId() {
        return "TXN" + System.currentTimeMillis();
    }
}

public class WithdrawalResult {
    private WithdrawalStatus status;
    private String transactionId;
    
    public WithdrawalStatus getStatus() {
        return status;
    }
    
    public void setStatus(WithdrawalStatus status) {
        this.status = status;
    }
    
    public String getTransactionId() {
        return transactionId;
    }
    
    public void setTransactionId(String transactionId) {
        this.transactionId = transactionId;
    }
}

public enum WithdrawalStatus {
    SUCCESS,
    INSUFFICIENT_FUNDS,
    DAILY_LIMIT_EXCEEDED,
    INVALID_AMOUNT
}
```

**Step 3: Refactor as needed**
After passing the tests, we might refactor to improve the code without changing its behavior:
- Extract validation logic to separate methods
- Improve transaction logging
- Enhance error messaging

This TDD approach ensures that:
1. All requirements from the user story are covered by tests
2. The code meets the requirements exactly
3. Edge cases (negative amounts, insufficient funds, limits) are handled
4. Development is driven by the expected behavior rather than implementation details

### 9. Using a sample feature list, organize features hierarchically (FDD approach).
**Answer:** Hierarchical Feature Organization for an E-commerce System (FDD Approach):

**Major Feature Set 1: Customer Account Management**
- Feature Group 1.1: Registration and Authentication
  - Feature 1.1.1: Register new customer account
  - Feature 1.1.2: Login using email and password
  - Feature 1.1.3: Reset forgotten password
  - Feature 1.1.4: Login using social media accounts
  - Feature 1.1.5: Verify email address through confirmation link

- Feature Group 1.2: Profile Management
  - Feature 1.2.1: Update personal information
  - Feature 1.2.2: Manage shipping addresses
  - Feature 1.2.3: Manage payment methods
  - Feature 1.2.4: View order history
  - Feature 1.2.5: Configure notification preferences

**Major Feature Set 2: Product Catalog**
- Feature Group 2.1: Product Browsing
  - Feature 2.1.1: Browse products by categories
  - Feature 2.1.2: Search products by keywords
  - Feature 2.1.3: Filter products by attributes
  - Feature 2.1.4: Sort products by price/rating/popularity
  - Feature 2.1.5: View product recommendations

- Feature Group 2.2: Product Details
  - Feature 2.2.1: View product images and descriptions
  - Feature 2.2.2: Read customer reviews
  - Feature 2.2.3: View product specifications
  - Feature 2.2.4: See product availability
  - Feature 2.2.5: Compare products side-by-side

**Major Feature Set 3: Shopping Experience**
- Feature Group 3.1: Shopping Cart
  - Feature 3.1.1: Add product to cart
  - Feature 3.1.2: Update product quantity
  - Feature 3.1.3: Remove product from cart
  - Feature 3.1.4: Save cart for later
  - Feature 3.1.5: Apply discount codes

- Feature Group 3.2: Checkout Process
  - Feature 3.2.1: Select shipping address
  - Feature 3.2.2: Choose shipping method
  - Feature 3.2.3: Select payment method
  - Feature 3.2.4: Review order before submission
  - Feature 3.2.5: Complete purchase and receive confirmation

**Major Feature Set 4: Order Processing**
- Feature Group 4.1: Order Management
  - Feature 4.1.1: Track order status
  - Feature 4.1.2: Receive shipping notifications
  - Feature 4.1.3: Download invoice
  - Feature 4.1.4: Cancel order
  - Feature 4.1.5: Request return or exchange

- Feature Group 4.2: Customer Support
  - Feature 4.2.1: Contact customer service
  - Feature 4.2.2: Submit product inquiry
  - Feature 4.2.3: Report delivery issues
  - Feature 4.2.4: Access FAQ section
  - Feature 4.2.5: Chat with support representative

This hierarchical organization follows FDD principles by:
1. Creating business-related feature groupings
2. Breaking features into client-valued functions that can be implemented within two weeks
3. Organizing features in a clear hierarchy for planning and tracking
4. Ensuring each feature provides tangible value to users
5. Creating a structure that supports incremental development

### 10. Illustrate how pair programming helps in reducing bugs.
**Answer:** Illustration of How Pair Programming Reduces Bugs:

**Scenario**: A team is developing a payment processing module for an e-commerce application

**Without Pair Programming**:
Developer Alex works alone on the payment processing code:
1. Alex writes code to handle credit card transactions
2. During implementation, Alex misunderstands how to validate card expiration dates, using MM-DD-YYYY format instead of MM-YYYY
3. Alex overlooks handling decimal places in currency calculations, occasionally causing rounding errors
4. Alex forgets to add validation for card security codes
5. The code passes basic testing because Alex tests with their own valid credit card
6. The bugs are discovered three weeks later during QA testing
7. By this time, Alex has moved on to other features and must context-switch back
8. Fixing the bugs requires substantial rework and delays the release

**With Pair Programming**:
Developers Alex and Jordan work together:
1. Alex drives (writes code) while Jordan navigates (reviews and thinks strategically)
2. When Alex begins implementing expiration date validation, Jordan notices the format issue:
   - Jordan: "Wait, I think card expiration dates are typically just month and year, not the day."
   - Alex: "You're right, let me fix that format to MM-YYYY."
3. As they implement currency calculations, they discuss proper handling:
   - Jordan: "Make sure we're using a decimal type with proper precision for currency."
   - Alex: "Good point, I'll use BigDecimal instead of float to avoid rounding errors."
4. Jordan references the requirements document during implementation:
   - Jordan: "The spec mentions validating the CVV code, but I don't see that in our code yet."
   - Alex: "Let's add that validation before we move on."
5. They take turns writing automated tests, ensuring comprehensive coverage
6. They discuss edge cases together:
   - "What happens if someone enters all zeros as the card number?"
   - "How do we handle expired cards?"
   - "What about international currencies?"
7. The code passes QA with minimal issues, allowing the team to move forward with other features

**Benefits Demonstrated**:
1. **Real-time code review**: Errors caught immediately rather than weeks later
2. **Knowledge sharing**: Jordan's knowledge about financial processing complemented Alex's coding skills
3. **Reduced tunnel vision**: Two sets of eyes spotted issues that one might miss
4. **Better design decisions**: Discussion led to using more appropriate data types
5. **More thorough testing**: Both developers considered different edge cases
6. **Higher code quality**: The final result had fewer bugs and better structure
7. **Reduced technical debt**: Less rework needed later in the development cycle
8. **Shared responsibility**: Both developers understand the code, improving future maintenance

This illustration shows how pair programming shifts bug detection from later phases (QA testing) to the coding phase itself, significantly reducing the cost and time needed to fix issues.

## Analyse (K4) - Break Down, Compare, Contrast

### 1. Analyse the pros and cons of Feature Driven Development vs Scrum.
**Answer:** Analysis of Feature Driven Development (FDD) vs Scrum:

**Pros of FDD:**
1. **Scalability**: FDD was designed for larger teams and projects, making it more suitable for enterprise-level development.
2. **Clear structure**: The five well-defined steps provide a clear roadmap for development.
3. **Feature-focused**: Organization around features makes it easy to track progress and understand what's being delivered.
4. **Domain modeling**: The initial domain modeling phase creates a strong foundation and shared understanding of the problem domain.
5. **Less meeting overhead**: FDD requires fewer meetings compared to Scrum, which can increase productive development time.
6. **Individual ownership**: Class ownership creates clear responsibility and accountability.
7. **Documentation**: FDD produces more documentation, which can be beneficial for regulatory compliance or complex domains.

**Cons of FDD:**
1. **Chief programmer dependency**: Heavy reliance on chief programmers creates potential bottlenecks and key person risks.
2. **Not ideal for small teams**: The specialized roles make FDD less suitable for small teams or projects.
3. **Limited customer involvement**: Less continuous customer involvement compared to Scrum.
4. **Individual vs. collective ownership**: Individual class ownership can create silos of knowledge.
5. **Less adaptable**: More structured approach makes it less flexible for rapidly changing requirements.
6. **Front-loaded design**: The initial domain modeling phase can delay delivery of working software.

**Pros of Scrum:**
1. **Adaptability**: Highly responsive to changing requirements through regular sprint reviews and backlog refinement.
2. **Continuous customer feedback**: Regular sprint reviews ensure customer validation of delivered features.
3. **Team empowerment**: Self-organizing teams have more autonomy and ownership of their work.
4. **Transparency**: Daily stand-ups and visible artifacts create high transparency of progress and impediments.
5. **Regular delivery**: Fixed-length sprints ensure regular delivery of working software.
6. **Simplicity**: Fewer roles and ceremonies make it easier to implement, especially for smaller teams.
7. **Collective ownership**: The entire team owns the product, reducing knowledge silos.

**Cons of Scrum:**
1. **Meeting overhead**: Daily stand-ups, sprint planning, reviews, and retrospectives consume significant time.
2. **Scaling challenges**: Basic Scrum framework requires adaptation for large-scale implementation.
3. **Potential for scope creep**: Product backlog can grow continuously if not managed well.
4. **Role conflicts**: Product Owner might face conflicts between stakeholder demands and team capacity.
5. **Short-term focus**: Sprint-based planning may not emphasize long-term architectural considerations.
6. **Less structure**: Provides less guidance on technical practices compared to FDD.

**Contextual Analysis:**
- **Project size**: FDD is more suitable for larger projects, while Scrum works well for small to medium-sized projects.
- **Team expertise**: FDD requires experienced chief programmers, while Scrum can work with more balanced teams.
- **Domain complexity**: FDD's upfront domain modeling benefits complex problem domains.
- **Change frequency**: Scrum handles frequent requirement changes better than FDD.
- **Documentation needs**: FDD provides more comprehensive documentation for regulatory environments.

While both are Agile frameworks, they represent different approaches to achieving agility. FDD emphasizes feature organization and class ownership within a more structured process, while Scrum focuses on iterative delivery with high customer involvement and team self-organization.

### 2. Compare how risk is handled in traditional and Agile methodologies.
**Answer:** Comparison of Risk Management in Traditional vs. Agile Methodologies:

**Traditional Risk Management:**
1. **Upfront Identification**: Comprehensive risk analysis conducted during initial planning phases.
2. **Documentation**: Formal risk registers with detailed mitigation plans developed early and updated periodically.
3. **Specialized Roles**: Often has dedicated risk managers or committees responsible for risk management.
4. **Preventive Approach**: Focus on anticipating and preventing risks before they occur.
5. **Milestone-Based Review**: Risks reviewed at predefined project milestones.
6. **Change Control**: Formal change control processes to assess risk impact of changes.
7. **Risk Categorization**: Extensive categorization of risks (technical, financial, operational, etc.).
8. **Linear Process**: Sequential risk identification, analysis, response planning, and monitoring.
9. **Detailed Contingency Plans**: Elaborate contingency and fallback plans documented in advance.