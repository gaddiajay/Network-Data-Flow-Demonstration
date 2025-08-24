 Network Data Flow Demonstration

 Project Overview
This project is an **interactive cybersecurity demonstration** that simulates the flow of sensitive data across a network.  
It allows users to experience how data is **encrypted, transmitted, and decrypted**, showcasing the importance of secure communication in the digital world.

The project is built as a **web-based interface** using **HTML, CSS, and JavaScript**, making it easy to understand core cybersecurity concepts in a visual and interactive way.

---

  Objectives
- Demonstrate how sensitive data can be **secured using encryption** before transmission.
- Simulate **data transmission across a network** with visual animations.
- Showcase how encrypted data is eventually **decrypted back into its original form**.
- Highlight the importance of **cybersecurity in protecting digital information**.

---

 Features
- **Step 1: Input & Encryption**  
  - Users enter sensitive data (like a password or secret).  
  - Data is encrypted (Base64 in current version).  
  - Clear (❌) and visibility toggle (🔑) options available.  

- **Step 2: Transmission**  
  - Encrypted data is sent across a simulated “network”.  
  - Includes a moving animation bar to represent live transmission.  

- **Step 3: Decryption**  
  - Received data is decrypted back to its original form.  
  - Shows how encryption ensures secure communication.  

- **Cybersecurity-Themed UI**  
  - Dark theme with gold/blue highlights.  
  - Responsive design with modern styling.  

---

 Technologies Used
- **HTML5** – Structure of the interactive page  
- **CSS3** – Cybersecurity-themed UI styling  
- **JavaScript (Vanilla JS)** – Logic for encryption, transmission, and decryption  

---

How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/gaddiajay/Network-Data-Flow-Demonstration.git
````

2. Navigate to the `SDT` folder:

   ```bash
   cd Network-Data-Flow-Demonstration/SDT
   ```
3. Open the `index.html` file in any modern web browser (Chrome, Edge, Firefox).

   * No extra setup required – works directly in the browser.

---

  Expected Output

* Entering data → Encrypts it into encoded text.
* Transmitting → Shows animated flow with encrypted data displayed.
* Decrypting → Recovers the original sensitive data.

This helps learners understand the **journey of data** from plaintext → encrypted → transmitted → decrypted.

---

  Future Enhancements

* Upgrade encryption from Base64 to **AES or RSA** using libraries like [CryptoJS](https://github.com/brix/crypto-js).
* Add an **attacker simulation view** to show risks of unencrypted transmission.
* Deploy project on **GitHub Pages** for live demo access.
* Extend with **packet capture demonstration** to connect web demo with real-world cybersecurity tools.

---

## 👨‍💻 Author

Ajay Gaddi


---

⭐ If you found this project useful, consider giving it a **star** on GitHub!

```

---

```
