# LSM_PrivacyPolicy
Privacy Policy
📅 Effective: November 9, 2026
🌐 Android App
✈️ craftxdesignlabs@gmail.com
Contents
Overview
Data We Collect
How We Use Your Data
Data Sharing
Data Storage & Security
Data Retention
Your Rights
Children's Privacy
Policy Changes
Contact Us
01
Overview
LSM — Liquor Stock Manager ("LSM", "we", "our", or "us") is an Android application developed by CraftX Design Labs. LSM is a business tool that helps liquor store owners and their staff manage inventory, record sales, track expenses, process invoices, and generate closing reports.

This Privacy Policy explains what data LSM collects, how it is used, and the rights available to you. By using LSM, you agree to the practices described here.

Who this applies to: Store owners who create an LSM account, and staff members who are invited to join a store. LSM is a B2B tool intended for use by adults operating a licensed liquor business.
02
Data We Collect
Account & Authentication
Email address and password (used for Supabase authentication)
Session tokens stored locally in encrypted storage on your device
Role assignment (owner or staff)
Store & Staff Data
Store name and location
Staff member names and phone numbers (used for WhatsApp invitation delivery)
Staff PIN codes (used for quick local authentication; stored encrypted)
Invitation tokens (temporary, expire after 48 hours)
Business Operations Data
Product catalog: names, categories, quantities, prices
Sales transactions: items sold, amounts, timestamps
Expense records: amounts, categories, dates
Invoice data: supplier names, line items, totals — including images you scan
Stock movements: additions, adjustments, transfers
Daily closing reports: sales totals, cash counts, notes
Device & Technical Data
Camera images captured for invoice scanning (processed locally using ML Kit OCR; images are not uploaded to our servers)
Local database stored on your device (SQLite via SQLDelight)
App crash and error information (through Supabase infrastructure logs)
Data We Do Not Collect
Location or GPS data
Contacts list
Advertising identifiers
Browsing history or cross-app data
Biometric data
03
How We Use Your Data
Purpose	Data Used
Authenticating you and maintaining your session	Email, password hash, session tokens
Delivering staff invitations via WhatsApp	Staff phone number, invitation link with token
Syncing store data across devices	Products, sales, expenses, invoices, closings
Scanning invoices with OCR	Camera image (processed on-device; not uploaded)
Generating reports and closing summaries	Sales, expenses, stock movement records
Securing staff access via PIN	Encrypted PIN stored locally on device
Diagnosing errors and improving the app	Anonymised error logs via Supabase
We do not use your data for advertising, profiling, or sale to third parties.

04
Data Sharing
We do not sell, rent, or trade your personal information. Data is shared only with the following infrastructure providers under strict data processing agreements:

Supabase (supabase.com)
Our cloud backend for authentication and database storage. Store business data (products, sales, expenses, invoices, staff records) is stored on Supabase-hosted PostgreSQL servers. Supabase is SOC 2 Type II certified. Data is hosted in the region selected at account creation.

WhatsApp (Meta)
When a store owner sends a staff invitation, LSM opens WhatsApp with a pre-composed message containing a one-time invitation link. This action is initiated explicitly by the store owner. LSM does not independently access your WhatsApp contacts or send messages without your action.

Google ML Kit
OCR (text recognition) for invoice scanning. ML Kit operates entirely on-device. No invoice images or extracted text are sent to Google or our servers.

Beyond these providers, your data is not shared with any other third party unless required by law or to protect the safety of users.

05
Data Storage & Security
On-Device Storage
LSM maintains a local SQLite database on your Android device using SQLDelight. This database contains a local copy of your store's data to support offline access. Session tokens and staff PIN codes are stored in Android's EncryptedSharedPreferences, which encrypts data at rest using AES-256-GCM.

Cloud Storage
Your store's data is synchronized to Supabase's cloud database over HTTPS (TLS 1.2+). Access to your store's data is enforced by Supabase Row Level Security (RLS) policies — each user can only read and write records belonging to their own store.

No Invoice Image Uploads
When you scan an invoice, the camera image is processed entirely on your device by ML Kit. The image and extracted text are not transmitted to LSM servers. Only the structured invoice data you save (product names, quantities, amounts) is stored in Supabase.

06
Data Retention
Business records (sales, expenses, stock movements, invoices, closings) are retained for as long as your account is active, as these are operational records you rely on for your store.

Expired invitation tokens are automatically deleted from our database after 48 hours.

When you delete your account, all personal data and store records associated with your account are permanently deleted from our systems within 30 days. Local data on your device is removed when you uninstall the app.

If you remove a staff member from your store, their access is revoked immediately and their association with your store is removed.

07
Your Rights
Depending on your jurisdiction, you may have the following rights regarding your personal data:

Access: Request a copy of the personal data we hold about you.
Correction: Request correction of inaccurate data.
Deletion: Request deletion of your account and associated data.
Portability: Request an export of your business data in a readable format.
Withdrawal of consent: Stop using the app and request account deletion at any time.
To exercise any of these rights, contact us at the email address in Section 10. We will respond within 30 days.

Note for store owners: As the account holder, you are the data controller for your store's business records and your staff members' information. You are responsible for ensuring your staff are aware that their name and phone number are stored in LSM to manage store access.
08
Children's Privacy
LSM is a business application intended exclusively for adults (18 years and older) who are licensed to operate a liquor business. We do not knowingly collect personal information from anyone under the age of 18. If you believe a minor has created an account, please contact us immediately at the address below and we will delete the account.

09
Policy Changes
We may update this Privacy Policy as LSM evolves. When we make material changes, we will update the "Effective" date at the top of this document. For significant changes, we will provide in-app notification. Continued use of LSM after the updated policy is posted constitutes your acceptance of the changes.

We will never reduce your rights under this policy without explicit notice and your opportunity to delete your account before the change takes effect.

10
Contact Us
For privacy questions, data requests, or to report a concern, contact us at:

CraftX Design Labs

Developer of LSM — Liquor Stock Manager

Email: craftxdesignlabs@gmail.com

We aim to respond to all privacy-related enquiries within 30 days.

LSM — Liquor Stock Manager  ·  CraftX Design Labs  ·  Effective November 9, 2026

This policy applies to the Android application com.CraftX.LiquorStockManager.
