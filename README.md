# ChhitoLedger
Digital version of Ledgers and Daybook

CHHITO LEDGER - USER MANUAL
============================
Version 1.3.1 | Developer: Tulaaram Kathariya
Website: tularam.com.np | Phone: +977 9848491651


CHAPTER 1: GETTING STARTED
============================


1.1 SYSTEM REQUIREMENTS
    - Operating System: Windows 10 / 11 (64-bit)
    - RAM: Minimum 2 GB
    - Storage: Minimum 200 MB free
    - Screen: Minimum 1366x768 resolution

1.2 INSTALLATION
    1. Run the ChhitoLedger_Setup.exe installer
    2. Read and accept the End User License Agreement
    3. Choose installation folder (default recommended)
    4. Click Install and wait for completion
    5. Launch Chhito Ledger from Desktop or Start Menu

1.3 SOFTWARE ACTIVATION
    - On first launch, you will see the Activation Screen
    - Note your Hardware ID shown on screen (e.g., ABCD-1234-EFGH-5678)
    - Contact the developer at +977 9848491651 or tularam.com.np
      with your Hardware ID to receive your unique License Key
    - Enter the License Key and click "Activate Software"
    - Activation is tied to your specific computer - each PC
      requires its own license key


CHAPTER 2: FIRST TIME SETUP
============================

2.1 SET ADMIN PIN
    - On first login, you will be prompted to create a 4-6 digit PIN
    - This PIN protects access to your accounting data
    - Keep this PIN secure

2.2 CREATE COMPANY
    - After login, click "Create Company"
    - Enter: Company Name, Address, Phone, PAN/VAT Number
    - Optionally upload Company Logo and Official Stamp
    - Click Save

2.3 SELECT ACTIVE COMPANY
    - Click on your company name to open the Dashboard
    - You can create multiple companies and switch between them


CHAPTER 3: DASHBOARD OVERVIEW
==============================

The Dashboard has the following sections in the left sidebar:

  [Flash Icon]   FAST BILLING     - Quick invoice/bill creation
  [People Icon]  CLIENTS          - Client ledger management
  [Work Icon]    SALARY           - Staff salary ledger
  [Bank Icon]    BANK             - Bank account tracking
  [Money Icon]   LIABILITIES      - Loans and liabilities
  [Receipt Icon] EXPENSES         - Daily expense tracking
  [Calendar]     DAYBOOK          - Daily cash summary
  [Analytics]    REPORTS          - Financial reports
  [Settings]     SETTINGS         - Backup, Restore, Date settings


CHAPTER 4: FAST BILLING
=========================

4.1 CREATING A BILL
    1. Click "Fast Billing" in the sidebar
    2. Select Client from the dropdown
    3. Enter Item Name, Quantity, Unit (default: Months), Rate
    4. Click "Add Item" to add to bill
    5. Add more items as needed
    6. Click "Save & Post to Ledger"
    - Bill is automatically recorded in the Client ledger
    - A printable receipt appears for thermal/regular printing

4.2 PRINTING BILLS
    - After saving, the print preview opens automatically
    - Click the Print icon and select your connected printer
    - Supports thermal printers (80mm roll) and regular printers


CHAPTER 5: LEDGER MANAGEMENT
=============================

5.1 CREATING A LEDGER ACCOUNT
    1. Navigate to the desired ledger type (Clients, Salary, etc.)
    2. Click the [+] button
    3. Enter account name and details
    4. Click Save

5.2 ADDING TRANSACTIONS
    1. Click on any ledger account to open it
    2. Click the [+] button to add entry
    3. Fill in: Date (BS), Particulars, Debit (Dr), Credit (Cr)
    4. Click Save

5.3 DELETING A LEDGER ACCOUNT
    - A ledger can only be deleted if it has NO entries
    - If entries exist: "Cannot delete - data exists" message shows
    - To delete: first delete all entries, then the ledger
    - Admin PIN is required to confirm deletion


CHAPTER 6: DAYBOOK (DAILY CASH TRACKING)
=========================================

6.1 HOW DAYBOOK WORKS
    - Shows all transactions for a selected date
    - Automatically calculates:
        * Opening Balance (from previous day's closing)
        * Cash IN (collections received)
        * Cash OUT (payments/expenses made)
        * Closing Balance (what's left in hand)

6.2 CASH FLOW LOGIC
    - Client ledger CREDIT = Cash IN (customer paid you)
    - Salary ledger CREDIT = Not cash (salary accrued, not paid)
    - Any DEBIT on non-client account = Cash OUT (you paid)
    - Closing Balance carries forward to next day's Opening Balance

6.3 DATE NAVIGATION
    - Use the date picker to view any day's daybook
    - Date is in Bikram Sambat (BS) format


CHAPTER 7: REPORTS
====================

- Reports can be filtered by date range and ledger type
- Shows total Debit, Credit, Income, and Expenses
- Use for monthly/yearly financial review


CHAPTER 8: SETTINGS
=====================

8.1 DATA BACKUP
    1. Go to Settings from the sidebar
    2. Click "Backup Data"
    3. Choose a folder (USB drive, Desktop, etc.)
    4. File saved as: HisabKitab_Backup_[timestamp].db
    IMPORTANT: Take regular backups to prevent data loss!

8.2 DATA RESTORE
    1. Go to Settings > Click "Restore Data"
    2. Select your .db backup file
    3. Confirm the restore (WARNING: replaces current data)
    4. App restarts automatically with restored data

8.3 NEPALI DATE CORRECTION
    - If the date shows 1 day ahead or behind:
    - Go to Settings > Nepali Date Correction
    - Click "-1 Day" to go back one day
    - Click "+1 Day" to go forward one day
    - Click "Reset (0)" to restore default

8.4 CHANGE PIN
    - Go to Dashboard > Settings icon (top right) > Change PIN
    - Enter your current PIN and new PIN


CHAPTER 9: TIPS & BEST PRACTICES
==================================

- Take a database backup at least ONCE A WEEK
- Store backups on a USB drive or cloud folder (Google Drive)
- Use Salary ledger CREDIT for salary accrual (not cash out)
- Use Salary ledger DEBIT when actually paying salary (cash out)
- Fast Billing CREDIT = cash received from clients
- Keep your Admin PIN safe - if forgotten, contact developer


CONTACT & SUPPORT
=====================

Developer:  Tulaaram Kathariya
Website:    tularam.com.np
Phone:      +977 9848491651

For license key requests, technical support, or questions,
please contact via the above information during business hours.


Thank you for choosing Chhito Ledger!
======================================
