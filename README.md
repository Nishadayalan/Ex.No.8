# Experiment 8: Prompt Engineering for AI Workflow Automation

### Date: 05-09-2026
### Registration no.: 212223230143

## Aim

To design and demonstrate an AI-powered workflow that automates common documentation and management tasks using structured prompts.

---

## Problem Statement

Managing a college symposium involves several repetitive activities such as writing emails, preparing meeting minutes, planning tasks, creating schedules, documenting requirements, and generating frequently asked questions.

Performing these tasks manually requires considerable time and may result in inconsistent documentation.

This experiment uses **Prompt Engineering** to create structured prompts that automate these activities using an AI system.

---

## Engineering Example

### College Symposium Management

A technical symposium called **TechNova 2026** is considered as the engineering example.

### Event Details

| Parameter             | Details                                                  |
| --------------------- | -------------------------------------------------------- |
| Event Name            | TechNova 2026                                            |
| Event Type            | College Technical Symposium                              |
| Date                  | 20 September 2026                                        |
| Venue                 | College Auditorium and Seminar Halls                     |
| Expected Participants | 500 Students                                             |
| Events                | Paper Presentation, Coding Contest, Project Expo, Quiz   |
| Teams                 | Registration, Technical, Publicity, Hospitality, Finance |

---

# Workflow

The proposed AI workflow follows these steps:

```text
Symposium Information
        ↓
Structured Prompt
        ↓
AI Processing
        ↓
Content Generation
        ↓
Review and Validation
        ↓
Final Document
```

The workflow automates six major activities:

1. Email Writing
2. Meeting Minutes
3. Task Planning
4. Project Scheduling
5. Requirement Documentation
6. FAQ Generation

---

# 1. Email Writing

## Objective

To automatically generate professional emails for students, participants, coordinators, sponsors, and volunteers.

## Structured Prompt

```text
Role:
You are a professional college event communication assistant.

Context:
TechNova 2026 is a technical symposium organized by our college
on 20 September 2026.

Task:
Write an invitation email for college students.

Requirements:
- Include event name and date.
- Mention major events.
- Use a professional but friendly tone.
- Include registration information.
- Keep the email below 200 words.

Output:
Subject + Email Body
```

## Sample Output

**Subject:** Invitation to TechNova 2026 – Technical Symposium

Dear Students,

We are pleased to invite you to TechNova 2026, our upcoming technical symposium on 20 September 2026.

The symposium includes Paper Presentation, Coding Contest, Project Expo, and Technical Quiz. Students can participate individually or as teams depending on the event requirements.

Interested students are requested to complete their registration before the specified deadline.

We look forward to your enthusiastic participation.

Regards,
TechNova 2026 Organizing Team

---

# 2. Meeting Minutes

## Objective

To convert unstructured meeting discussions into formal and organized Minutes of Meeting (MoM).

## Input

```text
Meeting Date: 10 September 2026

Discussion:
- Registration team must finalize participant form.
- Publicity team will create posters.
- Technical team will test coding platform.
- Hospitality team will arrange refreshments.
- Finance team will finalize the budget.
- Next meeting will be held on 15 September.
```

## Structured Prompt

```text
Role:
You are an administrative documentation assistant.

Task:
Convert the following meeting discussion into formal Minutes of Meeting.

Include:
1. Meeting date
2. Main discussion points
3. Decisions taken
4. Action items
5. Responsible team
6. Deadline

Use a clear table wherever appropriate.
```

## Sample Output

| Action Item                | Responsible Team | Deadline |
| -------------------------- | ---------------- | -------- |
| Finalize registration form | Registration     | 12 Sept  |
| Design promotional posters | Publicity        | 13 Sept  |
| Test coding platform       | Technical        | 14 Sept  |
| Arrange refreshments       | Hospitality      | 18 Sept  |
| Finalize budget            | Finance          | 14 Sept  |

---

# 3. Task Planning

## Objective

To divide the symposium activities into manageable tasks and assign responsibilities to different teams.

## Structured Prompt

```text
Role:
You are a project management assistant.

Task:
Create a task plan for organizing a college technical symposium.

Teams:
Registration, Technical, Publicity, Hospitality, Finance.

For each task provide:
- Task name
- Responsible team
- Priority
- Deadline
- Expected output

Organize the tasks according to priority.
```

## Sample Output

