# Store Management System - Premium Retail Solutions

A lightweight, secure, and modern Single-Page Application (SPA) designed to manage retail inventories, track active stock levels, handle customer and supplier directories, and process real-time point-of-sale (POS) billing with custom scannable receipts.

## 🚀 Key Features

- **Point-of-Sale (POS) Billing Engine:** 
  - Dynamic billing form with real-time stock-availability validation.
  - Generates instant official invoices featuring customer metadata, calculated subtotals, and custom verification QR codes.
- **Inventory & Stock Management:**
  - Automated status indicators (Good, Low, Critical) based on remaining stock levels.
  - Instant stock quantity updates and dynamic product search.
- **Scannable QR Codes Engine:**
  - **Store Profile QR:** Scan to instantly open the store database profile.
  - **Product QR Code:** Automatically generates a lookup QR code for every product added to the directory.
- **CRM Directories (Customers & Suppliers):**
  - Consolidated logs to track customer contact details and supplier associations.
- **Interactive Reports & Analytics:**
  - Responsive charts representing category demand and a complete chronological sales history.
- **Persistent Storage:** Browser **LocalStorage** synchronization for offline-ready data persistence.

## 🛠️ Tech Stack Used

- **Markup & Layout:** HTML5
- **Responsive Styling:** Tailwind CSS (via CDN)
- **Icons Library:** FontAwesome v6.4
- **Scripting & Business Logic:** Vanilla JavaScript (ES6)
- **Local Storage:** Browser LocalStorage