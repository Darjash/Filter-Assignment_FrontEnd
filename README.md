# FiltersAssignment

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.3.

## Development server
- Run `npm install`
- Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. 

## Taks

Create an application which has a button to create new filter and representation of already created filters.
Homepage consist of “Add Filter” button and representation of saved filters. If user clicks “Add Filter” button a filter dialog will appear. Representation ofsaved filters can be a table, dashboard or any other way to represent overview.

**Modal dialog functional requirements:**
- (+) button creates new line of filtering criteria
- (-) button deletes criteria
- Filter should contain at least one criteria
****
-There can be 3 types of criteria: 
- Amount with number comparing conditions
- Title with text comparing conditions
- Date with date comparing conditions, date choice can be represented by date picker or 3 combo boxes
****
- Each added criteria default as “Amount” type
- Comparing conditions should correspond to selected criteria type
- Filter dialog should have fixed size and be configurable to operate in modal/non-modal mode
- Let the user resize only the height
- If there are more rows than dialog can fit, scrolling should appear
- In non-modal mode user by clicking “Add Filter” button sees filter dialog as part of page


**Architecture constraints**
- Application backend should be implemented using Spring Boot (3+) and Java 17+
- Application frontend should be implement using any modern JS framework or library (e.g. Angular)
- Application frontend and backend should communicate using REST services and use JSON protocol for data transfer
- Application data should be kept in SQL database (it is “OK” to use H2)
- Application should create all required database schemas, tables and test-data on startup
- Test data should contain at least 2 filters
