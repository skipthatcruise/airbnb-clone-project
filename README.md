# airbnb-clone-project
This is the repository for the airbnb clone project for Alx pro dev course
The goal of this project is to create an airbnb clone, ny uding django, MYSQL, GRAPHQL

Team Roles
1. Backend Developer: The backend developer will be responsible for implementing the API endpoints, database schemas, and business logic for the airbnb project.
2. Database Administrator: The database administrator will manage the database design, indexing, and optimizations for the project.
3. DevOps Engineer: The DevOps engineer will handle the deployment, monitoring, and scaling of the backend services.
4. QA Engineer: The QA Enginerr will ensure the backend functionalities are thoroughly tested and meet quality. standards.

Technology Stack
1. Django: A high-level Python web framework used for building the RESTful API.
2. Django REST Framework: Provides tools for creating and managing RESTful APIs.
3. PostgreSQL: A powerful relational database used for data storage.
4. GraphQL: Allows for flexible and efficient querying of data.
5. Celery: For handling asynchronous tasks such as sending notifications or processing payments.
6. Redis: Used for caching and session management.
7. Docker: Containerization tool for consistent development and deployment environments.
8. CI/CD Pipelines: Automated pipelines for testing and deploying code changes.

Database Design
1. User ↔ Property:
One user (host) can have many properties.
User (1) → (∞) Property

2. User ↔ Booking:
One user (guest) can make many bookings.
User (1) → (∞) Booking

3. Property ↔ Booking:
One property can have many bookings over time.
Property (1) → (∞) Booking

4. Booking ↔ Payment:
One booking has one corresponding payment.
Booking (1) → (1) Payment

5. Property ↔ Review:
One property can have many reviews.
Property (1) → (∞) Review

6. User ↔ Review:
One user (guest) can write many reviews.
User (1) → (∞) Review


