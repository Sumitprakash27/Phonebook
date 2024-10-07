# Phonebook

Hii everyone,
Made by Sumitprakash27.


Features of the Phonebook Application
Linked List Data Structure:

Contacts are stored using a linked list, allowing efficient addition and removal of contacts.
Contact Management:

Add Contact: Users can add new contacts by providing a name and a number.
Remove Contact: Users can remove contacts by searching for them using either the name or the number.
Search Contact: Users can search for contacts by entering a partial name, which shows a list of matching contacts. This provides functionality similar to autocomplete.
Duplicate Name Handling:

The application checks for existing contacts with the same name before adding a new one.
If a duplicate is found, the user is prompted to either update the existing contact or create a new one with a modified name (e.g., "Sumit" becomes "Sumit2").
Persistence:

Contacts are saved to a JSON file (contacts.json) when the application closes, ensuring that data is not lost between sessions.
The application can load existing contacts from the JSON file upon startup.
Graphical User Interface (GUI):

Built using the tkinter library, the GUI allows users to interact with the phonebook easily.
Input fields for adding and searching contacts, as well as buttons for adding, removing, and displaying contacts.
Display of Contacts:

A text area in the GUI shows all contacts, allowing users to view their phonebook at a glance.
The contact display updates dynamically as contacts are added or removed.
User Notifications:

The application uses message boxes to notify users about successful additions, updates, removals, and warnings for incorrect inputs.
Efficient Data Handling:

The linked list allows for efficient addition and removal of contacts, while searching for contacts is optimized using linear search methods.
