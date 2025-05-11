# ATMSystem

A secure, command-line ATM simulation system built in C++.  
This project uses Vigenère Cipher layered with Base64 encoding to securely store and retrieve user data.
The system is designed to simulate ATM operations, including account management, transactions, and data encryption.
---

## 📁 Project Structure

- `main.cpp` — Entry point and system loop handler.
- `Login.h/.cpp` — Authentication and account verification.
- `Account.h/.cpp` — Core data models with getter/setter logic.
- `System.h/.cpp` — Transaction and ATM operations.
- `Base64.h/.cpp` — Base64 encoding/decoding logic.
- `vigenere.h` — Implements Vigenère cipher and helpers.
- `encrypt.h` — Combines Base64 and Vigenère for full-cycle encryption/decryption.

---

## 🛠️ Development Tools

| Tool         | Why We Chose It                                                                 |
|--------------|----------------------------------------------------------------------------------|
| **C++**      | High performance, memory control, and familiarity for systems-level programming |
| **CMake**    | Portable and modern build system                                                 |
| **CLion**    | Excellent CMake integration, smart code analysis *(Educational License)*         |
| **ChatGPT**  | Used for writing docs and structuring plans *(Free version)*                    |
| **GitHub**   | Collaboration, version control *(Student Premium)*                              |
| **Copilot**  | Code autocompletion assistance in CLion *(Free for students)*                   |
| **Notion**   | Centralized documentation sharing *(Education Plan)*                            |

---

## 📚 Documentation

Complete documentation and planning are available on **Notion**:  
🔗 [Notion Docs](https://paint-need-95e.notion.site/1ddda1083c44808292c8e0227ab6dac4?v=1deda1083c44803da55e000c0a1ebe53&pvs=4)

---

## 📖 License & Sharing

This project is **completely free and open-source** under the [MIT License](LICENSE).  
You're welcome to:
- Use it in your own projects
- Modify or extend it
- Share feedback or improvements

> I'm currently accepting suggestions, improvements, or code reviews. If you're a student or curious dev — reach out!

---

## 🙌 Contributions

Pull requests and reviews are highly encouraged!  
Please follow the encryption protocols and structure explained in the documentation before contributing.

---

## 👨‍💻 Author

Created by a student developer as part of an Operating Systems class project.  
Feel free to ⭐ this repo if you find it helpful!

---