# 🔒 Password Manager with Tkinter GUI

A secure password manager built with Python and Tkinter that generates and stores strong passwords locally. Includes auto-copy to clipboard functionality.

---

## 🔧 Features

1. **Password Generation**  
   Creates strong, random passwords between 12–18 characters.

2. **Secure JSON Storage**  
   Credentials are saved in a local `.json` file.

3. **Quick Search**  
   Instantly retrieve saved credentials by website name.

4. **Auto-Copy to Clipboard**  
   New passwords are automatically copied to your clipboard.

5. **Graphical User Interface**  
   Clean and intuitive interface built using Tkinter.

---

## 🛠️ Tech Stack

1. **Python 3**
2. **Tkinter (for GUI)**
3. **`pyperclip` Module (for clipboard)**
4. **JSON (for local data storage)**

---

## ▶️ How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/password-manager.git
   cd password-manager
   ```

2. **Install Dependencies**
   ```bash
   pip install pyperclip
   ```

3. **Set Up Your Email**  
   Open `main.py` and replace:
   ```python
   email = "YOUR_EMAIL@example.com"
   ```
   with your own email address.

4. **Run the Application**
   ```bash
   python main.py
   ```

5. **Use the Interface**  
   - Add new credentials  
   - Generate strong passwords  
   - Search for saved logins  

---

## 📁 File Structure

```bash
password-manager/
├── main.py               # Core application logic
├── data.json             # Local password storage (auto-generated)
├── logo.png              # App icon for GUI
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
```

---

## 📦 requirements.txt

```bash
pyperclip
```

---

## ⚠️ Security Notice

This project is a learning tool. For production use:

- Add **master password** protection
- Use proper **encryption**
- Avoid committing sensitive data
- Store secrets in **environment variables**

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🧠 Project Description

This is a simple password manager built with Python that allows users to generate and store secure passwords in a local JSON file using a clean Tkinter GUI. It automates copying the generated password to the clipboard and makes it easy to search for saved logins.

---

## ✨ Credits

- Built with ❤️ by Aarush Sharma 
- Inspired by best practices in Python GUI and security design
