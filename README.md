
# PrepTrack — Placement Preparation & Interview Tracking Platform

PrepTrack is a placement companion designed to help freshers organize technical preparation, track job applications, and manage upcoming interview rounds in one place.

Unlike a standalone question-practice application, PrepTrack aims to connect preparation progress with real job applications and interview schedules, helping students prioritize what to prepare based on the round type and time remaining.

**Project Status:** 🚧 In Development

## Problem Statement

Freshers often manage interview preparation, job applications, and interview schedules using separate platforms and spreadsheets. This makes it difficult to track preparation progress, identify weak areas, and plan revision when an interview is scheduled at short notice.

PrepTrack aims to bring these activities together in one platform.

## Planned Features

- **Topic-wise Question Bank:** Organize technical questions by topic and difficulty.
- **Preparation Tracking:** Record question attempts and monitor progress.
- **Job Application Management:** Track companies, application dates, and statuses.
- **Interview Round Tracking:** Manage aptitude, coding, technical, and HR rounds.
- **Time-Aware Preparation:** Prioritize revision based on round type and time remaining.
- **Automated Reminders:** Get reminders for upcoming interview rounds.
- **Role-Based Access:** Separate student and administrator permissions.
- **Performance Insights:** Identify weak topics using question-attempt history.
- **AI-Assisted Preparation (Future Scope):** Explore personalized recommendations using student progress and interview details.

## Tech Stack

| Technology | Purpose |
|---|---|
| Java | Backend programming |
| Spring Boot | REST API development |
| Spring Data JPA | Data access |
| Hibernate | Object-relational mapping |
| PostgreSQL | Relational database |
| Spring Security & JWT | Authentication and authorization |
| Bean Validation | Request validation |
| JUnit & Mockito | Automated testing |
| Maven | Build and dependency management |
| Postman | API testing |
| HTML, CSS & JavaScript | Frontend |
| Git & GitHub | Version control |

*Technologies will be integrated progressively during development.*

## Backend Engineering Focus

- Layered architecture: Controller, Service, and Repository
- Relational database design and entity relationships
- DTO-based request and response handling
- Input validation and global exception handling
- Authentication, role-based authorization, and data ownership
- Pagination, filtering, and database indexing
- Transaction management and application status transitions
- Scheduled jobs and reliable reminders
- Unit and integration testing
- Docker and deployment

## Development Roadmap

| Version | Scope | Status |
|---|---|---|
| V1 | Topic and question management with PostgreSQL | In Progress |
| V2 | Authentication, authorization, and validation | Planned |
| V3 | Attempts, progress tracking, applications, interview rounds, and reminders | Planned |
| V4 | Automated testing, Docker, and deployment | Planned |
| V5 | Optional AI-assisted preparation | Future Scope |

## Getting Started

### Prerequisites

- Java (compatible with the configured Spring Boot version)
- Maven
- PostgreSQL
- Git

### Setup

Setup instructions and run commands will be added once the initial version is ready to run locally.

The intended setup process is:

1. Clone the repository.
2. Create a PostgreSQL database.
3. Configure database credentials securely using environment variables or local configuration.
4. Build the application with Maven.
5. Run the Spring Boot application.
6. Test the REST APIs using Postman.

## Learning Objectives

This project is being developed to gain practical experience in Java backend development, REST API design, relational database modeling, application security, testing, and maintainable software architecture.

The goal is to understand and justify engineering decisions rather than simply implement features.

## Future Scope

- Personalized revision recommendations based on performance
- Preparation plans based on target job roles
- Optional LLM integration for context-aware preparation guidance
- Public deployment and a live demonstration

## Author

**Sayali Pawar**

GitHub: [Sayali-04](https://github.com/Sayali-04)

---

*This project is actively under development. Features, setup instructions, and documentation will be updated as implementation progresses.*
