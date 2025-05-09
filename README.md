# Sentinel OS

**Sentinel OS** is a secure alert and identity management system with a dual-interface structure — designed for LAN-based environments like security teams, roleplay servers, or classified setups. It features real-time full-screen alerts, person database control, encrypted authentication, and a user-managed change request system.

---

## 🔐 Features

### 🧑‍💻 Admin Interface
- Full-screen unclosable **Lockdown** or **Security Breach** alerts with flashing backgrounds
- Custom alert messaging
- Global message broadcasting to all users
- Add, edit, and delete person identity records (name, age, job, height, weight, etc.)
- Approve or deny user-submitted change requests with one click
- View live list of all registered users and pending requests
- Configure alert colors
- Password-protected access with encrypted local storage

### 👥 User Interface
- View and search person data
- Request changes to identity fields (e.g., job, age, sex, height/weight)
- Receive broadcast messages and full-screen alerts in real time
- Locally stored access password (set on first run)
- Clean, responsive GUI with optional unit conversion (cm/in, kg/lbs)

---

## 🌐 Network Support

- Works across devices on the same LAN (Wi-Fi and Ethernet)
- IP configuration stored in `config.json` (editable)
- Only devices with the installed program can access the system

---

## 🔒 Security

- Admin and user passwords stored with Fernet encryption
- Encrypted `.pyd` modules (Cython) to prevent reverse engineering
- Compiled to `.exe` using PyInstaller with custom encryption key
- Alerts cannot be closed, minimized, or bypassed without password

---

## 🚀 Setup Instructions
just run the .exe
