# Event Ticket Platform

<img width="1024" height="576" alt="organizers-landing-hero" src="https://github.com/user-attachments/assets/4f5e4436-1f22-409f-a883-fe4791fbedd7" />


A scalable event management and ticketing platform built using Spring Boot, JPA/Hibernate, PostgreSQL, and Keycloak. Enables organizers to create events, attendees to book tickets, and staff to validate entries, all with enterprise-grade security and real-time data analytics.

## Features

- **Event Management:** Organizers can create, edit, list, and delete events, set up multiple ticket types, and manage ticket inventory.
- **Ticket Booking:** Attendees can search published events, purchase tickets, access QR-code tickets, and view purchase history.
- **Secure Authentication:** Role-based access control with Spring Security and Keycloak (JWT & OAuth2) for organizers, attendees, and staff.
- **Ticket Validation:** Staff can validate tickets via QR code scanning, ensuring fast and accurate event entry.
- **Real-Time Reporting:** Automated sales and attendance dashboards for organizers.
- **Scalable Backend:** Optimized with Docker containerization, MapStruct for object mapping, and Lombok to reduce boilerplate code.

## Tech Stack

- **Backend:** Spring Boot, JPA/Hibernate, PostgreSQL
- **Security:** Spring Security, Keycloak, JWT, OAuth2
- **Frontend:** React (reference implementation)
- **Deployment:** Docker, Adminer for DB management
- **Development Tools:** MapStruct, Lombok, Maven

## Getting Started

### Prerequisites

- Java 21+
- Maven 3.8+
- Docker
- Node.js (for frontend)
- Keycloak (configured with required roles/users)

## API Endpoints

- **Events:** `/api/v1/events`
- **Tickets:** `/api/v1/tickets`
- **Published Events:** `/api/v1/published-events`
- **Ticket Validation:** `/api/v1/ticket-validations`

  ---

## 👨‍💻 Author 
### Mahalakshmu
### GitHub:  Maha-412
