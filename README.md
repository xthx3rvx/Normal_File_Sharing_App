# Normal_File_Sharing_App
# 📡 Localhost File Server with QR Code Access

This project is a simple Python script that turns your computer into a local HTTP file server and generates a QR code so other devices on your network can access it easily.

---

## 🚀 Features

- ✅ Serves files from your `OneDrive` folder (you can change the path to any directory).
- 🌐 Automatically detects your local IP and sets up a server on port `8010`.
- 📱 Generates a QR code pointing to the file server URL.
- 🖥️ Opens the QR code in your web browser for easy access.
- ⚡ No need for third-party file transfer apps—just scan the QR code and go!

---

## 🛠️ Requirements

Ensure you have Python 3 installed, then install the required packages:

```bash
pip install pyqrcode pypng
