# Micronaut QuickStart

- [1. **Install Micronaut CLI (Command Line Interface)**](#1-install-micronaut-cli-command-line-interface)
- [2. **Create a New Micronaut Application**](#2-create-a-new-micronaut-application)
- [3. **Navigate to the Project Directory**](#3-navigate-to-the-project-directory)
- [4. **Run the Micronaut Application**](#4-run-the-micronaut-application)

## 1. **Install Micronaut CLI (Command Line Interface)**

- Unix: use SDKMAN

- Windows: use Chocolatey

```dos
choco install micronaut
```

## 2. **Create a New Micronaut Application**

Use the Micronaut CLI to generate a new Micronaut application.

```dos
mn list-features
mn create-app com.example.myapp
```

<!-- Replace `com.example.myapp` with your desired package name. -->

<!-- The `--features` flag specifies the features you want to include in your project. In this example, I included `micronaut-jdbc-hikari` and `micronaut-hibernate-jpa` for database connectivity using Hibernate and HikariCP. -->

## 3. **Navigate to the Project Directory**

```dos
cd myapp
```

## 4. **Run the Micronaut Application**

Run the Micronaut application using the Gradle wrapper provided in the project.

```dos
gradlew run
```

This will start the Micronaut application, and can be access at `http://localhost:8080`.

Now we can start building the application logic and add additional dependencies/features as needed.
