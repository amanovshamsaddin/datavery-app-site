# DataVery.app 🚀

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fdatavery.app)](https://datavery.app)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)]()
[![Python](https://img.shields.io/badge/Python-Pyodide-3776AB?logo=python&logoColor=white)]()

**DataVery** is a zero-build-step, fully client-side interactive data science portfolio and learning laboratory. Built from first principles, it combines a professional resume with a suite of live technical environments, executing Python, SQL, and Assembly directly in the browser.

[**🔗 View Live Application**](https://datavery.app)

---

## 🎯 Project Overview

This application serves as both a professional portfolio and an interactive sandbox for my Master of Data Science coursework at Monash University. Instead of just listing skills, DataVery proves them by compiling and executing code entirely on the client side without relying on backend servers.

### Key Features

* **🐍 Python Lab Pro:** A fully functional Jupyter-style notebook running entirely in the browser using **Pyodide** (WebAssembly). It includes a custom Abstract Syntax Tree (AST) evaluator, a variable inspector, a virtual file system (EMFS) for CSV uploads, and custom Matplotlib hooks for inline plotting.
* **🗄️ DB ERD Lab & SQL Sandbox:** An interactive Entity-Relationship Diagram builder combined with an in-memory SQL engine powered by **AlaSQL**. Users can design schemas graphically, generate DDL, and run complex SQL queries against custom or pre-loaded datasets.
* **📊 Data Playground:** A dynamic data visualization tool. Users can upload raw CSV/TSV files, automatically detect data types, generate statistical summaries, and render charts using **Chart.js**.
* **⚙️ MARIE Simulator:** A custom-built assembler and virtual machine for the MARIE (Machine Architecture that is Really Intuitive and Easy) architecture. It supports a two-pass assembler, memory inspection, step-through execution, and CPU register tracking.
* **📂 Interactive Portfolio:** A dynamic, multi-theme interface detailing my professional background, GitHub repository integration via API, and a custom philosophical log.

---

## 🛠️ Technical Stack

DataVery is built with a focus on raw performance and zero dependencies on backend infrastructure. 

* **Frontend:** HTML5, CSS3 (Custom Properties for dynamic theming), Vanilla JavaScript.
* **Code Editing:** [CodeMirror 5](https://codemirror.net/5/) for syntax highlighting and IDE-like features.
* **Data Science Engine:** [Pyodide](https://pyodide.org/) for running CPython and the scientific stack (NumPy, Pandas, Scikit-Learn) via WebAssembly.
* **Database Engine:** [AlaSQL](https://github.com/agershun/alasql) for fast, in-memory relational database operations.
* **Visualization:** [Chart.js](https://www.chartjs.org/) for rendering responsive data graphics.

---

## 🚀 Local Setup

Because DataVery is entirely client-side, running it locally requires zero installation or build steps.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/amanovshamsaddin/datavery-app-site.git](https://github.com/amanovshamsaddin/datavery-app-site.git)
    ```
2.  **Navigate to the directory:**
    ```bash
    cd datavery-app-site
    ```
3.  **Run the application:**
    Simply open `index.html` in any modern web browser.
    *Note: For some features like Pyodide to fetch remote WASM binaries, an active internet connection is required upon initial load.*

---

## 📸 Interface Previews

*(Replace these placeholder links with actual screenshots of your app once you upload them to an `assets/` folder in your repo)*

* `![Python Lab](assets/python-lab.png)`
* `![Database ERD](assets/db-erd.png)`
* `![MARIE Simulator](assets/marie-sim.png)`

---

## 🤝 Contact & Connections

Designed and developed by **Shamsaddin Amanov**.

* **LinkedIn:** [/in/theamanov](https://www.linkedin.com/in/theamanov/)
* **GitHub:** [@amanovshamsaddin](https://github.com/amanovshamsaddin)
* **Portfolio:** [datavery.app](https://datavery.app)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
