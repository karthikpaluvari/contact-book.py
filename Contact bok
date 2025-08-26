class ContactBook:
    def __init__(self):
        self.contacts = {}

    def add_contact(self, name, number):
        self.contacts[name] = number
        print(f"{name}'s contact added successfully!")

    def delete_contact(self, name):
        if name in self.contacts:
            del self.contacts[name]
            print(f"{name}'s contact deleted successfully!")
        else:
            print(f"{name} not found in contacts.")

    def display_contacts(self):
        print("Contacts:")
        for name, number in self.contacts.items():
            print(f"{name}: {number}")

# Example usage
contact_book = ContactBook()

contact_book.add_contact("John Doe", "123-456-7890")
contact_book.add_contact("Jane Smith", "987-654-3210")

contact_book.display_contacts()

contact_book.delete_contact("John Doe")

contact_book.display_contacts()
