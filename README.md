# 🔐 SmartContracts-for-Verification

Welcome to **SmartContracts-for-Verification**, a curated repository of smart contracts intentionally designed with known vulnerabilities. These contracts are aligned with the **SWC (Smart Contract Weakness Classification)** registry and serve as a benchmark suite for evaluating and comparing formal verification tools.

## 📌 Overview

This repository provides a collection of vulnerable smart contracts that can be used to:

* 🧪 Test and benchmark smart contract verification tools
* 🔍 Analyze common security flaws in Ethereum smart contracts
* 📊 Compare detection capabilities across different verification frameworks
* 🎓 Support educational and research purposes in blockchain security

---

## 🧰 Supported Verification Tools

The contracts in this repository are intended to be analyzed using the following tools:

* **SolCMC**
* **Certora**
* **eThor**
* **HoRStify**
* **Securify2**

Each tool offers a different approach to formal verification, ranging from symbolic execution to model checking and rule-based analysis.

---

## ⚠️ Vulnerabilities Covered

All vulnerabilities included in this repository are based on the **SWC Registry**, which categorizes common smart contract weaknesses such as:

* Reentrancy
* Integer Overflow/Underflow
* Unchecked Call Return Values
* Access Control Issues
* Front-running
* Assert/Require violations
* Shadow State vars
* Timestamp manipulation

These examples are intentionally vulnerable and **must not be used in production environments**.

