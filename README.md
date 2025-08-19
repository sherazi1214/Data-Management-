# Data-Management


**English:**
Data Management is the practice of collecting, storing, organizing, securing, and using data effectively throughout its lifecycle.

**Urdu:**
Data management ka matlab hai data ko sahi tarah se collect, store, organize, secure aur use karna taa k business aur security dono improve ho.

### Key Objectives:

Accuracy (sahi data ho)

Security (safe from hackers)

Accessibility (authorized logon ko easily access milay)

Compliance (laws follow ho, jaise GDPR, HIPAA)

### Data Roles and Responsibilities

**Data Owner**

**English:** Person/department responsible for data, decides classification and access level.

**Urdu:** Wo banda ya department jo data ka zimmedar hota hai, aur decide karta hai k kaun access karega.

**Data Custodian**

**English:** IT team that stores, backs up, and maintains data systems.

**Urdu:** IT team jo data ko store, backup aur maintain karti hai.

**Data Steward**

**English:** Ensures data quality, consistency, and compliance.

**Urdu:** Ye ensure karta hai k data sahi, consistent aur compliant ho.

**Data User**

**English:** Employees or users who access and use the data for their tasks.

**Urdu:** Normal users jo apna kaam karne k liye data use karte hain.

### Data Protection Controls

**English:** Security measures to safeguard data from loss, theft, or unauthorized use.
**Urdu:** Ye wo methods hain jo data ko hackers ya unauthorized logon se protect karte hain.

### Examples:

**Encryption** – Convert data into unreadable format.

**Access Controls** – Passwords, RBAC (Role-Based Access Control).

**Firewalls & IDS/IPS** – Protect network data.

**Backup & Recovery** – Data loss k waqt restore karna.

**Audit Logs** – Monitor k data kisne access kiya.

### Data Masking

**English:**
Data masking hides sensitive data by replacing it with fake but realistic values for testing or development.

**Urdu:**
Data masking ka matlab hai asli sensitive data ko fake values se replace kar dena taa k hackers ya unauthorized log use na kar saken, lekin developers test kar saken.

Example:

**Real:** Credit Card = 4111-5678-9012-3456

**Masked:** Credit Card = 4111-XXXX-XXXX-3456

### Data Tokenization

**English:**
Tokenization replaces sensitive data (like credit card number) with a random unique token. Original data is stored securely in a separate vault.

**Urdu:**
Tokenization me asli data ko ek random token se replace kar dete hain, aur original data secure vault me rakha jata hai. Sirf authorized system hi us token ko asli data se map kar sakta hai.

### Example:

**Real:** Credit Card = 4111-5678-9012-3456

**Token:** TKN-9876543210

👉 Used in PCI DSS (payment security).

### Data Obfuscation

**English:**
Data obfuscation is the process of making data hard to understand by scrambling or encoding it, usually for security or privacy.

**Urdu:**
Obfuscation ka matlab hai data ko itna confusing aur scrambled bana dena k koi unauthorized banda easily samajh na sake.

### Example:

**Real:** Password = Hello@123

**Obfuscated:** H&^%3lo#@!!12X

👉 Mostly used in source code security & software protection.
