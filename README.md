# <p align="center">📌 Bank Management System (Assembly - EMU8086)</p>

## 📖 Project Overview  
The **Bank Management System** is an **Assembly Language (x86) application** developed using **EMU8086**. It allows users to perform banking operations such as:
- Checking personal details  
- Opening new accounts  
- Checking balances  
- Changing PINs  
- Depositing and withdrawing amounts  

It is implemented using **Assembly (8086)** instructions and works with **low-level memory management**.

---

## 🚀 Features  
✅ **Account Creation & Personal Details Storage**  
✅ **Balance Checking & Transaction Handling**  
✅ **PIN Management (Set, Verify, Change)**  
✅ **Deposit & Withdraw Money**  
✅ **Menu-Driven Command-Line Interface**  

---

## 🏗️ Data Structures Used  
- **Arrays & Buffers:** Store user details, balance, and PINs.  
- **Procedures & Subroutines:** Modular design for efficient execution.  
- **Registers & Stack:** Used for temporary storage and function calls.  

---

## ⏳ Algorithms Used  

### 🔍 **Key Algorithms:**  
#### **1️⃣ Menu-Based Selection**  
- Uses **ASCII comparison** to determine user choice.
- **Time Complexity:** **O(1)**  

#### **2️⃣ String Input & Storage**  
- Uses `mov ah, 10h` to read strings and store in arrays.  
- **Time Complexity:** **O(n)** (where `n` is input size).  

#### **3️⃣ PIN Verification & Modification**  
- Uses **array comparison** for PIN authentication.  
- **Time Complexity:** **O(1)**  

#### **4️⃣ Deposit & Withdrawal Operations**  
- **Arithmetic operations** on stored balances.  
- **Time Complexity:** **O(1)**  

---

## 🛠️ Tools & Technologies  
- **Language:** Assembly (8086)  
- **Assembler:** EMU8086  
- **Platform:** Windows  

---

## 📸 Screenshots  
### **Menu Interface**
<p align="center">  
  <img src="src/images/menu.png" alt="Menu Screenshot">  
</p>  

---

## 📌 Author
🔗 GitHub: [Umer Farooq Jillani](https://github.com/UmerFarooqJillani)  

---
