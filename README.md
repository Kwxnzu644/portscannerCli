# 🔍 Python Port Scanner – Customizable Profiles

A lightweight **command-line port scanner** built in Python for quick network diagnostics and **red team reconnaissance**.  
Features **predefined port profiles**, real-time **colored output**, and **scan logging**.

---

## 📌 Features
- **Predefined Port Profiles**  
  - **Top 10 Common Ports** (21, 22, 23, 25, 53, 80, 110, 139, 443, 445)  
  - **Web Ports Only** (80, 443)  
  - **Remote Access Ports** (22, 23, 3389, 5900)  
  - **Red Team Mix** (Common + Remote Access)  

- **Real-time Colored Output** using `colorama`  
- **Interactive Menu Selection** for port profiles  
- **Custom Banner Messages** via CLI arguments  
- **Logging to File** for scan results  
- **Error Handling** for unreachable hosts or ports  

---

## 📂 Project Structure

---

## ⚙️ Installation & Requirements
### 1️⃣ Clone the repository
```bash
git clone https://github.com/Kwxnzu644/portscannerCli.git
cd portscannerCli
pip install colorama


