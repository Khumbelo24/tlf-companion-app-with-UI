# TLF Companion Mobile Application (Frontend Prototype)

A beautifully structured, cross-platform mobile application frontend prototype engineered for the **Tshwane Leadership Foundation (TLF)** project. This layout features a secure login portal that dynamically routes users to a fully designed 4-tab dashboard containing real-time update panels, event tracking, a volunteer hour logger, and a system analytics interface.

---

## ⚠️ CRITICAL STEP 
To keep the file upload light and clean, the **`node_modules`** dependency folder was explicitly removed before zipping. 

**Before launching the application on your machine, you MUST restore these frontend packages.**

### 🛠️ How to Restore and Run:

1. **Download and Extract:** Download the repository ZIP file and extract it on your local machine.
2. **Open Terminal:** Navigate inside the main directory using your terminal or VS Code window.
3. **Restore Dependencies:** Run the following command to automatically reinstall all necessary layout and navigation packages:
   ```bash
   npm install
Boot the App Matrix: Once the installation finishes, run the clear script to launch the app:

Bash
npx expo start --clear
Open Browser Preview: Press w on your keyboard to open the local web viewer interface on localhost:8081.

💻 Tech Stack & System Features
Frontend Framework: React Native & Expo Router

Styling & Components: React Native StyleSheet API (Clean Blue & White Theme)

Icon Graphics Library: @expo/vector-icons (Feather package integration)

Pre-Built Views: * Login Gate: Secure credential layout interface.

Home View: Key performance indicators and announcements dashboard.

Explore View: Interactive upcoming community events stream.

Volunteer View: Data form designed for active user hours logging.

Reports View: Analytics interface optimized for tracking background database connections.

🗄️ Backend Integration Protocol (For Next Steps)
The frontend forms and dashboard metrics are currently rendering pristine visual placeholder states. To fully connect this layout to your operational project system:

Replace the component log handshakes with live database fetch() API calls.

Map incoming JSON fields directly to your local XAMPP (Apache/MySQL) server instance routes.
