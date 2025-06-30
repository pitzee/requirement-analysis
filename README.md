# requirement-analysis
Requirement Analysis in Software Development.

## 📌 Purpose

The main goal of this repository is to:

- Understand the importance of requirement analysis.
- Document methods and techniques used for gathering and analyzing requirements.
- Share examples, templates, and best practices.
- Provide learning resources for students and professionals in software engineering.

# Requirement Analysis in Software Development

Welcome to the **Requirement Analysis in Software Development** repository.  
This repository is created to explore and document the critical phase of **requirement analysis** in the Software Development Life Cycle (SDLC).

## 📌 Purpose

The main goal of this repository is to:

- Understand the importance of requirement analysis.
- Document methods and techniques used for gathering and analyzing requirements.
- Share examples, templates, and best practices.
- Provide learning resources for students and professionals in software engineering.

## 🧠 What is Requirement Analysis?

**Requirement Analysis** is the process of identifying, gathering, and documenting the functional and non-functional requirements of a software system. It serves as the foundation for designing, developing, and testing software that meets users’ needs and business goals.

This phase involves close collaboration between stakeholders, such as clients, end-users, project managers, and software engineers. Techniques like interviews, questionnaires, workshops, and document analysis are often used to extract detailed requirements.

### 🔍 Importance in the SDLC

Requirement analysis plays a crucial role in the **Software Development Life Cycle (SDLC)** because:

- It ensures a clear understanding of what the system must do.
- It helps avoid costly rework by catching issues early.
- It aligns the development team’s efforts with business objectives.
- It provides a basis for project planning, design, coding, and testing.

## 🛠️ Key Activities in Requirement Analysis

The Requirement Analysis phase involves several essential activities that help ensure the software meets the intended goals and user expectations. Below are the five key activities:

- **Requirement Gathering**
  - Involves collecting requirements from stakeholders such as clients, users, and subject matter experts.
  - Utilizes tools like surveys, interviews, observation, and existing documentation.

- **Requirement Elicitation**
  - Focuses on uncovering and clarifying requirements that stakeholders may not explicitly state.
  - Techniques include brainstorming sessions, use cases, and role-playing to draw out hidden or implicit needs.

- **Requirement Documentation**
  - All collected and elicited requirements are clearly documented in a structured format.
  - Common documents include Software Requirement Specifications (SRS), user stories, and functional specifications.

- **Requirement Analysis and Modeling**
  - Requirements are analyzed for feasibility, clarity, completeness, and consistency.
  - Visual models like Data Flow Diagrams (DFDs), UML diagrams, and process models are created to better understand and communicate the requirements.

- **Requirement Validation**
  - Ensures that the documented requirements accurately reflect stakeholder needs.
  - Involves stakeholder reviews, requirement walk-throughs, and prototyping to confirm correctness and completeness.

These activities help ensure a shared understanding of what the software should do, reducing misunderstandings and increasing project success.

## 📂 Types of Requirements

In software engineering, requirements are generally classified into two main types: **Functional Requirements** and **Non-functional Requirements**. Both are essential for building a complete and reliable system.

### ✅ Functional Requirements

Functional requirements describe **what the system should do**. They define the core functions and features of the software.

**Examples for a Booking Management System:**
- Users should be able to create an account and log in.
- The system must allow users to search available rooms based on date and location.
- Users should be able to make, modify, or cancel bookings.
- Admins should be able to add, edit, or remove booking listings.
- The system must send email confirmations after successful bookings.

### ⚙️ Non-functional Requirements

Non-functional requirements describe **how the system should behave**. They focus on performance, usability, reliability, and other quality attributes.

**Examples for a Booking Management System:**
- The system should load booking search results in under 2 seconds.
- It must be available 99.9% of the time throughout the year.
- User data should be encrypted and comply with data protection laws.
- The system should support up to 10,000 concurrent users.
- The user interface must be accessible and responsive on all devices.

## 📊 Use Case Diagrams

A **Use Case Diagram** is a visual representation that shows the interactions between users (called actors) and the system. It is used in requirement analysis to clarify system behavior from a user's point of view.

### 🔍 Benefits of Use Case Diagrams:
- Help identify all user interactions with the system.
- Provide a high-level overview of system functionality.
- Facilitate communication between stakeholders and developers.
- Assist in identifying missing requirements early in the development process.

## Why is Requirement Analysis Important?
Requirement Analysis is a crucial phase in the Software Development Life Cycle (SDLC) because it sets the foundation for all subsequent stages. Here are three key reasons why it is essential:

Clear Understanding of Stakeholder Needs
Requirement analysis ensures that developers and stakeholders have a shared understanding of what the system should do. This minimizes confusion and helps prevent costly misunderstandings later in the development process.

Prevents Scope Creep
By clearly defining and documenting requirements early, teams can avoid unplanned features and changes. This helps keep the project within budget, on time, and aligned with business objectives.

Improves Quality and Reduces Rework
Well-analyzed and validated requirements lead to better system design and fewer defects. This reduces the need for rework during testing or after deployment, saving both time and resources.



### 🧾 Use Case Diagram: Booking Management System

Below is a use case diagram for a typical booking management system. It highlights key actors and their interactions with the system.

## ✅ Acceptance Criteria

**Acceptance Criteria** are a set of predefined conditions that a software product must meet to be accepted by stakeholders. They define the boundaries and expected behavior of a feature, ensuring that developers and stakeholders have a shared understanding of what "done" means.

### 🧠 Importance of Acceptance Criteria

- **Clarity**: They eliminate ambiguity by clearly stating what is expected.
- **Testability**: They serve as the basis for creating test cases.
- **Scope Control**: Help prevent scope creep by defining precise conditions for feature completion.
- **Stakeholder Alignment**: Ensure that both technical teams and business users agree on feature functionality.

### 🧾 Example: Checkout Feature – Booking Management System

**Feature**: Checkout (Confirm Booking & Payment)

**Acceptance Criteria:**

- ✅ User must be logged in to proceed to checkout.
- ✅ User can view a summary of selected booking details (e.g., room, dates, price).
- ✅ User can select or input payment method (credit card, PayPal, etc.).
- ✅ System should validate payment and display a success or failure message.
- ✅ On successful payment, a confirmation email is sent to the user.
- ✅ Booking status is updated to "Confirmed" in the system.
