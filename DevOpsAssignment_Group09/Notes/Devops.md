# Introduction to DevOps

DevOps is a software development approach that combines **Development (Dev)** and **Operations (Ops)** teams. Its main goal is to improve collaboration, automate processes, and deliver software **faster, more reliably, and continuously**.

Traditionally, developers write and test code while operations teams deploy and maintain it. This separation can cause communication gaps and delays. DevOps brings both teams together throughout the software development lifecycle.

### Key Objectives of DevOps

* **Continuous Integration (CI):** Frequently integrate and test code changes.
* **Continuous Delivery/Deployment (CD):** Deliver tested software quickly and reliably.
* **Automation:** Automate repetitive tasks such as testing, building, and deployment.
* **Collaboration:** Improve communication between development, operations, and other teams.
* **Monitoring:** Continuously monitor applications and infrastructure.
* **Faster Delivery:** Reduce the time required to release new features and fixes.
* **Improved Reliability:** Detect and resolve problems quickly.

### Benefits of DevOps

* Faster software development and delivery
* Better collaboration between teams
* Early detection of bugs
* Reduced manual work
* More reliable releases
* Faster recovery from failures
* Continuous improvement of software

---

# DevOps Lifecycle / Phases

The DevOps lifecycle is a **continuous cycle** in which feedback from one phase is used to improve the next. The major phases are:

**Plan → Code → Build → Test → Release → Deploy → Operate → Monitor → Plan**

## 1. Plan

In the **Planning phase**, teams decide **what needs to be developed and how it should be developed**.

Activities include:

* Understanding customer and business requirements
* Defining project goals
* Creating tasks and user stories
* Estimating time and resources
* Prioritizing features
* Planning upcoming releases

Tools such as **Jira, Trello, and Azure Boards** can be used for planning and task management.

---

## 2. Code

In this phase, developers **write and manage the source code** according to the planned requirements.

Activities include:

* Writing new code
* Modifying existing code
* Using version control systems
* Creating branches for different features
* Reviewing code
* Committing and pushing changes

**Git and GitHub** are commonly used for version control.

---

## 3. Build

The Build phase converts the source code into a **usable software package or application**.

Activities include:

* Compiling the source code
* Installing dependencies
* Creating build artifacts
* Checking whether the code can be successfully built

Build automation helps ensure that every code change can be built consistently.

---

## 4. Test

In the Testing phase, the application is checked to ensure that it works correctly and meets the requirements.

Common testing activities include:

* Unit testing
* Integration testing
* Functional testing
* Regression testing
* Security testing

Automation is commonly used so that tests can run automatically whenever new code is added.

---

## 5. Release

The Release phase prepares a successfully tested build for deployment.

Activities include:

* Approving the build
* Managing release versions
* Preparing release configurations
* Maintaining release records
* Ensuring that the software is ready for deployment

In Continuous Delivery, the software is kept in a deployable state.

---

## 6. Deploy

In the Deployment phase, the application is **installed and made available in the target environment**, such as staging or production.

Activities include:

* Deploying application builds
* Configuring servers and environments
* Updating application versions
* Managing deployment processes
* Using automated deployment pipelines

DevOps aims to make deployments faster and more reliable through automation.

---

## 7. Operate

The Operations phase focuses on **running and maintaining the application** after deployment.

Activities include:

* Managing servers and infrastructure
* Maintaining application availability
* Handling operational issues
* Managing configurations
* Performing backups and maintenance

The goal is to keep the application stable and available to users.

---

## 8. Monitor

In the Monitoring phase, the application's **performance, availability, and health** are continuously observed.

Teams monitor:

* Application performance
* Server and infrastructure health
* Errors and failures
* Response times
* Resource usage
* User experience

Monitoring provides feedback that helps teams identify problems and improve future releases.

---

### 🔄 DevOps Cycle

```text
        PLAN
          ↓
        CODE
          ↓
        BUILD
          ↓
        TEST
          ↓
       RELEASE
          ↓
       DEPLOY
          ↓
       OPERATE
          ↓
       MONITOR
          ↓
       PLAN
```

The cycle is continuous because **monitoring and feedback help teams plan and improve the next version of the software**.
