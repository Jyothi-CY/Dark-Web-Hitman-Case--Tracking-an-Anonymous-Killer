# **DF Project - Dark Web Hitman – Tracking an Anonymous Killer**

## **Team Members:**
- **N. Jyothirmayee Siva Gayatri** (2022BCY0024)
- **P. Sasya** (2022BCY0022)

## **Problem Statement:**
A law enforcement agency intercepted a murder-for-hire plot on the dark web. A suspect was arrested but claims to have been framed. The forensic team must investigate the suspect’s desktop and mobile devices to find evidence of dark web access, cryptocurrency payments, or emails linked to the hitman contract.

The primary objectives of the investigation are to:
1. Determine whether the suspect accessed contract-killing forums or encrypted messaging apps.
2. Identify communication between the suspect and the alleged hitman.
3. Trace cryptocurrency transactions linked to the contract.
4. Uncover attempts to conceal or destroy digital evidence.
5. Establish a timeline of events and gather digital evidence for prosecution.

## **Summary of Investigation:**

The investigation involved a detailed forensic analysis of the suspect’s (Henry) desktop system. Key findings include:

1. **Dark Web Access:**  
   - The suspect installed and used the Tor Browser to access multiple .onion sites, including contract-killing forums.
   - Bookmarked several dark web URLs related to hitman services.

2. **Suspicious Searches:**  
   - Searches included: "how can i murder someone and avoid getting caught?", "how much does it cost to hire a contract killer through dark web", "what is dark web", and "can you pay for assassination using bitcoin".

3. **Communication with the Hitman:**  
   - Email correspondence with `Robert_Stephen12@proton.me` using coded language (e.g., "special projects", "cleaning job", "stain", "art piece").
   - Attachments exchanged: victim’s photo (`Cathy.jpg`), hitman contract (`hitman_contract.docx`), and Bitcoin payment receipts.

4. **Cryptocurrency Transactions:**  
   - Bitcoin wallet addresses linked to the suspect and the hitman.
   - Two payments of $40,000 USD each (advance and final) were made via Bitcoin.

5. **Attempts to Conceal Evidence:**  
   - Installation and use of **Proton VPN** to mask IP addresses.
   - Use of **VeraCrypt** to encrypt files and a USB drive.
   - Download and execution of **CCleaner** to wipe traces.
   - Secure deletion of files (`hitman_contract.pdf`).

6. **Geolocation Data:**  
   - Google Maps searches for the victim’s address (`354 West 48th Street, New York, NY`) and routes from the suspect’s location (`Parkside Ave, Brooklyn, NY`).

7. **Post-Crime Behavior:**  
   - Searches for "any woman murdered near brooklyn ny" and "hitman cases".
   - Planned trip to Montauk, NY, possibly to evade law enforcement.
   - Email to a friend about "taking a break" after the crime.

8. **Key Evidence Files:**  
   - `hitman_contract.docx` (contract details, Bitcoin wallet info).
   - `Hitman conversation.m4a` (audio recording of conversation with hitman).
   - `BTC advance.png` and `BTC final.png` (Bitcoin payment receipts).
   - `payment_details.txt` (hitman’s Bitcoin wallet address).
   - `address.txt` (saved victim’s address).

## **Forensic Process & Methodology:**

### **1. Evidence Acquisition:**
- Acquired a disk image (`hitman_case.dd`) of the suspect’s desktop.
- Verified integrity using hashing (MD5, SHA1).

### **2. Evidence Analysis:**
- Used **AXIOM Process v9.0.0.43519** for forensic examination.
- Extracted and analyzed:
  - **Web Browser Artifacts** (Chrome, Edge, Firefox/Tor):
    - Search history, downloads, bookmarks, cookies, favicons.
  - **Email Analysis** (Outlook `.ost` file):
    - Headers, attachments, timestamps, IP addresses.
  - **File System Analysis**:
    - Accessed files, hidden folders (`C:\Secret`), deleted files (Recycle Bin).
  - **Registry & Prefetch Analysis**:
    - Application execution counts (VPN, VeraCrypt, CCleaner).
  - **Network Artifacts**:
    - VPN connections, network profiles.
  - **Multimedia Analysis**:
    - Images, audio recordings (`Hitman conversation.m4a`).

### **3. Timeline Reconstruction:**
- Created a detailed timeline of events from **March 24, 2025**, to **April 4, 2025**.
- Correlated searches, email communications, file accesses, and application usage.

### **4. Data Correlation:**
- Linked Bitcoin transactions to email attachments.
- Mapped Tor browsing to dark web bookmarks.
- Connected VPN usage timestamps to email sending times.

### **5. Reporting:**
- Compiled findings into a forensic report with supporting artifacts.
- Answered 20+ investigative questions based on extracted evidence.

## **Tools & Technologies Used:**

### **Forensic Tools:**
- **AXIOM Process v9.0.0.43519** – Primary forensic analysis platform.
- **Disk Imaging Tool** – For creating `hitman_case.dd`.
- **Hash Calculators** – For integrity verification.

