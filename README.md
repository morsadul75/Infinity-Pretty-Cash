# 💰 Infinity Daily Pretty Cash

A lightweight, single-page web application designed to track daily budgets, opening balances, incoming funds, and categorized expenditures effortlessly. Features instant single-page printing, local browser persistence, and optional real-time cloud sync powered by Firebase Firestore.

🚀 **Live Web App:** [https://morsadul75.github.io/Infinity-Pretty-Cash/](https://morsadul75.github.io/Infinity-Pretty-Cash/)

---

## ✨ Features

* **Instant Financial Summary:** Automatically calculates **Grand Total Cash Received** (Opening Balance + Today's Budget + Additional Cash), total expenditures, and final remaining balance.
* **Pre-configured Categories:** Fast entries using pre-defined expense categories like *VAT, Conveyance, Gum Tape, Al Madina Bill, Kerosine, Thinner, Advance Salary, Saline, Ruhul Amin Bill, Romi Eng Bill, Forklift*, and custom items.
* **Dual Storage Engine:** Works out-of-the-box using local browser storage (`localStorage`) or connects to Google Firebase Firestore for permanent cloud backup.
* **1-Page Print Ready:** Built-in PDF/Print stylesheet formatted with 50px section spacing and standard double-signature footer lines.
* **Historical Lookup:** Load previous daily summaries instantly using the built-in date selector.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
* **Styling Framework:** Tailwind CSS CDN
* **Database:** Firebase Firestore SDK (v9/v10 compatibility layer) & Browser LocalStorage
* **Hosting:** GitHub Pages

---

## ⚙️ Quick Setup & Cloud Connection

1. Open the live app: `https://morsadul75.github.io/Infinity-Pretty-Cash/`
2. Click on **Firebase Settings**.
3. Fill in your Firebase Web App configuration keys:
   * `apiKey`
   * `authDomain`
   * `projectId`
   * `appId`
4. Click **Connect Firebase**. The app indicator will turn green (`● Firebase Connected`).
