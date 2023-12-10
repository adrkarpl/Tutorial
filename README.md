# Project Name

_'Alfred'_ the CLI Bot assistant.
![Alfred-sign](https://github.com/rafalradx/alfred-assist-bot/tree/main/alfred/Alfred.jpg)

<!-- trzeba sprawdzić ścieżkę dostępu -->

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Screenshots](#screenshots)
- [Setup](#setup)
- [Usage](#usage)
- [Project Status](#project-status)
- [Room for Improvement](#room-for-improvement)
- [Contributing](#contributing)
- [Info](#info)
- [Contact](#contact)
- [License](#license)

## General Information

_Alfred_ streamlines the management of your address book, offering a comprehensive set of features that empower users to add, edit, delete, search, and organize contacts with ease. The inclusion of birthday notifications, tags, and notes enhances the overall utility of the address book, making Alfred a valuable tool for effective contact management.
Alfred is designed with a user-friendly command-line interface for intuitive interaction. The command-line interface simplifies user commands and makes the address book management process efficient and accessible.

## Technologies Used

Python 3.11.5

No additional configurations are required. _Alfred_ stores the address book data locally.

<!-- czy taka wersja? -->

## Features

_Alfred_ provides a range of essential functionalities for managing your address book effectively. Here's an expanded overview of its capabilities:

    1. Adding Contacts - allows users to seamlessly add new contacts to their address book.
    2. Editing Contacts - users can easily modify contact details, such as phone numbers, email addresses, birthdays, addresses, tags, and notes.
    3. Deleting Contacts - enables users to remove contacts from the address book when they are no longer relevant or needed.
    4. Searching Contacts - allows users to quickly find specific contacts.
    5. Birthday Notifications - a convenient way to check the days remaining until the birthday of a specified contact.
    6. Upcoming Birthdays - enable users to check and plan for upcoming birthdays within a specified timeframe.
    7. Tagging Contacts - allows users to assign tags to contacts for easy categorization and grouping.
    8. Adding Notes - users can attach notes to contacts, providing additional information or context.

## Screenshots

![Alfred-show-all](https://github.com/rafalradx/alfred-assist-bot/tree/main/alfred/show_all.jpg)
![Alfred-birthdays](https://github.com/rafalradx/alfred-assist-bot/tree/main/alfred/birthdays.jpg)
![Alfred-show_notes](https://github.com/rafalradx/alfred-assist-bot/tree/main/alfred/show_notes.jpg)

<!-- trzeba sprawdzić ścieżkę dostępu -->

## Setup

1. **Clone the Repository:**

   - Clone this repository to your local machine using the following command:
     ```
     git clone [repository_url]
     ```

2. **Setup the Application:**

   - Navigate to the project directory:
     ```
     cd address-book-application
     ```
   - Run the following command to set up the application:
     ```
     python setup.py install
     ```

3. **Run the Application:**
   - Start the Address Book application using the following command:
     ```
     alfred-run
     ```
   - Follow the on-screen instructions to interact with the application.

## Usage

Follow the prompts to perform various operations on your address book.
Enter commands as instructed to manage your contacts effectively.

- `hello`: Start the interaction with a friendly greeting.
- `find`: Look up a contact by name.
- `search`: Find contacts using a keyword.
- `search notes`: Find a contact name by entering a keyword in tags or notes.
- `show all`: Display all contacts in the address book.
- `show`: Display a specified number of contacts from the address book.
- `add`: Add a new contact to the address book.
- `birthday`: Display the days until a contact's birthday.
- `upcoming birthdays`: Check upcoming birthdays within a specified timeframe.
- `edit phone`: Change a contact's phone number.
- `edit email`: Change a contact's email address.
- `edit birthday`: Change a contact's birthday.
- `edit address`: Change a contact's address.
- `edit tag`: Change a contact's tag.
- `edit notes`: Change a contact's notes.
- `delete contact`: Remove a contact from the address book.
- `delete phone`: Delete a contact's phone number.
- `delete email`: Delete a contact's email address.
- `delete birthday`: Delete a contact's birthday.
- `delete address`: Delete a contact's address.
- `delete tag`: Delete a contact's tag.
- `delete notes`: Delete a contact's notes.
- `good bye`, `close`, `exit`, `.`: Say goodbye and exit the program.

## Project Status

Current project version: 1.0.0
Project is: _in progress_.

## Room for Improvement

1. Database Interaction: Enhance by incorporating database support for persistent storage and retrieval of contacts
2. Data Export and Import: Allow users to export and import data, facilitating seamless data transfer between different program installations.
3. Advanced Search: Expand search functionality to enable users to perform more precise searches, such as by partial phone numbers, emails, or addresses.
4. Image Attachment: Introduce the capability to add images to contacts for easier identification.
5. Integration with External Sources: Add an automatic contact information completion feature by leveraging external sources through web service APIs.
6. External Communication: Transition Alfred into a server mode to enable remote access to functions via an API, useful for integration with other tools.
7. Authentication and Security: Implement user authentication features and secure access to editing or deletion functions with a password.
8. Activity History: Allow users to track the history of changes for each contact, facilitating monitoring of who made edits and when.
9. Command Extensions: Provide an easy way to add new commands and extend Alfred's capabilities without modifying existing code.

## Contributing

If you would like to contribute to the project, please fork the repository and submit a pull request with your change.

## Info

This project was completed during the "Python Developer" course organized by GOIT POLSKA Sp. z o.o.

## Contact

Created by **'Gotham Devs'**
**Katarzyna Drajok** _katarzyna.drajok@gmail.com_
**Katarzyna Czempiel** _katarzyna.czempiel@gmail.com_
**Rafał Pietras** _rafal.radx@gmail.com_
**Dawid Radzimski** _dawid.radzimski@gmail.com_
**Adrian Karwat** _adr.karwat@gmail.com_

Feel free to contact us!
Thank you for using _Alfred_!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

<!-- czy to pisać? czy dodajemy plik z licencją? -->
