# 🔐 Cryptography and Blockchain Fundamentals

A collection of Python projects developed as part of learning cryptography and blockchain fundamentals. This repository demonstrates SHA-256 hashing, digital signatures, a blockchain-based voting system, and vehicle registration.

## 📌 Projects Included

### 1. 🔑 SHA-256 Hash Generator

- Accepts a message from the user.
- Generates its SHA-256 hash using Python's `hashlib` module.
- Demonstrates how hashing helps verify data integrity.

### 2. ✍️ Digital Signature

- Generates a public-private key pair.
- Signs messages using a private key.
- Verifies signatures using the corresponding public key.
- Detects changes to a signed message during verification.

**Technology:** Python, RSA, `cryptography`

### 3. 🗳️ Blockchain Voting System

A menu-driven voting application built using Python to demonstrate basic blockchain concepts.

**Features:**
- Add and display election candidates.
- Cast votes using a voter ID.
- Allow only one vote per voter ID.
- Reject votes for invalid candidates.
- Store votes in blocks linked through SHA-256 hashes.
- Create a genesis block to start the blockchain.
- Display candidate vote counts and election results.
- Validate the blockchain by checking block hashes and previous-hash links.
- Display the blocks and their stored information.

**How it works:**

1. Candidates are added to the voting system.
2. A voter enters their voter ID and selects a candidate.
3. The system checks the voter ID and candidate.
4. The vote is recorded in a block linked to the previous block.
5. SHA-256 hashes help detect changes to stored block data.
6. The application can validate the blockchain and display election results.

**Note:** This is an educational Python project, not a production-ready election system. The blockchain is implemented in application code and does not provide the full security guarantees of a distributed blockchain network.

### 4. 🚗 Vehicle Registration System

A simple console-based application for registering and retrieving vehicle information.

**Features:**
- Register a vehicle using its number plate, owner name, and model.
- Store vehicle details in a Python dictionary.
- Retrieve vehicle details using the number plate.
- Reject duplicate number plates.
- Validate empty number plates, owner names, and vehicle models.
- Display an error if a vehicle is not registered.
- Use a menu-driven loop to perform multiple operations.

**Example:**

```text
===== VEHICLE REGISTRATION SYSTEM =====
1. Register Vehicle
2. Get Vehicle Details
3. Exit
```

## 🛠️ Technologies Used

- Python 3
- SHA-256 Hashing
- RSA Digital Signatures
- Python `hashlib` module
- Python `cryptography` library
- Dictionaries, functions, and loops
- Git and GitHub

## 📂 Project Structure

```text
Cryptography-and-Blockchain-Fundamentals/
│
├── voting_system.py
├── vehicle_registration.py
├── digital_signature.py
├── hash_generator.py
└── README.md
```

*The filenames above are examples. Update this structure to match the actual files in your repository.*

## ⚙️ Installation

### 1. Install Python

Download Python from:

https://www.python.org/downloads/

### 2. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace the placeholder with your actual repository URL.

### 3. Enter the Project Directory

```bash
cd Cryptography-and-Blockchain-Fundamentals
```

### 4. Install Dependencies

For projects that use the `cryptography` library:

```bash
pip install cryptography
```

Or install all dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Projects

Run the relevant Python file from the terminal.

**SHA-256 Hash Generator**

```bash
python hash_generator.py
```

**Digital Signature**

```bash
python digital_signature.py
```

**Blockchain Voting System**

```bash
python voting_system.py
```

**Vehicle Registration System**

```bash
python vehicle_registration.py
```

*Use the actual filenames present in your repository.*

## 🧪 Testing and Validation

The projects can be tested with the following cases:

- Generate a SHA-256 hash for a sample message.
- Sign a message and verify the signature.
- Modify a signed message and check that verification fails.
- Cast a vote for a valid candidate.
- Try voting twice with the same voter ID.
- Try voting for an invalid candidate.
- Validate the blockchain and check its hash links.
- Register a vehicle and retrieve it by number plate.
- Attempt to register a duplicate number plate.
- Search for a vehicle that does not exist.

## ⚠️ Limitations

- Data stored only in dictionaries or memory is lost when the program terminates.
- The voting application is an educational blockchain simulation, not a decentralized network.
- Hash linking can help detect data tampering, but by itself it does not guarantee complete blockchain security.
- These projects are intended for learning and demonstration purposes.

## 🎯 Learning Outcomes

Through these projects, I practiced:

- Generating SHA-256 hashes.
- Understanding public and private keys.
- Creating and verifying digital signatures.
- Understanding blockchain blocks and hash linking.
- Implementing a basic blockchain voting system.
- Validating voter IDs and candidate selections.
- Implementing vehicle registration and duplicate checking.
- Building menu-driven Python applications.
- Managing code with Git and GitHub.

## 👨‍💻 Author

**Rehan Ansari**

Computer Science Engineering Student

Interests: Python, Cryptography, Blockchain Development, and Web3.

## 📜 Acknowledgement

Developed as part of learning and practicing cryptography and blockchain fundamentals, including the Tutedude assignment.

---

⭐ If you find these projects useful, explore the code and try running the applications locally.

