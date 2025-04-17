# VaultLock Extension 🔐

**VaultLock** is a fully client-side encrypted password manager browser extension. It empowers users to store, retrieve, and manage credentials securely—without sending sensitive data over the internet.

## 🚀 Features

- 🔐 Zero-knowledge encryption (client-side only)
- 🧠 Secure password generation
- 🔎 Autofill support
- 🛡️ Offline-first design
- 📦 Easy import/export of encrypted vault
- 🧩 Works on Chromium-based browsers  

## 📂 Project Structure

vaultlock-extension/
│
├── src/                    
│   ├── assets/              
│   ├── background.js        
│   ├── content.js           
│   ├── popup.js             
│   ├── options.js           
│   └── utils.js             
│
├── assets/                  
│   ├── icon.png
│   ├── logo.png
│
├── public/                  
│   ├── manifest.json        
│   ├── popup.html           
│   └── options.html         
│
├── tests/                   
│   ├── background.test.js   
│   ├── content.test.js      
│   └── utils.test.js        
│
├── .gitignore               
├── LICENSE                  
└── README.md                

- `src/` – Extension scripts and components
- `assets/` – Icons and branding
- `manifest.json` – Chrome extension configuration
- `.github/` – Issue templates

## 🛠️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/vaultlock-extension.git
