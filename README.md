
### Technical Task Description

#### 1. Contacts

To store the contacts in your system, you need to organize a database that will contain all the necessary information.

This information should include:

- First Name
- Last Name
- Email Address
- Phone Number
- Birthdate
- Additional Data (optional)

#### 2. API

The API you develop should support basic data operations. Below is a list of actions that your API should be able to perform:

- Create a new contact
- Get a list of all contacts
- Get a single contact by ID
- Update an existing contact
- Delete a contact

#### 3. CRUD API

In addition to the basic functionality, the CRUD API should also have the following features:

- Contacts should be searchable by first name, last name, or email address (via query parameters).
- The API should be able to return a list of contacts with birthdays in the next 7 days.

---

### General Requirements for the Homework Assignment

- Use the **FastAPI** framework to create the API.
- Use the **SQLAlchemy ORM** to interact with the database.
- Use **PostgreSQL** as the database.
- Support CRUD operations for contacts.
- Support storing contact birthdates.
- Provide **Swagger** documentation for the REST API.
- Use the **Pydantic** module for data validation.

