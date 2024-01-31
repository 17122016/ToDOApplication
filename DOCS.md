# Project Name Documentation

## Technologies Used

- **Programming Language:** [Java](https://www.java.com/)
- **Framework:** [Spring Boot](https://spring.io/projects/spring-boot)
- **Database:** [MySQL](https://www.mysql.com/) (or replace with your database)
- **ORM:** [Hibernate](https://hibernate.org/)

## Prerequisites

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) installed
- [Apache Maven](https://maven.apache.org/) for building and managing the project
- [MySQL Server](https://www.mysql.com/) installed (or replace with your preferred database)

## How to Run Locally

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/17122016/ToDOApplication.git
    cd ToDOApplication
    ```

2. **Configure Database:**

    - Create a database in your MySQL server.
    - Update the database configuration in `src/main/resources/application.properties`:

        ```properties
        spring.datasource.url=jdbc:mysql://localhost:3306/your_database_name
        spring.datasource.username=your_username
        spring.datasource.password=your_password
        ```

3. **Build and Run the Application:**

    ```bash
    mvn clean install
    java -jar target/your-application-name.jar
    ```

    Replace `your-application-name` with the actual name of your application JAR file.

4. **Access the Application:**

    Open your web browser and navigate to [http://localhost:8080](http://localhost:8080)

5. **Usage:**

    Provide instructions on how to use the application. For example, how to create, update, and delete tasks in a ToDo application.



