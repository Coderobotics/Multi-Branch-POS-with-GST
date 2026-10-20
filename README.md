# Multi Branch POS with GST

Retail POS is a point-of-sale system for retail chains with more than one branch. It's built with Laravel 12, Livewire 3 and Tailwind CSS, runs in the browser and installs as an app (PWA). It covers barcode checkout, split payments, inventory and stock ledgers, purchasing with input GST, branch-to-branch transfers, cash shifts with X/Z reports, returns and credit notes, coupons and price lists, and expense tracking. It fully supports Indian GST, including CGST, SGST, IGST, HSN codes and GSTR-1 reports. Branches can also use other currencies with VAT, such as AED with 5% VAT. There are 18 reports with CSV export, an audit trail of every change, and five staff roles with 31 permissions. The POS keeps working without internet and syncs offline sales automatically, without duplicates. It is a good fit for supermarkets, fashion and electronics stores, mall shops and franchise chains. Buyers get the complete source code for a one-time payment, with one year of free updates and email support.

<img src="https://www.coderobotics.com/frontend/assets/icon/retail-pos-multi-branch-php-script.jpg">

Most POS systems run one shop well. They struggle once you add a second branch, a store in another state or a counter in another country, or when the Wi-Fi goes down at 7 pm on a Saturday. Retail POS was built for that. Each branch has its own staff, stock, prices, currency and tax rules, and the owner sees everything combined on one dashboard. Billing never stops, because sales made offline are kept on the device and uploaded automatically later.

What You Get
 
Fast POS terminal: sell by barcode, SKU or name. USB scanners work anywhere on the screen, and the camera works as a scanner on Chrome/Android. There are keyboard shortcuts (F2–F9) for a fast checkout.
Smart cart: quantity stepper, decimal quantities for weighed items, automatic offers, customer quick-add, and sales you can hold and resume.
Flexible payments: cash, card, UPI, wallet or split payment, with quick cash buttons and change worked out for you.
Full Indian GST: GST rate and HSN code per product, and CGST + SGST or IGST chosen automatically from the customer's state. GSTIN is validated, prices can include tax, and bills round off to the rupee.
Multi-currency branches: INR branches use GST, and other currencies use a flat VAT/sales tax (for example AED with VAT 5%). Every sale stores its exchange rate, so combined totals stay correct.
Receipts and documents: 80 mm thermal and PDF tax invoices, credit notes, and shift X/Z reports. Numbering runs per branch (e.g. CHN-2610-00001).
Inventory: stock on hand per branch or across all branches, stock adjustments with a reason, a guard that stops stock going negative, and a complete stock ledger with running balances.
Purchasing: suppliers with GSTIN and dues, goods received with input GST (CGST/SGST/IGST), landed-cost tracking, and full, partial or due payments.
Branch transfers: send, receive and cancel, with stock tracked while in transit.
Cash shifts: opening cash, cash in/out, automatic expected cash, denomination counting, and Balanced / Over / Short results on close.
Returns and refunds: partial or full returns with the tax reversed exactly as charged, optional restock, loyalty points deducted, and credit notes.
Promotions: percent or fixed-amount coupons with minimum bill, cap, expiry, usage limit and branch limits. Price lists cover wholesale, staff and similar.
Expenses: categories, payees and methods. Cash taken from the till reduces that shift's expected cash.
18 reports with CSV export: daily sales, by branch, cashier, payment method and category, product performance, returns, customers, purchases, stock valuation, stock movement, reorder suggestions, expenses, and profit & loss.
GSTR-1 ready: B2B invoices (table 4), B2C summary (table 7), HSN summary (table 12) and credit notes (table 9B).
Audit Center: every create, update and delete, plus sign-ins and sign-outs, with old and new values, IP address and device.
Offline sales: keep billing without internet and print provisional receipts. Sales upload automatically with their original counter time, and are never duplicated or refused at sync time.
Roles and permissions: super admin, branch admin, manager, cashier and staff, with 31 permissions you can edit in a role matrix.
Modern app shell: light/dark theme, Ctrl + K page search, a notification bell for low stock, transfers, dues and enquiries, a live sync-status pill, and a mobile layout with bottom navigation.
Landing website: a one-page product website with a "Request a demo" form.
Full demo data: 4 branches, 15 staff, 40 products and about 430 sales, ready to explore.

Why This POS?
 
Small retail chains often end up with one tool for billing, a spreadsheet for stock, another app for GST and a notebook for the cash drawer. Retail POS puts all of that in one place:

Built for multiple branches, not a single shop with branches added later.
Indian GST built in, including IGST for other states and GSTR-1 tables.
Works offline, so a bad connection never stops a sale.
Strict cash control with shift gates, X/Z reports and over/short tracking.
Audit trail for every change, so there are no unexplained edits.
Tested: 58 automated PHPUnit tests (548 assertions) plus browser end-to-end tests on desktop and phone widths.
Installs like an app on desktops, tablets and phones.
Perfect For
 
Retail chains and franchise stores with several branches
Supermarkets, grocery, fashion, electronics and general stores
Shops inside malls and multi-location brands
Businesses in India that need GST and GSTR-1 reports
Retailers in the UAE / GCC or other VAT countries
Developers and agencies building POS solutions for clients
Students and learners studying Laravel, Livewire and PWA architecture

Tech Stack
 
Laravel 12 (PHP 8.2+)
Livewire 3
Alpine.js
Tailwind CSS v4
MySQL / MariaDB
spatie/laravel-permission (roles and permissions)
owen-it/laravel-auditing (audit trail)
barryvdh/laravel-dompdf (PDF invoices)
picqer/php-barcode-generator (barcodes)
Service Worker + Web App Manifest (PWA and offline mode)
PHPUnit and Puppeteer (automated testing)

Prerequisites
 
PHP 8.2 or higher with pdo_mysql, intl, gd, mbstring, fileinfo and zip
Composer 2
Node.js 20+ and npm
MySQL 8 or MariaDB 10.4+ (XAMPP works)
HTTPS in production, for app install, offline mode and camera scanning

More details and download link:
https://www.coderobotics.com/product/multi-branch-pos-with-gst
