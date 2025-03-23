# 💥 Fusion Client

**The ultimate go-to multitool for modifying and managing the _SchoolBoy Runaway_ game with ease.**  
Created with 💙 by **Fusion Softworks** (Mark & Kito)

---

## 📸 Main Menu

![Image of Main Menu](https://github.com/user-attachments/assets/444eac06-bf16-4648-a48a-18aadee65eaf)

---

## 🎮 Features & Modules

### 1. 🔍 **Monitor Pass**
- **Function**: Monitors and logs current password for _SchoolBoy Runaway_.
- **Use Case**: For retrieving the in-game password in real-time from files.
  
![Monitor Pass Function](https://github.com/user-attachments/assets/02676e84-cb7f-4ec7-9b0e-9fa75df77aed)

---

### 2. 🔐 **Custom Pass**
- **Menu Options**:
  - `[1] Set New Password` — Manually sets a new in-game password (must be 4-digit).
  - `[2] Reset Password (Default)` — Restores original game DLL from GitHub.
  - `[3] Back to Main Menu`
- **How It Works**: Replaces the `Assembly-CSharp.dll` with a modified one and sets a custom password provided by the user.

![Custom Pass Function](https://github.com/user-attachments/assets/20121e3f-4c58-4241-8ac0-8dcc33826200)

---

### 3. 📦 **Presets Manager**
- **Menu Options**:
  - `[1] Download Presets` — Choose from 3 game-modifying presets:
    - Preset 1: Roof-related tweaks
    - Preset 2: Lose scene + kitchen gate + spray tweaks
    - Preset 3: Spray in dad’s room
  - `[2] Reset Presets (Default)` — Reverts game back to original DLL
  - `[3] Back to Main Menu`
- **How It Works**: Downloads specific versions of the DLL and applies them.

![Presets Manager](https://github.com/user-attachments/assets/36266e53-bb00-46a9-b049-469c8acbd1eb)

![Presets Available](https://github.com/user-attachments/assets/cc154f99-9ab8-43f2-9af8-5d0b3a61432d)

---

### 4. 🛠️ **Mod Menu (In-Game)**
- **Registry-based** menu switcher for enabling/disabling in-game mod mode.
- **Menu Options**:
  - `[1] Turn Mod Menu ON`
  - `[2] Turn Mod Menu OFF`
  - `[3] Check Current Status`
  - `[4] Back`
  
  ![Mod Menu](https://github.com/user-attachments/assets/975fff87-d3f0-409e-8dfb-853ac7984a35)

- **Registry Path**:  
  `HKCU\SOFTWARE\Linked Squad\SchoolBoy Runaway`  
  → `isOnMenuMode_h1994367598`

---

### 5. ⚙️ **Settings**
- **Menu Options**:
  - `[1] Toggle Webhook Logging` — Enable/disable logging events to a Discord webhook.
  - `[2] Set Webhook URL` — Manually set the Discord webhook URL.
  - `[3] Test Webhook` — Sends a test embed to verify setup.
  - `[4] Back`

![Settings Menu](https://github.com/user-attachments/assets/ac983b2d-a799-4781-8b21-a7bf6ca472eb)

- **Webhook Usage**:
  - Logs when the app starts, exits, or toggles logging.
  - Supports embed messages with icons and timestamps.

![Image of Webhook logs in Discord](https://github.com/user-attachments/assets/28e061f1-0400-4dae-a899-b4ea39c3aa33)

- **Persistent Storage**: Saves webhook URL and status in Windows Registry at  
  `HKCU\Software\FusionClient`

---

### 6. ❌ **Exit**
- Safely terminates the client after saving all settings and logging the exit event (if enabled).

---

## 📆 Download

🔎 Get the latest stable build from the [Releases Page](https://github.com/FusionHolder/FusionClient/releases/latest/download/fusionclient.zip)

Extract the `.zip`, run the single `.exe`, and enjoy!  
No dependencies or installers required thanks to embedded DLLs (Costura.Fody).

---

## 👥 Credits

**Owners:**
- `Mark` → _markedas_ / Discord: `1318285859023229020`
- `Kito` → _kitodoescode_ / Discord: `1206269486932566168`
