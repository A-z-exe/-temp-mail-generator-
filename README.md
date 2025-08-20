# 📧 Temp Mail Generator

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Python](https://img.shields.io/badge/python-3.10%2B-blue)
![Mail.tm API](https://img.shields.io/badge/Mail.tm-API-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![GitHub Repo stars](https://img.shields.io/github/stars/A-z-exe/temp-mail-generator?style=social)
![GitHub forks](https://img.shields.io/github/forks/A-z-exe/temp-mail-generator?style=social)

Temporary email generator with headless/browser modes for testing and privacy.  
A powerful Python tool for generating temporary email addresses using the Mail.tm API.  
Perfect for testing, verification, and protecting your privacy online.

---

## ✨ Features

- 🚀 **Instant Email Creation**: Generate temporary email addresses in seconds
- 🔍 **Smart Code Detection**: Automatically extracts verification codes from incoming emails
- 💾 **Auto-Save**: Saves verification codes and account information automatically
- 🌐 **Browser Integration**: Optional web interface access
- 🎨 **Colorful Interface**: Beautiful colored terminal output
- ⚡ **Real-time Monitoring**: Continuously checks for new messages

## ⚡ Quick Start

```bash
# 1. Clone and install
git clone https://github.com/A-z-exe/temp-mail-generator.git
cd temp-mail-generator && pip install -r requirements.txt

# 2. Run the tool
python temp-mail-no-browser.py

# 3. Use the generated email for verification
# 4. Codes will be automatically saved to codes.txt
```

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/A-z-exe/temp-mail-generator.git
   cd temp-mail-generator
   ```

2. **Install required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## 📋 Requirements

- Python 3.6+
- requests
- colorama

## 🚀 Usage

Run the script:
```bash
python temp-mail-no-browser.py
```

### What the tool does:

1. **Creates a temporary email** using Mail.tm API
2. **Displays the email address** for you to use
3. **Monitors incoming messages** for verification codes
4. **Extracts codes automatically** using smart pattern matching
5. **Saves everything** to local files for easy access

### Output Files:

- `codes.txt` - Contains extracted verification codes
- `account_info.json` - Stores account details and tokens

## 🎯 Use Cases

- **Account Verification**: Use for signing up on websites
- **Testing**: Perfect for developers testing email functionality
- **Privacy Protection**: Avoid using your real email for one-time registrations
- **Automation**: Integrate into automated testing workflows

## 🆚 Why Choose This Tool?

| Feature | This Tool | Others |
|---------|-----------|---------|
| Auto Code Extraction | ✅ | ❌ |
| Real-time Monitoring | ✅ | ❌ |
| Browser Integration | ✅ | ❌ |
| Colorful Interface | ✅ | ❌ |
| JSON Export | ✅ | ❌ |
| Free & Open Source | ✅ | ❌ |

## 📸 Sample Output

```
🔑 Verification code found: ABC123
📧 New message: Your verification code from GitHub  
✅ Email checking complete.
[+] Email created: temp123@mail.tm
[✓] Code ABC123 saved to codes.txt
```

## 🔧 Troubleshooting

**Q: No codes are being detected**
- Check if emails contain verification codes
- Try manually entering the code when prompted

**Q: Connection errors** 
- Check your internet connection
- Mail.tm API might be temporarily down

**Q: Browser doesn't open**
- Make sure you have a default browser set
- Try accessing https://mail.tm/ manually

## 🔧 Configuration

The tool uses these default settings:
- **Password**: `Masoud@123` (for all generated accounts)
- **Monitoring Time**: 60 seconds  
- **Check Interval**: 5 seconds

You can modify these in the script as needed.

## 📱 Code Extraction Patterns

The tool automatically detects verification codes using multiple patterns:
- `verification code is XXXXXX`
- `code is XXXXXX`
- `verification code: XXXXXX`
- Standalone 6-character alphanumeric codes

## 🌐 Web Interface

The tool can optionally open the Mail.tm web interface in your browser, allowing you to:
- View emails with full formatting
- Read messages manually
- Access advanced email features

## ⚠️ Important Notes

- Temporary emails are **automatically deleted** after a period of inactivity
- **Don't use for important accounts** - these emails are not permanent
- The tool is for **legitimate purposes only**
- Respect the terms of service of websites you're testing

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**AmirHossein Zarei**
- 🌐 GitHub: [@a-z-exe](https://github.com/a-z-exe)
- 📱 Telegram: [@A_Z_exe](https://t.me/A_Z_exe)
- 📷 Instagram: [@A_Z_exe](https://instagram.com/A_Z_exe)

## 🙏 Acknowledgments

- Thanks to [Mail.tm](https://mail.tm/) for providing the free temporary email API
- Built with Python and love ❤️

## 📊 Statistics

![Python](https://img.shields.io/badge/python-v3.6+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)

---

⭐ **If you find this tool useful, please give it a star!** ⭐
