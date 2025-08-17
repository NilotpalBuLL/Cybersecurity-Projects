# Text Encryption & Decryption Tool

## 📌 Overview

The **Text Encryption & Decryption Tool** is a simple GUI-based application built in Python that allows users to encrypt and decrypt text using different cryptographic techniques.
It is designed for educational purposes to demonstrate how encryption algorithms like Caesar Cipher, AES, DES, and RSA work in practice.

> ⚠️ **Note**: This project does not provide direct source code in the README. Instead, it explains the features, usage, and outputs.

---

## 🔑 Features

* **Multiple Encryption Methods**

  * Caesar Cipher (Classical shift-based encryption)
  * AES (Advanced Encryption Standard)
  * DES (Data Encryption Standard)
  * RSA (Rivest–Shamir–Adleman public key cryptography)

* **Encryption & Decryption**

  * Input plain text and encrypt it using a selected method
  * Decrypt previously encrypted text back into readable form

* **User-Friendly GUI**

  * Built with Python and Tkinter
  * Easy-to-use interface with text boxes and selection options

---

## 🖼️ Screenshots

### 🔹 GUI Interface

![GUI](Gui.jpg)

### 🔹 AES Encryption

![AES Encryption](AES%20Encryption.png)

### 🔹 AES Decryption

![AES Decryption](AES%20Decryption.png)

### 🔹 Caesar Cipher Encryption

![Caesar Cipher Encryption](Caesar%20Cipher%20Encryption.png)

### 🔹 Caesar Cipher Decryption

![Caesar Cipher Decryption](Caesar%20Cipher%20decryption.png)

### 🔹 DES Encryption

![DES Encryption](DES%20encryption.png)

### 🔹 DES Decryption

![DES Decryption](DES%20decryption.png)

### 🔹 RSA Encryption

![RSA Encryption](RSA%20Encrption.png)

### 🔹 RSA Decryption

![RSA Decryption](RSA%20decryption.png)

---

## 🚀 How to Use

1. Open the tool (run the Python file).
2. Enter your text in the **input box**.
3. Select the **encryption method** (Caesar, AES, DES, RSA).
4. Provide a **Key/Shift** value (if required).
5. Click **Encrypt** to convert plain text into cipher text.
6. Click **Decrypt** to recover the original plain text.

---

## 🎯 Example

* **Input Text**:

  ```
  Hey I am Nilotpal Sarma, From Guwahati. I Currently Pursuing BCA from GIMT and Just Pass Cybersecurity Diploma From IITG
  ```

* **AES Encrypted Output**:

  ```
  a4AK3FcaI8T0dGzu+faSCCSrgW4xRyOItxNlrF7ZOlkKasZkgJGiawxVwT+gBMUBRY1wt0zjj59x0/283HFOlFEi5zEdrJmECPOW2QnEHgyCHBRAzU1w/zgvLQJHasoTBdUChhQgycWd3UKX0wSRP2GtmYRV4amrjW0OjnNNJ4=
  ```

* **AES Decrypted Output**:

  ```
  Hey I am Nilotpal Sarma, From Guwahati. I Currently Pursuing BCA from GIMT and Just Pass Cybersecurity Diploma From IITG
  ```

---

## 🛠️ Tech Stack

* **Python** (Core programming language)
* **Tkinter** (GUI)
* **Cryptography libraries** (PyCryptodome, RSA, etc.)

---

## 📘 Notes

* This project is meant for **educational purposes only**.
* Do not use it for real-world secure communication.
* The README intentionally **does not provide source code**, only project explanation and demonstration.