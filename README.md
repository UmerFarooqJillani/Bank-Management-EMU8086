# <p align="center">📌 Bank Management System (Assembly - EMU8086)</p>

## 📖 Project Overview  
The **Bank Management System** is an **Assembly Language (x86) application** developed using **EMU8086 - MICROPROCESSOR EMULATOR**. It allows users to perform banking operations such as:
- Personal detail
- account open
- check balance
- change pin
- deposit amount 
- withdraw amount

It is implemented using **Assembly (8086)** instructions and works with **low-level memory management**.

## 📋 Requirements
Here is a bank (…….) and a number of customers here which are avail different 
services of bank like :
1. Personal detail
2. account open
3. check balance
4. change pin
5. deposit amount 
6. withdraw amount

User can select anyone option in this menu, according these options your you can 
design proper detail of user. They can select any option in menu. Use commands 
**Mov, al, print, main endp, .code add and subtract**. 
- Like they get option 1 they see their proper detail in different line.
- If select option 2 then show open account option and ask for the necessary 
required details like name cnic and store them in an array.
- If they check their balance, then your system shows his/her account number 
and balance detail. 
- If they choose option 4, then your system shows his/her account pin change 
option. 

## 🚀 Features  
✅ **Account Creation & Personal Details Storage**  
✅ **Balance Checking & Transaction Handling**  
✅ **PIN Management (Set, Verify, Change)**  
✅ **Deposit & Withdraw Money**  
✅ **Menu-Driven Command-Line Interface**  


## 🏗️ Data Structures Used  
- **Arrays & Buffers:** Store user details, balance, and PINs.  
- **Procedures & Subroutines:** Modular design for efficient execution.  
- **Registers & Stack:** Used for temporary storage and function calls.  


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


## 🛠️ Tools & Technologies  
- **Language:** Assembly (8086)  
- **Assembler:** EMU8086  
- **Platform:** Windows  


## 📸 Screenshots  
### **Menu Interface**
<p align="center">  
  <img src="src/images/menu.png" alt="Menu Screenshot">  
</p>  


## 📌 Author
🔗 GitHub: [Umer Farooq Jillani](https://github.com/UmerFarooqJillani)  

---
