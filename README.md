# WhatsApp Broadcast

A simple and efficient tool for broadcasting messages via WhatsApp using the WhatsApp Web interface. This project is designed to help businesses or individuals send bulk messages to multiple recipients without violating WhatsApp's terms of service.

---

## Features
- Send personalized messages to a list of contacts.
- Easy-to-use interface.
- Supports importing contacts from a CSV file.
- Message scheduling for automated delivery.
- Logs for sent messages.

---

## Prerequisites
- A WhatsApp account.
- Node.js installed on your system.
- Google Chrome or any Chromium-based browser.
- Puppeteer library for browser automation.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/whatsapp-broadcast.git
   cd whatsapp-broadcast
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Configure the `.env` file:
   Create a `.env` file in the root directory and add your configuration variables:
   ```env
   WHATSAPP_BROWSER_PATH=/path/to/your/chrome/browser
   MESSAGE_TEMPLATE_PATH=./templates/message.txt
   CONTACTS_FILE_PATH=./contacts/contacts.csv
   ```

---

## Usage

1. Prepare your contact list:
   - Create a `contacts.csv` file with the following structure:
     ```csv
     name,phone
     John Doe,+123456789
     Jane Smith,+987654321
     ```

2. Create a message template:
   - Write your message in a plain text file (e.g., `message.txt`) and use placeholders for personalization:
     ```
     Hello {{name}},

     This is a test broadcast message.

     Regards,
     Your Company
     ```

3. Visit the tool:
   - You can find the tool at [your-link-here](#).
   - If you need login credentials, please DM or email me at your-email@example.com.

4. Run the tool:
   ```bash
   npm start
   ```

5. Follow the instructions in the terminal to connect your WhatsApp account and start broadcasting messages.

---

## Logging
All sent messages will be logged in the `logs` folder for tracking purposes.

---

## Disclaimer
This tool is intended for ethical and non-spam use only. Users are responsible for ensuring compliance with WhatsApp’s terms of service and any applicable laws.

---

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements or suggestions.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Contact
For any questions or support, feel free to open an issue or contact us at your-email@example.com.

---