| Task                     | Team         | Priority | Deadline |
| ------------------------ | ------------ | -------- | -------- |
| Create registration form | Registration | High     | Sept 10  |
| Publish event poster     | Publicity    | High     | Sept 11  |
| Confirm judges           | Technical    | High     | Sept 12  |
| Arrange refreshments     | Hospitality  | Medium   | Sept 18  |
| Finalize budget          | Finance      | High     | Sept 14  |

---

# 4. Project Scheduling

## Objective

To generate a timeline for completing all symposium activities before the event date.

## Structured Prompt

```text
Role:
You are an event scheduling assistant.

Event Date:
20 September 2026

Create a schedule from 1 September to 20 September.

Include:
- Activity
- Start date
- End date
- Responsible team
- Dependency

Ensure that important tasks are completed before dependent activities begin.
```

## Sample Output

| Activity           | Start Date | End Date | Responsible Team |
| ------------------ | ---------- | -------- | ---------------- |
| Event Planning     | Sept 1     | Sept 3   | Core Team        |
| Registration Setup | Sept 4     | Sept 6   | Registration     |
| Publicity Campaign | Sept 7     | Sept 15  | Publicity        |
| Judge Confirmation | Sept 8     | Sept 12  | Technical        |
| Venue Preparation  | Sept 16    | Sept 19  | Hospitality      |
| Final Testing      | Sept 19    | Sept 19  | Technical        |
| Symposium          | Sept 20    | Sept 20  | All Teams        |

---

# 5. Requirement Documentation

## Objective

To automatically create a structured requirement document for the symposium management system.

## Structured Prompt

```text
Role:
You are a requirements analyst.

Project:
College Technical Symposium – TechNova 2026

Create a requirement document containing:

1. Project objective
2. Functional requirements
3. Non-functional requirements
4. Hardware requirements
5. Software requirements
6. User roles
7. Constraints

Present the requirements clearly using headings and tables.
```

## Sample Output

### Functional Requirements

* Student registration
* Event selection
* Participant management
* Attendance tracking
* Certificate generation
* Event result management

### Non-Functional Requirements

* Easy to use
* Secure participant data
* Reliable during registration
* Fast response time
* Mobile-friendly interface

### User Roles

* Administrator
* Event Coordinator
* Volunteer
* Participant
* Judge

---

# 6. FAQ Generation

## Objective

To automatically generate frequently asked questions and answers for symposium participants.

## Structured Prompt

```text
Role:
You are a college event support assistant.

Context:
TechNova 2026 is a college technical symposium.

Task:
Generate 10 frequently asked questions for participants.

Cover:
- Registration
- Eligibility
- Event timings
- Team size
- Venue
- Certificates
- Food
- Contact information

Provide each question with a short and clear answer.
```

## Sample Output

### Q1. Who can participate in TechNova 2026?

Students who meet the eligibility requirements can participate.

### Q2. What events are available?

Paper Presentation, Coding Contest, Project Expo, and Technical Quiz.

### Q3. Where will the symposium be conducted?

The event will be conducted in the college auditorium and seminar halls.

### Q4. Will participants receive certificates?

Yes, eligible participants will receive participation certificates.

---

# Prompt Engineering Techniques Used

| Technique          | Application                                                                    |
| ------------------ | ------------------------------------------------------------------------------ |
| Role Prompting     | Defines the AI's role as an event manager, analyst, or communication assistant |
| Context Setting    | Provides relevant symposium information                                        |
| Clear Instructions | Specifies exactly what the AI should generate                                  |
| Output Formatting  | Requests tables, headings, and structured responses                            |
| Constraints        | Controls word count and required information                                   |
| Few-Shot Prompting | Examples can be provided to guide the expected output                          |
| Task Decomposition | Breaks a large management task into smaller tasks                              |

---

---

# Result

The AI workflow successfully demonstrates the automation of:

* Email Writing
* Meeting Minutes
* Task Planning
* Project Scheduling
* Requirement Documentation
* FAQ Generation

using structured prompts.

---

# Conclusion

Prompt Engineering can transform an AI system from a simple text-generation tool into a useful workflow automation assistant.

By providing a clear role, context, task, constraints, and output format, AI can generate consistent and structured content for different stages of college symposium management.

The experiment demonstrates that structured prompting can reduce manual effort, improve productivity, and support efficient management of complex activities.


---

