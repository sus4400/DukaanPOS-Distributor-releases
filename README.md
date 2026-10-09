# 🚚 DukaanPOS Distributor — Wholesale, FMCG Distribution & Van Sales Management

[![Latest Release](https://img.shields.io/github/v/release/sus4400/DukaanPOS-Distributor-releases?color=green&label=Latest%20Version)](https://github.com/sus4400/DukaanPOS-Distributor-releases/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(64--bit)-0078D6?logo=windows)](https://github.com/sus4400/DukaanPOS-Distributor-releases/releases)
[![Runtime](https://img.shields.io/badge/.NET-8.0%20(Self--Contained)-512BD4?logo=dotnet)](https://github.com/sus4400/DukaanPOS-Distributor-releases/releases)
[![Database](https://img.shields.io/badge/Database-SQLite%20(Offline--First)-003B57?logo=sqlite)](https://github.com/sus4400/DukaanPOS-Distributor-releases)
[![Industry](https://img.shields.io/badge/Industry-FMCG%20%7C%20Wholesale%20%7C%20Distribution-2ea44f)](https://github.com/sus4400/DukaanPOS-Distributor-releases)

**DukaanPOS Distributor** is an enterprise-grade wholesale distribution, inventory, order booking, route dispatch, and credit ledger management software engineered specifically for **FMCG distributors, wholesale traders, stockists, agency dealers, and direct-store-delivery (van sales) fleets**.

Built with modern .NET 8 WPF technology, it streamlines bulk commercial invoicing, multi-tier packaging (Cartons / Packs / Units), delivery gate passes, salesman route reconciliation, and customer credit aging analysis — **completely offline with zero recurring cloud fees**.

---

## 💼 Key Features Built for Distributors & Wholesalers

### 1. 📦 Multi-Tier Packaging & Conversion (Carton / Pack / Unit)
- **Nested Unit Hierarchy:** Sell items by **Master Carton (CTN)**, **Inner Pack / Box**, or **Loose Single Unit (Pcs)**.
- **Dynamic Conversion Engine:** Enter orders in cartons or individual pieces — the system automatically calculates units and updates inventory down to the single piece.
- **Tiered Wholesale Pricing:** Set differential wholesale pricing based on order volume (Carton Rate vs Single Unit Rate).

### 2. 📑 Commercial Wholesale Invoicing (A4, A5 & Thermal)
- **Standard A4 Commercial Invoices:** Print formal invoices with company header, tax registration / NTN / STRN numbers, bank details, and customer shipping address.
- **A5 Compact Invoices:** Save paper with clean A5 landscape or portrait distribution bills.
- **80mm Thermal Gate Passes:** Print quick loading slips, driver delivery notes, and counter receipts on thermal paper.
- **Trade Discounts & Tax:** Automated calculation of trade discounts, percentage schemes, and sales taxes per line item.

### 3. 🚚 Order Booking, Dispatch & Gate Pass Management
- **Order Booking Pipeline:** Record advance retailer orders gathered by order-bookers or phone calls.
- **Dispatch Manifests & Loading Sheets:** Consolidate multiple orders into a single warehouse picking list and truck loading sheet.
- **Delivery Challans & Gate Passes:** Generate official delivery documentation for van drivers before vehicles leave the warehouse.
- **Route & Area Assignment:** Group delivery orders by geographic route, sector, or salesman territory.

### 4. 🚐 Van Sales Delivery & Cash Recovery
- **Driver Cash Reconciliation:** Reconcile total dispatched inventory against delivered items, return damages, and driver cash collections.
- **Partial Deliveries & Order Adjustments:** Easily adjust orders on the spot if a retailer takes fewer cartons than originally booked.
- **Damaged & Expiry Returns:** Log damaged, leaking, or expired goods separately with automated credit note creation.

### 5. ⏳ Accounts Receivable & Customer Aging Analysis
- **Aging Buckets:** Monitor overdue receivables categorized into **0–30 Days**, **31–60 Days**, **61–90 Days**, and **90+ Days Overdue**.
- **Credit Limit Controls:** Set maximum credit limits and credit days per retail shop; receive automated warnings when limits are exceeded.
- **Running Ledger Statements:** View and print complete debit/credit transaction histories for any retailer with a single click.
- **Debt Recovery Tracking:** Highlight chronic defaulters and prioritize recovery visits.

### 6. 🏭 Supplier & Principal Manufacturer Accounts (Payables)
- **Principal Purchase Invoices:** Record incoming shipments from parent manufacturers and brand companies with batch tracking.
- **Outsourced & Agency Inventory:** Track third-party consigned items and agency distribution stock.
- **Supplier Ledgers & Balance Statements:** Maintain running balances, advance payments, and bank transfers for principal suppliers.
- **Distributor Margin Reports:** Measure gross margin and net profit after factoring in trade schemes and manufacturer discounts.

### 7. 📥 Bulk Data Import Wizard (Excel / CSV)
- **Fast Onboarding:** Import thousands of products, categories, wholesale rates, and barcodes from Excel or CSV files in minutes.
- **Customer List Import:** Upload your entire existing retailer network with contact numbers, addresses, and opening credit balances.

### 8. 👥 Sales Team, Routes & Permissions
- **Salesman Commission Tracking:** Measure sales volume, recovery rates, and commissions per salesperson or route.
- **Role-Based Security:** Prevent unauthorized staff from editing wholesale prices, granting unapproved discounts, or deleting invoices.

---

## 🖥️ System Requirements

| Specification | Minimum Requirement | Recommended |
| :--- | :--- | :--- |
| **Operating System** | Windows 10 (64-bit, Build 1809 or higher) | Windows 11 (64-bit) |
| **Processor** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 or higher |
| **RAM** | 4 GB | 8 GB or 16 GB |
| **Storage** | 500 MB free space | Fast SSD (Solid State Drive) |
| **Display** | 1366 x 768 resolution | 1920 x 1080 (Full HD) |
| **Invoice Printer** | Standard A4 / A5 Laser or Inkjet Printer | High-Speed Laser Printer |
| **Receipt / Slip Printer** | 80mm ESC/POS Thermal Printer (Optional) | 80mm Thermal Printer for Gate Passes |
| **Barcode Scanner** | USB 1D/2D Barcode Scanner (Optional) | Long-range wireless scanner for warehouse picking |

---

## 📥 Installation & Quick Setup Guide

### Step 1: Download
Download the latest installer (`DukaanPOS-Distributor-Setup-x.x.x.exe` or `DukaanPOS-Setup-x.x.x.exe`) from the [**Releases Page**](https://github.com/sus4400/DukaanPOS-Distributor-releases/releases/latest).

### Step 2: Install
1. Run the downloaded installer.
2. Complete the setup wizard (all dependencies and .NET 8 runtimes are bundled; no internet or extra downloads required).
3. Ensure **Create a Desktop Shortcut** is checked and click **Finish**.

### Step 3: First-Time Company Configuration
1. Open **DukaanPOS Distributor** from your desktop shortcut.
2. Go to **Settings > General**:
   - Enter your **Company Name**, **Warehouse Address**, and **Contact Numbers**.
   - Fill in your **NTN / STRN / Tax Registration Numbers** (will appear automatically on A4 invoices).
   - Configure your **Bank Account Details** for customer payment transfers.
   - Set your **Currency Symbol** (e.g., `Rs`, `$`, `AED`).
3. Go to **Settings > Printing**:
   - Choose your default Invoice Printer (A4 Laser / Inkjet) and/or Slip Printer (80mm Thermal).
   - Select your preferred default format (**A4 Standard**, **A5 Half-Page**, or **80mm Thermal**).

### Step 4: Add Products & Retailers
1. Use **Data Import Wizard** to import your products and retailers from Excel, or add them manually under **Inventory** and **Customers**.
2. Configure packaging conversions (e.g., *1 Carton = 24 Pieces*).
3. Start booking orders and generating dispatches immediately!

---

## 🛡️ Data Safety, Offline Reliability & Upgrades

- **Complete Data Sovereignty:** All your distributor records, sales ledgers, customer aging histories, and inventory figures are stored on your local hard drive in:
  ```text
  %LocalAppData%\DukaanPosDistributor\dukaan-pos.db
  ```
- **Zero Data Loss Guarantee:** Updating to newer software releases will **NEVER** overwrite, reset, or erase your database. Upgrades are seamless and safe.
- **One-Click Backup:** dukaan-pos database can be backed up at any time via Settings or copied to an external drive or cloud folder for secure offsite preservation.

---

## ❓ Frequently Asked Questions (FAQ)

#### Q: Can I sell items in both Cartons and individual Units?
**Yes.** DukaanPOS Distributor includes a packaging conversion system. You can define how many units make up an inner box or master carton. During billing, you can sell in full cartons, loose units, or both, and the system automatically updates stock accordingly.

#### Q: Does it print formal commercial A4 invoices?
**Yes.** The system generates clean, professional A4 commercial invoices featuring your company header, tax numbers (NTN/GST), customer details, batch info, item breakdown, and terms of payment. You can also print in A5 half-page or 80mm thermal formats.

#### Q: How does the Route Dispatch & Van Sales workflow work?
You can book customer orders in advance, group them by delivery route or vehicle, and generate a **Loading Sheet / Dispatch Challan** for the driver. When the van returns, you record delivered items, any returned or damaged stock, and reconcile the cash and credit balances.

#### Q: How does Accounts Receivable Aging help my distribution business?
The Aging Report automatically categorizes all unpaid balances into age brackets (0–30, 31–60, 61–90, 90+ days). This immediately highlights overdue accounts and overdue amounts before you dispatch new stock to high-risk retailers.

#### Q: Can I import my existing product catalog from Excel?
**Yes.** DukaanPOS Distributor features an intuitive Data Import Wizard that lets you import thousands of products, wholesale rates, and customer contacts directly from CSV or Excel spreadsheets.

#### Q: Does DukaanPOS Distributor require an internet connection?
**No.** The software runs 100% offline. No internet connection is required to create invoices, print delivery challans, or reconcile routes.

---

## 📞 Support & Release Updates

- **Download Latest Releases:** [github.com/sus4400/DukaanPOS-Distributor-releases/releases](https://github.com/sus4400/DukaanPOS-Distributor-releases/releases)
- **Submit Issues & Feature Requests:** [Open an Issue](https://github.com/sus4400/DukaanPOS-Distributor-releases/issues)

*Engineered to empower FMCG distributors and wholesale operations with uncompromised speed, control, and financial clarity.*
