# 🧪 Lab Setup: VMware, Kali Linux & Metasploitable

## 1. Why We Need a Lab Environment
A lab environment is essential in cybersecurity to:
- Practice attacks legally
- Learn tools hands-on
- Avoid damaging real systems

⚠️ Important Rule:  
Only test systems you own or have permission to test.

---

## 2. Lab Architecture
This lab uses two virtual machines:
- Kali Linux (Attacker machine)
- Metasploitable (Vulnerable target)

Both run inside VMware.

---

## 3. Required Components
- VMware Workstation / Player
- Kali Linux Virtual Machine
- Metasploitable Virtual Machine

---

## 4. Install VMware
VMware allows running multiple operating systems on one computer.

Steps:
1. Download VMware
2. Install using default settings
3. Restart system

---

## 5. Setup Kali Linux
Kali Linux is used as the attacker machine.

Steps:
1. Download Kali Linux VMware image
2. Extract files
3. Open VMware
4. Click "Open Virtual Machine"
5. Select Kali VM file

---

## 6. Setup Metasploitable
Metasploitable is a vulnerable machine for practice.

Steps:
1. Download Metasploitable VM
2. Extract files
3. Open VMware
4. Open Metasploitable VM

---

## 7. Configure Network
Set both machines to:
- NAT or Host-Only

Purpose:
- Allow communication between machines
- Keep lab isolated from real internet

---

## 8. Verify Connectivity

### On Kali Linux:

### On Metasploitable:

### Test connection:

---

## 9. Security & Ethics
- Use lab only for learning
- Do not attack real systems
- Follow legal guidelines

---

## 10. Real-World Insight
This lab simulates:
- Attacker system
- Vulnerable server
- Internal network

Used in real penetration testing environments.
