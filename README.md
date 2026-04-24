# 🔍 ASP.NET Core Logging Visualizer

A simple web-based project built with **HTML, CSS, and JavaScript** to demonstrate and visualize how **Logging works in ASP.NET Core**.

This project helps developers understand logging concepts in a clear and interactive way, instead of just reading documentation.

---

## 🚀 Overview

Logging is a critical part of any modern application.
In ASP.NET Core, logging provides insight into application behavior, errors, and performance.

This project visually explains:

* Logging Levels
* Logging Categories
* Logging Providers
* Configuration using `appsettings.json`
* Real-world logging flow

---

## 🧠 What You Will Learn

By exploring this project, you will understand:

* How ASP.NET Core handles logging internally
* The purpose of each logging level
* How logs are filtered using categories
* How to configure logging behavior
* How different providers store or display logs

---

## 📊 Logging Levels

ASP.NET Core supports multiple logging levels:

* **Trace** → Detailed information (very low-level)
* **Debug** → Debugging information
* **Information** → General application flow
* **Warning** → Something unexpected but not critical
* **Error** → A failure occurred
* **Critical** → Serious failure (application crash)

---

## 🗂️ Logging Categories

Categories are used to group logs.

Examples:

* `Microsoft` → Framework logs
* `System` → System-level logs
* `YourApp.Controllers` → Custom application logs

They help in filtering logs based on source.

---

## ⚙️ Logging Providers

Logging providers determine **where logs are written**.

Common providers:

* Console Provider
* Debug Provider
* File Provider (e.g., using Serilog)
* Event Source / Event Log

---

## 🛠️ Configuration Example

Example from `appsettings.json`:

```json
"Logging": {
  "LogLevel": {
    "Default": "Information",
    "Microsoft": "Warning",
    "System": "Warning"
  }
}
```

This means:

* Default logs → Information and above
* Microsoft & System → Only warnings and errors

---

## 🎯 Project Features

* Interactive UI to explain logging concepts
* Clean and simple design using HTML & CSS
* JavaScript-based dynamic explanation
* Beginner-friendly explanation of backend concepts

---


## 🧑‍💻 Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)

---


## 🤝 Contributing

Feel free to fork the repo and improve it.
Pull requests are welcome!

---

## 📬 Contact

If you have any questions or suggestions, feel free to reach out.

---

## ⭐ Support

If you found this project helpful, give it a ⭐ on GitHub!
