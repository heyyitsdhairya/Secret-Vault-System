# Secret Vault System
Secret Vault System is a lightweight Python-based project for securely storing and managing sensitive data such as passwords, keys, and private information using local configuration and encryption logic.
The project is designed for simple, personal use and demonstrates secure handling concepts without requiring a database or heavy dependencies.
It includes a main script (`secure_vault.py`) that performs vault operations and a configuration file (`client_secret.json`) that holds encryption credentials or keys required by the system.

## Features
- Secure local storage of secrets  
- Simple Python implementation  
- Minimal dependencies  
- Easy configuration  
- Interactive usage flow  

## Project Structure
Secret-Vault-System/
- secure_vault.py — Main vault logic  
- client_secret.json — Secret/configuration file  
- README.md — Project documentation  

## Requirements
- Python 3.7 or higher

## Setup
Clone the repository and move into the folder:

git clone https://github.com/heyyitsdhairya/Secret-Vault-System.git  
cd Secret-Vault-System

(Optional) Create a virtual environment:

python -m venv venv  
source venv/bin/activate  (Linux/Mac)  
venv\Scripts\activate     (Windows)

## Configuration
Create or edit `client_secret.json` with your encryption key or required credentials. Do not upload real secrets to public repositories.

Example:
{
  "encryption_key": "your-secret-key"
}

## Usage
Run the program:

python secure_vault.py

Follow the on-screen prompts to store, retrieve, or manage secrets.

## Notes
- Keep your secret file backed up — losing it may make stored data unrecoverable.
- This project is intended for educational and small-scale use, not production-grade security systems.

## License
Add your preferred license here (MIT / Apache / GPL etc.).

## Author
Dhairya Shah
