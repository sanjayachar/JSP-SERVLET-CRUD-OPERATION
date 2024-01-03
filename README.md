# JSP, Servlet, and MySQL CRUD Operation Project

This project demonstrates a basic CRUD operation implementation using JSP, Servlet, and MySQL. It does not use Maven and relies on external JAR files.

## Prerequisites

- Java Development Kit (JDK)
- Apache Tomcat
- MySQL Database
- External JAR files for JDBC connectivity (e.g., `mysql-connector-java-x.x.x.jar`)

## Database Configuration

1. Create a MySQL database and tables. You can use the MySQL workbench software.

2. Update the `UserDAO.java` file with your MySQL database credentials and JDBC steps to connect database.

## External JAR Files

Place the necessary JAR files (e.g., `mysql-connector-java-x.x.x.jar`) in the `WebContent/WEB-INF/lib/` directory.

## Deployment

1. Build your project.

2. Deploy the project to Apache Tomcat.

3. Access the application at `http://localhost:8080/`.

## Usage

- Access the home page (`user-form.jsp`,`user-list.jsp` and `Error.jsp`) to navigate to different CRUD operations.
- Perform CRUD operations using the provided pages.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

