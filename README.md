# **Phone Number Tracker (Python)**

*A simple, console-based **Phone Number Tracker** built using **Python** where the user can enter a phone number, and the program will return information such as the **carrier**, **location**, and **time zone** of the number*.

---

## **Features**

- **Phone Number Parsing**: The program parses the input phone number to extract relevant details.
- **Carrier Information**: Displays the mobile carrier associated with the phone number.
- **Location Information**: Shows the location of the phone number based on the region.
- **Time Zone**: Displays the time zone(s) associated with the phone number.
- **Error Handling**: Handles invalid phone number formats and informs the user.

---

## **How to Use**

1. **Clone the repository** or download the code files.
2. **Run the `phone_tracker.py` file** in the terminal/command line.
3. **Enter the phone number** (including the country code, e.g., `+1` for USA).
4. The program will display:
   - The **carrier** associated with the phone number.
   - The **location** associated with the phone number.
   - The **time zone** based on the phone number’s country.

---

## **Code Flow**

1. **Input Phone Number**: The user inputs a phone number with the country code.
2. **Parse the Number**: The program parses the number using the `phonenumbers` library.
3. **Display Information**: It fetches and displays the carrier, location, and time zone information.
4. **Error Handling**: If the input number is invalid, the program will prompt the user to check the number format.

---

## **Technologies Used**

- **Python 3**: The programming language used for the logic and interactions.
- **phonenumbers**: Python library used to handle phone number parsing and retrieving details like carrier, location, and time zone.
  
  Install the library with:
  ```bash
  pip install phonenumbers
