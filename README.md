# Stellar Student DApp

Stellar Student DApp – Blockchain Based Student Data Management System

---

## Project Description

Stellar Student DApp is a decentralized smart contract solution built on the Stellar blockchain using Soroban SDK.
This project provides a secure and transparent platform for storing and managing student data directly on-chain.

The smart contract allows users to create, view, update, and delete student records using predefined contract functions.
All student information is stored in the contract storage, ensuring data persistence, integrity, and decentralization without relying on centralized databases.

Each student record is uniquely identified and permanently stored on the blockchain, providing reliability and security.

---

## Project Vision

Our vision is to demonstrate how blockchain technology can be used for secure academic data management by:

* Decentralizing Data Storage — moving student records to a distributed blockchain network
* Ensuring Ownership — data cannot be modified without contract interaction
* Guaranteeing Integrity — records stored on-chain cannot be tampered with
* Enhancing Security — blockchain cryptography protects stored information
* Building Trustless Systems — no central authority required

This project shows how decentralized applications can be used in education systems.

---

## Key Features

### 1. Student Creation

* Add new student data using smart contract
* Automatic ID generation
* Store name and major
* Persistent blockchain storage

### 2. Data Retrieval

* Fetch all stored students
* Fast access from contract storage
* Structured data format
* Ready for frontend integration

### 3. Update Student

* Modify student name or major
* Update using student ID
* Changes stored permanently on-chain

### 4. Delete Student

* Remove student by ID
* Immediate update of storage
* Clean data management

### 5. Blockchain Security

* Data stored on Stellar blockchain
* Immutable transaction history
* Safe smart contract execution
* No centralized database

### 6. Soroban Smart Contract

* Built using Rust
* Uses soroban_sdk
* Uses contract storage
* Uses Vec and Symbol keys

---

## Contract Details

Contract Address:

```
PUT_YOUR_CONTRACT_ID_HERE
```

Example:

```
CBUXXXXXXXXXXXXXXXXXXXXXXXXXXXX
```

You can get the contract ID after deploy:

```
stellar contract deploy
```

Screenshot:

![Contract](screenshots/contract.png)

---

## Future Scope

### Short-Term Improvements

1. Add student age field
2. Add GPA field
3. Add search function
4. Add pagination

### Medium-Term Development

5. Frontend integration
6. Wallet authentication
7. Multi-user interaction
8. Event logging

### Long-Term Vision

9. Full academic record system
10. Multi-contract integration
11. Cross-chain storage
12. Decentralized identity support
13. NFT certificate storage
14. DAO-based management

### Enterprise Features

15. University record system
16. Audit logging
17. Access permissions
18. Multi-language support

---

## Technical Requirements

* Rust
* Soroban SDK
* Stellar CLI
* Stellar Network
* Smart Contract Storage

---

## Getting Started

Build contract

```
cargo build
```

Deploy contract

```
stellar contract deploy
```

Invoke functions

```
create_student
get_students
update_student
delete_student
```


---

Stellar Student DApp — Secure Student Data on Blockchain
