# SwiftSign Digital Signature System ✒️ 

---

Developed by: **Mohamed Khaled Nassar, Ahmed El Shaboury, and Ahmed Maged**  
**Graduation Project** | Department of Cyber Security and Data Analytics  
**Faculty of Electronic Engineering, Menoufia University**  

---

## 📝 Description

**SwiftSign Digital Signature** is a secure, feature-rich, and user-friendly application designed for generating, signing, and verifying digital signatures. With a focus on licensing applications, the system aims to ensure the authenticity and integrity of digital licenses through the use of advanced cryptographic techniques.

The application supports multiple cryptographic algorithms, including ECC (ECDSA), RSA, ElGamal (RSA-PSS based), and Diffie-Hellman (HMAC-SHA256 based). A modern, intuitive GUI with drag-and-drop functionality, batch processing, and customizable settings makes SwiftSign accessible and efficient for users.

---

## 🚀 Features

- **Key Pair Generation**:
  - Supports ECC, RSA, ElGamal, and Diffie-Hellman key generation.
  - Generates and stores public and private keys securely.

- **Document Signing and Verification**:
  - Ability to create and verify digital signatures for files and data.
  - Signs files in various formats and ensures their authenticity.

- **Certificate Generation**:
  - Self-signed X.509 certificate creation for enhanced security.

- **Batch Operations**:
  - Sign and verify multiple files simultaneously in one operation for efficiency.

- **Drag-and-Drop Support**:
  - Simplifies file selection with native drag-and-drop functionality.

- **Audit Trail**:
  - Provides a detailed logging system to track actions performed in the tool.

- **Customizable Settings**:
  - Allows user preferences for key directories, dark mode, and UI animations.

---

## 🧰 Key Features with Explanation

### Supported Cryptographic Algorithms
SwiftSign implements and supports various algorithms to suit diverse requirements:
1. **ECC (ECDSA)**: Utilizes the NIST256p curve and SHA-256 for efficient and secure signatures.
2. **RSA**: Uses RSASSA-PSS with 2048-bit keys and SHA-256 for robust signing and verification.
3. **ElGamal**: A customized implementation of RSA-PSS with SHA-256 for secure digital signatures.
4. **Diffie-Hellman**: Leverages DH key exchange combined with HMAC-SHA256 for signing and verification.

### User-Friendly GUI
- A modern graphical interface developed with `tkinter`.
- Tab-based navigation for separate functionalities: Key Generation, Signing, Verification, Certificates, Settings, and About. 

### Signature Security
- Ensures the integrity of signed files through locally executed algorithms.
- Allows batch operations to process multiple files efficiently.

---

## 🛠️ Setup Instructions

### Pre-Requisites
Ensure you have Python `v3.8` or higher installed on your system alongside the following dependencies:

- **tkinter**: Pre-installed in Python distributions.
- **requests**: To enable API interactions.
- **ttkthemes**: To enhance the UI with custom themes.
- **Pillow**: For image handling in the UI.
- **tkinterdnd2** (Optional): For drag-and-drop UI support.
- **cryptography**: To perform various encryption and cryptography tasks.
- **ecdsa**: For Elliptic Curve Cryptography (ECC).

Install these dependencies with:
```bash
pip install -r requirements.txt
```

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/rayder54321/SwiftSign-Digital-Signature-program.git
    ```

2. Navigate to the project directory:
    ```bash
    cd SwiftSign-Digital-Signature-program
    ```

3. Run the application:
    ```bash
    python "SwiftSign Digital Signature.py"
    ```

---

## 🖥️ Usage

### Main Features
After launching **SwiftSign Digital Signature**, the application provides the following options:

1. **Key Generation**: Specify an algorithm and generate key pairs to file.
2. **File Signing**: Sign a single file or multiple files using the chosen cryptographic algorithm.
3. **Signature Verification**: Verify the authenticity and integrity of signed files.
4. **Batch Operations**: Sign or verify multiple files at the same time for efficiency.
5. **Certificate Generation**: Create self-signed X.509 certificates for secure usage with issued signatures.
6. **Settings**: Configure application settings, including themes, preferences, and default options.
7. **Feedback**: Provide suggestions or report issues via the in-app feedback module.

---

## 🎨 Themes and Customization
**SwiftSign Digital Signature** offers the following UI features:
- **Modern Dark Mode**: Switch to a visually comfortable dark mode theme.
- **Animations**: Optional animations for a smooth user experience.
- **Custom Preferences**: Set default values for key directories and algorithm selection.

---

## 🖥️ Project Structure

```
Project Directory/
│
├── SwiftSign Digital Signature.py       # Main application script
├── README.md                            # Project documentation
├── requirements.txt                     # Required dependencies
├── images/                              # Contains logo, icons, and theme visuals
├── icons/                               # Includes the app icon and other visual assets
└── certificates/                        # Stores default certificate keys
```

---

## ⚠️ Disclaimer

This tool is **intended for educational purposes** and must be used responsibly. Scanning or signing files and systems without proper authorization may be illegal. The developers are not responsible for its misuse.

---

## Contributing

We welcome contributors to suggest, report bugs, or enhance the system.  
Submit your ideas and changes using GitHub **Pull Requests** or open an **Issue**.

---

## ✍️ Authors

1. **Mohamed Khaled Nassar**  
2. **Ahmed El Shaboury**  
3. **Ahmed Maged**  

Developed as part of the graduation project for the **Department of Cyber Security and Data Analytics**, **Faculty of Electronic Engineering, Menoufia University**.

---

## 📬 Contact

If you have any questions or need further assistance, reach out via:  

📧 Email: [mohamednassar@el-eng.menofia.edu.eg](mailto:mohamednassar@el-eng.menofia.edu.eg)  

Visit the [GitHub Repository](https://github.com/rayder54321/SwiftSign-Digital-Sign)
