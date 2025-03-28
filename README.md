# Lab Exercise: Deciphering SHA256 Hash of a 3-Digit Number

## 🎯 Objectives

- Grasp the concept of SHA256 cryptographic hashing.
- Enhance analytical skills in decoding hash values.

## 🔍 Prerequisites

- Basic understanding of hashes and number systems.

## 🚀 Steps

1. **Learn About SHA256**: Familiarize yourself with the SHA256 hashing algorithm and its use cases.

2. **Access the Interface**: Navigate to the provided browser for hash cracking.

3. **Analyze the Given SHA256 Hash**: A unique SHA256 hash value of a 3-digit number will be displayed on your screen.

4. **Deductive Thinking**: Use your knowledge and logical reasoning to guess the original 3-digit number.

5. **Input Your Guess**: Enter your 3-digit number guess in the provided input field.

6. **Check Your Answer**: Click the 'Check' button to see if your guess decrypts the hash correctly.

7. **Iterate and Learn**: If unsuccessful, analyze your approach, learn from it, and try again!

## 🏁 Outcome
- Mastery in interpreting SHA256 hashes through critical thinking and analysis.


**Solution :**

🔐 SHA256 Hash Deciphering Lab

📌 Overview

This project is designed to help understand and practice SHA256 cryptographic hashing by deciphering the original number from a given hash. A random 3-digit number (100-999) is hashed using SHA256, and the challenge is to find the original number.

🎯 Objectives

Understand how SHA256 hashing works.

Enhance problem-solving skills by attempting to find the original number.

Learn about brute-force approaches to verify hashed values.

🔍 What is SHA256?

SHA256 (Secure Hash Algorithm 256-bit) is a one-way cryptographic hash function that produces a fixed-size (256-bit) unique hash for any given input. It is commonly used in password storage, digital signatures, and blockchain technology.

Why is SHA256 Irreversible?

It uses a one-way function, meaning the original value cannot be derived directly from the hash.

The only way to match a SHA256 hash to its original input is brute force (trying all possible inputs).

🚀 How This Works

A random 3-digit number (100-999) is selected.

The number is hashed using SHA256.

The SHA256 hash is stored and displayed.

The user tries to guess the original number.

The system verifies the guess by hashing it and checking against the stored hash.

✅ Given SHA256 Hash

f4466a4b51d21014b34f621813a1ed75f1c750ec328d908d9edc989c64778962

🎯 Deciphered 3-Digit Number

673

🛠️ How to Run the Code

Open the index.html file in a browser.

Enter your guess in the input box.

Click the Check button to verify if your guess matches the SHA256 hash.

Alternatively, you can modify the JavaScript file to generate new hashes and test different values.


📂 Files Included

index.html - User interface for the exercise.

script.js - Contains the SHA256 hashing and verification logic.

README.md - Explanation of the project.

📌 Conclusion

This lab exercise helps understand cryptographic hashing, its practical uses, and the brute-force approach for hash analysis. SHA256 remains one of the most secure hashing algorithms, making it a fundamental topic in cybersecurity. 🚀
