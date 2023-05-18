# The Contact Manager (TM)
Code Challenge: Contact Management System

You are tasked with building a Contact Management System in Java. The system should allow users to store and manage their contacts. The challenge will test your understanding of basic object-oriented concepts, data structures, and your ability to research and implement a solution.

Requirements:

1. A `Contact` should have the following attributes:
   - `name` (String): The name of the contact.
   - `phoneNumber` (String): The phone number of the contact.
   - `email` (String): The email address of the contact.
   - `address` (String): The address of the contact.

2. The `ContactManager` application manages a collection of contacts. It should implement the following functionalities:
   - `addContact`: Adds a new contact to the collection.
   - `removeContact`: Removes the contact with the specified name from the collection.
   - `searchContact`: Searches for a contact by name and returns the contact if found, or null if not found.
   - `getAllContacts`: Returns a list of all contacts in the collection.

3. Create either a `Main` class that serves as the entry point of your application or something equivalent (e.g. a web app, a mobile app, ...). 
The user interface of your choice (CLI, Web, Mobile, ..) should provide the following options:
   - Add a new contact: Prompt the user to enter the contact details and add it to the contact manager.
   - Remove a contact: Prompt the user to enter the name of the contact to remove and remove it from the contact manager.
   - Search for a contact: Prompt the user to enter the name of the contact to search for and display the contact details if found.
   - Display all contacts: Display a list of all contacts in the contact manager.

No persistence of data between application restarts is required. (i.e. it's ok if when I start the application I see no data every time)

Guidelines:

1. Use appropriate data structures to store the contacts internally.
2. Ensure proper encapsulation of data and use accessors and mutators where necessary.
3. Handle input validation and provide appropriate error messages if needed.
4. Write clean, readable, and well-structured code.
5. Use object-oriented programming principles such as encapsulation, inheritance, and polymorphism where appropriate.

Instructions:

1. Fork this repository and create a new Java project on your local machine.
2. Implement the required functionalitises and user interface.
4. Test your implementation with different scenarios to ensure it works correctly.
5. Commit your code to a Git repository.
6. Include a README file explaining how to compile and run your program.
7. If you encountered any issues or limitations during the challenge, describe them in the README file.

Note: You are allowed to search for information on the internet to learn and implement the required functionality. However, avoid copying code directly without understanding it, and make sure to provide proper attribution if you use any external resources.