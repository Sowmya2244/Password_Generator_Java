# Password Generator 🔐

## 📖 Description
A Java Console Application that generates random passwords based on user preferences and checks their strength.  
Built as a practice project to apply Object-Oriented Programming concepts in Java.  

---

## ✨ Features
1. **Generate a Password**
   - Choose whether to include:
     - Uppercase letters
     - Lowercase letters
     - Numbers
     - Symbols
   - Set desired password length
   - Generates a random password according to your choices

2. **Password Strength Checker**
   - Evaluates the password based on:
     - Presence of uppercase/lowercase letters
     - Numbers and symbols
     - Length ≥ 8 (minimum standard)
     - Length ≥ 16 (strong standard)
   - Displays strength: Weak / Medium / Good / Great

3. **Password Security Tips**
   - Avoid using the same password twice
   - Avoid character repetition, patterns, or dictionary words
   - Avoid predictable letter/number sequences

---

## 🛠 Tech Stack
- **Language:** Java
- **Type:** Console Application
- **Libraries:** None (Pure Java)
- **IDE Support:** VS Code, IntelliJ IDEA, Eclipse

---

## 📂 Project Structure
<pre>
  Password-Generator/
│
├── src/
│ ├── Main.java # Entry point of the program
│ ├── Generator.java # Password generation logic
│ ├── Password.java # Strength checking logic
│ └── Alphabet.java # Character sets used in generation
│
└── README.md # Project documentation
</pre>


---


## 🖥 Example Output


Enter 1 - Password Generator
Enter 2 - Password Strength Check
Enter 3 - Useful Information
Enter 4 - Quit
Choice:1

Hello, welcome to the Password Generator :) answer the following questions by Yes or No

Do you want Lowercase letters "abcd..." to be used?
yes
Do you want Uppercase letters "ABCD..." to be used? 
yes
Do you want Numbers "1234..." to be used? 
yes
Do you want Symbols "!@#$..." to be used? 
yes
Great! Now enter the length of the password
Your generated password -> z_ULec

Enter 1 - Password Generator
Enter 2 - Password Strength Check
Enter 3 - Useful Information
Enter 4 - Quit
Choice:4
Closing the program bye bye!

---
