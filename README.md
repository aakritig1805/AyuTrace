# 🍃 AyuTrace

> A modern, transparent, and secure supply chain tracing application designed for Ayurvedic herbs and wellness products.

---

## 📖 Introduction

In the Ayurvedic industry, authenticity and purity are paramount. **AyuTrace** provides a clear, verifiable chain of custody for herbal batches. It bridges the gap between different stakeholders in the supply chain:

1.  **Collectors:** Who source and harvest herbs.
2.  **Laboratories:** Who run chemical analyses to verify purity and check for contaminants.
3.  **Processors:** Who convert raw herbs into final shelf-ready consumer products.
4.  **Consumers:** Who scan product QR codes to view the complete history of their purchased items.
5.  **Admins:** Who govern the system registration and actor authorization.

---

## 📂 Repository Structure

This repository is structured as follows:

*   **`AyurTraceProject/`**: The core frontend web application, built with React, Vite, Tailwind CSS, Framer Motion, and Shadcn UI. It includes:
    *   Collector Dashboard (`/collector`)
    *   Lab Analysis Portal (`/lab`)
    *   Processor Facility Dashboard (`/processor`)
    *   Consumer Verification Timeline (`/consumer`)
    *   Admin Settings & Audit Log (`/admin`)

---

## 🚀 Quick Start

To run the web portal locally:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/aakritig1805/AyuTrace.git
    cd AyuTrace
    ```

2.  **Navigate to the web portal directory:**
    ```bash
    cd AyurTraceProject
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```

4.  **Launch the development server:**
    ```bash
    npm run dev
    ```

5.  **Open in browser:**
    Visit `http://localhost:5173` to explore the dashboards.

---

## 🛠️ Key Technologies

*   **Frontend Core:** React, Vite, TSX/JSX
*   **State & Query Caching:** TanStack React Query
*   **Interactive Visualizations:** Recharts (Analytics and statistics)
*   **Animation Engine:** Framer Motion (Transitions and interactive micro-animations)
*   **Styling:** Tailwind CSS (Custom nature-toned color variables)
*   **Routing:** React Router DOM
*   **QR Scanner Integration:** `@yudiel/react-qr-scanner` and `html5-qrcode`

---

## 🧑‍💻 Author

*   **aakritig1805** (Owner and Primary Developer) - [GitHub Profile](https://github.com/aakritig1805)
