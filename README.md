Project Prompt: BMS Business Management System — Android APK + Windows PC

Act as a senior Android developer, full-stack software engineer, and business ERP architect. Build a complete, production-ready BMS (Business Management System) for my company.

1. Project Requirements

Company name: BMS

Android application: Installable APK for Android phones

Desktop application: Windows 10/11

Users: 5–10

Business coverage: UAE and GCC

Hosting: No cloud hosting

Connectivity: Local Wi-Fi/LAN

Database: One shared database for Android and Windows

Interface: Modern, colourful, professional corporate ERP dashboard

2. Required Modules

Dashboard with sales, expenses, invoices, shipments, and outstanding payments.

Customer and supplier management.

Quotations with automatic numbering and PDF export.

Sales invoices, payment tracking, and printable invoices.

Freight forwarding and shipment management for air, sea, and land freight.

GCC transportation and cross-border shipment tracking.

Packing lists and shipment documentation.

Expense management and profit/loss reports.

User accounts, roles, permissions, and activity logs.

Company settings, VAT configuration, currencies, and document numbering.

Individual logos and customizable layouts for quotations, invoices, and packing lists.

PDF printing, Excel/CSV export, database backup, and restore.

3. Shared Database — No Cloud

Create a local API server that runs on the Windows PC and connects to a central database. The Android app must connect to this API over the same Wi-Fi/LAN network.

Both platforms must read and update the same records.

Use authentication and role-based access.

Use a reliable database such as SQLite for a single-PC deployment or PostgreSQL if required for concurrent users.

Provide automatic backups and recovery tools.

Do not store separate, disconnected customer or invoice databases on each device.

Provide clear connection status and error messages.

Document the Windows firewall and local network setup.

4. Android APK Requirements

Create a genuine native Android application.

Use a modern, responsive interface.

Include login, dashboard, forms, search, filters, and reports.

Connect to the Windows local API.

Support secure session handling and network error recovery.

Generate a signed release APK suitable for installation on Android.

Provide the debug APK for testing.

Do not provide a fake download link or an uncompiled APK.

5. Windows Requirements

Provide a Windows desktop application and a local API service.

Include a simple installation process and desktop shortcut.

Start the local service reliably and explain how to configure it.

Make the Windows PC the central host for shared records.

Include database backup and restore functionality.

6. Technical Requirements

Choose a maintainable technology stack. For example:

Android: Kotlin and Jetpack Compose.

Windows/API: Python with FastAPI.

Database: SQLite for an initial single-host deployment.

API communication: REST over the local network.

Document generation: PDF and spreadsheet exports.

Design the API, authentication, database schema, migrations, validation, logging, and error handling before implementation.

7. Deliverables

Provide:

Complete Android source code.

A real, installable APK file.

Complete Windows application source code and installer.

Local API server and database.

Installation instructions in simple English.

Setup instructions in Malayalam if possible.

Backup and restore instructions.

Testing evidence showing that records created on Windows are visible on Android and vice versa.

A direct download link to the actual compiled APK only after the build succeeds.

8. Acceptance Criteria

The project is complete only when:

The APK installs and opens on a real Android phone.

Windows and Android can connect over the same Wi-Fi.

Creating or editing a customer, quotation, invoice, shipment, or expense on either platform updates the shared database.

Authentication, permissions, backups, PDF documents, and reports work.

The application has been built, tested, and its limitations are documented.

Start by inspecting any existing BMS desktop source code and preserving useful functionality. Then implement the shared API and database, build the Android screens, compile the APK, test the complete workflow, and provide the finished deliverables. Do not stop at a mockup, a website, a project ZIP, or instructions alone.
