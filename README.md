# FinancialAdvisorManagement


The Financial Advisor Management System is a web application designed to help financial advisors manage their clients and their clients' portfolios. The system allows advisors to create, update, and remove clients, as well as manage the securities in each client's portfolio.

## Features

- Create, update, and delete clients.
- Manage client portfolios.
- Add, update, and remove securities in client portfolios.
- React dashboard for user interface.
- Spring framework for backend.
- Relational database for data storage.
- Highly scalable and 99% uptime.

## Technologies Used

- Java (Spring Framework)
- React.js
- Hibernate (JPA)
- MySQL (or any other relational database)

## Getting Started

### Prerequisites

To run this project, you will need:

- Java JDK 11 or higher
- Node.js and npm
- MySQL (or any other relational database)

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/yourusername/FinancialAdvisorManagement.git
    cd FinancialAdvisorManagement
    ```

2. **Backend setup:**

    - Open the project in your favorite IDE (e.g., IntelliJ IDEA, Eclipse).
    - Configure your database connection in `src/main/resources/application.properties`:

    ```properties
    spring.datasource.url=jdbc:mysql://localhost:3306/yourdatabase
    spring.datasource.username=yourusername
    spring.datasource.password=yourpassword
    spring.jpa.hibernate.ddl-auto=update
    ```

    - Build and run the Spring Boot application:

    ```sh
    ./mvnw spring-boot:run
    ```

3. **Frontend setup:**

    - Navigate to the `frontend` directory:

    ```sh
    cd frontend
    ```

    - Install the dependencies:

    ```sh
    npm install
    ```

    - Start the React development server:

    ```sh
    npm start
    ```

4. **Access the application:**

    Open your web browser and go to `http://localhost:3000`.

## Usage

1. **Login:**
   - Financial advisors can log in to access their dashboard.

2. **Manage Clients:**
   - Add new clients using the "Add Client" button.
   - Update client information by selecting a client and editing their details.
   - Delete clients as needed.

3. **Manage Portfolios:**
   - View client portfolios by selecting a client.
   - Add, update, and remove securities in the portfolios.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the code style and add tests for your changes.


