# PROJECT REQUIREMENTS

**1. User Interface (UI):**
- Create a user-friendly command-line interface (CLI) for the Contact Management System.
- Display a welcoming message and provide a menu with the following options:
        Welcome to the Contact Management System! 

        Menu:
        1. Add a new contact
        2. Edit an existing contact
        3. Delete a contact
        4. Search for a contact
        5. Display all contacts
        6. Export contacts to a text file
        7. Import contacts from a text file *BONUS*
        8. Quit

**2. Contact Data Storage:**
- Use nested dictionaries as the main data structure for storing contact information.
- Each contact should have a unique identifier (e.g., a phone number or email address) as the outer dictionary key.
- Store contact details within the inner dictionary, including:
        1. Name
        2. Phone number
        3. Email address
        4. Additional information (e.g., address, notes).

**3. Menu Actions:**
- Implement the following actions in response to menu selections:
        1. Adding a new contact.
        2. Editing an existing contact's information (name, phone number, email, etc.).
        3. Deleting a contact.
        4. Searching for a contact and displaying their details.
        5. Displaying a list of all contacts.
        6. Exporting contacts to a text file in a structured format.
        7. Importing contacts from a text file and adding them to the system. * BONUS

**4. User Interaction:**
- Utilize input() to enable users to select menu options and provide contact details.
- Implement input validation using regular expressions (regex) to ensure correct formatting of contact information.

**5. Error Handling:**
- Apply error handling using try, except, else, and finally blocks to manage unexpected issues that may arise during execution.

**6. GitHub Repository:**
- Create a GitHub repository for your project.
- Create a clean and interactive README.md file in your GitHub repository.
- Include clear instructions on how to run the application and explanations of its features.
