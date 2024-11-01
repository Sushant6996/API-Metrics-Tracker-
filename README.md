
Project Description: API Metrics Tracker
The API Metrics Tracker is a web application designed to log, store, and visualize metrics from various APIs, allowing developers to monitor performance and reliability. It captures essential data points such as API name, request count, minimum response time, maximum response time, and average response time, providing valuable insights for optimizing API usage.

Utilizing PostgreSQL for data persistence, the application securely stores logged metrics and simplifies data management with Spring Data JPA. A Looker Dashboard is employed for data visualization, presenting interactive charts and graphs to help identify trends and bottlenecks.

To ensure security, the application incorporates Spring Security for user authentication and authorization, allowing only authorized users to log metrics. Input data is validated using Bean Validation, maintaining data integrity before storage.

The application features dynamic API monitoring, aggregating metrics and computing statistics for comprehensive performance analysis. With tools like Spring Boot DevTools, developers can experience enhanced productivity through rapid application restarts and live reloading.
