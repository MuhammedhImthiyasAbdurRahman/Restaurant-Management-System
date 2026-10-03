# Restaurant Management System

**Java · Swing · NetBeans GUI forms · JDBC · Apache Derby**

An academic desktop application exploring restaurant workflows through a collection of Java Swing screens.

## Project overview

The source includes user and administrator login, registration, order management, billing, table reservation and print-oriented screens. It demonstrates desktop UI development and JDBC integration.

| Workflow | Source files |
| --- | --- |
| Startup and navigation | `Startup.java`, `MainMenu.java` |
| Login and registration | `Login.java`, `AdminLogin.java`, `Registration.java` |
| Orders | `OrderManagement.java`, `OderPrint.java` |
| Billing | `BillingManagement.java`, `BillingPrint.java` |
| Reservations | `TableReservation.java`, `TablePrint1.java` |

## Repository layout

```text
rms/
  *.java      Java source, in the rms package
  *.form      NetBeans GUI designer forms
  *.jpg       UI background assets
  rms.java    Application entry point
```

## Set up for development

1. Clone or download the repository.
2. Create a Java application project in NetBeans and place the `rms` directory beneath its source root.
3. Include the NetBeans **AbsoluteLayout** library and the **Apache Derby network client** JDBC driver.
4. Configure a local Derby database. The existing source expects a database named `RMS DB` on `localhost:1527`.
5. Review the SQL queries to reconstruct the required schema and replace the original demo connection settings with your local settings.
6. Check image resource paths, then launch the `rms.rms` main class.

## Current status

This is an academic source archive. The repository does not currently include database schema scripts, a complete build configuration or a verified end-to-end setup. The steps above describe the dependencies found in the source; a successful run has not been verified during this documentation update.

The bundled JPG files are UI assets, rather than captured screenshots of a running application. The original login code also uses hard-coded demo database settings; these should be moved into local configuration before further development.

## Suggested improvements

- Add a reproducible build and database schema with sample data.
- Replace machine-specific resource paths with packaged resources.
- Add screenshots of each running workflow.
- Improve input validation, authentication and database query handling.

## Author

**Abdur Rahman Imthiyas** · [Portfolio](https://abdurrahmanimthiyas.wordpress.com/) · [LinkedIn](https://www.linkedin.com/in/muhammedh-imthiyas-abdur-rahman-606a4a245)
