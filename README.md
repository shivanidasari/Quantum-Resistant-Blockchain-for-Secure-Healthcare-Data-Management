# Quantum-Resistant-Blockchain-for-Secure-Healthcare-Data-Management

## 📌 Project Overview
This project combines **Quantum-Resistant Cryptography** and **Blockchain Technology** to securely manage and store sensitive healthcare data. It addresses the future risks posed by **quantum computers**, which can easily break traditional cryptographic algorithms like RSA and AES.

By implementing **KYBER** for key exchange and **FALCON** for data encryption (simulated using **QISKIT API**), and storing all transactions on an **Ethereum-based blockchain**, this system ensures patient data remains **confidential**, **tamper-proof**, and **secure** from both classical and quantum attacks.

## 🔑 Key Features
- ✅ Post-quantum secure **key exchange** using KYBER (Qiskit simulation)
- ✅ **Quantum-resistant encryption** using FALCON algorithm
- ✅ **Decentralized data storage** using Ethereum Blockchain
- ✅ **Smart contract-based data management** (Solidity)
- ✅ End-to-end **patient-doctor communication security**
- ✅ **Tamper detection** through blockchain hash verification
- ✅ **Python-Flask backend** integrated with **Web3.py**
- ✅ **User-friendly HTML/JavaScript frontend**

## 🛠️ Technologies Used
| Layer | Technology |
|----|----|
| Quantum Layer | QISKIT, KYBER, FALCON |
| Backend | Python, Flask, Web3.py |
| Blockchain | Ethereum, Solidity Smart Contracts, Ganache, Truffle |
| Frontend | HTML, CSS, JavaScript |
| Deployment | Local Ethereum node (Ganache) |

## 📂 Project Structure
```
├── contracts/                  # Solidity Smart Contracts
├── backend/                    # Python Flask Backend API
├── frontend/                   # HTML + JavaScript Frontend Pages
├── blockchain/                 # Truffle, Migration, Deployment Scripts
├── quantum_key_exchange/       # Qiskit-based Quantum Key Exchange Python Scripts
├── runBlockchain.bat           # Script to start Ethereum Local Node
├── runServer.bat               # Script to start Python Backend Server
└── README.md                   # This File
```

## 🧪 System Workflow
1. **User Registration:** Doctors and patients sign up. Data is saved securely in the blockchain.
2. **Appointment Booking:** Patient books an appointment with a doctor. Disease details and reports are encrypted using FALCON.
3. **Quantum Key Exchange:** Secure key exchange between doctor and patient using KYBER.
4. **Prescription Upload:** Doctor generates and uploads the encrypted prescription.
5. **Prescription Download:** Patient downloads and decrypts the prescription using the shared key.
6. **Blockchain Verification:** Every transaction is logged on Ethereum Blockchain with a unique hash.

## 🚀 How to Run This Project Locally
1. **Start the Ethereum Blockchain Node:**
   ```
   Double click: runBlockchain.bat
   ```
2. **Deploy Smart Contract:**
   ```
   Open terminal in blockchain folder
   Run: truffle migrate
   ```
3. **Start the Backend Flask Server:**
   ```
   Double click: runServer.bat
   ```
4. **Access the Frontend:**
   ```
   Open browser and navigate to: http://127.0.0.1:8000/index.html
   ```
5. **Run Quantum Key Exchange (Optional for Testing):**
   ```
   Run Python script inside quantum_key_exchange/ folder
   ```

## 📸 Sample Screenshots
- ✅ User Registration Page
- ✅ Doctor Login and Appointment View
- ✅ Patient Prescription Download
- ✅ Blockchain Transaction Logs
- ✅ Quantum Key Generation Simulation

## ✅ Conclusion
This project offers a **future-proof healthcare data security system** by integrating **quantum cryptography** with **blockchain immutability**, ensuring protection against both current and next-generation threats.

## 📚 Future Enhancements
- ✅ Deploy on Ethereum Testnet or Mainnet
- ✅ Integrate with IPFS for distributed storage
- ✅ Add biometric authentication for enhanced security
- ✅ Use real-world post-quantum libraries like Open Quantum Safe (OQS)
 
