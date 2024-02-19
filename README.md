# Python Secure Vault


## Overview

Experience the power of Python Secure Vault, a project designed to provide a reliable solution for safeguarding sensitive information. With its advanced encryption techniques and user-friendly interface, Python Secure Vault ensures peace of mind when storing confidential data.

## Key Features

- **Advanced Encryption**: Employing cutting-edge encryption methods, Python Secure Vault secures your sensitive data, including passwords, within a SQL database.
  
- **Hash Authentication**: Utilizing robust SHA3_512 Hash Function for user verification, users establish a master password that is hashed and securely stored. During login, the entered password is hashed and compared to the stored hash for authentication.
  
- **Comprehensive Functionality**: Enjoy seamless CRUD (Create, Read, Update, Delete) operations for effortless data management.
  
- **Intuitive Interface**: With its visually appealing and color-coded prompts, Python Secure Vault offers an intuitive user experience.
  
- **Support for Multiple Users**: Collaborate effortlessly with multi-user support, ensuring seamless access for all authorized individuals.
  
- **Cross-Platform Compatibility**: Whether you're on Windows, Linux, Mac, or Android (Termux), Python Secure Vault has you covered.

## Security Advisory

While Python Secure Vault aims to prioritize security, it is important to acknowledge that it was developed as a project and may contain vulnerabilities. Users are cautioned against relying on it for storing critical information.

In the event of a security breach, all stored passwords and associated data may be at risk. Additionally, since files are stored locally, they can be deleted without requiring credentials. It is advisable to maintain backups elsewhere.

## System Requirements

Ensure the following dependencies are installed:

- Python 3.x
- cryptography library

To install the cryptography CLI using pip, execute the following command:

```bash
pip install cryptography
```

## Usage

Execute the main script to launch Python Secure Vault:

```bash
python secure_vault.py
```

## Acknowledgments

Python Secure Vault is a creation of Alina Yildirim, crafted with a passion for exploration and innovation.

## License

This project is licensed under the [MIT License](LICENSE).

## Disclaimer

This software is intended for educational purposes only and should not be used in production environments. Use it at your own discretion.


