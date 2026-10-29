# Data Privacy Basics: A Beginner's Manual

*Published by Asdale Dynamics, LLC — October 2026*

---

## Welcome

This manual walks you through practical steps to protect your personal data online. No jargon, no scare tactics — just clear actions you can take today.

**Who this is for:** Anyone who uses the internet and wants more control over their data. No technical background needed.

**Time to complete:** Read the whole thing in 30 minutes. Implement at your own pace.

---

## Table of Contents

1. [Passwords & Password Managers](#1-passwords--password-managers)
2. [Two-Factor Authentication (2FA)](#2-two-factor-authentication-2fa)
3. [Browser Privacy](#3-browser-privacy)
4. [App Permissions](#4-app-permissions)
5. [Data Deletion Requests](#5-data-deletion-requests)
6. [What Never to Share with AI](#6-what-never-to-share-with-ai)
7. [Printable Checklist](#7-printable-checklist)

---

## 1. Passwords & Password Managers

### The problem
Most people reuse passwords. If one site gets breached, attackers try that password everywhere else.

### The solution: Use a password manager
A password manager creates and stores unique, strong passwords for every site. You only remember one master password.

### Recommended password managers (free tiers available)
- **Bitwarden** — open source, cross-platform, highly recommended
- **1Password** — polished, family sharing, paid only
- **KeePassXC** — offline, local file, advanced users
- **Apple iCloud Keychain / Google Password Manager** — built in, convenient

### Step-by-step: Set up Bitwarden (free, recommended)

1. **Go to** [bitwarden.com](https://bitwarden.com) or search "Bitwarden" in your app store
2. **Create account** — use a strong master password (see below)
3. **Install browser extension** — Chrome, Firefox, Safari, Edge all supported
4. **Install mobile app** — iOS App Store or Google Play
5. **Import existing passwords** — most browsers let you export a CSV file
6. **Start using it** — when you log in somewhere, Bitwarden offers to save it. When you create a new account, Bitwarden generates a password.

### Creating a strong master password
Your master password unlocks everything. Make it memorable but unguessable.

**Method: Passphrase (recommended)**
Pick 4–6 random words. Add a number and symbol.
```
correct-horse-battery-staple-42!
```
**Why this works:** Length beats complexity. A 4-word passphrase takes centuries to crack.

**Never use:**
- Personal info (birthdays, names, pet names)
- Common patterns (Password123, qwerty, abc123)
- The same password you use anywhere else

### Quick password rules
| Do | Don't |
|---|---|
| Use unique password per site | Reuse passwords |
| Let password manager generate 20+ char passwords | Make up your own "clever" passwords |
| Enable 2FA on your password manager | Share master password with anyone |
| Back up your recovery kit (Bitwarden gives you one) | Lose your recovery kit |

---

## 2. Two-Factor Authentication (2FA)

### What is 2FA?
A second check after your password. Even if someone steals your password, they can't log in without the second factor.

### Types of 2FA (best to worst)

| Type | Example | Security | Convenience |
|---|---|---|---|
| **Hardware key** | YubiKey, Titan Key | ⭐⭐⭐⭐⭐ | Medium |
| **Authenticator app** | Bitwarden, Authy, Google Authenticator, Microsoft Authenticator | ⭐⭐⭐⭐ | High |
| **SMS / text message** | Code sent to phone | ⭐⭐ | High |
| **Email code** | Code sent to email | ⭐⭐ | High |

**Avoid SMS if possible** — SIM swap attacks can intercept texts.

### Step-by-step: Set up authenticator app 2FA

1. **Install an authenticator app** — Bitwarden has this built in (premium), or use Authy (free, syncs across devices), Google Authenticator, or Microsoft Authenticator
2. **Go to account security settings** on each site (Google, Facebook, bank, email, GitHub, etc.)
3. **Find "Two-Factor Authentication" or "2FA"** — usually under Security or Login settings
4. **Choose "Authenticator App"** — not SMS
5. **Scan the QR code** with your authenticator app
6. **Enter the 6-digit code** from the app to confirm
7. **Save backup codes** — print or save to password manager. These let you in if you lose your phone.

### Priority order: Enable 2FA here first
1. **Email** (Gmail, Outlook, Proton, etc.) — gateway to everything else
2. **Password manager** — Bitwarden, 1Password, etc.
3. **Banking & financial** — banks, PayPal, Venmo, investment accounts
4. **Social media** — Facebook, Instagram, Twitter/X, LinkedIn
5. **Shopping** — Amazon, eBay, anywhere with saved payment info
6. **Cloud storage** — Google Drive, Dropbox, iCloud, OneDrive
7. **Work accounts** — GitHub, Slack, Microsoft 365, etc.

---

## 3. Browser Privacy

### Why browsers leak data
Browsers send your IP address, location, browsing history, and device info to websites by default. Trackers follow you across sites.

### Quick wins (do these today)

#### Switch to a privacy-focused browser
| Browser | Best for | Notes |
|---|---|---|
| **Firefox** | Most people | Open source, strong privacy defaults, great extensions |
| **Brave** | Set-and-forget | Blocks ads/trackers by default, Chromium-based |
| **Safari** | Mac/iPhone users | Good privacy, built-in |
| **Tor Browser** | Maximum anonymity | Slow, for sensitive browsing only |

#### Essential browser settings (Firefox example — similar in others)

1. **Block third-party cookies**
   - Settings → Privacy & Security → Cookies → "Block third-party cookies"
   
2. **Enable "Do Not Track"**
   - Settings → Privacy & Security → Send "Do Not Track" signal → Always

3. **Use DNS over HTTPS (DoH)**
   - Settings → General → Network Settings → Settings → Enable DNS over HTTPS → Cloudflare or NextDNS

4. **Clear cookies on close (optional but strong)**
   - Settings → Privacy & Security → Cookies → "Delete cookies and site data when Firefox closes"

#### Install these extensions (Firefox/Chrome/Brave/Edge)

| Extension | What it does |
|---|---|
| **uBlock Origin** | Blocks ads, trackers, malware — the single best extension |
| **Privacy Badger** | Learns and blocks invisible trackers automatically |
| **HTTPS Everywhere** | Forces encrypted connections (built into modern browsers now) |
| **Cookie AutoDelete** | Removes cookies when you close a tab |
| **Decentraleyes** | Blocks requests to CDN trackers |

#### Search privately
- **DuckDuckGo** — no tracking, good results
- **Startpage** — Google results without tracking
- **Brave Search** — independent index, no tracking

---

## 4. App Permissions

### The problem
Apps ask for more permissions than they need. A flashlight app doesn't need your contacts or location.

### Rule of thumb: Minimum necessary
Only grant permissions the app genuinely needs to function.

### Phone: Audit your permissions (iOS & Android)

#### iOS (iPhone/iPad)
1. **Settings → Privacy & Security**
2. **Tap each category** (Location, Contacts, Photos, Microphone, Camera, etc.)
3. **Review each app** — change to "Never" or "Ask Next Time" if not needed
4. **Location Services** → Set apps to "While Using" instead of "Always" when possible

#### Android
1. **Settings → Privacy → Permission Manager** (or Settings → Apps → Permissions)
2. **Tap each permission** → review apps
3. **Change to "Don't allow" or "Allow only while using"** as appropriate

### Common permissions to question
| Permission | Legitimate uses | Often abused by |
|---|---|---|
| **Location** | Maps, ride-share, weather | Games, social media, shopping apps |
| **Contacts** | Messaging, email | Games, random utilities |
| **Microphone** | Voice calls, voice memos | Apps that don't record audio |
| **Camera** | Video calls, scanning | Apps with no camera feature |
| **Photos/Files** | Photo editors, cloud backup | Apps that don't manage media |
| **Tracking (iOS)** | Almost never needed | Ad networks, analytics |

### Desktop: Browser permissions
- **Settings → Site Settings** (Chrome/Edge/Brave) or **Settings → Privacy & Security → Permissions** (Firefox)
- Review: Location, Camera, Microphone, Notifications
- Block by default, allow per-site when needed

### Delete unused apps
Apps you don't use still collect data. Delete them.

---

## 5. Data Deletion Requests

### Your rights
- **GDPR (EU/UK)** — "Right to erasure" / "Right to be forgotten"
- **CCPA/CPRA (California)** — Right to delete
- **Other states** — Virginia, Colorado, Connecticut, Utah, and more have similar laws
- **Many companies honor globally** — even if not legally required

### Step-by-step: Request data deletion

#### 1. Find the right contact
- Check the site's **Privacy Policy** — look for "Your Rights," "Data Subject Requests," or "Contact Us"
- Search: "[Company name] data deletion request" or "[Company name] privacy contact"
- Common emails: `privacy@`, `dpo@`, `gdpr@`, `ccpa@`, `legal@`

#### 2. Use a template
```
Subject: Data Deletion Request — [Your Name]

To the Data Protection Officer / Privacy Team,

I hereby request deletion of all personal data you hold about me under [GDPR Article 17 / CCPA Section 1798.105 / applicable law].

Account details:
- Name: [Your full name]
- Email: [Email used for account]
- Username: [If applicable]
- Account ID: [If known]

Please confirm:
1. Receipt of this request
2. Deletion completion timeline
3. What data has been deleted
4. Whether any data is retained and the legal basis

I expect a response within [30 days GDPR / 45 days CCPA] as required by law.

Thank you,
[Your Name]
```

#### 3. Send and track
- Send from the email on the account
- Save sent email and any replies
- Follow up if no response in 2–3 weeks

#### 4. Use automated tools (optional)
- **DeleteMe** / **OneRep** / **Incogni** — paid services that automate requests to data brokers
- **Privacy.com** — virtual cards, not deletion but reduces data spread
- **SimpleLogin** / **AnonAddy** — email aliases to limit exposure

### Data brokers to target first
These companies sell your data. Opt out at each:
- Whitepages, Spokeo, BeenVerified, PeopleFinders, Intelius, MyLife, Radaris, TruePeopleSearch, FastPeopleSearch, FamilyTreeNow

---

## 6. What Never to Share with AI

### The rule: Assume anything you type into an AI chat can be seen by the company that runs it, used for training, or leaked in a breach.

### Never share with AI (any AI: ChatGPT, Claude, Gemini, local models you don't control, etc.)

| Category | Examples |
|---|---|
| **Credentials** | Passwords, API keys, tokens, SSH keys, database URLs, encryption keys |
| **Personal ID** | SSN, passport number, driver's license, medical record numbers |
| **Financial** | Credit card numbers, bank account numbers, routing numbers, crypto seed phrases |
| **Health** | Diagnoses, medications, insurance IDs, therapy notes, genetic data |
| **Legal** | Contracts under NDA, privileged communications, case details |
| **Work secrets** | Unreleased product info, source code (if proprietary), internal docs, customer data |
| **Other people's private info** | Anyone's PII without their consent |
| **Anything you'd regret public** | If you wouldn't post it on a billboard, don't put it in AI |

### What's generally okay to share
- General questions ("How do I reset a password?")
- Public information (Wikipedia facts, public docs)
- Anonymized examples ("I have a CSV with columns A, B, C — how do I parse it?")
- Code you wrote for learning/open source (no secrets)
- Creative writing, brainstorming, learning

### Safer AI practices
- **Use local models** (Ollama, LM Studio, GPT4All) for sensitive work — data stays on your machine
- **Disable chat history / training** — ChatGPT: Settings → Data Controls → "Improve the model for everyone" OFF. Claude: automatically doesn't train on your chats. Gemini: Activity → Turn off.
- **Use "incognito" / temporary chats** when available
- **Redact before pasting** — replace real values with `REDACTED` or `example.com`

---

## 7. Printable Checklist

See `checklist.md` for a one-page printable version.

---

## Next Steps

1. **This week:** Set up password manager + enable 2FA on email and password manager
2. **This month:** Audit browser, phone permissions, request deletion from 3 data brokers
3. **Ongoing:** Use email aliases for new signups, review permissions quarterly

---

## Resources

- **Bitwarden:** https://bitwarden.com
- **Authy:** https://authy.com
- **uBlock Origin:** https://ublockorigin.com
- **DuckDuckGo:** https://duckduckgo.com
- **GDPR.eu:** https://gdpr.eu
- **CCPA Guide:** https://oag.ca.gov/privacy/ccpa
- **Privacy Guides:** https://privacyguides.org
- **Asdale Dynamics:** https://dylanasdale.github.io

---

*This manual is educational only. Not legal, medical, or security advice. For high-stakes accounts, consult a professional.*

*Copyright (c) 2026 Asdale Dynamics, LLC. Licensed under MIT — see LICENSE.*