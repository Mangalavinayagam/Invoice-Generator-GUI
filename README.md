# Invoice-Generator-GUI
This Python Tkinter app creates invoices with customer details, product info, quantity, and price. It validates inputs and saves the information as a .docx file


This code is a GUI application for invoice generation using the tkinter library in Python.

Import the necessary libraries: tkinter for the GUI, docxtpl for creating Word documents, datetime for the datetime operation, and a message box for displaying messages.

The functions used are as follows

clear_item(): Clears the input field and adds new item.

add_item(): Deletes the list and adds a new item

new_invoice(): Clears and resets the invoice field.

generate_invoice(): Creates an invoice file based on given information and saves as .docx file.

To create an invoice:

Add informaton such as First name, last name, phone number, quantity, description, and value of items. Add an item, create an invoice, and a new invoice button.

The invoice generator allows users to enter customer information and add invoice items with quantities, descriptions, and prices. The application then calculates the subtotal, sales tax, and total for the invoice and creates a Word document with the invoice information.

Users can create new invoices and remove lists of invoice items as needed.

The Document Generator File is used to create and save the invoice as a document file
