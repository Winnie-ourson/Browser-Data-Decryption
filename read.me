# Browser Data Decryption Script

## Overview
This Python script extracts and decrypts sensitive browser data (passwords, cookies, and autofill information) from Google Chrome, Microsoft Edge, and Brave browsers on a Windows system. It retrieves the master encryption key for each browser and uses it to decrypt stored data, saving the results in text files.

**Note**: This script is intended for educational purposes or authorized security testing only. Unauthorized use to access or extract data without permission is illegal and unethical.

## Features
- Extracts master encryption keys from browser local state files.
- Decrypts stored passwords, cookies, and autofill data using AES-GCM or ChaCha20-Poly1305.
- Supports Google Chrome, Microsoft Edge, and Brave browsers.
- Saves decrypted data into organized text files per browser and profile.
- Requires administrative privileges for certain operations (e.g., LSASS impersonation).

## Requirements
- **Operating System**: Windows
- **Python Version**: Python 3.7+
- **Dependencies**:
  - `pywin32` (for Windows API interactions)
  - `pycryptodome` (for AES and ChaCha20-Poly1305 decryption)
  - `sqlite3` (included in Python standard library)
- **Permissions**: Must be run with administrative privileges.

Install dependencies using pip:
```bash
pip install pywin32 pycryptodome
```

## Usage
1. Ensure you have administrative privileges.
2. Install the required Python packages (see above).
3. Clone or download this repository.
4. Run the script:
   ```bash
   python main.py
   ```
5. The script will:
   - Terminate running browser processes (Chrome, Edge, Brave).
   - Extract master keys and save them in the `decrypted_keys` directory.
   - Decrypt and save passwords, cookies, and autofill data in browser-specific directories (`chrome`, `edge`, `brave`).

## Output
- **Decrypted Keys**: Saved in `decrypted_keys/<browser>_master_key.txt` with hex and base64 formats.
- **Browser Data**:
  - Passwords: `<browser>/<profile>/passwords.txt`
  - Cookies: `<browser>/<profile>/cookies.txt`
  - Autofill: `<browser>/<profile>/auto_fills.txt`

## Technical Details
- **Encryption**: Handles browser data encrypted with AES-GCM or ChaCha20-Poly1305 (v20 format).
- **Key Extraction**: Uses Windows DPAPI and LSASS impersonation to decrypt browser master keys.
- **Browser Support**: Processes data from `Default` and `Profile*` directories in the browser's user data path.
- **Error Handling**: Skips invalid or inaccessible data to ensure robustness.

## Disclaimer
This script is for educational or authorized security research purposes only. Use it responsibly and only on systems you have explicit permission to access. The author is not responsible for misuse or any resulting consequences.
