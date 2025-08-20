📧 Temporary Email Generator
A powerful Python tool for generating temporary email addresses using the Mail.tm API. Perfect for testing, verification, and protecting your privacy online.

✨ Features
🚀 Instant Email Creation: Generate temporary email addresses in seconds
🔍 Smart Code Detection: Automatically extracts verification codes from incoming emails
💾 Auto-Save: Saves verification codes and account information automatically
🌐 Browser Integration: Optional web interface access
🎨 Colorful Interface: Beautiful colored terminal output
⚡ Real-time Monitoring: Continuously checks for new messages
🛠️ Installation
Clone the repository:

git clone https://github.com/a-z-exe/temp-mail-generator.git
cd temp-mail-generator
Install required dependencies:

pip install -r requirements.txt
📋 Requirements
Python 3.6+
requests
colorama
🚀 Usage
Run the script:

python temp-mail-no-browser.py
What the tool does:
Creates a temporary email using Mail.tm API
Displays the email address for you to use
Monitors incoming messages for verification codes
Extracts codes automatically using smart pattern matching
Saves everything to local files for easy access
Output Files:
codes.txt - Contains extracted verification codes
account_info.json - Stores account details and tokens
🎯 Use Cases
Account Verification: Use for signing up on websites
Testing: Perfect for developers testing email functionality
Privacy Protection: Avoid using your real email for one-time registrations
Automation: Integrate into automated testing workflows
🔧 Configuration
The tool uses these default settings:

Password: Masoud@123 (for all generated accounts)
Monitoring Time: 60 seconds
Check Interval: 5 seconds
You can modify these in the script as needed.

📱 Code Extraction Patterns
The tool automatically detects verification codes using multiple patterns:

verification code is XXXXXX
code is XXXXXX
verification code: XXXXXX
Standalone 6-character alphanumeric codes
🌐 Web Interface
The tool can optionally open the Mail.tm web interface in your browser, allowing you to:

View emails with full formatting
Read messages manually
Access advanced email features
⚠️ Important Notes
Temporary emails are automatically deleted after a period of inactivity
Don't use for important accounts - these emails are not permanent
The tool is for legitimate purposes only
Respect the terms of service of websites you're testing
🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

👨‍💻 Author
AmirHossein Zarei

🌐 GitHub: @a-z-exe
📱 Telegram: @A_Z_exe
📷 Instagram: @A_Z_exe
🙏 Acknowledgments
Thanks to Mail.tm for providing the free temporary email API
Built with Python and love ❤️
📊 Statistics
Python License Maintenance

⭐ If you find this tool useful, please give it a star! ⭐