### **Artifacts Analyzed:**
- **Browser Data**:
  - Chrome: History, Downloads, Bookmarks, Favicons, Sessions.
  - Edge: History, Downloads, Cookies, Keyword Searches.
  - Firefox/Tor: Bookmarks, Web History (`.sqlite`).
- **Email Client**: Outlook `.ost` file.
- **File System**: NTFS partition analysis, Recycle Bin, hidden folders.
- **Registry & Logs**: Prefetch, UserAssist, Event Logs.
- **Network Artifacts**: VPN logs, network connections.

### **Techniques Applied:**
- **Keyword Searching**: For hitman-related terms, Bitcoin, VPN, encryption.
- **Metadata Extraction**: From documents, images, emails.
- **Geolocation Mapping**: Using Google Maps queries.
- **Timeline Analysis**: Cross-referencing multiple artifact timestamps.
- **Data Carving**: Recovering deleted images from unallocated space.

## **Tech Stack:**

AXIOM Process, Tor Browser Forensics, Bitcoin/Cryptocurrency Analysis, ProtonMail Forensics, VeraCrypt Analysis, Windows Artifact Analysis, Timeline Reconstruction, Metadata Extraction

## **Key Evidence Identified:**

### **1. Digital Footprint:**
- Tor Browser installation and usage.
- Proton VPN installation (18 launches).
- VeraCrypt and CCleaner downloads and execution.

### **2. Communication Evidence:**
- Email thread with `Robert_Stephen12@proton.me`.
- Audio file: `Hitman conversation.m4a`.
- Instagram searches for `catherine_20_25`.

### **3. Financial Evidence:**
- Bitcoin wallet addresses:
  - Suspect: `bc1qw23n48y7890abcde54321xyz67890`
  - Hitman: `bc1q9xyz123abc45def67890hijklm56789`
- Payment receipts: `BTC advance.png`, `BTC final.png`.

### **4. Incriminating Files:**
- `hitman_contract.docx` (last modified: 01-04-2025 06:55:34).
- `Cathy.jpg` (victim’s photo).
- `address.txt` (victim’s address).
- `payment_details.txt` (hitman’s Bitcoin address).

### **5. Behavioral Evidence:**
- Searches for how to commit murder and avoid detection.
- Attempts to erase digital traces using CCleaner.
- Post-crime searches for news about the murder.

## **Conclusion:**

The forensic investigation provides substantial digital evidence linking the suspect, Henry, to a murder-for-hire plot. Evidence includes dark web access, encrypted communication with a hitman, Bitcoin payments for the contract, and attempts to conceal digital traces. The suspect’s claims of being framed are contradicted by the comprehensive digital trail.

---
### **1. Digital Forensics & Incident Response (DFIR)**
*   **Why it fits:** The core of your project involved systematic evidence acquisition, analysis, and timeline reconstruction from a disk image to investigate a criminal incident.
*   **Detail to add:** "Conducted end-to-end DFIR, including evidence acquisition (disk imaging), artifact analysis (browser history, registry, filesystem), and timeline reconstruction to support a criminal investigation."

### **2. Dark Web & Anonymity Network Investigation**
*   **Why it fits:** You specifically investigated activity on the Tor network, identified .onion services, and understood how suspects use anonymity tools.
*   **Detail to add:** "Experienced in investigating dark web activity, including Tor browser forensics, analysis of .onion service access, and tracing attempts at anonymity using VPNs and encrypted communications."

### **3. Cryptocurrency Transaction Analysis**
*   **Why it fits:** You traced Bitcoin payments, identified wallet addresses, and linked financial transactions to criminal intent, which is a critical sub-skill in modern cybercrime investigations.
*   **Detail to add:** "Performed cryptocurrency transaction analysis, tracing Bitcoin payments across wallets to establish financial links in criminal conspiracy cases."

### **4. Forensic Analysis of Encrypted & Obfuscated Data**
*   **Why it fits:** You dealt with encrypted communications (ProtonMail), encrypted storage (VeraCrypt), and obfuscation techniques (coded language, secure deletion tools).
*   **Detail to add:** "Analyzed encrypted communications and storage artifacts, identifying cryptographic containers and recovering evidence from obfuscated user activities."

### **5. Multi-Source Evidence Correlation & Timeline Analysis**
*   **Why it fits:** You didn't rely on one data source; you correlated browser history, email metadata, file system timestamps, application logs, and network artifacts to build a cohesive narrative.
*   **Detail to add:** "Expert in correlating evidence from multiple digital sources (browsers, email, filesystem, memory) to construct comprehensive attack timelines and behavioral profiles."

### **Recommendations:**
1. **Legal Action**: Use extracted evidence for prosecution.
2. **Further Investigation**: Trace Bitcoin transactions on the blockchain.
3. **Collaboration**: Work with ProtonMail and VPN providers for additional logs.
4. **Suspect Monitoring**: Monitor for further evasion attempts.


## **References:**
- Case Number: `case01`
- Evidence File: `hitman_case.dd`
- Report Generated: Tuesday, April 8, 2025
- Forensic Software: AXIOM Process v9.0.0.43519

## **Appendices:**
- Full timeline of events.
- List of all Tor bookmarks and visited URLs.
- Email headers and attachments.
- Screenshots of key evidence.

