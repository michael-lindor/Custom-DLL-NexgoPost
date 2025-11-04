# CustomDLL NextGoPos

CustomDLL NextGoPos is a secure, extensible Dynamic Link Library (DLL) built to enhance **NextGo POS** environments.  
It provides a modular framework for adding custom logic, integrating peripherals, and automating business workflows.

## 🚀 Features
- Real-time POS event hooks and middleware extension
- Secure transaction and device API bridge
- Inventory, payments, and receipt automation
- Configurable logging and exception tracing
- Lightweight and dependency-free runtime

## 🛠️ Installation
1. Copy `CustomDLL_NextGoPos.dll` into your NextGo POS `plugins/` directory.  
2. Register the DLL in your POS settings or configuration file.  
3. Restart NextGo POS to activate the extension.

## 🧩 Usage
Import and call exported methods via your integration interface:
```csharp
[DllImport("CustomDLL_NextGoPos.dll")]
public static extern int SendTransaction(string jsonPayload);
⚙️ Configuration
Set environment variables or edit config.json to adjust:

Logging level

Endpoint URLs

Device and printer mapping

🧾 License
© 2025 Monarck / Prozs. All rights reserved. Proprietary component for NextGo POS integration.
